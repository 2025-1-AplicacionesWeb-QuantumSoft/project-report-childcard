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

### Preguntas para niñeras certificadas: 

1. ¿Qué medios usas actualmente para encontrar trabajo como niñera?

2. ¿Qué tan fácil o difícil te resulta encontrar nuevas familias que necesiten tus servicios?

3. ¿Qué es lo más importante para ti al momento de elegir trabajar con una familia nueva?

4. ¿Qué información te gustaría mostrar en tu perfil si te publicitaras en una aplicación?

5. ¿Te sentirías cómoda siendo evaluada o recibiendo comentarios públicos de las familias? ¿Por qué?

6. ¿Qué características o herramientas crees que debería tener una app para ayudarte a encontrar más trabajo como niñera?

7. ¿Has usado alguna aplicación o plataforma similar antes? ¿Cuál fue tu experiencia?

8. ¿Qué te haría confiar en una aplicación nueva para ofrecer tus servicios?

9. ¿Cómo prefieres que te contacten las familias: por mensaje, llamada, a través de la app...?

10. ¿Estarías dispuesta a pagar una pequeña comisión o suscripción si la app te ayudara a conseguir trabajo más fácilmente? ¿Por qué sí o por qué no?


### Preguntas para Para padres de familia

1. ¿Cómo sueles encontrar niñeras cuando las necesitas?

2. ¿Qué dificultades has tenido al buscar una niñera de confianza para tus hijos?

3. ¿Qué características buscas en una niñera ideal?

4. ¿Qué información te gustaría ver en el perfil de una niñera dentro de una aplicación?

5. ¿Qué tan importante es para ti que la plataforma verifique a las niñeras antes de que aparezcan en la app? ¿Qué tipo de verificación esperas?

6. ¿Qué tipo de servicios te gustaría encontrar en una niñera desde una app?

7. ¿Qué nivel de interacción te gustaría tener con la niñera antes de contratarla?

8. ¿Te sentirías cómodo(a) evaluando públicamente a la niñera después de un servicio? ¿Por qué sí o no?

9. ¿Cuánto estarías dispuesto(a) a pagar por un servicio confiable y seguro para encontrar niñeras?

10 .¿Qué te haría confiar en una nueva aplicación para contratar niñeras?


### 2.2.2. Registro de entrevistas. 

![Entrevista 1](assets/Entrevista%201.jpg)

- Entrevista N°1: Andrea Santur
- Sexo: Niñera
- Edad: 23 años

- Ubicación en Los olivos, Lima, Perú

#### Entrevista: ####

link: https://youtu.be/XEUXEqPSi4k

**Resumen**
Andrea, de 23 años, ha trabajado como niñera en varios hogares y encuentra trabajo principalmente por redes sociales y recomendaciones. Considera importante que las familias sean claras con sus necesidades y respeten los horarios acordados. Si usara una app, compartiría su foto, referencias, turnos y servicios específicos. Se siente cómoda recibiendo calificaciones públicas, ya que ayudan a mejorar su visibilidad y desempeño. Además, le gustaría que la app incluya comentarios, calificaciones, estadísticas y opciones de contacto.


![Entrevista 2](assets/Entrevista%202.jpg)

- Entrevista N°2: Alessandra Becerra
- Sexo: Femenino
- Edad: 20 años

- Ubicación no especificada para esta entrevista

#### Entrevista: ####
link: https://youtu.be/pCsz0xk5Z2k

**Resumen:**
Alessandra, una niñera de 20 años, comparte que encuentra trabajo principalmente a través de Facebook, recomendaciones y WhatsApp. Valora la confianza, el respeto y el buen trato con las familias. Le gustaría mostrar en su perfil experiencia, disponibilidad, referencias y formación. Apoya la idea de recibir comentarios respetuosos que ayuden a generar confianza. Considera útil que una app tenga filtrado por zona, calendario, chat y verificación de perfiles, aunque no ha tenido buena experiencia con apps similares. Confiaría en una nueva si se verificara a los padres.


#### Segmento 2:Padres de familia ####

![Entrevista 3](assets/Entrevista%203.jpg)

- Entrevista N°3: Edery Abanto
- Sexo: Masculino
- Edad: 30 años

