# Informe de Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**

**Ingeniería de Software**

**5to Ciclo**

**Código del curso:** 1ASI0729

**Nombre del curso:** Desarrollo de aplicaciones Open Source

**Sección:** 4289

**Nombre del profesor:** BAUTISTA UBILLUS, EFRAIN RICARDO

**Nombre del Startup:** BioPafi

**Nombre del Producto:** PlantSync

### Relación de Integrantes

| **Código** | **Apellidos y Nombres**             |
| ---------- | ----------------------------------- |
| U20231A500 | Palomino Fiestas, Erick Leonardo    |
|            | Gonzales Alvarado, Javier Sebastian |
|            | Palomares Andrade, Sean Farith      |
|            | Rivera Ratachi, Renzo Sebastian     |
|            | Torres Apolinario, Giovany Smith    |

**Abril 2025**

---

## Registro de Versiones del Informe

| **Versión** | **Fecha** | **Descripción de cambios** | **Autor(es)** |
| ----------- | --------- | -------------------------- | ------------- |
| 1.0         |           |                            |               |

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

| **Foto del Integrantes** | **Nombres y Apellidos**            | **Código de estudiante** | **Conocimientos técnicos y habilidades** |
| ------------------------ | ---------------------------------- | ------------------------ | ---------------------------------------- |
| 1                        | Erick Leonardo Palomino Fiestas    | U20231A500               | Conocimientos técnicos y habilidades     |
| 2                        | Javier Sebastian Gonzales Alvarado | Código de estudiante     | Conocimientos técnicos y habilidades     |
| 3                        | Sean Farith Palomares Andrade      | Código de estudiante     | Conocimientos técnicos y habilidades     |
| 4                        | Renzo Sebastian Rivera Ratachi     | Código de estudiante     | Conocimientos técnicos y habilidades     |
| 5                        | Giovany Smith Torres Apolinario    | Código de estudiante     | Conocimientos técnicos y habilidades     |

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

El propósito de BioPafi es ofrecer a los hogares peruanos una solución tecnológica amigable que permita monitorear de manera inteligente el estado de las plantas a través de sensores conectados a una plataforma web. Esta solución está dirigida a personas con plantas en casa, quienes desean cuidarlas pero no siempre cuentan con los conocimientos técnicos, el tiempo o los recursos para hacerlo de forma precisa.

El problema se presenta en el momento en que los usuarios deben tomar decisiones sobre el cuidado de sus plantas, como regarlas, moverlas de lugar o protegerlas del clima sin contar con información confiable y en tiempo real sobre su estado. Esta falta de datos conlleva a un cuidado improvisado, que muchas veces resulta en el deterioro de las plantas por exceso o falta de agua, condiciones ambientales inadecuadas, o incluso enfermedades que no son detectadas a tiempo. Actualmente, muchas personas dependen de la observación visual, el tacto o simples aplicaciones de recordatorios, lo que genera márgenes de error significativos en el mantenimiento de sus plantas.

Hemos identificado que esta incertidumbre en el cuidado de las plantas genera frustración, pérdida de tiempo, y en muchos casos, abandono del hábito de jardinería. Esta problemática se intensifica en ambientes urbanos donde las condiciones de iluminación, temperatura, y humedad varían mucho en espacios pequeños.

A todo esto nos surge la pregunta: ¿Cómo podríamos brindar a las personas una solución inteligente y automatizada que monitoree el estado de sus plantas, brinde alertas de cuidado y recomendaciones personalizadas?

- **Domain:** Jardinería doméstica y tecnología para el hogar.
- **Customer Segments:** Personas con plantas en casa, jardineros urbanos, especialistas en botánica.
- **Pain Points:** Falta de tiempo, desconocimiento sobre el cuidado de plantas, olvidos, riesgo excesivo o insuficiente.
- **Gap:** No hay soluciones accesible y personalizadas que brinden monitoreo y alertas sencillas de entender y recordar
- **Vision/Strategy:** Crear una plataforma que conecte sensores IoT con una WebApp amigable que ayude a cuidar plantas mediante recomendaciones en tiempo real.
- **Initial Segment:** Usuarios domésticos con al menos 3 plantas que busquen automatizar parte del cuidado.

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

