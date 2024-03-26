# HTML Quotation and Citation Elements

In this chapter we will go through the `<blockquote>,<q>, <abbr>, <address>, <cite>, and <bdo>` HTML elements.

### Example:
<p>Here is a quote from WWF's website:</p>

<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>

<br> <br>

# 1- HTML `<blockquote>`for Quotations
The HTML `<blockquote>` element defines a section that is quoted from another source.

Browsers usually indent`<blockquote>`elements.

```html
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
```

# 2- HTML `<q>` for Short Quotations
The HTML `<q>` tag defines a short quotation.

Browsers normally insert quotation marks around the quotation.

```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

# 3- HTML `<abbr>` for Abbreviations
The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".

Marking abbreviations can give useful information to browsers, translation systems and search-engines.

Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse 
over the element

```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

# 4- HTML `<address>` for Contact Information

HTML `<address>` for Contact Information
The HTML `<address>` tag defines the contact information for the author/owner of a document or an article.

The contact information can be an email address, URL, physical address, phone number, social media handle, etc.

The text in the `<address>` element usually renders in italic, and browsers will always add a line break before and after the `<address>` element.

```html

<p>The HTML address element defines contact information (author/owner) of a document or article.</p>

<address>
Written by John Doe.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

# 5- HTML `<cite>` for Work Title
The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

Note: A person's name is not the title of a work.

The text in the `<cite>` element usually renders in italic.

```html
<p>The HTML cite element defines the title of a work.</p>
<p>Browsers usually display cite elements in italic.</p>

<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

# 6- HTML `<bdo>` for Bi-Directional Override
BDO stands for Bi-Directional Override.

The HTML `<bdo>` tag is used to override the current text direction:

```html
<p>If your browser supports bi-directional override (bdo), the next line will be written from right to left (rtl):</p>

<bdo dir="rtl">This line will be written from right to left</bdo>
```
