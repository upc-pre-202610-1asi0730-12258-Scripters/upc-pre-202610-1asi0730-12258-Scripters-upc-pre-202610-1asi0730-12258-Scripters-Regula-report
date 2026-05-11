# Requirements Elicitations & Analysis

Esta etapa es fundamental en el desarrollo de nuestro sistema, ya que permite identificar, comprender y definir las necesidades reales de los usuarios y del negocio. En esta fase, se recopila información a partir de diferentes fuentes, como entrevistas, observación y análisis del contexto, con el objetivo de obtener una visión clara de los problemas existentes y las funcionalidades que la solución debe cubrir.

## **2.1. Competidores**

### **Competidor 1: IoT Smart Gas Platform**

**IoT Smart Gas** es una solución tecnológica basada en IoT que permite monitorear balones y tanques de gas en tiempo real mediante sensores conectados. Sus funcionalidades incluyen la medición de niveles de gas, presión y consumo, así como la visualización de datos a través de plataformas web o móviles, facilitando la gestión de inventario y la planificación de reposiciones. Es un competidor directo frente a nuestra startup, ya que también ofrece monitoreo y seguimiento en tiempo real; sin embargo, su enfoque está centrado principalmente en el consumo y control del suministro de gas, y no abarca de manera integral aspectos como la seguridad en almacenes mediante sensores ambientales, la gestión de cobranzas o el control completo de la distribución, que sí forman parte de la propuesta de Regula.

### **Competidor 2: GasSense (innovateIT – Smart LPG Monitoring)**

**GasSense** permite monitorear balones de gas en tiempo real mediante sensores inteligentes. Sus funcionalidades incluyen la medición del nivel de gas, generación de alertas cuando el contenido es bajo, análisis del consumo y visualización de datos a través de una plataforma web o aplicación móvil. Está orientado tanto a usuarios domésticos como a entornos industriales, buscando optimizar el uso y disponibilidad del gas. Es un competidor directo frente a nuestra startup, ya que también integra monitoreo en tiempo real y análisis de datos; sin embargo, su alcance se limita principalmente al seguimiento del estado del gas a nivel de consumo, sin integrar una solución enfocada en la operación del negocio, como la coordinación de distribución, el registro de movimientos de inventario o la administración financiera de los clientes.

### **Competidor 3: .one Meter (plataforma LPG de Aton)**

**.one Meter** es una solución empresarial orientada al sector energético que permite supervisar grandes volúmenes de balones y tanques de gas mediante tecnologías como IoT y RFID. Su sistema centraliza información en la nube y ofrece funcionalidades como trazabilidad de activos, geolocalización de unidades de transporte, control de operaciones y análisis de datos a nivel corporativo. Está diseñada principalmente para compañías de gran escala que requieren visibilidad completa de sus procesos logísticos y operativos. En relación con nuestra startup, representa un competidor directo en el ámbito del control y seguimiento de activos; sin embargo, su enfoque está dirigido a organizaciones más grandes y complejas, con soluciones menos accesibles para distribuidores pequeños o medianos.

| **Competitive Analysis Landscape** |     |
| ---- | ----- |
|  ¿Por qué llevar a cabo este análisis? |   Este análisis se realiza para comprender a fondo los problemas del sector, identificar las necesidades reales de los usuarios y definir requisitos claros que permitan desarrollar una solución efectiva. En el caso de Regula, permite asegurar que la aplicación web responda a problemas críticos como el control de inventario, la seguridad y la gestión de cobranzas. |

## Perfil

|                       | **Regula (Startup)** | Competidor 1 – **IoT Smart Gas Platform** <br> <img src="../../report/assets/images/smart-gas.png">| Competidor 2 – **GasSense** <br> <img src="../../report/assets/images/gas-sense.png"> | Competidor 3 – **.one Meter** <br> <img src="../../report/assets/images/.one-meter.png"> |
|-----------------------|----------------------------------|---------------------------------------------|--------------------------------|----------------------------------------|
| **Perfil / Overview** | Plataforma web orientada a empresas envasadoras y distribuidores de balones de gas que permite gestionar inventario, distribución y cobranzas, además de mejorar la seguridad mediante monitoreo ambiental con sensores de gas en almacenes. | Plataforma basada en IoT que permite monitorear balones y tanques de gas en tiempo real, enfocada en el seguimiento del consumo, niveles de gas y optimización del abastecimiento. | Sistema inteligente que utiliza sensores para supervisar el nivel de gas y generar alertas de consumo, orientado a mejorar la disponibilidad del recurso en hogares e industrias mediante análisis de datos. | Plataforma empresarial que permite el seguimiento y control de activos de gas a gran escala mediante tecnologías como IoT y RFID, ofreciendo trazabilidad, geolocalización y análisis centralizado de operaciones. |
| **Ventaja competitiva / Valor** | Ofrece una solución integral que combina gestión operativa con seguridad mediante monitoreo ambiental de gas en almacenes, todo centralizado en una aplicación web accesible y fácil de usar para empresas y distribuidores. | Su ventaja radica en el monitoreo en tiempo real del consumo y nivel de gas mediante sensores IoT, lo que permite optimizar el abastecimiento y evitar interrupciones en el suministro. | Ofrece como valor principal la predicción y control del consumo de gas a través de análisis de datos, facilitando alertas tempranas y una mejor planificación del uso del recurso. | Su ventaja competitiva es la capacidad de gestionar y supervisar grandes volúmenes de activos de gas con trazabilidad y geolocalización en tiempo real, orientado a operaciones de gran escala. |

