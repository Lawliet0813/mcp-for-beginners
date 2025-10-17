<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "f4733f39c05c58e0cf0eee0a8ae7e9a2",
  "translation_date": "2025-10-17T20:06:26+00:00",
  "source_file": "03-GettingStarted/samples/python/README.md",
  "language_code": "he"
}
-->
# שרת מחשבון MCP (Python)

מימוש פשוט של שרת Model Context Protocol (MCP) ב-Python המספק פונקציונליות בסיסית של מחשבון.

## התקנה

התקן את התלויות הנדרשות:

```bash
pip install -r requirements.txt
```
  
או התקן את MCP Python SDK ישירות:

```bash
pip install mcp>=1.18.0
```
  

## שימוש

### הפעלת השרת

השרת מיועד לשימוש על ידי לקוחות MCP (כמו Claude Desktop). כדי להפעיל את השרת:

```bash
python mcp_calculator_server.py
```
  
**הערה**: כאשר מפעילים ישירות דרך הטרמינל, ייתכן שתראו שגיאות אימות JSON-RPC. זהו התנהגות רגילה - השרת ממתין להודעות לקוח MCP בפורמט תקין.

### בדיקת הפונקציות

כדי לבדוק שהפונקציות של המחשבון פועלות כראוי:

```bash
python test_calculator.py
```
  

## פתרון בעיות

### שגיאות ייבוא

אם מופיעה השגיאה `ModuleNotFoundError: No module named 'mcp'`, התקן את MCP Python SDK:

```bash
pip install mcp>=1.18.0
```
  

### שגיאות JSON-RPC בעת הפעלה ישירה

שגיאות כמו "Invalid JSON: EOF while parsing a value" בעת הפעלת השרת ישירות הן צפויות. השרת זקוק להודעות לקוח MCP ולא לקלט ישיר מהטרמינל.

---

**כתב ויתור**:  
מסמך זה תורגם באמצעות שירות תרגום AI [Co-op Translator](https://github.com/Azure/co-op-translator). למרות שאנו שואפים לדיוק, יש לקחת בחשבון שתרגומים אוטומטיים עשויים להכיל שגיאות או אי דיוקים. המסמך המקורי בשפתו המקורית צריך להיחשב כמקור סמכותי. עבור מידע קריטי, מומלץ להשתמש בתרגום מקצועי אנושי. איננו אחראים לאי הבנות או לפרשנויות שגויות הנובעות משימוש בתרגום זה.