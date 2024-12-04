
===================<h1>HTML3.2</h1>==================
```
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph of text.</p>

    <table border="1">
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
    </table>

    <p>HTML 3.2 introduces more formatting options and tables.</p>

    <a href="https://www.example.com">Visit Example</a>
    
</body>

</html>
```
======================HTML3.2==========================
<h2>id</h2>
<p>Specifies a unique identifier for an element.</p>

```
<div id="unique-id">Content</div>
```

<h2>class</h2>
Specifies one or more class names for an element.

```
<div class="my-class another-class">Content</div>
```

<h2Inline CSS styles for an element.
html
```<div style="color: red; font-size: 20px;">Styled Content</div>
title
<br>
Specifies extra information about an element (tooltip).
html
Copy code
<button title="Click here to submit">Submit</button>
hidden
<br>
Indicates that an element is not visible.
html
Copy code
<div hidden>Content</div>
lang
<br>
Specifies the language of the element's content.
html
Copy code
<p lang="en">Hello, world!</p>
dir
<br>
Specifies the text direction.
html
Copy code
<p dir="rtl">abcdefghijklmnopqrstuvwxyz</p>
contenteditable
<br>
Indicates whether the content of an element is editable.
html
Copy code
<div contenteditable="true">Editable content</div>
spellcheck
<br>
Specifies whether the content should be checked for spelling errors.
html
Copy code
<textarea spellcheck="true"></textarea>
tabindex
<br>
Specifies the order in which elements should be focused when navigating with the Tab key.
html
Copy code
<input tabindex="1" />
<input tabindex="2" />
action
<br>
Specifies the URL to which form data will be sent.
html
Copy code
<form action="submit.php">
  <input type="text" name="username">
</form>
method
<br>
Defines the HTTP method for form submission.
html
Copy code
<form method="POST" action="submit.php">
  <input type="text" name="username">
</form>
enctype
<br>
Specifies the encoding type for form data.
html
Copy code
<form enctype="multipart/form-data">
  <input type="file" name="file">
</form>
autocomplete
<br>
Specifies whether the browser should enable auto-completion.
html
Copy code
<input type="text" autocomplete="on">
type
<br>
Specifies the type of an input element.
html
Copy code
<input type="text">
<input type="password">
<input type="submit">
name
<br>
Specifies the name of an input element.
html
Copy code
<input type="text" name="username">
value
<br>
Specifies the value of an input element.
html
Copy code
<input type="text" value="Default text">
placeholder
<br>
Provides a hint for an input field.
html
Copy code
<input type="text" placeholder="Enter your name">
required
<br>
Specifies that an input field must be filled out before submitting the form.
html
Copy code
<input type="text" required>
src
<br>
Specifies the source URL for an embedded content like images or videos.
html
Copy code
<img src="image.jpg" alt="Example Image">
alt
<br>
Provides alternative text for an image.
html
Copy code
<img src="image.jpg" alt="Example Image">
href
<br>
Specifies the URL of the linked page.
html
Copy code
<a href="https://www.example.com">Visit Example</a>
target
<br>
Specifies where to open the linked document.
html
Copy code
<a href="https://www.example.com" target="_blank">Open in a new tab</a>
rel
<br>
Specifies the relationship between the current document and the linked document.
html
Copy code
<a href="https://www.example.com" rel="noopener noreferrer">Link</a>
disabled
<br>
Specifies that an element is disabled.
html
Copy code
<button disabled>Disabled Button</button>
readonly
<br>
Specifies that an input field is read-only.
html
Copy code
<input type="text" readonly>
checked
<br>
Specifies that a checkbox or radio button is selected.
html
Copy code
<input type="checkbox" checked>
multiple
<br>
Specifies that multiple options can be selected.
html
Copy code
<select multiple>
  <option>Option 1</option>
  <option>Option 2</option>
</select>
maxlength
<br>
Specifies the maximum number of characters allowed in an input field.
html
Copy code
<input type="text" maxlength="10">
min
<br>
Specifies the minimum value allowed for a number input.
html
Copy code
<input type="number" min="1">
max
<br>
Specifies the maximum value allowed for a number input.
html
Copy code
<input type="number" max="100">
step
<br>
Specifies the intervals for numeric inputs.
html
Copy code
<input type="number" step="5">
data-*
<br>
Custom data attributes to store extra information.
html
Copy code
<div data-user-id="12345">User Info</div>
aria-*
<br>
Accessibility attributes to enhance support for screen readers.
html
Copy code
<button aria-label="Close">X</button>
These attributes are essential for creating functional, accessible, and well-structured HTML documents.
```




==========================CSS3===========================

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



