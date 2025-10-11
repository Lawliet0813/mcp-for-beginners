<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "94c80ae71fb9971e9b57b51ab0912121",
  "translation_date": "2025-10-11T11:30:02+00:00",
  "source_file": "03-GettingStarted/02-client/README.md",
  "language_code": "ta"
}
-->
# கிளையன்ட் உருவாக்குதல்

கிளையன்ட்கள் என்பது MCP சர்வருடன் நேரடியாக தொடர்பு கொண்டு வளங்கள், கருவிகள் மற்றும் ப்ராம்ப்ட்களை கோருவதற்கான தனிப்பயன் பயன்பாடுகள் அல்லது ஸ்கிரிப்ட்கள் ஆகும். சர்வரைத் தொடர்பு கொள்ள கிராபிகல் இன்டர்ஃபேஸை வழங்கும் இன்ஸ்பெக்டர் டூலைப் பயன்படுத்துவதற்கு மாறாக, உங்கள் சொந்த கிளையன்டை எழுதுவது நிரலாக்க மற்றும் தானியக்க தொடர்புகளைச் செய்ய அனுமதிக்கிறது. இது டெவலப்பர்களுக்கு MCP திறன்களை தங்கள் வேலைப்பாடுகளில் ஒருங்கிணைக்க, பணிகளை தானியக்கமாக்க, மற்றும் குறிப்பிட்ட தேவைகளுக்கு ஏற்ப தனிப்பயன் தீர்வுகளை உருவாக்க உதவுகிறது.

## மேலோட்டம்

இந்த பாடம் மாடல் கான்டெக்ஸ்ட் புரோட்டோகோல் (MCP) சூழலில் கிளையன்ட்களின் கருத்தை அறிமுகப்படுத்துகிறது. MCP சர்வருடன் இணைக்க உங்கள் சொந்த கிளையன்டை எழுதுவது எப்படி என்பதை நீங்கள் கற்றுக்கொள்வீர்கள்.

## கற்றல் நோக்கங்கள்

இந்த பாடத்தின் முடிவில், நீங்கள்:

- கிளையன்ட் என்ன செய்ய முடியும் என்பதைப் புரிந்துகொள்வீர்கள்.
- உங்கள் சொந்த கிளையன்டை எழுதுவீர்கள்.
- MCP சர்வருடன் இணைத்து, சர்வர் எதிர்பார்த்தபடி செயல்படுகிறதா என்பதை சோதிக்கவும்.

## கிளையன்டை எழுதுவதில் என்ன செய்ய வேண்டும்?

கிளையன்டை எழுத, நீங்கள் பின்வருவன செய்ய வேண்டும்:

- **சரியான நூலகங்களை இறக்குமதி செய்யுங்கள்**. நீங்கள் முன்பு பயன்படுத்திய அதே நூலகத்தை பயன்படுத்துவீர்கள், ஆனால் வேறுபட்ட கட்டமைப்புகளைப் பயன்படுத்துவீர்கள்.
- **கிளையன்டை உருவாக்குங்கள்**. இது ஒரு கிளையன்ட் இன்ஸ்டன்ஸை உருவாக்கி, தேர்ந்தெடுக்கப்பட்ட போக்குவரத்து முறைக்கு இணைக்க வேண்டும்.
- **வளங்களை பட்டியலிடுவது பற்றி முடிவு செய்யுங்கள்**. உங்கள் MCP சர்வர் வளங்கள், கருவிகள் மற்றும் ப்ராம்ப்ட்களுடன் வருகிறது, நீங்கள் எந்த ஒன்றை பட்டியலிட வேண்டும் என்பதை முடிவு செய்ய வேண்டும்.
- **கிளையன்டை ஹோஸ்ட் பயன்பாட்டுடன் ஒருங்கிணைக்கவும்**. சர்வரின் திறன்களை நீங்கள் அறிந்த பிறகு, உங்கள் ஹோஸ்ட் பயன்பாட்டுடன் இதை ஒருங்கிணைக்க வேண்டும், இதனால் ஒரு பயனர் ப்ராம்ப்ட் அல்லது பிற கட்டளையைத் தட்டச்சு செய்தால், தொடர்புடைய சர்வர் அம்சம் செயல்படுத்தப்படும்.

இப்போது, நாம் செய்யப்போகிறதை உயர் மட்டத்தில் புரிந்துகொண்டோம், அடுத்ததாக ஒரு எடுத்துக்காட்டு பார்க்கலாம்.

### ஒரு எடுத்துக்காட்டு கிளையன்ட்

இந்த எடுத்துக்காட்டு கிளையன்டை பார்ப்போம்:

### TypeScript

```typescript
import { Client } from "@modelcontextprotocol/sdk/client/index.js";
import { StdioClientTransport } from "@modelcontextprotocol/sdk/client/stdio.js";

const transport = new StdioClientTransport({
  command: "node",
  args: ["server.js"]
});

const client = new Client(
  {
    name: "example-client",
    version: "1.0.0"
  }
);

await client.connect(transport);

// List prompts
const prompts = await client.listPrompts();

// Get a prompt
const prompt = await client.getPrompt({
  name: "example-prompt",
  arguments: {
    arg1: "value"
  }
});

// List resources
const resources = await client.listResources();

// Read a resource
const resource = await client.readResource({
  uri: "file:///example.txt"
});

// Call a tool
const result = await client.callTool({
  name: "example-tool",
  arguments: {
    arg1: "value"
  }
});
```

