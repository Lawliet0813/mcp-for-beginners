<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "92af35e8c34923031f3d228dffad9ebb",
  "translation_date": "2025-10-11T11:45:39+00:00",
  "source_file": "03-GettingStarted/01-first-server/solution/dotnet/README.md",
  "language_code": "ta"
}
-->
# இந்த மாதிரியை இயக்குவது

## -1- தேவையான பொருட்களை நிறுவவும்

```bash
dotnet restore
```

## -3- மாதிரியை இயக்கவும்

```bash
dotnet run
```

## -4- மாதிரியை சோதிக்கவும்

ஒரு டெர்மினலில் சர்வரை இயக்கி வைத்திருக்கும் போது, மற்றொரு டெர்மினலை திறந்து கீழே உள்ள கட்டளையை இயக்கவும்:

```bash
npx @modelcontextprotocol/inspector dotnet run
```

இது ஒரு காட்சி இடைமுகத்துடன் ஒரு வலை சர்வரை தொடங்க வேண்டும், இது மாதிரியை சோதிக்க உங்களுக்கு உதவும்.

சர்வர் இணைக்கப்பட்ட பிறகு:

- கருவிகளை பட்டியலிட முயற்சிக்கவும் மற்றும் `add` ஐ இயக்கவும், 2 மற்றும் 4 ஆகியவற்றை அளவுருக்களாக கொடுக்கவும், முடிவில் 6 ஐ நீங்கள் காண வேண்டும்.
- resources மற்றும் resource template க்கு சென்று "greeting" ஐ அழைக்கவும், ஒரு பெயரை உள்ளிடவும், நீங்கள் கொடுத்த பெயருடன் ஒரு வாழ்த்து காணலாம்.

### CLI முறையில் சோதனை

நீங்கள் CLI முறையில் நேரடியாக இதை தொடங்க கீழே உள்ள கட்டளையை இயக்கவும்:

```bash
npx @modelcontextprotocol/inspector --cli dotnet run --method tools/list
```

இது சர்வரில் கிடைக்கும் அனைத்து கருவிகளையும் பட்டியலிடும். நீங்கள் கீழே உள்ள வெளியீட்டை காண வேண்டும்:

```text
{
  "tools": [
    {
      "name": "Add",
      "description": "Adds two numbers",
      "inputSchema": {
        "type": "object",
        "properties": {
          "a": {
            "type": "integer"
          },
          "b": {
            "type": "integer"
          }
        },
        "title": "Add",
        "description": "Adds two numbers",
        "required": [
          "a",
          "b"
        ]
      }
    }
  ]
}
```

ஒரு கருவியை அழைக்க:

```bash
npx @modelcontextprotocol/inspector --cli dotnet run --method tools/call --tool-name Add --tool-arg a=1 --tool-arg b=2
```

நீங்கள் கீழே உள்ள வெளியீட்டை காண வேண்டும்:

```text
{
  "content": [
    {
      "type": "text",
      "text": "Sum 3"
    }
  ],
  "isError": false
}
```

> [!TIP]
> CLI முறையில் inspector ஐ இயக்குவது உலாவியில் இயக்குவதைவிட பொதுவாக மிகவும் வேகமாக இருக்கும்.
> inspector பற்றி மேலும் படிக்க [இங்கே](https://github.com/modelcontextprotocol/inspector).

---

**குறிப்பு**:  
இந்த ஆவணம் [Co-op Translator](https://github.com/Azure/co-op-translator) என்ற AI மொழிபெயர்ப்பு சேவையைப் பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. நாங்கள் துல்லியத்திற்காக முயற்சிக்கின்றோம், ஆனால் தானியக்க மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறான தகவல்கள் இருக்கக்கூடும் என்பதை தயவுசெய்து கவனத்தில் கொள்ளுங்கள். அதன் தாய்மொழியில் உள்ள மூல ஆவணம் அதிகாரப்பூர்வ ஆதாரமாக கருதப்பட வேண்டும். முக்கியமான தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பைப் பயன்படுத்துவதால் ஏற்படும் எந்த தவறான புரிதல்கள் அல்லது தவறான விளக்கங்களுக்கு நாங்கள் பொறுப்பல்ல.