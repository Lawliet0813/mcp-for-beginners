<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "aa1ce97bc694b08faf3018bab6d275b9",
  "translation_date": "2025-09-30T12:29:40+00:00",
  "source_file": "study_guide.md",
  "language_code": "fr"
}
-->
# Guide d'étude du Protocole de Contexte Modèle (MCP) pour Débutants

Ce guide d'étude offre une vue d'ensemble de la structure et du contenu du dépôt pour le programme "Protocole de Contexte Modèle (MCP) pour Débutants". Utilisez ce guide pour naviguer efficacement dans le dépôt et tirer le meilleur parti des ressources disponibles.

## Vue d'ensemble du dépôt

Le Protocole de Contexte Modèle (MCP) est un cadre standardisé pour les interactions entre les modèles d'IA et les applications clientes. Initialement créé par Anthropic, le MCP est désormais maintenu par la communauté MCP via l'organisation officielle GitHub. Ce dépôt propose un programme complet avec des exemples de code pratiques en C#, Java, JavaScript, Python et TypeScript, conçu pour les développeurs d'IA, les architectes systèmes et les ingénieurs logiciels.

## Carte visuelle du programme

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

## Structure du dépôt

Le dépôt est organisé en onze sections principales, chacune se concentrant sur différents aspects du MCP :

1. **Introduction (00-Introduction/)**
   - Vue d'ensemble du Protocole de Contexte Modèle
   - Importance de la standardisation dans les pipelines d'IA
   - Cas d'utilisation pratiques et avantages

2. **Concepts de base (01-CoreConcepts/)**
   - Architecture client-serveur
   - Composants clés du protocole
   - Modèles de messagerie dans le MCP

3. **Sécurité (02-Security/)**
   - Menaces de sécurité dans les systèmes basés sur le MCP
   - Bonnes pratiques pour sécuriser les implémentations
   - Stratégies d'authentification et d'autorisation
   - **Documentation complète sur la sécurité** :
     - Bonnes pratiques de sécurité MCP 2025
     - Guide d'implémentation Azure Content Safety
     - Contrôles et techniques de sécurité MCP
     - Référence rapide des meilleures pratiques MCP
   - **Sujets clés en sécurité** :
     - Attaques par injection de prompts et empoisonnement d'outils
     - Détournement de session et problèmes de délégué confus
     - Vulnérabilités de transmission de jetons
     - Permissions excessives et contrôle d'accès
     - Sécurité de la chaîne d'approvisionnement pour les composants IA
     - Intégration de Microsoft Prompt Shields

4. **Premiers pas (03-GettingStarted/)**
   - Configuration de l'environnement
   - Création de serveurs et clients MCP de base
   - Intégration avec des applications existantes
   - Comprend des sections sur :
     - Première implémentation de serveur
     - Développement de clients
     - Intégration de clients LLM
     - Intégration avec VS Code
     - Serveur d'événements envoyés par le serveur (SSE)
     - Streaming HTTP
     - Intégration de l'AI Toolkit
     - Stratégies de test
     - Directives de déploiement

5. **Implémentation pratique (04-PracticalImplementation/)**
   - Utilisation des SDK dans différents langages de programmation
   - Techniques de débogage, test et validation
   - Création de modèles de prompts et workflows réutilisables
   - Projets exemples avec implémentations pratiques

6. **Sujets avancés (05-AdvancedTopics/)**
   - Techniques d'ingénierie de contexte
   - Intégration d'agents Foundry
   - Workflows IA multi-modaux
   - Démos d'authentification OAuth2
   - Capacités de recherche en temps réel
   - Streaming en temps réel
   - Implémentation de contextes racine
   - Stratégies de routage
   - Techniques d'échantillonnage
   - Approches de mise à l'échelle
   - Considérations de sécurité
   - Intégration de la sécurité Entra ID
   - Intégration de recherche web

7. **Contributions de la communauté (06-CommunityContributions/)**
   - Comment contribuer au code et à la documentation
   - Collaboration via GitHub
   - Améliorations et retours pilotés par la communauté
   - Utilisation de divers clients MCP (Claude Desktop, Cline, VSCode)
   - Travail avec des serveurs MCP populaires, y compris la génération d'images

8. **Leçons tirées des premières adoptions (07-LessonsfromEarlyAdoption/)**
   - Implémentations réelles et histoires de réussite
   - Construction et déploiement de solutions basées sur le MCP
   - Tendances et feuille de route future
   - **Guide des serveurs MCP Microsoft** : Guide complet de 10 serveurs MCP Microsoft prêts pour la production, y compris :
     - Serveur MCP Microsoft Learn Docs
     - Serveur MCP Azure (15+ connecteurs spécialisés)
     - Serveur MCP GitHub
     - Serveur MCP Azure DevOps
     - Serveur MCP MarkItDown
     - Serveur MCP SQL Server
     - Serveur MCP Playwright
     - Serveur MCP Dev Box
     - Serveur MCP Azure AI Foundry
     - Serveur MCP Microsoft 365 Agents Toolkit

