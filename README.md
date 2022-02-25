# When-Glaciers-Were-Cool
A workflow involving Landsat and SNOTEL data to visualize and evaluate changes in snow and ice cover on Mt. Baker over time.

Sydney Carr

## Background Information

Mount Baker is a 10,781 ft glacier-covered stratovolcano in Washington’s North Cascades with 1.79 km3 of volumetric snow and ice cover. Mount Baker has eleven named glaciers, the largest being the Coleman Glacier with a surface area of 5.2 km2. 

Glacial mass balance is dependent on snow accumulation and snow melt. At higher elevations, snowfall in the accumulation zone becomes glacier ice over time. At lower elevations, winter snow and glacier ice melt in the ablation zone. Between the accumulation and ablation zones, an equilibrium line can be determined to assess how a glacier is advancing or receding. Glaciers are susceptible to changes in precipitation and temperature, and physical changes over time are an important indicator of climate change.

## Objectives

Use Landsat imagery to visualize the glacial accumulation zone and ablation zone, and establish an equilibrium line.   
Is the equilibrium line advancing or receding over time?

Use SNOTEL datasets from the four stations at Mount Baker to build an annual snow accumulation and snowmelt timeseries.  
Is this consistent with accumulation and ablation observed from Landsat imagery? 


## Datasets

* Landsat-8   
* SNOTEL

## Tools/Packages

* Rasterio  
* Numpy  
* Matplotlib  
* Geopandas

## Methodology

Develop snow water equivalent timeseries plots from SNOTEL datasets to determine annual snow accumulation, peak snow water equivalent, and snow melt periods for Mount Baker.  


Extract the extents of Mount Baker from Landsat-8 raster imagery and create NDSI plots using visible and shorwave infared bands to visualize the clear extents of snow and ice cover on Mount Baker. 

Begin with more recent datasets to develop a workflow, perhaps using the SNOTEL timeseries to determine annual 'snow appearance', 'peak accumulation', and 'snow disappearance' dates from which to pull landsat imagery. From there, repeating the workflow with historic datasets to visualize and assess glacial trends at Mount Baker over time.


