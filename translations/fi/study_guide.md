<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "ac390de870be5c02165350f6279a8831",
  "translation_date": "2025-10-06T14:38:16+00:00",
  "source_file": "study_guide.md",
  "language_code": "fi"
}
-->
# Model Context Protocol (MCP) aloittelijoille - Opas

Tämä opas tarjoaa yleiskatsauksen "Model Context Protocol (MCP) for Beginners" -opetussuunnitelman arkiston rakenteesta ja sisällöstä. Käytä tätä opasta navigoidaksesi arkistossa tehokkaasti ja hyödyntääksesi saatavilla olevia resursseja parhaalla mahdollisella tavalla.

## Arkiston yleiskatsaus

Model Context Protocol (MCP) on standardoitu kehys AI-mallien ja asiakassovellusten välisille vuorovaikutuksille. Alun perin Anthropicin luoma MCP on nyt laajemman MCP-yhteisön ylläpitämä virallisen GitHub-organisaation kautta. Tämä arkisto tarjoaa kattavan opetussuunnitelman käytännön koodiesimerkeillä C#:ssa, Javassa, JavaScriptissä, Pythonissa ja TypeScriptissä, ja se on suunnattu AI-kehittäjille, järjestelmäarkkitehdeille ja ohjelmistosuunnittelijoille.

## Visuaalinen opetussuunnitelmakartta

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
      (Advanced Server Usage)
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

## Arkiston rakenne

Arkisto on jaettu yhteentoista pääosioon, joista jokainen keskittyy MCP:n eri osa-alueisiin:

1. **Johdanto (00-Introduction/)**
   - Model Context Protocolin yleiskatsaus
   - Miksi standardointi on tärkeää AI-putkistoissa
   - Käytännön käyttötapaukset ja hyödyt

2. **Peruskäsitteet (01-CoreConcepts/)**
   - Asiakas-palvelin-arkkitehtuuri
   - Protokollan keskeiset komponentit
   - Viestintämallit MCP:ssä

3. **Tietoturva (02-Security/)**
   - Tietoturvauhat MCP-pohjaisissa järjestelmissä
   - Parhaat käytännöt toteutusten suojaamiseksi
   - Todennus- ja valtuutusstrategiat
   - **Kattava tietoturvadokumentaatio**:
     - MCP Security Best Practices 2025
     - Azure Content Safety Implementation Guide
     - MCP Security Controls and Techniques
     - MCP Best Practices Quick Reference
   - **Keskeiset tietoturva-aiheet**:
     - Prompt injection- ja tool poisoning -hyökkäykset
     - Istunnon kaappaus ja confused deputy -ongelmat
     - Token passthrough -haavoittuvuudet
     - Liialliset käyttöoikeudet ja pääsynhallinta
     - AI-komponenttien toimitusketjun tietoturva
     - Microsoft Prompt Shields -integraatio

4. **Aloittaminen (03-GettingStarted/)**
   - Ympäristön asennus ja konfigurointi
   - Perus-MCP-palvelimien ja -asiakkaiden luominen
   - Integrointi olemassa oleviin sovelluksiin
   - Sisältää osiot:
     - Ensimmäinen palvelintoteutus
     - Asiakaskehitys
     - LLM-asiakasintegraatio
     - VS Code -integraatio
     - Server-Sent Events (SSE) -palvelin
     - Edistynyt palvelimen käyttö
     - HTTP-suoratoisto
     - AI Toolkit -integraatio
     - Testausstrategiat
     - Käyttöönotto-ohjeet

5. **Käytännön toteutus (04-PracticalImplementation/)**
   - SDK:iden käyttö eri ohjelmointikielissä
   - Virheenkorjaus-, testaus- ja validointitekniikat
   - Uudelleenkäytettävien prompt-mallien ja työnkulkujen luominen
   - Esimerkkiprojektit toteutusesimerkeillä

6. **Edistyneet aiheet (05-AdvancedTopics/)**
   - Kontekstisuunnittelutekniikat
   - Foundry-agentin integrointi
   - Monimodaaliset AI-työnkulut
   - OAuth2-todennusdemot
   - Reaaliaikaiset hakutoiminnot
   - Reaaliaikainen suoratoisto
   - Root-kontekstien toteutus
   - Reititysstrategiat
   - Näytteenottotekniikat
   - Skaalauslähestymistavat
   - Tietoturvanäkökohdat
   - Entra ID -tietoturvaintegraatio
   - Verkkohakuintegraatio

