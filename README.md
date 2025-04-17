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

1. [Capítulo I: Introducción]
   - [1.1 Startup Profile]
     - [1.1.1 Descripción de la Startup]
     - [1.1.2 Perfiles de Integrantes del equipo]
   - [1.2 Solution Profile]
     - [1.2.1 Antecedentes y problemática]
     - [1.2.2 Lean UX Process]
       - [1.2.2.1 Lean UX Problem Statements]
       - [1.2.2.2 Lean UX Assumptions]
       - [1.2.2.3 Lean UX Hypothesis Statements]
       - [1.2.2.4 Lean UX Canvas]
   - [1.3 Segmentos Objetivo]
  
2. [Capítulo II: Requirements Elicitation & Analysis]  
   - [2.1 Competidores]  
     - [2.1.1 Análisis competitivo]  
     - [2.1.2 Estrategias y tácticas frente a competidores]  
   - [2.2 Entrevistas]  
     - [2.2.1 Diseño de entrevistas]  
     - [2.2.2 Registro de entrevistas]  
     - [2.2.3 Análisis de entrevistas]  
   - [2.3 Needfinding]  
     - [2.3.1 User Personas]  
     - [2.3.2 User Task Matrix]  
     - [2.3.3 User Journey Mapping]  
     - [2.3.4 Empathy Mapping]  
     - [2.3.5 As-is Scenario Mapping]  
   - [2.4 Ubiquitous Language]  



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

### Competitive Analysis Landscape

| **Nombre de los Startups**               |                                       | **CleanWind** | **Comimtel** | **CARYMA** | **Ulloa** |
|--------------------------|----------------------------------------------------|---------------|--------------|------------|-----------|
| **Perfil**               | Overview                                           | Plataforma de gestión de residuos con estadísticas, recomendaciones y conexión a recicladoras. | Empresa especializada en tratamiento de RAEE. | Gestión integral de residuos sólidos peligrosos y no peligrosos. | Transporte y gestión de residuos peligrosos y no peligrosos a nivel industrial. |
|                          | Ventaja competitiva / ¿Qué valor ofrece a los clientes?           | Interfaz digital, datos en tiempo real, alertas y trazabilidad. | Planta de valorización propia, experiencia en RAEE. | Registro EO-RS, cumplimiento legal y enfoque ambiental. | Certificaciones ISO y amplia cobertura logística. |
| **Perfil de Marketing**  | Mercado objetivo                                   | Empresas medianas, grandes y ciudadanos conscientes. | Empresas tecnológicas y entidades públicas. | Empresas industriales y comercios que generan residuos. | Minería, construcción, energía, agroindustria. |
|                          | Estrategias de marketing                           | Modelo freemium, redes sociales, alianzas con recicladoras. | Reputación en el sector y asesorías especializadas. | Servicios personalizados y compromiso ambiental. | Relación directa con empresas industriales y servicios a gran escala. |
| **Perfil del Producto**  | Productos & Servicios                              | Plataforma web con monitoreo, mapas, reportes y recomendaciones. | Valorización y disposición de RAEE, reportes físicos. | Recolección, transporte y disposición de residuos, asesoría técnica. | Transporte, gestión y destrucción notarial. |
|                          | Precios & Costos                                   | Freemium + Premium ($15/mes). | Cotización según tipo y volumen. | Cotización por tipo de residuo y servicio. | Tarifa según residuo y logística. |
|                          | Canales de distribución (Web y/o Móvil)           | Web y móvil (en desarrollo). | Presencial y atención directa. | Presencial y atención por contacto. | Presencial con contacto por web corporativa. |
| **Análisis SWOT**        | Fortalezas                                         | Digital, accesible, conexión con recicladoras, enfoque educativo. | Experiencia técnica y planta propia. | Certificación MINAM y enfoque ambiental. | Cobertura nacional y flota especializada. |
|                          | Debilidades                                        | Proyecto en etapa inicial. | Limitado a RAEE. | Sin plataforma tecnológica. | Operación tradicional sin automatización digital. |
|                          | Oportunidades                                      | Alianzas con municipalidades, integración con apps educativas. | Expansión en RAEE domiciliarios. | Adopción de tecnologías de monitoreo. | Digitalización y modernización de procesos. |


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

