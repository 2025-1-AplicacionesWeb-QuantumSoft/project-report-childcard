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

| Miembro                        |   Código   |
| :----------------------------- | :--------: |
| Meza Camayo, Lynn Jeeferzon    | U20201C320 |
| Fajardo Monrroy, Walter Luis   | U202221632 |
| Cuentas Peña, Joaquin Alberto  | U20201F788 |
| Avila Palacios, Aarón Alexander | U201823654 |

</div>
<h3 align="center"> ABRIL - 2025   </h3>

## REGISTRO DE VERSIONES

| Versión  |   Fecha   |       Autor     |           Descripción de Modificación           |
|----------|-----------|-----------------|-------------------------------------------------|
|    0.1   | 03/04/25  |     Lynn Meza   | Desarrollo de la Structura del informe                 |
|       |   |        |                  |
|       |   |        |                  |

## PROJECT REPORT COLLABORATION INSIGHTS

URL del repositorio del project Report : [https://github.com/2025-1-AplicacionesWeb-QuantumSoft/project-report-childcard](https://github.com/2025-1-AplicacionesWeb-QuantumSoft/project-report-childcard)

***TB1***

Para el desarrollo de la entrega TB1, se desarrollo las actividades de elaboracion del informe de la siguiente manera:

## CONTENIDO

### Tabla de contenido
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)

- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
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
### 1.2.1  Antecedentes y problemática 
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
Los User personas se realizaron en base a las distintas personas que entrevistamos según nuestros segmentos objetivos.
**Niñera con experiencia:**
![María Fernanda User Persona](assets/US%20María%20Fernanda.png)
**Psicólogo certificado:**
![Alejandro Dominguez User Persona](assets/US%20Alejandro%20Dominguez.png)

### 2.3.2. User Task Matrix. 
En esta sección vamos a detallar las tareas que realizan los diferentes segmentos de usuarios representados por los User Personas de Keychild.
**Niñera con experiencia: María Fernanda**
| Actividades                          | María Fernanda | Frecuencia     | Importancia |
|-------------------------------------|------------------|----------------|-------------|
| Describir su experiencia con familias previas |                  | Frecuentemente | Alta        |
| Seleccionar su ubicación en el mapa          |                  | Ocasionalmente | Media       |
| Ver familias en búsqueda de niñera           |                  | Frecuentemente | Alta        |
| Ver reseñas de familias                      |                  | Ocasionalmente | Media       |
| Acceder a entrevistas virtuales              |                  | Frecuentemente | Media       |

**Padre de familia: Alejandro Dominguez**
| Actividades                          | Alejandro Dominguez | Frecuencia     | Importancia |
|-------------------------------------|----------------------|----------------|-------------|
| Buscar niñeras                      |                      | Frecuentemente | Alta        |
| Filtrar niñeras por proximidad      |                      | Frecuentemente | Alta        |
| Filtrar niñeras por experiencia     |                      | Ocasionalmente | Media       |
| Agregar descripción familiar        |                      | Ocasionalmente | Media       |
| Agregar ubicación                   |                      | Frecuentemente | Media       |

### 2.3.3. User Journey Mapping. 
**USER PERSONA: María Fernanda**
![Journey Map 1](assets/Journey%20Map,%20María%20Fernanda.png)
El viaje de Mafer, una profesional en busca de oportunidades como niñera, es distinto al de Luis en forma pero igual de cargado emocionalmente. Comienza desde una posición de baja visibilidad, con esperanza y aceptación, deseando acceder a oportunidades reales, lo que representa una oportunidad clave para que las plataformas generen confianza inicial a través de rankings, reputación o contenido educativo. En la búsqueda activa de vacantes, la ansiedad se intensifica, haciendo fundamental la transparencia y el seguimiento del estado de las postulaciones. Al ser contactada por padres, Mafer siente entusiasmo y deseo de ser tratada con respeto, por lo que una guía compartida para entrevistas puede mejorar la experiencia para ambas partes. En la etapa de evaluación de ofertas, adopta un enfoque analítico, lo que resalta la utilidad de comparativas claras entre opciones laborales mediante un checklist estándar. Finalmente, al aceptar una oferta, Mafer experimenta tranquilidad y preparación, siendo este el momento ideal para que la plataforma le proporcione herramientas administrativas, como contratos, gestión de horarios y capacitaciones para una buena integración.

