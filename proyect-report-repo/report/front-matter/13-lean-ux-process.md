### 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

En el sector de distribución y envasado de balones de gas, las empresas y distribuidores presentan varios problemas en sus operaciones diarias, tanto en la parte logística como en la gestión del negocio. Este sector depende mucho del control físico de los balones (cuántos hay, dónde están y en qué estado se encuentran), pero actualmente muchos de estos procesos no están digitalizados. Esto genera desorden, falta de información en tiempo real y riesgos en la seguridad, especialmente cuando no se detectan fugas de gas a tiempo o no se tiene un control claro del inventario.

Los principales involucrados son las empresas envasadoras y los distribuidores de gas, quienes necesitan controlar su stock, coordinar entregas y gestionar pagos de clientes. Sin embargo, enfrentan problemas como el uso de papel y lapicero para registrar entradas y salidas, lo que provoca errores; la falta de monitoreo en tiempo real en almacenes y durante el transporte; la detección tardía de fugas de gas en zonas de almacenamiento; robos de balones durante la distribución; y dificultades para llevar un control ordenado de las deudas de sus clientes, lo que afecta su flujo de dinero.

Existe una clara diferencia entre cómo se gestionan actualmente estas operaciones y cómo podrían optimizarse usando herramientas digitales. Mientras que otros sectores ya utilizan sistemas que les permiten ver su información en tiempo real, en este caso aún predominan procesos manuales que generan pérdidas, desorganización y poca visibilidad de lo que ocurre en el negocio.

Frente a esto, el proyecto propone desarrollar una aplicación web (Regula) que permita a las empresas y distribuidores registrar y controlar su inventario, gestionar entradas y salidas de balones, monitorear la distribución de los camiones y llevar un control organizado de las deudas de sus clientes. Además, la solución se complementa con el uso de sensores de gas instalados en almacenes, los cuales detectarán la presencia de gas en el ambiente y enviarán alertas al sistema en tiempo real. Toda esta información se mostrará en un panel (dashboard) dentro de la app web, permitiendo a los usuarios tomar decisiones rápidas y basadas en datos.

Como punto de inicio, se trabajará principalmente con distribuidores de gas, ya que suelen tener más problemas en la organización de sus procesos, especialmente en el control de inventario y cobranzas. Esto permitirá validar la solución de forma más rápida antes de implementarla en empresas envasadoras de mayor escala.

### 1.2.2.2. Lean UX Assumptions

- **Business Assumptions**

Se asume que las empresas envasadoras y distribuidores de balones de gas tienen pérdidas económicas significativas debido a fugas no detectadas, robos en ruta y desorganización en inventarios y cobranzas. También se asume que estas empresas están dispuestas a invertir en una aplicación web si perciben que esta les ayudará a reducir pérdidas, mejorar su control operativo y aumentar su rentabilidad. Además, se considera que existe una oportunidad de mercado, ya que el sector presenta bajo nivel de digitalización en comparación con otras industrias.

- **User Assumptions**

Se asume que los usuarios (principalmente distribuidores y personal operativo) tienen dificultades para gestionar sus procesos de manera manual, especialmente en el control de inventario y deudas. También se considera que están dispuestos a usar una aplicación web sencilla e intuitiva, siempre que no complique su trabajo diario. Asimismo, se asume que valoran tener acceso rápido a información clara sobre su negocio y que necesitan herramientas que les faciliten el registro y seguimiento de sus operaciones.

- **User Outcomes & Benefits Assumptions**

Se asume que los usuarios obtendrán beneficios claros al utilizar la solución, como un mejor control del inventario, reducción de errores en registros de compra y venta de balones y mayor organización en la gestión de cobranzas. También se espera que los usuarios puedan detectar problemas de seguridad de forma más rápida gracias a las alertas automáticas generadas por los sensores de gas instalados en los almacenes, las cuales se activarán cuando se detecte presencia de gas en el ambiente por encima de niveles normales. Estas alertas se visualizarán en la aplicación web en tiempo real, permitiendo tomar acciones inmediatas como revisar el área o aislar la zona afectada. Además, se considera que los usuarios valorarán poder tomar decisiones más rápidas al contar con un dashboard actualizado en tiempo real, donde podrán ver información clave como el estado del inventario, alertas activas y deudas pendientes, lo que les permitirá reaccionar de manera oportuna ante cualquier problema.

- **Business Outcome Assumptions**

