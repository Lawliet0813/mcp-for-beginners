<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "aa1ce97bc694b08faf3018bab6d275b9",
  "translation_date": "2025-09-30T16:22:46+00:00",
  "source_file": "study_guide.md",
  "language_code": "tr"
}
-->
# Model Context Protocol (MCP) için Yeni Başlayanlar - Çalışma Kılavuzu

Bu çalışma kılavuzu, "Model Context Protocol (MCP) için Yeni Başlayanlar" müfredatına ait depo yapısı ve içeriği hakkında genel bir bakış sunar. Depoyu verimli bir şekilde gezinmek ve mevcut kaynaklardan en iyi şekilde yararlanmak için bu kılavuzu kullanabilirsiniz.

## Depo Genel Bakışı

Model Context Protocol (MCP), yapay zeka modelleri ile istemci uygulamaları arasındaki etkileşimler için standartlaştırılmış bir çerçevedir. İlk olarak Anthropic tarafından oluşturulan MCP, artık resmi GitHub organizasyonu aracılığıyla daha geniş MCP topluluğu tarafından sürdürülmektedir. Bu depo, C#, Java, JavaScript, Python ve TypeScript dillerinde uygulamalı kod örnekleri içeren kapsamlı bir müfredat sunar ve yapay zeka geliştiricileri, sistem mimarları ve yazılım mühendisleri için tasarlanmıştır.

## Görsel Müfredat Haritası

```mermaid
mindmap
  root((MCP for Beginners))
    00. Introduction
      ::icon(fa fa-book)
      (Protocol Overview)
      (Standardization Benefits)
      (Real-world Use Cases)
      (AI Integration Fundamentals)
    01. Core Concepts
      ::icon(fa fa-puzzle-piece)
      (Client-Server Architecture)
      (Protocol Components)
      (Messaging Patterns)
      (Transport Mechanisms)
    02. Security
      ::icon(fa fa-shield)
      (AI-Specific Threats)
      (Best Practices 2025)
      (Azure Content Safety)
      (Auth & Authorization)
      (Microsoft Prompt Shields)
    03. Getting Started
      ::icon(fa fa-rocket)
      (First Server Implementation)
      (Client Development)
      (LLM Client Integration)
      (VS Code Extensions)
      (SSE Server Setup)
      (HTTP Streaming)
      (AI Toolkit Integration)
      (Testing Frameworks)
      (Deployment Strategies)
    04. Practical Implementation
      ::icon(fa fa-code)
      (Multi-Language SDKs)
      (Testing & Debugging)
      (Prompt Templates)
      (Sample Projects)
      (Production Patterns)
    05. Advanced Topics
      ::icon(fa fa-graduation-cap)
      (Context Engineering)
      (Foundry Agent Integration)
      (Multi-modal AI Workflows)
      (OAuth2 Authentication)
      (Real-time Search)
      (Streaming Protocols)
      (Root Contexts)
      (Routing Strategies)
      (Sampling Techniques)
      (Scaling Solutions)
      (Security Hardening)
      (Entra ID Integration)
      (Web Search MCP)
      
    06. Community
      ::icon(fa fa-users)
      (Code Contributions)
      (Documentation)
      (MCP Client Ecosystem)
      (MCP Server Registry)
      (Image Generation Tools)
      (GitHub Collaboration)
    07. Early Adoption
      ::icon(fa fa-lightbulb)
      (Production Deployments)
      (Microsoft MCP Servers)
      (Azure MCP Service)
      (Enterprise Case Studies)
      (Future Roadmap)
    08. Best Practices
      ::icon(fa fa-check)
      (Performance Optimization)
      (Fault Tolerance)
      (System Resilience)
      (Monitoring & Observability)
    09. Case Studies
      ::icon(fa fa-file-text)
      (Azure API Management)
      (AI Travel Agent)
      (Azure DevOps Integration)
      (Documentation MCP)
      (GitHub MCP Registry)
      (VS Code Integration)
      (Real-world Implementations)
    10. Hands-on Workshop
      ::icon(fa fa-laptop)
      (MCP Server Fundamentals)
      (Advanced Development)
      (AI Toolkit Integration)
      (Production Deployment)
      (4-Lab Structure)
    11. Database Integration Labs
      ::icon(fa fa-database)
      (PostgreSQL Integration)
      (Retail Analytics Use Case)
      (Row Level Security)
      (Semantic Search)
      (Production Deployment)
      (13-Lab Structure)
      (Hands-on Learning)
```