## Perfil de Marketing


|                       | **Regula (Startup)** | Competidor 1 – **IoT Smart Gas Platform** <br> <img src="../../report/assets/images/smart-gas.png">| Competidor 2 – **GasSense** <br> <img src="../../report/assets/images/gas-sense.png"> | Competidor 3 – **.one Meter** <br> <img src="../../report/assets/images/.one-meter.png"> |
|-----------------------|----------------------------------|---------------------------------------------|--------------------------------|----------------------------------------|
| **Mercado objetivo** | Empresas envasadoras de gas y distribuidores de balones de GLP, especialmente pequeñas y medianas empresas que necesitan mejorar su control de inventario, distribución, cobranzas y seguridad operativa. | Empresas de gas, industrias y organizaciones que buscan optimizar el abastecimiento mediante monitoreo del consumo y niveles de gas en tanques o cilindros. | Usuarios domésticos, comercios e industrias que desean controlar el consumo de gas y recibir alertas para una mejor gestión del suministro. | Grandes corporaciones del sector energético y empresas de distribución de gas que operan a gran escala y requieren soluciones avanzadas para la gestión y seguimiento de activos. |
| **Estrategias de marketing** | Estrategia enfocada en un modelo B2B, con captación directa de clientes mediante demostraciones del sistema, visitas a distribuidores y alianzas con empresas del sector gas. Se complementa con presencia digital (redes, landing page) y un enfoque en mostrar ahorro de costos, control operativo y mejora en seguridad como propuesta de valor. | Estrategia basada en marketing tecnológico, destacando innovación IoT, automatización y eficiencia operativa. Utiliza canales digitales, demostraciones del producto y contenido técnico para atraer empresas interesadas en la transformación digital. | Estrategia mixta B2C y B2B, enfocada en resaltar comodidad, control del consumo y ahorro. Utiliza marketing digital, aplicaciones móviles y comunicación directa de beneficios al usuario final. | Estrategia corporativa dirigida a grandes empresas, basada en soluciones empresariales a medida, participación en ferias del sector energético y posicionamiento como proveedor tecnológico avanzado a nivel internacional. |

## Perfil de producto

|                       | **Regula (Startup)** | Competidor 1 – **IoT Smart Gas Platform** <br> <img src="../../report/assets/images/smart-gas.png">| Competidor 2 – **GasSense** <br> <img src="../../report/assets/images/gas-sense.png"> | Competidor 3 – **.one Meter** <br> <img src="../../report/assets/images/.one-meter.png"> |
|-----------------------|----------------------------------|---------------------------------------------|--------------------------------|----------------------------------------|
| **Productos & Servicios** | Aplicación web para gestión de inventario, distribución y cobranzas, junto con monitoreo ambiental de gas en almacenes mediante sensores y alertas en tiempo real. | Plataforma IoT con sensores para monitoreo de niveles, consumo y estado del gas, con visualización de datos en tiempo real. | Sistema de monitoreo de gas con sensores inteligentes, alertas de nivel bajo y análisis de consumo accesible desde app o web. | Plataforma empresarial para gestión de activos de gas con IoT y RFID, incluyendo trazabilidad, geolocalización y análisis de datos. |
| **Precios & Costos** | Regula utiliza un modelo SaaS basado en suscripción mensual, donde los clientes pagan por el acceso a la plataforma según su tamaño o uso. Adicionalmente, puede generar ingresos por servicios complementarios como implementación inicial y venta o integración de sensores de gas. | Opera con un modelo híbrido que combina la venta de dispositivos IoT (sensores) con suscripciones a una plataforma digital para monitoreo y gestión de datos. | Su modelo de negocio se basa en la comercialización de sensores inteligentes junto con el acceso a su sistema de monitoreo mediante suscripción, ofreciendo valor a través del análisis del consumo. | Funciona bajo un modelo empresarial que combina licencias de software, servicios personalizados e integración tecnológica, generalmente mediante contratos y suscripciones dirigidas a grandes compañías. |
| **Canales de distribución (Web y/o Móvil)** | Principalmente a través de una aplicación web, accesible desde cualquier dispositivo con internet, con posibilidad de integración futura con versión móvil. | Acceso mediante plataforma web y aplicación móvil, complementado con dispositivos físicos conectados (sensores IoT). | Uso de aplicación móvil y plataforma web para monitoreo y visualización de datos en tiempo real. | Distribución a través de plataforma web empresarial en la nube, con acceso remoto para gestión y monitoreo de operaciones. |


