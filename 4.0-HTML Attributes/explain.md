# HTML Attributes
HTML attributes provide additional information about HTML elements.

## HTML Attributes
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"



# 1 - The href Attribute:

The ```<a>``` tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

Example
```html

<!DOCTYPE html>
<html>
<body>

<h2>The href Attribute</h2>

<p>HTML links are defined with the a tag. The link address is specified in the href attribute:</p>

<a href="https://www.w3schools.com">Visit W3Schools</a>

</body>
</html>



```
You will learn more about links in our [HTML Links chapter](https://www.w3schools.com/html/html_links.asp).

 <br>  <br> 

# 2-The src Attribute
The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

Example:

```html

<!DOCTYPE html>
<html>
<body>

<h2>The src Attribute</h2>
<p>HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute:</p>

<img src="img_girl.jpg">

</body>
</html>


```

## There are two ways to specify the URL in the `src` attribute:

1. <strong>Absolute URL</strong> - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. <strong>Relative URL</strong> - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

<br>

Tip: It is almost always best to use relative URLs. They will not break if you change domain.


<br> 

# 3-The width and height Attributes:
The `<img>` tag should also contain the `width` and `height` attributes, which specify the width and height of the image (in pixels):

Example:
```html

<!DOCTYPE html>
<html>
<body>

<h2>The src Attribute</h2>
<p>HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute:</p>

<img src="img_girl.jpg" width="500" height="600">

</body>
</html>


```

# 4-The alt Attribute:
The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the `src` attribute, or if the user uses a screen reader.

Example-1:
```html

<!DOCTYPE html>
<html>
<body>

<h2>The alt Attribute</h2>
<p>The alt attribute should reflect the image content, so users who cannot see the image get an understanding of what the image contains:</p>

<img src="img_girl.jpg" alt="Girl with a jacket" width="500" height="600">

</body>
</html>


```

Example-2: <br>
See what happens if we try to display an image that does not exist:

```html

<!DOCTYPE html>
<html>
<body>

<img src="img_typo.jpg" alt="Girl with a jacket">

<p>If we try to display an image that does not exist, the value of the alt attribute will be displayed instead. </p>

</body>
</html>

```

# 5-The style Attribute:
The `style` attribute is used to add styles to an element, such as color, font, size, and more.

Example:

```html

<!DOCTYPE html>
<html>
<body>

<h2>The style Attribute</h2>
<p>The style attribute is used to add styles to an element, such as color:</p>

<p style="color:red;">This is a red paragraph.</p>

</body>
</html>


```

<br>

# 6-The lang Attribute:
You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:

```html
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>

```
Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

The following example specifies English as the language and United States as the country:

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>

```

You can see all the language codes in our [HTML Language Code Reference](https://www.w3schools.com/tags/ref_language_codes.asp).


<br> <br>


# 7-The title Attribute:

The `title` attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

Example
```html

<!DOCTYPE html>
<html>
<body>

<h2>The style Attribute</h2>
<p>The style attribute is used to add styles to an element, such as color:</p>

<p style="color:red;">This is a red paragraph.</p>

</body>
</html>



```
## Suggest-1: Always Use Lowercase Attributes

The HTML standard does not require lowercase attribute names.

The title attribute (and all other attributes) can be written with uppercase or lowercase like title or TITLE.

However, W3C recommends lowercase attributes in HTML, and demands lowercase attributes for stricter document types like XHTML.


## Suggest-2: Always Quote Attribute Values
The HTML standard does not require quotes around attribute values.

However, W3C recommends quotes in HTML, and demands quotes for stricter document types like XHTML.

Good:
```HTML
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>


```

Bad:
```HTML 
<a href=https://www.w3schools.com/html>Visit our HTML tutorial</a>

```

Example:

```html


<!DOCTYPE html>
<html>
<body>

<h1>About W3Schools</h1>

<p title=About W3Schools>
You cannot omit quotes around an attribute value 
if the value contains spaces.
</p>

<p><b>
If you move the mouse over the paragraph above,
your browser will only display the first word from the title.
</b></p>

</body>
</html>

```


## Chapter Summary
- All HTML elements can have attributes
- The `href` attribute of `<a>` specifies the URL of the page the link goes to
- The `src` attribute of `<img>` specifies the path to the image to be displayed
- The `width` and `height` attributes of `<img>` provide size information for images
- The `alt` attribute of `<img>` provides an alternate text for an image
- The `style` attribute is used to add styles to an element, such as color font, size, and more
- The `lang` attribute of the `<html>` tag declares the language of the Web page
- The `title` attribute defines some extra information about an element


## HTML Attribute Reference
A complete list of all attributes for each HTML element, is listed in w3Schools: [HTML Attribute Reference](https://www.w3schools.com/tags/ref_attributes.asp).



