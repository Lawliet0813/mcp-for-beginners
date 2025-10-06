<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "ac390de870be5c02165350f6279a8831",
  "translation_date": "2025-10-06T13:17:04+00:00",
  "source_file": "study_guide.md",
  "language_code": "es"
}
-->
# Protocolo de Contexto de Modelos (MCP) para Principiantes - Guía de Estudio

Esta guía de estudio ofrece una visión general de la estructura y el contenido del repositorio para el currículo "Protocolo de Contexto de Modelos (MCP) para Principiantes". Utiliza esta guía para navegar eficientemente por el repositorio y aprovechar al máximo los recursos disponibles.

## Descripción General del Repositorio

El Protocolo de Contexto de Modelos (MCP) es un marco estandarizado para las interacciones entre modelos de IA y aplicaciones cliente. Inicialmente creado por Anthropic, MCP ahora es mantenido por la comunidad MCP a través de la organización oficial en GitHub. Este repositorio proporciona un currículo completo con ejemplos prácticos de código en C#, Java, JavaScript, Python y TypeScript, diseñado para desarrolladores de IA, arquitectos de sistemas e ingenieros de software.

## Mapa Visual del Currículo

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

## Estructura del Repositorio

El repositorio está organizado en once secciones principales, cada una enfocada en diferentes aspectos de MCP:

1. **Introducción (00-Introduction/)**
   - Descripción general del Protocolo de Contexto de Modelos
   - Importancia de la estandarización en los flujos de trabajo de IA
   - Casos de uso prácticos y beneficios

2. **Conceptos Básicos (01-CoreConcepts/)**
   - Arquitectura cliente-servidor
   - Componentes clave del protocolo
   - Patrones de mensajería en MCP

3. **Seguridad (02-Security/)**
   - Amenazas de seguridad en sistemas basados en MCP
   - Mejores prácticas para implementar seguridad
   - Estrategias de autenticación y autorización
   - **Documentación de Seguridad Completa**:
     - Mejores Prácticas de Seguridad MCP 2025
     - Guía de Implementación de Azure Content Safety
     - Controles y Técnicas de Seguridad MCP
     - Referencia Rápida de Mejores Prácticas MCP
   - **Temas Clave de Seguridad**:
     - Ataques de inyección de prompts y envenenamiento de herramientas
     - Secuestro de sesiones y problemas de "confused deputy"
     - Vulnerabilidades de paso de tokens
     - Permisos excesivos y control de acceso
     - Seguridad en la cadena de suministro de componentes de IA
     - Integración con Microsoft Prompt Shields

4. **Primeros Pasos (03-GettingStarted/)**
   - Configuración del entorno
   - Creación de servidores y clientes MCP básicos
   - Integración con aplicaciones existentes
   - Incluye secciones sobre:
     - Implementación del primer servidor
     - Desarrollo de clientes
     - Integración de clientes LLM
     - Integración con VS Code
     - Servidor de Eventos Enviados por el Servidor (SSE)
     - Uso avanzado del servidor
     - Transmisión HTTP
     - Integración con AI Toolkit
     - Estrategias de prueba
     - Directrices de despliegue

5. **Implementación Práctica (04-PracticalImplementation/)**
   - Uso de SDKs en diferentes lenguajes de programación
   - Técnicas de depuración, pruebas y validación
   - Creación de plantillas de prompts y flujos de trabajo reutilizables
   - Proyectos de ejemplo con implementaciones prácticas

6. **Temas Avanzados (05-AdvancedTopics/)**
   - Técnicas de ingeniería de contexto
   - Integración de agentes Foundry
   - Flujos de trabajo de IA multimodal
   - Demos de autenticación OAuth2
   - Capacidades de búsqueda en tiempo real
   - Transmisión en tiempo real
   - Implementación de contextos raíz
   - Estrategias de enrutamiento
   - Técnicas de muestreo
   - Enfoques de escalabilidad
   - Consideraciones de seguridad
   - Integración de seguridad Entra ID
   - Integración de búsqueda web

7. **Contribuciones de la Comunidad (06-CommunityContributions/)**
   - Cómo contribuir con código y documentación
   - Colaboración a través de GitHub
   - Mejoras y comentarios impulsados por la comunidad
   - Uso de varios clientes MCP (Claude Desktop, Cline, VSCode)
   - Trabajo con servidores MCP populares, incluida la generación de imágenes

8. **Lecciones de la Adopción Temprana (07-LessonsfromEarlyAdoption/)**
   - Implementaciones reales y casos de éxito
   - Construcción y despliegue de soluciones basadas en MCP
   - Tendencias y hoja de ruta futura
   - **Guía de Servidores MCP de Microsoft**: Guía completa de 10 servidores MCP de Microsoft listos para producción, incluyendo:
     - Servidor MCP de Microsoft Learn Docs
     - Servidor MCP de Azure (15+ conectores especializados)
     - Servidor MCP de GitHub
     - Servidor MCP de Azure DevOps
     - Servidor MCP de MarkItDown
     - Servidor MCP de SQL Server
     - Servidor MCP de Playwright
     - Servidor MCP de Dev Box
     - Servidor MCP de Azure AI Foundry
     - Servidor MCP del Kit de Herramientas de Agentes de Microsoft 365

