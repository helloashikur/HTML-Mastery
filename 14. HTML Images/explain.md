# HTML Images
Images can improve the design and the appearance of a web page.

```html
<!DOCTYPE html>
<html>
<body>

<h2>HTML Image</h2>
<img src="pic_trulli.jpg" alt="Trulli" width="500" height="333">

</body>
</html>

```

<br> <br> <br>

# HTML Images Syntax

The HTML `<img>` tag is used to embed an image in a web page.
The `<img>` tag has two required attributes:

- `src` - Specifies the path to the image
- `alt` - Specifies an alternate text for the image

## 1- The src Attribute
The required `src` attribute specifies the path (URL) to the image.

## 2- The alt Attribute
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).


<br> <br> <br>
# Image Size - Width and Height

You can use the `style` attribute to specify the width and height of an image.

Exp-1:

```HTML
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

```

Exp-2:

```HTML
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">

```

<br> <br> <br>
# Images in Another Folder
If you have your images in a sub-folder, you must include the folder name in the `src` attribute:

```html
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

```

<br> <br> <br>
# Images on Another Server/Website

Some web sites point to an image on another server.

To point to an image on another server, you must specify an absolute (full) URL in the `src` attribute:

```html
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">

```
<br> <br> <br>
# Image as a Link
To use an image as a link, put the `<img>` tag inside the` <a>` tag:

```html
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

```

<br> <br> <br>
# Common Image Formats

![alt text](image.png)



<br> <br> <br>
# Chapter Summary

- Use the HTML` <img>` element to define an image
- Use the HTML `src` attribute to define the URL of the image
- Use the HTML `alt` attribute to define an alternate text for an image, if it cannot be displayed
- Use the HTML `width` and `height` attributes or the CSS `width` and `height` properties to define the size of the image
- Use the CSS `float` property to let the image float to the left or to the right