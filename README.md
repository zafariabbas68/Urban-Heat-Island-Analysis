
# 🌡️ Urban Heat Island Analysis for Lombardy Region, Italy

[![Python](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GIS](https://img.shields.io/badge/GIS-QGIS-orange.svg)](https://qgis.org/)
[![Remote Sensing](https://img.shields.io/badge/Remote%20Sensing-Landsat%208%2F9-red.svg)](https://www.usgs.gov/landsat-missions)

## 📌 Project Overview

This project presents a **comprehensive Urban Heat Island (UHI) analysis** for the **Lombardy region** in northern Italy, one of Europe's most industrialized and densely populated areas. The study integrates land cover classification, Land Surface Temperature (LST) mapping, demographic vulnerability assessment, and Nature-Based Solutions (NBS) prioritization.

### 🎯 Key Objectives

- Map and quantify land cover distribution across Lombardy using 30m resolution data
- Assess Land Surface Temperature patterns for summer and winter seasons
- Calculate and classify UHI intensity across the region
- Identify vulnerable populations (children 0-5 years and elderly 65+ years)
- Evaluate green infrastructure adaptive capacity and cooling potential
- Prioritize areas for Nature-Based Solution interventions

---

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| **Summer UHI Intensity** | **4.8°C** (urban vs rural) |
| **Maximum UHI Intensity** | **6.6°C** |
| **Very High UHI Areas** | **71.9%** of the region |
| **Vulnerable Population at Extreme Risk** | **23,912** (children + elderly) |
| **Forest Cooling Effect** | **4.8°C** |
| **Critical Priority Area** | **9.2 km²** (immediate intervention) |
| **High Priority Area** | **113.4 km²** (short-term action) |
| **Total Study Area** | **238.75 km²** |

---

## 🗺️ Results Gallery

### Land Cover Classification Map
![Land Cover Map](Lombardy_LandCover_2022_Professional.png)
*Figure 1: Land Cover Classification Map of Lombardy Region (2022) showing cropland (45.14%), forest (29.38%), and built-up areas (10.56%)*

### Land Surface Temperature Maps
![LST Maps](uhi_land_surface_temperature.png)
*Figure 2: Seasonal Land Surface Temperature maps - Summer (left) and Winter (right)*

### UHI Intensity Maps
![UHI Intensity](uhi_intensity_maps.png)
*Figure 3: Summer and Winter UHI Intensity Maps showing temperature difference from rural reference*

### Spatial Pattern Analysis
![Spatial Patterns](spatial_pattern_analysis.png)
*Figure 4: Spatial distribution of key land cover types across Lombardy*

### UHI Transect Profiles
![Transects](uhi_transect_profiles.png)
*Figure 5: UHI Profile Transects in four directions showing temperature decay from urban cores*

### Temperature by Land Cover
![Temperature by Land Cover](uhi_temperature_by_landcover.png)
*Figure 6: Summer temperature and UHI intensity by land cover type*

### UHI Intensity Distribution
![UHI Distribution](uhi_intensity_distribution.png)
*Figure 7: UHI Intensity Distribution - 71.9% of region experiences "Very High UHI"*

### Mitigation Priority Map
![Mitigation Priority](uhi_mitigation_priority_map.png)
*Figure 8: UHI Mitigation Priority Map identifying Critical and High priority areas*

### Comprehensive Dashboard
![Dashboard](uhi_comprehensive_dashboard.png)
*Figure 9: Comprehensive UHI Dashboard with all key metrics*

### Additional Visualizations

| Figure | Description |
|--------|-------------|
| ![Land Cover Distribution](land_cover_distribution.png) | Pie and bar charts of land cover distribution |
| ![Detailed Breakdown](detailed_land_cover_breakdown.png) | Complete land cover breakdown with percentages |
| ![Urban vs Natural](urban_vs_natural_comparison.png) | Urban vs natural areas comparison |
| ![Land Cover Dashboard](land_cover_dashboard.png) | Land cover analysis dashboard |
| ![Water Resources](water_resources_analysis.png) | Water bodies and wetlands analysis |
| ![UHI Analysis Dashboard](uhi_analysis_dashboard.png) | UHI statistics dashboard |
| ![Distance Decay](uhi_distance_decay_curve.png) | UHI intensity decay with distance |
| ![Hotspot Analysis](uhi_hotspot_coldspot_analysis.png) | UHI hotspot and coldspot analysis |
| ![Radar Chart](uhi_radar_chart.png) | Seasonal UHI performance radar chart |
| ![Transect Profiles](uhi_transect_profiles.png) | Four-direction transect analysis |

---

## 📈 Land Cover Statistics

| Rank | Land Cover Type | Class | Area (km²) | Percentage |
|------|----------------|-------|------------|------------|
| 1 | Cropland | 8 | 107.76 | 45.14% |
| 2 | Forest | 20 | 70.15 | 29.38% |
| 3 | Built-up | 13 | 25.22 | 10.56% |
| 4 | Grassland | 7 | 17.07 | 7.15% |
| 5 | Water | 15 | 7.21 | 3.02% |
| 6 | Bareland | 12 | 6.66 | 2.79% |
| 7 | Shrubland | 5 | 3.75 | 1.57% |
| 8 | Ice/Snow | 16 | 0.84 | 0.35% |
| 9 | Wetland | 9 | 0.10 | 0.04% |

---

## 🌡️ Temperature Analysis

### Summer Temperature by Land Cover

| Land Cover Type | Mean Summer Temp (°C) | vs Rural Reference |
|----------------|---------------------|-------------------|
| Built-up (Urban) | 28.6 | +4.8°C |
| Bareland | 28.0 | +4.3°C |
| Cropland | 26.5 | +2.8°C |
| Grassland | 25.2 | +1.5°C |
| Shrubland | 25.0 | +1.3°C |
| Forest | 23.8 | +0.1°C |
| Water | 22.7 | -1.0°C |
| Wetland | 22.7 | -1.0°C |

### Winter Temperature by Land Cover

| Land Cover Type | Mean Winter Temp (°C) | vs Rural Reference |
|----------------|---------------------|-------------------|
| Built-up (Urban) | 3.8 | +2.4°C |
| Bareland | 3.5 | +2.1°C |
| Cropland | 2.8 | +1.4°C |
| Grassland | 2.5 | +1.1°C |
| Shrubland | 2.4 | +1.0°C |
| Forest | 1.4 | 0.0°C |
| Water | 0.5 | -0.9°C |

---

## 🏙️ UHI Intensity Classification

| UHI Class | Intensity Range | Pixel Count | Percentage |
|-----------|----------------|-------------|------------|
| Very Low UHI | <0.2°C | 61,017 | 23.0% |
| Low UHI | 0.2-0.4°C | 4,909 | 1.9% |
| Moderate UHI | 0.4-0.6°C | 4,433 | 1.7% |
| High UHI | 0.6-0.8°C | 4,239 | 1.6% |
| **Very High UHI** | **>0.8°C** | **190,685** | **71.9%** |

---

## 📍 Mitigation Priority Areas

| Priority Level | Area (km²) | Percentage | Recommended Action |
|----------------|------------|------------|-------------------|
| Critical Priority | 9.2 | 1.8% | Immediate intervention |
| High Priority | 113.4 | 22.7% | Short-term action (1-3 years) |
| Medium Priority | 37.3 | 7.5% | Medium-term planning |
| Low Priority | 56.1 | 11.2% | Long-term strategy |
| Very Low Priority | 0.5 | 0.1% | Maintenance only |

---

## 🛠️ Methodology & Tools

### Data Sources

| Data Type | Source | Resolution | Year |
|-----------|--------|------------|------|
| Land Cover | GLC_FCS30D (ESA) | 30m | 2022 |
| Land Surface Temperature | Landsat 8/9 (simulated) | 30m | 2022 |
| Administrative Boundaries | Lombardy Region | Vector | 2022 |

### Software & Libraries

| Tool | Purpose |
|------|---------|
| **Python 3.13** | Core data processing |
| **rasterio** | Raster data handling |
| **numpy** | Numerical computations |
| **pandas** | Data manipulation |
| **matplotlib / seaborn** | Visualization |
| **scipy** | Statistical analysis |
| **QGIS 3.34** | Additional spatial analysis |
| **Google Earth Engine** | LST processing reference |

---

## 📁 Repository Structure

```
Urban-Heat-Island-Analysis/
├── README.md                                    # Project documentation
├── LICENSE                                      # MIT License
├── Lombardy_LandCover_2022_Professional.png     # Main land cover map
├── uhi_land_surface_temperature.png             # Summer/Winter LST maps
├── uhi_intensity_maps.png                       # UHI intensity maps
├── spatial_pattern_analysis.png                # Spatial patterns
├── uhi_transect_profiles.png                   # Transect analysis
├── uhi_temperature_by_landcover.png            # Temperature by land cover
├── uhi_radar_chart.png                         # Seasonal performance
├── uhi_distance_decay_curve.png                # Distance decay analysis
├── uhi_mitigation_priority_map.png             # NBS priority map
├── uhi_intensity_distribution.png              # UHI distribution donut
├── land_cover_dashboard.png                    # Land cover dashboard
├── uhi_comprehensive_dashboard.png             # Complete UHI dashboard
├── land_cover_distribution.png                 # Pie/bar charts
├── detailed_land_cover_breakdown.png           # Detailed breakdown
├── urban_vs_natural_comparison.png             # Urban vs natural
├── water_resources_analysis.png                # Water/wetland analysis
├── uhi_analysis_dashboard.png                  # UHI statistics
├── uhi_hotspot_coldspot_analysis.png           # Hotspot analysis
└── Urban_heat_Island_for_Lombardy-2.pdf        # Complete report
```

---

## 💡 Recommendations

### Immediate Actions (Critical Priority - 9.2 km²)

| Action | Expected Impact |
|--------|-----------------|
| Implement cool roofs and green roofs | 2-3°C reduction |
| Increase tree canopy cover by 30% | 1-2°C reduction |
| Create shaded pedestrian corridors | 2-4°C perceived cooling |
| Install cool pavements | 1-2°C surface reduction |
| Develop cooling centers for elderly | Health protection |

### Short-Term Actions (High Priority - 113.4 km²)

| Action | Expected Impact |
|--------|-----------------|
| Plant street trees (30% canopy target) | 1-2°C reduction |
| Create pocket parks and community gardens | 1-3°C reduction |
| Implement water-sensitive urban design | 1-2°C reduction |
| Create green buffer zones | 2-3°C reduction |
| Restore riparian corridors | 1-2°C reduction |

---

## 📖 Citation

If you use this work, please cite:

```bibtex
@misc{zafari2026uhi,
  author = {Zafari, Ghulam Abbas},
  title = {Urban Heat Island Analysis for Lombardy Region, Italy},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/zafariabbas68/Urban-Heat-Island-Analysis}
}
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Ghulam Abbas Zafari**
- GitHub: [@zafariabbas68](https://github.com/zafariabbas68)
- Email: ghulamabbas.zafari@mail.polimi.it

---

## 🙏 Acknowledgments

- Inspired by Buffoli et al. (2025) - Urban Heat Exposure in Milan study
- GLC_FCS30D dataset provided by ESA
- Landsat 8/9 imagery from USGS
- Politecnico di Milano - Department of Civil, Environmental and Land Management Engineering

---

## 📊 Key Insights Summary

| Metric | Value |
|--------|-------|
| 🔥 **Severe UHI Detected** | 4.8°C temperature difference |
| 🏙️ **Urban Extent** | 25.2 km² (10.6% of region) |
| 🌡️ **Very High UHI Areas** | 71.9% of the region |
| ❄️ **Forest Cooling** | 4.8°C cooling effect |
| 💧 **Water Cooling** | 5.9°C cooling effect |
| 🚨 **Critical Priority** | 9.2 km² needs immediate intervention |
| ⚠️ **High Priority** | 113.4 km² requires short-term action |

---

## 🔗 Links

- [GitHub Repository](https://github.com/zafariabbas68/Urban-Heat-Island-Analysis)
- [Complete PDF Report](Urban_heat_Island_for_Lombardy-2.pdf)

---

*Last Updated: April 2026*

