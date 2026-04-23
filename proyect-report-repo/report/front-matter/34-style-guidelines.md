# Capítulo IV: Product Design
# 4.1. Style Guidelines

## 4.1.1. General Style Guidelines

La voz de Regula debe reflejar los valores del producto: seguridad, eficiencia y confianza. Cada mensaje, etiqueta, alerta o texto de interfaz debe estar alineado con los siguientes principios:

- **Confiable y profesional:** Regula opera en contextos de alta responsabilidad (seguridad industrial, control de inventario, detección de fugas). El lenguaje debe transmitir solidez técnica y respaldo institucional, evitando ambigüedades.
- **Claro y directo:** Los usuarios son operarios, supervisores y distribuidores con alta carga operativa. Los mensajes deben ser concisos, sin tecnicismos innecesarios. Las alertas y notificaciones deben ser inmediatamente comprensibles.
- **Orientado a la acción:** Las instrucciones, botones y CTAs deben incitar a actuar de forma natural. Ejemplos: "Registrar entrada", "Ver alerta", "Confirmar entrega", "Monitorear almacén".
- **Cercano pero no informal:** Regula habla de tú a tú con el usuario, reconociendo el contexto operativo de su trabajo. El tono no es corporativo frío ni coloquial excesivo; es empático y funcional.
- **Enfocado en beneficios tangibles:** Los mensajes destacan resultados concretos: reducción de pérdidas, mayor seguridad, control de inventario en tiempo real, trazabilidad de repartos.

---

## Tipografía

La tipografía de Regula prioriza la legibilidad funcional en pantalla, especialmente en contextos de trabajo donde los usuarios consultan información rápida de tableros, alertas y registros.

### Familia tipográfica principal: Inter

Inter es una fuente sans-serif diseñada específicamente para interfaces digitales. Ofrece excelente legibilidad a tamaños pequeños y medios, siendo ideal para dashboards, formularios y textos operativos.

| Elemento | Fuente | Tamaño | Peso | Uso Principal |
|---|---|---|---|---|
| H1 – Título de página | Inter | 32px / 2rem | Bold 700 | Nombres de sección, pantalla principal del dashboard |
| H2 – Subtítulo | Inter | 24px / 1.5rem | SemiBold 600 | Subtítulos de módulos, encabezados de tarjetas |
| H3 – Encabezado | Inter | 20px / 1.25rem | SemiBold 600 | Títulos de widgets, tablas y formularios |
| Body – Cuerpo | Inter | 16px / 1rem | Regular 400 | Textos descriptivos, párrafos, etiquetas de campo |
| Small – Secundario | Inter | 14px / 0.875rem | Regular 400 | Metadatos, timestamps, textos de apoyo |
| Caption – Pie | Inter | 12px / 0.75rem | Medium 500 | Leyendas de gráficas, tooltips, notas |
| Label – CTA | Inter | 14–16px | Bold 700 | Botones de acción, badges de estado, alertas |

### Fuente monoespaciada: JetBrains Mono

Uso específico: Códigos de balón, IDs de operación, timestamps técnicos y datos de sensores IoT donde se requiere precisión visual.

### Jerarquía visual

- **Contraste de tamaño:** Los títulos deben ser al menos 1.5× el tamaño del cuerpo para generar jerarquía clara.
- **Interlineado:** 1.5× el tamaño de fuente para cuerpo; 1.2× para títulos y etiquetas compactas.
- **Longitud de línea:** Máximo 75 caracteres por línea para garantizar legibilidad óptima en pantalla.

---

## Colores

| Color | Hex | Nombre | Uso |
|---|---|---|---|
| 🟠 | `#F26E22` | Naranja Activo | Botones CTA primarios, íconos de acción, highlights |
| 🔶 | `#F25922` | Naranja Alerta | Alertas de fuga, estados críticos, indicadores de riesgo |
| 🩶 | `#A5B1BF` | Gris Acero | Bordes, separadores, texto secundario, íconos inactivos |
| ⬜ | `#F8F8FB` | Blanco Hielo | Fondo general, background de cards, superficie base |
| ⬜ | `#FFFFFF` | Blanco Puro | Texto sobre fondos oscuros, iconografía en navy/naranja |
| ⬛ | `#111111` | Negro Suave | Textos principales de alta legibilidad sobre fondo claro |
| 🔘 | `#555F6E` | Gris Medio | Texto de cuerpo, etiquetas, metadatos |
| 🔲 | `#E8ECF0` | Gris Claro | Fondos de filas alternas en tablas, separadores sutiles |

