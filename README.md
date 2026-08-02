# Control-hospitalario

# 🏥 Análisis de Ocupación Hospitalaria e Impacto de Enfermedades Respiratorias

## 📌 Descripción del Proyecto
Este proyecto analiza el impacto de enfermedades respiratorias (COVID-19, Influenza y Virus Sincitial Respiratorio - VRS) en la capacidad hospitalaria y la ocupación de camas (generales y UCI) a nivel regional. Mediante técnicas de procesamiento y manipulación de datos con **Python y Pandas**, se extraen métricas clave para evaluar la carga del sistema de salud y apoyar la toma de decisiones.

---

## 🎯 Objetivos Analíticos
* Procesar y transformar datos hospitalarios tabulares provenientes de reportes semanales.
* Calcular e interpretar métricas de ocupación en camas generales y de Cuidados Intensivos (UCI), segmentadas por población adulta y pediátrica.
* Identificar patrones y tendencias de hospitalización asociados a virus respiratorios.

---

## 📖 Diccionario de Datos Principales
| Variable | Descripción |
| :--- | :--- |
| `Week Ending Date` | Fecha de corte del reporte semanal |
| `Geographic aggregation` | Región geográfica de agregación de datos |
| `Number of Inpatient Beds` | Total de camas de hospitalización disponibles |
| `Number of ICU Beds` | Total de camas en Unidad de Cuidados Intensivos (UCI) |
| `Number of Adult/Pediatric Patients Hospitalized with [Virus]` | Conteo de pacientes hospitalizados por COVID-19, Influenza o VRS |

---

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Entorno:** Google Colab / Jupyter Notebook
* **Librerías:** `pandas`, `numpy`
