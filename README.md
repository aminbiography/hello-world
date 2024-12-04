![HTML-CSS](https://i.pinimg.com/736x/fa/37/53/fa3753237e71d6807259d5b499bc48a7.jpg)

===================<h1>HTML Algorithms, Structures, & Examples</h1>==================
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Algorithms</title>
</head>
<body>

<!-- 1. Simple HTML Structure -->
<h1>Welcome to HTML Algorithms</h1>
<p>This is a basic HTML structure example with a heading and a paragraph.</p>

<!-- 2. Creating a Table -->
<h2>Example: Simple Table</h2>
<table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
    <tr>
        <td>Row 2, Cell 1</td>
        <td>Row 2, Cell 2</td>
    </tr>
</table>

<!-- 3. Forms with Input Fields -->
<h2>Example: Simple Form</h2>
<form action="/submit" method="POST">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name"><br><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email"><br><br>
    <input type="submit" value="Submit">
</form>

<!-- 4. Ordered List -->
<h2>Example: Ordered List</h2>
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

<!-- 5. Unordered List -->
<h2>Example: Unordered List</h2>
<ul>
    <li>Item A</li>
    <li>Item B</li>
    <li>Item C</li>
</ul>

<!-- 6. Image Insertion -->
<h2>Example: Inserting an Image</h2>
<img src="https://via.placeholder.com/150" alt="Placeholder Image">

<!-- 7. Anchor Link -->
<h2>Example: Anchor Link</h2>
<a href="https://www.example.com" target="_blank">Go to Example.com</a>

<!-- 8. HTML Comments -->
<h2>Example: HTML Comment</h2>
<!-- This is a comment in HTML -->
<p>This is visible text.</p>

<!-- 9. Div and Span Elements -->
<h2>Example: Div and Span</h2>
<div>
    <p>This paragraph is inside a div element.</p>
</div>
<span>This is a span element.</span>

<!-- 10. Embedding a Video -->
<h2>Example: Embedding a Video</h2>
<video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

<!-- 11. Input with Checkbox -->
<h2>Example: Checkbox Input</h2>
<form>
    <input type="checkbox" id="subscribe" name="subscribe" value="yes">
    <label for="subscribe">Subscribe to Newsletter</label><br><br>
    <input type="submit" value="Submit">
</form>

<!-- 12. Button Element -->
<h2>Example: Button</h2>
<button onclick="alert('Button Clicked!')">Click Me</button>

</body>
</html>
```

==========================<h1>HTML Attributes & Elements</h1>===============================
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Attributes</title>
</head>
<body>

<!-- 1. class Attribute -->
<h1 class="header">HTML Attributes Example</h1>
<p class="description">The "class" attribute is used to define CSS classes for styling HTML elements.</p>

<!-- 2. id Attribute -->
<p id="para1">This is a paragraph with an "id" attribute.</p>
<p id="para2">Another paragraph with a different "id" attribute.</p>

<!-- 3. src Attribute -->
<img src="https://via.placeholder.com/150" alt="Placeholder Image" />
<!-- The "src" attribute is used in <img> to specify the image source URL. -->

<!-- 4. alt Attribute -->
<img src="https://via.placeholder.com/150" alt="Placeholder Image" />
<!-- The "alt" attribute provides alternative text for images in case they don't load. -->

<!-- 5. href Attribute -->
<a href="https://www.example.com">Go to Example.com</a>
<!-- The "href" attribute specifies the URL of a link. -->

<!-- 6. target Attribute -->
<a href="https://www.example.com" target="_blank">Open in a new tab</a>
<!-- The "target" attribute specifies where to open the linked document. "_blank" opens the link in a new tab. -->

<!-- 7. title Attribute -->
<a href="https://www.example.com" title="Visit Example">Hover over me</a>
<!-- The "title" attribute provides additional information when the user hovers over an element. -->

<!-- 8. type Attribute (Input Element) -->
<form>
    <input type="text" name="username" placeholder="Enter Username">
    <input type="password" name="password" placeholder="Enter Password">
</form>
<!-- The "type" attribute specifies the type of input (text, password, etc.). -->

<!-- 9. value Attribute -->
<input type="button" value="Click Me">
<!-- The "value" attribute specifies the initial value of an input element. -->

<!-- 10. placeholder Attribute -->
<input type="text" placeholder="Enter your name">
<!-- The "placeholder" attribute provides a short hint in the input field before the user types. -->

<!-- 11. disabled Attribute -->
<button disabled>Disabled Button</button>
<!-- The "disabled" attribute is used to disable user interaction with form elements or buttons. -->

<!-- 12. readonly Attribute -->
<input type="text" value="This is readonly" readonly>
<!-- The "readonly" attribute makes an input field read-only, meaning the user cannot modify it. -->

<!-- 13. checked Attribute (Checkbox or Radio Button) -->
<input type="checkbox" checked> I agree to the terms and conditions
<!-- The "checked" attribute specifies that the checkbox is pre-selected when the page loads. -->

<!-- 14. name Attribute -->
<form action="/submit" method="POST">
    <input type="text" name="username" placeholder="Enter Username">
    <input type="password" name="password" placeholder="Enter Password">
</form>
<!-- The "name" attribute is used to name form elements, and is essential when submitting form data. -->

<!-- 15. style Attribute -->
<p style="color: blue; font-size: 20px;">This paragraph is styled with the "style" attribute.</p>
<!-- The "style" attribute is used to apply inline CSS styles to an element. -->

<!-- 16. lang Attribute -->
<p lang="en">This is a paragraph with a "lang" attribute specifying English.</p>
<!-- The "lang" attribute specifies the language of the content in an element. -->

<!-- 17. action Attribute (Form) -->
<form action="/submit" method="POST">
    <input type="submit" value="Submit">
</form>
<!-- The "action" attribute defines the URL where form data is submitted. -->

<!-- 18. method Attribute (Form) -->
<form action="/submit" method="POST">
    <input type="submit" value="Submit">
</form>
<!-- The "method" attribute specifies the HTTP method (GET, POST) to be used when submitting the form. -->

<!-- 19. for Attribute (Label) -->
<label for="username">Username:</label>
<input type="text" id="username" name="username">
<!-- The "for" attribute associates a label with an input element, improving accessibility. -->

<!-- 20. autocomplete Attribute -->
<form autocomplete="on">
    <input type="text" name="email" placeholder="Enter your email">
    <input type="password" name="password" placeholder="Enter your password">
</form>
<!-- The "autocomplete" attribute specifies whether form data should be auto-completed by the browser. -->

<!-- 21. media Attribute (For External Resources) -->
<link href="styles.css" rel="stylesheet" media="screen">
<!-- The "media" attribute specifies the type of device or media that the resource is intended for. -->

<!-- 22. width and height Attributes -->
<img src="https://via.placeholder.com/150" alt="Placeholder Image" width="150" height="150">
<!-- The "width" and "height" attributes specify the size of an image. -->

<!-- 23. colspan and rowspan Attributes (Table) -->
<table border="1">
    <tr>
        <th colspan="2">Header 1 and Header 2</th>
    </tr>
    <tr>
        <td rowspan="2">Row 1, Column 1</td>
        <td>Row 1, Column 2</td>
    </tr>
    <tr>
        <td>Row 2, Column 2</td>
    </tr>
</table>
<!-- The "colspan" and "rowspan" attributes are used to merge cells in a table. -->

<!-- 24. data-* Attributes (Custom Data Attributes) -->
<p data-author="John Doe">This is a paragraph with a custom data attribute.</p>
<!-- The "data-*" attributes allow you to store custom data within an element. -->

</body>
</html>
```



==========================CSS3 Syntax===========================

```
<br>
01.color
Sets the color of text.
css
Copy code
p {
  color: red;
}
<br>
02. background-color
Sets the background color of an element.
css
Copy code
div {
  background-color: lightblue;
}
<br>
03. font-size
Sets the size of the font.
css
Copy code
h1 {
  font-size: 24px;
}
<br>
04. font-family
Specifies the font of the text.
css
Copy code
body {
  font-family: Arial, sans-serif;
}
<br>
05. font-weight
Sets the weight (boldness) of the font.
css
Copy code
h2 {
  font-weight: bold;
}
<br>
06. text-align
Aligns the text inside an element.
css
Copy code
p {
  text-align: center;
}
<br>
07. margin
Sets the margin space outside of an element.
css
Copy code
div {
  margin: 20px;
}
<br>
08. padding
Sets the padding space inside an element.
css
Copy code
div {
  padding: 15px;
}
<br>
09. border
Specifies the border style, width, and color of an element.
css
Copy code
div {
  border: 2px solid black;
}
<br>
10. width
Sets the width of an element.
css
Copy code
div {
  width: 200px;
}
<br>
11. height
Sets the height of an element.
css
Copy code
div {
  height: 100px;
}
<br>
12. display
Defines how an element should be displayed on the page (e.g., block, inline).
css
Copy code
div {
  display: block;
}
<br>
13. position
Specifies the positioning method for an element (e.g., relative, absolute, fixed).
css
Copy code
div {
  position: relative;
}
<br>
14. top, right, bottom, left
Defines the position of an element relative to its containing element (used with position).
css
Copy code
div {
  position: absolute;
  top: 20px;
  left: 30px;
}
<br>
15. z-index
Controls the stacking order of elements.
css
Copy code
div {
  position: absolute;
  z-index: 10;
}
<br>
16. overflow
Controls what happens when content overflows an element's box.
css
Copy code
div {
  overflow: hidden;
}
<br>
17. box-shadow
Adds shadow to an element’s box.
css
Copy code
div {
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);
}
<br>
18. text-shadow
Adds shadow to text.
css
Copy code
h1 {
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
<br>
19. opacity
Specifies the opacity level of an element (0 = fully transparent, 1 = fully opaque).
css
Copy code
div {
  opacity: 0.5;
}
<br>
20. visibility
Specifies whether an element is visible or hidden (but still takes up space in the layout).
css
Copy code
div {
  visibility: hidden;
}
<br>
21. float
Specifies whether an element should float to the left or right.
css
Copy code
img {
  float: left;
}
<br>
22. clear
Specifies the sides of an element where floating elements are not allowed.
css
Copy code
div {
  clear: both;
}
<br>
23. flex
Defines flexible container properties for a layout using Flexbox.
css
Copy code
.container {
  display: flex;
  justify-content: space-between;
}
<br>
24. grid
Defines grid container properties for a layout using CSS Grid.
css
Copy code
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
<br>
25. align-items
Aligns items vertically within a flex container.
css
Copy code
.container {
  display: flex;
  align-items: center;
}
<br>
26. justify-content
Aligns items horizontally within a flex container.
css
Copy code
.container {
  display: flex;
  justify-content: center;
}
<br>
27. transition
Specifies the duration and type of transition effect when an element’s property changes.
css
Copy code
div {
  transition: all 0.5s ease;
}
<br>
28. transform
Allows you to apply transformations to an element, like rotating or scaling.
css
Copy code
div {
  transform: rotate(45deg);
}
<br>
29. font-style
Defines the style of the font (e.g., italic).
css
Copy code
p {
  font-style: italic;
}
<br>
30. text-transform
Controls the capitalization of text (e.g., uppercase, lowercase).
css
Copy code
p {
  text-transform: uppercase;
}
<br>
31. letter-spacing
Adjusts the space between characters in text.
css
Copy code
p {
  letter-spacing: 2px;
}
<br>
32. line-height
Specifies the height of a line box, influencing the vertical spacing between lines of text.
css
Copy code
p {
  line-height: 1.5;
}
<br>
33. border-radius
Rounds the corners of an element’s border.
css
Copy code
div {
  border-radius: 10px;
}
<br>
34. cursor
Specifies the type of cursor to be displayed when hovering over an element.
css
Copy code
button {
  cursor: pointer;
}
<br>
35. max-width
Specifies the maximum width of an element.
css
Copy code
div {
  max-width: 100%;
}
<br>
36. min-width
Specifies the minimum width of an element.
css
Copy code
div {
  min-width: 200px;
}
<br>
37. max-height
Specifies the maximum height of an element.
css
Copy code
div {
  max-height: 400px;
}
<br>
38. min-height
Specifies the minimum height of an element.
css
Copy code
div {
  min-height: 100px;
}
These CSS properties are commonly used for styling and positioning elements on a webpage, providing control over layouts, visual effects, and interactivity.
```