### Descripción de colores

- **Azul Marino Profundo (`#172D40`):** Color primario de marca. Transmite confianza, control y seriedad técnica. Se usa en header, sidebar, títulos principales y elementos de navegación. Es el color ancla de la identidad de Regula.
- **Naranja Activo (`#F26E22`):** Acento principal de energía y acción. Representa dinamismo, urgencia positiva y visibilidad operativa. Ideal para botones CTA primarios, íconos destacados y elementos interactivos de primer nivel.
- **Naranja Alerta (`#F25922`):** Variante más intensa del naranja. Se usa para alertas de mayor urgencia, indicadores de riesgo moderado-alto y estados activos críticos como detección de fuga o estado "en ruta".
- **Gris Acero (`#A5B1BF`):** Color neutro frío. Complementa al azul marino en elementos secundarios: bordes, separadores, textos de apoyo, íconos inactivos y fondos de tarjetas neutras.
- **Blanco Hielo (`#F8F8FB`):** Fondo principal de la interfaz. Proporciona limpieza visual, contraste suave y reduce la fatiga ocular en sesiones de trabajo prolongadas para un tono más respetuoso.

---

## Espaciado

| Valor | Rem | Uso |
|---|---|---|
| 4px | 0.25rem | Espaciado mínimo entre elementos relacionados (íconos + texto, label + input) |
| 8px | 0.5rem | Padding interno de badges, chips y etiquetas compactas |
| 12px | 0.75rem | Espaciado entre líneas de texto en tarjetas y listas |
| 16px | 1rem | Padding estándar de cards, campos de formulario y contenedores base |
| 24px | 1.5rem | Separación entre secciones dentro de un módulo o tarjeta grande |
| 32px | 2rem | Espacio entre tarjetas, widgets del dashboard y módulos principales |
| 48–64px | 3–4rem | Margen entre secciones de página completa o bloques de contenido diferenciado |

---

## Layout

### Principios de Layout

- **Grid de 12 columnas:** Layout responsivo basado en 12 columnas con gutter de 16–24px. En móvil: 4 columnas; tablet: 8; escritorio: 12.
- **Ancho máximo de contenido:** 1280px para contenedores de página completa. Centrado con márgenes laterales automáticos.
- **Sidebar fijo:** Navegación lateral de 240–260px de ancho. Colapsable a 64px en modo compacto para mayor área de trabajo.
- **Cards y tarjetas:** Border radius de 10–12px. Sombra suave: `box-shadow: 0 2px 8px rgba(23,45,64, 0.08)`. Sin bordes duros en fondos claros.
- **Tablas de datos:** Filas de altura mínima 48px. Alternar filas entre `#FFFFFF` y `#F8F8FB`. Header de tabla en `#172D40` con texto blanco.
- **Formularios:** Labels sobre los campos (no inline). Campos con `border: 1px solid #A5B1BF`. Focus state: border naranja (`#F26E22`) + sombra sutil.
- **Jerarquía de información:** Seguir el patrón: título de sección → subtítulo → contenido → acciones secundarias. Nunca mezclar niveles de jerarquía en una misma área.

---

## Componentes

### Botones

- **Primario (CTA principal):** Fondo `#F26E22`, texto blanco, `border-radius: 8px`, padding `12×24px`. Hover: `#F25922`. Para acciones principales como "Registrar entrada", "Guardar", "Confirmar".
- **Secundario:** Borde `1.5px #172D40`, texto `#172D40`, fondo transparente. Hover: fondo `#172D40` + texto blanco. Para acciones de soporte.
- **Destructivo / Alerta:** Fondo `#EF4444`, texto blanco. Exclusivamente para eliminar, cancelar entrega o confirmar alerta crítica.
- **Deshabilitado:** Fondo `#E8ECF0`, texto `#A5B1BF`. No clicable, `cursor: not-allowed`.

