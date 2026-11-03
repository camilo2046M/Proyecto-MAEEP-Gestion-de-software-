# 🌍 Plataforma de Apoyo Educativo para Estudiantes de Escuelas Públicas (Caso 4)

![Estado del Proyecto](https://img.shields.io/badge/Avance_Global-35%25_(Fase_3_Dise%C3%B1o)-blue)
![SPI](https://img.shields.io/badge/SPI-1.00_(En_Fecha)-brightgreen)
![CPI](https://img.shields.io/badge/CPI-0.98_(En_Rango)-brightgreen)
![Presupuesto](https://img.shields.io/badge/Presupuesto_Base-%24147%2C895_USD-informational)
![Arquitectura](https://img.shields.io/badge/Arquitectura-Offline--First_%7C_2G%2F3G-orange)

Repositorio oficial de gestión, gobernanza (PMBOK) e integración técnica (DevOps / Arquitectura) del proyecto **"Plataforma Web y Móvil de Apoyo Educativo"**, desarrollado por la consultora **Prompt Labs** en alianza con el **Distrito Escolar** y una **ONG Internacional** para mitigar la deserción escolar y mejorar el rendimiento en ciencias y matemáticas en zonas de alta vulnerabilidad del África subsahariana.

---

## 📋 Ficha Técnica y Gobernanza del Proyecto

| Atributo | Detalle Oficial |
| :--- | :--- |
| **Organización Desarrolladora** | Prompt Labs (Oficina de Proyectos e Ingeniería de Software) |
| **Cliente / Patrocinadores** | Dra. Amina Diallo (Directora de Educación Distrital) & Johnathan Smith (Director ONG Internacional) |
| **Asignatura y Sección** | GPY1102 - Gestión de Proyectos de Software (Sección 001D) |
| **Docente** | Juan Hernández Aliaga |
| **Duración y Horizonte** | 475 días hábiles (10 Hitos críticos inamovibles | Cierre: 11/06/2027) |
| **Presupuesto Total Aprobado** | $147,895 USD (Incluye Reserva de Contingencia del 10%: $13,445 USD) |
| **Estándares Aplicados** | Guía del PMBOK (6.ª y 7.ª ed.), ISO/IEC 25010, WCAG 2.1 Nivel AA, GDPR (Protección Infantil) |

### 👥 Equipo Directivo y Técnico (Prompt Labs)
* **Benjamín Lizama** — *Project Manager (PM)*: Gestión integral del proyecto, control de líneas base (alcance, cronograma, costos) y gobernanza de riesgos y cambios (CCB).
* **Camilo Mena** — *Líder Técnico y Arquitecto de Software*: Definición de arquitectura *Offline-First*, contratos de integración (APIs/Webhooks), modelado de datos y supervisión de desarrollo.
* **Lucciano Martínez** — *Líder de Aseguramiento de Calidad (QA) y Procesos*: Plan de pruebas integrales, certificación de estrés en redes 2G/3G ($\le 250\text{ KB}$ / $< 2\text{ s}$) y monitoreo de KPIs técnicos.

---

## 🎯 Acceso Rápido por Evaluación (Índice para Revisión Docente)

Para facilitar la revisión académica sin perder la estructura profesional de industria, a continuación se enlazan directamente los entregables correspondientes a cada hito evaluativo:

### 📌 Evaluación Parcial N°1: Planificación y Factores Ambientales
* 📄 **[Informe Resumen Ejecutivo - Planificación](./01-executive-reports/01-resumen-ejecutivo-planificacion-ev1.docx)** *(Alcance de 5 módulos, EEFs, estrategias híbridas y justificación de herramientas).*
* 📄 **[Acta de Constitución del Proyecto (Project Charter)](./02-pmbok-governance/01-acta-constitucion-proyecto.docx)**
* 📄 **[Plan de Dirección del Proyecto](./02-pmbok-governance/02-plan-direccion-proyecto.docx)**
* 📄 **[Estructura de Desglose del Trabajo (EDT)](./02-pmbok-governance/03-estructura-desglose-trabajo-edt.docx)** | 🖼️ **[Vista de Árbol EDT](./02-pmbok-governance/04-diagrama-arbol-edt.png)**

### 📌 Evaluación Parcial N°2: Monitoreo, Control y Gestión del Cambio
* 📄 **[Reporte Ejecutivo: Monitoreo, Control y Gestión del Cambio (PDF)](./01-executive-reports/02-resumen-ejecutivo-monitoreo-control-ev2.pdf)** *(Flujos de gobernanza, KPIs/KRIs, resolución de imprevistos vía RFC, Matriz RACI y Valor Ganado EVM).*
* 📄 **[Diseño del Sistema de Monitoreo y Consola Trello](./01-executive-reports/03-diseno-sistema-monitoreo-trello-ev2.docx)**
* 📊 **[Matrices de Control (Presupuesto, Gantt, Riesgos y Cambios RFC)](./03-monitoring-and-control/)**
* 📋 **[Plan de Gestión de Comunicaciones](./02-pmbok-governance/05-plan-comunicaciones-proyecto.docx)**

### 📌 Evaluación N°3: Plan de Integración del Proyecto de Software
* 📘 **[Documento Maestro: Plan de Integración del Proyecto](./01-executive-reports/04-plan-integracion-software-ev3.docx)** *(Propósito, entorno operativo, solución propuesta, planificación de recursos y diseño lógico).*
* ⚙️ **[Requisitos Funcionales y No Funcionales de Integración (RFI / RNFI)](./04-technical-integration/02-requisitos-integracion-rfi-rnfi.docx)**
* 👥 **[Especificación de Actores del Sistema (Humanos y Externos)](./04-technical-integration/03-especificacion-actores-sistema.docx)**
* 📑 **[Catálogo de Requerimientos Funcionales (Módulos 1 al 5)](./04-technical-integration/01-requerimientos-funcionales-m1-m5.pdf)**
* 🏗️ **[Modelos y Diagramas de Arquitectura e Integración](./04-technical-integration/architecture-models/)** *(Casos de Uso, Secuencia, Componentes/Despliegue, BPMN AS-IS / TO-BE y Modelo de Datos).*

---

## 🗂️ Arquitectura del Repositorio (Enfoque Dual: PMBOK + DevOps)

El repositorio está estructurado bajo el paradigma de integración dual que articula la **Gobernanza del Proyecto (PMBOK)** con la **Ingeniería e Integración Continua (DevOps)**:

1. 📁 **`01-executive-reports/`**: Informes ejecutivos consolidados dirigidos a la alta dirección (ONG Internacional y Distrito Escolar) para la toma de decisiones estratégicas.
2. 📁 **`02-pmbok-governance/`**: Artefactos fundacionales de la PMO que establecen las líneas base de alcance, tiempo, costo, calidad, recursos y comunicaciones.
3. 📁 **`03-monitoring-and-control/`**: Instrumentos operativos de seguimiento (Valor Ganado, Consola Kanban de 7 columnas en Trello, Registro de Riesgos y Log de Solicitudes de Cambio - RFC).
4. 📁 **`04-technical-integration/`**: Especificaciones de ingeniería de software, contratos de interoperabilidad con sistemas externos (**SGE del Distrito**, **Motor Cloud de IA/LLM**, **CDN Offline-First** y **Gateway SMS/Email**) y modelado arquitectónico.

---

## 📊 Resumen de Módulos e Integraciones Clave

La plataforma integra **5 módulos funcionales** diseñados para operar en dispositivos móviles de gama baja y redes 2G/3G intermitentes ($< 1\text{ Mbps}$):

1. **Módulo 1 — Tutorías en Línea:** Agendamiento flexible, salas ligeras y mensajería asíncrona con resolución garantizada en $< 24\text{ h}$ (`RF 1.1` - `RF 1.5`).
2. **Módulo 2 — Biblioteca de Recursos Educativos (*Offline-First*):** Repositorio curricular categorizado con empaquetado comprimido y sincronización local mediante `IndexedDB` y `CDN` (`RF 2.1` - `RF 2.5` | `RFI-04`).
3. **Módulo 3 — Programa de Mentoría:** Emparejamiento (*matching*) vocacional y canal de mensajería supervisado con protección de datos de menores (`RF 3.1` - `RF 3.5`).
4. **Módulo 4 — Seguimiento del Progreso y Alertas Tempranas:** Dashboards estudiantiles/docentes, exportación de consolidados al **SGE del Distrito** y despacho de alertas vía **Pasarela SMS/Email** (`RF 4.1` - `RF 4.5` | `RFI-01`, `RFI-05`, `RFI-06`).
5. **Módulo 5 — Motor de Personalización con IA:** Diagnóstico de brechas y generación dinámica de rutas de aprendizaje adaptativas mediante **API Cloud de IA / Webhooks** (`RF 5.1` - `RF 5.5` | `RFI-02`, `RFI-03`).