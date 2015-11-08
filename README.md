Flip-Popup-Jquery-Plugin
========================

Flip Popup Jquery Plugin

Add this js file in the head of your html page with the right path

```
<script src="flip-popup-jquery.js"></script>

```
and add the css files with the right path to your html page
```
<link rel="stylesheet" type="text/css" href="lightbox.css">
  <link rel="stylesheet" href="flippopup.css">
```
add 2 attributes to your links where you will click to popup

```
data-flip-popup=""
```
and the name of the div you want to popup for exemple

```
rel="pop1"
```
the link will be something like this

```
<a href="#" data-flip-popup="" rel="pop1" ><div class="linkpuls" data-flippopup="example-1" >click to popup</div></a>
```

now customize the popup addding the settings in json format

simply add this div within body tag  and change the values of properties

```
<div id='flipset' data-settings='    
                                                                        
    "albumLabel": "Image %1 of %2",
    "alwaysShowNavOnTouchDevices": false,
    "fadeDuration": 500,
    "fitImagesInViewport": true,
    "positionFromTop": 50,
    "resizeDuration": 700,
    "showImageNumberLabel": true,
    "wrapAround": false,
    "color": "#fff",
    "xcolor":"#ff5599",
    "lightboxcolor":"#33ffff",
    "popupboxcolor":"#ff00cc",
    "backgroundcolor":"#33ffff",
    "border_radius":"25px",
    "speed":0.5,
    "shadowcolor":"#ff5599",
    "shadowsize":"0px 0px 25px 5px",
    "font_family":"arial",
    "popupwidth":"600px",
    "popupheight":"400px",
    "loadurl":"",
    "imageurl":""'>
    </div>
```

Pay attention to the quotation marks in the settings
Each line should be like this

```
  "popupwidth":"600px",
```
except for the ones with number like this

    "speed":0.5,

it’s better these properties should be the same

```
"albumLabel": "Image %1 of %2",
    "alwaysShowNavOnTouchDevices": false,
    "fadeDuration": 500,
    "fitImagesInViewport": true,
    "positionFromTop": 50,
    "resizeDuration": 700,
    "showImageNumberLabel": true,
    "wrapAround": false,
```

if you want to change the color of the text in the popup you should change this
```
"color": "#fff",
```
for the color of the X for closing the popup you should change this
```
"xcolor":"#ff5599",
```
for the lightbox color this
```
"lightboxcolor":"#33ffff",
```
for the popup box color this
```
"popupboxcolor":"#ff00cc",
```
for the background color this 
```
"backgroundcolor":"#33ffff",
```
for the radius of border this
```
"border_radius":"25px",
```
for the speed of transition this
```
"speed":0.5,
```
for the color of the shadow of the popup this
```
"shadowcolor":"#ff5599",
```
for the shadow size this:
```
"shadowsize":"0px 0px 25px 5px",
```
for the font of the popup text this
```
"font_family":"arial",
```
for the popup width and height these
```
"popupwidth":"600px",
 "popupheight":"400px",
```
for the ajax request to load data this
```
    "loadurl":"",
```
for the image you want to load inside the popup add the image url here
```
    "imageurl":"http://image.url.example"
```
