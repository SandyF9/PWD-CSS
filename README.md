# PWD-CSS
Cascading Style Sheets (CSS) bahasa pemrograman yang digunakan untuk mengatur tampilan atau gaya (styling) dari halaman web yang dibuat dengan HTML.

## HTML HOME
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightblue;
}
h4 {
  color: white;
  text-align: center;
}
p {
  font-family: verdana;
  font-size: 20px;
}
</style>
</head>
<body>
<h4>Ini adalah style warna pada text dan background</h4>
<p>Hai saya Sandy Febrianto.</p>
</body>
</html>

## CSS Introduction 
CSS memberikan sebuah warna maupun value ke dalam pemograman html, yang disempurnakan oleh CSS.
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightblue;
}
h1 {
  color: white;
  text-align: center;
}
p {
  font-family: verdana;
  font-size: 20px;
}
</style>
</head>
<body>
  
<h1>Example Style</h1>
<p>Begitu Indah bukan Backgroundnya.</p>
</body>
</html>

## CSS Syntax 
<ul>
  <li> p is a selector in CSS it points HTML element you want to style p </li>
  <li> color is a property, and red is the property value </li>
  <li> text-align is a property, and center is the property value </li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
p {
  color: red;
  text-align: center;
} 
</style>
</head>
<body>
<p>Hello World!</p>
<p>These paragraphs are styled with CSS.</p>
</body>
</html>

## CSS Selector
<!DOCTYPE html>
<html>
<head>
<style>
#para1 {
  text-align: center;
  color: red;
}
</style>
</head>
<body>
<p id="para1">Hello World!</p>
<p>This paragraph is not affected by the style.</p>

</body>
</html>

## CSS How To
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}


<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>

## CSS Comments
<!DOCTYPE html>
<html>
<head>
<style>
/* This is a single-line comment */
p {
  color: red;
} 
</style>
</head>
<body>

<p>Hello World!</p>
<p>This paragraph is styled with CSS.</p>
<p>CSS comments are not shown in the output.</p>

</body>
</html>

## CSS Colors
Anda Dapat Mengetes Warna Di ColorZilla
<!DOCTYPE html>
<html>
<body>

<h4 style="/*border: 2px*/ solid Tomato;">Tomato Collor</h4>

<h4 style="/*border: 2px*/ solid DodgerBlue;">DodgerBlue collor</h4>

<h4 style="/*border: 2px*/ solid Violet;">Violet Collor</h4>

</body>
</html>

## CSS Backgrounds
#### BackGround Color
<ul>
  <li>background-color</li>
  <li>background-image</li>
  <li>background-repeat</li>
  <li>background-attachment</li>
  <li>background-position</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightblue;
}
</style>
</head>
<body>
<h3>Hello World!</h3>
<p>This page has a light blue background color!</p>
</body>
</html>

#### BackGround Image
body {
background-image: url("paper.gif");
background-image: url("bgdesert.jpg");
}
p {
  background-image: url("paper.gif");
}

#### BackGround Repeat
body {
  background-image: url("gradient_bg.png");
  background-repeat: repeat-x;
}

#### BackGround Attachment
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}

## CSS Borders
#### Border 
<ul>
  <li>dotted - Defines a dotted border</li>
  <li>dashed - Defines a dashed border</li>
  <li>solid - Defines a solid border</li>
  <li>double - Defines a double border</li>
  <li>groove - Defines a 3D grooved border. The effect depends on the border-color value</li>
  <li>ridge - Defines a 3D ridged border. The effect depends on the border-color value</li>
  <li>inset - Defines a 3D inset border. The effect depends on the border-color value</li>
  <li>outset - Defines a 3D outset border. The effect depends on the border-color value</li>
  <li>none - Defines no border</li>
  <li>hidden - Defines a hidden border</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
</style>
</head>
<body>

<h2>The border-style Property</h2>
<p>This property specifies what kind of border to display:</p>

<p class="dotted">A dotted border.</p>
<p class="dashed">A dashed border.</p>
<p class="solid">A solid border.</p>
<p class="double">A double border.</p>
<p class="groove">A groove border.</p>
<p class="ridge">A ridge border.</p>
<p class="inset">An inset border.</p>
<p class="outset">An outset border.</p>
<p class="none">No border.</p>
<p class="hidden">A hidden border.</p>
<p class="mix">A mixed border.</p>

</body>
</html>

#### Border Width
p.one {
  border-style: solid;
  border-width: 5px;
}

p.two {
  border-style: solid;
  border-width: medium;
}

p.three {
  border-style: dotted;
  border-width: 2px;
}

p.four {
  border-style: dotted;
  border-width: thick;
}
#### Border Color
<ul>
  <li>name - specify a color name, like "red"</li>
  <li>HEX - specify a HEX value, like "#ff0000"</li>
  <li>RGB - specify a RGB value, like "rgb(255,0,0)"</li>
  <li>HSL - specify a HSL value, like "hsl(0, 100%, 50%)"</li>
  <li>transparent</li>
</ul>

p.one {
  border-style: solid;
  border-color: red;
}

p.two {
  border-style: solid;
  border-color: green;
}

p.three {
  border-style: dotted;
  border-color: blue;
}

#### Border Sides
p {
  border-top-style: dotted;
  border-right-style: solid;
  border-bottom-style: dotted;
  border-left-style: solid;
}
p {
border-style: dotted solid;
}

#### Border Shortland
p {
  border: 5px solid red;
}  
p {
  border-left: 6px solid red;
  background-color: lightgrey;
}

