# Calculator
**INTRODUCTION**

**HTML Files**

This README explains the HTML and CSS code used to create a basic calculator web page. The web page provides a user interface for performing arithmetic calculations.


The HTML structure of the web page is organized as follows:

<!DOCTYPE html>: Defines the document type as HTML5.

<html lang="en">: Specifies the language for the document.
    
<head>: Contains metadata and links to external CSS and JavaScript files.
    
<meta charset="UTF-8">: Sets the character encoding to UTF-8.

<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport for responsive design.

<meta http-equiv="X-UA-Compatible" content="ie=edge">: Ensures compatibility with Internet Explorer.

<title>Calculator</title>: Sets the page title.

<link rel="stylesheet" href="../css/abc.css" type="text/css"> and <link rel="stylesheet" href="../css/def.css" type="text/css">: Links to external CSS stylesheets.

<body class="col">: Sets the background style for the body.
        
<div class="container mx auto">: Contains the calculator interface.
        
<div class="row">: Represents a row in the calculator.
        
<input class="input" type="text" placeholder="calculate"/>: Input field for displaying and entering calculations.

Additional rows with buttons for digits (0-9), operators (+, -, *, /, %), decimal point, "C" (clear), and "=" (equals) buttons.

CSS Styles:
The provided CSS styles control the appearance and layout of elements in the calculator interface. Key styles include:

Styling for buttons (button and button-special-button) to create a visually appealing interface with padding, margins, borders, and cursor styles.

Styling for rows (row) to set margins, text color, and font size.

Styling for the input field (input) to define its appearance with padding, borders, and border-radius.

Usage:
To use this calculator web page, follow these steps:

Include the HTML code in an HTML file (e.g., calculator.html).

Include the CSS files (abc.css and def.css) and JavaScript file (1q.js) in the appropriate directories.

Open the HTML file in a web browser to access the calculator.

Users can interact with the calculator by clicking on the buttons to input numbers and perform calculations.

**Contributing**
If you'd like to contribute to this project or make improvements to the calculator interface, please follow these steps:

->Fork the repository.

->Make your desired changes or additions.

->Submit a pull request with a clear description of your changes.


Feel free👍 to adapt and expand this README to provide more detailed information or instructions for your specific project.


**CSS Files**

**abc.css**

This README explains the CSS styles defined in the provided code snippet. The styles are designed to be applied to HTML elements to control their appearance and layout. Below, we describe each CSS class and its purpose.

.col Class

The .col class is designed to set the background image of elements to create an attractive visual effect. It uses the background-image property to display an image. You will need to replace the image path inside the code with the path to your own image.

.col {

    background-image: url('../backgroundimage.jpeg'); /* Replace with your image path */

}

.container Class

The .container class is intended to apply styling to a container element. It helps to structure and format the content within the container. It provides the following styles:

margin-top: 150px;: This creates a top margin of 150 pixels, which can be adjusted as needed.

color: #000;: This sets the text color to black (#000).

text-align: center;: This centers the text within the container.

.container {

    margin-top: 150px;
    color: #000;
    text-align: center;
    
}

.mx-auto Class

The .mx-auto class is often used with CSS frameworks like Bootstrap to horizontally center elements within a parent container. In your code snippet, it doesn't have any styles applied directly. Instead, it serves as a class name that you can use in HTML elements to achieve horizontal centering.

.mx-auto
{
    /* No styles applied directly, used for centering elements */
}

You can apply these CSS classes to your HTML elements by adding the respective class names to the elements' class attribute. For example:

<div class="col">
    <!-- Content goes here -->
</div>

<div class="container">
    <p>This is centered text with black color.</p>
</div>

<div class="mx-auto">
    <!-- Content to be centered horizontally -->
</div>

Please ensure that you have the appropriate HTML structure and include this CSS in your project's stylesheet for it to take effect.

**def.css**

This README explains the CSS styles defined in the provided code snippet. The styles are designed to control the appearance and layout of HTML elements to create an aesthetically pleasing and functional user interface.

**CSS Styles**

Font Import

The CSS code imports the "Roboto" font from Google Fonts, which is then applied to the entire HTML document. This font import statement ensures that the "Roboto" font is available for use in your project.

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');

html, body 

{

    height: 100%;
    width: 100%;
    font-family: 'Roboto', sans-serif;

}

Global Styles
These styles apply to the entire HTML document and set the following properties:

height: 100%; and width: 100%;: These properties ensure that the HTML and body elements occupy the full height and width of the viewport.
font-family: 'Roboto', sans-serif;: This sets the default font for the entire document to "Roboto" and falls back to a generic sans-serif font if "Roboto" is not available.
**Button Styles**
The .button class styles buttons in your interface. It defines the following properties:

padding: 20px;: Adds padding around the button content.
width: 66px;: Sets a fixed width for the button.
margin: 0 4px;: Provides margin spacing to separate buttons.
border: 2px solid black;: Adds a black border around the button.
border-radius: 10px;: Rounds the corners of the button.
cursor: pointer;: Changes the cursor to a pointer on hover, indicating that the button is clickable.
Row Styles
The .row class styles rows in your interface. It defines the following properties:

margin: 8px 0;: Adds margin spacing above and below the row.
color: #000;: Sets the text color to black.
font-size: 25px;: Sets the font size for text in the row.
Input Styles
Styles for input elements within rows are defined by the .row input selector. It defines the following properties:

margin: 0;: Removes margin spacing around the input.
padding: 25px 70px;: Adds padding to the input field.
border: 2px solid black;: Adds a black border around the input field.
border-radius: 10px;: Rounds the corners of the input field.
Special Button Styles
The .button-special-button class styles special buttons in your interface. It defines the following properties:

width: 140px;: Sets a fixed width for special buttons.
padding: 20px;: Adds padding around the button content.
margin: 0 4px;: Provides margin spacing to separate special buttons.
border: 2px solid black;: Adds a black border around special buttons.
border-radius: 10px;: Rounds the corners of special buttons.
cursor: pointer;: Changes the cursor to a pointer on hover, indicating that the special button is clickable.
This README provides an overview of the CSS styles defined in the code snippet. You can adapt and expand this documentation to suit your project's needs.
