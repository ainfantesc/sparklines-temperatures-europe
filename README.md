# Sparklines: anomalías anuales de temperatura en Europa (2000–2025)

Visualización interactiva de anomalías anuales de temperatura para España, Francia, Alemania, Italia, Portugal y Reino Unido. Cada sparkline muestra 26 observaciones (2000–2025) en una escala vertical común. La línea horizontal discontinua indica 0 °C respecto a la referencia 1991–2020.

**Fuente:** Our World in Data, [Annual temperature anomalies](https://ourworldindata.org/grapher/annual-temperature-anomalies), con datos de Copernicus.

**Archivos:** `index.html` (página), `sparklines.js` (datos y código ECharts), `temperaturas_europa_2000_2025.xlsx` (datos filtrados) y `annual-temperature-anomalies.csv` (archivo original).

**Publicación:** subir `index.html` y `sparklines.js` a la raíz de un repositorio público, activar GitHub Pages en Settings → Pages → Deploy from a branch → main / (root). La URL será `https://USUARIO.github.io/REPOSITORIO/`. Requiere Internet para cargar Apache ECharts desde CDN.

**Interpretación:** las anomalías son diferencias respecto a la temperatura media del periodo de referencia, no temperaturas absolutas.