மேலே உள்ள குறியீட்டில், நாம்:

- நூலகங்களை இறக்குமதி செய்கிறோம்.
- stdio போக்குவரத்தைப் பயன்படுத்தி கிளையன்ட் இன்ஸ்டன்ஸை உருவாக்கி இணைக்கிறோம்.
- ப்ராம்ப்ட்கள், வளங்கள் மற்றும் கருவிகளை பட்டியலிட்டு அவற்றை அனைத்தையும் செயல்படுத்துகிறோம்.

இங்கே, MCP சர்வருடன் பேசக்கூடிய ஒரு கிளையன்ட் உள்ளது.

அடுத்த பயிற்சி பிரிவில், ஒவ்வொரு குறியீட்டு துண்டையும் பிரித்து, என்ன நடக்கிறது என்பதை விளக்க நேரம் எடுத்துக்கொள்வோம்.

## பயிற்சி: கிளையன்டை எழுதுதல்

மேலே கூறியபடி, குறியீட்டை விளக்க நேரம் எடுத்துக்கொள்வோம், மேலும் நீங்கள் விரும்பினால் குறியீட்டை எழுதுங்கள்.

### -1- நூலகங்களை இறக்குமதி செய்யுங்கள்

நாம் தேவையான நூலகங்களை இறக்குமதி செய்வோம், கிளையன்டிற்கும் தேர்ந்தெடுக்கப்பட்ட போக்குவரத்து நெறிமுறைக்கும் குறிப்புகள் தேவைப்படும். stdio என்பது உங்கள் உள்ளூர் கணினியில் இயங்குவதற்கான நெறிமுறை. SSE என்பது மற்றொரு போக்குவரத்து நெறிமுறை, அதை எதிர்கால அத்தியாயங்களில் காண்போம், ஆனால் அது உங்கள் மற்றொரு விருப்பம். தற்போது, stdio-வுடன் தொடருவோம்.

#### TypeScript

```typescript
import { Client } from "@modelcontextprotocol/sdk/client/index.js";
import { StdioClientTransport } from "@modelcontextprotocol/sdk/client/stdio.js";
```

#### Python

```python
from mcp import ClientSession, StdioServerParameters, types
from mcp.client.stdio import stdio_client
```

#### .NET

```csharp
using Microsoft.Extensions.AI;
using Microsoft.Extensions.Configuration;
using Microsoft.Extensions.Hosting;
using ModelContextProtocol.Client;
using ModelContextProtocol.Protocol.Transport;
```

#### Java

Java-க்கு, நீங்கள் முந்தைய பயிற்சியில் இருந்து MCP சர்வருடன் இணைக்கும் ஒரு கிளையன்டை உருவாக்குவீர்கள். [Getting Started with MCP Server](../../../../03-GettingStarted/01-first-server/solution/java) என்ற Java Spring Boot திட்ட அமைப்பைப் பயன்படுத்தி, `src/main/java/com/microsoft/mcp/sample/client/` கோப்புறையில் `SDKClient` என்ற புதிய Java வகுப்பை உருவாக்கி, பின்வரும் இறக்குமதிகளைச் சேர்க்கவும்:

```java
import java.util.Map;
import org.springframework.web.reactive.function.client.WebClient;
import io.modelcontextprotocol.client.McpClient;
import io.modelcontextprotocol.client.transport.WebFluxSseClientTransport;
import io.modelcontextprotocol.spec.McpClientTransport;
import io.modelcontextprotocol.spec.McpSchema.CallToolRequest;
import io.modelcontextprotocol.spec.McpSchema.CallToolResult;
import io.modelcontextprotocol.spec.McpSchema.ListToolsResult;
```

#### Rust

உங்கள் `Cargo.toml` கோப்பில் பின்வரும் சார்புகளைச் சேர்க்க வேண்டும்.

```toml
[package]
name = "calculator-client"
version = "0.1.0"
edition = "2024"

[dependencies]
rmcp = { version = "0.5.0", features = ["client", "transport-child-process"] }
serde_json = "1.0.141"
tokio = { version = "1.46.1", features = ["rt-multi-thread"] }
```

அதன் பிறகு, உங்கள் கிளையன்ட் குறியீட்டில் தேவையான நூலகங்களை இறக்குமதி செய்யலாம்.

```rust
use rmcp::{
    RmcpError,
    model::CallToolRequestParam,
    service::ServiceExt,
    transport::{ConfigureCommandExt, TokioChildProcess},
};
use tokio::process::Command;
```

இப்போது, இன்ஸ்டன்சேஷனுக்கு நகர்வோம்.

### -2- கிளையன்ட் மற்றும் போக்குவரத்தை உருவாக்குதல்

நாம் போக்குவரத்து மற்றும் கிளையன்டின் ஒரு இன்ஸ்டன்ஸை உருவாக்க வேண்டும்:

#### TypeScript

```typescript
const transport = new StdioClientTransport({
  command: "node",
  args: ["server.js"]
});

const client = new Client(
  {
    name: "example-client",
    version: "1.0.0"
  }
);

await client.connect(transport);
```

மேலே உள்ள குறியீட்டில், நாம்:

