---
title: Technical Assignment 1
order: 8
part: course portfolio
---
University of Virginia
DH 8991-001: Introduction to Digital Humanities (Fall 2026)
Gabriel Santos de Oliveira
Technical Assignment 1

  The first technical assignment I would like to discuss briefly here relates to GIS maps I produced this semester. I worked with Drew, the Scholars’ Lab GIS specialist, for two weeks to learn how to cross different georeferenced variables and interpret their geographical relationships. In this instance, Drew helped me georeference Amazonian rivers with archaeological sites previously mapped by 2 other archaeologists, Arellano Lopez and Sanna Saunaluoma, which could indicate that people in the Amazonian past used rivers as geographical markers for constructing geometric sites.
  Drew helped me compile the two datasets provided by  Arellano Lopez and Sanna Saunaloma and created two .kmz archives with the archaeological sites geographically referenced. During this initial geospatial analysis, I downloaded a vector from Humanitarian Data Exchange  that plotted and named all Bolivian rivers, which helped me situate the sites in relation to the waterways. Beyond that, raster layers from portals such as MapBiomas Bolivia  helped me understand distinct natural characteristics of Amazonian environments.
  Initially, I plotted the sites based on previous archaeological work, followed by a cross-sectional analysis, which showed a clear spatial distribution pattern: all the sites are either at river confluences or close to them.

{% include essay/feature/image-gallery.html
   objectid="/assets/img/ta1-map1-surveys.jpg"
   alt="Map of the Bolivian departments of Pando and Beni. White circles mark sites from Arellano’s survey and red diamonds mark sites from Saunaluoma’s survey, spread across northern Pando from Porvenir in the west to Loma Alta in the east."
   caption="Map 1: Archaeological Reconnaissance in Pando and Beni (Bolivia) – Arellano’s and Saunaluoma’s Surveys."
   width="75" %}

{% include essay/feature/image-gallery.html
   objectid="/assets/img/ta1-map2-rivers.jpg"
   alt="The same map of Pando and Beni with the main rivers labeled, including the Tahuamanu, Manuripi, Madre de Dios, Orthon, Negro and Beni. The survey sites lie along and between these rivers."
   caption="Map 2: Archaeological Reconnaissance in Pando and Beni in Relation to Rivers."
   width="75" %}

  After that, Drew helped me apply hillshades and Euclidean distances to my GIS data to capture deeper geographical relationships between sites and rivers based on topography and distance. For example, based on Arellano Lopez’s data, the distance from the Porvenir site to the Loma Alta site is 296km along the Orthon-Tahuamanu margins, which may suggest an even more extensive network of sites at the mouths of other rivers.
  The Euclidean Distance created in ArcGIS Pro only showed the obvious intrinsic relationship between rivers and some earthworks, by suggesting that the further away the rivers are, the harder it is to see sites – based on the two available archaeological surveys.

{% include essay/feature/image-gallery.html
   objectid="/assets/img/ta1-map3-hillshade.jpg"
   alt="Colored hillshade relief map of Pando and Beni. A black line labeled 296 km distance connects the Porvenir site in the west to the Loma Alta site in the east, with the other survey sites marked along the way."
   caption="Map 3: Hillshade with DEM showing the archaeological sites and the distance between Porvenir and Loma Alta."
   width="75" %}

{% include essay/feature/image-gallery.html
   objectid="/assets/img/ta1-map4-euclidean.jpg"
   alt="Map titled Euclidean Distance – Archaeological Sites in Relation to Rivers. A shaded surface in green and yellow shows Euclidean distance, with the survey sites and river names marked."
   caption="Map 4: Euclidean Distance of the recorded archaeological sites in relation to rivers."
   width="75" %}

  Although very preliminary, the results of this spatial analysis are interesting because they show a clear relationship between the earthworks in Pando (mainly) and Beni and the rivers. This suggests a logic that links the construction of these sites to a specific strategy for capturing water resources and, in my work, will help me begin my archaeological research in Bolivia. As mentioned, rivers are not the only natural feature that may have influenced how indigenous peoples built their settlements in the past, but they are still relevant. Talking to local people about rivers and their functions, and perhaps following their paths to see whether there are earthworks, is a potential strategy for developing a systematic mapping of sites. Drew’s help over these two weeks was pivotal to advancing the spatial analysis for my dissertation.

References
Saunaluoma, Sanna. "Pre-Columbian Earthworks in the Riberalta Region of the Bolivian Amazon." Amazônica: Revista de Antropologia 2, no. 1 (2010): 104–138.
Arellano López, Jorge. 2002. Reconocimiento arqueológico de la cuenca del Río Orthon, Amazonía boliviana. Quito: Museo Jacinto Jijón y Caamaño; Taraxacum.


