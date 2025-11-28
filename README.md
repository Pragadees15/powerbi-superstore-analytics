<div align="center">
  <img src="https://img.shields.io/badge/Analytics-SuperStore%20Pulse-6C63FF?style=for-the-badge&logo=power-bi&logoColor=white" alt="SuperStore badge" />
  <h1>Power BI SuperStore Analytics</h1>
  <p><em>From descriptive KPIs to predictive intelligence — one crafted workspace that feels like a polished product launch.</em></p>
  <p>
    <a href="https://powerbi.microsoft.com/"><img src="https://img.shields.io/badge/Made%20with-Power%20BI-F2C811?logo=power-bi&logoColor=black" /></a>
    <a href="#-dashboard-lineup"><img src="https://img.shields.io/badge/Dashboards-4%20immersive%20pages-9D4EDD" /></a>
    <a href="#-python-toolkit"><img src="https://img.shields.io/badge/Python-ready%20for%20ML-3776AB?logo=python&logoColor=white" /></a>
    <a href="https://github.com/Pragadees15/powerbi-superstore-analytics"><img src="https://img.shields.io/badge/GitHub-view%20project-24292F?logo=github" /></a>
  </p>
</div>

<div align="center">
  <img src="dashboard_images/Powerbi-1.png" alt="Hero Dashboard" width="95%" />
</div>

<div align="center">
  <table>
    <tr>
      <td><strong>🚀 KPIs</strong><br/>Sales • Profit • Orders • Customers</td>
      <td><strong>🧠 Intelligence</strong><br/>Python ML forecasts + what-if slicers</td>
      <td><strong>🎨 Themes</strong><br/>Apple Modern + Dark Studio</td>
      <td><strong>📱 Form Factors</strong><br/>Desktop, mobile, boardroom</td>
    </tr>
  </table>
</div>

---

