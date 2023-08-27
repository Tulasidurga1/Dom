# Dom
#hosted Link:-https://tulasidurga1.github.io/Dom/
#HTML Structure:

The HTML file begins with the usual <html>, <head>, and <body> tags.
Inside the <head>, there are meta tags for character encoding and viewport settings, and a title for the page.
The stylesheet is linked using the <link> tag with a reference to "style.css".
The page body contains a <div> with the class "main-container" that wraps the form elements and the <div> to be styled.
Several dropdown menus are provided for selecting color, background color, padding, font size, and font weight.
A <div> with the id "styledDiv" contains the text "Hello Guys I am Tulasi Durga" and serves as the element to be styled.
JavaScript:

The JavaScript code inside the <script> tag at the end of the HTML file selects all the relevant HTML elements (dropdowns and the div to be styled) using their respective IDs.
Event listeners are added to each dropdown element to listen for changes in their values.
When the value of a dropdown changes, the corresponding style of the "styledDiv" is updated using the selected value.
For example, when the font size dropdown changes, the fontSize style of the div is updated with the selected value plus "px".
CSS:

The CSS code included in the HTML is a basic stylesheet that resets some default styles and sets a background color for the whole page.
The "#styledDiv" selector sets styles for the div element that is being dynamically styled:
It adds a black border, sets width and height, and adds margins.
The ".main-container" class styles the wrapping container div to center its contents.
