JavaScript DOM Manipulation Example
This simple example demonstrates how to use JavaScript to manipulate the Document Object Model (DOM) for a specific HTML element. In this case, we target a <div> element with the id "targetDiv" and apply various style changes using JavaScript.

Getting Started
To use this example, follow these steps:

Clone or download the repository to your local machine.
Open the index.html file in a web browser.
Code Explanation
Retrieving the Element
var targetElement = document.getElementById("targetDiv");
This line of code uses getElementById to fetch the HTML element with the id "targetDiv" and stores it in the variable targetElement for further manipulation.

Modifying Style Properties
javascript
Copy code
// Change the background color to yellow
targetElement.style.backgroundColor = "yellow";

// Add a margin of 20 pixels
targetElement.style.margin = "20px";

// Apply a padding of 10 pixels
targetElement.style.padding = "10px";

// Change the font size to 18 pixels
targetElement.style.fontSize = "18px";

// Set the font weight to bold
targetElement.style.fontWeight = "bold";

// Change the height to 200 pixels
targetElement.style.height = "200px";

// Modify the width to 300 pixels
targetElement.style.width = "300px";
These lines modify various style properties of the targetElement, including background color, margin, padding, font size, font weight, height, and width.

License
This example is licensed under the MIT License - see the LICENSE file for details.

Feel free to customize this README file according to your project's structure and requirements.
