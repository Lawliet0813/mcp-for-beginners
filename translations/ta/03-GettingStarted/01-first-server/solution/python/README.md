<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "d4c162484df410632550a4a357d40341",
  "translation_date": "2025-10-11T11:44:42+00:00",
  "source_file": "03-GettingStarted/01-first-server/solution/python/README.md",
  "language_code": "ta"
}
-->
# இந்த மாதிரியை இயக்குவது

`uv` நிறுவ பரிந்துரைக்கப்படுகிறது, ஆனால் இது கட்டாயம் அல்ல, [வழிமுறைகளை](https://docs.astral.sh/uv/#highlights) பார்க்கவும்.

## -0- ஒரு மெய்நிகர் சூழலை உருவாக்கவும்

```bash
python -m venv venv
```

## -1- மெய்நிகர் சூழலை செயல்படுத்தவும்

```bash
venv\Scripts\activate
```

## -2- தேவையான பொருட்களை நிறுவவும்

```bash
pip install "mcp[cli]"
```

## -3- மாதிரியை இயக்கவும்

```bash
mcp run server.py
```

## -4- மாதிரியை சோதிக்கவும்

சர்வர் ஒரு டெர்மினலில் இயங்கும் போது, மற்றொரு டெர்மினலை திறந்து கீழே உள்ள கட்டளையை இயக்கவும்:

```bash
mcp dev server.py
```

இது ஒரு வலை சர்வரை தொடங்க வேண்டும், இது மாதிரியை சோதிக்க ஒரு காட்சி இடைமுகத்தை வழங்கும்.

சர்வர் இணைக்கப்பட்டவுடன்:

- கருவிகளை பட்டியலிட முயற்சிக்கவும் மற்றும் `add` ஐ இயக்கவும், 2 மற்றும் 4 என்ற அளவுகளை கொடுக்கவும், முடிவில் 6 ஐ காணலாம்.

- resources மற்றும் resource template க்கு சென்று `get_greeting` ஐ அழைக்கவும், ஒரு பெயரை உள்ளிடவும், நீங்கள் கொடுத்த பெயருடன் ஒரு வாழ்த்து காணலாம்.

### CLI முறையில் சோதனை

நீங்கள் இயக்கிய inspector உண்மையில் ஒரு Node.js பயன்பாடாகும், மேலும் `mcp dev` அதன் சுற்றுப்புறமாக செயல்படுகிறது.

நீங்கள் CLI முறையில் நேரடியாக அதை இயக்க கீழே உள்ள கட்டளையை இயக்கவும்:

```bash
npx @modelcontextprotocol/inspector --cli mcp run server.py --method tools/list
```

இது சர்வரில் கிடைக்கும் அனைத்து கருவிகளையும் பட்டியலிடும். நீங்கள் கீழே உள்ள வெளியீட்டை காணலாம்:

```text
{
  "tools": [
    {
      "name": "add",
      "description": "Add two numbers",
      "inputSchema": {
        "type": "object",
        "properties": {
          "a": {
            "title": "A",
            "type": "integer"
          },
          "b": {
            "title": "B",
            "type": "integer"
          }
        },
        "required": [
          "a",
          "b"
        ],
        "title": "addArguments"
      }
    }
  ]
}
```

ஒரு கருவியை அழைக்க:

```bash
npx @modelcontextprotocol/inspector --cli mcp run server.py --method tools/call --tool-name add --tool-arg a=1 --tool-arg b=2
```

நீங்கள் கீழே உள்ள வெளியீட்டை காணலாம்:

```text
{
  "content": [
    {
      "type": "text",
      "text": "3"
    }
  ],
  "isError": false
}
```

> [!TIP]
> inspector ஐ CLI முறையில் இயக்குவது உலாவியில் இயக்குவதைவிட பொதுவாக வேகமாக இருக்கும்.
> inspector பற்றி மேலும் படிக்க [இங்கே](https://github.com/modelcontextprotocol/inspector).

---

**குறிப்பு**:  
இந்த ஆவணம் [Co-op Translator](https://github.com/Azure/co-op-translator) என்ற AI மொழிபெயர்ப்பு சேவையை பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. எங்கள் தரத்தை உறுதிப்படுத்த முயற்சிக்கிறோம், ஆனால் தானியக்க மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறுகள் இருக்கக்கூடும் என்பதை கவனத்தில் கொள்ளவும். அதன் தாய்மொழியில் உள்ள மூல ஆவணம் அதிகாரப்பூர்வ ஆதாரமாக கருதப்பட வேண்டும். முக்கியமான தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பைப் பயன்படுத்துவதால் ஏற்படும் எந்த தவறான புரிதல்கள் அல்லது தவறான விளக்கங்களுக்கு நாங்கள் பொறுப்பல்ல.