Se asume que la implementación de Regula permitirá a las empresas reducir pérdidas económicas, tanto por fugas de gas como por robos o errores en inventario. También se espera que mejore el flujo de ingresos mediante una mejor gestión de cobranzas, reduciendo el porcentaje de clientes morosos. Por último, consideramos que nuestra solución contribuirá a una mayor eficiencia operativa, disminuyendo tiempos de gestión y mejorando la toma de decisiones.

- **Features Assumptions**

Se asume que ciertas funcionalidades serán clave para generar valor en los usuarios, como el registro digital de inventario (entradas y salidas), el dashboard con información en tiempo real, el módulo de gestión de cobranzas y el sistema de alertas por detección de gas en almacenes. También se considera importante el seguimiento de la distribución, para tener mayor control sobre los balones durante el transporte. Se asume que estas funcionalidades cubrirán las principales necesidades del usuario y serán utilizadas de manera frecuente.

### 1.2.2.3. Lean UX Hypothesis Statements

- **User Hypotheses**

**Creemos que** los distribuidores de balones de gas tienen dificultades para gestionar su inventario porque utilizan métodos manuales; **por ello**, si les ofrecemos una aplicación web para registrar entradas y salidas en tiempo real, podrán organizar mejor su stock, **y sabremos que esto es cierto** si disminuyen los errores y diferencias en el inventario.

**Creemos que** los usuarios necesitan tener mayor visibilidad de sus operaciones; **por ello**, si implementamos un dashboard con información de ventas, ubicación de sus repartidores en tiempo real y un sistema de alertas por fugas de gas dentro de la aplicación web, podrán tomar decisiones más rápidas, **y sabremos que esto es cierto** si los usuarios consultan frecuentemente la plataforma y reportan mayor control sobre su negocio.

- **Business Hypotheses**

**Creemos que** las empresas envasadoras y distribuidores están perdiendo dinero debido a fugas, robos y desorganización; **por ello**, si implementamos una solución digital que centralice la información, podremos reducir estas pérdidas, **y sabremos que esto es cierto** si disminuyen los incidentes reportados y mejora la rentabilidad del negocio.

**Creemos que** mejorar la gestión de cobranzas impactará directamente en el flujo de ingresos; **por ello**, si ofrecemos un sistema digital para registrar y dar seguimiento a deudas pendientes, se reducirá el porcentaje de pagos atrasados, **y sabremos que esto es cierto** si disminuye la cantidad de clientes morosos.

- **Feature Hypotheses**

**Creemos que** la implementación de sensores de gas en almacenes permitirá detectar fugas de manera oportuna; **por ello**, si integramos estos sensores con la aplicación web para generar alertas en tiempo real, los usuarios podrán actuar rápidamente, **y sabremos que esto es cierto** si se incrementa la detección temprana de incidentes.

**Creemos que** el sistema de monitoreo de distribución ayudará a mejorar la seguridad en ruta; **por ello**, si registramos y visualizamos el movimiento de los camiones y/o motorizados dentro de la aplicación web, se podrá tener mayor control logístico, **y sabremos que esto es cierto** si disminuyen los reportes de pérdidas, accidentes o robos.

- **User Outcome Hypotheses**

**Creemos que** los usuarios necesitan organizar mejor sus cobranzas; **por ello**, si implementamos un sistema que permita registrar deudas por cliente y hacer seguimiento, podrán tener mayor control financiero,**y sabremos que esto es cierto** si los usuarios logran identificar rápidamente quién debe, cuánto debe y desde cuándo.

**Creemos que** los usuarios valorarán la reducción de riesgos en sus operaciones;**por ello**, si reciben alertas en tiempo real sobre posibles fugas de gas, podrán prevenir accidentes, **y sabremos que esto es cierto** si los usuarios reportan mayor sensación de seguridad en sus almacenes.



### 1.2.2.4. Lean UX Canvas