- Alertas automáticas, claras y personalizadas a cada tipo de planta.
- Información simple, íconos de estado y gráficos sencillos.
- Un diseño amigable y natural que no parezca técnico.
- Posibilidad de registrar múltiples plantas, asignarle nombres y fotos.

6. **¿Cómo debería lucir y comportarse el producto?**

BioPafi debe ser visualmente atractivo, con colores naturales y una interfaz limpia. Debe transmitir calidez, tranquilidad y confianza, sin ser complejo ni técnico.<br/><br/>

##### Feature Assumptions<br/><br/>

1. **Creemos que** la aplicación debe contar con una interfaz de usuario intuitiva y amigable que permita a los usuarios sin conocimientos técnicos interactuar fácilmente con la plataforma, facilitando el monitoreo de sus plantas y la recepción de recomendaciones sin complicaciones.

2. **Creemos que** el sistema debe proporcionar alertas automáticas y personalizables que notifiquen a los usuarios de manera oportuna sobre condiciones críticas en el entorno de sus plantas, como niveles bajos de humedad o temperaturas extremas, permitiendo así una acción inmediata.

3. **Creemos que** la aplicación debe integrar representaciones gráficas simples y visuales para mostrar los valores históricos de humedad del suelo, temperatura y humedad ambiental, permitiendo a los usuarios observar patrones y tomar decisiones basadas en tendencias.

4. **Creemos que** la aplicación debe contar con una opción de vinculación con servicios externos como APIs de pronóstico del clima, que permitan anticipar condiciones ambientales y ajustar las recomendaciones según la temperatura y humedad externa.

5. **Creemos que** el producto debe ofrecer funcionalidades adicionales según el plan de suscripción, como análisis avanzado del historial, generación de reportes semanales, recomendaciones específicas por especie de planta o integración con asistentes virtuales del hogar.<br/><br/>

##### 1.2.2.3. Lean UX Hypothesis Statements

Hypothesis Statement 01:

**Creemos que** los expertos y principiantes cuidadores de plantas necesitan una plataforma que les permita llevar un control preciso de sus plantas
**Sabremos** que hemos tenido exito
**Cuando** la tasa de adopción de usuarios de la plataforma se encuentre alrededor del 70%

Hypothesis Statement 02:

**Creemos que** emplear alertas, notificaciones y recordatorios ayudarán a los usuarios a tener plantas más saludables
**Sabremos** que esto es cierto
**Cuando** alrededor del 70% de los usuarios con dos o más plantas reporten una mejora en la salud de sus plantas después de 2 semanas de usar la plataforma.

Hypothesis Statement 03:

**Creemos que** la visualización de datos históricos apoyandonos en graficas simples será de ayuda para que los usuarios ajusten sus rutinas de cuidado
**Sabremos** que esto es cierto
**Cuando** al menos el 40% de los usuarios revisen la seccion de historial cada mes

Hypothesis Statement 04:

**Creemos que** la implementación de guías será de ayuda para los principiantes cuidadores de planta
**Sabremos** que esto es cierto
**Cuando** observemos que este segmento obejtivo consulta las guías al menos una vez por semana

##### 1.2.2.4. Lean UX Canvas