## Análisis SWOT

*Análisis FODA*

|                       | **Regula (Startup)** | Competidor 1 – **IoT Smart Gas Platform** <br> <img src="../../report/assets/images/smart-gas.png">| Competidor 2 – **GasSense** <br> <img src="../../report/assets/images/gas-sense.png"> | Competidor 3 – **.one Meter** <br> <img src="../../report/assets/images/.one-meter.png"> |
|-----------------------|----------------------------------|---------------------------------------------|--------------------------------|----------------------------------------|
| **Fortalezas** | Solución integral que combina gestión operativa y seguridad, fácil de usar, accesible para PYMES y enfocada en necesidades reales del sector. | Monitoreo en tiempo real mediante IoT, automatización de datos y optimización del abastecimiento de gas. | Capacidad de análisis y predicción de consumo, con alertas inteligentes que mejoran la gestión del uso de gas. | Alta escalabilidad, trazabilidad de activos y gestión centralizada para operaciones de gran volumen. |
| **Debilidades** | Marca nueva en el mercado, menor experiencia en el sector y dependencia de adopción tecnológica por parte de usuarios tradicionales. | Dependencia de hardware (sensores) que eleva costos iniciales y enfoque limitado al monitoreo del gas, sin cubrir procesos del negocio. | Enfoque centrado en consumo y no en la gestión operativa completa, con menor utilidad para distribuidores o empresas logísticas. | Alto costo y complejidad de implementación, orientado a grandes empresas, lo que dificulta su adopción en PYMES. |
| **Oportunidades** | Creciente necesidad de digitalización en el sector, baja adopción tecnológica en distribuidores y demanda por mejorar seguridad y control operativo. | Creciente necesidad de digitalización en el sector, baja adopción tecnológica en distribuidores y demanda por mejorar seguridad y control operativo. | Mayor interés en eficiencia energética y control de consumo tanto en hogares como en industrias. | Crecimiento de grandes empresas energéticas que requieren soluciones avanzadas para optimizar sus operaciones a gran escala. |
| **Amenazas** | Competencia de soluciones tecnológicas ya posicionadas, resistencia al cambio por parte de usuarios tradicionales y posibles limitaciones en adopción por presupuesto. | Alta competencia en el mercado IoT y barreras de adopción por costos iniciales o complejidad técnica. | Saturación de soluciones similares enfocadas en consumo y dificultad para diferenciarse en el mercado. | Dependencia de grandes clientes y competencia de soluciones más accesibles que pueden captar segmentos más pequeños del mercado. |


## Estrategias y tácticas preliminares frente a la competencia

Para definir las estrategias y tácticas preliminares de Regula frente a la competencia, se toma como base el análisis competitivo realizado, considerando las fortalezas y debilidades de cada competidor, así como las oportunidades del mercado y las amenazas presentes en el sector de distribución y monitoreo de gas GLP.

---

## Estrategias para afrontar las fortalezas de los competidores

### Frente a IoT Smart Gas Platform

La principal fortaleza de IoT Smart Gas Platform es el monitoreo en tiempo real mediante sensores IoT y la optimización del abastecimiento de gas. Frente a ello, Regula aplica una estrategia de diferenciación funcional integral.

Mientras IoT Smart Gas se enfoca principalmente en el consumo y suministro de gas, Regula incorpora además gestión de inventario, distribución, cobranzas y monitoreo ambiental de seguridad en almacenes dentro de una sola plataforma.

**Táctica:**  
Posicionar a Regula como una solución completa para empresas distribuidoras y envasadoras, resaltando que no solo monitorea el gas, sino que también optimiza toda la operación del negocio.

### Frente a GasSense

GasSense tiene como principal fortaleza el análisis predictivo del consumo y las alertas inteligentes para usuarios domésticos e industriales. Frente a ello, Regula aplica una estrategia de especialización orientada al sector empresarial B2B.

GasSense está enfocado principalmente en el control del consumo de gas, mientras que Regula cubre necesidades operativas críticas de distribuidores y empresas envasadoras.

**Táctica:**  
Destacar que la plataforma fue diseñada específicamente para resolver problemas de logística, control de inventario, cobranzas y seguridad operativa, aspectos que GasSense no aborda de forma integral.

### Frente a .one Meter

La principal ventaja competitiva de .one Meter es la gestión de grandes volúmenes de activos mediante IoT y RFID con trazabilidad corporativa. Frente a ello, Regula aplica una estrategia de accesibilidad y enfoque en PYMES.

