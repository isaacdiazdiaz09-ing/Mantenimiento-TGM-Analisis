# Análisis de Riesgo Operativo y Continuidad: Mantenimiento TGM 2025 en Dispositivos de Seguridad. 

Este proyecto demuestra el impacto de la ciencia de datos en la **continuidad operativa** de Talleres Gráficos de México (TGM). A través de un análisis exhaustivo de los programas de mantenimiento, se transformaron registros administrativos en una hoja de ruta estratégica para mitigar riesgos y optimizar la infraestructura crítica.

## Objetivo del Proyecto
Identificar vulnerabilidades en la programación de mantenimiento para el primer semestre de 2025, utilizando herramientas de **Data Analytics** para proponer soluciones que aseguren la operación ininterrumpida de la planta.

## Herramientas Utilizadas
* **Python**: Procesamiento y limpieza de datos.
* **Pandas**: Categorización de activos y análisis de calidad de datos.
* **Seaborn & Matplotlib**: Generación de mapas de calor (Heatmaps) y visualización de carga operativa.

---

## Hallazgos de Alto Impacto (Data Insights)

### 1. Análisis de Calidad y Gobernanza de Datos
Se realizó un perfilado de datos (*Data Profiling*) sobre el dataset original, detectando:
* **Integridad de Datos:** 71.43%.
* **Inconsistencia Crítica:** Un **28.57%** de los registros carecen de información temporal específica ("sin dato"). 
* **Hallazgo:** La falta de validación en la captura de datos impide una auditoría precisa sobre el ciclo de vida de activos vitales.

### 2. Detección de Activos en Riesgo (Análisis Prescriptivo)
Mediante la creación de un **Reporte de Riesgo Operativo**, se identificaron **4 activos con Prioridad ALTA** que operan bajo un esquema reactivo por falta de programación:
* **Sistemas Hidroneumáticos y de Bombeo (3 registros):** Vitales para el suministro de agua y presión en procesos de impresión.
* **Red de Drenaje y Desazolve:** Crítico para evitar inundaciones internas y paros técnicos.

### 3. Continuidad Operativa y Estacionalidad
El análisis de **Matriz de Continuidad** reveló:
* **Gestión Madura:** El sistema de **CCTV** y seguridad electrónica presenta un cumplimiento mensual del 100%.
* **Picos de Carga:** Los meses de **mayo y junio** concentran el mantenimiento especializado (Rayos X), sugiriendo una alta demanda de supervisión técnica en el segundo trimestre.

---

##  Plan de Acción Recomendado (Roadmap)

1. **Saneamiento Inmediato (15 días):** Asignar fechas definitivas a los 4 activos identificados en el reporte de riesgo para garantizar su cobertura preventiva.
2. **Estandarización de Captura:** Implementar protocolos que eliminen el uso de "sin dato", asegurando que cada activo crítico tenga al menos un mes tentativo de intervención.
3. **Análisis Predictivo:** Adoptar el uso de *Heatmaps* para la planeación anual, evitando la saturación de proveedores y optimizando el flujo de caja operativo.

---

##  Contacto y Conexiones

Si estás interesado en conocer más sobre este proyecto o discutir oportunidades en el área de **Análisis de Datos**, no dudes en contactarme:

* ** Correo:** [isaac.diazdiaz09@gmail.com](mailto:isaac.diazdiaz09@gmail.com)
* ** LinkedIn:** [Isaac Diaz Diaz Barriga](https://www.linkedin.com/in/isaac-diaz-diaz-barriga/)
