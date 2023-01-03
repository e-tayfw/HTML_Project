# **IMPORTANT TAGS AND ATTRIBUTEs TO TAKE NOTE**

# HTML Paragraphs

The HTML p element defines a paragraph.
A paragraph always start on a new line, and browsers automatically add soem white space (a margin) before and after a paragraph.

### Example:
```htm
<p>This is a paragraph.</p> 
<p>This is another paragprah.</p>
```

## HTML Display
You cannot be sure how the HTML will be displayed.
Large or small screens, and resized windows will create different results.
With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code
The browser will automatically remove any extra spaces and lines when the page is displayed

### Example:
```htm
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>
```
See how these codes are runned below
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>

## HTML Horizontal Rules
The hr tag defines a thermic break in an HTML page. This break is often displayed as a horizontal rule, a line break
    
The hr elemnt is used to seperate content (or define a change) in a HTML page:

### Example:
```htm
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```
LOOK AT HOW THE CODE IS BEING RUNNED BELOW:

<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

 The hr tag is an empty tag, this means that there is no end tag, and element within the tag

## HTML Line Breaks
The HTML br element defines a line break.
Use br if you want a line break (a new line) without starting a new paragraph

```htm
<p>This is<br>a paragraph<br>with line breaks</p>
```
NOTICE HOW THE LINE BREAKS NOW WITH <br>
<p>This is<br>a paragraph<br>with line breaks</p>

## HTML Pre Element
Lets say you want to display your code in the format shown below

### Example:
```htm
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>
```

NOTICE HOW THE ACTUAL OUTPUT IS IN ONE LINE

<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>

This is why we use pre, which defines pre-formatted text. The text inside a pre element is displayed in a fixed-width font (usually Courier), and it preserves boths SPACES and LINE BREAKS:

