# HTML Styles - CSS

CSS stands for Cascading Style Sheets.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

## What is CSS?
Cascading Style Sheets (CSS) is used to format the layout of a webpage.

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

Tip: The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!

## Using CSS
CSS can be added to HTML documents in 3 ways:
- Inline - by using the `style` attribute inside HTML elements
- Internal - by using a `<style>` element in the `<head>` section
- External - by using a `<link>` element to link to an external CSS file



## 1- Inline CSS

An inline CSS is used to apply a unique style to a single HTML element.

An inline CSS uses the style attribute of an HTML element.

The following example sets the text color of the `<h1>` element to blue, and the text color of the `<p>` element to red:

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;">A Blue Heading</h1>

<p style="color:red;">A red paragraph.</p>

</body>
</html>
```

## 2- Internal CSS
An internal CSS is used to define a style for a single HTML page.

An internal CSS is defined in the `<head>` section of an HTML page, within a `<style>` element.

The following example sets the text color of ALL the `<h1>` elements (on that page) to blue, and the text color of ALL the `<p>` elements to red. In addition, the page will be displayed with a "powderblue" background color: 

```html
<!DOCTYPE html>
<html>
<head>


    <!-- Internal CSS Start -->
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>

   <!-- Internal CSS end-->




</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```


## 3- External CSS

An external style sheet is used to define the style for many HTML pages.

To use an external style sheet, add a link to it in the `<head>` section of each HTML page:

```html
<!DOCTYPE html>
<html>
<head>

  <link rel="stylesheet" href="styles.css"> <!-- External CSS File link -->


</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## <q>"styles.css":</q>
```css
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

Tip: With an external style sheet, you can change the look of an entire web site, by changing one file!

---

# CSS Colors, Fonts and Sizes

Here, we will demonstrate some commonly used CSS properties. You will learn more about them later.

- The CSS `color` property defines the text color to be used.

- The CSS `font-family` property defines the font to be used.

- The CSS `font-size` property defines the text size to be used.

``` html
!DOCTYPE html>
<html>
<head>
<style>

    
h1 {
  color: blue; /* CSS color */
  font-family: verdana; /* CSS font Family */
  font-size: 300%; /* CSS font size */

}
p  {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

# CSS Border
CSS Border
The CSS `border` property defines a border around an HTML element.

Tip: You can define a border for nearly all HTML elements.

Example:
```html
<!DOCTYPE html>
<html>
<head>
<style>
p {
  border: 2px solid powderblue; /* CSS Border */
}
</style>
</head>
<body>

<h1>This is a heading</h1>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
</html>
```

# CSS Padding
The CSS padding property defines a padding (space) between the text and the border.

## Example
Use of CSS border and padding properties:
```html
<!DOCTYPE html>
<html>
<head>
<style>
p {
  border: 2px solid powderblue;
  padding: 30px; /* CSS Paddomng */
}
</style>
</head>
<body>

<h1>This is a heading</h1>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
</html>
```

# CSS Margin

The CSS `margin` property defines a margin (space) outside the border.

## Example
Use of CSS border and margin properties:
```html
<!DOCTYPE html>
<html>
<head>

<style>
p {
  border: 2px solid powderblue;
  margin: 50px; /* CSS Margin */
}
</style>

</head>
<body>

<h1>This is a heading</h1>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
</html>
```

<br> <br>
# Link to External CSS

External style sheets can be referenced with a full URL or with a path relative to the current web page.


## Example-1
This example uses a full URL to link to a style sheet:
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## Example-2
This example links to a style sheet located in the html folder on the current web site: 

```html 
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="/html/styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## Example-3

This example links to a style sheet located in the same folder as the current page:
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

# Chapter Summary

- Use the HTML style attribute for inline styling
- Use the HTML `<style>` element to define internal CSS
- Use the HTML `<link>` element to refer to an external CSS file
- Use the HTML `<head>` element to store `<style>` and `<link>` elements
- Use the CSS `color` property for text colors
- Use the CSS `font-family` property for text fonts
- Use the CSS `font-size property` for text sizes
- Use the CSS `border` property for borders
- Use the CSS `padding` property for space inside the border
- Use the CSS `margin` property for space outside the border


