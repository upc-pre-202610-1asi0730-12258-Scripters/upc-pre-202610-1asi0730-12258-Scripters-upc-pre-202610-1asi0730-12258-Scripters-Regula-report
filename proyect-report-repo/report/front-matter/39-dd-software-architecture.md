# 4.6. Domain-Driven Software Architecture

## 4.6.1. Design-Level EventStorming

### Introducción
El Design-Level EventStorming se realizó con el objetivo de refinar el modelo del dominio del sistema **Regula**, pasando de una visión general (Big Picture) a un nivel de detalle orientado a diseño, siguiendo principios de Domain-Driven Design (DDD).

Esta sesión permitió profundizar en los procesos críticos del negocio, identificando eventos, comandos, reglas de negocio y estructuras internas del sistema, con el fin de construir una base sólida para la implementación.

La sesión tuvo una duración aproximada de **1.5 horas**, cumpliendo con la recomendación de concentrar esfuerzos sin extender innecesariamente el proceso.

Se utilizó la herramienta **Miro** para modelar colaborativamente el flujo completo.

---

### Objetivo del Design-Level EventStorming
El propósito principal fue:

- Refinar los *bounded contexts* identificados previamente
- Modelar procesos complejos del negocio con mayor detalle
- Traducir procesos reales a estructuras de software (DDD)
- Servir como puente entre análisis y desarrollo

Este tipo de EventStorming se enfoca en:

- Subdominios críticos
- Lógica de negocio compleja
- Preparación para implementación

---

### Agenda de la sesión

#### 1. Definición del alcance
Se seleccionaron los procesos más críticos:

- Monitoreo de fugas (core)
- Inventario de balones (core)
- Distribución (core)
- Cobranzas (soporte)

---

#### 2. Identificación de Domain Events
Se definieron los eventos que representan hechos importantes del sistema:

- Gas Leak Detected
- Alert Generated
- Cylinder Entered Inventory
- Cylinder Exited Inventory
- Delivery Assigned
- Payment Received

---

#### 3. Definición de Commands
Se agregaron los comandos que generan los eventos:

- Detect Gas → Gas Leak Detected
- Register Entry → Cylinder Entered Inventory
- Assign Delivery → Delivery Assigned
- Register Payment → Payment Received

---

#### 4. Identificación de Actores
Se definieron los responsables de ejecutar los comandos:

- Supervisor
- Administrador
- Distribuidor
- Repartidor
- Sistema IoT (externo)

---

#### 5. Definición de Policies
Se modelaron automatizaciones del sistema:

- Si ocurre **Gas Leak Detected** → generar **Alert Generated**
- Si ocurre **Payment Received** → actualizar deuda
- Si ocurre **Delivery Delayed** → notificar supervisor

---

#### 6. Identificación de Aggregates
Se agruparon eventos y reglas en agregados:

- Inventory
- Safety
- Delivery
- Billing

Esto permitió organizar la lógica del sistema y mantener consistencia.

---

#### 7. Read Models y UX
Se definieron vistas que el usuario necesita:

- Dashboard principal (alertas + stock)
- Lista de entregas en tiempo real
- Historial de movimientos de balones
- Vista de deudas por cliente

También se relacionaron con mockups previamente diseñados.

---

#### 8. Sistemas externos
Se identificaron integraciones:

- Sensores IoT → detección de gas
- GPS → seguimiento de vehículos

---

#### 9. Reglas de negocio
Se definieron reglas clave:

- Un balón defectuoso no puede ser vendido
- Una alerta debe ser atendida antes de cerrarse
- No se puede registrar salida sin stock disponible

---

### Bounded Contexts

Se reorganizó el sistema en subdominios siguiendo arquitectura SaaS:

#### Core Domains
- Service Execution and Monitoring (monitoreo de fugas y alertas)
- Resource and Asset Management (gestión de balones e inventario)
- Service Design and Planning (distribución y logística)

#### Supporting Domains
- Dashboard and Analytics
- Subscriptions and Payment Management
- Loyalty and Engagement (cobranzas y clientes)

#### Generic Domains
- Identity and Access Management
- Profiles and Preferences Management

---

### Highlighted Core

Se identificaron los subdominios más críticos:

- Monitoreo de fugas (Safety)
- Control de inventario (Inventory)
- Distribución (Delivery)

Estos representan la principal ventaja competitiva del sistema.

---

### Resultados de la sesión

La sesión permitió:

- Refinar el modelo del dominio con alto nivel de detalle
- Identificar claramente responsabilidades del sistema
- Reducir ambigüedad en procesos
- Definir base para arquitectura y desarrollo

Además, se logró una comprensión compartida del dominio entre todos los integrantes del equipo.

---

### Evidencia

Se incluyen capturas de la sesión en Miro que muestran:

- Flujo completo de eventos
- Relación entre comandos y actores
- Agrupación en agregados
- Delimitación de bounded contexts  