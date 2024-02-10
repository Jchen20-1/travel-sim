# travel-simulator

![](assets/example.png)


## Difficulty
Beginner
## Objective

Use **HTML Links, Images, Headers** and correctly specify the file paths to travel around the world.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of CSS (Selectors, Basic Properties like Width and Height)

## Concepts

| HTML      | Description                                                                               |
|-----------|-------------------------------------------------------------------------------------------|
| HTML      | **H** yper **T** ext **M** arkup **L** anguage used to create the structure of web pages. |
| element   | An element is an individual part, or a building block, of a web page.                     |
| attribute | A modifier of an element.                                                                 |
| div       | A container element.                                                                      |
| img       | An image element.                                                                         |
| a         | A link element.                                                                           |
| href      | An attribute used to specify the link destination.                                        |
| link      | A link tag that links external style sheets to your HTML page.                            |
| id        | A unique attribute on an element used for targeting in CSS.                               |
| class     | An attribute that can be applied to multiple elements used for targeting in CSS.          |

| File Paths         | Description                                                                                                              |
|--------------------|--------------------------------------------------------------------------------------------------------------------------|
| File Path          | Describes the location of a file in a web site's folder structure.                                                       |
| Absolute File Path | Full URL to an Internet file. Ex. https://manoa.hawaii.edu/wp/wp-content/uploads/2017/10/uhm-white-seal-nameplate@2x.png |
| Relative File Path | Path to a file relative to the current page. Ex. assets/paris.jpeg                                                       |

| Relative File Paths | Description                                                                                          |
|---------------------|------------------------------------------------------------------------------------------------------|
| assets/paris.jpeg   | Goes into the assets folder, then points to the paris.jpeg.                                          |
| ../assets/paris.jpg | Goes outside of the current folder, then goes into the assets folder, then points to the paris.jpeg. |
## Before You Start:

Make sure you have a folder/directory named "assets", with all the pictures of various places in there. If not, please copy the assets folder from above and paste it into your repel.


## Your Challenge

### Part I: Main HTML Page

Create the following files:

* index.html file
* styles.css file

#### Make sure you link the css file correctly!

1. Create a ```div``` with an ```id``` of "header".
* Inside the div, we want to show the title of the web page, which is going to be "Travel Simulator", lets put that in a ```h1``` tag.
* Then make another ```h2``` tag with the text, "Click on a portal to travel to a new location!" so users know how to operate our website. 

2. Create another ```div``` with an ```id``` of "container".
* Inside the div, add the following:
    * A link element using the ```a``` tag
    * Inside the link element, create an image element using the ```img``` tag, and give the image element a ```class``` of "portals".
    * Repeat this 5 times for a total of 5 different link elements with image elements inside of them.
* Then find the portal image in the assets folder, and set the ```src``` of each image element to that image.

3. Then, create 5 new HTML files for the 5 places that each portal will be linked to, each named after the 5 pictures in the assets folder:
* paris.html
* rome.html
* tokyo.html
* las-vegas.html
* antarctica.html

4. After that, go back to the original index.html file, and create a ```href``` attribute for each of the 5 portals, each linking to a different location based on the html files you created in the last step. For example:
   * you can set the ```href``` attribute of the first portal to link to paris.html, second to rome.html, and so on and so forth. 

### Part II Main CSS file

1. Target the "container" ```id```.

* Set the position of the portals to be somewhere in the middle of th page. You can do this by setting the ```position``` to ```fixed```, which allows us to directly specify where we want the portals to stay on the page.
* Afterwards, you can play around with the ```top```, ```right```, ```left```, and ```bottom``` properties to place the portals where ever you want. 

2. Target the "portals" ```class```.
   * Set the ```height``` of the portal to around ```200 px```.
   * Give each portal a ```margin``` of around ```30 px``` so each portal is spaced out properly.

3. Target the "header" ```id```.
* Set the ```color``` of the text to white so it contrasts our darker background, making it easier to read. 
* Then set the ```text-align``` property to ```center```, so our text stays centered on the page. 

4. Target the ```body``` tag.
* Set the ```background-image``` to the portal-background image located in the assets folder. You can look on this [website](https://www.w3schools.com/css/css_background_image.asp) if you need a hint.

### Part III Other CSS Files

1. Create the following files:
* paris.css
* rome.css
* tokyo.css
* las-vegas.css
* antarctica.css

### Part IV Locations HTML

1. Link the correct style sheet to all 5 of the new html files you created for the locations the portals go to. 
* paris.css will link with paris.html, rome.css with rome.html, so on and so forth. 
2. Just like with the home page, we want to create a ```div``` with an ```id``` of "header".
   * Inside the ```div```, we want to create a ```h1``` tag, but this time, with the text, "Welcome to [location name]!", where location name is the name of the location you linked the portal to. 
   * Also inside the ```div```, create a ```h2``` tag with the instructions, "Click on a portal to travel elsewhere, or click the first portal to go back.".
3. Then create another ```div``` with an ```id``` of "container".
* Inside the div, add the same 5 portal link elements like we did before with the home page.
* When you're altering the ```href``` attribute of the links, make sure you link the first portal back to the "index.html" page, so users can choose to go back to the home page if they want to.
* The rest of the portals you can link according to the order to linked them previously, just make sure you don't link any of the portals to the existing page. So for example, if you're currently working on "paris.html", don't link any of the portals back to "paris.html". 

##### Repeat this 5 times for each of the 5 different portal locations.

### Part V Locations CSS

1. Since the 5 different location pages are very similar to the homepage when it comes to layout, we can simply copy over all of the CSS content in the "styles.css" file over to each of the 5 new CSS files you created for all the locations.
2. The modifications you'll have to make to the CSS files are the following:
* Set the ```background-image``` of each page to their own image available in the assets folder.
* Set the ```background-size``` of each page to ```cover```, that way it will cover the whole page, no matter the original size of the image. 
* Set the ```height``` attribute to ```100vh```, and ```width``` attribute to ```100vw``` so it uses the full height and width of the image. 
* Finally, if the default black header text color makes it harder to read because of the darker background image, change the ```color``` attribute to any bright color you like, so it's easier for users to read. 

##### Repeat this 5 times for each of the 5 different portal location CSS files. 

Fantastic Job! Double check each of the pages and portals to make sure everything is working, and customize the colors to your liking. 

### Stretch Goals

1. Create another portal in the index.html file that takes you somewhere you want to visit!
2. Create a whole new set of portals of places you've been to before!