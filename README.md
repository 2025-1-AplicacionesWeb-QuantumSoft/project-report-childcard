<h1 align="center"> UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS </h1>

<h2 align="center"> INGENIERIA DE SOFTWARE</h2>
<h2 align="center"> CICLO 2025-1</h2>

<div align="center">
    <img src="./assets/logo-upc.png">
</div>

<br>
<h3 align="center"> Aplicaciones Web - WS51 </h3>
<h3 align="center"> Profesor del Curso: Hugo Allan Mori Paiva </h3>
<h3 align="center"> "INFORME DE TRABAJO FINAL"</h3>
<h3 align="center"> Nombre de Startup: QuantumSoft  </h3>
<h3 align="center"> Nombre del Producto: ChildCard  </h3>

<div align="center">

| Miembro                       |   Código   |
| :---------------------------- | :--------: |
| Meza Camayo, Lynn Jeeferzon   | U20201C320 |
| Fajardo Monrroy, Walter Luis  | U202221632 |
| Cuentas Peña, Joaquin Alberto | U20201F788 |

</div>
<h3 align="center"> ABRIL - 2025   </h3>

## REGISTRO DE VERSIONES

| Versión | Fecha    | Autor     | Descripción de Modificación            |
| ------- | -------- | --------- | -------------------------------------- |
| 0.1     | 03/04/25 | Lynn Meza | Desarrollo de la Structura del informe |
|         |          |           |                                        |
|         |          |           |                                        |

## PROJECT REPORT COLLABORATION INSIGHTS