Aunque .one Meter ofrece soluciones avanzadas para grandes compañías, su complejidad y costos dificultan su adopción en distribuidores pequeños y medianos.

**Táctica:**  
Posicionar a Regula como una alternativa moderna, sencilla y accesible económicamente, permitiendo que empresas con menor capacidad de inversión puedan digitalizar sus operaciones sin requerir infraestructuras complejas.

---

## Estrategias para aprovechar las debilidades de los competidores

### Debilidad de IoT Smart Gas Platform

Su enfoque está limitado principalmente al monitoreo del gas y depende considerablemente de hardware especializado, lo que incrementa costos de implementación.

Regula aprovecha esta debilidad ofreciendo una plataforma centrada también en procesos administrativos y operativos del negocio, reduciendo la dependencia exclusiva del monitoreo físico.

**Táctica:**  
Enfatizar el ahorro operativo y la facilidad de implementación mediante una aplicación web accesible desde cualquier dispositivo con internet.

### Debilidad de GasSense

Su propuesta se concentra en el análisis del consumo y no en la gestión integral de operaciones empresariales.

Regula aprovecha esta brecha ofreciendo módulos orientados específicamente al control de distribución, inventario y cobranzas.

**Táctica:**  
Mostrar casos de uso relacionados con empresas distribuidoras de GLP, evidenciando cómo Regula mejora la eficiencia operativa y reduce problemas administrativos cotidianos.

### Debilidad de .one Meter

Su alto costo y complejidad de implementación dificultan la adopción por parte de pequeñas y medianas empresas.

Regula aprovecha esta debilidad mediante una estrategia de penetración en el segmento pyme, ofreciendo una solución SaaS más flexible y económica.

**Táctica:**  
Brindar demostraciones gratuitas, pruebas piloto y acompañamiento inicial para facilitar la adopción tecnológica por parte de distribuidores tradicionales.

---

## Estrategias para aprovechar las oportunidades del entorno

El sector de distribución de GLP presenta una baja digitalización y todavía depende en gran medida de procesos manuales para el control de inventario, distribución y cobranzas.

Regula aprovecha esta oportunidad mediante una estrategia de transformación digital accesible, enfocándose en empresas que necesitan modernizar sus operaciones sin realizar inversiones elevadas.

**Táctica:**  
Ofrecer una plataforma intuitiva y fácil de implementar, acompañada de capacitaciones y soporte básico para acelerar la adopción.

Asimismo, existe una creciente preocupación por la seguridad en almacenes y operaciones relacionadas con gas GLP, especialmente en empresas que aún no cuentan con sistemas de monitoreo ambiental.

Regula aprovecha esta oportunidad integrando sensores ambientales y alertas en tiempo real dentro de su propuesta de valor.

**Táctica:**  
Comunicar la importancia de la prevención de fugas y riesgos operativos como un beneficio diferencial frente a otras soluciones centradas únicamente en consumo o logística.

Otra oportunidad importante es el incremento del interés por soluciones IoT y plataformas inteligentes en el sector energético.

Regula aprovecha este contexto posicionándose como una startup innovadora que integra monitoreo y gestión operativa en una única solución.

**Táctica:**  
Fortalecer la presencia digital mediante landing pages, redes sociales y demostraciones enfocadas en mostrar beneficios reales para distribuidores y empresas envasadoras.

---

## Estrategias para mitigar las amenazas del entorno

Una de las principales amenazas identificadas es la presencia de empresas tecnológicas ya posicionadas en el mercado IoT y energético, las cuales cuentan con mayor reconocimiento y experiencia.

Para mitigar esta amenaza, Regula aplica una estrategia de diferenciación basada en cercanía con el cliente y adaptación a necesidades reales del sector GLP.

**Táctica:**  
Mantener comunicación constante con los primeros clientes para incorporar mejoras continuas al sistema según sus problemas operativos reales.

Otra amenaza importante es la resistencia al cambio y la baja adopción tecnológica por parte de distribuidores tradicionales que aún trabajan con métodos manuales.

Regula enfrenta esta situación mediante una estrategia de simplificación de uso y acompañamiento inicial.

**Táctica:**  
Ofrecer capacitaciones, soporte básico y una interfaz intuitiva que reduzca la dificultad de transición hacia procesos digitalizados.

Finalmente, existe la amenaza de que nuevas soluciones tecnológicas más económicas ingresen al mercado y compitan directamente con Regula.

Para reducir este riesgo, la startup aplica una estrategia de fidelización temprana, buscando construir relaciones sólidas con sus primeros clientes.

**Táctica:**  
Proporcionar atención personalizada, actualizaciones frecuentes y mejoras constantes que generen confianza y dependencia positiva hacia la plataforma.