7. **Yhteisön panokset (06-CommunityContributions/)**
   - Kuinka osallistua koodin ja dokumentaation kehittämiseen
   - Yhteistyö GitHubin kautta
   - Yhteisön parannukset ja palaute
   - Erilaisten MCP-asiakkaiden käyttö (Claude Desktop, Cline, VSCode)
   - Työskentely suosittujen MCP-palvelimien kanssa, mukaan lukien kuvagenerointi

8. **Opit varhaisesta käyttöönotosta (07-LessonsfromEarlyAdoption/)**
   - Todelliset toteutukset ja menestystarinat
   - MCP-pohjaisten ratkaisujen rakentaminen ja käyttöönotto
   - Trendit ja tulevaisuuden tiekartta
   - **Microsoft MCP Servers Guide**: Kattava opas 10 tuotantovalmiista Microsoft MCP -palvelimesta, mukaan lukien:
     - Microsoft Learn Docs MCP Server
     - Azure MCP Server (15+ erikoistunutta liitintä)
     - GitHub MCP Server
     - Azure DevOps MCP Server
     - MarkItDown MCP Server
     - SQL Server MCP Server
     - Playwright MCP Server
     - Dev Box MCP Server
     - Azure AI Foundry MCP Server
     - Microsoft 365 Agents Toolkit MCP Server

9. **Parhaat käytännöt (08-BestPractices/)**
   - Suorituskyvyn viritys ja optimointi
   - Vikasietoiset MCP-järjestelmät
   - Testaus- ja resilienssistrategiat

10. **Tapaustutkimukset (09-CaseStudy/)**
    - **Seitsemän kattavaa tapaustutkimusta**, jotka osoittavat MCP:n monipuolisuuden eri skenaarioissa:
    - **Azure AI Travel Agents**: Moniagenttiorganisointi Azure OpenAI:n ja AI-haun kanssa
    - **Azure DevOps -integraatio**: Työnkulkujen automatisointi YouTube-datapäivityksillä
    - **Reaaliaikainen dokumenttien haku**: Python-konsoliasiakas suoratoistavalla HTTP:llä
    - **Interaktiivinen opintosuunnitelman generaattori**: Chainlit-verkkosovellus keskustelevaa AI:ta käyttäen
    - **Editorin sisäinen dokumentaatio**: VS Code -integraatio GitHub Copilot -työnkulkujen kanssa
    - **Azure API Management**: Yrityksen API-integraatio MCP-palvelimen luomisella
    - **GitHub MCP Registry**: Ekosysteemin kehitys ja agenttien integrointialusta
    - Toteutusesimerkit kattavat yritysintegraation, kehittäjien tuottavuuden ja ekosysteemin kehityksen

11. **Käytännön työpaja (10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/)**
    - Kattava käytännön työpaja, joka yhdistää MCP:n AI Toolkitin kanssa
    - Älykkäiden sovellusten rakentaminen, jotka yhdistävät AI-mallit todellisiin työkaluihin
    - Käytännön moduulit, jotka kattavat perusteet, mukautetun palvelimen kehittämisen ja tuotantokäyttöönottostrategiat
    - **Lab-rakenne**:
      - Lab 1: MCP-palvelimen perusteet
      - Lab 2: Edistynyt MCP-palvelimen kehitys
      - Lab 3: AI Toolkit -integraatio
      - Lab 4: Tuotantokäyttöönotto ja skaalaus
    - Lab-pohjainen oppimismenetelmä vaiheittaisilla ohjeilla

