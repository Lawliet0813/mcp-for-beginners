<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "3880d89fa60abc699e1a17a82ae514ef",
  "translation_date": "2025-10-11T11:55:21+00:00",
  "source_file": "03-GettingStarted/11-simple-auth/solution/typescript/README.md",
  "language_code": "ta"
}
-->
# மாதிரி இயக்கவும்

## சார்புகளை நிறுவவும்

```sh
npm install
```

## கட்டமைக்கவும்

```sh
npm run build
```

## டோக்கன்களை உருவாக்கவும்

```sh
npm run generate
```

இது *.env* என்ற கோப்பில் ஒரு டோக்கனை உருவாக்கும். கிளையன்ட் இந்த கோப்பிலிருந்து படிக்கும்.

## குறியீட்டை இயக்கவும்

சர்வரை தொடங்க:

```sh
npm start
```

கிளையன்டை, வேறு ஒரு டெர்மினலில் இயக்கவும்:

```sh
npm run client
```

சர்வர் டெர்மினலில், நீங்கள் இதற்கு ஒத்த ஒரு வெளியீட்டை காணலாம்:

```text
User exists
User has required scopes
Middleware executed
```

கிளையன்ட் டெர்மினலில், நீங்கள் இதற்கு ஒத்த ஒரு வெளியீட்டை காணலாம்:

```text
Connected to MCP server with session ID: c1e50d7b-acff-4f11-8f96-5ae490ca1eaa
Available tools: { tools: [ { name: 'process-files', inputSchema: [Object] } ] }
Client disconnected.
Exiting...
```

### மாற்றங்களைச் செய்யவும்

நாம் ஸ்கோப்புகளை புரிந்துகொள்வதை உறுதிப்படுத்துவோம். *server.ts* கோப்பை கண்டறிந்து, இந்த குறியீட்டை பாருங்கள்:

```typescript
 if(!hasScopes(token, ["User.Read"])){
        res.status(403).send('Forbidden - insufficient scopes');
    }
```

இது "User.Read" என்ற ஸ்கோப்புடன் டோக்கன் அனுப்பப்பட வேண்டும் என்று கூறுகிறது. அதை "User.Write" ஆக மாற்றுவோம். இப்போது `npm run build` ஐ இயக்கி, சர்வரை மீண்டும் தொடங்க `npm start`. இப்போது அங்கீகாரம் தோல்வியடைவதை நீங்கள் காணலாம், ஏனெனில் இந்த ஸ்கோப் (User.Read மற்றும் Admin.Write) எங்களிடம் இல்லை:

கிளையன்ட் இப்போது கூறுகிறது

```text
Error initializing client: Error: Error POSTing to endpoint (HTTP 403): Forbidden - insufficient scopes
```

மேலும் சர்வர் டெர்மினலில், இது கூறுகிறது:

```text
User exists
```

மேலும் இது இந்த புள்ளியைத் தாண்டி செல்லவில்லை.

இது "User.Write" ஸ்கோப்பைச் சேர்த்து `npm run generate` ஐ இயக்கி, கிளையன்டை மீண்டும் இயக்கவும் அல்லது சர்வர் குறியீட்டை மீண்டும் மாற்றவும்.

---

**குறிப்பு**:  
இந்த ஆவணம் [Co-op Translator](https://github.com/Azure/co-op-translator) என்ற AI மொழிபெயர்ப்பு சேவையைப் பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. நாங்கள் துல்லியத்திற்காக முயற்சிக்கிறோம், ஆனால் தானியக்க மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறான தகவல்கள் இருக்கக்கூடும் என்பதை தயவுசெய்து கவனத்தில் கொள்ளுங்கள். அதன் தாய்மொழியில் உள்ள மூல ஆவணம் அதிகாரப்பூர்வ ஆதாரமாக கருதப்பட வேண்டும். முக்கியமான தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பைப் பயன்படுத்துவதால் ஏற்படும் எந்த தவறான புரிதல்கள் அல்லது தவறான விளக்கங்களுக்கு நாங்கள் பொறுப்பல்ல.