9. **Bonnes pratiques (08-BestPractices/)**
   - Optimisation des performances
   - Conception de systèmes MCP tolérants aux pannes
   - Stratégies de test et de résilience

10. **Études de cas (09-CaseStudy/)**
    - **Sept études de cas complètes** démontrant la polyvalence du MCP dans divers scénarios :
    - **Agents de voyage Azure AI** : Orchestration multi-agents avec Azure OpenAI et AI Search
    - **Intégration Azure DevOps** : Automatisation des processus de workflow avec des mises à jour de données YouTube
    - **Récupération de documentation en temps réel** : Client console Python avec streaming HTTP
    - **Générateur de plan d'étude interactif** : Application web Chainlit avec IA conversationnelle
    - **Documentation intégrée à l'éditeur** : Intégration VS Code avec workflows GitHub Copilot
    - **Gestion des API Azure** : Intégration d'API d'entreprise avec création de serveurs MCP
    - **Registre MCP GitHub** : Développement d'écosystèmes et plateforme d'intégration agentique
    - Exemples d'implémentation couvrant l'intégration d'entreprise, la productivité des développeurs et le développement d'écosystèmes

11. **Atelier pratique (10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/)**
    - Atelier pratique complet combinant MCP avec AI Toolkit
    - Création d'applications intelligentes reliant des modèles d'IA à des outils du monde réel
    - Modules pratiques couvrant les fondamentaux, le développement de serveurs personnalisés et les stratégies de déploiement en production
    - **Structure des laboratoires** :
      - Lab 1 : Fondamentaux des serveurs MCP
      - Lab 2 : Développement avancé de serveurs MCP
      - Lab 3 : Intégration de l'AI Toolkit
      - Lab 4 : Déploiement en production et mise à l'échelle
    - Approche d'apprentissage basée sur des laboratoires avec instructions pas à pas

12. **Laboratoires d'intégration de bases de données pour serveurs MCP (11-MCPServerHandsOnLabs/)**
    - **Parcours d'apprentissage complet en 13 laboratoires** pour construire des serveurs MCP prêts pour la production avec intégration PostgreSQL
    - **Implémentation d'analytique de vente au détail en conditions réelles** utilisant le cas d'utilisation Zava Retail
    - **Modèles de niveau entreprise** incluant la sécurité au niveau des lignes (RLS), la recherche sémantique et l'accès aux données multi-locataires
    - **Structure complète des laboratoires** :
      - **Labs 00-03 : Fondations** - Introduction, Architecture, Sécurité, Configuration de l'environnement
      - **Labs 04-06 : Construction du serveur MCP** - Conception de base de données, Implémentation du serveur MCP, Développement d'outils
      - **Labs 07-09 : Fonctionnalités avancées** - Recherche sémantique, Tests et débogage, Intégration VS Code
      - **Labs 10-12 : Production et bonnes pratiques** - Déploiement, Surveillance, Optimisation
    - **Technologies couvertes** : Framework FastMCP, PostgreSQL, Azure OpenAI, Azure Container Apps, Application Insights
    - **Résultats d'apprentissage** : Serveurs MCP prêts pour la production, modèles d'intégration de bases de données, analytique alimentée par l'IA, sécurité d'entreprise

## Ressources supplémentaires

Le dépôt inclut des ressources de soutien :