- stdio போக்குவரத்து இன்ஸ்டன்ஸை உருவாக்குகிறோம். சர்வரை கண்டுபிடித்து தொடங்குவதற்கான கட்டளைகள் மற்றும் arguments-ஐ குறிப்பிடுவது எப்படி என்பதை கவனிக்கவும், இது கிளையன்டை உருவாக்கும் போது செய்ய வேண்டிய ஒன்று.

    ```typescript
    const transport = new StdioClientTransport({
        command: "node",
        args: ["server.js"]
    });
    ```

- கிளையன்டை ஒரு பெயர் மற்றும் பதிப்புடன் உருவாக்குகிறோம்.

    ```typescript
    const client = new Client(
    {
        name: "example-client",
        version: "1.0.0"
    });
    ```

- கிளையன்டை தேர்ந்தெடுக்கப்பட்ட போக்குவரத்துடன் இணைக்கிறோம்.

    ```typescript
    await client.connect(transport);
    ```

#### Python

```python
from mcp import ClientSession, StdioServerParameters, types
from mcp.client.stdio import stdio_client

# Create server parameters for stdio connection
server_params = StdioServerParameters(
    command="mcp",  # Executable
    args=["run", "server.py"],  # Optional command line arguments
    env=None,  # Optional environment variables
)

async def run():
    async with stdio_client(server_params) as (read, write):
        async with ClientSession(
            read, write
        ) as session:
            # Initialize the connection
            await session.initialize()

          

if __name__ == "__main__":
    import asyncio

    asyncio.run(run())
```

மேலே உள்ள குறியீட்டில், நாம்:

- தேவையான நூலகங்களை இறக்குமதி செய்கிறோம்.
- சர்வர் அளவுரு பொருளை உருவாக்குகிறோம், இதை கிளையன்டுடன் இணைக்க சர்வரை இயக்க பயன்படுத்துவோம்.
- `run` என்ற முறைவை வரையறுக்கிறோம், இது `stdio_client`-ஐ அழைக்கிறது, இது ஒரு கிளையன்ட் அமர்வை தொடங்குகிறது.
- `asyncio.run`-க்கு `run` முறைவை வழங்கும் ஒரு நுழைவு புள்ளியை உருவாக்குகிறோம்.

#### .NET

```dotnet
using Microsoft.Extensions.AI;
using Microsoft.Extensions.Configuration;
using Microsoft.Extensions.Hosting;
using ModelContextProtocol.Client;
using ModelContextProtocol.Protocol.Transport;

var builder = Host.CreateApplicationBuilder(args);

builder.Configuration
    .AddEnvironmentVariables()
    .AddUserSecrets<Program>();



var clientTransport = new StdioClientTransport(new()
{
    Name = "Demo Server",
    Command = "dotnet",
    Arguments = ["run", "--project", "path/to/file.csproj"],
});

await using var mcpClient = await McpClientFactory.CreateAsync(clientTransport);
```

மேலே உள்ள குறியீட்டில், நாம்:

- தேவையான நூலகங்களை இறக்குமதி செய்கிறோம்.
- stdio போக்குவரத்தை உருவாக்கி, `mcpClient` என்ற கிளையன்டை உருவாக்குகிறோம். இதை MCP சர்வரில் அம்சங்களை பட்டியலிட மற்றும் செயல்படுத்த பயன்படுத்துவோம்.

குறிப்பு: "Arguments"-இல், நீங்கள் *.csproj* அல்லது செயல்படுத்தக்கூடிய கோப்பை சுட்டிக்காட்டலாம்.

#### Java

```java
public class SDKClient {
    
    public static void main(String[] args) {
        var transport = new WebFluxSseClientTransport(WebClient.builder().baseUrl("http://localhost:8080"));
        new SDKClient(transport).run();
    }
    
    private final McpClientTransport transport;

    public SDKClient(McpClientTransport transport) {
        this.transport = transport;
    }

    public void run() {
        var client = McpClient.sync(this.transport).build();
        client.initialize();
        
        // Your client logic goes here
    }
}
```

மேலே உள்ள குறியீட்டில், நாம்:

- `http://localhost:8080`-இல் இயங்கும் MCP சர்வரை சுட்டிக்காட்டும் SSE போக்குவரத்தை அமைக்கும் ஒரு முக்கிய முறைவை உருவாக்குகிறோம்.
- போக்குவரத்தை ஒரு கட்டமைப்புப் பராமரிப்பாக எடுத்துக்கொள்ளும் கிளையன்ட் வகுப்பை உருவாக்குகிறோம்.
- `run` முறைவையில், போக்குவரத்தைப் பயன்படுத்தி ஒத்திசைவு MCP கிளையன்டை உருவாக்கி இணைப்பை ஆரம்பிக்கிறோம்.
- Java Spring Boot MCP சர்வர்களுடன் HTTP அடிப்படையிலான தொடர்புக்கு ஏற்ற SSE (Server-Sent Events) போக்குவரத்தைப் பயன்படுத்துகிறோம்.

#### Rust

இந்த Rust கிளையன்ட், "calculator-server" என்ற பெயரில் அதே கோப்புறையில் உள்ள சகோதர திட்டமாக சர்வரை எடுத்துக்கொள்கிறது. கீழே உள்ள குறியீடு சர்வரை தொடங்கி அதனுடன் இணைக்கும்.

