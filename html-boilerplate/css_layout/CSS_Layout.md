# CSS LAYOUTS
<hr>
<hr>
<br>
CSS page layout techniques allow us to take elements contained in a web page and control where they're positioned relative to the following factors: 
<br>
 1. their default position in normal flow layout
 2. The other elements around them
 3. The main viewport/ window
<br>
The page layout techniques will be covered more into detail:
    - [Normal flow] (#Normal Flow)
    - [The display property] (#The Display Property)
    - [Flexbox] (#Flexbox)
    - [Grid] (#Grid)
    - [Floats] (#Floats)
    - [Positioning] (#Positioning)
    - [Table Layout] (#Table Layout)
    - [Multiple Column Layout] (#Multiple Column Layout)
<hr>

## Normal Flow

Normal flow is how the browser lays out the HTML pages by default when you do nothing to control the page layout. This is an example:
```htm
<p>I love my cat.</p>

<ul>
  <li>Buy cat food</li>
  <li>Exercise</li>
  <li>Cheer up friend</li>
</ul>

<p>The end!</p>
```
<br>
By default, this is the end result:
<img src="../img/Normal_Layout.png" alt="Normal Layout Code">

Notice how the output follow the exact layout as the code being shown above.
- The elements that appear below and above wach other are *** BLOCK ELEMENTS ***
- The elements that appear beside each other, as shown in a sentence are *** INLINE ELEMENTS ***

Note: The direction in which block element contents are laid out is described as the Block Direction. The Block Direction runs vertically in a language such as English, which has a horizontal writing mode. It would run horizontally in any language with a Vertical Writing Mode, such as Japanese. The corresponding Inline Direction is the direction in which inline contents (such as a sentence) would run.
<hr>

## Display Property

We specify methods using the display property to change the way that the elements are being displayed in a specific way. 

For example:
    <a> element is displayed inline by default, so if we want to change the way that the <a> element is displayed, we can use display : block to display the elements in block style

Lets look at another example:
    the elements in <li> lists are displayed in block form, if you want them to be displayed in inline form, you can use the display property accordingly, display : inline

There are many more ways to use the display property, which will be gone through in the next few sections such as *** display : flex *** or **display : grid**
<hr>

## FlexBox

Flexbox is a one-dimensional layout methodfor arranging items in row or columns. Items will expand (in this term: flex) to fill additional space or shrink to fit into smaller spaces.

In order to understand:
This is what the code intially looks like
<hr>
<img src="../img/FlexBox_Example" alt="initial layout">

With the new code:
<a href="../css_layout/flexbox0.html">Look at the link below</a>

```css
section {
        display: flex
      }
```
What the code above does causes the section elements to become a *** flex** container and the children to become *** flex *** items.
The default values given to flex items are set up to solve the following problems:

- Vertically centering a block of content inside its parent.
-  all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

To further understand the flex model, it looks like this:
<img src="../img/flex_model" alt="initial layout">