- **Dossier Images** : Contient des diagrammes et illustrations utilisés dans tout le programme
- **Traductions** : Support multilingue avec traductions automatiques de la documentation
- **Ressources officielles MCP** :
  - [Documentation MCP](https://modelcontextprotocol.io/)
  - [Spécification MCP](https://spec.modelcontextprotocol.io/)
  - [Dépôt GitHub MCP](https://github.com/modelcontextprotocol)

## Comment utiliser ce dépôt

1. **Apprentissage séquentiel** : Suivez les chapitres dans l'ordre (00 à 11) pour une expérience d'apprentissage structurée.
2. **Focus sur un langage spécifique** : Si vous êtes intéressé par un langage de programmation particulier, explorez les répertoires d'exemples pour des implémentations dans votre langage préféré.
3. **Implémentation pratique** : Commencez par la section "Premiers pas" pour configurer votre environnement et créer votre premier serveur et client MCP.
4. **Exploration avancée** : Une fois à l'aise avec les bases, plongez dans les sujets avancés pour approfondir vos connaissances.
5. **Engagement communautaire** : Rejoignez la communauté MCP via les discussions GitHub et les canaux Discord pour échanger avec des experts et d'autres développeurs.

## Clients et outils MCP

Le programme couvre divers clients et outils MCP :

1. **Clients officiels** :
   - Visual Studio Code
   - MCP dans Visual Studio Code
   - Claude Desktop
   - Claude dans VSCode
   - API Claude

2. **Clients communautaires** :
   - Cline (basé sur terminal)
   - Cursor (éditeur de code)
   - ChatMCP
   - Windsurf

3. **Outils de gestion MCP** :
   - MCP CLI
   - MCP Manager
   - MCP Linker
   - MCP Router

## Serveurs MCP populaires

Le dépôt présente divers serveurs MCP, notamment :

1. **Serveurs MCP Microsoft officiels** :
   - Serveur MCP Microsoft Learn Docs
   - Serveur MCP Azure (15+ connecteurs spécialisés)
   - Serveur MCP GitHub
   - Serveur MCP Azure DevOps
   - Serveur MCP MarkItDown
   - Serveur MCP SQL Server
   - Serveur MCP Playwright
   - Serveur MCP Dev Box
   - Serveur MCP Azure AI Foundry
   - Serveur MCP Microsoft 365 Agents Toolkit

2. **Serveurs de référence officiels** :
   - Système de fichiers
   - Fetch
   - Mémoire
   - Pensée séquentielle

3. **Génération d'images** :
   - Azure OpenAI DALL-E 3
   - Stable Diffusion WebUI
   - Replicate

4. **Outils de développement** :
   - Git MCP
   - Contrôle terminal
   - Assistant de code

5. **Serveurs spécialisés** :
   - Salesforce
   - Microsoft Teams
   - Jira & Confluence

## Contribution

Ce dépôt accueille les contributions de la communauté. Consultez la section Contributions de la communauté pour des conseils sur la manière de contribuer efficacement à l'écosystème MCP.

## Journal des modifications

| Date | Modifications |
|------|--------------||
| 29 septembre 2025 | - Ajout de la section 11-MCPServerHandsOnLabs avec un parcours d'apprentissage complet en 13 laboratoires sur l'intégration de bases de données<br>- Mise à jour de la carte visuelle du programme pour inclure les laboratoires d'intégration de bases de données<br>- Amélioration de la structure du dépôt pour refléter les onze sections principales<br>- Ajout d'une description détaillée de l'intégration PostgreSQL, du cas d'utilisation analytique de vente au détail et des modèles d'entreprise<br>- Mise à jour des directives de navigation pour inclure les sections 00-11 |
| 26 septembre 2025 | - Ajout de l'étude de cas Registre MCP GitHub à la section 09-CaseStudy<br>- Mise à jour des études de cas pour refléter sept études de cas complètes<br>- Amélioration des descriptions des études de cas avec des détails spécifiques d'implémentation<br>- Mise à jour de la carte visuelle du programme pour inclure le Registre MCP GitHub<br>- Révision de la structure du guide d'étude pour refléter l'accent sur le développement de l'écosystème |
| 18 juillet 2025 | - Mise à jour de la structure du dépôt pour inclure le Guide des serveurs MCP Microsoft<br>- Ajout d'une liste complète de 10 serveurs MCP Microsoft prêts pour la production<br>- Amélioration de la section Serveurs MCP populaires avec les serveurs MCP Microsoft officiels<br>- Mise à jour de la section Études de cas avec des exemples de fichiers réels<br>- Ajout de détails sur la structure des laboratoires pour l'atelier pratique |
| 16 juillet 2025 | - Mise à jour de la structure du dépôt pour refléter le contenu actuel<br>- Ajout de la section Clients et outils MCP<br>- Ajout de la section Serveurs MCP populaires<br>- Mise à jour de la carte visuelle du programme avec tous les sujets actuels<br>- Amélioration de la section Sujets avancés avec toutes les zones spécialisées<br>- Mise à jour des études de cas pour refléter des exemples réels<br>- Clarification de l'origine du MCP comme étant créé par Anthropic |
| 11 juin 2025 | - Création initiale du guide d'étude<br>- Ajout de la carte visuelle du programme<br>- Esquisse de la structure du dépôt<br>- Inclusion de projets exemples et de ressources supplémentaires |

---

*Ce guide d'étude a été mis à jour le 29 septembre 2025 et fournit une vue d'ensemble du dépôt à cette date. Le contenu du dépôt peut être mis à jour après cette date.*

---

**Avertissement** :  
Ce document a été traduit à l'aide du service de traduction automatique [Co-op Translator](https://github.com/Azure/co-op-translator). Bien que nous nous efforcions d'assurer l'exactitude, veuillez noter que les traductions automatisées peuvent contenir des erreurs ou des inexactitudes. Le document original dans sa langue d'origine doit être considéré comme la source faisant autorité. Pour des informations critiques, il est recommandé de recourir à une traduction professionnelle réalisée par un humain. Nous déclinons toute responsabilité en cas de malentendus ou d'interprétations erronées résultant de l'utilisation de cette traduction.