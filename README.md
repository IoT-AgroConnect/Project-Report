<p align="center">
  <img src="img/image1.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">

# <span style="color:red">**Universidad Peruana de Ciencias Aplicadas**</span>
## Carrera de Ingeniería de Software

Ciclo: 2025 - 10

Curso: 1ASI0572 Desarrollo de Soluciones IoT

NRC: 2968

Profesor: León Baca, Marco Antonio

“Informe de Trabajo Final"

Startup: AgroTech

Producto: AgroCuy

Grupo: 4

|          Integrantes          |      Código      |
|:-----------------------------:|:-------------------:|
|   Cuadros Rodriguez, Juan Alejandro    |    u20221a359    |
|   Jarama Peñaloza, Fiorella    |   u202120418  |
|  Lucas Coronel, Nadia Alessandra   |    U202120430    |
|   Moreno Vergara, Johan Raúl  |    u20201c105    |
|  Ramirez Mendez, Sebastian Andre   |    u20191e575    |

Abril 2025 

</div>

---

## Registro de Versiones Del Informe

<table>
  <tr>
    <th>Versión</th>
    <th>Fecha</th>
    <th>Autores</th>
    <th>Descripción de modificación</th>
  </tr>
  <tr>
    <td rowspan="5">TB1</td>
    <td rowspan="5">04/10/2025</td>
    <td>Cuadros Rodriguez, Juan Alejandro</td>
    <td rowspan="5">
      <strong>Capítulo I</strong>: Introducción<br>
      <strong>Capítulo II</strong>: Requirements Elicitation & Analysis<br>
      <strong>Capítulo III</strong>: Requirements Specification<br>
      <strong>Capítulo IV</strong>: Solution Software Design
    </td>
  </tr>
  <tr>
    <td>Fiorella Jarama Peñaloza</td>
  </tr>
  <tr>
    <td>Lucas Coronel, Nadia Alessandra</td>
  </tr>
  <tr>
    <td>Moreno Vergara, Johan Raúl</td>
  </tr>
  <tr>
    <td>Ramirez Mendez, Sebastian Andre</td>
  </tr>
</table>



## Project Report Collaboration Insights

### **Reporte de colaboración de la entrega del TB1:**

------

# Contenido

## [Capítulo I: Introducción](#capítulo-i-introducción)
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

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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

## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. System Landscape Diagram](#4131-system-landscape-diagram)
    - [4.1.3.2. Context Level Diagrams](#4132-context-level-diagrams)
    - [4.1.3.2. Container Level Diagrams](#4132-container-level-diagrams)
    - [4.1.3.3. Deployment Diagrams](#4133-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.1. Bounded Context: Security](#421-bounded-context-security)
    - [4.2.1.1. Domain Layer](#4211-domain-layer)
    - [4.2.1.2. Interface Layer](#4212-interface-layer)
    - [4.2.1.3. Application Layer](#4213-application-layer)
    - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
    - [4.2.1.5. Component Level Diagrams](#4215-component-level-diagrams)
    - [4.2.1.6. Code Level Diagrams](#4216-code-level-diagrams)
      - [4.2.1.6.1. Domain Layer Class Diagrams](#42161-domain-layer-class-diagrams)
      - [4.2.1.6.2. Database Design Diagram](#42162-database-design-diagram)
    - [4.2.2. Bounded Context: Monitoring](#422-bounded-context-monitoring)
    - [4.2.2.1. Domain Layer](#4221-domain-layer)
    - [4.2.2.2. Interface Layer](#4222-interface-layer)
    - [4.2.2.3. Application Layer](#4223-application-layer)
    - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
    - [4.2.2.5. Component Level Diagrams](#4225-component-level-diagrams)
    - [4.2.2.6. Code Level Diagrams](#4226-code-level-diagrams)
      - [4.2.2.6.1. Domain Layer Class Diagrams](#42261-domain-layer-class-diagrams)
      - [4.2.2.6.2. Database Design Diagram](#42262-database-design-diagram)
    - [4.2.3. Bounded Context: Consulting](#423-bounded-context-consulting)
    - [4.2.3.1. Domain Layer](#4231-domain-layer)
    - [4.2.3.2. Interface Layer](#4232-interface-layer)
    - [4.2.3.3. Application Layer](#4233-application-layer)
    - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
    - [4.2.3.5. Component Level Diagrams](#4235-component-level-diagrams)
    - [4.2.3.6. Code Level Diagrams](#4236-code-level-diagrams)
      - [4.2.3.6.1. Domain Layer Class Diagrams](#42361-domain-layer-class-diagrams)
      - [4.2.3.6.2. Database Design Diagram](#42362-database-design-diagram)
    - [4.2.4. Bounded Context: Management](#424-bounded-context-management)
    - [4.2.4.1. Domain Layer](#4241-domain-layer)
    - [4.2.4.2. Interface Layer](#4242-interface-layer)
    - [4.2.4.3. Application Layer](#4243-application-layer)
    - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
    - [4.2.4.5. Component Level Diagrams](#4245-component-level-diagrams)
    - [4.2.4.6. Code Level Diagrams](#4246-code-level-diagrams)
      - [4.2.4.6.1. Domain Layer Class Diagrams](#42461-domain-layer-class-diagrams)
      - [4.2.4.6.2. Database Design Diagram](#42462-database-design-diagram)
    - [4.2.5. Bounded Context: Publication](#425-bounded-context-publication)
    - [4.2.5.1. Domain Layer](#4251-domain-layer)
    - [4.2.5.2. Interface Layer](#4252-interface-layer)
    - [4.2.5.3. Application Layer](#4253-application-layer)
    - [4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)
    - [4.2.5.5. Component Level Diagrams](#4255-component-level-diagrams)
    - [4.2.5.6. Code Level Diagrams](#4256-code-level-diagrams)
      - [4.2.5.6.1. Domain Layer Class Diagrams](#42561-domain-layer-class-diagrams)
      - [4.2.5.6.2. Database Design Diagram](#42562-database-design-diagram)

## [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
- [5.1. Style Guidelines](#51-style-guidelines)
  - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
  - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
  - [5.2.1. Organization Systems](#521-organization-systems)
  - [5.2.2. Labeling Systems](#522-labeling-systems)
  - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
  - [5.2.4. Searching Systems](#524-searching-systems)
  - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
  - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
  - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-applications-uxui-design)
  - [5.4.1. Applications Wireframes](#541-applications-wireframes)
  - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
  - [5.4.2. Applications Mock-ups](#542-applications-mock-ups)
  - [5.4.3. Applications User Flow Diagrams](#543-applications-user-flow-diagrams)
- [5.5. Applications Prototyping](#55-applications-prototyping)

## [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Development Environment Configuration](#611-development-environment-configuration)
  - [6.1.2. Source Code Management](#612-source-code-management)
  - [6.1.3. Style Guide & Conventions](#613-style-guide--conventions)
  - [6.1.4. Deployment Configuration](#614-deployment-configuration)
- [6.2. Implementation](#62-implementation)
  - [6.2.1. Sprint 1](#621-sprint-1)
    - [6.2.1.1. Sprint Planning](#6211-sprint-planning)
    - [6.2.1.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
    - [6.2.1.3. Sprint Backlog](#6213-sprint-backlog)
    - [6.2.1.4. Development Evidence](#6214-development-evidence)
    - [6.2.1.5. Testing Suite Evidence](#6215-testing-suite-evidence)
    - [6.2.1.6. Execution Evidence](#6216-execution-evidence)
    - [6.2.1.7. Services Documentation](#6217-services-documentation)
    - [6.2.1.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence)
    - [6.2.1.9. Team Collaboration Insights](#6219-team-collaboration-insights)
  - [6.2.2. Sprint 2](#622-sprint-2)
    - [6.2.2.1. Sprint Planning](#6221-sprint-planning)
    - [6.2.2.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
    - [6.2.2.3. Sprint Backlog](#6223-sprint-backlog)
    - [6.2.2.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
    - [6.2.2.5. Testing Suite Evidence for Sprint Review](#6225-testing-suite-evidence-for-sprint-review)
    - [6.2.2.6. Execution Evidence for Sprint Review](#6226-execution-evidence-for-sprint-review)
    - [6.2.2.7. Services Documentation Evidence for Sprint Review](#6227-services-documentation-evidence-for-sprint-review)
    - [6.2.2.8. Software Deployment Evidence for Sprint Review](#6228-software-deployment-evidence-for-sprint-review)
    - [6.2.2.9. Team Collaboration Insights during Sprint](#6229-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)

## [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)



## Student Outcome

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>
    <td>
      <strong>Cuadros Rodriguez, Juan Alejandro</strong><br>
      <em>TB1</em><br>
      Realicé la investigación y revisión de los puntos del trabajo, lo que me permitió implementar adecuadamente la redacción del proyecto y asegurar la correcta revisión del contenido.<br>
      <strong>Jarama Peñaloza, Fiorella</strong><br>
      <em>TB1</em><br>
      Me aseguré de que todos estuviéramos avanzando de forma constante, hice revisiones (reus) del trabajo del equipo y ofrecí apoyo cuando alguien se quedaba atrás.<br>
      <em>TB2</em><br>
      Lideré la integración entre el backend y el frontend para la visualización de datos del ESP32 usando MQTT. Me encargué de configurar la recepción de los datos de sensores en tiempo real desde el ESP32, desarrollar la lógica para mostrar los límites críticos en la interfaz, y de implementar las notificaciones automáticas al detectar valores fuera de rango. También realicé pruebas completas de la comunicación IoT y aseguré la conexión estable del sistema.
      <strong>Lucas Coronel, Nadia Alessandra</strong><br>
      <em>TB1</em><br>
       Me encargué de dividir el trabajo de manera equitativa y de establecer plazos de entrega claros para cada miembro del equipo. Además, coordiné las tareas, asegurándome de que cada persona comprendiera sus responsabilidades y los objetivos a alcanzar. Realicé un seguimiento constante del progreso y brindé apoyo para resolver dudas o dificultades que surgieran durante el desarrollo del proyecto.<br>
      <strong>Ramirez Mendez, Sebastián André</strong><br>
      <em>TB1</em><br>
      Me encargué de coordinar la estructura del documento y asegurar que cada sección tuviera coherencia, además de participar en la redacción de los antecedentes del proyecto y revisión técnica del contenido.<br>
      <strong>Moreno Vergara, Johan</strong><br>
      <em>TB1</em><br>
      Para esta entrega nos pusimos de acuerdo para tener reuniones para elegir el tema de nuestro proyecto y delegar responsabilidades. Además de una reunión para corroborar el correcto avance de cada uno de los miembros de nuestro equipo.<br>
      <br>
      …  
    </td>
    <td>
      <em>TB1</em><br>
      Durante el desarrollo del proyecto, el equipo demostró un liderazgo compartido y efectivo, basado en la colaboración continua. Cada miembro asumió responsabilidades específicas, apoyó a sus compañeros y mantuvo una comunicación constante para garantizar la calidad de los entregables. Gracias a esta dinámica, logramos integrar nuestras habilidades individuales en un trabajo cohesivo y bien estructurado.<br>
    </td>
  </tr>
  <tr>
    <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
    <td>
      <strong>Cuadros Rodriguez, Juan Alejandro</strong><br>
      <em>TB1</em><br>
      e estableció un ambiente de colaboración, por lo que se implementó un sistema de fechas de entrega, acompañado del compromiso del equipo para cumplir con los plazos establecidos.<br>
      <strong>Jarama Peñaloza, Fiorella</strong><br>
      <em>TB1</em><br>
      Fomenté un ambiente donde todos pudieran participar, ayudé a organizar las tareas del equipo y propuse metas claras para cumplir con los entregables a tiempo.<br>
      <em>TB2</em><br>
      Fomenté un ambiente colaborativo e inclusivo durante el desarrollo del proyecto. Establecí metas claras junto con el equipo, organicé la planificación de tareas en función de nuestras fortalezas y aseguré que todos participaran activamente. Además, supervisé el cumplimiento de los objetivos semanales y coordiné entregas clave como la integración IoT con MQTT, el backend para recibir datos del ESP32, y el frontend para mostrar los límites en tiempo real.
      <strong>Lucas Coronel, Nadia Alessandra</strong><br>
<em>TB1</em><br>
Fomenté un entorno colaborativo e inclusivo, asegurándome de que todos los integrantes se sintieran escuchados y valorados. Establecí metas claras para el equipo, planifiqué la distribución de tareas según las fortalezas de cada miembro y definí plazos de entrega realistas. Gracias a esta organización y al acompañamiento constante, cumplimos con los objetivos planteados de manera eficiente.<br>
      <strong>Ramirez Mendez, Sebastian Andre</strong><br>
      <em>TB1</em><br>
      Propicié un entorno colaborativo asegurando la participación de todos los miembros, ayudé a definir metas claras, y coordiné la planificación de tareas para que se cumplieran los objetivos del equipo dentro de los plazos establecidos.<br>
      <strong>Moreno Vergara, Johan</strong><br>
      <em>TB1</em><br>
      Se establecieron fechas de entrega para cada tarea delegada, de esa forma aseguramos que se cumpla el objetivo de cada miembro de equipo y poder tener el trabajo en fechas específicas antes de la entrega.<br>
      <br>
      …  
    </td>
    <td>
       <em>TB1</em><br>
      El equipo promovió un ambiente inclusivo en el que todos los integrantes participaron activamente en la toma de decisiones y en el desarrollo de las tareas asignadas. Se establecieron metas claras y realistas, acompañadas de una planificación adecuada que permitió cumplir con los plazos establecidos. La colaboración y el compromiso de cada miembro fueron claves para alcanzar los objetivos propuestos de manera organizada y efectiva. <br>
    </td>
  </tr>
</table>

### Tabla de Trabajo Colaborativo – TP1

| **Criterio específico** | **Acciones realizadas (TP1)** | **Conclusiones (TP1)** |
|-------------------------|-------------------------------|-------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **Cuadros Rodríguez, Juan Alejandro**  <br> *TP1*  <br> Participé en la estructuración de los entregables del proyecto, brindando soporte técnico en la interfaz y validación de los componentes implementados por mis compañeros. Coordiné puntos clave para la integración de código y participé activamente en las sesiones de retroalimentación. <br><br> **Jarama Peñaloza, Fiorella**  <br> *TP1*  <br> Me encargué de testear las funcionalidades desarrolladas en el frontend, y propuse ajustes de usabilidad en base a pruebas exploratorias. También apoyé la documentación visual de las interfaces y organicé sesiones para revisión por pares. <br><br> **Lucas Coronel, Nadia Alessandra**  <br> *TP1*  <br> Organicé reuniones semanales para dar seguimiento al avance del frontend. También consolidé los entregables técnicos y coordiné la división de tareas para cubrir correctamente todas las US. Fui responsable del deployment de la landing y su validación. <br><br> **Ramírez Méndez, Sebastián André**  <br> *TP1*  <br> Me encargué de los componentes más técnicos relacionados con la lógica y validaciones del sistema. Además, me aseguré de que la documentación técnica del frontend sea clara y consistente, apoyando a otros miembros en pruebas de integración. <br><br> **Moreno Vergara, Johan Raúl**  <br> *TP1*  <br> Desarrollé y conecté componentes clave del frontend. Durante las reuniones asumí un rol de apoyo y validación cruzada del trabajo de otros compañeros, contribuyendo a mejorar la calidad final del entregable. | *TP1*  <br> En este tramo del proyecto, el equipo demostró nuevamente un liderazgo colaborativo al asumir tareas críticas del desarrollo del frontend y la integración de las secciones funcionales. Todos participaron activamente, compartiendo conocimientos técnicos, validando el trabajo entre pares y aportando mejoras que permitieron entregar una versión funcional y profesional de la aplicación. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Cuadros Rodríguez, Juan Alejandro**  <br> *TP1*  <br> Contribuí al seguimiento de los avances grupales y aseguré que se cumplieran los acuerdos de codificación. Participé activamente en reuniones de planificación para definir las metas y la organización de commits por sprint. <br><br> **Jarama Peñaloza, Fiorella**  <br> *TP1*  <br> Apoyé la planificación visual del proyecto, asegurándome de que todos contáramos con acceso a los archivos de diseño y entendimiento compartido. También propuse soluciones simples para problemas detectados en validaciones. <br><br> **Lucas Coronel, Nadia Alessandra**  <br> *TP1*  <br> Definí un cronograma de avances con fechas intermedias y tareas asignadas para cada miembro. Estuve pendiente de los bloqueos de mis compañeros y coordiné la integración de los entregables parciales en un repositorio limpio y funcional. <br><br> **Ramírez Méndez, Sebastián André**  <br> *TP1*  <br> Organicé el orden de los componentes en el repositorio principal y me aseguré de que la estructura de carpetas y archivos fuera coherente. Participé en la verificación del cumplimiento de las metas trazadas para cada User Story. <br><br> **Moreno Vergara, Johan Raúl**  <br> *TP1*  <br> Apoyé la integración de todos los módulos desarrollados y me aseguré de que la configuración del entorno fuera clara para todos. Contribuí a que el entorno colaborativo se mantuviera alineado y productivo. | *TP1*  <br> El equipo fortaleció su dinámica colaborativa estableciendo procesos más definidos, herramientas compartidas (repositorio, Trello, entornos de pruebas) y objetivos semanales claros. Esto permitió que las tareas se cumplieran dentro del cronograma y que el producto entregado mantuviera altos estándares técnicos, tanto en funcionalidad como en presentación visual. |

-----
### Tabla de Trabajo Colaborativo – TB2


| **Criterio específico** | **Acciones realizadas (TB2)** | **Conclusiones (TB2)** |
|-------------------------|-------------------------------|-------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **Cuadros Rodríguez, Juan Alejandro**  <br> *TB2*  <br> Participé activamente en la implementación del módulo de estadísticas con filtros por fecha y rol. Coordiné puntos clave de integración entre componentes del frontend y colaboré en la depuración general de la interfaz. Además, brindé soporte técnico en la integración de la primera versión del mobile app. <br><br> **Jarama Peñaloza, Fiorella**  <br> *TB2*  <br> Colaboré en la validación de usabilidad de la interfaz principal, incluyendo el Landing Page. Documenté observaciones durante las pruebas funcionales y apoyé la revisión visual del frontend. También ayudé en la revisión cruzada del diseño del prototipo móvil. <br><br> **Lucas Coronel, Nadia Alessandra**  <br> *TB2*  <br> Consolidé y desplegué la versión final del Landing Page, coordinando con el equipo la conexión de endpoints y el uso de datos reales. Supervisé la integración del frontend completo, y participé en las pruebas iniciales del prototipo IoT con lógica de edge computing. <br><br> **Ramírez Méndez, Sebastián André**  <br> *TB2*  <br> Refactoricé la lógica de reportes y estadísticas, asegurando que los datos personales y globales se visualicen según reglas temporales y de rol. Supervisé la calidad del código del frontend e integré la lógica del sistema con el backend. Colaboré en la validación funcional del módulo de sensores IoT. <br><br> **Moreno Vergara, Johan Raúl**  <br> *TB2*  <br> Desarrollé la vista de tendencias (Top 15) y me encargué de asegurar su correcto funcionamiento en tiempo real. También implementé y validé la interfaz del prototipo IoT y participé en la construcción de la primera versión del mobile app. | *TB2*  <br> En este tramo del proyecto, el equipo consolidó su liderazgo colaborativo al entregar una versión funcional y sólida del sistema. Se completaron con éxito el Landing Page, el frontend completo, la primera versión del mobile app y el prototipo IoT. La coordinación entre miembros permitió una integración fluida de tecnologías diversas, con un enfoque técnico compartido y validación cruzada que elevó la calidad del entregable final. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Cuadros Rodríguez, Juan Alejandro**  <br> *TB2*  <br> Establecí prioridades para el desarrollo del módulo de estadísticas, promoviendo una distribución equitativa de tareas. Colaboré en mantener la documentación técnica actualizada en GitHub. <br><br> **Jarama Peñaloza, Fiorella**  <br> *TB2*  <br> Apoyé la organización del entorno colaborativo mediante Trello y control de versiones. Registré mejoras sugeridas y propuse acciones puntuales para mejorar la experiencia de usuario. <br><br> **Lucas Coronel, Nadia Alessandra**  <br> *TB2*  <br> Lideré el cronograma de entregables de frontend y landing, y aseguré que todas las tareas de integración se completaran a tiempo. También di soporte en las validaciones del entorno móvil y pruebas de IoT. <br><br> **Ramírez Méndez, Sebastián André**  <br> *TB2*  <br> Documenté la lógica de separación de datos por rol/fecha y coordiné con el backend para mantener consistencia. Aporté en la revisión técnica del código general y propuse refactorizaciones clave. <br><br> **Moreno Vergara, Johan Raúl**  <br> *TB2*  <br> Organicé la estructura de archivos para la vista de tendencias y para los componentes de mobile. Verifiqué que la integración IoT se adapte al entorno de pruebas en edge computing. | *TPB*  <br> El equipo fortaleció su entorno colaborativo a través de una planificación precisa, cronogramas definidos, sesiones de revisión cruzada y comunicación continua. El cumplimiento de objetivos se mantuvo constante, incluso ante desafíos técnicos como el despliegue móvil o la integración de hardware. Esto permitió entregar una versión integrada, validada y funcional de todos los módulos clave del sistema. |


## Capítulo I: Introducción 

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup


AgroTech nace con el objetivo de facilitar y modernizar la crianza de cuyes en el Perú, mediante la implementación de tecnologías IoT que automatizan y optimizan los procesos clave dentro de los criaderos. A través de nuestra aplicación AgroCuy, brindamos a los pequeños y medianos criadores una herramienta tecnológica que les permite gestionar, monitorear y controlar su producción desde cualquier lugar y en tiempo real, utilizando sus dispositivos móviles o computadoras.

La solución propuesta por AgroTech integra funcionalidades como alimentación automatizada, monitoreo ambiental con sensores de temperatura, humedad y gases, control de calidad del agua y riego automatizado. Esto permite a los usuarios garantizar un entorno saludable para los cuyes, mejorar su bienestar, reducir riesgos y aumentar la eficiencia operativa de sus granjas.

**Misión:**

Optimizar la crianza de cuyes en el Perú mediante herramientas avanzadas de automatización y monitoreo. De esta manera, contribuir al desarrollo sostenible de la producción ganadera y al bienestar animal a través de soluciones tecnológicas accesibles.

**Visión:**

Ser la plataforma tecnológica más utilizada por criadores de cuyes en el país, promoviendo la innovación, eficiencia y sostenibilidad en el sector ganadero. Asimismo, consolidarnos como referentes en el uso de IoT en la crianza animal y expandirnos hacia otras especies en el futuro.

<p align="center">
  <img src="img/logo.png"
  alt="logo de AgroCuy"
  width="200">
</p>

_Imagen 1. Logo de la aplicación AgroCuy_

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <th>
      <img src="img/sebas_perfil.jpeg" alt="Foto de perfil de" width="800px">
    </th>
    <td valign="top">
      <p><b>Ramírez Méndez, Sebastián André</b></p>
      <p>
        Soy una persona entusiasta que disfruta colaborar en equipo, y me caracterizo por ser transparente en mis objetivos y en mi enfoque de trabajo. Me enorgullece la capacidad que tengo para complementar a mi equipo en áreas donde puedan necesitar apoyo. Mi pasión por mi carrera me impulsa a desafiar mis habilidades y aspirar a alcanzar todo su potencial.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/perfil_fiorella.jpg" alt="Foto de perfil de Fiorella" width="800px">
    </th>
    <td valign="top">
      <p><b>Jarama Peñaloza, Fiorella</b></p>
      <p>
        Mi nombre es Fiorella Jarama Peñaloza y soy estudiante de séptimo ciclo de Ingeniería de Software. Me considero una persona apasionada por la tecnología, curiosa y orientada al detalle. Tengo experiencia en Flutter, MySQL, APIs, y estoy en constante aprendizaje sobre Inteligencia Artificial. Mi objetivo es aplicar mis habilidades para desarrollar soluciones innovadoras y eficientes, contribuyendo a proyectos que tengan un impacto positivo y sostenible.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/nadia_perfil.png" alt="Foto de perfil de Nadia" width="800px">
    </th>
    <td valign="top">
      <p><b>Lucas Coronel, Nadia Alessandra</b></p>
      <p>
        Mi nombre es Nadia Alessandra Lucas Coronel y soy estudiante de octavo ciclo de la carrera de Ingeniería de Software. Me considero una persona entusiasta, perseverante y responsable. Cuento con conocimientos en SQL, C++, Python, HTML, CSS, JavaScript, despligue y metodologías ágiles. Me comprometo a aplicar mis conocimientos de manera efectiva para contribuir al desarrollo de soluciones de software de alta calidad.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="https://i.postimg.cc/yxcDXfTV/RREeduc-Foto-Carnet-Johan-Moreno-min-1.png" alt="Foto de perfil de Johan" width="800px">
    </th>
    <td valign="top">
      <p><b>Moreno Vergara, Johan Raúl</b></p>
      <p>
        Me llamo Johan y soy estudiante de la carrera de Ingeniería de Software. Soy una persona bastante optimista y responsable. Me apasionan los temas de ciberseguridad e inteligencia artificial. Cuento con conocimientos en Python, SQL, ciberseguridad, entrenamiento de modelos de IA y algunos frameworks de desarrollo web.Dentro de mis hobbies está practicar artes marciales como el boxeo, Muay Thai y MMA. Me comprometo a apoyar a mi equipo y poner en práctica mis conocimientos.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/Juan-Photo.png" alt="Foto de perfil de" width="700px">
    </th>
    <td valign="top">
      <p><b>Cuadros Rodriguez, Juan Alejandro</b></p>
      <p>
        Mi nombre es Juan Cuadros me considero una persona responsable, paciente y comprometida. Tengo conocimientos en los lenguajes de programación C/C++, Python y Java. Además de experiencia en gran manejo de datos usando SQL. También tengo conocimientos en Análisis de vulnerabilidades y explotación de datos. Estoy comprometido con el equipo y el proyecto.
      </p>
    </td>
  </tr>
</table>


<br>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

- **What:** El sector de la crianza de cuyes enfrenta desafíos en la gestión eficiente de las granjas, la falta de acceso a tecnologías adecuadas y la necesidad de mejorar el bienestar animal y la sostenibilidad de las prácticas agrícolas. 
- **Where:** Nos enfocaremos en todo el territorio nacional del Perú, especialmente en los departamentos donde se concentra la mayor parte del comercio y la actividad económica del país, y donde la crianza de cuyes es más prevalente
- **When:** Actualmente, el sector agropecuario se enfrenta a estos desafíos en la gestión de la crianza de cuyes. Con el crecimiento de la población en el país y la demanda de alimentos en aumento, se requiere una mayor eficiencia en la producción agrícola. Además, las preocupaciones ambientales y de bienestar animal están impulsando la necesidad de adoptar prácticas agrícolas más sostenibles y éticas.
- **Who:** AgroTech, como empresa líder en tecnología aplicada a la agricultura, asume la responsabilidad de liderar la innovación en la gestión de la crianza de cuyes. En este proceso, trabajamos en estrecha colaboración con expertos y asesores en la crianza de cuyes, quienes aportan su conocimiento especializado para desarrollar soluciones tecnológicas específicas y efectivas. Además, involucramos activamente a los criadores de cuyes, quienes son los beneficiarios directos de estas soluciones, asegurando que se adapten a sus necesidades y realidades específicas.
- **Why:** Para abordar estos desafíos y mejorar la gestión y productividad en la crianza de cuyes, garantizando el bienestar animal y promoviendo prácticas sostenibles en la industria agropecuaria. Además, se busca mejorar la rentabilidad de los agricultores y contribuir a la seguridad alimentaria peruana.
- **How:** Mediante el desarrollo de AgroCuy, una aplicación integral que combina asesoría especializada con herramientas IoT de automatización y monitoreo en tiempo real. Esta solución incluye: Sistemas de alimentación automatizada, con dispensadores controlados por horarios. Sensores ambientales IoT, que monitorean temperatura, humedad y gases como amoníaco y CO₂, garantizando un ambiente saludable. Sensores de calidad del agua, para asegurar una hidratación adecuada. Riego automatizado, que optimiza el uso de agua en función de las necesidades del entorno. Alertas y análisis predictivo, que permiten prevenir enfermedades y mejorar la toma de decisiones. Todo esto se controla desde dispositivos móviles o computadoras, permitiendo una gestión remota, inteligente y eficiente.
- **How much:** Se espera que AgroCuy tenga un impacto significativo en la optimización de las granjas de cuyes, elevando la productividad, reduciendo pérdidas por enfermedades y mejorando las condiciones de crianza. Esta innovación se alinea con los esfuerzos del Ministerio de Desarrollo Agrario y Riego (Midagri), que reportó un incremento del 20% en las crianzas de cuyes gracias a la adopción de nuevas tecnologías. Además, según datos del Midagri (2023), entre 2020 y 2021 se observó un crecimiento de 116 mil cuyes a nivel nacional, lo que evidencia una tendencia al alza en la producción. (Revisar [Anexo N°1: Gráfico de evolución de población de cuyes](#anexo-n1-gráfico-de-evolución-de-población-de-cuyes)). Nuestra aplicación busca responder a problemas comunes en el sector como la malnutrición, la falta de control sanitario y las malas condiciones ambientales, que afectan directamente la productividad de las granjas. (Revisar [Anexo N°2: Diagrama de problemas en la crianza de cuyes](#anexo-n2-diagrama-de-problemas-en-la-crianza-de-cuyes))

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

***Problem Statement 1***

|Nuestro producto tiene como objetivo mejorar la gestión de granjas de cuyes en el Perú mediante soluciones IoT.|
| - |
|Hemos observado que los criadores de cuyes en Perú enfrentan dificultades para gestionar eficientemente sus granjas, debido a la falta de herramientas tecnológicas que les permitan monitorear variables críticas como temperatura, humedad o niveles de alimentación en tiempo real. Esto impacta negativamente en su productividad y en el bienestar de los animales|
|¿Podría nuestra aplicación AgroCuy, equipada con sensores IoT y sistemas de automatización, ayudar a los criadores de cuyes a mejorar la gestión de sus granjas y aumentar su productividad?|


***Problem Statement 2***

|Nuestro producto tiene como objetivo aumentar la rentabilidad de los criadores de cuyes en Perú a través del uso de tecnologías IoT.|
| - |
|Hemos observado que muchos criadores enfrentan pérdidas económicas por el mal uso de recursos como agua o alimento, y por la falta de detección temprana de enfermedades en sus animales.|
|¿Podría AgroCuy, mediante el uso de sensores inteligentes y alertas en tiempo real, ayudar a reducir costos operativos y mejorar la eficiencia, contribuyendo así a una mayor rentabilidad?|


***Problem Statement 3***

|Nuestro producto tiene como objetivo facilitar el acceso a mercados y mejorar la comercialización de los productos de cuy en Perú, apoyándose en tecnología IoT.|
| - |
|Hemos observado que muchos criadores de cuyes tienen poca trazabilidad de sus procesos de producción, lo que limita la confianza de los compradores y reduce sus oportunidades en el mercado formal.|
|¿Podría AgroCuy, al recopilar datos automatizados sobre las condiciones de crianza mediante sensores IoT, generar reportes que validen la calidad del producto y así ayudar a los criadores a acceder a nuevos mercados y mejorar su comercialización?|


#### 1.2.2.2. Lean UX Assumptions.

1. **¿Quién es el usuario?** 

   El usuario principal de nuestro producto es el criador de cuyes en Perú, particularmente aquellos que buscan modernizar sus métodos de crianza mediante la adopción de tecnologías innovadoras como el Internet de las Cosas (IoT). También forman parte del ecosistema otros actores clave como los trabajadores de las granjas que interactúan con los dispositivos IoT, los compradores que valoran la trazabilidad del producto, y los consumidores finales interesados en alimentos producidos bajo estándares de bienestar animal y sostenibilidad.

1. **¿Dónde encaja nuestro producto en su trabajo o vida?**

   AgroCuy se integra directamente en las actividades diarias del criador de cuyes, permitiéndole gestionar su granja de forma remota y automatizada gracias al uso de sensores y dispositivos IoT. Estos sensores monitorean en tiempo real parámetros vitales como temperatura, humedad, calidad del agua, y niveles de alimentación, enviando alertas y recomendaciones a través de la aplicación. Así, AgroCuy se convierte en un aliado constante del criador, brindándole mayor control, eficiencia y tranquilidad.

1. **¿Qué problemas tiene nuestro producto? ¿Resolver?**

   Actualmente, el producto está enfocado únicamente en la crianza de cuyes y aún no está adaptado para otros tipos de ganado. Sin embargo, AgroCuy aborda de forma precisa varios problemas comunes en la crianza de cuyes:<br>
   - Falta de monitoreo en tiempo real.<br>
   - Ineficiente uso de recursos como agua y alimento.<br>
   - Dificultad en la detección temprana de enfermedades.<br>
   - Gestión manual de registros de salud y reproducción.<br>
   - Bajo acceso a mercados y falta de trazabilidad.<br>
   Gracias al uso de IoT, nuestro producto ofrece una solución tecnológica completa que automatiza la supervisión de las granjas, mejora el bienestar animal, optimiza los recursos y reduce el impacto ambiental, mejorando así la rentabilidad y sostenibilidad del negocio.

1. **¿Cuándo y cómo es nuestro producto? ¿Usado?** 

   AgroCuy será utilizado diariamente por los criadores de cuyes a través de sus dispositivos móviles o computadoras. Los sensores instalados en las granjas estarán en funcionamiento continuo, recolectando datos y enviándolos a la plataforma en tiempo real. De esta manera, el usuario podrá recibir notificaciones instantáneas, visualizar reportes gráficos, y tomar decisiones informadas en cualquier momento y desde cualquier lugar con conexión a internet.

1. **¿Qué características son importantes?**

   Monitoreo ambiental con IoT: Sensores que registran condiciones como temperatura, humedad, y calidad del agua, esenciales para la salud de los cuyes.

   Alertas inteligentes: Notificaciones automáticas en caso de condiciones anómalas o necesidades de intervención.

   Análisis predictivo: Algoritmos que, con base en los datos recolectados por sensores, brindan recomendaciones personalizadas para optimizar la nutrición, salud y reproducción de los cuyes.

   Gestión automatizada: Herramientas para registrar automáticamente eventos como alimentación, vacunación, o mortalidad, evitando el uso de formatos físicos.

   Conexión con mercados: Trazabilidad basada en datos, que mejora la confianza del consumidor y abre nuevas oportunidades comerciales.

1. **¿Cómo debe verse nuestro producto y cómo comportarse?**

   AgroCuy debe tener una interfaz intuitiva y adaptable a distintos niveles de alfabetización digital, con visualizaciones claras de los datos que recogen los sensores IoT. El diseño debe ser limpio, atractivo y centrado en la experiencia del usuario. El sistema debe comportarse de forma fluida, con actualizaciones en tiempo real, alertas precisas y navegación sencilla. Además, debe garantizar altos estándares de seguridad para proteger tanto los datos de los usuarios como la información recopilada por los sensores.

#### 1.2.2.3. Lean UX Hypothesis Statements.

**Hypothesis Statement 1**

|Creemos que al proporcionar a los criadores de cuyes en Perú acceso a tecnologías avanzadas de Internet de las Cosas (IoT) y asesoramiento especializado a través de nuestra plataforma AgroCuy, mejorarán la eficiencia y la rentabilidad de sus granjas al optimizar el monitoreo ambiental y la salud animal.|
| - |
|Sabremos que esto es cierto…|
|Cuando se aprecie un incremento del 20% en la cantidad de solicitudes de asesorías relacionadas con el uso de sensores IoT y sistemas automatizados de alimentación durante los primeros 6 meses de lanzamiento.|

**Hypothesis Statement 2**

|Creemos que al promover prácticas agrícolas sostenibles y éticas en la crianza de cuyes en Perú mediante el monitoreo constante de los recursos a través de IoT, los criadores adoptarán un enfoque más responsable con el medio ambiente y mejorarán la calidad de vida de los cuyes.|
| - |
|Sabremos que esto es cierto…|
|Cuando proporcionemos recursos específicos sobre prácticas sostenibles apoyadas por el análisis de datos en tiempo real proporcionados por los sensores IoT, y evaluemos la adopción de estas prácticas por parte de los criadores, viendo un aumento del 15% en la implementación de prácticas sostenibles en el uso de agua, alimentación automatizada y calidad del aire dentro de los primeros 6 meses de lanzamiento.|

**Hypothesis Statement 3**

|Creemos que al facilitar el acceso a mercados y mejorar la comercialización de los productos de cuy en Perú, mediante la trazabilidad y calidad certificada proporcionada por el monitoreo IoT, los criadores aumentarán sus ventas y expandirán sus negocios.|
| - |
|Sabremos que esto es cierto…|
|Cuando los datos de trazabilidad y calidad de los productos de cuy generados a través de los dispositivos IoT sean utilizados para establecer conexiones con compradores y mercados, y evaluemos el impacto en las ventas de los criadores mediante un aumento del 25% en las ventas en los primeros 6 meses de uso de la aplicación.|

**Hypothesis Statement 4**

|Creemos que al ofrecer soluciones IoT que mejoren la gestión diaria de las granjas, los criadores podrán monitorear en tiempo real el estado de sus operaciones y obtener asesorías más personalizadas, lo que les permitirá aumentar la productividad y eficiencia.|
| - |
|Sabremos que esto es cierto…|
|Cuando se observe un aumento del 20% en el número de criadores que implementan sistemas de monitoreo IoT, como sensores de temperatura, humedad y salud animal, dentro de los primeros tres meses tras el lanzamiento. Además, mediremos la retroalimentación de los usuarios mediante encuestas regulares, y consideraremos que hemos tenido éxito si al menos el 70% de las respuestas son positivas en relación con la experiencia de uso y la mejora en la gestión de la granja.|

#### 1.2.2.4. Lean UX Canvas.

![Lean Ux Canvas](img/leanuxcanvas.png)

_Imagen 2. Lean UX Canvas_

## 1.3. Segmentos objetivo

Por el lado de los asesores, hemos considerado que estos tendrán experiencia en el campo y/o estudios universitarios en carreras como ingeniería agrónoma, medicina veterinaria, zootecnia, etc. Debido a que el plan de estudios de estas carreras es de mínimo 5 años a más, y necesitan cierto grado de experiencia para dar recomendaciones y planes de acción confiables, hemos decidido que el rango de edad será de 25 años hasta 65 años.

Los asesores tendrán el conocimiento necesario para implementar y utilizar tecnologías avanzadas como sensores IoT, sistemas automatizados de alimentación y monitoreo de salud animal, así como plataformas de gestión de datos. Ellos proporcionarán a los criadores de cuyes las herramientas para analizar información en tiempo real y realizar recomendaciones basadas en datos IoT, mejorando la productividad y eficiencia de las granjas.

Según el Ministerio de Desarrollo Agrario y Riego (2023), la crianza de cuyes es una alternativa para la generación de ingresos monetarios para más de 800,000 familias agrarias en el Perú, las cuales se ubican en su mayoría en la sierra del país. El consumo de carne de cuy se ha mantenido en el tiempo e incluso ha trascendido al mercado externo. Esta información destaca la importancia de los asesores en la crianza de cuyes, ya que su conocimiento y orientación, apoyados por tecnologías como el IoT, pueden ser fundamentales para el éxito y la sostenibilidad de los productores en este sector.

|**Segmento objetivo**|Asesores |
| :- | :- |
|**Edad**|25-65 años|
|**Ubicación**|Perú|
|**Sexo**|Masculino y Femenino|
|**Formación educativa**|Universitario o cualquier educación superior|
|**Poder adquisitivo**|Bajo, medio y alto|
|**Tecnologia Utilizada**|Uso de plataformas IoT para monitoreo y análisis de datos, sensores inteligentes para salud animal y gestión eficiente de recursos, asesoramiento basado en datos recolectados en tiempo real.|

Para delimitar el segmento objetivo de criadores de cuyes, nos basamos en el diagnóstico situacional de la crianza de cuyes en Cajamarca realizado en julio de 2004. Dicho diagnóstico menciona que el 44.6% de los productores tenían más de 50 años, sus esposas que conducían la crianza de cuyes tenían entre 31 a 50 años. Además, los hijos que vivían con los padres tenían entre 6 a 17 años. Por lo tanto, para el rango de edad de los criadores decidimos seleccionar desde los 18 años de edad hasta los 60 años para abarcar tanto a los padres que manejan la crianza como a los hijos mayores de edad que la apoyan.

El mismo diagnóstico señala que el grado de instrucción predominante en la familia es de educación primaria con un 65.6%, lo cual tomaremos en cuenta.

Los criadores de cuyes estarán cada vez más dispuestos a integrar tecnologías avanzadas como el Internet de las Cosas (IoT) para optimizar la gestión de sus granjas. A través de sensores IoT, podrán monitorear en tiempo real aspectos como la calidad del agua, la temperatura y la humedad dentro de las instalaciones, lo que les permitirá hacer ajustes automáticos para mejorar el ambiente y el bienestar de los cuyes. Esto, junto con el uso de dispositivos para controlar la alimentación y otros parámetros, les dará herramientas efectivas para aumentar su eficiencia y rentabilidad.


|**Segmento objetivo**|Criadores de cuyes|
| :- | :- |
|**Edad**|18-60 años|
|**Ubicación**|Perú|
|**Sexo**|Masculino y Femenino|
|**Formación educativa**|Educación primaria|
|**Poder adquisitivo**|Bajo y medio|
|**Tecnologia Utilizada**|Sensores IoT para monitoreo ambiental (temperatura, humedad, calidad del aire), dispositivos automatizados para alimentación, control remoto de las operaciones y plataformas móviles para gestionar la granja de manera eficiente.|


## Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo
<table>
  <tr>
    <th colspan="6" valign="top">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4" valign="top">Objetivo 1: Adquirir conocimiento acerca de las propuestas ofrecidas por nuestros competidores y obtener enseñanzas a partir de las áreas en las que presentan limitaciones.<br>
    Objetivo 2: Identificar los puntos fuertes y las limitaciones de nuestros competidores con el fin de formular una estrategia competitiva sólida y efectiva.
    </td>
  </tr>
  <tr>
    <td colspan="2" rowspan="2" valign="top">Empresa/App</td>
    <td valign="top">AgroConnect </td>
    <td valign="top">BestFarm</td>
    <td valign="top">CattleMax</td>
    <td valign="top">BarnTools</td>
  </tr>
  <tr>
    <td valign="top"><img src="img/logo.png" alt="Logo AgroConnect" height="100px"></td>
    <td valign="top"><img src="img/bestfarm_logo.png" alt="Logo BestFarm" height="100px"></td>
    <td valign="top"><img src="img/cattlemax_logo.png" alt="Logo CattleMax" height="100px"></td>
    <td valign="top"><img src="img/barntool_logo.png" alt="Logo BarnTools" height="100px"></td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil</td>
    <td valign="top">Overview</td>
    <td valign="top">Una aplicación integral desarrollada por AgroTech para mejorar la gestión de granjas de cuyes en el Perú. Ofrece asesoramiento especializado y herramientas tecnológicas para optimizar la alimentación, salud y sostenibilidad en la crianza de cuyes, empoderando a los granjeros a través de la innovación tecnológica.</td>
    <td valign="top">Plataforma integral de gestión agrícola que abarca una amplia gama de actividades agrícolas, incluyendo cultivos y ganadería.</td>
    <td valign="top">Aplicación especializada en la gestión de ganado. Está diseñada específicamente para ayudar a los ganaderos a llevar un registro detallado de su ganado, gestionar la salud y el seguimiento de la reproducción.</td>
    <td valign="top">BarnTools es una aplicación que se centra en la gestión de animales de granja en general, incluyendo ganado, aves de corral y otros animales. </td>
  </tr>
  <tr>
    <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td valign="top">La ventaja competitiva de AgroConnect es la integración completa de tecnología y asesoramiento especializado. Esto significa que no solo proporcionamos herramientas tecnológicas avanzadas a través de AgroConnect, sino que también ofrecemos orientación y asesoramiento específico para la crianza de cuyes.</td>
    <td valign="top">La ventaja competitiva de BestFarm radica en su enfoque de la gestión agrícola, que permite a los usuarios gestionar tanto cultivos como animales en una sola plataforma.</td>
    <td valign="top">La principal ventaja competitiva de CattleMax es que ofrece características y herramientas específicas para el ganado, lo que lo convierte en una opción sólida para ganaderos que buscan una solución dedicada.</td>
    <td valign="top">La ventaja competitiva de BarnTools radica en su capacidad para gestionar una variedad de animales de granja, lo que la hace adecuada para granjeros con múltiple variedad de ganado.</td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil de Marketing</td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">El mercado objetivo de AgroConnect son los criadores de cuyes en Perú, así como otros actores involucrados en la cadena de producción y comercialización de productos cárnicos de cuy.</td>
    <td valign="top">El mercado objetivo de BestFarm incluye a agricultores y ganaderos que gestionan operaciones mixtas de cultivos y ganado.</td>
    <td valign="top">El mercado objetivo de CattleMax son los ganaderos y criadores de ganado de todas las escalas.</td>
    <td valign="top">El mercado objetivo de BarnTools son los granjeros y ganaderos que gestionan una variedad de animales</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Campañas educativas en línea y fuera de línea para resaltar los beneficios de AgroConnet en términos de mejora de la productividad, bienestar animal y sostenibilidad en la crianza de cuyes.</td>
    <td valign="top">Promoción en ferias agrícolas y ganaderas para mostrar la versatilidad de la plataforma.</td>
    <td valign="top">Colaboración con asociaciones ganaderas y veterinarios especializados en ganado.</td>
    <td valign="top">Publicidad en revistas agrícolas y ganaderas</td>
  </tr>
  <tr>
    <td rowspan="3" valign="top">Perfil de Producto</td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Plataforma integral de gestión para la crianza de cuyes. Ofreciendo una solución completa para la gestión eficiente de granjas de cuyes.</td>
    <td valign="top">Plataforma integral de gestión agrícola para cultivos y animales, planificación de cultivos, programación de tareas, seguimiento de salud, análisis de datos agrícolas</td>
    <td valign="top">Plataforma de gestión de ganado bovino, registro de animales, seguimiento de salud, programación de tareas, seguimiento de reproducción, gestión de gastos.</td>
    <td valign="top">Plataforma versátil para la gestión de animales de granja en general, registro de animales, seguimiento de salud, programación de tareas.</td>
  </tr>
  <tr>
    <td valign="top">Precios & Costos</td>
    <td valign="top">Modelo de suscripción mensual o anual. Los precios varían según la escala de la operación y las funcionalidades requeridas.</td>
    <td valign="top">BestFarm utiliza  precios basados en suscripción.</td>
    <td valign="top">CattleMax utiliza  precios basados en suscripción.</td>
    <td valign="top">BarnTools utiliza  precios basados en la suscripción.</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución (Web y/o Móvil)</td>
    <td valign="top">AgroConnect se distribuye principalmente a través de una plataforma web accesible desde cualquier navegador. También ofrece una aplicación móvil.</td>
    <td valign="top">BestFarm se distribuye a través de una plataforma web</td>
    <td valign="top">CattleMax se distribuye a través de una plataforma web y ofrece una aplicación móvil</td>
    <td valign="top">BarnTools se distribuye principalmente a través de una plataforma web accesible desde navegadores de computadoras de escritorio y dispositivos móviles.</td>
  </tr>
  <tr>
    <td rowspan="4" valign="top">Análisis SWOT</td>
    <td valign="top">Fortalezas</td>
    <td valign="top">- Integración completa de tecnología y asesoramiento especializado.<br>
    - Mejora del bienestar animal y la sostenibilidad en la crianza de cuyes.<br>
    - Plataforma integral que aborda múltiples aspectos de la gestión de granjas de cuyes.<br>
    - Potencial para expandirse hacia otros tipos de animales en el futuro.
    </td>
    <td valign="top">- Ofrece una plataforma integral para la gestión de cultivos y animales.<br>
    - Enfoque en la agricultura.<br>
    - Planificación y análisis de datos agrícolas.
    </td>
    <td valign="top">- Enfoque especializado en la gestión de ganado bovino.<br>
    - Herramientas específicas para ganado bovino.<br>
    - Plataforma web y aplicación móvil para mayor accesibilidad.
    </td>
    <td valign="top">- Versatilidad para gestionar una variedad de animales de granja.<br>
    - Registro de animales, seguimiento de salud y programación de tareas.<br>
    - Plataforma web y aplicación móvil para mayor accesibilidad.
    </td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">– Posible resistencia al cambio por parte de algunos criadores de cuyes.<br>
    - Costos de implementación y acceso a tecnología en áreas rurales o remotas.<br>
    - Necesidad de una curva de aprendizaje para algunos usuarios menos familiarizados con la tecnología.<br>
    - Dependencia de la conectividad a internet para el funcionamiento óptimo de la plataforma.
    </td>
    <td valign="top">- Competencia en nichos de mercado más específicos.<br>
    - Puede ser percibido como demasiado complejo para usuarios con necesidades simples.
    </td>
    <td valign="top">- Limitado en términos de diversificación de servicios para otros tipos de animales.</td>
    <td valign="top">- Mayor competencia en el mercado de gestión de animales de granja.</td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">- Creciente demanda de soluciones tecnológicas en el sector agrícola.<br>
    - Aumento de la conciencia sobre el bienestar animal y la sostenibilidad.<br>
    - Posibilidad de colaboraciones con instituciones gubernamentales y organizaciones agrícolas para promover el uso de tecnología en la crianza de cuyes.<br>
    - Expansión a nuevos mercados regionales o internacionales.
    </td>
    <td valign="top">- Expansión hacia mercados agrícolas más amplios.<br>
    - Colaboración con proveedores de tecnología agrícola.
    </td>
    <td valign="top">- Expansión hacia otros nichos de mercado ganadero.</td>
    <td valign="top">- Colaboración con proveedores de tecnología agrícola.</td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">- Competencia de otras soluciones tecnológicas en el mercado agrícola.<br>
    - Cambios en la regulación gubernamental que podrían afectar la industria de la crianza de cuyes.
    </td>
    <td valign="top">- Competidores especializados en áreas específicas de la agricultura</td>
    <td valign="top">- Cambios en las regulaciones ganaderas.</td>
    <td valign="top">- Competidores especializados en áreas específicas de la gestión de animales de granja.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores
**Estrategias:**

**Diferenciación del producto:** Destacaremos las características únicas de AgroConnect, como la integración completa de tecnología y asesoramiento especializado, para diferenciarnos claramente de otras soluciones en el mercado.

**Enfoque en el valor agregado:** Nos centraremos en comunicar y demostrar el valor agregado que AgroConnect ofrece a los criadores de cuyes, resaltando los beneficios tangibles como la mejora del bienestar animal, la eficiencia operativa y la sostenibilidad.


**Tácticas:**

**Marketing de contenido:** Crearemos contenido educativo y relevante sobre la crianza de cuyes, tecnología agrícola y prácticas sostenibles, para posicionarnos como líderes de pensamiento en el sector y atraer a clientes potenciales.

**Programas de prueba y demostraciones:** Ofreceremos programas de prueba gratuitos y demostraciones en granjas para permitir a los clientes experimentar directamente los beneficios de AgroConnect y generar confianza en nuestra solución.

**Desarrollo de alianzas estratégicas:** Buscaremos colaboraciones con instituciones agrícolas, asociaciones de criadores de cuyes y otras empresas del sector para ampliar nuestra red de clientes y aumentar la visibilidad de AgroConnect.

**Servicio al cliente excepcional:** Nos comprometemos a brindar un excelente servicio al cliente, proporcionando soporte técnico, capacitación y asistencia personalizada para garantizar la satisfacción y fidelidad de nuestros usuarios.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmento: Asesor**
1. ¿Cuál es su experiencia trabajando en granjas y cuántos años lleva en este campo? ¿Ha utilizado o está familiarizado con sistemas que permiten monitorear o controlar automáticamente las condiciones dentro de una granja?

2. En su trabajo actual, ¿qué tipo de ayuda o asesoramiento brinda a los criadores? ¿Qué aspectos considera más importantes a tener en cuenta en una granja de cuyes?

3. ¿Cuáles considera que son los problemas más comunes que enfrentan los nuevos criadores de cuyes? ¿Cómo podría ayudar una herramienta que muestre información actualizada sobre el ambiente de la granja?

4. ¿Qué tipo de alertas o funciones automáticas cree que serían más útiles para usted como asesor o para los criadores? Por ejemplo: avisos por temperatura alta, humedad baja, falta de alimento, o reportes automáticos.

5. ¿Ha tenido alguna experiencia previa con tecnologías aplicadas al campo, como sensores, termómetros digitales o sistemas automáticos? ¿Qué impresión le dejaron?

6. ¿Qué tipo de información del ambiente de la granja considera más valiosa para el cuidado de los cuyes? Por ejemplo: temperatura, humedad, ventilación, calidad del aire, entre otros.

7. ¿Cómo cree que podría beneficiarse su trabajo si tuviera acceso desde su celular o computadora a datos en tiempo real sobre varias granjas que asesora?

8. Pensando en una herramienta como “AgroConnect”, ¿qué funciones le parecerían más útiles? Por ejemplo: ver historial de datos, recibir alertas, comparar granjas o generar reportes automáticos.

9. ¿Cree que los criadores estarían dispuestos a utilizar una plataforma digital sencilla si les ayudara a tener mejores resultados? ¿Qué factores cree que facilitarían su adopción?

10. ¿Qué tipo de capacitación o acompañamiento considera necesario para que los criadores puedan aprovechar este tipo de herramientas tecnológicas en su día a día?


**Segmento: Criador de cuyes**

1. ¿Cuántos cuyes cría actualmente y desde hace cuánto tiempo se dedica a esta actividad? ¿Cría algún otro tipo de animal además de cuyes?

2. En su día a día, ¿cuáles son los principales problemas o dificultades que enfrenta al cuidar su granja? Por ejemplo: cambios de temperatura, falta de alimento, enfermedades, organización del tiempo, etc.

3. ¿Lleva algún tipo de registro sobre el estado de salud, crecimiento o producción de sus cuyes? ¿Utiliza cuadernos, Excel u otra herramienta?

4. ¿Cómo se organiza para alimentar a los animales, controlar su salud y mantener las instalaciones limpias? ¿Cree que una herramienta que le avise con alarmas o recordatorios podría ayudarle en estas tareas?

5. ¿Qué información consulta normalmente para tomar decisiones en su granja? Por ejemplo: pronóstico del clima, consejos de otros criadores, experiencia personal, etc.

6. Si existiera un sistema que le informe automáticamente sobre la temperatura, humedad o actividad de los animales, ¿le parecería útil? ¿Qué información le gustaría recibir y cómo preferiría verla: por celular, mensajes de texto, o de otro modo?

7. ¿Ha usado alguna vez una aplicación o herramienta digital para gestionar su granja? ¿Cómo fue esa experiencia?

8. ¿Qué tipo de información o apoyo adicional le gustaría tener para mejorar su crianza de cuyes? Por ejemplo: alertas automáticas, consejos personalizados, videos educativos, etc.

9. ¿Le interesaría recibir orientación o ayuda de otros criadores con más experiencia a través de una aplicación o grupo en línea? ¿Cree que esa ayuda sería más útil si se basara en datos reales de su granja?

10. ¿Estaría dispuesto a probar una herramienta tecnológica si fuera sencilla de usar, le ayudara a ahorrar tiempo y mejorara la salud de sus animales? ¿Qué condiciones o garantías necesitaría para animarse a probarla?

### 2.2.2. Registro de entrevistas

Puedes visualizar las entrevistas completas realizadas a asesores y criadores en el siguiente enlace:

🔗 **[Ver entrevistas grabadas – AgroCuy](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120430_upc_edu_pe/Ef3BzOMHxeBKpY029QWebTkBya2vl3KgeQLqDOw0BOHDDw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=eem7Mx)**  
*Repositorio audiovisual en SharePoint con los registros de las entrevistas de campo realizadas.*

#### **Entrevista N.º 1 – Asesor**

- **Entrevistador:** Sebastián Ramírez  
- **Entrevistado:** Arianna Joya  
- **Duración:** [00:00:00 – 00:05:41] (**5 minutos 41 segundos**)  

![Imagen 3. Entrevista a Arianna Joya](img/interview1.png)  
*Imagen 3. Entrevista a Arianna Joya*

**Resumen:**  
Arianna es una asesora rural con aproximadamente 10 años de experiencia en la crianza de cuyes. Si bien no ha trabajado con sensores ni sistemas automatizados en granjas, expresó un alto interés por conocer e implementar este tipo de tecnologías. Señaló como barrera la falta de conectividad en zonas rurales, destacando la importancia de soluciones que funcionen incluso sin internet. Recalcó la necesidad de capacitaciones presenciales, visitas técnicas y pruebas piloto para demostrar la efectividad del sistema a los criadores, así como contar con soporte técnico continuo para resolver dudas recurrentes.

---

#### **Entrevista N.º 2 – Asesor**

- **Entrevistador:** Juan Cuadros  
- **Entrevistado:** Daniela Flores  
- **Duración:** [00:05:41 – 00:11:33] (**5 minutos 52 segundos**)  

![Imagen 4. Entrevista a Daniela Flores](img/Entrevista_1.png)  
*Imagen 4. Entrevista a Daniela Flores*

**Resumen:**  
Daniela es médica veterinaria con más de ocho años de experiencia brindando asesoría técnica en granjas de cuyes. Su familia ha comenzado a usar termohigrómetros digitales para monitoreo ambiental, lo cual ha mejorado la gestión de sus animales. Considera que AgroConnect puede fortalecer la conexión entre criadores y asesores, y sugiere que el sistema genere reportes automáticos a partir de los datos recolectados para facilitar el análisis y la toma de decisiones.

---

#### **Entrevista N.º 3 – Asesor**

- **Entrevistador:** Nadia Lucas  
- **Entrevistado:** Nayeli Chávez  
- **Duración:** [00:11:33 – 00:18:35] (**7 minutos 2 segundos**)  

![Imagen 5. Entrevista a Nayeli Chávez](img/entrevista2.png)  
*Imagen 5. Entrevista a Nayeli Chávez*

**Resumen:**  
Nayeli, zootecnista egresada de la UNALM, tiene 2 años de experiencia como asesora de productores altoandinos. Ha investigado sistemas implementados en otros países como China, y destaca la necesidad urgente de monitoreo en tiempo real de temperatura, humedad y CO₂. Recomienda funciones como reportes automáticos, notificaciones ante incidentes y asistencia visual. También enfatiza que muchos criadores temen usar tecnología, por lo que la plataforma debe ser intuitiva, contar con capacitaciones prácticas y soporte continuo.

---

### Entrevistas a Criadores

---

#### **Entrevista N.º 4 – Criador**

- **Entrevistador:** Johan Moreno  
- **Entrevistado:** Willy Valentín  
- **Duración:** [00:18:35 – 00:22:55] (**4 minutos 20 segundos**)  

![Imagen 6. Entrevista a Willy Valentín](img/entrevista6.png)  
*Imagen 6. Entrevista a Willy Valentín*

**Resumen:**  
Willy, de 21 años, vive en Lima y su familia cría cuyes desde hace 4 años. Manejan 90 animales y registran datos manualmente en un cuaderno. Destacó la necesidad de conocer en tiempo real la temperatura y recibir alertas. Le interesa una herramienta que integre recomendaciones prácticas, tutoriales y conexión con otros criadores para compartir experiencias.

---

#### **Entrevista N.º 5 – Criador**

- **Entrevistador:** Fiorella Jarama  
- **Entrevistado:** Claudia Ramos  
- **Duración:** [00:22:55 – 00:27:40] (**4 minutos 45 segundos**)  

![Imagen 7. Entrevista a Claudia Ramos](img/Entrevista_4.png)  
*Imagen 7. Entrevista a Claudia Ramos*

**Resumen:**  
Claudia, de 23 años, es criadora principiante con 6 meses de experiencia y 25 cuyes. No lleva registros constantes y busca una herramienta sencilla con recordatorios, alertas, consejos personalizados y tutoriales. Aunque no ha usado aplicaciones, está abierta a probar una si es segura, intuitiva y cuenta con guía de uso.

---

#### **Entrevista N.º 6 – Criador**

- **Entrevistador:** Sebastián Ramírez  
- **Entrevistado:** Carla Pereyra  
- **Duración:** [00:27:40 – 00:31:08] (**3 minutos 28 segundos**)  

![Imagen 8. Entrevista a Carla Pereyra](img/entrevista5.png)  
*Imagen 8. Entrevista a Carla Pereyra*

**Resumen:**  
Carla es una criadora con experiencia a cargo de 20 cuyes. Actualmente gestiona su información de forma manual, pero le gustaría contar con alertas de temperatura y alimentación. Le interesa una aplicación que le ofrezca asesoría confiable, notificaciones y beneficios claros para mejorar el manejo de sus animales.

### 2.2.3. Análisis de entrevistas

### Desafíos Relacionados con la Monitorización y el Uso de Sensores

#### Desafíos Identificados por Asesores Técnicos

| Desafíos en la crianza                  | Daniela Flores | Nayeli Chavez | Otros Asesores |
|-----------------------------------------|----------------|----------------|----------------|
| Gestión de la alimentación              | X              | X              | X              |
| Mantenimiento de condiciones ambientales| X              | X              | X              |
| Control de enfermedades                 | X              | X              | X              |
| Falta de datos en tiempo real           | X              | X              | X              |
| Dificultad para adopción tecnológica    |                | X              | X              |
| Capacitación limitada para criadores    |                | X              | X              |


<img src="img/piechart_asesores.png" alt="% de Asesores que identifican desafíos relacionados con la monitorización" width="80%">

_Imagen 11. Gráfico circular - Desafíos de Asesores_

- **Análisis:** Los asesores consideran esencial contar con herramientas que automaticen la captura y análisis de datos ambientales, lo cual mejoraría significativamente el control sanitario y la eficiencia de las granjas. La adopción tecnológica debe ir acompañada de capacitaciones.

---

#### Desafíos Identificados por Criadores

| Desafíos en la crianza                  | Carla Pereyra  | Willy Valentin | Claudia Ramos |
|-----------------------------------------|----------------|----------------|----------------|
| Registro manual de datos                | X              | X              | X              |
| Falta de monitoreo ambiental            | X              | X              | X              |
| Dependencia del clima sin control       | X              | X              | X              |
| Falta de alertas para toma de decisiones| X              | X              | X              |
| Limitado acceso a asesoría técnica      | X              |                | X              |
| Falta de experiencia en manejo          |                |                | X              |
| Deseo de conectarse con otros criadores |                | X              | X              |



<img src="img/piechart_criadores.png" alt="% de Criadores que identifican desafíos relacionados con la monitorización" width="100%">

_Imagen 12. Gráfico circular - Desafíos de Criadores_

- **Análisis:** Los criadores identifican que la falta de información en tiempo real limita su capacidad de reaccionar ante problemas. Están abiertos a soluciones digitales, siempre que estas sean accesibles, intuitivas, y les ofrezcan beneficios claros como alertas y conexión con otros criadores.

---

### Conclusión Integrada

Los desafíos compartidos por asesores y criadores giran en torno a la **falta de datos en tiempo real**, el **control ambiental insuficiente**, y la **necesidad de asistencia técnica** basada en información confiable. La implementación de sensores y plataformas de monitoreo es vista como una solución clave para **mejorar la toma de decisiones** y **reducir la incertidumbre** en la gestión diaria de las granjas de cuyes.

Esta información refuerza la propuesta de AgroConnect como una herramienta capaz de **automatizar el monitoreo**, **emitir alertas**, y **facilitar la colaboración** entre criadores y asesores, promoviendo una **crianza más eficiente y tecnológica**.


## 2.3. Needfinding

### 2.3.1. User Personas

Para la realización de las fichas de User Personas se han considerado los 2 segmentos objetivos: asesores y criadores de cuyes. Se elaborarán las fichas con la información recopilada de las entrevistas sobre su perfil.

**Segmento Asesor**

<img src="img/persona_asesor.png" alt="Persona Asesor">

_Imagen 14. User Persona - Asesor_

**Segmento Criador**

<img src="img/persona_criador.png" alt="Persona Criador">

_Imagen 15. User Persona - Criador_

### 2.3.2. User Task Matrix

<table>
  <tr>
    <th rowspan="2" valign="top"><b>Task Matrix</b></th>
    <th colspan="2" valign="top"><b>Asesores</b></th>
    <th colspan="2" valign="top"><b>Criadores</b></th>
  </tr>
  <tr>
    <td valign="top"><b>Frecuencia</b></td>
    <td valign="top"><b>Importancia</b></td>
    <td valign="top"><b>Frecuencia</b></td>
    <td valign="top"><b>Importancia</b></td>
  </tr>
  <tr>
    <td>Alimentar a los cuyes</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Diaria</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Proporcionar agua limpia</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Diaria</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Limpiar jaulas</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Semanal</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Comprar suministros y alimentos</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Mensual</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Vender cuyes</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Mensual</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar gastos y ganancias</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Mensual</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear la salud y el bienestar de los cuyes</td>
    <td>Mensual</td>
    <td>Alta</td>
    <td>Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Investigar sobre nuevas prácticas y tecnologías para la crianza de cuyes</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Casi Nunca</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Realizar seguimiento y evaluación de progreso de granjas</td>
    <td>Semanal</td>
    <td>Alta</td>
    <td>Semanal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Participar de sesiones de asesoramiento para recibir información actualizada</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Mensual</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Resolver problemas específicos en las granjas</td>
    <td>Según necesidad</td>
    <td>Muy Alta</td>
    <td>Según necesidad</td>
    <td>Muy Alta</td>
  </tr>
  <tr>
    <td>Desarrollar y/o asistir a sesiones de capacitación sobre técnicas de crianza</td>
    <td>A veces</td>
    <td>Alta</td>
    <td>A veces</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Elaborar y/o leer informes de progreso con recomendaciones</td>
    <td>Trimestral</td>
    <td>Alta</td>
    <td>Trimestral</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Evaluar las condiciones y necesidades de las granjas de forma presencial</td>
    <td>Casi nunca</td>
    <td>Alta</td>
    <td>Diaria</td>
    <td>Media</td>
  </tr>
</table>

<br>
A partir del User Task Matrix, resaltaremos las tareas de mayor trascendencia. Entre ellas tenemos ‘monitorear la salud y bienestar de los cuyes’ ya que los criadores están pendientes constantemente de la salud de los cuyes viendo comportamientos inusuales y posibles enfermedades para comunicárselo a los asesores quienes otorgarían consejos sobre el accionar ante una posible enfermedad o comportamiento inusual. Esta tarea es fundamental para que haya una producción exitosa y sin contratiempos.

Asimismo, la tarea de ‘realizar seguimiento y evaluación de progreso de granjas’ es fundamental por el mismo motivo porque permite una mejora continua en el rendimiento de las granjas.

Por otro lado, las principales diferencias entre ambos segmentos radican en las actividades diarias dentro del criadero ya que solo participan los criadores para asegurarse de la salud y crecimiento de los cuyes. Por lo tanto, los criadores están monitoreando constantemente las condiciones de sus granjas, mientras que los asesores tienen que separar una fecha para realizar esto de forma presencial.

Finalmente, la principal coincidencia encontrada es que tanto los asesores como los criadores deben estar preparados para solucionar problemas específicos cuando estos aparezcan.


### 2.3.3. User Journey Mapping

Para el segmento de los asesores especializados, se ha considerado desde el momento en que reciben una solicitud de servicio por parte de un criador de cuyes hasta el seguimiento de los avances con respecto a los cambios planteados.
Por otro lado, para el segmento de criadores de cuyes se tomó en cuenta desde la búsqueda inicial de información y contactos de asesores hasta la implementación de nuevos conocimientos y el análisis de resultados obtenidos.

**Segmento Asesor**

<img src="img/journeymap_asesor.png" alt="Journey Map Asesor">

_Imagen 16. User Journey Map - Asesor_

**Segmento Criador**

<img src="img/journeymap_criador.png" alt="Journey Map Criador">

_Imagen 17. User Journey Map - Criador_

### 2.3.4. Empathy Mapping

En esta sección, se desarrollaron los Empathy Maps de cada segmento objetivo. Se utilizó una plantilla de EXPressia que contiene los apartados que debe tener el Empathy Map junto a preguntas que se respondieron conforme a lo identificado de nuestro segmento objetivo para desarrollar este artefacto.

**Segmento Asesor**

<img src="img/empathymap_asesor.png" alt="Empathy Map Asesor">

_Imagen 18. Empathy Map - Asesor_

**Segmento Criador**

<img src="img/empathymap_criador.png" alt="Empathy Map Criador">

_Imagen 19. Empathy Map - Criador_

### 2.3.5. As-is Scenario Mapping.

**Segmento: Asesor**

|**Phases**|**Búsqueda de de trabajo**|**Publicar su experiencia en el rubro** |**Comunicación con el ganadero**|**Asesorar al ganadero**|
| :- | :- | :- | :- | :- |
|**Doing**|- Busca la manera de llegar a más público, creándose  foros de difusión, cuentas de instagram,etc.Para que así más personas adquieran sus servicios.|- Habiendo creado su perfil, empieza a publicar información acerca de él, la experiencia que tiene en el campo, el rubro con el que se especializa, entre otros datos relevantes que ayuden a captar el interés del cliente.|-Se comunica con el ganadero mediante whatsapp, instagram o en llamadas cortas explicando los beneficios de su servicio.|- Mediante whatsapp y luego de haber llegado a un acuerdo se reúne con el ganador para poder asesorar en lo que necesita|
|**Thinking**|- "Necesito que me contraten para poder generar ingresos."|- "Espero que la información que publique interese a los clientes."|- "Es importante comunicarse con la persona, sin embargo no llegó a comprender que exactamente desea."|- "El asesoramiento que brinda al ganadero ha sido no tan eficiente pero sí eficaz."|
|**Feeling**|<p>-Estresado por no saber donde debo posicionarme para poder buscar trabajo. </p><p>- Decepcionado por no conocer una página o aplicación que me brinde la facilidad de conectar con mis clientes.</p>|<p>- Preocupado sobre qué dirán las personas al ver lo que ofrezco.</p><p>- Tímido al publicar mi información en mi feed.</p>|<p>- Satisfecho por haber conseguido un cliente dispuesto a contratarme.</p><p>- Confundido porque el cliente no detalla bien qué servicio  desea  de mí.</p>|<p>- Satisfecho de haber culminado mi asesoramiento continuo al cliente.</p><p></p><p>-Frustrado por el tiempo que me demore en asesorar debido a la gran cantidad de herramientas que he usado.</p>|

**Segmento: Criador**

|**Phases**|**Búsqueda de Información y Asesoramiento**|**Comunicación con el Asesor** |**Registro de Datos y Asesoramiento**|**Uso Continuo**|
| :- | :- | :- | :- | :- |
|**Doing**|- Busca información sobre la crianza de cuyes en línea y en libros especializados.|- Contacta a un asesor a través de la aplicación para obtener asesoramiento sobre la crianza de su ganado de cuyes.|<p>- Proporciona detalles sobre su ganado de cuyes, como la cantidad, la salud, la alimentación y otros aspectos relevantes, al asesor. </p><p>- Recibe asesoramiento y recomendaciones del asesor.</p>|- Mantiene una comunicación regular con el asesor para recibir orientación continua sobre la crianza de su ganado de cuyes.|
|**Thinking**|- "Necesito encontrar información precisa y útil para mejorar la crianza de mi ganado de cuyes."|- "Espero que el asesor tenga el conocimiento necesario para ayudarme."|- "Es importante proporcionar datos precisos para recibir un asesoramiento efectivo."|- "La relación continua con el asesor es clave para el éxito de mi ganado de cuyes."|
|**Feeling**|<p>- Motivado por mejorar la salud y la productividad de su ganado de cuyes.</p><p>`- Interesado en aprender más sobre la crianza de cuyes</p>|<p>- Optimista sobre la posibilidad de recibir asesoramiento valioso del asesor.</p><p>- Satisfecho al establecer una comunicación efectiva.</p>|<p>- Satisfecho por recibir recomendaciones que benefician a su ganado de cuyes. </p><p>- Responsable de seguir las recomendaciones del asesor.</p>|<p>- Satisfecho con la relación continua con el asesor. </p><p>- Comprometido con mejorar su ganadería de cuyes a largo plazo.</p>|

## 2.4. Ubiquitous Language.

En esta sección, se definirán términos utilizados a lo largo del proyecto para que se pueda comprender para todos los miembros del equipo y agentes interesados. 

- **Guinea pig breeder** (Criador de cuyes): Persona dedicada a la crianza y producción de cuyes con el fin de obtener carne y otros productos derivados de estos animales.
- **Ganadero** (Rancher): Individuo dedicado a la crianza de animales. En este contexto, es otra forma de llamar a los criadores de cuyes, pero de forma más general. Los ganaderos son responsables del cuidado diario de los cuyes, incluida la alimentación, el manejo del hábitat y la reproducción.
- **Advisor** (Asesor): En el contexto del proyecto, es una persona con experiencia y conocimientos especializados en la crianza de cuyes y prácticas agrícolas relacionadas. Su papel es brindar apoyo personalizado para resolver desafíos específicos que enfrentan los criadores en el cuidado de los cuyes.
- **Guinea pig farm** (Granja de cuyes): Instalación destinada a la cría y manejo de cuyes, equipada con las infraestructuras necesarias para su cuidado y reproducción.
- **Animal welfare** (Bienestar animal): Estado de salud física y psicológica de los cuyes que garantiza su crecimiento óptimo, garantizado mediante prácticas de crianza adecuadas que respetan sus necesidades naturales.
- **Sustainable agricultural practices** (Prácticas agrícolas sostenibles): Técnicas y métodos de producción que preservan los recursos naturales y minimizan el impacto ambiental negativo, contribuyendo a la conservación a largo plazo del medio ambiente y los ecosistemas.

- **Self-sustainable** (Auto-sustentable): En el contexto de la crianza de cuyes, se refiere a la práctica de consumir los cuyes criados en la granja principalmente para satisfacer las necesidades alimenticias de los criadores y sus familias. En lugar de venderlos para generar ingresos adicionales.

- **Shed** (Galpón): Es el ambiente donde se construyen o colocan las pozas o jaulas para criar a los cuyes, lo que permite un mejor control de los animales.

- **Cage** (Jaula): Espacio donde vive un grupo de cuyes normalmente construidos de madera o mallas metálicas.

- **Resources** (Recursos): Elementos físicos necesarios para la crianza de cuyes como el alimento que consumen los cuyes, la medicina para los cuyes enfermos, o recursos de producción como pueden ser las pieles de los cuyes.

- **Expenses** (Gastos): Inversiones de dinero del criador para cubrir las necesidades de la crianza como puede ser la compra de los alimentos de los cuyes.

- **Review** (Reseña): Evaluación del desempeño de un asesor durante una cita. Consta de calificación (con rango de 0 a 5 estrellas) y de un comentario opcional.

- **Appointment** (Cita): Encuentro programado entre el criador y el asesor con el objetivo de recibir asistencia técnica en desafíos en la crianza, y con el objetivo de recibir recomendaciones.

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping  
**Segmento: Asesor**  
<br>

| **Phases** | **Registro y personalización del perfil** | **Revisión del estado de la granja** | **Comunicación con el criador** | **Asesoramiento remoto** |
| :- | :- | :- | :- | :- |
| **Doing** | - Ingreso a la app “AgroCuy” y me registro como asesor especializado.<br>- Personalizo mi perfil con experiencia, especialidades y horarios disponibles para asesorías. | - Accedo al dashboard del criador para revisar en tiempo real el estado del agua, temperatura, humedad y dispensadores de comida en cada jaula.<br>- Verifico alertas activas generadas por el sistema de monitoreo. | - Recibo una solicitud de asesoría del criador junto a las alertas y el estado de su granja.<br>- Le escribo dentro de la misma app para coordinar una videollamada. | - Realizo la videollamada programada directamente desde AgroCuy.<br>- Le doy recomendaciones con base en los datos que observé previamente.<br>- Sugiero acciones para mejorar la crianza según lo monitoreado. |
| **Thinking** | "Qué útil que pueda mostrar mi experiencia desde el inicio." | "Puedo tener una visión clara de lo que pasa en la granja sin estar presente." | "Todo lo que necesito para comunicarme con el criador está en la misma app." | "El monitoreo en tiempo real me permite dar asesorías más precisas y útiles." |
| **Feeling** | <p>- Seguro de que los criadores verán mi perfil y querrán contactarme.</p><p>- Orgulloso de mostrar mis logros en el área.</p> | <p>- Confiado por poder detectar problemas sin tener que estar físicamente en la granja.</p><p>- Tranquilo gracias a los datos que ya están organizados.</p> | <p>- Cómodo porque la app me facilita la coordinación.</p><p>- Satisfecho al ver que el criador puede explicarme su situación con datos.</p> | <p>- Orgulloso de brindar soluciones efectivas desde cualquier lugar.</p><p>- Inspirado al ver cómo la tecnología mejora mi labor como asesor.</p> |

## 3.1. To-Be Scenario Mapping  
**Segmento: Criadores**  
<br>

| **Phases** | **Instalación y Configuración Inicial** | **Monitoreo del estado de la granja** | **Consulta con el asesor** | **Seguimiento continuo** |
| :- | :- | :- | :- | :- |
| **Doing** | - Instalo la app “AgroCuy” y configuro los sensores en cada jaula.<br>- Registro las jaulas, cuyes por jaula, tipo de alimentación y horarios de dispensadores. | - Reviso en tiempo real desde la app el estado del agua, temperatura y comida de cada jaula.<br>- Recibo alertas si falta agua, está contaminada o si hay condiciones fuera del rango ideal. | - Solicito asesoría con un técnico disponible desde la sección de “Consultas”.<br>- Envío automáticamente los datos recolectados por los sensores al asesor. | - Aplico las recomendaciones dadas por el asesor.<br>- Continúo revisando el estado diario de mi granja desde la app.<br>- Reprogramo videollamadas si vuelven a surgir alertas. |
| **Thinking** | "Qué útil que la app me ayude desde el inicio a organizar mis jaulas y sensores." | "Es genial ver todo el estado de mi granja desde el celular, sin tener que estar entrando a cada jaula." | "Puedo obtener ayuda personalizada y rápida gracias a que el asesor ve lo mismo que yo." | "Con esta app puedo llevar un control constante y profesional sin ser un experto." |
| **Feeling** | <p>- Motivado al ver que puedo automatizar partes importantes de mi granja.</p><p>- Seguro al configurar sensores correctamente.</p> | <p>- Tranquilo al ver que todo está bajo control o cuando se me alerta a tiempo.</p><p>- Confiado en que tengo visibilidad de lo que pasa con mis cuyes.</p> | <p>- Satisfecho de poder contactar a un asesor y recibir consejos sin salir de casa.</p><p>- Agradecido por el soporte que tengo en tiempo real.</p> | <p>- Comprometido a seguir mejorando mi crianza.</p><p>- Contento de ver resultados positivos gracias al monitoreo y el acompañamiento técnico.</p> |


## 3.2. User Stories

Se identificaron las siguientes épicas que se componen de las historias de usuario, ahora con foco en el monitoreo de la granja de cuyes.

<table> <tr><th><b>Epic ID</b></th><th><b>Epic</b></th><th><b>User story ID</b></th><th><b>User stories</b></th></tr> <tr><td rowspan="10"><b>E01</b></td><td rowspan="10">Sistema de búsqueda y programación de citas con asesores y calificaciones</td><td>US01</td><td>Visualización del catálogo de asesores</td></tr> <tr><td>US02</td><td>Visualización de información de un asesor</td></tr> <tr><td>US03</td><td>Visualización de horarios de asesores</td></tr> <tr><td>US04</td><td>Programación de citas con asesores</td></tr> <tr><td>US05</td><td>Visualización de información del criador de cuyes</td></tr> <tr><td>US06</td><td>Notificación de citas al asesor</td></tr> <tr><td>US07</td><td>Notificación de citas al criador</td></tr> <tr><td>US08</td><td>Calificación al asesor luego de una cita</td></tr> <tr><td>US14</td><td>Separación de fechas disponibles para asesoría</td></tr> <tr><td>US31</td><td>Visualización de calendario</td></tr><tr><td rowspan="2"><b>E02</b></td><td rowspan="2">Publicaciones en la aplicación</td><td>US09</td><td>Gestión de publicaciones de asesores</td></tr> <tr><td>US10</td><td>Visualización de publicaciones de los asesores</td></tr><tr><td rowspan="3"><b>E03</b></td><td rowspan="3">Sistema integral de registro y seguimiento animal</td><td>US11</td><td>Gestión de jaulas de cuyes</td></tr> <tr><td>US12</td><td>Registro de información de animales</td></tr> <tr><td>US13</td><td>Visualización y edición de información de animales</td></tr> <tr><td rowspan="2"><b>E04</b></td><td rowspan="2">Gestión de granja</td><td>US15</td><td>Gestión de recursos de la granja</td></tr> <tr><td>US16</td><td>Gestión de gastos realizados</td></tr> <tr><td rowspan="2"><b>E05</b></td><td rowspan="2">Eficiencia y seguridad de aplicación</td><td>US17</td><td>Seguridad de información</td></tr> <tr><td>US18</td><td>Disponibilidad y confiabilidad</td></tr> <tr><td rowspan="3"><b>E06</b></td><td rowspan="3">Registro, acceso a la aplicación y datos personales</td><td>US19</td><td>Registro de un usuario nuevo</td></tr> <tr><td>US20</td><td>Inicio de sesión</td></tr> <tr><td>US21</td><td>Recuperación de contraseña</td></tr> <tr><td rowspan="6"><b>E07</b></td><td rowspan="6">Visualización de una Landing Page estática</td><td>US22</td><td>Visualización de Navbar y Footer</td></tr> <tr><td>US23</td><td>Visualización de sección de inicio</td></tr> <tr><td>US24</td><td>Visualización de sección “Acerca De”</td></tr> <tr><td>US25</td><td>Visualización de sección “Sobre Nosotros”</td></tr> <tr><td>US26</td><td>Visualización de sección “Características”</td></tr> <tr><td>US27</td><td>Visualización de sección “Contacto”</td></tr> <tr><td rowspan="7"><b>E08</b></td><td rowspan="7">Funcionalidades con APIs</td><td>US28</td><td>Uso de un API para videollamadas</td></tr> <tr><td>US29</td><td>Uso de un API para alojar imágenes</td></tr> <tr><td>US32</td><td>Uso de nuestra API para gestionar usuarios</td></tr> <tr><td>US33</td><td>Uso de nuestra API para manejar recursos y gastos</td></tr> <tr><td>US34</td><td>Uso de nuestra API para manejar la reserva de citas entre asesores y criadores</td></tr> <tr><td>US35</td><td>Uso de nuestra API para manejar las jaulas y animales</td></tr> <tr><td>US36</td><td>Integración con API para monitorear sensores de granja (IoT)</td></tr> <tr><td rowspan="7"><b>E09</b></td><td rowspan="7">Monitoreo inteligente mediante IoT</td><td>US37</td><td>Recepción de alertas cuando los parámetros ambientales (temperatura, humedad, CO₂, agua) exceden los rangos aceptables.</td></tr> <tr><td>US38</td><td>Visualización de gráficas históricas de parámetros ambientales para análisis de comportamiento.</td></tr> <tr><td>US39</td><td>Configuración personalizada por el criador de los rangos aceptables de temperatura, humedad, nivel de CO₂ y estado del agua.</td></tr><tr><td>US40</td><td>Detección automática de agua en mal estado o escasez, con alertas para el criador.</td></tr> <tr><td>US41</td><td>Activación y programación de dispensación automática de alimento en horarios establecidos.</td></tr>
<tr><td>US42</td><td>Alerta de necesidad de limpieza cuando se detecta un nivel alto de CO₂ o condiciones desfavorables.</td></tr> </table>

|**Epic / Story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Relacionado con (Epic ID)**|
| :- | :- | :- | :- | :- |
|US01|Visualización del catálogo de asesores|**Como** criador de cuyes **quiero** explorar un catálogo de asesores **para** conocer quiénes me pueden apoyar con asesorías|<p>**Escenario 1: Explorar catálogo de asesores**</p><p>**Given** el criador quiere explorar el catálogo de asesores.</p><p>**And** se encuentra en el apartado de “Asesores”.</p><p>**When** seleccione el botón “Catálogo de asesores”.</p><p>**Then** el sistema le mostrará una lista de todos los asesores disponibles en la aplicación.</p><p></p><p>**Escenario 2: Filtrar búsqueda de asesores**</p><p>**Given** el criador quiere personalizar su búsqueda.</p><p>**And** se encuentra en el apartado de “Asesores”.</p><p>**When** seleccione el botón de filtros.</p><p>**Then** el sistema** le permitirá filtrar el catálogo de asesores por ubicación, experiencia o reputación.</p><p></p><p>**Escenario 3: Ver mis asesores**</p><p>**Given** el criador desea ver los asesores a los que les solicitó un servicio para recibir una mentoría.</p><p>**And** se encuentra en el apartado de “Asesores”.</p><p>**When** haga clic en el botón “Mis Asesores”</p><p>**Then** el sistema le mostrará una lista de todos los asesores a los que ha solicitado una cita.</p>|E01|
|US02|Visualización de información de un asesor|**Como** criador de cuyes **quiero** ver la información de un asesor **para** tomar una decisión informada antes de separar una cita|<p>**Escenario 1: Ver información de un asesor** </p><p>**Given** el criador quiere ver información de un asesor.</p><p>**And se** encuentra en el apartado de “Asesores”.</p><p>**When** seleccione al cuadro de un asesor.</p><p>**Then** el sistema le mostrará la información del asesor como nombre, experiencia, calificación y reseñas.</p><p></p><p>**Escenario 2: Fallar al visualizar la información del asesor**</p><p>**Given** el criador quiere ver información relevante del asesor.</p><p>**And se** encuentra en el apartado de “Asesores”</p><p>**When** seleccione al cuadro de un asesor.</p><p>**And** se encuentre con un error al cargar la información.</p><p>**Then** el sistema le mostrará un mensaje de error de carga.</p>|E01|
|US03|Visualización de horarios de asesores|**Como** criador de cuyes **quiero** ver los horarios disponibles de los asesores **para** seleccionar un horario que se ajuste a mi agenda.|<p>**Escenario 1: Visualizar horarios disponibles**</p><p>**Given** el criador desea visualizar los horarios disponibles de un asesor elegido.</p><p>**And** se encuentra viendo la información del perfil de un asesor.</p><p>**When** haga clic en el botón “Reservar Cita”</p><p>**Then** el sistema le mostrará una interfaz con los horarios disponibles del asesor</p><p></p><p>**Escenario 2: Fallar al intentar visualizar horarios.**</p><p>**Given** el criador desea visualizar los horarios disponibles del asesor elegido.</p><p>**And** se encuentra viendo la información del perfil de un asesor.</p><p>**When** haga clic en el botón “Reservar Cita”</p><p>**And** el asesor no tenga horarios disponibles</p><p>**Then** el sistema le mostrará un mensaje de error “El asesor no tiene horarios disponibles”.</p>|E01|
|US04|Programación de citas con asesores|**Como** criador de cuyes **quiero** programar una cita con un asesor **para** recibir orientación personalizada sobre la crianza de cuyes|<p>**Escenario 1: Programar cita**</p><p>**Given** el criador desea programar una cita.</p><p>**And** se encuentra en el apartado de “Horarios Disponibles” del perfil de un asesor.</p><p>**When** seleccione un horario disponible</p><p>**And** complete los campos solicitados.</p><p>**And** haga clic en el botón “Reservar Cita”</p><p>**Then** el sistema le mostrará un mensaje de confirmación.</p><p></p><p>**Escenario 2: Fallar al programar cita**</p><p>**Given** el criador desea programar una cita.</p><p>**And** se encuentra en el apartado de “Horarios Disponibles” del perfil de un asesor.</p><p>**When** seleccione un horario disponible</p><p>**And** se encuentra un error técnico o de conexión que impide completar la programación.</p><p>**Then** el sistema le mostrará un mensaje de error sugiriendo contactar con soporte.</p>|E01|
|US05|Visualización de información del criador de cuyes|**Como** asesor **quiero** tener información de la granja del criador de cuyes **para** planificar los temas de la asesoría|<p>**Escenario 1: Ver información del criador**</p><p>**Given** el asesor desea ver información del criador de cuyes con el que tendrá una asesoría</p><p>**And** se encuentra en la sección de “Mis Citas” .</p><p>**And** observa que tiene una cita programada con un criador.</p><p>**When** haga clic en la card de la cita.</p><p>**Then** el sistema le permitirá ver información de la granja del criador como número de jaulas y número de cuyes, como también información del criador como nombre, edad y localización.</p><p></p><p>**Escenario 2: Fallar al acceder a la información del criador**</p><p>**Given** el asesor desea ver información del criador de cuyes con el que tendrá una asesoría</p><p>**And** se encuentra en la sección de “Mis Citas” .</p><p>**And** observa que tiene una cita programada con un criador.</p><p>**When** haga clic en la card de la cita.</p><p>**And** se encuentre con un error al cargar la información.</p><p>**Then** el sistema le mostrará un mensaje de error indicando que hubo un error de carga.</p>|E01|
|US06|Notificación de citas al asesor|**Como** asesor**, quiero** recibir notificaciones de citas programadas por los criadores **para** mantenerme al tanto de mis ofertas laborales.|<p>**Escenario 1: Ver notificaciones de cita programadas por criadores**</p><p>**Given** el asesor desea ver sus notificaciones de citas programadas.</p><p>**When** se encuentre en el apartado de “Notificaciones”</p><p>**Then** el sistema le mostrará un mensaje que describe brevemente la solicitud.</p><p></p><p>**Scenario 2: Aceptar notificación de cita programada con el criador**</p><p>**Given** que el asesor decide cerrar la notificación para liberar espacio y permitir la visualización de otras notificaciones.</p><p>**And** se encuentra en la sección de "Notificaciones" del sistema.</p><p>**When** haga clic en el botón "Aceptar" dentro de la notificación correspondiente a la cita programada con el criador.</p><p>**Then** el sistema eliminará la notificación de la lista.</p>|E03|
|US07|Notificación de citas al criador|**Como** criador de cuyes **quiero** recibir notificaciones referentes al estado de mis citas **para** mantenerme al tanto de las asesorías que he solicitado.|<p>**Escenario 1: Ver notificaciones de cita programadas con los asesores**</p><p>**Given** el criador desea ver sus notificaciones de citas programadas.</p><p>**When** se encuentre en el apartado de “Notificaciones”</p><p>**Then** el sistema le mostrará un mensaje que describe brevemente la solicitud.</p><p></p><p>**Scenario 2: Aceptar notificación de cita programada con el asesor**</p><p>**Given** que el criador decide cerrar la notificación para liberar espacio y permitir la visualización de otras notificaciones.</p><p>**And** se encuentra en la sección de "Notificaciones" del sistema.</p><p>**When** haga clic en el botón "Aceptar" dentro de la notificación correspondiente a la cita programada con el asesor.</p><p>**Then** el sistema eliminará la notificación de la lista de notificaciones.</p><p></p>|E01|
|US08|Calificación del asesor luego de una cita|**Como** criador de cuyes **quiero** calificar al asesor luego de la consulta **para** ayudar a otros criadores a tomar una decisión informada antes de separar una cita.|<p>**Escenario 1: Calificar al asesor**</p><p>**Given** el criador desea hacer un feedback referente al servicio del asesor.</p><p>**And** se encuentra en la vista de calificación del servicio.</p><p>**When** haga clic en el botón “Calificar Servicio”</p><p>**Then** el sistema le permitirá asignarle un número de estrellas y reseñar el servicio del asesor.</p><p></p><p>**Escenario 2: Omitir Calificación**</p><p>**Given** el criador no desea dar feedback al asesor referente al servicio.</p><p>**And** se encuentra en la vista de calificación del servicio.</p><p>**When** haga clic en el botón “Omitir calificación”</p><p>**Then** el sistema le permitirá omitir la reseña.</p>|E01|
|US09|Gestión de publicaciones de asesores|**Como** asesor **quiero** hacer publicaciones referentes a mis trabajos **para** que los criadores tengan más confianza en mí.|<p>**Escenario 1: Crear una nueva publicación**</p><p>**Given** el asesor desea crear una publicación.</p><p>**And** está en el apartado de "Mis Publicaciones".</p><p>**When** hace clic en el botón "Crear Publicación" de la Sidebar.</p><p>**Then** se le redirige a un formulario donde puede ingresar el contenido de su nueva publicación.</p><p>**And** después de completar el contenido, hace clic en el botón "Publicar".</p><p>**Then** el sistema le mostrará un mensaje de confirmación.</p><p></p><p>**Escenario 2: Editar una publicación existente**</p><p>**Given** el asesor desea editar una publicación existente.</p><p>**And** está en el apartado de "Mis Publicaciones" de la Sidebar.</p><p>**And** tiene una publicación previamente creada.</p><p>**When** selecciona la opción de editar en la publicación que desea modificar.</p><p>**Then** se le redirige al formulario de edición donde puede modificar el contenido de la publicación.</p><p>**And** después de realizar los cambios deseados, hace clic en el botón "Guardar Cambios".</p><p>**Then** el sistema le mostrará un mensaje de confirmación y los cambios se reflejan en la publicación actualizada.</p><p></p><p>**Escenario 3: Eliminar una publicación existente**</p><p>**Given** el asesor desea eliminar una publicación existente.</p><p>**And** está en el apartado de "Mis Publicaciones" de la Sidebar.</p><p>**And** tiene una publicación previamente creada.</p><p>**When** selecciona la opción de eliminar en la publicación que desea borrar.</p><p>**Then** el sistema le mostrará un mensaje de confirmación solicitando la confirmación de la eliminación.</p><p>**And** después de confirmar, la publicación se elimina de su perfil y ya no está disponible para los criadores.</p>|E02|
|US10|Visualización de publicaciones de los asesores|**Como** criador de cuyes **quiero** poder ver las publicaciones de la comunidad de asesores **para** obtener información útil y, si es necesario, solicitar asesoramiento en base a esas publicaciones.|<p>**Escenario 1: Visualizar publicaciones de asesores**</p><p>**Given** el criador desea ver las publicaciones de la comunidad</p><p>**When** haga clic en el botón “Publicaciones” de la Sidebar.</p><p>**Then** el sistema le mostrará una lista de las últimas publicaciones de la comunidad de asesores.</p>|E02|
|US11|Gestión de jaulas de cuyes|**Como** criador de cuyes **quiero** poder registrar una jaula en la plataforma **para** poder almacenar y gestionar mis cuyes de manera efectiva, garantizando su seguridad y bienestar.|<p>**Escenario 1: Registro exitoso de la jaula**</p><p>**Given** que el criador desea registrar su galón.</p><p>**And** se encuentra en el apartado "Mis Animales".</p><p>**When** haga clic en el botón "Registrar Jaula".</p><p>**And** completa el formulario con la información requerida de la jaula.</p><p>**And** hace clic en el botón "Registrar".</p><p>**Then** el sistema le mostrará un mensaje del registro exitoso de la jaula.</p><p></p><p>**Escenario 2: Eliminar jaula**</p><p>**Given** que el criador desea eliminar su galón.</p><p>**And** se encuentra en el apartado "Mis Animales".</p><p>**When** haga clic en el botón "Borrar" de la jaula deseada.</p><p>**Then** el sistema le mostrará un mensaje de confirmación solicitando la confirmación de la eliminación.</p><p>**And** después de confirmar, la jaula se elimina.</p>|E03|
|US12|Registro de información de animales|**Como** criador de cuyes **quiero** contar con un sistema de registro de animales **para** almacenar información básica sobre cada animal, incluyendo su número de identificación, nombre, raza, género, peso y fecha de nacimiento.|<p>**Escenario 1: Registrar un nuevo animal**</p><p>**Given** el criador desea registrar un cuy en su galpón.</p><p>**And** se encuentra en la jaula deseada</p><p>**When** haga clic en el botón ”Nuevo cuy”</p><p>**And** ingresa la información básica del animal, incluyendo su número de identificación, número de galpón, raza, género y fecha de nacimiento.</p><p>**And** haga clic “Registrar”</p><p>**Then** el sistema le mostrará una confirmación del registro.</p><p></p><p>**Escenario 2: Fallar en el registro de animal**</p><p>**Given** el criador desea registrar un cuy en su galpón.</p><p>**And** se encuentra en la jaula deseada</p><p>**When** haga clic en el botón ”Nuevo cuy”</p><p>**And i**ntenta ingresar la información del animal pero deja en blanco algunos campos obligatorios para el registro**.**</p><p>**And** haga clic “Registrar”.</p><p>**Then** el sistema le mostrará un mensaje de error.</p>|E03|
|US13|Visualización y edición de información de animales|**Como** criador de cuyes **quiero** acceder a la información de un animal **para** visualizar o actualizar su información registrada.|<p>**Escenario 1: Visualizar la información de un animal registrado**</p><p>**Given** el criador tiene varios cuyes registrados en la aplicación y desea visualizar la información de uno en específico.</p><p>**And** se encuentra en el apartado de “Mis Animales”</p><p>**When** haga clic en “Ver” de una jaula</p><p>**And** seleccione el card de un cuy  específico.</p><p>**Then** el sistema le mostrará la información detallada del cuy.</p><p></p><p>**Escenario 2: Actualizar información de un animal registrado**</p><p></p><p>**Given** el criador tiene varios cuyes registrados en la aplicación y desea editar la información de uno en específico.</p><p>**And** se encuentra viendo la información detallada de un cuy </p><p>**When** haga clic en “Editar”</p><p>**And** realiza cambios en la información del cuy.</p><p>**Then** el sistema actualizará la información detallada del cuy.</p><p></p>|E03|
|US14|Separación de fechas disponibles para asesoría|**Como** asesor, **quiero** poder seleccionar y separar las fechas y horas en las que estoy disponible para ofrecer asesorías **para** que los usuarios interesados puedan ver mis horarios disponibles y agendar una cita en un momento conveniente.|<p>**Escenario 1: Registrar disponibilidad para asesorías**</p><p>**Given** el asesor desea registrar sus fechas y horas disponibles para asesorías.</p><p>**And**  está visualizando la página de "Horario disponible"</p><p>**When** haga clic en el botón “Registrar nueva fecha”</p><p>**And**  complete los datos del nuevo horario disponible que tiene el asesor</p><p>**Then** el sistema actualizará y guardará las fechas y horas seleccionadas como disponibles.</p><p></p><p>**Escenario 2: Eliminar horario de disponibilidad para asesorías**</p><p>**Given** el asesor desea eliminar un horario de disponibilidad para asesorías</p><p>**And** está visualizando la página de "Horario disponible"</p><p>**When** haga clic en el botón “Eliminar” junto al horario que desea eliminar</p><p>**And** confirme la eliminación del horario</p><p>**Then** el sistema actualizará y eliminará el horario de disponibilidad seleccionado</p><p></p>|E01|
|US15|Gestión de recursos de la granja|**Como** criador de cuyes **quiero** registrar el inventario de mi granja **para** tener un control sobre los recursos esenciales como alimentos y medicamentos.|<p>**Escenario 1: Registrar de nuevo ingreso de recursos en el inventario**</p><p>**Given** el criador ha recibido el pedido de recursos por parte del proveedor y desea registrar esto en su inventario.</p><p>**And** se encuentra en el apartado de “Mi Granja” de la Sidebar.</p><p>**And** ingresa a la sección de “Gestión de Recursos” del apartado de “Mi Granja”.</p><p>**When** haga clic en el botón “Nuevo Recurso”</p><p>**And** ingresa los detalles de nombre y tipo de recurso, fecha, cantidad y observación.</p><p>**Then** el sistema mostrará una confirmación.</p><p></p><p>**Escenario 2: Ver recursos**</p><p>**Given** el criador desea ver los recursos que posee.</p><p>**And** se encuentra en el apartado de “Mi Granja” de la Sidebar.</p><p>**When** haga clic en el botón “Gestión de Recursos”.</p><p>**Then** el sistema le permitirá visualizar sus recursos que incluyen datos como el nombre del recurso, el tipo de recurso (alimento, medicina, cultivo u otro) y la fecha en el que fue registrado este recurso.</p><p></p><p>**Escenario 2: Filtrar recursos**</p><p>**Given** el creador desea ver un recurso de un tipo en específico.</p><p>**And** se encuentra en la sección de “Gestión de Recursos”del apartado de “Mi Granja”.</p><p>**When** seleccione el tipo de recurso que sea filtrar (todos, alimento, medicina, cultivo)</p><p>**And** haga clic en el botón “Filtrar”</p><p>**Then** el sistema le mostrará una lista de todos los recursos que pertenezcan a ese tipo.</p><p></p><p>**Escenario 3: Editar recurso**</p><p></p><p>**Escenario 4: Eliminar recurso**</p>|E04|
|US16|Gestión de gastos realizados|**Como** criador de cuyes **quiero** registrar gastos relacionados con mi negocio **para** tener un control y poder tomar decisiones financieras que serán útiles para tener una mejor rentabilidad.|<p>**Escenario 1: Registrar gasto**</p><p>**Given** el criador desea registrar los gastos que ha realizado.</p><p>**And** se encuentra en el apartado de “Mi Granja” de la Sidebar.</p><p>**And** ingresa a la sección de “Gestión de Gastos”del apartado de “Mi Granja”.</p><p>**When** haga clic en el botón “Nuevo Gasto”</p><p>**And** ingrese datos como el precio, tipo de gasto, fecha y demás campos.</p><p>**Then** el sistema registrará correctamente los detalles del gasto.</p><p></p><p>**Escenario 2: Ver gasto registrado**</p><p>**Given** el criador desea ver un gasto ya registrado.</p><p>**And** se encuentra en el apartado de “Mi Granja” de la Sidebar.</p><p>**When** haga clic en el botón “Gestión de gastos”</p><p>**Then** el sistema le permitirá visualizar sus gastos.</p><p></p><p>**Escenario 3: Filtrar gasto**</p><p>**Given** el criador desea ver un recurso de un tipo en específico.</p><p>**And** se encuentra en la sección de “Gestión de Gastos”del apartado de “Mi Granja”.</p><p>**When** seleccione el tipo de gasto que desea filtrar (todos, salud, alimento, Mantenimiento de criadero)</p><p>**And** haga clic en el botón “Filtrar”</p><p>**Then** el sistema le mostrará una lista de todos los recursos que pertenezcan a ese tipo.</p><p></p><p>**Escenario 3: Editar gasto**</p><p></p><p>**Escenario 4: Eliminar gasto**</p>|E04|
|US17|Seguridad de información|**Como** usuario **quiero** que la aplicación cumpla con los estándares de seguridad **para** proteger mi información registrada.|<p>**Escenario 1: Registro de un nuevo usuario con verificación de seguridad (sign-up)**</p><p>**Dado que** el usuario desea registrarse</p><p>**Cuando** el sistema recibe una solicitud POST con los datos del nuevo usuario a la API</p><p>**Entonces** se registrará el nuevo usuario</p><p>**Y** brindará respuesta a la petición realizada</p><p>**Escenario 2: Inicio de sesión del usuario con verificación de seguridad exitoso (sign-in)**</p><p>**Dado** que el usuario desea iniciar sesión de forma segura</p><p>**Cuando** el sistema recibe una solicitud POST con las credenciales de inicio de sesión del usuario (correo electrónico y contraseña) a la API</p><p>**Entonces** se verificarán las credenciales</p><p>**Y** la API responde con un código de estado 200 y el token de autenticación válido</p><p>**Escenario 3: Inicio de sesión del usuario con verificación de seguridad fallido (sign-in)**</p><p>**Dado** que el usuario desea iniciar sesión de forma segura</p><p>**Cuando** el sistema recibe una solicitud POST con las credenciales de inicio de sesión del usuario (correo electrónico y contraseña) a la API</p><p>**Entonces** se verificarán las credenciales</p><p>**Y** la API responde con un código de estado 400 indicando que no se encontró un usuario con las credenciales ingresadas</p>|E05|
|US18|Disponibilidad y confiabilidad|**Como** usuario **quiero** que la aplicación esté disponible siempre **para** acceder a ella en cualquier momento y sin interrupciones.|<p>**Escenario 1: Acceso a la aplicación en todo momento**</p><p>**Given** el usuario desea usar la aplicación en cualquier instante.</p><p>**When** ingrese a la aplicación.</p><p>**Then** la aplicación se encuentra disponible y funcional.</p><p></p><p>**Escenario 2: Acceso a la aplicación sin interrupciones**</p><p>**Given** el usuario desea usar la aplicación en cualquier instante.</p><p>**When** ingresa a la aplicación.</p><p>**Then** la aplicación carga rápidamente y controla el tráfico para que la experiencia sea fluida.</p>|E05|
|US19|Registro de un usuario nuevo|**Como** usuario **quiero** registrarme **para** acceder a las funciones de usuario.|<p>**Escenario 1: Registro de cuenta por formulario**</p><p>**Given** el usuario desea registrarse en la aplicación.</p><p>**And** se encuentra en el apartado de “Registrarse”.</p><p>**When** complete el formulario de registro con su información personal.</p><p>**And** seleccione su rol en la aplicación entre “Criador” o “Asesor”</p><p>**And** los datos** sean correctos según las validaciones establecidas.</p><p>**Then** la cuenta se creará.</p><p></p><p>**Escenario 2: Registro incorrecto de cuenta**</p><p>**Given** el usuario se encuentra en el apartado de “Registrarse”.</p><p>**When** ingrese los datos solicitados de manera errónea.</p><p>**Then** la cuenta no se creará.</p><p>**And** recibirá un mensaje indicando el error.</p>|E06|
|US20|Inicio de sesión|**Como** usuario **quiero** acceder a mi cuenta registrada **para** acceder a las funciones de usuario.|<p>**Escenario 1: Inicio de sesión exitoso**</p><p>**Given** el usuario desea acceder a su cuenta registrada. </p><p>**And** se encuentra en el apartado de “Iniciar Sesión”.</p><p>**When** introduzca sus credenciales correctamente.</p><p>**Then** será redireccionado a su vista de usuario.</p><p></p><p>**Escenario 2: Inicio de sesión fallido**</p><p>**Given** el usuario desea acceder a su cuenta registrada. </p><p>**And** se encuentra en el apartado de “Iniciar Sesión”.</p><p>**When** introduzca sus credenciales incorrectamente.</p><p>**Then** no se le permitirá acceso a su cuenta.</p><p>**And** recibirá un mensaje indicando el error.</p><p></p><p>**Escenario 3: Bloqueo de sesión por exceso de intentos**</p><p>**Given** el usuario desea acceder a su cuenta registrada. </p><p>**And** se encuentra en el apartado de “Iniciar sesión”.</p><p>**When** introduzca sus credenciales incorrectamente.</p><p>**And** siga errando hasta alcanzar el número máximo de intentos permitidos (tres intentos).</p><p>**Then** recibirá un mensaje que le informe que ha excedido el número de intentos permitidos.</p><p>**And** su cuenta será bloqueada temporalmente.</p>|E06|
|US21|Recuperación de contraseña|**Como** usuario **quiero** poder recuperar mi contraseña **para** acceder a mi cuenta.|<p>**Escenario 1: Recuperación de contraseña**</p><p>**Given** el usuario olvidó su contraseña</p><p>**When** se dirija a la sección de “Inicio de sesión”</p><p>**And** seleccione “olvidé mi contraseña”</p><p>**And** coloque su correo vinculado a la cuenta.</p><p></p><p>**Then** se le enviará un correo para que cambie su contraseña.</p>|E06|
|US22|Visualización de Navbar y Footer|**Como** potencial usuario **quiero** navegar con facilidad **para** movilizarme a través de la página y conocer sobre la aplicación.|<p>**Escenario 1: Visualización de Navbar y Footer**</p><p>**Given** el usuario desea conocer sobre la aplicación.</p><p>**When** ingresa al Landing Page,</p><p>**Then** se mostrará el Navbar y Footer que permitirá al usuario navegar con facilidad.</p>|E07|
|US23|Visualización de sección de inicio|**Como** potencial usuario **quiero** acceder a una página de inicio **para** conocer la idea principal de la aplicación y ver un diseño agradable.|<p>**Escenario 1: Visualización de página de inicio**</p><p>**Given** el usuario desea conocer sobre la aplicación.</p><p>**When** ingresa al Landing Page.</p><p>**Then** se mostrará la página inicial sencilla que da a entender la idea principal.</p>|E07|
|US24|Visualización de sección “Acerca De”|**Como** potencial usuario **quiero** acceder a una página sobre el problema que resuelve **para** conocer el propósito de la aplicación.|<p>**Escenario 1: Visualización de página Acerca De**</p><p>**Given** el usuario desea conocer sobre el problema que resuelve la aplicación</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Acerca De</p><p>**Then** se mostrará la página Acerca De, en la que se detalla la problemática que resolverá la aplicación.</p>|E07|
|US25|Visualización de sección “Sobre Nosotros”|**Como** potencial usuario **quiero** acceder a una página sobre la startup **para** conocer el propósito de la empresa detrás de la aplicación.|<p>**Escenario 1: Visualización de página Sobre Nosotros**</p><p>**Given** el usuario desea conocer sobre la empresa detrás de la aplicación.</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Sobre Nosotros</p><p>**Then** se mostrará la página Sobre Nosotros, en la que detalla información sobre la startup, su misión y visión.</p>|E07|
|US26|Visualización de sección “Características”|**Como** potencial usuario **quiero** acceder a una página sobre las características **para** conocer las principales funcionalidades de la aplicación.|<p>**Escenario 1: Visualización de página Características**</p><p>**Given** el usuario desea conocer sobre las características de la aplicación</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Características</p><p>**Then** se mostrará la página Características en la que detalla información sobre las funcionalidades principales que ofrece la aplicación.</p>|E07|
|US27|Visualización de sección “Contacto”|**Como** potencial usuario **quiero** acceder a una página de contacto **para** poder contactar con la empresa en caso tenga algún problema, duda o sugerencia.|<p>**Escenario 1: Visualización de página Contacto**</p><p>**Given** el usuario desea contactar con el área de soporte de la empresa</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Contacto</p><p>**Then** se mostrará la página Contacto, en la que se muestra los medios de contacto que puede usar el usuario para hacer consultas.</p>|E07|
|US28|Uso de un API para videollamadas|**Como** desarrollador **quiero** integrar la creación de videollamadas utilizando la API de Jitsi Meet **para** facilitar las asesorías en la aplicación**	|<p>**Escenario 1: Creación de videollamada**</p><p>**Given** el usuario tiene una asesoría pendiente</p><p>**When** seleccione la opción de ingresar a la asesoría</p><p>**Then** el sistema lo redireccionará a un enlace con la videollamada de Google Meet para que el usuario acceda a su asesoría</p><p></p>|E08|
|US29|Uso de un API para alojar imágenes|**Como** desarrollador **quiero** integrar la API de almacenamiento de Firebase **para** que los usuarios puedan subir y visualizar sus imágenes de foto de perfil y publicaciones.|<p>**Escenario 1: Subir imágenes**</p><p>**Given** el usuario desea subir una imagen en nuestra plataforma</p><p>**When** se reciba la imagen en el formato compatible</p><p>**Then** el sistema sube la imagen usando la API del almacenamiento de Firebase para generar el enlace de visualización</p><p></p>|E08|
|US31|Visualización de calendario|**Como** usuario **quiero** visualizar un calendario **para** ver de forma agradable y ordenada las asesorías programadas que tengo.|<p>**Escenario 1: Visualizar calendario como criador**</p><p>**Given** el criador ha separado una o más asesorías</p><p>**When** ingrese a la sección Calendario del Sidebar</p><p>**Then** se mostrará un calendario que muestra las citas programadas con los asesores en las fechas correspondientes</p><p></p><p>**Escenario 2: Visualizar calendario como asesor**</p><p>**Given** el asesor tiene programada una o más asesorías</p><p>**When** ingrese a la sección Calendario del Sidebar</p><p>**Then** se mostrará un calendario que muestra las citas programadas con los criadores en las fechas correspondientes</p>|E01|
|US32|Uso de nuestra API para gestionar usuarios|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de los usuarios en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.|<p>**Escenario 1: Integrar un API para manejar las solicitudes HTTP de los usuarios y notificaciones**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración.</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST o PUT con los datos solicitados del usuario o notificación a la API.</p><p>**Then** La API responde con un código de estado correspondiente (200 OK o 201 Created)</p><p>**And** se realiza la operación solicitada.</p><p>**Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de usuarios y notificaciones**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados del usuario o notificación a la API</p><p>**And** ocurre un error.</p><p>**Then** la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).</p><p>**And** el sistema proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.</p>|E08|
|US33|Uso de nuestra API para gestionar publicaciones|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de las publicaciones de asesores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.|<p>**Escenario 1: Integrar un API para manejar las solicitudes HTTP de las publicaciones**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración.</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST o DELETE con los datos solicitados de la publicación a la API.</p><p>**Then** La API responde con un código de estado correspondiente (200 OK o 201 Created) y se realiza la operación solicitada.</p><p>**Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de publicaciones**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST o DELETE con los datos solicitados de la publicación a la API y ocurre un error.</p><p>**Then** la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).</p><p>**And** el sistema captura el error y proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.</p>|E08|
|US34|Uso de nuestra API para manejar recursos y gastos|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de los recursos y gastos de los criadores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.|<p>**Escenario 1: Integrar un API para manejar las solicitudes HTTP de los recursos o gastos**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración.</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados del recurso o gasto a la API.</p><p>**Then** La API responde con un código de estado correspondiente (200 OK o 201 Created)  y se realiza la operación solicitada.</p><p>**Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de recursos o gastos**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados del recurso o gasto a la API y ocurre un error.</p><p>**Then** la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).</p><p>**And** el sistema captura el error y proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.</p>|E08|
|US35|Uso de nuestra API para manejar la reserva de citas entre asesores y criadores|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de las citas entre asesores y criadores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.|<p>**Escenario 1: Integrar un API para manejar las solicitudes HTTP de las citas y horarios disponibles de asesores**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración.</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados de una cita entre un asesor y un criador a la API.</p><p>**Then** La API responde con un código de estado correspondiente (200 OK o 201 Created)  y se realiza la operación solicitada.</p><p>**Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de citas y horarios disponibles de asesores**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados de de una cita entre un asesor y un criador a la API y ocurre un error.</p><p>**Then** la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).</p><p>**And** el sistema captura el error y proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.</p>|E08|
|US36|Uso de nuestra API para manejar las jaulas y animales|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de las jaulas y los animales de los criadores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.|<p>**Escenario 1: Integrar un API para manejar las solicitudes HTTP de las jaulas o animales**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados de la jaula o animal a la API.</p><p>**Then** La API responde con un código de estado correspondiente (200 OK o 201 Created)  y se realiza la operación solicitada.</p><p>**Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de jaulas o animales**</p><p>**Given** el desarrollador tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración</p><p>**When** el desarrollador envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados de la jaula o animal a la API y ocurre un error.</p><p>**Then** la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).</p><p>**And** el sistema captura el error y proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.</p>|E08| 
|US37|Integración con API para monitorear sensores de granja (IoT)|**Como** desarrollador **quiero** conectar sensores IoT mediante una API **para** monitorear en tiempo real los parámetros ambientales dentro de la granja.|<p>**Escenario 1: Integración exitosa con sensores IoT**</p><p>**Given** el desarrollador tiene acceso a la API y los sensores IoT están correctamente instalados.</p><p>**When** se realiza una solicitud GET para obtener los datos de los sensores.</p><p>**Then** el sistema muestra la información en tiempo real de temperatura, humedad, CO₂ y estado del agua.</p><p>**Escenario 2: Fallo en la conexión con sensores IoT**</p><p>**Given** los sensores IoT están desconectados o mal configurados.</p><p>**When** el sistema intenta conectarse a la API de sensores.</p><p>**Then** se muestra un mensaje de error indicando que no se pueden recuperar los datos y se sugiere verificar la conexión.</p>|E09|
|US38|Recepción de alertas cuando los parámetros ambientales (temperatura, humedad, CO₂, agua) exceden los rangos aceptables|**Como** criador **quiero** recibir alertas automáticas **para** saber cuándo los parámetros ambientales están fuera de los rangos normales.|<p>**Escenario 1: Parámetro excede el rango**</p><p>**Given** los sensores están midiendo parámetros ambientales en tiempo real.</p><p>**When** un valor supera el límite configurado.</p><p>**Then** se genera una alerta visual y sonora en el sistema y se envía una notificación al criador.</p>|E09|
|US39|Visualización de gráficas históricas de parámetros ambientales para análisis de comportamiento|**Como** criador **quiero** ver gráficas históricas **para** analizar el comportamiento ambiental y tomar mejores decisiones.|<p>**Escenario 1: Acceso a datos históricos**</p><p>**Given** hay datos almacenados sobre los parámetros de la granja.</p><p>**When** el criador accede al módulo de gráficas.</p><p>**Then** se muestran líneas de tiempo con valores de temperatura, humedad, CO₂ y agua por fecha y hora.</p>|E09|
|US40|Configuración personalizada por el criador de los rangos aceptables de temperatura, humedad, nivel de CO₂ y estado del agua|**Como** criador **quiero** personalizar los valores de los rangos aceptables **para** que las alertas se ajusten a las necesidades de mi granja.|<p>**Escenario 1: Configuración de rangos**</p><p>**Given** el criador accede a la sección de configuración.</p><p>**When** el criador introduce nuevos valores límite para los parámetros.</p><p>**Then** el sistema guarda la configuración y la utiliza para generar futuras alertas.</p>|E09|
|US41|Detección automática de agua en mal estado o escasez, con alertas para el criador|**Como** criador **quiero** que el sistema detecte cuando el agua está en mal estado o hay escasez **para** recibir una alerta inmediata.|<p>**Escenario 1: Detección de agua en mal estado**</p><p>**Given** hay sensores que monitorean la calidad del agua.</p><p>**When** se detecta un valor anormal.</p><p>**Then** se genera una alerta que indica el problema y se sugiere una acción.</p>|E09|
|US42|Activación y programación de dispensación automática de alimento en horarios establecidos|**Como** criador **quiero** programar horarios automáticos de dispensación de alimento **para** asegurar que los animales coman a tiempo sin intervención manual.|<p>**Escenario 1: Programación de horarios**</p><p>**Given** el criador configura los horarios desde la interfaz.</p><p>**When** se alcanza la hora programada.</p><p>**Then** se activa automáticamente el dispensador y se registra la acción.</p>|E09|
|US43|Alerta de necesidad de limpieza cuando se detecta un nivel alto de CO₂ o condiciones desfavorables|**Como** criador **quiero** recibir alertas de limpieza **para** mantener un ambiente saludable cuando los niveles de CO₂ u otras condiciones lo indiquen.|<p>**Escenario 1: Activación de alerta de limpieza**</p><p>**Given** el sistema monitorea niveles de CO₂ en tiempo real.</p><p>**When** se supera el umbral de CO₂ permitido.</p><p>**Then** se emite una alerta que sugiere realizar una limpieza del espacio afectado.</p>|E09|

## 3.3. Impact Mapping

Este mapa de impacto permite visualizar cómo las funcionalidades del sistema contribuyen a los objetivos del criador y asesor, conectando necesidades clave con acciones del sistema y entregables concretos. A continuación, se presentan los distintos segmentos del mapa clasificados por área funcional.

**Segmento: Criador**

<img src="img/impact-map-criador.png" alt="ImpactMap Criador">
 
 _Imagen 20. impact map - criador_

 **Segmento: Asesor**

<img src="img/impact-map-asesor.png" alt="ImpactMap Asesor">
 
 _Imagen 21. impact map - asesor_

## 3.4. Product Backlog

Para trabajar el Product Backlog, se utilizó la herramienta Trello, la cual se encuentra en el siguiente enlace:

🔗 [Ver tablero en Trello](https://trello.com/b/J5cnOwWT/product-backlog)

<img src="img/product backlog - agrocuy.PNG" alt="Product Backlog">
 
 _Imagen 22. Product Backlog_

|**# Orden**|**User Story Id**|**Título**|**Descripción**|**Story Points (1/2/3/5/8)**|
| :- | :- | :- | :- | :- |
|1|US22|Visualización de Navbar y Footer|**Como** potencial usuario **quiero** navegar con facilidad **para** movilizarme a través de la página y conocer sobre la aplicación.|2|
|2|US23|Visualización de sección de inicio|**Como** potencial usuario **quiero** acceder a una página de inicio **para** conocer la idea principal de la aplicación y ver un diseño agradable.|1|
|3|US24|Visualización de sección “Acerca De”|**Como** potencial usuario **quiero** acceder a una página sobre el problema que resuelve **para** conocer el propósito de la aplicación.|2|
|4|US25|Visualización de sección “Sobre Nosotros”|**Como** potencial usuario **quiere** acceder a una página sobre la startup **para** conocer el propósito de la empresa detrás de la aplicación.|2|
|5|US26|Visualización de sección “Características”|**Como** potencial usuario **quiero** acceder a una página sobre las características **para** conocer las principales funcionalidades de la aplicación.|2|
|6|US27|Visualización de sección “Contacto”|**Como** potencial usuario **quiero** acceder a una página de contacto **para** poder contactar con la empresa en caso tenga algún problema, duda o sugerencia.|2|
|7|US32|Uso de nuestra API para gestionar usuarios|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de los usuarios en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP. |5|
|8|US33|Uso de nuestra API para manejar recursos y gastos|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de los recursos y gastos de criadores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP. |5|
|9|US34|Uso de nuestra API para gestionar publicaciones|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de las publicaciones de asesores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP. |5|
|10|US35|Uso de nuestra API para manejar la reserva de citas entre asesores y criadores|**Como** desarrollador **quiero** integrar un API **para** gestionar la información de las citas entre asesores y criadores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP. |5|
|11|US29|Uso de un API para alojar imágenes|**Como** desarrollador **quiero** integrar la API de almacenamiento de Firebase **para** que los usuarios puedan subir y visualizar sus imágenes de foto de perfil y publicaciones.|5|
|12|US36|Uso de la API para manejar las jaulas y animales|**Como** desarrollador **quiero** conectar sensores IoT mediante una API **para** monitorear en tiempo real los parámetros ambientales dentro de la granja.|5|
|13|US28|Uso de un API para videollamadas|**Como** desarrollador **quiero** integrar la creación de videollamadas utilizando la API de Jitsi Meet **para** facilitar las asesorías en la aplicación.|5|
|14|37| Integración con API para monitorear sensores de granja (IoT)|**Como** desarrollador **quiero** integrar la API de almacenamiento de Firebase **para** que los usuarios puedan subir y visualizar sus imágenes de foto de perfil y publicaciones.|5|
|15|US01|Visualización del catálogo de asesores|**Como** criador de cuyes **quiero** explorar el catálogo de asesores **para** conocer quiénes me pueden apoyar con asesorías.|5|
|16|US02|Visualización de información de un asesor|**Como** criador de cuyes **quiero** tener acceso a la información de un asesor **para** tomar una decisión informada antes de separar una cita.|3|
|17|US03|Visualización de horarios de asesores|**Como** criador de cuyes **quiero** ver los horarios disponibles de los asesores **para** seleccionar un horario que se ajuste a mi agenda.|3|
|18|US04|Programación de citas con asesores|**Como** criador de cuyes **quiero** poder programar una cita con un asesor **para** recibir orientación personalizada|8|
|19|US05|Visualización de información del criador de cuyes|**Como** asesor **quiero** tener tener información de la granja del criador de cuyes **para** planificar los temas de la asesoría.|5|
|20|US06|Notificación de citas al asesor|**Como** asesor, **quiero** recibir notificaciones de citas programadas por los criadores **para** mantenerme al tanto de mis ofertas laborales.|3|
|21|US07|Notificación de citas al criador|**Como** criador de cuyes **quiero** recibir notificaciones referentes al estado de mis citas **para** mantenerme al tanto de mi solicitud.|3|
|22|US08|Calificación al asesor luego de una cita|**Como** criador de cuyes **quiero** calificar al asesor luego de consulta **para** ayudar a otros criadores a tomar una decisión informada antes de separar una cita.|5|
|23|US09|Gestión de publicaciones de asesores|**Como** asesor **quiero** hacer publicaciones **para** tener una mayor visibilidad.|5|
|24|US10|Visualización de publicaciones de los asesores|**Como** criador de cuyes **quiero** poder ver las publicaciones de la comunidad de asesores **para** obtener información útil y, si es necesario, solicitar asesoramiento en base a esas publicaciones.|3|
|25|US11|Gestión de jaulas de cuyes|**Como** criador de cuyes **quiero** poder registrar una jaula en la plataforma **para** poder gestionar la información de mis cuyes de manera organizada.|3|
|26|US12|Registro de información de un animal|**Como** criador de cuyes **quiero** contar con un sistema de registro de animales **para** almacenar información básica sobre cada animal, incluyendo su número de identificación, nombre, raza, género, peso y fecha de nacimiento.|3|
|27|US13|Visualización y edición de información de animales|**Como** criador de cuyes **quiero** acceder a la información de un animal **para** visualizar o actualizar su información registrada.|5|
|28|US14|Separación de fechas disponibles para asesoría|**Como** asesor **quiero** poder seleccionar y separar las fechas y horas en las que estoy disponible para ofrecer asesorías **para** que los usuarios interesados puedan ver mis horarios disponibles y agendar una cita en un momento conveniente.|3|
|29|US15|Gestión de recursos de la granja|**Como** criador de cuyes **quiero** gestionar los recursos de mi granja **para** tener un control sobre los recursos esenciales como alimentos y medicamentos.|5|
|30|US16|Gestión de gastos realizados|**Como** criador de cuyes **quiero** gestionar los gastos relacionados con mi negocio **para** tener un control y poder tomar decisiones financieras que serán útiles para tener una mejor rentabilidad.|5|
|34|US17|Seguridad de información|**Como** usuario **quiero** que la aplicación cumpla con los estándares de seguridad **para** proteger mi información registrada.|5|
|35|US18|Disponibilidad y confiabilidad|**Como** usuario **quiero** que la aplicación esté disponible siempre **para** acceder a ella en cualquier momento y sin interrupciones.|3|
|31|US19|Registro de un usuario nuevo|**Como** usuario **quiero** registrarme **para** acceder a las funciones de usuario.|3|
|32|US20|Inicio de sesión|**Como** usuario **quiero** acceder a mi cuenta registrada **para** acceder a las funciones de usuario.|3|
|33|US21|Recuperación de contraseña|**Como** usuario **quiero** poder recuperar mi contraseña **para** acceder a mi cuenta.|5|
|32|US31|Visualización de calendario|**Como** usuario **quiero** visualizar un calendario **para** ver de forma agradable y ordenada las asesorías programadas que tengo.|3|
|33|US38|Recepción de alertas cuando los parámetros ambientales (temperatura, humedad, CO₂, agua) exceden los rangos aceptables|**Como** criador **quiero** recibir alertas automáticas **para** saber cuándo los parámetros ambientales están fuera de los rangos normales.|3|
|34|US39|Visualización de gráficas históricas de parámetros ambientales para análisis de comportamiento|**Como** criador **quiero** ver gráficas históricas **para** analizar el comportamiento ambiental y tomar mejores decisiones.|5|
|35|US40|Configuración personalizada por el criador de los rangos aceptables de temperatura, humedad, nivel de CO₂ y estado del agua|**Como** criador **quiero** personalizar los valores de los rangos aceptables **para** que las alertas se ajusten a las necesidades de mi granja.|5|
|36|US41|Detección automática de agua en mal estado o escasez, con alertas para el criador|**Como** criador **quiero** que el sistema detecte cuando el agua está en mal estado o hay escasez **para** recibir una alerta inmediata.|5|
|37|US42|Activación y programación de dispensación automática de alimento en horarios establecidos|**Como** criador **quiero** programar horarios automáticos de dispensación de alimento **para** asegurar que los animales coman a tiempo sin intervención manual.|5|
|38|US43|Alerta de necesidad de limpieza cuando se detecta un nivel alto de CO₂ o condiciones desfavorables|**Como** criador **quiero** recibir alertas de limpieza **para** mantener un ambiente saludable cuando los niveles de CO₂ u otras condiciones lo indiquen.|5|
## Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design. 
### 4.1.1. EventStorming. 

<p>Realizamos nuestro proceso de event storming a través de la herramienta Figma, donde trazamos todo el recorrido del sistema. Iniciamos con la fase inicial de Unstructured Exploration, en la cual discutimos y contrastamos nuestras ideas respecto a los eventos clave del dominio, guiándonos por las sugerencias recomendadas y centrandonos en el objetivo numero uno de nuestro proyecto. Asimismo, tomamos en cuenta diversos aspectos al elegir los eventos, tales como su importancia, recurrencia y momento de ocurrencia.<p>


Leyenda: 
  - Naraja: Eventos Clave
  - Verde: Main Timeline
  - Amarillo Oscuro: Pain points
  - Azul: Commands
  - Morado: Policies
  - Rosado: Read Models
  - Amarillo Claro: Sistemas Externos

🔗 [Ver Figma](https://www.figma.com/design/bBQCiFvraA0jM3SFmloKWi/Event-Storming---IoT?node-id=0-1&t=uHqde6eWHW5RX70z-1)

<img src="img/event-storming-figma.PNG" alt="Unstructured_exploration" width="800">

<br>

**Step 1: Unstructured Exploration**

<p>Iniciamos con una exploración libre del dominio, donde cada integrante propuso eventos clave desde su perspectiva. Esta etapa nos permitió intercambiar ideas, descubrir puntos relevantes y construir una comprensión compartida del proceso. Para seleccionar los eventos, consideramos criterios como relevancia, frecuencia y temporalidad.<p>

<img src="img/unstructured_exploration.png" alt="Unstructured_exploration" width="800">
<br>
<br>
<br>
<br>

**Step 2: Timelines**
<p>En esta fase organizamos los eventos del dominio de forma cronológica. Esto nos permitió visualizar el flujo completo del sistema, identificar el orden natural de los eventos y comprender mejor cómo interactúan los actores dentro del proceso de crianza de cuyes.<p>

<img src="img/timelines_1.png" alt="Timeline 1" width="800">

<img src="img/timelines_2.png" alt="Timeline 2" width="800">

<img src="img/timelines_3.png" alt="Timeline 3" width="800">

<img src="img/timelines_4.png" alt="Timeline 4" width="800">

<img src="img/timelines_5.png" alt="Timeline 5" width="800">
<br>
<br>
<br>
<br>

**Step 3: Paint Points**
<p>Detectamos los puntos críticos o problemáticos que enfrentan tanto los criadores como el sistema actual. Estos incluían desde la falta de alertas oportunas sobre condiciones ambientales, hasta la dificultad de acceso a asesoría en tiempo real para criadores principiantes.<p>

<img src="img/paint_points_1.png" alt="Paint Point 1" width="800">

<img src="img/paint_points_2.png" alt="Paint Point 2" width="800">

<img src="img/paint_points_3.png" alt="Paint Point 31" width="800">

<img src="img/paint_points_4.png" alt="Paint Point 4" width="800">
<br>
<br>
<br>
<br>

**Step 4: Pivotal Points**
<p>Identificamos los momentos clave que marcan cambios importantes dentro del proceso, como el momento en que se detecta un problema ambiental o cuando se solicita ayuda a un experto. Estos puntos nos ayudaron a definir posibles mejoras de alto impacto.<p>

<img src="img/pivotal_points.png" alt="Pivotal Points" width="800">
<br>
<br>
<br>
<br>

**Step 5: Commands**
<p>Aquí definimos las acciones que los usuarios o el sistema pueden ejecutar, como "Registrar Alerta", "Consultar Experto", o "Actualizar Condiciones de Jaula". Cada comando representa una intención concreta que da lugar a eventos en el dominio.<p>

<img src="img/commands.png" alt="Commands" width="800">
<br>
<br>
<br>
<br>

**Step 6: Policies**
<p>Establecimos las reglas de negocio que deben ejecutarse de forma automática ante ciertos eventos. Por ejemplo, si se detecta una temperatura fuera del rango, se activa una política que genera y envía una alerta al criador correspondiente.<p>

<img src="img/policies.png" alt="Policies" width="800">
<br>
<br>
<br>
<br>

**Step 7: Read Models**
<p>Diseñamos los modelos de lectura que permitirán consultar el estado de la jaula, historial de alertas, perfiles de expertos y más. Estos modelos están optimizados para las necesidades de visualización de los usuarios dentro de la app.<p>

<img src="img/read_models.png" alt="Read Models" width="800">
<br>
<br>
<br>
<br>

**Step 8: External Systems**
<p>Identificamos los sistemas externos que interactúan con AgroCuy, como servicios de notificación (por ejemplo, Firebase para el envío de alertas), APIs de sensores, o incluso plataformas externas para aprendizaje y asesoramiento remoto.<p>

<img src="img/external_systems.png" alt="External Systems" width="800">
<br>
<br>
<br>
<br>

**Step 9: Aggregates**
<p>Por último, definimos los aggregates, que representan los límites consistentes del dominio. Un ejemplo claro fue el aggregate de AlertaDeMonitoreoDeJaula, que encapsula la lógica de generación y notificación de alertas por condiciones anómalas en las jaulas. Este aggregate centraliza todo el comportamiento relacionado con el monitoreo ambiental, siendo clave para garantizar una crianza automatizada y segura.<p>

<img src="img/aggregate_sesion_usuario.png" alt="Aggregate Sesion Usuario" width="800">

<img src="img/aggregate_alerta.png" alt="Aggregate Alerta Jaulas" width="800">

<img src="img/aggregate_asesoria.png" alt="Aggregate Asesoria" width="800">

<img src="img/aggregate_jaula_inventario.png" alt="Aggregate Jaula e inventario" width="800">

<img src="img/aggregate_publicacion.PNG" alt="Aggregate Publication" width="800">


#### 4.1.1.1 Candidate Context Discovery.

**Identificación de Valores del Negocio:**  
<p>Analizamos los aspectos fundamentales del negocio: el monitoreo automatizado de variables ambientales, el control de dispensadores de comida en horarios definidos, la detección de condiciones del agua, la gestión de jaulas y distribución de cuyes, y la comunicación entre criadores y asesores técnicos. Estos valores permiten una crianza más eficiente, segura y con acompañamiento personalizado, promoviendo buenas prácticas en la comunidad agropecuaria.</p>

**Identificación de Funcionalidades Clave:**  
<p>A partir de estos valores, identificamos funcionalidades esenciales para el sistema:</p>

- Gestión de alertas ambientales (temperatura, humedad, calidad del agua).
- Control de dispensadores de comida por horario.
- Gestión de jaulas y cantidad de cuyes por jaula.
- Notificación de agua insuficiente o en mal estado.
- Videollamadas entre criadores y asesores técnicos.
- Calendario de disponibilidad de asesores y solicitud de citas.
- Confirmación y gestión de citas por parte de los asesores.
- Gestión de cuentas para criadores y asesores.
- Reportes visuales y estado en tiempo real.
- Publicaciones.

**Priorización de Contextos:**  
<p>La priorización de bounded contexts nos ayudó a enfocar el diseño del sistema en torno a lo que realmente sostiene el valor de AgroCuy. Al distinguir los núcleos del dominio, pudimos aislar lógicas críticas que deben evolucionar de forma independiente y con alta cohesión.</p>

**Contextos Identificados:**

1. **Security:** gestiona la autenticación y perfiles de criadores y asesores técnicos.  
2. **Monitoring:** monitorea las condiciones dentro de las jaulas y emite alertas cuando se detectan situaciones críticas.  
3. **Breeding:** permite gestionar la cantidad de cuyes por jaula, el estado del agua y el uso de dispensadores automáticos de comida.  
4. **Consulting:** facilita la interacción entre criadores y asesores mediante videollamadas, programación de citas y gestión de disponibilidad.  
5. **Publication:** facilita que los asesores técnicos publiquen contenido relacionado a su experiencia o conocimientos, permitiendo visibilizar su perfil y atraer a potenciales criadores interesados en su asesoría.

**Bounded Context Security**
  <img src="img/bounded_context_security.png" alt="Bounded Context Security" width="800">

**Bounded Context Monitoring**
    <img src="img/bounded_context_enviormental.png" alt="Bounded Context Monitoring" width="800">

**Bounded Context Breeding**
    <img src="img/bounded_context_breeding.png" alt="Bounded Context Breeding" width="800">

**Bounded Context Consulting**
    <img src="img/bounded_context_consulting.png" alt="Bounded Context Consulting" width="800">

**Bounded Context Publication**
    <img src="img/bounded_context_publication.PNG" alt="Bounded Context Publication" width="800">

#### 4.1.1.2 Domain Message Flows Modeling.

<p>Este gráfico muestra cómo el usuario interactúa con el sistema para monitorear a sus cuyes. A través de la interfaz web/app, se solicita información del criadero y los parámetros medidos, la cual es obtenida desde sensores IoT. Si se detecta un valor fuera de rango, se activa una alerta y se notifica al usuario en tiempo real.<p>

**Monitoreo**

<img src="img/Domain Message Flow - Monitoreo.png" alt="Domain Message Flow - Monitoreo" width="800">

**Seguridad**

<img src="img/Domain Message Flow - Seguridad.png" alt="Domain Message Flow - Seguridad" width="800">

**Brending**

<img src="img/Domain Message Flow - Brending.png" alt="Domain Message Flow - Brending" width="800">

**Consulta**

<img src="img/Domain Message Flow - Consulta.png" alt="Domain Message Flow - Consulta" width="800">



#### 4.1.1.3 Bounded Context Canvases. 

<p>En este canvas definimos el Bounded Context del sistema de monitoreo para criaderos de cuyes, donde detallamos su propósito, comunicaciones, decisiones clave y lenguaje ubicuo. Representa cómo interactúan sensores, usuarios y alertas dentro del sistema.<p>

**Monitoreo**

<img src="img/Bounded Context Canvases - Monitoreo.png" alt="Bounded Context Canvases - Monitoreo" width="800">

**Seguridad**

<img src="img/Bounded Context Canvases - Seguridad.png" alt="Bounded Context Canvases - Seguridad" width="800">

**Brending**

<img src="img/Bounded Context Canvases - Brending.png" alt="Bounded Context Canvases - Brending" width="800">

**Consulta**

<img src="img/Bounded Context Canvases - Consulta.png" alt="Bounded Context Canvases - Consulta" width="800">

### **4.1.2. Context Mapping**

<p>Una vez definidos nuestros Bounded Contexts, realizamos el mapeo de sus relaciones para comprender cómo se comunican dentro del sistema de AgroCuy y asignar los patrones adecuados según su interacción.</p>

<p>
– <strong>Security</strong> provee autenticación y manejo de perfiles tanto para criadores como para asesores técnicos. Es utilizado por los demás contextos, pero no depende de ninguno. Esta relación fue clasificada como <strong>Shared Kernel</strong>, ya que su lógica y entidades clave deben ser consistentes y compartidas de forma controlada.
</p>

<p>
– <strong>Monitoring</strong> detecta situaciones como falta de agua o comida, y genera alertas críticas. Esta información es consumida por <strong>Breeding</strong> para tomar decisiones sobre el manejo de jaulas. Dado que Breeding depende del lenguaje de eventos generado por Monitoring, aplicamos el patrón <strong>Conformist</strong>.
</p>

<p>
– <strong>Consulting</strong> se encarga de la programación de citas, videollamadas y disponibilidad de asesores. Su interacción con <strong>Security</strong> (para acceder al perfil del asesor o criador) sigue el patrón <strong>Customer–Supplier</strong>, ya que Consulting consume datos que Security expone.
</p>

– <strong>Publication</strong> se encargar de la gestion de publicaciones de asesores para mayor visibilidad. Su interacción con <strong>Security</strong> (para acceder al perfil del asesor o criador) sigue el patrón <strong>Customer–Supplier</strong>, ya que Consulting consume datos que Security expone.
</p>

<p>
– Además, la comunicación entre <strong>Breeding</strong> y <strong>Monitoring</strong> también puede considerarse como <strong>Published Language</strong> en algunos escenarios, cuando ambos deben interpretar eventos de forma coherente (por ejemplo, para emitir alertas o automatizar los dispensadores).
</p>

<p>
Este mapeo nos ayuda a establecer relaciones claras entre los contextos, identificar dependencias y definir una arquitectura que mantenga separadas las responsabilidades de cada módulo en AgroCuy.
</p>

**Bounded Context All - Vista Completa**
    <img src="img/bounded_context_all_view.PNG" alt="Bounded Context Consulting" width="800">

### 4.1.3. Software Architecture


#### 4.1.3.1. Software Architecture System Landscape Diagram

El presente diagrama representa la vista de *System Landscape* de la solución **AgroCuy**, la cual forma parte de un ecosistema tecnológico orientado a mejorar la crianza y gestión de cuyes a través del uso de tecnologías web, móviles y dispositivos IoT (Arduino).

Esta vista tiene como propósito mostrar los diferentes sistemas de software, dispositivos físicos y usuarios que interactúan entre sí para dar soporte completo a la automatización y asesoramiento de granjas de cuyes.

La plataforma **AgroCuy** actúa como sistema central de integración, permitiendo que los **criadores de cuyes** (*Breeder*) puedan gestionar sus granjas, visualizar datos recolectados en tiempo real y recibir asesoramiento técnico remoto. Del mismo modo, los **asesores técnicos** (*Advisor*) se conectan al sistema para brindar soporte a distancia.

Además, el sistema se integra con:

- **Jitsi Meet**: para generar enlaces de videollamadas donde se llevan a cabo sesiones de asesoría remota.
- **Firebase Storage**: para el almacenamiento de imágenes u otros archivos multimedia relevantes a la gestión de la granja.
- **Módulo IoT (Arduino + sensores)**: proporciona la capacidad de recolección automatizada de datos del entorno (temperatura, humedad, etc.) y eventualmente el control de dispositivos como ventiladores o dispensadores automáticos.
- **Aplicación móvil AgroCuy**: actúa como interfaz directa entre el criador y la plataforma, permitiéndole recibir alertas y monitorear condiciones de su granja desde cualquier lugar.

Este *System Landscape* ofrece una visión clara del entorno digital y físico de AgroCuy, destacando su enfoque integral al combinar asesoría especializada con automatización, en beneficio de los productores rurales.

![Diagrama de sistema AgroCuy](img/grocuy-landscape.png)


#### **4.1.3.2. Software Architecture Context Level Diagrams**

El diagrama de contexto presenta una vista de alto nivel del sistema **AgroCuy**, mostrando su relación con los actores humanos y sistemas externos que lo rodean. Este diagrama representa el primer nivel del modelo C4 (Context Diagram), enfocado en identificar **quiénes usan la plataforma y cómo interactúan con ella**, sin entrar aún en los componentes internos.

**AgroCuy** es una plataforma diseñada para brindar apoyo a criadores de cuyes mediante asesoría remota, visualización de datos en tiempo real y automatización mediante sensores IoT conectados a dispositivos Arduino. Desde esta vista, se destaca la interacción directa entre los siguientes elementos:

- **Criador de cuyes (Breeder):** usuario principal del sistema, que accede a AgroCuy para recibir alertas, visualizar datos del entorno de su granja, y comunicarse con asesores técnicos.
- **Asesor técnico (Advisor):** profesional que brinda soporte y seguimiento al criador a través del sistema.
- **Sistema de videollamadas (Jitsi Meet):** se usa para agendar y generar reuniones de asesoramiento entre criador y asesor.
- **Módulo IoT (Arduino + sensores):** dispositivo que recolecta datos de la granja y los transmite hacia AgroCuy para su visualización y análisis.
- **Aplicación móvil AgroCuy:** interfaz móvil que permite al criador interactuar fácilmente con la plataforma desde su dispositivo.

Esta vista facilita comprender el **alcance del sistema**, sus **límites** y las **interacciones clave** que permiten su funcionamiento, sirviendo como punto de partida para niveles de detalle más específicos como el Container Diagram.

![Diagrama de sistema AgroCuy](img/agrocuy-context2.png)

#### 4.1.3.3. Software Architecture Container Level Diagrams

El Container Diagram representa la segunda capa del modelo C4 para la solución **AgroCuy**, y muestra cómo se estructura el sistema como un conjunto de contenedores: aplicaciones móviles, aplicaciones web, APIs, bases de datos y componentes IoT. Cada contenedor tiene una responsabilidad clara, y se comunica con otros contenedores o sistemas externos mediante interfaces bien definidas, principalmente a través de servicios RESTful.

Esta vista es fundamental para comprender la arquitectura técnica de alto nivel y los puntos de integración del sistema.

### Contenedores principales del sistema AgroCuy

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Contenedor</th>
      <th>Tecnología</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Web Application</td>
      <td>Angular</td>
      <td>Aplicación web utilizada por asesores técnicos para gestionar usuarios y monitorear granjas.</td>
    </tr>
    <tr>
      <td>Mobile Application</td>
      <td>Flutter</td>
      <td>Aplicación móvil para criadores, que permite recibir notificaciones y ver información del criadero.</td>
    </tr>
    <tr>
      <td>RESTful API</td>
      <td>Spring Boot</td>
      <td>API central que expone los servicios de negocio: autenticación, sensores, usuarios.</td>
    </tr>
    <tr>
      <td>Base de Datos</td>
      <td>PostgreSQL</td>
      <td>Repositorio de datos que almacena información de sensores, usuarios, alertas y configuraciones.</td>
    </tr>
    <tr>
      <td>Edge API</td>
      <td>Python (Flask)</td>
      <td>API embebida en Raspberry que conecta sensores con la nube.</td>
    </tr>
    <tr>
      <td>Embedded App</td>
      <td>Arduino C++</td>
      <td>Firmware instalado en microcontroladores Arduino que recolecta datos del entorno y los envía.</td>
    </tr>
  </tbody>
</table>

### Sistemas externos integrados

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Sistema Externo</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Firebase Storage</td>
      <td>Servicio externo para almacenar archivos, imágenes y documentos generados.</td>
    </tr>
    <tr>
      <td>Jitsi Meet</td>
      <td>Plataforma de videollamadas utilizada para asesoramiento remoto.</td>
    </tr>
  </tbody>
</table>

![Diagrama de sistema AgroCuy](img/Container_Diagram.png)

#### 4.1.3.4. Software Architecture Deployment Diagrams

El Deployment Diagram muestra cómo se distribuyen físicamente los contenedores de la solución AgroCuy en los distintos nodos del entorno de producción. Este diagrama refleja la arquitectura de despliegue real de los componentes, incluyendo servidores, dispositivos IoT, navegadores web, aplicaciones móviles y servicios externos. 

El objetivo es evidenciar dónde y cómo se ejecutan los elementos del sistema en la infraestructura final, asegurando su conectividad, interoperabilidad y funcionamiento distribuido.

### Nodos de despliegue y componentes

<table>
  <thead>
    <tr>
      <th><strong>Nodo</strong></th>
      <th><strong>Contenedores/Sistemas desplegados</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Servidor Cloud</td>
      <td>RESTful API, Base de Datos</td>
    </tr>
    <tr>
      <td>Raspberry Pi</td>
      <td>Edge API (Gateway IoT)</td>
    </tr>
    <tr>
      <td>Arduino (Microcontrolador)</td>
      <td>Embedded App (Firmware para sensores)</td>
    </tr>
    <tr>
      <td>Navegador Web</td>
      <td>Web Application (Angular)</td>
    </tr>
    <tr>
      <td>Smartphone Android</td>
      <td>Mobile Application (Flutter)</td>
    </tr>
    <tr>
      <td>Servicios Externos</td>
      <td>Firebase Storage, Jitsi Meet</td>
    </tr>
  </tbody>
</table>

![Diagrama de sistema AgroCuy](img/Deployment_Diagram.png)

## 4.2. Tactical-Level Domain-Driven Design

<br><br>

### 4.2.1. Bounded Context: Security
### 4.2.1.1. Domain Layer
A continuación, se presenta la organización del Domain Layer siguiendo la estructura: Aggregate, Value Objects, Domain Services y Repositories, con todos los elementos organizados en tablas independientes.
<br>

## Aggregate

<table>
  <thead>
    <tr>
      <th>Entidad</th>
      <th>Atributos Clave</th>
      <th>Value Objects Asociados</th>
      <th>Métodos / Reglas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Usuario</td>
      <td>id, nombre, email, contraseña, tipoPerfil, roles, granjas</td>
      <td>Rol, Permiso, Perfil</td>
      <td>
        autenticarUsuario()<br>
        asignarRol()<br>
        agregarGranja()<br>
        definirTipoPerfil()<br>
        obtenerPerfil()<br>
        validarPerfilUnico()<br>
        esAsesor()<br>
        esCriador()
      </td>
    </tr>
  </tbody>
</table>

---

## Value Objects

<table>
  <thead>
    <tr>
      <th>VO</th>
      <th>Atributos</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Rol</td>
      <td>id, nombre, permisos</td>
      <td>Define conjunto de permisos asignables a un usuario</td>
    </tr>
    <tr>
      <td>Permiso</td>
      <td>id, nombre, descripcion</td>
      <td>Acción específica que puede ejecutar un usuario</td>
    </tr>
    <tr>
      <td>Perfil</td>
      <td>nombre, email, tipoPerfil, especialidad, ubicacion</td>
      <td>Datos públicos del usuario expuestos a otros contextos</td>
    </tr>
  </tbody>
</table>

---

## Domain Services

<table>
  <thead>
    <tr>
      <th>Servicio</th>
      <th>Métodos</th>
      <th>Responsabilidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SecurityManagementService</td>
      <td>
        autenticarUsuario()<br>
        registrarUsuario()<br>
        asignarRol()<br>
        validarPermiso()<br>
        obtenerPerfil()<br>
        listarUsuariosPorTipo()
      </td>
      <td>Orquestación de operaciones de seguridad</td>
    </tr>
  </tbody>
</table>

---

## Repositories

<table>
  <thead>
    <tr><th>Repositorio</th><th>Métodos</th><th>Entidad</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>UserRepository</td>
      <td>
        findById(),<br/>
        findByEmail(),<br/>
        findByTipoPerfil(),<br/>
        save(),<br/>
        deleteById()
      </td>
      <td>Usuario</td>
    </tr>
    <tr>
      <td>RolRepository</td>
      <td>
        findByNombre(),<br/>
        save(),<br/>
        deleteById()
      </td>
      <td>Rol</td>
    </tr>
    <tr>
      <td>PermisoRepository</td>
      <td>
        findByNombre(),<br/>
        save(),<br/>
        deleteById()
      </td>
      <td>Permiso</td>
    </tr>
  </tbody>
</table>

### 4.2.1.2. Interface Layer

En esta sección, presentamos la Capa de Interfaz de nuestra plataforma de AgroConnect para la gestión de seguridad. Representa el punto de entrada para las interacciones entre los usuarios (criadores y asesores técnicos) y el sistema. Está compuesta por una serie de controladores que manejan las peticiones entrantes de los usuarios y devuelven las respuestas adecuadas, permitiendo una comunicación efectiva entre la plataforma y sus usuarios o bounded contexts consumidores.

El contexto de esta capa incluye cuatro controladores principales: `UserController`, `SensorController`, `PermissionController` y `GranjaController`. Estos controladores son responsables de gestionar operaciones sobre usuarios, autenticación, sensores, permisos y granjas vinculadas.


## Controladores

<table border="1" style="width:100%; text-align:left;">
  <tr>
    <th style="width:50%;">UserController</th>
    <th style="width:50%;">PermissionController</th>
  </tr>
  <tr>
    <td>
      + authenticateUser(email, password): TokenDto<br/>
      + registerUser(usuarioDto): ResponseEntity<br/>
      + getAllUsers(): List&lt;UsuarioDto&gt;<br/>
      + updateUser(id, usuarioDto): UsuarioDto<br/>
      + deleteUser(id): ResponseEntity<br/>
      + getPerfilUsuario(id): PerfilDto<br/>
      + getUsuariosPorTipo(tipoPerfil): List&lt;UsuarioDto&gt;
    </td>
    <td>
      + getAllPermissions(): List&lt;PermisoDto&gt;<br/>
      + assignPermissionToUser(userId, permisoId): ResponseEntity<br/>
      + removePermissionFromUser(userId, permisoId): ResponseEntity
    </td>
  </tr>
</table>

<br/>

<table border="1" style="width:100%; text-align:left;">
  <tr>
    <th style="width:50%;">SensorController</th>
    <th style="width:50%;">GranjaController</th>
  </tr>
  <tr>
    <td>
      + getAllSensors(): List&lt;SensorDto&gt;<br/>
      + addSensor(sensorDto): ResponseEntity<br/>
      + updateSensor(id, sensorDto): SensorDto<br/>
      + deleteSensor(id): ResponseEntity
    </td>
    <td>
      + getGranjasByUsuario(usuarioId): List&lt;GranjaDto&gt;<br/>
      + addGranja(granjaDto): ResponseEntity<br/>
      + updateGranja(id, granjaDto): GranjaDto<br/>
      + deleteGranja(id): ResponseEntity
    </td>
  </tr>
</table>

### 4.2.1.3. Application Layer

En esta sección, se presenta la Capa de Aplicación (Application Layer) del contexto de Seguridad de AgroConnect. Esta capa actúa como intermediaria entre la lógica de dominio y la infraestructura, orquestando el flujo de datos para realizar operaciones como el registro, autenticación y manejo de perfiles.

Se definen tanto Command Handlers como Event Handlers, los cuales coordinan los servicios relevantes para ejecutar acciones específicas del sistema, como asignar roles, generar perfiles o responder a eventos de login/logout.

---

## Handlers

<table border="1" style="width:100%; text-align:left; background-color:#ffffe0;">
  <tr>
    <th style="width:50%;">UserRegistrationCommandHandler</th>
    <th style="width:50%;">AssignRoleCommandHandler</th>
  </tr>
  <tr>
    <td>
      + userService: UserService<br/>
      + handle(RegisterUserCommand command): Usuario
    </td>
    <td>
      + userService: UserService<br/>
      + handle(AssignRoleCommand command): void
    </td>
  </tr>
</table>

<br/>

<table border="1" style="width:100%; text-align:left; background-color:#ffffe0;">
  <tr>
    <th style="width:50%;">ProfileRequestedEventHandler</th>
    <th style="width:50%;">UserLogoutEventHandler</th>
  </tr>
  <tr>
    <td>
      + userService: UserService<br/>
      + handle(ProfileRequestedEvent event): Perfil
    </td>
    <td>
      + authService: AuthService<br/>
      + handle(UserLoggedOutEvent event): void
    </td>
  </tr>
</table>

### 4.2.1.4. Infrastructure Layer

En esta sección, se presenta la Capa de Infraestructura (Infrastructure Layer) dentro del contexto de Seguridad de AgroConnect. Esta capa proporciona los componentes técnicos y de soporte que permiten la interacción con bases de datos, servicios de autenticación y almacenamiento de perfiles. 

Su función principal es implementar los contratos definidos en el dominio y permitir la persistencia de los datos relacionados con usuarios, roles, permisos y sensores. Además, se asegura de que la lógica de seguridad y autenticación funcione correctamente en conjunto con tecnologías como Spring Security y OAuth 2.0.

Los repositorios definidos en esta capa utilizan frameworks como Spring Data JPA para la persistencia, y representan un puente entre la lógica de negocio y el almacenamiento físico de datos.
<br>
## Repositorios

<table border="1" style="width:100%; text-align:left;">
  <tr>
    <th style="width:50%;">UserRepository</th>
    <th style="width:50%;">RoleRepository</th>
  </tr>
  <tr>
    <td>
      + findById(userId: UUID): Usuario<br/>
      + findByEmail(email: String): Usuario<br/>
      + findByTipoPerfil(tipoPerfil: Enum): List&lt;Usuario&gt;<br/>
      + save(usuario: Usuario): void<br/>
      + deleteById(userId: UUID): void
    </td>
    <td>
      + findByNombre(nombre: String): Rol<br/>
      + save(rol: Rol): void<br/>
      + deleteById(rolId: UUID): void
    </td>
  </tr>
</table>

<br/>

<table border="1" style="width:100%; text-align:left;">
  <tr>
    <th style="width:50%;">PermisoRepository</th>
    <th style="width:50%;">SensorRepository</th>
  </tr>
  <tr>
    <td>
      + findByNombre(nombre: String): Permiso<br/>
      + save(permiso: Permiso): void<br/>
      + deleteById(permisoId: UUID): void
    </td>
    <td>
      + findById(sensorId: UUID): Sensor<br/>
      + findByTipo(tipo: String): List&lt;Sensor&gt;<br/>
      + save(sensor: Sensor): void<br/>
      + deleteById(sensorId: UUID): void
    </td>
  </tr>
</table>

### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

<img src="img/Security_Diagram.png" alt="Security Component Diagram" width="800">

### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
En esta sección se presenta el diagrama de diseño de base de datos del contexto de seguridad. El modelo de datos refleja la estructura de las entidades y sus relaciones a través de claves primarias y foráneas. Este diseño asegura la integridad referencial entre los usuarios, roles, permisos y sensores.

<img src="img/Security_UML.png" alt="Security Component Diagram" width="800">


### 4.2.1.6.2. Bounded Context Database Design Diagram

El sistema diferencia principalmente entre dos tipos de usuarios: **criadores** y **asesores técnicos**, cada uno con **niveles de acceso diferenciados**. Los criadores están vinculados directamente con las **granjas**, las cuales agrupan sensores físicos que recolectan información clave sobre las condiciones de crianza de los cuyes. Por su parte, los asesores técnicos pueden acceder a información crítica a través de permisos específicos y validaciones de seguridad.

<img src="img/Security_dbDiagram.png" alt="Security Component Diagram" width="800">

<br><br>

### 4.2.2. Bounded Context: Monitoring

#### 4.2.2.1. Domain Layer

A continuación, se presenta la organización del Domain Layer para el Bounded Context "Monitoring", siguiendo la estructura: Aggregate, Value Objects, Domain Services y Repositories, con todos los elementos organizados en tablas independientes.

<br/>

##### Aggregate

| Entidad         | Atributos Clave                                          | Métodos                |
|------------------|----------------------------------------------------------|------------------------|
| MonitoringEvent  | id, type (EventType), message, severity (SeverityLevel), createdAt | alertIfCritical(), isRelevantEvent() |

---

##### Value Objects

| VO             | Atributos               | Descripción                                                                 |
|----------------|--------------------------|------------------------------------------------------------------------------|
| EventType      | name                     | Tipo de evento generado en el sistema (AnimalHealth, CageTemp, AppointmentMissed) |
| SeverityLevel  | CRITICAL, WARNING, INFO  | Clasificación del nivel de importancia de cada evento monitoreado           |

---

##### Domain Services

| Servicio           | Métodos                                                                                   | Responsabilidad                                                      |
|--------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| MonitoringService  | registrarEvento(), obtenerEventosCriticos(), filtrarPorTipo(), enviarAlertaSiEsNecesario() | Gestiona la lógica de registro y clasificación de eventos relevantes |

---

##### Repositories

| Repositorio               | Métodos                                                       | Entidad          |
|---------------------------|----------------------------------------------------------------|------------------|
| MonitoringEventRepository | findAll(), findBySeverity(), findByType(), save(), deleteById() | MonitoringEvent  |

---

#### 4.2.2.2. Interface Layer

La capa de interfaz define los puntos de entrada HTTP para registrar nuevos eventos del sistema, consultar alertas críticas y filtrar eventos por tipo o nivel de severidad.

##### Controladores

| Controlador           | Operaciones                                                                                               |
|-----------------------|-----------------------------------------------------------------------------------------------------------|
| MonitoringController  | + registerEvent(eventDto)<br/> + getAllEvents()<br/> + getEventsByType(type)<br/> + getCriticalEvents()<br/> + deleteEvent(id) |

---

#### 4.2.2.3. Application Layer

Esta capa orquesta la ejecución de los casos de uso de monitoreo, incluyendo el registro de eventos, recuperación de registros y ejecución de alertas ante eventos críticos.

##### Handlers

| Handler                          | Método                                        | Descripción                                                             |
|----------------------------------|-----------------------------------------------|-------------------------------------------------------------------------|
| RegisterEventCommandHandler      | handle(RegisterEventCommand)                 | Registra un nuevo evento de monitoreo                                   |
| GetCriticalEventsQueryHandler    | handle(GetCriticalEventsQuery)               | Obtiene todos los eventos con severidad CRITICAL                        |
| GetEventsByTypeQueryHandler      | handle(GetEventsByTypeQuery)                 | Filtra los eventos según su tipo                                        |
| DeleteEventCommandHandler        | handle(DeleteEventCommand)                   | Elimina un evento registrado                                            |

---

#### 4.2.2.4. Infrastructure Layer

Esta capa proporciona acceso a persistencia e integración con otros contextos que emiten eventos relevantes. Implementa los contratos definidos en el dominio y comunica la lógica de monitoreo con la base de datos o servicios externos.

##### Repositorios

| Repositorio               | Métodos                                                                   |
|---------------------------|----------------------------------------------------------------------------|
| MonitoringEventRepository | findAll(), findByType(type), findBySeverity(level), save(event), deleteById(id) |

---

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

<img src="img/monitoring_component_diagram.png" alt="Monitoring Component Diagram" width="800">

---

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

<img src="img/class_diagram_monitoring.png" alt="Monitoring Class Diagram" width="800">

---

##### 4.2.2.6.2. Bounded Context Database Design Diagram

<img src="img/database_monitoring.png" alt="Monitoring Database Diagram" width="800">


<br><br>

### 4.2.3. Bounded Context: Consulting <Bounded Context Consulting>
### 4.2.3.1. Domain Layer
A continuación, se presenta la organización del Domain Layer siguiendo la estructura: Aggregate, Value Objects, Domain Services y Repositories, con todos los elementos organizados en tablas independientes.

## Aggregate

<table>
  <thead>
    <tr><th>Entidad</th><th>Atributos Clave</th><th>Métodos</th></tr>
  </thead>
  <tbody>
    <tr>
      <td> Asesoria </td>
      <td>
        id, date, status, title, breederId, advisor_id
      </td>
      <td>
        getAppointment(),
        updateAppointment()
      </td>
    </tr>
  </tbody>
</table>

---

## Value Objects

<table>
  <thead>
    <tr>
      <th>VO</th>
      <th>Atributos</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>DateAppointment.java</code></td>
      <td><code>date</code></td>
      <td>Define la fecha de cada cita</td>
    </tr>
    <tr>
      <td><code>Status.java</code></td>
      <td><code>PENDIENTE, TERMINADO</code></td>
      <td>Define el estatus de cada cita</td>
    </tr>
  </tbody>
</table>


---

## Domain Services

<table>
  <thead>
    <tr><th>Servicio</th><th>Métodos</th><th>Responsabilidad</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>ConsultingCommandService</td>
      <td>
        CreateConsultingCommand(),<br/>
        UpdateConsultingCommand (),<br/>
        DeleteConsultingCommand()
      </td>
      <td>Este servicio define la lógica para crear, actualizar y eliminar publicaciones a partir de comandos específicos, siguiendo el patrón Command Handler en una arquitectura orientada al dominio (DDD)</td>
    </tr>
    <tr>
      <td>ConsultingQueryService</td>
      <td>
        GetAllConsultingQuery(),<br/>
        GetConsultingByIdQuery(),<br/>
        GetConsultingByAdvisorIdQuery()
      </td>
      <td>Este servicio representa el módulo de consultas (Query Service) del patrón CQRS, y se encarga de recuperar publicaciones mediante distintos criterios (todas, por ID o por asesor), sin modificar el estado del sistema.</td>
    </tr>
  </tbody>
</table>

---

## Repositories

<table> <thead> <tr> <th>Repositorio</th> <th>Métodos</th> <th>Entidad</th> </tr> </thead> <tbody> <tr> <td>ConsultingRepository</td> <td> save(Consulting consulting),<br/> findById(Long id),<br/> findAll(),<br/> deleteById(Long id),<br/> findAllByAdvisorId(Long advisorId),<br/> findAllByBreederId(Long farmerId) </td> <td>Consulting</td> </tr> </tbody> </table>

### 4.2.3.2. Interface Layer
Esta capa expone las funcionalidades del contexto Assessment a través de un controlador principal. Este controlador gestiona las operaciones CRUD y las consultas disponibles.

<table border="1" style="width:100%; text-align:left;"> <tr> <th style="width:50%;">ConsultingController</th> </tr> <tr> <td> + createConsulting(resource): ResponseEntity&lt;ConsultingResource&gt;<br/> + getAllConsultings(): ResponseEntity&lt;List&lt;ConsultingResource&gt;&gt;<br/> + getConsultingById(consultingId): ResponseEntity&lt;ConsultingResource&gt;<br/> + getConsultingsByAdvisorId(advisorId): ResponseEntity&lt;List&lt;ConsultingResource&gt;&gt;<br/> + getConsultingsByFarmerId(farmerId): ResponseEntity&lt;List&lt;ConsultingResource&gt;&gt;<br/> + updateConsulting(consultingId, resource): ResponseEntity&lt;ConsultingResource&gt;<br/> + deleteConsulting(consultingId): ResponseEntity&lt;Void&gt; </td> </tr> </table>

### 4.2.3.3. Application Layer

La Capa de Aplicación se encarga de orquestar la ejecución de los casos de uso definidos en el dominio. En esta sección se describen los servicios de comandos y consultas (handlers) que procesan los distintos flujos relacionados con la gestión de consultorías.

<table border="1" style="width:100%; text-align:left;"> <tr> <th style="width:50%;">ConsultingCommandServiceImpl</th> </tr> <tr> <td> + handle(CreateConsultingCommand command): Long </td> <td> Crea una nueva consultoría entre un asesor técnico y un criador, y la guarda en la base de datos. </td> </tr> <tr> <td> + handle(UpdateConsultingCommand command): Long </td> <td> Actualiza el contenido, fecha o detalles de una consultoría existente. </td> </tr> <tr> <td> + handle(DeleteConsultingCommand command): void </td> <td> Elimina una consultoría del sistema si existe. </td> </tr> </table> <br/> <table border="1" style="width:100%; text-align:left;"> <tr> <th style="width:50%;">ConsultingQueryServiceImpl</th> </tr> <tr> <td> + handle(GetAllConsultingsQuery query): List&lt;Consulting&gt; </td> <td> Recupera la lista completa de consultorías registradas. </td> </tr> <tr> <td> + handle(GetConsultingByIdQuery query): Optional&lt;Consulting&gt; </td> <td> Obtiene una consultoría específica según su identificador único. </td> </tr> <tr> <td> + handle(GetConsultingsByAdvisorIdQuery query): List&lt;Consulting&gt; </td> <td> Devuelve todas las consultorías asociadas a un asesor técnico específico. </td> </tr> <tr> <td> + handle(GetConsultingsByFarmerIdQuery query): List&lt;Consulting&gt; </td> <td> Devuelve todas las consultorías asociadas a un criador específico. </td> </tr> </table>


### 4.2.3.4. Infrastructure Layer
<table> <thead> <tr><th>Repositorio</th><th>Métodos</th><th>Entidad</th></tr> </thead> <tbody> <tr> <td>ConsultingRepository</td> <td> findAllByAdvisorId()<br/> findAllByFarmerId() </td> <td>Consulting</td> </tr> </tbody> </table>

### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

<img src="img/Appointment_Component_Diagram (1).png" alt="Read Models" width="800">

### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

<img src="img/class_diagram_appointment.png" alt="Read Models" width="800">

### 4.2.3.6.2. Bounded Context Database Design Diagram

<img src="img/Appointment_database_diagram.png" alt="Read Models" width="800">

<br><br>

### 4.2.4. Bounded Context: Management
### 4.2.4.1. Domain Layer

A continuación, se presenta la organización del Domain Layer siguiendo la estructura: Aggregate, Value Objects, Domain Services y Repositories, con todos los elementos organizados en tablas independientes.

## Aggregate

<table>
  <thead>
    <tr><th>Entidad</th><th>Atributos Clave</th><th>Métodos</th></tr>
  </thead>
  <tbody>
    <tr>
      <td> Cage </td>
      <td>
        id, name, size, observations, breederId
      </td>
      <td>
        getCage(), updateCage()
      </td>
    </tr>
  </tbody>
</table>

---

## Value Objects

<table>
  <thead>
    <tr>
      <th>VO</th>
      <th>Atributos</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>Name.java</code></td>
      <td><code>name</code></td>
      <td>Define el nombre (animal, recurso o gasto)</td>
    </tr>
    <tr>
      <td><code>Size.java</code></td>
      <td><code>size</code></td>
      <td>Define el tamaño de una jaula</td>
    </tr>
    <tr>
      <td><code>Observations.java</code></td>
      <td><code>observations</code></td>
      <td>Observaciones generales</td>
    </tr>
  </tbody>
</table>


---

## Domain Services

<table>
  <thead>
    <tr><th>Servicio</th><th>Métodos</th><th>Responsabilidad</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>ManagementCommandService</td>
      <td>
        CreateResourceCommand(), <br/> UpdateResourceCommand(), <br/> DeleteResourceCommand(),<br/> CreateAnimalCommand()
      </td>
      <td>Encargado de crear, actualizar o eliminar entidades (gastos, recursos, animales, jaulas, etc.) siguiendo el patrón Command Handler.</td>
    </tr>
    <tr>
      <td>ManagementQueryService</td>
      <td>
        GetAllResourcesQuery(),<br/> GetAnimalsByCageIdQuery()
      </td>
      <td>Representa el módulo de consultas. Recupera información de recursos, animales y gastos. No modifica el estado del sistema.</td>
    </tr>
  </tbody>
</table>

---

## Repositories

<table> <thead> <tr> <th>Repositorio</th> <th>Métodos</th> <th>Entidad</th> </tr> </thead> <tbody> <tr> <td>ManagementRepository</td> <td> save(), findAll(), findById(), deleteById(), findAllByCageId(), findAllByBreederId() </td> <td>Cage, Animal, Resource, Expense</td> </tr> </tbody> </table>

### 4.2.4.2. Interface Layer

Esta capa expone las funcionalidades del contexto Management a través de un controlador principal. Este controlador gestiona las operaciones CRUD y las consultas disponibles.


<table>
  <thead>
    <tr>
      <th colspan="2">ManagementController</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>+ createResource(resource):</td>
      <td>ResponseEntity&lt;ResourceResource&gt;</td>
    </tr>
    <tr>
      <td>+ getAllResources():</td>
      <td>ResponseEntity&lt;List&lt;ResourceResource&gt;&gt;</td>
    </tr>
    <tr>
      <td>+ getResourceById(resourceId):</td>
      <td>ResponseEntity&lt;ResourceResource&gt;</td>
    </tr>
    <tr>
      <td>+ deleteResource(resourceId):</td>
      <td>ResponseEntity&lt;Void&gt;</td>
    </tr>
    <tr>
      <td>+ createAnimal(animal):</td>
      <td>ResponseEntity&lt;AnimalResource&gt;</td>
    </tr>
    <tr>
      <td>+ getAnimalsByCageId(cageId):</td>
      <td>ResponseEntity&lt;List&lt;AnimalResource&gt;&gt;</td>
    </tr>
    <tr>
      <td>+ updateCage(cageId, cage):</td>
      <td>ResponseEntity&lt;CageResource&gt;</td>
    </tr>
    <tr>
      <td>+ getExpensesByBreederId(breederId):</td>
      <td>ResponseEntity&lt;List&lt;ExpenseResource&gt;&gt;</td>
    </tr>
    <tr>
      <td>+ createExpense(expense):</td>
      <td>ResponseEntity&lt;ExpenseResource&gt;</td>
    </tr>
  </tbody>
</table>

### 4.2.4.3. Application Layer

La Capa de Aplicación se encarga de orquestar la ejecución de los casos de uso definidos en el dominio. 
En esta sección se describen los servicios de comandos y consultas (handlers) que procesan los distintos flujos relacionados con la gestión del inventario de la granja.

<table>
  <thead>
    <tr>
      <th colspan="2">ManagementCommandServiceImpl</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>+ handle(CreateResourceCommand command): Long</td>
      <td>Crea un nuevo recurso y lo guarda en la base de datos.</td>
    </tr>
    <tr>
      <td>+ handle(UpdateResourceCommand command): Long</td>
      <td>Actualiza los detalles de un recurso existente.</td>
    </tr>
    <tr>
      <td>+ handle(DeleteResourceCommand command): void</td>
      <td>Elimina un recurso del sistema si existe.</td>
    </tr>
    <tr>
      <td>+ handle(CreateAnimalCommand command): Long</td>
      <td>Crea un nuevo cuy y lo asigna a una jaula.</td>
    </tr>
    <tr>
      <td>+ handle(UpdateCageCommand command): Long</td>
      <td>Actualiza los datos de una jaula.</td>
    </tr>
    <tr>
      <td>+ handle(CreateExpenseCommand command): Long</td>
      <td>Registra un nuevo gasto para el criador.</td>
    </tr>
  </tbody>
</table>

<br/>

<table>
  <thead>
    <tr>
      <th colspan="2">ManagementQueryServiceImpl</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>+ handle(GetAllResourcesQuery query): List&lt;Resource&gt;</td>
      <td>Recupera todos los recursos registrados.</td>
    </tr>
    <tr>
      <td>+ handle(GetAnimalsByCageIdQuery query): List&lt;Animal&gt;</td>
      <td>Recupera los cuyes pertenecientes a una jaula específica.</td>
    </tr>
    <tr>
      <td>+ handle(GetExpensesByBreederIdQuery query): List&lt;Expense&gt;</td>
      <td>Recupera los gastos asociados a un criador específico.</td>
    </tr>
  </tbody>
</table>


### 4.2.4.4. Infrastructure Layer

Esta sección describe la Capa de Infraestructura del contexto Management. Esta capa se encarga de la persistencia de datos, es decir, de comunicar el dominio con el sistema de almacenamiento (base de datos). 
Aquí se encuentran los repositorios JPA que permiten ejecutar operaciones CRUD de forma declarativa sobre las entidades del dominio.
</p>

<table>
  <thead>
    <tr>
      <th>Repositorio</th>
      <th>Métodos</th>
      <th>Entidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ManagementRepository</td>
      <td>findAllByCageId(), findAllByBreederId()</td>
      <td>Cage, Animal, Resource, Expense</td>
    </tr>
  </tbody>
</table>

### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

<img src="img/Management_Component_Diagram_Managment.png" alt="Management Component Diagram" style="width:100%; max-width:800px;" />

### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

<img src="img/class_diagram_management.png" alt="Class Diagram - Management" style="width:100%; max-width:800px;" />


### 4.2.4.6.2. Bounded Context Database Design Diagram

<img src="img/Database Design Diagram - Managment.png" alt="Database Design Diagram - Management" style="width:100%; max-width:1000px;" />

### 4.2.5. Bounded Context: Publication

### 4.2.5.1. Domain Layer

A continuación, se presenta la organización del Domain Layer siguiendo la estructura: Aggregate, Value Objects, Domain Services y Repositories, con todos los elementos organizados en tablas independientes.

<br>

## Aggregate

<table>
  <thead>
    <tr><th>Entidad</th><th>Atributos Clave</th><th>Métodos</th></tr>
  </thead>
  <tbody>
    <tr>
      <td> Publication </td>
      <td>
        title, description, image, advisor_id
      </td>
      <td>
        updatePublicationContent()
      </td>
    </tr>
  </tbody>
</table>

---

## Value Objects

<table>
  <thead>
    <tr><th>VO</th><th>Atributos</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>PublicationContent.java</td>
      <td>title, descrition, image</td>
      <td>Define el contenido de cada publicación</td>
    </tr>
  </tbody>
</table>

---

## Domain Services

<table>
  <thead>
    <tr><th>Servicio</th><th>Métodos</th><th>Responsabilidad</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>PublicationCommandService</td>
      <td>
        CreatePublicationCommand(),<br/>
        UpdatePublicationCommand (),<br/>
        DeletePublicationCommand()
      </td>
      <td>Este servicio define la lógica para crear, actualizar y eliminar publicaciones a partir de comandos específicos, siguiendo el patrón Command Handler en una arquitectura orientada al dominio (DDD)</td>
    </tr>
    <tr>
      <td>PublicationQueryService</td>
      <td>
        GetAllPublicationsQuery(),<br/>
        GetPublicationByIdQuery(),<br/>
        GetPublicationsByAdvisorIdQuery()
      </td>
      <td>Este servicio representa el módulo de consultas (Query Service) del patrón CQRS, y se encarga de recuperar publicaciones mediante distintos criterios (todas, por ID o por asesor), sin modificar el estado del sistema.</td>
    </tr>
  </tbody>
</table>

### 4.2.5.2. Interface Layer

En esta sección se describe la Capa de Interfaz de la plataforma AgroConnect, específicamente para la gestión de publicaciones. Se destaca el controlador PublicationsController, que permite a los asesores técnicos publicar contenido relacionado a su experiencia o conocimientos, lo cual contribuye a visibilizar su perfil profesional y atraer a potenciales criadores interesados en sus servicios.

El contexto de esta capa incluye un controlador principal: `PublicationsController`

## Controladores

<table border="1" style="width:100%; text-align:left;">
  <tr>
    <th style="width:50%;">PublicationsController</th>
  </tr>
  <tr>
    <td>
      + createPublication(resource): ResponseEntity<-PublicationResource><br/>
      + getAllPublications(): ResponseEntity<-List<-PublicationResource>><br/>
      + getPublicationById(publicationId): ResponseEntity<-PublicationResource><br/>
      + updatePublication(publicationId, resource): ResponseEntity<-PublicationResource><br/>
      + deletePublication(publicationId): ResponseEntity<br/>
    </td>
  </tr>
</table>

### 4.2.5.3. Application Layer

La Capa de Aplicación se encarga de orquestar la ejecución de los casos de uso definidos en el dominio. En esta sección se describen los servicios de comandos y consultas (handlers) que procesan los distintos flujos relacionados con la gestión de publicaciones.

---

## Handlers

<table border="1" style="width:100%; text-align:left;">
  <tr>
    <th style="width:50%;">PublicationCommandServiceImpl</th>
  </tr>
  <tr>
    <td>
      + handle(CreatePublicationCommand command): Long
    </td>
    <td>
      Crea una nueva publicación asociada a un asesor y la guarda en la base de datos.
    </td>
  </tr>
  <tr>
    <td>
      + handle(UpdatePublicationCommand command): Long
    </td>
    <td>
      Actualiza el contenido, título o imagen de una publicación existente.
    </td>
  </tr>
  <tr>
    <td>
      + handle(DeletePublicationCommand command): void
    </td>
    <td>
      Elimina una publicación del repositorio si existe.
    </td>
  </tr>
</table>

<br/>

<table border="1" style="width:100%; text-align:left;">
  <tr>
    <th style="width:50%;">PublicationQueryServiceImpl</th>
  </tr>
  <tr>
    <td>
      + handle(GetAllPublicationsQuery query): List&lt;Publication&gt;
    </td>
    <td>
      Recupera la lista completa de publicaciones registradas.
    </td>
  </tr>
  <tr>
    <td>
      + handle(GetPublicationByIdQuery query): Optional&lt;Publication&gt;
    </td>
    <td>
      Obtiene una publicación específica según su identificador único.
    </td>
  </tr>
  <tr>
    <td>
      + handle(GetPublicationsByAdvisorIdQuery query): List&lt;Publication&gt;
    </td>
    <td>
      Devuelve todas las publicaciones asociadas a un asesor técnico específico.
    </td>
  </tr>
</table>


### 4.2.5.4. Infrastructure Layer

En esta sección se describe la Capa de Infraestructura de la funcionalidad de publicaciones en la plataforma AgroConnect. Esta capa se encarga de la persistencia de datos, es decir, de comunicar el dominio con el sistema de almacenamiento (base de datos). Aquí se encuentran los repositorios JPA, que permiten ejecutar operaciones CRUD de forma declarativa sobre las entidades del dominio.

#### Repositories

<table>
  <thead>
    <tr><th>Repositorio</th><th>Métodos</th><th>Entidad</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>PublicationRepository</td>
      <td>
        findAllByAdvisorId()
      </td>
      <td>Repository</td>
    </tr>
  </tbody>
</table>

### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

<img src="img/Publication_Component_Diagram.png" alt="Read Models" width="800">

### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams

### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

<img src="img/class_diagram_publication.png" alt="Read Models" width="800">

### 4.2.5.6.2. Bounded Context Database Design Diagram

<img src="img/database_diagram_publication.png" alt="Read Models" width="800">

<br><br>
<br><br>



## Capítulo V: Solution UI/UX Design 

## 5.1. Style Guidelines

La importancia del estilo de un producto radica en la creación de una experiencia visual armoniosa y atractiva para los usuarios. A continuación, se presentará una descripción detallada de las pautas de estilo de nuestro proyecto.

### 5.1.1. General Sytle Guidelines 

**Consistencia Visual**

Garantizar una apariencia uniforme en todos los aspectos del producto, desde la disposición de la interfaz de usuario hasta los elementos visuales. Esto implica seleccionar colores coherentes, tipografía adecuada, estilos consistentes y una navegación web intuitiva.

<p align="center">
  <img src="img/consistencia-visual.webp" alt="Ejemplo de consistencia visual" width="600">
</p>

_Imagen 23. Ejemplo de consistencia visual_

**Simplicidad**

Enfatizar la simplicidad en el diseño para una experiencia de usuario intuitiva y evitar el uso excesivo de elementos que puedan hacer perder el foco de atención al usuario.

<p align="center">
  <img src="img/simplicidad.jpg" alt="Ejemplo de simplicidad" width="600">
</p>

_Imagen 24. Ejemplo de simplicidad_

**Branding**

El logotipo de AgroCuy se presenta en forma de un círculo, que simboliza la unidad y la conexión dentro de las comunidades agrícolas peruanas. En el centro del círculo se encuentra un cuy, animal característico de las granjas peruanas y un símbolo de la agricultura local. El cuy está representado de manera amigable y sonriente, transmitiendo la naturaleza acogedora y cercana de la plataforma. El cuy lleva un pequeño gorro de granjero como un guiño a la laboriosa comunidad agrícola.

<p align="center">
  <img src="img/logo.png" alt="logo de AgroCuy" width="200">
</p>

_Imagen 25. Logo de AgroCuy_

**Typography**

La tipografía elegida para AgroCuy es "Inter", una fuente sans-serif moderna y altamente legible. Este tipo de letra se destaca por su estilo limpio y contemporáneo, lo que comunica profesionalismo y actualización. La elección de Inter asegura que el texto en las interfaces de usuario sea fácilmente legible y tenga una apariencia moderna y uniforme. Además, Inter es una fuente versátil que ofrece una amplia variedad de pesos y estilos, lo que permite una adaptación flexible a diferentes contextos y tamaños de texto en la aplicación.

<p align="center">
  <img src="img/font1.png" alt="Fuentes" width="600">
</p>

_Imagen 26. Fuentes_

**Colors**

AgroCuy ha seleccionado una paleta de colores que comunica confiabilidad y eficiencia en la contratación de asesores especializados y en el uso de herramientas avanzadas. Los tonos predominantes, como los marrones, amarillos y anaranjados, transmiten una sensación cálida que evoca la calidez y la energía de la naturaleza presente en las granjas peruanas. Esta elección de colores no solo refleja la conexión con la tierra y las raíces agrícolas, sino que también sugiere un ambiente acogedor y estimulante para los usuarios de la plataforma.

**Spacing**

El spacing garantiza una distribución uniforme y un equilibrio visual en la interfaz. Se han establecido las siguientes medidas.

````
 - Botones: padding de 16px vertical y 32px horizontal 
 - Margin entre texto 16px 
 - Margin entre elementos 24px 
 - Margin entre secciones 72px
````

**Diseño Visual con Patrón Z**

 Vamos a incorporar el conocido Patrón Z en nuestro diseño visual, el cual dirige de manera intuitiva la atención del usuario a través de la interfaz. Este enfoque implica estratégicamente ubicar los elementos clave en las esquinas superior e inferior izquierdas, mientras que los elementos secundarios se colocan en las esquinas superior e inferior derechas. Este diseño genera un flujo visual eficaz y atractivo que mejora la experiencia del usuario.

<p align="center">
  <img src="img/patronZ.png" alt="Patron Z ejemplo" width="600">
</p>

_Imagen 27. Ejemplo de Patron Z_

### 5.1.2. Web, Mobile and IoT Style Guidelines

**Colors**

AgroCuy ha seleccionado cuidadosamente una paleta de colores que refleja los valores y la identidad de la plataforma. Los tonos elegidos comunican confiabilidad y eficiencia en la contratación de asesores especializados y en el uso de herramientas avanzadas.

<p align="center">
  <img src="img/colors.png" alt="Colores de AgroCuy" width="600">
</p>

_Imagen 28. Colores de AgroCuy_

**Typography**

La tipografía desempeña un papel fundamental en la apariencia y la legibilidad de AgroCuy. Hemos seleccionado cuidadosamente la fuente "Inter", una fuente sans-serif moderna y altamente legible.

<p align="center">
  <img src="img/font2.png" alt="Tipografia de AgroCuy" width="600">
</p>

_Imagen 29. Tipografia de AgroCuy_

**Icons**

Los íconos desempeñan un papel importante en la experiencia del usuario al proporcionar una representación visual rápida y reconocible de diversas funciones y características dentro de AgroCuy. Hemos seleccionado una colección de íconos que son consistentes con la identidad visual de la plataforma y que refuerzan su propósito y temática agrícola.

<p align="center">
  <img src="img/icons.png" alt="Iconos de AgroCuy" width="600">
</p>

_Imagen 30. Iconos de AgroCuy_

**Spacing**

El espaciado adecuado entre elementos es esencial para lograr una apariencia equilibrada y una experiencia de usuario cómoda en AgroCuy. Hemos establecido pautas claras de espaciado que garantizan coherencia y claridad en toda la plataforma.

<p align="center">
  <img src="img/spacing.png" alt="Spacing de AgroCuy" width="600">
</p>

_Imagen 31. Spacing de AgroCuy_

**Grid System**

El grid system es una herramienta esencial en el diseño y la organización de la interfaz de usuario de AgroCuy. Proporciona una estructura visual que ayuda a distribuir y alinear los elementos de la página de manera consistente y armoniosa en diferentes tamaños de pantalla.

<p align="center">
  <img src="img/grid.png" alt="Grid System de AgroCuy" width="600">
</p>

_Imagen 32. Grid System de AgroCuy_

**Button**

Los botones son elementos importantes en la interfaz de usuario de AgroCuy, ya que proporcionan una forma clara y visualmente destacada para que los usuarios realicen acciones importantes. Hemos definido un estilo de botón consistente que refleja la identidad visual de la plataforma y promueve una experiencia de usuario intuitiva y coherente.

<p align="center">
  <img src="img/button.png" alt="Button de AgroCuy" width="600">
</p>

_Imagen 33. Button de AgroCuy_

**Input System**

El input system es fundamental en la experiencia del usuario en AgroCuy, ya que proporciona formas para que los usuarios ingresen datos y realicen acciones dentro de la plataforma. Hemos definido un sistema de entrada consistente que garantiza una experiencia de usuario intuitiva y coherente en toda la interfaz.

<p align="center">
  <img src="img/input-system.png" alt="Input Sys AgroCuy" width="600">
</p>

_Imagen 34. Input System de AgroCuy_


## 5.2. Information Architecture

La arquitectura de información desempeña un papel fundamental en la organización y estructuración del contenido para garantizar su accesibilidad y comprensión por parte de los usuarios. En este apartado, se detallarán los sistemas de organización, etiquetado, etiquetas SEO y metaetiquetas, sistema de búsqueda y sistemas de navegación que componen la arquitectura de la información de nuestro producto.

### 5.2.1. Organization Systems

En AgroCuy, aplicamos un sistema de jerarquía visual para resaltar la información esencial y relevante, garantizando que los usuarios encuentren fácilmente lo que necesitan. Utilizamos una organización secuencial para guiar intuitivamente a los usuarios a través del proceso de registro y búsqueda de asesores o asesoría. En lo que respecta a la categorización de contenido, está organizado según audiencia (Criadores y Asesores)

### 5.2.2. Labeling Systems

En el proyecto AgroCuy se eligió implementar un sistema de etiquetado breve y fácil de comprender para los usuarios. Las etiquetas que se utilizarán son las siguientes:


**Vista de Criador:**

<table>
  <tbody>
  <tr>
      <th>My Farm - Mi Granja</th>
      <td>Se implementará un botón que permitirá a los usuarios gestionar su inventario, que incluirá medicamentos, producción de carne, fertilizante y otros elementos relacionados.</td>
  </tr>
  <tr>
      <th>Advisors - Mis asesores</th>
      <td>Se implementará un botón que permitirá a los usuarios contactar con asesores.</td>
  </tr>
  <tr>
      <th>My animals - Mis animales</th>
      <td>Se implementará un botón que permitirá al usuario llevar un registro y seguimiento de los animales en la granja.</td>
  </tr>
  <tr>
      <th>Calendar - Calendario</th>
      <td>Se implementará un botón que permitirá visualizar un calendario con las citas registradas.</td>
  </tr>
  <tr>
      <th>Registry - Registro</th>
      <td>Se implementará un botón que permitirá al usuario registrar información de nuevos animales, datos de la gastos y recursos.</td>
  </tr>
  <tr>
      <th>Notifications - Notificaciones</th>
      <td>Se implementará un botón que permitirá visualizar notificaciones respecto a las solicitudes de las ofertas de empleo.</td>
  </tr>
  <tr>
      <th>Logout</th>
      <td>Se implementará un botón que permitirá al usuario desvincularse de su cuenta.</td>
  </tr>
  </tbody>
</table>

<br></br>
**Vista de Asesor:**

<table>
  <tbody>
  <tr>
      <th>Home - Inicio</th>
      <td>Se implementará un botón que permitirá al usuario ver publicaciones de clientes y poder ofertar.</td>
  </tr>
  <tr>
      <th>My clients - Mis clientes</th>
      <td>Se implementará un botón que permitirá a los usuarios ver su clientes.</td>
  </tr>
  <tr>
      <th>My publications - Mis publicaciones</th>
      <td>Se implementará un botón que permitirá al usuario ver el historial de sus publicaciones de ofertas de trabajo.</td>
  </tr>
  <tr>
      <th>Notifications - Notificaciones</th>
      <td>Se implementará un botón que permitirá visualizar notificaciones respecto a las solicitudes de las ofertas de empleo y recordatorios de citas pendientes.</td>
  </tr>
    <tr>
      <th>Calendar - Calendario</th>
      <td>Se implementará un botón que permitirá visualizar un calendario con las citas registradas.</td>
  </tr>
  <tr>
      <th>Logout</th>
      <td>Se implementará un botón que permitirá al usuario desvincularse de su cuenta.</td>
  </tr>
</table>

### 5.2.3. SEO Tags and Meta Tags

Las Search Engine Optimization (Etiquetas SEO) y las Meta Tags (Meta Etiquetas) juegan un papel vital en la visibilidad y el posicionamiento del contenido en los motores de búsqueda. Existen varios tipos de etiquetas SEO y metaetiquetas, y a continuación se destacan algunas de las más relevantes para la empresa:

- **Metaetiqueta de Descripción (Meta Description Tag):** Esta etiqueta ofrece una breve   descripción del contenido de la página. Aunque no influye directamente en el ranking de búsqueda, una meta descripción bien redactada puede aumentar la tasa de clics (CTR) al proporcionar a los usuarios una visión clara del contenido de la página.

````
<meta name="description" content="AgroTech ofrece soluciones tecnológicas innovadoras para mejorar la gestión de granjas de cuyes. Nuestra misión es empoderar a los granjeros con herramientas inteligentes y eficientes.">
````

**Metaetiqueta de Autor (Meta Autor Tag):** Esta etiqueta especifica el autor del contenido de la página. Esto puede ser útil para atribuir la propiedad intelectual o identificar la fuente del contenido.

````
<meta name="author" content="AgroTech">
````

**Etiqueta de Título (Title Tag):** Esta etiqueta es esencial para el SEO, ya que define el título de una página web y aparece como el título principal en los resultados de búsqueda. 

````
<title>AgroCuy</title>
````

**Etiqueta de Idioma (Language Tag):** Esta etiqueta especifica el idioma principal del contenido de la página. Es útil para la clasificación en búsquedas locales y ayuda a los motores de búsqueda a comprender el idioma del contenido.

````
<html lang="en">
````

**Metaetiqueta de Robots (Meta Robots Tag):** Esta etiqueta indica a los motores de búsqueda cómo indexar y rastrear la página. Puede especificar si la página debe ser indexada, si deben seguirse los enlaces o si se deben seguir ciertas instrucciones específicas.

````
<meta name="robots" content="index, follow"> 
````

<p align="center">
  <img src="img/seotags.jpeg" alt="SEO tags" width="600">
</p>

_Imagen 35. SEO tags de AgroCuy_

### 5.2.4. Searching Systems

La aplicación AgroCuy desarrollará un sistema de búsqueda intuitivo, diseñado para que los usuarios encuentren rápidamente la información que necesitan. Este sistema se basará en filtros inteligentes que simplificarán la búsqueda de asesores, evitando así que los usuarios se vean abrumados por la cantidad de información disponible. Con esta mejora, nuestra aplicación garantizará una experiencia de usuario más fluida y satisfactoria al buscar información relevante.

<table>
  <tbody>
  <tr>
      <th>Ubicación</th>
      <td>Permite al usuario buscar asesores o recibir solicitudes de asesoramiento basadas en su ubicación actual o en una ubicación específica.</td>
  </tr>
  <tr>
      <th>Tipo de Asesoría</th>
      <td>Permite al usuario buscar según el tipo de asesoría ofrecida.</td>
  </tr>
  <tr>
      <th>Presupuesto</th>
      <td>Permite al usuario buscar asesores que se ajusten a su presupuesto.</td>
  </tr>
  <tr>
      <th>Experiencia</th>
      <td>Permite al usuario buscar asesores con un nivel de experiencia específico.</td>
  </tr>
  <tr>
      <th>Reputación</th>
      <td>Permite al usuario buscar asesores según las calificaciones obtenidas.</td>
  </tr>
  <tr>
      <th>Idioma</th>
      <td>Permite al usuario buscar según el idioma.</td>
  </tr>
  <tr>
      <th>Palabras Clave</th>
      <td>Proporciona un cuadro de búsqueda donde los usuarios pueden ingresar palabras clave específicas relacionadas con el tipo de asesoría que necesitan.</td>
  </tr>
  </tbody>
</table>

### 5.2.5. Navigation Systems

La página de inicio de AgroCuy ha sido diseñada para una experiencia fácil y completa, ofreciendo las siguientes características:

 - ***Menús de Navegación:*** Los menús de navegación son una estructura estándar que se utiliza para organizar y presentar las diversas secciones y páginas de un producto. Estos menús pueden adoptar diferentes formas, como menús desplegables, ubicados en la parte superior o lateral de una página, e incluso enlaces de navegación en el pie de página.

 - ***Navegación por Pestañas:*** Es un sistema que emplea pestañas para organizar el contenido en secciones o categorías. Esto permite a los usuarios cambiar entre las distintas secciones de contenido simplemente haciendo clic en las pestañas correspondientes, sin necesidad de cargar nuevas páginas.

## 5.3. Landing Page UI Design

En este apartado, nos enfocaremos en el diseño de la interfaz de usuario (UI) de nuestra landing page. Es crucial que los usuarios que visiten nuestra página comprendan rápidamente de qué se trata nuestro producto y qué beneficios principales ofrecemos.

### 5.3.1. Landing Page Wireframe

**Wireframe - sección de ‘Inicio’ de AgroCuy:** la sección tendrá una imagen de fondo llamativa con un mensaje que refleja el objetivo de la startup para llamar la atención de posibles usuarios.

<p align="center">
  <img src="img/wireframe-landing-about-app.png" alt="Pagina Acerca de" width="600">
</p>

_Imagen 36. Pagina Acerca de_

**Wireframe - sección de ‘Sobre Nosotros’:** la sección tendrá una imagen de fondo y tendrá información sobre la startup Agrotech junto con nuestra misión y visión.

<p align="center">
  <img src="img/wireframe-landing-about-us.png" alt="Pagina Sobre Nosotros" width="600">
</p>

_Imagen 37. Pagina Sobre Nosotros_

**Wireframe - sección de ‘Características’:** la sección tendrá una imagen de fondo y tendrá información sobre los servicios que ofrecemos con nuestra aplicación AgroCuy.

<p align="center">
  <img src="img/wireframe-landing-features.png" alt="Pagina Características" width="600">
</p>

_Imagen 38. Pagina Características_

**Wireframe - sección de ‘Contacto’:** la sección tendrá una imagen de fondo y tendrá un formulario donde los usuarios potenciales puedan escribir consultas para que sean respondidas en un correo por un miembro de AgroTech.

<p align="center">
  <img src="img/wireframe-landing-contact.png" alt="Pagina Contacto" width="600">
</p>

_Imagen 39. Pagina Contacto_

### 5.3.2. Landing Page Mock-up
**Mockup - sección de ‘Inicio’ de AgroCuy:** la sección tiene una imagen de fondo llamativa con un mensaje que refleja el objetivo de la startup para llamar la atención de posibles usuarios.

<p align="center">
  <img src="img/mockup-landing-home.png" alt="Pagina de Inicio" width="600">
</p>

_Imagen 40. Mockup Pagina Inicio_

**Mockup - sección de ‘Acerca de’:** la sección tiene una imagen de fondo y tiene información sobre la problemática que queremos resolver.

<p align="center">
  <img src="img/mockup-landing-about-app.png" alt="Página Acerca de la problemática" width="600">
</p>

_Imagen 41. Mockup Pagina Acerca de_

**Mockup - sección de ‘Sobre Nosotros’:** la sección tiene una imagen de fondo y tiene información sobre la startup Agrotech junto con nuestra misión y visión.

<p align="center">
  <img src="img/mockup-landing-about-us.png" alt="Pagina Sobre Nosotros" width="600">
</p>

_Imagen 42. Mockup Pagina Sobre Nosotros_

**Mockup - sección de ‘Características’:** la sección tiene una imagen de fondo y tiene información sobre los servicios que ofrecemos con nuestra aplicación AgroCuy.

<p align="center">
  <img src="img/mockup-landing-features.png" alt="Pagina de Características" width="600">
</p>

_Imagen 43. Mockup Pagina de Características_

**Mockup - sección de ‘Contacto’:** la sección tiene una imagen de fondo y tiene un formulario donde los usuarios potenciales pueden escribir consultas para que sean respondidas en un correo por un miembro de AgroTech.

<p align="center">
  <img src="img/mockup-landing-contact.png" alt="Pagina de Contacto" width="600">
</p>

_Imagen 44. Mockup Pagina de Contacto_

## 5.4. Applications UX/UI Design

### 5.4.1. Applications WireFrames

### Web Application:

<img src="img/wireframe-webapp-signup.png" alt="Wireframe Registro Usuario" width="600">
<img src="img/wireframe-webapp-review.png" alt="Wireframe Reseñas" width="600">
<img src="img/wireframe-webapp-myanimals.png" alt="Wireframe Mis Animales" width="600">
<img src="img/wireframe-webapp-advisor.png" alt="Wireframe Página Principal Asesor" width="600">
<img src="img/wireframe-webapp-review-animal.png" alt="Wireframe Reseña Animal" width="600">
<img src="img/wireframe-webapp-register.png" alt="Wireframe Registro General" width="600">
<img src="img/wireframe-webapp-register-resource.png" alt="Wireframe Registro Recurso" width="600">
<img src="img/wireframe-webapp-no-review.png" alt="Wireframe Sin Reseña" width="600">
<img src="img/wireframe-webapp-register-cuy.png" alt="Wireframe Registro Cuy" width="600">
<img src="img/wireframe-webapp-advisor-notifications.png" alt="Wireframe Notificaciones Asesor" width="600">
<img src="img/wireframe-webapp-advisor-clients.png" alt="Wireframe Clientes Asesor" width="600">
<img src="img/wireframe-webapp-advisor-notifications-new.png" alt="Wireframe Notificaciones Nuevas" width="600">
<img src="img/wireframe-webapp-advisor-publication.png" alt="Wireframe Publicación Asesor" width="600">

### Mobile Application

<img src="img/wireframe-mobile-loginandregister.png" alt="Wireframe Login y Registro Móvil" width="600">
<img src="img/wireframe-mobile-publication.png" alt="Wireframe Publicación Móvil" width="600">
<img src="img/wireframe-mobile-calendar.png" alt="Wireframe Calendario Móvil" width="600">
<img src="img/wireframe-mobile-advisor.png" alt="Wireframe Página Principal Asesor" width="600">
<img src="img/wireframe-mobile-notifications.png" alt="Wireframe Notificaciones Móvil" width="600">
<img src="img/wireframe-mobile-dates.png" alt="Wireframe Fechas Móvil" width="600">
<img src="img/wireframe-mobile-publication-advisor.png" alt="Wireframe Publicación Asesor" width="600">
<img src="img/wireframes-mobile-schedule-advisor.png" alt="Wireframe Horario Asesor" width="600">
<img src="img/wireframe-mobile-notifications-advisor.png" alt="Wireframe Notificaciones Asesor" width="600">
<img src="img/wireframe-mobile-calendar-advisor.png" alt="Wireframe Calendario Asesor" width="600">

### 5.4.2. Applications WireFlow Diagrams

<img src="img/wireflow-app-usergoal1.png" alt="Wireframe User Goal 1" width="600">
<img src="img/wireflow-app-usergoal2.png" alt="Wireframe User Goal 2" width="600">
<img src="img/wireflow-app-usergoal3.png" alt="Wireframe User Goal 3" width="600">
<img src="img/wireflow-app-usergoal4.png" alt="Wireframe User Goal 4" width="600">
<img src="img/wireflow-app-usergoal5.png" alt="Wireframe User Goal 5" width="600">
<img src="img/wireflow-app-usergoal6.png" alt="Wireframe User Goal 6" width="600">
<img src="img/wireflow-app-usergoal7.png" alt="Wireframe User Goal 7" width="600">
<img src="img/wireflow-app-usergoal8.png" alt="Wireframe User Goal 8" width="600">
<img src="img/wireflow-app-usergoal9.png" alt="Wireframe User Goal 9" width="600">
<img src="img/wireflow-app-usergoal10.png" alt="Wireframe User Goal 10" width="600">
<img src="img/wireflow-app-usergoal11.png" alt="Wireframe User Goal 11" width="600">
<img src="img/wireflow-app-usergoal12.png" alt="Wireframe User Goal 12" width="600">
<img src="img/wireflow-app-usergoal13.png" alt="Wireframe User Goal 13" width="600">
<img src="img/wireflow-app-usergoal14.png" alt="Wireframe User Goal 14" width="600">
<img src="img/wireflow-app-usergoal15.png" alt="Wireframe User Goal 15" width="600">
<img src="img/wireflow-app-usergoal16.png" alt="Wireframe User Goal 16" width="600">
<img src="img/wireflow-app-usergoal17.png" alt="Wireframe User Goal 17" width="600">

### 5.4.3. Applications Mock-ups.

### Web Application:
  <img src="img/mockup-webapp-signup.png" alt="Pagina de Registro" width="600">
  <img src="img/mockup-webapp-myanimals.png" alt="Pagina de Cuy" width="600">
  <img src="img/mockup-webapp-review.png" alt="Pagina de Reseña" width="600">
  <img src="img/mockup-webapp-advisor.png" alt="Pagina de Asesor" width="600">
  <img src="img/mockup-webapp-register.png" alt="Pagina de Registro" width="600">
  <img src="img/mockup-webapp-review-advisor.png" alt="Pagina de Registro Asesor" width="600">
  <img src="img/mockup-webapp-resource-register.png" alt="Pagina de Recurso Registro" width="600">
  <img src="img/mockup-webapp-no-clients.png" alt="Pagina de No Clientes" width="600">
  <img src="img/mockup-webapp-publication.png" alt="Pagina de Publicacion" width="600">
  <img src="img/mockup-webapp-no-resources-register.png" alt="Pagina de Recursos no registrados" width="600">
  
### IoT Application:
  <img src="img/mockup-iot.png" alt="Pagina de IoT" width="600">

### Mobile Application:

### Breeder:

 <img src="img/mockup-mobile-loginandregister.png" alt="Pagina de Criador" width="600">
 <img src="img/mockup-mobile-publication.png" alt="Pagina de Criador" width="600">
 <img src="img/mockup-mobile-calendar.png" alt="Pagina de Criador" width="600">
 <img src="img/mockup-mobile-advisor.png" alt="Pagina de Criador" width="600">
 <img src="img/mockup-mobile-notifications.png" alt="Pagina de Criador" width="600">
 
<br>

### Advisor:

<img src="img/mockup-mobile-dates.png" alt="Pagina de Asesor" width="600">
<img src="img/mockup-mobile-publication-advisor.png" alt="Pagina de Asesor" width="600">
<img src="img/mockup-mobile-schedule-advisor.png" alt="Pagina de Asesor" width="600">
<img src="img/mockup-mobile-notifications-advisor.png" alt="Pagina de Asesor" width="600">
<img src="img/mockup-mobile-calendar-advisor.png" alt="Pagina de Asesor" width="600">


### 5.4.4. Applications User Flow Diagrams
Cabe mencionar que los happy paths son representados por cuadros amarillos, mientras que los unhappy paths se identifican por los cuadros con tonalidad rojiza.

Cabe mencionar que los happy paths son representados por cuadros amarillos, mientras que los unhappy paths se identifican por los cuadros con tonalidad rojiza.

**Para usuario:**

<img src="img/userflow1.png" alt = "userflow 1">

_Imagen 88. usuario - inicio sesion_

<img src="img/userflow3.png" alt = "userflow 3">

_Imagen 89. usuario - recuperar contraseña_

**Para asesor:**

<img src="img/userflow2.png" alt = "userflow 2">

_Imagen 90. asesor - registro_

<img src="img/userflow4.png" alt = "userflow 4">

_Imagen 91. asesor - visualizar clientes_

<img src="img/userflow5.png" alt = "userflow 5">

_Imagen 92. asesor - crear publicaciones_

<img src="img/userflow6.png" alt = "userflow 6">

_Imagen 93. asesor - recibir notificaciones_

**Para criador:**

<img src="img/userflow7.png" alt = "userflow 7">

_Imagen 94. criador - registrar jaulas_

<img src="img/userflow8.png" alt = "userflow 8">

_Imagen 95. criador - registrar cuyes_

<img src="img/userflow9.png" alt = "userflow 9">

_Imagen 96. criador - registrar gastos_

<img src="img/userflow10.png" alt = "userflow 10">

_Imagen 97. criador - registrar recursos_

<img src="img/userflow11.png" alt = "userflow 11">

_Imagen 98. criador - modificar informacion jaulas_

<img src="img/userflow12.png" alt = "userflow 12">

_Imagen 99. criador - eliminar jaulas_

<img src="img/userflow13.png" alt = "userflow 13">

_Imagen 100. criador - ver en que jaulas pertencen cuyes_

<img src="img/userflow14.png" alt = "userflow 14">

_Imagen 101. criador - eliminar registro cuy_

<img src="img/userflow15.png" alt = "userflow 15">

_Imagen 102. criador - editar registro cuy_

<img src="img/userflow16.png" alt = "userflow 16">

_Imagen 103. criador - buscar asesores_

<img src="img/userflow17.png" alt = "userflow 17">

_Imagen 104. criador - calificar asesoria_

## 5.5. Applications Prototyping

A partir de los User Flows definidos en el punto anterior, se trabajó el prototipo funcional en Figma.
<img src="img/prototipo.png" alt="Prototipo" width="600">


# Capítulo VI Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management.

### 6.1.1. Software Development Environment Configuration.

**Project Management:**

Para la gestión del proyecto, utilizamos como principal medio de comunicación WhatsApp, a través de un grupo en el cual compartimos nuestras ideas y opiniones sobre cada parte del trabajo. A esto se le suma el uso de la herramienta Google Meet, para realizar reuniones en videoconferencia y conversar de forma síncrona. Por otro lado, el proyecto también tiene que ser documentado con todos los puntos requeridos, por lo que utilizamos Google Drive para la creación de documentos compartidos y trabajar de forma colaborativa, permitiendo un mejor flujo de trabajo y tener un historial sobre lo que realizó cada uno. Asimismo, utilizamos GitHub para el manejo de repositorios a través de una comunidad conformada por todos los integrantes del equipo. En esta, también documentamos los reportes y la aplicación en sí.

**Requirements Management:**

Para el registro de los requisitos, o también llamadas historias de usuario, utilizamos la herramienta Pivotal Tracker, en la cual registramos cada una de ellas y ordenadas por prioridad según el Product Backlog. La realización de este fue grupal, todos los integrantes aportamos en las historias de usuario y discutimos sobre las principales funcionalidades que consideramos que debe tener la aplicación web.

**Product UX/UI Design:**

Se realizaron los productos de UX con la herramienta UXPressia, así como el User Persona, Empathy Mapping, Impact Mapping, entre otras. Gracias a esto pudimos modelar bien los diseños de la experiencia de usuario, lo cual nos sirve para poder ponernos en una mejor perspectiva para nuestros segmentos objetivo. Por otro lado, hicimos los prototipos de la aplicación web utilizando la herramienta Figma, la cual nos permitió crear los Wireframes y Mock-ups para tener un diseño previo al desarrollo de la aplicación.

**Software Development:**

Como principal IDE, utilizamos Visual Studio Code, el cual es el entorno de desarrollo con el que estamos más familiarizados, además que ofrece flexibilidad, facilidad de uso y una gran variedad de soporte de lenguajes de programación. Además, permite la conexión con repositorios en línea creados en GitHub, lo cual nos permite tener una mejor gestión del proyecto, así como el historial de todos los cambios realizados. En la otra mano, para el desarrollo usamos los lenguajes aprendidos previamente, como HTML, CSS y JavaScript, y nuevos conocimientos adquiridos este ciclo como el framework de AngularJS.

**Software Testing:**

Las pruebas de aceptación son importantes a realizar para comprobar que los criterios de aceptación planteados están favoreciendo a las necesidades del negocio y cumplir con los requerimientos, para lo cual utilizamos el lenguaje Gherkin. Este consiste en trabajar el escenario con Given When Then, y lograr identificar las variables de input y output, lo cual es sencillo de entender para todos ya que utiliza lenguaje natural. Gracias a este, es que se logra garantizar la calidad del software, por ello cumple un papel esencial en los proyectos de desarrollo.

### 6.1.2. Source Code Management.

**Usuarios de GitHub**

<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Integrante</th>
      <th>Usuario de GitHub</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Jarama Peñaloza, Fiorella</td>
      <td>Fio0407</td>
    </tr>
    <tr>
      <td>Moreno Vergara, Johan</td>
      <td>JohanMV</td>
    </tr>
    <tr>
      <td>Lucas Coronel, Nadia Alessandra</td>
      <td>nad21lc</td>
    </tr>
    <tr>
      <td>Paredes Puente, Sebastián Roberto</td>
      <td>yorusaurio</td>
    </tr>
    <tr>
      <td>Cuadros Rodríguez, Juan Alejandro</td>
      <td>JuanAlejandroCuadrosRodriguez</td>
    </tr>
  </tbody>
</table>

<br>

<p><em><strong>URL de repositorio de Landing Page:</strong></em> 
  <a href="https://github.com/IoT-AgroConnect/Landing-Page-Main" target="_blank">https://github.com/IoT-AgroConnect/Landing-Page-Main</a>
</p>

<p><em><strong>URL de repositorio de Frontend Web Application:</strong></em> 
  <a href="https://github.com/IoT-AgroConnect/Frontend-Web-Application" target="_blank">https://github.com/IoT-AgroConnect/Frontend-Web-Application</a>
</p>

<p><em><strong>URL de repositorio de Project Report:</strong></em> 
  <a href="https://github.com/IoT-AgroConnect/Project-Report" target="_blank">https://github.com/IoT-AgroConnect/Project-Report</a>
</p>

<p><em><strong>URL de repositorio de Acceptance Tests:</strong></em> 
  <a href="https://github.com/IoT-AgroConnect/Acceptance-Tests" target="_blank">https://github.com/IoT-AgroConnect/Acceptance-Tests</a>
</p>

<p><em><strong>URL de repositorio de Web Services:</strong></em> 
  <a href="https://github.com/IoT-AgroConnect/Web-Services-main" target="_blank">https://github.com/IoT-AgroConnect/Web-Services-main</a>
</p>

<p><em><strong>URL de repositorio de Mobile App:</strong></em> 
  <a href="https://github.com/IoT-AgroConnect/AgroCuy-mobileApp" target="_blank">https://github.com/IoT-AgroConnect/AgroCuy-mobileApp</a>
</p>


### 6.1.3. Source Code Style Guide & Conventions.

HTML

Es el lenguaje utilizado para estructurar el contenido de una página web, brindando una variedad de elementos posibles como texto, imágenes, formularios, etc.
🔗 Guía de HTML5

    Declarar el tipo de documento en la primera línea con <!DOCTYPE html>.

    Respetar la estructura básica del HTML: <html>, <head>, <body>.

    Declarar el título de la página para dar a conocer al usuario en qué página se encuentra. (Usar el elemento <title> en <head>).

    Usar indentación coherente para lograr una lectura sencilla del código.

    Siempre cerrar los elementos que lo requieran. (Ejemplo: <div> debe cerrarse con </div>).

    Declarar el atributo alt para las imágenes.

CSS

Es el lenguaje utilizado para definir el diseño de la página web, así como los estilos, fuentes, colores, contenedores, etc.
🔗 Guía de CSS de Google

    Usar indentación de forma correcta.

    Los nombres para elementos deben ser cortos y en minúsculas.

    Declarar los colores en código hexadecimal. (Ejemplo: #024A86).

    Dejar comentarios que indiquen el propósito del estilo y su uso.

    El diseño debe ser responsive para que los usuarios puedan visualizar el sitio cómodamente desde cualquier dispositivo.

JavaScript

Es el lenguaje de programación más utilizado para la programación web, ya que permite desarrollar páginas interactivas con animaciones agradables para los usuarios.
🔗 Guía de convenciones en JavaScript

    Declarar nombres coherentes y cortos para variables y funciones.

    Comentar cada parte importante del código.

    Siempre colocar un punto y coma ; al final de cada línea.

    Usar const para valores que no cambian.

    Usar comparación estricta (=== en lugar de ==).

TypeScript

Es el superconjunto de JavaScript que añade características como el tipado estático.
🔗 Documentación oficial de TypeScript

    Nombres significativos y consistentes para variables y funciones.

    Declarar interfaces y tipos en PascalCase.

    Declarar variables y funciones en camelCase.

    Comentar claramente el propósito de cada bloque de código.

    Usar interfaces para reutilización de código.

Java

Lenguaje usado para programación web y móvil, multiplataforma.
🔗 Guía de estilo para Java

    Usar CamelCase para clases, variables y funciones.

    Usar HTTPS para conexiones seguras.

    Indentación clara y ordenada.

    Usar comillas dobles (") para cadenas de texto.

    Comentar bloques de código.

    Declarar constantes si el valor no cambia.

Gherkin

Lenguaje para diseñar casos de prueba en base a requisitos de negocio.
🔗 Convenciones de Gherkin

    Separar bloques: Given, When, Then para claridad.

    Usar tablas para inputs y outputs cuando sea necesario.

    Separar escenarios múltiples con líneas en blanco.

    Insertar líneas en blanco dentro de cada Step para mejor lectura.

### 6.1.4. Software Deployment Configuration.

Para la configuración del despliegue de la aplicación, utilizaremos Git, un sistema de control de versiones distribuido que es bastante utilizado en proyectos de desarrollo de software. Es una herramienta esencial para trabajar colaborativamente y poder hacer el seguimiento de los cambios realizados por los miembros del grupo. Una de sus mejores ventajas es su capacidad para rastrear los cambios en los archivos de un proyecto a lo largo del tiempo. Con Git, es posible crear ramas, realizar cambios en ellas y fusionarlos eficientemente, permitiendo que varios desarrolladores trabajen en diferentes aspectos del proyecto simultáneamente sin interferencias.

Por otro lado, tenemos a GitHub, el cual es la plataforma para poder alojar repositorios de Git. Es uno de los servicios más utilizados por desarrolladores de forma mundial, ya que permite manejar repositorios públicos y privados para almacenar el código en la nube. A parte de ello, maneja el historial de los repositorios, permitiendo a los usuarios acceder a todas las versiones trabajadas, permitiendo que puedan retornar a una versión anterior en caso lo deseen. Ofrece otras herramientas que son muy útiles como los pull requests, los cuales son solicitudes de revisiones de una rama y luego poder fusionarla con otra rama.

Así es como con este, que cada miembro podrá trabajar de forma remota desde su IDE, teniendo una copia del repositorio Git a través del repositorio en línea almacenado en GitHub, así poder hacer commits para empujar los cambios que hayan realizado.

## 6.2. Landing Page, Services & Applications Implementation.

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning

La planificación del primer sprint se llevó a cabo mediante una reunión virtual a través de Google Meet. Durante esta sesión, el equipo acordó los objetivos del sprint, estimó las historias de usuario y definió la capacidad de trabajo (*velocity*) para el periodo. La siguiente tabla resume la información discutida y registrada durante dicha sesión.

| **Elemento** | **Detalle** |
|--------------|-------------|
| **Sprint #** | Sprint 1 |
| **Sprint Planning Background** | Planificación inicial del proyecto AgroCuy, priorizando la entrega de interfaces clave tanto en la landing page como en la primera versión funcional del frontend web. |
| Fecha | 2025-05-01 |
| Hora | 10:00 PM |
| Lugar | Virtual (Google Meet) |
| Preparado por | Lucas Coronel, Nadia Alessandra |
| Participantes de la reunión de planificación | - Cuadros Rodríguez, Juan Alejandro<br> - Jarama Peñaloza, Fiorella<br> - Lucas Coronel, Nadia Alessandra<br> - Moreno Vergara, Johan Raúl<br> - Ramírez Méndez, Sebastián André |
| Resumen del Sprint n–1 (Review) | No aplica — este es el primer sprint del proyecto. |
| Resumen del Sprint n–1 (Retrospectiva) | No aplica — este es el primer sprint del proyecto. |
| **Sprint Goal & User Stories** | Nuestro objetivo para este Sprint 1 es entregar una **primera versión de la Landing Page** y el **Frontend Web Application de AgroCuy**, que permitan comunicar de manera clara la propuesta de valor de la plataforma, facilitar la interacción entre criadores y asesores, e implementar las funcionalidades base del sistema. Esto incluirá componentes clave como Navbar, Footer, secciones informativas (Inicio, Acerca de, Características, Contacto), así como los primeros módulos de gestión de asesores, publicaciones, animales, jaulas y recursos. El éxito del sprint se evaluará mediante la validación visual, funcional y la ejecución de pruebas de aceptación automatizadas. |
| Velocidad del Sprint (Story Points esperados) | 72 |
| Suma total de Story Points asignados | 72 |


#### 6.2.1.2. Aspect Leaders and Collaborators

Durante este primer sprint, el equipo se organizó según los aspectos clave identificados en el desarrollo de la **Landing Page estática** del sistema AgroCuy. Cada aspecto (o feature) fue asignado con un miembro responsable como **líder (L)** y uno o más **colaboradores (C)** para facilitar el trabajo colaborativo, promover la responsabilidad compartida y optimizar la comunicación.

Los aspectos considerados en este sprint fueron:

- **Navbar & Footer**
- **Sección de Inicio**
- **Acerca De**
- **Sobre Nosotros**
- **Características**
- **Contacto**

A continuación, se presenta la matriz Leadership-and-Collaboration (LACX):

| **Team Member (Last Name, First Name)** | **GitHub Username** | **Navbar & Footer** | **Inicio** | **Acerca De** | **Sobre Nosotros** | **Características** | **Contacto** |
|----------------------------------------|----------------------|----------------------|------------|----------------|----------------------|----------------------|--------------|
| Lucas Coronel, Nadia Alessandra        | nad21lc           | L                    | L          | C              | C                    |                      |              |
| Ramírez Mendez, Sebastián Andre        | yorusaurio          | C                    |            | L              | C                    |                      |              |
| Cuadros Rodriguez, Juan Alejandro      | JuanAlejandroCuadrosRodriguez          |                      |            | C              | L                    | C                    |              |
| Moreno Vergara, Johan Raúl             | JohanMV          |                      |            |                |                      | L                    | C            |
| Jarama Peñaloza, Fiorella              | Fio0407       |                      |            |                |                      | C                    | L            |

> La asignación de líderes y colaboradores se alinea directamente con la distribución de tareas en el Sprint Backlog, garantizando coherencia entre la planificación y la ejecución técnica.


#### 6.2.1.3. Sprint Backlog 1

Durante el Sprint 1, se definió como objetivo principal la implementación de la **Landing Page estática** del sistema AgroCuy. Para gestionar eficientemente los ítems de trabajo, se utilizó una **tabla colaborativa en Trello**, la cual permitió asignar tareas, estimar el esfuerzo requerido y dar seguimiento al estado de cada actividad.

🔗 [Sprint Backlog 1 en Trello](https://trello.com/b/AtaOZblV/sprint-backlog-1)

<img src="img/sprintBacklog.jpg" width="100%">

*Imagen 118. Sprint Backlog 1 gestionado en Trello*

---

A continuación, se presenta la tabla estructurada del Sprint Backlog 1, que detalla las **User Stories**, sus respectivos **Tasks**, estimaciones y responsables:

<table>
  <tr>
  <th valign="top">Sprint #</th>
  <th colspan="7" valign="top">Sprint 1</th>
</tr>
<tr>
  <td colspan="2" valign="top">User Story</td>
  <td colspan="6" valign="top">Work-Item / Task</td>
</tr>
<tr>
  <td valign="top">Id</td>
  <td valign="top">Title</td>
  <td valign="top">Id</td><td valign="top">Title</td>
  <td valign="top">Description</td>
  <td valign="top">Estimation</td><td valign="top">Assigned To</td>
  <td valign="top">Status (To-Do / In-Process / Review / Done)</td>
</tr>
<tr>
  <td rowspan="2" valign="top">US22</td>
  <td rowspan="2" valign="top">Visualización de Navbar y Footer</td>
  <td valign="top">TS01</td>
  <td valign="top">Implementación de Navbar</td>
  <td valign="top">Se implementa el navbar de forma responsive.</td>
  <td rowspan="2" valign="top">2</td>
  <td valign="top">Fiorella Jarama</td><td valign="top">Done</td>
</tr>
<tr>
  <td valign="top">TS02</td>
  <td valign="top">Implementación de Footer</td>
  <td valign="top">Se implementa el footer de forma responsive.</td>
  <td valign="top">Fiorella Jarama</td>
  <td valign="top">Done</td>
</tr>
<tr><td valign="top">US23</td><td valign="top">Visualización de sección de inicio</td><td valign="top">TS03</td><td valign="top">Implementación de página de inicio</td><td valign="top">Se implementa la página de inicio de forma responsive y con su archivo css correspondiente.</td><td valign="top">1</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td></tr>
<tr><td valign="top">US24</td><td valign="top">Visualización de sección “Acerca De”</td><td valign="top">TS04</td><td valign="top">Implementación de sección Acerca De</td><td valign="top">Se implementa la página Acerca De, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Sebastián Ramirez</td><td valign="top">Done</td></tr>
<tr><td valign="top">US25</td><td valign="top">Visualización de sección “Sobre Nosotros”</td><td valign="top">TS05</td><td valign="top">Implementación de sección Sobre Nosotros</td><td valign="top">Se implementa la página Sobre Nosotros, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Juan Cuadros</td><td valign="top">Done</td></tr>
<tr><td valign="top">US26</td><td valign="top">Visualización de sección “Características”</td><td valign="top">TS06</td><td valign="top">Implementación de sección Características</td><td valign="top">Se implementa la página Características, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td></tr>
<tr><td valign="top">US27</td><td valign="top">Visualización de sección “Contacto”</td><td valign="top">TS07</td><td valign="top">Implementación de sección Contacto</td><td valign="top">Se implementa la página Contacto, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Johan Moreno</td><td valign="top">Done</td></tr>
</table>

<table>
    <tr>
      <td valign="top">US01</td><td valign="top">Visualización de catálogo de asesores</td><td valign="top">TS01</td><td valign="top">Implementación de búsqueda de asesores</td><td valign="top">Se implementa el componente para la búsqueda de asesores para los criadores.</td><td valign="top">5</td>
      <td valign="top">Juan Cuadros</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US02</td><td valign="top">Visualización de información de un asesor</td><td valign="top">TS02</td><td valign="top">Implementación de vista de información de un asesor</td><td valign="top">Se implementa el componente con la vista de información de un asesor.</td><td valign="top">3</td><td valign="top">Juan Cuadros</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US03</td><td valign="top">Visualización de horarios de asesores</td><td valign="top">TS03</td><td valign="top">Implementación de vista de horarios</td><td valign="top">Se implementa el componente con la vista de los horarios disponibles del asesor.</td><td valign="top">3</td>
      <td valign="top">Juan Cuadros</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US04</td><td valign="top">Programación de citas con asesores</td><td valign="top">TS04</td><td valign="top">Implementación de vista para programar cita</td><td valign="top">Se implementa la vista para programar una cita con un asesor.</td><td valign="top">8</td>
      <td valign="top">Juan Cuadros</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US05</td><td valign="top">Visualización de información del criador de cuyes</td><td valign="top">TS05</td><td valign="top">Implementación de detalles de cita</td><td valign="top">Se implementa la página para visualizar los datos del criador previa a la cita.</td><td valign="top">5</td>
      <td valign="top">Fiorella Jarama</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="2">US06</td><td valign="top" rowspan="2">Notificación de citas al asesor</td><td valign="top">TS06</td><td valign="top">Implementación de visualización de notificaciones al asesor</td><td valign="top">Se implementa el componente que muestra la vista de notificaciones para los asesores.</td><td valign="top" rowspan="2">3</td>
      <td valign="top">Fiorella Jarama</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS07</td><td valign="top">Implementación de eliminación de notificaciones al asesor</td><td valign="top">Se implementa la función que permite eliminar una notificación.</td><td valign="top">Fiorella Jarama</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="3">US07</td><td valign="top" rowspan="3">Notificación de citas al criador</td><td valign="top">TS08</td><td valign="top">Implementación de visualización de notificaciones al criador</td><td valign="top">Se implementa el componente que muestra la vista de notificaciones para los criadores.</td><td valign="top" rowspan="3">3</td>
      <td valign="top">Nadia Lucas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS09</td><td valign="top">Implementación de eliminación de notificaciones al criador</td><td valign="top">Se implementa la función que permite eliminar una notificación.</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS10</td><td valign="top">Implementación de Pantalla de Resultados Vacíos</td><td valign="top">Se implementa un componente que recibe un mensaje como parámetro y permite mostrar una vista cuando no se encuentren datos disponibles.</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US08</td><td valign="top">Calificación al asesor luego de una cita</td><td valign="top">TS11</td><td valign="top">Implementación de registro de calificación del asesor</td><td valign="top">Se implementa la funcionalidad en el componente para registrar la calificación del asesor brindada por el criador.</td><td valign="top">5</td>
      <td valign="top">Juan Cuadros</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="2">US09</td>
      <td valign="top" rowspan="2">Gestión de una publicación</td>
      <td valign="top">TS12</td>
      <td valign="top">Implementación de creación de publicaciones</td>
      <td valign="top">Se implementa el componente para crear nuevas publicaciones</td>
      <td valign="top" rowspan="2">2</td>
      <td valign="top">Fiorella Jarama</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS13</td>
      <td valign="top">Implementación de eliminación de publicaciones</td>
      <td valign="top">Se implementa la función dentro del componente de publicaciones para eliminar una publicación</td>
      <td valign="top">Fiorella Jarama</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US10</td><td valign="top">Visualización de publicaciones de asesores</td><td valign="top">TS14</td><td valign="top">Implementación de visualización de publicaciones</td><td valign="top">Se implementa el componente para visualizar publicaciones de asesores para el criador.</td><td valign="top">3</td>
      <td valign="top">Fiorella Jarama</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="3">US11</td><td valign="top" rowspan="3">Gestión de jaulas de cuyes</td><td valign="top">TS15</td><td valign="top">Implementación de registro de una jaula</td><td valign="top">Se implementa el componente para registrar una nueva jaula de cuyes.</td><td valign="top" rowspan="3">3</td><td valign="top">Sebastian Ramirez</td><td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">TS16</td><td valign="top">Implementación de edición de una jaula</td><td valign="top">Se implementa la función que permite editar la información de una jaula.</td><td valign="top">Johan Moreno</td><td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">TS17</td><td valign="top">Implementación de eliminación de una jaula</td><td valign="top">Se implementa la función que permite eliminar una jaula junto a la información de los cuyes que habitan en ella.</td><td valign="top">Johan Moreno</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US12</td><td valign="top">Registro de información de animales</td><td valign="top">TS18</td><td valign="top">Implementación de registro de un cuy</td><td valign="top">Se implementa el componente para registrar un cuy en una jaula existente.</td><td valign="top">3</td><td valign="top">Sebastian Ramirez</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td rowspan="2" valign="top">US13</td>
      <td rowspan="2" valign="top">Visualización y edición de información de animales</td>
      <td valign="top">TS19</td>
      <td valign="top">Implementación de vista de información de animales</td>
      <td valign="top">Se implementa el componente para visualizar las jaulas y el componente para visualizar la información de los cuyes.</td>
      <td valign="top" rowspan="2">5</td><td valign="top">Johan Moreno</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS20</td><td valign="top">Implementación de edición de información de animales</td><td valign="top">Se implementa la edición dentro de la componente de jaula, así como la edición para la componente de información de un cuy.</td><td valign="top">Johan Moreno</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td rowspan="2" valign="top">US15</td>
      <td rowspan="2" valign="top">Gestión de recursos de la granja</td>
      <td valign="top">TS22</td>
      <td valign="top">Implementación de registro de recurso</td>
      <td valign="top">Se implementa el componente para registrar un recurso para el criador.</td>
      <td valign="top" rowspan="2">5</td><td valign="top">Sebastian Ramirez</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS23</td>
      <td valign="top">Implementación de vista de recursos</td>
      <td valign="top">Se implementa el componente para la vista de los recursos del criador</td>
      <td valign="top">Nadia Lucas</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td rowspan="2" valign="top">US16</td>
      <td rowspan="2" valign="top">Gestión de gastos realizados</td>
      <td valign="top">TS24</td>
      <td valign="top">Implementación de registro de gasto</td>
      <td valign="top">Se implementa el componente para registrar un gasto para el criador.</td>
      <td valign="top" rowspan="2">5</td>
      <td valign="top">Sebastian Ramirez</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS25</td>
      <td valign="top">Implementación de vista de gastos</td>
      <td valign="top">Se implementa el componente para la vista de los recursos del criador.</td>
      <td valign="top">Nadia Lucas</td>
      <td valign="top">Done</td>
    </tr>
</table>



### 6.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo avanzó en dos frentes de desarrollo: la **Landing Page del sistema AgroCuy**, orientada a presentar la propuesta de valor del proyecto, y la **primera versión del Frontend Web Application**, que implementa la lógica funcional de las historias de usuario correspondientes.

A continuación, se presentan los commits más representativos del trabajo realizado, organizados por repositorio:

---

#### 🔹 Repositorio: [Landing Page AgroCuy](https://github.com/IoT-AgroConnect/Landing-Page-Main)

| **Repository**                      | **Branch**               | **Commit ID** | **Commit Message**                                     | **Committed on (Date)** |
|------------------------------------|---------------------------|----------------|----------------------------------------------------------|--------------------------|
| IoT-AgroConnect/Landing-Page-Main  | feature/us23              | d66396a        | Merge pull request #8 from IoT-AgroConnect/feature/us23 | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us23              | 87299dd        | Merge branch 'developer' into feature/us23              | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/about-app         | 7ab288d        | feat: added about-app section                           | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us25              | 72c9bf9        | feat: added about-us section and contact                | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us26-us23         | 019861c        | feat: added features section and home section           | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/iot-api-setup     | c16aaee        | feat: initial setup for IoT API integration             | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us11              | 44fbb57        | feat: added jaula registration view                     | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us01              | 3f404b3        | feat: added catalog view of advisors                    | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | developer                 | 6e19647        | Merge pull request #7 from IoT-AgroConnect/developer    | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us27              | b736b92        | Merge pull request #6 from IoT-AgroConnect/feature/us27 | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us22              | 9880e9b        | Merge pull request #5 from IoT-AgroConnect/feature/us22 | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/contact           | dbf8041        | feat: added contact section styles                      | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/contact           | ef55992        | feat: added contact section logic                       | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/home              | d656cea        | feat: added home section styles                         | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/home              | d889fe8        | feat: added home section logic                          | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/footer            | 1521326        | feat: added footer styles                               | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/navbar            | 2c9d256        | feat: added navbar styles                               | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/navbar            | 78926e7        | feat: added navbar logic                                | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/footer            | e1a5724        | feat: added footer                                      | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us26              | 4076edf        | Merge pull request #4 from IoT-AgroConnect/feature/us26 | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us26              | 9e8b818        | feat: added features section                            | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us24              | 96e0aaa        | Merge pull request #3 from IoT-AgroConnect/feature/us24 | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us24              | 946ece5        | fix: our team description                               | 2025-05-14               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us23              | 447fed2        | Merge pull request #2 from IoT-AgroConnect/feature/us23 | 2025-05-13               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us23              | c062114        | feat: added home section                                | 2025-05-13               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us25              | 2fdf6b4        | Merge pull request #1 from IoT-AgroConnect/feature/us25 | 2025-05-13               |
| IoT-AgroConnect/Landing-Page-Main  | feature/us25              | a6bc2c7        | feat: added about-us section                            | 2025-05-13               |


---

#### 🔹 Repositorio: [Frontend Web Application AgroCuy](https://github.com/IoT-AgroConnect/Frontend-Web-Application)

| **Repository** | **Branch**                    | **Commit ID** | **Commit Message**                                                             | **Committed on (Date)** |
|----------------|-------------------------------|---------------|---------------------------------------------------------------------------------|--------------------------|
| Frontend-Web-Application | feature/us11                | 7a2b8fa      | feat: implement edit functionality for cage information                         | 14/05/2025               |
| Frontend-Web-Application | feature/us11                | f6f1a9d      | feat: improve formatting and readability of cage list component template        | 14/05/2025               |
| Frontend-Web-Application | feature/us15                | 1122cdc      | feat(resource): implement components to manage and register farm resources      | 14/05/2025               |
| Frontend-Web-Application | feature/us15                | eb97f36      | feat(expense): implement components to manage and register farm expenses        | 14/05/2025               |
| Frontend-Web-Application | feature/us13                | 89e633e      | feat: implement animal detail and edit form with dynamic binding and actions    | 14/05/2025               |
| Frontend-Web-Application | feature/us13                | 3492155      | Merge branch 'feature/us13' into develop                                        | 14/05/2025               |
| Frontend-Web-Application | feature/us12                | e8a61fc      | feat: validate cage existence before updating animal information                | 14/05/2025               |
| Frontend-Web-Application | feature/us12                | ae481b3      | feat: agregar documentación del componente MyFarmResourceManagement             | 14/05/2025               |
| Frontend-Web-Application | feature/us13                | 832109e      | Merge: resolve conflict and merge feature/us13 into develop                     | 14/05/2025               |
| Frontend-Web-Application | feature/us13                | 5e9b13a      | feat: map gender and health status to string values for form compatibility      | 14/05/2025               |
| Frontend-Web-Application | feature/us15                | 8ea1e34      | Merge branch 'feature/us15' into develop                                        | 14/05/2025               |
| Frontend-Web-Application | feature/us16                | d9c465d      | Merge branch 'feature/us16' into develop                                        | 14/05/2025               |
| Frontend-Web-Application | feature/us12                | 6c1b13d      | Merge pull request #6 from IoT-AgroConnect/feature/us12                         | 14/05/2025               |
| Frontend-Web-Application | develop                     | 5241bb8      | Merge branch 'develop' into develop                                             | 14/05/2025               |
| Frontend-Web-Application | feature/us08                | 95d3ed6      | feat: implement advisor profile view with detailed information and review       | 14/05/2025               |
| Frontend-Web-Application | feature/us08                | 59416b7      | feat: implement dynamic star rating display for advisor profile                 | 14/05/2025               |
| Frontend-Web-Application | feature/us08                | 8fb0666      | feat: Add advisor about us                                                      | 14/05/2025               |
| Frontend-Web-Application | feature/us08                | 629f1e7      | feat: display detailed advisor information in card view                         | 14/05/2025               |
| Frontend-Web-Application | feature/us08                | ade4eef      | Merge pull request #7 from IoT-AgroConnect/feature/us08                         | 14/05/2025               |
| Frontend-Web-Application | feature/us02                | 005cd40      | feat: Add Component                                                             | 14/05/2025               |
| Frontend-Web-Application | feature/us02                | db73423      | feat: Add getAdvisor()                                                          | 14/05/2025               |
| Frontend-Web-Application | feature/us02                | 5cdabe1      | Merge pull request #8 from IoT-AgroConnect/feature/us02                         | 14/05/2025               |
| Frontend-Web-Application | feature/us02                | 9afcd8d      | feat: Add schedule                                                              | 14/05/2025               |
| Frontend-Web-Application | feature/us03                | 5c52ee2      | feat: Add valid Date Validator                                                  | 14/05/2025               |
| Frontend-Web-Application | feature/us03                | ceb420f      | feat: Add method abailable date                                                 | 14/05/2025               |
| Frontend-Web-Application | feature/us03                | 0196f58      | Merge pull request #9 from IoT-AgroConnect/feature/us03                         | 14/05/2025               |
| Frontend-Web-Application | feature/us03                | ac9c3ef      | fix: Document add availability schedule                                         | 14/05/2025               |
| Frontend-Web-Application | feature/us04                | 2588040      | feat: Date service                                                              | 14/05/2025               |
| Frontend-Web-Application | feature/us04                | 0080c1a      | Service in the root injector                                                    | 14/05/2025               |
| Frontend-Web-Application | feature/us04                | b82652d      | feat: Service extends the base service                                          | 14/05/2025               |
| Frontend-Web-Application | feature/us04                | 9870b64      | Merge pull request #10 from IoT-AgroConnect/feature/us04                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us05              | e3791e4       | feat: Add getFarmById() method                                                  | 14/05/2025               |
| Frontend-Web-Application  | feature/us05              | b6c90da       | feat: create view for breeder farm info                                         | 14/05/2025               |
| Frontend-Web-Application  | feature/us05              | cccaa3b       | Merge pull request #11 from IoT-AgroConnect/feature/us05                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us06              | 2b39ed7       | feat: Notification model created                                                | 14/05/2025               |
| Frontend-Web-Application  | feature/us06              | 0d6c60e       | feat: created notification view                                                 | 14/05/2025               |
| Frontend-Web-Application  | feature/us06              | d801b5c       | Merge pull request #12 from IoT-AgroConnect/feature/us06                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us07              | 473860f       | feat: Notification for breeder                                                  | 14/05/2025               |
| Frontend-Web-Application  | feature/us07              | b0a8764       | feat: Notification delete breeder                                               | 14/05/2025               |
| Frontend-Web-Application  | feature/us07              | b4fa369       | Merge pull request #13 from IoT-AgroConnect/feature/us07                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us09              | 18063b1       | feat: Publication component created                                             | 14/05/2025               |
| Frontend-Web-Application  | feature/us09              | 7f5e7ad       | feat: add remove publication logic                                              | 14/05/2025               |
| Frontend-Web-Application  | feature/us09              | 423ebc3       | Merge pull request #14 from IoT-AgroConnect/feature/us09                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us10              | e7c8e93       | feat: visualizer for publications                                               | 14/05/2025               |
| Frontend-Web-Application  | feature/us10              | 6e521f2       | Merge pull request #15 from IoT-AgroConnect/feature/us10                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us01              | 2ea70e4       | feat: catalog component created                                                 | 14/05/2025               |
| Frontend-Web-Application  | feature/us01              | 8bdc9e3       | feat: fetch advisors for criador                                                | 14/05/2025               |
| Frontend-Web-Application  | feature/us01              | b0d23cb       | Merge pull request #16 from IoT-AgroConnect/feature/us01                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us13              | 9c7b2ae       | feat: view/edit animal info with dynamic form binding                           | 14/05/2025               |
| Frontend-Web-Application  | feature/us11              | 9c4570f       | feat: animal management UI implemented for cage detail view                     | 14/05/2025               |
| Frontend-Web-Application  | feature/us11              | cbe93ae       | feat: add form validation for cage registration                                 | 14/05/2025               |
| Frontend-Web-Application  | feature/us11              | 410f437       | feat: delete cage functionality added                                           | 14/05/2025               |
| Frontend-Web-Application  | feature/us11              | 8fcaf64       | feat: update cage view with new features                                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us11              | c446b34       | feat: list and filter cages for breeder                                         | 14/05/2025               |
| Frontend-Web-Application  | feature/us11              | f1c3c6a       | feat: component for cage registration implemented                               | 14/05/2025               |
| Frontend-Web-Application  | feature/us11              | 1f9959c       | Merge pull request #17 from IoT-AgroConnect/feature/us11                        | 14/05/2025               |
| Frontend-Web-Application  | feature/us13              | 78b13c6       | fix: responsive form updates for animal detail                                  | 14/05/2025               |
| Frontend-Web-Application  | feature/us13              | 3142f51       | Merge pull request #18 from IoT-AgroConnect/feature/us13                        | 14/05/2025               |
| Frontend-Web-Application  | develop                   | 7c56a03       | Merge pull request #19 from IoT-AgroConnect/develop                             | 14/05/2025               |
| Frontend-Web-Application  | main                      | 49b8d77       | Merge pull request #20 from IoT-AgroConnect/main                                | 14/05/2025               |
| Frontend-Web-Application  | main                      | 6f1d5f4       | chore: updated readme and project structure for delivery                        | 14/05/2025               |
| Frontend-Web-Application  | main                      | b70df1c       | refactor: applied code formatting and naming consistency                        | 14/05/2025               |


> Todos los commits registrados permiten evidenciar el cumplimiento de los objetivos del Sprint 1, así como la correcta trazabilidad de cada historia de usuario implementada en la **Landing Page del sistema AgroCuy** y en la **primera versión del Frontend Web Application**.


---

#### 6.2.1.5. Testing Suite Evidence for Sprint Review

Durante el Sprint 1, se desarrollaron pruebas de aceptación automatizadas utilizando el lenguaje **Gherkin**, las cuales fueron registradas en archivos `.feature` y versionadas en el repositorio correspondiente.

Estas pruebas se diseñaron para validar el cumplimiento de criterios de aceptación de las User Stories priorizadas, garantizando que las funcionalidades desarrolladas cumplan con las expectativas del usuario desde una perspectiva funcional y de comportamiento.

🔗 Repositorio: [Acceptance Tests - AgroCuy](https://github.com/IoT-AgroConnect/Acceptance-Tests)

| **Repository**                     | **Branch** | **Commit ID** | **Commit Message**                                      | **Commited on (Date)** |
|-----------------------------------|------------|----------------|----------------------------------------------------------|-------------------------|
| AgroTech-UPC/Acceptance-Tests     | main       | 818417c        | feat: added feature file for US22                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 530ab54        | feat: add feature file for US23                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 31b09e5        | feat: add feature file for US24                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | d7c8cb7        | feat: add feature file for US25                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 56c2cfe        | feat: add feature file for US26                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 3754e25        | feat: add feature file for US27                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 65a02ca        | feat: add feature file for US01                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 53394b8        | feat: add feature file for US02                        | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | fde5473        | feat: add feature file for US03 | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 346c658        | feat: add feature file for US04                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 1d86777        | feat: add feature file for US05                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 6a236cc        | feat: add feature file for US06                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | f2b2386        | feat: add feature file for US08                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | bdb3f98        | feat: add feature file for US08                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 7028433        | feat: add feature file for US09                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 01f5cae        | feat: add feature file for US10                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | c63680b        | feat: add feature file for US11                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | d13e372        | feat: add feature file for US12                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | c9aaece        | feat: add feature file for US13                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 01d9ce8        | feat: add feature file for US15                          | 14/05/2025              |
| AgroTech-UPC/Acceptance-Tests     | main       | 5968886        | feat: add feature file for US16                          | 14/05/2025              |


#### 6.2.1.6. Execution Evidence for Sprint Review

Como parte de la evaluación del Sprint 1, se presenta la evidencia visual del entregable final correspondiente a la **Landing Page estática** del sistema AgroCuy. Esta interfaz representa el primer acercamiento público del sistema, enfocada en comunicar su propuesta de valor a potenciales usuarios y partes interesadas.

🎥 **Video demostrativo – Landing Page**:  
[Execution Evidence – AgroCuy Landing Page](https://youtu.be/Yi3p53UjKF0)

---

<img src="img/evidence_landing_page_1.png" width="100%">
<p style="text-align:center"><em>Imagen 119. Vista general de la landing page</em></p>

---

### 🔹 Navbar

Se desarrolló un componente de navegación *responsive* que adapta dinámicamente sus elementos para asegurar una navegación fluida en cualquier dispositivo. En pantallas móviles, las secciones se agrupan en un menú lateral tipo hamburguesa.

<img src="img/evidence_landing_page_2.png" width="100%">
<p style="text-align:center"><em>Imagen 120. Navbar expandido en pantalla amplia</em></p>

<img src="img/evidence_landing_page_3.png" width="100%">
<p style="text-align:center"><em>Imagen 121. Navbar colapsado en vista móvil</em></p>

---

### 🔹 Footer

El pie de página mantiene la identidad visual del sistema, asegurando consistencia y accesibilidad en diferentes tamaños de pantalla.

<img src="img/evidence_landing_page_4.png" width="100%">
<p style="text-align:center"><em>Imagen 122. Footer en pantalla completa</em></p>

<img src="img/evidence_landing_page_5.png" width="100%">
<p style="text-align:center"><em>Imagen 123. Footer en vista móvil</em></p>

---

### 🔹 Página de Inicio

La sección de bienvenida presenta una introducción clara al propósito de la plataforma AgroCuy, resaltando sus beneficios y enfoques principales.

<img src="img/evidence_landing_page_6.png" width="100%">
<p style="text-align:center"><em>Imagen 124. Sección de bienvenida</em></p>

<img src="img/evidence_landing_page_7.png" width="100%">
<p style="text-align:center"><em>Imagen 125. Continuación de la sección de inicio</em></p>

---

### 🔹 Sección “Problemática” y Segmentos Objetivo

Esta sección incluye tarjetas interactivas (*flip cards*) con información clave sobre los desafíos que enfrentan los criadores de cuyes. También se describen los dos segmentos objetivos del sistema: criadores y asesores técnicos.

<img src="img/landing-page-1.jpg" width="100%">
<img src="img/landing-page-2.jpg" width="100%">

---

### 🔹 Sección “Características”

Se muestran las funcionalidades clave del sistema AgroCuy mediante íconos explicativos y texto conciso, con un diseño moderno y estructurado.

<img src="img/landing-page-3.jpg" width="100%">

---

### 🔹 Sección “Sobre Nosotros”

Aquí se describe la identidad de la startup, su misión, visión y los integrantes del equipo. Se incluyen fotos de los miembros, fortaleciendo la conexión con el usuario.

<img src="img/landing-page-4.jpg" width="100%">
<img src="img/landing-page-5.jpg" width="100%">

---

### 🔹 Sección “Contacto”

La sección de contacto presenta los canales de comunicación con el equipo, mediante un formulario responsivo que facilita el envío de consultas o sugerencias.

<img src="img/landing-page-6.jpg" width="100%">

---

### ✅ Conclusión del Sprint

Todos los componentes definidos para este Sprint fueron implementados satisfactoriamente y validados visualmente, cumpliendo con el objetivo de entregar una landing page funcional, accesible y coherente con los estándares de diseño web moderno.

---

### 🌐 Evidencia del Frontend Web Application

Además de la landing page, se implementaron funcionalidades adicionales correspondientes a las historias de usuario del **Sprint Backlog 1**. Esta primera versión funcional del Frontend refleja la estructura básica de interacción y navegación dentro de la plataforma AgroCuy.

🎥 **Video demostrativo – Frontend Web Application**:  
[Execution Evidence – AgroCuy Frontend](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221b127_upc_edu_pe/EYY0ErnjEsFBiUZXlO60wHQBnqjOJRxM13gjVWm8Gpbbzg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Hd2T2Y)

<img src="img/front-web-evidence.png" width="100%">
<p style="text-align:center"><em>Imagen 134. Vista general del sistema web funcional</em></p>

#### 6.2.1.7. Services Documentation Evidence for Sprint Review. 
El alcance de este primer sprint ha priorizado el desarrollo de la parte de Front-end de la aplicación web y de la landing page estática, por lo que en este caso no se evidencia el empleo de web services.

#### 6.2.1.8. Software Deployment Evidence for Sprint Review. 
Una vez acabamos de trabajar con todas las historias de usuario, realizamos el deployment del Landing Page y el Front-end web application.

**Landing Page:**

URL de deployment de Landing Page: https://iot-agroconnect.github.io/Landing-Page-Main/about-us.html

Para lograr hacer el deployment, entramos a la configuración del repositorio y a la sección de Pages. Luego, debemos seleccionar la rama sobre la cual se hará el deployment.

<img src="img/despliegue-landing-githubpages.jpg" width="100%">
<p style="text-align:center"><em>Imagen 134. github - pages - 1</em></p>

Escogimos la rama main, ya que es la rama principal sobre la cual se guarda la versión final para hacer el deployment. Una vez se escoge, se guardan los cambios.

<img src="img/despliegue-landing-githubpages2.jpg" width="100%">
<p style="text-align:center"><em>Imagen 135. github - pages - 2</em></p>

Finalmente, solo se espera a que GitHub cree la página y nos brinde el enlace.
<img src="img/despliegue-landing-githubpages3.jpg" width="100%">
<p style="text-align:center"><em>Imagen 136. github - pages - 3</em></p>

<img src="img/despliegue-landing-githubpages4.jpg" width="100%">
<p style="text-align:center"><em>Imagen 137. github - pages - 4</em></p>

**Front-end web:**

Url: Despliegue del Front-end: https://agrocuy-webapp.web.app/login
Primero, se utilizó el comando ng build para crear la carpeta dist, la cual sirve para realizar el deployment en Firebase.

<img src="img/deploymentfront1.png" width="100%">
<p style="text-align:center"><em>Imagen 138. DeployFront - pages - 1</em></p>

<img src="img/deploymentfront2.png" width="100%">
<p style="text-align:center"><em>Imagen 139. DeployFront - pages - 2</em></p>

Luego, se utilizó el comando de lite-server para comprobar el funcionamiento de la aplicación.

Se instaló firebase-tools dentro del proyecto, y luego se inició sesión.

<img src="img/deployment4.png" width="100%">
<p style="text-align:center"><em>Imagen 140. DeployFront - pages - 3</em></p>

<img src="img/deployment5.png" width="100%">
<p style="text-align:center"><em>Imagen 141. DeployFront - pages - 4</em></p>

Se crea el proyecto Firebase en el cual se guardará todos los archivos, el cual le pusimos como nombre agroconnect-demo, y Se ejecuta el comando para instalar @angular/fire.

<img src="img/deployment7.png" width="100%">
<p style="text-align:center"><em>Imagen 142. DeployFront - pages - 5</em></p>

Se selecciona la opción ng deploy -- hosting.
<img src="img/deployment8.png" width="100%">
<p style="text-align:center"><em>Imagen 143. DeployFront - pages - 6</em></p>

Se selecciona el proyecto y se crea el enlace donde se aloja el proyecto
<img src="img/deployment9.png" width="100%">
<p style="text-align:center"><em>Imagen 143. DeployFront - pages - 7</em></p>

Se usa el comando ng deploy para deployear la aplicación
<img src="img/deployment11.png" width="100%">
<p style="text-align:center"><em>Imagen 144. DeployFront - pages - 8</em></p>

<img src="img/deployment12.png" width="100%">
<p style="text-align:center"><em>Imagen 145. DeployFront - pages - 9</em></p>

Finalmente, logramos acceder a nuestra aplicación deployada.
<img src="img/deployment14.png" width="100%">
<p style="text-align:center"><em>Imagen 146. DeployFront - pages - 10 </em></p>

https://frontend-web-application-delta.vercel.app/login

#### 6.2.1.9. Team Collaboration Insights during Sprint 

### 6.2.2. Sprint 2

#### 6.2.2.1. Sprint Planning

La planificación del segundo sprint se realizó de manera virtual mediante Google Meet. En esta sesión, el equipo acordó entregar la versión final del Landing Page y del Frontend Web Application de AgroCuy, así como implementar la **primera versión del aplicativo móvil** para criadores y asesores y entregar el **primer prototipo funcional del sistema IoT** para gestión de jaulas inteligentes.

| **Elemento** | **Detalle** |
|--------------|-------------|
| **Sprint #** | Sprint 2 |
| **Sprint Planning Background** | Segunda iteración del proyecto AgroCuy, con foco en cerrar la experiencia digital en web, integrar la arquitectura IoT, y entregar la primera versión usable de la aplicación móvil. |
| **Fecha** | 2025-05-21 |
| **Hora** | 9:00 PM |
| **Lugar** | Virtual (Google Meet) |
| **Preparado por** | Lucas Coronel, Nadia Alessandra |
| **Participantes de la reunión de planificación** | - Cuadros Rodríguez, Juan Alejandro<br> - Jarama Peñaloza, Fiorella<br> - Lucas Coronel, Nadia Alessandra<br> - Moreno Vergara, Johan Raúl<br> - Ramírez Méndez, Sebastián André |
| **Resumen del Sprint n–1 (Review)** | Se entregó exitosamente una versión funcional y responsiva del Landing Page y Frontend Web App, incluyendo navegación, catálogo de asesores, citas y visualización de recursos. Se validó funcional y visualmente con pruebas automatizadas. |
| **Resumen del Sprint n–1 (Retrospectiva)** | El equipo identificó como mejora la necesidad de **integrar pruebas de UI en la app móvil**, mejorar documentación técnica desde el inicio del sprint y avanzar con mayor paralelismo entre frontend y backend. |
| **Sprint Goal & User Stories** | El objetivo de este Sprint 2 es entregar la **versión final del Landing Page** y el **Frontend Web Application**, **la primera versión operativa del Mobile App**, y un **prototipo funcional IoT** (Edge + Dispositivo físico). El éxito del sprint será evaluado mediante pruebas funcionales en dispositivos físicos, validaciones de usuario en entorno móvil y pruebas de lectura y alerta desde sensores reales conectados a jaulas. |
| **Velocidad del Sprint (Story Points esperados)** | 168 |
| **Suma total de Story Points asignados** | 168 |

#### 6.2.2.2. Aspect Leaders and Collaborators

Durante el segundo sprint, el equipo se reorganizó para abarcar aspectos más amplios y complejos del sistema AgroCuy, incluyendo el refinamiento del Landing Page, la consolidación del Frontend Web Application, el desarrollo inicial del Mobile App y la integración del prototipo IoT (sistema de sensores y notificaciones desde jaulas conectadas).

La distribución de liderazgo y colaboración por aspecto se presenta en la siguiente tabla:

| **Team Member (Last Name, First Name)**       | **GitHub Username**        | **Landing Page Final** | **Frontend Web Final** | **Mobile App v1** | **IoT Prototype** | **Pruebas Automatizadas** | **Validación Usuario** |
|----------------------------------------------|-----------------------------|--------------------------|-------------------------|-------------------|-------------------|----------------------------|-------------------------|
| Lucas Coronel, Nadia Alessandra              | nad21lc                    | C                        | L                       | C                 |                   |                            | L                       |
| Ramírez Méndez, Sebastián André              | yorusaurio                 | L                        | C                       | L                 | C                 |                            | C                       |
| Cuadros Rodríguez, Juan Alejandro            | JuanAlejandroCuadrosRodriguez |                        | C                       | C                 | L                 |                            | C                       |
| Moreno Vergara, Johan Raúl                   | JohanMV                    |                          | C                       | C                 | L                 | C                          | L                       |
| Jarama Peñaloza, Fiorella                    | Fio0407                    | C                        | C                       |                   |                   | L                          |                         |

> Esta distribución asegura cobertura de todos los aspectos clave en el Sprint 2, optimizando la colaboración entre miembros y alineando responsabilidades con los objetivos establecidos. La incorporación del prototipo IoT y la app móvil exigió una asignación técnica más específica, reforzada con validaciones funcionales y de usuario.


#### 6.2.2.3. Sprint Backlog

El objetivo de este segundo sprint es la implementación de la parte faltante de Frontend y empezar con el Backend, Edge, Aplicacion Movil y sistema Embebido. Igualmente, se trabajó con una tabla en Trello para manejar los Work-Items de forma adecuada.
<https://trello.com/b/VboaXtwW/sprint-backlog-2>
<img src="img/sprint-backlog-2.png" width="100%">

<table><tr><th colspan="1" valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 3</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Description</td><td colspan="1" valign="top">Estimation </td><td colspan="1" valign="top">Assigned To</td><td colspan="1" valign="top">Status (To-Do / In-Process / Review / Done)</td></tr>
<tr><td colspan="1" valign="top">US02</td><td colspan="1" valign="top">Visualización de información de un asesor</td><td colspan="1" valign="top">TS01</td><td colspan="1" valign="top">Mejorar estilos en la página de información del asesor</td><td colspan="1" valign="top">Mejorar los estilos CSS en la página de información del asesor.</td><td colspan="1" valign="top">3</td><td colspan="1" valign="top">Nadia Lucas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US04</td><td colspan="1" valign="top">Programación de citas con asesores</td><td colspan="1" valign="top">TS02</td><td colspan="1" valign="top">Mejorar estilos en mensaje de confirmación de cita</td><td colspan="1" valign="top">Mejorar los estilos CSS en el mensaje de confirmación de cita reservada para el criador.</td><td colspan="1" valign="top">3</td><td colspan="1" valign="top">Johan Romero</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US05</td><td colspan="1" valign="top">Visualización de información del criador de cuyes</td><td colspan="1" valign="top">TS03</td><td colspan="1" valign="top">Mejorar estilo para la visualización de los clientes del asesor</td><td colspan="1" valign="top">Mejorar los estilos CSS para la vista de clientes (criadores) para la vista del asesor.</td><td colspan="1" valign="top">5</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US10</td><td colspan="1" rowspan="2" valign="top">Visualización de publicaciones de asesores</td><td colspan="1" valign="top">TS04</td><td colspan="1" valign="top">Implementación de página para visualizar publicaciones</td><td colspan="1" valign="top">Implementar la página para que los criadores puedan visualizar las publicaciones de asesores.</td><td colspan="1" rowspan="2" valign="top">3</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS05</td><td colspan="1" valign="top">Agregar botón para ir al perfil del asesor</td><td colspan="1" valign="top">Agregar un botón debajo de la publicación que redireccione al perfil del asesor.</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US11</td><td colspan="1" valign="top">Gestión de jaula de cuyes</td><td colspan="1" valign="top">TS06</td><td colspan="1" valign="top">Reubicación de opción de registro de jaulas</td><td colspan="1" valign="top">Se mueve la opción de registro de jaulas dentro del componente de la vista Mi Granja</td><td colspan="1" valign="top">3</td><td colspan="1" valign="top">Sebastián Ramirez</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US13</td><td colspan="1" valign="top">Visualización y edición de información de animales</td><td colspan="1" valign="top">TS07</td><td colspan="1" valign="top">Mejorar estilos en la página de la vista de edición de animales</td><td colspan="1" valign="top">Mejorar los estilos CSS en la página de visualización y edición de animales.</td><td colspan="1" valign="top">5</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US14</td><td colspan="1" valign="top">Separar fechas disponibles para asesoría</td><td colspan="1" valign="top">TS08</td><td colspan="1" valign="top">Implementación de componente para colocar fechas disponibles de asesoría</td><td colspan="1" valign="top">Implementar la componente para que el asesor pueda agregar sus horarios disponibles para ofrecer asesorías.</td><td colspan="1" valign="top">3</td><td colspan="1" valign="top">Sebastián Ramirez</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="3" valign="top">US15</td><td colspan="1" rowspan="3" valign="top">Gestión de recursos</td><td colspan="1" valign="top">TS09</td><td colspan="1" valign="top">Agregar Botón de Edición e Implementar Apartado Aislado de Edición</td><td colspan="1" valign="top">Agregar un botón de edición a cada recurso e implementar una interfaz aislada que se active al hacer clic en el botón de edición, donde los usuarios puedan realizar cambios y guardarlos.</td><td colspan="1" rowspan="3" valign="top">5</td><td colspan="1" valign="top">Nadia Lucas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS10</td><td colspan="1" valign="top">Agregar botón de eliminación de recurso</td><td colspan="1" valign="top">Agregar un botón de eliminación a cada recurso, permitiendo a los usuarios eliminar recursos individualmente.</td><td colspan="1" valign="top">Johan Romero</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS11</td><td colspan="1" valign="top">Mejorar el diseño de la ruta “Mi Granja” en la vista del criador</td><td colspan="1" valign="top">Realizar mejoras en el maquetado del HTML y los estilos de la vista principal para mejorar la experiencia del usuario.</td><td colspan="1" valign="top">Sebastian Ramirez</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="4" valign="top">US16</td><td colspan="1" rowspan="4" valign="top">Gestión de gastos</td><td colspan="1" rowspan="2" valign="top">TS12</td><td colspan="1" rowspan="2" valign="top">Mejorar el diseño de la ruta “Mi Granja” en la vista del criador</td><td colspan="1" rowspan="2" valign="top">Realizar mejoras en el maquetado del HTML y los estilos de la vista principal para mejorar la experiencia del usuario.</td><td colspan="1" rowspan="4" valign="top">5</td><td colspan="1" rowspan="2" valign="top">Sebastian Ramirez</td><td colspan="1" rowspan="2" valign="top">Done</td></tr>
<tr></tr>
<tr><td colspan="1" valign="top">TS13</td><td colspan="1" valign="top">Agregar Botón de Edición e Implementar Apartado Aislado de Edición</td><td colspan="1" valign="top">Agregar un botón de edición a cada gasto e implementar una interfaz aislada que se active al hacer clic en el botón de edición, donde los usuarios puedan realizar cambios y guardarlos.</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS14</td><td colspan="1" valign="top">Agregar botón de eliminación de gasto</td><td colspan="1" valign="top">Agregar un botón de eliminación a cada gasto, permitiendo a los usuarios eliminar gastos individualmente.</td><td colspan="1" valign="top">Nadia Lucas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US19</td><td colspan="1" rowspan="2" valign="top">Registro de un usuario nuevo</td><td colspan="1" valign="top">TS15</td><td colspan="1" valign="top">Implementación de componente para registrar un criador</td><td colspan="1" valign="top">Implementar el componente para registrar a un criador nuevo dentro de la aplicación.</td><td colspan="1" rowspan="2" valign="top">3</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS16</td><td colspan="1" valign="top">Implementación de componente para registrar un asesor</td><td colspan="1" valign="top">Implementar el componente para registrar un asesor nuevo dentro de la aplicación.</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US20</td><td colspan="1" valign="top">Inicio de sesión</td><td colspan="1" valign="top">TS17</td><td colspan="1" valign="top">Implementación de página para iniciar sesión</td><td colspan="1" valign="top">Implementar la página para iniciar sesión dentro de la aplicación, validando los datos ingresados.</td><td colspan="1" valign="top">3</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US21</td><td colspan="1" valign="top">Recuperación de contraseña</td><td colspan="1" valign="top">TS18</td><td colspan="1" valign="top">Implementación de página para recuperar contraseña</td><td colspan="1" valign="top">Implementar la página para recuperar la contraseña en caso el usuario la olvide.</td><td colspan="1" valign="top">5</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="1" valign="top">US29</td><td colspan="1" rowspan="1" valign="top">Uso de API para subir imágenes (Firebase)</td><td colspan="1" valign="top">TS19</td><td colspan="1" valign="top">Implementación de protocolos HTTP para subir imágenes</td><td colspan="1" valign="top">Se integra la API de Firebase para permitir a los usuarios subir y visualizar imágenes de perfil o publicaciones.</td><td colspan="1" rowspan="1" valign="top">3</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US31</td><td colspan="1" valign="top">Visualización de calendario</td><td colspan="1" valign="top">TS20</td><td colspan="1" valign="top">Implementación de página para visualizar el calendario</td><td colspan="1" valign="top">Implementar la página que muestra el calendario con las citas programadas para el usuario.</td><td colspan="1" valign="top">3</td><td colspan="1" valign="top">Johan Moreno</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US32</td><td colspan="1" rowspan="2" valign="top">Uso de nuestra API para gestionar usuarios</td><td colspan="1" valign="top">TS21</td><td colspan="1" valign="top">Implementación de protocolos HTTP para usuarios</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para los usuarios (criadores y asesores) dentro de nuestra API.</td><td colspan="1" rowspan="2" valign="top">5</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS22</td><td colspan="1" valign="top">Implementación de protocolos HTTP para notificaciones</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las notificaciones dentro de nuestra API.</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US33</td><td colspan="1" valign="top">Uso de nuestra API para gestionar publicaciones</td><td colspan="1" valign="top">TS23</td><td colspan="1" valign="top">Implementación de protocolos HTTP para publicaciones</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las publicaciones dentro de nuestra API.</td><td colspan="1" valign="top">5</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US34</td><td colspan="1" rowspan="2" valign="top">Uso de nuestra API para manejar recursos y gastos</td><td colspan="1" valign="top">TS24</td><td colspan="1" valign="top">Implementación de protocolos HTTP para recursos</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para los recursos dentro de nuestra API.</td><td colspan="1" rowspan="2" valign="top">5</td><td colspan="1" valign="top">Nadia Lucas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS25</td><td colspan="1" valign="top">Implementación de protocolos HTTP para gastos</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para los gastos dentro de nuestra API.</td><td colspan="1" valign="top">Juan Cuadros</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="3" valign="top">US35</td><td colspan="1" rowspan="3" valign="top">Uso de nuestra API para manejar la reserva de citas entre asesores y criadores</td><td colspan="1" valign="top">TS26</td><td colspan="1" valign="top">Implementación de protocolos HTTP para citas</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las citas de asesorías dentro de nuestra API.</td><td colspan="1" rowspan="3" valign="top">5</td><td colspan="1" valign="top">Sebastián Ramirez, Johan Moreno</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS27</td><td colspan="1" valign="top">Implementación de protocolos HTTP para horarios disponibles</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para los horarios disponibles de los asesores dentro de nuestra API.</td><td colspan="1" valign="top">Sebastián Ramirez</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS28</td><td colspan="1" valign="top">Implementación de protocolos HTTP para reseñas</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las reseñas sobre los asesores dentro de nuestra API.</td><td colspan="1" valign="top">Johan Moreno</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US36</td><td colspan="1" rowspan="2" valign="top">Uso de la API para manejar el registro de jaulas y animales </td><td colspan="1" valign="top">TS29</td><td colspan="1" valign="top">Implementación de protocolos HTTP para jaulas</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las jaulas dentro de nuestra API.</td><td colspan="1" rowspan="2" valign="top">5</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS30</td><td colspan="1" valign="top">Implementación de protocolos HTTP para animales</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para los animales dentro de nuestra API.</td><td colspan="1" valign="top">Nadia Lucas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="1" valign="top">US37</td><td colspan="1" rowspan="1" valign="top">Integración con API para monitorear sensores de granja (IoT)</td><td colspan="1" valign="top">TS31</td><td colspan="1" valign="top">Implementación de integración con sensores IoT</td><td colspan="1" valign="top">Se implementa la conexión con la API de sensores para recibir datos ambientales en tiempo real.</td><td colspan="1" rowspan="1" valign="top">5</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="1" valign="top">US38</td><td colspan="1" rowspan="1" valign="top">Recepción de alertas cuando los parámetros ambientales exceden los rangos aceptables</td><td colspan="1" valign="top">TS32</td><td colspan="1" valign="top">Implementación de alertas automáticas por parámetros ambientales</td><td colspan="1" valign="top">El sistema detecta cuando un valor excede el límite configurado y genera una notificación inmediata.</td><td colspan="1" rowspan="1" valign="top">3</td><td colspan="1" valign="top">Johan Moreno</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="1" valign="top">US40</td><td colspan="1" rowspan="1" valign="top">Configuración personalizada por el criador de los rangos aceptables</td><td colspan="1" valign="top">TS33</td><td colspan="1" valign="top">Implementación de configuración personalizada de rangos ambientales</td><td colspan="1" valign="top">Se implementa la funcionalidad que permite al criador establecer los valores límite personalizados de temperatura, humedad, CO₂ y agua.</td><td colspan="1" rowspan="1" valign="top">5</td><td colspan="1" valign="top">Johan Moreno</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="1" valign="top">US41</td><td colspan="1" rowspan="1" valign="top">Detección automática de agua en mal estado o escasez</td><td colspan="1" valign="top">TS34</td><td colspan="1" valign="top">Implementación de alerta por agua en mal estado o escasa</td><td colspan="1" valign="top">Se integra la lógica para detectar automáticamente escasez o mala calidad del agua y generar una alerta al criador.</td><td colspan="1" rowspan="1" valign="top">5</td><td colspan="1" valign="top">Fiorella Jarama</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="1" valign="top">US42</td><td colspan="1" rowspan="1" valign="top">Activación y programación de dispensación automática de alimento</td><td colspan="1" valign="top">TS35</td><td colspan="1" valign="top">Implementación de programación de dispensación automática de alimento</td><td colspan="1" valign="top">Se permite al criador establecer horarios de alimentación automatizada, y el sistema activa el dispensador en dichos horarios.</td><td colspan="1" rowspan="1" valign="top">5</td><td colspan="1" valign="top">Sebastián Ramírez</td><td colspan="1" valign="top">Done</td></tr>
</table>

#### 6.2.2.4. Development Evidence for Sprint Review

Durante el Sprint 2, el equipo centró sus esfuerzos en consolidar las funcionalidades principales de la aplicación móvil **AgroCuy**, con el objetivo de ofrecer una experiencia fluida e intuitiva para criadores de cuyes. Este sprint tuvo como foco el desarrollo del módulo de agendamiento de citas con asesores, así como mejoras significativas en la estructura de navegación, el diseño visual y la persistencia de sesión de usuario.

Las tareas priorizadas se alinearon con el objetivo del sprint: **validar y optimizar la interacción básica entre criadores y asesores dentro de la app móvil**, sentando las bases de una experiencia de usuario clara, funcional y escalable. Se avanzó también en la integración de componentes visuales y en la conexión con servicios Firebase para el control de autenticación, lo que permite una gestión segura de accesos desde el inicio.

A continuación, se presentan las evidencias del desarrollo correspondiente a este sprint, incluyendo capturas de pantalla, fragmentos de código y validaciones funcionales sobre el cumplimiento de las historias de usuario planteadas.

#### 🔹 Repositorio: [Mobile App AgroCuy](https://github.com/IoT-AgroConnect/AgroCuy-mobileApp)

| **Repository**                      | **Branch**     | **Commit ID** | **Commit Message**                                                                 | **Committed on (Date)** |
|------------------------------------|----------------|----------------|--------------------------------------------------------------------------------------|--------------------------|
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us16   | deedfa8        | merge: integrar feature/us16 con gestión local de recursos y gastos usando SharedPreferences | 2025-06-19               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us16   | f74deae        | feat: SharedPreferences - Recursos & Gastos                                         | 2025-06-19               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | e6b3a9b        | style: format code for improved readability in JaulaDetailScreen                    | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 628354a        | feat: enhance JaulaDetailScreen with IoT device status and humidity monitoring features | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 54e2c7c        | feat: refactor schedule data source and presentation logic; add JaulaDetailScreen for managing cuyes with IoT monitoring features | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 0fe4740        | feat: Implement schedule management feature with remote data source feedback for schedule operations. | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 8512d15        | feat: calendar screen advisor implemented.                                          | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | a3c5b2e        | feat: add CalendarScreenAdvisor for advisor-specific calendar functionality         | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | a2c8b13        | feat: add ConfigurationScreen for user settings management and preferences          | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 9f8d7cb        | feat: enhance CalendarScreen with detailed event management and improved UI         | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | c19ec7b        | feat: add JaulaDetailScreen and JaulaFormScreen for managing cages and cuyes        | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | abb9c89        | feat: pass user details to GranjaHomeView and NotificationScreen for enhanced role-based functionality | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 64892d5        | feat: add popup menu to app bar and enhance user drawer with role-based navigation  | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | f29b047        | fix: updated appointment name and navigation in breeder drawer                      | 2025-06-17               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 1c65367        | feat: calendar                                                                      | 2025-06-16               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 915d21c        | fix: register of breeder and advisor                                                | 2025-06-06               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | b34d549        | fix: fixed error with login token                                                   | 2025-06-06               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 1ebec07        | fix: upload image for register (advisor)                                            | 2025-06-05               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us31   | 695fd2         | Merge pull request #6 from IoT-AgroConnect/feature/us31                             | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us31   | b58cfe3        | Merge branch 'develop' into feature/us31                                            | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 0e9cb8a        | feat: update main app to use LoginScreen instead of CalendarScreen                  | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 766b54c        | feat(us16): integración de vista granja con rutas de assets corregidas              | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 4dc2e2b        | Corrige rutas de imágenes y overflow en GranjaHomeView (US16)                       | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 9ad33b6        | feat(us16): added granja home view and expenses module                              | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | 68151bd        | feat(us15): gestión de recursos de la granja (formulario y lista)                   | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us35   | 6db88bc        | Merge pull request #5 from IoT-AgroConnect/feature/us35                             | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us35   | 58faf69        | Merge branch 'develop' into feature/us35                                            | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us06   | 4b32b9e        | Merge pull request #3 from IoT-AgroConnect/feature/us06                             | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us06   | e9cc1fc        | feat: available date picking                                                        | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us06   | aabe945        | feat: available date cards                                                          | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us06   | afb6253        | feat: available date model & data source                                            | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | feature/us06   | 74e980d6       | feat: added search bar & available dates btn                                        | 2025-06-04               |
| IoT-AgroConnect/AgroCuy-mobileApp  | develop        | db55fef        | feat: advisor list & detail                                                         | 2025-06-03               |


Todos los commits registrados permiten evidenciar el cumplimiento de los objetivos establecidos para el Sprint 2, demostrando avances clave en la funcionalidad y experiencia de usuario de la **aplicación móvil AgroCuy**. Se logró implementar la gestión de calendarios y agendamiento de citas, integración con sensores IoT para monitoreo de jaulas, así como la persistencia de datos locales mediante SharedPreferences. Además, se fortaleció la navegación basada en roles y se mejoró la configuración visual de múltiples pantallas. Cada historia de usuario abordada presenta trazabilidad directa con su respectivo commit, asegurando coherencia y control del progreso del desarrollo.

----


#### 6.2.2.5. Testing Suite Evidence for Sprint Review

Durante el Sprint 2, se continuó con la implementación de pruebas de aceptación automatizadas para validar el comportamiento esperado de las funcionalidades críticas en la aplicación móvil **AgroCuy**. Estas pruebas se formularon utilizando el lenguaje **Gherkin** y fueron registradas en archivos `.feature`, permitiendo validar los criterios de aceptación definidos para las historias de usuario priorizadas en este sprint.

Las pruebas se enfocaron principalmente en escenarios de interacción entre criadores y asesores, gestión de horarios, visualización de jaulas con sensores IoT, y configuración de preferencias del usuario. Esta estrategia de testing busca asegurar la correcta funcionalidad de los flujos clave desde la perspectiva del usuario, promoviendo calidad continua en el desarrollo.

🔗 Repositorio: [Acceptance Tests - AgroCuy](https://github.com/IoT-AgroConnect/Acceptance-Tests)

#### 6.2.2.6. Execution Evidence for Sprint Review

Como parte de la evaluación del Sprint 2, se presenta la evidencia visual del entregable correspondiente al **prototipo funcional de la aplicación móvil AgroCuy**. Esta versión incluye múltiples funcionalidades dirigidas a criadores y asesores, integrando componentes IoT, gestión de recursos, y experiencias personalizadas según el rol del usuario.

🎥 **Video demostrativo – AgroCuy Mobile App**:  
[Execution Evidence – AgroCuy Mobile Sprint 2](https://youtu.be/xxxxxxxxxxx)

---

### 🔹 Gestión de Jaulas y Sensores IoT

Se implementó una vista detallada por jaula, permitiendo a los criadores visualizar el estado en tiempo real de los sensores conectados (como humedad). Además, se incluye un componente visual intuitivo con cards individuales por jaula.

<div style="text-align:center">
  <img src="img/evidence_jaula_1.png" width="50%">
  <p><em>Imagen 201. Estado de sensores IoT en jaula</em></p>
</div>

<div style="text-align:center">
  <img src="img/evidence_jaula_2.png" width="50%">
  <p><em>Imagen 202. Vista de detalle con nivel de humedad</em></p>
</div>

<div style="text-align:center">
  <img src="img/evidence_jaula_3.png" width="50%">
  <p><em>Imagen 203. Vista de detalle de los cuyes en la jaula</em></p>
</div>

---

### 🔹 Gestión de Calendario y Citas

Se integró una pantalla de calendario con eventos dinámicos. Se pueden ver y agendar citas entre criadores y asesores, incluyendo vista personalizada para asesores técnicos.

<div style="text-align:center">
  <img src="img/evidence_calendar_1.png" width="50%">
  <p><em>Imagen 204. Calendario con eventos y agendamiento</em></p>
</div>

<div style="text-align:center">
  <img src="img/evidence_calendar_2.png" width="50%">
  <p><em>Imagen 205. Vista de calendario de asesor técnico</em></p>
</div>

<div style="text-align:center">
  <img src="img/evidence_calendar_3.png" width="50%">
  <p><em>Imagen 206. Vista de cita asesor técnico</em></p>
</div>


---

### 🔹 Recursos y Gastos

El módulo de recursos permite registrar y listar materiales, mientras que el módulo de gastos asocia recursos a transacciones simples. La persistencia local se implementó con SharedPreferences.

<div style="text-align:center">
  <img src="img/evidence_recursos_1.png" width="50%">
  <p><em>Imagen 207. Pantalla de mi granja de criador</em></p>
</div>

<div style="text-align:center">
  <img src="img/evidence_recursos_2.png" width="50%">
  <p><em>Imagen 208. Registro de recursos de la granja</em></p>
</div>

<div style="text-align:center">
  <img src="img/evidence_gastos_1.png" width="50%">
  <p><em>Imagen 209. Registro de gastos relacionados</em></p>
</div>


---

### 🔹 Configuración del Usuario y Drawer Personalizado

Se implementó una pantalla de configuración para el usuario logueado, así como un menú lateral contextualizado según el tipo de rol (criador o asesor), permitiendo acceso a funciones específicas según el perfil.

<div style="text-align:center">
  <img src="img/evidence_user_drawer.png" width="50%">
  <p><em>Imagen 210. Drawer dinámico según rol del usuario</em></p>
</div>

<div style="text-align:center">
  <img src="img/evidence_config_screen.png" width="50%">
  <p><em>Imagen 211. Pantalla de configuración personal</em></p>
</div>

---

### 🔹 Vista Principal del Criador

Se diseñó una pantalla principal para el criador que centraliza el acceso a los módulos de la aplicación. Esta vista incluye tarjetas con resumen de recursos y gastos, accesos directos a funciones frecuentes y visuales adaptados al perfil de usuario.

<div style="text-align:center">
  <img src="img/evidence_granja_home.png" width="50%">
  <p><em>Imagen 212. Vista principal de criador con acceso a módulos clave</em></p>
</div>

---

### 🔹 Pantalla de Inicio de Sesión y Persistencia

Se implementó el flujo de inicio de sesión mediante email y contraseña. Se corrigieron errores en la validación del token y se configuró el guardado de sesión para asegurar que el usuario no tenga que volver a iniciar sesión tras cerrar la app.

<div style="text-align:center">
  <img src="img/evidence_login.png" width="50%">
  <p><em>Imagen 213. Pantalla de login funcional con persistencia de sesión</em></p>
</div>

--- 

### 🔹 Lista y Detalle de Asesores

Se desarrolló una vista con catálogo de asesores disponibles, con posibilidad de ver detalles individuales antes de agendar una cita. Esta funcionalidad permite a los criadores seleccionar asesores por especialidad o disponibilidad.

<img src="img/evidence_asesores_list.png" width="50%">
<p style="text-align:center"><em>Imagen 214. Lista de asesores disponibles</em></p>

<img src="img/evidence_asesores_detail.png" width="50%">
<p style="text-align:center"><em>Imagen 215. Detalle del asesor seleccionado</em></p>

---

### 🔹 Pantalla de Notificaciones

<div style="text-align:center">
  <img src="img/evidence_notifications.png" width="50%">
  <p><em>Imagen 216. Tarjetas con notifcaciones por parte de los asesores</em></p>
</div>

---

### 🔹 Gestión de Jaulas y Sensores IoT - Web

Se implementó una vista detallada por jaula, permitiendo a los criadores visualizar el estado en tiempo real de los sensores conectados (como humedad). Además, se incluye un componente visual intuitivo con cards individuales por jaula.

<img src="img/iot_monitoring.png" alt="IoT Monitoring" width="600" /> <br>

<img src="img/iot_monitoring_2.png" alt="IoT Monitoring 2" width="600" />

---

### ✅ Conclusión del Sprint

Todas las funcionalidades planificadas en el Sprint 2 fueron implementadas satisfactoriamente. Se logró avanzar en los módulos clave que fortalecen la propuesta de valor de la app AgroCuy, habilitando interacciones reales entre usuarios, monitoreo con sensores y gestión operativa de granjas, todo desde una interfaz móvil accesible y fluida.

---

#### 6.2.2.7. Services Documentation Evidence for Sprint Review. 
Para este sprint, hemos implementado una primera versión del backend con el 90% de endpoints necesarios para su funcionamiento incluyendo aquellos que interactúan con el lado IoT del proyecto.

Enlace al repositorio de Web Services: https://github.com/IoT-AgroConnect/Web-Services-main

|Método|Endpoint|Descripción|
|--|--|--|
|GET|/api/v1/users|Se obtiene la lista de usuarios|
|POST|/api/v1/users|Se publica un nuevo usuario|
|GET|/api/v1/users/{id}|Se obtiene un usuario por ID|
|GET|/api/v1/users/{id}/notifications|Se obtiene la lista de notificaciones de un usuario por su ID|
|GET|/api/v1/breeders|Se obtiene la lista de los criadores|
|POST|/api/v1/breeders|Se publica un nuevo criador|
|GET|/api/v1/breeders/{id}|Se obtiene un criador por ID|
|GET|/api/v1/breeders/{id}/cages|Se obtiene la lista de jaulas de un criador por su ID|
|GET|/api/v1/breeders/{id}/appointments|Se obtiene la lista de citas para la asesoria de un criador por su ID|
|GET|/api/v1/breeders/{id}/resources|Se obtiene la lista de recursos de un criador por su ID|
|GET|/api/v1/breeders/{id}/expenses|Se obtiene la lista de gastos de un criador por su ID|
|GET|/api/v1/advisors|Se obtiene la lista de los asesores|
|POST|/api/v1/advisors|Se publica un nuevo asesor|
|GET|/api/v1/advisors/{id}|Se obtiene un asesor por ID|
|GET|/api/v1/advisors/{id}/available-dates|Se obtiene la lista de fechas disponibles de un asesor por su ID|
|GET|/api/v1/advisors/{id}/publications|Se obtiene la lista de publicaciones de un asesor por su ID|
|GET|/api/v1/advisors/{id}/appointments|Se obtiene la lista de citas de un asesor por su ID|
|GET|/api/v1/notifications|Se obtiene la lista de las notificaciones|
|POST|/api/v1/notifications|Se publica una nueva notificacion|
|GET|/api/v1/notifications/{id}|Se obtiene una notificacion por ID|
|DELETE|/api/v1/notifications/{id}|Se elimina una notificacion por ID|
|GET|/api/v1/available-dates|Se obtiene la lista de los horarios disponibles de los asesores|
|POST|/api/v1/available-dates|Se publica un nuevo horario|
|GET|/api/v1/available-dates/{id}|Se obtiene un horario por ID|
|DELETE|/api/v1/available-dates/{id}|Se elimina un horario por ID|
|GET|/api/v1/publications|Se obtiene la lista de las publicaciones de los asesores|
|POST|/api/v1/publications|Se publica una nueva publicacion|
|GET|/api/v1/publications/{id}|Se obtiene una publicacion por ID|
|DELETE|/api/v1/publications/{id}|Se elimina una publicacion por ID|
|GET|/api/v1/appointments|Se obtiene la lista de las citas entre asesores y criadores|
|POST|/api/v1/appointments|Se publica una nueva cita|
|GET|/api/v1/appointments/{id}|Se obtiene una cita por ID|
|PUT|/api/v1/appointments/{id}|Se modifica una cita por ID|
|GET|/api/v1/appointments/{id}/reviews|Se obtienen la reseña de una cita por ID|
|GET|/api/v1/reviews|Se obtiene la lista de las reseñas|
|POST|/api/v1/reviews|Se publica una nueva reseña|
|GET|/api/v1/reviews/{id}|Se obtiene una reseña por ID|
|GET|/api/v1/resources|Se obtiene la lista de recursos|
|POST|/api/v1/resources|Se publica un nuevo recurso|
|GET|/api/v1/resources/{id}|Se obtiene un recurso por ID|
|PUT|/api/v1/resources/{id}|Se modifica un recurso por ID|
|DELETE|/api/v1/resources/{id}|Se elimina un recurso por ID|
|GET|/api/v1/expenses|Se obtiene la lista de gastos|
|POST|/api/v1/expenses|Se publica un nuevo gasto|
|GET|/api/v1/expenses/{id}|Se obtiene un gasto por ID|
|PUT|/api/v1/expenses/{id}|Se modifica un gasto por ID|
|DELETE|/api/v1/expenses/{id}|Se elimina un gasto por ID|
|GET|/api/v1/cages|Se obtiene la lista de jaulas|
|POST|/api/v1/cages|Se publica una nueva jaula|
|GET|/api/v1/cages/{id}|Se obtiene una jaula por ID|
|PUT|/api/v1/cages/{id}|Se modifica una jaula por ID|
|DELETE|/api/v1/cages/{id}|Se elimina una jaula por ID|
|GET|/api/v1/animals|Se obtiene la lista de animales|
|POST|/api/v1/animals|Se publica un nuevo animal|
|GET|/api/v1/animals/{id}|Se obtiene un animal por ID|
|PUT|/api/v1/animals/{id}|Se modifica un animal por ID|
|DELETE|/api/v1/animals/{id}|Se elimina un animal por ID|
|GET|/api/v1/iot/sensor-data/{id}|Se obtiene datos del sensor por ID|
|PUT|/api/v1/iot/sensor-data/{id}|Se actualiza datos del sensor por ID|
|DELETE|/api/iot/sensor-data/{id}|Se elimina datos del sensor por ID|
|GET|/api/v1/iot/sensor-data|Se obtiene la lista de sensores|
|POST|/api/v1/iot/sensor-data|Se publica un nuevo sensor|
|GET|/api/v1/iot/sensor-data/by-cage/{id}|Se obtiene datos del sensor por CageID|
|PUT|/api/v1/acceptable-ranges/{id}|Se actualiza datos rango de datos aceptable|
|GET|/api/v1/acceptable-ranges|Se obtiene la lista de rangos aceptables para cada jaula|
|POST|/api/v1/acceptable-ranges|Se publica un nuevo rango aceptable|
|POST|/api/v1/acceptable-ranges/by-cage/{cageId}|Se obtiene rango aceptable por cageId|
|PUT|/api/v1/feeding-schedules/{id}|Se actualiza un horario de alimentación por ID|
|PUT|/api/v1/feeding-schedules/global|Se actualiza un horario de alimentación por ID|
|POST|/api/v1/feeding-schedules|Se publica uno o todos los horarios de alimentación para una o para todas las jaulas|
|GET|/api/v1/feeding-schedules/global-summary|Se visualiza todos los horarios de alimentación|
------

#### 6.2.2.8. Software Deployment Evidence for Sprint Review. 

### Deploy Backend

Para desplegar el Web Service se volvió a utilizar Render.com. Por lo que, se generó la carpeta target con los archivos actualizados del proyecto.

![Backend Deployment](img/backend-deployment1.png)

Luego, se ingreso al dashboard de Render y se seleccionó 'Manual Deploy' y 'deploy latest commit' para que se actualize el Web Service deployado.

![Backend Deployment](img/backend-deployment2.png)

Con ello, se empezó con el despliegue del Web Service.

![Backend Deployment](img/backend-deployment3.png)

Finalmente, se comprobó el funcionamiento del Web Service al entrar al swagger desde el enlace del producto desplegado https://web-services-18bk.onrender.com/swagger-ui/index.html

![Backend Deployment](img/backend-deployment4.png)

### Sistema Embebido 

![Sistema Embebido](img/Sistema-Embebido.png)

En el proyecto AgroCuy, se implementa un sistema de monitoreo inteligente basado en el microcontrolador ESP32 para supervisar en tiempo real las condiciones del criadero de cuyes. El circuito integra sensores ultrasónicos para detectar movimiento en zonas clave del corral, un sensor DHT22 para medir temperatura y humedad del ambiente, una pantalla LCD que muestra constantemente los valores capturados, y un servomotor que puede activarse automáticamente para abrir compuertas de ventilación o alimentación según las condiciones registradas. Esta solución permite a los criadores tomar decisiones oportunas, optimizando el bienestar de los animales y mejorando la eficiencia del manejo diario.

#### 6.2.2.9. Team Collaboration Insights during Sprint 

## 6.3. Validation Interviews.

### 6.3.1. Diseño de Entrevistas.

Para validar la utilidad y experiencia de usuario del sistema **AgroCuy**, se diseñaron entrevistas de validación dirigidas a usuarios reales de nuestros segmentos objetivo: criadores de cuyes y asesores técnicos. Estas entrevistas se realizaron de forma virtual, permitiendo observar el uso real del sistema (landing page, aplicación web, app móvil y prototipo IoT) mientras se recogía retroalimentación directa mediante preguntas semiestructuradas.

---

## 🧑‍🌾 Entrevistas a Criadores de Cuyes

### 🔹 Parte 1: Introducción
1. ¿Conoces alguna herramienta o aplicación digital para criadores de cuyes?
2. ¿Cuál es tu nivel de experiencia usando tecnología para gestionar tu trabajo?
3. ¿Estás familiarizado con conceptos como sensores o monitoreo remoto?

### 🔹 Parte 2: Landing Page
1. ¿Qué impresión te da esta página al verla por primera vez?
2. ¿Te queda clara la propuesta del sistema AgroCuy?
3. ¿Hay algo que no entiendas o que te confunda en esta página?
4. ¿Qué cambiarías para que más personas como tú se interesen?

### 🔹 Parte 3: Aplicación Web
1. ¿Te resulta fácil entender el menú y las secciones del sistema?
2. ¿Crees que podrías encontrar fácilmente a un asesor o gestionar tus jaulas?
3. ¿Hay algo que te parezca complicado o innecesario?
4. ¿Qué funcionalidades te parecen más útiles hasta ahora?

### 🔹 Parte 4: Aplicación Móvil
1. ¿Puedes identificar rápidamente para qué sirve cada pantalla?
2. ¿La navegación en el celular te resulta cómoda?
3. ¿Te gustaría recibir notificaciones o alertas desde esta app?
4. ¿Preferirías usar esta app o hacerlo todo en papel como antes?

### 🔹 Parte 5: Prototipo IoT
1. ¿Entiendes para qué sirven los sensores conectados a las jaulas?
2. ¿Te gustaría que se te avise automáticamente si algo anda mal con tus animales?
3. ¿Confías en este tipo de tecnología para ayudarte a cuidar a tus cuyes?
4. ¿Qué mejoras sugerirías para que esto funcione mejor en tu granja?

### 🔹 Parte 6: Cierre
1. En una frase, ¿qué es lo que más te gustó del sistema AgroCuy?
2. ¿Qué mejorarías antes de que esta herramienta esté disponible para todos?
3. ¿Estarías dispuesto a usar esta herramienta en tu día a día? ¿Por qué?

---

## 👨‍🔬 Entrevistas a Asesores Técnicos

### 🔹 Parte 1: Introducción
1. ¿Conoces herramientas digitales que hayas recomendado o utilizado en el ámbito agropecuario?
2. ¿Qué tan frecuentemente brindas soporte técnico a criadores de cuyes?
3. ¿Estás familiarizado con tecnologías como sensores IoT o monitoreo remoto?

### 🔹 Parte 2: Landing Page
1. ¿Consideras que la propuesta de AgroCuy está bien presentada?
2. ¿Crees que transmite valor para los criadores a los que asesoras?
3. ¿Hay aspectos que podrían reforzarse para mejorar la comunicación?
4. ¿Qué agregarías desde tu experiencia como asesor?

### 🔹 Parte 3: Aplicación Web
1. ¿La interfaz te parece adecuada para usuarios con poca experiencia digital?
2. ¿Te facilitaría el trabajo poder conectarte con los criadores a través del sistema?
3. ¿Qué funcionalidades crees que faltan desde tu rol?
4. ¿Visualizas algún riesgo en la adopción de esta herramienta?

### 🔹 Parte 4: Aplicación Móvil
1. ¿Ves útil que los criadores accedan desde su celular a datos de producción o contacto contigo?
2. ¿Qué opinas sobre el uso de alertas o notificaciones para asesoría preventiva?
3. ¿La app se adapta bien a las rutinas del trabajo en campo?
4. ¿Cómo imaginas integrarla en tus actividades actuales?

### 🔹 Parte 5: Prototipo IoT
1. ¿Qué ventajas técnicas destacarías del uso de sensores en la crianza de cuyes?
2. ¿Crees que los datos recolectados pueden complementar tu asesoría?
3. ¿Qué indicadores te parecería clave monitorear?
4. ¿Qué recomendaciones darías para hacer esta tecnología más útil y adoptable?

### 🔹 Parte 6: Cierre
1. ¿Qué es lo que más destacarías del sistema AgroCuy desde tu rol?
2. ¿Qué mejoras crees necesarias antes de una implementación a mayor escala?
3. ¿Recomendarías esta herramienta a otros asesores o usuarios? ¿Por qué?

---


### 6.3.2. Registro de Entrevistas.

#### **Entrevista N.º 1 – Asesor**

- **Entrevistador:** Juan Cuadros  
- **Entrevistado:** Diego Bazan  
- **Duración:** [00:05:41 – 00:11:33] (**5 minutos 52 segundos**)  

![Imagen 4. Entrevista a Diego Bazan](img/Entrevista_Asesor_DiegoBazan.png)  
*Imagen 4. Entrevista a Diego Bazan*

**Resumen:**  
Diego Bazán, asesor de cuyes, valora el uso de sensores IoT y monitoreo remoto porque le permiten dar una asesoría más precisa y rápida. Destaca que la plataforma AgroCuy es clara y útil, aunque sugiere agregar testimonios para hacerla más cercana. Le gusta la app web por mejorar la comunicación con los criadores y la móvil por sus alertas que ayudan a prevenir problemas. Para él, lo más valioso es cómo todo el sistema se integra para tomar mejores decisiones y cuidar mejor a los animales.

---
#### **Entrevista N.º 2 – Criador**

- **Entrevistador:** Johan  
- **Entrevistado:** Abel (Sobrino del criador)  
- **Duración:** [00:00:20 – 00:07:45] (**7 minutos 45 segundos**)  

![Imagen 5. Entrevista a Criador Abel](img/Entrevista_Criador_Abel.png)  
*Imagen 5. Entrevista a Criador Abel*

**Resumen:**  
Abel, quien apoya a su familiar en la crianza de cuyes en provincia, considera muy útil la propuesta de AgroCuy. Aunque no conocía otras herramientas similares, le parece que la plataforma es clara, moderna y fácil de usar. Destaca que el menú es intuitivo, la app móvil cómoda para registrar gastos y recibir alertas, y que el monitoreo con sensores es lo más valioso, ya que podría evitar problemas con los animales. Sugiere que más personas como su tío se beneficiarían si la app envía avisos automáticos sobre cambios en temperatura o humedad. En general, confía en la tecnología y estaría dispuesto a usarla en el día a día para mejorar el cuidado de los animales.


### 6.3.3. Evaluaciones según heurísticas.

## 6.4. Video About-the-Product.

En el vídeo se proporciona información sobre el producto AgroConnect. Se mencionan las diferentes funcionalidades de la aplicación como son la visualización del catálogo de asesores, la creación de publicaciones y la gestión de la granja. Asimismo, se incluye el testimonio positivo de una asesora especializada.

Screenshot del video:

<img src="img/about-the-product (1).PNG" width="100%">

**Enlace al vídeo de YouTube:** [Video About-The-Product Open Source UPC YouTube](https://youtube.com/shorts/PJiVdbOyj1s?si=sjVnvqluE7vOP8bp)

**Enlace al vídeo de Microsoft Stream:** [Video About-The-Product Open Source UPC.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120430_upc_edu_pe/EWIpOVJ41GdBlHCwN581pnUBuGb_Y6LXdw49NgSSD5-H3w?e=2pBDnM&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Duración del vídeo:** 0:38

# Conclusiones

## Avance de Conclusiones y recomendaciones

* La implementación del proceso Lean UX permitió a AgroTech identificar objetivos clave, competidores y necesidades del mercado. Desde la definición de problemas hasta la creación del Lean UX canvas, cada paso mejoró la eficiencia y agilidad en el desarrollo de AgroConnect.

* AgroTech ha realizado un análisis exhaustivo de sus competidores, así como entrevistas y actividades de needfinding para comprender las necesidades de sus usuarios. Lo anteriormente desarrollado se realizó en el capítulo II, dónde se realizó dicha investigación y análisis que aportaron con la creación de una solución como lo es AgroConnect, para que satisfaga las necesidades reales de sus usuarios.

* Los requisitos iniciales del proyecto se identificaron mediante herramientas como empathy mappings, user personas y user stories, que ayudaron a diseñar una experiencia de usuario satisfactoria y optimizar el desarrollo de la aplicación a través de un product backlog priorizado.

* La identificación de los Bounded Contexts y la realización del Context Mapping en AgroCuy nos permitió comprender de manera precisa las relaciones de dependencia, colaboración y comunicación entre los distintos módulos del sistema. Al aplicar patrones de interacción como Shared Kernel, Conformist, Customer–Supplier y Published Language, pudimos establecer límites claros de responsabilidad, asegurar la consistencia en los datos compartidos y reducir el acoplamiento entre contextos. Este análisis resulta fundamental para diseñar una arquitectura robusta, escalable y alineada a los principios de Domain-Driven Design, garantizando que cada área funcional de AgroCuy pueda evolucionar de forma independiente pero coordinada dentro del ecosistema general.

* Al desarrollar el backend con Spring Boot y alinear los bounded contexts utilizando la arquitectura DDD, conseguimos establecer una estructura sólida y modularizada. La exhaustiva documentación en Swagger nos sirvió como una guía clara para comprender y trabajar con cada componente, lo que no solo optimiza la organización y mantenimiento del código, sino que también promueve la colaboración entre equipos y facilita la escalabilidad del proyecto a medida que avanza. Por otro lado, las entrevistas de validación del producto brindaron una visión completa de cómo perciben y qué necesitan los usuarios. Aunque se reconocieron aspectos positivos como la utilidad de la Landing Page y la facilidad de uso de la Web Application, también se identificaron áreas de mejora en términos de claridad de la información, diseño y navegación. Estos insights proporcionan una base sólida para implementar ajustes significativos y perfeccionar la experiencia del usuario en futuras iteraciones del producto, garantizando así una mayor satisfacción y usabilidad.

* Finalmente, durante el desarrollo del trabajo aprendimos a planificar mejor la arquitectura del backend y optimizar las consultas a la base de datos desde el inicio para manejar eficientemente grandes volúmenes de datos. Asimismo, mejoramos la comunicación entre equipos para asegurar una integración fluida del frontend y backend, implementando estrategias de integración continua para facilitar actualizaciones rápidas y consistentes del sistema. Del mismo modo, nuestra startup AgroTech ha podido lograr una implementación exitosa de AgroConnect, demostrando competencia en la aplicación de metodologías como Lean UX y principios ágiles. Además, Hemos integrado eficientemente el frontend y backend mediante tecnologías open-source y prácticas colaborativas como GitFlow, garantizando estándares de seguridad y funcionalidad necesarios para cumplir con las expectativas del usuario final.

## Video About-the-Team.

# Bibliografía

* Aguilar, G., Bustamante, J., Bazán, V. y Falcón, N. (2011). Diagnóstico situacional de la crianza de cuyes en una zona de Cajamarca. _Revista de Investigaciones Veterinarias del Perú, 22_(1), 09-14. http://www.scielo.org.pe/scielo.php?script=sci_arttext&pid=S1609-91172011000100002&lng=es&tlng=es

* Guerra, C. (2009). _Manual técnico de crianza de cuyes_. Cedepas. https://www.cedepas.org.pe/sites/default/files/manual_tecnico_de_crianza_de_cuyes.pdf

* Instituto Nacional de Innovación Agraria. (23 de enero de 2023). Razas de cuyes del INIA mejoran un 20% la productividad de la crianza familiar y consumo de carne. _El Peruano_. https://www.elperuano.pe/noticia/225260-razas-de-cuyes-del-inia-mejoran-un-20-la-productividad-de-la-crianza-familiar-y-consumo-de-carne

* Luque, R. (2023). _Meta Tags | Las 7 más importantes en SEO_. SEOcrawl. https://seocrawl.com/meta-tags/

* Ministerio de Desarrollo Agrario y Riego. (2023). _Cadena productiva de cuyes_. https://cdn.www.gob.pe/uploads/document/file/4061856/Cadena%20productiva%20de%20cuy.pdf

* SENASA. (2019). _Cajamarca es el principal productor de cuy en el Perú_. https://www.senasa.gob.pe/senasacontigo/cajamarca-es-el-principal-productor-de-cuy-en-el-peru/

# Anexos

### Anexo N°1: EventStorming - Figma

https://www.figma.com/design/bBQCiFvraA0jM3SFmloKWi/Event-Storming---IoT?node-id=0-1&t=uHqde6eWHW5RX70z-1 

### Anexo N°2: Video Entrevistas - TB1

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120430_upc_edu_pe/EfzTMIMyG21NhDYkWcIYIW4Bqez_n89UYtLGVZP2rhv7wg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=PqnF4I 

### Anexo N°3: Video Exposicion - TB1

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120430_upc_edu_pe/Ec0vHNEl-PFKtUFc6u9QPw8B6os5ydM3cMbI07MyLXU2ow?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=2c0F93

## Anexo N°4: Repositorio del Informe.

https://github.com/IoT-AgroConnect/Project-Report