# Capítulo IV
## 4.1 Style Guidelines
CleanWind es una plataforma enfocada en la gestión sostenible de residuos. Para ofrecer una experiencia amigable y clara, se ha optado por un diseño visual limpio y funcional. Predominan colores fríos como el verde claro, verde oscuro, blanco y negro, transmitiendo compromiso ecológico y profesionalismo. El diseño prioriza la simplicidad, el orden y la accesibilidad, facilitando que cualquier usuario pueda interactuar con la plataforma de forma intuitiva y efectiva.

## 4.1.1. General Style Guidelines
CleanWiew emplea un diseño minimalista y moderno, centrado en la funcionalidad, la accesibilidad y la estética limpia. La interfaz combina los siguientes colores:

- Verde menta – #D9F2EF (Fondo principal)
Utilizado como color de fondo general. Refleja sostenibilidad, frescura y modernidad, alineándose con el enfoque ecológico del proyecto.

- Blanco – #FFFFFF (Subfondo)
Aplicado en tarjetas, bloques de contenido y secciones internas. Mejora la lectura, aporta limpieza visual y permite un buen contraste con el texto.

- Negro – #000000 (Texto)
Color principal del texto en toda la interfaz. Garantiza legibilidad óptima sobre cualquier fondo, manteniendo un estilo profesional y claro.

- Verde azulado oscuro – #00A295 (Cuadros informativos destacados)
Empleado en cajas de datos, estadísticas y elementos visuales destacados. Atrae la atención del usuario hacia información clave.

- Verde menta brillante – #89E0B0 (Botones de interacción y alertas)
Usado en botones y elementos interactivos. Agrega dinamismo visual y guía la acción del usuario de manera intuitiva.