### Badges y estados

| Estado | Fondo | Texto | Uso |
|---|---|---|---|
| Operativo / Normal | `#DCFCE7` | `#15803D` | Balones en buen estado, almacén sin alertas |
| En ruta / Activo | `#FEF3C7` | `#B45309` | Entregas en curso, sensores activos |
| Alerta / Advertencia | `#F25922` | Blanco | Detecciones de gas, retrasos o anomalías |
| Error / Crítico | `#FEE2E2` | `#DC2626` | Fugas confirmadas, pérdidas de conexión, balones descartados |

### Alertas y notificaciones

- **Estilo:** Banner en la parte superior de pantalla o panel lateral de notificaciones. Sin interrumpir el flujo de trabajo (no modales para alertas informativas).
- **Urgencia alta (fuga detectada):** Banner rojo o naranja intenso con ícono de advertencia + texto breve + botón "Ver detalle". Sonido de alerta opcional en versión de escritorio.
- **Urgencia media (inventario bajo):** Banner amarillo-naranja informativo. Puede descartarse manualmente.
- **Urgencia baja (recordatorio):** Toast notification en esquina inferior derecha. Desaparece automáticamente en 5 segundos.

---

## Accesibilidad

- **Contraste de texto:** Mínimo 4.5:1 para texto normal; 3:1 para texto grande (18px+ bold). El naranja (`#F26E22`) sobre blanco cumple este estándar.
- **Contraste de componentes UI:** Mínimo 3:1 para bordes de campos, íconos funcionales y elementos interactivos.
- **No solo color:** Nunca comunicar información únicamente mediante color. Acompañar siempre con ícono, texto o patrón (especialmente en alertas y estados de error).
- **Tamaño de toque mínimo:** 44×44px para elementos interactivos en dispositivos táctiles (tablets de campo, móviles).
- **Foco visible:** Estado focus claramente visible con outline naranja o borde grueso `#F26E22` de 2–3px. No eliminar el outline nativo sin reemplazarlo.
- **Textos alternativos:** Todos los íconos funcionales y gráficos del dashboard deben tener atributo `aria-label` descriptivo.

# 4.1.2. Web Style Guidelines

## Dispositivos soportados

| Dispositivo | Breakpoint | Columnas | Comportamiento |
|---|---|---|---|
| Mobile | < 640px | 4 columnas | Navegación hamburger, layout apilado, cards de ancho completo |
| Tablet | 640–1023px | 8 columnas | Sidebar colapsable, cards en 2 columnas, navegación visible |
| Desktop | 1024–1279px | 12 columnas | Layout completo, sidebar fija, cards en 3 columnas |
| Wide | ≥ 1280px | 12 columnas | Ancho máximo 1280px centrado, márgenes laterales automáticos |

- **Mobile-first:** Diseñar primero para móvil y agregar complejidad visual conforme aumenta el viewport.
- **Navegación adaptativa:** Menú hamburger en móvil (< 640px); navegación horizontal completa en tablet y desktop.
- **Imágenes responsivas:** Usar `srcset` y tamaños relativos. Nunca fijar anchos en píxeles absolutos para imágenes de contenido.
- **Tipografía fluida:** Los tamaños de fuente escalan con el viewport usando `clamp()` o clases responsivas de utilidad.
- **Touch targets:** Todo elemento interactivo debe tener mínimo 44×44px de área táctil en móvil.
- **Dashboard en tablet:** El dashboard de métricas de gas en tiempo real se oculta o simplifica en móvil; se muestra completo en tablet y desktop.

---

## Comunicación con el usuario