![Imagen de Lean UX Canvas](https://i.imgur.com/fWHQw4a.jpeg)

Enlace del [Lean UX Canvas](https://miro.com/app/board/uXjVIDSq_vA=/?share_link_id=642247421109)

### 1.3. Segmentos Objetivo

Según Revista Economía (2020), los peruanos realizaron más de 51 mil búsquedas online relacionadas a áreas verdes de enero a octubre del 2020. De las cuales un 66% eran de mantenimiento y mejora de jardines en el hogar.
El 64% de las personas que realizaron estas búsquedas tenian entre 34 y 50 años.

Ello nos indica que hay segmentos dispuestos a adoptar soluciones tecnológicas que les faciliten el cuidado de sus jardines.

- **Principiantes cuidadores de plantas:**

  Personas interesadas en iniciarse en el cuidado de plantas.

  - Características demográficas

    **Edad:** De 12 a 50 años.

    **Ubicación:** Residentes de zonas urbanas y suburbanas con espacio limitado.

    **Nivel socioeconómico:** Medio, dispuesto a invertir en plantas pero con una tendencia a elegir opciones accesibles.

    **Nivel educativo:** Con conocimientos de tecnología pero desean algo facil de usar.

- **Expertos cuidadores de plantas**

  Personas con experiencia en el cuidado de plantas

  - Características demográficas

    **Edad:** De 18 a 50 años

    **Ubicación:** Residentes de áreas urbanas y suburbanas con mayor disponibilidad de espacios para sus plantas.

    **Nivel socioeconómico:** Medio a alto con acceso a tecnología y con disposición a invertir en herramientas que faciliten el cuidado de plantas.

    **Nivel educativo:** Usuarios con habilidades tecnológicas que se sienten comodos usando herramientas digitales. Además poseen conocimientos y experiencia en el cuidado de plantas.

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
    <td> PlantSync

![logo plantsync](https://i.postimg.cc/vBW1fJFD/Whats-App-Image-2025-04-14-at-5-27-23-PM.jpg)

</td>
    <td>
    Plant Care Reminder
    
![logo plant care reminder](https://cdn6.aptoide.com/imgs/f/2/a/f2aa9d334e80461cf1803883ce0b7d4c_icon.png?w=128)</td>
    <td>
     Blossom
![logo blossom](https://play-lh.googleusercontent.com/rDH_bkyIeGmKXB106DWmXW0xgaZwTOEVETMtBJU4VnhXtAuc35BI_ZYKi7MC5juBIA)</td>
    <td>
  PictureThis    
![logo PictureThis](https://www.picturethisai.com/image-handle/website_cmsname/static/name/6e9d6b3268fceedd5926c8fd01430f00/img/icon/prod_logo2.png?x-oss-process=image/format,webp/resize,s_177&v=1.0)</td>
  </tr>
  <tr>
    <td>PlantSync es una aplicacion que se apoya de la IA
     para identificar plantas y asistir en su cuidado.
     Tambien cuenta con un chatbot para resolver dudas sobre el cuidado de las plantas</td>
    <td>Es una aplicación que se enfoca en la gestión personalizada del cuidado de plantas, permitiendo a los usuarios crear perfiles individuales para cada planta en su colección.</td>
    <td>Blossom es una aplicación de identificacion de plantas y diagnostico basico de enfermedades </td>
    <td> Aplicacion que puede identificar plantas y dar recomendaciones o consejos de cuidado en base a la identificacion previa.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva
    ¿Que valor ofrece a los clientes?</td>
    <td>Uso de inteligencia artificial para ofrecer soporte avanzado y adaptado a las necesidades específicas de cada planta.</td>
    <td>

- Ofrecen recordatorios para el riegue o abonado de plantas
- Organizacion de plantas a traves de perfiles personalizables
    </td>
    <td>


* Gran cobertura de especies de plantas
* Ofrece una seccion de diario para realizar el seguimiento de plantas
    </td>
    <td>

- Acceso a informacion de cuidado de las plantas identificadas
- Deteccion de enfermedades usando la cámara.
  </td>
  </tr>
  <tr>
    <td rowspan="2">PERFIL DEL MARKETING</td>
    <td>Mercado
Objetivo</td>
    <td>Usuarios expertos acostumbrados a la vida urbana que deseen una guía sencilla y eficaz para el cuidado de su planta en su entorno.</td>
    <td>Principiantes y aficionados a las plantas con la necesidad de recordatorios.</td>
    <td>Usuarios urbanos o principiantes al cuidado de las plantas.</td>
    <td>Principiantes e interesados por las plantas que busquen empezar a cuidar plantas</td>
  </tr>
  <tr>
    <td>Estrategias de
Marketing</td>
    <td>

* Anuncios en distintas redes sociales (Instagram, Facebook, etc)
* Articulos en blogs de jardineria o tecnologia innovadora

</td>
    <td>Posicionamiento del mercado como la herramienta tecnológica para jardineros organizados</td>
    <td>

Aparece en diversos blogs y paginas dedicadas a la jardineria.
</td>
<td>Contratar articulos en portales periodisticos para generar discusion sobre la aplicación</td>

  </tr>
  <tr>
    <td rowspan="3">PERFIL DEL PRODUCTO</td>
    <td>Productos &
Servicios</td>
    <td>

- Identificación de plantas mediante fotos
- Recomendaciones basadas mediante Inteligencia Artificial
- Recordatorio de riegos, fertilización, etc.
- Consejos adaptados a las condiciones del ambiente
    </td>
    <td>

* Perfiles personalizados para cada planta.

- Recordatorios específicos para tareas como el riego o cambio de abono.
- Seguimiento constante del crecimiento.
</td>
   <td>


* Recordatorios que se establecen manualmente.
* Identificacion de enfermedades.
* Identifica más de 30,000 plantas
de interior o exterior.
</td>
    <td>

- Identificacion de especies de plantas usando la camara.
- Reconocimiento de enfermedades en plantas.
- Ofrece recomendaciones generales para las plantas identificadas.
</td>
  </tr>
  <tr>
    <td>Precios &
Costos</td>
    <td>Ofrecemos los planes Basico ($2.99/mes), Premium ($10.99/mes) y PRO ($16.99/mes)</td>
    <td>Utiliza el modelo freemium, monetizando mediante funciones avanzadas como el poder crear más de 5 perfiles para plantas.</td>
    <td> 
    Cuenta con una version gratuita con funcionalidades limitadas. 
    La versión premium cuesta ($4,99/mes o $29.99/año). 
    </td>
    <td>Contiene los planes de suscripcion mensual Gold ($5.49) y suscripciones anuales Premium ($39.99) y Platinum ($66.99).
    </td>
  </tr>
  <tr>
    <td>Canales de
distribución
(web/móvil)</td>
    <td>Móvil y Web</td>
    <td>Móvil</td>
    <td>Móvil</td>
    <td>Móvil</td>
  </tr>
  <tr>
    <td rowspan="4">ANÁLISIS SWOT</td>
    <td>Fortalezas</td>
    <td>

- Uso de la inteligencia artificial para el cuidado de cada tipo de planta
- Combinar el cuidado de plantas con la educación e importancia de estas.
- Interfaz fácil y sencilla de usar
  </td>
      <td>

  - Interfaz amigable
  - Actualizaciones constantes
  - Personalización para cada planta del usuario
  </td>
      <td>

- Interfaz amigable y sencilla de usar
- Tecnología de Inteligencia Artificial
- Amplia base de datos de plantas
</td>
    <td>

- Facil de usar para principiantes
- Interfaz amigable y sencilla
</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>

- Dependencia de las suscripciones para monetizar
- Requerimiento de innovación constante para mantener el valor agregado característico</td>
    <td>

* Acceso limitado a varias de sus funciones

- Falta de funciones para la identificación de plantas
- Catálogo de plantas pobre
</td>
    <td>

* Dependencia de las suscripciones para la monetización
* Falta de valor diferencial destacado
</td>
    <td>

- Cierta informacion es incorrecta respecto al cuidado de plantas
- No comunica las recomendaciones o guias de forma clara para los usuarios
  </td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>

* Aprovechar tecnologias como la inteligencia artificial para añadir funcionalidades

- Colaboración con productos de tecnología para las plantas</td>
    <td>

* Agregar funcionalidades como la identificación de plantas

- Expansión a plataformas web</td>
   <td>

* Expansión a plataformas web
* Conexión con otros dispositivos inteligentes del hogar
</td>
    <td>

* Agregar un seguimiento de plantas y mejorar las guias con informacion actualizada
    </td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>

- Limitantes tecnológicas podrían afectar la experiencia del usuario.
- Amplia competencia en el mercado

</td>
    <td>
 
+ Alta competencia con aplicaciones más completas
- Pérdida del mercado ante la preferencia de opciones más automatizadas</td>
    <td>
+ Saturación en el mercado de aplicaciones para la jardinería</td>
    <td>
    
- Descontento de los usuarios por monetizacion predatoria
    </td>
  </tr>
</tbody></table>

#### 2.1.2. Estrategias y tácticas frente a competidores

De acuerdo al análisis competitivo realizado previamente, se logró determinar con precisión las principales fortalezas, oportunidades, debilidades y amenazas de los competidores. A continuación, se presentarán una serie de estrategias y acciones que se tomaran para destacar la aplicación en el mercado objetivo.

## Afrontando las fortalezas de nuestros competidores:

- Interfaz sencilla y amigable de usar.
- Base de datos de plantas amplia.
- Uso de tecnologias novedosas como la inteligencia artificial.

## Comprendemos que nuestras fortalezas son:

- Uso de la inteligencia artificial para el cuidado de cada tipo de planta.
- Combinar el cuidado de plantas con la educación e importancia de estas.
- Diseño simple y amigable.

Entonces, podemos aplicar las siguientes estrategias y tácticas:

## Estrategias:

- Generar una experiencia amigable al usuario novato.
- Asegurarnos de contar con la informacion las plantas que los usuarios expertos podrian desear.

## Tácticas:

- Incluir una base de datos amplia que contenga la mayor cantidad de plantas posible.

- Utilizar entrevistas para planificar el movimiento de nuestros usuarios a traves de la app.


#### 2.1.2. Estrategias y tácticas frente a competidores  
=======
## Afrontando las debilidades de nuestros competidores:

- Acceso limitado a varias de sus funciones en algunos modelos de pago.
- Falta de funciones para la identificación de plantas.
- Falta de claridad al comunicar guias o descripciones a los usuarios.

## Comprendemos que nuestras debilidades son:

- Dependencia de las suscripciones para monetizar.
- Requerimiento de innovación constante para mantener el valor agregado característico.

Entonces, podemos aplicar las siguientes estrategias y tácticas:

## Estrategias:

- Incentivar al usuario a pagar por una suscripción.

- Comunicar al usuario de forma clara y en un idioma entendible
  las recomendaciones o guias que puede aplicar en sus plantas.

## Tácticas:

- Ofrecer funcionalidades clave en las suscrpiciones mas baratas que se complementan con las que se encuentran en suscripciones mas costosas.
- Enviar mensajes claros y concisos al usuario acerca del estado de sus plantas.

## Afrontando las oportunidades de nuestros competidores:

- Agregar funcionalidades como la identificación de plantas.
- Expansión a plataformas web.
- Conexión con otros dispositivos inteligentes del hogar.
- Agregar un seguimiento de plantas y mejorar las guias con informacion actualizada.

## Comprendemos que nuestras oportunidades son:

- Aprovechar tecnologias como la inteligencia artificial para añadir funcionalidades.
- Colaboración con productos de tecnología para las plantas.

Entonces, podemos aplicar las siguientes estrategias y tácticas:

## Estrategias:

- Innovar en la experiencia del usuario mediante la integración de inteligencia artificial para ofrecer cuidados personalizados de plantas.

## Tácticas:

- Desarrollar una funcionalidad de identificación automática de plantas por subida de archivo.

## Afrontando las amenazas de nuestros competidores:

- Alta competencia con aplicaciones más completas.
- Pérdida del mercado ante la preferencia de opciones más automatizadas.
- Saturación en el mercado de aplicaciones para la jardinería.
- Descontento de los usuarios por monetizacion predatoria.

## Comprendemos que nuestras amenazas son:

- Limitantes tecnológicas podrían afectar la experiencia del usuario.
- Amplia competencia en el mercado.

Entonces, podemos aplicar las siguientes estrategias y tácticas:

## Estrategias:

- Distinguirnos de las aplicaciones que suelen ser tediosas en su uso.

- Mantener la confianza que tiene el usuario con nosotros.

## Tácticas:

- Implementar recordatorios automaticos para mejorar la experiencia del usuario.
- Evitar prácticas de monetización invasivas y comunicar de forma transparente cómo se usan los datos del usuario.


### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas


#### 2.2.2. Registro de entrevistas


**Entrevista para personas con experiencia como hobbyistas (años cuidando plantas en casa):**

**1.-** ¿Cuántos años llevas cuidando plantas en casa y cómo comenzó tu interés?

**2.-** ¿Cuáles son los mayores retos que enfrentas cuando cuidas tus plantas?

**3.-** ¿Tienes un tipo de planta o rutina favorita en tu cuidado diario?

**4.-** ¿Sueles registrar la información del cuidado de tus plantas (cuándo regaste, fertilizaste, etc.)? ¿Cómo lo haces actualmente?

**5.-** ¿Conoces o has usado aplicaciones o blogs especializados para ayudarte con el cuidado?

**6.-** ¿Qué tan interesante te parecería una función que analice tu clima local y te sugiera cuidados específicos?

**7.-** ¿Qué opinas de una función de escaneo de plantas por foto para detectar identificar la especie?

**8.-** ¿Qué opinas sobre la idea de usar una aplicación que te ayude a registrar y monitorear el estado de tus plantas mediante predicciones a través de formularios visuales (por ejemplo, seleccionas la opciones "hojas verdes", "tierra húmeda" y la aplicación te ayudara durante ese momento según una predicción, cuando tienes que regarla o fertilizarla)?

**9.-** ¿Hay alguna función avanzada que te encantaría tener en una app para potenciar tu experiencia como cuidador de plantas?

**10.-** ¿Estarías dispuesto/a  pagar por una suscripción que te ofrezca mas ayudas para el cuidado de tus plantas? (podría cambiar)

**Entrevista para personas con poca experiencia en el cuidado de plantas:**

**1.-** ¿Alguna vez has tenido una planta en casa? Si es así, ¿cómo fue tu experiencia?

**2.-** ¿Cuáles son los mayores retos o problemas que enfrentas actualmente al cuidar tus plantas?

**3.-** ¿Te resulta difícil saber cuánta agua, luz o cuidados necesita una planta? ¿Por qué?

**4.-** ¿Usas actualmente alguna app, blog o comunidad online para ayudarte con el cuidado? ¿Qué te gusta y qué no de esas herramientas?

**5.-** ¿Te interesaría usar una app que te dé recordatorios de riego y consejos simples para tus plantas según su tipo? ¿Por qué sí o por qué no?

**6.-** ¿Te interesaría una función que analice tu clima local y te dé recomendaciones específicas para cada planta? ¿Por qué sí o por qué no?

**7.-** ¿Qué opinas de una función que permita identificar una planta tomando una foto con el celular? ¿La usarías?

**8.-** ¿Cómo te sentirías con una función que te permita registrar el estado de la planta mediante formularios visuales (como elegir “hojas secas” o “tierra muy húmeda”) y que, en base a eso, te sugiera acciones?

**9.-** ¿Hay alguna función avanzada que te encantaría tener en una app para ayudarte como cuidador de plantas? (por ejemplo: predicción de enfermedades, guía de trasplante, alertas inteligentes, etc.)

**10.-** ¿Estarías dispuesto/a a pagar por funciones premium que mejoren tu experiencia? ¿Qué tendría que ofrecer una app para que valga la pena pagarla?

#### 2.2.2. Registro de entrevistas  

*Entrevista para personas con experiencia como hobbyistas (años cuidando plantas en casa):*
---
<br>

<table align="center">
  <tr>
    <th colspan="2" style="text-align:center">Entrevista 1</th>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Pedro vargas</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>23</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>San Miguel</td>
  </tr>
  <tr>
    <td><strong>Timing</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td><strong>URL</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:justify">
      Resumen:<br>
      Pedro, de 23 años, cuida plantas desde niño gracias a la influencia de una tía. Su rutina se basa en la observación diaria, sin registros formales ni el uso de apps. Sus principales retos son el control del suelo y las plagas. Aunque no utiliza herramientas digitales específicas, suele informarse por YouTube o internet, mostrando un manejo básico de tecnología. Le interesa una aplicación que le permita registrar cuándo fertiliza y que, en base a la edad y estado de la planta, le indique cuándo volver a hacerlo. Desea un calendario que le ayude a planificar cuidados y recibir recomendaciones personalizadas. También valora que la app considere si las plantas están en interiores o exteriores. Aunque prefiere opciones gratuitas, evaluaría pagar por funciones útiles. 
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="ruta/al/screenshot.png" alt="Screenshot Entrevista" width="1000">
    </td>
  </tr>
</table>


<br>

<table align="center">
  <tr>
    <th colspan="2" style="text-align:center">Entrevista 1</th>
  </tr>
  <tr>
    <td><strong>Entrevistada</strong></td>
    <td>Leonor Gonzales</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>60</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>San Miguel</td>
  </tr>
  <tr>
    <td><strong>Timing</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td><strong>URL</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:justify">
      Resumen:<br>
      Leonor comenzó a cuidar plantas hace seis años cuando empezó a ayudar a su madre con el jardín, y desde entonces ha convertido esta actividad en parte de su rutina. Uno de los mayores desafíos que enfrenta es entender los cuidados específicos de cada tipo de planta, ya que varían mucho en cuanto a exposición solar, cantidad de agua y tipo de suelo. Comenta que al tener muchas plantas, recordar estos detalles se vuelve difícil. Actualmente no utiliza ninguna aplicación especializada. Se apoya principalmente en su memoria, en consejos familiares y en búsquedas en Google, aunque señala que la información suele estar dispersa y poco personalizada. Mencionó que nunca ha encontrado una herramienta digital que le permita organizar, registrar y optimizar el cuidado de sus plantas de manera práctica y confiable. Leonor se mostró muy interesada en funcionalidades como recordatorios personalizados, identificación de especies mediante fotografía y monitoreo del estado de cada planta. Considera que una herramienta con esas características facilitaría su rutina y evitaría errores comunes. Finalmente, afirmó que estaría dispuesta a pagar por una suscripción si la aplicación realmente le ayuda a mantener sus plantas sanas y organizadas.
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="images/entrevista-leonor-segmento2.png" alt="Screenshot Entrevista 2" width="1000">
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <th colspan="2" style="text-align:center">Entrevista 1</th>
  </tr>
  <tr>
    <td><strong>Entrevistada</strong></td>
    <td>Guadalupe Alvarado</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>52</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>San Miguel</td>
  </tr>
  <tr>
    <td><strong>Timing</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td><strong>URL</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:justify">
      Resumen:<br>
      Guadalupe comenzó a cuidar activamente sus plantas durante la pandemia, aunque desde siempre ha sentido afinidad por ellas. Desde entonces ha desarrollado una rutina de jardinería en casa, pero comenta que su principal dificultad es no saber con precisión cada cuánto regar o cuánta agua usar, especialmente porque cada planta requiere cuidados diferentes. A esto se suma que tiene una vida laboral muy agitada, lo cual le impide dedicar tiempo suficiente a investigar temas como tipos de fertilizantes, control de plagas o condiciones de luz y sombra. Actualmente, no lleva un registro del cuidado de sus plantas, ni utiliza herramientas específicas. Suele obtener la información a través de videos en YouTube o reels en Instagram, que si bien le parecen útiles, no siempre son confiables o aplicables a sus casos. Por eso, considera que una app que centralice estos datos y brinde recomendaciones personalizadas sería una gran ayuda, sobre todo por el ahorro de tiempo que implicaría en medio de sus responsabilidades laborales y domésticas. Entre las funcionalidades que más le interesaron destacan el análisis del clima local con recomendaciones específicas, la identificación de plantas mediante imágenes y el registro del estado de cada planta. Guadalupe indicó que estaría dispuesta a pagar por una suscripción siempre que la aplicación realmente le ahorre tiempo, le brinde valor y simplifique el cuidado de sus plantas.
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="images/entrevista-guadalupe-segmento2.png" alt="Screenshot Entrevista 3" width="1000">
    </td>
  </tr>
</table>

<br>

*Entrevista para personas con poca experiencia en el cuidado de plantas:*
---
<br>

<table align="center">
  <tr>
    <th colspan="2" style="text-align:center">Entrevista 1</th>
  </tr>
  <tr>
    <td><strong>Entrevistada</strong></td>
    <td>...o</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td><strong>Timing</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td><strong>URL</strong></td>
    <td>...</td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:justify">
      Resumen:<br>
      ....
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="images/ejemplo.png" alt="UPC logo" width="1000">
    </td>
  </tr>
</table>

#### 2.2.3. Análisis de entrevistas  

*Analisis de entrevista para personas con experiencia como hobbyistas (años cuidando plantas en casa):*
---

*Analisis de entrevista para personas con poca experiencia en el cuidado de plantas:*
---




### 2.3. Needfinding

#### 2.3.1. User Personas

#### 2.3.2. User Task Matrix

#### 2.3.3. User Journey Mapping

#### 2.3.4. Empathy Mapping

#### 2.3.5. As-is Scenario Mapping

Segmento 1: Mauricio Alcantara
![AS IS SEGMENTO 1](https://imgur.com/6FZnUb2.jpg)

Segmento 2: Roxana Madero
![AS IS SEGMENTO 2](https://imgur.com/c7CyxiD.jpg)

### 2.4. Ubiquitous Language

---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping


### 3.2. User Stories

#### Epics

<table border ="1" >
  <tbody>
    <tr>
      <td>Epic ID</td>
      <td>Título</td>
      <td>Descripción</td>
    </tr>
    <tr>
      <td>01</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

---

#### User Stories

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>01</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>02</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>03</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>04</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>05</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>06</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>07</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>08</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>09</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>10</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>11</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>12</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>13</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>14</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>15</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>16</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>17</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>18</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>19</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>20</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>21</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>22</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>23</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>24</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

<table border ="1" >
  <tbody>
    <tr>
      <td>User Story ID</td>
      <td>25</td>
      <td>Epic ID</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Title</td>
      <td colspan="3">titulo</td>
    </tr>
    <tr>
      <td>Description</td>
      <td colspan="3">descripcion</td>
    </tr>
    <tr>
      <td>Aceptance Criteria</td>
      <td colspan="3">criterios</td>
    </tr>
  </tbody>
</table>

### 3.3. Impact Mapping

=======

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

Revista Economía. (2020). Incremento del interés de los peruanos por el cuidado de las áreas verdes. https://www.revistaeconomia.com/incremento-del-interes-de-los-peruanos-por-el-cuidado-de-las-areas-verdes/

## Anexos
