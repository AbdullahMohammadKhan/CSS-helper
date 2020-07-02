# CSS-helper

## CSS Color
*[Standard 140 color names with their hex codes](https://www.w3schools.com/colors/colors_names.asp)

*[More color values](https://www.w3schools.com/colors/colors_hex.asp)

*[Color Group](https://www.w3schools.com/colors/colors_groups.asp)

*[Everything about colors from W3School](https://www.w3schools.com/colors/)

## CSS Backgrounds
#### background-color
Opacity / Transparency:
The opacity property specifies the opacity/transparency of an element. It can take a value from 0.0 - 1.0. The lower value, the more transparent:


![alt text](https://github.com/AbdullahMohammadKhan/CSS-helper/blob/master/images/Screen%20Shot%202020-07-02%20at%2011.44.18%20AM.png "Opacity for css background")

Note: When using the opacity property to add transparency to the background of an element, all of its child elements inherit the same transparency. This can make the text inside a fully transparent element hard to read.

Transparency using RGBA
If you do not want to apply opacity to child elements, like in our example above, use RGBA color values. The following example sets the opacity for the background color and not the text:

![alt text](https://github.com/AbdullahMohammadKhan/CSS-helper/blob/master/images/Screen%20Shot%202020-07-02%20at%2011.56.09%20AM.png "2")
#### background-image
The background-image property specifies an image to use as the background of an element.
By default, the image is repeated so it covers the entire element.
The background image for a page can be set like this: 
```
body {
  background-image: url("paper.gif");
  background-image: url("paper.jpg");
}
```
#### CSS Background Repeat
By default, the background-image property repeats an image both horizontally and vertically.Some images should be repeated only horizontally or vertically, or they will look strange.
To repeat an image vertically, set ```background-repeat: repeat-y;```
To repeat an image horizontally, set ```background-repeat: repeat-x```;