```rust
async fn main() -> Result<(), RmcpError> {
    // Assume the server is a sibling project named "calculator-server" in the same directory
    let server_dir = std::path::Path::new(env!("CARGO_MANIFEST_DIR"))
        .parent()
        .expect("failed to locate workspace root")
        .join("calculator-server");

    let client = ()
        .serve(
            TokioChildProcess::new(Command::new("cargo").configure(|cmd| {
                cmd.arg("run").current_dir(server_dir);
            }))
            .map_err(RmcpError::transport_creation::<TokioChildProcess>)?,
        )
        .await?;

    // TODO: Initialize

    // TODO: List tools

    // TODO: Call add tool with arguments = {"a": 3, "b": 2}

    client.cancel().await?;
    Ok(())
}
```

### -3- சர்வர் அம்சங்களை பட்டியலிடுதல்

இப்போது, நாம் ஒரு கிளையன்டை உருவாக்கியுள்ளோம், இது இயக்கப்படும் போது சர்வருடன் இணைக்க முடியும். ஆனால், இது அதன் அம்சங்களை பட்டியலிடவில்லை, எனவே அதை அடுத்ததாக செய்யலாம்:

#### TypeScript

```typescript
// List prompts
const prompts = await client.listPrompts();

// List resources
const resources = await client.listResources();

// list tools
const tools = await client.listTools();
```

#### Python

```python
# List available resources
resources = await session.list_resources()
print("LISTING RESOURCES")
for resource in resources:
    print("Resource: ", resource)

# List available tools
tools = await session.list_tools()
print("LISTING TOOLS")
for tool in tools.tools:
    print("Tool: ", tool.name)
```

இங்கே, `list_resources()` மற்றும் `list_tools` மூலம் கிடைக்கக்கூடிய வளங்களை பட்டியலிட்டு அவற்றை அச்சிடுகிறோம்.

#### .NET

```dotnet
foreach (var tool in await client.ListToolsAsync())
{
    Console.WriteLine($"{tool.Name} ({tool.Description})");
}
```

மேலே உள்ளது, சர்வரில் உள்ள கருவிகளை பட்டியலிடுவதற்கான உதாரணம். ஒவ்வொரு கருவிக்கும், அதன் பெயரை அச்சிடுகிறோம்.

#### Java

```java
// List and demonstrate tools
ListToolsResult toolsList = client.listTools();
System.out.println("Available Tools = " + toolsList);

// You can also ping the server to verify connection
client.ping();
```

மேலே உள்ள குறியீட்டில், நாம்:

- MCP சர்வரிலிருந்து கிடைக்கும் அனைத்து கருவிகளையும் பெற `listTools()`-ஐ அழைக்கிறோம்.
- சர்வருடன் இணைப்பு செயல்படுகிறதா என்பதை உறுதிப்படுத்த `ping()`-ஐ பயன்படுத்துகிறோம்.
- `ListToolsResult`-இல் கருவிகளின் பெயர்கள், விளக்கங்கள் மற்றும் உள்ளீட்டு ஸ்கீமாக்கள் போன்ற தகவல்கள் அடங்கும்.

சிறந்தது, இப்போது நாம் அனைத்து அம்சங்களையும் பிடித்துள்ளோம். இப்போது கேள்வி என்னவென்றால், அவற்றை எப்போது பயன்படுத்துவது? இந்த கிளையன்ட் மிகவும் எளிமையானது, எளிமையானது என்றால், நாம் அவற்றை விரும்பும்போது அம்சங்களை வெளிப்படையாக அழைக்க வேண்டும். அடுத்த அத்தியாயத்தில், அதன் சொந்த பெரிய மொழி மாதிரி (LLM) அணுகுமுறை கொண்ட ஒரு மேம்பட்ட கிளையன்டை உருவாக்குவோம். தற்போது, சர்வரில் உள்ள அம்சங்களை எப்படி செயல்படுத்தலாம் என்பதை பார்ப்போம்:

#### Rust

முக்கிய செயல்பாட்டில், கிளையன்டை ஆரம்பித்த பிறகு, சர்வரை ஆரம்பித்து அதன் சில அம்சங்களை பட்டியலிடலாம்.

```rust
// Initialize
let server_info = client.peer_info();
println!("Server info: {:?}", server_info);

// List tools
let tools = client.list_tools(Default::default()).await?;
println!("Available tools: {:?}", tools);
```

### -4- அம்சங்களை செயல்படுத்துதல்

அம்சங்களை செயல்படுத்த, நாம் சரியான arguments மற்றும் சில சந்தர்ப்பங்களில் செயல்படுத்த வேண்டிய பெயரை குறிப்பிட வேண்டும்.

#### TypeScript

```typescript

// Read a resource
const resource = await client.readResource({
  uri: "file:///example.txt"
});

// Call a tool
const result = await client.callTool({
  name: "example-tool",
  arguments: {
    arg1: "value"
  }
});

// call prompt
const promptResult = await client.getPrompt({
    name: "review-code",
    arguments: {
        code: "console.log(\"Hello world\")"
    }
})
```

மேலே உள்ள குறியீட்டில், நாம்:

