<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "f4733f39c05c58e0cf0eee0a8ae7e9a2",
  "translation_date": "2025-10-17T20:05:52+00:00",
  "source_file": "03-GettingStarted/samples/python/README.md",
  "language_code": "th"
}
-->
# เซิร์ฟเวอร์ MCP Calculator (Python)

การใช้งานเซิร์ฟเวอร์ Model Context Protocol (MCP) แบบง่ายใน Python ที่มีฟังก์ชันเครื่องคิดเลขพื้นฐาน

## การติดตั้ง

ติดตั้ง dependencies ที่จำเป็น:

```bash
pip install -r requirements.txt
```

หรือสามารถติดตั้ง MCP Python SDK โดยตรง:

```bash
pip install mcp>=1.18.0
```

## การใช้งาน

### การเริ่มต้นเซิร์ฟเวอร์

เซิร์ฟเวอร์นี้ออกแบบมาเพื่อใช้งานร่วมกับ MCP clients (เช่น Claude Desktop) ในการเริ่มต้นเซิร์ฟเวอร์:

```bash
python mcp_calculator_server.py
```

**หมายเหตุ**: เมื่อรันโดยตรงใน terminal คุณอาจเห็นข้อผิดพลาด JSON-RPC validation นี่เป็นพฤติกรรมปกติ - เซิร์ฟเวอร์กำลังรอข้อความจาก MCP client ที่มีรูปแบบถูกต้อง

### การทดสอบฟังก์ชัน

เพื่อทดสอบว่าฟังก์ชันเครื่องคิดเลขทำงานถูกต้อง:

```bash
python test_calculator.py
```

## การแก้ไขปัญหา

### ข้อผิดพลาดการนำเข้า

หากคุณเห็น `ModuleNotFoundError: No module named 'mcp'` ให้ติดตั้ง MCP Python SDK:

```bash
pip install mcp>=1.18.0
```

### ข้อผิดพลาด JSON-RPC เมื่อรันโดยตรง

ข้อผิดพลาดเช่น "Invalid JSON: EOF while parsing a value" เมื่อรันเซิร์ฟเวอร์โดยตรงเป็นสิ่งที่คาดไว้ เซิร์ฟเวอร์ต้องการข้อความจาก MCP client ไม่ใช่การป้อนข้อมูลโดยตรงใน terminal

---

**ข้อจำกัดความรับผิดชอบ**:  
เอกสารนี้ได้รับการแปลโดยใช้บริการแปลภาษา AI [Co-op Translator](https://github.com/Azure/co-op-translator) แม้ว่าเราจะพยายามให้การแปลมีความถูกต้อง แต่โปรดทราบว่าการแปลอัตโนมัติอาจมีข้อผิดพลาดหรือความไม่ถูกต้อง เอกสารต้นฉบับในภาษาดั้งเดิมควรถือเป็นแหล่งข้อมูลที่เชื่อถือได้ สำหรับข้อมูลสำคัญ ขอแนะนำให้ใช้บริการแปลภาษามืออาชีพ เราไม่รับผิดชอบต่อความเข้าใจผิดหรือการตีความผิดที่เกิดจากการใช้การแปลนี้