## Depo Yapısı

Depo, MCP'nin farklı yönlerine odaklanan on bir ana bölümden oluşmaktadır:

1. **Giriş (00-Introduction/)**
   - Model Context Protocol'e genel bakış
   - Yapay zeka süreçlerinde standartlaşmanın önemi
   - Pratik kullanım alanları ve faydalar

2. **Temel Kavramlar (01-CoreConcepts/)**
   - İstemci-sunucu mimarisi
   - Protokolün ana bileşenleri
   - MCP'deki mesajlaşma desenleri

3. **Güvenlik (02-Security/)**
   - MCP tabanlı sistemlerde güvenlik tehditleri
   - Uygulamaları güvence altına almak için en iyi uygulamalar
   - Kimlik doğrulama ve yetkilendirme stratejileri
   - **Kapsamlı Güvenlik Belgeleri**:
     - MCP Güvenlik En İyi Uygulamaları 2025
     - Azure İçerik Güvenliği Uygulama Kılavuzu
     - MCP Güvenlik Kontrolleri ve Teknikleri
     - MCP En İyi Uygulamalar Hızlı Referans
   - **Önemli Güvenlik Konuları**:
     - Prompt enjeksiyonu ve araç zehirlenmesi saldırıları
     - Oturum kaçırma ve karışık vekil sorunları
     - Token geçişi açıkları
     - Aşırı izinler ve erişim kontrolü
     - Yapay zeka bileşenleri için tedarik zinciri güvenliği
     - Microsoft Prompt Shields entegrasyonu

4. **Başlangıç (03-GettingStarted/)**
   - Ortam kurulumu ve yapılandırma
   - Temel MCP sunucuları ve istemcileri oluşturma
   - Mevcut uygulamalarla entegrasyon
   - Şunları içeren bölümler:
     - İlk sunucu uygulaması
     - İstemci geliştirme
     - LLM istemci entegrasyonu
     - VS Code entegrasyonu
     - Server-Sent Events (SSE) sunucusu
     - HTTP akışı
     - Yapay Zeka Araç Seti entegrasyonu
     - Test stratejileri
     - Dağıtım yönergeleri

5. **Pratik Uygulama (04-PracticalImplementation/)**
   - Farklı programlama dillerinde SDK'ları kullanma
   - Hata ayıklama, test etme ve doğrulama teknikleri
   - Yeniden kullanılabilir prompt şablonları ve iş akışları oluşturma
   - Uygulama örnekleri içeren örnek projeler

6. **İleri Düzey Konular (05-AdvancedTopics/)**
   - Bağlam mühendisliği teknikleri
   - Foundry ajan entegrasyonu
   - Çok modlu yapay zeka iş akışları
   - OAuth2 kimlik doğrulama demoları
   - Gerçek zamanlı arama yetenekleri
   - Gerçek zamanlı akış
   - Root bağlamları uygulamaları
   - Yönlendirme stratejileri
   - Örnekleme teknikleri
   - Ölçeklendirme yaklaşımları
   - Güvenlik hususları
   - Entra ID güvenlik entegrasyonu
   - Web arama entegrasyonu

7. **Topluluk Katkıları (06-CommunityContributions/)**
   - Kod ve belgeler nasıl katkıda bulunulur
   - GitHub üzerinden iş birliği
   - Topluluk odaklı iyileştirmeler ve geri bildirim
   - Çeşitli MCP istemcileri kullanma (Claude Desktop, Cline, VSCode)
   - Görüntü oluşturma dahil popüler MCP sunucularıyla çalışma

