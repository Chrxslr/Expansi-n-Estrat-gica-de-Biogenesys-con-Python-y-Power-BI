# 🧬 Proyecto M4 – Expansión Estratégica de Biogenesys con Python y Power BI  

**Autor:** Christian Daniel Lara Larios  
**Email:** larad8704@gmail.com  
**Cohorte:** DAFT-16  
**Fecha de entrega:** 04/07/2025  
**Institución:** Biogenesys Institute of Data Science  

---

## 📌 Introducción  
Este proyecto integrador tuvo como objetivo brindar **soluciones analíticas para la expansión estratégica de los laboratorios Biogenesys en América Latina**.  

En un contexto post-pandémico, la empresa buscaba identificar los países más prometedores para invertir en infraestructura sanitaria, basándose en datos sobre:  
- Incidencia de COVID-19.  
- Cobertura de vacunación.  
- Personal médico disponible.  

El análisis se centró en **Brasil, Chile, México, Argentina, Colombia y Perú**.  

---

## 🛠️ Desarrollo del proyecto  

### 🔹 Recopilación y procesamiento de datos (Python)  
- **Dataset principal:** `data_latinoamerica.csv` → depurado en `df_pais_principal.csv`.  
- **Herramientas:** Visual Studio Code + librerías:  
  - `pandas`, `numpy` → manejo y transformación de datos.  
  - `matplotlib`, `seaborn` → visualizaciones exploratorias.  
  - `datetime` → tratamiento de fechas.  

**Transformaciones clave:**  
- Conversión de fechas a `datetime`.  
- Cálculo de sumatorias acumuladas (casos, decesos, vacunación).  
- Normalización de indicadores (vacunas por millón, médicos por cada 1000 hab.).  
- Filtrado de columnas irrelevantes.  

**Visualizaciones en Python:**  
- Líneas → evolución temporal de casos y vacunaciones.  
- Barras → personal médico por país.  
- Boxplots y heatmaps → distribución y correlaciones.  
- Áreas apiladas → comportamiento acumulativo de vacunación.  

---

### 🔹 Dashboard en Power BI  

**Página 1 – Presentación General**  
- Portada con logotipo Biogenesys.  
- Botones de navegación.  
- Diseño profesional con colores institucionales.  

**Página 2 – Incidencia & Vacunación**  
- KPIs: casos confirmados, decesos, recuperados.  
- Gráfico de torta → casos vs decesos.  
- Gráfico de líneas → evolución por país.  
- Columnas apiladas → vacunas administradas mes a mes.  
- Barras horizontales → personal médico por cada 1000 hab.  

**Página 3 – Expansión: Brasil & Chile**  
- KPIs de salud pública (esperanza de vida, mortalidad infantil y adulta).  
- Barras → densidad de personal médico.  
- Treemap → distribución de casos (Brasil, México, Argentina dominan).  
- Barras horizontales → decesos por país.  
- Área apilada → vacunas administradas con mejor claridad visual.  

---

## 📈 Insights principales  

- **Brasil** → mayor número absoluto de casos y vacunaciones, pero bajo nivel de personal médico por habitante.  
- **Chile** → mayor densidad de personal médico, vacunación eficiente y sistema de salud sólido.  
- **Argentina & México** → altas cifras de decesos y casos acumulados → oportunidad de mejorar cobertura sanitaria.  
- **Perú & Colombia** → avances en vacunación pero con retos en infraestructura.  
- **Estacionalidad** → picos en junio y diciembre → campañas estratégicas en esos períodos.  
- **COGS vs Utilidad** → alta sensibilidad en márgenes brutos por variaciones de costo.  

---

## 🧭 Conclusiones y recomendaciones  

- **Brasil**: alta demanda sanitaria → mercado con mayor potencial.  
- **Chile**: ideal para centro de operaciones → sistema de salud eficiente y cobertura médica sólida.  
- **Perú y Colombia**: mercados secundarios con potencial en distribución.  
- **Futuro:** integrar variables económicas (PIB, urbanización) y usar análisis geoespacial para ubicar ciudades clave.  

---

## 💭 Reflexión personal  

Este proyecto fue un **desafío integral** que consolidó mis competencias en:  
- Python (EDA, limpieza y visualización).  
- Power BI (modelado, storytelling y diseño UX/UI).  
- Pensamiento analítico aplicado a problemas estratégicos reales.  

👉 Principales aprendizajes:  
- La calidad del dato es tan importante como el análisis mismo.  
- Storytelling visual en dashboards es esencial para comunicar insights complejos.  
- El análisis de datos puede guiar decisiones con impacto real en empresas del sector salud.  

---

## ⭐ Extra Credit  

### 🔹 Aportes de Python  
- Automatización de agregaciones por país y fecha.  
- Depuración masiva de columnas antes de Power BI.  
- Flexibilidad estadística y escalabilidad a múltiples fuentes.  

### 🔹 Oportunidades futuras  
- Integrar **machine learning** (RandomForest, XGBoost) para predicciones.  
- Usar **mapas interactivos** (Plotly, Folium) para análisis geoespacial.  
- Combinar datos epidemiológicos con variables económicas y demográficas.  

---

## 🚀 Tecnologías utilizadas  
- **Python (pandas, numpy, matplotlib, seaborn)**.  
- **Power BI (Power Query, DAX, storytelling visual)**.  
- **VS Code** (entorno de desarrollo).  

---

✍️ *Este proyecto demuestra cómo el flujo Python → Power BI permite transformar datos sanitarios en insights estratégicos para la toma de decisiones de negocio.*  