12. **MCP-palvelimen tietokantaintegraatiolaboratoriot (11-MCPServerHandsOnLabs/)**
    - **Kattava 13-laboratorion oppimispolku** tuotantovalmiiden MCP-palvelimien rakentamiseen PostgreSQL-integraatiolla
    - **Todellisen vähittäiskaupan analytiikan toteutus** Zava Retail -käyttötapauksen avulla
    - **Yritystason mallit**, mukaan lukien rivitason tietoturva (RLS), semanttinen haku ja monivuokraajadata
    - **Täydellinen laboratoriorakenne**:
      - **Laboratoriot 00-03: Perusteet** - Johdanto, arkkitehtuuri, tietoturva, ympäristön asennus
      - **Laboratoriot 04-06: MCP-palvelimen rakentaminen** - Tietokantasuunnittelu, MCP-palvelimen toteutus, työkalujen kehitys
      - **Laboratoriot 07-09: Edistyneet ominaisuudet** - Semanttinen haku, testaus ja virheenkorjaus, VS Code -integraatio
      - **Laboratoriot 10-12: Tuotanto ja parhaat käytännöt** - Käyttöönotto, valvonta, optimointi
    - **Käytetyt teknologiat**: FastMCP-kehys, PostgreSQL, Azure OpenAI, Azure Container Apps, Application Insights
    - **Oppimistulokset**: Tuotantovalmiit MCP-palvelimet, tietokantaintegraatiomallit, AI-pohjainen analytiikka, yritystason tietoturva

## Lisäresurssit

Arkisto sisältää tukiresursseja:

