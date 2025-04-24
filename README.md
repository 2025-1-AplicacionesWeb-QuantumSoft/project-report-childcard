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

- Padres de Familia

- Niñeras

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
| US01           | Visualizar la Descripcion clara del app      | Como visitante, quiero ver una descripción clara de la app para entender su valor y lo que ofrece.                                                                                        | Escenario 1:Visitante visualiza informacion clara de la app <br> _Dado_ que el visitante accede a la landing page <br> _Cuando_ la pagina carga completamente <br> _Entonces_, visualiza un titular con el texto "Encuentra niñeras confiables en minutos"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EP01                   |
| US02           | Testimonios de Usuarios                      | Como visitante, quiero ver testimonios reales para confiar en el servicio de la app                                                                                                       | Escenario 1: El visitante visualiza testimonios de usuarios que utilizaran la app <br> _Dado_ que el visitante esta en la seccion "Testimonios"<br> _Cuando_ se despliega la pagina <br> _Entonces_, visualizará tarjetas con testimonios de opinion de la app                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | EP01                   |
| US03           | Acceso Directo                               | Como visitante, quiero acceder directo al sitio web para no tener que buscar en el navegador.                                                                                             | Escenario 1: El visitante accede al sitio web <br> _Dado_ que el visitante esta en la seccion del Navbar <br> _Cuando_ busca al boton acceder y lo presina <br> _Entonces_, el boton lo enlaza al sitio web.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP01                   |
| US04           | Contacto con la Equipo                       | Como visitante, quiero contactar al equipo para tener un medio directo con el equipo de desarrollo.                                                                                       | Escenario 1: El visitante accede al sitio web <br> _Dado_ que el visitante esta en la seccion del Navbar <br> _Cuando_ busca al boton acceder y lo presina <br> _Entonces_, el boton lo enlaza al sitio web.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP01                   |
| US05           | Equipo de Desarrollo                         | Como visitante, quiero conocer a los miembros del equipo de desarrollo del proyecto, para conocer sus papeles.                                                                            | Escenario 1: El visitante visualiza al equipo desarrollo <br> _Dado_ que el visitante esta en la landing page <br> _Cuando_ esta en la seccion "Team" <br> _Entonces_, visualizará los perfiles del equipo de desarrollo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | EP01                   |
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

## 3.4. Product Backlog.

