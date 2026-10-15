# Edwards-Aquifer-Recharge-Zone-Development-Suitability
### Project Overview
GIS project aimed at analyzing development suitability across the Edwards Aquifer Recharge Zone. Involved the comparison of three different weighted models, which took land slope, impervious surface change, road accessibility, and population density into account

### Background Information
The Edwards Aquifer is an important source of water in Central Texas, especially in San Antonio and the Hill Country. 
It is important as it supplies drinking water to local communities, supports agriculture, and sustains many local ecosystems and springs.

I specifically looked at the Recharge Zone because that is where surface water and precipitation can access the groundwater system. This is also where contaminants can enter the system, making it important to ensure that development in the region is sustainable.

However, development has rapidly increased over the last few decades in Central Texas. Unsustainable development can lead to issues such as altered natural drainage patterns and increased runoff pollution. This makes the geographic analysis of development pressure across the recharge zone an important endeavor. 

### Methodology
In my suitability analysis, I incorporated four geographic criteria:

**Terrain Slope**- Flatter land got higher suitability values, as it is easier to develop.

**Road Accessibility**- Areas closer to major roads were assigned higher suitability values.

**Population Density**- More densely populated areas received higher suitability values.

**Impervious Surface Change**- This criterion measured the change in impervious surface from 2005 to 2025. Areas experiencing greater increases received higher suitability values.

Each criterion was standardized onto a five-point suitability score, going from very low to very high.
These criteria were then applied to several models with different weights, using the suitability modeler in ArcGIS Pro.

Protected lands identified under PAD-US GAP Status Codes 1–3 were excluded from the final suitability analysis. 

### Model Weighting Scenarios

| Criterion | Equal-Weight | Growth-Oriented | Infrastructure-Oriented |
|---|---:|---:|---:|
| Terrain slope | 25% | 10% | 15% |
| Road accessibility | 25% | 35% | 45% |
| Population density | 25% | 30% | 20% |
| Impervious surface change | 25% | 25% | 20% |

## Results
### Consensus Development Suitability 
This analysis identified areas classified as high or very high suitability across all three models. 

43,707 acres were identified, which represents around 6.7% of the eligible area.

![Consensus Development Suitability Map](Map%20Layouts/PNG%20Maps/Consensus%20Development%20Suitability.png)
### Model Agreement
Looks at how many models classified a location as suitable.


| Number of Models Identifying High Suitability | Area (Acres) |
|---|---:|
| 0 | 467,310 |
| 1 | 140,740 |
| 2 | 3,732 |
| 3 | 43,707 |

This shows that the three models considered the vast majority of land unsuitable. However, a substantial amount of land was identified as suitable by only one model. 

![Model Agreement Suitability Map](Map%20Layouts/PNG%20Maps/Edwards%20Aquifer%20Model%20Agreement%20Layout.png) 
### Equal-Weights Model
Gives equal weight to all the geographic criteria.

![Equal-Weights Suitability Map](Map%20Layouts/PNG%20Maps/Edward_Aquifer_Equal_Weights.png) 
### Growth-Oriented Model
Places greater emphasis on population density and road accessibility than the equal-weights model. Impervious change has the same weight, while terrain slope has a much smaller weight. 

![Growth-Oriented Suitability Map](Map%20Layouts/PNG%20Maps/Growth-Oriented%20Layout.png) 
### Infrastructure-Oriented Model
Assigns the largest weight to road accessibility, while the other three weights are decreased.

![Infrastructure-Oriented Suitability Map](Map%20Layouts/PNG%20Maps/Infrastructure-Oriented%20Layout.png) 

### Key Findings
1) 43,707 acres were identified by all 3 models as highly suitable.
2) Model weighting has a substantial effect on suitability calculation; there were 140,740 acres that were identified by only one model
3) Road accessibility was a particularly important criterion. About 99.4% of the acreage identified by only one model were in the Infrastructure-Oriented model.
4) Areas consistently classified as highly suitable are less sensitive to different weighting scenarios. 



