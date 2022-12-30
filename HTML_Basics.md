# "ELEMENTS FUNDEMENTAL"
1. All elements have a tag, take note of how it looks like <tagname>CONTENT GOES INSIDE HERE</tagname> Always have a <start tag> and an </end tag>

2. All elements are not case sensitive, meaning that <P> would be the same as <p> but it is good code ethic to maintain a consistent rule, so just use lower case

# "BASIC ELEMENTS"
<!DOCTYPE html>
All HTML documents to start off with <!DOCTYPE html>, this is to ensure that you are telling the computer that it is a HTML5 Document

<html>
Next will be the root element <html> which defines the whole HTML document, there  are elements with this element which makes this element a **NESTED ELEMENT**

 <heading>
    Within the html element there are certian basic tags to remember, this is the first one, the heading 
    
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
    
    consist of total of 6 headings pirority is highest at 1 all the way to 6   
    Search engines use the headings to index the structure and content of your web pages.

    Users often skim a page by its headings. It is important to use headings to show the document structure.

    <h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on.

    Font size can be changed, will go through later



<p1>
    Next will be the paragraph tags, this is self explanatory 


REMEMBER THAT EVERY SINGLE ONE OF THESE ELEMENTS HAVE A END TAG AS WELL


```htm
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

# "HTML Attributes"
1. All HTML elements can have attributes
2. Attributes provide additional information about elements 
3. Attributes are always specified in the start tag
4. Most importantly, attributes always come in name/value pairs, think of it as a python dictionary

## Simplified list of attributes 

### Href Attribute 
    <a> defines a hyper link , within the start tag, href attribute specifies URL of the page the link goes to


<a href="https://www.w3schools.com">Visit W3Schools</a>

 More will be run through later 

### Src Attribute
embedded with a <img> tag in a HTML page, src specifices the path to the image to be displayed

```htm
<img src="img_girl.jpg">
```
There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.

### Width and Height Attribute
embedded within the <img> tag as well, specify the width and height of the image
```htm
 <img src="img_girl.jpg" width="500" height="600">  
```
### Alt Attribute
embedded with the <img> tag, specifies and alternative text for the image in the case that the image cannot be displayed or found. This occurs due to a slow connection/ error in src or if the user uses a screen reader
```htm
    <img src="img_typo.jpg" alt="Girl with a jacket">
```
### Style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.
```htm
 <p style="color:red;"> This is a paragraph. </p>
```
More will be learnt later
### Lang Attribute 
Lang is included within the start tag of <html>, to define the language of the entire Web page. This is meant to assit search engines and browsers
```htm
<!DOCTYPE html>
    <html lang="en-US">
    <body>
    ...
    </body>
    </html>
```
As you can see above, language can also be specificed by country type, in the case above the language is specificed to be United States English

More can be seen in the hyper link below:
```htm
<a href="https://www.w3schools.com/tags/ref_language_codes.asp">HTML Langugae Code</a>
```
### Title Attribute 
The title attribute defines some extra information about an element.
The value of the title attribute will be displayed as a tooltip when you mouse over the element:
```htm
<p title="I'm a tooltip">This is a paragraph.</p>
```

# TIPS TO TAKE NOTE OFF:
1. Use lowercases, HTML standard does not require it, this is however, demanded in stricter document types like XHTML, and it is also good to standardise throughout

2. Always Quote attribute values, HTML standard does not require it, this is however, demanded in stricter document types like XHTML, and it is also good to standardise throughout

Good:
```htm
 <a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
```
 Bad:
```htm
 <a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
```

Quotes are also required, especially when using the title attribute and there is a space in the title

# Single or Double Quotes

Double quotes around attribute values are the most common in HTML, but single quotes can also be used.
In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

```htm
<p title='John "ShotGun" Nelson'>
```
or vice versa
```htm
<p title="John 'ShotGun' Nelson">
```

HTML attribute reference:
 <a href="https://www.w3schools.com/tags/ref_attributes.asp">All Attributes</a>

