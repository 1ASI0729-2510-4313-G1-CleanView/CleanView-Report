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
|Valentino Sandoval Paiva     |U20211A962    |

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

1. [Capítulo I: Introducción](./Repo/Capitulo%201.md)
   - [1.1 Startup Profile](./Repo/Capitulo%201.md)
     - [1.1.1 Descripción de la Startup](./Repo/Capitulo%201.md)
     - [1.1.2 Perfiles de Integrantes del equipo](./Repo/Capitulo%201.md)
   - [1.2 Solution Profile](./Repo/Capitulo%201.md)
     - [1.2.1 Antecedentes y problemática](./Repo/Capitulo%201.md)
     - [1.2.2 Lean UX Process](./Repo/Capitulo%201.md)
       - [1.2.2.1 Lean UX Problem Statements](./Repo/Capitulo%201.md)
       - [1.2.2.2 Lean UX Assumptions](./Repo/Capitulo%201.md)
       - [1.2.2.3 Lean UX Hypothesis Statements](./Repo/Capitulo%201.md)
       - [1.2.2.4 Lean UX Canvas](./Repo/Capitulo%201.md)
   - [1.3 Segmentos Objetivo](./Repo/Capitulo%201.md)



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
| US-001           | Monitoreo de residuos en tiempo real | **Como** empresario <br/> **Quiero** visualizar la cantidad y tipo de residuos generados en tiempo real <br/> **Para** tomar decisiones rápidas. | *Escenario 1:* <br/> **"Visualización de residuos en tiempo real"** <br/> **Dado que** soy empresario y estoy usando la plataforma clean Wind. <br/> **Cuando** accedo al panel de monitoreo y el sistema detecta un incremento inusual en la generación de residuos. <br/> **Entonces** se genera una alerta automática sobre el problema. <br/><br/> *Escenario 2:* <br/> **"Identificación de los residuos"** <br/> **Dado que** estoy monitoreando la aparición de residuos. <br/> **Cuando** accedo al panel de monitoreo y el sistema detecta un incremento inusual en la generación de residuos. <br/> **Entonces** el sistema me muestra los detalles del residuo que se ha identificado y en que parte se encuentra. | - |
| US-002           | Reporte detallado sobre residuos | **Como** empresario <br/> **Quiero** ver reportes detallados de producción y desperdicio <br/>  **Para** tomar decisiones que reduzcan los desperdicios y mejoren la eficiencia. | *Escenario 1:* <br/> **"Visualización de los detalles de residuo por alertas"** <br/> **Dado que** estoy monitoreando la aparición de residuos. <br/> **Cuando** Seleccione la opción ver detalles de alerta. <br/> **Entonces** me muestra los detalles del residuo que se ha identificado. <br/><br/> *Escenario 2:* <br/> **"Visualización diaria de desperdicio"** <br/> **Dado que** estoy monitoreando la aparición de residuos. <br/> **Cuando** Seleccione la ventana de Panel de Control<br/> **Entonces** me muestra los detalles de residuos encontrados por medio de un gráfico. <br/><br/> *Escenario 3:* <br/> **"Visualización detallada de los residuos en un gráfico"** <br/> **Dado que** estoy monitoreando la aparición de residuos. <br/> **Cuando** Seleccione una barra de la grafica<br/> **Entonces** me muestra los detalles de residuos encontrados en ese momento. | - |
| US-003           | Puntos de reciclaje cercanos | **Como** Ciudadano <br/> **Quiero** ver puntos de reciclaje cerca de mi casa <br/> **Para** poder reciclar fácilmente y contribuir al cuidado del medio ambiente | *Escenario 1:* <br/> **"Visualizar puntos cercanos automáticamente"** <br/> **Dado que** ingreso a la aplicación con permisos de ubicación activados <br/> **Cuando** abro el mapa. <br/> **Entonces** me muestra los puntos de reciclaje más cercanos a mi ubicación actual <br/><br/> *Escenario 2:* <br/> **"Busca por dirección o Distrito"** <br/> **Dado que** quiero reciclar un tipo específico de residuo. <br/> **Cuando** escribo una dirección o nombre de Distrito. <br/> **Entonces** el sistema me muestra los puntos de reciclaje cercanos a esa ubicación <br/><br/> *Escenario 3:* <br/> **"Ver detalles de un punto"** <br/> **Dado que** veo un punto de reciclaje en el mapa. <br/> **Cuando** haga clic sobre él. <br/> **Entonces** se muestra la dirección, horario y tipo de materiales aceptados| - |
| US-004           | Consejos para manejo de residuos | **Como** Ciudadano <br/> **Quiero** recibir consejos del cuidado ambiental y reciclaje <br/> **Para** reducir residuos en casa.  | *Escenario 1:* <br/> **"Acceder a consejos desde la app"** <br/> **Dado que** quiero informarme. <br/> **Cuando** entro a la sección de “Tips Verdes”. <br/> **Entonces** veo una lista de recomendaciones actualizadas y categorizadas. <br/><br/> *Escenario 2:* <br/> **"Filtrar por tipo de consejo "** <br/> **Dado que** busco algo específico <br/> **Cuando** entro a la sección de “Tips Verdes” y uso la barra de búsqueda. <br/> **Entonces** me muestra consejos relacionados a esa categoría <br/><br/> *Escenario 3:* <br/> **"Guardar consejos favoritos"** <br/> **Dado que** me gustó un consejo <br/> **Cuando** lo marco como favorito. <br/> **Entonces** lo puedo consultar luego de una forma más rápida. | - |
| US-005           | Gamificación ecológica | **Como** Ciudadano <br/> **Quiero** recibir puntos por buenas prácticas <br/> **Para** motivarme más a reciclar  | *Escenario 1:* <br/> **"Acumulación automatica de puntos"** <br/> **Dado que** realizo una acción ecológica. <br/> **Cuando** el sistema la valida. <br/> **Entonces** se me asignan puntos automáticamente en mi perfil y en la sección recompensas. <br/><br/> *Escenario 2:* <br/> **"Ver historial de puntos"** <br/> **Dado que** quiero saber cómo he acumulado mis puntos. <br/> **Cuando** Ingres a la sección Recompensas“”. <br/> **Entonces** veo el desglose de mis acciones y los puntos ganados. <br/><br/> *Escenario 3:* <br/> **"Canjear puntos por beneficios”** <br/> **Dado que** acumulo puntos suficientes. <br/> **Cuando** Ingres a la sección Recompensas“”. <br/> **Entonces** canjear los puntos que he estado ganando. | - |
| US-006           | Alertas por umbrales críticos | **Como** Empresario <br/> **Quiero** alertas cuando los residuos superen un umbral <br/> **Para** poder tomar decisiones rápidas que garanticen el cumplimento ambiental | *Escenario 1:* <br/> **"Notificación de desperdicio crítico"** <br/> **Dado que** quiero actuar rápidamente ante problemas. <br/> **Cuando** el desperdicio supera un umbral definido. <br/> **Entonces** el sistema me envía una notificación o alerta al correo <br/><br/> *Escenario 2:* <br/> **"Configuración de umbrales"** <br/> **Dado que** quiero poner un límite distinto además de lo legal. <br/> **Cuando** configure un nuevo umbral <br/> **Entonces** el sistema deberá usar este nuevo umbral para activar alertas  | - |
| US-007           | Comparación entre periodos | **Como** Empresario <br/> **Quiero** comparar residuos entre meses <br/> **Para** identificar patrones de generación y evaluar la efectividad de estrategias de reducción | *Escenario 1:* <br/> **"Comparación gráfica mensual"** <br/> **Dado que** quiero ver los residuos generados mes a mes. <br/> **Cuando** accedo al módulo panel de control. <br/> **Entonces** debe mostrar una gráfica comparativa de residuos por tipo <br/><br/> *Escenario 2:* <br/> **"Comparación porcentual"** <br/> **Dado que** existe un resumen de los residuos por mes. <br/> **Cuando** seleccione el Periodo que quiero ver los porcentajes. <br/> **Entonces** el sistema deberá mostrar el porcentaje de incremento o disminución por categoría de residuo <br/><br/> *Escenario 2:* <br/> **"Exportación de comparación"** <br/> **Dado que** los datos pueden ser útiles para reportes externos. <br/> **Cuando** finalice una comparación. <br/> **Entonces** el sistema deberá permitir exportar los resultados. | - |
| US-008           | Ranking interno de sostenibilidad | **Como** Empresario <br/> **Quiero** ver áreas que generan menos recursos <br/> **Para** replicar estrategias eficientes en otras áreas | *Escenario 1:* <br/> **"Ranking de áreas por generación de residuos"** <br/> **Dado que** el sistema recopila datos de residuos por área. <br/> **Cuando** accedo al informe mensual. <br/> **Entonces** se debe mostrar un ranking de áreas.<br/><br/> *Escenario 2:* <br/> **"Visualización de gráfica por área de operación"** <br/> **Dado que** los datos están registrados por área de operación. <br/> **Cuando** selecciono un periodo de tiempo. <br/> **Entonces** el sistema debe mostrar un gráfico comparativo por áreas con su respectiva cantidad de residuos <br/><br/> *Escenario 3:* <br/> **"Filtros por tipo de residuo"** <br/> **Dado que** los residuos pueden calificarse. <br/> **Cuando** aplique un filtro por residuo. <br/> **Entonces** la visualización debe actualizarse mostrando las áreas donde este ha sido identificado | - |
| US-009           | Exportación de reportes | **Como** Empresario <br/> **Quiero** exportar reportes en PDF o Excel <br/> **Para** analizarlos fuera del sistema y compartirlos con mi equipo | *Escenario 1:* <br/> **" Exportación de reporte"** <br/> **Dado que** visualizo un reporte mensual de residuos. <br/> **Cuando** seleccione la opción “Exportar”. <br/> **Entonces** el sistema debe mostrar opciones del formato en el que quiero exportar los datos. <br/><br/> *Escenario 2:* <br/> **" Exportación de reporte en formato PDF "** <br/> **Dado que** visualizo el reporte mensual de residuos. <br/> **Cuando** selecciono la opción “PDF”. <br/> **Entonces** el sistema debe generar un archivo pdf con el contenido del reporte y los gráficos. <br/><br/> *Escenario 3:* <br/> **" Exportación de reporte en formato EXCEL "** <br/> **Dado que** trabajo con los datos en una hoja de cálculo. <br/> **Cuando** selecciono la opción “EXCEL”. <br/> **Entonces** el sistema debe generar un archivo .xlsx con los datos tabulados incluyendo fechas y cantidades. | - |
| US-010           | Integración con sensores IoT | **Como** Empresario <br/> **Quiero** usar sensores inteligentes <br/> **Para** monitoreo automático e residuos | *Escenario 1:* <br/> **” Visualización en tiempo real "** <br/> **Dado que** los sensores transmiten datos constantemente. <br/> **Cuando** accedo al panel de monitoreo. <br/> **Entonces** debe visualizar los niveles actuales de residuos por tipo, ubicación y hora. <br/><br/> *Escenario 2:* <br/> **" Integración de reportes automáticos"** <br/> **Dado que** los datos provienen directamente de los sensores. <br/> **Cuando** se genere un reporte mensual. <br/> **Entonces** el sistema debe utilizar los datos recolectados por los sensores. <br/><br/> *Escenario 3:* <br/> **" Registro de un nuevo sensor inteligente"** <br/> **Dado que** he adquirido un nuevo sensor inteligente para monitorear residuos. <br/> **Cuando** accedo a la sección Panel de Control <br/>**Y** selecciono en añadir sensores en el sistema.<br/> **Y** Completo los campos requeridos para su instalación.<br/> **Entonces** el sistema debe guardar el sensor en base de datos. <br/> **Y** mostrar un mensaje de confirmación.<br/><br/> *Escenario 4:* <br/> **" Eliminación de sensor inteligente"** <br/> **Dado que** necesito remover un sensor de una zona ya configurada. <br/> **Cuando** accedo a la sección “Mis Zonas” desde el Panel de Control. <br/> **Y** selecciono el botón de “borrar sección, <br/> **Y** presiono el icono de tacho al lado del sensor que deseo eliminar. <br/> **Entonces** el sistema me muestra un mensaje de confirmación para eliminar.<br/> **Y** cuando confirmo, el sensor es eliminado de la lista.| - |
| US-011           | Notificación por tipo de residuo | **Como** Empresario <br/> **Quiero** recibir alertas si un tipo específico de residuo aumenta <br/> **Para** poder tomar decisiones rápidas que mitiguen impactos negativos | *Escenario 1:* <br/> **” Cambio de canal de notificaciones "** <br/> **Dado que** he configurado inicialmente el canal de alerta por correo. <br/> **Cuando** modifica la configuración para recibir alertas por SMS. <br/> **Entonces** las próximas alertas deben enviarse exclusivamente pr SMS. <br/><br/> *Escenario 2:* <br/> **" Generación de alerta por superación de umbral "** <br/> **Dado que** el umbral para “Plástico” está configurado en 50 kg. <br/> **Y** el sistema detecta un total de 60 kg está semana <br/> **Cuando** se realiza la evaluación. <br/> **Entonces** el sistema debe generar una alerta y enviarla por correo electrónico al empresario. | - |
|US-012            |Servicio de recojo automático| **Como**empresario <br/> **Quiero** que se solicite un servicio de recojo automáticamente cuando los sensores detectan que el 80% está lleno <br/> **Para** evitar acumulaciones y mantener la limpieza.|*Escenario 1:*  <br/> **"Generación automática de orden de recojo "** <br/> **Dado que**que mis sensores están activos y conectados a CleanView . <br/> **Cuando** uno o más sensores superan el 80% de llenado. <br/> **Entonces** se debe generar automáticamente una orden de recojo al proveedor asignado. <br/><br/>*Escenario 2:* <br/> **"Información de fecha estimada de recojo"** <br/> **Dado que**  se genera la orden . <br/> **Cuando** el proveedor acepta el servicio. <br/> **Entonces** debo recibir la información con la fecha estimada de recojo .<br/><br/>*Escenario 3:* <br/> **"Reinicio de sensores tras completar el servicio de recojo."** <br/> **Dado que** el servicio fue completado. <br/> **Cuando** se cierre la orden . <br/>**Entonces** los sensores deben volver a cero.| - |
| US-013           | Plan de reducción de residuos | **Como** Empresario <br/> **Quiero** un plan personalizado <br/> **Para** reducir la generación de residuos | *Escenario 1:* <br/> **" Evaluación del progreso "** <br/> **Dado que** el plan tiene metas temporales ya sea mensuales o trimestrales. <br/> **Cuando** se alcance la una fecha de revisión. <br/> **Entonces** el sistema debe mostrar el progreso alcanzado y sugerir ajustes si no cumplen los objetivos. <br/><br/> *Escenario 2:* <br/> **" Selección de objetivos empresariales "** <br/> **Dado que** el sistema tiene acceso al historial de generación de residuos. <br/> **Cuando** solicito un plan personalizado. <br/> **Entonces** el sistema debe analizar los datos y generar un plan con recomendaciones específicas por área y tipo de residuo. | - |
| US-014           | chat de soporte ambiental | **Como** Usuario <br/> **Quiero** consultar dudas con un asistente virtual <br/> **Para** obtener respuestas rápidas y precisas sin depender del soporte humano | *Escenario 1:* <br/> **" Comunicación con el asistente virtual en la app "** <br/> **Dado que** Quiero información rápida sobre residuos mientras usa la app. <br/> **Cuando** dé click en el globo de texto en la parte inferior de la pantalla. <br/> **Entonces** el asistente virtual lo saluda con su nombre y pregunta sobre lo que quiera saber. <br/><br/> *Escenario 2:* <br/> **" Comunicación con el asistente virtual en la landing page "** <br/> **Dado que** quiero información rápida sobre la app. <br/> **Cuando** dé click en el globo de texto en la parte inferior de la pantalla.. <br/> **Entonces** el asistente virtual lo saluda con el mensaje e “Hola, ¿Cómo puedo ayudarte?”. <br/><br/> *Escenario 3:* <br/> **" Preguntas frecuentes sobre residuos "** <br/> **Dado que** El sistema incluye información técnica sobre residuos. <br/> **Cuando** consulte con algo como “¿Qué residuo es peligroso?”. <br/> **Entonces** el asistente debe brindar una definición comprensible y ejemplos. | - |
| US-015           | Verificación de acciones sostenibles | **Como** Empresario<br/> **Quiero** validar si las acciones implementadas reducen residuos <br/> **Para** medir su efectividad y ajustar estrategias en función de resultados | *Escenario 1:* <br/> **" Comparación antes y después de implementar acciones "** <br/> **Dado que** se ha registrado una acción de reducción de residuos. <br/> **Cuando** se analice los datos del mes anterior y posterior a la implementación. <br/> **Entonces** el sistema debe mostrar si hubo una disminución significativa en la cantidad de residuos generados. <br/><br/> *Escenario 2:* <br/> **" Visualzación de progreso hacia objetivos "** <br/> **Dado que** tengo metas definidas de reducción de residuos. <br/> **Cuando** revise los indicadores en el panel de control. <br/> **Entonces** el sistema debe mostrar el avance porcentual y si las acciones actuales están contribuyendo al cumplimento. | - |
| US-016           | Integración con APIs externas | **Como** Desarrollador<br/> **Quiero** conectar CleanWind a otras plataformas <br/> **Para** integrar datos y funcionalidades con sistemas externos | *Escenario 1:* <br/> **" API REST disponible y documentada "** <br/> **Dado que** CleanWind debe comunicar. <br/> **Cuando**  accedo al portal de desarrolladores. <br/> **Entonces** debo encontrar documentación clara solo endpoints, autenticación y ejemplos de uso. <br/><br/> *Escenario 2:* <br/> **" Autenticación segura (API Keys) "** <br/> **Dado que**  una aplicación externa quiere consumir datos de CleanWind. <br/> **Cuando** se registre una aplicación en el sistema. <br/> **Entonces** debe generarse una API key o token de acceso seguro. <br/><br/> *Escenario 3:* <br/> **" Exportación automatizada de datos "** <br/> **Dado que** otra plataforma requiere datos periódicos. <br/> **Cuando**  se configure una integración. <br/> **Entonces** CleanWind debe exportar los datos automáticamente en el formato requerido (JSON, CSV, XML). | - |
| US-017           | Recomendaciones inteligentes | **Como** Usuario<br/> **Quiero** recibir recomendaciones personalizadas según mis datos <br/> **Para** tomar decisiones más informadas que me ayuden a reducir residuos | *Escenario 1:* <br/> **"  Actualización dinámica de sugerencias "** <br/> **Dado que** mis datos cambian con el tiempo. <br/> **Cuando**  se registre nueva información. <br/> **Entonces** el sistema debe actualizar las recomendaciones de manera automática o notificar al usuario.  <br/><br/> *Escenario 2:* <br/> **" Análisis de comportamiento previo "** <br/> **Dado que**  el sistema registra el historial de residuos del usuario. <br/> **Cuando** accedo al panel de recomendaciones. <br/> **Entonces** el sistema debe mostrar sugerencias basadas en sus patrones de generación de residuos. | - |
| US-018           | Sistema de insignias por logros sostenibles | **Como** Usuario<br/> **Quiero**  recibir insignias por hitos alcanzados <br/> **Para** motivarme, reconocer mis logros y visualizar mi progreso | *Escenario 1:* <br/> **"  Insignia por reducción de residuos "** <br/> **Dado que** he logrado reducir un cierto porcentaje de residuos en un período. <br/> **Cuando**  se cumpla el hito. <br/> **Entonces** el sistema debe otorgarle automáticamente una insignia y mostrar una notificación. <br/><br/> *Escenario 2:* <br/> **" Visualización de insignias obtenidas "** <br/> **Dado que** he ganado varias insignias. <br/> **Cuando** accedo a mi perfil. <br/> **Entonces** debo poder ver una lista con las insignia que obtuve junto a sus detalles. <br/><br/> *Escenario 3:* <br/> **"  Comparte tus logros "** <br/> **Dado que** valoro el reconocimiento. <br/> **Cuando**  obtenga una nueva insignia. <br/> **Entonces** CleanWind debo poder compartirlo en redes sociales. | - |
| US-019           | Contratación de servicios de recolección | **Como** empresa <br/> **Quiero** contratar servicios de recolección de residuos <br/> **Para** asegurar el recojo eficiente según mi necesidad. | *Escenario 1:* <br/> **"Selección de proveedor de recolección "** <br/> **Dado que** necesito gestionar los residuos de mi empresa. . <br/> **Cuando** ingreso a la sección de puntos de acopio y busco la empresa que mejor se acomode a mis necesidades. . <br/> **Entonces** el sistema me permite contratar el servicio según mi elección. <br/><br/> *Escenario 2:* <br/> **" Visualización del estado de contrato"** <br/> **Dado que** . <br/> ya contraté un servicio de recolección. **Cuando** accedo a “Mis servicios contratados” desde el apartado de puntos de acopio. <br/> **Entonces**  el sistema me muestra la recolectora, el tipo de residuo con el que trabajo en nuestra empresa y el estado del servicio y la fecha programada. <br/><br/> *Escenario 3:* <br/> **"Cancelación de servicio de recolección"** <br/> **Dado que** ya contraté un servicio de recolección pero deseo cancelarlo . <br/> **Cuando** accedo a “Mis servicios contratados” y presiono el ícono de basurero . <br/> **Entonces** el sistema me solicita confirmación y, tras aceptarla, cancela el servicio y lo elimina de la lista. | - |
| US-020           | Añadir nueva zona de monitoreo | **Como** empresario <br/> **Quiero** añadir una nueva zona de monitoreo con sensores <br/> **Para** gestionar y supervisar mejor los residuos en distintas áreas. | *Escenario 1:* <br/> **"Registro de nueva zona correctamente"** <br/> **Dado que** necesito crear una nueva zona para monitorear residuos . <br/> **Cuando** accedo a “Mis Zonas” desde el Panel de Control y selecciono el botón “Añadir Zona”. <br/> **Entonces** el sistema me muestra un formulario donde ingreso los datos de la zona, **Y** al presionar “Registrar” la zona se registra correctamente <br/><br/> *Escenario 2:* <br/> **"Visualización de zona registrada"** <br/> **Dado que** he registrado una nueva zona. <br/> **Cuando** accedo a la sección “Mis Zonas” . <br/> **Entonces** el sistema muestra la nueva zona en la lista junto con el número de sensores y los datos asignados. <br/><br/> *Escenario 3:* <br/> **"Prevención de zonas duplicadas "** <br/> **Dado que** ya existe una zona con el mismo nombre y ubicación. <br/> **Cuando** intento registrar una nueva zona con esa misma información . <br/> **Entonces** el sistema me muestra un mensaje indicando que esa zona ya fue registrada previamente. | - |
| US-021           |  |  |  | - |


## 3.3. Impact Mapping

![Impact Mapping](https://github.com/1ASI0729-2510-4313-G1-CleanView/CleanView-Report/blob/develop/img/Impact%20Mapping.jpg)
> https://miro.com/welcomeonboard/NFZvdkRBQXJwLzdFTTM4OXNGSkQxOFpsSTFtQmE2bFVxYTJhMEw4YzhseXgxTFpVbDFLQnpydlUrdVNuM1ZCalF6U3Bha2g3dUhqeUsrbWtERUxFeVpjeFp5Z0xpTFR0Y0hzdFl2SkxITzBwQUo0T090VnNkaTJsUHdZODNlYUtyVmtkMG5hNDA3dVlncnBvRVB2ZXBnPT0hdjE=?share_link_id=65294902373 

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

