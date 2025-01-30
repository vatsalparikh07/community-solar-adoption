# Community Solar Adoption in Indiana 🌞

Geospatial analysis platform identifying optimal community solar sites for tax-exempt organizations in Indiana.

## 📌 Project Overview
**Objective:** Identify and prioritize solar installation sites for tax-exempt organizations through data-driven analysis of:
- Solar potential (Google Solar API)
- Economic impact (Utility billing data)
- Parcel characteristics (Indiana GIS Data Harvest)
- Energy consumption patterns (DOE Commercial Buildings Survey)

**Key Stakeholders:**
- Indiana Energy Independence Fund
- Municipal utilities
- Non-profit organizations (Schools, Religious institutions, Community centers)

**Impact Metrics:**
- $8.2M potential annual savings
- 2,299 ton CO₂ reduction potential
- 311 homes powered equivalent (Southridge HS site)

## 📊 Core System Components

### 1. Geospatial Analysis Engine
- **Data Integration:**  
  Aggregates parcel data from Indiana GIS Harvest with:
  - Google Solar API metrics  
  - Municipal utility records  
  - DOE energy consumption patterns
  
### 2. Interactive Mapping Interface
| Feature | Description | Technologies |
|---------|-------------|--------------|
| Layer Toggling | Solar potential vs parcel boundaries | Folium/OpenStreetMap |
| Heatmaps | Power density visualization | Google Solar API |
| Cluster Markers | Site grouping by impact | MarkerCluster |
| Filter Controls | Dynamic CO₂/power thresholds | Panel widgets |

### 3. Automated Reporting System
**Report Components:**
1. Municipal Summary Dashboard
2. Site Comparison Matrices
3. Energy Savings Projections
4. Environmental Impact Visualizations

**Sample Output Metrics:**

### Stakeholder-Focused Metrics
- **Energy Equivalency:**  
  `1 Array = 311 Homes Powered (Southridge HS Benchmark)`
- **Savings Calculation:**
  `Annual Savings = (kWh Generated × Local Rate) × 0.25 # 25% community discount`
- **CO₂ Impact:**  
  `1 kWh Solar = 0.7 lb CO₂ Offset`

### Top Performing Sites
| Site | Annual Savings | CO₂ Reduction | Homes Equivalent |
|------|----------------|---------------|------------------|
| Southridge HS | $1.2M | 2,299 tons | 311 |
| Huntingburg Elementary | $475K | 907 tons | 123 |
| Linton Middle School | $384K | 894 tons | 121 |


## 🔮 Future Development Roadmap

1. **Energy Storage Analysis Module**  
   Battery feasibility modeling for critical facilities

2. **Policy Impact Simulator**  
   Legislative change scenario modeling

3. **Community Portal**  
   Public-facing solar ROI calculator

4. **Statewide Expansion**  
   Scalable framework for Indiana-wide deployment

---

*Developed in partnership with Indiana Energy Independence Fund - 2024*

