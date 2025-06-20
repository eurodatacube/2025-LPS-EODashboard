## TITLE ##

At night, on the surface of our planet, multiple sources of illumination, such as streetlights, buildings and ships can be seen from space. These **nighttime lights** are a reliable proxy for measuring the scope and intensity of **human activity**.
Nighttime lights can be applied across a wide range of studies, from analyzing trends in urbanization — such as tracking urban expansion, or estimating population distribution.

<figure style="text-align: center;">
    <img src="https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2013/10/night_lights/13355175-1-eng-GB/Night_lights_pillars.jpg" 
         alt=" Photograph taken from onboard the International Space Station showing a nighttime Paris and London. . " 
         style="display: block; margin: 0 auto;"
         width="800								">
    <figcaption>
         Photograph taken from onboard the International Space Station showing a nighttime Paris and London. Credit: 
        <a href="https://www.esa.int/ESA_Multimedia/Search?SearchText=nighttime+lights&result_type=images" target="_blank">
             ESA/NASA
        </a>.
    </figcaption>
</figure>

###  SUBTITTLE ###
One source of nighttime light imagery is the Visible Infrared Imaging Radiometer Suite (VIIRS) aboard the  [Suomi National Polar-orbiting Partnership (Suomi NPP)](https://eospso.nasa.gov/missions/suomi-national-polar-orbiting-partnership), a joint mission of the National Oceanic and Atmospheric Administration ([NOAA](https://www.noaa.gov/)) and [NASA](https://www.nasa.gov/). This satellite makes global daily measurements of nocturnal visible and near-infrared (NIR) light that can be used for Earth system science and applications, allowing to observe signals such as city lights, gas flares, fishing vessels, aurora, gravity waves and wildfires.  

##  EXPLORING THE DATASET (map tour)

##  Visualization<!--{ as="eox-map" mode="tour" }-->
### <!--{ layers='[{"type":"Tile","properties":{"id":"Overlay labels"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/overlay_base_bright_3857/default/g/{z}/{y}/{x}.jpg"]}},{"type":"Tile","properties":{"id":"JAXA_Nighttimelevel_Urban"},"source":{"type":"TileWMS","urls":["https://services.sentinel-hub.com/ogc/wms/0635c213-17a1-48ee-aef7-9d1731695a54"],"params":{"layers":"JAXA-NIGHTTIMELEVEL-URBAN","styles":"","format":"image/png","time":"2019-01-01T00:00:00Z"}}},{"type":"Tile","properties":{"id":"Terrain light"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/terrain-light_3857/default/g/{z}/{y}/{x}.jpg"]}}]' zoom="7.568167497148919" center=[-81.69190982357188,36.13000317868601] animationOptions={duration:500}}-->
#### TITLE OF THE SIDE PANEL
This dataset is valuable for studying the distribution of artificial lighting in urban regions, offering insights into urban growth, infrastructure development, and socio-economic activity.
<figure style="text-align: center;">
    <img src="https://eospso.nasa.gov/sites/default/files/sat/Suomi-NPP.jpg" 
         alt=" Sea ice concentration in May 2023. " 
         style="display: block; margin: 0 auto;"
         width="500">
    <figcaption>
         SUOMI-NPP Satellite. Source:
        <a href="https://eospso.nasa.gov/missions/suomi-national-polar-orbiting-partnership" target="_blank">
             NASA
        </a>.
    </figcaption>
</figure>


### <!--{ layers='[{"type":"Tile","properties":{"id":"Overlay labels"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/overlay_base_bright_3857/default/g/{z}/{y}/{x}.jpg"]}},{"type":"Tile","properties":{"id":"JAXA_Nighttimelevel_Urban"},"source":{"type":"TileWMS","urls":["https://services.sentinel-hub.com/ogc/wms/0635c213-17a1-48ee-aef7-9d1731695a54"],"params":{"layers":"JAXA-NIGHTTIMELEVEL-URBAN","styles":"","format":"image/png","time":"2019-01-01T00:00:00Z"}}},{"type":"Tile","properties":{"id":"Terrain light"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/terrain-light_3857/default/g/{z}/{y}/{x}.jpg"]}}]' zoom="9.823650315180059" center=[-73.99550312972447,40.83001718614142] animationOptions={duration:500}}-->
#### 
This dataset metrics, are 'nighttime radiance values' (measured in nanowatts per square centimeter per steradian, nW/cm²/sr), which represent the brightness of artificial lighting in urban areas. From this, the Nighttime Light Intensity (NTLI) can be generated, a composite of observations reflecting the overall intensity of visible nighttime lights in urban landscapes.
<figure style="text-align: center;">
    <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flive.staticflickr.com%2F8745%2F16384318544_178f2f5482_b.jpg&f=1&nofb=1&ipt=25829b7e1b15806e923ac37a1f3283fca53fcec2090012dc5cd4fa2d91cceaa7&ipo=images" 
         alt=" " 
         style="display: block; margin: 0 auto;"
         width="800
								">
    <figcaption>
        Times Square at night, New York. Credit: 
        <a href="https://www.flickr.com/photos/106447493@N05/16384318544" target="_blank">
             Leon Yaakkov
        </a>
    </figcaption>
</figure>


## Open-sience: Jupyter Notebook 
To further promote Open Science we can also share here the  [notebook](https://hub.eox.at/services/eoxhub-gateway/eurodatacube/notebook-view/notebooks/contributions/NightLights/Night_Lights_Blending.ipynb) (which reproduces the method developed by Professor Tojo allowing to visualize urban expansion and infrastrucutre development using additive color blending - i.e. assigning different years to RGB channels to reveal where artificial areas increased (which could be linked to economic growth) or decreased (suggesting reduced activity).

<figure style="text-align: center;">
    <img src="https://github.com/eurodatacube/eodash-assets/blob/main/stories/Nightlights/nightime_notebook_image.jpg?raw=true" 
         alt=" . " 
         style="display: block; margin: 0 auto;"
         width="500">
    <figcaption>
         Jupyter Notebook: Nightime Lights with SUOMI NPP.
        <a href="https://hub.eox.at/services/eoxhub-gateway/eurodatacube/notebook-view/notebooks/contributions/NightLights/Night_Lights_Blending.ipynb" target="_blank">
             Access the Notebook
        </a>.
    </figcaption>
</figure>

[Access the notebook](https://hub.eox.at/services/eoxhub-gateway/eurodatacube/notebook-view/notebooks/contributions/NightLights/Night_Lights_Blending.ipynb) to analyze trends, and uncover patterns of human activity on a location of your choice. 
