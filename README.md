# Community Solar Adoption in Indiana ([Project Website](https://vatsalparikh.me/community-solar-adoption/))🌞

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

#### Peak Sun Hours Diagram
![image](https://github.com/user-attachments/assets/40424f8d-b536-41e7-8bf5-418519e17cba)


## 📊 Core System Components

### 1. Geospatial Analysis Engine
- **Data Integration:**  
  Aggregates parcel data from Indiana GIS Harvest with:
  - Google Solar API metrics  
  - Municipal utility records  
  - DOE energy consumption patterns

#### Parcel Boundary Visualization  
![image](https://github.com/user-attachments/assets/aacfaebd-e316-4d09-ba52-9585747f2571)

#### Parcel Information Table
![image](https://github.com/user-attachments/assets/e8433fab-2f52-4be7-b98b-4d59a21f3109)

  
### 2. Interactive Mapping Interface
| Feature | Description | Technologies |
|---------|-------------|--------------|
| Layer Toggling | Solar potential vs parcel boundaries | Folium/OpenStreetMap |
| Heatmaps | Power density visualization | Google Solar API |
| Cluster Markers | Site grouping by impact | MarkerCluster |
| Filter Controls | Dynamic CO₂/power thresholds | Panel widgets |

#### Community Solar Sites GIS Dashboard (Indiana)
![image](https://github.com/user-attachments/assets/acad47d7-9a31-42ef-9486-f19e3a0d6f32)

#### Solar Potential Heatmap with Filtering Options
![image](https://github.com/user-attachments/assets/b647b42b-1ec3-4c45-9da1-05b1e349a40c)


### 3. Automated Reporting System
**Report Components:**
1. Municipal Summary Dashboard
2. Site Comparison Matrices
3. Energy Savings Projections
4. Environmental Impact Visualizations
   
**Sample Output Metrics:**

#### Community Solar Report for Washington, IN
![image](https://github.com/user-attachments/assets/2b3d3845-8c14-4dd0-a22c-a0b0e5785e8f)

#### Ranked List of Solar Sites by Performance Metrics
![image](https://github.com/user-attachments/assets/720bdb61-86a4-4b1c-a1a2-527352dc08d2)

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

