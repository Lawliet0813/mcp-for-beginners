<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "41f16dac486d2086a53bc644a01cbe42",
  "translation_date": "2025-10-11T12:41:25+00:00",
  "source_file": "07-LessonsfromEarlyAdoption/README.md",
  "language_code": "ta"
}
-->
# 🌟 ஆரம்ப பயனாளர்களிடமிருந்து கற்றுக்கொள்ளும் பாடங்கள்

[![MCP ஆரம்ப பயனாளர்களிடமிருந்து கற்றுக்கொள்ளும் பாடங்கள்](../../../translated_images/08.980bb2babbaadd8a97739effc9b31e5f1abd8f4c4a3fbc90fb9f931a866674d0.ta.png)](https://youtu.be/jds7dSmNptE)

_(இந்த பாடத்தின் வீடியோவைப் பார்க்க மேலே உள்ள படத்தை கிளிக் செய்யவும்)_

## 🎯 இந்த பகுதி என்ன கற்றுக்கொடுக்கிறது

இந்த பகுதி மாடல் கான்டெக்ஸ்ட் புரோட்டோகால் (MCP) பயன்படுத்தி உண்மையான சவால்களை எவ்வாறு தீர்க்கலாம் மற்றும் புதுமையை எவ்வாறு இயக்கலாம் என்பதை உண்மையான நிறுவனங்கள் மற்றும் டெவலப்பர்கள் எப்படி பயன்படுத்துகிறார்கள் என்பதை ஆராய்கிறது. விரிவான வழக்குக் கள ஆய்வுகள் மற்றும் நடைமுறை உதாரணங்கள் மூலம், மொழி மாதிரிகள், கருவிகள் மற்றும் நிறுவன தரவுகளை இணைக்கும் பாதுகாப்பான, அளவீட்டுக்குரிய AI ஒருங்கிணைப்பை MCP எவ்வாறு செயல்படுத்துகிறது என்பதை நீங்கள் கண்டறியலாம்.

### வழக்குக் கள ஆய்வு 5: Azure MCP – நிறுவன தரத்திற்கேற்ப மாடல் கான்டெக்ஸ்ட் புரோட்டோகால் சேவை

Azure MCP ([https://aka.ms/azmcp](https://aka.ms/azmcp)) என்பது மைக்ரோசாஃப்ட் வழங்கும் நிர்வகிக்கப்படும், நிறுவன தரத்திற்கேற்ப மாடல் கான்டெக்ஸ்ட் புரோட்டோகால் செயல்பாடு ஆகும். இது அளவீட்டுக்குரிய, பாதுகாப்பான மற்றும் ஒழுங்குமுறை MCP சர்வர் திறன்களை மேக சேவையாக வழங்க வடிவமைக்கப்பட்டுள்ளது. இந்த விரிவான தொகுப்பு பல்வேறு Azure சேவைகள் மற்றும் சூழல்களுக்கு ஏற்ற MCP சர்வர்களை உள்ளடக்கியது.

[Microsoft MCP மையம்](https://mcp.azure.com) உங்கள் அளவீட்டுக்குரிய, நிறுவனத்திற்கேற்ப MCP பதிவேடுகளை Azure API மையத்துடன் உருவாக்கவும். இது கிடைக்கும் மைக்ரோசாஃப்ட் MCP சர்வர்களின் பட்டியலாகும்.

> **🎯 தயாரிப்பு தயாரான கருவிகள்**
> 
> இந்த வழக்குக் கள ஆய்வு பல தயாரிப்பு தயார MCP சர்வர்களை பிரதிநிதித்துவப்படுத்துகிறது! Azure MCP சர்வர் மற்றும் பிற Azure ஒருங்கிணைக்கப்பட்ட சர்வர்களைப் பற்றி மேலும் அறிய எங்கள் [**Microsoft MCP Servers Guide**](microsoft-mcp-servers.md#2--azure-mcp-server) ஐப் பாருங்கள்.

**முக்கிய அம்சங்கள்:**
- உள்ளமைக்கப்பட்ட அளவீடு, கண்காணிப்பு மற்றும் பாதுகாப்புடன் முழுமையாக நிர்வகிக்கப்படும் MCP சர்வர் ஹோஸ்டிங்
- Azure OpenAI, Azure AI Search மற்றும் பிற Azure சேவைகளுடன் உள்ளமைக்கப்பட்ட ஒருங்கிணைவு
- Microsoft Entra ID மூலம் நிறுவன அங்கீகாரம் மற்றும் அனுமதி
- தனிப்பயன் கருவிகள், ப்ராம்ப்ட் டெம்ப்ளேட்கள் மற்றும் வளங்கள் இணைப்பாளர்களுக்கு ஆதரவு
- நிறுவன பாதுகாப்பு மற்றும் ஒழுங்குமுறை தேவைகளுடன் இணக்கம்
- தரவுத்தொகுப்பு, கண்காணிப்பு மற்றும் சேமிப்பு போன்ற 15+ சிறப்பு Azure சேவை இணைப்பாளர்கள்

**Azure MCP சர்வர் திறன்கள்:**
- **வள மேலாண்மை**: முழுமையான Azure வள வாழ்க்கை சுழற்சி மேலாண்மை
- **தரவுத்தொகுப்பு இணைப்பாளர்கள்**: Azure Database for PostgreSQL மற்றும் SQL Server க்கு நேரடி அணுகல்
- **Azure மானிட்டர்**: KQL மூலம் இயக்கம் மற்றும் பதிவு பகுப்பாய்வு
- **அங்கீகாரம்**: DefaultAzureCredential மற்றும் நிர்வகிக்கப்பட்ட அடையாள வடிவமைப்புகள்
- **சேமிப்பு சேவைகள்**: Blob Storage, Queue Storage மற்றும் Table Storage செயல்பாடுகள்
- **கண்டெய்னர் சேவைகள்**: Azure Container Apps, Container Instances மற்றும் AKS மேலாண்மை

### 📚 MCP செயல்பாட்டை நேரடியாக காணுங்கள்

இந்தக் கொள்கைகளை தயாரிப்பு தயாரான கருவிகளில் பயன்படுத்துவது எப்படி என்பதைப் பார்க்க விரும்புகிறீர்களா? எங்கள் [**10 Microsoft MCP Servers That Are Transforming Developer Productivity**](microsoft-mcp-servers.md) ஐப் பாருங்கள், இது இன்று நீங்கள் பயன்படுத்தக்கூடிய உண்மையான மைக்ரோசாஃப்ட் MCP சர்வர்களை வெளிப்படுத்துகிறது.

## மேலோட்டம்

இந்த பாடம் ஆரம்ப பயனாளர்கள் மாடல் கான்டெக்ஸ்ட் புரோட்டோகாலை (MCP) பயன்படுத்தி உண்மையான சவால்களை எவ்வாறு தீர்த்தனர் மற்றும் பல்வேறு துறைகளில் புதுமையை எவ்வாறு இயக்கினர் என்பதை ஆராய்கிறது. விரிவான வழக்குக் கள ஆய்வுகள் மற்றும் நடைமுறை திட்டங்கள் மூலம், MCP பெரிய மொழி மாதிரிகள், கருவிகள் மற்றும் நிறுவன தரவுகளை ஒரே கட்டமைப்பில் இணைக்கும் முறையை எவ்வாறு செயல்படுத்துகிறது என்பதை நீங்கள் காணலாம். MCP அடிப்படையிலான தீர்வுகளை வடிவமைத்து உருவாக்குவதில் நடைமுறை அனுபவத்தைப் பெறுவீர்கள், நிரூபிக்கப்பட்ட செயல்படுத்தல் முறைமுறைகளிலிருந்து கற்றுக்கொள்வீர்கள் மற்றும் MCP ஐ தயாரிப்பு சூழல்களில் பயன்படுத்த சிறந்த நடைமுறைகளை கண்டறிவீர்கள். மேலும், இந்த பாடம் உருவாகும் போக்குகள், எதிர்கால திசைகள் மற்றும் திறந்த மூல வளங்களை வெளிப்படுத்துகிறது, MCP தொழில்நுட்பத்தின் முன்னணியில் நீங்கள் இருக்க உதவுகிறது.

## கற்றல் நோக்கங்கள்

- பல்வேறு துறைகளில் உண்மையான MCP செயல்பாடுகளை பகுப்பாய்வு செய்யவும்
- முழுமையான MCP அடிப்படையிலான பயன்பாடுகளை வடிவமைத்து உருவாக்கவும்
- MCP தொழில்நுட்பத்தில் உருவாகும் போக்குகள் மற்றும் எதிர்கால திசைகளை ஆராயவும்
- உண்மையான மேம்பாட்டு சூழல்களில் சிறந்த நடைமுறைகளைப் பயன்படுத்தவும்

## உண்மையான MCP செயல்பாடுகள்

### வழக்குக் கள ஆய்வு 1: நிறுவன வாடிக்கையாளர் ஆதரவு தானியக்கமாக்கல்

ஒரு பன்னாட்டுக் கூட்டுறவுக் நிறுவனம், தங்கள் வாடிக்கையாளர் ஆதரவு அமைப்புகளில் AI தொடர்புகளை ஒரே மாதிரியாக்க MCP அடிப்படையிலான ஒரு தீர்வை செயல்படுத்தியது. இதன் மூலம் அவர்கள்:

- பல LLM வழங்குநர்களுக்கான ஒரே இடைமுகத்தை உருவாக்கினர்
- துறைகளுக்கு இடையே ஒரே மாதிரியான ப்ராம்ப்ட் மேலாண்மையை பராமரித்தனர்
- வலுவான பாதுகாப்பு மற்றும் ஒழுங்குமுறை கட்டுப்பாடுகளை செயல்படுத்தினர்
- குறிப்பிட்ட தேவைகளின் அடிப்படையில் வெவ்வேறு AI மாதிரிகளை எளிதாக மாறச் செய்தனர்

**தொழில்நுட்ப செயல்பாடு:**

```python
# Python MCP server implementation for customer support
import logging
import asyncio
from modelcontextprotocol import create_server, ServerConfig
from modelcontextprotocol.server import MCPServer
from modelcontextprotocol.transports import create_http_transport
from modelcontextprotocol.resources import ResourceDefinition
from modelcontextprotocol.prompts import PromptDefinition
from modelcontextprotocol.tool import ToolDefinition

# Configure logging
logging.basicConfig(level=logging.INFO)

async def main():
    # Create server configuration
    config = ServerConfig(
        name="Enterprise Customer Support Server",
        version="1.0.0",
        description="MCP server for handling customer support inquiries"
    )
    
    # Initialize MCP server
    server = create_server(config)
    
    # Register knowledge base resources
    server.resources.register(
        ResourceDefinition(
            name="customer_kb",
            description="Customer knowledge base documentation"
        ),
        lambda params: get_customer_documentation(params)
    )
    
    # Register prompt templates
    server.prompts.register(
        PromptDefinition(
            name="support_template",
            description="Templates for customer support responses"
        ),
        lambda params: get_support_templates(params)
    )
    
    # Register support tools
    server.tools.register(
        ToolDefinition(
            name="ticketing",
            description="Create and update support tickets"
        ),
        handle_ticketing_operations
    )
    
    # Start server with HTTP transport
    transport = create_http_transport(port=8080)
    await server.run(transport)

if __name__ == "__main__":
    asyncio.run(main())
```

**முடிவுகள்:** மாதிரி செலவுகளில் 30% குறைவு, பதிலளிப்பு ஒரே மாதிரியாக 45% மேம்பாடு மற்றும் உலகளாவிய செயல்பாடுகளில் மேம்பட்ட ஒழுங்குமுறை.

### வழக்குக் கள ஆய்வு 2: சுகாதார நோயறிதல் உதவியாளர்

ஒரு சுகாதார வழங்குநர் பல்வேறு சிறப்பு மருத்துவ AI மாதிரிகளை ஒருங்கிணைக்க MCP அடிப்படையிலான ஒரு கட்டமைப்பை உருவாக்கினார், அதே நேரத்தில் நுண்ணறிவு நோயாளி தரவுகள் பாதுகாக்கப்பட்டன:

- பொது மற்றும் சிறப்பு மருத்துவ மாதிரிகளுக்கு இடையே சீரான மாறுதல்
- கடுமையான தனியுரிமை கட்டுப்பாடுகள் மற்றும் தணிக்கை தடங்கள்
- உள்ளமைக்கப்பட்ட மின்னணு சுகாதார பதிவுகள் (EHR) அமைப்புகளுடன் ஒருங்கிணைவு
- மருத்துவ சொற்களுக்கான சீரான ப்ராம்ப்ட் இன்ஜினியரிங்

**தொழில்நுட்ப செயல்பாடு:**

```csharp
// C# MCP host application implementation in healthcare application
using Microsoft.Extensions.DependencyInjection;
using ModelContextProtocol.SDK.Client;
using ModelContextProtocol.SDK.Security;
using ModelContextProtocol.SDK.Resources;

public class DiagnosticAssistant
{
    private readonly MCPHostClient _mcpClient;
    private readonly PatientContext _patientContext;
    
    public DiagnosticAssistant(PatientContext patientContext)
    {
        _patientContext = patientContext;
        
        // Configure MCP client with healthcare-specific settings
        var clientOptions = new ClientOptions
        {
            Name = "Healthcare Diagnostic Assistant",
            Version = "1.0.0",
            Security = new SecurityOptions
            {
                Encryption = EncryptionLevel.Medical,
                AuditEnabled = true
            }
        };
        
        _mcpClient = new MCPHostClientBuilder()
            .WithOptions(clientOptions)
            .WithTransport(new HttpTransport("https://healthcare-mcp.example.org"))
            .WithAuthentication(new HIPAACompliantAuthProvider())
            .Build();
    }
    
    public async Task<DiagnosticSuggestion> GetDiagnosticAssistance(
        string symptoms, string patientHistory)
    {
        // Create request with appropriate resources and tool access
        var resourceRequest = new ResourceRequest
        {
            Name = "patient_records",
            Parameters = new Dictionary<string, object>
            {
                ["patientId"] = _patientContext.PatientId,
                ["requestingProvider"] = _patientContext.ProviderId
            }
        };
        
        // Request diagnostic assistance using appropriate prompt
        var response = await _mcpClient.SendPromptRequestAsync(
            promptName: "diagnostic_assistance",
            parameters: new Dictionary<string, object>
            {
                ["symptoms"] = symptoms,
                patientHistory = patientHistory,
                relevantGuidelines = _patientContext.GetRelevantGuidelines()
            });
            
        return DiagnosticSuggestion.FromMCPResponse(response);
    }
}
```

**முடிவுகள்:** மருத்துவர்களுக்கு மேம்பட்ட நோயறிதல் பரிந்துரைகள் வழங்கப்பட்டது, HIPAA ஒழுங்குமுறையை முழுமையாக பராமரித்தது மற்றும் அமைப்புகளுக்கு இடையே உள்ள சூழல் மாறுதல்களை குறைத்தது.

### வழக்குக் கள ஆய்வு 3: நிதி சேவைகள் அபாய பகுப்பாய்வு

ஒரு நிதி நிறுவனம், தங்கள் அபாய பகுப்பாய்வு செயல்முறைகளை MCP மூலம் ஒரே மாதிரியாக்கியது:

- கடன் அபாயம், மோசடி கண்டறிதல் மற்றும் முதலீட்டு அபாய மாதிரிகளுக்கான ஒரே இடைமுகத்தை உருவாக்கியது
- கடுமையான அணுகல் கட்டுப்பாடுகள் மற்றும் மாதிரி பதிப்புகளை செயல்படுத்தியது
- அனைத்து AI பரிந்துரைகளின் தணிக்கைத்தன்மையை உறுதிசெய்தது
- பல்வேறு அமைப்புகளில் ஒரே மாதிரியான தரவுத் வடிவமைப்பை பராமரித்தது

**தொழில்நுட்ப செயல்பாடு:**

```java
// Java MCP server for financial risk assessment
import org.mcp.server.*;
import org.mcp.security.*;

public class FinancialRiskMCPServer {
    public static void main(String[] args) {
        // Create MCP server with financial compliance features
        MCPServer server = new MCPServerBuilder()
            .withModelProviders(
                new ModelProvider("risk-assessment-primary", new AzureOpenAIProvider()),
                new ModelProvider("risk-assessment-audit", new LocalLlamaProvider())
            )
            .withPromptTemplateDirectory("./compliance/templates")
            .withAccessControls(new SOCCompliantAccessControl())
            .withDataEncryption(EncryptionStandard.FINANCIAL_GRADE)
            .withVersionControl(true)
            .withAuditLogging(new DatabaseAuditLogger())
            .build();
            
        server.addRequestValidator(new FinancialDataValidator());
        server.addResponseFilter(new PII_RedactionFilter());
        
        server.start(9000);
        
        System.out.println("Financial Risk MCP Server running on port 9000");
    }
}
```

**முடிவுகள்:** ஒழுங்குமுறை இணக்கத்தை மேம்படுத்தியது, மாதிரி வெளியீட்டு சுழற்சிகளை 40% வேகமாக்கியது மற்றும் துறைகளுக்கு இடையே அபாய மதிப்பீட்டின் ஒரே மாதிரியை மேம்படுத்தியது.

### வழக்குக் கள ஆய்வு 4: Microsoft Playwright MCP Server – உலாவி தானியக்கமாக்கல்

Microsoft [Playwright MCP server](https://github.com/microsoft/playwright-mcp) ஐ உருவாக்கியது, இது மாடல் கான்டெக்ஸ்ட் புரோட்டோகால் மூலம் பாதுகாப்பான, ஒரே மாதிரியாக்கப்பட்ட உலாவி தானியக்கமாக்கலை இயக்குகிறது. இந்த தயாரிப்பு தயார MCP சர்வர், AI முகவர்கள் மற்றும் LLM களை கட்டுப்படுத்தப்பட்ட, தணிக்கைக்குரிய மற்றும் விரிவாக்கக்கூடிய முறையில் வலை உலாவிகளுடன் தொடர்பு கொள்ள அனுமதிக்கிறது—தானியக்க வலை சோதனை, தரவுத் திரட்டல் மற்றும் முடிவுக்கு முடிவு வேலைப்பாடுகள் போன்ற பயன்பாடுகளை இயக்குகிறது.

> **🎯 தயாரிப்பு தயார கருவி**
> 
> இந்த வழக்குக் கள ஆய்வு நீங்கள் இன்று பயன்படுத்தக்கூடிய உண்மையான MCP சர்வரை வெளிப்படுத்துகிறது! Playwright MCP Server மற்றும் பிற 9 தயாரிப்பு தயார Microsoft MCP சர்வர்களைப் பற்றி மேலும் அறிய எங்கள் [**Microsoft MCP Servers Guide**](microsoft-mcp-servers.md#8--playwright-mcp-server) ஐப் பாருங்கள்.

**முக்கிய அம்சங்கள்:**
- MCP கருவிகளாக உலாவி தானியக்க திறன்களை (நாவிகேஷன், படிவம் நிரப்புதல், ஸ்கிரீன்ஷாட் பிடித்தல், போன்றவை) வெளிப்படுத்துகிறது
- அனுமதிக்கப்படாத செயல்களைத் தடுக்க கடுமையான அணுகல் கட்டுப்பாடுகள் மற்றும் சாண்ட்பாக்சிங் செயல்படுத்துகிறது
- அனைத்து உலாவி தொடர்புகளுக்கும் விரிவான தணிக்கை பதிவுகளை வழங்குகிறது
- Azure OpenAI மற்றும் பிற LLM வழங்குநர்களுடன் ஒருங்கிணைப்புக்கு ஆதரவு
- GitHub Copilot இன் கோடிங் முகவரின் வலை உலாவல் திறன்களை இயக்குகிறது

**தொழில்நுட்ப செயல்பாடு:**

```typescript
// TypeScript: Registering Playwright browser automation tools in an MCP server
import { createServer, ToolDefinition } from 'modelcontextprotocol';
import { launch } from 'playwright';

const server = createServer({
  name: 'Playwright MCP Server',
  version: '1.0.0',
  description: 'MCP server for browser automation using Playwright'
});

// Register a tool for navigating to a URL and capturing a screenshot
server.tools.register(
  new ToolDefinition({
    name: 'navigate_and_screenshot',
    description: 'Navigate to a URL and capture a screenshot',
    parameters: {
      url: { type: 'string', description: 'The URL to visit' }
    }
  }),
  async ({ url }) => {
    const browser = await launch();
    const page = await browser.newPage();
    await page.goto(url);
    const screenshot = await page.screenshot();
    await browser.close();
    return { screenshot };
  }
);

// Start the MCP server
server.listen(8080);
```

**முடிவுகள்:**

- AI முகவர்கள் மற்றும் LLM களுக்கான பாதுகாப்பான, நிரலாக்க உலாவி தானியக்கத்தை இயக்கியது
- கையேடு சோதனை முயற்சியை குறைத்து, வலை பயன்பாடுகளுக்கான சோதனை வரம்பை மேம்படுத்தியது
- நிறுவன சூழல்களில் உலாவி அடிப்படையிலான கருவி ஒருங்கிணைப்புக்கான மறுபயன்படுத்தக்கூடிய, விரிவாக்கக்கூடிய கட்டமைப்பை வழங்கியது
- GitHub Copilot இன் வலை உலாவல் திறன்களை இயக்கியது

**குறிப்புகள்:**

- [Playwright MCP Server GitHub Repository](https://github.com/microsoft/playwright-mcp)
- [Microsoft AI மற்றும் தானியக்க தீர்வுகள்](https://azure.microsoft.com/en-us/products/ai-services/)

### வழக்குக் கள ஆய்வு 5: Azure MCP – நிறுவன தரத்திற்கேற்ப மாடல் கான்டெக்ஸ்ட் புரோட்டோகால் சேவை

Azure MCP Server ([https://aka.ms/azmcp](https://aka.ms/azmcp)) என்பது மைக்ரோசாஃப்ட் வழங்கும் நிர்வகிக்கப்படும், நிறுவன தரத்திற்கேற்ப மாடல் கான்டெக்ஸ்ட் புரோட்டோகால் செயல்பாடு ஆகும். Azure MCP நிறுவனங்களுக்கு Azure AI, தரவுகள் மற்றும் பாதுகாப்பு சேவைகளுடன் MCP சர்வர்களை விரைவாகப் பயன்படுத்த, நிர்வகிக்க மற்றும் ஒருங்கிணைக்க அனுமதிக்கிறது, செயல்பாட்டு சுமையை குறைத்து AI ஏற்றத்தை வேகமாக்குகிறது.

> **🎯 தயாரிப்பு தயார கருவி**
> 
> இது நீங்கள் இன்று பயன்படுத்தக்கூடிய உண்மையான MCP சர்வர்! Azure AI Foundry MCP Server பற்றி மேலும் அறிய எங்கள் [**Microsoft MCP Servers Guide**](microsoft-mcp-servers.md) ஐப் பாருங்கள்.

- உள்ளமைக்கப்பட்ட அளவீடு, கண்காணிப்பு மற்றும் பாதுகாப்புடன் முழுமையாக நிர்வகிக்கப்படும் MCP சர்வர் ஹோஸ்டிங்
- Azure OpenAI, Azure AI Search மற்றும் பிற Azure சேவைகளுடன் உள்ளமைக்கப்பட்ட ஒருங்கிணைவு
- Microsoft Entra ID மூலம் நிறுவன அங்கீகாரம் மற்றும் அனுமதி
- தனிப்பயன் கருவிகள், ப்ராம்ப்ட் டெம்ப்ளேட்கள் மற்றும் வளங்கள் இணைப்பாளர்களுக்கு ஆதரவு
- நிறுவன பாதுகாப்பு மற்றும் ஒழுங்குமுறை தேவைகளுடன் இணக்கம்

**தொழில்நுட்ப செயல்பாடு:**

```yaml
# Example: Azure MCP server deployment configuration (YAML)
apiVersion: mcp.microsoft.com/v1
kind: McpServer
metadata:
  name: enterprise-mcp-server
spec:
  modelProviders:
    - name: azure-openai
      type: AzureOpenAI
      endpoint: https://<your-openai-resource>.openai.azure.com/
      apiKeySecret: <your-azure-keyvault-secret>
  tools:
    - name: document_search
      type: AzureAISearch
      endpoint: https://<your-search-resource>.search.windows.net/
      apiKeySecret: <your-azure-keyvault-secret>
  authentication:
    type: EntraID
    tenantId: <your-tenant-id>
  monitoring:
    enabled: true
    logAnalyticsWorkspace: <your-log-analytics-id>
```

**முடிவுகள்:**  
- தயாரிப்பு தயார MCP சர்வர் தளத்தை வழங்குவதன் மூலம் நிறுவன AI திட்டங்களுக்கான நேரத்தை குறைத்தது
- LLM கள், கருவிகள் மற்றும் நிறுவன தரவுத் தரவுத்தொகுப்புகளை எளிதாக ஒருங்கிணைத்தது
- MCP வேலைப்பாடுகளுக்கான பாதுகாப்பு, கண்காணிப்பு மற்றும் செயல்பாட்டு திறனை மேம்படுத்தியது
- Azure SDK சிறந்த நடைமுறைகள் மற்றும் தற்போதைய அங்கீகார வடிவமைப்புகளுடன் குறியீட்டு தரத்தை மேம்படுத்தியது

**குறிப்புகள்:**  
- [Azure MCP ஆவணங்கள்](https://aka.ms/azmcp)
- [Azure MCP Server GitHub Repository](https://github.com/Azure/azure-mcp)
- [Azure AI சேவைகள்](https://azure.microsoft.com/en-us/products/ai-services/)
- [Microsoft MCP மையம்](https://mcp.azure.com)

## வழக்குக் கள ஆய்வு 6: NLWeb 
MCP (Model Context Protocol) என்பது Chatbots மற்றும் AI உதவியாளர்கள் கருவிகளுடன் தொடர்பு கொள்ள உருவாக்கப்பட்ட ஒரு புதிய புரோட்டோகால் ஆகும். ஒவ்வொரு NLWeb நிகழ்வும் ஒரு MCP சர்வராகவும் செயல்படுகிறது, இது ஒரு முக்கியமான முறை, "ask" ஐ ஆதரிக்கிறது, இது ஒரு வலைத்தளத்திடம் இயல்பான மொழியில் கேள்வி கேட்கப் பயன்படுத்தப்படுகிறது. திரும்பிய பதில் schema.org ஐ பயன்படுத்துகிறது, இது வலைத் தரவுகளை விவரிக்க பரவலாகப் பயன்படுத்தப்படும் ஒரு சொற்களஞ்சியம் ஆகும். சுருக்கமாகச் சொன்னால், MCP என்பது NLWeb ஆகும், Http என்பது HTML ஆகும். NLWeb, புரோட்டோகால்கள், Schema.org வடிவங்கள் மற்றும் மாதிரி குறியீடுகளை இணைத்து, வலைத்தளங்கள் விரைவாக இந்த முடிவுகளை உருவாக்க உதவுகிறது, உரையாடல் இடைமுகங்கள் மூலம் மனிதர்களுக்கும் இயற்கையான முகவர்-முகவர் தொடர்பு மூலம் இயந்திரங்களுக்கும் பயனளிக்கிறது.

NLWeb க்கு இரண்டு தனித்துவமான கூறுகள் உள்ளன:
- ஒரு புரோட்டோகால், ஆரம்பத்தில் மிகவும் எளிமையானது, ஒரு வலைத்தளத்துடன் இயற்கை மொழியில் தொடர்பு கொள்ளவும், திரும்பிய பதிலுக்கான வடிவம், json மற்றும் schema.org ஐ பயன்படுத்துகிறது. REST API பற்றிய ஆவணங்களில் மேலும் விவரங்களைப் பார்க்கவும்.
- (1) இன் நேரடி செயல்பாடு, பொருட்கள், சமையல் குறிப்புகள், ஈர்க்கும் இடங்கள், மதிப்பீடுகள் போன்றவற்றின் பட்டியல்களாக சுருக்கப்படக்கூடிய தளங்களுக்கு ஏற்றவாறு உள்ளமைக்கப்பட்டுள்ளத.
**ஏன் இது முக்கியம்:**
- மைக்ரோசாஃப்ட் தொழில்நுட்பங்களுக்கான "காலாவதியான AI அறிவு" பிரச்சினையை தீர்க்கிறது
- AI உதவியாளர்கள் .NET, C#, Azure மற்றும் Microsoft 365 அம்சங்களின் சமீபத்திய தகவல்களை அணுகுவதை உறுதிசெய்கிறது
- துல்லியமான குறியீடு உருவாக்கத்திற்கான அதிகாரப்பூர்வ, முதல் தர தகவல்களை வழங்குகிறது
- வேகமாக மாறும் மைக்ரோசாஃப்ட் தொழில்நுட்பங்களுடன் பணியாற்றும் டெவலப்பர்களுக்கு இன்றியமையாதது

**முடிவுகள்:**
- மைக்ரோசாஃப்ட் தொழில்நுட்பங்களுக்கான AI உருவாக்கிய குறியீட்டின் துல்லியத்தை கணிசமாக மேம்படுத்தியது
- தற்போதைய ஆவணங்கள் மற்றும் சிறந்த நடைமுறைகளைத் தேடுவதற்கான நேரத்தை குறைத்தது
- சூழ்நிலைக்கு ஏற்ப ஆவணங்களை மீட்டெடுப்பதன் மூலம் டெவலப்பர் உற்பத்தித்திறனை மேம்படுத்தியது
- IDE-ஐ விட்டு வெளியேறாமல் மேம்பாட்டு பணிச்சூழலுடன் ஒருங்கிணைந்தது

**குறிப்புகள்:**
- [Microsoft Learn Docs MCP Server GitHub Repository](https://github.com/MicrosoftDocs/mcp)
- [Microsoft Learn Documentation](https://learn.microsoft.com/)

## நடைமுறை திட்டங்கள்

### திட்டம் 1: பல வழங்குநர் MCP சர்வரை உருவாக்குதல்

**நோக்கம்:** குறிப்பிட்ட அளவுகோல்களின் அடிப்படையில் பல AI மாடல் வழங்குநர்களுக்கு கோரிக்கைகளை வழிநடத்தக்கூடிய MCP சர்வரை உருவாக்கவும்.

**தேவைகள்:**

- குறைந்தது மூன்று மாடல் வழங்குநர்களுக்கு ஆதரவு (எ.கா., OpenAI, Anthropic, உள்ளூர் மாடல்கள்)
- கோரிக்கை தரவுகளின் அடிப்படையில் வழிநடத்தும் முறைமையை செயல்படுத்தவும்
- வழங்குநர் சான்றுகளை நிர்வகிக்க ஒரு கட்டமைப்பு அமைப்பை உருவாக்கவும்
- செயல்திறன் மற்றும் செலவுகளை மேம்படுத்த கேஷிங் சேர்க்கவும்
- பயன்பாட்டை கண்காணிக்க ஒரு எளிய டாஷ்போர்டை உருவாக்கவும்

**செயல்படுத்தும் படிகள்:**

1. அடிப்படை MCP சர்வர் அமைப்பை அமைக்கவும்
2. ஒவ்வொரு AI மாடல் சேவைக்கும் வழங்குநர் அடாப்டர்களை செயல்படுத்தவும்
3. கோரிக்கை பண்புகளின் அடிப்படையில் வழிநடத்தும் தர்க்கத்தை உருவாக்கவும்
4. அடிக்கடி வரும் கோரிக்கைகளுக்கான கேஷிங் முறைமைகளைச் சேர்க்கவும்
5. கண்காணிப்பு டாஷ்போர்டை உருவாக்கவும்
6. பல்வேறு கோரிக்கை மாதிரிகளுடன் சோதிக்கவும்

**தொழில்நுட்பங்கள்:** Python (.NET/Java/Python உங்கள் விருப்பத்தின் அடிப்படையில்), கேஷிங்கிற்கான Redis மற்றும் டாஷ்போர்டிற்கான ஒரு எளிய வலை அமைப்பு.

### திட்டம் 2: நிறுவன ப்ராம்ப்ட் மேலாண்மை அமைப்பு

**நோக்கம்:** ஒரு நிறுவனத்திற்குள் ப்ராம்ப்ட் டெம்ப்ளேட்களை நிர்வகிக்க, பதிப்புகளை பராமரிக்க மற்றும் வெளியிட MCP அடிப்படையிலான ஒரு அமைப்பை உருவாக்கவும்.

**தேவைகள்:**

- ப்ராம்ப்ட் டெம்ப்ளேட்களுக்கான மையக சேமிப்பகத்தை உருவாக்கவும்
- பதிப்பு மற்றும் ஒப்புதல் பணிச்சூழல்களை செயல்படுத்தவும்
- மாதிரித் தரவுகளுடன் டெம்ப்ளேட் சோதனை திறன்களை உருவாக்கவும்
- பாத்திர அடிப்படையிலான அணுகல் கட்டுப்பாடுகளை உருவாக்கவும்
- டெம்ப்ளேட் மீட்பு மற்றும் வெளியீட்டிற்கான API ஒன்றை உருவாக்கவும்

**செயல்படுத்தும் படிகள்:**

1. டெம்ப்ளேட் சேமிப்பிற்கான தரவுத்தொகுப்பு அமைப்பை வடிவமைக்கவும்
2. டெம்ப்ளேட் CRUD செயல்பாடுகளுக்கான மைய API-ஐ உருவாக்கவும்
3. பதிப்பு முறைமையை செயல்படுத்தவும்
4. ஒப்புதல் பணிச்சூழலை உருவாக்கவும்
5. சோதனை அமைப்பை உருவாக்கவும்
6. மேலாண்மைக்கான ஒரு எளிய வலை இடைமுகத்தை உருவாக்கவும்
7. MCP சர்வருடன் ஒருங்கிணைக்கவும்

**தொழில்நுட்பங்கள்:** உங்கள் விருப்பமான பின்புற அமைப்பு, SQL அல்லது NoSQL தரவுத்தொகுப்பு மற்றும் மேலாண்மை இடைமுகத்திற்கான முன்னணி அமைப்பு.

### திட்டம் 3: MCP அடிப்படையிலான உள்ளடக்க உருவாக்க தளம்

**நோக்கம்:** பல்வேறு உள்ளடக்க வகைகளுக்கு ஒரே மாதிரியான முடிவுகளை வழங்க MCP-ஐ பயன்படுத்தி ஒரு உள்ளடக்க உருவாக்க தளத்தை உருவாக்கவும்.

**தேவைகள்:**

- பல உள்ளடக்க வடிவங்களை ஆதரிக்கவும் (வலைப்பதிவுகள், சமூக ஊடகம், சந்தைப்படுத்தல் நகல்)
- தனிப்பயனாக்கல் விருப்பங்களுடன் டெம்ப்ளேட் அடிப்படையிலான உருவாக்கத்தை செயல்படுத்தவும்
- உள்ளடக்க மதிப்பாய்வு மற்றும் கருத்து முறைமையை உருவாக்கவும்
- உள்ளடக்க செயல்திறன் அளவுகோல்களை கண்காணிக்கவும்
- உள்ளடக்க பதிப்பாக்கம் மற்றும் திருத்தத்தை ஆதரிக்கவும்

**செயல்படுத்தும் படிகள்:**

1. MCP கிளையன்ட் அமைப்பை அமைக்கவும்
2. பல உள்ளடக்க வகைகளுக்கான டெம்ப்ளேட்களை உருவாக்கவும்
3. உள்ளடக்க உருவாக்க குழாய்களை உருவாக்கவும்
4. மதிப்பாய்வு முறைமையை செயல்படுத்தவும்
5. அளவுகோல் கண்காணிப்பு முறைமையை உருவாக்கவும்
6. டெம்ப்ளேட் மேலாண்மை மற்றும் உள்ளடக்க உருவாக்கத்திற்கான பயனர் இடைமுகத்தை உருவாக்கவும்

**தொழில்நுட்பங்கள்:** உங்கள் விருப்பமான நிரலாக்க மொழி, வலை அமைப்பு மற்றும் தரவுத்தொகுப்பு அமைப்பு.

## MCP தொழில்நுட்பத்தின் எதிர்கால திசைகள்

### உருவாகும் போக்குகள்

1. **மல்டி-மோடல் MCP**
   - படங்கள், ஒலி மற்றும் வீடியோ மாடல்களுடன் MCP தொடர்புகளை நிலைப்படுத்த விரிவாக்கம்
   - குறுக்கு-மோடல் தர்க்க திறன்களை உருவாக்குதல்
   - வெவ்வேறு முறைமைகளுக்கான நிலைப்படுத்தப்பட்ட ப்ராம்ப்ட் வடிவங்கள்

2. **ஃபெடரேட்டட் MCP கட்டமைப்பு**
   - நிறுவனங்களுக்கு இடையே வளங்களைப் பகிர்ந்து கொள்ளக்கூடிய விநியோகிக்கப்பட்ட MCP நெட்வொர்க்குகள்
   - பாதுகாப்பான மாடல் பகிர்வுக்கான நிலைப்படுத்தப்பட்ட நெறிமுறைகள்
   - தனியுரிமையைப் பாதுகாக்கும் கணக்கீட்டு நுட்பங்கள்

3. **MCP சந்தைகள்**
   - MCP டெம்ப்ளேட்கள் மற்றும் பிளகின்களை பகிர்ந்து கொள்ள மற்றும் வருமானம் ஈட்டும் சூழல்கள்
   - தர உறுதிப்படுத்தல் மற்றும் சான்றிதழ் செயல்முறைகள்
   - மாடல் சந்தைகளுடன் ஒருங்கிணைவு

4. **எட்ஜ் கம்ப்யூட்டிங்கிற்கான MCP**
   - வளங்கள் குறைவான எட்ஜ் சாதனங்களுக்கு MCP நிலைகளின் தழுவல்
   - குறைந்த வலையமைப்பு சூழல்களுக்கு மேம்படுத்தப்பட்ட நெறிமுறைகள்
   - IoT சூழலுக்கான சிறப்பு MCP செயல்பாடுகள்

5. **சட்டரீதமான கட்டமைப்புகள்**
   - சட்டரீதமான இணக்கத்திற்கான MCP நீட்டிப்புகளை உருவாக்குதல்
   - நிலைப்படுத்தப்பட்ட தணிக்கை தடங்கள் மற்றும் விளக்கத்தன்மை இடைமுகங்கள்
   - உருவாகும் AI ஆளுமை கட்டமைப்புகளுடன் ஒருங்கிணைவு

### மைக்ரோசாஃப்ட் வழங்கும் MCP தீர்வுகள்

Microsoft மற்றும் Azure பல திறந்த மூல சேமிப்பகங்களை உருவாக்கியுள்ளது, இது டெவலப்பர்களுக்கு MCP-ஐ பல்வேறு சூழல்களில் செயல்படுத்த உதவுகிறது:

#### Microsoft அமைப்பு

1. [playwright-mcp](https://github.com/microsoft/playwright-mcp) - உலாவி தானியங்கி மற்றும் சோதனைக்கான Playwright MCP சர்வர்
2. [files-mcp-server](https://github.com/microsoft/files-mcp-server) - உள்ளூர் சோதனை மற்றும் சமூக பங்களிப்புக்கான OneDrive MCP சர்வர் செயல்பாடு
3. [NLWeb](https://github.com/microsoft/NlWeb) - திறந்த நெறிமுறைகள் மற்றும் தொடர்புடைய திறந்த மூல கருவிகள் தொகுப்பு. AI வலைக்கான அடிப்படை அடுக்கு அமைப்பை உருவாக்குதல் இதன் முக்கிய நோக்கம்

#### Azure-Samples அமைப்பு

1. [mcp](https://github.com/Azure-Samples/mcp) - பல மொழிகளைப் பயன்படுத்தி Azure-ல் MCP சர்வர்களை உருவாக்கவும் ஒருங்கிணைக்கவும் உதவும் மாதிரிகள், கருவிகள் மற்றும் வளங்களுக்கான இணைப்புகள்
2. [mcp-auth-servers](https://github.com/Azure-Samples/mcp-auth-servers) - தற்போதைய மாடல் சூழல் நெறிமுறையின் மூலம் அங்கீகாரத்தை விளக்கும் குறிப்பு MCP சர்வர்கள்
3. [remote-mcp-functions](https://github.com/Azure-Samples/remote-mcp-functions) - Azure Functions-ல் தொலை MCP சர்வர் செயல்பாடுகளுக்கான தரவுத்தளம்
4. [remote-mcp-functions-python](https://github.com/Azure-Samples/remote-mcp-functions-python) - Python பயன்படுத்தி தனிப்பயன் தொலை MCP சர்வர்களை உருவாக்கவும், வெளியிடவும் விரைவான மாதிரி
5. [remote-mcp-functions-dotnet](https://github.com/Azure-Samples/remote-mcp-functions-dotnet) - .NET/C# பயன்படுத்தி தனிப்பயன் தொலை MCP சர்வர்களை உருவாக்கவும், வெளியிடவும் விரைவான மாதிரி
6. [remote-mcp-functions-typescript](https://github.com/Azure-Samples/remote-mcp-functions-typescript) - TypeScript பயன்படுத்தி தனிப்பயன் தொலை MCP சர்வர்களை உருவாக்கவும், வெளியிடவும் விரைவான மாதிரி
7. [remote-mcp-apim-functions-python](https://github.com/Azure-Samples/remote-mcp-apim-functions-python) - Python பயன்படுத்தி Azure API மேலாண்மை மூலம் தொலை MCP சர்வர்களுடன் ஒருங்கிணைவு
8. [AI-Gateway](https://github.com/Azure-Samples/AI-Gateway) - APIM ❤️ AI பரிசோதனைகள், Azure OpenAI மற்றும் AI Foundry உடன் MCP திறன்களை ஒருங்கிணைத்தல்

இந்த சேமிப்பகங்கள் Model Context Protocol-ஐப் பயன்படுத்தி பல்வேறு நிரலாக்க மொழிகள் மற்றும் Azure சேவைகளில் வேலை செய்யும் செயல்பாடுகள், மாதிரிகள் மற்றும் வளங்களை வழங்குகின்றன. இவை அடிப்படை சர்வர் செயல்பாடுகள் முதல் அங்கீகாரம், மேக வெளியீடு மற்றும் நிறுவன ஒருங்கிணைப்பு வரை பல பயன்பாட்டு வழக்குகளை உள்ளடக்கியவை.

#### MCP வளங்கள் அடைவு

அதிகாரப்பூர்வ மைக்ரோசாஃப்ட் MCP சேமிப்பகத்தில் உள்ள [MCP Resources directory](https://github.com/microsoft/mcp/tree/main/Resources) மாடல் சூழல் நெறிமுறைகள் சர்வர்களுடன் பயன்படுத்த மாதிரி வளங்கள், ப்ராம்ப்ட் டெம்ப்ளேட்கள் மற்றும் கருவி வரையறைகள் ஆகியவற்றின் தொகுப்பை வழங்குகிறது. MCP அடிப்படையிலான தீர்வுகளை உருவாக்கவும், வெளியிடவும் சிறந்த நடைமுறைகளை உறுதிசெய்யவும் இந்த வளங்கள் உதவுகின்றன.

#### MCP வளங்கள் அடைவு

- [MCP Resources (Sample Prompts, Tools, and Resource Definitions)](https://github.com/microsoft/mcp/tree/main/Resources)

### ஆராய்ச்சி வாய்ப்புகள்

- MCP கட்டமைப்புகளில் திறமையான ப்ராம்ப்ட் மேம்பாட்டு நுட்பங்கள்
- பல பயனாளர்களுக்கான MCP வெளியீடுகளுக்கான பாதுகாப்பு மாதிரிகள்
- MCP செயல்பாடுகளுக்கான செயல்திறன் ஒப்பீடு
- MCP சர்வர்களுக்கான உத்தியோகபூர்வ சரிபார்ப்பு முறைகள்

## முடிவு

மாடல் சூழல் நெறிமுறை (MCP) பல தொழில்துறைகளில் நிலைப்படுத்தப்பட்ட, பாதுகாப்பான மற்றும் ஒருங்கிணைந்த AI ஒருங்கிணைப்பின் எதிர்காலத்தை வேகமாக வடிவமைக்கிறது. இந்த பாடத்தில் உள்ள வழக்குப் படிப்புகள் மற்றும் நடைமுறை திட்டங்கள் மூலம், மைக்ரோசாஃப்ட் மற்றும் Azure உட்பட ஆரம்பகால பயனாளர்கள் MCP-ஐ எவ்வாறு பயன்படுத்துகிறார்கள், உண்மையான உலக சவால்களைத் தீர்க்க, AI ஏற்றத்தை வேகமாக்க மற்றும் இணக்கத்தன்மை, பாதுகாப்பு மற்றும் அளவீட்டத்தை உறுதிசெய்யும் என்பதை நீங்கள் பார்த்தீர்கள். MCP-ஐ தொடர்ந்து மேம்படுத்துவதில் ஈடுபடுவதும், திறந்த மூல வளங்களை ஆராய்வதும், சிறந்த நடைமுறைகளைப் பயன்படுத்துவதும் வலுவான, எதிர்காலத்திற்கேற்ப AI தீர்வுகளை உருவாக்க முக்கியமாக இருக்கும்.

## கூடுதல் வளங்கள்

- [MCP Foundry GitHub Repository](https://github.com/azure-ai-foundry/mcp-foundry)
- [Foundry MCP Playground](https://github.com/azure-ai-foundry/foundry-mcp-playground)
- [Integrating Azure AI Agents with MCP (Microsoft Foundry Blog)](https://devblogs.microsoft.com/foundry/integrating-azure-ai-agents-mcp/)
- [MCP GitHub Repository (Microsoft)](https://github.com/microsoft/mcp)
- [MCP Resources Directory (Sample Prompts, Tools, and Resource Definitions)](https://github.com/microsoft/mcp/tree/main/Resources)
- [MCP Community & Documentation](https://modelcontextprotocol.io/introduction)
- [Azure MCP Documentation](https://aka.ms/azmcp)
- [Playwright MCP Server GitHub Repository](https://github.com/microsoft/playwright-mcp)
- [Files MCP Server (OneDrive)](https://github.com/microsoft/files-mcp-server)
- [Azure-Samples MCP](https://github.com/Azure-Samples/mcp)
- [MCP Auth Servers (Azure-Samples)](https://github.com/Azure-Samples/mcp-auth-servers)
- [Remote MCP Functions (Azure-Samples)](https://github.com/Azure-Samples/remote-mcp-functions)
- [Remote MCP Functions Python (Azure-Samples)](https://github.com/Azure-Samples/remote-mcp-functions-python)
- [Remote MCP Functions .NET (Azure-Samples)](https://github.com/Azure-Samples/remote-mcp-functions-dotnet)
- [Remote MCP Functions TypeScript (Azure-Samples)](https://github.com/Azure-Samples/remote-mcp-functions-typescript)
- [Remote MCP APIM Functions Python (Azure-Samples)](https://github.com/Azure-Samples/remote-mcp-apim-functions-python)
- [AI-Gateway (Azure-Samples)](https://github.com/Azure-Samples/AI-Gateway)
- [Microsoft AI and Automation Solutions](https://azure.microsoft.com/en-us/products/ai-services/)

## பயிற்சிகள்

1. வழக்குப் படிப்புகளில் ஒன்றை பகுப்பாய்வு செய்து, மாற்று செயல்பாட்டு அணுகுமுறையை முன்மொழியவும்.
2. திட்டக் கருத்துக்களில் ஒன்றைத் தேர்ந்தெடுத்து, விரிவான தொழில்நுட்ப விவரக்குறிப்பை உருவாக்கவும்.
3. வழக்குப் படிப்புகளில் உள்ளதல்லாத ஒரு தொழில்துறையை ஆராய்ந்து, அதன் குறிப்பிட்ட சவால்களை MCP எவ்வாறு தீர்க்க முடியும் என்பதை சுட்டிக்காட்டவும்.
4. எதிர்கால திசைகளில் ஒன்றை ஆராய்ந்து, அதை ஆதரிக்க புதிய MCP நீட்டிப்பு ஒன்றுக்கான கருத்தை உருவாக்கவும்.

அடுத்தது: [Microsoft MCP Server](../07-LessonsfromEarlyAdoption/microsoft-mcp-servers.md)

---

**அறிவிப்பு**:  
இந்த ஆவணம் [Co-op Translator](https://github.com/Azure/co-op-translator) என்ற AI மொழிபெயர்ப்பு சேவையை பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. நாங்கள் துல்லியத்திற்காக முயற்சிக்கிறோம், ஆனால் தானியங்கி மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறுகள் இருக்கக்கூடும் என்பதை கவனத்தில் கொள்ளவும். அதன் சொந்த மொழியில் உள்ள மூல ஆவணம் அதிகாரப்பூர்வ ஆதாரமாக கருதப்பட வேண்டும். முக்கியமான தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பைப் பயன்படுத்துவதால் ஏற்படும் எந்த தவறான புரிதல்கள் அல்லது தவறான விளக்கங்களுக்கும் நாங்கள் பொறுப்பல்ல.