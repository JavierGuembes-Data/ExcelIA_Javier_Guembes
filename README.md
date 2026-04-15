# Análisis de Gastos de Viaje y Compensaciones - Aerolíneas

## Descripción del Proyecto
Este proyecto presenta un análisis integral de datos sobre gastos operativos derivados de irregularidades en vuelos (retrasos y cancelaciones) para aerolíneas líderes como Avianca y LATAM. El objetivo principal es transformar datos brutos en información estratégica para optimizar la toma de decisiones en el departamento de reembolsos y atención al cliente.

El análisis se centra en cuantificar el impacto financiero de la "no calidad" y en identificar oportunidades para mejorar la eficiencia operativa y el flujo de caja.

## Pregunta Clave de Negocio
**¿En qué medida las irregularidades operativas están generando costos no recuperables y cómo afecta esto al flujo de caja según el estado de las reclamaciones?**

## Metodología y Herramientas
Para este proyecto se utilizó **Microsoft Excel**, aplicando técnicas avanzadas de preparación y análisis de datos:

1.  **Limpieza y Transformación de Datos:**
    * Uso de fórmulas lógicas anidadas (`SI`, `O`, `IF`, `OR`) para estandarizar categorías de gastos y criterios de elegibilidad de reembolsos.
    * Generación de datos simulados coherentes mediante lógicas condicionales para análisis de escenarios.
2.  **Análisis Estadístico:**
    * Cálculo de métricas de impacto basadas en horas de demora (`Delay_Hours`) y tipos de incidencia (`Complaint_Type`).
3.  **Visualización de Datos:**
    * Tablas dinámicas para resumir costos por tipo de queja y aerolínea.
    * Segmentadores de datos (Slicers) para interactividad en tiempo real (filtrado por `Status` y `Airline`).

## Estructura del Análisis
* **Distribución de Gastos:** Identificación de los costos más altos (Hotel, Alimentación, Transporte) frente a la elegibilidad de reembolso.
* **Tendencia Temporal:** Análisis de incidencias diarias para detectar picos operativos.
* **Estado de Reclamaciones:** Visualización del pasivo financiero acumulado en casos "Open" y "Pending".

## Resultados y Soluciones de Negocio
* **Priorización de Pagos:** Herramienta para identificar casos de alto monto que requieren cierre inmediato para mejorar la satisfacción del cliente.
* **Optimización de Políticas:** Propuesta de umbrales de demora para la aprobación automática de asistencias, reduciendo la carga administrativa.

---
**Autor:** Javier Guembes
**Herramientas:** Excel / GitHub / Análisis de Datos