8. **Erken Benimsemeden Alınan Dersler (07-LessonsfromEarlyAdoption/)**
   - Gerçek dünya uygulamaları ve başarı hikayeleri
   - MCP tabanlı çözümler oluşturma ve dağıtma
   - Trendler ve gelecekteki yol haritası
   - **Microsoft MCP Sunucuları Kılavuzu**: 10 üretime hazır Microsoft MCP sunucusuna yönelik kapsamlı kılavuz, şunları içerir:
     - Microsoft Learn Docs MCP Sunucusu
     - Azure MCP Sunucusu (15+ özel bağlayıcı)
     - GitHub MCP Sunucusu
     - Azure DevOps MCP Sunucusu
     - MarkItDown MCP Sunucusu
     - SQL Server MCP Sunucusu
     - Playwright MCP Sunucusu
     - Dev Box MCP Sunucusu
     - Azure AI Foundry MCP Sunucusu
     - Microsoft 365 Agents Toolkit MCP Sunucusu

9. **En İyi Uygulamalar (08-BestPractices/)**
   - Performans ayarlama ve optimizasyon
   - Hata toleranslı MCP sistemleri tasarlama
   - Test ve dayanıklılık stratejileri

10. **Vaka Çalışmaları (09-CaseStudy/)**
    - MCP'nin çeşitli senaryolardaki çok yönlülüğünü gösteren **yedi kapsamlı vaka çalışması**:
    - **Azure AI Seyahat Acenteleri**: Azure OpenAI ve AI Search ile çoklu ajan orkestrasyonu
    - **Azure DevOps Entegrasyonu**: YouTube veri güncellemeleriyle iş akışı süreçlerini otomatikleştirme
    - **Gerçek Zamanlı Belge Alma**: HTTP akışı ile Python konsol istemcisi
    - **Etkileşimli Çalışma Planı Oluşturucu**: Konuşma yapay zekası ile Chainlit web uygulaması
    - **Editör İçi Belgelendirme**: GitHub Copilot iş akışları ile VS Code entegrasyonu
    - **Azure API Yönetimi**: MCP sunucusu oluşturma ile kurumsal API entegrasyonu
    - **GitHub MCP Kaydı**: Ekosistem geliştirme ve ajan entegrasyon platformu
    - Kurumsal entegrasyon, geliştirici verimliliği ve ekosistem geliştirme alanlarında uygulama örnekleri

11. **Uygulamalı Atölye Çalışması (10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/)**
    - MCP ile Yapay Zeka Araç Seti'ni birleştiren kapsamlı uygulamalı atölye çalışması
    - Yapay zeka modellerini gerçek dünya araçlarıyla birleştiren akıllı uygulamalar oluşturma
    - Temel bilgiler, özel sunucu geliştirme ve üretim dağıtım stratejilerini kapsayan pratik modüller
    - **Laboratuvar Yapısı**:
      - Laboratuvar 1: MCP Sunucu Temelleri
      - Laboratuvar 2: İleri Düzey MCP Sunucu Geliştirme
      - Laboratuvar 3: Yapay Zeka Araç Seti Entegrasyonu
      - Laboratuvar 4: Üretim Dağıtımı ve Ölçeklendirme
    - Adım adım talimatlarla laboratuvar tabanlı öğrenme yaklaşımı

12. **MCP Sunucu Veritabanı Entegrasyon Laboratuvarları (11-MCPServerHandsOnLabs/)**
    - PostgreSQL entegrasyonu ile üretime hazır MCP sunucuları oluşturmak için **kapsamlı 13 laboratuvarlık öğrenme yolu**
    - **Zava Retail kullanım senaryosu** ile gerçek dünya perakende analitiği uygulaması
    - **Kurumsal düzeyde desenler**: Satır Düzeyi Güvenlik (RLS), anlamsal arama ve çok kiracılı veri erişimi
    - **Tam Laboratuvar Yapısı**:
      - **Laboratuvarlar 00-03: Temeller** - Giriş, Mimari, Güvenlik, Ortam Kurulumu
      - **Laboratuvarlar 04-06: MCP Sunucusunu Oluşturma** - Veritabanı Tasarımı, MCP Sunucu Uygulaması, Araç Geliştirme
      - **Laboratuvarlar 07-09: İleri Düzey Özellikler** - Anlamsal Arama, Test ve Hata Ayıklama, VS Code Entegrasyonu
      - **Laboratuvarlar 10-12: Üretim ve En İyi Uygulamalar** - Dağıtım, İzleme, Optimizasyon
    - **Kapsanan Teknolojiler**: FastMCP çerçevesi, PostgreSQL, Azure OpenAI, Azure Container Apps, Application Insights
    - **Öğrenim Çıktıları**: Üretime hazır MCP sunucuları, veritabanı entegrasyon desenleri, yapay zeka destekli analitik, kurumsal güvenlik

