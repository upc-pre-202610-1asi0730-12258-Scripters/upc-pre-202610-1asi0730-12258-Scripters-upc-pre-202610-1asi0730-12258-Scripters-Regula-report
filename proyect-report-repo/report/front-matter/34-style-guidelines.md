# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

La voz de Regula debe reflejar los valores del producto: **seguridad, eficiencia y confianza**. Cada mensaje, etiqueta, alerta o texto de interfaz debe estar alineado con los siguientes principios:

* **Confiable y profesional:**
  Regula opera en contextos de alta responsabilidad (seguridad industrial, control de inventario, detección de fugas). El lenguaje debe transmitir solidez técnica y respaldo institucional, evitando ambigüedades.

* **Claro y directo:**
  Los usuarios son operarios, supervisores y distribuidores con alta carga operativa. Los mensajes deben ser concisos, sin tecnicismos innecesarios. Las alertas y notificaciones deben ser inmediatamente comprensibles.

* **Orientado a la acción:**
  Las instrucciones, botones y CTAs deben incitar a actuar de forma natural.
  Ejemplos: *"Registrar entrada"*, *"Ver alerta"*, *"Confirmar entrega"*, *"Monitorear almacén"*.

* **Cercano pero no informal:**
  Regula habla de tú a tú con el usuario, reconociendo el contexto operativo de su trabajo. El tono no es corporativo frío ni coloquial excesivo; es empático y funcional.

* **Enfocado en beneficios tangibles:**
  Los mensajes destacan resultados concretos: reducción de pérdidas, mayor seguridad, control de inventario en tiempo real y trazabilidad de repartos.

---

### Tipografía

La tipografía de Regula prioriza la **legibilidad funcional en pantalla**, especialmente en contextos de trabajo donde los usuarios consultan información rápida de tableros, alertas y registros.

* **Familia tipográfica principal:** Inter
  Inter es una fuente sans-serif diseñada específicamente para interfaces digitales. Ofrece excelente legibilidad a tamaños pequeños y medios, siendo ideal para dashboards, formularios y textos operativos.


### Escala Tipográfica

| Elemento              | Fuente | Tamaño          | Peso         | Uso Principal                                        |
| --------------------- | ------ | --------------- | ------------ | ---------------------------------------------------- |
| H1 – Título de página | Inter  | 32px / 2rem     | Bold 700     | Nombres de sección, pantalla principal del dashboard |
| H2 – Subtítulo        | Inter  | 24px / 1.5rem   | SemiBold 600 | Subtítulos de módulos, encabezados de tarjetas       |
| H3 – Encabezado       | Inter  | 20px / 1.25rem  | SemiBold 600 | Títulos de widgets, tablas y formularios             |
| Body – Cuerpo         | Inter  | 16px / 1rem     | Regular 400  | Textos descriptivos, párrafos, etiquetas de campo    |
| Small – Secundario    | Inter  | 14px / 0.875rem | Regular 400  | Metadatos, timestamps, textos de apoyo               |
| Caption – Pie         | Inter  | 12px / 0.75rem  | Medium 500   | Leyendas de gráficas, tooltips, notas                |
| Label – CTA           | Inter  | 14–16px         | Bold 700     | Botones de acción, badges de estado, alertas         |

### Tipografía Complementaria

* **Fuente monoespaciada:** JetBrains Mono
  **Uso específico:** Códigos de balón, IDs de operación, timestamps técnicos y datos de sensores IoT donde se requiere precisión visual.

---

### Jerarquía Visual

* **Contraste de tamaño:**
  Los títulos deben ser al menos **1.5×** el tamaño del cuerpo para generar una jerarquía clara.

* **Interlineado:**

    * **1.5×** el tamaño de fuente para cuerpo
    * **1.2×** para títulos y etiquetas compactas

* **Longitud de línea:**
  Máximo **75 caracteres por línea** para garantizar legibilidad óptima en pantalla.

---

### Descripción de Colores