- ஒரு வளத்தைப் படிக்கிறோம், `readResource()`-ஐ அழைத்து `uri`-ஐ குறிப்பிடுகிறோம். இது சர்வர் பக்கம் இவ்வாறு இருக்கும்:

    ```typescript
    server.resource(
        "readFile",
        new ResourceTemplate("file://{name}", { list: undefined }),
        async (uri, { name }) => ({
          contents: [{
            uri: uri.href,
            text: `Hello, ${name}!`
          }]
        })
    );
    ```

    எங்கள் `uri` மதிப்பு `file://example.txt` சர்வரில் `file://{name}`-ஐ பொருந்துகிறது. `example.txt` `name`-க்கு வரைபடமாக்கப்படும்.

- ஒரு கருவியை அழைக்கிறோம், `name` மற்றும் அதன் `arguments`-ஐ குறிப்பிடுவதன் மூலம்:

    ```typescript
    const result = await client.callTool({
        name: "example-tool",
        arguments: {
            arg1: "value"
        }
    });
    ```

- ப்ராம்ப்டை பெற, `getPrompt()`-ஐ `name` மற்றும் `arguments`-ஐ கொண்டு அழைக்கிறோம். சர்வர் குறியீடு இவ்வாறு இருக்கும்:

    ```typescript
    server.prompt(
        "review-code",
        { code: z.string() },
        ({ code }) => ({
            messages: [{
            role: "user",
            content: {
                type: "text",
                text: `Please review this code:\n\n${code}`
            }
            }]
        })
    );
    ```

    எனவே, உங்கள் resulting client code இவ்வாறு இருக்கும்:

    ```typescript
    const promptResult = await client.getPrompt({
        name: "review-code",
        arguments: {
            code: "console.log(\"Hello world\")"
        }
    })
    ```

#### Python

```python
# Read a resource
print("READING RESOURCE")
content, mime_type = await session.read_resource("greeting://hello")

# Call a tool
print("CALL TOOL")
result = await session.call_tool("add", arguments={"a": 1, "b": 7})
print(result.content)
```

மேலே உள்ள குறியீட்டில், நாம்:

- `greeting` என்ற வளத்தை `read_resource` மூலம் அழைக்கிறோம்.
- `add` என்ற கருவியை `call_tool` மூலம் செயல்படுத்துகிறோம்.

#### .NET

1. ஒரு கருவியை அழைக்க சில குறியீட்டைச் சேர்ப்போம்:

  ```csharp
  var result = await mcpClient.CallToolAsync(
      "Add",
      new Dictionary<string, object?>() { ["a"] = 1, ["b"] = 3  },
      cancellationToken:CancellationToken.None);
  ```

1. முடிவை அச்சிட, இதைச் செய்ய சில குறியீடு:

  ```csharp
  Console.WriteLine(result.Content.First(c => c.Type == "text").Text);
  // Sum 4
  ```

#### Java

```java
// Call various calculator tools
CallToolResult resultAdd = client.callTool(new CallToolRequest("add", Map.of("a", 5.0, "b", 3.0)));
System.out.println("Add Result = " + resultAdd);

CallToolResult resultSubtract = client.callTool(new CallToolRequest("subtract", Map.of("a", 10.0, "b", 4.0)));
System.out.println("Subtract Result = " + resultSubtract);

CallToolResult resultMultiply = client.callTool(new CallToolRequest("multiply", Map.of("a", 6.0, "b", 7.0)));
System.out.println("Multiply Result = " + resultMultiply);

CallToolResult resultDivide = client.callTool(new CallToolRequest("divide", Map.of("a", 20.0, "b", 4.0)));
System.out.println("Divide Result = " + resultDivide);

CallToolResult resultHelp = client.callTool(new CallToolRequest("help", Map.of()));
System.out.println("Help = " + resultHelp);
```

மேலே உள்ள குறியீட்டில், நாம்:

- `CallToolRequest` பொருட்களுடன் `callTool()` முறைவைப் பயன்படுத்தி பல கணக்கீட்டு கருவிகளை அழைக்கிறோம்.
- ஒவ்வொரு கருவி அழைப்பும் அந்த கருவிக்கு தேவையான arguments-ஐ குறிப்பிடுகிறது.
- சர்வர் கருவிகள் குறிப்பிட்ட அளவுரு பெயர்களை எதிர்பார்க்கின்றன (கணித செயல்பாடுகளுக்கு "a", "b" போன்றவை).
- முடிவுகள் `CallToolResult` பொருட்களாக திரும்புகின்றன, இது சர்வரிலிருந்து பதிலை உள்ளடக்கியது.

#### Rust

```rust
// Call add tool with arguments = {"a": 3, "b": 2}
let a = 3;
let b = 2;
let tool_result = client
    .call_tool(CallToolRequestParam {
        name: "add".into(),
        arguments: serde_json::json!({ "a": a, "b": b }).as_object().cloned(),
    })
    .await?;
println!("Result of {:?} + {:?}: {:?}", a, b, tool_result);
```

### -5- கிளையன்டை இயக்குங்கள்

கிளையன்டை இயக்க, டெர்மினலில் பின்வரும் கட்டளையைத் தட்டச்சு செய்யுங்கள்:

#### TypeScript

*package.json* இல் "scripts" பிரிவுக்கு பின்வரும் நுழைவைச் சேர்க்கவும்:

```json
"client": "tsc && node build/client.js"
```

