# chawdah@mymacewan.ca javascript assignment 1

Q1. What is innerHTML?
A1.innerHTML is a JavaScript property that gets or sets the HTML content inside an element, including all its child elements and text.
Example:
<h1 id="name"></h1>

<script>
  document.getElementById("name").innerHTML = "Hardi Chawda";
  document.getElementById("name").style.color = "black";
</script>


Q2> What is the DOM?
A2.The DOM (Document Object Model) is a structured way that a web browser represents an HTML page so it can be accessed and changed using JavaScript.
It organizes the page into elements such as headings, images, and paragraphs, allowing JavaScript to interact with them by reading, modifying, or updating the content and appearance of the web page.
Example of HTML :
<p id="message">Hello</p>
<button onclick="changeText()">Click Me</button>

Example of JavaScript:
<script>
    function changeText() {
        document.getElementById("message").innerHTML = "Hello, DOM!";
    }
</script>