## Ek Kaynaklar

Depo, destekleyici kaynaklar içerir:

- **Görseller klasörü**: Müfredat boyunca kullanılan diyagramlar ve illüstrasyonlar içerir
- **Çeviriler**: Belgelerin otomatik çevirileri ile çok dilli destek
- **Resmi MCP Kaynakları**:
  - [MCP Belgeleri](https://modelcontextprotocol.io/)
  - [MCP Spesifikasyonu](https://spec.modelcontextprotocol.io/)
  - [MCP GitHub Deposu](https://github.com/modelcontextprotocol)

## Bu Depoyu Nasıl Kullanabilirsiniz

1. **Sıralı Öğrenme**: Yapılandırılmış bir öğrenme deneyimi için bölümleri sırayla takip edin (00'dan 11'e kadar).
2. **Dil Odaklı Çalışma**: Belirli bir programlama diliyle ilgileniyorsanız, tercih ettiğiniz dildeki uygulamaları görmek için örnekler dizinlerini inceleyin.
3. **Pratik Uygulama**: Ortamınızı kurmak ve ilk MCP sunucunuzu ve istemcinizi oluşturmak için "Başlangıç" bölümünden başlayın.
4. **İleri Düzey Keşif**: Temel bilgilere alıştıktan sonra, ileri düzey konulara dalarak bilginizi genişletin.
5. **Topluluk Katılımı**: GitHub tartışmaları ve Discord kanalları aracılığıyla MCP topluluğuna katılarak uzmanlar ve diğer geliştiricilerle bağlantı kurun.

## MCP İstemcileri ve Araçları

Müfredat, çeşitli MCP istemcilerini ve araçlarını kapsar:

1. **Resmi İstemciler**:
   - Visual Studio Code 
   - MCP Visual Studio Code'da
   - Claude Desktop
   - Claude VSCode'da 
   - Claude API

2. **Topluluk İstemcileri**:
   - Cline (terminal tabanlı)
   - Cursor (kod editörü)
   - ChatMCP
   - Windsurf

3. **MCP Yönetim Araçları**:
   - MCP CLI
   - MCP Manager
   - MCP Linker
   - MCP Router

## Popüler MCP Sunucuları

Depo, çeşitli MCP sunucularını tanıtır, bunlar arasında:

1. **Resmi Microsoft MCP Sunucuları**:
   - Microsoft Learn Docs MCP Sunucusu
   - Azure MCP Sunucusu (15+ özel bağlayıcı)
   - GitHub MCP Sunucusu
   - Azure DevOps MCP Sunucusu
   - MarkItDown MCP Sunucusu
   - SQL Server MCP Sunucusu
   - Playwright MCP Sunucusu
   - Dev Box MCP Sunucusu
   - Azure AI Foundry MCP Sunucusu
   - Microsoft 365 Agents Toolkit MCP Sunucusu

2. **Resmi Referans Sunucuları**:
   - Dosya Sistemi
   - Fetch
   - Bellek
   - Sıralı Düşünme

3. **Görüntü Oluşturma**:
   - Azure OpenAI DALL-E 3
   - Stable Diffusion WebUI
   - Replicate

4. **Geliştirme Araçları**:
   - Git MCP
   - Terminal Kontrolü
   - Kod Asistanı

5. **Özel Sunucular**:
   - Salesforce
   - Microsoft Teams
   - Jira & Confluence

## Katkıda Bulunma

Bu depo, topluluktan gelen katkılara açıktır. MCP ekosistemine etkili bir şekilde katkıda bulunma konusunda rehberlik için Topluluk Katkıları bölümüne bakın.

## Değişiklik Günlüğü

| Tarih | Değişiklikler |
|------|---------||
| 29 Eylül 2025 | - 11-MCPServerHandsOnLabs bölümünü kapsamlı 13 laboratuvarlık veritabanı entegrasyonu öğrenme yolu ile ekledik<br>- Görsel Müfredat Haritası'nı Veritabanı Entegrasyon Laboratuvarlarını içerecek şekilde güncelledik<br>- Depo yapısını on bir ana bölümü yansıtacak şekilde geliştirdik<br>- PostgreSQL entegrasyonu, perakende analitiği kullanım senaryosu ve kurumsal desenler hakkında ayrıntılı açıklama ekledik<br>- 00-11 bölümlerini içeren gezinme rehberini güncelledik |
| 26 Eylül 2025 | - GitHub MCP Kaydı vaka çalışmasını 09-CaseStudy bölümüne ekledik<br>- Vaka Çalışmaları bölümünü yedi kapsamlı vaka çalışmasını yansıtacak şekilde güncelledik<br>- Vaka çalışması açıklamalarını belirli uygulama ayrıntılarıyla geliştirdik<br>- Görsel Müfredat Haritası'nı GitHub MCP Kaydı'nı içerecek şekilde güncelledik<br>- Çalışma kılavuzu yapısını ekosistem geliştirme odaklı olacak şekilde revize ettik |
| 18 Temmuz 2025 | - Depo yapısını Microsoft MCP Sunucuları Kılavuzu'nu içerecek şekilde güncelledik<br>- 10 üretime hazır Microsoft MCP sunucusunun kapsamlı listesini ekledik<br>- Popüler MCP Sunucuları bölümünü Resmi Microsoft MCP Sunucuları ile geliştirdik<br>- Vaka Çalışmaları bölümünü gerçek dosya örnekleriyle güncelledik<br>- Uygulamalı Atölye Çalışması için Laboratuvar Yapısı ayrıntılarını ekledik |
| 16 Temmuz 2025 | - Depo yapısını mevcut içeriği yansıtacak şekilde güncelledik<br>- MCP İstemcileri ve Araçları bölümünü ekledik<br>- Popüler MCP Sunucuları bölümünü ekledik<br>- Görsel Müfredat Haritası'nı mevcut tüm konularla güncelledik<br>- İleri Düzey Konular bölümünü tüm özel alanlarla geliştirdik<br>- Vaka Çalışmaları bölümünü gerçek örneklerle güncelledik<br>- MCP'nin Anthropic tarafından oluşturulduğunu netleştirdik |
| 11 Haziran 2025 | - Çalışma kılavuzunun ilk oluşturulması<br>- Görsel Müfredat Haritası eklendi<br>- Depo yapısı taslağı oluşturuldu<br>- Örnek projeler ve ek kaynaklar dahil edildi |

---

*Bu çalışma kılavuzu 29 Eylül 2025 tarihinde güncellenmiş olup, bu tarihteki depo içeriği hakkında genel bir bakış sunmaktadır. Depo içeriği bu tarihten sonra güncellenebilir.*

---

**Feragatname**:  
Bu belge, AI çeviri hizmeti [Co-op Translator](https://github.com/Azure/co-op-translator) kullanılarak çevrilmiştir. Doğruluk için çaba göstersek de, otomatik çevirilerin hata veya yanlışlık içerebileceğini lütfen unutmayın. Belgenin orijinal dili, yetkili kaynak olarak kabul edilmelidir. Kritik bilgiler için profesyonel insan çevirisi önerilir. Bu çevirinin kullanımından kaynaklanan yanlış anlamalar veya yanlış yorumlamalar için sorumluluk kabul edilmemektedir.