#### Rounded border
p {
  border: 2px solid red;
  border-radius: 5px;
}

## CSS Margins
Margin adalah pemberi jarak.
div {
  margin: 200px;
  border: 1px solid #4CAF50;
}  
<ul> margin-top</ul>
<ul> margin-right</ul>
<ul> margin-bottom</ul>
<ul> margin-left</ul>

#### Margin Colapse
h1 {
  margin: 0 0 50px 0;
}
h2 {
  margin: 20px 0 0 0;
}

## CSS Padding
<ul>
  <li>padding-top (25px) </li>
  <li>padding-right (50px) </li>
  <li>padding-bottom (75px) </li>
  <li>padding-left (100px) </li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
div {
  padding: 70px;
  border: 1px solid #4CAF50;
}
</style>
</head>
<body>

<h2>CSS Padding</h2>
<div>This element has a padding of 70px.</div>

</body>
</html>

div {
  padding: 25px 50px 75px 100px;
}

## CSS Height/Width
div {
  height: 200px;
  width: 50%;
  background-color: powderblue;
}

<!DOCTYPE html>
<html>
<head>
<style>
div {
  max-width: 500px;
  height: 100px;
  background-color: powderblue;
}
</style>
</head>
<body>

<h2>Set the max-width of an element</h2>

<div>This div element has a height of 100px and a max-width of 500px.</div>

<p>Resize the browser window to see the effect.</p>

</body>
</html>

## CSS Box Model
320px (width of content area)
+ 20px (left padding + right padding)
+ 10px (left border + right border)
= 350px (total width)

  50px (height of content area)
+ 20px (top padding + bottom padding)
+ 10px (top border + bottom border)
= 80px (total height)

div {
  width: 320px;
  height: 50px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}

## CSS Outline
Outline adalah sebuah penebalan dalam tabel atau kolom.

<ul> 
  <li>outline-style</li>
  <li>outline-color</li>
  <li>outline-width</li>
  <li>outline-offset</li>
  <li>outline</li>
</ul>
#### Outline Width
p.ex1 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: thin;
}
p.ex2 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: medium;
}
p.ex3 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: thick;
}
p.ex4 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: 4px;
}

#### Outline color 
p.ex1 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: red;
}

p.ex2 {
  border: 2px solid black;
  outline-style: dotted;
  outline-color: blue;
}

p.ex3 {
  border: 2px solid black;
  outline-style: outset;
  outline-color: grey;
}

#### Outline Shorles
p.ex1 {outline: dashed;}
p.ex2 {outline: dotted red;}
p.ex3 {outline: 5px solid yellow;}
p.ex4 {outline: thick ridge pink;}

#### Outline Offset
p {
  margin: 30px;
  border: 1px solid black;
  outline: 1px solid red;
  outline-offset: 15px;
}

## CSS Text
#### Text Color
body {
  color: blue;
}

h1 {
  color: green;
}

#### Text Aliigment
<ul>
  <li>text-align</li>
  <li>text-align-last</li>
  <li>direction</li>
  <li>unicode-bidi</li>
  <li>vertical-align</li>
</ul>

h1 {
  text-align: center;
}
h2 {
  text-align: left;
}
h3 {
  text-align: right;
}

#### Text Decoration
<ul> 
  <li>text-decoration-line</li>
  <li>text-decoration-color</li>
  <li>text-decoration-style</li>
  <li>text-decoration-thickness</li>
  <li>text-decorationv</li>
</ul>

h1 {
  text-decoration-line: overline;
  text-decoration-color: red;
}

h2 {
  text-decoration-line: line-through;
  text-decoration-color: blue;
}

h3 {
  text-decoration-line: underline;
  text-decoration-color: green;
}

p {
  text-decoration-line: overline underline;
  text-decoration-color: purple;
}

#### Text Tranformation
Berbagai Text Menarik.
<!DOCTYPE html>
<html>
<head>
<style>
p.uppercase {
  text-transform: uppercase;
}

p.lowercase {
  text-transform: lowercase;
}

p.capitalize {
  text-transform: capitalize;
}
</style>
</head>
<body>

<h1>Using the text-transform property</h1>

<p class="uppercase">This text is transformed to uppercase.</p>
<p class="lowercase">This text is transformed to lowercase.</p>
<p class="capitalize">This text is capitalized.</p>

</body>
</html>


#### Text Spacing
Pemberi jarak pada text dalam dan dapat digunakan untuk memperbaiki text juga.
<ul>
  <li>text-indent</li>
  <li>letter-spacing</li>
  <li>line-height</li>
  <li>word-spacing</li>
  <li>white-space</li>
</ul>
p {
  text-indent: 50px;
}

#### Text Shadow
Memberikan Penebalan atau bayangan pada text
h1 {
  text-shadow: 2px 2px;
}

## CSS Fonts


## CSS Icons
## CSS Links
## CSS Lists
## CSS Tables
## CSS Display
## CSS Max-width
## CSS Position
## CSS Z-index
## CSS Overflow
## CSS Float
## CSS Inline-block
## CSS Align
## CSS Combinators
## CSS Pseudo-classes
## CSS Pseudo-elements
## CSS Opacity
## CSS Navigation Bar
## CSS Dropdowns
## CSS Image Gallery
## CSS Image Sprites
## CSS Attr Selectors
## CSS Forms
## CSS Counters
## CSS Website Layout
## CSS Units
## CSS Specificity
## CSS !important
## CSS Math Functions





