# Node-RED Make IoT Smart

## 🌐 Idioma

[![English](https://img.shields.io/badge/lang-English-blue.svg)](README.md) [![中文](https://img.shields.io/badge/lang-中文-red.svg)](README_ZH.md) [![Deutsch](https://img.shields.io/badge/lang-Deutsch-green.svg)](README_DE.md) [![Español](https://img.shields.io/badge/lang-Español-orange.svg)](README_ES.md) [![Français](https://img.shields.io/badge/lang-Français-purple.svg)](README_FR.md) [![日本語](https://img.shields.io/badge/lang-日本語-yellow.svg)](README_JA.md) [![한국어](https://img.shields.io/badge/lang-한국어-pink.svg)](README_KO.md) [![Português](https://img.shields.io/badge/lang-Português-cyan.svg)](README_PT.md) [![Русский](https://img.shields.io/badge/lang-Русский-brown.svg)](README_RU.md) [![繁體中文](https://img.shields.io/badge/lang-繁體中文-lightblue.svg)](README_TW.md)


---

Una extensión de asistente de IA diseñada específicamente para Node-RED, que hace el desarrollo de IoT más inteligente y eficiente.
[![npm version](https://badge.fury.io/js/@jhe.zheng%2Fnode-red-make-iot-smart.svg)](https://badge.fury.io/js/@jhe.zheng%2Fnode-red-make-iot-smart)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node-RED](https://img.shields.io/badge/Node--RED-2.0%2B-red)](https://nodered.org/)
## Descripción General

Node-RED Make IoT Smart es un agente de IA integral diseñado específicamente para el desarrollo de Node-RED. Proporciona asistencia de código inteligente, optimización de flujos automatizada y funciones de depuración inteligente para mejorar su experiencia de desarrollo de IoT. La extensión ahora admite seis escenarios principales: aprendizaje, soluciones, integración, desarrollo, configuración y gestión.

## Características

### 🤖 Asistente de IA

- **Sugerencias de Código Inteligentes**: Recomendaciones de código conscientes del contexto para flujos de Node-RED.
- **Análisis de Flujo Inteligente**: Analiza flujos y proporciona sugerencias de optimización.
- **Interfaz de Lenguaje Natural**: Interactúa con el entorno Node-RED usando comandos de lenguaje natural.
- **Soporte Multiidioma**: Admite chino, inglés, japonés, coreano y otros idiomas. Sigue los cambios de configuración de idioma de Node-RED.
- **Soporte Multi-Proveedor**: Basado en el framework LangChain.js, admite OpenAI, Anthropic, Google, DeepSeek y otros modelos de IA.
- **Gestión de Memoria Inteligente**: Sistema de memoria a corto y largo plazo basado en SQLite, admite historial de conversaciones, preferencias de usuario y almacenamiento de plantillas de flujo.
- **Prompts Basados en Escenarios**: Gestión de prompts basados en escenarios configurados en JSON, admite inyección de parámetros dinámicos.
- **Integración de Herramientas MCP**: Admite llamadas de herramientas del Protocolo de Contexto de Modelo (MCP), ampliando las capacidades del asistente de IA.


### 🔧 Herramientas de Desarrollo

- **Análisis de Código en Tiempo Real**: Análisis continuo de flujos de Node-RED.
- **Gestión de Configuración**: Configuración de API centralizada para diferentes proveedores de IA.
- **Barra Lateral Interactiva**: Panel de asistente de IA dedicado integrado en el editor de Node-RED.
- **Editor JSON**: Editor de archivos de configuración incorporado con resaltado de sintaxis.
- **Integración de Herramientas MCP**: Admite llamadas de herramientas del Protocolo de Contexto de Modelo (MCP), ampliando las capacidades del asistente de IA.
- **Gestión de Herramientas LangChain**: Framework de gestión de herramientas unificado, admite herramientas incorporadas y herramientas MCP.
- **Soporte Basado en Escenarios**: Soporte personalizado para siete escenarios principales:
  - **Aprendizaje**: Explica nodos y conceptos, proporciona flujos de ejemplo.
  - **Soluciones**: Proporciona varias soluciones de IoT, incluyendo JSON de flujo y guías de instalación de nodos.
  - **Integración**: Asiste en la integración de protocolos (ej. MQTT, Modbus) o software.
  - **Desarrollo**: Optimiza flujos existentes y código de nodos de función.
  - **Configuración**: Guía para modificar configuraciones de Node-RED (ej. `settings.js`).
  - **Gestión**: Admite acceso remoto, integración Git y despliegue por lotes.

### 🚀 Características Próximas

- **Depuración Remota**: Depuración remota asistida por IA de flujos de Node-RED.
- **Gestión de Equipos**: Desarrollo colaborativo con funciones de gestión de equipos.
- **Análisis Avanzado**: Perspectivas profundas sobre el rendimiento del sistema IoT.
- **Despliegue Inteligente**: Estrategias de despliegue de aplicaciones IoT guiadas por IA.

## Instalación

### Instalar desde npm

```bash
npm install @djzrs/node-red-iot-agent
```

### Instalar desde el Gestor de Paleta de Node-RED

1. Abra el editor de Node-RED.
2. Vaya a **Menú → Gestionar paleta**.
3. Busque `@djzrs/node-red-iot-agent`.
4. Haga clic en **Instalar**.
5. Reinicie Node-RED después de la instalación.
6. Después de la instalación, verá una nueva pestaña **Asistente de IA** en la barra lateral de Node-RED.
7. Haga clic en el botón **Configurar** para configurar su proveedor de IA.
8. Seleccione de los proveedores admitidos:
   - **DeepSeek**: Opción rentable con fuertes capacidades de codificación.
   - **OpenAI**: Modelos GPT líderes en la industria.
   - **Anthropic**: Capacidades de razonamiento avanzadas con modelos Claude.
9. Ingrese su clave API y seleccione el modelo apropiado.
10. Después de la configuración, puede comenzar a usar el asistente de IA. Tenga en cuenta que después de guardar la configuración, NodeRED generará automáticamente un nodo de configuración. NodeRED mostrará cambios en el flujo, simplemente haga clic en fusionar.
11. ¡Comience a interactuar con su asistente de IA!

## Inicio Rápido
### Ingrese "Analizar nodo actual"
<img src="https://github.com/jimmyfreecoding/node-red-make-iot-smart/raw/main/public/current-node.gif" width="800" height="450" alt="Animación de demostración" />


### Ingrese "Crear un flujo de ejemplo"
<img src="https://github.com/jimmyfreecoding/node-red-make-iot-smart/raw/main/public/create-flow.gif" width="800" height="450" alt="Animación de demostración" />

### Ingrese "Verificación de salud"
<img src="https://github.com/jimmyfreecoding/node-red-make-iot-smart/raw/main/public/health-check.gif" width="800" height="450" alt="Animación de demostración" />

## Configuración

### Configuración de Depuración LangSmith (Opcional)

Para mejor depuración y monitoreo de la ejecución de LangChain, puede configurar el soporte de LangSmith:

1. Copie el archivo `.env.example` como `.env`:
   ```bash
   cp .env.example .env
   ```

2. Edite el archivo `.env` y complete su configuración de LangSmith:
   ```env
   LANGCHAIN_TRACING_V2=true
   LANGCHAIN_API_KEY=your_langsmith_api_key_here
   LANGCHAIN_PROJECT=your_project_name
   ```

3. Reinicie Node-RED para aplicar la configuración.

4. Visite [LangSmith](https://smith.langchain.com/) para ver información detallada de seguimiento de ejecución y depuración.

**Nota**: La configuración de LangSmith es opcional y no afectará las funciones básicas.

## Uso

### Interfaz de Chat Básica

- Abra la pestaña de la barra lateral **Asistente de IA**.
- Ingrese sus preguntas o instrucciones en lenguaje natural.
- Obtenga respuestas inteligentes con sugerencias de código y explicaciones.

### Selección de Escenarios

- Seleccione escenarios (Aprendizaje, Soluciones, Integración, Desarrollo, Configuración, Gestión) a través del menú desplegable en la barra lateral.
- La IA adapta las respuestas basándose en el escenario seleccionado, proporcionando herramientas relevantes y JSON de flujo.

### Procesamiento JSON/Código

- Las salidas grandes de JSON o código están ocultas detrás de botones **Ver JSON/Código** para mantener la UI limpia.
- Edite JSON de flujo en el editor incorporado con resaltado de sintaxis y aplique cambios directamente.

### Escenarios Admitidos

#### Resumen de Escenarios

| Escenario | Nombre en Español | Descripción | Herramientas Admitidas |
|-----------|-------------------|-------------|------------------------|
| learning | Modo de Aprendizaje | Asistente de aprendizaje de Node-RED, proporciona guías de enseñanza y respuestas de conocimiento | get-flows, get-nodes, create-flow, update-flow |
| solution | Modo de Soluciones | Experto en soluciones IoT, proporciona soluciones técnicas y asesoramiento de arquitectura | create-flow, update-flow, get-flows, create-subflow |
| integration | Modo de Integración | Experto en integración de sistemas, maneja conexiones de dispositivos e integración de datos | create-flow, update-flow, install-node, get-node-info |
| development | Modo de Desarrollo | Asistente de desarrollo de código, ayuda a escribir y optimizar flujos de Node-RED | create-flow, update-flow, create-subflow, get-node-info, install-node, get-flow |
| configuration | Modo de Configuración | Experto en configuración de sistemas, maneja entorno Node-RED y configuración de nodos | get_settings, update_settings, install_node, get_node_info, get_diagnostics |
| management | Modo de Gestión | Asistente de gestión de proyectos, ayuda con organización de flujos y planificación de proyectos | get-flows, create-flow, update-flow, create-subflow |
| general | Modo General | Asistente de IA general, maneja varias preguntas relacionadas con Node-RED | Sin restricciones específicas de herramientas |

#### Ejemplos de Prompts Predefinidos

| Escenario | Prompts Predefinidos |
|-----------|----------------------|
| **Modo de Aprendizaje** | • Soy nuevo en Node-RED, por favor presente los conceptos básicos y funciones principales de Node-RED<br>• Por favor explique qué son los flujos, nodos y conexiones en Node-RED<br>• ¿Cómo creo mi primer flujo simple en Node-RED? Por favor proporcione pasos detallados<br>• ¿Cuáles son los nodos principales comúnmente utilizados en Node-RED? ¿Cuáles son sus respectivas funciones? |
| **Modo de Soluciones** | • Necesito diseñar un sistema de control de hogar inteligente, por favor proporcione una arquitectura completa de solución IoT<br>• ¿Cómo construyo un sistema de recopilación y monitoreo de datos de Industria 4.0 usando Node-RED?<br>• Por favor diseñe una solución IoT agrícola, incluyendo recopilación de datos de sensores y control automatizado<br>• Quiero construir una red de monitoreo ambiental de ciudad inteligente, ¿qué solución técnica se necesita? |
| **Modo de Integración** | • ¿Cómo integro dispositivos MQTT y APIs HTTP en Node-RED? Por favor proporcione una solución de integración detallada<br>• Necesito enviar datos de sensores desde dispositivos Modbus a una base de datos en la nube, ¿cómo lo implemento?<br>• Por favor ayúdeme a diseñar un flujo de transformación de datos que convierta JSON a XML y lo envíe a un sistema de terceros<br>• ¿Cómo implemento recopilación y procesamiento unificado de datos para múltiples dispositivos con diferentes protocolos en Node-RED? |
| **Modo de Desarrollo** | • Explicación detallada y descripción del flujo actual<br>• Explicación detallada y descripción del nodo actual<br>• Por favor ayúdeme a escribir código de nodo Function que implemente filtrado de datos y conversión de formato<br>• ¿Cómo creo un nodo personalizado en Node-RED? Por favor proporcione pasos completos de desarrollo |
| **Modo de Configuración** | • ¿Cómo está la configuración actual de NodeRed?<br>• ¿Cómo está el diagnóstico actual de NodeRed?<br>• ¿Cómo configuro las configuraciones de seguridad de Node-RED, incluyendo autenticación de usuario y HTTPS?<br>• Por favor ayúdeme a optimizar la configuración de rendimiento de Node-RED y mejorar la eficiencia de ejecución del sistema<br>• ¿Cómo instalo y gestiono paquetes de nodos de terceros en Node-RED?<br>• Necesito configurar registro y monitoreo para Node-RED, ¿cómo debo configurarlo? |
| **Modo de Gestión** | • Por favor ayúdeme a crear un plan de desarrollo y hitos para un proyecto IoT<br>• ¿Cómo organizo y gestiono la estructura de flujos de proyectos grandes en Node-RED?<br>• Necesito evaluar los riesgos y calidad del proyecto actual, por favor proporcione recomendaciones de análisis<br>• ¿Cómo establezco estándares de desarrollo de Node-RED de colaboración en equipo y mejores prácticas? |
| **Modo General** | • ¿Qué es Node-RED? ¿Cuáles son sus características principales y escenarios de aplicación?<br>• Tengo un problema con Node-RED, por favor ayúdeme con el análisis y la solución<br>• Por favor recomiende algunos recursos de aprendizaje de Node-RED y mejores prácticas<br>• ¿Cómo selecciono el modo de escenario de Node-RED apropiado para resolver mis necesidades específicas? |

#### Activación Inteligente por Palabras Clave

| Escenario | Palabras Clave | Comportamiento de Activación |
|-----------|----------------|------------------------------|
| **Modo de Desarrollo** | crear flujo, generar flujo, crear flujo, nuevo flujo | Cambio automático al modo de desarrollo, genera código JSON completo de flujo Node-RED y proporciona explicaciones detalladas |
| **Modo de Configuración** | configuración actual, configuración del sistema, información de configuración, configuraciones, configuraciones actuales | Llamada automática de la herramienta get_settings para obtener información de configuración y mostrar en formato de tabla |
| **Modo de Configuración** | diagnóstico actual, diagnóstico del sistema, información de diagnóstico, verificación de salud | Llamada automática de la herramienta get_diagnostics para diagnóstico del sistema |

#### Parámetros de Entrada Dinámicos

Todos los escenarios admiten la siguiente inyección de parámetros dinámicos:
- `nodeRedVersion` - Información de versión de Node-RED
- `nodeVersion` - Información de versión de Node.js  
- `currentTime` - Marca de tiempo actual
- `selectedFlow` - Flujo actualmente seleccionado
- `selectedNodes` - Nodos actualmente seleccionados
- `lang` - Configuración de idioma actual
- `mcpTools` - Lista de herramientas MCP disponibles

Cada escenario también admite parámetros dinámicos específicos:
- **Modo de Aprendizaje**: `userLevel` (nivel de habilidad del usuario)
- **Modo de Soluciones**: `projectRequirements` (requisitos del proyecto)
- **Modo de Integración**: `integrationTargets` (objetivos de integración)
- **Modo de Desarrollo**: `developmentTask` (tarea de desarrollo)
- **Modo de Configuración**: `configurationNeeds` (necesidades de configuración)
- **Modo de Gestión**: `projectStatus` (estado del proyecto)

#### Características de Prompts del Sistema

Cada escenario está configurado con prompts del sistema especializados para asegurar que el asistente de IA pueda:
1. **Posicionamiento de Rol**: Rol profesional claro en escenarios específicos
2. **Formato de Salida**: Formatos de respuesta estructurados basados en requisitos de escenario
3. **Integración de Herramientas**: Llamada inteligente de herramientas MCP correspondientes y APIs de Node-RED
4. **Conciencia de Contexto**: Uso de parámetros dinámicos para recomendaciones personalizadas


| Escenario | Descripción                                                                    |
| --------- | ------------------------------------------------------------------------------ |
| Aprendizaje | Explica nodos/conceptos y proporciona flujos de ejemplo para aprender.        |
| Soluciones | Proporciona varias soluciones IoT con JSON de flujo y guías de instalación de nodos. |
| Integración | Asiste en la integración de protocolos/software, genera flujos correspondientes. |
| Desarrollo | Optimiza flujos existentes y código de nodos de función.                      |
| Configuración | Guía para modificar configuraciones de Node-RED (ej. `settings.js`).          |
| Gestión | Admite acceso remoto, integración Git y despliegue por lotes.                 |

## Proveedores de IA Admitidos


| Proveedor | Modelos                                 | Características                |
| --------- | --------------------------------------- | ------------------------------ |
| OpenAI    | GPT-3.5, GPT-4, GPT-4o                 | Propósito general, amplia compatibilidad |
| Anthropic | Claude-3, Claude-3.5                    | Razonamiento avanzado, enfocado en seguridad |
| Google    | Gemini Pro, Gemini Flash                | Multimodal, alto rendimiento   |
| DeepSeek  | deepseek-chat, deepseek-coder           | Rentable, enfocado en codificación |
| Otros     | Todos los proveedores LLM admitidos por LangChain.js | Alta extensibilidad, configuración flexible |

## Configuración de API

- Las claves API se almacenan localmente y se cifran.
- Admite configuraciones de múltiples proveedores.
- Cambio fácil entre diferentes proveedores y modelos.
- Configuraciones de modelo separadas para fases de planificación y ejecución.

## Desarrollo

### Estructura del Proyecto

```
├── ai-sidebar.html          # Interfaz principal de barra lateral
├── ai-sidebar-config.json   # Configuración de UI
├── make-iot-smart.html      # Plantilla de configuración de nodo
├── make-iot-smart.js        # Implementación de nodo backend
├── lib/
│   ├── langchain-manager.js # Gestor principal de LangChain
│   ├── memory-manager.js    # Gestión de memoria SQLite
│   └── scenario-manager.js  # Gestión de prompts basados en escenarios
├── config/
│   └── scenarios.json       # Archivo de configuración de escenarios
├── data/
│   └── memory.db           # Archivo de base de datos SQLite
└── package.json            # Configuración de paquete
```

### Arquitectura Técnica

Este proyecto está basado en el framework **LangChain.js** y utiliza un diseño de arquitectura modular:

- **LangChain Manager**: Gestión principal de modelos de IA, admite múltiples proveedores LLM
- **Memory Manager**: Sistema de memoria inteligente basado en SQLite, admite memoria a corto y largo plazo
- **Scenario Manager**: Gestión de prompts basados en escenarios, admite configuración JSON y parámetros dinámicos
- **Tool Manager**: Framework de gestión de herramientas unificado, integra herramientas MCP y herramientas incorporadas
- **API Layer**: Interfaz API RESTful, admite chat en streaming y ejecución de herramientas

### Contribuir

1. Hacer fork del repositorio.
2. Crear rama de características.
3. Realizar cambios y hacer commit.
4. Enviar pull request.

## Hoja de Ruta

### Fase 1 (Completada)

- ✅ Integración de asistente de IA
- ✅ Soporte multi-proveedor
- ✅ Barra lateral interactiva
- ✅ Gestión de configuración
- ✅ Soporte basado en escenarios
- ✅ Migración de arquitectura LangChain.js
- ✅ Sistema de gestión de memoria SQLite
- ✅ Integración de herramientas MCP
- ✅ Framework de gestión de herramientas unificado

### Fase 2 (Próximamente)

- 🔄 Funciones de depuración remota
- 🔄 Funciones de colaboración en equipo
- 🔄 Análisis avanzado de flujos
- 🔄 Herramientas de despliegue inteligente

### Fase 3 (Futuro)

- 📋 Sistema de gestión de equipos
- 📋 Características empresariales
- 📋 Opciones de seguridad avanzadas
- 📋 Entrenamiento de modelos personalizados

## Requisitos del Sistema

- Node.js >= 18.0.0
- Node-RED >= 2.0.0

## Licencia

Licenciado bajo la Licencia MIT. Ver archivo [LICENSE](LICENSE) para detalles.

## Soporte
El desarrollo de IA es más arte que técnica, dominar los LLMs no es una tarea simple y requiere una comprensión profunda de los modelos de IA, datos y escenarios de aplicación. Cada sesión de preguntas y respuestas puede producir resultados diferentes, las versiones iniciales a menudo no son satisfactorias, pero con la mejora de la ingeniería de prompts, gradualmente satisfará las necesidades diarias de los usuarios de Node-RED, ya sean ingenieros de TI u OT. Damos la bienvenida a más personas interesadas para unirse al proyecto.
- **Retroalimentación de Problemas**: [GitHub Issues](https://github.com/jimmyfreecoding/node-red-make-iot-smart/issues)
- **Documentación**: [Wiki](https://github.com/jimmyfreecoding/node-red-make-iot-smart/wiki)
- **Discusión**: [GitHub Discussions](https://github.com/jimmyfreecoding/node-red-make-iot-smart/discussions)

## Autor

**Zheng He**
- Email: jhe.zheng@gmail.com
- GitHub: [@jimmyfreecoding](https://github.com/jimmyfreecoding)
- Website: [https://www.makeiotsmart.com](https://www.makeiotsmart.com)
---

*¡Haga que la asistencia impulsada por IA haga su desarrollo IoT más inteligente!*

---