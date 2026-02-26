# flood-risk-assessment-of-lumbini-province

This project demonstrates a comprehensive **Flood Risk Assessment** conducted for **Lumbini Province, Nepal**, using advanced GIS and spatial analysis tools in **ArcGIS Desktop**. A **multi-criteria evaluation** approach was used, integrating several spatial parameters that influence flood vulneribility. <br>
The resulting map highlights flood prone areas. This provides valuable insights for, **Disaster Risk Management Agencies**, **Urban & Regional Planners and Environmental Researchers**.
<hr>

Required raster data for Flood Risk Assessment were downloaded from USGS Earth Explorer.

<hr>

Step 1: Imported ShapeFile of Study Area
<br>
<br>

Step 2: Imported DEM of Study Area
<br>
<br>

Step 3: Generated Slope Raster using DEM
<br>
<br>

Step 4: Prepared LULC of study Area
<img width="1400" height="1010" alt="image" src="https://github.com/user-attachments/assets/22b138c8-c56c-4919-9ea0-55a5bf5d18b0" />
<br>
<br>

Step 5: Loaded precipitation data of wet weather
<br>
<br>

Step 6: Determined Proximity to Streams:<br>
  -> Performed hydrological analysis to extract Streams (fill, flow direction, flow accumulation)<br>
  -> Reclassified flow accumulation to obtain main streams. then calculated Eculidean Distance.
<br>
<br>

Step 7: Reclassified each of the layers from 0 to 10.<br>
  -> 0 Being Low Flood Risk and 10 Being High Flood Risk.<br>
<br>
<br>

Step 8: **Assigning influencial factor**<br>
                            Elevation: 10%<br>
                            Slope: 15%<br>
                            LULC: 10%<br>
                            Precipitation: 35%<br>
                            Proximity to Stream: 30%<br>
<br>

Step 9: **Finally, reclassified the weighted raster in 5 classes**<br>
            1 => very low risk<br>
            2 => low risk<br>
            3 => moderate risk<br>
            4 => high risk<br>
            5 => very high risk<br>
<img width="1436" height="1013" alt="image" src="https://github.com/user-attachments/assets/1132d64b-2771-4636-9189-2e4b841a6590" />