- Ubicación no especificada para esta entrevista

#### Entrevista: ####
link: https://youtu.be/k-bONuGLquw

**Resumen:**
Edery, un padre de familia comparte sus expectativas sobre una aplicación para contratar niñeras. Él busca principalmente seguridad, verificación de identidad y antecedentes, referencias reales, y disponibilidad clara. Prefiere tener una interacción previa con la niñera a través de chat o videollamada, y estaría dispuesto a pagar entre 20 y 50 soles por hora según el servicio. También valora una interfaz fácil de usar, reseñas de otros padres y la posibilidad de hacer evaluaciones públicas. Sus respuestas ofrecen una guía directa para diseñar una plataforma confiable, útil y centrada en las necesidades reales de los usuarios.


![Entrevista 4](assets/Entrevista%204.jpg)

- Entrevista N°4: Eric Olivera
- Sexo: Masculino
- Edad: 27 años

- Ubicación en San Miguel, Lima, Perú

#### Entrevista: ####
link: https://youtu.be/5tE2mM7XAik

**Resumen**
Eric, de 27 años, es padre de dos hijos y suele buscar niñeras a través de recomendaciones personales. Aunque ha probado grupos en redes sociales, no le inspiran confianza. Encuentra difícil conseguir niñeras disponibles y confiables. Busca personas con experiencia, responsabilidad, puntualidad y manejo de emergencias. En una app, le gustaría ver perfiles con fotos, referencias, videos de presentación, formación y disponibilidad. Considera esencial que la plataforma verifique identidad. Está dispuesto a pagar entre 100 y 200 soles, o suscribirse mensualmente, si se le garantiza seguridad y buenas opciones

### 2.2.3. Análisis de entrevistas. 

 **Segmento 1: Niñeras con experiencia**
 **Entrevista 1: Andrea Santur** 
**Análisis de la entrevista:** La entrevista con Andrea, una joven niñera de 23 años con experiencia previa, valora que las familias sean claras en sus requerimientos y respetuosas con los horarios y límites. Al presentarse en una app, desea mostrar su rostro, disponibilidad, referencias y experiencia. Está completamente abierta a recibir calificaciones públicas y espera funciones como valoraciones, estadísticas de desempeño, chats en vivo y la posibilidad de ofrecer servicios premium. Para acceder a suscribirse, consideraría clave la facilidad de uso, buena reputación y funcionalidades específicas que le ayuden a visibilizarse


 **Entrevista 2: Alessandra Becerra**
 **Análisis de la entrevista:**  La entrevista con Alessandra, permite comprender las necesidades, preferencias y limitaciones de las niñeras en la búsqueda de empleo. Ella destaca la importancia de la confianza mutua con las familias, la visibilidad de su experiencia, referencias y formación, así como el uso frecuente de canales de comunicación como redes sociales y WhatsApp. Identifica limitaciones como la inestabilidad en la demanda y la baja efectividad de las plataformas existentes. Finalmente, expresa disposición para ser evaluada y pagar por una aplicación útil


**Segmento 2: Padres de familia**

**Entrevista 1:  Edery Abanto**
**Análisis de la entrevista:** El entrevistado, un padre de familia, revela su preocupación fundamental por la seguridad, la verificación de antecedentes, y la transparencia en los perfiles de las niñeras. Además, menciona su preferencia por plataformas con interacción previa, variedad de servicios y buena experiencia de usuario. La entrevista refleja una necesidad de soluciones tecnológicas confiables en el ámbito del cuidado de niños pequeños, destacando puntos clave para el desarrollo de nuestra aplicación.

 **Entrevista 2: Eric Olivera**
 **Análisis de la entrevista:** La entrevista con Eric, revela preocupaciones comunes en los padres al buscar servicios de niñera: confianza, seguridad y facilidad de uso. Prefiere recomendaciones cercanas, pero reconoce que eso limita las opciones. Su principal barrera al usar plataformas digitales es la falta de verificación confiable. Eric busca una niñera responsable, puntual, con experiencia y capacidad para manejar emergencias. Valora perfiles detallados, con fotos, videos, referencias y disponibilidad clara. Además, espera poder interactuar con las candidatas antes de contratarlas.


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