**Paleta de colores para CleanWind**
![image](https://github.com/user-attachments/assets/5e1d61e5-d554-4bd6-8ccd-79a5c5ca4f9b)

**Tipografía**
La tipografía utilizada para CleanWind es Poppins, seleccionada por su claridad y modernidad, asegurando que sea legible y adecuada para su uso tanto en personas adultas jóvenes, como en personas ancianas. La base de la tipografía es de 14.5px con un interlineado de 1.1. Además, se utiliza una escala con un ratio de 1.125 para ajustar los tamaños de la tipografía según las necesidades de la web, abarcando desde títulos, subtítulos hasta el cuerpo del texto.

**Escala:**
Base: 14.5px
Ratio: 1.125
Tipografía: Poppins
Interlineado: 1.1

**Weights:**
- Delgado
- Extra Fino
- Fino
- Normal
- Mediano
- Semi negrita
- **Negrita**
- **Extra negrita**
- **Grueso**

**Nomenclatura:**
Nombre / Tamaño / Peso
Título 0 / 20px / Medium

**Ejemplo:**
![image](https://github.com/user-attachments/assets/566b559c-bde0-4ca9-b61a-f69eb6b931de)

**Branding e Icono:**
El logo de CleanWind representa su compromiso con el medio ambiente mediante un diseño simple y simbólico. En el centro, se muestra un tacho de basura verde con un símbolo de reciclaje blanco, reflejando la gestión responsable de residuos. A los costados, hojas verdes refuerzan la conexión ecológica. Todo está enmarcado por círculos verdes, y sobre ellos se encuentra el nombre CleanWind en color verde. Este diseño transmite sostenibilidad, orden y conciencia ambiental de forma clara y visualmente amigable.

![image](https://github.com/user-attachments/assets/612b96ac-0ef3-4768-84c1-b8dcb33ee716)

## 4.1.2. Web Style Guidelines
La versión web de CleanWind está pensada para usuarios empresariales, con diseño responsivo, paneles modulares y visualizaciones claras de datos.

- Diseño responsivo: la plataforma se adapta perfectamente a dispositivos móviles, tabletas y escritorio.
- Hover Effects: los botones cambian de verde claro a verde oscuro al pasar el cursor.
- Navbar superior: accesos a Inicio, Mi impacto, Reportes, Consejos y Soporte.
- Animaciones suaves: transiciones sutiles al cambiar entre secciones o desplegar menús.

## 4.2. Information Architecture.  
La arquitectura de la información de CleanView busca ofrecer una experiencia fluida e intuitiva para dos tipos de usuarios: personas naturales y empresas. La organización y etiquetado de contenidos se diseñó para guiar al usuario de forma eficiente desde el registro hasta el aprovechamiento de todas las funcionalidades de la plataforma. Esto se logra a través de una combinación de jerarquías visuales claras, secuencias lógicas y categorizaciones adaptadas a cada audiencia.

## 4.2.1. Organization Systems.  
El sistema de organización en CleanView ha sido diseñado para brindar una experiencia intuitiva y eficiente, diferenciando las necesidades de personas naturales y empresas. Aunque ambas audiencias acceden a secciones similares, el enfoque y la profundidad de acceso varía según el tipo de usuario.

**Persona Natural**  
Los usuarios personas acceden a una interfaz centrada en su historial de recolección y acciones sostenibles. Se utiliza una estructura jerárquica para resaltar primero la información más útil, como puntos acumulados o tips destacados del mes.

+ Inicio: Se organiza de manera matricial, ya que se muestran varios módulos visuales al mismo nivel: un tip destacado, el resumen de progreso, puntos de acopio cercanos y el estado actual de sus recompensas. Cada bloque tiene su función clara, y se disponen de manera visual en cuadrícula para facilitar la interacción rápida.

+ Recompensas: En la sección de Recompensas para persona natural se aplica un sistema de organización matricial, ya que el usuario puede visualizar en paralelo tanto las recompensas disponibles como sus puntos acumulados. Esta estructura permite comparar de forma inmediata lo que el usuario tiene con lo que puede obtener, favoreciendo la motivación y toma de decisiones. Las recompensas se presentan en tarjetas visuales con imágenes, descripciones y requisitos, mientras que los puntos acumulados se muestran como un resumen destacado en el mismo nivel jerárquico.

+ Acciones sostenibles: Visualmente se maneja con jerarquía, mostrando primero los tips destacados del mes. Ademas de organización por categoría de residuo (orgánico, reciclable, electrónico, etc.). Se presenta una lista de tips donde el usuario puede filtrar por tipo de residuo o usar la barra de búsqueda.

+ Puntos de acopio: Organización visual jerárquica, mostrando primero los puntos más cercanos al usuario, con posibilidad de filtrar por tipo de residuo, distrito y ver detalles. Se prioriza la proximidad como factor clave.

+ Reportes: Organización cronológica, mostrando el historial de recolección filtrado por mes y año. Se prioriza una visualización clara, empezando por el resumen mensual.

**Empresas**  
El segmento de empresas comparte varias secciones y estructuras organizativas con el de personas naturales, como Inicio, Acciones Sostenibles, Puntos de Acopio y Reportes, aplicando sistemas similares como la organización jerárquica en las recomendaciones, la categorización por tópicos y filtros personalizados. Sin embargo, el módulo para empresas incluye funcionalidades adicionales orientadas a la gestión operativa. Por ejemplo cuenta con la gestión de recolección automatizada, donde las empresas pueden contratar recolectoras que se activan cuando los sensores detectan que se alcanzó un umbral de residuos, optimizando así los tiempos de recolección. Ademas de reportes avanzados, que generan informes detallados, exportables en PDF o Excel, útiles para auditorías, certificaciones y análisis de eficiencia.  
Se cuenta con la nueva sección de: 
+ Panel de Control: Vista general del estado actual de generación de residuos por zona, sensores activos, niveles de llenado y alertas. Esto tiene una organizacion de tipo matricial.

## 4.2.2. Labeling Systems.  
**Landing Page:** 
|Etiqueta| Descripción|
|--------|------------|
|Home| Presenta la propuesta de valor con una imagen representativa|
|Join as a Company|Registro rápido enfocado a organizaciones y compañías|
|Join as a User|Registro rápido enfocado a usuarios individuales|
|Solutions|Muestra los beneficios y funcionalidades clave de CleanView de acuerdo a cada segmento objetivo|
|¿How Work?|Explica paso a paso el proceso de uso, registro y operación  de acuerdo a cada segmento objetivo|
|About Us| Breve de la misión y visión de CleanView|
|Contact| Breve de la misión y visión de CleanView|
|About Us| Formulario y medios de contacto directo con el equipo|
|Log In| Botón de acceso a la plataforma para usuarios registrados|

**App Web:** 

|Etiqueta| Descripción|
|--------|------------|
|Inicio/ Dashboard| Muestra un resumen de actividad y alertas importantes|
|Puntos de Acopio| Mapa interactivo con puntos de acopio cercanos, con sus datos. En empresas puedes observar los servicios contratados|
|Perfil| Edición de datos personales, preferencias y ubicación|
|Cerrar Sesión| Salida segura de la plataforma|  
|Recompensas| Acceso al sistema de puntos e incentivos ecológicos|
|Acciones Sostenibless|Visualización de tips, sugerencias y actividades ecológicas realizadas por el usuario|
|Panel de Control| Seguimiento de residuos generados, alertas y zonas|
|Reportes|	Historial de recolección para persona natural o reportes detallados para empresas.|
|Añadir Zona|Permite agregar nuevas zonas de recolección de residuos.|
|Añadir Sensor|Permite añadir sensores a las zonas para monitoreo de residuos en tiempo real.|
|Contratar|Contratar servicios de recolección de residuos según el tipo.|

## 4.2.3. SEO Tags and Meta Tags  

Para mejorar la visibilidad de CleanWide en los motores de búsqueda y atraer a los usuarios adecuados, se ha optado por definir los siguientes datos:

**Landing Page**  
+ Title:
  CleanWide - Plataforma de Gestión de Residuos y Limpieza para Espacios Compartidos
+ Meta Description: CleanWide es una plataforma innovadora que conecta personas y empresas para una gestión eficiente de la limpieza y el reciclaje de espacios compartidos. Facilita la recolección de residuos y el cumplimiento de prácticas sostenibles.
+ Keywords: gestión de residuos, limpieza de espacios compartidos, reciclaje, sostenibilidad, gestión de residuos urbanos, plataforma de limpieza, recolección de residuos, acciones sostenibles.
+ Author: CleanWide Team

**Dashboard / Inicio**
+ Title: Dashboard de CleanWide - Resumen de Actividad y Progreso Ambiental
+ Meta Description: Accede a tu resumen de actividades y progreso en la recolección de residuos.
+ Keywords: dashboard, gestión de residuos, progreso ambiental, recolección de residuos, impacto ecológico.
+ Author: CleanWide Team

**Puntos de Acopio**
+ Title: Puntos de Acopio de CleanWide - Encuentra Ubicaciones Cercanas para el Reciclaje
+ Meta Description: Consulta el mapa interactivo de puntos de acopio en tu área. Encuentra lugares cercanos para depositar tus residuos reciclables y contribuir al cuidado del medio ambiente.
+ Keywords: puntos de acopio, reciclaje, mapa de puntos de acopio, residuos reciclables, gestión de residuos.
+ Author: CleanWide Team

**Acciones Sostenibles**
+ Title: Acciones Sostenibles en CleanWide - Iniciativas Ecológicas para Reducir Residuos
+ Meta Description: Descubre consejos prácticos y acciones sostenibles para reducir tu huella ecológica. Aprende a gestionar tus residuos de manera eficiente y contribuye a la sostenibilidad.
+ Keywords: acciones sostenibles, reducción de residuos, reciclaje, prácticas ecológicas, consejos sostenibles.
+ Author: CleanWide Team

**Recompensas**
+ Title: Recompensas CleanWide - Acumula Puntos por Acciones Sostenibles
+ Meta Description: Acumula puntos por tus acciones sostenibles y accede a recompensas ecológicas. Incentivos para fomentar el reciclaje y la reducción de residuos en tu comunidad.
+ Keywords: recompensas, puntos sostenibles, incentivos ecológicos, reciclaje, recompensas por acciones sostenibles.
+ Author: CleanWide Team

**Reportes**
+ Title: Reportes de Residuos CleanWide - Generación de Informes Detallados
+ Meta Description: Genera reportes detallados sobre la recolección de residuos, filtrados por mes y año. Descarga informes de tu progreso en la gestión de residuos y sostenibilidad.
+ Keywords: reportes, informes de residuos, generación de reportes, progreso de recolección, gestión de residuos, informes ambientales.
+ Author: CleanWide Team

**Panel de Control** 
+ Title: Panel de Control CleanWide - Gestión Eficiente de Residuos en Empresas
+ Meta Description: Accede al panel de control de CleanWide para gestionar el rendimiento ambiental de tu empresa. Monitorea los puntos de acopio y el uso de sensores en tiempo real.
+ Keywords: panel de control, gestión empresarial de residuos, sensores de residuos, gestión de residuos en empresas, seguimiento de residuos.
+ Author: CleanWide Team


## 4.2.4. Searching Systems.  

El sistema de búsqueda diseñado para CleanWide tiene como objetivo facilitar a los usuarios la localización eficiente de información clave relacionada con tareas de limpieza, mantenimiento, reportes y participación comunitaria. Este sistema está diseñado para minimizar la pérdida de tiempo y mejorar la experiencia general del usuario, brindando filtros específicos según el tipo de usuario (persona natural o empresa) y el tipo de actividad que desea consultar o gestionar.

|Nombre del Filtro| Descripción|
|--------|------------|
|Buscar Acciones Sostenibles|Permite ingresar palabras clave para encontrar acciones sostenibles registradas. Los resultados se muestran con tarjetas que incluyen tips sostenibles y un boton para guardarlos. Ademas que se puede filtrar segun el tipo de residuo, como reciclaje, órganico, plástico.|
|Filtrar Reportes por Mes y Año |Herramienta que permite al usuario visualizar sus reportes ambientales o de actividades filtrando por periodo específico.|
|Buscar Puntos de Acopio |Campo de búsqueda que permite encontrar puntos de acopio por nombre, zona o tipo de residuo que reciben (plástico, vidrio, electrónicos, etc.). Incluye filtros por distrito y tipo de residuo.|

## 4.2.5. Navigation Systems.  
El sistema de navegación de CleanView ha sido diseñado para facilitar el recorrido del usuario tanto en la Landing Page como dentro de la aplicación web, garantizando una experiencia fluida, eficiente y centrada en el cumplimiento de los objetivos del usuario. Se aplican principios de diseño centrado en el usuario y técnicas modernas de navegación que aseguran accesibilidad, claridad y mínimo esfuerzo cognitivo.

**Landing Page - CleanWide**

+ Estructura:
  Presentación general del propósito de CleanWide: conectar a usuarios y empresas en torno a la adecuada gestion de residuos.
+ Incluye acceso rápido a:
   + Registro / Inicio de sesión (con roles de Usuario o Empresa).
   + Información destacada sobre los beneficios del sistema.
   + Seccion de contacto
+ Acción del Usuario: Cualquier visitante puede navegar por la landing page. Puede registrarse como empresa o persona natural.

**Sección: Inicio**
+ Estructura:
  + Muestra un resumen personalizado con una frase de bienvenida.
  + Muestra un resumen de sus actividades.
  + Organización matricial con tarjetas visuales.
    
+ Acción del Usuario:
   + Persona Natural: Puede ver su progreso, cuantos puntos le faltan para llegar a ciertas recompensas y puntos cercanos a su hogar.
   + Empresa: Visualiza alertas del sistema y estadísticas rápidas.

**Sección de Recompensas**

+ Estructura:
   + Sección con visualización paralela de puntos acumulados y catálogo de recompensas disponibles.
   + Diseño en tarjetas con filtros por categoría.

+ Acción del Usuario:
   + Persona Natural: Puede canjear recompensas, revisar puntos y consultar requisitos.
   + Empresa: No tiene acceso a esta sección (no aplica en su flujo).

**Sección de Acciones Sostenibles**

+ Estructura:
   + Lista filtrable de tips y sugerencias.
   + Incluye barra de búsqueda.
   + Tips destacados del mes

+ Acción del Usuario:
   + Persona Natural: Puede visualizar, buscar segun sus intereses y guardar las mejores recomendaciones.
   + Empresa:  Puede visualizar, buscar segun sus intereses y guardar las mejores recomendaciones. Esto esta mas enfocado a tips de gestion de residuos para empresas
  
**Sección de Puntos de Acopio**

+ Estructura:
   + Mapa interactivo
   + filtros por distrito y tipo de residuo.
   + Incluye detalles de cada punto y servicios disponibles.

+ Acción del Usuario:
    + Persona Natural: Puede ubicar puntos cercanos y filtrarlos por necesidades.
    + Empresa: Puede visualizar puntos contratados y monitorear el estado de servicio. Ademas de poder visualizar otros puntos de acopio para poder contratarlos.
      
**Sección de Reportes**
+ Estructura:
   + Historial de recolección con filtros por mes y año.
   + Breve resumen de lo logrado

+ Acción del Usuario:
    + Persona Natural: Consulta reportes simples de sus actividades. Ademas de ver un resumen de kilogramos de residuos 
    + Empresa: Genera reportes detallados y exportables, útiles para auditorías o certificaciones.
  
**Sección de Panel de Control**
+ Estructura:
   + Vista general de sensores
   + Zonas de recolección y alertas
   + Graficas de nivel de residuos

+ Acción del Usuario:
    + Persona Natural: No tiene acceso a esta sección.
    + Empresa: Supervisa en tiempo real el estado de sus zonas y sensores. Puede tomar decisiones y activar servicios desde aquí.
  