```sh
npm run client
```

#### Python

கிளையன்டை பின்வரும் கட்டளையுடன் அழைக்கவும்:

```sh
python client.py
```

#### .NET

```sh
dotnet run
```

#### Java

முதலில், உங்கள் MCP சர்வர் `http://localhost:8080`-இல் இயங்குகிறதா என்பதை உறுதிப்படுத்துங்கள். பின்னர் கிளையன்டை இயக்குங்கள்:

```bash
# Build you project
./mvnw clean compile

# Run the client
./mvnw exec:java -Dexec.mainClass="com.microsoft.mcp.sample.client.SDKClient"
```

மாற்றாக, `03-GettingStarted\02-client\solution\java` என்ற தீர்வு கோப்புறையில் வழங்கப்பட்ட முழு கிளையன்ட் திட்டத்தை இயக்கலாம்:

```bash
# Navigate to the solution directory
cd 03-GettingStarted/02-client/solution/java

# Build and run the JAR
./mvnw clean package
java -jar target/calculator-client-0.0.1-SNAPSHOT.jar
```

#### Rust

```bash
cargo fmt
cargo run
```

## பணிக்கூற்று

இந்த பணிக்கூற்றில், நீங்கள் கிளையன்டை உருவாக்குவதில் கற்றதைக் கொண்டு உங்கள் சொந்த கிளையன்டை உருவாக்குவீர்கள்.

இங்கே, உங்கள் கிளையன்ட் குறியீட்டின் மூலம் அழைக்க வேண்டிய ஒரு சர்வர் உள்ளது, சர்வருக்கு மேலும் அம்சங்களைச் சேர்த்து அதை மேலும் சுவாரஸ்யமாக்க முயற்சிக்கவும்.

### TypeScript

```typescript
import { McpServer, ResourceTemplate } from "@modelcontextprotocol/sdk/server/mcp.js";
import { StdioServerTransport } from "@modelcontextprotocol/sdk/server/stdio.js";
import { z } from "zod";

// Create an MCP server
const server = new McpServer({
  name: "Demo",
  version: "1.0.0"
});

// Add an addition tool
server.tool("add",
  { a: z.number(), b: z.number() },
  async ({ a, b }) => ({
    content: [{ type: "text", text: String(a + b) }]
  })
);

// Add a dynamic greeting resource
server.resource(
  "greeting",
  new ResourceTemplate("greeting://{name}", { list: undefined }),
  async (uri, { name }) => ({
    contents: [{
      uri: uri.href,
      text: `Hello, ${name}!`
    }]
  })
);

// Start receiving messages on stdin and sending messages on stdout

async function main() {
  const transport = new StdioServerTransport();
  await server.connect(transport);
  console.error("MCPServer started on stdin/stdout");
}

main().catch((error) => {
  console.error("Fatal error: ", error);
  process.exit(1);
});
```

### Python

```python
# server.py
from mcp.server.fastmcp import FastMCP

# Create an MCP server
mcp = FastMCP("Demo")


# Add an addition tool
@mcp.tool()
def add(a: int, b: int) -> int:
    """Add two numbers"""
    return a + b


# Add a dynamic greeting resource
@mcp.resource("greeting://{name}")
def get_greeting(name: str) -> str:
    """Get a personalized greeting"""
    return f"Hello, {name}!"

```

### .NET

```csharp
using Microsoft.Extensions.DependencyInjection;
using Microsoft.Extensions.Hosting;
using Microsoft.Extensions.Logging;
using ModelContextProtocol.Server;
using System.ComponentModel;

var builder = Host.CreateApplicationBuilder(args);
builder.Logging.AddConsole(consoleLogOptions =>
{
    // Configure all logs to go to stderr
    consoleLogOptions.LogToStandardErrorThreshold = LogLevel.Trace;
});

builder.Services
    .AddMcpServer()
    .WithStdioServerTransport()
    .WithToolsFromAssembly();
await builder.Build().RunAsync();

[McpServerToolType]
public static class CalculatorTool
{
    [McpServerTool, Description("Adds two numbers")]
    public static string Add(int a, int b) => $"Sum {a + b}";
}
```

