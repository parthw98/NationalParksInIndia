# Guided Tour of National Parks In India

## Project Description and Goal
<p>This interactive web map gives a guided tour of major mational parks in India. It is a Storymap which provides geo-visual as well as textual information about different national parks which are major tourist attractions and fine vacation destinations for people to explore. These natural habitats are away from the crowded, noisy, and cemented urban cities providing an escape from the rigors of regular life into a natural landscape and oxygen rich habitats, with different categories of flora and fauna to see and make meaningful memories to cherish.</p>

<p>This map focuses on wildlife enthusiasts especially tiger enthusaists as well as avid wildlife species spotters. It also attracts the attention of people who are newly interrested in exploring the wildlife and vegetation available. This map is hosted on github, created using various programming libraries, and Atom as the base software editor.</p>

## Data Sources
<p> This project does not use any complicated data sources and sticks to simple coordinates, basemaps and their respective tiles, images, and text information in order to create a simple but interactive and user friendly experience for the user. The following table provides the data sources used.</p>

| Data        | Usage           | Type  |
| ------------- |:-------------:| -----:|
| text information      | description purposes | raster |
| images      | visualization     |   raster |
| coordinates | locational      |    vector |
| maptiles    | reference     | raster |

<p> The above vector as well as raster data sources provided an overall enriching user experience and pop-ups help in creating user interaction. The User interface is viberant and constitutes of beoth visual images which provide a visual understanding of the fauna that can be spotted at these national parks and provide the user with a pleasant visual delight of the wild forests sitting in concrete buildings with noise, air pollution, etc. giving them an escape into the wild from their regular lives. </p>
<p> The User interface also provides textual information to the user, providing him the knowledge about this place and giving him an idea of the relevance and importance of this national park for the animals, as well as the local people and tourists. The Web mapping design is of a classic story map by providing information in te form of text and image on the left that constitute the content of the map, while the right side of the web page displays the map. The map provides a geographic understanding of the location of the national park and provides a spatial reference to the user. This system of the story map helps the user gain textual knowledge on the left side with visual representation on the right giving an hollistic approach to learning and the growth of knowledge. </p>

## Applied Libraries

<p> Code is the main component for obtaining the desired output and creating the desired design on the story map. This map uses the <code> storymap.js </code> library at the center of its execution as it gives the program its definite structure and communicates with the browser and the computer to run codes and implement actions in a certain way. The placement of objects, alignment of contents, use of images and texts, and placement of coordinates, icons, and data points is implemented by the program and the various libraries it inherits in its <code>head</code> section. The Leaflet JavaScript Library is also a great resource which provides the <code>L</code> function to call different classes making geospatial operations easire and effortless.</p>

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <!--leaflet css-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.4.0/leaflet.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css">


    <!--add favicon for the web page-->
    <link rel="shortcut icon" href="../../img/favicon.ico" type="image/x-icon">

    <!--Fonts-->
    <link href="https://fonts.googleapis.com/css?family=Cairo" rel="stylesheet">


    <link rel="stylesheet" type="text/css" href="css/storymap.2.5.css">
    <!--add required libraries-->

    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.4.0/leaflet.js"></script>
    <!--jquery-->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js"></script>

    <!--boostrap-->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <!--leaflet.ajax for asynchronously adding geojson data-->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet-ajax/2.1.0/leaflet.ajax.min.js"></script>

    <!--mini globle map-->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.5/d3.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/topojson/1.6.19/topojson.min.js"></script>
    <script src="../../js/globeminimap.js"></script>

    <!--story map plugin-->
    <script src="js/storymap.2.5.js"></script>
```

<p>These are the various libraries, plugins, and references used in order to run the storymap program. It involves various leaflet CSS stylesheets to provide the design and aesthetic beauty to the web page. Various classes can be directly used from there stylesheets,css, and js folders directly into to the code for better performance and easy use. Jquery is another libary implemented in order to use geospatial data and process geojson files. This library provides functions to directly implement spatial data coordinates, locational geojson files etc. into the code and directly serve the desired purpose. The storymap plugin is an important reference as it helps in the creation of this story map and provides classes and functions in order to systematically execute a sequence and provide it in the form of a story line.</p>

## Web Services
<p> This web map is hosted on Github a open source developing tool and is coordinated using <code>git</code> functions of push and fetch. It inherits various basemaps from different map developing websites and open source services like ArcGIS, Google Earth Satellite Imagery, Mapbox, etc. These open sources provide viberant and useful basemaops to be implemented into the code and is useful in providing intensive visualizations to the user.</p>

## Acknowledgement
<p> I want to give credit to my Professor, Bo Zhao, Department of Geography, University of Washington, Seattle, fir teachin me the skills and showing me ways to build interactive web maps. </p>
