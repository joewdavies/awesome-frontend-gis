<!--lint disable awesome-heading awesome-git-repo-age awesome-github double-link awesome-toc-->

<div>
    <a href="https://github.com/eurostat/gridviz" target="_blank">
        <img src='https://user-images.githubusercontent.com/25485293/191950255-cbd83c6a-4880-4c0a-a665-b59a21467702.PNG'>
    </a>
</div>

<h2 align="center">Awesome Frontend GIS</h2>

<p align="center">
  A compilation of geospatial-related frameworks, tools, demos, applications, data sources and more - all for use on the browser.
  <br />
  <br />
  <a href="https://github.com/sindresorhus/awesome">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome" href="https://github.com/sindresorhus/awesome">
  </a>
  &nbsp;
  <a href="https://github.com/sindresorhus/awesome-lint">
    <img src="https://github.com/joewdavies/awesome-frontend-gis/workflows/Lint/badge.svg" alt="Lint status">
  </a>
  <br />
  <br />
</p>



## Contents
- [**JS Libraries**](#js-libraries)
  - [Mapping](#mapping) 
      - [Map viewers](#map-viewers) 
      - [Thematic mapping](#thematic-mapping) 
      - [D3-based](#d3-based)
  - [Data analysis](#data-analysis)
  - [LiDAR](#lidar)
  - [Remote Sensing](#remote-sensing)
- [**Data sources**](#data-sources)
  - [Downloads](#downloads)
  - [Web APIs](#web-apis)
       - [Routing](#routing)
  - [Collections](#collections)
- [**Notebooks**](#notebooks)
- [**Web maps**](#web-maps)
- [**Web apps**](#web-apps)
- [**Colour advice**](#colour-advice)
- [**Videos**](#videos)
- [**Further reading**](#further-reading)
- [**Contributing**](#Contributing)

## JS Libraries 

### Mapping 
Libraries for building maps.

#### Map viewers 
Map engines for visualizing geospatial data.
- [Leaflet](https://leafletjs.com/) - The leading open-source JavaScript library for mobile-friendly interactive maps.
- [OpenLayers](https://openlayers.org/) - A high-performance, feature-packed library for creating interactive maps on the web.
- [Cesium.js](https://cesiumjs.org/) - An open-source JavaScript library for world-class 3D mapping of geospatial data.
- [ArcGIS API for JS](https://developers.arcgis.com/JavaScript/latest/release-notes/) - A lightweight way to embed maps and tasks in web applications.
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/examples/) - JavaScript library that uses WebGL to render interactive maps from vector tiles.
- [maplibre](https://github.com/maplibre/maplibre-gl-js) - It originated as an open-source fork of mapbox-gl-js, before their switch to a non-OSS license in December 2020.
- [MapTalks.js](https://github.com/maptalks/maptalks.js) - An open-source JavaScript library for integrated 2D/3D maps.
- [antvis L7](https://github.com/antvis/L7) - Large-scale WebGL-powered Geospatial Data Visualization.
- [Tangram](https://github.com/tangrams/tangram) - WebGL map rendering engine for creative cartography.
- [Three.js](https://github.com/mrdoob/three.js) - Easy to use, lightweight, cross-browser, general purpose 3D library.
- [Procedural GL JS](https://github.com/felixpalmer/procedural-gl-js) - Procedural GL JS is a library built on top THREE.js for creating 3D maps on the web.
- [iTowns](https://github.com/iTowns/itowns) - A Three.js-based framework written in JavaScript/WebGL for visualizing 3D geospatial data.
- [globe.gl](https://globe.gl/) - This library is a convenience wrapper around the three-globe plugin, and uses ThreeJS/WebGL for 3D rendering.
- [ArcGIS API for JS v4](https://developers.arcgis.com/javascript/) - A lightweight way to embed maps and tasks in web applications.
- [Wrld.js](https://github.com/wrld3d/wrld.js/) - Animated 3D city maps based on Leaflet.
- [Deck.GL](https://github.com/uber/deck.gl) - WebGL2 powered geospatial visualization layers.
- [harp.gl](https://github.com/heremaps/harp.gl) - An experimental and work in progress open-source 3D map rendering engine.
- [HERE maps API](https://developer.here.com/develop/javascript-api) - Build web applications with feature-rich and customizable HERE maps.

#### Thematic mapping 
For mapping a particular theme to a geographic area. Think of them as cartographic dataviz.
- [Eurostat-map](https://github.com/eurostat/eurostat-map.js) - Create and customise web maps showing Eurostat data using D3.js.
- [Bertin.js](https://github.com/neocarto/bertin) - A JavaScript library for visualizing geospatial data and making thematic maps for the web.
- [gridviz](https://github.com/eurostat/gridviz) - A Three.js-based library for visualizing gridded statistics datasets as CSV files. 
- [regl-map-animation](https://github.com/eurostat/regl-map-animation) - Animate x/y point data using regl and categorize them into a bar chart.

#### D3-based

Mapping libraries and plugins based on the [D3 data visualization library](https://observablehq.com/@d3/gallery). Thanks to [awesome-d3](https://github.com/wbkd/awesome-d3).

- [d3-carto-map](https://github.com/emeeks/d3-carto-map) - A mapping API that uses D3 geospatial functionality.
- [d3-composite-projections](https://github.com/rveciana/d3-composite-projections) - Projections for showing countries' distant lands together.
- [datamaps](https://github.com/markmarkoh/datamaps) - Customizable map visualizations in one file.
- [d3-topogram](https://github.com/shawnbot/topogram) - Continuous area cartograms based on TopoJSON.
- [d3-exploder](https://github.com/bsouthga/d3-exploder) - Lets you easily move and resize geographic features.
- [d3-geo](https://github.com/d3/d3-geo) - A library for creating maps based on D3.js.
- [d3-geo-polygon](https://github.com/d3/d3-geo-polygon) - Clipping and geometric operations for spherical polygons.
- [d3-geo-projection](https://github.com/d3/d3-geo-projection) - Extended geographic projections.
- [d3-geo-scale-bar](https://github.com/HarryStevens/d3-geo-scale-bar) - Displays automatic scale bars for projected geospatial data.
- [d3-geo-voronoi](https://github.com/Fil/d3-geo-voronoi) - Voronoi diagrams and Delaunay triangulation for the sphere.
- [d3-geomap](https://github.com/yaph/d3-geomap) - Library for creating geographic maps.
- [d3.geo2rect](https://github.com/sebastian-meier/d3.geo2rect) - Morphing geojson polygons into rectangles.
- [d3-inertia](https://github.com/Fil/d3-inertia) - An extension to d3-drag that continues the mouse movement with some inertia.
- [earthjs](https://github.com/earthjs/earthjs) - Building orthographic globe with SVG, Canvas & WebGL.
- [mapmap.js](https://github.com/floledermann/mapmap.js) - A data-driven API for interactive thematic maps.
- [mapsense.js](https://github.com/mapsense/mapsense.js) - Full resolution vector maps with D3.
- [maptable](https://github.com/Packet-Clearing-House/maptable) - Convert datasets to a set of visual components (Map, Filters, Table).
- [simple-map-d3](https://github.com/MinnPost/simple-map-d3) - Easy choropleth style maps.
- [spam](https://github.com/newsappsio/spam) - Create maps with D3 and Canvas, easily.
- [leaflet-d3](https://github.com/Asymmetrik/leaflet-d3) - Collection of plugins for using D3 with Leaflet.
- [react-d3-basic](https://github.com/react-d3/react-d3-basic) - Library For Building Composable And Declarative Maps.
- [Wikimaps-D3js Atlas](https://github.com/WikimapsAtlas/WikimapsAtlas-generator) - CLI to generate raster, topojson and svg maps.
- [react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) - An SVG mapping component library for React, built on top of d3-geo.

### Data analysis 
Libraries that help you analyse and process geospatial data.
- [Turf.js](https://github.com/Turfjs/turf) - Turf is a JavaScript library for spatial analysis.
- [Proj4js](https://github.com/proj4js/proj4js) - Transform coordinates from one coordinate system to another, including datum transformations.
- [GeoTiff.js](https://github.com/geotiffjs/geotiff.js) - Parse TIFF files for visualization or analysis.
- [Arc.js](https://github.com/springmeyer/arc.js) - Calculate great circles routes as lines in GeoJSON or WKT format.
- [awesome-GeoJSON](https://github.com/tmcw/awesome-geojson) - Catalogue of GeoJSON tools.
- [topoJSON](https://github.com/topojson/topojson) - Convert GeoJSON to TopoJSON for use in D3 maps.
- [Wicket](https://github.com/arthur-e/Wicket) - A modest library for moving between Well-Known Text (WKT) and various framework geometries.
- [koop](https://github.com/koopjs/koop) - Koop is a JavaScript toolkit for connecting incompatible spatial APIs.
- [spl.js](https://github.com/jvail/spl.js) - Makes it possible to use SpatiaLite functionality in JavaScript. Behind the scenes, a WebAssembly port of SpatiaLite is used.
- [geotoolbox](https://github.com/neocarto/geotoolbox) - Provides several GIS operations for use with geojson properties. Useful for thematic cartography.
- [supercluster](https://www.npmjs.com/package/supercluster) - A very fast JavaScript library for geospatial point clustering for browsers and Node.
- [geoblaze](https://github.com/GeoTIFF/geoblaze) - A blazing fast JavaScript raster processing engine. Using geoblaze, you can run computations ranging from basic statistics (min, max, mean, mode) to band arithmetic and histogram generation in either a web browser or a node application.

### LiDAR
Tools for visualizing point clouds.
- [Potree](https://github.com/potree/potree) - WebGL point cloud viewer for large datasets.
- [Plasio](https://github.com/verma/plasio) - Drag-n-drop In-browser LAS/LAZ point cloud viewer.
- [Potree & Cesium.js](http://potree.org/potree/examples/cesium_retz.html) - Rezt, Austria LIDAR viewer.
- [Three.js](https://threejs.org/examples/#webgl_loader_pcd) - Point cloud data loader.

### Remote Sensing
- [Google Earth Engine](https://developers.google.com/earth-engine/tutorials/tutorial_api_01) - Google Earth Engine is a geospatial processing service. With Earth Engine, you can perform geospatial processing at scale, powered by Google Cloud Platform.
- [sentinelhub-js](https://github.com/sentinel-hub/sentinelhub-js/) - Download and process satellite imagery in JavaScript or TypeScript using Sentinel Hub services.
- [Sentinel Hub custom scripts](https://github.com/sentinel-hub/custom-scripts) - A repository of custom scripts to be used with Sentinel Hub.
- [Spectral](https://github.com/awesome-spectral-indices) - Awesome Spectral Indices for the Google Earth Engine JavaScript API (Code Editor).


## Data sources 
A collection of geospatial open data sources.

### Downloads 
Data available for download.
- [OpenMapTiles](https://openmaptiles.org/) - Free OpenStreetMap Vector Tiles.
- [OpenStreetMap](https://www.geofabrik.de/data/download.html) - A free, world-wide geographic data set.
- [Natural Earth](https://www.naturalearthdata.com/) - Free vector and raster map data at 1:10m, 1:50m, and 1:110m scales.
- [Copernicus global DEM](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/elevation/copernicus-dem/elevation) - Global elevation tiles.
- [ETOPO1](https://www.ngdc.noaa.gov/mgg/global/) - 1 arc-minute global relief model of Earth's surface that integrates land topography and ocean bathymetry.
- [HydroSHEDS](https://www.hydrosheds.org/) - Hydrographic information in a consistent and comprehensive format for regional and global-scale applications.
- [geoboundaries](https://www.geoboundaries.org/) - The world's largest open, free and research-ready database of political administrative boundaries.
- [Global power plant database](https://datasets.wri.org/dataset/globalpowerplantdatabase) - A comprehensive, global, open source database of power plants.
- [Ookla internet speed data](https://github.com/teamookla/ookla-open-data) - Provides global network performance metrics. Data is provided in both Shapefile format as well as Apache Parquet.

### Web APIs 
Restful APIs for consuming geospatial data on the fly.

- [REST counrties](https://restcountries.com/) - Get information about countries via a RESTful API.
- [USGS earthquake data](https://earthquake.usgs.gov/fdsnws/event/1/) - Allows custom searches for earthquake information using a variety of parameters.
- [movebank-api](https://github.com/movebank/movebank-api-doc) - Movebank is a free, online database and research platform for animal tracking and other on-animal sensor data. 
- [Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API) - Retrieve OpenStreetMap data.
- [Open Notify](http://open-notify.org/Open-Notify-API/) - Get the current location of the International Space Station (ISS) and current number of people in space!

#### Routing 
- [openrouteservice](https://openrouteservice.org/dev/#/api-docs) - Directions, Isochrones, Time-Distance Matrix, Pelias Geocoding, POIs, Elevation, Optimization.
- [GraphHopper Route Optimization API](https://www.graphhopper.com/route-optimization/) - Solves a variety of vehicle routing problems, including the classical “traveling salesman problem”.

### Collections 
Compilations and repositories of open datasets.
- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) - An awesome repository full of open datasets from an abundance of different categories.
- [Free GIS data](https://freegisdata.rtwilson.com/) - Links to over 500 sites providing freely available geographic datasets.
- [WRI](https://www.wri.org/data) - World resources institute.
- [Public APIs](https://github.com/public-apis/public-apis) - A collective list of free APIs for use in software and web development.

## Notebooks 
Some JavaScript notebooks to help you code.

- [Try to impeach this? Challenge accepted!](https://observablehq.com/@karimdouieb/try-to-impeach-this-challenge-accepted) - Karim Douieb.
- [Bars and pubs in Paris](https://observablehq.com/@neocartocnrs/bars-pubs-in-paris) - Nicolas Lambert.
- [How to make a nice scalebar](https://observablehq.com/@jgaffuri/nice-scale-bar) - Julien Gaffuri.
- [Brussels Street Gender Inequality](https://observablehq.com/@karimdouieb/brussels-streets-gender-inequality) - Karim Douieb.
- [Visualizing earthquakes with Three.js](https://observablehq.com/@joewdavies/visualizing-earthquakes-with-three-js) - Joe Davies.
- [Animating voting maps with regl](https://observablehq.com/@bmschmidt/animating-voting-maps-with-regl) - Benjamin Schmidt.
- [Hello, Bertin.js](https://observablehq.com/@neocartocnrs/hello-bertin-js) - Nicolas Lambert.
- [Election maps as dorling striped circles](https://observablehq.com/@jgaffuri/election-map-dorling-striped-circles) - Julien Gaffuri.
- [Visualizing Eurostat grid data using Three.js & D3](https://observablehq.com/@joewdavies/visualizing-eurostat-grid-data-using-three-js-d3) - Joe Davies.
- [GeoParquet on the web](https://observablehq.com/@kylebarron/geoparquet-on-the-web) - Kyle Barron.
- [Interactive Regl wind demo](https://observablehq.com/@dkaoster/interactive-regl-wind-demo) - Daniel Kao.
- [Bivariate Choropleth with Continuous Color Scales](https://observablehq.com/@stephanietuerk/bivariate-choropleth-with-continuous-color-scales) - Stephanie Tuerk.
- [Hexgrid maps with d3-hexgrid](https://observablehq.com/@larsvers/hexgrid-maps-with-d3-hexgrid) - Larsvers.
- [Dorling cartogram of the Spanish Presidential election](https://observablehq.com/@adrianblanco/dorling-cartogram-of-the-spanish-presidential-election) - Adrián Blanco.



## Web maps 
A compilation of interesting web maps.
- [Map of notable people](https://tjukanovt.github.io/notable-people) - Topi Tjukanov.
- [Submarine cable map](https://www.submarinecablemap.com/) - TeleGeography.
- [Radio Garden](https://radio.garden/) - 3D Globe Radio Tuner.
- [Map of every building in the United States](https://www.nytimes.com/interactive/2018/10/12/us/map-of-every-building-in-the-united-states.html) - New York Times.
- [Map of the Roman transport network](https://orbis.stanford.edu/) - The Stanford Geospatial Network Model of the Roman World.

## Web apps 
Plug-and-play geospatial web apps!

- [city roads](https://anvaka.github.io/city-roads/) - Render every single road in any city at once.
- [Kepler](https://kepler.gl/demo) - A powerful open source geospatial analysis tool for large-scale data sets.
- [Plasio](https://github.com/verma/plasio) - Drag-n-drop In-browser LAS/LAZ point cloud viewer.
- [mapshaper](https://mapshaper.org/) - Online editor for map data.
- [geotiff.io](http://app.geotiff.io/) - GeoTIFF.io provides quick access to easy-to-use raster processing.
- [StoryMap JS](https://storymap.knightlab.com/) - The Open source alternative to ESRI's Story map application.

## Colour advice 
Tools to help you choose the best colours for your maps.
- [ColorBrewer](https://colorbrewer2.org/) - Colour advice for maps.
- [viz-palette](https://projects.susielu.com/viz-palette) - This project is optimized for tweaking, copying, and pasting colors in and out of JavaScript.
- [Chroma.js Color Palette Helper](https://gka.github.io/palettes/#/9) - This chroma.js-powered tool is here to help us mastering multi-hued, multi-stops color scales.

## Videos
Videos of web mapping presentations and tutorials.

- [Mapping Geolocation with Leaflet.js - Working with Data and APIs in JavaScript](https://www.youtube.com/watch?v=nZaZ2dB6pow) - The Coding Train.
- [10 Maps, and the Tech and Stories Behind Them](https://www.youtube.com/watch?v=PpWAKVjPlgU) - Maarten Lambrechts.
- [Intermediate Three.js Tutorial - Create a Globe with Custom Shaders](https://www.youtube.com/watch?v=vM8M4QloVL0&t=4418s) - Chris Courses.


## Further reading
- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) - Claus O. Wilke.
- [A Workbook for Interactive Cartography and Visualization on the Open Web](https://github.com/uwcartlab/webmapping) - Robert Roth, Carl Sack, Gareth Baldrica-Franklin, Yuying Chen, Rich Donohue, Lily Houtman, Tim Prestby, Robin Tolochko, Nick Underwood.
- [Thematic Mapping: 101 Inspiring Ways to Visualise Empirical Data](https://www.esri.com/en-us/esri-press/browse/thematic-mapping) - Kenneth Field.


## Contributing

- Please check for duplicates first.
- Keep descriptions short, simple and unbiased.
- Please make an individual commit for each suggestion.
- Add a new category if needed.

Thanks for your suggestions!

---

If you have any questions about this list, please don't hesitate to contact me [@joewdavies](https://twitter.com/joewdavies) on Twitter or [open a GitHub issue](https://github.com/joewdavies/awesome-frontend-gis/issues/new).
