# Capítulo IV: Product Implementation & Validation

## 4. Product Implementation & Validation

### 4.1. Software Configuration Management
Todo software requiere distintos entornos para su desarrollo, validación, despliegue y funcionamiento.  
La configuración del entorno de implementación consiste en establecer y mantener estos espacios de trabajo, asegurando que cada fase del ciclo de vida del proyecto cuente con las condiciones necesarias.  
Por ello, en esta sección se describen las principales herramientas empleadas para la gestión y configuración de dichos entornos.

**4.1.1.** Software Development Environment Configuration  
### Project Management  
**1. [WhatsApp](https://www.whatsapp.com/)**  
Usamos WhatsApp como nuestro principal medio de comunicación y coordinación del equipo.  
Nos permitió mantener una comunicación constante, compartir avances rápidamente y realizar llamadas grupales para discutir decisiones importantes del proyecto.  

---

### Requirements Management  
**1. [Trello](https://trello.com/)**  
Usamos esta herramienta para el manejo de nuestros requerimientos con el objetivo de organizar de manera más efectiva el backlog en equipo.  
Trello es una aplicación para gestionar proyectos. Te permite crear y organizar tareas, plazos y equipos.  
Trello se adapta a cualquier tipo de proyecto y se integra con otras aplicaciones.  

---

### Product UX/UI Design  
**1. [UXPressia](https://uxpressia.com/)**  
Esta herramienta nos ayudó en el desarrollo de nuestras *User Personas*, *Customer Journey Map*, *Empathy Map* e *Impact Map*,  
debido a que ofrece plantillas que facilitan el desarrollo ágil de estos artefactos.  

**2. [Mural](https://www.mural.co/)**  
Realizamos nuestro *Scenario Mapping* para nuestros dos segmentos objetivos,  
debido a que Mural es una herramienta fácil de usar y brinda plantillas de uso libre.  

**3. [Figma](https://www.figma.com/)**  
Usamos esta herramienta para la creación de nuestros *Wireframes*, *Mockups* y *Mobile Application Prototypes*,  
ya que permite trabajar de manera colaborativa y cuenta con múltiples utilidades.  

---

### Software Development  
**1. Landing Page**  
Para el desarrollo de nuestra *Landing Page* usamos herramientas básicas para el diseño de páginas web como lo son:  
**HTML5**, **CSS3** y **JavaScript**.  

**2. Android Studio**  
Empleamos **Android Studio** como entorno de desarrollo integrado (IDE) para la creación y prueba de nuestra aplicación móvil nativa.  
Esta herramienta nos permitió implementar funcionalidades directamente sobre Android, realizar emulaciones en distintos dispositivos  
y optimizar el rendimiento de la app mediante Kotlin y XML.  

---

### Software Documentation  
**1. [LucidChart](https://lucid.app/)**  
Esta herramienta la usamos para el desarrollo de *User Flow Diagrams*, *Wireflows* y el *Diagrama de Clases*.  
En LucidChart se pueden crear diversos diagramas de forma rápida y colaborativa.  

**2. [Structurizr](https://www.structurizr.com/)**  
Nos permitió realizar los diagramas **C4** de manera rápida con el lenguaje de programación **C#**.  

**3. [Vertabelo](https://vertabelo.com/)**  
Realizamos nuestra base de datos en esta herramienta debido a que cuenta con una amplia variedad de motores  
y permite trabajar colaborativamente.  

**4.1.2.** Source Code Management  

La gestión y actualización tanto de nuestra *landing page* como de este informe se llevaron a cabo mediante un repositorio colaborativo en **[GitHub](https://github.com/)**,donde administramos el control de versiones y registramos los cambios realizados por cada integrante del equipo. 

**Organization:** [https://github.com/1ACC0238-2520-14650-VIBE-STAGE](https://github.com/1ACC0238-2520-14650-VIBE-STAGE)  
**Landing Page Repository:** [https://github.com/1ACC0238-2520-14650-VIBE-STAGE/Landing-Page](https://github.com/1ACC0238-2520-14650-VIBE-STAGE/Landing-Page)  
**Report Repository:** [https://github.com/1ACC0238-2520-14650-VIBE-STAGE/Vibestage-Report](https://github.com/1ACC0238-2520-14650-VIBE-STAGE/Vibestage-Report)

Para optimizar la organización del código y asegurar un flujo de trabajo ordenado, implementamos la metodología **GitFlow**,  
que facilita la creación y administración de ramas durante el ciclo de desarrollo.  
Dentro de esta estructura, mantenemos dos ramas principales:  

- **Main:** Contiene la versión estable y lista para producción del proyecto, representando el historial oficial de lanzamientos.  
- **Develop:** Funciona como la rama central de integración, donde se reúnen y prueban las nuevas funcionalidades antes de ser publicadas.  

Además, utilizamos ramas auxiliares llamadas **Feature**, destinadas a la implementación de nuevas características o mejoras.  
Estas ramas parten de *develop* y se integran nuevamente una vez completadas, lo que permite trabajar en paralelo sin comprometer la estabilidad del entorno principal.  

**4.1.3.** Source Code Style Guide & Conventions  
**4.1.4.** Software Deployment Configuration  

### 4.2. *Landing Page & Mobile Application Implementation*
#### 4.2.1. *Sprint 1*
**4.2.1.1.** Sprint Planning 1 

| **Sprint #** | **Sprint 1** |
|---------------|--------------|
| **Sprint Planning Background** | |
| **Date** | 08/10/2025 |
| **Time** | 16:00 pm |
| **Location** | Modalidad remota por Discord |
| **Prepared By** | Equipo VibeStage |
| **Attendees** | Todos los miembros del grupo VibeStage |
| **Sprint n - 0 Review Summary** | Se desarrolló la **Landing Page** y la primera versión de la **Aplicación móvil**, ambas alineadas con los objetivos del proyecto *VibeStage*. <br><br> **Landing Page:** Propósito claro de la plataforma, Navegación fluida entre secciones, Diseño responsive adaptable,Versión en inglés y soporte multilenguaje, Formulario de contacto funcional, Selección del tipo de usuario,Visualización de planes por tipo de usuario, Botones CTA funcionales, Menú fijo con desplazamiento suave, Sección del equipo visible, Botón de “Enviar” funcional. <br><br> **Aplicación móvil:** Registro de artista, Acceso al dashboard del artista, Búsqueda de eventos por afinidad, Postulación rápida a eventos, Registro del promotor/local, Dashboard del promotor/local, Registro de usuario con selección de rol, Inicio de sesión con credenciales, Agenda de eventos del artista. <br><br> **Notas técnicas:** Se implementó estructura modular, pantallas por rol, flujo de registro y login funcional, navegación estable, interfaz coherente con la identidad visual de VibeStage y componentes reutilizables con Material Design. |
| **Sprint n - 1 Retrospective Summary** | **Puntos positivos:** Se logró cumplir el alcance total del Sprint, entregando una experiencia funcional tanto en la web como en la app. Se consolidó la base de la arquitectura, diseño visual, navegación, e internacionalización. <br> **Aspectos destacados:** Alta cohesión en equipo, cumplimiento de tiempos, y pruebas exitosas en dispositivos móviles y navegadores. <br> **Próximos pasos:** (1) Integración con backend para gestión real de datos; (2) implementación de base de datos; (3) optimización SEO y despliegue productivo; (4) conexión del módulo de eventos, pagos y reputación. |
| **Sprint Goal & User Stories** | **Objetivo del Sprint 1:** Implementar la base visual y funcional de *VibeStage* (Landing Page y App Móvil) para presentar el propósito del producto, atraer nuevos usuarios (artistas y promotores) y establecer el flujo inicial de registro y navegación por rol. <br><br> **User Stories desarrolladas:** <br> - *Landing Page:* US01, US02, US03, US04, US05, US06, US21, US22, US23, US24, US26. <br> - *Aplicación móvil:* US07, US08, US09, US10, US14, US15, US31, US32, US34. <br><br> **Technical Stories :** TS1, TS2, TS3, TS4, TS5, TS6, TS7, TS8, TS9, TS10, TS11.|
| **Sprint 1 Velocity** | **Total de HU completadas:** 19   |  **Velocidad total:** 19 puntos |  **Estado general:** Sprint 1 completado exitosamente con todos los entregables funcionales y alineados al MVP de VibeStage. |

**4.2.1.2.** Sprint Backlog 1  

En esta sección se especifican los detalles del Sprint Backlog, que es una lista de tareas que se deben realizar para completar el Sprint.

| **Sprint #** | **Sprint 1** |
|---------------|--------------|

| **User Story** | **Work-Item / Task** | | | | | |
|----------------|----------------------|---|---|---|---|---|
| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status (To-do / In-Process / To-Review / Done)** |
| **US01** | Propósito claro de la plataforma | **T01** | Implementar encabezado principal y tagline | Mostrar el propósito de VibeStage y botón de acción principal. | 2 | Stephano Landauri | Done |
| | | **T02** | Agregar logotipo y menú principal | Incluir logo, navegación y enlaces internos. | 2 | Carlos Álvarez | Done |
| **US02** | Navegación fluida entre secciones | **T03** | Implementar scroll suave | Permitir desplazamiento fluido por anclas internas del menú. | 1 | Juan Paul Llamccaya | Done |
| | | **T04** | Configurar navegación responsive | Asegurar que el menú se adapte correctamente a todos los dispositivos. | 1.5 | Gabriel Lapa | Done |
| **US03** | Diseño responsive adaptable | **T05** | Crear media queries | Asegurar visualización correcta en móviles y tablets. | 2 | Rafael Cuya | Done |
| **US04** | Implementar versión en inglés | **T06** | Configurar traducción ES/EN | Añadir archivo `translations.js` y textos bilingües. | 2 | Stephano Landauri | Done |
| **US05** | Formulario de contacto funcional | **T07** | Crear formulario con validaciones | Implementar inputs, validación y mensaje de confirmación. | 3 | Carlos Álvarez | Done |
| **US06** | Selección del tipo de usuario | **T08** | Agregar botones “Soy artista” / “Soy local” | Redirigir a flujo de registro según rol. | 2 | Juan Paul Llamccaya | Done |
| **US21** | Visualización de planes | **T09** | Crear sección de planes | Mostrar planes para artistas y locales con sus características. | 3 | Gabriel Lapa | Done |
| **US22** | Botones CTA funcionales | **T10** | Implementar botones de registro | Añadir acciones directas hacia el registro desde la landing. | 1 | Rafael Cuya | Done |
| **US23** | Menú fijo y desplazamiento suave | **T11** | Añadir efecto sticky al menú | Mantener visible el menú durante el desplazamiento. | 1.5 | Stephano Landauri | Done |
| **US24** | Sección del equipo visible | **T12** | Crear sección "Nuestro equipo" | Mostrar foto, rol y enlaces de cada miembro. | 3 | Carlos Álvarez | Done |
| **US26** | Botón “Enviar” funcional | **T13** | Añadir botón de envío en contacto | Validar datos y mostrar mensaje de éxito. | 1 | Rafael Cuya | Done |
| **US07** | Registro de artista | **T14** | Diseñar formulario de registro | Crear flujo visual de registro para artistas. | 3 | Stephano Landauri | Done |
| **US08** | Dashboard del artista | **T15** | Crear vista principal del artista | Incluir resumen de perfil, agenda y eventos. | 4 | Carlos Álvarez | Done |
| **US14** | Registro del promotor/local | **T16** | Crear flujo de registro para locales | Implementar formulario y vista inicial. | 2.5 | Juan Paul Llamccaya | Done |
| **US15** | Dashboard del promotor/local | **T17** | Diseñar panel administrativo | Mostrar publicaciones, agenda y evaluaciones. | 3 | Gabriel Lapa | Done |
| **US31** | Registro con selección de rol | **T18** | Implementar elección de rol | Permitir elegir entre Artista o Local al registrarse. | 2 | Rafael Cuya | Done |
| **US32** | Inicio de sesión | **T19** | Crear flujo de login | Iniciar sesión y redirigir al dashboard. | 3 | Stephano Landauri | Done |
| **US34** | Agenda del artista | **T20** | Crear vista de agenda | Mostrar eventos confirmados con fechas y estados. | 2 | Carlos Álvarez | Done |
| **TS01** | Implementación del encabezado | **T21** | Crear estructura HTML/CSS del header | Mostrar tagline y botón principal. | 1.5 | Stephano Landauri | Done |
| **TS02** | Menú fijo y navegación | **T22** | Agregar lógica JS del menú responsive | Controlar apertura/cierre del menú y scroll. | 2 | Rafael Cuya | Done |
| **TS03** | Diseño responsive | **T23** | Configurar estilos adaptativos | Ajustar tamaños, grillas y tipografía por dispositivo. | 2 | Carlos Álvarez | Done |
| **TS04** | Implementar traducción EN/ES | **T24** | Desarrollar archivo `translations.js` | Definir textos multilenguaje. | 1.5 | Stephano Landauri | Done |
| **TS05** | Formulario de contacto | **T25** | Añadir validación JS | Mostrar alertas de confirmación o error. | 2 | Juan Paul Llamccaya | Done |
| **TS06** | Botones de registro por rol | **T26** | Vincular botones CTA con secciones de registro | Habilitar navegación dinámica. | 1.5 | Gabriel Lapa | Done |
| **TS07** | Sección de testimonios | **T27** | Crear sección “Testimonios” | Incluir tarjetas con nombre, rol y opinión. | 2 | Carlos Álvarez | Done |
| **TS08** | Diagrama de contexto del artista | **T28** | Elaborar C4 Context Diagram | Mostrar interacción del artista con servicios externos. | 2 | Stephano Landauri | Done |
| **TS09** | Componentes de eventos | **T29** | Crear C4 de componentes | Mostrar interacción entre servicios de eventos. | 2.5 | Rafael Cuya | Done |
| **TS10** | Contratos y Riders | **T30** | Diseñar diagrama C4 del módulo | Representar flujo de firma digital y validación técnica. | 2 | Juan Paul Llamccaya | Done |
| **TS11** | Pagos y reputación | **T31** | Generar código estructurado del backend simulado | Mostrar endpoints y entidades de pagos/evaluaciones. | 3 | Stephano Landauri | Done |

**4.2.1.3.** Development Evidence for Sprint Review 

| **Repository** | **Branch** | **Commit ID** | **Author** | **Message** | **Time ago** |
|----------------|-------------|---------------|-------------|--------------|---------------|
| **vibestage-kotlin-app** | main | c1c8c1b | bluexdev | feat: fix style | 08/10/2025 |
| vibestage-kotlin-app | main | 347def1 | bluexdev | feat: fix style | 08/10/2025 |
| vibestage-kotlin-app | main | 584574d | bluexdev | feat: fix style | 08/10/2025 |
| vibestage-kotlin-app | main | 7382f26 | bluexdev | feat(promoter): release version 2 with navigation and UI bug fixes | 06/10/2025 |
| vibestage-kotlin-app | main | d2d79c1 | bluexdev | Initial version | 05/10/2025 |
| **Landing Page** | main | 47c98e9 | bluexdev | feat: add new team member to landing page with photo, name, and alt text | 17/09/2025 |
| Landing Page | main | ac3175c | Rafael Cuya | Feat added some pictures | 17/09/2025 |
| Landing Page | main | ed6a9bf | Rafael Cuya | Merge remote-tracking branch 'origin/main' | 17/09/2025 |
| Landing Page | main | e197375 | Rafael Cuya | Feat added style | 17/09/2025 |
| Landing Page | main | 4426a42 | Rafael Cuya | Feat added main-en | 17/09/2025 |
| Landing Page | main | 8904fd8 | Rafael Cuya | Feat added main.js | 17/09/2025 |
| Landing Page | main | 8a91016 | Rafael Cuya | Feat added index | 17/09/2025 |
| Landing Page | main | a746977 | Rafael Cuya | Feat added translation | 17/09/2025 |
| Landing Page | main | aff4c44 | Rafael Cuya | Feat added pictures | 17/09/2025 |
| Landing Page | main | 7bd30af | Rafael Cuya | feat added README | 17/09/2025 |
| Landing Page | main | 8cc4fc3 | Rafael Cuya | Feat added Readme | 17/09/2025 |
| Landing Page | main | 961ad56 | Rafael Cuya | Initial commit | 17/09/2025 |

**4.2.1.4.** Testing Suite Evidence for Sprint Review  
**4.2.1.5.** Execution Evidence for Sprint Review  
**4.2.1.6.** Services Documentation Evidence for Sprint Review  
**4.2.1.7.** Software Deployment Evidence for Sprint Review  
**4.2.1.8.** Team Collaboration Insights during Sprint  

#### 4.3. *Validation Interviews*
**4.3.1.** Diseño de Entrevistas  
**4.3.2.** Registro de Entrevistas  
**4.3.3.** Evaluaciones según heurísticas  