- **Confiable y profesional:** Qlic opera en contextos donde los datos son críticos (fugas, presión, temperatura). El lenguaje transmite solidez técnica sin ser frío o distante. Los usuarios confían en los datos porque el sistema habla con autoridad.
- **Cercano y empático:** Se habla de tú a tú con el usuario. Se reconocen sus necesidades reales —prevenir desperdicios, evitar daños— y se les habla en consecuencia. Sin tecnicismos innecesarios.
- **Claro y directo:** Evitar ambigüedades. Cada mensaje comunica una cosa. Las alertas son inmediatamente comprensibles: el usuario sabe qué pasó y qué hacer.
- **Orientado a beneficios tangibles:** Los textos destacan resultados concretos para hogares (prevenir fugas) y negocios (auditorías, cumplimiento, reducción de costos).
- **Sin jerga técnica en UI:** Términos como volumen o bar pueden aparecer en métricas, pero deben acompañarse de contexto (ej. indicadores de estado verde/amarillo/rojo) para que usuarios no técnicos también los entiendan.

---

## Tipografía

| Elemento | Fuente | Tamaño | Peso | Line-height | Uso |
|---|---|---|---|---|---|
| Display / Hero | Poppins | 48–56px | 700 Bold | 1.1 | Título principal hero section |
| H1 Página | Poppins | 36–40px | 700 Bold | 1.2 | Encabezados de sección principal |
| H2 Sección | Poppins | 28–32px | 600 SemiBold | 1.3 | Subtítulos de sección y módulo |
| H3 Card | Poppins | 20–24px | 600 SemiBold | 1.4 | Títulos de cards y widgets |
| Body Large | Roboto | 18px | 400 Regular | 1.6 | Descripción hero y about us |
| Body Base | Roboto | 16px | 400 Regular | 1.6 | Párrafos generales, contenido |
| Body Small | Roboto | 14px | 400 Regular | 1.5 | Metadatos, etiquetas, pie de card |
| Caption | Roboto | 12px | 400 Regular | 1.4 | Leyendas, tooltips, notas legales |
| Button / Label | Poppins | 14–16px | 600 SemiBold | 1.0 | Botones CTA, badges, navegación |
| Precio / Métrica | Poppins | 32–40px | 700 Bold | 1.1 | Planes de precios, métricas dashboard |

---

## Colores

### Descripción de colores

- **Azul Principal (`#0C4AFD`):** Color primario de marca. Transmite tecnología, confianza y precisión. Presente en el header, navegación, botones CTA generales, íconos de acción y elementos de identidad de marca.
- **Azul Oscuro (`#0A1F6E`):** Para textos de alto contraste sobre fondos claros, títulos principales y elementos de marca de máxima jerarquía. Confiere seriedad y autoridad.
- **Azul Medio (`#3B82F6`):** Versión accesible del azul para la mayoría de botones CTA interactivos: "Get Started", "Choose Plan", hover states y enlaces activos.
- **Verde (`#22C55E`):** Color de acento para éxito y acción específica. Usado exclusivamente en el botón "Send" del formulario de contacto, el badge "Real-Time Water Monitoring", e indicadores de estado operativo normal.
- **Negro (`#0F0F0F`):** Para títulos de sección, texto principal de máxima legibilidad y encabezados de alto impacto. Garantiza contraste AAA sobre fondos claros.
- **Gris Oscuro (`#374151`):** Para cuerpo de texto general, párrafos, descripciones de cards y la mayoría del contenido textual de la plataforma.
- **Gris Medio (`#6B7280`):** Para textos secundarios, metadatos, timestamps, textos de placeholder y contenido de menor jerarquía visual.
- **Gris Claro (`#F3F4F6`):** Para fondos de sección alternos, filas pares en tablas, fondos de cards neutras y separadores visuales sutiles.
- **Blanco (`#FFFFFF`):** Fondo principal de la plataforma, superficie de cards, modales y paneles. También para texto sobre fondos oscuros (header azul, botones primarios).

### Paleta de colores