- **Kuvat-kansio**: Sisältää kaavioita ja kuvituksia, joita käytetään opetussuunnitelman aikana
- **Käännökset**: Monikielinen tuki dokumentaation automaattisilla käännöksillä
- **Viralliset MCP-resurssit**:
  - [MCP Documentation](https://modelcontextprotocol.io/)
  - [MCP Specification](https://spec.modelcontextprotocol.io/)
  - [MCP GitHub Repository](https://github.com/modelcontextprotocol)

## Kuinka käyttää tätä arkistoa

1. **Järjestelmällinen oppiminen**: Seuraa lukuja järjestyksessä (00–11) saadaksesi rakenteellisen oppimiskokemuksen.
2. **Kielikohtainen painotus**: Jos olet kiinnostunut tietystä ohjelmointikielestä, tutustu näytekansioihin toteutuksiin haluamallasi kielellä.
3. **Käytännön toteutus**: Aloita "Aloittaminen"-osiosta asentaaksesi ympäristön ja luodaksesi ensimmäisen MCP-palvelimen ja -asiakkaan.
4. **Edistynyt tutkimus**: Kun perusasiat ovat hallussa, syvenny edistyneisiin aiheisiin laajentaaksesi tietämystäsi.
5. **Yhteisön osallistuminen**: Liity MCP-yhteisöön GitHub-keskustelujen ja Discord-kanavien kautta saadaksesi yhteyden asiantuntijoihin ja muihin kehittäjiin.

## MCP-asiakkaat ja työkalut

Opetussuunnitelma kattaa erilaisia MCP-asiakkaita ja työkaluja:

1. **Viralliset asiakkaat**:
   - Visual Studio Code 
   - MCP Visual Studio Codessa
   - Claude Desktop
   - Claude VSCode:ssa 
   - Claude API

2. **Yhteisön asiakkaat**:
   - Cline (pohjautuu terminaaliin)
   - Cursor (koodieditori)
   - ChatMCP
   - Windsurf

3. **MCP-hallintatyökalut**:
   - MCP CLI
   - MCP Manager
   - MCP Linker
   - MCP Router

## Suositut MCP-palvelimet

Arkisto esittelee erilaisia MCP-palvelimia, mukaan lukien:

1. **Viralliset Microsoft MCP-palvelimet**:
   - Microsoft Learn Docs MCP Server
   - Azure MCP Server (15+ erikoistunutta liitintä)
   - GitHub MCP Server
   - Azure DevOps MCP Server
   - MarkItDown MCP Server
   - SQL Server MCP Server
   - Playwright MCP Server
   - Dev Box MCP Server
   - Azure AI Foundry MCP Server
   - Microsoft 365 Agents Toolkit MCP Server

2. **Viralliset referenssipalvelimet**:
   - Tiedostojärjestelmä
   - Fetch
   - Muisti
   - Järjestelmällinen ajattelu

3. **Kuvagenerointi**:
   - Azure OpenAI DALL-E 3
   - Stable Diffusion WebUI
   - Replicate

4. **Kehitystyökalut**:
   - Git MCP
   - Terminaalin hallinta
   - Koodiassistentti

5. **Erikoistuneet palvelimet**:
   - Salesforce
   - Microsoft Teams
   - Jira & Confluence

## Osallistuminen

Tämä arkisto toivottaa yhteisön panokset tervetulleiksi. Katso Yhteisön panokset -osio saadaksesi ohjeita MCP-ekosysteemiin osallistumisesta.

## Muutosloki

| Päivämäärä | Muutokset |
|------------|-----------||
| 29. syyskuuta 2025 | - Lisätty 11-MCPServerHandsOnLabs-osio kattavalla 13-laboratorion tietokantaintegraation oppimispolulla<br>- Päivitetty visuaalinen opetussuunnitelmakartta sisältämään tietokantaintegraatiolaboratoriot<br>- Parannettu arkiston rakennetta heijastamaan yksitoista pääosiota<br>- Lisätty yksityiskohtainen kuvaus PostgreSQL-integraatiosta, vähittäiskaupan analytiikan käyttötapauksesta ja yritystason malleista<br>- Päivitetty navigointiohjeet sisältämään osiot 00–11 |
| 26. syyskuuta 2025 | - Lisätty GitHub MCP Registry -tapaustutkimus 09-CaseStudy-osioon<br>- Päivitetty tapaustutkimukset heijastamaan seitsemää kattavaa tapaustutkimusta<br>- Parannettu tapaustutkimusten kuvauksia erityisillä toteutustiedoilla<br>- Päivitetty visuaalinen opetussuunnitelmakartta sisältämään GitHub MCP Registry<br>- Tarkistettu opasrakenne heijastamaan ekosysteemin kehityksen painotusta |
| 18. heinäkuuta 2025 | - Päivitetty arkiston rakenne sisältämään Microsoft MCP Servers Guide<br>- Lisätty kattava lista 10 tuotantovalmiista Microsoft MCP-palvelimesta<br>- Parannettu Suositut MCP-palvelimet -osio virallisilla Microsoft MCP-palvelimilla<br>- Päivitetty tapaustutkimukset osio todellisilla tiedostoesimerkeillä<br>- Lisätty Lab-rakenteen tiedot käytännön työpajalle |
| 16. heinäkuuta 2025 | - Päivitetty arkiston rakenne heijastamaan nykyistä sisältöä<br>- Lisätty MCP-asiakkaat ja työkalut -osio<br>- Lisätty Suositut MCP-palvelimet -osio<br>- Päivitetty visuaalinen opetussuunnitelmakartta kaikilla nykyisillä aiheilla<br>- Parannettu Edistyneet aiheet -osio kaikilla erikoistuneilla alueilla<br>- Päivitetty tapaustutkimukset heijastamaan todellisia esimerkkejä<br>- Selkeytetty MCP:n alkuperä Anthropicin luomana |
| 11. kesäkuuta 2025 | - Opas luotu alun perin<br>- Lisätty visuaalinen opetussuunnitelmakartta<br>- Kuvaillut arkiston rakenne<br>- Sisällytetty esimerkkiprojektit ja lisäresurssit |
| 6. lokakuuta 2025 | Lisätty oppitunti edistyneestä palvelimen käytöstä |

---

*Tämä opas päivitettiin 29. syyskuuta 2025 ja tarjoaa yleiskatsauksen arkistosta kyseisenä päivänä. Arkiston sisältöä voidaan päivittää tämän päivämäärän jälkeen.*

---

**Vastuuvapauslauseke**:  
Tämä asiakirja on käännetty käyttämällä tekoälypohjaista käännöspalvelua [Co-op Translator](https://github.com/Azure/co-op-translator). Vaikka pyrimme tarkkuuteen, huomioithan, että automaattiset käännökset voivat sisältää virheitä tai epätarkkuuksia. Alkuperäinen asiakirja sen alkuperäisellä kielellä tulisi pitää ensisijaisena lähteenä. Kriittisen tiedon osalta suositellaan ammattimaista ihmiskäännöstä. Emme ole vastuussa väärinkäsityksistä tai virhetulkinnoista, jotka johtuvat tämän käännöksen käytöstä.