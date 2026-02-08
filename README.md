# Uriel Olaf Martínez Remigio — Portafolio (Data Analytics + Automatización)

**Rol objetivo:** Data Analyst Jr / BI Jr (SQL · Python · Power BI · Google Sheets) + Automatización (n8n)  
**Ubicación:** Estado de México (Naucalpan) | **Modalidad:** Presencial / Híbrido / Remoto  
**Contacto:** martinezremigiou@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/olaf-remigio-b06393304/

---

## Quien soy?
Soy un perfil en transición a tecnología, enfocado en **análisis de datos end-to-end**: desde limpieza y modelado (Python/SQL), hasta **dashboards ejecutivos en Power BI**.  
Este repositorio funciona como **índice** para navegar mis proyectos: incluye el **problema**, el **stack**, y la **evidencia** (repositorios + entregables).

---

## Stack principal
- **SQL (PostgreSQL):** joins, agregaciones, modelado tipo estrella, vistas, QA
- **Python (Pandas):** limpieza, validación, métricas, exports, evidencia reproducible
- **Power BI:** modelado, DAX, visuales ejecutivos, segmentación y geografía
- **Google Sheets:** KPIs, tablas dinámicas, validación, dashboards
- **Automatización (n8n):** flujos con Gmail/Sheets/APIs (en progreso)

---

# Proyectos destacados (índice)

> **Tip:** Abre cada repo y revisa el README del proyecto: ahí está el contexto, KPIs, metodología y entregables.

| Proyecto (Prioridad) | Stack | Qué resolví (impacto) | Evidencia (Repo / Entregables) |
|---|---|---|---|
| **1) Olist Logistics — Panel SLA (SQL + Python + Power BI)** | **PostgreSQL · Python (Pandas) · Power BI (DAX)** | Medí desempeño logístico **end-to-end** (SLA) y detecté **drivers** de atraso (geografía, categoría, payment mix). Construí un dashboard por páginas: **Resumen Ejecutivo / Geografía / Drivers**. | **Repo:** https://github.com/martinezremigiou-cloud/olist-logistics-sla-dashboard |
| **2) Panel de Ventas Walmart (Google Sheets)** | Google Sheets | Dashboard con KPIs (ventas por m², participación por depto, volatilidad) + filtros dinámicos y tablas dinámicas. | **Repo:** https://github.com/martinezremigiou-cloud/walmart-sales-dashboard |

---

# Proyecto 1 (destacado): Olist Logistics — Panel SLA (SQL + Python + Power BI)

## Objetivo
Construir un flujo profesional para responder:
- ¿Cuál es el **tiempo típico de entrega** (end-to-end)?
- ¿Cuál es el **SLA real** (P90/P95) y su comportamiento?
- ¿Qué porcentaje de órdenes llega tarde (**late_rate**)?
- ¿Dónde está concentrado el riesgo (estados/categorías/payment_type)?

## KPIs trabajados (núcleo)
- **delivery_time_days:** días desde compra hasta entrega al cliente
- **delay_days:** días de atraso vs fecha estimada
- **late_rate:** % de órdenes entregadas tarde
- **SLA P90 / P95:** percentiles para acuerdos de servicio (cola larga)
- **Análisis de outliers:** decisión profesional entre “análisis real” vs “cap visual” (para gráficos sin distorsión)

## Flujo end-to-end (cómo se construyó)
1) **Python:** limpieza, tipado de fechas, creación de KPIs, validaciones y exports de evidencia  
2) **SQL (Postgres):** staging/QA, modelado tipo estrella (facts/dims), vistas para consumo BI  
3) **Power BI:** relaciones limpias, dim_date, medidas DAX, visuales por páginas y validación de agregaciones (evitar “sumas infladas”)

## Uso puntual de IA (agentes)
Se utilizó IA de forma **asistida** para acelerar:
- documentación (README y notas),
- estructura de módulos/scripts,
- checklist y validaciones repetibles.  
**Importante:** las decisiones y validaciones se confirmaron con resultados medibles (SQL/Python/Power BI).

## Entregables principales
- Dashboard Power BI (páginas: Executive / Geo / Drivers)
- Tablas y exports (reports) para evidencia
- SQL scripts/vistas + notebooks de Python + entorno reproducible (`environment.yml`)

---

# Proyecto 2: Panel de Ventas Walmart (Google Sheets)

## Objetivo
Construir un dashboard con KPIs y filtros para lectura ejecutiva:
- ventas por m²
- participación por departamento
- volatilidad (coeficiente de variación)

## Entregables
- Dashboard en Sheets con tablas dinámicas, gráficos y filtros dinámicos
- Estructura clara para auditar cálculos

---

