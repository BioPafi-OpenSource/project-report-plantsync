# Informe de Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**  

**Ingeniería de Software**  

**5to Ciclo**

**Código del curso:**  1ASI0729

**Nombre del curso:**  Desarrollo de aplicaciones Open Source

**Sección:**  4289

**Nombre del profesor:** BAUTISTA UBILLUS, EFRAIN RICARDO

**Nombre del Startup:** BioPafi

**Nombre del Producto:**  PlantSync

### Relación de Integrantes

| **Código** | **Apellidos y Nombres** |
|--------|----------------------|
|U20231A500|Palomino Fiestas, Erick Leonardo|
|        |Gonzales Alvarado, Javier Sebastian |
|        |Palomares Andrade, Sean Farith |
|        |Rivera Ratachi, Renzo Sebastian|
|        | Torres Apolinario, Giovany Smith|

**Abril 2025**  

---

## Registro de Versiones del Informe

| **Versión** | **Fecha** | **Descripción de cambios** | **Autor(es)** |
|--------|-------|-------------------------|-----------|
| 1.0    |       |                         |           |

---

## Project Report Collaboration Insights

---

## Contenido

- [Student Outcome](#student-outcome)  
- [Capítulo I: Introducción](#capítulo-i-introducción)  
  - [1.1. Startup Profile](#11-startup-profile)  
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
  - [1.2. Solution Profile](#12-solution-profile)  
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)  
    - [1.2.2. Lean UX Process](#122-lean-ux-process)  
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
    - [5.2.1. Sprint 1](#521-sprint-1)  
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)  
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)  
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)  
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

- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)  
- [Video About-the-Team](#video-about-the-team)  
- [Bibliografía](#bibliografía)  
- [Anexos](#anexos)

---

## Student Outcome

---

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup  

Nuestra startup, BioPafi, nace con el propósito de brindar soluciones innovadoras para el cuidado de plantas en el hogar y con ello impulsando un cambio ambiental, combinando el poder las ultimas tecnologias. Nuestro primer producto es PlantSync, una aplicación web y móvil que permite a los usuarios monitorear el estado de sus plantas de interior, registrarlas, recibir notificaciones de riego y fertilización, acceder a guías de cuidado y hasta identificar plantas mediante fotos.

**Visión:**

En 5 años, convertirnos en líderes en tecnología ambiental aplicada al hogar en América Latina, destacándonos por la calidad, accesibilidad e innovación de nuestros productos y servicios.

**Misión:**

Facilitar el cuidado de plantas en el hogar mediante soluciones tecnológicas inteligentes, contribuyendo al bienestar ambiental y al fortalecimiento del vínculo de las personas con la naturaleza.

#### 1.1.2. Perfiles de integrantes del equipo  

| **Foto del Integrantes** | **Nombres y Apellidos** | **Código de estudiante**|**Conocimientos técnicos y habilidades**|
|--------|----------------------|----------------------|----------------------|
| 1 | Erick Leonardo Palomino Fiestas | U20231A500 | Conocimientos técnicos y habilidades |
| 2 | Javier Sebastian Gonzales Alvarado | Código de estudiante | Conocimientos técnicos y habilidades |
| 3 | Sean Farith Palomares Andrade | Código de estudiante | Conocimientos técnicos y habilidades |
| 4 | Renzo Sebastian Rivera Ratachi | Código de estudiante | Conocimientos técnicos y habilidades |
| 5 | Giovany Smith Torres Apolinario | Código de estudiante | Conocimientos técnicos y habilidades |


### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática  

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

El propósito de BioPafi es ofrecer a los hogares peruanos una solución tecnológica amigable que permita monitorear de manera inteligente el estado de las plantas a través de sensores conectados a una plataforma web. Esta solución está dirigida a personas con plantas en casa, quienes desean cuidarlas pero no siempre cuentan con los conocimientos técnicos, el tiempo o los recursos para hacerlo de forma precisa.

El problema se presenta en el momento en que los usuarios deben tomar decisiones sobre el cuidado de sus plantas, como regarlas, moverlas de lugar o protegerlas del clima sin contar con información confiable y en tiempo real sobre su estado. Esta falta de datos conlleva a un cuidado improvisado, que muchas veces resulta en el deterioro de las plantas por exceso o falta de agua, condiciones ambientales inadecuadas, o incluso enfermedades que no son detectadas a tiempo. Actualmente, muchas personas dependen de la observación visual, el tacto o simples aplicaciones de recordatorios, lo que genera márgenes de error significativos en el mantenimiento de sus plantas.

Hemos identificado que esta incertidumbre en el cuidado de las plantas genera frustración, pérdida de tiempo, y en muchos casos, abandono del hábito de jardinería. Esta problemática se intensifica en ambientes urbanos donde las condiciones de iluminación, temperatura, y humedad varían mucho en espacios pequeños. 

A todo esto nos surge la pregunta: ¿Cómo podríamos brindar a las personas una solución inteligente y automatizada que monitoree el estado de sus plantas, brinde alertas de cuidado y recomendaciones personalizadas?

+ **Domain:** Jardinería doméstica y tecnología para el hogar.
+ **Customer Segments:** Personas con plantas en casa, jardineros urbanos, especialistas en botánica.
+ **Pain Points:** Falta de tiempo, desconocimiento sobre el cuidado de plantas, olvidos, riesgo excesivo o insuficiente.
+ **Gap:** No hay soluciones accesible y personalizadas que brinden monitoreo y alertas sencillas de entender y recordar
+ **Vision/Strategy:** Crear una plataforma que conecte sensores IoT con una WebApp amigable que ayude a cuidar plantas mediante recomendaciones en tiempo real.
+ **Initial Segment:** Usuarios domésticos con al menos 3 plantas que busquen automatizar parte del cuidado.

##### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions<br/><br/>

1. **Creemos que nuestros clientes tienen la necesidad de** cuidar adecuadamente sus plantas sin tener conocimientos técnicos ni depender exclusivamente de su intuición.

2. **Estas necesidades se pueden resolver con** un sistema automatizado que proporcione datos confiables, alertas y recomendaciones personalizadas a través de un WebApp conectada con sensores IoT.

3. **Nuestros clientes iniciales serán** personas que ya estan cuidando plantas en casa y busquen automatizar su cuidado.

4. **El principal valor que un cliente espera obtener de nuestro servicio es** la tranquilidad de saber que sus plantas están sanas y que reciben el cuidado adecuado.

5. **El cliente también puede obtener** recomendación según el tipo de planta, historial de cuidado, y conexión con el clima.

6. **Adquiriremos la mayoría de nuestros clientes a través de** redes sociales, ferias verdes, y recomendaciones entre comunidades de jardinería urbana.

7. **Generamos ingresos mediante** planes de suscripción mensual con funcionalidades escalables según el plan.

8. **Nuestra competencia principal en el mercado** apps móviles de recordatorio de riego. 

9. **Superaremos a la competencia gracias a** una solución completa, fácil de usar, con alertas automatizadas y diseño centrado en el usuario. 

10. **Nuestro mayor riesgo es** que los sensores no funcionen correctamente o presenten dificultades al ser instalados por nuestros usuarios finales.

11. **Solucionaremos esto mediante** kits preconfigurados, tutoriales simples y servicio de soporte remoto.

12. **Otro riesgo que debemos considerar es que** si los usuarios no captan frente a las apps gratuitas, podrían abandonar el proyecto o no pagar las suscripciones. <br/><br/>

##### User Assumptions<br/><br/>

1. **¿Quién es el usuario?**

Asumimos que nuestros usuarios son personas entre 25 y 60 años con una estilo de vida urbano, que tienen plantas en sus hogares. Suelen tener ocupaciones que les dificultan prestar atención constante a sus plantas. Muchos de ellos no tienen conocimientos técnicos en jardinería ni en dispositivos IoT, pero se adecuan al utilizar plataformas web simples.

2. **¿Dónde encaja nuestro producto en su vida?**

En la rutina diaria del hogar. BioPafi se convierte en la herramienta útil de asistencia de jardinería sin interrumpir otras actividades. 

3. **¿Qué problemas resuelve nuestro producto?**

BioPafi busca resolver frustraciones como: el olvido en el riego, el exceso de agua, la falta de conocimiento técnico y la frustración por perder plantas sin saber por qué.

4. **¿Cuándo y cómo se usa nuestro producto?**

Asumimos que BioPafi se usa de manera ocasional pero efectiva. El usos principal será cuando los usuarios reciban una alerta sobre una condición que requiere acción (riego, cambio de tierra, exceso de humedad) o también cuando ingresan a la WebApp para consultar el estado de sus plantas. 

5. **¿Qué características son importantes?**

+ Alertas automáticas, claras y personalizadas a cada tipo de planta.
+ Información simple, íconos de estado y gráficos sencillos.
+ Un diseño amigable y natural que no parezca técnico.
+ Posibilidad de registrar múltiples plantas, asignarle nombres y fotos. 

6. **¿Cómo debería lucir y comportarse el producto?**

BioPafi debe ser visualmente atractivo, con colores naturales y una interfaz limpia. Debe transmitir calidez, tranquilidad y confianza, sin ser complejo ni técnico.<br/><br/>

##### Feature Assumptions<br/><br/>

1. **Creemos que** la aplicación debe contar con una interfaz de usuario intuitiva y amigable que permita a los usuarios sin conocimientos técnicos interactuar fácilmente con la plataforma, facilitando el monitoreo de sus plantas y la recepción de recomendaciones sin complicaciones.

2. **Creemos que** el sistema debe proporcionar alertas automáticas y personalizables que notifiquen a los usuarios de manera oportuna sobre condiciones críticas en el entorno de sus plantas, como niveles bajos de humedad o temperaturas extremas, permitiendo así una acción inmediata.

3. **Creemos que** la aplicación debe integrar representaciones gráficas simples y visuales para mostrar los valores históricos de humedad del suelo, temperatura y humedad ambiental, permitiendo a los usuarios observar patrones y tomar decisiones basadas en tendencias.

4. **Creemos que** la aplicación debe contar con una opción de vinculación con servicios externos como APIs de pronóstico del clima, que permitan anticipar condiciones ambientales y ajustar las recomendaciones según la temperatura y humedad externa.

5. **Creemos que** el producto debe ofrecer funcionalidades adicionales según el plan de suscripción, como análisis avanzado del historial, generación de reportes semanales, recomendaciones específicas por especie de planta o integración con asistentes virtuales del hogar.<br/><br/>
 

##### 1.2.2.3. Lean UX Hypothesis Statements  

##### 1.2.2.4. Lean UX Canvas  

### 1.3. Segmentos Objetivo  

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

En esta sección se llevará a cabo un análisis comparativo de tres proyectos que operan dentro del mismo nicho de mercado que nuestra propuesta. El propósito es detectar brechas y oportunidades que nos permitan diferenciarnos, ofreciendo una propuesta de valor única y mejor alineada con necesidades que hoy en día no están siendo atendidas de manera efectiva.

#### 2.1.1. Análisis competitivo  


<table border ="1" ><thead>
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr></thead>
<tbody>
  <tr>
    <td rowspan="2">¿Por qué llevar acabo este
análisis?</td>
    <td colspan="5">Quienes son nuestros principales competidores?</td>
  </tr>
  <tr>
    <td colspan="5">  Gracias al estudio de la competencia dentro del mercado, es posible entender el entorno competitivo en el que se desarrollará nuestro producto. Esto permite obtener una visión clara de como los competidores han implementado funciones y como satisfacen las necesidades de sus usuarios.</td>
  </tr>
  <tr>
    <td rowspan="3">PERFIL</td>
    <td rowspan="2">Overview</td>
    <td> Biokeeper

![logo biokeeper](https://www.upc.edu.pe/static/img/logo_upc_red.png)
</td>
    <td>
    Plant Care Reminder
    
![logo plant care reminder](https://cdn6.aptoide.com/imgs/f/2/a/f2aa9d334e80461cf1803883ce0b7d4c_icon.png?w=128)</td>
    <td>
     VERA
![logo VERA](https://www.upc.edu.pe/static/img/logo_upc_red.png)</td>
    <td>
  PictureThis    
![logo PictureThis](https://www.picturethisai.com/image-handle/website_cmsname/static/name/6e9d6b3268fceedd5926c8fd01430f00/img/icon/prod_logo2.png?x-oss-process=image/format,webp/resize,s_177&v=1.0)</td>
  </tr>
  <tr>
    <td>TODO</td>
    <td>Es una aplicación que se enfoca en la gestión personalizada del cuidado de plantas, permitiendo a los usuarios crear perfiles individuales para cada planta en su colección. Además pueden establecer recordatorios específicos para tareas de cuidado como el riego y la fertilización</td>
    <td></td>
    <td> Aplicacion que puede identificar plantas y dar recomendaciones o consejos de cuidado en base a la identificacion previa.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva
    ¿Que valor ofrece a los clientes?</td>
    <td>TODO</td>
    <td>

- Ofrecen recordatorios para el riegue o abonado de plantas
- Organizacion de plantas a traves de perfiles personalizables  
    </td>
    <td></td>
    <td>

+ Acceso a informacion de cuidado de las plantas identificadas
- Deteccion de enfermedades usando la cámara.
  </td>
  </tr>
  <tr>
    <td rowspan="2">PERFIL DEL MARKETING</td>
    <td>Mercado
Objetivo</td>
    <td></td>
    <td>Principiantes y aficionados a las plantas con la necesidad de recordatorios.</td>
    <td></td>
    <td>Principiantes e interesados por las plantas que busquen empezar a cuidar plantas</td>
  </tr>
  <tr>
    <td>Estrategias de
Marketing</td>
    <td></td>
    <td>Posicionamiento del mercado como la herramienta tecnológica para jardineros organizados</td>
    <td></td>
    <td>Contratar articulos en portales periodisticos para generar discusion sobre la aplicación</td>
  </tr>
  <tr>
    <td rowspan="3">PERFIL DEL PRODUCTO</td>
    <td>Productos &
Servicios</td>
    <td></td>
    <td> 

- Perfiles personalizados para cada planta
- Recordatorios específicos para tareas como el riego o cambio de abono.
- Seguimiento constante del crecimiento
 </td>
    <td></td>
    <td>

- Identificacion de especies de plantas usando la camara
- Reconocimiento de enfermedades en plantas
- Ofrece recomendaciones generales para las plantas identificadas
    </td>
  </tr>
  <tr>
    <td>Precios &
Costos</td>
    <td></td>
    <td>Utiliza el modelo freemium, monetizando mediante funciones avanzadas como el poder crear más de 5 perfiles para plantas.</td>
    <td></td>
    <td>Contiene los planes de suscripcion mensual Gold ($5.49) y suscripciones anuales Premium ($39.99) y Platinum ($66.99)
    </td>
  </tr>
  <tr>
    <td>Canales de
distribución
(web/móvil)</td>
    <td></td>
    <td>Móvil</td>
    <td></td>
    <td>Móvil</td>
  </tr>
  <tr>
    <td rowspan="4">ANÁLISIS SWOT</td>
    <td>Fortalezas</td>
    <td></td>
    <td> 

  - Interfaz amigable
  - Actualizaciones constantes
  - Personalización para cada planta del usuario
</td>
    <td></td>
    <td>
    
- Facil de usar para principiantes
- Interfaz amigable y sencilla
</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td></td>
    <td>

 - Acceso limitado a varias de sus funciones
 - Falta de funciones para la identificación de plantas
 - Catálogo de plantas pobre
</td>
    <td></td>
    <td>
    
- Cierta informacion es incorrecta respecto al cuidado de plantas
- No comunica las recomendaciones o guias de forma clara para los usuarios
  </td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td></td>
    <td>

 + Agregar funcionalidades como la identificación de plantas
 - Expansión a plataformas web</td>
    <td></td>
    <td>
    
+ Agregar un seguimiento de plantas y mejorar las guias con informacion actualizada
    </td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td></td>
    <td>
 
- Alta competencia con aplicaciones más completas
 - Pérdida del mercado ante la preferencia de opciones más automatizadas</td>
    <td></td>
    <td>No alerta al usuario del cobro de las suscripciones, generando asi un descontento para los usuarios</td>
  </tr>
</tbody></table>



#### 2.1.2. Estrategias y tácticas frente a competidores  

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas  

#### 2.2.2. Registro de entrevistas  

#### 2.2.3. Análisis de entrevistas  

### 2.3. Needfinding

#### 2.3.1. User Personas  

#### 2.3.2. User Task Matrix  

#### 2.3.3. User Journey Mapping  

#### 2.3.4. Empathy Mapping  

#### 2.3.5. As-is Scenario Mapping  

### 2.4. Ubiquitous Language  

---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping 

### 3.2. User Stories  

### 3.3. Impact Mapping 

### 3.4. Product Backlog  

---

## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines 

#### 4.1.2. Web Style Guidelines  

### 4.2. Information Architecture

#### 4.2.1. Organization Systems 

#### 4.2.2. Labeling Systems  

#### 4.2.3. SEO Tags and Meta Tags  

#### 4.2.4. Searching Systems  

#### 4.2.5. Navigation Systems  

### 4.3. Landing Page UI Design

#### 4.3.1. Landing Page Wireframe  

#### 4.3.2. Landing Page Mock-up  

### 4.4. Web Applications UX/UI Design

#### 4.4.1. Web Applications Wireframes  

#### 4.4.2. Web Applications Wireflow Diagrams 

#### 4.4.3. Web Applications Mock-ups  

#### 4.4.4. Web Applications User Flow Diagrams  

### 4.5. Web Applications Prototyping  

### 4.6. Domain-Driven Software Architecture

#### 4.6.1. Software Architecture Context Diagram  

#### 4.6.2. Software Architecture Container Diagrams  

#### 4.6.3. Software Architecture Components Diagrams  

### 4.7. Software Object-Oriented Design

#### 4.7.1. Class Diagrams  

#### 4.7.2. Class Dictionary  

### 4.8. Database Design

#### 4.8.1. Database Diagram  

---

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

#### 5.1.1. Software Development Environment Configuration  

#### 5.1.2. Source Code Management  

#### 5.1.3. Source Code Style Guide & Conventions  

#### 5.1.4. Software Deployment Configuration  

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1 

##### 5.2.1.2. Aspect Leaders and Collaborators

##### 5.2.1.3. Sprint Backlog 1 

##### 5.2.1.4. Development Evidence for Sprint Review  

##### 5.2.1.5. Execution Evidence for Sprint Review

##### 5.2.1.6. Services Documentation Evidence for Sprint Review

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

##### 5.2.1.8. Team Collaboration Insights during Sprint  

### 5.3. Validation Interviews

#### 5.3.1. Diseño de Entrevistas  

#### 5.3.2. Registro de Entrevistas  

#### 5.3.3. Evaluaciones según heurísticas  

### 5.4. Video About-the-Product  

---

## Conclusiones

### Conclusiones y recomendaciones  

### Video About-the-Team  

---

## Bibliografía  

---

## Anexos  