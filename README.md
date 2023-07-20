
# Aspect Score

It is an ArcGIS module that allows the aspect factor used in analyzes to switch from subjective scoring to objective scoring.

Calculates the aspect score of an area based on the aspect directions. An additional parameter should be set as to define which direction should be full scored. It scores between 0 to 1. In this scoring, you determine the maximum aspect score you will receive.

# How to Install
Tested with Arcmap10.8.

1. Download the Aspect Score.tbx file.
2. Open Arcmap. :)
3. Find the location of the tbx file with ArcCatalog.
4. You will see the model in the .tbx. You can start directly. Check out the parameters below.

# Parameters
There are 6 parameters that need to be explained about the module.

**1) Layer:** Feature for which the aspect score is to be calculated. This layer must be polygon or polyline

**2) Constant Field:** Constant field in the Feature for which the aspect score is to be calculated. With zonal statistic, the outputs produced from raster data take the average value of the aspect score in the feature and then match according to the column. This column must be a literal column. It is recommended to select "OBJECTID".

**3) Projection:** Projection fixation to avoid coordinate errors

**4) Field Boundary:** Boundaries around the area

**5) Contour Lines:** Contour Curves will be used in Aspect analysis.

**6) Max Aspect Score Direction:** Calculates the aspect score of an area based on the north and south directions. North directions are given a score close to 0, while south directions are given a score close to 1. Scoring is calculated with a custom-made sine curve. This scoring method was made in accordance with forest roads and landslide areas. While forest roads are line features, landslide areas are polygon features.

## Direction - Degrees

| Aspect             | Degree                                                                |
| ----------------- | ------------------------------------------------------------------ |
| North | 0 and 360 degrees |
|Northeast: |45 degrees|
|East: |90 degrees|
|Southeast: |135 degrees|
|South: |180 degrees|
|Southwest: |225 degrees|
|West: |270 degrees|
|Northwest: |315 degrees|
## Screenshot

![Screenshot of Module](https://tahayasin.com/aspect_score/Screenshot.jpg)

  
## Used technologies

**Program:** ArcGIS, ArcMap

**Language:** ArcPy

  
## Radar Plot Svg of Landslide Areas and Forest Roads

Demoya gif veya bağlantı ekleyin

  Landslide Areas: 
  https://tahayasin.com/aspect_score/All_Landslides.svg

  Forest Roads:
  https://tahayasin.com/aspect_score/All_Forest_Roads.svg
## Users

This project may be preferred by the following users:

- Forest Engineers
- Survey Engineers
- Landscape Architects
- Environmental Engineers
- Urban and Regional Planner
- Mining engineer

.. professional groups dealing with land planning and analysis

  
## Feedback

If you have any feedback, please contact us at tyhatay@ktu.edu.tr.

  
## Thanks

- thanks to [@zubeyir91](https://www.github.com/zubeyir91

  
