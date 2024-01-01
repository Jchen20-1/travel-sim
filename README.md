# travel-sim



## Objective

Use **HTML Links, Images, Headers** and correctly specify the file paths to travel around the world.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of CSS (Selectors, Basic Properties like Width and Height)

## Concepts

HTML | Description
-----|------------
HTML | **H** yper **T** ext **M** arkup **L** anguage used to create the structure of web pages.
element | An element is an individual part, or a building block, of a web page.
attribute | A modifier of an element.
div | A container element.
img | An image element.
a | A link element.
href | An attribute used to specify the link destination.
link | A link tag that links external style sheets to your HTML page.
id | A unique attribute on an element used for targeting in CSS.
class | An attribute that can be applied to multiple elements used for targeting in CSS.

File Paths | Description
---------- | -----------
File Path | Describes the location of a file in a web site's folder structure.
Absolute File Path | Full URL to an Internet file. Ex. https://manoa.hawaii.edu/wp/wp-content/uploads/2017/10/uhm-white-seal-nameplate@2x.png
Relative File Path | Path to a file relative to the current page. Ex. assets/paris.jpeg

Relative File Paths | Description
------------------- | -----------
assets/paris.jpeg | Goes into the assets folder, then points to the paris.jpeg.
../assets/paris.jpg | Goes outside of the current folder, then goes into the assets folder, then points to the paris.jpeg.

## Your Challenge

### Part I: Main HTML Page

Create the following files:

* index.html file
* styles.css file

#### Make sure you link the css file correctly!

1. Create a ```div``` with an ```id``` of "container".
* Inside the div, add the following:
    * A link element using the ```a``` tag
    * Inside the link element, create an image element using the ```img``` tag, and give the image element a ```class``` of "portals".
    * Repeat this 5 times for a total of 5 different link elements with image elements inside of them.
* Then find the portal image in the assets folder, and set the ```src``` of each image element to that image.

2. Then, create 5 new HTML files for the 5 places that each portal will be linked to. 



### Stretch Goals

1. Create another portal in the index.html file that takes you somewhere you want to visit!
2. Create a whole new set of portals of places you've been to before!