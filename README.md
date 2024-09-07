<div align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="logo"  width="20%"/>

**Universidad Peruana de Ciencias Aplicadas** <br>
**Ingeniería de Software** <br>
**Ciclo 2024-2** <br>

<h4>Arquitecturas de Software Emergentes</h4>

**Sección:** SW82
**Profesor:** Royer Edelwer Rojas Malasquez

<h3>INFORME DEL TRABAJO FINAL</h3>

**Startup:** SocialTech

**Producto:**

**Integrantes:**

Achamizo Huamani, Jean Carlos <br>
Aliaga Trevejo, Lucía Guadalupe <br>
Raymundo Guevara, Rodrigo Alejandro <br>
Siancas Reategui, Luis Alberto <br>
Trujillo Lopez, Luis Alberto <br>

**Setiembre, 2024**

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| ------- | ----- | ----- | ------------------------------ |
|   1.0     |   06/09/2024   |  Achamizo Huamani Jean Carlos,  Aliaga Trevejo Lucía Guadalupe, Raymundo Guevara Rodrigo Alejandro, Siancas Reategui Luis Alberto, Trujillo Lopez Luis Alberto  |   Se añadieron los elementos correspondientes al entregable de la TB1 (capítulos 1 al 4)|

---

# Project Report Collaboration Insights

URL del repositorio: https://github.com/ASE-SocialTech/report

---


# Contenido

## Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
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
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Product Backlog](#product-backlog)
  - [Tabla de Product Backlog](#tabla-de-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality attribute](#4122-quality-attribute)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  


---

# Student Outcome

| Criterio específico                                              | Acciones realizadas                                                                 | Conclusiones |
|------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Durante la presentación del perfil de la startup SocialTech en la sección 1.1, me enfoqué en explicar la misión y visión de nuestra startup. Al describir el **Lean UX Canvas** (1.2.2.4), destaqué cómo nuestras hipótesis y suposiciones estaban alineadas con los problemas detectados en las entrevistas realizadas. Adapté mi discurso para diferentes audiencias, asegurándome de que tanto los stakeholders técnicos como los no técnicos comprendieran nuestro enfoque. <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> En las reuniones de presentación de los resultados del análisis competitivo (2.1.1), me encargué de comunicar cómo las **estrategias y tácticas frente a los competidores** (2.1.2) influenciaban el desarrollo de la solución. Expliqué con claridad los desafíos y oportunidades, asegurándome de que la audiencia comprendiera las ventajas competitivas de SocialTech. <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Al presentar los resultados de las **entrevistas** (2.2), me aseguré de que los distintos perfiles de los usuarios potenciales, basados en el **Needfinding** (2.3), fueran comprendidos tanto por el equipo técnico como por los involucrados en la toma de decisiones. Utilicé ejemplos de las entrevistas y los **User Personas** (2.3.1) para conectar con el público. <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> Mi presentación se centró en el mapeo de escenarios, donde describí tanto los **As-is** como los **To-be Scenarios** (2.3.4 y 3.1). Al comunicar las mejoras proyectadas para el sistema, ajusté mi lenguaje para que tanto los desarrolladores como los líderes de proyecto pudieran entender claramente los beneficios del diseño propuesto. <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Durante las presentaciones sobre el **Impact Mapping** y la **Product Backlog** (3.3 y 3.4), destaqué cómo los **User Stories** (3.2) guiaban nuestro proceso de desarrollo. Adapté mi lenguaje para que el equipo técnico pudiera entender las historias de usuario y cómo estas reflejaban las necesidades identificadas en las entrevistas y el **Empathy Mapping** (2.3.3). <br><br>|  *TB1* <br> La comunicación oral fue efectiva en la transmisión de conceptos complejos y estratégicos a audiencias diversas, adaptando el lenguaje y las explicaciones según el nivel de conocimiento técnico de cada público. Esto facilitó la toma de decisiones y la alineación de los objetivos del proyecto entre las partes interesadas. |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Al redactar la sección sobre el **Lean UX Canvas** (1.2.2.4) y el análisis de la problemática (1.2.1), me aseguré de utilizar un lenguaje accesible para describir los **Problem Statements** (1.2.2.1) y su relación con las necesidades detectadas en la fase de entrevistas. Mi objetivo fue que cualquier lector, independiente de su perfil, pudiera entender las hipótesis clave del proyecto. <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> En mi contribución escrita al **Análisis Competitivo** (2.1.1), detallé las fortalezas y debilidades de los competidores y cómo SocialTech podía diferenciarse. Me aseguré de que el informe explicara claramente las **estrategias** propuestas (2.1.2) para superar a nuestros competidores en términos de innovación tecnológica y accesibilidad. <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Mi redacción sobre las **entrevistas** (2.2) fue clave para establecer una narrativa clara que conectara las necesidades del usuario con las soluciones propuestas. En particular, en la sección de **User Personas** (2.3.1), enfoqué mis escritos en describir los comportamientos y necesidades de cada segmento de usuarios de manera comprensible para el equipo de diseño y desarrollo. <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> En la sección de **To-Be Scenario Mapping** (3.1), me aseguré de que las propuestas de escenarios futuros estuvieran claramente explicadas y justificadas en relación con los datos obtenidos del **Empathy Mapping** (2.3.3). Además, describí las mejoras proyectadas para el sistema en términos de impacto en la experiencia del usuario. <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Al redactar la **Product Backlog** (3.4), me centré en asegurar que las **User Stories** (3.2) fueran claras y accesibles, de modo que el equipo de desarrollo pudiera priorizarlas fácilmente. También me aseguré de explicar cómo estas historias de usuario estaban alineadas con los resultados del **Impact Mapping** (3.3) y los requerimientos del cliente. <br><br>|   *TB1* <br> La comunicación escrita permitió detallar de forma clara los aspectos técnicos y estratégicos del proyecto, facilitando la comprensión y el alineamiento de las expectativas entre las partes interesadas. Se utilizó un lenguaje preciso y accesible que permitió a los equipos técnicos y no técnicos trabajar en conjunto de manera efectiva. |


---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

SocialTech es un startup creado por estudiantes de la UPC, dedicada al desarrollo de soluciones innovadoras en el campo de la visión artificial. Nuestro equipo utiliza Python y otras tecnologías avanzadas para crear herramientas que transforman la manera en que se analizan y procesan las imágenes. En SocialTech, estamos comprometidos con la innovación y la accesibilidad, aplicando nuestros conocimientos y habilidades para ofrecer soluciones efectivas y escalables que aborden desafíos visuales complejos.

### 1.1.2. Perfiles de integrantes del equipo


<table>
    <tr>
        <td>Perfil</td>
        <td>Foto</td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Achamizo Huamani, Jean Carlos<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Como estudiante de Ingeniería de Software en la Universidad UPC, mi entusiasmo por el aprendizaje constante me impulsa a buscar siempre nuevas maneras de perfeccionar mis habilidades académicas y aplicarlas en situaciones prácticas, también poseo aptitudes en comunicación asertiva y escucha activa. Reconozco la importancia de una comunicación clara y efectiva en cualquier proyecto de software, y cuento con la capacidad de escuchar de manera atenta para comprender las necesidades y expectativas de los clientes y colegas de equipo.  
        <td><img src="./assets/JeanFoto.jpg" alt="Jean Achamizo" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Aliaga Trevejo, Lucía Guadalupe <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy una estudiante de Ingeniería de Software, actualmente interesada en el desarrollo web front y back end. Me gusta crear interfaces intuitivas y llamativas para mejorar la experiencia de usuario. Me considero una persona responsable y centrada. Mis habilidades blandas incluyen comunicación efectiva, trabajo en equipo, liderazgo y adaptabilidad. Aspiro a contribuir de manera significativa en proyectos innovadores para seguir expandiendo mis conocimientos técnicos y capacidades. 
        <td><img src="./assets/Lucia-Aliaga.jpg" alt="Lucía Aliaga"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Raymundo Guevara, Rodrigo Alejandro <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy estudiante de la carrera de Ingeniería de Software y un apasionado de la tecnología. Me gusta descubrir nuevas formas de solucionar problemas con diversos frameworks y algoritmos. Me considero una persona responsable y empática. Me gusta mucho trabajar en equipo y ayudar a mis compañeros 
        <td><img src="./assets/RodrigoFoto.jpg" alt="Rodrigo Raymundo"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Siancas Reategui, Luis Alberto<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Descripción 
        <td><img src="" alt="Luis Siancas" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Trujillo Lopez, Luis Alberto<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Descripción 
        <td><img src="" alt="Luis Trujillo" width="600"></td>
    </tr>
   <table>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

La ausencia de Equipos de Protección Personal (EPP) adecuados incrementa significativamente la probabilidad de accidentes en el lugar de trabajo, lo que puede llevar a lesiones graves e incluso a la muerte. Los trabajadores que no utilizan cascos, guantes o botas de seguridad están más expuestos a caídas, cortes, quemaduras y otros peligros asociados con el trabajo en construcción. En muchas obras de construcción en Perú, especialmente en las pequeñas o informales, no existe una cultura sólida de seguridad. Los trabajadores a menudo no reciben capacitación adecuada sobre el uso de EPPs, y las empresas no siempre implementan sistemas efectivos para garantizar que se utilicen correctamente.

**What (Qué)** <br>
Actualmente existen algunas normativas y regulaciones que exigen el uso de EPPs, pero en la práctica no siempre se cumplen. Existen soluciones tradicionales para la gestión de la seguridad laboral, como auditorías manuales y capacitaciones, pero no están siendo suficientemente efectivas para garantizar el uso correcto y constante de los EPPs en los lugares de trabajo. Nuestra propuesta aborda este problema mediante el uso de tecnología de visión artificial para detectar en tiempo real si los trabajadores están utilizando correctamente los EPPs.

**When (Cuándo)** <br>
La problemática surge principalmente en el día a día de las actividades laborales en los sitios de construcción, cuando los trabajadores omiten o usan incorrectamente los EPPs. En muchos casos, los supervisores no pueden monitorear continuamente a todos los trabajadores debido a la carga de trabajo o a la cantidad de empleados. Esto pone en riesgo la seguridad de los trabajadores y expone a las empresas a sanciones legales y multas.

**Where (Dónde)** <br>
Nuestra solución se implementará inicialmente en sitios de construcción de Lima, Perú, tanto en proyectos de gran envergadura como en pequeñas obras, donde la falta de control y capacitación en el uso de EPPs es más evidente. Posteriormente, planeamos expandir nuestra solución a nivel nacional y, a largo plazo, a nivel internacional en regiones con problemáticas similares.

**Who (Quién)** <br>
Nuestra plataforma está dirigida a empresas del sector de la construcción y otros sectores industriales que necesiten asegurar el cumplimiento de las normativas de seguridad laboral. Los usuarios principales incluyen supervisores de obra, encargados de seguridad y salud ocupacional, así como trabajadores que deseen mejorar la seguridad en su entorno laboral.

**Why (Por qué)** <br>
Planteamos esta solución porque queremos reducir el número de accidentes laborales relacionados con la falta de uso de EPPs y mejorar la cultura de seguridad en las empresas. El uso adecuado de los EPPs no solo protege la vida de los trabajadores, sino que también mejora la productividad y reduce los costos asociados a accidentes y sanciones por incumplimiento de normativas de seguridad.

**How (Cómo)** <br>
Utilizaremos tecnología de visión artificial integrada a cámaras de vigilancia ya instaladas en los sitios de construcción, o cámaras especializadas si es necesario, para detectar en tiempo real si los trabajadores están usando correctamente los EPPs. Los responsables de seguridad recibirán alertas automáticas cuando se detecten infracciones, permitiendo una acción inmediata. Además, se generarán informes detallados para facilitar la gestión y cumplimiento de las normativas.

**How much (Cuánto)** <br>
En el Perú, aunque existen algunas soluciones para la gestión de la seguridad laboral, ninguna ofrece la capacidad de detección en tiempo real del uso de EPPs mediante visión artificial. Nuestra solución busca cerrar esta brecha tecnológica, contribuyendo a una mejora significativa en la seguridad laboral y posicionando a Perú a la vanguardia de la innovación en seguridad industrial.

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**PS1:** Los trabajadores en los diversos entornos industriales o de fabricación enfrentan el riesgo constante de accidentes debido al uso inadecuado o la falta de control sobre sus Equipos de Protección Personal (EPP). Necesitan un sistema que ayude a gestionar el uso correcto de los EPP para evitar posibles accidentes. ¿Cómo podemos desarrollar un sistema de monitoreo que garantice el uso adecuado de los EPP en tiempo real, para prevenir riesgos y asegurar el cumplimiento de las normativas de seguridad?

**PS2:** Los supervisores de seguridad carecen de herramientas efectivas para controlar si los trabajadores están utilizando correctamente sus EPP durante las operaciones. Es por ello que necesitan una herramienta que les permita monitorear de forma automática el cumplimiento de las EPP en entornos laborales. ¿Cómo podemos crear una solución que permita monitorear el estado y uso de los EPP de manera eficiente, reduciendo así los riesgos de accidentes laborales?

**PS3:** Existe una necesidad por un sistema que integre la supervisión del uso de EPP y genere alertas en caso de incumplimientos, lo que mejora la prevención de accidentes laborales. Es gracias a ello que se requiere una solución capaz de satisfacer las necesidades de los supervisores para evitar el accidente de los trabajadores. ¿Cómo podemos ofrecerles una herramienta que simplifique este proceso y asegure una mayor seguridad en el lugar de trabajo?

#### 1.2.2.2. Lean UX Assumptions

**Business outcomes**

- Incrementar el cumplimiento de las normativas de seguridad en un 20% en las empresas que implementen el sistema.
- Reducir los incidentes relacionados con el uso incorrecto de EPP en un 15% dentro de los primeros 6 meses de implementación.
- Mejorar la retención de clientes gracias a la integración de nuevas funcionalidades como la generación de reportes automáticos sobre el uso de EPP.


**User**

- Los usuarios son supervisores de seguridad que desean una solución que les permita controlar el uso de EPP en tiempo real de manera automática, sin depender de verificaciones manuales constantes.
- Los trabajadores aceptarán más fácilmente el monitoreo de EPP si el sistema es fácil de usar y no interfiere con sus actividades laborales en cualquier periodo regular.


**User & Customers**

¿Quién es el usuario?
- Los usuarios son los trabajadores que utilizan Equipos de Protección Personal (EPP) en entornos laborales con un grado de riesgo, como fábricas, manufacturas, plantas de construcción, minería, y otros sectores industriales.
- Los usuarios pueden incluir supervisores de seguridad de cualquier entorno laboral con un grado de riesgo como las mencionadas previamente

¿Dónde encajan nuestros productos en sus trabajos o vidas?
- El sistema de monitoreo de EPP se integra en el día a día de los supervisores de seguridad, permitiéndoles monitorear en tiempo real si los trabajadores cumplen con los requisitos de seguridad. Los trabajadores lo usan para asegurar que están siguiendo las normativas y evitar posibles sanciones o accidentes.
- La herramienta se convierte en una parte esencial del proceso de prevención de riesgos en las empresas, ayudando a cumplir con las normativas de seguridad ocupacional y a reducir los incidentes laborales.

¿Qué problema resuelve nuestro producto?
- El sistema se utiliza en tiempo real durante las operaciones laborales en los entornos de alto riesgo, donde los supervisores de seguridad monitorean de forma remota el estado de los EPP.
- Los trabajadores lo usan durante toda su jornada laboral, ya que el sistema verifica automáticamente si están utilizando los EPP correctos, generando alertas o notificaciones si detecta fallos o incumplimientos.

¿Qué características son importantes?
- Monitoreo en tiempo real del uso de los EPP por parte de los trabajadores.
- Alertas instantáneas a supervisores en caso de que los trabajadores no estén usando los EPP adecuados.
- Generación automática de reportes de cumplimiento para auditorías de seguridad.

¿Cómo debería verse y comportarse nuestro producto?
- El sistema debe tener una interfaz intuitiva y fácil de usar para supervisores, con paneles de control que muestren el estado del EPP de todos los trabajadores en tiempo real.
- El diseño debe ser visualmente claro, con códigos de colores y alertas para identificar rápidamente cualquier incumplimiento. Además, debe ser accesible desde múltiples dispositivos, incluyendo móviles y tabletas, para facilitar el monitoreo en campo.


**Features**
- El sistema debe permitir a los supervisores observar en tiempo real el estado del EPP de cada trabajador, verificando si están usando el equipo de protección requerido mientras están en zonas de riesgo.
- Enviar notificaciones instantáneas a los supervisores si el sistema detecta que un trabajador no está usando el EPP o si hay fallas en el equipo, como cascos o guantes mal ajustados, o detectores de gases sin activación.
- Generar reportes automáticos sobre el cumplimiento del uso de EPP para auditorías internas o externas. Estos informes deben ser personalizables y mostrar estadísticas clave como porcentajes de cumplimiento, incidentes y tiempos de respuesta.
- El sistema debe ser accesible desde dispositivos móviles, tabletas, y estaciones de trabajo, para permitir a los supervisores realizar el monitoreo y recibir alertas desde cualquier lugar, dentro o fuera del sitio de trabajo.
- Funcionalidad para detectar automáticamente cuando un trabajador ingresa a una zona de riesgo y verificar si está utilizando el EPP adecuado, generando una alerta si el sistema detecta un incumplimiento.

#### 1.2.2.3. Lean UX Hypothesis Statements

**H1: Monitoreo en Tiempo Real**

Creemos que: Si implementamos un sistema de monitoreo en tiempo real para el uso de EPP, entonces los supervisores podrán detectar y corregir incumplimientos más rápidamente.

Sabremos que habremos tenido éxito, cuando la tasa de incidentes relacionados con el uso incorrecto de EPP se reduzca en un 15% y la satisfacción de los supervisores con la rapidez y precisión del sistema supere el 80%.

**H2: Notificaciones Instantáneas**

Creemos que: Si el sistema envía notificaciones instantáneas a los supervisores cuando detecta un incumplimiento en el uso de EPP, entonces los supervisores podrán tomar medidas correctivas de manera más eficiente.

Sabremos que habremos tenido éxito, cuando el tiempo de respuesta a las notificaciones sea menor a 5 segundos y al menos el 85% de las alertas resulten en una acción correctiva efectiva.

**H3: Reportes Automáticos**

Creemos que: Si el sistema genera reportes automáticos sobre el uso de EPP, entonces los supervisores podrán realizar auditorías más precisas y tomar decisiones basadas en datos relevantes.

Sabremos que habremos tenido éxito, cuando la generación de reportes sea precisa y personalizable y la satisfacción del cliente con las funcionalidades de reporte sea superior al 85%.

#### 1.2.2.4. Lean UX Canvas
<table><tr><th colspan="1" valign="top"><p><b>Business Problem</b><br>  <br>` `Los trabajadores en entornos industriales enfrentan riesgos significativos debido al uso inadecuado o la falta de control sobre los Equipos de Protección Personal (EPP). Los supervisores carecen de herramientas efectivas para monitorear el cumplimiento de los EPP en tiempo real, lo que puede llevar a accidentes graves y violaciones de las normativas de seguridad.</p><p> </p></th><th colspan="1" rowspan="2" valign="top"><p><b>Solution Ideas</b></p><p>Monitorear el uso de EPP de los trabajadores en tiempo real.</p><p>Recibir notificaciones instantáneas en caso de incumplimientos.</p><p>Generar reportes automáticos sobre el uso de EPP.</p><p>Acceder al sistema desde múltiples dispositivos, incluyendo móviles y tabletas.</p></th><th colspan="1" valign="top"><p><b>Business Outcomes</b><br>Incrementar el cumplimiento de las normativas de seguridad en un 20% en las empresas que implementen el sistema.</p><p>Reducir los incidentes relacionados con el uso incorrecto de EPP en un 15% dentro de los primeros 6 meses de implementación.</p><p>Mejorar la retención de clientes gracias a la integración de nuevas funcionalidades como la generación de reportes automáticos sobre el uso de EPP.</b><br></p><p></p></th></tr>
<tr><td colspan="1" valign="top"><p><b>User & Customers</b><br>`  `<b>Usuarios</b>: Supervisores de seguridad y trabajadores en entornos industriales de alto riesgo, como fábricas, construcciones y minería.</p><p><b>Clientes</b>: Empresas que buscan mejorar la seguridad laboral y el cumplimiento de las normativas de protección.</p></td><td colspan="1" valign="top"><p><b>User Benefits<br><br>Supervisores de Seguridad:</b> Mayor visibilidad y control sobre el uso de EPP, capacidad para tomar decisiones basadas en datos, y reducción en la necesidad de supervisión manual constante.</p><p><b>Trabajadores:</b> Notificaciones y recordatorios que ayudan a asegurar el uso adecuado de EPP, acceso a guías y recomendaciones para mejorar el cumplimiento.</p><p></p></td></tr>
<tr><td colspan="1" valign="top"><p><b>Hypotheses</b><br>  <br>` `<b>Monitoreo en Tiempo Real:</b> Implementar un sistema de monitoreo en tiempo real reducirá los incidentes de EPP en un 15% y aumentará el cumplimiento de las normativas en un 20%.</p><p><b>Notificaciones Instantáneas:</b> Notificaciones instantáneas mejorarán la capacidad de los supervisores para responder rápidamente a incumplimientos, disminuyendo el riesgo de accidentes.</p><p><b>Reportes Automáticos:</b> La generación de reportes automáticos mejorará la toma de decisiones y la satisfacción del cliente, contribuyendo a la retención de clientes.</p></td><td colspan="1" valign="top"><p><b>What’s the most important</b><br>`  `<b>thing we need to learn</b><br>`  `<b>first?</b><br>  </p><p>Lo más importante que necesitamos aprender primero es: La eficacia del sistema de monitoreo en tiempo real para detectar y notificar incumplimientos de EPP.</p></td><td colspan="1" valign="top"><b>What’s the least amount of work</b><br>`  `<b>we need to do to learn the most</b><br>`  `<b>important</b> <b>thing?</b><br>  <br><b>Mínimo trabajo necesario:</b> Desarrollar un prototipo básico del sistema de monitoreo que incluya funcionalidades clave como monitoreo en tiempo real, notificaciones y generación de reportes. Realizar pruebas piloto en un entorno controlado para validar la efectividad del sistema y recopilar retroalimentación de los usuarios para iterar y mejorar el producto antes del lanzamiento completo.</td></tr>
</table>
## 1.3. Segmentos objetivo

**Segmento 1:** Trabajadores de almacenes o construcción civil

Los trabajadores del sector construcción en Perú son en su mayoría hombres, representando el 90% de la fuerza laboral entre 2019 y 2022. En este segmento predominan los adultos de 30 años o más, que constituyeron el 69.6% de los trabajadores en 2022, con un total aproximado de 907 mil ocupados (MTPE, 2024).

El empleo en el sector construcción se concentra principalmente en la costa del país, con Lima agrupando un 33.9% del total de trabajadores (MTPE, 2024). Estos trabajadores enfrentan importantes riesgos laborales, como trabajo en altura, manejo de maquinaria pesada y exposición a materiales peligrosos. Además, es común el uso inadecuado de Equipos de Protección Personal (EPPs), ya sea por falta de supervisión, incomodidad o desconocimiento.

**Segmento 2:** Jefes del área de seguridad

Los jefes de Seguridad, Salud Ocupacional y Medio Ambiente (SSOMA) son responsables de la gestión y supervisión de las políticas y procedimientos de seguridad en los lugares de trabajo, especialmente en sectores de alto riesgo como construcción y almacenamiento. Este segmento está compuesto por profesionales del sector industrial y de construcción, tales como: ingenieros civiles, industriales, etc.


---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Nombre del Competidor | Descripción |
| :-------------------: | :---------- |
| GoDoWorks | GoDoWorks ofrece la funcionalidad de detección de EPP basada en IA en sus soluciones. Su tecnología utiliza cámaras de alta resolución y algoritmos de visión por computadora para monitorear el uso de equipos de protección personal en entornos industriales. El sistema de GoDoWorks analiza las imágenes capturadas en tiempo real para verificar el cumplimiento de las normativas de seguridad, asegurando que los trabajadores usen cascos, chalecos, guantes y otros implementos de protección de manera adecuada. La plataforma emite alertas automáticas si se detecta que un trabajador no está utilizando el EPP correctamente, ayudando a reducir riesgos y mejorar la seguridad en el lugar de trabajo. |
| SoterGenius | Soter Analytics y su software SoterGenius ofrecen un sistema integral para la supervisión del uso de equipos de protección personal, como cascos y chalecos, en entornos industriales. Su solución combina IA con cámaras de visión por computadora para monitorear el cumplimiento en tiempo real. El software analiza las imágenes capturadas para detectar si los trabajadores llevan el equipo de protección necesario y alerta a los supervisores sobre cualquier falta de cumplimiento o riesgo potencial, lo que ayuda a reducir accidentes y mejorar la seguridad general en el lugar de trabajo. |
| IA Box | IA Box ofrece una solución de seguridad basada en inteligencia artificial que analiza video en tiempo real para detectar el correcto uso de EPPs y otros riesgos en el entorno laboral. Utilizando cámaras y sensores ya existentes, su sistema es altamente flexible y configurable, permitiendo la integración con diferentes tecnologías. Además, emite alertas automáticas en caso de detectar anomalías, ayudando a prevenir accidentes y mejorar la seguridad en el lugar de trabajo. |

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
  </tr>
  <tr>
    <td colspan="5">Comparar las características y funcionalidades clave de nuestra solución con las de la competencia para identificar ventajas competitivas y posibles áreas de mejora.</td>
  </tr>
  <tr>
    <td colspan="3">Competidores</td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        Nuestro producto
        <div style="text-align: center; margin-top: 10px;">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        GoDoWorks
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        SoterGenius
        <div style="text-align: center; margin-top: 10px;">
        </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        IA Box
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Ofrece un software que permite detectar y prevenir el mal uso de los implementos de seguridad en almacenes y construcciones. La solución utiliza inteligencia artificial para identificar la correcta utilización de los equipos de protección personal (EPPs).
    </td>
    <td colspan="1" valign="top">Orece un software en tiempo real que analiza imágenes para verificar el uso adecuado de los EPPs y asegurar que se sigan las normas de seguridad
    </td>
    <td colspan="1" valign="top">Proporciona un sistema que previene accidentes por el uso incorrecto de los equipos de protección personal (EPPs), utilizando una inteligencia artificial entrenada con cientos de imágenes de implementos de seguridad para su detección.
    </td>
    <td colspan="1" valign="top">Ofrece un software de seguridad que utiliza inteligencia artificial para monitorear en tiempo real el uso correcto de EPPs y detectar riesgos en el lugar de trabajo, emitiendo alertas automáticas para prevenir accidentes.
    </td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Monitoreo constante y alertas inmediatas cuando detecte un mal uso de EPPs.

Asistencia al cliente 24/7
</td>
    <td colspan="1" valign="top">Emite una alerta al personal de oficina cada vez que detecte la falta de EPPs</td>
    <td colspan="1" valign="top">Ofrece asistencias a problemas con el software 24/7</td>
    <td colspan="1" valign="top">Ofrece un valor significativo a los clientes al mejorar la seguridad en el lugar de trabajo mediante la detección en tiempo real de riesgos y el uso incorrecto de EPPs</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Se centra en el uso de IA para la prevención de accidentes basándose en la detección temprana del mal uso de los EPPso</td>
    <td colspan="1" valign="top">Se enfoca en la integración de inteligencia artificial en la detección de equipo de protección personal (EPP). Su perfil de marketing destaca la innovación y la seguridad en el lugar de trabajo.</td>
    <td colspan="1" valign="top">Se centra en la gestión y monitoreo de EPP mediante tecnología de sensores y análisis de datos para mejorar la seguridad laboral.</td>
    <td colspan="1" valign="top">Se presenta como un líder en la integración de inteligencia artificial para mejorar la seguridad personal en entornos laborales. Destacan su enfoque en utilizar algoritmos específicos para proporcionar soluciones avanzadas de seguridad.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Promover el uso de IA para la prevención de accidentes. Además de realizar programas para la familiarización del sector con el sistema.</td>
    <td colspan="1" valign="top">Utilizan el avance tecnológico y la inteligencia artificial como su principal atractivo. Promocionan la eficiencia y la reducción de riesgos laborales como ventajas clave.</td>
    <td colspan="1" valign="top">Promueven el uso de tecnología avanzada y datos en tiempo real para optimizar el cumplimiento de normas de seguridad. Hacen hincapié en la prevención de accidentes y en la mejora de la eficiencia operativa.</td>
    <td colspan="1" valign="top">La estrategia de marketing se centra en educar a los visitantes sobre los beneficios de la inteligencia artificial en la seguridad.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Ofrece un software basado en IA para la detección del correcto uso de los EPPs en entornos laborales.</td>
    <td colspan="1" valign="top">Ofrecen una solución basada en IA para la detección y prevención del uso incorrecto de EPP. La tecnología está diseñada para mejorar la seguridad en los entornos laborales.</td>
    <td colspan="1" valign="top">Ofrecen sistemas de monitoreo para EPP con sensores que proporcionan datos analíticos sobre su uso. También brindan informes y análisis para ayudar a las empresas a cumplir con las normativas de seguridad.</td>
    <td colspan="1" valign="top">Ofrecen una variedad de productos relacionados con la seguridad en el trabajo</td>
  </tr>
  <tr>
    <td colspan="2">Precios y Costos</td>
    <td colspan="1" valign="top">Por definir</td>
    <td colspan="1" valign="top">La página no proporciona detalles específicos sobre precios.</td>
    <td colspan="1" valign="top">La página no ofrece detalles sobre precios específicos.</td>
    <td colspan="1" valign="top">La página no proporciona información sobre precios.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución</td>
    <td colspan="1" valign="top">El producto se distribuye por medio de la página web, la aplicación y la aplicación móvil.</td>
    <td colspan="1" valign="top">La distribución principal es a través de su sitio web.</td>
    <td colspan="1" valign="top">Distribuyen sus productos principalmente a través de su sitio web.</td>
    <td colspan="1" valign="top">Su distribución principal se realiza a través de su sitio web.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">

- Uso de IA de última generación
- Mejora de seguridad en entorno laboral
- Interfaz amigable

</td>
    <td colspan="1" valign="top">

- Innovación Tecnológica 
- Mejora de Seguridad
- Especialización en EPP

</td>
    <td colspan="1" valign="top">
    
- Monitoreo en Tiempo Real
- Análisis Detallado

</td>
    <td colspan="1" valign="top">

- Enfoque en IA
- Educación del Mercado

</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">

- Sin experiencia en el mercado objetivo
- Poco conocimiento del software en el mercado

</td>
    <td colspan="1" valign="top">
    
- Falta de Información sobre Precios
- Dependencia de Tecnología
</td>
    <td colspan="1" valign="top">

- Falta de Detalles de Precios
- Enfoque en un Nicho Específico
</td>
    <td colspan="1" valign="top">

- Información Limitada sobre Productos y Precios
- Dependencia de Tecnología Específica
</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">
    
- Pocas implementaciones parecidas en el mercado peruano
- Entrenar la IA con nuevos objetos para ampliar nuestro alcance
</td>
    <td colspan="1" valign="top">

- Aumento de la Demanda de Seguridad Laboral
- Expansión a Nuevos Mercados
</td>
    <td colspan="1" valign="top">
    
- Creciente Necesidad de Cumplimiento de Normas
- Desarrollo de Nuevas Funcionalidades
</td>
    <td colspan="1" valign="top">

- Aumento de la Conciencia sobre Seguridad
- Expansión de Contenidos Educativos
</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">
    
- Competencia con más experiencia en el mercado
- Falta de dataset para entrenar el modelo
</td>
    <td colspan="1" valign="top">
    
- Competencia en el Sector
- Evolución Rápida de la Tecnología
</td>
    <td colspan="1" valign="top">

- Competencia Intensa
- Problemas de Privacidad y Datos
</td>
    <td colspan="1" valign="top">
    
- Competencia en Innovación Tecnológica
- Cambios en Regulaciones
</td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

<table>
  <tr>
    <th colspan="3" valign="top"></th>
    <th colspan="4" valign="top"><b>OPORTUNIDADES</b></th>
    <th colspan="4" valign="top"><b>AMENAZAS</b></th>
  </tr>
  <tr>
    <th colspan="3" valign="top"></th>
    <td colspan="4" valign="top">
    O1: Pocas implementaciones parecidas en el mercado peruano

O2: Entrenar la IA con nuevos objetos para ampliar nuestro alcance</td>
    <td colspan="4" valign="top">A1: Competencia con más experiencia en el mercado

A2: Falta de dataset para entrenar el modelo</td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>FORTALEZAS</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FO (Ofensivas)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FA (Defensiva)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">F1: Uso de IA de última generación

F2: Mejora de seguridad en entorno laboral</td>
    <td colspan="4" valign="top">
 
- Implementar campañas que destaquen el uso avanzado de IA para captar la atención de clientes que buscan innovaciones tecnológicas (F1, O1). 
- Realizar pilotos en empresas locales para demostrar la efectividad del software y generar casos de estudio (F2, O1). 
- Resaltar la facilidad de uso de la interfaz en todas las campañas de marketing para atraer a usuarios menos técnicos (F3, O2).</td>

<td colspan="4" valign="top">

- Colaborar con universidades y centros de investigación para obtener datasets más amplios y mejorar el entrenamiento del modelo (F1, A2). 
- Ofrecer soporte técnico personalizado y capacitación para diferenciarse de competidores más experimentados (F2, A1).
- Implementar una estrategia de retención basada en la simplicidad de uso para mantener la base de usuarios (F3, A1).</td>

  </tr>

  <tr>
    <th colspan="3" valign="top"><b>DEBILIDADES</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DO (Reorientación)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DA (Supervivencia)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">D1: Sin experiencia en el mercado objetivo
D2: Poco conocimiento del software en el mercado</td>
    <td colspan="4" valign="top">

- Adoptar una estrategia de alianzas con empresas locales para ganar credibilidad y visibilidad en el mercado (D1, O1).
- Realizar campañas educativas sobre los beneficios del software y la IA en la seguridad laboral, enfocadas en el mercado peruano (D2, O1).</td>

<td colspan="4" valign="top">

- Enfocarse en ofrecer un soporte técnico robusto y crear tutoriales que guíen a los nuevos usuarios a lo largo de su experiencia (D1, A1).
- Ofrecer versiones de prueba gratuitas o a bajo costo para atraer a usuarios y recolectar datos valiosos que puedan utilizarse para mejorar el modelo (D2, A2).</td>

  </tr>

</table>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

**Segmento 1:** Trabajadores de almacenes o construcción civil

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Piero Valverde<br>
      <b>Edad: </b>20<br>
      <b>Distrito:</b> Independecia <br>
      <b>Timing:</b> 0:0:00 - 0:07:27  <br>
      <b>Duración:</b>  07:27 minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a>https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EYA63Hzg-k1Dk7dqBwwoU1UB45Nn96U2dYqSBtjv9TxVJA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7PE7je</a>
      <br>
      <b>Resumen:</b> Piero Valverde, de 20 años, se desempeña actualmente como asistente de almacén en Sodimac. Durante la entrevista, nos comenta que las marcas más utilizadas por su empresa en cuanto a implementos de seguridad son 3M y Delta, debido a su alta calidad y reconocimiento. Piero se describe como una persona que sigue las normas al pie de la letra. Para comunicarse con sus compañeros de trabajo y mantenerse informado sobre los anuncios laborales, utiliza principalmente WhatsApp e Instagram. Sin embargo, menciona que en ocasiones los equipos de protección personal (EPP) que les proporcionan están algo anticuados y presentan defectos, como rajaduras. Además, admite que en algunas ocasiones ha trabajado sin EPPs debido a olvidos en la implementación, aunque al darse cuenta, se asegura de corregir la situación lo más rápido posible.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Italo Vargas <br>
      <b>Edad:</b>  24 años <br>
      <b>Distrito:</b> Los Olivos <br>
      <b>Timing:</b> 0:07:27 - 0:11:15  <br>
      <b>Duración:</b>  03:48 minutos
    </td>
    <td align=center>
      <img src="./assets/ItaloVargas-Entrevista.jpg" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a>https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EYA63Hzg-k1Dk7dqBwwoU1UB45Nn96U2dYqSBtjv9TxVJA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7PE7je</a>
      <br>
      <b>Resumen:</b> El trabajador menciona que las marcas le dan los equipos de seguridad sin una marca en especifico y que al desgastarse se le renuevan los equipos. Tambien menciona que una aplicacion que ayude a mejorar su uso de los epps. Tambien quisiera que le llegara un reporte del dia sobre su uso correcto de epps.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Nombre <br>
      <b>Edad:</b>  edad <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:11:15 - 0:19:36  <br>
      <b>Duración:</b>  8:21 minutos
    </td>
    <td align=center>
      <img src="./assets/ItaloVargas-Entrevista.jpg" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a>https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EYA63Hzg-k1Dk7dqBwwoU1UB45Nn96U2dYqSBtjv9TxVJA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7PE7je</a>
      <br>
      <b>Resumen:</b> 
    </td>
  </tr>
</table>

**Segmento 2:** Jefes del área de seguridad

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Edfrank Martinez  <br>
      <b>Edad:</b>  36 años <br>
      <b>Distrito:</b> Magdalena del Mar <br>
      <b>Timing:</b> 0:19:36 - 0:29:45  <br>
      <b>Duración:</b> 10:09 minutos 
    </td>
    <td align=center>
      <img src="./assets/entrevista-edfrank.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a>https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EYA63Hzg-k1Dk7dqBwwoU1UB45Nn96U2dYqSBtjv9TxVJA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7PE7je</a>
      <br>
      <b>Resumen:</b> Edfrank, de 36 años, trabaja actualmente como supervisor SSOMA. En la entrevista comenta que algunas de sus marcas preferidas para sus implementos de seguridad son 3M, Delta y Bata debido a su calidad. Suele utilizar redes como Instagram y TikTok para encontrar proveedores de EPPs. Respecto a su labor, menciona que se realizan supervisiones mensuales para asegurar que los implementos de seguridad están en buen estado. Uno de los desafíos que enfrenta es que los trabajadores nuevos no están acostumbrados al uso de los EPPs, razón por la cual no siempre se los colocan, por lo que considera importante capacitarlos y educarlos sobre la seguridad en el trabajo. En su día a día, se encarga de vigilar que los obreros tengan puestos todos sus EPPs, previamente entregados por los empleadores. Edfrank considera que un sistema de monitoreo debería tener la capacidad de identificar si los trabajadores están usando o no adecuadamente sus EPPs y enviar una alerta al dispositivo del supervisor, ya que no siempre existen suficientes supervisores para monitorear a todos en todo momento.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Andrea Eguavil   <br>
      <b>Edad:</b>  30 años <br>
      <b>Distrito:</b> Callao <br>
      <b>Timing:</b> 0:29:45 - 0:41:10  <br>
      <b>Duración:</b> 11:25 minutos 
    </td>
    <td align=center>
      <img src="./assets/entrevista-andrea.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a>https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EYA63Hzg-k1Dk7dqBwwoU1UB45Nn96U2dYqSBtjv9TxVJA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7PE7je</a>
      <br>
      <b>Resumen:</b> Andrea es una supervisora SSOMA que labora en el Callao. Comenta que, en su centro de labor, se utilizan implementos de marca 3M, los cuales son renovados de acuerdo con su estado de uso. Suele utilizar redes sociales como Facebook, Instagram y TikTok. Andrea menciona que uno de los desafíos que enfrenta es que los trabajadores no siempre tienen colocados sus implementos de seguridad, por lo cual se les realizan amonestaciones. Se considera una persona estricta, pero trata de entender al personal y capacitarlo sobre la importancia del uso de las EPPs. En su día a día realiza inspecciones para asegurarse del uso adecuado de las EPPs. En cuanto a un sistema de monitoreo, le gustaría que se pueda supervisar a los trabajadores en cada área. Además, considera importante que el sistema sea rápido y eficaz para que las notificaciones lleguen a tiempo. 
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Ricardo Carlos  <br>
      <b>Edad:</b>  42 años <br>
      <b>Distrito:</b> Jesús María <br>
      <b>Timing:</b> 0:41:10 - 1:01:14  <br>
      <b>Duración:</b> 20:02 minutos 
    </td>
    <td align=center>
      <img src="./assets/entrevista-ricardo.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a>https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EYA63Hzg-k1Dk7dqBwwoU1UB45Nn96U2dYqSBtjv9TxVJA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7PE7je</a>
      <br>
      <b>Resumen:</b> Ricardo, de 42 años, ocupa el puesto de Jefe de Seguridad Salud Ocupacional y Medio Ambiente en su empresa. En la entrevista menciona que algunas de las marcas más utilizadas son 3M, Hawk, Clute, entre otras, dependiendo del tipo de EPP. Las redes sociales que más usa son LinkedIn para el contacto con proveedores, además de Whatsapp, donde suele unirse a grupos para compartir información sobre seguridad. Respecto a su labor, menciona que se realizan inspecciones programadas e inspecciones diarias inopinadas (al azar) para verificar el estado de los EPPs. Ricardo comenta haber presenciado casos en los que los obreros no utilizan adecuadamente los EPPs y algunas de las razones por las cuales tienen este tipo de comportamientos inseguros son factores psicológicos e incomodidad al usarlos. Ante ello, considera que es importante capacitar no solo a los trabajadores, sino a todos los niveles de la empresa. Por último, Ricardo menciona que un sistema de monitoreo debería ser permanente y tener la capacidad de permitir al supervisor elegir qué EPPs se deben supervisar en ciertos ambientes, ya que los requerimientos pueden variar en las distintas áreas de la obra. Por ejemplo, en algunos pisos se requiere el uso de arnés, mientras que al inicio de la obra no es necesario.
    </td>
  </tr>
</table>

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

**Segmento 1:** Trabajadores de almacenes o construcción civil

![User Persona Luis Martinez](./assets/user-persona-luis-martinez.png)

**Segmento 2:** Jefes del área de seguridad

![User Persona Santiago Fernandez](./assets/user-persona-santiago-fernandez.png)


### 2.3.2. User Task Matrix

**Segmento 1:** Trabajadores de almacenes o construcción civil

<table>
  <tr>
    <th>User Task</th>
    <th colspan="2">Luis Martinez</th>
  </tr>
  <tr>
    <th></th>
    <th>Frequency</th>
    <th>Importance</th>
  </tr>
  <tr>
    <td>Colocarse correctamente todos los EPPs antes de iniciar su trabajo</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Informar a los supervisores sobre EPPs dañados o en mal estado</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Verificar el estado de los EPPs antes de usarlos</td>
    <td>USUALMENTE</td>
    <td>MEDIA</td>
  </tr>
  <tr>
    <td>Asistir a capacitaciones sobre el uso de EPPs</td>
    <td>A VECES</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Reportar cualquier incidente relacionado con el uso de EPPs</td>
    <td>A VECES</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Mantener los EPPs en buen estado, limpiándolos y guardándolos adecuadamente</td>
    <td>SIEMPRE</td>
    <td>MEDIA</td>
  </tr>
</table>

**Segmento 2:** Jefes del área de seguridad

<table>
  <tr>
    <th>User Task</th>
    <th colspan="2">Santiago Fernandez</th>
  </tr>
  <tr>
    <th></th>
    <th>Frequency</th>
    <th>Importance</th>
  </tr>
  <tr>
    <td>Planificar las estrategias de seguridad</td>
    <td>USUALMENTE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Realizar inspecciones para verificar el estado de los EPPs</td>
    <td>USUALMENTE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Supervisar el uso de EPPs en campo</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Organizar y conducir capacitaciones</td>
     <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Gestionar relación con proveedores de EPPs</td>
    <td>USUALMENTE</td>
    <td>MEDIA</td>
  </tr>
  <tr>
    <td>Reportar incidentes y aplicar medidas correctivas</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Implementar sistemas de monitoreo de seguridad</td>
    <td>A VECES</td>
    <td>ALTA</td>
  </tr>
</table>

### 2.3.3. Empathy Mapping

**Segmento 1:** Trabajadores de almacenes o construcción civil

![Empathy Mapping Luis Martinez](./assets/empathy-mapping-luis-martinez.png)

**Segmento 2:** Jefes del área de seguridad

![Empathy Mapping Santiago Fernandez](./assets/empathy-mapping-santiago-fernandez.png)

### 2.3.4. As-is Scenario Mapping

**Segmento 1:** Trabajadores de almacenes o construcción civil

![As Is Scenario Mapping Luis Martinez](./assets/asis-scenario-mapping-luis-martinez.jpg)

**Segmento 2:** Jefes del área de seguridad

![As Is Scenario Mapping Santiago Fernandez](./assets/asis-scenario-mapping-santiago-fernandez.jpg)

## 2.4. Ubiquitous Language

| **Término**                        | **Definición**                                                                                                          |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| **Personal Protective Equipment (PPE)** | Equipos que se usan para proteger a los trabajadores de peligros en el lugar de trabajo, como cascos, guantes, gafas de seguridad y chalecos reflectantes. |
| **Compliance**                  | Cumplimiento con el uso adecuado del EPP según las regulaciones de seguridad.                                           |
| **Monitoring**                  | Proceso de observar y verificar el uso del EPP entre los trabajadores para asegurar que se mantenga la seguridad.        |
| **Worker**                      | Persona que realiza labores en un sitio de construcción o almacén y que debe usar el EPP para su protección.              |
| **Report**                      | Documento que resume el estado del cumplimiento del EPP, incluyendo estadísticas y cualquier incidente relacionado.      |
| **Hazard**                      | Condición o situación en el lugar de trabajo que puede causar daño y que puede requerir el uso de un tipo específico de EPP. |
| **Incident**                    | Evento relacionado con el uso del EPP que ha ocurrido en el lugar de trabajo, incluyendo detalles sobre qué ocurrió y las acciones tomadas. |
| **Regulations**                 | Reglas y directrices establecidas para el uso del EPP y la seguridad en el lugar de trabajo.                            |
| **Training**                    | Capacitación proporcionada a los trabajadores sobre la importancia del EPP y cómo usarlo correctamente.                 |

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**Segmento 1:** Trabajadores de almacenes o construcción civil

![To Be Scenario Mapping](./assets/To-beSupervisor.jpg)

**Segmento 2:** Jefes del área de seguridad

![To Be Scenario Mapping](./assets/To-beTrabajador.jpg)

## 3.2. User Stories

| **Epic / User Story ID** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                          | **Relacionado con (Epic ID)** |
|---------------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EP01**                  | **Monitoreo de Cumplimiento de EPP**          | Implementar funcionalidades para detectar y notificar incumplimientos en el uso de equipo de protección personal (EPP) por parte de los trabajadores.                                                                                      |                                                                                                                                                                                                                                                                                                                |                               |
| **US01**                  | **Notificación de EPP Incorrecto**            | Como trabajador, quiero recibir notificaciones si no estoy usando correctamente mi EPP para poder corregir el problema de inmediato.                                                                                                       | - **Escenario 1:** Dado que el sistema detecta que no estoy usando correctamente mi casco, cuando estoy en una zona de trabajo, entonces recibo una notificación en mi dispositivo móvil indicando el error.<br> - **Escenario 2:** Dado que recibo una notificación sobre el uso incorrecto de mi EPP, cuando corrijo el error, entonces el sistema deja de enviar alertas y actualiza mi estado a cumplimiento. | EP01                          |
| **US02**                  | **Historial de Notificaciones**               | Como trabajador, quiero revisar mi historial de notificaciones sobre el uso de EPP para entender y corregir mis errores pasados.                                                                                                         | - **Escenario 1:** Dado que quiero revisar mi historial, cuando accedo a la sección de notificaciones en la aplicación, entonces puedo ver todas las alertas que he recibido con fechas y detalles específicos.<br> - **Escenario 2:** Dado que he corregido el uso de mi EPP después de recibir notificaciones, cuando reviso el historial, entonces se indica claramente qué alertas ya han sido resueltas. | EP01                          |
| **US03**                  | **Confirmación de Cumplimiento de EPP**       | Como trabajador, quiero confirmar que estoy usando el EPP correcto al inicio de mi jornada para evitar problemas futuros.                                                                                                                | - **Escenario 1:** Dado que estoy por iniciar una jornada de trabajo, cuando me preparo para comenzar, entonces recibo un recordatorio en la aplicación para verificar mi EPP.<br> - **Escenario 2:** Dado que verifico mi EPP, cuando confirmo en la aplicación que todo está en orden, entonces el sistema registra mi cumplimiento y no emite más recordatorios para esa jornada. | EP01                          |
| **US04**                  | **Guía de Uso de EPP**                       | Como trabajador, quiero acceder a una guía interactiva sobre el uso de EPP para asegurarme de que estoy utilizando el equipo correctamente.                                                                                                 | - **Escenario 1:** Dado que quiero aprender a usar correctamente mi EPP, cuando accedo a la guía en la aplicación, entonces puedo ver videos y tutoriales interactivos sobre el uso adecuado de cada tipo de EPP.<br> - **Escenario 2:** Dado que necesito revisar un procedimiento específico, cuando selecciono un tema en la guía, entonces el sistema me lleva directamente al video o tutorial relacionado con ese tema. | EP01                          |
| **US05**                  | **Recomendaciones Personalizadas**           | Como trabajador, quiero recibir recomendaciones personalizadas basadas en mi historial de cumplimiento para mejorar mi uso de EPP.                                                                                                       | - **Escenario 1:** Dado que he tenido varios incumplimientos, cuando reviso mis notificaciones, entonces puedo ver recomendaciones personalizadas para mejorar mi cumplimiento en el uso de EPP.<br> - **Escenario 2:** Dado que sigo las recomendaciones, cuando reviso mi estado de cumplimiento posteriormente, entonces veo una mejora en mis estadísticas de uso de EPP. | EP01                          |
| **EP02**                  | **Gestión de Alertas y Auditorías**           | Implementar funcionalidades para gestionar alertas relacionadas con el incumplimiento de EPP y realizar auditorías para asegurar el cumplimiento de las normas de seguridad.                                                               |                                                                                                                                                                                                                                                                                                                |                               |
| **US06**                  | **Visualización de Incumplimientos**          | Como jefe de seguridad, quiero ver una lista de trabajadores que no están usando EPP correctamente para tomar medidas correctivas.                                                                                                        | - **Escenario 1:** Dado que el sistema detecta varios trabajadores sin EPP, cuando accedo al panel de seguridad, entonces puedo ver una lista con los nombres y ubicaciones de los trabajadores afectados.<br> - **Escenario 2:** Dado que quiero ver los detalles de un trabajador en particular, cuando selecciono su nombre en la lista, entonces se muestra información detallada sobre sus incumplimientos y su ubicación exacta en el sitio. | EP02                          |
| **US07**                  | **Generación de Reportes Semanales**          | Como jefe de seguridad, quiero generar reportes semanales sobre el uso de EPP para analizar el cumplimiento general y tomar decisiones basadas en datos.                                                                                  | - **Escenario 1:** Dado que es el final de la semana, cuando genero un reporte, entonces puedo ver un resumen de todos los incidentes relacionados con el EPP, incluidos detalles de fechas, horas, y trabajadores involucrados.<br> - **Escenario 2:** Dado que necesito presentar el reporte a la gerencia, cuando exporto el reporte, entonces se genera un archivo PDF con todos los detalles y gráficos relevantes. | EP02                          |
| **US08**                  | **Monitorización en Tiempo Real**             | Como jefe de seguridad, quiero ver un flujo en vivo de las áreas de trabajo para detectar incumplimientos de EPP en tiempo real.                                                                                                         | - **Escenario 1:** Dado que estoy supervisando la seguridad en el sitio, cuando accedo al panel de monitorización, entonces puedo ver un flujo en vivo de las áreas de trabajo con indicaciones visuales de incumplimientos de EPP.<br> - **Escenario 2:** Dado que detecto un incumplimiento en tiempo real, cuando selecciono la alerta, entonces puedo ver detalles específicos del trabajador y del equipo que no está siendo utilizado correctamente. | EP02                          |
| **US09**                  | **Configuración de Alertas**                 | Como jefe de seguridad, quiero configurar alertas personalizadas para el incumplimiento de EPP para adaptarlas a las necesidades específicas del sitio de trabajo.                                                                       | - **Escenario 1:** Dado que quiero configurar alertas, cuando accedo a la sección de configuración de alertas, entonces puedo seleccionar los tipos de EPP y las condiciones específicas para emitir alertas.<br> - **Escenario 2:** Dado que he configurado alertas personalizadas, cuando un trabajador incumple con el EPP, entonces recibo una notificación basada en las condiciones que he especificado. | EP02                          |
| **US10**                  | **Análisis de Tendencias**                   | Como jefe de seguridad, quiero analizar las tendencias en el uso de EPP para identificar patrones y áreas de mejora.                                                                                                                     | - **Escenario 1:** Dado que quiero analizar las tendencias, cuando accedo a la sección de análisis, entonces puedo ver gráficos y estadísticas sobre el uso de EPP por parte de los trabajadores durante un periodo específico.<br> - **Escenario 2:** Dado que quiero enfocar el análisis en una zona específica, cuando selecciono esa zona en el sistema, entonces los gráficos y estadísticas se actualizan para reflejar los datos de esa área en particular. | EP02                          |


## 3.3. Impact Mapping

![Impact Mapping](./assets/impactmapping.svg)

## 3.4. Product Backlog

# Product Backlog

## Tabla de Product Backlog

| **Orden** | **User Story Id** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Story Points** |
|-----------|----------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| 1         | US01| Notificación de EPP Incorrecto                | Como trabajador, quiero recibir notificaciones si no estoy usando correctamente mi EPP para poder corregir el problema de inmediato.                                                                                                       | 5                |
| 2         | US02|Historial de Notificaciones                   | Como trabajador, quiero revisar mi historial de notificaciones sobre el uso de EPP para entender y corregir mis errores pasados.                                                                                                         | 3                |
| 3         | US03| Confirmación de Cumplimiento de EPP           | Como trabajador, quiero confirmar que estoy usando el EPP correcto al inicio de mi jornada para evitar problemas futuros.                                                                                                                | 3                |
| 4         | US04| Guía de Uso de EPP                           | Como trabajador, quiero acceder a una guía interactiva sobre el uso de EPP para asegurarme de que estoy utilizando el equipo correctamente.                                                                                                 | 5                |
| 5         | US05| Recomendaciones Personalizadas               | Como trabajador, quiero recibir recomendaciones personalizadas basadas en mi historial de cumplimiento para mejorar mi uso de EPP.                                                                                                       | 5                |
| 6         | US06| Visualización de Incumplimientos              | Como jefe de seguridad, quiero ver una lista de trabajadores que no están usando EPP correctamente para tomar medidas correctivas.                                                                                                        | 8                |
| 7         | US07| Generación de Reportes Semanales              | Como jefe de seguridad, quiero generar reportes semanales sobre el uso de EPP para analizar el cumplimiento general y tomar decisiones basadas en datos.                                                                                  | 8                |
| 8         | US08| Monitorización en Tiempo Real                 | Como jefe de seguridad, quiero ver un flujo en vivo de las áreas de trabajo para detectar incumplimientos de EPP en tiempo real.                                                                                                         | 8                |
| 9         | US09| Configuración de Alertas                     | Como jefe de seguridad, quiero configurar alertas personalizadas para el incumplimiento de EPP para adaptarlas a las necesidades específicas del sitio de trabajo.                                                                       | 5                |
| 10        | US10| Análisis de Tendencias                       | Como jefe de seguridad, quiero analizar las tendencias en el uso de EPP para identificar patrones y áreas de mejora.                                                                                                                     | 5                |


# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

El propósito del proceso de diseño de nuestra solución es abordar la problemática identificada en el sector de la seguridad industrial, donde la correcta utilización de Equipos de Protección Personal (EPP) es esencial para la protección de los trabajadores y el cumplimiento de las normativas de seguridad. Reconocemos la necesidad de proporcionar una plataforma que permita a las empresas monitorizar y garantizar el uso adecuado de los EPP por parte de sus empleados, mejorando así la seguridad en el lugar de trabajo y asegurando el cumplimiento normativo.

Nuestra solución está diseñada para satisfacer las necesidades de los segmentos objetivo, que incluyen tanto a las empresas industriales que requieren una gestión rigurosa del uso de EPP, como a los trabajadores que necesitan asegurar su protección en el entorno laboral. Al ofrecer una plataforma que utiliza tecnología de visión artificial para detectar en tiempo real el uso correcto de los EPP, así como la posibilidad de recibir notificaciones y reportes detallados sobre el cumplimiento, estamos proporcionando una herramienta integral que responde a las preocupaciones actuales del mercado de seguridad laboral.

Además, nuestro proceso de diseño se orienta a satisfacer las necesidades del negocio al establecer una propuesta de valor clara y diferenciada en el sector de la seguridad. Al enfocarnos en la innovación tecnológica, la educación sobre el uso de EPP, y la colaboración estratégica con proveedores de equipos de protección, estamos posicionando nuestra solución como líder en el mercado de la gestión de EPP, ofreciendo un equilibrio entre efectividad, facilidad de uso y cumplimiento de normativas.

En resumen, el propósito de nuestro proceso de diseño es crear una solución que aborde las necesidades específicas del sector de la seguridad industrial, garantizando el uso adecuado de los EPP mediante tecnología avanzada de detección, y proporcionando herramientas que faciliten la monitorización y el cumplimiento normativo, contribuyendo así a un entorno laboral más seguro y a la mejora del rendimiento empresarial en este ámbito crítico.

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality (Primary User Stories)

|**Epic / User Story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|
| :- | :- | :- | :- |
|USC01|Notificación de no uso de EPP|Detectar automáticamente cuando un trabajador no esté utilizando el EPP requerido y enviar notificaciones en tiempo real|<p>Escenario 1: Cuando el sistema detecta que un trabajador no está usando el EPP correcto (ej. casco o guantes), debe generar una notificación en menos de 5 segundos.</p><p>Escenario 2: Cuando un trabajador corrige el uso del EPP, la notificación debe cesar y el sistema debe actualizar su estado a "cumplimiento".</p><p></p>|
|USC06|Visualización de Incumplimientos|<p>Permitir a los supervisores visualizar una lista detallada de trabajadores que no están usando EPP correctamente, con alertas visuales en el panel de control.</p><p></p>|<p>Escenario 1: Cuando un trabajador no cumple con el uso de EPP, debe aparecer en una lista dentro del panel de control del supervisor, con detalles como nombre, ubicación y tipo de incumplimiento.</p><p>Escenario 2: Al hacer clic en un trabajador en la lista, se debe mostrar información detallada, incluyendo una foto del incumplimiento y el tiempo que lleva sin EPP adecuado.</p>|
|USC07|Generación de Reportes Semanales|Generar automáticamente reportes personalizados sobre el uso de EPP, incluyendo estadísticas y gráficos detallados, descargables para auditorías.|---|
|USC08|Monitorización en Tiempo Real|Proporcionar un flujo de vídeo en vivo de las áreas de trabajo con detección en tiempo real de incumplimientos.|Escenario 1: El sistema debe mostrar una transmisión en vivo de las cámaras de vigilancia instaladas en las zonas de riesgo.|
#### 4.1.2.2. Quality attribute 

|**Atributo**|**Fuente**|**Estímulo**|**Artefacto**|**Entorno**|**Respuesta**|**Medida**|
| :- | :- | :- | :- | :- | :- | :- |
|Seguridad|Gerente de IT	|Un usuario no autorizado intenta acceder al panel de control de seguridad.|Sistema de Gestión de EPP	|Entorno de producción	|El sistema debe bloquear el acceso no autorizado y generar una alerta.	|El acceso debe bloquearse en menos de 1 segundo tras la detección.|
|Escalabilidad|Gerente de IT	|La cantidad de trabajadores monitoreados aumenta un 50% en un nuevo sitio de construcción|Sistema de Monitoreo de EPP	|Expansión del sistema a nuevos sitios	|El sistema debe continuar operando sin degradación en el rendimiento.	|El sistema debe escalar y mantener el rendimiento con hasta 500 usuarios concurrentes.|
|Disponibilidad|Supervisor de seguridad|El sistema detecta que un trabajador no está usando el EPP correcto.|Sistema de Monitoreo de EPP|Operación normal	|El sistema debe enviar una notificación a los supervisores.|<p>El tiempo de respuesta debe ser menor a 5 segundos.</p><p></p>|
|Usabilidad|Trabajador|Un trabajador intenta revisar el historial de notificaciones en la aplicación móvil.|Interfaz de usuario de la aplicación	|Uso en el sitio de trabajo	|El trabajador debe poder acceder y navegar por el historial fácilmente.	|El tiempo para acceder a la función no debe superar los 3 clics o 5 segundos.|
|Fiabilidad|Supervisor de seguridad	|El sistema pierde la conexión a Internet durante 5 minutos.	|Sistema de Monitoreo de EPP	|Entorno de trabajo con pérdida de conexión	|El sistema debe continuar operando localmente y sincronizarse cuando se restablezca la conexión.	|La pérdida de datos no debe superar el 1% durante la desconexión|

#### 4.1.2.3. Constraints
Define las limitaciones técnicas, operativas y de diseño que influyen en las decisiones arquitectónicas y de desarrollo del sistema. Estas restricciones pueden ser impuestas por factores como el hardware, el software, la infraestructura, los recursos disponibles, la compatibilidad con tecnologías existentes o regulaciones de seguridad. Las restricciones ayudan a definir los límites dentro de los cuales debe operar el sistema, asegurando que el diseño cumpla con las expectativas y requerimientos predefinidos.

|**Technical Story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|
| :- | :- | :- | :- |
|TC-01|Limitaciones de Hardware|Integración con Dispositivos de Monitoreo y Sensores|El sistema debe ser capaz de integrarse con dispositivos de monitoreo de seguridad, como cámaras, sensores de movimiento y dispositivos portátiles, que puedan detectar el uso o no uso de EPP en tiempo real. Los dispositivos deben ser compatibles con las normativas de seguridad en entornos industriales.|
|TC-02|Restricciones de Seguridad|Todos los datos capturados por el sistema deben ser almacenados y transmitidos utilizando protocolos de seguridad estándar, como encriptación de extremo a extremo, para garantizar la privacidad y la seguridad de los trabajadores y de las empresas que implementen el sistema.|<p>Los datos deben ser encriptados utilizando AES-256 tanto en reposo como en tránsito.</p><p>Cualquier intento no autorizado de acceso debe generar una alerta y registrar el incid</p>|
|TC-03|Escalabilidad para Grandes Volúmenes de Usuarios|El sistema debe ser escalable para soportar grandes volúmenes de trabajadores y supervisores, sin afectar el rendimiento ni la capacidad de generar alertas en tiempo real.|<p>El sistema debe poder gestionar un mínimo de 1,000 trabajadores simultáneamente por sitio sin comprometer el tiempo de respuesta de las alertas (máximo 5 segundos de retraso).</p><p>La infraestructura debe ser capaz de escalar horizontalmente sin degradación del rendimiento para hasta 10,000 usuarios simultáneos en múltiples sitios.</p><p></p>|
### 4.1.3. Architectural Drivers Backlog
l Architectural Drivers Backlog es una lista priorizada de los principales factores que influyen en el diseño arquitectónico del sistema. Los drivers son elementos clave como los requisitos funcionales, atributos de calidad, restricciones y cualquier otro aspecto que pueda impactar las decisiones técnicas y estructurales del proyecto. Esta lista permite al equipo de desarrollo enfocar los esfuerzos en los aspectos más críticos para cumplir con las expectativas de los stakeholders y asegurar que la solución técnica sea viable y sostenible.

|**Driver ID**|**Título de Driver**|**Descripción**|**Importancia para Stakeholders**|**Impacto en Architecture Technical Complexity**|
| :- | :- | :- | :- | :- |
|AD-01|Monitoreo en Tiempo Real	|El sistema debe monitorear el uso de EPP en tiempo real, generando alertas inmediatas en caso de fallos.	|Alta|Requiere una arquitectura escalable con capacidad de procesamiento en tiempo real y detección de eventos.	|
|AD-02|Notificaciones Automáticas	|Implementar notificaciones automáticas a supervisores y trabajadores cuando se detecten incumplimientos.	|Alta|Necesita integración con sistemas de notificación y procesamiento continuo para enviar alertas en tiempo real.	|
|AD-03|Accesibilidad Multiplataforma	|La solución debe ser accesible desde dispositivos móviles, tabletas y estaciones de trabajo.	|Media|Afecta el diseño de la interfaz de usuario y requiere compatibilidad con varios tipos de dispositivos y sistemas operativos.	|
|AD-04|Generación de Reportes	|Capacidad de generar reportes automáticos y personalizados para auditorías internas y externas.	|Alta |Necesita mecanismos eficientes para almacenar, acceder y procesar grandes volúmenes de datos históricos y generar reportes complejos.	|
|AD-05|Seguridad de Datos	|Asegurar que todos los datos de los trabajadores y su EPP se manejen de forma segura y cumplan con normativas.	|ALta |Implica la integración de medidas de seguridad como cifrado, autenticación y autorización en la arquitectura del sistema.|
|AD-06|Detección Automática de Incumplimientos	|El sistema debe identificar automáticamente cuando un trabajador entra en una zona de riesgo sin el EPP adecuado.	|Alta|Afecta directamente los algoritmos de detección y análisis de imágenes, y puede influir en el diseño del procesamiento de datos.	|
### 4.1.4. Architectural Design Decisions
Son las decisiones críticas que se toman durante el desarrollo de la arquitectura del sistema para definir su estructura y comportamiento. Estas decisiones afectan aspectos clave del sistema, como su rendimiento, escalabilidad, seguridad y mantenibilidad. Cada decisión está basada en los drivers arquitectónicos, restricciones y requisitos del proyecto. Documentar estas decisiones ayuda a asegurar que las soluciones arquitectónicas elegidas sean claras y comprensibles para todos los involucrados.
**Etapas de las Architectural Design Decisions:**
- Identificación de los Drivers Arquitectónicos: Basado en los architectural drivers identificados en el backlog, el equipo determina las áreas clave donde se deben tomar decisiones de diseño, como rendimiento, seguridad o escalabilidad.
- Evaluación de Alternativas: Para cada driver, se evalúan diferentes alternativas de diseño. Estas pueden incluir el uso de diferentes tecnologías, patrones de diseño o enfoques arquitectónicos (por ejemplo, arquitectura basada en microservicios vs. arquitectura monolítica).
- Análisis de Impacto: Cada alternativa es analizada en términos de su impacto en los requisitos funcionales, no funcionales (atributos de calidad) y las restricciones técnicas. Esto incluye factores como la complejidad, costo, tiempo de implementación, riesgos técnicos, etc.
- Selección de la Solución Óptima: Se selecciona la mejor solución basada en los análisis previos, tomando en cuenta las necesidades de los stakeholders, el impacto en la arquitectura y la viabilidad técnica.
- Documentación de la Decisión: Una vez tomada la decisión, se documenta claramente para que todos los miembros del equipo y los stakeholders entiendan las razones detrás de la elección y su impacto en el proyecto. Esto asegura coherencia y facilita futuras revisiones o modificaciones.
- Validación y Seguimiento: Finalmente, se valida la implementación de la decisión y se monitoriza su efectividad durante el desarrollo del sistema. Cualquier ajuste necesario se retroalimenta al proceso de toma de decisiones.
### 4.1.5. Quality Attribute Scenario Refinements

|**Atributo**|**Fuente**|**Estímulo**|**Artefacto**|**Entorno**|**Respuesta**|**Medida de éxito**|
| :- | :- | :- | :- | :- | :- | :- |
|Rendimiento|Usuario|El usuario solicita una notificación en tiempo real cuando un trabajador no usa el EPP adecuado.	|Sistema de Notificaciones	|Operación normal con carga alta	|El sistema envía la notificación en menos de 2 segundos.	|Notificación enviada en ≤ 2 segundos en el 95% de los casos.|
|Disponibilidad	|Sistema externo	|El sistema de autenticación externa (OAuth) se cae temporalmente.	|Módulo de autenticación	|Operación con falla de servicio externo	|El sistema debe permitir el acceso limitado usando credenciales almacenadas en caché.	|El sistema se recupera sin interrupciones mayores a 10 segundos.|
|Escalabilidad|Admin|El número de trabajadores conectados se duplica durante una auditoría de seguridad.	|Sistema de Monitoreo en Tiempo Real	|Sobrecarga de usuarios	|El sistema sigue monitoreando y procesando los datos sin disminución perceptible.	|El sistema soporta hasta el doble de usuarios sin degradación en el rendimiento.|
|Seguridad|Hacker	|Un atacante intenta acceder a los datos de EPP de los trabajadores mediante un ataque de fuerza bruta.	|Sistema de Autenticación	|Operación bajo ataque de seguridad	|El sistema detecta el ataque y bloquea el intento después de 3 intentos fallidos.	|<p>El 100% de los ataques de fuerza bruta son bloqueados sin comprometer datos.</p><p></p>|
|Mantenibilidad|Equipo de desarrollo	|Un desarrollador necesita realizar una actualización del sistema sin interrumpir el servicio.	|Backend|Durante operación normal	|La actualización se implementa sin causar interrupciones a los usuarios.	|<p>El 95% de las actualizaciones se realizan sin tiempo de inactividad.</p><p></p>|
|Usabilidad	|Trabajador|Un trabajador debe confirmar que está usando el EPP adecuado al entrar en una zona de riesgo.	|Interfaz de usuario	|Operación normal	|La interfaz guía al trabajador en menos de 3 pasos para verificar el uso de EPP.	|Los trabajadores completan la verificación en menos de 5 segundos el 90% de las veces.|
## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming
![EventStorming](/assets/EventStorming.png)

Enlace completo del Miroo:
https://miro.com/app/board/uXjVKiSjLO0=/?share_link_id=691985821601 

### 4.2.2. Candidate Context Discovery


### 4.2.3. Domain Message Flows Modeling

### 4.2.4. Bounded Context Canvases

### 4.2.5. Context Mapping

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

### 4.3.2. Software Architecture Context Level Diagrams

### 4.3.3. Software Architecture Container Level Diagrams

### 4.3.4. Software Architecture Deployment Diagrams

---

# Conclusiones

--- 

# Bibliografía


Ministerio de Trabajo y Promoción del Empleo (MTPE). (2024). *Reporte del Mercado Laboral: Sector Construcción*. Recuperado de https://cdn.www.gob.pe/uploads/document/file/6565614/5716638-reporte-mercado-laboral-sector-construccion.pdf. 

--- 

# Anexos