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
<h3 align="center"> Nombre del Producto: KidyCare  </h3>

<div align="center">

| Miembro                        |   Código   |
| :----------------------------- | :--------: |
| Meza Camayo, Lynn Jeeferzon    | U20201C320 |
| Fajardo Monrroy, Walter Luis   | U202221632 |
| Cuentas Peña, Joaquin Alberto  | U20201F788 |
| Linares Arroyo, Jorge Alexandro  | U202318624 |
| Avila Palacios, Aarón Alexander | U201823654 |

</div>
<h3 align="center"> ABRIL - 2025   </h3>

## REGISTRO DE VERSIONES

| Versión  |   Fecha   |       Autor     |           Descripción de Modificación           |
|----------|-----------|-----------------|-------------------------------------------------|
|    0.1   | 03/04/25  |     Lynn Meza   | Desarrollo de la Structura del informe          |
|    0.1   | 20/04/25  | Aaron Avila     | Registro y analisis de entrevista               |
|       |   |        |                  |

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
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
  - [1. Página de Inicio](#1-página-de-inicio)
  - [2. Buscar Cuidadores (Para Padres y Tutores)](#2-buscar-cuidadores-para-padres-y-tutores)
  - [3. Registro de Cuidadores](#3-registro-de-cuidadores)
  - [4. Reservar Servicios de Cuidado](#4-reservar-servicios-de-cuidado)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
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
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n.](#5211-sprint-planning-n)
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

- Tutores

![tutores-to-be-scenario-map](./assets/Tutor-to-be-scenary.png)

- Niñeras

![niñeras-to-be-scenario-map](./assets/Niñera-to-be-scenario-map.png)

## 3.2. User Stories.

| EPICA                   | ID EPICA |
| ----------------------- | -------- |
| Landing Page            | EP01     |
| Registro de Usuarios    | EP02     |
| Registro de Servicios   | EP03     |
| Sistema de Reserva      | EP04     |
| Sistema de Comunicacion | EP05     |
| Sistema de Pagos        | EP06     |
| Sistema de Comentarios  | EP07     |
| Historias Tecnicas      | EP08     |

| Epic/ Story ID | Titulo                                       | Description                                                                                                                                                                               | Criterios de Aceptacion                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Relacion con (Epic ID) |
| -------------- | -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
| US01           | Cuerpo de la App                             | Como visitante, quiero ver una descripción clara de la app para entender su valor y lo que ofrece.                                                                                        | Escenario 1:Visitante visualiza informacion clara de la app <br> _Dado_ que el visitante accede a la landing page <br> _Cuando_ la pagina carga completamente <br> _Entonces_, visualiza un titular con el texto "Encuentra niñeras confiables en minutos"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EP01                   |
| US02           | Testimonios de Usuarios                      | Como visitante, quiero ver testimonios reales para confiar en el servicio de la app                                                                                                       | Escenario 1: El visitante visualiza testimonios de usuarios que utilizaran la app <br> _Dado_ que el visitante esta en la landing page <br> _Cuando_ seleccion la seccion "Testimonios" en el navbar <br> _Entonces_, visualizará tarjetas con testimonios de opinion de la app                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | EP01                   |
| US03           | Lista de Características                     | Como visitante, visualizar las características principales de la app para conocer sus funcionalidades antes de registrarme y decidir si se ajusta a mis necesidades.                      | Escenario 1: El visitante visualiza las caracteristicas de la aplicacion. <br> _Dado_ que el visitante esta en la seccion del Navbar <br> _Cuando_ presiona "Services" <br> _Entonces_, el sistema mostrara las caracteristicas que ofrece la app.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | EP01                   |
| US04           | Contacto con la Equipo                       | Como visitante, quiero contactar al equipo para tener un medio directo con el equipo de desarrollo.                                                                                       | Escenario 1: El visitante accede al sitio web <br> _Dado_ que el visitante esta en la seccion del Navbar <br> _Cuando_ presiona "Call to Action" <br> _Entonces_, el sistema muestra un formulario de contacto que es el medio de contacto con el equipo de desarrollo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | EP01                   |
| US05           | Beneficios                                   | Como visitante, quiero conocer los beneficios y funciones que ofrece la app, para conocer sus servicios.                                                                                  | Escenario 1: El visitante visualiza los beneficios de app <br> _Dado_ que el visitante esta en la landing page <br> _Cuando_ esta en la seccion "Services" <br> _Entonces_, visualizará los beneficios y funcionalidades de la app.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EP01                   |
| US06           | Registro del Usuario                         | Como Tutor, quiero crear una cuenta en la plataforma para poder buscar niñeras y gestionar reservas para mi hijo.                                                                         | Escenario 1: El tutor visualiza el formulario de registro. Dado que el tutor es visitante de la app, cuando abre la app, se muestra el dashboard de "inicio Sesión" y "Registro". Entonces el sistema muestra el formulario de "Registro" y el formulario contiene los campos obligatorios de ingresar.<br> Escenario 2: El tutor completa y envía el formulario de registro. Dado que el tutor ha rellenado todos los campos obligatorios correctamente, cuando presiona el botón "Registrar", entonces el sistema muestra el mensaje "Se envió correctamente". <br> Escenario 3: El tutor deja campos obligatorios vacíos. Dado que el tutor dejó uno o más campos vacíos, cuando presiona el botón "Registrar", entonces el sistema muestra el mensaje de error "falta completar datos".                                                                                                                                                                                                                                                                                                                | EP02                   |
| US07           | Registro como Niñera                         | Como Niñera, quiero registrarme en la plataforma y crear un perfil detallado para mostrar mi experiencia y certificaciones a los Tutores, y ofrecer mis servicios de cuidado y enseñanza. | Escenario 1: La niñera visualiza el formulario de registro. Dado que la niñera es visitante del sitio web, cuando ingresa a la web, se muestra el dashboard de "inicio Sesión" y "Registro", y selecciona "Registro". Entonces el sistema muestra el formulario de "Registro" y el formulario contiene los campos obligatorios de ingresar.<br> Escenario 2: La niñera completa y envía el formulario de registro. Dado que la niñera ha rellenado todos los campos obligatorios correctamente, cuando presiona el botón "Registrar", entonces el sistema muestra el mensaje "Se envió correctamente". <br> Escenario 3: La niñera deja campos obligatorios vacíos. Dado que la niñera dejó uno o más campos vacíos, cuando presiona el botón "Registrar", entonces el sistema muestra el mensaje de error "falta completar datos".                                                                                                                                                                                                                                                                        | EP02                   |
| US08           | Validación de Registro                       | Como administrador, quiero un mecanismo de autentificación segura para verificar las credenciales del registro de cuenta.                                                                 | Escenario 1: El visitante visualiza el mecanismo de autentificación. Dado que el visitante está en la sección de registro de datos, cuando selecciona "Vincular cuenta", entonces el sistema muestra las opciones de vinculación de cuentas.<br> Escenario 2: El visitante completa exitosamente la vinculación. Dado que el visitante selecciona la opción con que va a registrar su cuenta, cuando recibe el código de verificación y lo ingresa en el formulario, entonces el sistema muestra el mensaje "Código correcto" y registra la cuenta, redireccionando al dashboard de inicio del sitio web. <br> Escenario 3: El visitante ingresa mal el código de verificación. Dado que el visitante selecciona la opción con que va a registrar su cuenta, cuando recibe el código de verificación e ingresa un código incorrecto, entonces el sistema muestra el mensaje "Código incorrecto" y da un tiempo de 20 segundos para ingresar el nuevo código.                                                                                                                                               | EP02                   |
| US09           | Actualización de cuenta del Tutor            | Como Tutor, quiero actualizar y completar mi perfil para añadir detalles sobre las necesidades especiales de mi hijo.                                                                     | Escenario 1: El tutor visualiza su perfil. Dado que el tutor ingresa al sitio web, cuando selecciona su icono de perfil, entonces el sistema le redireccionará al dashboard de su perfil y visualizará los datos que rellenó cuando registró la cuenta.<br> Escenario 2: El tutor actualiza su perfil. Dado que el tutor presiona el botón de actualizar, cuando ingresa los datos actualizados y la información adicional o faltante del perfil y presiona el botón de "Guardar Cambios", entonces el sistema muestra el mensaje "Se guardó correctamente".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP02                   |
| US10           | Actualización de cuenta de la Niñera         | Como Niñera, quiero actualizar y completar mi perfil con mi experiencia y certificaciones, para atraer a más Tutores.                                                                     | Escenario 1: La niñera visualiza su perfil. Dado que la niñera ingresa al sitio web, cuando selecciona su icono de perfil, entonces el sistema le redireccionará al dashboard de su perfil y visualizará los datos que rellenó cuando registró la cuenta.<br> Escenario 2: La niñera actualiza su perfil. Dado que la niñera presiona el botón de actualizar, cuando ingresa los datos actualizados y la información adicional o faltante del perfil y presiona el botón de "Guardar Cambios", entonces el sistema muestra el mensaje "Se guardó correctamente". <br> Escenario 3: La niñera ingresa documentos a su perfil. Dado que el tutor presiona el botón de "Subir Documento", cuando selecciona el documento y presiona el botón de "Guardar", entonces el sistema muestra el mensaje "Se subió el documento correctamente".                                                                                                                                                                                                                                                                      | EP02                   |
| US11           | Ingreso de Horario de Disponibilidad         | Como Niñera, quiero ingresar mi disponibilidad de servicios, para asegurar que los Tutores vean los horarios de atención de mis servicios.                                                | Escenario 1: La niñera ingresa sus horarios. Dado que la niñera se encuentra dentro del sitio web, cuando ingresa a su perfil y selecciona "Ingresar Horario", entonces el sistema muestra el calendario para ingresar los días y horarios disponibles.<br> Escenario 2: La niñera guarda sus horarios. Dado que la niñera rellena los horarios dentro del calendario, cuando presiona el botón de "Guardar Horario", entonces el sistema muestra el mensaje "Se guardó correctamente".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | EP03                   |
| US12           | Actualizar Horario de Disponibilidad         | Como Niñera, quiero poder actualizar mis horarios de disponibilidad en la app, para que los padres vean cuándo estoy libre para ofrecer mis servicios.                                    | Escenario 1: La niñera puede actualizar sus horarios de servicio. Dado que la niñera se encuentra en su horario de servicio <br> **Cuando** selecciona el icono de lapiz y agrega los nuevos horaios <br> **Entonces**, el sistema mostrar muestra la opcion de "Guardar" o "Cancelar". <br> Escenario 2: La niñera guarda sus nuevos horarios de servicio: **Dado** que se encuentra en la seccion "Services" <br> **Cuando** actualizo su nuevo horario y selecciono "Guardar" <br> Entonces, el sistema actualizo y guardo el nuevo horario y notifico "Guardado exitosamente". <br> Escenario 3: La niñera cancela actualizar su horario. **Dado** que se encuentra en la seccion de "Servicios" <br> **Cuando** actualiza el horario y selecciona "Cancelar" <br> **Entonces** el sistema no modifica el horario.                                                                                                                                                                                                                                                                                     | EP03                   |
| US13           | Gestión de Costos de Servicios               | Como Niñera, quiero establecer mis tarifas por hora o sesión, para que los Tutores sepan cuánto cobraré por mis servicios.                                                                | Escenario 1: La niñera establece las Tarifas de sus servicios. Dado que la niñera está en la sección de configuración de tarifas, cuando introduce una tarifa por hora o por sesión y guarda los cambios, entonces el sistema actualiza el perfil de la niñera para mostrar las tarifas establecidas.<br> Escenario 2: La niñera actualiza las Tarifas de sus servicios. Dado que la niñera desea ajustar sus tarifas, cuando modifica la tarifa por hora o por sesión en la sección de configuración y guarda los cambios, entonces el sistema actualiza automáticamente el perfil de la niñera para reflejar las nuevas tarifas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | EP03                   |
| US14           | Filtrado de Ubicación                        | Como Tutor, quiero buscar niñera basados en la ubicación y servicio, para encontrar a alguien cercano a mi hogar.                                                                         | Escenario 1: El Tutor visualiza la sección de búsqueda. Dado que el Tutor ingresa al sitio web, cuando selecciona la sección de búsqueda, entonces el sistema le direccionará al dashboard de búsqueda donde visualizará a todos las niñeras que ofrecen sus servicios de cuidado.<br> Escenario 2: El Tutor hace un filtrado de datos por ubicación. Dado que el tutor ingresa el dato a buscar y selecciona el tipo de búsqueda, cuando ingresa la opción de búsqueda por "Ubicación" y presiona el botón de buscar, entonces el sistema muestra a todos los perfiles de las niñera que coinciden con la ubicación ingresada.<br> Escenario 3: El Tutor hace un filtrado de datos por servicio. Dado que el tutor ingresa el dato a buscar y selecciona el tipo de búsqueda, cuando ingresa la opción de búsqueda por "Servicio" y presiona el botón de buscar, entonces el sistema muestra a todos los perfiles de niñera que tienen el servicio igual al dato buscado.                                                                                                                                 | EP04                   |
| US15           | Visualización de Perfil                      | Como Tutor, quiero ver las certificaciones y antecedentes de la niñera, para asegurarme de que sean adecuados para mi hijo.                                                               | Escenario 1: El Tutor selecciona el perfil. Dado que el Tutor realiza el filtrado de búsqueda, cuando selecciona a la niñera interesado, entonces el sistema le direccionará al perfil de la niñera y visualizará todos sus datos.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | EP04                   |
| US16           | Solicitud de Reserva                         | Como Tutor, quiero solicitar una reserva para un niñera, para asegurarme de que estén disponibles en el horario que necesito.                                                             | Escenario 1: El Tutor selecciona los horarios de atención. Dado que el Tutor se encuentra en el Perfil de la niñera seleccionado, cuando presiona la opción de "Solicitar Reserva de Atención", entonces el sistema mostrará los horarios de atención en un calendario de la semana con la opción de seleccionar los días y horas disponibles.<br> Escenario 2: El Tutor envía la solicitud de reserva. Dado que el Tutor selecciona los horarios de la reserva, cuando presiona la opción de "Enviar Solicitud", entonces el sistema mostrará un mensaje indicando "Se envió la solicitud" y notificará a la niñera sobre la solicitud de reserva.                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EP04                   |
| US17           | Actualización de Solicitud de Reserva        | Como Tutor, quiero poder actualizar mis reservas, para cambiar horarios o cancelar si es necesario.                                                                                       | Escenario 1: El Tutor accede a las solicitudes de reserva. Dado que el Tutor ha iniciado sesión en su cuenta, cuando accede a la sección de solicitudes de reserva, entonces visualizará la lista actualizada de todas las solicitudes de reserva, incluyendo aquellas que están aceptadas, pendientes o rechazadas.<br> Escenario 2: El Tutor cambia el horario de la reserva. Dado que el Tutor tiene una solicitud de reserva existente, cuando selecciona la opción de cambiar el horario en la solicitud seleccionada, entonces el Tutor visualizará el calendario de horarios disponibles para el cambio, y al seleccionar un nuevo horario y confirmar el cambio, entonces el sistema actualizará la solicitud con el nuevo horario y enviará una notificación de confirmación al Tutor.<br> Escenario 3: El Tutor cancela la solicitud. Dado que el Tutor tiene una solicitud de reserva existente, cuando selecciona la opción de cancelar la solicitud, entonces el sistema cancela la solicitud y notificará a la niñera sobre la cancelación, actualizando la solicitud en la lista del Tutor. | EP04                   |
| US18           | Vista de Solicitudes                         | Como Niñera, quiero recibir notificación de las solicitudes de reserva en tiempo real, para poder ingresar y visualizar las solicitudes entrantes.                                        | Escenario 1: La niñera recibe notificación de Solicitud. Dado que la niñera recibe una notificación al celular de una Solicitud de Reserva, cuando selecciona la notificación, entonces el sistema le redirecciona a la sección de "Solicitudes" del sitio web.<br> Escenario 2: La niñera ingresa a la sección de Solicitud. Dado que la niñera está en el sitio web y recibe la notificación, cuando ingresa a la sección "Solicitudes", entonces visualizará la solicitud notificada.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | EP04                   |
| US19           | Gestión de Solicitudes                       | Como Niñera, quiero gestionar las solicitudes recibidas, para aceptar o rechazar la reserva.                                                                                              | Escenario 1: La niñera acepta la solicitud. Dado que la niñera recibe una solicitud de reserva, cuando accede a la solicitud en su panel de control y selecciona "Aceptar", entonces el sistema actualiza el estado de la solicitud a "Aceptada" y notifica al Tutor sobre la confirmación de la reserva.<br> Escenario 2: La niñera rechaza la solicitud. Dado que la niñera recibe una solicitud de reserva, cuando accede a la solicitud en su panel de control y selecciona "Rechazar", entonces el sistema actualiza el estado de la solicitud a "Rechazada" y notifica al Tutor sobre la decisión de rechazo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EP04                   |
| US20           | Sistema de Comunicación                      | Como Tutor, quiero enviar mensajes a la niñera que contrate, para discutir detalles y expectativas.                                                                                       | Escenario 1: El Tutor accede a la función de mensajería. Dado que el Tutor está autenticado en su cuenta, cuando accede a la sección de comunicación, entonces visualizará una opción para enviar y recibir mensajes de la niñera.<br> Escenario 2: El Tutor envía un mensaje. Dado que el Tutor tiene una conversación con una niñera, cuando redacta un mensaje y presiona "Enviar", entonces el mensaje se envía a la niñera y aparece en la conversación correspondiente.<br> Escenario 3: El Tutor recibe una notificación del mensaje entrante. Dado que la niñera envía un nuevo mensaje, cuando el Tutor recibe el mensaje, entonces es notificado sobre el nuevo mensaje.                                                                                                                                                                                                                                                                                                                                                                                                                         | EP05                   |
| US21           | Registro de Medios de Pago                   | Como Niñera, quiero recibir pagos a través de la plataforma, para asegurar una transacción segura y sencilla.                                                                             | Escenario 1: La niñera configura los métodos de pago. Dado que la niñera está en su cuenta, cuando accede a la sección de "Configuración de Pagos", entonces puede agregar y gestionar métodos de pago, como cuentas bancarias o tarjetas de crédito/débito.<br> Escenario 2: La niñera visualiza el pago de sus servicios. Dado que el pago ha sido procesado, cuando la niñera accede a la sección de "Historial de Pagos", entonces visualizará el pago registrado, incluyendo detalles como la cantidad, la fecha y el estado del pago.<br> Escenario 3: La niñera visualiza el historial de pagos. Dado que la niñera accede a la sección "Historial de Pagos", cuando revisa el historial, entonces visualizará un registro completo de todos los pagos recibidos, en orden cronológico, con detalles de cada transacción.                                                                                                                                                                                                                                                                           | EP06                   |
| US22           | Sistema de Pagos                             | Como Tutor, quiero realizar los pagos a través de la plataforma, para asegurar una transacción segura y sencilla.                                                                         | Escenario 1: El Tutor realiza el pago. Dado que el Tutor necesita realizar un pago por una sesión o servicio, cuando accede a la sección de "Pagos" y selecciona el monto a pagar, entonces puede confirmar y procesar el pago utilizando el método de pago configurado.<br> Escenario 2: El Tutor visualiza el historial de pagos. Dado que el Tutor accede a la sección de historial de pagos, cuando revisa el historial, entonces visualizará un registro completo de todos los pagos realizados, en orden cronológico, con detalles de cada transacción.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | EP06                   |
| US23           | Sistema de Reseñas                           | Como Tutor, quiero dejar una reseña sobre el niñera, para ayudar a otros Tutores a tomar decisiones informadas.                                                                           | Escenario 1: El Tutor deja una reseña. Dado que el Tutor ha utilizado los servicios de la niñera, cuando accede a la sección de "Reseñas" en el perfil de la niñera y escribe una reseña, entonces el sistema guarda la reseña y la muestra en el perfil de la niñera para que otros Tutores la vean.<br> Escenario 2: El Tutor califica a la Niñera. Dado que el Tutor desea calificar a la niñera, cuando selecciona una calificación de estrellas, de 1 a 5 estrellas, en la sección de "Reseñas", entonces el sistema guarda la calificación junto con la reseña escrita.<br> Escenario 3: El Tutor elimina una reseña. Dado que el Tutor decide eliminar una reseña que ha dejado, cuando selecciona la opción para eliminar la reseña en la sección de reseñas, entonces el sistema borra la reseña del perfil del Cuidador y muestra un mensaje de confirmación de que la reseña ha sido eliminada.                                                                                                                                                                                                 | EP07                   |
| US24           | Visualización de Reseñas                     | Como Niñera, quiero visualizar las reseñas dejadas por los tutores de los servicios ofrecidos anteriormente, para ver en qué puedo mejorar.                                               | Escenario 1: La niñera accede a las reseñas de su perfil. Dado que la niñera está en su cuenta, cuando accede a la sección de "Reseñas", entonces el sistema muestra una lista de todas las reseñas dejadas por los Tutores que han recibido sus servicios.<br> Escenario 2: La niñera visualiza los detalles de la reseña. Dado que la niñera está en la sección de reseñas, cuando selecciona una reseña específica, entonces el sistema mostrará los detalles completos de la reseña, incluyendo la calificación, comentarios y cualquier otra información relevante proporcionada por el tutor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EP07                   |
| US25           | Autentificación de Usuarios                  | Como Administrador de la API, quiero autenticar me con mis credenciales, para que pueda gestionar los recursos protegidos de la plataforma.                                               | Escenario 1: El administrador proporciona credenciales válidas.<br> **Dado** que el administrador proporciona credenciales válidas, **cuando** realiza una solicitud al endpoint `POST /api/auth/login`, **entonces** el sistema debe generar un token JWT que se usará en futuras solicitudes.<br> Escenario 2: El administrador proporciona credenciales inválidas.<br> **Dado** que el administrador proporciona credenciales inválidas, **cuando** intenta iniciar sesión, **entonces** el sistema debe retornar un error con estado HTTP 401 y un mensaje indicando "Credenciales incorrectas".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | EP08                   |
| US26           | Gestión de Roles y Permisos                  | Como Administrador, quiero definir diferentes roles y permisos para los usuarios, para que puedan tener acceso a diferentes funciones de la plataforma.                                   | Escenario 1: Rol con acceso completo. Dado que el administrador crea o edita un rol, cuando define los permisos de dicho rol, entonces el sistema actualiza las restricciones de acceso de acuerdo con los permisos asignados.<br> Escenario 2: Rol con acceso limitado. Dado que un usuario con permisos limitados intenta acceder a una función restringida, cuando intenta realizar una acción no permitida, entonces el sistema devuelve un error de "Acceso denegado".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | EP08                   |
| US27           | Optimización de Consultas a la Base de Datos | Como Administrador, quiero optimizar las consultas a la base de datos, para que las respuestas del servidor sean más rápidas y eficientes.                                                | Escenario 1: Base de datos lenta. Dado que una consulta a la base de datos tarda más de lo esperado, cuando se identifica una mejora en el índice de las tablas o estructura de las consultas, entonces el sistema ejecuta las consultas en menos de 500 ms.<br> Escenario 2: Base de datos optimizado. Dado que se ha optimizado el sistema de caché, cuando un usuario realiza varias solicitudes repetidas, entonces el servidor devuelve la respuesta desde el caché en lugar de la base de datos.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | EP08                   |
| US28           | Gestión de Archivos Subidos                  | Como Administrador, quiero manejar la subida de archivos de manera eficiente y segura, para que los archivos sean almacenados y accesibles de forma adecuada.                             | Escenario 1: Carga exitosa de archivos dentro del límite de tamaño permitido. Dado que un usuario sube un archivo, cuando el archivo se almacena en el servidor, entonces el sistema genera una URL única de acceso al archivo y la almacena en la base de datos.<br> Escenario 2: Rechazo de carga por exceder el límite de tamaño de archivo. Dado que el archivo supera el tamaño permitido, cuando el usuario intenta subirlo, entonces el sistema rechaza la subida y devuelve un mensaje de error con el límite de tamaño permitido.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EP08                   |
| US29           | Notificaciones en Tiempo Real                | Como Administrador, quiero implementar un sistema de notificaciones en tiempo real, para que los usuarios reciban alertas instantáneas de eventos importantes.                            | Escenario 1: El usuario inició sesión. Dado que se produce un evento relevante (nueva solicitud, mensaje, actualización), cuando el usuario está conectado a la plataforma, entonces el sistema envía una notificación en tiempo real utilizando WebSockets o tecnologías similares.<br> Escenario 2: El usuario no inició sesión. Dado que el usuario no está conectado, cuando se produce un evento, entonces el sistema almacena la notificación y la muestra al usuario la próxima vez que inicie sesión.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | EP08                   |
| US30           | Filtrado y Ordenación de Recursos            | Como administrador de la API, quiero filtrar y ordenar los resultados de los listados, para gestionar los recursos de manera más eficiente.                                               | Escenario 1: Filtros aplicados.<br> **Dado** que el administrador consulta una lista de recursos, **cuando** utiliza parámetros de filtro como `role=admin`, **entonces** el sistema debe devolver solo los recursos que coincidan con ese filtro.<br> Escenario 2: Ordenación de resultados.<br> **Dado** que el administrador desea ordenar los resultados, **cuando** utiliza los parámetros `sort` y `order` (por ejemplo, `sort=created_at&order=desc`), **entonces** el sistema debe devolver los resultados en el orden especificado.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP08                   |
| US31           | Actualización de Información del Usuario     | Como administrador, quiero poder actualizar el perfil de un usuario a través de la API, para gestionar los datos de los usuarios de la plataforma.                                        | Escenario 1: Actualización exitosa.<br> **Dado** que el administrador desea actualizar la información de un usuario, **cuando** envía una solicitud `PUT /api/users/{id}` con los datos actualizados, **entonces** el sistema debe validar y actualizar los datos en la base de datos.<br> Escenario 2: Error en campos no permitidos.<br> **Dado** que intenta actualizar campos no permitidos, **cuando** envía la solicitud, **entonces** el sistema debe devolver un error especificando qué campos no son modificables.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP08                   |

## 3.3. Impact Mapping.

![impact-mappig](./assets/Impact-map.png)

## 3.4. Product Backlog.

| # Orden | User ID | Título                                   | Descripción                                                                                                                                                          | Story Points |
| ------- | ------- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| 1       | US08    | Validación de Registro                   | Como administrador, quiero un mecanismo de autentificación segura para verificar las credenciales del registro de cuenta.                                            | 8            |
| 2       | US21    | Registro de Medios de Pago               | Como Niñera, quiero recibir pagos a través de la plataforma, para asegurar una transacción segura y sencilla.                                                        | 8            |
| 3       | US25    | Autentificación de Usuarios              | Como Administrador de la API, quiero autenticarme con mis credenciales, para gestionar los recursos protegidos de la plataforma.                                     | 8            |
| 4       | US26    | Gestión de Roles y Permisos              | Como Administrador, quiero definir roles y permisos para que los usuarios accedan a diferentes funciones de la plataforma.                                           | 8            |
| 5       | US29    | Notificaciones en Tiempo Real            | Como Administrador, quiero implementar notificaciones en tiempo real para alertas instantáneas de eventos importantes.                                               | 8            |
| 6       | US07    | Registro como Niñera                     | Como Niñera, quiero registrarme y crear un perfil detallado para mostrar mi experiencia y certificaciones a los Tutores.                                             | 5            |
| 7       | US14    | Filtrado de Ubicación                    | Como Tutor, quiero buscar niñeras basados en ubicación y servicio para encontrar alguien cercano a mi hogar.                                                         | 5            |
| 8       | US16    | Solicitud de Reserva                     | Como Tutor, quiero solicitar reservas para asegurar disponibilidad de niñeras en los horarios que necesito.                                                          | 5            |
| 9       | US20    | Sistema de Comunicación                  | Como Tutor, quiero enviar mensajes a la niñera contratada para discutir detalles y expectativas.                                                                     | 5            |
| 10      | US22    | Sistema de Pagos                         | Como Tutor, quiero realizar pagos a través de la plataforma para transacciones seguras y sencillas.                                                                  | 5            |
| 11      | US27    | Optimización de Consultas a la BD        | Como Administrador, quiero optimizar consultas a la base de datos para respuestas más rápidas y eficientes.                                                          | 5            |
| 12      | US28    | Gestión de Archivos Subidos              | Como Administrador, quiero manejar la subida de archivos de manera eficiente y segura para su almacenamiento y acceso.                                               | 5            |
| 13      | US06    | Registro del Usuario                     | Como Tutor, quiero crear una cuenta para buscar niñeras y gestionar reservas para mi hijo.                                                                           | 3            |
| 14      | US10    | Actualización de cuenta de la Niñera     | Como Niñera, quiero actualizar mi perfil con experiencia y certificaciones para atraer más Tutores.                                                                  | 3            |
| 15      | US11    | Ingreso de Horario de Disponibilidad     | Como Niñera, quiero ingresar mi disponibilidad para que los Tutores vean mis horarios de atención.                                                                   | 3            |
| 16      | US17    | Actualización de Solicitud de Reserva    | Como Tutor, quiero actualizar mis reservas para cambiar horarios o cancelar si es necesario.                                                                         | 3            |
| 17      | US18    | Vista de Solicitudes                     | Como Niñera, quiero recibir notificaciones de solicitudes de reserva en tiempo real para visualizarlas.                                                              | 3            |
| 18      | US30    | Filtrado y Ordenación de Recursos        | Como administrador de la API, quiero filtrar y ordenar resultados para gestionar recursos eficientemente.                                                            | 3            |
| 19      | US31    | Actualización de Información del Usuario | Como administrador, quiero actualizar perfiles de usuarios a través de la API para gestionar sus datos.                                                              | 3            |
| 20      | US09    | Actualización de cuenta del Tutor        | Como Tutor, quiero actualizar mi perfil para añadir detalles sobre necesidades especiales de mi hijo.                                                                | 2            |
| 21      | US12    | Actualizar Horario de Disponibilidad     | Como Niñera, quiero actualizar mis horarios para que los padres vean cuándo estoy disponible.                                                                        | 2            |
| 22      | US13    | Gestión de Costos de Servicios           | Como Niñera, quiero establecer tarifas por hora/sesión para que los Tutores sepan mi costo.                                                                          | 2            |
| 23      | US19    | Gestión de Solicitudes                   | Como Niñera, quiero gestionar solicitudes recibidas para aceptar o rechazar reservas.                                                                                | 2            |
| 24      | US23    | Sistema de Reseñas                       | Como Tutor, quiero dejar reseñas sobre niñeras para ayudar a otros Tutores a decidir.                                                                                | 2            |
| 25      | US15    | Visualización de Perfil                  | Como Tutor, quiero ver certificaciones y antecedentes de niñeras para asegurar que sean adecuadas para mi hijo.                                                      | 1            |
| 26      | US24    | Visualización de Reseñas                 | Como Niñera, quiero visualizar reseñas de tutores para identificar áreas de mejora.                                                                                  | 1            |
| 27      | US01    | Visualizar la Descripcion clara del app  | Como visitante, quiero ver una descripción clara de la app para entender su valor y lo que ofrece.                                                                   | 1            |
| 28      | US02    | Testimonios de Usuarios                  | Como visitante, quiero ver testimonios reales para confiar en el servicio de la app                                                                                  | 1            |
| 29      | US03    | Lista de Características                 | Como visitante, visualizar las características principales de la app para conocer sus funcionalidades antes de registrarme y decidir si se ajusta a mis necesidades. | 1            |
| 30      | US04    | Contacto con la Equipo                   | Como visitante, quiero contactar al equipo para tener un medio directo con el equipo de desarrollo.                                                                  | 1            |
| 31      | US05    | Beneficios                               | Como visitante, quiero conocer los beneficios y funciones que ofrece la app, para conocer sus servicios..                                                            | 1            |

link de Trello : [https://trello.com/invite/b/67f6a7f270ad52954f91b6ac/ATTI705356836b6476fe05a897e8fbdc0db837CDF36C/1asi0730-2510-4380-grupo-3-quantumsoft](https://trello.com/invite/b/67f6a7f270ad52954f91b6ac/ATTI705356836b6476fe05a897e8fbdc0db837CDF36C/1asi0730-2510-4380-grupo-3-quantumsoft)

# Capítulo IV: Product Design 
## 4.1. Style Guidelines.

En **KindyCare**, establecemos pautas de estilo sólidas para garantizar una experiencia visual coherente, profesional y centrada en el usuario. Estas directrices abarcan tanto el diseño general como los elementos específicos de la interfaz web, con el fin de proyectar una imagen de confianza, seguridad y calidez para los padres y tutores que buscan cuidado infantil de calidad. 

### 4.1.1. General Style Guidelines.
**Task:**  
En esta sección, se detallarán las directrices generales de estilo que guiarán el diseño y la presentación de **KindyCare**. Estas directrices asegurarán que todos los elementos visuales y textuales sean coherentes y alineados con la identidad de nuestra marca, proporcionando una experiencia de usuario fluida, confiable y profesional.

**Insight:**  
La consistencia en el estilo y diseño es crucial para establecer una identidad de marca sólida y reconocible en KindyCare. Una guía de estilo clara ayuda a mantener la coherencia a lo largo del proyecto, asegurando que la plataforma refleje confianza y profesionalismo en cada interacción, facilitando la navegación y el uso para los padres que buscan cuidadores y profesores confiables.

**Branding:**  
El logo de **KindyCare** está compuesto por una figura de una casa colorida que simboliza el cariño, la enseñanza, la atención y el compromiso con el bienestar infantil. Los colores de la marca reflejan suavidad y confianza: tonos pastel cálidos que evocan cercanía, amabilidad y profesionalismo.

<p align="center">
  <img src="./assets/logo.png" alt="Logo" width="850">
</p>

**Typography:**  
Se utiliza una fuente moderna y altamente legible tanto en pantallas móviles como de escritorio. La tipografía se seleccionó para facilitar la lectura, evitar la fatiga visual y transmitir accesibilidad y claridad. Se distinguen visualmente los títulos, subtítulos y textos informativos mediante jerarquías tipográficas bien definidas.

<p align="center">
  <img src="./assets/tipografy app web.png" alt="tipografy" width="850">
</p>

<p align="center">
  <img src="./assets/colors.png" alt="colors" width="850">
</p>

**Íconos y Elementos Gráficos:**  
Los íconos son minimalistas, con bordes redondeados y líneas suaves. Se emplean para guiar al usuario en la navegación y mejorar la comprensión del contenido sin sobrecargar visualmente la interfaz.


### 4.1.2. Web Style Guidelines

**Landing Page:**  
La página principal está diseñada para ofrecer un resumen claro y conciso del servicio. Se destacan los beneficios de KindyCare, el proceso para conectar con cuidadores y profesores, y los llamados a la acción para registrarse o buscar servicios. Desde el primer acceso, los usuarios deben sentir que han llegado a un espacio seguro, accesible y confiable.

**Diseño Responsivo:**  
La interfaz de KindyCare se adapta perfectamente a dispositivos móviles, tabletas y computadoras. Se optimiza el contenido para cada tamaño de pantalla, manteniendo la claridad y facilidad de uso en todos los contextos.

**Espaciado y Alineación:**  
Usamos una escala basada en múltiplos de 4px para todos los márgenes y rellenos, asegurando consistencia y armonía en el diseño. Este sistema permite que los elementos respiren adecuadamente, creando una experiencia visual agradable y ordenada.

**Colores y Contraste:**  
La paleta de colores incluye tonos suaves como el azul cielo, verde menta y durazno pastel, combinados con acentos más vibrantes para botones y enlaces. Estos colores no solo son agradables a la vista, sino que también cumplen con estándares de accesibilidad para asegurar el contraste suficiente.

**Imágenes y Fondos:**  
Las imágenes utilizadas en la plataforma son cuidadosamente seleccionadas para representar el objetivo de KidyCare: el bienestar y la educación infantil. Se han optado por imágenes que reflejan confianza y cuidado, alineadas con los valores de la plataforma. El uso de fondos claros y limpios asegura que la atención del usuario permanezca en la información y las llamadas a la acción principales.

---

## 4.2. Information Architecture

El diseño de la plataforma KindyCare responde a la necesidad de crear una experiencia simple, segura y eficiente tanto para padres como para cuidadores. La organización de la información se estructura para facilitar la navegación, el descubrimiento de servicios y la interacción entre usuarios.

## 1. Página de Inicio

- **Vista Previa de Cuidadores Disponibles:**  
  Muestra cuidadores destacados o populares para captar la atención de los padres que buscan servicios.

- **Registro de Cuidadores:**  
  Enlace directo para que nuevos cuidadores puedan registrarse en la plataforma y comenzar a ofrecer sus servicios.

- **Quiénes Somos y Contacto:**  
  Información sobre la misión de la plataforma, los valores fundamentales y los medios de contacto para consultas o asistencia.

## 2. Buscar Cuidadores (Para Padres y Tutores)

- **Categorías de Servicios:**  
  Sección que agrupa los servicios de cuidado infantil según las necesidades específicas: cuidado a tiempo completo, cuidado parcial, cuidado de niños con necesidades especiales, etc.

- **Filtros de Búsqueda:**  
  Herramientas que permiten a los padres filtrar cuidadores según criterios como experiencia, calificaciones, precio, ubicación y disponibilidad.

- **Vista Detallada de Perfiles:**  
  Cada cuidador cuenta con una página individual que muestra su experiencia, calificaciones, tarifas, disponibilidad y certificaciones.

## 3. Registro de Cuidadores

- **Formulario de Registro:**  
  Formulario para que los cuidadores se registren en la plataforma, ingresando información como experiencia, habilidades, certificaciones y disponibilidad.

- **Gestión de Servicios:**  
  Una vez registrados, los cuidadores pueden crear o editar su perfil, subir certificaciones y gestionar su disponibilidad.

- **Historial de Servicios y Pagos:**  
  Los cuidadores pueden revisar un historial de los servicios que han realizado, las calificaciones obtenidas y los pagos recibidos.

## 4. Reservar Servicios de Cuidado

- **Interfaz de Reserva:**  
  Una interfaz simple para que los padres seleccionen el cuidador, fecha y hora para reservar el servicio de cuidado infantil.

- **Vista Previa y Confirmación:**  
  Los padres pueden visualizar los detalles de la reserva antes de confirmar, incluyendo la tarifa total y la duración del servicio.

---

### 4.2.1. Organization Systems

1. **Categorización de la Información:**

   - **Perfiles de Cuidadores:**  
     Categorizados por experiencia, tipo de cuidado (niños pequeños, cuidado especializado, cuidado nocturno, etc.) y certificaciones.

   - **Servicios de Cuidado:**  
     Categorizados por tiempo completo, medio tiempo, ocasional, etc.

2. **Filtros y Búsqueda:**

   - **Filtros para Padres:**  
     Los padres pueden filtrar los cuidadores según la ubicación, experiencia, precio, calificaciones, disponibilidad y otros parámetros.

   - **Búsqueda Avanzada:**  
     Función que permite a los padres buscar cuidadores con características específicas, como "cuidadores con experiencia en niños con necesidades especiales" o "cuidadores disponibles los fines de semana".

3. **Interfaz de Usuario Intuitiva:**

   - **Menú Principal:**  
     Un menú claro y accesible que incluye las secciones clave: Buscar Cuidadores, Registro de Cuidadores, Historial de Servicios, y Perfil de Usuario.

   - **Submenús Contextuales:**  
     Dentro de las secciones principales, los submenús guían a los usuarios hacia opciones específicas como "cuidado a tiempo completo" o "cuidado de niños con necesidades especiales".

4. **Funcionalidades Específicas:**

   - **Perfiles de Cuidadores:**  
     Cada cuidador tiene una página individual que muestra su experiencia, certificaciones, calificaciones, tarifas y disponibilidad, junto con una opción para contactarlo o reservar un servicio.

   - **Reservas:**  
     Los padres pueden gestionar y ver sus reservas previas, y repetir servicios con cuidadores específicos desde su historial.

---

### 4.2.2. Labeling Systems

Para mejorar la navegación, KindyCare utiliza etiquetas claras y descriptivas:

- Buscar Cuidadores  
- Registrarse como Cuidador  
- Reservar Servicio  
- Historial de Servicios  
- Mi Perfil  
- Certificaciones y Habilidades  
- Disponibilidad

---

### 4.2.3. SEO Tags and Meta Tags

Cada página de la plataforma incluirá:

- Meta título con palabras clave relevantes como *"cuidado infantil seguro"*, *"niñeras calificadas cerca de mí"*, etc.  
- Meta descripciones optimizadas para buscadores.  
- Uso estratégico de etiquetas `alt` en imágenes para mejorar accesibilidad y SEO.

---

### 4.2.4. Searching Systems

El sistema de búsqueda dentro de la plataforma permitirá a los padres y cuidadores encontrar la información que necesitan de manera rápida y eficaz.

1. **Búsqueda por Tipo de Cuidado:**  
   Ej.: "cuidado nocturno", "cuidado a tiempo completo", "cuidado de niños con necesidades especiales".

2. **Búsqueda por Ubicación:**  
   Filtro de resultados según proximidad al hogar.

   - Por Tipo de Servicio: Cuidado nocturno, apoyo escolar, acompañamiento en casa, etc.  
   - Por Ubicación: Integración con mapas.  
   - Por Calificación: Filtro por puntuación y reseñas.  
   - Por Certificación o Idioma: Habilidades específicas.  
   - Por Rango de Precio y Disponibilidad: Compatible con calendarios.

---

### 4.2.5. Navigation Systems

El sistema de navegación está diseñado para ofrecer una experiencia fluida, fácil de usar y segura para ambos segmentos (padres y cuidadores).

1. **Menú Principal (Dashboard):**  
   Siempre visible, con acceso a todas las secciones clave.

2. **Navegación Contextual:**  
   Submenús personalizados que facilitan el acceso a categorías específicas.

3. **CTA (Call to Action) destacados:**  
   Botones como "Buscar Cuidadores", "Reservar Ahora" o "Postularme como Cuidador", resaltados con colores vibrantes.

4. **Barra de Búsqueda Fija:**  
   Siempre visible para facilitar búsquedas rápidas y directas.

5. **Flujo de Navegación Intuitivo:**  
   Desde la búsqueda hasta la reserva de servicios, con un flujo lógico y claro que guía a los usuarios en cada etapa.

## 4.3. Landing Page UI Design. 
### 4.3.1. Landing Page Wireframe.
**Hero Section**
<p align="center">
  <img src="./assets/hero-section-wireframe.png" alt="Hero Section" width="850">
</p>

**Features Section**
<p align="center">
  <img src="./assets/features-section-wireframe.png" alt="Features Section" width="850">
</p>

**Benefits Section**
<p align="center">
  <img src="./assets/benefits-section-wireframe.png" alt="Benefits Section" width="850">
</p>

**Steps Section**
<p align="center">
  <img src="./assets/steps-section-wireframe.png" alt="Steps Section" width="850">
</p>

**Testimonial Section**
<p align="center">
  <img src="./assets/testimonial-section-wireframe.png" alt="Testimonial Section" width="850">
</p>

**Contact Section**
<p align="center">
  <img src="./assets/contact-section-wireframe.png" alt="Contact Section" width="850">
</p>

### 4.3.2. Landing Page Mock-up.
**Hero Section**
<p align="center">
  <img src="./assets/hero-section-mockup.png" alt="Hero Section" width="850">
</p>

**Features Section**
<p align="center">
  <img src="./assets/features-section-mockup.png" alt="Features Section" width="850">
</p>

**Benefits Section**
<p align="center">
  <img src="./assets/benefits-section-mockup.png" alt="Benefits Section" width="850">
</p>

**Steps Section**
<p align="center">
  <img src="./assets/steps-section-mockup.png" alt="Steps Section" width="850">
</p>

**Testimonial Section**
<p align="center">
  <img src="./assets/testimonial-section-mockup.png" alt="Testimonial Section" width="850">
</p>

**Contact Section**
<p align="center">
  <img src="./assets/contact-section-mockup.png" alt="Contact Section" width="850">
</p>

## 4.4. Web Applications UX/UI Design. 
### 4.4.1. Web Applications Wireframes.
**Log In**

<p align="center">
  <img src="./assets/wireframes-app/login.png" alt="Log In" width="850">
</p>

**Sign Up**
<p align="center">
  <img src="./assets/wireframes-app/signup.png" alt="Sign Up" width="850">
</p>

**Babysitter List**  
<p align="center">
  <img src="./assets/wireframes-app/babysitter-list.png" alt="Babysitter List" width="850">
</p>

**Babysitter Detail**  
<p align="center">
  <img src="./assets/wireframes-app/babysitter-detail.png" alt="Babysitter Detail" width="850">
</p>

**Babysitter Profile**
<p align="center">
  <img src="./assets/wireframes-app/babysitter-profile.png" alt="Babysitter Profile" width="850">
</p>

**Babysitter Review**  
<p align="center">
  <img src="./assets/wireframes-app/review-babysitter.png" alt="Babysitter Review" width="850">
</p>

**Babysitter Booking**  
<p align="center">
  <img src="./assets/wireframes-app/booking-babysitter.png" alt="Babysitter Booking" width="850">
</p>

**Babysitter Payment**  
<p align="center">
  <img src="./assets/wireframes-app/payment-babysitter.png" alt="Babysitter Payment" width="850">
</p>

**Parent Profile**  
<p align="center">
  <img src="./assets/wireframes-app/parent-profile.png" alt="Parent Profile" width="850">
</p>

**Parent Review**  
<p align="center">
  <img src="./assets/wireframes-app/review-parent.png" alt="Log In" width="850">
</p>

**Parent Payment**  
<p align="center">
  <img src="./assets/wireframes-app/payment-parent.png" alt="Parent Payment" width="850">
</p>

**Parent Booking**  
<p align="center">
  <img src="./assets/wireframes-app/booking-parent.png" alt="Parent Booking" width="850">
</p>

**Chat**  
<p align="center">
  <img src="./assets/wireframes-app/chat.png" alt="Chat" width="850">
</p>

**Dashboard**  
<p align="center">
  <img src="./assets/wireframes-app/main-dashboard.png" alt="Dashboard" width="850">
</p>

### 4.4.2. Web Applications Wireflow Diagrams. 

### 4.4.2. Web Applications Mock-ups.
**Log In**

<p align="center">
  <img src="./assets/mockups-app/login.png" alt="Log In" width="850">
</p>

**Sign Up**
<p align="center">
  <img src="./assets/mockups-app/signup.png" alt="Sign Up" width="850">
</p>

**Babysitter List**  
<p align="center">
  <img src="./assets/mockups-app/babysitters-list.png" alt="Babysitter List" width="850">
</p>

**Babysitter Detail**  
<p align="center">
  <img src="./assets/mockups-app/babysitter-detail.png" alt="Babysitter Detail" width="850">
</p>

**Babysitter Profile**
<p align="center">
  <img src="./assets/mockups-app/profile-babysitter.png" alt="Babysitter Profile" width="850">
</p>

**Babysitter Review**  
<p align="center">
  <img src="./assets/mockups-app/review-babysitter.png" alt="Babysitter Review" width="850">
</p>

**Babysitter Booking**  
<p align="center">
  <img src="./assets/mockups-app/booking-babysitter.png" alt="Babysitter Booking" width="850">
</p>

**Babysitter Payment**  
<p align="center">
  <img src="./assets/mockups-app/payment-babysitter.png" alt="Babysitter Payment" width="850">
</p>

**Parent Profile**  
<p align="center">
  <img src="./assets/mockups-app/profile-parent.png" alt="Parent Profile" width="850">
</p>

**Parent Review**  
<p align="center">
  <img src="./assets/mockups-app/review-parent.png" alt="Log In" width="850">
</p>

**Parent Payment**  
<p align="center">
  <img src="./assets/mockups-app/payment-parent.png" alt="Parent Payment" width="850">
</p>

**Parent Booking**  
<p align="center">
  <img src="./assets/mockups-app/booking-parent.png" alt="Parent Booking" width="850">
</p>

**Chat**  
<p align="center">
  <img src="./assets/mockups-app/chat.png" alt="Chat" width="850">
</p>

**Dashboard**  
<p align="center">
  <img src="./assets/mockups-app/main-dashboard.png" alt="Dashboard" width="850">
</p> 

### 4.4.3. Web Applications User Flow Diagrams. 

## 4.5. Web Applications Prototyping.
<p align="center">
  <img src="./assets/prototyping.png" alt="Prototyping" width="850">
</p>  

## 4.6. Domain-Driven Software Architecture. 
### 4.6.1. Software Architecture Context Diagram.
<p align="center">
  <img src="./assets/context-diagram.png" alt="context-diagram" width="850">
</p> 

### 4.6.2. Software Architecture Container Diagrams. 
<p align="center">
  <img src="./assets/container-diagram.png" alt="container-diagram" width="850">
</p>

### 4.6.3. Software Architecture Components Diagrams. 
<p align="center">
  <img src="./assets/components-diagram.png" alt="components-diagram" width="850">
</p>

## 4.7. Software Object-Oriented Design. 
### 4.7.1. Class Diagrams.
<p align="center">
  <img src="./assets/class-diagram.jpg" alt="class-diagram" width="850">
</p>

### 4.7.2. Class Dictionary. 
| Clase         | Descripción                                                                                                                                  |
|---------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| User          | Representa a cualquier persona que utiliza la plataforma, ya sea padre o niñera. Contiene información general como nombre, email y rol.     |
| Parent        | Es una especialización de User. Representa a los usuarios que buscan contratar servicios de niñeras para el cuidado de sus hijos.           |
| Babysitter    | También especializada desde User. Representa a las niñeras registradas, incluyendo su perfil, experiencia, disponibilidad y calificaciones. |
| Message       | Representa un mensaje individual enviado entre usuarios dentro de una sesión de chat. Incluye contenido, hora de envío y emisor/receptor.    |
| ChatSession   | Define una conversación entre un padre y una niñera. Agrupa todos los mensajes relacionados a una interacción específica.                    |
| Notification  | Almacena alertas generadas para los usuarios, como confirmaciones de reserva, nuevos mensajes y pagos.|
| Availability  | Registra los días y horas que una niñera está disponible para ser contratada. Se vincula con su perfil para facilitar las búsquedas.         |
| Reservation   | Representa una reserva de servicio entre un padre y una niñera, incluyendo fechas, duración, estado (pendiente, aceptada, cancelada, etc).  |
| Review        | Almacena comentarios y calificaciones que los padres dejan sobre las niñeras después de una reserva. Ayuda a construir reputación.           |
| Payment       | Registra transacciones realizadas por los padres para pagar por los servicios contratados despues de una reserva, y puede incluir métodos de pago y estado.         |

## 4.8. Database Design.
### 4.8.1. Database Diagram. 
<p align="center">
  <img src="./assets/database-diagram.png" alt="database-diagram" width="850">
</p>


# Capítulo V: Product Implementation, Validation & Deployment  
## 5.1. Software Configuration Management.

A continuación, se describe el proceso por el cual organizamos, gestionamos y controlamos los cambio de desarrollo de KydiCare.

### 5.1.1. Software Development Environment Configuration.

Gestión de las necesidades

  - Trello: Herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente marcos en red de trabajos ágiles. El segmento para visualizar y actualizar el estado real de las tareas e historias de usuario pertenecientes al sprint a desarrollado.
  
    Ruta de referencia:[https://trello.com/es](https://trello.com/es)

Diseño UX/UI

  - Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizada para el diseño digital. En el caso del proyecto, se utilizó para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.

    Ruta de referencia: https://www.figma.com/login

  - Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de flujos de cable, flujos de usuario y el diagrama de clases asociadas a la aplicación.
    Ruta de referencia: https://www.lucidchart.com/

Desarrollo de software

  - Visual Studio Code: Entorno de desarrollo integrado elegido para la elaboración y compilación de los factores de control por dominio por parte de los integrantes del equipo de trabajo. Utilizar este IDE supone valor para el desarrollo del proyecto puesto que incluye la posibilidad de añadir extensiones de utilidad, soporte de edición de texto en múltiples lenguajes de programación, disponibilidad en varios sistemas, operativos entre otros beneficios.
    Ruta de referencia: https://code.visualstudio.com/

  - HTML5: HyperText Markup Language, o siglas por sus HTML, es un lenguaje de etiquetado para páginas web. Será empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación.
    Ruta de referencia: https://www.w3schools.com/html/html5-syntax.asp

  - CSS: Hojas de estilo en cascada es un lenguaje que maneja el diseño y presentación de las páginas web, el que va de la mano con HTML.
    Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html

  - Bootstrap: Marco CSS que crea motores web de forma rápida y eficiente. Bootstrap se utilizará para la creación de la interfaz responsiva, asegurando que la plataforma funcione correctamente en distintos dispositivos.
    Ruta de referencia: https://getbootstrap.com/

  
Implementación de software

  - Git: Una herramienta de control de versiones que facilitan el registro y la gestión de las versiones distintas del programa. Su propósito es mantener un historial de cambios y simplificar el corrección de errores. Los integrantes del equipo A través de la línea de comandos en sus sistemas locales.

    Ruta de referencia: https://git-scm.com/

    Documentación y gestión de proyectos de software

  - Github: Una plataforma en la nube que hospedará los repositorios de código del proyecto. Permitir la colaboración en tiempo real y la revisión de las contribuciones de cada miembro del equipo. Los integrantes del equipo se puede acceder a través de sus navegadores web.
    Ruta de referencia: https://github.com/


### 5.1.2. Source Code Management. 

El proyecto sigue el flujo de trabajo GitFlow para el control de versiones, GitHub como plataforma de alojamiento y gestión del código. A continuación, se detalla la implementación de este modelo.

**Flujo de trabajo GitFlow**

Flujo de Trabajo GitFlow para el Desarrollo de UniRider

El proyecto adopta el modelo GitFlow, una estrategia de ramificación basada en Git diseñada para optimizar la colaboración y el control de versiones en equipos de desarrollo. Este enfoque organiza el trabajo en ramas específicas, una integración fluida de nuevas funcionalidades y una gestión eficiente de lanzamientos.

Ramas Principales

  - main(principal)

    - Contiene el código estable y listo para la producción, correspondiente a las versiones oficiales de KydiCare.

    - Cada release se marca con etiquetas semánticas (ej. v1.0.0) para facilitar el rastreo y la aplicación de las actualizaciones.

  - develop(rama de desarrollo)

    - Alberga la versión más reciente en estado de preproducción, donde se integran todas las funcionalidades completadas.

    - Funciona como base para pruebas internas y ajustes previos a su fusión con main.

Ramas de Soporte

  - feature/*(ramas de características)

    - Cada nueva funcionalidad se desarrolla en un rama independiente (ej. feature/login), derivada de develop.

    - Perfilo trabajo paralelo sin afectar la base de los códigos principales hasta su revisión y aprobación.

  - release/*(ramas de lanzamiento)

    - Preparadas para versiones específicas, permiten pruebas finales y corrección de bugs antes de su despliegue en main.

  - hotfix/*(ramas de las urgencias)

    - Resuelven errores desprendentes en producción, derivando directamente de mainy fusión tanto en maincomo en develop.
  
  ![Git-Flow](./assets/git-flow.png)

### 5.1.3. Source Code Style Guide & Conventions. 

Para garantizar coherencia, mantenibilidad y escalabilidad del código, se establecen las siguientes normas de estilo:

  1. HTML
Estructura básica  
        
          <!DOCTYPE html>
          HTM lang = " es ">

     - Reglas generales:
        - Todos los elementos deben estar correctamente cerrados 

               (ej. <img />, <div></div>).

         - Usar comillas dobles (" ") en atributos que contengan espacios.

         - Incluir atributos esenciales en imágenes.


1. CSS

    Formato:

      - Sangría: 2 espacios (sin pestañas).

      - Minúsculas en Selectores, propiedades y valores.

      - Empiteación en blanco innecesarios y líneas vacías redundantes.

2. Tailwind

    Principios:

      - Aprovechar al máximo las utilidades predefinidas (sistema de red, componentes, ayudantes).

      - Evitar sobrescribir estilos base; usar clases contextuales (ej. bg-primary, text-success).

      - Solo agrega CSS personalizado.

3. vue.js

    Reglas clave:

    - Nombres de Compentes: PascalCase(Ej: UserProfile.vue)
    - Props: Definir tipos y valores por defecto.
  

### 5.1.4. Software Deployment Configuration. 

  Hemos seleccionado GitHub Pages como plataforma para alojar el sitio web estático del proyecto. A continuación se detalla el proceso completo:

  1. **Creación del repositorio en GitHub:**

    - Primero, se debe crear un nuevo repositorio en GitHub. Asegúrate de que el repositorio sea público para que GitHub Pages pueda generar y alojar el sitio.
   - Clona el repositorio a tu máquina local para realizar los desarrollos necesarios.
   - **Ejemplo:**
     ```bash
     git clone https://github.com/2025-1-AplicacionesWeb-QuantumSoft/project-report-childcard.git
     ```
  2. **Desarrollo del sitio estático:**

   - El desarrollo del **Landing Page** se realiza utilizando HTML, CSS, Tailwind.css , JavaScript y vue.js. Estos archivos deben estar en la raíz del repositorio o en la carpeta `docs`, dependiendo de la configuración elegida para GitHub Pages.

  3. **Configuración de GitHub Pages:**

   - Dirígete a la configuración del repositorio en GitHub:
     - Ir a la seccion `Settings`.
     - Desplázate hacia abajo hasta la sección **Pages**.
     - En el menú desplegable "Source", selecciona la creada `gh-pages`  y la carpeta raíz (`/root`) o `docs/` si los archivos están organizados dentro de esa carpeta.
   - Una vez seleccionado, GitHub Pages generará una URL para acceder a tu sitio web.
  
  4. **Verificar el despliegue:**
    - En este caso, el **Link del Landing Page desplegado del proyecto KYDICARE** es:  
     [Landing Page SafeChild](https://2025-1-aplicacionesweb-quantumsoft.github.io/landing-page/)


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