```htm
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>


# HTML Styles
The HTML style is used to add styles to an element, such as colour, font, size and many more

## HTML Style Attribute
Remember that if you want to include any styles to your text, a style atrribute must be included 
The HTML style attribute is included in the following syntax below

```htm
<h1 style="property:value;"></h1>
```
The property is a CSS property and the value is a CSS value. More will be taught in HTML CSS 

## HTML Background Colour
Self-explanatory, the CSS background-colour defines the background colour for an HTML element

### Example:
In this example, we will set the background colour of our webpage to powderblue

```htm
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```

<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
You can also set the background colour for 2 different elements
```htm
<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
```
<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>

## HTML Text Colour
The CSS color property defines text color of a HTML element. Take note that the word color is in the United States format

### Example:
```htm
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph</p>
```
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph</p>

## HTML Text Size
The CSS font-size property defines the text size for a HTML element

### Example:
```htm
<h1 style="font-size:300%;">This is a heading</h1>
<h1 style="font-size:250%;">This is a heading as well, with a smaller font</h1>
```
<h1 style="font-size:300%;">This is a heading</h1>
<h1 style="font-size:250%;">This is a heading as well, with a smaller font</h1>

## HTML Text Alignment
The CSS text-align property defines the horizontal text alignment for an HTML element

### Example:
```htm
<h1 style="text-align:center;">This is a centered heading</h1>
<p style="text-align:center;">This is a centered paragraph</p>
```
<h1 style="text-align:center;">This is a centered heading</h1>
<p style="text-align:center;">This is a centered paragraph</p>


# HTML Formatting
HTML contains several elements for defining text with a special meaning. This can be done by formatting text in specific ways, using various formatting elements.

## HTML Bold
HTML text be bolded, by doing the following below with a b tag, without any extra importance

### Example:
```htm
<b>This text is bold</b>
```
<b>This text is bold</b>

## HTML Strong
This HTML element defines a bolded text, with extra importance

### Example:
```htm
<strong>This text is bolded, with extra importance</strong>
```
<strong>This text is bolded, with extra importance</strong>

## HTML Italic
This HTML element makes text italic with the i tag. The HTML i element defines part of text in an alternative mood or voice. This element is often used to indicate a technical term, a phrase from another language, a thought or a ship name etc.

### Example:
```htm
<i>This text is italic</i>
```
<i>This text is italic</i>

## HTML Emphasized Text
This HTML element displayed emphasized text in italic. A screen reader will pronounce the words in <em> with an emphasis, using verbal stress

<em>This text is emphasized</em>

## HTML Small Element
This small element defines smaller text

### Example:
```htm
<small>This is a small text</small>
```
<small>This is a small text</small>

## HTML Mark Element
This mark element defines text that is highlighted or marked. Used in a nested element

### Example:
```htm
<p>Do not forget to buy <mark>milk</mark>.</p>
```
<p>Do not forget to buy <mark>milk</mark>.</p>

## HTML Del Element
The del element defines text that have been deleted from a document. Usually browsers will strikethrough a deleted text

### Example:
```htm
<p>My favourite colour is <del>blue</del> red.</p>
```
<p>My favourite colour is <del>blue</del> red.</p>

## HTML Ins Element
The ins element defines a text that has been inserted into a document. Usually, browsers will underscore inserted text

### Example:
```htm
<p>My favourite colour is <del>blue</del> <ins>red</ins>.</p>
```
<p>My favourite colour is <del>blue</del> <ins>red</ins>.</p>

## HTML Sub Element
The HTML sub element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:

### Example:
```htm
<p>This is <sub>subscripted</sub> text.</p>
```
<p>This is <sub>subscripted</sub> text.</p>

## HTML Sup Element
The HTML sup element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:

### Example:
```htm
<p>This is <sub>superscripted</sub> text.</p>
```
<p>This is <sub>superscripted</sub> text.</p>


# HTML Quotations/Citations
We will go through different quoting elements in this section

## HTML Blockquotes
The HTML <blockquote> element defines a section that is quoted from another source. Browsers will usually indent the blockquote sections

### Example:
```htm
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
```
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>

## HTML Short Quotations 
The HTML q tag defines a short quotation. Browsers normally insert quotation marks around the quotation

### Example:
```htm
<p> WWF goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```
<p> WWF goal is to: <q>Build a future where people live in harmony with nature.</q></p>

## HTML Abbreviations
 The HTML tag abbr defines a abbreviation or an acronym. Marking abbreviations can give useful information to browsers, translation-systems and search engines.

Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element. 

### Example:
```htm
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

## HTML Address
The address element defines the contact information for the author of a document. Contact information can be: email address, URL, physical address, phone number, social media handle, etc. The text in the address element usually renders in italic, and browsers will always add a line break before and after the address element.

### Example:
```htm
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

## HTML Work Title
The HTML cite tag defines the title for a creative work. A person's name is not the title of a work

### Example:
```htm
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>
```
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>

## HTML Bi-Directional Override
    The HTML tag <bdo> is used to override the current text direction
### Example:
```htm
<bdo dir="rtl">This text will be written from right to left</bdo>
```
<bdo dir="rtl">This text will be written from right to left</bdo>

Take note of the attribute dir used to show what direction, in this case is rtl(right to left)


# HTML Comments
HTML Comments are not displayed on the web page in the browser, but they can help with your HTML source code

## HTML Comment Tag
You can add comments on HTML using the following syntax below
<! -- Write your comments here -->
Notice that there is an exclamation point only at the start tag but not at the end tag

YOU CAN USE COMMENT DIFFERNETLY
## Add Comment
 With comments you can place reminders and notifications

### Example:
```htm
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->

```
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->

## Hide Comment
Comments can also be useful in hiding content temporarily. Once everything is confirmed, you can deleted the appropriate hidden text

### Example:
```htm
<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>
```
<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>

## Hide Inline Comment
Comments can also be used to hide parts in the middle of the HTML code.

### Example:
```htm
<p>This <!-- great text --> is a paragraph.</p>
```
<p>This <!-- great text --> is a paragraph.</p>

For more regarding the HTML Tag Reference, click below:
<a href="https://www.w3schools.com/tags/default.asp">HTML Tag Reference</a>