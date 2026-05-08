# 🍯 Brasil Honey Analytics

Interactive AgroTech dashboard for historical honey production analysis in Brazil between 2000 and 2024.

Built entirely with:

* HTML
* CSS
* JavaScript
* TailwindCSS
* Apache ECharts
* Leaflet.js
* PapaParse

No backend, database, or framework required.

---

# 📊 Overview

Brasil Honey Analytics is a modern SaaS-style Data Visualization dashboard focused on historical honey production intelligence across Brazilian municipalities and states.

The platform enables:

* Historical production analysis
* State production ranking
* Choropleth geographic visualization
* Temporal production heatmaps
* Municipal ranking analysis
* Weighted price calculations
* Interactive crossfilter exploration
* Exportable charts and filtered datasets

The project was designed with an AgroTech + Business Intelligence visual identity inspired by platforms such as:

* Power BI
* Tableau
* Climate FieldView
* ArcGIS Dashboards

---

# ✨ Features

## KPI Cards

* Total national production
* Total production value
* Weighted average honey price
* Number of producing municipalities
* Top producing state
* Year-over-year growth

---

## Interactive Visualizations

### 📈 Historical Production Chart

* Bar + line combined chart
* Temporal zoom
* Weighted average price overlay

### 🏆 State Ranking

* Top 10 producing states
* Horizontal ranking bars

### 🗺 Interactive Brazil Map

* Choropleth production visualization
* Hover tooltips
* Crossfilter interaction

### 🔥 Temporal Heatmap

* State vs year production intensity

### 📉 Multi-State Historical Analysis

* Comparative production evolution

### 🌳 State Participation Treemap

* Relative production share

### 🏙 Municipality Ranking Table

* Searchable
* Sortable
* Interactive filtering

---

# ⚡ Technical Highlights

* Fully client-side processing
* No backend required
* CSV-based analytics
* Crossfilter interactions
* Dynamic weighted calculations
* Responsive layout
* Export to PNG
* Export filtered CSV
* Glassmorphism UI
* AgroTech-inspired premium design

---

# 📁 Project Structure

```text
/agrotech-honey-analytics
 ├── index.html
 ├── mel_tratado_2000_2024.csv
 ├── brasil_estados.geojson
```

---

# 🚀 Running Locally

## Option 1 — Recommended

Run a local Python server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## Option 2 — GitHub Pages

This project is fully compatible with GitHub Pages.

Simply upload the repository and enable:

```text
Settings → Pages → Deploy from branch
```

---

# 📦 Dataset

The dashboard uses historical Brazilian honey production data from 2000 to 2024.

Expected CSV columns:

| Column                   | Description            |
| ------------------------ | ---------------------- |
| cod_municipio            | Municipality IBGE code |
| municipio                | Municipality name      |
| estado                   | State abbreviation     |
| ano                      | Year                   |
| producao_kg              | Honey production (kg)  |
| valor_producao_mil_reais | Production value       |
| preco_medio_kg           | Average price per kg   |

---

# 🧮 Analytical Calculations

## Weighted Average Price

```text
SUM(valor_producao_mil_reais * 1000) / SUM(producao_kg)
```

## YoY Growth

```text
(Current Year - Previous Year) / Previous Year
```

---

# 🎨 Design System

Main palette inspired by:

* Honey
* Beeswax
* Agriculture
* Pollen
* Natural landscapes

Key colors:

* Warm amber
* Pastel honey
* Sage green
* Sky blue
* Dusty lavender

---

# 🛠 Technologies

| Technology         | Purpose                 |
| ------------------ | ----------------------- |
| TailwindCSS        | Layout and styling      |
| Apache ECharts     | Advanced visualizations |
| Leaflet.js         | Interactive maps        |
| PapaParse          | CSV parsing             |
| Vanilla JavaScript | Data processing         |

---

# 📌 Future Improvements

* Forecasting models
* Predictive analytics
* Seasonality analysis
* Production clustering
* AI-generated insights
* Dark mode
* Mobile-first optimization
* Animated storytelling
* PDF executive reports

---

# 👨‍💻 Author

Gabriel Martins

Business Intelligence • AgroTech • Data Analytics • Market Intelligence

---
