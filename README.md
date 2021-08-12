![image](https://user-images.githubusercontent.com/44501803/127709395-3b5a8649-cae6-4e78-b3d6-0097826bb302.png)![image](https://user-images.githubusercontent.com/44501803/127709433-c75615c3-fc0f-4641-b563-f6fc32bfa422.png)

![image](https://user-images.githubusercontent.com/44501803/127249693-217ac1bb-7cda-4978-8d78-45afd7fa6d5e.png)![image](https://user-images.githubusercontent.com/44501803/127577117-1e505edc-27b1-49ad-b5f0-7cf2405b663e.png)

### :globe_with_meridians: 𝚙𝚢𝚝𝚑𝚘𝚗 𝚊𝚙𝚕𝚒𝚌𝚊𝚍𝚘 𝚊𝚕 𝚊𝚗𝚊𝚕𝚒𝚜𝚒𝚜 𝚍𝚎𝚕 𝚎𝚜𝚙𝚊𝚌𝚒𝚘 𝚞𝚛𝚋𝚊𝚗𝚘 :globe_with_meridians:
--------------------------------------------------------------------------------------------

`AU</>Py` es un repositorio que recopila un conjunto de técnicas de **análisis urbano con python**. A través de las mismas, se busca facilitar el trabajo con  distintas dinámicas del espacio urbano y brindar una serie de recursos que conformen un primer kit de herramientas para todo aquel interesado en sumergirse en el mundo de la **ciencia de datos urbanos**. 

#### Modulo 1: Introducción al manejo de datos geográficos

* Funciones regulares y anónimas: `map`, `apply`, `applymap` y `lambda x`
* `Geopandas`: GeoDataFrames y GeoSeries
* Tipos de geometrías, atributos y métodos disponibles con `shapely` 
* Sistemas de coordenadas (CRS) y reproyecciones
* Operaciones espaciales (spatial join, overlay y dissolve)

#### Modulo 2: Enriquecimiento, geolocalización y visualización

* `APIs` y `requests`
* Normalización de direcciones
* Geolocalización
* Enriquecimiento de entidades geográficas
* Visualización (`Contextily`, `Leaflet`, `Folium`)
* `Folium`: Markers, Cluster markers, Mapas de calor, Choropletas, etc.

#### Modulo 3: Fuentes de datos secundarios

* Unidades geoestadísticas (CNPHV-Indec)
* Construccuón de Coropletas: `pysal/mapclassify`
* Esquemas de clasificación: `NaturalBreaks` vs `FisherJenks`
* Construcción de clases y objetos con fuentes censales
* Conjuntos de datos en [GoogleBigQuey](https://drive.google.com/file/d/1IyXAvy_ndGl-LsXvP2wNSalg02EMoCfH/view?usp=sharing) 
* Ajustes por inflación para series de precios de alquiler

#### Modulo 4: Grafos y redes de transporte

* Visualización de redes dinámicas: `Plotly`
* Manipulación de nodos y arcos, tipos de grafos y direccionalidad, métricas de conectividad y centralidad de una red: `NetworkX`
* Descarga de geometrías, formas de construcción de un grafo, simplificación de una red, estadísticas básicas y extendidas, betweenness centrality and shortest path routing: `OSMNx`

#### Modulo 5: Clustering