9. **Mejores Prácticas (08-BestPractices/)**
   - Optimización y ajuste de rendimiento
   - Diseño de sistemas MCP tolerantes a fallos
   - Estrategias de prueba y resiliencia

10. **Estudios de Caso (09-CaseStudy/)**
    - **Siete estudios de caso completos** que demuestran la versatilidad de MCP en diversos escenarios:
    - **Agentes de Viajes de Azure AI**: Orquestación multi-agente con Azure OpenAI y AI Search
    - **Integración con Azure DevOps**: Automatización de procesos de flujo de trabajo con actualizaciones de datos de YouTube
    - **Recuperación de Documentación en Tiempo Real**: Cliente de consola en Python con transmisión HTTP
    - **Generador Interactivo de Planes de Estudio**: Aplicación web Chainlit con IA conversacional
    - **Documentación en el Editor**: Integración de VS Code con flujos de trabajo de GitHub Copilot
    - **Gestión de API de Azure**: Integración empresarial de API con creación de servidores MCP
    - **Registro MCP de GitHub**: Desarrollo de ecosistemas y plataforma de integración agentic
    - Ejemplos de implementación que abarcan integración empresarial, productividad del desarrollador y desarrollo de ecosistemas

11. **Taller Práctico (10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/)**
    - Taller práctico completo que combina MCP con AI Toolkit
    - Creación de aplicaciones inteligentes que conectan modelos de IA con herramientas del mundo real
    - Módulos prácticos que cubren fundamentos, desarrollo de servidores personalizados y estrategias de despliegue en producción
    - **Estructura del Taller**:
      - Laboratorio 1: Fundamentos del Servidor MCP
      - Laboratorio 2: Desarrollo Avanzado de Servidores MCP
      - Laboratorio 3: Integración con AI Toolkit
      - Laboratorio 4: Despliegue y Escalado en Producción
    - Enfoque de aprendizaje basado en laboratorios con instrucciones paso a paso

12. **Laboratorios de Integración de Bases de Datos con Servidores MCP (11-MCPServerHandsOnLabs/)**
    - **Ruta de aprendizaje de 13 laboratorios** para construir servidores MCP listos para producción con integración de PostgreSQL
    - **Implementación de análisis minorista en el mundo real** utilizando el caso de uso de Zava Retail
    - **Patrones de nivel empresarial** que incluyen Seguridad a Nivel de Fila (RLS), búsqueda semántica y acceso a datos multi-tenant
    - **Estructura Completa de los Laboratorios**:
      - **Laboratorios 00-03: Fundamentos** - Introducción, Arquitectura, Seguridad, Configuración del Entorno
      - **Laboratorios 04-06: Construcción del Servidor MCP** - Diseño de Base de Datos, Implementación del Servidor MCP, Desarrollo de Herramientas
      - **Laboratorios 07-09: Funciones Avanzadas** - Búsqueda Semántica, Pruebas y Depuración, Integración con VS Code
      - **Laboratorios 10-12: Producción y Mejores Prácticas** - Despliegue, Monitoreo, Optimización
    - **Tecnologías Cubiertas**: Marco FastMCP, PostgreSQL, Azure OpenAI, Azure Container Apps, Application Insights
    - **Resultados de Aprendizaje**: Servidores MCP listos para producción, patrones de integración de bases de datos, análisis impulsado por IA, seguridad empresarial

## Recursos Adicionales

El repositorio incluye recursos de apoyo:

