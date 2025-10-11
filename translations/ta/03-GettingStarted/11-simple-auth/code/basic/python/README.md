<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "3f68294760a11dd3fdd175bd7f904a92",
  "translation_date": "2025-10-11T11:55:44+00:00",
  "source_file": "03-GettingStarted/11-simple-auth/code/basic/python/README.md",
  "language_code": "ta"
}
-->
# மாதிரி இயக்கம்

இந்த மாதிரி ஒரு MCP சர்வரை தொடங்குகிறது, இதில் Authorization header சரியானதா என்பதை சரிபார்க்கும் ஒரு மிடில்வேரும் உள்ளது.

## சார்புகளை நிறுவவும்

```bash
pip install "mcp[cli]" 
```

## சர்வரை தொடங்கவும்

```bash
python server.py
```

மற்றொரு டெர்மினலில் கிளையண்டை தொடங்கவும்

```bash
python client.py
```

நீங்கள் இதைப் போன்ற ஒரு முடிவைக் காணலாம்:

```text
2025-09-30 13:25:54 - mcp_client - INFO - Tool result: meta=None content=[TextContent(type='text', text='{\n  "current_time": "2025-09-30T13:25:54.311900",\n  "timezone": "UTC",\n  "timestamp": 1759238754.3119,\n  "formatted": "2025-09-30 13:25:54"\n}', annotations=None, meta=None)] structuredContent={'current_time': '2025-09-30T13:25:54.311900', 'timezone': 'UTC', 'timestamp': 1759238754.3119, 'formatted': '2025-09-30 13:25:54'} isError=False
```

இது credential அனுப்பப்பட்டு அனுமதிக்கப்பட்டது என்பதை அர்த்தம்.

`client.py`-இல் credential-ஐ "secret-token2" ஆக மாற்ற முயற்சிக்கவும், பின்னர் நீங்கள் பதிலின் ஒரு பகுதியாக இந்த உரையை காணலாம்:

```text
2025-09-30 13:27:44 - httpx - INFO - HTTP Request: POST http://localhost:8000/mcp "HTTP/1.1 403 Forbidden"
```

இது நீங்கள் அங்கீகரிக்கப்பட்டீர்கள் (உங்களிடம் credential இருந்தது), ஆனால் அது தவறானது என்பதை அர்த்தம்.

---

**குறிப்பு**:  
இந்த ஆவணம் [Co-op Translator](https://github.com/Azure/co-op-translator) என்ற AI மொழிபெயர்ப்பு சேவையைப் பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. நாங்கள் துல்லியத்திற்காக முயற்சிக்கின்றோம், ஆனால் தானியக்க மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறான தகவல்கள் இருக்கக்கூடும் என்பதை தயவுசெய்து கவனத்தில் கொள்ளுங்கள். அதன் தாய்மொழியில் உள்ள மூல ஆவணம் அதிகாரப்பூர்வ ஆதாரமாக கருதப்பட வேண்டும். முக்கியமான தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பைப் பயன்படுத்துவதால் ஏற்படும் எந்த தவறான புரிதல்கள் அல்லது தவறான விளக்கங்களுக்கு நாங்கள் பொறுப்பல்ல.