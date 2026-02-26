# flood-risk-assessment-of-lumbini-province

Required raster data for Flood Risk Assessment were downloaded from USGS Earth Explorer.



**Procedure Followed**

Step 1
Imported ShapeFile of Study Area

Step 2
Imported DEM of Study Area

Step 3
Generated Slope Raster using DEM

Step 4
Prepared LULC of study Area
<img width="1400" height="1010" alt="image" src="https://github.com/user-attachments/assets/22b138c8-c56c-4919-9ea0-55a5bf5d18b0" />

Step 5
Loaded precipitation data of wet weather

Step 6
To determine Proximity to Streams:
  -> Performed hydrological analysis to extract Streams (fill, flow direction, flow accumulation)
	-> Reclassified flow accumulation to obtain main streams. then calculated Eculidean Distance.

Step 7
Reclassified each of the layers from 0 to 10.
  -> 0 Being Low Flood Risk and 10 Being High Flood Risk.

Step 8
**Assigning influencial factor**
                            Elevation: 10%
                            Slope: 15%
                            LULC: 10%
                            Precipitation: 35%
                            Proximity to Stream: 30%

Step 9
** Finally, reclassified the weighted raster in 5 classes **
            1 => very low risk
            2 => low risk
            3 => moderate risk
            4 => high risk
            5 => very high risk
<img width="1436" height="1013" alt="image" src="https://github.com/user-attachments/assets/1132d64b-2771-4636-9189-2e4b841a6590" />