- **Carpeta de Imágenes**: Contiene diagramas e ilustraciones utilizados a lo largo del currículo
- **Traducciones**: Soporte multilingüe con traducciones automáticas de la documentación
- **Recursos Oficiales de MCP**:
  - [Documentación de MCP](https://modelcontextprotocol.io/)
  - [Especificación de MCP](https://spec.modelcontextprotocol.io/)
  - [Repositorio de MCP en GitHub](https://github.com/modelcontextprotocol)

## Cómo Usar Este Repositorio

1. **Aprendizaje Secuencial**: Sigue los capítulos en orden (00 al 11) para una experiencia de aprendizaje estructurada.
2. **Enfoque por Lenguaje**: Si te interesa un lenguaje de programación en particular, explora los directorios de ejemplos para implementaciones en tu lenguaje preferido.
3. **Implementación Práctica**: Comienza con la sección "Primeros Pasos" para configurar tu entorno y crear tu primer servidor y cliente MCP.
4. **Exploración Avanzada**: Una vez que domines los conceptos básicos, profundiza en los temas avanzados para ampliar tus conocimientos.
5. **Participación Comunitaria**: Únete a la comunidad MCP a través de discusiones en GitHub y canales de Discord para conectarte con expertos y otros desarrolladores.

## Clientes y Herramientas MCP

El currículo cubre varios clientes y herramientas MCP:

1. **Clientes Oficiales**:
   - Visual Studio Code 
   - MCP en Visual Studio Code
   - Claude Desktop
   - Claude en VSCode 
   - API de Claude

2. **Clientes de la Comunidad**:
   - Cline (basado en terminal)
   - Cursor (editor de código)
   - ChatMCP
   - Windsurf

3. **Herramientas de Gestión MCP**:
   - MCP CLI
   - MCP Manager
   - MCP Linker
   - MCP Router

## Servidores MCP Populares

El repositorio presenta varios servidores MCP, incluyendo:

1. **Servidores MCP Oficiales de Microsoft**:
   - Servidor MCP de Microsoft Learn Docs
   - Servidor MCP de Azure (15+ conectores especializados)
   - Servidor MCP de GitHub
   - Servidor MCP de Azure DevOps
   - Servidor MCP de MarkItDown
   - Servidor MCP de SQL Server
   - Servidor MCP de Playwright
   - Servidor MCP de Dev Box
   - Servidor MCP de Azure AI Foundry
   - Servidor MCP del Kit de Herramientas de Agentes de Microsoft 365

2. **Servidores de Referencia Oficiales**:
   - Sistema de Archivos
   - Fetch
   - Memoria
   - Pensamiento Secuencial

3. **Generación de Imágenes**:
   - Azure OpenAI DALL-E 3
   - Stable Diffusion WebUI
   - Replicate

4. **Herramientas de Desarrollo**:
   - Git MCP
   - Control de Terminal
   - Asistente de Código

5. **Servidores Especializados**:
   - Salesforce
   - Microsoft Teams
   - Jira & Confluence

## Contribuciones

Este repositorio da la bienvenida a contribuciones de la comunidad. Consulta la sección de Contribuciones de la Comunidad para obtener orientación sobre cómo contribuir de manera efectiva al ecosistema MCP.

## Registro de Cambios

| Fecha | Cambios |
|------|---------||
| 29 de septiembre de 2025 | - Se agregó la sección 11-MCPServerHandsOnLabs con una ruta de aprendizaje de 13 laboratorios sobre integración de bases de datos<br>- Se actualizó el Mapa Visual del Currículo para incluir los Laboratorios de Integración de Bases de Datos<br>- Se mejoró la estructura del repositorio para reflejar once secciones principales<br>- Se agregó una descripción detallada de la integración con PostgreSQL, el caso de uso de análisis minorista y patrones empresariales<br>- Se actualizó la guía de navegación para incluir las secciones 00-11 |
| 26 de septiembre de 2025 | - Se agregó el estudio de caso Registro MCP de GitHub a la sección 09-CaseStudy<br>- Se actualizaron los Estudios de Caso para reflejar siete estudios de caso completos<br>- Se mejoraron las descripciones de los estudios de caso con detalles específicos de implementación<br>- Se actualizó el Mapa Visual del Currículo para incluir el Registro MCP de GitHub<br>- Se revisó la estructura de la guía de estudio para reflejar el enfoque en el desarrollo del ecosistema |
| 18 de julio de 2025 | - Se actualizó la estructura del repositorio para incluir la Guía de Servidores MCP de Microsoft<br>- Se agregó una lista completa de 10 servidores MCP de Microsoft listos para producción<br>- Se mejoró la sección de Servidores MCP Populares con los Servidores MCP Oficiales de Microsoft<br>- Se actualizó la sección de Estudios de Caso con ejemplos de archivos reales<br>- Se agregaron detalles de la Estructura del Taller para el Taller Práctico |
| 16 de julio de 2025 | - Se actualizó la estructura del repositorio para reflejar el contenido actual<br>- Se agregó la sección de Clientes y Herramientas MCP<br>- Se agregó la sección de Servidores MCP Populares<br>- Se actualizó el Mapa Visual del Currículo con todos los temas actuales<br>- Se mejoró la sección de Temas Avanzados con todas las áreas especializadas<br>- Se actualizaron los Estudios de Caso para reflejar ejemplos reales<br>- Se aclaró el origen de MCP como creado por Anthropic |
| 11 de junio de 2025 | - Creación inicial de la guía de estudio<br>- Se agregó el Mapa Visual del Currículo<br>- Se delineó la estructura del repositorio<br>- Se incluyeron proyectos de ejemplo y recursos adicionales |
| 6 de octubre de 2025 | Se agregó una lección sobre uso avanzado del servidor |

---

*Esta guía de estudio fue actualizada el 29 de septiembre de 2025 y proporciona una visión general del repositorio hasta esa fecha. El contenido del repositorio puede actualizarse después de esta fecha.*

---

**Descargo de responsabilidad**:  
Este documento ha sido traducido utilizando el servicio de traducción automática [Co-op Translator](https://github.com/Azure/co-op-translator). Aunque nos esforzamos por garantizar la precisión, tenga en cuenta que las traducciones automatizadas pueden contener errores o imprecisiones. El documento original en su idioma nativo debe considerarse como la fuente autorizada. Para información crítica, se recomienda una traducción profesional realizada por humanos. No nos hacemos responsables de malentendidos o interpretaciones erróneas que puedan surgir del uso de esta traducción.