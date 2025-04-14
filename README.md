# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

![UPC Logo](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

## "Informe de Trabajo Final"

**A1SI0729 - Desarrollo de Aplicaciones Open Source**

**Ingeniería de Software – 5to Ciclo**

**Profesor:** Alberto Wilmer Sánchez Seña  
**Sección:** 4313  
**Startup:** BetterLife  
**Producto:** CleanView  

---

### Integrantes:

| Nombre                                | Código       |
|---------------------------------------|--------------|
|Renzo Sebastian Uribe Livia            |U202311745    |
|Fabian Alejandro Oliva Lopez           |U202312013    |
|Marcia Victoria Melgarejo Gomez        |U20231C505    |
|Gabriel Fernando Gordon Salas          |U20221E229    |
|Valentino Sandoval Paiva               |U20211A962    |

**Abril 2025**

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
|--------|-------|-------|-------------------------------|
|        |       |       |                               |

---

## Project Report Collaboration Insights

Repositorio del repositorio del **Project Report**: [)

---

## Student Outcome

| Criterio Específico                                                                 | Acciones realizadas | Conclusiones |
|-------------------------------------------------------------------------------------|---------------------|--------------|
| 3.c1 Comunica de manera oral con efectividad a diferentes rangos de audiencia       |                     |              |
| 3.c2 Comunica por escrito con efectividad rangos de audiencia                       |                     |              |

## Repertorio

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
    - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
      - [4.2.1. Organization Systems](#421-organization-systems)
      - [4.2.2. Labeling Systems](#422-labeling-systems)
      - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
      - [4.2.4. Searching Systems](#424-searching-systems)
      - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
      - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [Desktop Web Browser:](#desktop-web-browser)
        - [Mobile Web Browser:](#mobile-web-browser)
      - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
        - [Desktop Web Browser:](#desktop-web-browser-1)
        - [Mobile Web Browser:](#mobile-web-browser-1)
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
    - [4.8. Database Design](#48-database-design)
    - [4.7.2. Database Dictionary](#472-database-dictionary)
      - [4.8.1. Database Diagram](#481-database-diagram)
  - [Capítulo V: Product Implementation, Validation \& Deploymentt](#capítulo-v-product-implementation-validation--deploymentt)
    - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
  - [Diseño y Desarrollo](#diseño-y-desarrollo)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
    - [5.2 Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
    - [5.2.1 . Sprint 1](#521--sprint-1)
      - [5.2.1.1 Sprint Planning 1.](#5211-sprint-planning-1)
      - [5.2.1.2 Sprint Backlog 1.](#5212-sprint-backlog-1)
      - [5.2.1.3 Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4 Testing Suite Evidence for Sprint Review.](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5 Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6 Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7 Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8 Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2 . Sprint 2](#522--sprint-2)
      - [5.2.2.1 Sprint Planning 2.](#5221-sprint-planning-2)
      - [5.2.2.2 Sprint Backlog 2.](#5222-sprint-backlog-2)
      - [5.2.2.3 Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
      - [5.2.2.4 Testing Suite Evidence for Sprint Review.](#5224-testing-suite-evidence-for-sprint-review)
      - [5.2.2.5 Execution Evidence for Sprint Review.](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6 Services Documentation Evidence for Sprint Review.](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7 Software Deployment Evidence for Sprint Review.](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8 Team Collaboration Insights during Sprint.](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3 . Sprint 3](#523--sprint-3)
      - [5.2.3.1 Sprint Planning 3.](#5231-sprint-planning-3)
      - [5.2.3.2 Sprint Backlog 3.](#5232-sprint-backlog-3)
      - [5.2.3.3 Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)
      - [5.2.3.4 Testing Suite Evidence for Sprint Review.](#5234-testing-suite-evidence-for-sprint-review)
      - [5.2.3.5 Execution Evidence for Sprint Review.](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6 Services Documentation Evidence for Sprint Review.](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7 Software Deployment Evidence for Sprint Review.](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8 Team Collaboration Insights during Sprint.](#5238-team-collaboration-insights-during-sprint)
    - [5.2.4 . Sprint 4](#524--sprint-4)
      - [5.2.4.1 Sprint Planning 4.](#5241-sprint-planning-4)
      - [5.2.4.2 Sprint Backlog 4.](#5242-sprint-backlog-4)
      - [5.2.4.3 Development Evidence for Sprint Review](#5243-development-evidence-for-sprint-review)
      - [5.2.4.4 Testing Suite Evidence for Sprint Review.](#5244-testing-suite-evidence-for-sprint-review)
      - [5.2.4.5 Execution Evidence for Sprint Review.](#5245-execution-evidence-for-sprint-review)
      - [5.2.4.6 Services Documentation Evidence for Sprint Review.](#5246-services-documentation-evidence-for-sprint-review)
      - [5.2.4.7 Software Deployment Evidence for Sprint Review.](#5247-software-deployment-evidence-for-sprint-review)
      - [5.2.4.8 Team Collaboration Insights during Sprint.](#5248-team-collaboration-insights-during-sprint)
    - [5.3 Validation Interviews](#53-validation-interviews)
      - [5.3.1 Diseño de Entrevistas](#531-diseño-de-entrevistas)
      - [5.3.2 Registro de Entrevistas](#532-registro-de-entrevistas)
      - [5.3.3 Evaluaciones según Heurísticas](#533-evaluaciones-según-heurísticas)
    - [5.4 Video About-the-Product](#54-video-about-the-product)
    - [Conclusiones](#conclusiones)
    - [Bibliografia](#bibliografia)
    - [Anexos](#anexos)

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción del Startup

En el contexto actual, muchas empresas enfrentan el desafío de gestionar de manera eficiente sus residuos y cumplir con las normativas ambientales, mientras buscan reducir costos operativos. **CleanView** surge como una solución tecnológica que permite a las empresas gestionar sus residuos de manera eficiente, optimizando los procesos de reciclaje y ayudando a reducir la generación de desechos a través de la inteligencia artificial y análisis de datos en tiempo real.

**Misión**:
Ofrecer una plataforma innovadora en tiempo real para ayudar a las empresas a gestionar sus residuos de manera eficiente, facilitando el monitoreo, la reducción de desechos y el cumplimiento de normativas ambientales. Trabajamos en conjunto con nuestros segmentos objetivos para crear soluciones que optimicen sus procesos, con el compromiso de seguir los códigos éticos y morales que establece la Universidad Peruana de Ciencias Aplicadas, en cumplimiento con las normas APA 7 para garantizar la legibilidad y claridad en nuestra documentación.

**Visión**:
Ser la herramienta líder en la gestión de residuos para empresas a nivel global, ayudando a miles de negocios a optimizar sus operaciones, reducir costos asociados a la gestión de desechos y promover la sostenibilidad ambiental mediante el uso de tecnología innovadora.

**Valores**:

- **Innovación y sostenibilidad**  
- **Compromiso con el medio ambiente**  
- **Transparencia y confianza**  
- **Eficiencia y calidad**


#### 1.1.2. Perfiles de integrantes del equipo

| Nombre                        | Rol                     | Contacto                                   | Habilidades y conocimientos técnicos |
|-------------------------------|-------------------------|--------------------------------------------|--------------------------------------|
| Renzo Sebastian Uribe Livia   | Ingeniero de software   | renzosebastianuribelivia@gmail.com         | Desarrollo en C++, diseño de HTML    |
| Fabian Alejandro Oliva Lopez  | Ingeniero de sofware    | fabianalejandro1001@gmail.com              | Desarrollo en Visual Studio          |                                                                             
| Marcia Victoria Melgarejo Gomez|Ingeniera de Software   |melgarejogomezmarcia@gmail.com              | Desarrollo en C++, HTML, CSS, JS     |
| Gabriel Fernando Gordon Salas | Ingeniero de Software   | gabrielfgs2004@gmail.com                   | Desarrollo en C++, HTML, CSS, JS, SQL, Python|
|                               |                         |                                            |                                      |

## 1.2. Solution Profile

La aplicación lleva por nombre **CleanView**. El propósito de la aplicación se centra en la gestión eficiente de residuos, permitiendo a las empresas acceder a datos detallados sobre la generación de desechos, su almacenamiento adecuado y las mejores prácticas de reciclaje. Además, facilita el monitoreo en tiempo real de la producción de residuos, notificando a los usuarios cuando es momento de reducir su generación de desechos o coordinar la recolección con centros de reciclaje cercanos.

Finalmente, **CleanView** promete a sus usuarios ser la herramienta clave para gestionar sus residuos de manera inteligente, ayudando a las empresas a reducir pérdidas económicas por mala gestión de desechos, optimizar sus procesos de reciclaje y mejorar la eficiencia operativa. Además, les permitirá tomar decisiones informadas para cumplir con regulaciones ambientales y aumentar la sostenibilidad de sus operaciones.

### 1.2.1 Antecedentes y problemática

Las empresas, especialmente en sectores industriales y comerciales, generan grandes cantidades de residuos diariamente. La falta de herramientas tecnológicas para monitorear y analizar su producción de desechos dificulta la toma de decisiones sostenibles. Esta situación provoca un incremento en los costos operativos, dificulta el cumplimiento de normas ambientales y afecta negativamente su impacto ecológico.

Para comprender mejor esta problemática, se aplica la técnica de las **5W’s + 2H’s**:

#### 🟩 What (¿Qué sucede?)
Las empresas producen residuos en grandes cantidades sin una gestión eficiente. No cuentan con datos claros ni soluciones digitales para reducir, clasificar o reciclar de forma efectiva.

#### 🟩 Why (¿Por qué es un problema?)
La falta de visibilidad y control sobre los residuos:
- Incrementa los costos operativos.
- Impide el cumplimiento de normativas ambientales.
- Afecta la reputación y sostenibilidad de la empresa.
- Desaprovecha oportunidades de ahorro y reciclaje.

#### 🟩 Who (¿A quiénes afecta?)
- A las **empresas** que buscan mejorar su sostenibilidad y reducir costos.
- A los **responsables de operaciones, logística o sostenibilidad** dentro de las organizaciones.
- A la **sociedad en general**, debido al impacto ambiental negativo.

#### 🟩 When (¿Cuándo ocurre?)
De forma **constante**, especialmente conforme las empresas aumentan su producción y volumen de residuos sin adoptar soluciones tecnológicas de control.

#### 🟩 Where (¿Dónde ocurre?)
En **zonas industriales, urbanas y comerciales**, donde operan empresas con poca digitalización en la gestión de residuos. Es más común en países donde la cultura ambiental o normativas aún están en desarrollo.

#### 🟩 How (¿Cómo sucede?)
- Falta de herramientas para medir y analizar residuos.
- No existen alertas o recomendaciones para reducir desechos.
- No hay conexión directa con centros de reciclaje.
- La información, cuando existe, es dispersa y no procesable en tiempo real.

#### 🟩 How Much (¿Cuánto cuesta o impacta?)
- **Económicamente**: Aumentan los gastos por transporte, almacenamiento o multas ambientales.
- **Ambientalmente**: Mayor contaminación y pérdida de materiales reciclables.
- **Socialmente**: Daño a la imagen corporativa y pérdida de confianza de consumidores y aliados estratégicos.


### 1.2.2 Lean UX Process

El proceso de Lean UX se enfoca en crear productos digitales eficientes mediante la experimentación rápida y la validación constante de hipótesis, priorizando la colaboración y el aprendizaje continuo. En el caso de nuestra plataforma de gestión de residuos, el proceso Lean UX se desarrolló en las siguientes fases:

#### Comprender
En esta fase, se realiza una investigación cualitativa y cuantitativa con empresas de diferentes sectores, enfocándonos en entender cómo gestionan actualmente sus residuos. A través de entrevistas y encuestas, descubrimos que la mayoría de las empresas no tienen acceso a datos claros sobre su producción de residuos, lo que dificulta la toma de decisiones informadas y sostenibles. Este entendimiento nos permitió identificar los puntos de dolor principales y las áreas de oportunidad.

#### Esbozar
Con los hallazgos de la investigación, comenzamos a crear prototipos de baja fidelidad para la plataforma. Estos prototipos se enfocaron en funcionalidades clave como:
- **Dashboard** que presenta métricas clave sobre la generación de residuos.
- **Registro de actividades** de reciclaje realizadas por la empresa.
- **Recomendaciones automáticas** para reducir los residuos generados.
- **Mapa interactivo** con centros de reciclaje cercanos a la ubicación de la empresa.

#### Probar
Se realizaron pruebas de usabilidad con empresas piloto que nos permitieron validar la funcionalidad de los prototipos. Durante las pruebas, observamos cómo los usuarios interactuaban con el dashboard y las recomendaciones, y recopilamos feedback sobre la claridad de la interfaz y la utilidad de las funcionalidades. Con esta información, ajustamos el diseño para asegurar que se alineara con las necesidades reales de los usuarios.

#### Medir
Una vez implementados los prototipos mejorados, comenzamos a medir el rendimiento de las funcionalidades clave. Analizamos métricas como la tasa de interacción con el dashboard, el tiempo dedicado a la visualización de los reportes, y la frecuencia con la que los usuarios interactuaban con las recomendaciones. También recopilamos datos sobre la satisfacción del usuario para guiar futuras iteraciones del producto, asegurándonos de que la plataforma fuera fácil de usar y realmente útil para los responsables de la gestión de residuos.



#### 1.2.2.1 Lean UX Problem Statements

##### Problem Statement 1
Muchas empresas generan grandes cantidades de residuos sin contar con herramientas digitales que les permitan monitorear en tiempo real la producción de desechos y el impacto ambiental de sus actividades. Esto genera problemas como el incumplimiento de normativas ambientales, el aumento de costos operativos y la falta de visibilidad sobre los residuos reciclables o peligrosos, afectando tanto su eficiencia como su imagen corporativa.

**¿Cómo podríamos diseñar una solución digital que permita a las empresas tener visibilidad en tiempo real sobre la generación de residuos, ayudándolas a reducir su impacto ambiental, cumplir con regulaciones y optimizar sus costos operativos?**

---

##### Problem Statement 2
En la actualidad, muchas empresas carecen de acceso a datos claros y prácticos sobre cómo reducir su producción de residuos y mejorar sus prácticas de reciclaje. Como resultado, las decisiones se toman sin una base sólida, lo que puede generar desperdicios innecesarios, pérdida de recursos reciclables y un impacto negativo en la sostenibilidad empresarial.

**¿Cómo podríamos diseñar la experiencia dentro de la plataforma para proporcionar a las empresas recomendaciones personalizadas y fáciles de seguir para reducir la generación de residuos y mejorar sus procesos de reciclaje de forma eficiente?**

---

##### Problem Statement 3
Muchos responsables de sostenibilidad o logística dentro de las empresas no tienen visibilidad sobre los centros de reciclaje cercanos ni sobre las fechas óptimas de recolección de residuos. Esto provoca retrasos en la recolección, la acumulación de desechos no reciclados y la falta de acción frente a residuos que podrían ser reciclados o reutilizados.

**¿Cómo podríamos diseñar la plataforma para ofrecer alertas personalizadas y un mapa interactivo de centros de reciclaje cercanos, ayudando a las empresas a coordinar mejor la recolección y optimizar el reciclaje de sus residuos?**

#### 1.2.2.2 Lean UX Assumptions

### 1.2.2.2.1 Business Assumptions
- Existe un mercado no atendido de pequeñas y medianas empresas que requieren soluciones tecnológicas para el monitoreo y gestión de sus residuos.
- Las pérdidas económicas de las empresas están vinculadas a la mala gestión de residuos, lo que genera una necesidad urgente de soluciones para optimizar los procesos de reciclaje y reducir la producción de desechos.
- Las empresas están dispuestas a invertir en soluciones que les permitan mejorar su eficiencia operativa y cumplir con regulaciones ambientales, por lo que podrían ver valor en una plataforma como *Plataforma de Gestión de Residuos*.

### 1.2.2.2.2 Business Outcomes
- Generar oportunidades de monetización mediante un modelo freemium y suscripciones premium, ofreciendo servicios adicionales como reportes detallados y notificaciones personalizadas.
- Mejorar la percepción de la marca de la plataforma como una solución innovadora y eficiente para la gestión de residuos en empresas, especialmente en PyMEs y grandes corporaciones.
- Facilitar alianzas con organizaciones de sostenibilidad y proveedores de reciclaje para fortalecer la red de soluciones disponibles.

### 1.2.2.2.3 User Assumptions
- Los responsables de la gestión de residuos en las empresas no utilizan actualmente herramientas digitales especializadas, sino que se basan en métodos manuales (hojas de cálculo, registros físicos).
- Tienen interés en reducir la producción de residuos y optimizar el reciclaje, pero no siempre saben cómo abordar estas tareas de manera eficiente.
- Existen barreras de conocimiento y recursos para implementar prácticas sostenibles de forma efectiva, por lo que buscan soluciones accesibles y fáciles de usar.

### 1.2.2.2.4 User Outcomes
- Los usuarios reportan una mayor eficiencia en la gestión de residuos, con un mejor seguimiento de los desechos generados y optimización de los procesos de reciclaje.
- Las empresas disminuyen las pérdidas económicas asociadas a la mala gestión de residuos, como los costos por desechos no reciclados o la acumulación innecesaria de desechos.
- Los responsables de sostenibilidad dentro de las empresas logran tomar decisiones más informadas y cumplen con las normativas ambientales de forma más eficaz.

### 1.2.2.3 Lean UX Hypothesis Statements

#### Hypothesis Statement 1
Creemos que lograremos una mejora en la eficiencia en la gestión de residuos y una reducción en los costos asociados a la mala gestión de desechos.

Sabremos que si las empresas  
Obtienen visibilidad en tiempo real sobre la generación de residuos y las oportunidades de reciclaje,  
Cuando veamos con una solución digital que permita monitorear los residuos generados, ofrecer recomendaciones de reducción y conectar con centros de reciclaje cercanos.

---

#### Hypothesis Statement 2
Creemos que lograremos un aumento en la toma de decisiones informadas para la optimización de los procesos de reciclaje y reducción de desechos.

Sabremos que si los responsables de sostenibilidad en las empresas  
Tienen acceso a datos detallados sobre su producción de residuos y sus impactos ambientales,  
Cuando veamos con una funcionalidad que ofrezca recomendaciones claras y datos visuales sobre cómo reducir la generación de residuos y mejorar el reciclaje.

---

#### Hypothesis Statement 3
Creemos que lograremos una mejora en el cumplimiento de normativas ambientales y un aumento en la eficiencia operativa de las empresas.

Sabremos que si las empresas  
Reciben alertas personalizadas y recomendaciones para mejorar sus prácticas de reciclaje y cumplir con las regulaciones ambientales,  
Cuando veamos con un sistema que envíe notificaciones sobre fechas de recolección, objetivos de reducción de residuos y cumplimiento de normativas ambientales.

#### 1.2.2.4. Lean UX Canvas

![Lean Canvas](https://github.com/JKOlimpo/CleanView/blob/547a420da087ae0baa56f920879e0d67cf6886a6/img/Canvas-%20Open%20source.jpg)  
*Nota: Este es un placeholder para el Lean Canvas.*

### 1.3. Segmentos objetivo

**Segmento 1: Personas Naturales**  
- **Características:**  
  - Ciudadanos comprometidos con el medio ambiente o interesados en comenzar prácticas sostenibles.  
  - Edades entre 20 y 60 años.  
  - Nivel socioeconómico medio a alto.  
  - Interés en la gestión de residuos domésticos, reciclaje y reducción del impacto ambiental.

- **Necesidades:**  
  - Aplicación intuitiva para registrar y analizar sus hábitos de consumo y reciclaje.  
  - Recomendaciones personalizadas para reducir su generación de residuos.  
  - Mapa interactivo con centros de reciclaje cercanos.  
  - Alertas y notificaciones sobre fechas de recolección y tips ecológicos.


**Segmento 2: Empresas (PyMEs, Grandes Empresas y ONGs)**  
- **Características:**  
  - Organizaciones de distintos tamaños, desde pequeñas hasta grandes, incluyendo ONGs enfocadas en sostenibilidad.  
  - Sectores como manufactura, comercio, servicios, logística, y tecnología.  
  - Ingresos mensuales variados: desde $10,000 hasta más de $1,000,000 USD.

- **Necesidades:**  
  - Herramientas digitales para monitorear en tiempo real la generación de residuos.  
  - Análisis y reportes detallados sobre impacto ambiental y reducción de costos.  
  - Integración con sistemas internos de gestión.  
  - Recomendaciones prácticas para cumplir con normativas medioambientales.  
  - Funcionalidades colaborativas para conectar con centros de reciclaje y otras instituciones sostenibles.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

**Comimtel**: Comimtel es una de las empresas más reconocidas en Perú en el tratamiento de residuos de aparatos eléctricos y electrónicos (RAEE). Cuenta con más de 20 años de experiencia y se destaca por su enfoque en la valorización de residuos y el cumplimiento de normas ambientales. Su robusto sistema de trazabilidad y su planta de valorización en Lima le permiten operar a nivel nacional, convirtiéndola en un referente del sector de gestión de residuos tecnológicos.

**CARYMA**: Esta empresa peruana se especializa en la gestión integral de residuos sólidos, tanto peligrosos como no peligrosos. CARYMA se caracteriza por su compromiso con el medio ambiente y cuenta con el registro de Empresa Operadora de Residuos Sólidos otorgado por el Ministerio del Ambiente. Su experiencia en recolección, transporte y disposición final de residuos la posiciona como un aliado confiable para industrias que requieren servicios ambientalmente responsables.

**Ulloa**: Con más de 27 años en el mercado, Ulloa S.A. se ha consolidado como una empresa especializada en el transporte y gestión de residuos peligrosos y no peligrosos. Su flota moderna, certificaciones internacionales y alcance nacional le permiten atender a sectores estratégicos como minería, construcción y agroindustria. Ulloa destaca por su enfoque en seguridad, cumplimiento normativo y servicios de destrucción especializada.

### 2.1.1. Análisis competitivo

|Competencia                          | CleanWind                          | Comimtel                                   | CARYMA                               | Ulloa                                |
|-------------------------------------|------------------------------------|--------------------------------------------|--------------------------------------|---------------------------------
|**Precio**                           | Modelo freemium + premium ($15/mes) con reportes avanzados y automatización de recolecciones. | Servicios cotizados según tipo y volumen de RAEE, sin modelo de suscripción digital. | Tarifas bajo cotización. No incluye versiones gratuitas ni autoservicio digital. | Costos tradicionales por tipo de residuo y transporte, sin integración tecnológica. |
|**Confiabilidad**                    | Alta confiabilidad gracias a IoT, validación de actividades, alertas inteligentes y trazabilidad completa. | Procesos estandarizados y confiables en valorización de RAEE, con planta propia. | Cumple con regulación ambiental nacional como EO-RS (Entidad Operadora de Residuos Sólidos). | Amplia experiencia (27+ años), certificaciones ISO y enfoque en residuos industriales. |
|**Información**                      | Dashboard con métricas en tiempo real, análisis de tendencias y reportes automáticos. | Datos trazables pero sin acceso digital ni reportes automatizados. | Información técnica bajo solicitud, sin paneles web. | Manejo documentado tradicional, sin analítica automatizada. |
|**Limitaciones**                     | Requiere conexión a internet y geolocalización habilitada. Plan freemium con acceso limitado. | Limitado a RAEE (residuos eléctricos y electrónicos). | No cuenta con herramientas tecnológicas avanzadas ni analítica predictiva. | Procesos no digitalizados ni automatizados; sin conectividad online. |
|**Características Diferenciales**    |Plataforma web con monitoreo inteligente, mapa de reciclaje, alertas personalizadas, reportes de impacto y conexión con recicladores. | Especialización técnica en RAEE con planta de valorización. | Gestión completa de residuos con enfoque ambiental, pero sin plataforma digital. | Servicios logísticos especializados en residuos industriales, con cobertura nacional. |

### 2.1.2. Estrategias y tácticas frente a competidores.
Nuestra estrategia se basa en la diferenciación tecnológica y el uso de datos en tiempo real para optimizar la gestión de residuos en empresas. Así, nuestras tácticas clave son:

🟩 **Optimizar la experiencia del usuario en la plataforma**

Garantizar que el panel sea visualmente intuitivo, fácil de navegar y accesible para responsables ambientales, operativos y administrativos, lo que impulsa la adopción de la herramienta y fideliza a los clientes.

🟩 **Colaborar con centros de reciclaje y autoridades locales**

Establecer alianzas con entidades recicladoras, municipios y operadores ambientales para facilitar la conexión directa desde la plataforma, automatizando recolecciones y asegurando rutas sostenibles para los residuos.

🟩 **Realizar campañas educativas de concientización ambiental**

Promover buenas prácticas de manejo de residuos, cumplimiento de normativas y beneficios del reciclaje corporativo a través de contenidos digitales, webinars y redes sociales dirigidas a empresas y ciudadanos responsables.

🟩 **Fomentar la adopción de CleanWind**

Ofrecer planes gratuitos con funcionalidades clave, e incentivos como reportes personalizados o conexión con proveedores en los primeros meses, para atraer usuarios iniciales, validar el modelo y generar confianza en el mercado.

## 2.2. Entrevistas
Las entrevistas de usuarios para CleanWind tienen como objetivo principal comprender las necesidades, preocupaciones y expectativas de los usuarios potenciales en relación con la gestión de residuos dentro de sus empresas. Asimismo, se busca identificar las dificultades en la medición, reducción y reciclaje de desechos, así como su interés en herramientas tecnológicas que promuevan una gestión ambiental más eficiente.

### 2.2.1 Diseño de entrevistas
Para el diseño de las entrevistas, se ha tomado en cuenta el perfil de los diferentes segmentos de usuarios de CleanWind (empresas medianas, grandes empresas y ciudadanos interesados en reciclar), así como sus objetivos, características y principales desafíos. Se definieron los objetivos de la investigación, las preguntas clave y los temas a abordar durante cada entrevista.

![entrevistas-1](https://github.com/user-attachments/assets/57cb9e34-cf67-458b-8fc5-b754c461b2f3)
![entrevistas-2](https://github.com/user-attachments/assets/facdca92-c876-402a-968e-008e4612f5d0)

## 2.3. Needfinding

### 2.3.1. User Personas
>  Segmento 1 : Empresas

![user persona 1 - segmento 1](https://github.com/JKOlimpo/CleanView/blob/main/img/User%20Persona-%20Segmento%202.png)

>  Segmento 2 : Personas Naturales

![user persona 1 - segmento 2](https://github.com/JKOlimpo/CleanView/blob/main/img/User%20Persona%202%20-%20Segmento%202.png)

### 2.3.2. User Task Matrix

> Leonardo Dan

| Actividades                                       | Frecuencia | Importancia |
| --------------------------------------------------|------------|-------------|
| Analizar datos en tiempo real                     | Diario     | Alto        |
| Generar reportes de impacto ambiental             | Semanal    | Alto        |
| Revisar cimplimiento de normativas ambientales    | Mensual    | Alto        |
| Capacitar al equipo en uso de la app              | Diario     | Alto        |
 
> Diana Costa

| Actividades                                       | Frecuencia | Importancia |
| --------------------------------------------------|------------|-------------|
| Registrar residuos diarios                        | Diario     | Alto        |
| Monitorear el impacto ambiental                   | Semanal    | Alto        |
| Compartir avances en redes sociales               | Mensual    | Medio       |
| Recibir alertas de recolección                    | Diario     | Alto        |

 
### 2.3.3. User Journey Mapping

![user persona 1 - segmento 1 - JMP 1](https://github.com/JKOlimpo/CleanView/blob/main/img/Journey%20map%201.png)

![user persona 1 - segmento 2 - JMP 2](https://github.com/JKOlimpo/CleanView/blob/main/img/Journey%20map%202.png)

### 2.3.4. Empathy Mapping
![Empathy Mapping 1](https://github.com/JKOlimpo/CleanView/blob/833ad151a9b478ff48b214a388a50ddf0020ed85/img/Empathy%20Mapping%201.png)
![Empathy Mapping -2](https://github.com/JKOlimpo/CleanView/blob/e5df12ba57658d28de4ca1aea7b273765c464a73/img/Empathy%20Mapping-2.png)

### 2.3.5. As-is Scenario Mapping

>  Segmento 1 : Empresas

![AS-IS Segmento 1](https://github.com/JKOlimpo/CleanView/blob/c4fe59115133d1f64908ec68993bf86c4bf7d23d/img/AS-IS%20-%20Segmento%201.jpg)

>Segmento 2 : Personas Naturales

![AS-IS Segmento 2](https://github.com/JKOlimpo/CleanView/blob/c4fe59115133d1f64908ec68993bf86c4bf7d23d/img/AS-IS%20-%20Segmento%202.jpg)

## 2.4. Ubiquitous Language 


# Capítulo III : Requirements Specification 

## 3.1. To-Be Scenario Mapping
>  Segmento 1 : Empresas

![TO-BE Segmento 1](https://github.com/JKOlimpo/CleanView/blob/b47c727e6fd4a4d59d1dd675a468e9aeba787303/img/TO-BE%20-%20Segmento%201.jpg)

>Segmento 2 : Personas Naturales

![TO-BE Segmento 2](https://github.com/JKOlimpo/CleanView/blob/5614947fd18c4e4b2412340d6bdd21dedbe92ebf/img/TO-BE%20-%20Segmento%202.jpg)


## 3.2. User Stories

| Epic / Story ID  | Título  | Descripción  | Criterios de Aceptación  | Relacionado con (Epic ID)  |
|------------------|---------|--------------|---------------------------|-----------------------------|
| US-001           | Monitoreo de residuos en tiempo real | Como empresario quiero visualizar la cantidad y tipo de residuos generados en tiempo real, para tomar decisiones rápidas. | Al acceder al panel, puedo ver datos en tiempo real y alertas por incremento inusual. | EP-001 |
| US-002           | Cumplimiento de normativas ambientales | Como gerente, quiero generar reportes automáticos que cumplan con regulaciones ambientales. | El sistema genera reportes conforme a normativas locales e internacionales. | EP-002 |
| US-003           | Reporte detallado sobre residuos | Como gerente de operaciones, quiero ver reportes detallados, para reducir desperdicios. | El panel muestra tipo, cantidad y origen de residuos. | EP-001 |
| US-004           | Puntos de reciclaje cercanos | Como ciudadano, quiero ver puntos de reciclaje cerca de mi casa. | La app muestra centros de reciclaje en un mapa con filtros por tipo. | EP-003 |
| US-005           | Consejos para manejo de residuos | Como ciudadano, quiero recibir consejos para reducir residuos en casa. | El sistema recomienda buenas prácticas sostenibles basadas en mi actividad. | EP-003 |
| US-006           | Gamificación ecológica | Como ciudadano, quiero recibir puntos por buenas prácticas, para motivarme. | Registro acciones y gano puntos visibles en mi perfil. | EP-003 |
| US-007           | Registro manual de residuos | Como ciudadano, quiero registrar los residuos que genero. | El sistema permite ingresar tipo, cantidad y frecuencia de residuos. | EP-003 |
| US-008           | Alertas por umbrales críticos | Como gerente, quiero alertas cuando los residuos superen un umbral. | Configuro umbrales y recibo alertas por e-mail o app. | EP-001 |
| US-009           | Comparación entre periodos | Como gerente, quiero comparar residuos entre meses. | Gráficos comparativos disponibles en dashboard. | EP-002 |
| US-010           | Ranking interno de sostenibilidad | Como gerente, quiero ver qué áreas generan menos residuos. | La plataforma ordena las áreas por sostenibilidad. | EP-002 |
| US-011           | Exportación de reportes | Como gerente, quiero exportar reportes en PDF o Excel. | Botón de exportación con selección de formato. | EP-002 |
| US-012           | Integración con sensores IoT | Como empresa, quiero usar sensores inteligentes para monitoreo automático. | Datos actualizados automáticamente desde sensores. | EP-001 |
| US-013           | Notificación por tipo de residuo | Como gerente, quiero recibir alertas si un tipo específico de residuo aumenta. | Configuro alertas específicas por categoría. | EP-001 |
| US-014           | Información sobre normativa local | Como ciudadano, quiero saber qué leyes ambientales aplican a mi zona. | Visualización de regulaciones según ubicación. | EP-003 |
| US-015           | Simulación de impacto ambiental | Como usuario, quiero ver una simulación del impacto ambiental de mis residuos. | Gráfico interactivo con equivalencias ecológicas. | EP-003 |
| US-016           | Plan de reducción de residuos | Como empresa, quiero un plan personalizado para reducir residuos. | Sistema sugiere acciones y metas según historial. | EP-001 |
| US-017           | Chat de soporte ambiental | Como usuario, quiero consultar dudas con un asesor ambiental. | Chat disponible en horario laboral con asistencia técnica. | EP-003 |
| US-018           | Gestión de roles y permisos | Como administrador, quiero asignar permisos a cada usuario. | Puedo definir qué usuarios acceden a qué funciones. | EP-002 |
| US-019           | Módulo de auditorías | Como auditor, quiero acceder a reportes históricos y registros. | Panel con auditorías pasadas, descargas y bitácoras. | EP-002 |
| US-020           | Tareas programadas de reciclaje | Como ciudadano, quiero programar recordatorios para reciclar. | Calendario con alertas personalizadas por tipo. | EP-003 |
| US-021           | Verificación de acciones sostenibles | Como gerente, quiero validar si las acciones implementadas reducen residuos. | Módulo compara acciones con impacto posterior. | EP-002 |
| US-022           | Marketplace de reciclaje | Como empresa, quiero vender o donar residuos reciclables a otros actores. | Plataforma conecta generadores con recicladores. | EP-001 |
| US-023           | Panel para municipios | Como entidad pública, quiero ver datos agregados por distrito. | Dashboard con mapas, indicadores y comparación entre zonas. | EP-004 |
| US-024           | Centro de aprendizaje ambiental | Como usuario, quiero aprender sobre sostenibilidad en videos o blogs. | Acceso a recursos educativos segmentados por nivel. | EP-003 |
| US-025           | Integración con APIs externas | Como desarrollador, quiero conectar CleanWind a otras plataformas. | Disponibilidad de API REST para consulta de datos. | EP-002 |
| US-026           | Recomendaciones inteligentes | Como usuario, quiero recomendaciones personalizadas según mis datos. | Sugerencias automáticas basadas en historial y perfil. | EP-003 |
| US-027           | Etiquetado de residuos | Como operario, quiero categorizar residuos desde un móvil. | App permite escanear, clasificar y etiquetar con códigos QR. | EP-001 |
| US-028           | Control de almacenamiento de residuos peligrosos | Como empresa, quiero controlar residuos peligrosos con alertas. | Módulo especializado con alertas y registro histórico. | EP-001 |
| US-029           | Seguimiento de reducción de huella de carbono | Como gerente, quiero ver cómo mis acciones reducen emisiones. | Gráfico que muestra reducción de CO2 equivalente. | EP-002 |
| US-030           | Sistema de insignias por logros sostenibles | Como usuario, quiero recibir insignias por hitos alcanzados. | Insignias visibles en perfil al cumplir metas. | EP-003 |
| US-031           | Escaneo de productos reciclables | Como ciudadano, quiero escanear un producto y saber si es reciclable. | Escaneo por código de barras y sugerencia de reciclaje. | EP-003 |
| US-032           | Foro de comunidad ambiental | Como usuario, quiero compartir ideas y experiencias en sostenibilidad. | Foro accesible por tema, con comentarios y reacciones. | EP-003 |


## 3.3. Impact Mapping

## 3.4. Product Backlog

| # Orden | User Story Id | Título                                           | Descripción                                                                                      | Story Points (1/2/3/5/8) |
|---------|---------------|--------------------------------------------------|--------------------------------------------------------------------------------------------------|--------------------------|
| 1       | US-001        | Monitoreo de residuos en tiempo real             | Como empresario quiero visualizar la cantidad y tipo de residuos generados a tiempo real         | 5                        |
| 2       | US-002        | Cumplimiento de normativas ambientales           | Como gerente, quiero generar reportes automáticos que cumplan con regulaciones ambientales       | 3                        |
| 3       | US-003        | Reporte detallado sobre residuos                 | Como gerente, quiero ver reportes detallados para reducir desperdicios                           | 3                        |
| 4       | US-008        | Alertas por umbrales críticos                    | Como gerente, quiero alertas cuando los residuos superen un umbral crítico                       | 3                        |
| 5       | US-004        | Puntos de reciclaje cercanos                     | Como ciudadano, quiero ver puntos de reciclaje cerca de mi casa                                  | 2                        |
| 6       | US-005        | Consejos para manejo adecuado de residuos        | Como ciudadano, quiero recibir consejos para reducir residuos en el hogar                        | 2                        |
| 7       | US-016        | Plan de reducción de residuos                    | Como empresa, quiero un plan personalizado para reducir residuos                                 | 5                        |
| 8       | US-007        | Registro manual de residuos                      | Como ciudadano, quiero registrar los residuos que genero                                         | 3                        |
| 9       | US-006        | Gamificación ecológica                           | Como ciudadano, quiero recibir puntos por buenas prácticas ecológicas                            | 3                        |
| 10      | US-009        | Comparación entre periodos                       | Como gerente, quiero comparar residuos entre meses                                               | 3                        |
| 11      | US-011        | Exportación de reportes                          | Como gerente, quiero exportar reportes en PDF o Excel                                            | 2                        |
| 12      | US-012        | Integración con sensores IoT                     | Como empresa, quiero usar sensores inteligentes para monitoreo automático                        | 8                        |
| 13      | US-013        | Notificación por tipo de residuo                | Como gerente, quiero recibir alertas por aumento de un tipo de residuo específico                | 2                        |
| 14      | US-014        | Información sobre normativa local                | Como ciudadano, quiero conocer las leyes ambientales de mi zona                                  | 2                        |
| 15      | US-017        | Chat de soporte ambiental                        | Como usuario, quiero consultar dudas con un asesor ambiental                                     | 3                        |
| 16      | US-010        | Ranking interno de sostenibilidad                | Como gerente, quiero ver qué áreas generan menos residuos                                        | 3                        |
| 17      | US-018        | Gestión de roles y permisos                      | Como administrador, quiero asignar permisos a cada usuario                                       | 3                        |
| 18      | US-019        | Módulo de auditorías                             | Como auditor, quiero acceder a registros históricos y bitácoras                                  | 5                        |
| 19      | US-020        | Tareas programadas de reciclaje                  | Como ciudadano, quiero programar recordatorios para reciclar                                     | 2                        |
| 20      | US-021        | Verificación de acciones sostenibles             | Como gerente, quiero validar si las acciones implementadas reducen residuos                     | 5                        |
| 21      | US-022        | Marketplace de reciclaje                         | Como empresa, quiero vender o donar residuos reciclables a otros actores                         | 8                        |
| 22      | US-023        | Panel para municipios                            | Como entidad pública, quiero ver datos agregados por distrito                                   | 5                        |
| 23      | US-024        | Centro de aprendizaje ambiental                  | Como usuario, quiero aprender sobre sostenibilidad en videos o blogs                             | 3                        |
| 24      | US-015        | Simulación de impacto ambiental                  | Como usuario, quiero ver una simulación del impacto ambiental de mis residuos                    | 3                        |
| 25      | US-025        | Integración con APIs externas                    | Como desarrollador, quiero conectar CleanWind a otras plataformas                                | 5                        |
| 26      | US-026        | Recomendaciones inteligentes                     | Como usuario, quiero recomendaciones personalizadas según mis datos                              | 5                        |
| 27      | US-027        | Etiquetado de residuos                           | Como operario, quiero categorizar residuos desde un móvil                                        | 3                        |
| 28      | US-028        | Control de almacenamiento de residuos peligrosos | Como empresa, quiero controlar residuos peligrosos con alertas                                  | 5                        |
| 29      | US-029        | Seguimiento de huella de carbono                 | Como gerente, quiero ver cómo mis acciones reducen emisiones                                     | 3                        |
| 30      | US-030        | Sistema de insignias por logros sostenibles      | Como usuario, quiero recibir insignias por hitos alcanzados                                      | 2                        |
| 31      | US-031        | Escaneo de productos reciclables                 | Como ciudadano, quiero escanear un producto y saber si es reciclable                             | 3                        |
| 32      | US-032        | Foro de comunidad ambiental                      | Como usuario, quiero compartir ideas y experiencias sobre sostenibilidad                         | 2                        |


## Capítulo V: Product Implementation, Validation & Deploymentt

### 5.1. Software Configuration Management.

La Gestión de Configuración de Software (SCM, por sus siglas en inglés) es una disciplina en el desarrollo de software encargada de identificar, controlar y rastrear los componentes del software a lo largo de su ciclo de vida. Esta metodología facilita la administración organizada de cambios en documentos, códigos y otros elementos durante el proceso de desarrollo, garantizando así una gestión eficiente y ordenada. Su objetivo principal es mejorar la eficiencia del equipo de desarrollo y minimizar los errores. (Martin, 2023)

### 5.1.1. Software Development Environment Configuration.

**Directrices de Desarrollo para CleanView**

En esta sección, presentaremos las convenciones y prácticas recomendadas que hemos adoptado en HTML, CSS y JavaScript para el desarrollo de CleanView, nuestra plataforma tecnológica orientada a la gestión eficiente de residuos en empresas. Este conjunto de lineamientos ha sido diseñado para garantizar una estructura coherente del código, facilitar su mantenibilidad y optimizar el rendimiento de nuestra solución en tiempo real.

Dado que CleanView busca responder a los desafíos actuales en torno a la sostenibilidad empresarial —como la reducción de costos operativos y el cumplimiento de normativas ambientales—, estas buenas prácticas permiten que nuestro sistema se mantenga robusto, escalable y alineado con los principios de innovación y responsabilidad ética promovidos por la Universidad Peruana de Ciencias Aplicadas.

A continuación, detallaremos cómo se aplican estas convenciones en cada una de las tecnologías utilizadas, contribuyendo a una plataforma confiable que apoya a las empresas en el monitoreo, análisis y reducción de desechos mediante inteligencia artificial y análisis de datos en tiempo real.

**Definición de Requisitos**

Antes de iniciar el desarrollo de CleanView, resulta fundamental definir con precisión los requisitos funcionales y técnicos que darán forma a la plataforma. Estos requisitos reflejan nuestro compromiso con la sostenibilidad ambiental, la eficiencia operativa y el cumplimiento normativo, y se enfocan en proporcionar herramientas tecnológicas efectivas para empresas que buscan mejorar su gestión de residuos. Tales como:

- **Automatización de Procesos:** Desarrollo de funcionalidades que optimicen y automaticen procesos de gestión de residuos, reduciendo la intervención manual y mejorando la eficiencia operativa.
- **Gestión Inteligente de Datos:** Implementación de bases de datos robustas que permitan una administración precisa, segura y accesible de la información relacionada con residuos y reciclaje.
- **Personalización por Empresa:** Capacidades de configuración adaptables a las necesidades específicas de cada empresa, considerando su tamaño, sector y ubicación.
- **Colaboración y Monitoreo en Tiempo Real:** Herramientas que fomenten la colaboración entre equipos de trabajo y permitan un seguimiento en tiempo real del cumplimiento de objetivos ambientales, integrando metodologías ágiles de gestión.

**Elección de la Tecnología**

Con base en estos requisitos, hemos seleccionado un conjunto de tecnologías modernas que nos permiten construir una solución escalable, segura y de alto rendimiento para CleanView. Estas tecnologías no solo responden a las necesidades del sistema, sino que también aseguran una experiencia de usuario intuitiva y eficiente, alineada con nuestra misión de promover la sostenibilidad mediante la innovación tecnológica.

- **Frontend:** Angular para una interfaz de usuario dinámica y receptiva, que permita una interacción fluida con las herramientas de gestión y análisis.

- **Configuración del Entorno de Desarrollo** ItelliJ IDEA

  - **Editor de Código**: IntelliJ IDEA.
  - **Propósito**: Desarrollo de software y edición de código.
  - **Ruta de descarga**: https://www.jetbrains.com/idea/download/

- **Editor de Código:** Visual Studio Code

  - **Propósito:** Desarrollo y edición de código con soporte extensivo para JavaScript y herramientas de desarrollo.
  - **Ruta de descarga:** https://code.visualstudio.com/

- **Control de Versiones:** Git, con repositorios en GitHub.
  - **Propósito:** Gestión de versiones y colaboración en el código.
  - **Ruta de descarga:** https://git-scm.com/
  - **Repositorio:** https://github.com/1ASI0729-2510-4313-G1-CleanView

**Product UX/UI Design**

- **UI/UX:** Crear una interfaz amigable y accesible para los usuarios.
  - **Herramienta:** Figma
  - **Propósito:** Diseño de prototipos y interfaces de usuario.
  - **Ruta del Figma**: https://www.figma.com/design/bXnTP7xfO3bneisawRwlM5/Untitled?node-id=0-1&p=f&t=OTruJWbPB0L0sV6e-0

![FIGMA](img/figma.png)

**Software Development**
**HTML:**

- **Descripción:** El lenguaje base de etiquetado para aplicaciones web sera empleado en este proyecto.
- **Enlace:** https://www.w3schools.com/html/default.asp
  **CSS:**
- **Descripción:** Cascade Styles Sheet maneja el diseño visual de la landing page.
- **Enlace:** https://www.w3schools.com/css/default.asp

Con CleanView, buscamos no solo ofrecer herramientas tecnológicas avanzadas para la gestión eficiente de residuos, sino también posicionarnos como un socio estratégico para las empresas. Nuestra plataforma está diseñada para impulsar el crecimiento sostenible de nuestros clientes, ayudándolos a cumplir con las normativas ambientales, optimizar sus procesos operativos y destacar en un mercado cada vez más competitivo y comprometido con la responsabilidad ambiental.

### 5.1.2. Source Code Management.

**Gestión de Cambios en el Código Fuente con GitHub**

En esta sección, nuestro equipo detalla los métodos y la estructura organizativa para gestionar los cambios en el código fuente utilizando GitHub como plataforma de control de versiones. Hemos configurado un repositorio remoto en GitHub para almacenar el código fuente y facilitar la colaboración entre los miembros del equipo. Los URLs de los repositorios son los siguientes:

- **Landing Page**: https://github.com/1ASI0729-2510-4313-G1-CleanView/Landing-Page
- **Frontend Web Applications**: 
- **Backend Web Applications**: 

**Estructura del Repositorio**

Hemos organizado el repositorio en ramas específicas para diferentes etapas del desarrollo, garantizando un flujo de trabajo ordenado y eficiente. La estructura de ramas es la siguiente:

- **Main branch (rama principal):** Contiene la versión estable y lista para producción del software.
- **Develop branch:** Contiene el código en desarrollo que se integrará en la rama principal después de ser probado y validado.

Además, para el desarrollo de nuevas funcionalidades, creamos ramas específicas siguiendo las convenciones de nomenclatura:

- **Feature branches:** Ramas dedicadas al desarrollo de nuevas características. La nomenclatura para estas ramas es `feature/nueva-funcionalidad`.

Implementamos GitFlow, un modelo de ramificación diseñado por Vincent Driessen, que incluye las siguientes ramas:

- **Main branch:** Rama principal que alberga el código estable y preparado para producción.
- **Develop branch:** Rama de desarrollo donde se integran nuevas funcionalidades y correcciones antes de ser fusionadas a la rama principal.
- **Feature branches:** Creadas a partir de `develop` para añadir nuevas características, siguiendo la nomenclatura `feature/nueva-funcionalidad`.
- **Release branches:** Preparadas para la liberación de nuevas versiones, permitiendo pruebas finales y corrección de errores antes del despliegue a producción.
- **Hotfix branches:** Utilizadas para corregir errores críticos en producción, siguiendo la nomenclatura `hotfix/correccion-critica`.

**Mensajes de Commits**

Adoptamos el estándar Conventional Commits para los mensajes de nuestros commits, lo que facilita la comprensión del historial de cambios y la automatización de versiones. Ejemplos de mensajes son:

- **feat:** Añadir nueva funcionalidad, por ejemplo, `feat: implementar sistema de notificaciones`.
- **fix:** Corregir errores, por ejemplo, `fix: solucionar problema con la validación de datos`.
- **docs:** Actualizar documentación, por ejemplo, `docs: actualizar guía de instalación`.
- **style:** Aplicar formato, por ejemplo, `style: ajustar estilo de código según las pautas`.
- **refactor:** Mejorar el código sin cambiar su funcionalidad, por ejemplo, `refactor: optimizar el rendimiento del módulo de usuario`.
- **test:** Añadir o modificar pruebas, por ejemplo, `test: añadir pruebas para la funcionalidad de autenticación`.

**Documentación**

La documentación del proyecto se encuentra en el archivo `README.md` dentro del repositorio. Este archivo proporciona detalles sobre la configuración, el uso del software y las guías para contribuir al proyecto.

### 5.1.3. Source Code Style Guide & Conventions.

En el _Source Code Style Guide_, presentaremos las convenciones, estilos, diseños y principios aplicados en los lenguajes utilizados durante el desarrollo de nuestro producto. Los lenguajes y herramientas empleados incluyen:

**LENGUAJES UTILIZADOS**

- **_HTML_** : Estructura del contenido en la web, utilizando etiquetas semánticas para mejorar la accesibilidad.
- **_CSS_**: Estilos y diseño visual del software, garantizando una experiencia de usuario óptima.
- **_JavaScript_**: Lógica y funcionalidad interactiva, permitiendo la automatización y personalización del software.
- **_TypeScript_**: Superset de JavaScript que añade tipado estático y otras características para mejorar la mantenibilidad y la detección de errores en tiempo de compilación.

**HTML**

- **Nombres Descriptivos:** Utiliza nombres de clases e IDs que sean descriptivos y significativos, facilitando la comprensión del propósito de cada elemento. Por ejemplo, en lugar de `box`, usa `project-card`.

- **Indentación:** Indenta correctamente el código HTML para mejorar la legibilidad y mantener una estructura clara.

- **Etiquetas Semánticas:** Emplea etiquetas semánticas apropiadas, como `<header>`, `<nav>`, `<main>`, y `<footer>`, para mejorar la accesibilidad y el SEO del sitio.
- **Comentarios:** Usa comentarios para explicar secciones complejas o partes importantes del código HTML, facilitando la comprensión para otros desarrolladores.

**CSS**

- **Nombres Descriptivos:** Utiliza nombres de clases y selectores que sean descriptivos y coherentes para facilitar la identificación y el mantenimiento de los estilos. Por ejemplo, usa `btn-submit` en lugar de `btn`.
- **Agrupación y Comentarios:** Agrupa propiedades relacionadas y separa secciones de CSS con comentarios claros, como /_ Estilos de botones _/. Esto organiza el código y facilita su navegación.
- **Preferencia por Clases:** Prefiere el uso de clases en lugar de IDs para estilos reutilizables y más flexibles.
- **Compatibilidad y Prefijos:** Utiliza prefijos de vendedor y asegúrate de que el código sea compatible con diferentes navegadores cuando sea necesario.
- **Medidas Relativas:** Usa medidas relativas como `em`, `rem`, y `%` en lugar de medidas absolutas para mejorar la flexibilidad y la accesibilidad del diseño.

**JavaScript**

- **Nombres Descriptivos:** Usa nombres de variables y funciones que sean descriptivos y significativos para que el código sea autoexplicativo, `fetchProjectData` en lugar de `getData`..
- **Comentarios:** Incluye comentarios para explicar la lógica compleja o el propósito de las funciones. Esto facilita la comprensión y el mantenimiento del código.
- **Espacios y Sangrías:** Utiliza espacios en blanco y sangrías para mejorar la legibilidad del código. Sigue un estilo consistente en todo el código.
- **Modularidad:** Evita la creación de funciones globales. Utiliza módulos o patrones de diseño para modularizar el código y evitar conflictos de nombres.
- **Convención de Nombres:** Emplea `camelCase` para nombrar variables y funciones, siguiendo una convención consistente.

**TypeScript**

- **Tipado Estático:** Utiliza el tipado estático de TypeScript para definir los tipos de variables, parámetros de funciones y retornos. Esto ayuda a detectar errores de manera anticipada. Por ejemplo, en lugar de `let age = "25"`, define el tipo correctamente: `let age: number = 25`.

- **Interfaces y Tipos Personalizados:** Define interfaces y tipos personalizados para describir la forma de los objetos y otros datos complejos. Esto mejora la claridad del código y facilita su mantenimiento. Ejemplo:

  ```typescript
  interface Project {
    id: number;
    name: string;
    description: string;
  }
  ```

- **Decoradores y Clases:** Emplea clases y decoradores para aprovechar las características orientadas a objetos de TypeScript, facilitando la organización del código, especialmente en Angular. Ejemplo de clase:

  ```typescript
  class User {
    constructor(public name: string, public age: number) {}
  }
  ```

- **Manejo de Errores en Tiempo de Compilación:** TypeScript permite identificar errores en tiempo de compilación, lo que reduce problemas en tiempo de ejecución. Aprovecha este control para escribir código más seguro.

- **Convención de Nombres:** Sigue las mismas convenciones de JavaScript, utilizando `camelCase` para variables y funciones, pero aplicando también la convención `PascalCase` para clases e interfaces.

- **Convenciones y Nomenclaturas:** Es necesario definir las convenciones y nomenclaturas que se utilizarán en el proyecto. Esto incluye el uso de `camelCase` para variables y funciones, `PascalCase` para clases e interfaces, y nombres de métodos descriptivos para mejorar la legibilidad del código.

**Comentarios**

- **Propósito y Complejidad:** Utiliza comentarios para explicar el propósito de bloques de código, funciones o partes complejas del código. Asegúrate de que añadan valor y contexto.
- **Actualización de Comentarios:** Mantén los comentarios actualizados a medida que el código evoluciona para evitar información desactualizada.
- **Evita Comentarios Redundantes:** Evita comentarios obvios o redundantes que no añaden información útil. Los comentarios deben proporcionar claridad y contexto adicional.

**Convenciones y Nomenclaturas**

- **Referencias de Nomenclatura:** Para la nomenclatura de elementos, adoptaremos convenciones inspiradas en **BEM (Block Element Modifier)** y **OOCSS (Object-Oriented CSS)**, promoviendo claridad y reutilización.

- **Estructura de Nombres:** Los nombres de las clases deben ser compuestos por tres partes: bloque, elemento y modificador. Por ejemplo, un botón de envío puede llamarse `btn--primary`, donde `btn` es el bloque y `primary` es el modificador.

### 5.1.4. Software Deployment Configuration.

En los siguientes pasos se explicará cómo llevar a cabo la implementación de nuestro sitio web utilizando GitHub Pages

**Deploy con GitHub Pages:**
En primer lugar, accedemos al repositorio de GitHub donde se encuentra nuestro proyecto y luego navegamos hacia la configuración del repositorio.

* LINK LANDING PAGE DESPLEGADA: https://1asi0729-2510-4313-g1-cleanview.github.io/Landing-Page/

![Settings](img/landing1.png)

Dentro del menú de ajustes, elegimos la opción "Pages".
![Settings](img/landing2.png)
**Control de Versiones**

- **Uso de Git:** Mantén un historial completo de cambios y facilita el manejo de diferentes versiones del código.

En la sección de GitHub Pages, escogemos la rama principal (main) en el menú desplegable de la sección "Branch" y guardamos la configuración presionando el botón "Save".
Después de unos momentos, recibiremos el enlace a nuestro sitio web publicado en GitHub Pages.

### 5.2 Landing Page, Services & Applications Implementation.

El desarrollo, testeo y despliegue de nuestra landing page es importante para que nuestros clientes puedan acceder a la información sobre nuestra empresa y producto a través de una interfaz con diseño responsivo, navegación intuitiva y solo con información relevante. Esta primera etapa nos permite crear un diseño conceptual sobre la estética que nuestra aplicación completa y lista para su uso. Estas etapas nos ayudaran a dar una primera impresión a los clientes para validar ideas e identificar problemas que se deben solucionar.


### 5.2.1 . Sprint 1

El primer sprint representa una etapa clave dentro de nuestro marco de trabajo basado en la metodología ágil Scrum. Durante este periodo inicial en el desarrollo de CleanView, se llevan a cabo reuniones orientadas a fortalecer el conocimiento entre los integrantes del equipo, permitiendo identificar fortalezas individuales y fomentar una colaboración efectiva.

Asimismo, se realiza la asignación de tareas enfocadas en convertir los requerimientos y funcionalidades previamente definidos en una landing page funcional, la cual no solo represente visualmente a CleanView, sino que también cumpla con principios de usabilidad y heurísticas de diseño. Este primer entregable constituye la base visual y técnica del proyecto, alineada con nuestros objetivos de sostenibilidad y eficiencia operativa.

#### 5.2.1.1 Sprint Planning 1.

El sprint planning es una reunion antes de cada sprint en la metodologia Scrum donde el equipo elige las user stories que va a transformar en un producto tangible. Tambien define que como se van a separar los trabajos y quien sera responsable. Nuestro objetivo sera construir un plan resolubre en un tiempo determinado que sera lo que dure el sprint, para crearlo fomentaremos la colaboracion para que todos sepan y entiendas los objetivos y prioridades.

| Sprint #| Sprint 1|
| -- | -- |
| **Sprint Planning Background**||
| **Date**| 14/04/2025|
| **Time**| 18:00 PM|
| **Location**| Discord (Reunión virtual)|
| **Prepared By**| Sandoval Paiva, Valentino|
| **Attendees (to planning meeting)** | Renzo Sebastian Uribe Livia, Fabian Alejandro Oliva Lopez, Marcia Victoria Melgarejo Gomez, Gabriel Fernando Gordon Salas, Valentino Sandoval Paiva|
| **Sprint Goal & User Stories**||
| **Sprint 1 Goal**| Nuestro enfoque está en finalizar el informe y desplegar nuestra Landing Page desde el repositorio de GitHub. Creemos que esto entrega una experiencia de usuario optimizada a nuestros clientes. Esto se confirmará cuando todas las tareas se muevan a la columna "Terminado" en Trello. |
| **Sprint 1 Velocity**| ------ |
| **Sum of Story Points**| 19 |

#### 5.2.1.2 Sprint Backlog 1.

Para el primer sprint backlog, recopilamos historias de usuario relacionadas con la página de inicio (landing page) . Para organizar y administrar estas historias de usuario, las dividimos en tareas fáciles de realizar y las asignamos a los miembros del equipo de manera efectiva, utilizamos la herramienta Trello. Nos concentramos en completar las historias de usuario durante este sprint, con el objetivo principal de crear una landing page completa con un diseño atractivo y fácil de usar. Gracias a Trello, pudimos colaborar efectivamente y seguir el progreso de las tareas, lo que nos permitió abordar y resolver

![alt text](assets/TB1-image/Trelloo1.png)


Link Trello: 

#### 5.2.1.3 Development Evidence for Sprint Review




#### 5.2.1.4 Testing Suite Evidence for Sprint Review.


#### 5.2.1.5 Execution Evidence for Sprint Review.

En este Sprint, los miembros del equipo de desarrollo de software de CleanView han completado y desplegado la Landing Page. A continuación, mostramos imágenes que demuestran cómo nuestra página presenta de manera clara e intuitiva la información sobre nuestro producto y nuestra empresa.

<p align="center">
  <img src="img/lp1.png">
  <br>
  Vista general de la Landing Page, destacando el diseño limpio y moderno que permite a los usuarios navegar fácilmente por la información.
</p>

<p align="center">
  <img src="img/lp2.png">
  <br>
  Sección de soluciones clave del producto, mostrando cómo se presentan de manera atractiva y accesible para atraer a los usuarios.
</p>

<p align="center">
  <img src="img/lp3.png">
  <br>
La sección “How Work” está diseñada para ofrecer una explicación visual y sencilla del funcionamiento de la plataforma CleanView, diferenciando la experiencia para empresas y usuarios individuales. A través de tarjetas ilustradas y pasos numerados, se guía a cada tipo de usuario en el proceso de uso de la plataforma, desde el registro hasta la interacción con funciones clave como la recolección de residuos, sugerencias personalizadas y generación de reportes.

Esta sección tiene como objetivo proporcionar una comprensión rápida y accesible del valor y operatividad de CleanView, contribuyendo a una mejor experiencia de usuario desde el primer contacto con la plataforma.
</p>

<p align="center">
  <img src="img/LP4.png">
  <br>
 La sección Contacto de CleanView está diseñada para facilitar una comunicación directa y efectiva entre los usuarios y el equipo de soporte. Está compuesta por dos áreas diferenciadas: un panel informativo con los canales de contacto oficiales (correo electrónico, teléfono fijo y número móvil) y un formulario interactivo donde los usuarios pueden enviar consultas, comentarios o solicitudes personalizadas.

Esta interfaz intuitiva permite ingresar datos básicos como nombre, teléfono, correo electrónico y mensaje, simplificando el proceso de atención y garantizando una respuesta oportuna. De esta manera, CleanView refuerza su compromiso con la atención al cliente y el acompañamiento continuo en el uso de la plataforma.
</p>


</p>

#### 5.2.1.7 Software Deployment Evidence for Sprint Review.

**Resumen**
Durante este Sprint, nos hemos enfocado en el despliegue de la landing page. Las actividades realizadas incluyen la configuración del entorno de desarrollo y el despliegue inicial del sitio. A continuación, se detalla el proceso seguido para el despliegue de la landing page.

**Actividades Realizadas**

- Creación de Cuentas y Configuración de Recursos:

Proveedor de Hosting: Selección y configuración de la cuenta en el proveedor de hosting para desplegar la landing page.
Configuración del Entorno: Establecimiento del entorno de desarrollo y producción para la landing page.

- Configuración de Proyectos para Integración:

Repositorio de Código: Configuración del repositorio en GitHub para la integración continua y despliegue automático.
Automatización: Configuración de scripts y herramientas para la automatización del despliegue.

- Despliegue de la Landing Page:

Subida de Archivos: Transferencia de archivos y recursos al servidor de hosting.
Verificación: Comprobación de que la landing page se despliega correctamente y está accesible en la web.

**Deploy del Landing Page**
![deploy](img/lp1.png)
**Capturas de Pantalla**

- Repositorio de Landing Page:
  ![alt text](img/landing23.png)

**Enlace al Repositorio**: https://github.com/1ASI0729-2510-4313-G1-CleanView/Landing-Page

#### 5.2.1.8 Team Collaboration Insights during Sprint.

En esta sección, se presenta un análisis detallado de la colaboración del equipo durante el Sprint. Durante este sprint, las actividades de implementación se organizaron siguiendo una metodología ágil, garantizando una colaboración fluida entre los miembros del equipo. Se exponen capturas de los analíticos de colaboración y de los commits realizados en GitHub, lo que permite visualizar la contribución individual de cada miembro del equipo.

- Diseño y Desarrollo:
  Diseño de la Landing Page: Desarrollo y diseño completo de la landing page, incluyendo la creación de secciones y funcionalidad.
  Implementación: Realización de las tareas de codificación, pruebas y ajustes necesarios para completar la página.
- Documentación y Despliegue:
  Documentación: Creación de documentación relevante para la landing page, incluyendo capturas de pantalla y descripciones.
  Despliegue: Configuración del entorno de despliegue y transferencia de archivos al servidor.

**Landing Page**

![Commits](assets/TB1-new/landingc1.jpeg)
![Commits](assets/TB1-new/landingc2.jpeg)


- Valentino Sandoval Paiva: 
- Renzo Sebastian Uribe Livia	
- Fabian Alejandro Oliva Lopez	
- Marcia Victoria Melgarejo Gomez	
- Gabriel Fernando Gordon Salas	


**Report:**

![alt text](assets/TB1-new/commitsall2.jpeg)

![alt text](assets/TB1-new/commitall1.jpeg)

![alt text](assets/TB1-image/commitsreport3.jpeg)

![Commits](assets/TB1-image/commitsreport3.jpeg)


- Renzo Sebastian Uribe Livia	
- Fabian Alejandro Oliva Lopez	
- Marcia Victoria Melgarejo Gomez	
- Gabriel Fernando Gordon Salas	
- Valentino Sandoval Paiva: 

