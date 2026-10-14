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

