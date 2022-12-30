# **IMPORTANT ELEMENTS AND ATTRIBUTEs TO TAKE NOTE**

# HTML Paragraphs

    The HTML <p> element defines a paragraph.
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

See how these codes are runned above

## HTML Horizontal Rules
    The <hr> tag defines a thermic break in an HTML page. This break is often displayed as a horizontal rule, a line break
    
    The <hr> elemnt is used to seperate content (or define a change) in a HTML page:

```htm
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

<hr> tag is an empty tag, this means that there is no end tag, and element within the tag

## HTML Line Breaks
    The HTML <br> element defines a line break.
    Use <br> if you want a line break (a new line) without starting a new paragraph