இந்த திட்டத்தைப் பாருங்கள், [ப்ராம்ப்ட்கள் மற்றும் வளங்களைச் சேர்க்க](https://github.com/modelcontextprotocol/csharp-sdk/blob/main/samples/EverythingServer/Program.cs) எப்படி என்பதை அறிய.

மேலும், [ப்ராம்ப்ட்கள் மற்றும் வளங்களை அழைக்க](https://github.com/modelcontextprotocol/csharp-sdk/blob/main/src/ModelContextProtocol/Client/) எப்படி என்பதை இந்த இணைப்பில் பார்க்கவும்.

### Rust

முந்தைய பிரிவில் (../01-first-server), Rust-இல் ஒரு எளிய MCP சர்வரை உருவாக்குவது எப்படி என்பதை நீங்கள் கற்றீர்கள். அதில் தொடரலாம் அல்லது Rust அடிப்படையிலான MCP சர்வர் உதாரணங்களை மேலும் பார்க்க இந்த இணைப்பைப் பார்க்கவும்: [MCP Server Examples](https://github.com/modelcontextprotocol/rust-sdk/tree/main/examples/servers)

## தீர்வு

**தீர்வு கோப்புறை** இந்த டுடோரியலில் உள்ள அனைத்து கருத்துகளையும் விளக்கும் முழுமையான, இயக்கத்திற்குத் தயாரான கிளையன்ட் செயல்பாடுகளை உள்ளடக்கியது. ஒவ்வொரு தீர்வும் தனித்துவமான, தனித்துவமான திட்டங்களில் கிளையன்ட் மற்றும் சர்வர் குறியீட்டை உள்ளடக்கியது.

### 📁 தீர்வு அமைப்பு

தீர்வு கோப்புறை நிரலாக்க மொழி மூலம் ஒழுங்கமைக்கப்பட்டுள்ளது:

```text
solution/
├── typescript/          # TypeScript client with npm/Node.js setup
│   ├── package.json     # Dependencies and scripts
│   ├── tsconfig.json    # TypeScript configuration
│   └── src/             # Source code
├── java/                # Java Spring Boot client project
│   ├── pom.xml          # Maven configuration
│   ├── src/             # Java source files
│   └── mvnw             # Maven wrapper
├── python/              # Python client implementation
│   ├── client.py        # Main client code
│   ├── server.py        # Compatible server
│   └── README.md        # Python-specific instructions
├── dotnet/              # .NET client project
│   ├── dotnet.csproj    # Project configuration
│   ├── Program.cs       # Main client code
│   └── dotnet.sln       # Solution file
├── rust/                # Rust client implementation
|  ├── Cargo.lock        # Cargo lock file
|  ├── Cargo.toml        # Project configuration and dependencies
|  ├── src               # Source code
|  │   └── main.rs       # Main client code
└── server/              # Additional .NET server implementation
    ├── Program.cs       # Server code
    └── server.csproj    # Server project file
```

### 🚀 ஒவ்வொரு தீர்வும் என்ன வழங்குகிறது

ஒவ்வொரு மொழி-குறிப்பான தீர்வும் வழங்குகிறது:

- **முழுமையான கிளையன்ட் செயல்பாடு** டுடோரியலில் உள்ள அனைத்து அம்சங்களுடன்
- **சரியான சார்புகள் மற்றும் கட்டமைப்புடன் வேலை செய்யும் திட்ட அமைப்பு**
- **கட்டமைப்பு மற்றும் செயல்பாட்டிற்கான கட்டமைப்பு மற்றும் இயக்க ஸ்கிரிப்ட்கள்**
- **மொழி-குறிப்பான வழிமுறைகளுடன் விரிவான README**
- **பிழை கையாளுதல்** மற்றும் முடிவு செயலாக்க உதாரணங்கள்

### 📖 தீர்வுகளைப் பயன்படுத்துதல்

1. **உங்கள் விருப்பமான மொழி கோப்புறைக்கு செல்லுங்கள்**:

   ```bash
   cd solution/typescript/    # For TypeScript
   cd solution/java/          # For Java
   cd solution/python/        # For Python
   cd solution/dotnet/        # For .NET
   ```

2. **ஒவ்வொரு கோப்புறையிலும் README வழிமுறைகளைப் பின்பற்றுங்கள்**:
   - சார்புகளை நிறுவுதல்
   - திட்டத்தை கட்டமைத்தல்
   - கிளையன்டை இயக்குதல்

3. **உதாரண வெளியீடு** நீங்கள் காண வேண்டும்:

   ```text
   Prompt: Please review this code: console.log("hello");
   Resource template: file
   Tool result: { content: [ { type: 'text', text: '9' } ] }
   ```

முழுமையான ஆவணங்கள் மற்றும் படி-படி வழிமுறைகளுக்கு, பார்க்கவும்: **[📖 தீர்வு ஆவணங்கள்](./solution/README.md)**

## 🎯 முழுமையான உதாரணங்கள்

இந்த டுடோரியலில் உள்ள அனைத்து செயல்பாடுகளையும் விளக்கும் முழுமையான, வேலை செய்யும் கிளையன்ட் செயல்பாடுகளை நாங்கள் வழங்கியுள்ளோம். இந்த உதாரணங்கள் குறிப்புகள் செயல்பாடுகளுக்கான குறிப்புகள் அல்லது உங்கள் சொந்த திட்டங்களுக்கான தொடக்க புள்ளிகளாக பயன்படுத்தப்படலாம்.

### கிடைக்கக்கூடிய முழுமையான உதாரணங்கள்

| மொழி | கோப்பு | விளக்கம் |
|----------|------|-------------|
| **Java** | [`client_example_java.java`](../../../../03-GettingStarted/02-client/client_example_java.java) | SSE போக்குவரத்துடன் முழுமையான Java கிளையன்ட், விரிவான பிழை கையாளுதல் |
| **C#** | [`client_example_csharp.cs`](../../../../03-GettingStarted/02-client/client_example_csharp.cs) | stdio போக்குவரத்துடன் முழுமையான C# கிளையன்ட், தானியக்க சர்வர் தொடக்கம் |
| **TypeScript** | [`client_example_typescript.ts`](../../../../03-GettingStarted/02-client/client_example_typescript.ts) | MCP புரோட்டோகோல் முழுமையான ஆதரவுடன் TypeScript கிளையன்ட் |
| **Python** | [`client_example_python.py`](../../../../03-GettingStarted/02-client/client_example_python.py) | async/await முறைகளைப் பயன்படுத்தும் முழுமையான Python கிளையன்ட் |
| **Rust** | [`client_example_rust.rs`](../../../../03-GettingStarted/02-client/client_example_rust.rs) | async செயல்பாட
- ✅ **முடிவுகளை செயலாக்குதல்** மற்றும் வடிவமைக்கப்பட்ட வெளியீடு
- ✅ **விரிவான பிழை கையாளுதல்**
- ✅ **சுத்தமான, ஆவணப்படுத்தப்பட்ட குறியீடு** படிப்படியாக விளக்கங்களுடன்

### முழுமையான எடுத்துக்காட்டுகளுடன் தொடங்குதல்

1. **உங்கள் விருப்பமான மொழியை தேர்ந்தெடுக்கவும்** மேலே உள்ள அட்டவணையில் இருந்து
2. **முழுமையான எடுத்துக்காட்டு கோப்பை பார்வையிடவும்** முழு செயல்பாட்டை புரிந்துகொள்ள
3. **எடுத்துக்காட்டை இயக்கவும்** [`complete_examples.md`](./complete_examples.md) உள்ள வழிகாட்டுதல்களை பின்பற்றி
4. **உங்கள் குறிப்பிட்ட பயன்பாட்டிற்காக எடுத்துக்காட்டை மாற்றவும் மற்றும் விரிவாக்கவும்**

இந்த எடுத்துக்காட்டுகளை இயக்குவதற்கும் தனிப்பயனாக்குவதற்கும் விரிவான ஆவணங்களைப் பார்க்க: **[📖 முழுமையான எடுத்துக்காட்டு ஆவணங்கள்](./complete_examples.md)**

### 💡 தீர்வு vs. முழுமையான எடுத்துக்காட்டுகள்

| **தீர்வு கோப்புறை** | **முழுமையான எடுத்துக்காட்டுகள்** |
|--------------------|--------------------- |
| கட்டமைப்பு கோப்புகளுடன் முழு திட்ட அமைப்பு | ஒற்றை கோப்பு செயல்பாடுகள் |
| சார்புகளுடன் உடனடியாக இயக்கக்கூடியது | கவனம் செலுத்திய குறியீட்டு எடுத்துக்காட்டுகள் |
| உற்பத்தி போன்ற அமைப்பு | கல்வி குறிப்புகள் |
| மொழி-குறிப்பான கருவிகள் | மொழி-குறிப்பற்ற ஒப்பீடு |

இரு அணுகுமுறைகளும் மதிப்புமிக்கவை - முழு திட்டங்களுக்காக **தீர்வு கோப்புறையை** பயன்படுத்தவும், கற்றல் மற்றும் குறிப்புகளுக்காக **முழுமையான எடுத்துக்காட்டுகளை** பயன்படுத்தவும்.

## முக்கிய குறிப்புகள்

இந்த அத்தியாயத்தின் முக்கிய குறிப்புகள் வாடிக்கையாளர்களைப் பற்றியவை:

- சர்வரில் அமல்படுத்தப்பட்ட அம்சங்களை கண்டறியவும், அழைக்கவும் பயன்படுத்தலாம்.
- இது தானாகவே தொடங்கும்போது சர்வரை தொடங்க முடியும் (இந்த அத்தியாயத்தில் போல) ஆனால் வாடிக்கையாளர்கள் இயங்கும் சர்வர்களுடன் இணைக்கவும் முடியும்.
- சர்வர் திறன்களை சோதிக்க சிறந்த வழி, முந்தைய அத்தியாயத்தில் விவரிக்கப்பட்ட Inspector போன்ற மாற்றுகளுக்கு அடுத்ததாக.

## கூடுதல் வளங்கள்

- [MCP-இல் வாடிக்கையாளர்களை உருவாக்குதல்](https://modelcontextprotocol.io/quickstart/client)

## மாதிரிகள்

- [Java Calculator](../samples/java/calculator/README.md)
- [.Net Calculator](../../../../03-GettingStarted/samples/csharp)
- [JavaScript Calculator](../samples/javascript/README.md)
- [TypeScript Calculator](../samples/typescript/README.md)
- [Python Calculator](../../../../03-GettingStarted/samples/python)
- [Rust Calculator](../../../../03-GettingStarted/samples/rust)

## அடுத்தது என்ன?

- அடுத்தது: [LLM உடன் வாடிக்கையாளரை உருவாக்குதல்](../03-llm-client/README.md)

---

**அறிவிப்பு**:  
இந்த ஆவணம் [Co-op Translator](https://github.com/Azure/co-op-translator) என்ற AI மொழிபெயர்ப்பு சேவையை பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. நாங்கள் துல்லியத்திற்காக முயற்சிக்கிறோம், ஆனால் தானியங்கி மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறுகள் இருக்கக்கூடும் என்பதை கவனத்தில் கொள்ளவும். அதன் சொந்த மொழியில் உள்ள மூல ஆவணம் அதிகாரப்பூர்வ ஆதாரமாக கருதப்பட வேண்டும். முக்கியமான தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பைப் பயன்படுத்துவதால் ஏற்படும் எந்த தவறான புரிதல்களுக்கும் அல்லது தவறான விளக்கங்களுக்கும் நாங்கள் பொறுப்பல்ல.