## 📌 Table of Contents
1. [Why This Project?](#-why-this-project)
2. [Dashboard Lineup](#-dashboard-lineup)
3. [Solution Blueprint](#-solution-blueprint)
4. [Dataset & Metrics](#-dataset--metrics)
5. [Quickstart Guide](#-quickstart-guide)
6. [Dashboard Deep Dive](#-dashboard-deep-dive)
7. [Design System](#-design-system)
8. [Key Visuals](#-key-visuals)
9. [Customization Paths](#-customization-paths)
10. [Use Cases](#-use-cases)
11. [Contributors](#-contributors)
12. [Resources](#-resources)

---

## 🎯 Why This Project?
- **Single source of truth** for sales, profit, retention, and payment insights.
- **Decision-ready storytelling** powered by themed layouts (light + dark).
- **Predictive intelligence** via Python-driven ML forecasts embedded inside Power BI.
- **Business-friendly deployment**: shareable PBIP/PBIX files and semantic model definitions.

---

## 📊 Dashboard Lineup
| Experience | What You See | Snapshot |
| --- | --- | --- |
| **Sales & Performance** | KPIs, margin health, monthly velocity, segment mix | ![Sales Dashboard](dashboard_images/Powerbi-2.png) |
| **Customer Insights** | Retention, CLV, geo split, top customers, cohort trend | ![Customer Insights](dashboard_images/Powerbi-3.png) |
| **Payment Behavior** | Wallet share by mode, profitability, digital vs. offline | ![Payment Behavior](dashboard_images/Powerbi-4.png) |
| **ML Predictions** | Auto ML forecast, Python visuals, scenario slicers | ![ML Predictions](dashboard_images/Powerbi-5.png) |

---

## 🧱 Solution Blueprint
```
powerbi-superstore-analytics/
├─ dashboard_images/                  # Storytelling assets
├─ Improved Dashboard Updated Dark themed.pbix
├─ p.pbip                            # Power BI Project (source-controlled)
├─ p.Report/definition/pages         # Page + visual JSON definitions
├─ p.SemanticModel/definition        # Tables, relationships, metadata
├─ SuperStore_Sales_UpdatedDates.csv # Curated fact table
├─ requirements.txt                  # Python runtime dependencies
└─ README.md
```

---

## 📋 Dataset & Metrics
**Source:** SuperStore Sales (Orders, Customers, Products, Payments).

**Core Columns**
- Orders: ID, dates, ship mode
- Customers: ID, name, segment
- Geography: Country → Region hierarchy
- Products: Category, Sub-category, SKU
- Finance: Sales, Profit, Quantity, Returns
- Payments: Mode + online/offline flag

**Calculated KPIs**
- Total Sales / Profit / Orders / Customers
- Profit Margin & Sales-per-Order
- Average Shipping Time
- Segmented performance lift

---

## ⚙️ Quickstart Guide
1. **Clone**
   ```bash
   git clone https://github.com/Pragadees15/powerbi-superstore-analytics.git
   cd powerbi-superstore-analytics
   ```
2. **Install Python toolkit**
   ```bash
   pip install -r requirements.txt
   ```
3. **Open in Power BI Desktop**
   - Load `p.pbip` for source-controlled editing.
   - Prefer `Improved Dashboard Updated Dark themed.pbix` if you just want the polished dark theme.
   - Update the path to `SuperStore_Sales_UpdatedDates.csv`, then refresh.

### 🐍 Python Toolkit
- `pandas>=1.5.0` for feature engineering
- `numpy>=1.21.0` for numeric ops
- `matplotlib>=3.5.0` & `seaborn>=0.11.0` for quick viz
- `scikit-learn>=1.1.0` powering ML forecasts

---

## 🔍 Dashboard Deep Dive
- **Main Sales Dashboard**: KPI wall, trend ribbon, profit waterfall, and per-order economics.
- **Customer Insights**: Lifetime value lens, retention funnel, geo scatter, and top buyer league tables.
- **Payment Behavior**: Payment mix donut, profitability treemap, adoption over time, online vs offline cards.
- **ML Predictions**: Python visual hosting trained model output, forecast table, and “what-if” slicers for segments.

---

## 🧑‍🎨 Design System
- **Apple Modern** palette with accent pops; dark-theme alternative for low-light rooms.
- **Interaction-first layout**: cross-highlighting, drill-through, and mobile-friendly views.
- **Custom visuals** for KPI density cards, treemaps, and forecasting overlays.

---

## 📈 Key Visuals
- KPI deck: Total Sales, Profit, Orders, Customers
- Trend stories: month-on-month sales and retention curves
- Geo intelligence: regional choropleths and city scatter
- Segment grid: bar + treemap combos
- Forecast canvas: ML prediction ribbons + table
- Payment matrix: donut, pivot, and stacked bars

---

## 🛠️ Customization Paths
### Update the Dataset
1. Replace `SuperStore_Sales_UpdatedDates.csv`.
2. Keep schema consistent (or adjust the semantic model).
3. Refresh the PBIX/PBIP file.

### Extend the Dashboards
- Add measures in the semantic model.
- Spin up new pages for additional personas.
- Swap themes under **View → Themes**.
- Wire your own Python scripts for bespoke forecasting.

---

## 💼 Use Cases
- Revenue/performance readouts for weekly exec reviews.
- Customer segmentation & loyalty storytelling for marketing.
- Payment optimization insights for finance/product teams.
- Scenario planning & demand forecasting for operations.
- Regional benchmarking for territory managers.

---

## 🤝 Contributors
| Contributor | Focus |
| --- | --- |
| <a href="https://github.com/Pragadees15"><img src="https://avatars.githubusercontent.com/Pragadees15" alt="Pragadees15" width="90" /></a><br/>[Pragadeeswaran K](https://github.com/Pragadees15) | Project lead, Power BI architecture, ML integration |
| <a href="https://github.com/SHYAM140305"><img src="https://avatars.githubusercontent.com/SHYAM140305" alt="SHYAM140305" width="90" /></a><br/>[Shyam S](https://github.com/SHYAM140305) | Dashboard polishing, storytelling content |

---

## 📚 Resources
- [Power BI Documentation](https://docs.microsoft.com/power-bi/)
- [DAX Guide](https://dax.guide/)
- [Power BI Community](https://community.powerbi.com/)

> **Heads-up:** If you relocate the repo, revisit the data source settings inside Power BI Desktop to point to the new CSV path.

