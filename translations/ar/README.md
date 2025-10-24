<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "56ad2bfef916cebf4443ef2d620d06e5",
  "translation_date": "2025-10-24T08:51:15+00:00",
  "source_file": "README.md",
  "language_code": "ar"
}
-->
![MCP-for-beginners](../../translated_images/mcp-beginners.2ce2b317996369ff66c5b72e25eff9d4288ab2741fc70c0b4e523d1ae1e249fd.ar.png)

[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/graphs/contributors)  
[![GitHub issues](https://img.shields.io/github/issues/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/issues)  
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/pulls)  
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/mcp-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/mcp-for-beginners/watchers)  
[![GitHub forks](https://img.shields.io/github/forks/microsoft/mcp-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/mcp-for-beginners/fork)  
[![GitHub stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners?style=social&label=Star)](https://GitHub.com/microsoft/mcp-for-beginners/stargazers)

[![Microsoft Azure AI Foundry Discord](https://dcbadge.limes.pink/api/server/ByRwuEEgH4)](https://discord.com/invite/ByRwuEEgH4)

اتبع هذه الخطوات للبدء باستخدام هذه الموارد:  
1. **قم بعمل Fork للمستودع**: اضغط [![GitHub forks](https://img.shields.io/github/forks/microsoft/mcp-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/mcp-for-beginners/fork)  
2. **قم باستنساخ المستودع**: `git clone https://github.com/microsoft/mcp-for-beginners.git`  
3. [**انضم إلى مجتمع Azure AI Foundry على Discord وتواصل مع الخبراء والمطورين الآخرين**](https://discord.com/invite/ByRwuEEgH4)

### 🌐 دعم متعدد اللغات

#### مدعوم عبر GitHub Action (تلقائي ودائم التحديث)

[Arabic](./README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

# 🚀 منهج بروتوكول سياق النموذج (MCP) للمبتدئين

## **تعلم MCP من خلال أمثلة عملية في C#، Java، JavaScript، Rust، Python، وTypeScript**

## 🧠 نظرة عامة على منهج بروتوكول سياق النموذج  
مرحبًا بك في رحلتك لاستكشاف بروتوكول سياق النموذج! إذا كنت قد تساءلت يومًا كيف تتواصل تطبيقات الذكاء الاصطناعي مع الأدوات والخدمات المختلفة، فأنت على وشك اكتشاف الحل الأنيق الذي يغير طريقة بناء المطورين لأنظمة ذكية.

فكر في MCP كأنه مترجم عالمي لتطبيقات الذكاء الاصطناعي - تمامًا مثلما تسمح منافذ USB بتوصيل أي جهاز بجهاز الكمبيوتر الخاص بك، يسمح MCP لنماذج الذكاء الاصطناعي بالاتصال بأي أداة أو خدمة بطريقة موحدة. سواء كنت تبني أول روبوت دردشة لك أو تعمل على تدفقات عمل ذكاء اصطناعي معقدة، فإن فهم MCP سيمنحك القدرة على إنشاء تطبيقات أكثر قدرة ومرونة.

تم تصميم هذا المنهج بعناية وصبر لرحلتك التعليمية. سنبدأ بمفاهيم بسيطة تفهمها بالفعل ونبني خبرتك تدريجيًا من خلال ممارسة عملية بلغتك البرمجية المفضلة. كل خطوة تتضمن تفسيرات واضحة، أمثلة عملية، والكثير من التشجيع على طول الطريق.

بحلول الوقت الذي تنهي فيه هذه الرحلة، ستشعر بالثقة لبناء خوادم MCP الخاصة بك، دمجها مع منصات الذكاء الاصطناعي الشهيرة، وفهم كيف تعيد هذه التقنية تشكيل مستقبل تطوير تطبيقات الذكاء الاصطناعي. لنبدأ هذه المغامرة المثيرة معًا!

### الوثائق الرسمية والمواصفات

تصبح هذه الموارد أكثر قيمة مع تقدم فهمك، لكن لا تشعر بالضغط لقراءتها كلها فورًا. ابدأ بالمجالات التي تثير اهتمامك أكثر!  
- 📘 [وثائق MCP](https://modelcontextprotocol.io/) – هذا هو المورد الأساسي الخاص بك للحصول على دروس خطوة بخطوة وأدلة المستخدم. الوثائق مكتوبة مع مراعاة المبتدئين، وتوفر أمثلة واضحة يمكنك اتباعها بسهولة.  
- 📜 [مواصفات MCP](https://modelcontextprotocol.io/docs/) – فكر في هذا كدليل مرجعي شامل. أثناء تقدمك في المنهج، ستجد نفسك تعود هنا للبحث عن تفاصيل محددة واستكشاف الميزات المتقدمة.  
- 📜 [المواصفات الأصلية لـ MCP](https://spec.modelcontextprotocol.io/) – تحتوي على تفاصيل تقنية إضافية يمكن أن تكون مفيدة للتطبيقات المتقدمة. إنها موجودة عندما تحتاج إليها، لكن لا تقلق بشأنها عندما تبدأ.  
- 🧑‍💻 [مستودع MCP على GitHub](https://github.com/modelcontextprotocol) – هنا ستجد SDKs، أدوات، وأمثلة برمجية بلغات برمجة متعددة. إنه مثل كنز مليء بالأمثلة العملية والمكونات الجاهزة للاستخدام.  
- 🌐 [مجتمع MCP](https://github.com/orgs/modelcontextprotocol/discussions) – انضم إلى المتعلمين الآخرين والمطورين ذوي الخبرة في مناقشات حول MCP. إنه مجتمع داعم حيث يتم الترحيب بالأسئلة ومشاركة المعرفة بحرية.

## أهداف التعلم

بحلول نهاية هذا المنهج، ستشعر بالثقة والحماس بشأن قدراتك الجديدة. إليك ما ستحققه:

• **فهم أساسيات MCP**: ستتعرف على ما هو بروتوكول سياق النموذج ولماذا يغير طريقة عمل تطبيقات الذكاء الاصطناعي معًا، باستخدام أمثلة وتشبيهات تجعل الأمور واضحة.  

• **بناء أول خادم MCP خاص بك**: ستقوم بإنشاء خادم MCP يعمل بلغتك البرمجية المفضلة، بدءًا من أمثلة بسيطة وتنمية مهاراتك خطوة بخطوة.  

• **ربط نماذج الذكاء الاصطناعي بالأدوات الحقيقية**: ستتعلم كيفية سد الفجوة بين نماذج الذكاء الاصطناعي والخدمات الفعلية، مما يمنح تطبيقاتك قدرات جديدة قوية.  

• **تنفيذ أفضل ممارسات الأمان**: ستفهم كيفية الحفاظ على أمان تطبيقات MCP الخاصة بك، وحماية كل من تطبيقاتك ومستخدميك.  

• **النشر بثقة**: ستعرف كيفية نقل مشاريع MCP الخاصة بك من التطوير إلى الإنتاج، باستخدام استراتيجيات نشر عملية تعمل في العالم الحقيقي.  

• **الانضمام إلى مجتمع MCP**: ستصبح جزءًا من مجتمع متنامٍ من المطورين الذين يشكلون مستقبل تطوير تطبيقات الذكاء الاصطناعي.

## الخلفية الأساسية

قبل أن نتعمق في تفاصيل MCP، دعنا نتأكد من أنك تشعر بالراحة مع بعض المفاهيم الأساسية. لا تقلق إذا لم تكن خبيرًا في هذه المجالات - سنشرح كل ما تحتاج إلى معرفته أثناء تقدمنا!

### فهم البروتوكولات (الأساس)

فكر في البروتوكول كأنه قواعد للمحادثة. عندما تتصل بصديق، كلاكما يعرف أن يقول "مرحبًا" عند الإجابة، يأخذ دوره في الحديث، ويقول "وداعًا" عند الانتهاء. تحتاج البرامج إلى قواعد مشابهة للتواصل بشكل فعال.

MCP هو بروتوكول - مجموعة من القواعد المتفق عليها التي تساعد نماذج الذكاء الاصطناعي والتطبيقات على إجراء "محادثات" منتجة مع الأدوات والخدمات. تمامًا مثلما تجعل قواعد المحادثة التواصل البشري أكثر سلاسة، يجعل MCP التواصل بين تطبيقات الذكاء الاصطناعي أكثر موثوقية وقوة.

### علاقات العميل والخادم (كيف تعمل البرامج معًا)

أنت بالفعل تستخدم علاقات العميل والخادم كل يوم! عندما تستخدم متصفح ويب (العميل) لزيارة موقع ويب، فأنت تتصل بخادم ويب يرسل لك محتوى الصفحة. يعرف المتصفح كيفية طلب المعلومات، ويعرف الخادم كيفية الرد.

في MCP، لدينا علاقة مشابهة: نماذج الذكاء الاصطناعي تعمل كعملاء يطلبون معلومات أو إجراءات، بينما توفر خوادم MCP تلك القدرات. إنه مثل وجود مساعد مفيد (الخادم) يمكن للنموذج أن يطلب منه أداء مهام محددة.

### لماذا يهم التوحيد القياسي (جعل الأشياء تعمل معًا)

تخيل لو أن كل مصنع سيارات استخدم أشكالًا مختلفة لمضخات الوقود - ستحتاج إلى محول مختلف لكل سيارة! التوحيد القياسي يعني الاتفاق على نهج مشترك بحيث تعمل الأشياء معًا بسلاسة.

يوفر MCP هذا التوحيد القياسي لتطبيقات الذكاء الاصطناعي. بدلًا من أن يحتاج كل نموذج ذكاء اصطناعي إلى كود مخصص للعمل مع كل أداة، ينشئ MCP طريقة عالمية للتواصل. هذا يعني أن المطورين يمكنهم بناء الأدوات مرة واحدة وجعلها تعمل مع العديد من أنظمة الذكاء الاصطناعي المختلفة.

## 🧭 نظرة عامة على مسار التعلم الخاص بك

تم تصميم رحلتك مع MCP بعناية لبناء ثقتك ومهاراتك تدريجيًا. كل مرحلة تقدم مفاهيم جديدة مع تعزيز ما تعلمته بالفعل.

### 🌱 المرحلة التأسيسية: فهم الأساسيات (الوحدات 0-2)

هنا تبدأ مغامرتك! سنقدم لك مفاهيم MCP باستخدام تشبيهات مألوفة وأمثلة بسيطة. ستفهم ما هو MCP، لماذا يوجد، وكيف يتناسب مع العالم الأكبر لتطوير الذكاء الاصطناعي.

• **الوحدة 0 - مقدمة إلى MCP**: سنبدأ باستكشاف ما هو MCP ولماذا هو مهم جدًا لتطبيقات الذكاء الاصطناعي الحديثة. سترى أمثلة واقعية لـ MCP أثناء العمل وتفهم كيف يحل المشكلات الشائعة التي يواجهها المطورون.  

• **الوحدة 1 - شرح المفاهيم الأساسية**: هنا ستتعلم اللبنات الأساسية لـ MCP. سنستخدم الكثير من التشبيهات والأمثلة المرئية للتأكد من أن هذه المفاهيم تبدو طبيعية ومفهومة.  

• **الوحدة 2 - الأمان في MCP**: قد يبدو الأمان مخيفًا، لكننا سنوضح لك كيف يتضمن MCP ميزات أمان مدمجة وسنعلمك أفضل الممارسات التي تحمي تطبيقاتك من البداية.

### 🔨 مرحلة البناء: إنشاء أول تطبيقاتك (الوحدة 3)

الآن تبدأ المتعة الحقيقية! ستحصل على تجربة عملية في بناء خوادم وعملاء MCP حقيقيين. لا تقلق - سنبدأ ببساطة ونرشدك خلال كل خطوة.

تتضمن هذه الوحدة أدلة عملية متعددة تتيح لك الممارسة بلغتك البرمجية المفضلة. ستقوم بإنشاء أول خادم، بناء عميل للاتصال به، وحتى دمجه مع أدوات تطوير شهيرة مثل VS Code.

كل دليل يتضمن أمثلة كود كاملة، نصائح لحل المشكلات، وتفسيرات حول سبب اتخاذنا خيارات تصميم محددة. بحلول نهاية هذه المرحلة، سيكون لديك تطبيقات MCP تعمل وتفتخر بها!

### 🚀 مرحلة النمو: المفاهيم المتقدمة والتطبيق الواقعي (الوحدات 4-5)

مع إتقان الأساسيات، أنت جاهز لاستكشاف ميزات MCP الأكثر تطورًا. سنغطي استراتيجيات التنفيذ العملية، تقنيات تصحيح الأخطاء، ومواضيع متقدمة مثل دمج الذكاء الاصطناعي متعدد الوسائط.

ستتعلم أيضًا كيفية توسيع نطاق تطبيقات MCP الخاصة بك للاستخدام الإنتاجي ودمجها مع منصات السحابة مثل Azure. تعد هذه الوحداتك لبناء حلول MCP يمكنها التعامل مع متطلبات العالم الحقيقي.

### 🌟 مرحلة الإتقان: المجتمع والتخصص (الوحدات 6-11)
المرحلة النهائية تركز على الانضمام إلى مجتمع MCP والتخصص في المجالات التي تهمك أكثر. ستتعلم كيفية المساهمة في مشاريع MCP مفتوحة المصدر، تنفيذ أنماط المصادقة المتقدمة، وبناء حلول شاملة متكاملة مع قواعد البيانات.

يستحق الوحدة 11 ذكرًا خاصًا - إنها مسار تعليمي عملي يتضمن 13 مختبرًا يعلمك كيفية بناء خوادم MCP جاهزة للإنتاج مع تكامل PostgreSQL. إنها بمثابة مشروع نهائي يجمع كل ما تعلمته!

### 📚 هيكل المنهج الكامل

| الوحدة | الموضوع | الوصف | الرابط |
|--------|---------|-------|--------|
| **الوحدات 1-3: الأساسيات** | | | |
| 00 | مقدمة إلى MCP | نظرة عامة على بروتوكول Model Context وأهميته في خطوط أنابيب الذكاء الاصطناعي | [اقرأ المزيد](./00-Introduction/README.md) |
| 01 | شرح المفاهيم الأساسية | استكشاف معمق للمفاهيم الأساسية لـ MCP | [اقرأ المزيد](./01-CoreConcepts/README.md) |
| 02 | الأمان في MCP | تهديدات الأمان وأفضل الممارسات | [اقرأ المزيد](./02-Security/README.md) |
| 03 | البدء مع MCP | إعداد البيئة، الخوادم/العملاء الأساسية، التكامل | [اقرأ المزيد](./03-GettingStarted/README.md) |
| **الوحدة 3: بناء أول خادم وعميل** | | | |
| 3.1 | أول خادم | إنشاء أول خادم MCP | [دليل](./03-GettingStarted/01-first-server/README.md) |
| 3.2 | أول عميل | تطوير عميل MCP أساسي | [دليل](./03-GettingStarted/02-client/README.md) |
| 3.3 | عميل مع LLM | دمج نماذج اللغة الكبيرة | [دليل](./03-GettingStarted/03-llm-client/README.md) |
| 3.4 | تكامل VS Code | استخدام خوادم MCP في VS Code | [دليل](./03-GettingStarted/04-vscode/README.md) |
| 3.5 | خادم stdio | إنشاء خوادم باستخدام نقل stdio | [دليل](./03-GettingStarted/05-stdio-server/README.md) |
| 3.6 | بث HTTP | تنفيذ بث HTTP في MCP | [دليل](./03-GettingStarted/06-http-streaming/README.md) |
| 3.7 | أدوات الذكاء الاصطناعي | استخدام أدوات الذكاء الاصطناعي مع MCP | [دليل](./03-GettingStarted/07-aitk/README.md) |
| 3.8 | الاختبار | اختبار تنفيذ خادم MCP الخاص بك | [دليل](./03-GettingStarted/08-testing/README.md) |
| 3.9 | النشر | نشر خوادم MCP للإنتاج | [دليل](./03-GettingStarted/09-deployment/README.md) |
| 3.10 | استخدام الخادم المتقدم | استخدام الخوادم المتقدمة للحصول على ميزات متقدمة وتحسين الهيكلية | [دليل](./03-GettingStarted/10-advanced/README.md) |
| 3.11 | المصادقة البسيطة | فصل يوضح المصادقة من البداية وRBAC | [دليل](./03-GettingStarted/11-simple-auth/README.md) |
| **الوحدات 4-5: العملية والمتقدمة** | | | |
| 04 | التنفيذ العملي | SDKs، التصحيح، الاختبار، قوالب المطالبات القابلة لإعادة الاستخدام | [اقرأ المزيد](./04-PracticalImplementation/README.md) |
| 05 | مواضيع متقدمة في MCP | الذكاء الاصطناعي متعدد الوسائط، التوسع، الاستخدام المؤسسي | [اقرأ المزيد](./05-AdvancedTopics/README.md) |
| 5.1 | تكامل Azure | تكامل MCP مع Azure | [دليل](./05-AdvancedTopics/mcp-integration/README.md) |
| 5.2 | تعدد الوسائط | العمل مع وسائط متعددة | [دليل](./05-AdvancedTopics/mcp-multi-modality/README.md) |
| 5.3 | عرض OAuth2 | تنفيذ مصادقة OAuth2 | [دليل](./05-AdvancedTopics/mcp-oauth2-demo/README.md) |
| 5.4 | السياقات الجذرية | فهم وتنفيذ السياقات الجذرية | [دليل](./05-AdvancedTopics/mcp-root-contexts/README.md) |
| 5.5 | التوجيه | استراتيجيات التوجيه في MCP | [دليل](./05-AdvancedTopics/mcp-routing/README.md) |
| 5.6 | أخذ العينات | تقنيات أخذ العينات في MCP | [دليل](./05-AdvancedTopics/mcp-sampling/README.md) |
| 5.7 | التوسع | توسيع تنفيذات MCP | [دليل](./05-AdvancedTopics/mcp-scaling/README.md) |
| 5.8 | الأمان | اعتبارات الأمان المتقدمة | [دليل](./05-AdvancedTopics/mcp-security/README.md) |
| 5.9 | البحث على الويب | تنفيذ قدرات البحث على الويب | [دليل](./05-AdvancedTopics/web-search-mcp/README.md) |
| 5.10 | البث المباشر | بناء وظيفة البث المباشر | [دليل](./05-AdvancedTopics/mcp-realtimestreaming/README.md) |
| 5.11 | البحث المباشر | تنفيذ البحث المباشر | [دليل](./05-AdvancedTopics/mcp-realtimesearch/README.md) |
| 5.12 | مصادقة Entra ID | المصادقة باستخدام Microsoft Entra ID | [دليل](./05-AdvancedTopics/mcp-security-entra/README.md) |
| 5.13 | تكامل Foundry | التكامل مع Azure AI Foundry | [دليل](./05-AdvancedTopics/mcp-foundry-agent-integration/README.md) |
| 5.14 | هندسة السياق | تقنيات هندسة السياق الفعالة | [دليل](./05-AdvancedTopics/mcp-contextengineering/README.md) |
| 5.15 | نقل MCP المخصص | تنفيذات النقل المخصصة | [دليل](./05-AdvancedTopics/mcp-transport/README.md) |
| **الوحدات 6-10: المجتمع وأفضل الممارسات** | | | |
| 06 | مساهمات المجتمع | كيفية المساهمة في نظام MCP | [دليل](./06-CommunityContributions/README.md) |
| 07 | رؤى من التبني المبكر | قصص تنفيذ واقعية | [دليل](./07-LessonsFromEarlyAdoption/README.md) |
| 08 | أفضل الممارسات لـ MCP | الأداء، تحمل الأخطاء، المرونة | [دليل](./08-BestPractices/README.md) |
| 09 | دراسات حالة MCP | أمثلة تنفيذ عملية | [دليل](./09-CaseStudy/README.md) |
| 10 | ورشة عمل عملية | بناء خادم MCP باستخدام أدوات الذكاء الاصطناعي | [مختبر](./10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/README.md) |
| **الوحدة 11: مختبر عملي لخادم MCP** | | | |
| 11 | تكامل قاعدة بيانات خادم MCP | مسار تعليمي عملي شامل يتضمن 13 مختبرًا لتكامل PostgreSQL | [مختبرات](./11-MCPServerHandsOnLabs/README.md) |
| 11.1 | مقدمة | نظرة عامة على MCP مع تكامل قاعدة البيانات وحالة استخدام تحليلات البيع بالتجزئة | [مختبر 00](./11-MCPServerHandsOnLabs/00-Introduction/README.md) |
| 11.2 | الهيكل الأساسي | فهم هيكل خادم MCP، طبقات قاعدة البيانات، وأنماط الأمان | [مختبر 01](./11-MCPServerHandsOnLabs/01-Architecture/README.md) |
| 11.3 | الأمان وتعدد المستأجرين | أمان مستوى الصف، المصادقة، والوصول إلى بيانات متعددة المستأجرين | [مختبر 02](./11-MCPServerHandsOnLabs/02-Security/README.md) |
| 11.4 | إعداد البيئة | إعداد بيئة التطوير، Docker، موارد Azure | [مختبر 03](./11-MCPServerHandsOnLabs/03-Setup/README.md) |
| 11.5 | تصميم قاعدة البيانات | إعداد PostgreSQL، تصميم مخطط البيع بالتجزئة، والبيانات النموذجية | [مختبر 04](./11-MCPServerHandsOnLabs/04-Database/README.md) |
| 11.6 | تنفيذ خادم MCP | بناء خادم FastMCP مع تكامل قاعدة البيانات | [مختبر 05](./11-MCPServerHandsOnLabs/05-MCP-Server/README.md) |
| 11.7 | تطوير الأدوات | إنشاء أدوات استعلام قاعدة البيانات واستكشاف المخطط | [مختبر 06](./11-MCPServerHandsOnLabs/06-Tools/README.md) |
| 11.8 | البحث الدلالي | تنفيذ تضمينات المتجهات باستخدام Azure OpenAI وpgvector | [مختبر 07](./11-MCPServerHandsOnLabs/07-Semantic-Search/README.md) |
| 11.9 | الاختبار والتصحيح | استراتيجيات الاختبار، أدوات التصحيح، ونهج التحقق | [مختبر 08](./11-MCPServerHandsOnLabs/08-Testing/README.md) |
| 11.10 | تكامل VS Code | إعداد تكامل VS Code MCP واستخدام الدردشة الذكية | [مختبر 09](./11-MCPServerHandsOnLabs/09-VS-Code/README.md) |
| 11.11 | استراتيجيات النشر | نشر Docker، تطبيقات حاويات Azure، واعتبارات التوسع | [مختبر 10](./11-MCPServerHandsOnLabs/10-Deployment/README.md) |
| 11.12 | المراقبة | رؤى التطبيقات، تسجيل الأحداث، مراقبة الأداء | [مختبر 11](./11-MCPServerHandsOnLabs/11-Monitoring/README.md) |
| 11.13 | أفضل الممارسات | تحسين الأداء، تعزيز الأمان، ونصائح للإنتاج | [مختبر 12](./11-MCPServerHandsOnLabs/12-Best-Practices/README.md) |

### 💻 مشاريع أمثلة على الكود

واحدة من أكثر الأجزاء إثارة في تعلم MCP هي رؤية مهاراتك في البرمجة تتطور تدريجيًا. لقد صممنا أمثلة الكود لدينا لتكون بسيطة في البداية وتصبح أكثر تعقيدًا مع تعمق فهمك. نقدم المفاهيم بكود سهل الفهم ولكنه يظهر مبادئ MCP الحقيقية، لتفهم ليس فقط ما يفعله هذا الكود، ولكن لماذا تم هيكلته بهذه الطريقة وكيف يتناسب مع تطبيقات MCP الأكبر.

#### أمثلة أساسية لحاسبة MCP

| اللغة | الوصف | الرابط |
|-------|-------|--------|
| C# | مثال خادم MCP | [عرض الكود](./03-GettingStarted/samples/csharp/README.md) |
| Java | حاسبة MCP | [عرض الكود](./03-GettingStarted/samples/java/calculator/README.md) |
| JavaScript | عرض MCP | [عرض الكود](./03-GettingStarted/samples/javascript/README.md) |
| Python | خادم MCP | [عرض الكود](../../03-GettingStarted/samples/python/mcp_calculator_server.py) |
| TypeScript | مثال MCP | [عرض الكود](./03-GettingStarted/samples/typescript/README.md) |
| Rust | مثال MCP | [عرض الكود](./03-GettingStarted/samples/rust/README.md) |

#### تنفيذات MCP المتقدمة

| اللغة | الوصف | الرابط |
|-------|-------|--------|
| C# | مثال متقدم | [عرض الكود](./04-PracticalImplementation/samples/csharp/README.md) |
| Java مع Spring | مثال تطبيق الحاوية | [عرض الكود](./04-PracticalImplementation/samples/java/containerapp/README.md) |
| JavaScript | مثال متقدم | [عرض الكود](./04-PracticalImplementation/samples/javascript/README.md) |
| Python | تنفيذ معقد | [عرض الكود](../../04-PracticalImplementation/samples/python/READMEmd) |
| TypeScript | مثال الحاوية | [عرض الكود](./04-PracticalImplementation/samples/typescript/README.md) |

## 🎯 المتطلبات الأساسية لتعلم MCP

لتحقيق أقصى استفادة من هذا المنهج، يجب أن تكون لديك:

- معرفة أساسية بالبرمجة في واحدة على الأقل من اللغات التالية: C#، Java، JavaScript، Python، أو TypeScript  
- فهم لنموذج العميل-الخادم وواجهات برمجة التطبيقات  
- معرفة بمفاهيم REST وHTTP  
- (اختياري) خلفية في مفاهيم الذكاء الاصطناعي/التعلم الآلي  

- الانضمام إلى مناقشات المجتمع للحصول على الدعم  

## 📚 دليل الدراسة والموارد

يتضمن هذا المستودع العديد من الموارد لمساعدتك على التنقل والتعلم بفعالية:

### دليل الدراسة

يتوفر [دليل الدراسة](./study_guide.md) الشامل لمساعدتك على التنقل في هذا المستودع بفعالية. يعرض خريطة منهجية مرئية توضح كيفية ارتباط جميع المواضيع ويوفر إرشادات حول كيفية استخدام مشاريع الأمثلة بفعالية. إنه مفيد بشكل خاص إذا كنت متعلمًا بصريًا يحب رؤية الصورة الكبيرة.

يتضمن الدليل:
- خريطة منهجية مرئية توضح جميع المواضيع المغطاة  
- تفصيل دقيق لكل قسم في المستودع  
- إرشادات حول كيفية استخدام مشاريع الأمثلة  
- مسارات تعلم موصى بها لمستويات المهارة المختلفة  
- موارد إضافية لتكملة رحلة التعلم الخاصة بك  

### سجل التغييرات

نحافظ على [سجل التغييرات](./changelog.md) المفصل الذي يتتبع جميع التحديثات المهمة لمواد المنهج، حتى تتمكن من البقاء على اطلاع بأحدث التحسينات والإضافات.
- إضافات محتوى جديدة  
- تغييرات هيكلية  
- تحسينات الميزات  
- تحديثات الوثائق  

## 🛠️ كيفية استخدام هذا المنهج بفعالية

كل درس في هذا الدليل يتضمن:

1. تفسيرات واضحة لمفاهيم MCP  
2. أمثلة حية للكود بلغات متعددة  
3. تمارين لبناء تطبيقات MCP حقيقية  
4. موارد إضافية للمتعلمين المتقدمين  

## محتوى عند الطلب 

### [أيام مطوري MCP يوليو 2025](https://developer.microsoft.com/en-us/reactor/series/S-1563/)  
#### [➡️شاهد عند الطلب - أيام مطوري MCP](https://developer.microsoft.com/en-us/reactor/series/S-1563/)  
استعد ليومين من الرؤى التقنية العميقة، الاتصال المجتمعي، والتعلم العملي في أيام مطوري MCP، وهو حدث افتراضي مخصص لبروتوكول Model Context (MCP) - المعيار الناشئ الذي يربط بين نماذج الذكاء الاصطناعي والأدوات التي تعتمد عليها.
يمكنك مشاهدة أيام تطوير MCP من خلال التسجيل في صفحة الحدث الخاصة بنا: https://aka.ms/mcpdevdays.

#### [اليوم الأول: إنتاجية MCP، أدوات التطوير، والمجتمع:](https://developer.microsoft.com/en-us/reactor/series/S-1563/)

يهدف إلى تمكين المطورين من استخدام MCP في سير عملهم البرمجي والاحتفال بالمجتمع الرائع لـ MCP. سنكون برفقة أعضاء المجتمع وشركاء مثل Arcade، Block، Okta، وNeon لنرى كيف يتعاونون مع Microsoft لتشكيل نظام MCP مفتوح وقابل للتوسيع. 
عروض حية من العالم الحقيقي عبر VS Code، Visual Studio، GitHub Copilot، وأدوات المجتمع الشهيرة.
سير عمل برمجي عملي وموجه بالسياق.
جلسات بقيادة المجتمع ورؤى قيمة.
سواء كنت مبتدئًا في استخدام MCP أو تعمل بالفعل عليه، فإن اليوم الأول سيضع الأساس للإلهام والنصائح العملية.

#### [اليوم الثاني: بناء خوادم MCP بثقة](https://developer.microsoft.com/en-us/reactor/series/S-1563/)

مخصص لبناة MCP. سنغوص في استراتيجيات التنفيذ وأفضل الممارسات لإنشاء خوادم MCP ودمج MCP في سير عمل الذكاء الاصطناعي.

#### المواضيع تشمل:

- بناء خوادم MCP ودمجها في تجارب الوكلاء.
- تطوير موجه بالمطالب.
- أفضل الممارسات الأمنية.
- استخدام اللبنات الأساسية مثل Functions، ACA، وAPI Management.
- توافق السجل والأدوات (1P + 3P).

إذا كنت مطورًا، أو منشئ أدوات، أو استراتيجي منتجات الذكاء الاصطناعي، فإن هذا اليوم مليء بالرؤى التي تحتاجها لبناء حلول MCP قابلة للتوسع، آمنة، وجاهزة للمستقبل.

### معسكر تدريب MCP أغسطس 2025
تعلم من خلال جلسات فيديو مكثفة كيفية إنشاء خوادم MCP، التكامل مع VS Code، والنشر بشكل احترافي على Azure بناءً على محتوى منهج MCP للمبتدئين. احصل على مهارات عملية في تقنية تستخدمها بالفعل الشركات الكبرى.

#### [➡️شاهد عند الطلب معسكر تدريب MCP | الإنجليزية](https://developer.microsoft.com/en-us/reactor/series/s-1568/)
#### [➡️شاهد عند الطلب معسكر تدريب MCP | البرازيلية](https://developer.microsoft.com/en-us/reactor/series/S-1566/)
#### [➡️شاهد عند الطلب معسكر تدريب MCP | الإسبانية](https://developer.microsoft.com/en-us/reactor/series/S-1567/)

### لنتعلم MCP مع C# - سلسلة دروس
لنتعلم عن بروتوكول سياق النموذج (MCP)، وهو إطار عمل متقدم مصمم لتوحيد التفاعلات بين نماذج الذكاء الاصطناعي وتطبيقات العملاء. من خلال هذه الجلسة المناسبة للمبتدئين، سنقدم لك MCP ونرشدك خلال إنشاء أول خادم MCP خاص بك.
#### C#: [https://aka.ms/letslearnmcp-csharp](https://aka.ms/letslearnmcp-csharp)
#### Java: [https://aka.ms/letslearnmcp-java](https://aka.ms/letslearnmcp-java)
#### JavaScript: [https://aka.ms/letslearnmcp-javascript](https://aka.ms/letslearnmcp-javascript)
#### Python: [https://aka.ms/letslearnmcp-python](https://aka.ms/letslearnmcp-python)

## 🎓 رحلتك مع MCP تبدأ الآن

تهانينا! لقد اتخذت الخطوة الأولى في رحلة مثيرة ستوسع قدراتك البرمجية وتوصلك إلى أحدث تطورات الذكاء الاصطناعي.

### ما الذي أنجزته بالفعل

من خلال قراءة هذا المقدمة، بدأت بالفعل في بناء أساس معرفتك بـ MCP. لقد فهمت ما هو MCP، لماذا هو مهم، وكيف سيدعم هذا المنهج رحلتك التعليمية. هذا إنجاز كبير وبداية لتخصصك في هذه التقنية المهمة.

### المغامرة القادمة

بينما تتقدم خلال الوحدات، تذكر أن كل خبير كان يومًا ما مبتدئًا. المفاهيم التي قد تبدو معقدة الآن ستصبح طبيعية مع الممارسة والتطبيق. كل خطوة صغيرة تبني نحو قدرات قوية ستخدمك طوال مسيرتك البرمجية.

### شبكة الدعم الخاصة بك

أنت تنضم إلى مجتمع من المتعلمين والخبراء الذين يهتمون بـ MCP ويتحمسون لمساعدة الآخرين على النجاح. سواء كنت تواجه تحديًا برمجيًا أو متحمسًا لمشاركة إنجاز، فإن المجتمع هنا لدعم رحلتك.

إذا واجهت أي صعوبات أو كانت لديك أسئلة حول بناء تطبيقات الذكاء الاصطناعي، انضم إلى المتعلمين الآخرين والمطورين ذوي الخبرة في مناقشات حول MCP. إنه مجتمع داعم حيث يتم الترحيب بالأسئلة ومشاركة المعرفة بحرية.

[![Azure AI Foundry Discord](https://img.shields.io/badge/Discord-Azure_AI_Foundry_Community_Discord-blue?style=for-the-badge&logo=discord&color=5865f2&logoColor=fff)](https://aka.ms/foundry/discord)

إذا كانت لديك ملاحظات حول المنتج أو أخطاء أثناء البناء، قم بزيارة:

[![Azure AI Foundry Developer Forum](https://img.shields.io/badge/GitHub-Azure_AI_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

### هل أنت مستعد للبدء؟

مغامرتك مع MCP تبدأ الآن! ابدأ مع الوحدة 0 لتغوص في أولى تجاربك العملية مع MCP، أو استكشف المشاريع النموذجية لترى ما ستقوم ببنائه. تذكر - كل خبير بدأ تمامًا من حيث أنت الآن، ومع الصبر والممارسة، ستندهش مما يمكنك تحقيقه.

مرحبًا بك في عالم تطوير بروتوكول سياق النموذج. دعونا نبني شيئًا رائعًا معًا!

## 🤝 المساهمة في مجتمع التعلم

هذا المنهج يصبح أقوى بفضل مساهمات المتعلمين مثلك! سواء كنت تصلح خطأً، تقترح شرحًا أوضح، أو تضيف مثالًا جديدًا، فإن مساهماتك تساعد المبتدئين الآخرين على النجاح.

شكرًا لـ Microsoft Valued Professional [Shivam Goyal](https://www.linkedin.com/in/shivam2003/) على مساهمته في نماذج التعليمات البرمجية.

عملية المساهمة مصممة لتكون مرحبة وداعمة. تتطلب معظم المساهمات اتفاقية ترخيص المساهم (CLA)، ولكن الأدوات الآلية ستوجهك خلال العملية بسلاسة.

## 📜 التعلم مفتوح المصدر

هذا المنهج بالكامل متاح بموجب [ترخيص MIT](../../LICENSE)، مما يعني أنه يمكنك استخدامه وتعديله ومشاركته بحرية. هذا يدعم مهمتنا في جعل معرفة MCP متاحة للمطورين في كل مكان.

## 🤝 إرشادات المساهمة

هذا المشروع يرحب بالمساهمات والاقتراحات. تتطلب معظم المساهمات منك الموافقة على اتفاقية ترخيص المساهم (CLA) التي تعلن أنك لديك الحق، وتقوم فعليًا، بمنحنا الحقوق لاستخدام مساهمتك. لمزيد من التفاصيل، قم بزيارة <https://cla.opensource.microsoft.com>.

عندما تقدم طلب سحب، سيقوم روبوت CLA تلقائيًا بتحديد ما إذا كنت بحاجة إلى تقديم CLA وتزيين الطلب بشكل مناسب (مثل فحص الحالة، التعليق). ببساطة اتبع التعليمات المقدمة من الروبوت. ستحتاج إلى القيام بذلك مرة واحدة فقط عبر جميع المستودعات التي تستخدم CLA الخاص بنا.

هذا المشروع تبنى [مدونة قواعد السلوك مفتوحة المصدر من Microsoft](https://opensource.microsoft.com/codeofconduct/).
لمزيد من المعلومات، راجع [الأسئلة الشائعة حول مدونة قواعد السلوك](https://opensource.microsoft.com/codeofconduct/faq/) أو
تواصل مع [opencode@microsoft.com](mailto:opencode@microsoft.com) لأي أسئلة أو تعليقات إضافية.

---

*هل أنت مستعد لبدء رحلتك مع MCP؟ ابدأ مع [الوحدة 00 - مقدمة إلى MCP](./00-Introduction/README.md) واتخذ أولى خطواتك في عالم تطوير بروتوكول سياق النموذج!*

## 🎒 دورات أخرى
فريقنا ينتج دورات أخرى! تحقق من:

### Azure / Edge / MCP / Agents
[![AZD للمبتدئين](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI للمبتدئين](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP للمبتدئين](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents للمبتدئين](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### سلسلة الذكاء الاصطناعي التوليدي
[![الذكاء الاصطناعي التوليدي للمبتدئين](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![الذكاء الاصطناعي التوليدي (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![الذكاء الاصطناعي التوليدي (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![الذكاء الاصطناعي التوليدي (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---

### التعلم الأساسي
[![تعلم الآلة للمبتدئين](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![علم البيانات للمبتدئين](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![الذكاء الاصطناعي للمبتدئين](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![الأمن السيبراني للمبتدئين](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![تطوير الويب للمبتدئين](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![إنترنت الأشياء للمبتدئين](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![تطوير XR للمبتدئين](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### سلسلة Copilot
[![Copilot للبرمجة المزدوجة بالذكاء الاصطناعي](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot لـ C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)  
[![مغامرة Copilot](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)  
<!-- نهاية دورات CO-OP TRANSLATOR الأخرى -->

---

**إخلاء المسؤولية**:  
تم ترجمة هذا المستند باستخدام خدمة الترجمة بالذكاء الاصطناعي [Co-op Translator](https://github.com/Azure/co-op-translator). بينما نسعى لتحقيق الدقة، يرجى العلم أن الترجمات الآلية قد تحتوي على أخطاء أو عدم دقة. يجب اعتبار المستند الأصلي بلغته الأصلية المصدر الرسمي. للحصول على معلومات حاسمة، يُوصى بالترجمة البشرية الاحترافية. نحن غير مسؤولين عن أي سوء فهم أو تفسير خاطئ ينشأ عن استخدام هذه الترجمة.