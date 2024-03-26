# HTML Comments
HTML comments are not displayed in the browser, but they can help document your HTML source code.

You can add comments to your HTML source by using the following syntax:

```html
<!-- Write your comments here -->
```

Notice that there is an exclamation point (!) in the start tag, but not in the end tag.

Note: Comments are not displayed by the browser, but they can help document your HTML source code.

# 1- Add Comments
With comments you can place notifications and reminders in your HTML code:

```html
<!DOCTYPE html>
<html>
<body>

<!-- This is a comment -->
<p>This is a paragraph.</p>
<!-- Comments are not displayed in the browser -->

</body>
</html>

```

# 2- Hide Content

Comments can be used to hide content.

This can be helpful if you hide content temporarily:

```html
<!DOCTYPE html>
<html>
<body>

<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>

</body>
</html>
```

You can also hide more than one line. Everything between the `<!-- and the -->` will be hidden from the display.

```html
<!DOCTYPE html>
<html>
<body>

<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>

</body>
</html>

```

# 3- Hide Inline Content

Comments can be used to hide parts in the middle of the HTML code.

```html
<!DOCTYPE html>
<html>
<body>

<p>This <!-- great text --> is a paragraph.</p>

</body>
</html>

```