| Color | Hex | Nombre | Rol | Uso Principal |
|---|---|---|---|---|
| 🔵 | `#0C4AFD` | Azul Principal | Primario | Header, navegación, elementos de marca, badge activo |
| 🟦 | `#0A1F6E` | Azul Oscuro | Secundario | Títulos de sección, texto principal de alta jerarquía |
| 💙 | `#3B82F6` | Azul Medio | CTA General | Botones: Get Started, Choose Plan, CTAs interactivos |
| 🟢 | `#22C55E` | Verde | Acento | Botón Send (formulario), badge Real-Time, estado normal |
| ⬛ | `#0F0F0F` | Negro | Texto | Títulos H1/H2, encabezados de sección, texto hero |
| 🔘 | `#374151` | Gris Oscuro | Texto | Cuerpo de texto general, párrafos, descripciones |
| 🔲 | `#6B7280` | Gris Medio | Secundario | Textos de apoyo, metadatos, placeholders, timestamps |
| ⬜ | `#F3F4F6` | Gris Claro | Fondo | Secciones alternas, filas de tabla, fondos neutros |
| ⬜ | `#F9FAFB` | Blanco Suave | Superficie | Fondo de cards, inputs, paneles de contenido |
| ⬜ | `#FFFFFF` | Blanco Puro | Base | Fondo principal del sitio, modales, texto en oscuros |
| 🔳 | `#E5E7EB` | Gris Borde | Neutro | Bordes de cards, inputs, divisores, separadores |
| 🔷 | `#EFF6FF` | Azul Muy Claro | Fondo acento | Fondos de badges azules, highlights informativos |
| 🟩 | `#F0FDF4` | Verde Muy Claro | Fondo acento | Fondo del badge en tiempo real |

### Reglas de uso del color

- **Un botón verde por página:** El verde (`#22C55E`) es exclusivo del botón "Send" del formulario de contacto y del badge de estado en tiempo real. No usar verde en otros botones o CTAs para mantener su significado semántico único.
- **Azul como color dominante:** El azul en sus tres variantes (principal, oscuro, medio) es el color ancla de la marca. Debe estar presente en el header y navegación en toda la plataforma.
- **Fondos alternativos:** Alternar entre fondo blanco (`#FFFFFF`) y gris muy claro (`#F3F4F6`) entre secciones de la landing para crear ritmo visual sin usar colores de marca en fondos grandes.
- **Contraste mínimo WCAG AA:** Todo texto sobre fondo coloreado debe cumplir ratio mínimo 4.5:1. El texto blanco sobre azul principal (`#0C4AFD`) cumple este estándar.
- **No usar colores fuera de paleta:** Ningún elemento de UI debe introducir colores no definidos en esta guía sin aprobación del equipo de diseño.

---

## Espaciado

| Token | Valor px | Valor rem | Uso típico |
|---|---|---|---|
| space-1 | 4px | 0.25rem | Separación mínima entre ícono y texto inline |
| space-2 | 8px | 0.5rem | Padding interno de badges, chips y tags |
| space-3 | 12px | 0.75rem | Gap entre elementos de lista, íconos y labels en nav |
| space-4 | 16px | 1rem | Padding estándar de cards, campos de formulario, contenedores |
| space-6 | 24px | 1.5rem | Gap entre cards dentro de una sección, padding de sección pequeña |
| space-8 | 32px | 2rem | Separación entre subsecciones, padding lateral de contenedores |
| space-12 | 48px | 3rem | Margen entre secciones principales de la landing page |
| space-16 | 64px | 4rem | Padding superior e inferior de secciones hero y de impacto |
| space-24 | 96px | 6rem | Separación máxima entre bloques de contenido diferenciado |

---

## Botones

- **Padding:** `12px 24px` (medium) · `10px 20px` (small) · `16px 32px` (large)
- **Border-radius:** `8px` para todos los botones. Consistencia en toda la plataforma.
- **Font:** Poppins SemiBold 600, 14–16px, `letter-spacing: 0.01em`
- **Hover state:** Reducir opacidad al 90% o aclarar 10% el color base. Transición `150ms ease`.
- **Focus state:** Outline `3px` con offset `2px` en el color del botón al 40% de opacidad. Nunca eliminar sin reemplazar.
- **Loading state:** Spinner dentro del botón, texto cambia a "Cargando...", botón deshabilitado.