| # Orden | User ID | Título                                   | Descripción                                                                                                                      | Story Points |
| ------- | ------- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| 1       | US08    | Validación de Registro                   | Como administrador, quiero un mecanismo de autentificación segura para verificar las credenciales del registro de cuenta.        | 8            |
| 2       | US21    | Registro de Medios de Pago               | Como Niñera, quiero recibir pagos a través de la plataforma, para asegurar una transacción segura y sencilla.                    | 8            |
| 3       | US25    | Autentificación de Usuarios              | Como Administrador de la API, quiero autenticarme con mis credenciales, para gestionar los recursos protegidos de la plataforma. | 8            |
| 4       | US26    | Gestión de Roles y Permisos              | Como Administrador, quiero definir roles y permisos para que los usuarios accedan a diferentes funciones de la plataforma.       | 8            |
| 5       | US29    | Notificaciones en Tiempo Real            | Como Administrador, quiero implementar notificaciones en tiempo real para alertas instantáneas de eventos importantes.           | 8            |
| 6       | US07    | Registro como Niñera                     | Como Niñera, quiero registrarme y crear un perfil detallado para mostrar mi experiencia y certificaciones a los Tutores.         | 5            |
| 7       | US14    | Filtrado de Ubicación                    | Como Tutor, quiero buscar niñeras basados en ubicación y servicio para encontrar alguien cercano a mi hogar.                     | 5            |
| 8       | US16    | Solicitud de Reserva                     | Como Tutor, quiero solicitar reservas para asegurar disponibilidad de niñeras en los horarios que necesito.                      | 5            |
| 9       | US20    | Sistema de Comunicación                  | Como Tutor, quiero enviar mensajes a la niñera contratada para discutir detalles y expectativas.                                 | 5            |
| 10      | US22    | Sistema de Pagos                         | Como Tutor, quiero realizar pagos a través de la plataforma para transacciones seguras y sencillas.                              | 5            |
| 11      | US27    | Optimización de Consultas a la BD        | Como Administrador, quiero optimizar consultas a la base de datos para respuestas más rápidas y eficientes.                      | 5            |
| 12      | US28    | Gestión de Archivos Subidos              | Como Administrador, quiero manejar la subida de archivos de manera eficiente y segura para su almacenamiento y acceso.           | 5            |
| 13      | US06    | Registro del Usuario                     | Como Tutor, quiero crear una cuenta para buscar niñeras y gestionar reservas para mi hijo.                                       | 3            |
| 14      | US10    | Actualización de cuenta de la Niñera     | Como Niñera, quiero actualizar mi perfil con experiencia y certificaciones para atraer más Tutores.                              | 3            |
| 15      | US11    | Ingreso de Horario de Disponibilidad     | Como Niñera, quiero ingresar mi disponibilidad para que los Tutores vean mis horarios de atención.                               | 3            |
| 16      | US17    | Actualización de Solicitud de Reserva    | Como Tutor, quiero actualizar mis reservas para cambiar horarios o cancelar si es necesario.                                     | 3            |
| 17      | US18    | Vista de Solicitudes                     | Como Niñera, quiero recibir notificaciones de solicitudes de reserva en tiempo real para visualizarlas.                          | 3            |
| 18      | US30    | Filtrado y Ordenación de Recursos        | Como administrador de la API, quiero filtrar y ordenar resultados para gestionar recursos eficientemente.                        | 3            |
| 19      | US31    | Actualización de Información del Usuario | Como administrador, quiero actualizar perfiles de usuarios a través de la API para gestionar sus datos.                          | 3            |
| 20      | US09    | Actualización de cuenta del Tutor        | Como Tutor, quiero actualizar mi perfil para añadir detalles sobre necesidades especiales de mi hijo.                            | 2            |
| 21      | US12    | Actualizar Horario de Disponibilidad     | Como Niñera, quiero actualizar mis horarios para que los padres vean cuándo estoy disponible.                                    | 2            |
| 22      | US13    | Gestión de Costos de Servicios           | Como Niñera, quiero establecer tarifas por hora/sesión para que los Tutores sepan mi costo.                                      | 2            |
| 23      | US19    | Gestión de Solicitudes                   | Como Niñera, quiero gestionar solicitudes recibidas para aceptar o rechazar reservas.                                            | 2            |
| 24      | US23    | Sistema de Reseñas                       | Como Tutor, quiero dejar reseñas sobre niñeras para ayudar a otros Tutores a decidir.                                            | 2            |
| 25      | US15    | Visualización de Perfil                  | Como Tutor, quiero ver certificaciones y antecedentes de niñeras para asegurar que sean adecuadas para mi hijo.                  | 1            |
| 26      | US24    | Visualización de Reseñas                 | Como Niñera, quiero visualizar reseñas de tutores para identificar áreas de mejora.                                              | 1            |
| 27      | US01    | Visualizar la Descripcion clara del app  | Como visitante, quiero ver una descripción clara de la app para entender su valor y lo que ofrece.                               | 1            |
| 28      | US02    | Testimonios de Usuarios                  | Como visitante, quiero ver testimonios reales para confiar en el servicio de la app                                              | 1            |
| 29      | US03    | Acceso Directo                           | Como visitante, quiero acceder directo al sitio web para no tener que buscar en el navegador.                                    | 1            |
| 30      | US04    | Contacto con la Equipo                   | Como visitante, quiero contactar al equipo para tener un medio directo con el equipo de desarrollo.                              | 1            |
| 31      | US05    | Equipo de Desarrollo                     | Como visitante, quiero conocer a los miembros del equipo de desarrollo del proyecto, para conocer sus papeles.                   | 1            |

link de Trello : [https://trello.com/invite/b/67f6a7f270ad52954f91b6ac/ATTI705356836b6476fe05a897e8fbdc0db837CDF36C/1asi0730-2510-4380-grupo-3-quantumsoft](https://trello.com/invite/b/67f6a7f270ad52954f91b6ac/ATTI705356836b6476fe05a897e8fbdc0db837CDF36C/1asi0730-2510-4380-grupo-3-quantumsoft)

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
