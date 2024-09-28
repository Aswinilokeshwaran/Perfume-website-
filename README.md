# Perfume-website-
Here's a detailed explanation of the HTML and CSS code of Simple Perfume Website

## Code Explanation

### HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Perfumy</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
```
- **`<!DOCTYPE html>`**: Declares the document type as HTML5.
- **`<html lang="en">`**: Sets the language of the HTML document to English.
- **`<title>Perfumy</title>`**: Sets the title of the webpage, which appears on the browser tab.
- **`<link rel="stylesheet" href="style.css">`**: Links the external stylesheet `style.css` to style the HTML elements.

### Header and Navigation Section

```html
<div class="header">
  <nav>
    <h1>Perfumy</h1>
    <ul>
      <li>Home|</li>
      <li>Products|</li>
      <li>About us|</li>
      <li>Contact us</li>
    </ul>
  </nav>
</div>
```
- **`<div class="header">`**: Creates a container for the header section.
- **`<nav>`**: Defines a navigation section with the brand name "Perfumy" and a list of links (`Home`, `Products`, `About us`, `Contact us`).
  - **`<h1>`**: Displays the heading "Perfumy".
  - **`<ul>`**: Creates an unordered list of navigation items.
  - **`<li>`**: Represents each item in the navigation bar. The items have a separator (`|`) between them.

### Search Bar Section

```html
<div class="searchbar">
    <input placeholder="search">
</div>
```
- **`<div class="searchbar">`**: Creates a container for the search bar.
  - **`<input placeholder="search">`**: Creates an input field with the placeholder text "search".

### Product Section

```html
<div class="product">
  <div class="box">   
    <img src="pic 2.webp" width="220px" height="220px">
    <p>Perfume Palace</p>
  </div>
  <div class="box">   
    <img src="pic 2.jpg" width="220px" height="220px">
    <p>Perfume BlackBon</p>
  </div>
  <div class="box">   
    <img src="pic 3.jpg" width="220px" height="220px">
    <p>Perfume Lovefall</p>
  </div>
</div>
```
- **`<div class="product">`**: Contains a group of product items.
  - **`<div class="box">`**: Represents an individual product box.
    - **`<img src="pic 2.webp" width="220px" height="220px">`**: Displays an image of the product with fixed dimensions.
    - **`<p>Perfume Palace</p>`**: Describes the product below the image.

This structure is repeated for each product item in the `product` section.

### About Us Section

```html
<div class="about">
  <h1>About us</h1>
  <p class="one">Lorem ipsum dolor sit, amet consectetur...</p>
</div>
```
- **`<div class="about">`**: Contains the "About us" section of the page.
  - **`<h1>About us</h1>`**: Displays the heading "About us".
  - **`<p class="one">`**: Paragraph describing the company with placeholder text.

### Contact Us Section

```html
<div class="Contact">
  <h3>Contact Us</h3>
  <h5>+91 59566640</h5>
  <h5>Perfume123@gmail.com</h5>
  <p class="two">Lorem ipsum dolor sit amet consectetur...</p>
</div>
```
- **`<div class="Contact">`**: Contains the contact information section.
  - **`<h3>Contact Us</h3>`**: Displays a subheading "Contact Us".
  - **`<h5>+91 59566640</h5>`**: Displays the phone number.
  - **`<h5>Perfume123@gmail.com</h5>`**: Displays the email address.
  - **`<p class="two">`**: Contains placeholder text with additional contact information.

### Closing Tags
```html
</body>
</html>
```
- Closes the body and HTML tags.

---

## CSS Style Explanation

### Global Style

```css
* {
    margin: 0;
    padding: 0;
    cursor: pointer;
}
```
- Applies a reset to all elements, removing default margin and padding. Sets the default cursor to `pointer` for interactive elements.

### Navigation Bar Styling

```css
nav {
    background-color: black;
    color: white;
    padding: 20px;
}
```
- Sets the navigation bar's background color to black and text color to white. Adds 20px padding around the content.

```css
li, h1, ul {
    display: inline;
}
```
- Sets the display property of list items (`li`), heading (`h1`), and unordered list (`ul`) to `inline` so they appear on a single line.

```css
ul {
    margin-left: 60%;
}
```
- Moves the navigation menu to the right using `margin-left: 60%`.

```css
li {
    color: gray;
    cursor: pointer;
}
```
- Sets the initial text color of list items to gray and ensures the cursor changes to a pointer when hovered.

```css
li:hover {
    color: white;
}
```
- Changes the list items' text color to white when hovered over.

### Search Bar Styling

```css
.searchbar {
    text-align: center;
    padding: 50px;
}
```
- Centers the search bar content and adds padding of 50px around it.

```css
input {
    width: 55%;
    padding: 15px;
}
```
- Sets the width of the search bar input to 55% and adds 15px padding inside the input field.

### Product Section Styling

```css
.p {
    display: block;
}
```
- Ensures paragraph elements within product boxes are displayed as block elements.

```css
.box {
    border-color: black;
    border-style: solid;
    border-width: 2px;
    display: inline-block;
    width: 220px;
    margin-left: 30px;
}
```
- Styles individual product boxes (`.box`) with a solid black border, fixed width, and inline-block display. Adds 30px margin on the left side.

```css
.box :hover {
    background-color: black;
    color: white;
    cursor: pointer;
}
```
- Changes the product box background to black and text color to white when hovered over.

### About Us Section Styling

```css
.about {
    text-align: center;
    margin-top: 20px;
}
```
- Centers the content and adds 20px margin on top.

```css
.one {
    text-align: justify;
    padding: 30px;
}
```
- Justifies the text and adds 30px padding inside the paragraph.

### Contact Us Section Styling

```css
.Contact {
    text-align: center;
    background-color: black;
    color: white;
    padding: 30px;
    cursor: pointer;
}
```
- Centers the content, sets the background color to black, text color to white, and adds 30px padding. Changes the cursor to `pointer`.

```css
.two {
    padding-top: 15px;
    text-align: justify;
    font-size: small;
}
```
- Adds padding at the top, justifies the text, and sets a small font size for the paragraph.

---

This code creates a well-structured webpage for a perfume shop, with a navigation bar, search bar, product listings, "About us" section, and "Contact Us" information. The styling is minimalistic yet effective, ensuring a professional look for the perfume shop's website.