URL del repositorio del project Report : [https://github.com/2025-1-AplicacionesWeb-QuantumSoft/project-report-childcard](https://github.com/2025-1-AplicacionesWeb-QuantumSoft/project-report-childcard)

**_TB1_**

Para el desarrollo de la entrega TB1, se desarrollo las actividades de elaboracion del informe de la siguiente manera:

## CONTENIDO

### Tabla de contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process.](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores.](#21-competidores)
    - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas.](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
    - [2.3.1. User Personas.](#231-user-personas)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping.](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language.](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping.](#31-to-be-scenario-mapping)
  - [3.2. User Stories.](#32-user-stories)
  - [3.3. Impact Mapping.](#33-impact-mapping)
  - [3.4. Product Backlog.](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
  - [4.2. Information Architecture.](#42-information-architecture)
    - [4.2.1. Organization Systems.](#421-organization-systems)
    - [4.2.2. Labeling Systems.](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems.](#424-searching-systems)
    - [4.2.5. Navigation Systems.](#425-navigation-systems)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design.](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)
    - [4.4.2. Web Applications Mock-ups.](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams.](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram.](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design.](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams.](#471-class-diagrams)
    - [4.7.2. Class Dictionary.](#472-class-dictionary)
  - [4.8. Database Design.](#48-database-design)
    - [4.8.1. Database Diagram.](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1.](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog n.](#5213-sprint-backlog-n)
      - [5.2.1.4. Development Evidence for Sprint Review.](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews.](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas.](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas.](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas.](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product.](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)
  - [Video About-the-Team.](#video-about-the-team)
  - [Bibliografía Anexos](#bibliografía-anexos)

### Tabla de imagenes

## STUDENT OUTCOME

<table>
    <tr>
        <th>CRITERIO ESPECIFICO</th>
        <th>ACCIONES REALIZADAS</th>
        <th>CONCLUSIONES</th>
    </tr>
    <tr>
        <th>Trabaja en equipo para proporcionar liderazgo en forma conjunta</th>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <th>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos</th>
        <td></td>
        <td></td>
    </tr>
</table>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

#### 1.2.2.2. Lean UX Assumptions.

#### 1.2.2.3. Lean UX Hypothesis Statements.

#### 1.2.2.4. Lean UX Canvas.

## 1.3. Segmentos objetivo.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.

### 2.1.1. Análisis competitivo.

### 2.1.2. Estrategias y tácticas frente a competidores.

## 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.

### 2.2.2. Registro de entrevistas.

### 2.2.3. Análisis de entrevistas.

## 2.3. Needfinding.

### 2.3.1. User Personas.

### 2.3.2. User Task Matrix.

### 2.3.3. User Journey Mapping.

### 2.3.4. Empathy Mapping.

### 2.3.5. As-is Scenario Mapping.

## 2.4. Ubiquitous Language.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

## 3.2. User Stories.

## 3.3. Impact Mapping.

## 3.4. Product Backlog.

# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.

### 4.1.2. Web Style Guidelines.

## 4.2. Information Architecture.

### 4.2.1. Organization Systems.

### 4.2.2. Labeling Systems.

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems.

### 4.2.5. Navigation Systems.

## 4.3. Landing Page UI Design.

### 4.3.1. Landing Page Wireframe.

### 4.3.2. Landing Page Mock-up.

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.

### 4.4.2. Web Applications Wireflow Diagrams.

### 4.4.2. Web Applications Mock-ups.

### 4.4.3. Web Applications User Flow Diagrams.

## 4.5. Web Applications Prototyping.

## 4.6. Domain-Driven Software Architecture.

### 4.6.1. Software Architecture Context Diagram.

### 4.6.2. Software Architecture Container Diagrams.

### 4.6.3. Software Architecture Components Diagrams.

## 4.7. Software Object-Oriented Design.

### 4.7.1. Class Diagrams.

### 4.7.2. Class Dictionary.

## 4.8. Database Design.

### 4.8.1. Database Diagram.

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.

### 5.1.2. Source Code Management.

### 5.1.3. Source Code Style Guide & Conventions.

### 5.1.4. Software Deployment Configuration.

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.

El equipo de desarrollo se reunió virtualmente para definir los objetivos, tareas y entregables del primer sprint, el cual tendrá una duración de una semana. El enfoque principal será el desarrollo y despliegue de la landing page del proyecto en GitHub Pages, asegurando que el producto inicial esté operativo y sirva como base sólida para las siguientes iteracciones.

| Sprint                             | Sprint 1                                                                                                                                                                                     |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sprint Planning Background         |
| Date                               | 2025/04/21                                                                                                                                                                                   |
| Time                               | 21:00 PM                                                                                                                                                                                     |
| Location                           | El desarrollo de la reunión se hizo virtualmente por medio de Discord                                                                                                                        |
| Prepared By                        | Meza Camayo, Lynn Jeeferzon                                                                                                                                                                  |
| Attendees (to planning meeting)    | Meza Camayo, Lynn Jeeferzon/ Fajardo Monrroy, Walter Luis / Cuentas Peña, Joaquin Alberto/Linares Arroyo, Jorge Alexandro/ Avila Palacios, Aarón Alexander/                                  |
| Sprint n – 1 Review Summary        | Se desarrollara el primer sprint donde se planea desarrollar el landing page con HTML , CSS3 y tailwind CSS.                                                                                 |
| Sprint n – 1 Retrospective Summary |                                                                                                                                                                                              |
| Sprint Goal & User Stories         |
| Sprint 1 Goal                      | Desarrollar y desplegar la landing page funcional en Github Pages, garantizando que cumpla con los requisitos básicos de diseño, contenido y accesibilidad para servir como base de proyecto |
| Sprint 1 Velocity                  | 8                                                                                                                                                                                            |
| Sum of Story Points                | 5                                                                                                                                                                                            |

#### 5.2.1.2. Aspect Leaders and Collaborators.

Para garantizar una ejecución eficiente del Sprint, el equipo ha definido una matriz de liderazgo y colaboración (LACX), que asigna responsabilidades claras en los aspectos clave del desarrollo. Esta estructura promueve la coordinación efectiva, evita duplicidad de esfuerzos y asegura que cada tarea cuente con un líder responsable y colaboradores de apoyo.

| Team Member (Last Name, First Name) | GitHub Username | Cuerpo de la Aplicación | Lista de Caracteristicas | Contacto con el Equipo | Beneficios | Testimonios de Usuario |
| ----------------------------------- | --------------- | ----------------------- | ------------------------ | ---------------------- | ---------- | ---------------------- |
| Meza Camayo, Lynn Jeeferzon         | ajimenezrosas   | C                       | L                        | C                      | C          | C                      |
| Fajardo Monrroy, Walter Luis        | ajimenezrosas   | C                       | C                        | L                      | C          | C                      |
| Cuentas Peña, Joaquin Alberto       | ajimenezrosas   | C                       | C                        | C                      | C          | L                      |
| Linares Arroyo, Jorge Alexandro     | ajimenezrosas   | L                       | C                        | C                      | C          | C                      |
| Avila Palacios, Aarón Alexander     | ajimenezrosas   | C                       | C                        | C                      | L          | C                      |

#### 5.2.1.3. Sprint Backlog n.

En esta sección se detallan las tareas específicas que el equipo se compromete a completar durante el Sprint 1, alineadas con el Sprint Goal previamente definido. El Sprint Backlog incluye actividades técnicas, de diseño y validación necesarias para desarrollar la landing page funcional, con estimaciones de tiempo, responsables asignados según la matriz LACX.

| **Sprint #**   | **Sprint 1**             |        |                                                  |                                                                        |                        |                                 |            |
| -------------- | ------------------------ | ------ | ------------------------------------------------ | ---------------------------------------------------------------------- | ---------------------- | ------------------------------- | ---------- |
| **User Story** | **Work-Item / Task**     |
| **Id**         | **Title**                | **Id** | **Title**                                        | **Description**                                                        | **Estimation (Hours)** | **Assigned to**                 | **Status** |
| US-0           | Cuerpo de la App         | W-01   | Implementar Home y Navbar                        | Creación de la sección HOME y un navbar funcional.                     | 2                      | Linares Arroyo, Jorge Alexandro | Done       |
| US-0           | Lista de Características | W-02   | Crear sección de Caracteristicas                 | Desarrollar la sección de las principales caracteristicas de la app.   | 2                      | Meza Camayo, Lynn Jeeferzon     | Done       |
| US-0           | Contacto con el Equipo   | W-03   | Crear sección del "Call to Action"               | Implementar una sección de contacto con el equipo de desarrollo.       | 2                      | Fajardo Monrroy, Walter Luis    | Done       |
| US-0           | Beneficios               | W-04   | Crear sección de los Beneficio y funcionalidades | Desarrollar una sección de Beneficios y funcionalidades de la app.     | 2                      | Avila Palacios, Aarón Alexander | Done       |
| US-0           | Testimonios de Usuarios  | W-04   | Crear sección de Reseñas y Footer                | Desarrollar una sección de reseñas con testimonios y el pie de página. | 2                      | Cuentas Peña, Joaquin Alberto   | Done       |

Link del Trello: [https://trello.com/b/1RZIOAAB/1asi0730-2510-4380-grupo-3-quantumsoft](https://trello.com/b/1RZIOAAB/1asi0730-2510-4380-grupo-3-quantumsoft)

#### 5.2.1.4. Development Evidence for Sprint Review.

En esta sección, se presentan los commits realizados en el repositorio de la landing page en GitHub.

| **Repository** | **Branch** | **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
| -------------- | ---------- | ------------- | ------------------ | ----------------------- | ---------------------- |
|                |            |               |                    |                         |                        |

#### 5.2.1.5. Execution Evidence for Sprint Review.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

#### 5.2.1.8. Team Collaboration Insights during Sprint.

## 5.3. Validation Interviews.

### 5.3.1. Diseño de Entrevistas.

### 5.3.2. Registro de Entrevistas.

### 5.3.3. Evaluaciones según heurísticas.

## 5.4. Video About-the-Product.

# Conclusiones

## Conclusiones y recomendaciones.

## Video About-the-Team.

## Bibliografía Anexos