* **Azul Marino Profundo (#172D40):**
  Color primario de marca. Transmite confianza, control y seriedad técnica. Se usa en header, sidebar, títulos principales y elementos de navegación. Es el color ancla de la identidad de Regula.

* **Naranja Activo (#F26E22):**
  Acento principal de energía y acción. Representa dinamismo, urgencia positiva y visibilidad operativa. Ideal para botones CTA primarios, íconos destacados y elementos interactivos de primer nivel.

* **Naranja Alerta (#F25922):**
  Variante más intensa del naranja. Se usa para alertas de mayor urgencia, indicadores de riesgo moderado-alto y estados activos críticos como detección de fuga o estado *"en ruta"*.

* **Gris Acero (#A5B1BF):**
  Color neutro frío. Complementa al azul marino en elementos secundarios: bordes, separadores, textos de apoyo, íconos inactivos y fondos de tarjetas neutras.

* **Blanco Hielo (#F8F8FB):**
  Fondo principal de la interfaz. Proporciona limpieza visual, contraste suave y reduce la fatiga ocular en sesiones de trabajo prolongadas.

### Paleta de Colores

| Código Hex                                                              | Nombre         | Uso Principal                                            |
|-------------------------------------------------------------------------| -------------- | -------------------------------------------------------- |
| #F26E22  | Naranja Activo | Botones CTA primarios, íconos de acción, highlights      |
| #F25922                                                                 | Naranja Alerta | Alertas de fuga, estados críticos, indicadores de riesgo |
| #A5B1BF                                                                 | Gris Acero     | Bordes, separadores, texto secundario, íconos inactivos  |
| #F8F8FB                                                                 | Blanco Hielo   | Fondo general, background de cards, superficie base      |
| #FFFFFF                                                                 | Blanco Puro    | Texto sobre fondos oscuros, iconografía en navy/naranja  |
| #111111                                                                 | Negro Suave    | Textos principales de alta legibilidad sobre fondo claro |
| #555F6E                                                                 | Gris Medio     | Texto de cuerpo, etiquetas, metadatos                    |
| #E8ECF                                                                  | Gris Claro     | Fondos de filas alternas en tablas, separadores sutiles  |

### Sistema de Espaciado

* **4px (0.25rem):**
  Espaciado mínimo entre elementos relacionados (íconos + texto, label + input).

* **8px (0.5rem):**
  Padding interno de badges, chips y etiquetas compactas.

* **12px (0.75rem):**
  Espaciado entre líneas de texto en tarjetas y listas.

* **16px (1rem):**
  Padding estándar de cards, campos de formulario y contenedores base.

* **24px (1.5rem):**
  Separación entre secciones dentro de un módulo o tarjeta grande.

* **32px (2rem):**
  Espacio entre tarjetas, widgets del dashboard y módulos principales.

* **48–64px (3–4rem):**
  Margen entre secciones de página completa o bloques de contenido diferenciado.

---

### Principios de Layout

* **Grid de 12 columnas:**
  Layout responsivo basado en 12 columnas con gutter de 16–24px.

    * Móvil: 4 columnas
    * Tablet: 8 columnas
    * Escritorio: 12 columnas

* **Ancho máximo de contenido:**
  1280px para contenedores de página completa. Centrado con márgenes laterales automáticos.

* **Sidebar fijo:**
  Navegación lateral de 240–260px de ancho. Colapsable a 64px en modo compacto para mayor área de trabajo.

* **Cards y tarjetas:**
  Border radius de 10–12px.
  Sombra suave: `box-shadow: 0 2px 8px rgba(23,45,64, 0.08)`.
  Sin bordes duros en fondos claros.

* **Tablas de datos:**
  Filas de altura mínima 48px.
  Alternar filas entre `#FFFFFF` y `#F8F8FB`.
  Header de tabla en `#172D40` con texto blanco.

* **Formularios:**
  Labels sobre los campos (no inline).
  Campos con `border: 1px solid #A5B1BF`.
  Focus state: borde naranja (`#F26E22`) + sombra sutil.

* **Jerarquía de información:**
  Seguir el patrón: **título de sección → subtítulo → contenido → acciones secundarias**.
  Nunca mezclar niveles de jerarquía en una misma área.

---

### Botones

* **Primario (CTA principal):**
  Fondo `#F26E22`, texto blanco, border-radius 8px, padding 12×24px.
  Hover: `#F25922`.
  Uso: *"Registrar entrada"*, *"Guardar"*, *"Confirmar"*.

* **Secundario:**
  Borde `1.5px #172D40`, texto `#172D40`, fondo transparente.
  Hover: fondo `#172D40` + texto blanco.
  Uso: acciones de soporte.

* **Destructivo / Alerta:**
  Fondo `#EF4444`, texto blanco.
  Uso exclusivo: eliminar, cancelar entrega o confirmar alerta crítica.

* **Deshabilitado:**
  Fondo `#E8ECF0`, texto `#A5B1BF`.
  No clicable, cursor `not-allowed`.

---

### Badges y Estados

* **Operativo / Normal:**
  Fondo verde claro (`#DCFCE7`) + texto (`#15803D`).
  Uso: balones en buen estado, almacén sin alertas.

* **En ruta / Activo:**
  Fondo naranja claro (`#FEF3C7`) + texto (`#B45309`).
  Uso: entregas en curso, sensores activos.

* **Alerta / Advertencia:**
  Fondo naranja intenso (`#F25922`) + texto blanco.
  Uso: detecciones de gas, retrasos o anomalías.

* **Error / Crítico:**
  Fondo rojo (`#FEE2E2`) + texto (`#DC2626`).
  Uso: fugas confirmadas, pérdidas de conexión o balones descartados.

---

### Alertas y Notificaciones

* **Estilo:**
  Banner en la parte superior de pantalla o panel lateral de notificaciones.
  No interrumpir el flujo de trabajo (evitar modales para alertas informativas).

* **Urgencia alta (fuga detectada):**
  Banner rojo o naranja intenso con ícono de advertencia + texto breve + botón *"Ver detalle"*.
  Sonido de alerta opcional en escritorio.

* **Urgencia media (inventario bajo):**
  Banner amarillo-naranja informativo.
  Puede descartarse manualmente.

* **Urgencia baja (recordatorio):**
  Toast notification en esquina inferior derecha.
  Desaparece automáticamente en 5 segundos.

---

### Accesibilidad

* **Contraste de texto:**
  Mínimo **4.5:1** para texto normal; **3:1** para texto grande (18px+ bold).
  El naranja (`#F26E22`) sobre blanco cumple este estándar.

* **Contraste de componentes UI:**
  Mínimo **3:1** para bordes de campos, íconos funcionales y elementos interactivos.

* **No solo color:**
  Nunca comunicar información únicamente mediante color.
  Acompañar con ícono, texto o patrón (especialmente en alertas y errores).

* **Tamaño de toque mínimo:**
  **44×44px** para elementos interactivos en dispositivos táctiles.

* **Foco visible:**
  Estado focus claramente visible con outline naranja o borde grueso `#F26E22` de 2–3px.
  No eliminar el outline nativo sin reemplazarlo.

* **Textos alternativos:**
  Todos los íconos funcionales y gráficos del dashboard deben incluir atributo `aria-label` descriptivo.


## 4.1.2. Web Style Guidelines

### Dispositivos Soportados

| Dispositivo | Breakpoint  | Columnas    | Comportamiento                                                |
| ----------- | ----------- | ----------- | ------------------------------------------------------------- |
| Mobile      | < 640px     | 4 columnas  | Navegación hamburger, layout apilado, cards de ancho completo |
| Tablet      | 640–1023px  | 8 columnas  | Sidebar colapsable, cards en 2 columnas, navegación visible   |
| Desktop     | 1024–1279px | 12 columnas | Layout completo, sidebar fija, cards en 3 columnas            |
| Wide        | ≥ 1280px    | 12 columnas | Ancho máximo 1280px centrado, márgenes laterales automáticos  |

---

### Principios Responsive

* **Mobile-first:**
  Diseñar primero para móvil y agregar complejidad visual conforme aumenta el viewport.

* **Navegación adaptativa:**
  Menú hamburger en móvil (< 640px); navegación completa en tablet y desktop.

* **Imágenes responsivas:**
  Usar `srcset` y tamaños relativos. Nunca fijar anchos en píxeles absolutos.

* **Tipografía fluida:**
  Escala mediante `clamp()` o clases responsivas.

* **Touch targets:**
  Mínimo **44×44px** en móvil.

* **Dashboard en tablet:**
  El dashboard de métricas en tiempo real se simplifica en móvil y se muestra completo en tablet y desktop.

---

### Comunicación con el Usuario

* **Confiable y profesional:**
  Qlic opera en contextos críticos (fugas, presión, temperatura). El lenguaje transmite autoridad sin ser distante.

* **Cercano y empático:**
  Comunicación directa con el usuario, enfocada en prevenir riesgos y optimizar su trabajo.

* **Claro y directo:**
  Cada mensaje comunica una sola idea. Las alertas indican claramente qué ocurrió y qué hacer.

* **Orientado a beneficios tangibles:**
  Enfatiza resultados: prevención de fugas, reducción de costos, cumplimiento y seguridad.

* **Sin jerga técnica en UI:**
  Métricas técnicas deben incluir contexto visual (colores, estados) para usuarios no expertos.

---

### Escala Tipográfica Web

| Elemento         | Fuente  | Tamaño  | Peso         | Line-height | Uso                                      |
| ---------------- | ------- | ------- | ------------ | ----------- | ---------------------------------------- |
| Display / Hero   | Poppins | 48–56px | 700 Bold     | 1.1         | Título principal de hero section         |
| H1 Página        | Poppins | 36–40px | 700 Bold     | 1.2         | Encabezados principales                  |
| H2 Sección       | Poppins | 28–32px | 600 SemiBold | 1.3         | Subtítulos de sección                    |
| H3 Card          | Poppins | 20–24px | 600 SemiBold | 1.4         | Títulos de cards y widgets               |
| Body Large       | Roboto  | 18px    | 400 Regular  | 1.6         | Descripción hero, secciones informativas |
| Body Base        | Roboto  | 16px    | 400 Regular  | 1.6         | Párrafos generales                       |
| Body Small       | Roboto  | 14px    | 400 Regular  | 1.5         | Metadatos, etiquetas                     |
| Caption          | Roboto  | 12px    | 400 Regular  | 1.4         | Tooltips, notas legales                  |
| Button / Label   | Poppins | 14–16px | 600 SemiBold | 1.0         | Botones, navegación                      |
| Precio / Métrica | Poppins | 32–40px | 700 Bold     | 1.1         | Métricas y precios                       |

---

### Sistema de Colores

| Hex     | Nombre          | Rol        | Uso Principal                 |
| ------- | --------------- | ---------- | ----------------------------- |
| #0C4AFD | Azul Principal  | Primario   | Header, navegación, identidad |
| #0A1F6E | Azul Oscuro     | Secundario | Títulos, textos principales   |
| #3B82F6 | Azul Medio      | CTA        | Botones interactivos          |
| #22C55E | Verde           | Acento     | Botón Send, estado normal     |
| #0F0F0F | Negro           | Texto      | Encabezados principales       |
| #374151 | Gris Oscuro     | Texto      | Párrafos                      |
| #6B7280 | Gris Medio      | Secundario | Metadatos                     |
| #F3F4F6 | Gris Claro      | Fondo      | Secciones alternas            |
| #F9FAFB | Blanco Suave    | Superficie | Cards, inputs                 |
| #FFFFFF | Blanco Puro     | Base       | Fondo principal               |
| #E5E7EB | Gris Borde      | Neutro     | Bordes, divisores             |
| #EFF6FF | Azul Muy Claro  | Fondo      | Highlights informativos       |
| #F0FDF4 | Verde Muy Claro | Fondo      | Badge tiempo real             |

---

### Reglas de Uso de Color

* **Un botón verde por página:**
  Exclusivo para “Send” y estado en tiempo real.

* **Azul dominante:**
  Presente en navegación y elementos clave.

* **Fondos alternativos:**
  Uso de blanco y gris claro para ritmo visual.

* **Contraste mínimo WCAG AA:**
  Ratio mínimo 4.5:1.

* **Restricción de paleta:**
  No usar colores fuera de la guía.

---

### Sistema de Espaciado (Tokens)

| Token    | px   | rem     | Uso típico                |
| -------- | ---- | ------- | ------------------------- |
| space-1  | 4px  | 0.25rem | Ícono + texto inline      |
| space-2  | 8px  | 0.5rem  | Badges, chips             |
| space-3  | 12px | 0.75rem | Listas, navegación        |
| space-4  | 16px | 1rem    | Cards, formularios        |
| space-6  | 24px | 1.5rem  | Entre cards               |
| space-8  | 32px | 2rem    | Sub-secciones             |
| space-12 | 48px | 3rem    | Secciones principales     |
| space-16 | 64px | 4rem    | Hero, bloques importantes |
| space-24 | 96px | 6rem    | Separación máxima         |

---

### Botones (Web)

* **Padding:**

  * Medium: 12px 24px
  * Small: 10px 20px
  * Large: 16px 32px

* **Border-radius:**
  8px

* **Tipografía:**
  Poppins SemiBold 600, 14–16px, letter-spacing: 0.01em

* **Hover:**
  Opacidad 90% o aclarado 10% (150ms ease)

* **Focus:**
  Outline 3px con offset 2px

* **Loading:**
  Spinner + texto *“Cargando…”*, botón deshabilitado