**USER PERSONA: Alejandro Dominguez**
![Journey Map 2](assets/Journey%20Map,%20Alejandro.png)
El viaje de Alejandro al buscar una niñera refleja una profunda necesidad de confianza, seguridad y compatibilidad emocional. Desde el inicio, se enfrenta a una sobrecarga de opciones poco diferenciadas, lo que genera preocupación y la necesidad de filtros avanzados y validaciones visibles que inspiren confianza. Durante la exploración, la falta de perfiles estandarizados le exige invertir tiempo extra, por lo que se recomienda estructurar mejor la información con campos obligatorios y sellos de verificación. Al contactar a las candidatas, adopta una actitud vigilante, esperando profesionalismo y empatía, donde una agenda integrada para entrevistas puede facilitar el proceso. En la etapa de evaluación, busca una conexión más profunda y emocional, por lo que guías para entrevistas y checklists serían herramientas valiosas. Finalmente, al cerrar el trato, aunque siente alegría, aún le preocupa cómo se adaptarán sus hijos, lo que sugiere la utilidad de herramientas post-contratación como plantillas de contrato, gestión de horarios y seguimiento del desempeño.

### 2.3.4. Empathy Mapping.
**USER PERSONA: María Fernanada**
![Empathy Map 1](assets/Empathy%20map%20Mafer.png)

**USER PERSONA: Alejandro Dominguez**
![Empathy Map 2](assets/Empathy%20map%20Alejandro.png)

### 2.3.5. As-is Scenario Mapping. 
**USER PERSONA: María Fernanda**
![Scenario Mapping 1](assets/Scenario%20Mapping%20Mafer.jpg)
El proceso de buscar trabajo como niñera es demandante emocionalmente. Mafer depende de canales poco convencionales como grupos de Facebook o WhatsApp, lo que limita su visibilidad profesional y genera inseguridad constante sobre su capacidad para destacar entre tantas opciones. Luego de un largo tiempo de espera, durante la postulación, enfrenta entrevistas muy variables de acuerdo al carácter del padre de familia. Una vez contratada, no siempre recibe continuidad laboral ni reconocimiento profesional, lo cual la obliga a empezar desde cero en cada oportunidad. El sistema actual le genera frustración, incertidumbre y una sensación de estancamiento, pese a su motivación por mejorar.

**USER PERSONA: Alejandro Dominguez**
![Scenario Mapping 1](Assets/Scenario-Mapping1.jpg)
El proceso de encontrar una niñera confiable para Alejandro ocurre principalmente bajo presión y con poco tiempo de anticipación. Esto lo obliga a recurrir a contactos y decisiones rápidas, sin contar con referencias verificadas o una base confiable de candidatas. El proceso genera estrés, y en muchas ocasiones una carga mental adicional al intentar equilibrar su vida laboral y familiar. Aunque logra resolver el problema de cuidado infantil de forma temporal, la elección de la niñera muchas veces deja una sensación de riesgo, incertidumbre y la necesidad de tener que repetir el proceso en futuras ocasiones, sin garantías de mejor resultado.


## 2.4. Ubiquitous Language. 
El "Ubiquitous Language" será una herramienta esencial en nuestro trabajo, ya que nos permitirá establecer un lenguaje común y compartido entre todos los miembros del equipo.
**Ubiquitous Language – KYDICARE** 
1. Niñera Verificada: Persona cuidadora que ha pasado el proceso de verificación de identidad, referencias y experiencia por parte de la plataforma.

2. Padre de familia: Persona(s) que busca(n) servicios de cuidado infantil a través de la app para sus hijos.

3. Perfil Profesional: Página personal de la niñera con información relevante como experiencia, certificaciones, disponibilidad, y calificaciones.

4. Solicitud de Servicio: Acción iniciada por un padre para contactar y contratar una niñera en una fecha y horario específicos.

5. Match Seguro: Coincidencia entre niñera y familia basada en filtros (ubicación, disponibilidad, experiencia) y políticas de seguridad.

6. Calificación y Reseña: Sistema de evaluación que permite a los usuarios valorar la experiencia después de cada servicio.

7. Verificación de Identidad: Proceso obligatorio para todas las niñeras antes de publicar su perfil, incluyendo documentos, entrevistas o chequeo de antecedentes.

8. Reservación Confirmada: Estado del servicio cuando ambas partes (niñera y padre) han aceptado los términos y se ha fijado el horario.

9. Panel de Seguridad: Conjunto de funciones dentro de la app que aseguran la transparencia y protección de todos los usuarios (verificación, soporte, seguimiento en tiempo real).

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
### 5.2.1. Sprint n 
#### 5.2.1.1. Sprint Planning n.
#### 5.2.1.2. Aspect Leaders and Collaborators.
#### 5.2.1.3. Sprint Backlog n.
#### 5.2.1.4. Development Evidence for Sprint Review.
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

