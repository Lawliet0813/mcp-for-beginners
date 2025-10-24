<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "56ad2bfef916cebf4443ef2d620d06e5",
  "translation_date": "2025-10-24T09:17:26+00:00",
  "source_file": "README.md",
  "language_code": "th"
}
-->
![MCP-for-beginners](../../translated_images/mcp-beginners.2ce2b317996369ff66c5b72e25eff9d4288ab2741fc70c0b4e523d1ae1e249fd.th.png)

[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/graphs/contributors)  
[![GitHub issues](https://img.shields.io/github/issues/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/issues)  
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/pulls)  
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/mcp-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/mcp-for-beginners/watchers)  
[![GitHub forks](https://img.shields.io/github/forks/microsoft/mcp-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/mcp-for-beginners/fork)  
[![GitHub stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners?style=social&label=Star)](https://GitHub.com/microsoft/mcp-for-beginners/stargazers)

[![Microsoft Azure AI Foundry Discord](https://dcbadge.limes.pink/api/server/ByRwuEEgH4)](https://discord.com/invite/ByRwuEEgH4)

ทำตามขั้นตอนเหล่านี้เพื่อเริ่มต้นใช้งานทรัพยากรเหล่านี้:  
1. **Fork Repository**: คลิก [![GitHub forks](https://img.shields.io/github/forks/microsoft/mcp-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/mcp-for-beginners/fork)  
2. **Clone Repository**: `git clone https://github.com/microsoft/mcp-for-beginners.git`  
3. [**เข้าร่วม Azure AI Foundry Discord เพื่อพบปะผู้เชี่ยวชาญและนักพัฒนาคนอื่นๆ**](https://discord.com/invite/ByRwuEEgH4)

### 🌐 รองรับหลายภาษา

#### รองรับผ่าน GitHub Action (อัตโนมัติและอัปเดตเสมอ)

[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](./README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

# 🚀 หลักสูตร Model Context Protocol (MCP) สำหรับผู้เริ่มต้น

## **เรียนรู้ MCP ด้วยตัวอย่างโค้ดใน C#, Java, JavaScript, Rust, Python และ TypeScript**

## 🧠 ภาพรวมของหลักสูตร Model Context Protocol  
ยินดีต้อนรับสู่การเดินทางของคุณในโลกของ Model Context Protocol! หากคุณเคยสงสัยว่าแอปพลิเคชัน AI สื่อสารกับเครื่องมือและบริการต่างๆ ได้อย่างไร คุณกำลังจะค้นพบวิธีแก้ปัญหาที่เปลี่ยนแปลงวิธีการที่นักพัฒนาสร้างระบบอัจฉริยะ

ลองนึกถึง MCP ว่าเป็นเหมือนตัวแปลภาษาสากลสำหรับแอปพลิเคชัน AI - เช่นเดียวกับพอร์ต USB ที่ช่วยให้คุณเชื่อมต่ออุปกรณ์ใดๆ กับคอมพิวเตอร์ MCP ช่วยให้โมเดล AI เชื่อมต่อกับเครื่องมือหรือบริการใดๆ ได้ในรูปแบบมาตรฐาน ไม่ว่าคุณจะสร้างแชทบอทตัวแรกของคุณหรือทำงานกับเวิร์กโฟลว์ AI ที่ซับซ้อน การเข้าใจ MCP จะช่วยให้คุณสร้างแอปพลิเคชันที่มีความสามารถและยืดหยุ่นมากขึ้น

หลักสูตรนี้ออกแบบมาเพื่อให้คุณเรียนรู้ได้อย่างสะดวกและมั่นใจ เราจะเริ่มต้นด้วยแนวคิดง่ายๆ ที่คุณเข้าใจอยู่แล้ว และค่อยๆ สร้างความเชี่ยวชาญของคุณผ่านการฝึกปฏิบัติในภาษาการเขียนโปรแกรมที่คุณชื่นชอบ ทุกขั้นตอนมีคำอธิบายที่ชัดเจน ตัวอย่างที่ใช้งานได้จริง และกำลังใจมากมายตลอดเส้นทาง

เมื่อคุณเรียนจบหลักสูตรนี้ คุณจะมีความมั่นใจในการสร้างเซิร์ฟเวอร์ MCP ของคุณเอง ผสานรวมกับแพลตฟอร์ม AI ยอดนิยม และเข้าใจว่าเทคโนโลยีนี้กำลังเปลี่ยนแปลงอนาคตของการพัฒนา AI อย่างไร มาเริ่มต้นการผจญภัยที่น่าตื่นเต้นนี้ไปด้วยกัน!

### เอกสารและสเปคอย่างเป็นทางการ

ทรัพยากรเหล่านี้จะมีคุณค่ามากขึ้นเมื่อความเข้าใจของคุณเพิ่มขึ้น แต่ไม่ต้องกังวลที่จะอ่านทุกอย่างในทันที เริ่มต้นจากส่วนที่คุณสนใจมากที่สุด!  
- 📘 [เอกสาร MCP](https://modelcontextprotocol.io/) – นี่คือแหล่งข้อมูลที่คุณสามารถใช้สำหรับบทเรียนและคู่มือการใช้งานแบบทีละขั้นตอน เอกสารนี้เขียนขึ้นโดยคำนึงถึงผู้เริ่มต้น โดยมีตัวอย่างที่ชัดเจนที่คุณสามารถทำตามได้ในจังหวะของคุณเอง  
- 📜 [สเปค MCP](https://modelcontextprotocol.io/docs/) – คิดว่านี่เป็นคู่มืออ้างอิงที่ครอบคลุม เมื่อคุณทำงานผ่านหลักสูตร คุณจะกลับมาที่นี่เพื่อค้นหารายละเอียดเฉพาะและสำรวจฟีเจอร์ขั้นสูง  
- 📜 [สเปค MCP ดั้งเดิม](https://spec.modelcontextprotocol.io/) – มีรายละเอียดทางเทคนิคเพิ่มเติมที่สามารถเป็นประโยชน์สำหรับการใช้งานขั้นสูง มันจะอยู่ที่นี่เมื่อคุณต้องการ แต่ไม่ต้องกังวลเมื่อคุณเริ่มต้น  
- 🧑‍💻 [MCP GitHub Repository](https://github.com/modelcontextprotocol) – ที่นี่คุณจะพบ SDK เครื่องมือ และตัวอย่างโค้ดในหลายภาษาการเขียนโปรแกรม เป็นเหมือนขุมทรัพย์ของตัวอย่างที่ใช้งานได้จริงและส่วนประกอบที่พร้อมใช้งาน  
- 🌐 [ชุมชน MCP](https://github.com/orgs/modelcontextprotocol/discussions) – เข้าร่วมกับผู้เรียนและนักพัฒนาที่มีประสบการณ์ในการพูดคุยเกี่ยวกับ MCP เป็นชุมชนที่สนับสนุนซึ่งยินดีต้อนรับคำถามและแบ่งปันความรู้กันอย่างอิสระ  

## วัตถุประสงค์การเรียนรู้

เมื่อจบหลักสูตรนี้ คุณจะรู้สึกมั่นใจและตื่นเต้นกับความสามารถใหม่ของคุณ นี่คือสิ่งที่คุณจะบรรลุ:  

• **เข้าใจพื้นฐานของ MCP**: คุณจะเข้าใจว่า Model Context Protocol คืออะไร และทำไมมันถึงเปลี่ยนแปลงวิธีการที่แอปพลิเคชัน AI ทำงานร่วมกัน โดยใช้การเปรียบเทียบและตัวอย่างที่เข้าใจง่าย  

• **สร้างเซิร์ฟเวอร์ MCP ตัวแรกของคุณ**: คุณจะสร้างเซิร์ฟเวอร์ MCP ที่ใช้งานได้ในภาษาการเขียนโปรแกรมที่คุณชื่นชอบ โดยเริ่มต้นจากตัวอย่างง่ายๆ และพัฒนาทักษะของคุณทีละขั้นตอน  

• **เชื่อมต่อโมเดล AI กับเครื่องมือจริง**: คุณจะเรียนรู้วิธีเชื่อมโยงโมเดล AI กับบริการจริง เพื่อเพิ่มความสามารถใหม่ๆ ให้กับแอปพลิเคชันของคุณ  

• **นำแนวปฏิบัติด้านความปลอดภัยมาใช้**: คุณจะเข้าใจวิธีการรักษาความปลอดภัยในการใช้งาน MCP เพื่อปกป้องทั้งแอปพลิเคชันและผู้ใช้งานของคุณ  

• **ปรับใช้ด้วยความมั่นใจ**: คุณจะรู้วิธีนำโครงการ MCP ของคุณจากการพัฒนาไปสู่การใช้งานจริง ด้วยกลยุทธ์การปรับใช้ที่ใช้งานได้ในโลกจริง  

• **เข้าร่วมชุมชน MCP**: คุณจะกลายเป็นส่วนหนึ่งของชุมชนที่เติบโตขึ้นของนักพัฒนาที่กำลังสร้างอนาคตของการพัฒนาแอปพลิเคชัน AI  

## พื้นฐานที่จำเป็น

ก่อนที่เราจะเจาะลึกในรายละเอียดของ MCP มาทำความเข้าใจแนวคิดพื้นฐานบางอย่างกันก่อน ไม่ต้องกังวลหากคุณยังไม่เชี่ยวชาญในด้านเหล่านี้ - เราจะอธิบายทุกสิ่งที่คุณจำเป็นต้องรู้ระหว่างทาง!

### การทำความเข้าใจโปรโตคอล (พื้นฐาน)

ลองนึกถึงโปรโตคอลว่าเป็นกฎสำหรับการสนทนา เมื่อคุณโทรหาเพื่อน คุณทั้งคู่รู้ว่าต้องพูด "สวัสดี" เมื่อรับสาย สลับกันพูด และพูด "ลาก่อน" เมื่อจบการสนทนา โปรแกรมคอมพิวเตอร์ก็ต้องการกฎที่คล้ายกันเพื่อสื่อสารอย่างมีประสิทธิภาพ

MCP คือโปรโตคอล - ชุดของกฎที่ตกลงกันไว้ซึ่งช่วยให้โมเดล AI และแอปพลิเคชันสามารถสนทนา "อย่างมีประสิทธิภาพ" กับเครื่องมือและบริการต่างๆ เช่นเดียวกับการมีกฎการสนทนาที่ทำให้การสื่อสารของมนุษย์ราบรื่น การมี MCP ทำให้การสื่อสารของแอปพลิเคชัน AI มีความน่าเชื่อถือและทรงพลังมากขึ้น

### ความสัมพันธ์ระหว่าง Client-Server (วิธีการทำงานร่วมกันของโปรแกรม)

คุณใช้ความสัมพันธ์ระหว่าง Client-Server อยู่ทุกวัน! เมื่อคุณใช้เว็บเบราว์เซอร์ (Client) เพื่อเข้าชมเว็บไซต์ คุณกำลังเชื่อมต่อกับเว็บเซิร์ฟเวอร์ที่ส่งเนื้อหาของหน้าเว็บให้คุณ เบราว์เซอร์รู้วิธีการขอข้อมูล และเซิร์ฟเวอร์รู้วิธีการตอบกลับ

ใน MCP เรามีความสัมพันธ์ที่คล้ายกัน: โมเดล AI ทำหน้าที่เป็น Client ที่ร้องขอข้อมูลหรือการดำเนินการ ในขณะที่เซิร์ฟเวอร์ MCP ให้ความสามารถเหล่านั้น เป็นเหมือนการมีผู้ช่วยที่เป็นประโยชน์ (เซิร์ฟเวอร์) ที่โมเดล AI สามารถขอให้ทำงานเฉพาะเจาะจงได้

### ทำไมการมาตรฐานถึงสำคัญ (ทำให้สิ่งต่างๆ ทำงานร่วมกัน)

ลองจินตนาการว่าผู้ผลิตรถยนต์แต่ละรายใช้ปั๊มน้ำมันที่มีรูปร่างแตกต่างกัน - คุณจะต้องมีอะแดปเตอร์ที่แตกต่างกันสำหรับรถแต่ละคัน! การมาตรฐานหมายถึงการตกลงในวิธีการทั่วไปเพื่อให้สิ่งต่างๆ ทำงานร่วมกันได้อย่างราบรื่น

MCP ให้การมาตรฐานนี้สำหรับแอปพลิเคชัน AI แทนที่โมเดล AI แต่ละตัวจะต้องใช้โค้ดเฉพาะเพื่อทำงานร่วมกับเครื่องมือแต่ละตัว MCP สร้างวิธีการสากลสำหรับการสื่อสาร ซึ่งหมายความว่านักพัฒนาสามารถสร้างเครื่องมือเพียงครั้งเดียวและให้มันทำงานร่วมกับระบบ AI ที่หลากหลายได้

## 🧭 ภาพรวมเส้นทางการเรียนรู้ของคุณ

การเดินทางในโลก MCP ของคุณถูกออกแบบมาอย่างพิถีพิถันเพื่อสร้างความมั่นใจและทักษะของคุณอย่างต่อเนื่อง แต่ละขั้นตอนจะแนะนำแนวคิดใหม่ๆ พร้อมกับเสริมสร้างสิ่งที่คุณได้เรียนรู้ไปแล้ว

### 🌱 ขั้นพื้นฐาน: ทำความเข้าใจเบื้องต้น (โมดูล 0-2)

นี่คือจุดเริ่มต้นของการผจญภัยของคุณ! เราจะอธิบายแนวคิดของ MCP โดยใช้การเปรียบเทียบที่คุ้นเคยและตัวอย่างง่ายๆ คุณจะเข้าใจว่า MCP คืออะไร ทำไมมันถึงมีความสำคัญ และมันเข้ากับโลกของการพัฒนา AI อย่างไร

• **โมดูล 0 - แนะนำ MCP**: เราจะเริ่มต้นด้วยการสำรวจว่า MCP คืออะไร และทำไมมันถึงสำคัญสำหรับแอปพลิเคชัน AI สมัยใหม่ คุณจะเห็นตัวอย่างจริงของ MCP ในการใช้งาน และเข้าใจว่ามันแก้ปัญหาทั่วไปที่นักพัฒนาต้องเผชิญได้อย่างไร  

• **โมดูล 1 - อธิบายแนวคิดหลัก**: ที่นี่คุณจะได้เรียนรู้ส่วนประกอบสำคัญของ MCP เราจะใช้การเปรียบเทียบและตัวอย่างภาพเพื่อให้แนวคิดเหล่านี้รู้สึกเป็นธรรมชาติและเข้าใจง่าย  

• **โมดูล 2 - ความปลอดภัยใน MCP**: ความปลอดภัยอาจฟังดูน่ากลัว แต่เราจะแสดงให้คุณเห็นว่า MCP มีฟีเจอร์ความปลอดภัยในตัว และสอนแนวปฏิบัติที่ดีที่สุดที่ช่วยปกป้องแอปพลิเคชันของคุณตั้งแต่เริ่มต้น  

### 🔨 ขั้นสร้าง: สร้างการใช้งานครั้งแรกของคุณ (โมดูล 3)

ตอนนี้ความสนุกที่แท้จริงเริ่มต้นขึ้น! คุณจะได้ประสบการณ์จริงในการสร้างเซิร์ฟเวอร์และ Client MCP จริง ไม่ต้องกังวล - เราจะเริ่มต้นอย่างง่ายและแนะนำคุณในทุกขั้นตอน  

โมดูลนี้รวมถึงคู่มือการฝึกปฏิบัติหลายฉบับที่ให้คุณฝึกฝนในภาษาการเขียนโปรแกรมที่คุณชื่นชอบ คุณจะสร้างเซิร์ฟเวอร์ตัวแรกของคุณ สร้าง Client เพื่อเชื่อมต่อกับมัน และแม้กระทั่งผสานรวมกับเครื่องมือพัฒนายอดนิยมอย่าง VS Code  

แต่ละคู่มือมีตัวอย่างโค้ดที่สมบูรณ์ เคล็ดลับการแก้ไขปัญหา และคำอธิบายว่าทำไมเราถึงเลือกการออกแบบเฉพาะเจาะจง เมื่อจบขั้นตอนนี้ คุณจะมีการใช้งาน MCP ที่ใช้งานได้จริงที่คุณสามารถภูมิใจได้!  

### 🚀 ขั้นพัฒนา: แนวคิดขั้นสูงและการใช้งานจริง (โมดูล 4-5)

เมื่อคุณเชี่ยวชาญพื้นฐานแล้ว คุณพร้อมที่จะสำรวจฟีเจอร์ MCP ที่ซับซ้อนมากขึ้น เราจะครอบคลุมกลยุทธ์การใช้งานจริง เทคนิคการแก้ไขข้อผิดพลาด และหัวข้อขั้นสูง เช่น การผสานรวม AI แบบหลายรูปแบบ  

คุณยังจะได้เรียนรู้วิธีการขยายการใช้งาน MCP ของคุณสำหรับการใช้งานในระดับการผลิต และผสานรวมกับแพลตฟอร์มคลาวด์อย่าง Azure โมดูลเหล่านี้เตรียมคุณให้พร้อมสำหรับการสร้างโซลูชัน MCP ที่สามารถรองรับความต้องการในโลกจริง  

### 🌟 ขั้นเชี่ยวชาญ: ชุมชนและการเชี่ยวชาญเฉพาะทาง (โมดูล 6-11)  
ขั้นตอนสุดท้ายเน้นการเข้าร่วมชุมชน MCP และการเชี่ยวชาญในด้านที่คุณสนใจมากที่สุด คุณจะได้เรียนรู้วิธีการมีส่วนร่วมในโครงการ MCP แบบโอเพ่นซอร์ส การนำรูปแบบการยืนยันตัวตนขั้นสูงไปใช้ และการสร้างโซลูชันที่รวมฐานข้อมูลอย่างครบวงจร

โมดูลที่ 11 ควรได้รับการกล่าวถึงเป็นพิเศษ - เป็นเส้นทางการเรียนรู้แบบลงมือทำที่มีทั้งหมด 13 ห้องปฏิบัติการ ซึ่งสอนคุณในการสร้างเซิร์ฟเวอร์ MCP ที่พร้อมใช้งานจริงพร้อมการรวม PostgreSQL เป็นเหมือนโครงการสรุปที่รวบรวมทุกสิ่งที่คุณได้เรียนรู้มา!

### 📚 โครงสร้างหลักสูตรทั้งหมด

| โมดูล | หัวข้อ | คำอธิบาย | ลิงก์ |
|-------|--------|----------|-------|
| **โมดูล 1-3: พื้นฐาน** | | | |
| 00 | แนะนำ MCP | ภาพรวมของ Model Context Protocol และความสำคัญในกระบวนการ AI | [อ่านเพิ่มเติม](./00-Introduction/README.md) |
| 01 | อธิบายแนวคิดหลัก | การสำรวจเชิงลึกเกี่ยวกับแนวคิดหลักของ MCP | [อ่านเพิ่มเติม](./01-CoreConcepts/README.md) |
| 02 | ความปลอดภัยใน MCP | ภัยคุกคามด้านความปลอดภัยและแนวทางปฏิบัติที่ดีที่สุด | [อ่านเพิ่มเติม](./02-Security/README.md) |
| 03 | เริ่มต้นใช้งาน MCP | การตั้งค่าสภาพแวดล้อม เซิร์ฟเวอร์/ไคลเอนต์พื้นฐาน การรวมระบบ | [อ่านเพิ่มเติม](./03-GettingStarted/README.md) |
| **โมดูล 3: สร้างเซิร์ฟเวอร์และไคลเอนต์แรกของคุณ** | | | |
| 3.1 | เซิร์ฟเวอร์แรก | สร้างเซิร์ฟเวอร์ MCP แรกของคุณ | [คู่มือ](./03-GettingStarted/01-first-server/README.md) |
| 3.2 | ไคลเอนต์แรก | พัฒนาไคลเอนต์ MCP พื้นฐาน | [คู่มือ](./03-GettingStarted/02-client/README.md) |
| 3.3 | ไคลเอนต์พร้อม LLM | รวมโมเดลภาษาขนาดใหญ่ | [คู่มือ](./03-GettingStarted/03-llm-client/README.md) |
| 3.4 | การรวม VS Code | ใช้เซิร์ฟเวอร์ MCP ใน VS Code | [คู่มือ](./03-GettingStarted/04-vscode/README.md) |
| 3.5 | เซิร์ฟเวอร์ stdio | สร้างเซิร์ฟเวอร์โดยใช้การส่งข้อมูลแบบ stdio | [คู่มือ](./03-GettingStarted/05-stdio-server/README.md) |
| 3.6 | การสตรีม HTTP | ใช้การสตรีม HTTP ใน MCP | [คู่มือ](./03-GettingStarted/06-http-streaming/README.md) |
| 3.7 | AI Toolkit | ใช้ AI Toolkit กับ MCP | [คู่มือ](./03-GettingStarted/07-aitk/README.md) |
| 3.8 | การทดสอบ | ทดสอบการใช้งานเซิร์ฟเวอร์ MCP ของคุณ | [คู่มือ](./03-GettingStarted/08-testing/README.md) |
| 3.9 | การปรับใช้ | ปรับใช้เซิร์ฟเวอร์ MCP สู่การใช้งานจริง | [คู่มือ](./03-GettingStarted/09-deployment/README.md) |
| 3.10 | การใช้งานเซิร์ฟเวอร์ขั้นสูง | ใช้เซิร์ฟเวอร์ขั้นสูงสำหรับการใช้งานฟีเจอร์ขั้นสูงและสถาปัตยกรรมที่ดีขึ้น | [คู่มือ](./03-GettingStarted/10-advanced/README.md) |
| 3.11 | การยืนยันตัวตนแบบง่าย | บทที่แสดงการยืนยันตัวตนตั้งแต่เริ่มต้นและ RBAC | [คู่มือ](./03-GettingStarted/11-simple-auth/README.md) |
| **โมดูล 4-5: การปฏิบัติและขั้นสูง** | | | |
| 04 | การใช้งานจริง | SDKs, การดีบัก, การทดสอบ, เทมเพลตคำสั่งที่นำกลับมาใช้ใหม่ได้ | [อ่านเพิ่มเติม](./04-PracticalImplementation/README.md) |
| 05 | หัวข้อขั้นสูงใน MCP | AI แบบหลายรูปแบบ, การขยายขนาด, การใช้งานในองค์กร | [อ่านเพิ่มเติม](./05-AdvancedTopics/README.md) |
| 5.1 | การรวม Azure | การรวม MCP กับ Azure | [คู่มือ](./05-AdvancedTopics/mcp-integration/README.md) |
| 5.2 | การใช้งานหลายรูปแบบ | การทำงานกับหลายรูปแบบ | [คู่มือ](./05-AdvancedTopics/mcp-multi-modality/README.md) |
| 5.3 | การสาธิต OAuth2 | ใช้การยืนยันตัวตน OAuth2 | [คู่มือ](./05-AdvancedTopics/mcp-oauth2-demo/README.md) |
| 5.4 | Root Contexts | ทำความเข้าใจและใช้งาน root contexts | [คู่มือ](./05-AdvancedTopics/mcp-root-contexts/README.md) |
| 5.5 | การกำหนดเส้นทาง | กลยุทธ์การกำหนดเส้นทาง MCP | [คู่มือ](./05-AdvancedTopics/mcp-routing/README.md) |
| 5.6 | การสุ่มตัวอย่าง | เทคนิคการสุ่มตัวอย่างใน MCP | [คู่มือ](./05-AdvancedTopics/mcp-sampling/README.md) |
| 5.7 | การขยายขนาด | ขยายการใช้งาน MCP | [คู่มือ](./05-AdvancedTopics/mcp-scaling/README.md) |
| 5.8 | ความปลอดภัย | การพิจารณาด้านความปลอดภัยขั้นสูง | [คู่มือ](./05-AdvancedTopics/mcp-security/README.md) |
| 5.9 | การค้นหาเว็บ | ใช้ความสามารถในการค้นหาเว็บ | [คู่มือ](./05-AdvancedTopics/web-search-mcp/README.md) |
| 5.10 | การสตรีมแบบเรียลไทม์ | สร้างฟังก์ชันการสตรีมแบบเรียลไทม์ | [คู่มือ](./05-AdvancedTopics/mcp-realtimestreaming/README.md) |
| 5.11 | การค้นหาแบบเรียลไทม์ | ใช้การค้นหาแบบเรียลไทม์ | [คู่มือ](./05-AdvancedTopics/mcp-realtimesearch/README.md) |
| 5.12 | การยืนยันตัวตน Entra ID | การยืนยันตัวตนด้วย Microsoft Entra ID | [คู่มือ](./05-AdvancedTopics/mcp-security-entra/README.md) |
| 5.13 | การรวม Foundry | การรวมกับ Azure AI Foundry | [คู่มือ](./05-AdvancedTopics/mcp-foundry-agent-integration/README.md) |
| 5.14 | การออกแบบ Context | เทคนิคสำหรับการออกแบบ context ที่มีประสิทธิภาพ | [คู่มือ](./05-AdvancedTopics/mcp-contextengineering/README.md) |
| 5.15 | MCP Custom Transport | การใช้งาน Custom Transport | [คู่มือ](./05-AdvancedTopics/mcp-transport/README.md) |
| **โมดูล 6-10: ชุมชนและแนวปฏิบัติที่ดีที่สุด** | | | |
| 06 | การมีส่วนร่วมในชุมชน | วิธีการมีส่วนร่วมในระบบนิเวศ MCP | [คู่มือ](./06-CommunityContributions/README.md) |
| 07 | ข้อมูลเชิงลึกจากการใช้งานในช่วงแรก | เรื่องราวการใช้งานจริง | [คู่มือ](./07-LessonsFromEarlyAdoption/README.md) |
| 08 | แนวปฏิบัติที่ดีที่สุดสำหรับ MCP | ประสิทธิภาพ, ความทนทานต่อข้อผิดพลาด, ความยืดหยุ่น | [คู่มือ](./08-BestPractices/README.md) |
| 09 | กรณีศึกษา MCP | ตัวอย่างการใช้งานจริง | [คู่มือ](./09-CaseStudy/README.md) |
| 10 | เวิร์กช็อปแบบลงมือทำ | สร้างเซิร์ฟเวอร์ MCP ด้วย AI Toolkit | [ห้องปฏิบัติการ](./10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/README.md) |
| **โมดูล 11: ห้องปฏิบัติการ MCP Server** | | | |
| 11 | การรวมฐานข้อมูล MCP Server | เส้นทางการเรียนรู้แบบลงมือทำ 13 ห้องปฏิบัติการสำหรับการรวม PostgreSQL | [ห้องปฏิบัติการ](./11-MCPServerHandsOnLabs/README.md) |
| 11.1 | บทนำ | ภาพรวมของ MCP พร้อมการรวมฐานข้อมูลและกรณีการใช้งานการวิเคราะห์การค้าปลีก | [Lab 00](./11-MCPServerHandsOnLabs/00-Introduction/README.md) |
| 11.2 | สถาปัตยกรรมหลัก | ทำความเข้าใจสถาปัตยกรรมเซิร์ฟเวอร์ MCP ชั้นฐานข้อมูล และรูปแบบความปลอดภัย | [Lab 01](./11-MCPServerHandsOnLabs/01-Architecture/README.md) |
| 11.3 | ความปลอดภัยและการใช้งานหลายผู้เช่า | Row Level Security, การยืนยันตัวตน และการเข้าถึงข้อมูลหลายผู้เช่า | [Lab 02](./11-MCPServerHandsOnLabs/02-Security/README.md) |
| 11.4 | การตั้งค่าสภาพแวดล้อม | การตั้งค่าสภาพแวดล้อมการพัฒนา Docker, ทรัพยากร Azure | [Lab 03](./11-MCPServerHandsOnLabs/03-Setup/README.md) |
| 11.5 | การออกแบบฐานข้อมูล | การตั้งค่า PostgreSQL, การออกแบบ schema การค้าปลีก และข้อมูลตัวอย่าง | [Lab 04](./11-MCPServerHandsOnLabs/04-Database/README.md) |
| 11.6 | การใช้งานเซิร์ฟเวอร์ MCP | สร้างเซิร์ฟเวอร์ FastMCP พร้อมการรวมฐานข้อมูล | [Lab 05](./11-MCPServerHandsOnLabs/05-MCP-Server/README.md) |
| 11.7 | การพัฒนาเครื่องมือ | สร้างเครื่องมือสอบถามฐานข้อมูลและการตรวจสอบ schema | [Lab 06](./11-MCPServerHandsOnLabs/06-Tools/README.md) |
| 11.8 | การค้นหาเชิงความหมาย | ใช้ vector embeddings กับ Azure OpenAI และ pgvector | [Lab 07](./11-MCPServerHandsOnLabs/07-Semantic-Search/README.md) |
| 11.9 | การทดสอบและการดีบัก | กลยุทธ์การทดสอบ เครื่องมือดีบัก และวิธีการตรวจสอบ | [Lab 08](./11-MCPServerHandsOnLabs/08-Testing/README.md) |
| 11.10 | การรวม VS Code | การตั้งค่า VS Code MCP integration และการใช้งาน AI Chat | [Lab 09](./11-MCPServerHandsOnLabs/09-VS-Code/README.md) |
| 11.11 | กลยุทธ์การปรับใช้ | การปรับใช้ Docker, Azure Container Apps และการพิจารณาการขยายขนาด | [Lab 10](./11-MCPServerHandsOnLabs/10-Deployment/README.md) |
| 11.12 | การตรวจสอบ | Application Insights, การบันทึก, การตรวจสอบประสิทธิภาพ | [Lab 11](./11-MCPServerHandsOnLabs/11-Monitoring/README.md) |
| 11.13 | แนวปฏิบัติที่ดีที่สุด | การปรับปรุงประสิทธิภาพ, การเพิ่มความปลอดภัย, และเคล็ดลับการใช้งานจริง | [Lab 12](./11-MCPServerHandsOnLabs/12-Best-Practices/README.md) |

### 💻 โครงการตัวอย่างโค้ด

หนึ่งในส่วนที่น่าตื่นเต้นที่สุดของการเรียนรู้ MCP คือการเห็นทักษะการเขียนโค้ดของคุณพัฒนาขึ้นอย่างต่อเนื่อง เราออกแบบตัวอย่างโค้ดของเราให้เริ่มต้นง่ายและซับซ้อนขึ้นเมื่อความเข้าใจของคุณลึกซึ้งขึ้น นี่คือวิธีที่เราแนะนำแนวคิด - ด้วยโค้ดที่เข้าใจง่ายแต่แสดงหลักการ MCP จริง คุณจะเข้าใจไม่เพียงแค่ว่าโค้ดนี้ทำอะไร แต่ทำไมมันถึงมีโครงสร้างแบบนี้ และมันเข้ากับแอปพลิเคชัน MCP ขนาดใหญ่ได้อย่างไร

#### ตัวอย่าง MCP Calculator พื้นฐาน

| ภาษา | คำอธิบาย | ลิงก์ |
|------|----------|-------|
| C# | ตัวอย่างเซิร์ฟเวอร์ MCP | [ดูโค้ด](./03-GettingStarted/samples/csharp/README.md) |
| Java | MCP Calculator | [ดูโค้ด](./03-GettingStarted/samples/java/calculator/README.md) |
| JavaScript | MCP Demo | [ดูโค้ด](./03-GettingStarted/samples/javascript/README.md) |
| Python | เซิร์ฟเวอร์ MCP | [ดูโค้ด](../../03-GettingStarted/samples/python/mcp_calculator_server.py) |
| TypeScript | ตัวอย่าง MCP | [ดูโค้ด](./03-GettingStarted/samples/typescript/README.md) |
| Rust | ตัวอย่าง MCP | [ดูโค้ด](./03-GettingStarted/samples/rust/README.md) |

#### การใช้งาน MCP ขั้นสูง

| ภาษา | คำอธิบาย | ลิงก์ |
|------|----------|-------|
| C# | ตัวอย่างขั้นสูง | [ดูโค้ด](./04-PracticalImplementation/samples/csharp/README.md) |
| Java with Spring | ตัวอย่าง Container App | [ดูโค้ด](./04-PracticalImplementation/samples/java/containerapp/README.md) |
| JavaScript | ตัวอย่างขั้นสูง | [ดูโค้ด](./04-PracticalImplementation/samples/javascript/README.md) |
| Python | การใช้งานที่ซับซ้อน | [ดูโค้ด](../../04-PracticalImplementation/samples/python/READMEmd) |
| TypeScript | ตัวอย่าง Container | [ดูโค้ด](./04-PracticalImplementation/samples/typescript/README.md) |

## 🎯 ความต้องการเบื้องต้นสำหรับการเรียนรู้ MCP

เพื่อให้ได้ประโยชน์สูงสุดจากหลักสูตรนี้ คุณควรมี:

- ความรู้พื้นฐานเกี่ยวกับการเขียนโปรแกรมในภาษาใดภาษาหนึ่งต่อไปนี้: C#, Java, JavaScript, Python หรือ TypeScript
- ความเข้าใจเกี่ยวกับโมเดลไคลเอนต์-เซิร์ฟเวอร์และ API
- ความคุ้นเคยกับแนวคิด REST และ HTTP
- (ตัวเลือก) พื้นฐานในแนวคิด AI/ML

- เข้าร่วมการสนทนาในชุมชนของเราเพื่อรับการสนับสนุน

## 📚 คู่มือการศึกษาและทรัพยากร

ที่เก็บนี้รวมทรัพยากรหลายอย่างเพื่อช่วยให้คุณนำทางและเรียนรู้ได้อย่างมีประสิทธิภาพ:

### คู่มือการศึกษา

[คู่มือการศึกษา](./study_guide.md) ที่ครอบคลุมมีให้เพื่อช่วยให้คุณนำทางที่เก็บนี้ได้อย่างมีประสิทธิภาพ แผนภาพหลักสูตรที่แสดงภาพแสดงให้เห็นว่าหัวข้อทั้งหมดเชื่อมโยงกันอย่างไร และให้คำแนะนำเกี่ยวกับวิธีการใช้โครงการตัวอย่างอย่างมีประสิทธิภาพ โดยเฉพาะอย่างยิ่งมีประโยชน์หากคุณเป็นผู้เรียนที่ชอบเห็นภาพรวม

คู่มือประกอบด้วย:
- แผนภาพหลักสูตรที่แสดงภาพหัวข้อทั้งหมดที่ครอบคลุม
- การแบ่งรายละเอียดของแต่ละส่วนในที่เก็บ
- คำแนะนำเกี่ยวกับวิธีการใช้โครงการตัวอย่าง
- เส้นทางการเรียนรู้ที่แนะนำสำหรับระดับทักษะต่างๆ
- ทรัพยากรเพิ่มเติมเพื่อเสริมการเรียนรู้ของคุณ

### Changelog

เรารักษา [Changelog](./changelog.md) ที่ละเอียดซึ่งติดตามการอัปเดตที่สำคัญทั้งหมดในวัสดุหลักสูตร เพื่อให้คุณทันสมัยกับการปรับปรุงและการเพิ่มใหม่ล่าสุด
- การเพิ่มเนื้อหาใหม่
- การเปลี่ยนแปลงโครงสร้าง
- การปรับปรุงฟีเจอร์
- การอัปเดตเอกสาร

## 🛠️ วิธีการใช้หลักสูตรนี้อย่างมีประสิทธิภาพ

แต่ละบทเรียนในคู่มือนี้ประกอบด้วย:

1. คำอธิบายที่ชัดเจนเกี่ยวกับแนวคิด MCP  
2. ตัวอย่างโค้ดสดในหลายภาษา  
3. แบบฝึกหัดเพื่อสร้างแอปพลิเคชัน MCP จริง  
4. ทรัพยากรเพิ่มเติมสำหรับผู้เรียนขั้นสูง  

## เนื้อหาตามความต้องการ 

### [MCP Dev Days กรกฎาคม 2025](https://developer.microsoft.com/en-us/reactor/series/S-1563/)
#### [➡️รับชมตามความต้องการ - MCP Dev Days](https://developer.microsoft.com/en-us/reactor/series/S-1563/)
เตรียมพร้อมสำหรับสองวันของข้อมูลเชิงลึกทางเทคนิคที่ลึกซึ้ง การเชื่อมต่อชุมชน และการเรียนรู้แบบลงมือทำที่ MCP Dev Days งานเสมือนจริงที่อุทิศให้กับ Model Context Protocol (MCP) — มาตรฐานที่เกิดขึ้นใหม่ที่เชื่อมโยงโมเดล AI และเครื่องมือที่พวกมันพึ่งพา
คุณสามารถรับชม MCP Dev Days ได้โดยการลงทะเบียนที่หน้าอีเวนต์ของเรา: https://aka.ms/mcpdevdays

#### [วันแรก: MCP Productivity, DevTools, & Community:](https://developer.microsoft.com/en-us/reactor/series/S-1563/)

เน้นการเพิ่มพลังให้กับนักพัฒนาในการใช้ MCP ในกระบวนการพัฒนา และเฉลิมฉลองชุมชน MCP ที่ยอดเยี่ยม เราจะมีสมาชิกชุมชนและพันธมิตร เช่น Arcade, Block, Okta และ Neon มาร่วมแบ่งปันวิธีการที่พวกเขาร่วมมือกับ Microsoft เพื่อสร้างระบบนิเวศ MCP ที่เปิดกว้างและขยายได้ เดโมจากโลกจริงใน VS Code, Visual Studio, GitHub Copilot และเครื่องมือชุมชนยอดนิยม
เวิร์กโฟลว์การพัฒนาที่ใช้งานได้จริงและมีบริบท
เซสชันที่นำโดยชุมชนและข้อมูลเชิงลึก
ไม่ว่าคุณจะเพิ่งเริ่มต้นกับ MCP หรือกำลังสร้างด้วยมัน วันแรกจะเป็นการเริ่มต้นที่เต็มไปด้วยแรงบันดาลใจและสิ่งที่นำไปใช้ได้จริง

#### [วันที่สอง: สร้าง MCP Servers ด้วยความมั่นใจ](https://developer.microsoft.com/en-us/reactor/series/S-1563/)

สำหรับผู้สร้าง MCP เราจะเจาะลึกกลยุทธ์การดำเนินการและแนวทางปฏิบัติที่ดีที่สุดในการสร้าง MCP servers และการผสาน MCP เข้ากับเวิร์กโฟลว์ AI ของคุณ

#### หัวข้อที่ครอบคลุม:

- การสร้าง MCP Servers และการผสานเข้ากับประสบการณ์ของเอเจนต์
- การพัฒนาที่ขับเคลื่อนด้วยคำสั่ง (Prompt-driven development)
- แนวทางปฏิบัติที่ดีที่สุดด้านความปลอดภัย
- การใช้ส่วนประกอบพื้นฐาน เช่น Functions, ACA และ API Management
- การจัดแนว Registry และเครื่องมือ (1P + 3P)

หากคุณเป็นนักพัฒนา ผู้สร้างเครื่องมือ หรือผู้วางกลยุทธ์ผลิตภัณฑ์ AI วันนี้เต็มไปด้วยข้อมูลเชิงลึกที่คุณต้องการเพื่อสร้างโซลูชัน MCP ที่ขยายได้ ปลอดภัย และพร้อมสำหรับอนาคต

### MCP Boot Camp สิงหาคม 2025
เรียนรู้ผ่านวิดีโอเซสชันเข้มข้นเกี่ยวกับวิธีการสร้าง MCP servers การผสานรวมกับ VS Code และการปรับใช้ใน Azure อย่างมืออาชีพ โดยอ้างอิงจากเนื้อหาหลักสูตร MCP สำหรับผู้เริ่มต้น ออกไปพร้อมกับทักษะที่ใช้งานได้จริงในเทคโนโลยีที่บริษัทใหญ่ๆ กำลังใช้งานอยู่

#### [➡️รับชม MCP Bootcamp ตามความต้องการ | ภาษาอังกฤษ](https://developer.microsoft.com/en-us/reactor/series/s-1568/)
#### [➡️รับชม MCP Bootcamp ตามความต้องการ | ภาษาโปรตุเกส](https://developer.microsoft.com/en-us/reactor/series/S-1566/)
#### [➡️รับชม MCP Bootcamp ตามความต้องการ | ภาษาสเปน](https://developer.microsoft.com/en-us/reactor/series/S-1567/)

### เรียนรู้ MCP กับ C# - ชุดบทเรียน
มาทำความรู้จักกับ Model Context Protocol (MCP) ซึ่งเป็นกรอบการทำงานที่ล้ำสมัยที่ออกแบบมาเพื่อมาตรฐานการโต้ตอบระหว่างโมเดล AI และแอปพลิเคชันของลูกค้า ผ่านเซสชันที่เหมาะสำหรับผู้เริ่มต้น เราจะนำคุณเข้าสู่ MCP และแนะนำวิธีการสร้าง MCP server แรกของคุณ
#### C#: [https://aka.ms/letslearnmcp-csharp](https://aka.ms/letslearnmcp-csharp)
#### Java: [https://aka.ms/letslearnmcp-java](https://aka.ms/letslearnmcp-java)
#### JavaScript: [https://aka.ms/letslearnmcp-javascript](https://aka.ms/letslearnmcp-javascript)
#### Python: [https://aka.ms/letslearnmcp-python](https://aka.ms/letslearnmcp-python)

## 🎓 การเดินทางของคุณกับ MCP เริ่มต้นแล้ว

ขอแสดงความยินดี! คุณได้เริ่มต้นการเดินทางที่น่าตื่นเต้นซึ่งจะขยายขีดความสามารถในการเขียนโปรแกรมของคุณและเชื่อมโยงคุณกับการพัฒนา AI ที่ล้ำสมัย

### สิ่งที่คุณได้ทำสำเร็จแล้ว

โดยการอ่านบทนำนี้ คุณได้เริ่มสร้างพื้นฐานความรู้เกี่ยวกับ MCP แล้ว คุณเข้าใจว่า MCP คืออะไร ทำไมมันถึงสำคัญ และหลักสูตรนี้จะสนับสนุนการเรียนรู้ของคุณอย่างไร นี่เป็นความสำเร็จที่สำคัญและเป็นจุดเริ่มต้นของความเชี่ยวชาญในเทคโนโลยีที่สำคัญนี้

### การผจญภัยที่รออยู่

เมื่อคุณก้าวผ่านโมดูลต่างๆ จำไว้ว่าผู้เชี่ยวชาญทุกคนเคยเป็นมือใหม่มาก่อน แนวคิดที่อาจดูซับซ้อนในตอนนี้จะกลายเป็นเรื่องธรรมดาเมื่อคุณฝึกฝนและนำไปใช้ แต่ละก้าวเล็กๆ จะสร้างความสามารถที่ทรงพลังซึ่งจะเป็นประโยชน์ต่อคุณตลอดอาชีพการพัฒนา

### เครือข่ายสนับสนุนของคุณ

คุณกำลังเข้าร่วมชุมชนของผู้เรียนและผู้เชี่ยวชาญที่หลงใหลใน MCP และกระตือรือร้นที่จะช่วยเหลือผู้อื่นให้ประสบความสำเร็จ ไม่ว่าคุณจะติดปัญหาในการเขียนโค้ดหรืออยากแบ่งปันความสำเร็จ ชุมชนนี้พร้อมที่จะสนับสนุนการเดินทางของคุณ

หากคุณติดขัดหรือมีคำถามเกี่ยวกับการสร้างแอป AI เข้าร่วมการสนทนากับผู้เรียนและนักพัฒนาที่มีประสบการณ์เกี่ยวกับ MCP นี่คือชุมชนที่สนับสนุนซึ่งยินดีต้อนรับคำถามและแบ่งปันความรู้กันอย่างอิสระ

[![Azure AI Foundry Discord](https://img.shields.io/badge/Discord-Azure_AI_Foundry_Community_Discord-blue?style=for-the-badge&logo=discord&color=5865f2&logoColor=fff)](https://aka.ms/foundry/discord)

หากคุณมีข้อเสนอแนะเกี่ยวกับผลิตภัณฑ์หรือพบข้อผิดพลาดขณะสร้าง โปรดเยี่ยมชม:

[![Azure AI Foundry Developer Forum](https://img.shields.io/badge/GitHub-Azure_AI_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

### พร้อมเริ่มต้นหรือยัง?

การผจญภัย MCP ของคุณเริ่มต้นแล้ว! เริ่มต้นด้วย Module 0 เพื่อเข้าสู่ประสบการณ์ MCP ครั้งแรกของคุณ หรือสำรวจโปรเจกต์ตัวอย่างเพื่อดูสิ่งที่คุณจะสร้าง จำไว้ว่า - ผู้เชี่ยวชาญทุกคนเริ่มต้นจากจุดที่คุณอยู่ตอนนี้ และด้วยความอดทนและการฝึกฝน คุณจะประหลาดใจกับสิ่งที่คุณสามารถทำได้

ยินดีต้อนรับสู่โลกของการพัฒนา Model Context Protocol มาสร้างสิ่งที่น่าทึ่งไปด้วยกัน!

## 🤝 การมีส่วนร่วมในชุมชนการเรียนรู้

หลักสูตรนี้จะเติบโตแข็งแกร่งขึ้นด้วยการมีส่วนร่วมจากผู้เรียนเช่นคุณ! ไม่ว่าคุณจะช่วยแก้ไขคำผิด แนะนำคำอธิบายที่ชัดเจนขึ้น หรือเพิ่มตัวอย่างใหม่ การมีส่วนร่วมของคุณช่วยให้ผู้เริ่มต้นคนอื่นๆ ประสบความสำเร็จ

ขอขอบคุณ Microsoft Valued Professional [Shivam Goyal](https://www.linkedin.com/in/shivam2003/) สำหรับการมีส่วนร่วมในตัวอย่างโค้ด

กระบวนการมีส่วนร่วมถูกออกแบบมาให้เป็นมิตรและสนับสนุน การมีส่วนร่วมส่วนใหญ่ต้องการข้อตกลงใบอนุญาตผู้มีส่วนร่วม (CLA) แต่เครื่องมืออัตโนมัติจะนำคุณผ่านกระบวนการได้อย่างราบรื่น

## 📜 การเรียนรู้แบบโอเพ่นซอร์ส

หลักสูตรทั้งหมดนี้มีให้ภายใต้ MIT [LICENSE](../../LICENSE) หมายความว่าคุณสามารถใช้ ปรับเปลี่ยน และแบ่งปันได้อย่างอิสระ สิ่งนี้สนับสนุนภารกิจของเราในการทำให้ความรู้ MCP เข้าถึงได้สำหรับนักพัฒนาทุกคน

## 🤝 แนวทางการมีส่วนร่วม

โปรเจกต์นี้ยินดีต้อนรับการมีส่วนร่วมและข้อเสนอแนะ การมีส่วนร่วมส่วนใหญ่ต้องการให้คุณตกลงกับ
Contributor License Agreement (CLA) ซึ่งระบุว่าคุณมีสิทธิ์และจริงๆ แล้วให้สิทธิ์เรา
ในการใช้การมีส่วนร่วมของคุณ สำหรับรายละเอียดเพิ่มเติม โปรดเยี่ยมชม <https://cla.opensource.microsoft.com>

เมื่อคุณส่ง pull request CLA bot จะตรวจสอบโดยอัตโนมัติว่าคุณต้องให้
CLA หรือไม่ และตกแต่ง PR อย่างเหมาะสม (เช่น การตรวจสอบสถานะ ความคิดเห็น) เพียงทำตามคำแนะนำ
ที่ bot ให้ คุณจะต้องทำสิ่งนี้เพียงครั้งเดียวสำหรับทุก repo ที่ใช้ CLA ของเรา

โปรเจกต์นี้ได้นำ [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/) มาใช้
สำหรับข้อมูลเพิ่มเติม ดูที่ [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) หรือ
ติดต่อ [opencode@microsoft.com](mailto:opencode@microsoft.com) หากมีคำถามหรือความคิดเห็นเพิ่มเติม

---

*พร้อมเริ่มต้นการเดินทาง MCP ของคุณหรือยัง? เริ่มต้นด้วย [Module 00 - Introduction to MCP](./00-Introduction/README.md) และก้าวแรกเข้าสู่โลกของการพัฒนา Model Context Protocol!*

## 🎒 หลักสูตรอื่นๆ
ทีมของเราผลิตหลักสูตรอื่นๆ ด้วย! ลองดู:

### Azure / Edge / MCP / Agents
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### Generative AI Series
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---

### หลักสูตรพื้นฐาน
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### Copilot Series
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot สำหรับ C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)  
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)  
<!-- สิ้นสุดคอร์สอื่นๆ ของ CO-OP TRANSLATOR -->

---

**ข้อจำกัดความรับผิดชอบ**:  
เอกสารนี้ได้รับการแปลโดยใช้บริการแปลภาษา AI [Co-op Translator](https://github.com/Azure/co-op-translator) แม้ว่าเราจะพยายามให้การแปลมีความถูกต้อง แต่โปรดทราบว่าการแปลอัตโนมัติอาจมีข้อผิดพลาดหรือความไม่ถูกต้อง เอกสารต้นฉบับในภาษาดั้งเดิมควรถือเป็นแหล่งข้อมูลที่เชื่อถือได้ สำหรับข้อมูลที่สำคัญ ขอแนะนำให้ใช้บริการแปลภาษามืออาชีพ เราจะไม่รับผิดชอบต่อความเข้าใจผิดหรือการตีความผิดที่เกิดจากการใช้การแปลนี้