| **Business Problem** | **Solutions** | **Business Outcomes** |
| -------------------- | ------------- | --------------------- | 
| El sector de distribución y envasado de balones de gas presenta múltiples deficiencias en el control operativo, la seguridad y la gestión financiera. Muchas empresas y distribuidores aún utilizan métodos manuales como papel y lapicero para registrar inventarios y ventas, lo que genera errores, desorden y falta de información en tiempo real. Además, existen problemas críticos como fugas de gas no detectadas oportunamente, que pueden representar pérdidas de entre el 20% y 25% del contenido de un balón. A esto se suma que más de 4 millones de balones no cumplen con normas técnicas, incrementando riesgos de accidentes y pérdidas económicas. También se presentan robos durante el transporte, donde un solo incidente puede generar pérdidas de entre S/10,000 y S/40,000, así como problemas de cobranza debido a la falta de control organizado de deudas por cliente. | Regula propone el desarrollo de una plataforma web que permita gestionar inventarios, monitorear la distribución y registrar operaciones en tiempo real. Asimismo, se plantea la implementación de sensores de gas en almacenes para detectar la presencia de gas en el ambiente y generar alertas inmediatas. La solución incluye dashboards con indicadores clave, reportes automatizados y un sistema de gestión de clientes y cobranzas, integrando en un solo sistema todas las necesidades operativas. | El objetivo de Regula es reducir las pérdidas económicas, mejorar la eficiencia operativa y aumentar la seguridad en toda la cadena de distribución. Se espera disminuir los errores de inventario en al menos un 30%, reducir el porcentaje de deudas no cobradas que puede representar entre el 10% y 30% de las ventas en distribuidores y mejorar la capacidad de respuesta ante incidentes. Asimismo, se busca optimizar la planificación logística, reducir robos en ruta y lograr una mejor organización en la gestión de clientes y cobranzas. |

| **Users** | **Users Outcomes and Benefits** |
| --------- | ------------------------------- |
| Los principales usuarios de la solución Regula son **las empresas envasadoras** de balones de gas y **los distribuidores**, tanto formales como independientes, quienes necesitan mejorar el control de sus operaciones diarias. Dentro de estos grupos, también se incluyen los administradores y gerentes, que requieren información clara y en tiempo real para la toma de decisiones, así como el personal operativo, como encargados de almacén y transporte, quienes interactúan directamente con el registro de inventario, distribución y manejo de los balones. Todos estos usuarios comparten la necesidad de optimizar sus procesos, reducir errores y mejorar la seguridad en sus actividades. | Con el uso de Regula, los usuarios podrán lograr un mayor control y organización en sus operaciones, accediendo a información en tiempo real sobre inventario, distribución y condiciones del almacén. Esto les permitirá **reducir pérdidas económicas** causadas por fugas, robos o errores en el registro, así como mejorar la planificación de compras y ventas. Además, podrán gestionar de manera más eficiente las deudas de sus clientes, facilitando el seguimiento de pagos y mejorando su flujo de ingresos. En términos de seguridad, la detección temprana de presencia de gas en el ambiente ayudará a prevenir accidentes. En conjunto, la solución permitirá a los usuarios tomar decisiones más rápidas y precisas, aumentando la eficiencia y sostenibilidad de sus negocios. |

| **Hypotheses** | **What’s the most important thing we need to learn first?** | **What’s the least amount of work we need to do to learn the next most important thing?** |
| -------------- | ------------------ | ---------------- |
| Se plantea que los usuarios adoptarán una solución digital si esta simplifica sus procesos y reduce sus pérdidas operativas. También se considera que el monitoreo en tiempo real permitirá prevenir incidentes como fugas o robos, y que la digitalización de la cobranza mejorará el control de deudas. Estas hipótesis parten de la premisa de que la falta de tecnología es una de las principales causas de ineficiencia en el sector. | Lo más importante que necesitamos validar primero es si las empresas envasadoras y distribuidores realmente perciben como un problema crítico la falta de control en sus operaciones y si estarían dispuestos a adoptar una solución digital para resolverlo. Es fundamental entender qué tan frecuente son problemas como las fugas no detectadas, los errores en inventario, los robos en ruta y el desorden en la cobranza, así como el impacto real que estos tienen en su negocio. Además, es clave conocer si los usuarios confiarían en un sistema que combine monitoreo ambiental con gestión digital, y si consideran valioso contar con información en tiempo real para la toma de decisiones. | La forma más rápida y sencilla de validar estas hipótesis es realizar entrevistas directas con empresas y distribuidores, complementadas con encuestas breves que permitan recopilar información sobre sus procesos actuales y principales problemas. Asimismo, se puede desarrollar un prototipo básico (por ejemplo, en Figma) que simule las principales funcionalidades del sistema, como el control de inventario, alertas y gestión de cobranzas, para obtener feedback temprano de los usuarios. También se podría plantear una prueba piloto simple con un sensor de gas en un almacén para validar la utilidad del monitoreo ambiental. Estas acciones permiten obtener aprendizaje valioso con un esfuerzo mínimo antes de desarrollar una solución completa. |