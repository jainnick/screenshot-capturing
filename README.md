# screenshot-capturing
## Interactive Map Screenshot HTML Page

An overview and explanation of the HTML page that enables capturing and saving a screenshot of an interactive map.

---

## Table of Contents

1. [Introduction](#introduction)
2. [HTML Structure](#html-structure)
   - [Head Section](#head-section)
   - [Body Section](#body-section)
3. [Google Maps Integration](#google-maps-integration)
4. [Screenshot Capture and Download Logic](#screenshot-capture-and-download-logic)
5. [Conclusion](#conclusion)

---

## 1. Introduction <a name="introduction"></a>

This HTML page showcases an interactive map integrated using the Google Maps JavaScript API. The page allows users to place a marker on the map, capture a screenshot of the map, and save it as a PNG image.

## 2. HTML Structure <a name="html-structure"></a>

### Head Section <a name="head-section"></a>

In the head section, we include necessary metadata, styles, Google Maps API, and the HTML2Canvas library for capturing a screenshot.

### Body Section <a name="body-section"></a>

In the body section, we have a map container, an input to search for a location, and a button to capture and save the screenshot.

## 3. Google Maps Integration <a name="google-maps-integration"></a>

The `initMap` function initializes the Google Map, sets the default center and zoom level, and sets up a click event listener to place a marker on the map when clicked.

## 4. Screenshot Capture and Download Logic <a name="screenshot-capture-and-download-logic"></a>

The "Capture and Save Screenshot" button triggers a function to capture the screenshot of the map container using HTML2Canvas. Once the screenshot is captured, it is converted to a Blob and saved as a PNG image. The logic creates a temporary link element (`<a>`) to trigger the download, specifying the desired filename for the downloaded image, and triggering a click event on the link to initiate the download.

This logic ensures that users can capture a screenshot of the map and download it as "map_screenshot.png" by clicking the designated button.

## 5. Conclusion <a name="conclusion"></a>

This HTML page provides a simple and interactive way to capture and save a screenshot of the map. Users can utilize and integrate this functionality into their projects for map screenshot features.

