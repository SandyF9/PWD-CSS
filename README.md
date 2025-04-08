# PWD-CSS
Cascading Style Sheets (CSS) bahasa pemrograman yang digunakan untuk mengatur tampilan atau gaya (styling) dari halaman web yang dibuat dengan HTML.

## HTML HOME
Memberikan Warna pada background, text.
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
Text berada pada tengah menggunakan center dan text berwarna.
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
#Paral memberikan bagian bagian, atau membagi tugas menjadi beberapa bagian yang dapat dikerjakan secara bersamaan. 
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
Anda Dapat Mengetes Warna Di ColorZilla.
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
Memberikan warna pada background, dan warna warna pada gambar.
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
Memberikan berbagai jenis tabel, dll, serta warna.
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
Hampir sama, yaitu memberikan jarak, supaya text menjadi terstruktur. Pada Pading memberikan jarak dari kiri.
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
Tinggi dan lebar.
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
Membuat isi di dalam box, dengan berbagai style warna.
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
Memberikan berbagai font pada text.
#### Font Family
<ul>
   <li>Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.</li>
   <li>Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.</li>
   <li>Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. </li>
   <li>Cursive fonts imitate human handwriting.</li>
   <li>Fantasy fonts are decorative/playful fonts.</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
.p1 {
  font-family: "Times New Roman", Times, serif;
}

.p2 {
  font-family: Arial, Helvetica, sans-serif;
}

.p3 {
  font-family: "Lucida Console", "Courier New", monospace;
}
</style>
</head>
<body>

<h1>CSS font-family</h1>
<p class="p1">This is a paragraph, shown in the Times New Roman font.</p>
<p class="p2">This is a paragraph, shown in the Arial font.</p>
<p class="p3">This is a paragraph, shown in the Lucida Console font.</p>

</body>
</html>

#### Font Web Safe
<!DOCTYPE html>
<html>
<head>
<style>
p {
font-family: Tahoma, Verdana, sans-serif;
}
</style>
</head>
<body>

<h1>CSS Fallback Fonts</h1>

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>

#### Font Fallbacks
<ul>
  <li>Serif</li>
  <li>Sans-serif</li>
  <li>Monospace</li>
  <li>Cursive</li>
  <li>Fantasy</li>
  <li>font-Family = Copperplate, Papyrus, fantasy</li>
  <li>font-Family = "Brush Script MT", cursive</li>
  <li>font-Family = "Courier New", Courier, monospace</li>
</ul>

#### Font Style
<ul>
  <li>normal - The text is shown normally</li>
  <li>italic - The text is shown in italics</li>
  <li>oblique - The text is "leaning" (oblique is very similar to italic, but less supported)</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
p.normal {
  font-style: normal;
}

p.italic {
  font-style: italic;
}

p.oblique {
  font-style: oblique;
}
</style>
</head>
<body>

<h1>The font-style property</h1>

<p class="normal">This is a paragraph in normal style.</p>
<p class="italic">This is a paragraph in italic style.</p>
<p class="oblique">This is a paragraph in oblique style.</p>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<style>
p.normal {
  font-weight: normal;
}

p.light {
  font-weight: lighter;
}

p.thick {
  font-weight: bold;
}

p.thicker {
  font-weight: 900;
}
</style>
</head>
<body>

<h1>The font-weight property</h1>

<p class="normal">This is a paragraph.</p>
<p class="light">This is a paragraph.</p>
<p class="thick">This is a paragraph.</p>
<p class="thicker">This is a paragraph.</p>

</body>
</html>

#### Font Size
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  font-size: 40px;
}

h2 {
  font-size: 30px;
}

p {
  font-size: 14px;
}
</style>
</head>
<body>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>

#### Font Google
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
<style>
body {
  font-family: "Sofia", sans-serif;
}
</style>
</head>
<body>

<h1>Sofia Font</h1>
<p>Lorem ipsum dolor sit amet.</p>
<p>123456790</p>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Trirong">
<style>
body {
  font-family: "Trirong", serif;
}
</style>
</head>
<body>

<h1>Trirong Font</h1>
<p>Lorem ipsum dolor sit amet.</p>
<p>123456790</p>

</body>
</html>

#### Font Pairing
Pelengkap Font dengan style warna.
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: black;
  font-family: Verdana, sans-serif;
  font-size: 16px;
  color: gray;  
}

h1 {
  font-family: Georgia, serif;
  font-size: 60px;
  color: white;
}
</style>
</head>
<body>

<h1>Beautiful Norway</h1>
<p>Norway has a total area of 385,252 square kilometers and a population of 5,438,657 (December 2020). Norway is bordered by Sweden, Finland and Russia to the north-east, and the Skagerrak to the south, with Denmark on the other side.</p>
<p>Norway has beautiful mountains, glaciers and stunning fjords. Oslo, the capital, is a city of green spaces and museums. Bergen, with colorful wooden houses, is the starting point for cruises to the dramatic Sognefjord. Norway is also known for fishing, hiking and skiing.</p>
</body>
</html>

#### Font Shorthand
<ul>
  <li>font-style</li>
  <li>font-variant</li>
  <li>font-weight</li>
  <li>font-size/line-height</li>
  <li>font-family</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
p.a {
  font: 20px Arial, sans-serif;
}

p.b {
  font: italic small-caps bold 12px/30px Georgia, serif;
}
</style>
</head>
<body>

<h1>The font Property</h1>

<p class="a">This is a paragraph. The font size is set to 20 pixels, and the font family is Arial.</p>

<p class="b">This is a paragraph. The font is set to italic, small-caps and bold, the font size is set to 12 pixels, the line height is set to 30 pixels, and the font family is Georgia.</p>

</body>
</html>

## CSS Icons
Menmbahkan icon ke dalam html dan css.
<!DOCTYPE html>
<html>
<head>
<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

<i class="fas fa-cloud"></i>
<i class="fas fa-heart"></i>
<i class="fas fa-car"></i>
<i class="fas fa-file"></i>
<i class="fas fa-bars"></i>

</body>
</html>

## CSS Links
Menambahkan link ke dalam html dengan css dan warna.
<!DOCTYPE html>
<html>
<head>
<style>
a {
  color: hotpink;
}
</style>
</head>
<body>

<h2>Style a link with a color</h2>

<p><b><a href="default.asp" class="link" target="_blank">This is a link</a></b></p>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<style>
a:link {
  text-decoration: none;
}

a:visited {
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

a:active {
  text-decoration: underline;
}
</style>
</head>
<body>

<h2>Styling a link with text-decoration property</h2>

<p><b><a href="default.asp" target="_blank">This is a link</a></b></p>
<p><b>Note:</b> a:hover MUST come after a:link and a:visited in the CSS definition in order to be effective.</p>
<p><b>Note:</b> a:active MUST come after a:hover in the CSS definition in order to be effective.</p>

</body>
</html>

## CSS Lists
Contoh membuat:

Unordered Lists:
<ul>Coffee
  <li>Tea</li>
  <li>Coca Cola</li>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>
Ordered Lists:
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}
</style>
</head>
<body>

<h2>The list-style-type Property</h2>

<p>Example of unordered lists:</p>
<ul class="a">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>

<ul class="b">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>

<p>Example of ordered lists:</p>
<ol class="c">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ol>

<ol class="d">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ol>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-image: url('sqpurple.gif');
}
</style>
</head>
<body>

<h2>The list-style-image Property</h2>

<p>The list-style-image property specifies an image as the list item marker:</p>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<style>
ul.a {
  list-style-position: outside;
}

ul.b {
  list-style-position: inside;
}
</style>
</head>
<body>

<h1>The list-style-position Property</h1>

<h2>list-style-position: outside (default):</h2>
<ul class="a">
  <li>Coffee - A brewed drink prepared from roasted coffee beans, which are the seeds of berries from the Coffea plant</li>
  <li>Tea - An aromatic beverage commonly prepared by pouring hot or boiling water over cured leaves of the Camellia sinensis, an evergreen shrub (bush) native to Asia</li>
  <li>Coca Cola - A carbonated soft drink produced by The Coca-Cola Company. The drink's name refers to two of its original ingredients, which were kola nuts (a source of caffeine) and coca leaves</li>
</ul>

<h2>list-style-position: inside:</h2>
<ul class="b">
  <li>Coffee - A brewed drink prepared from roasted coffee beans, which are the seeds of berries from the Coffea plant</li>
  <li>Tea - An aromatic beverage commonly prepared by pouring hot or boiling water over cured leaves of the Camellia sinensis, an evergreen shrub (bush) native to Asia</li>
  <li>Coca Cola - A carbonated soft drink produced by The Coca-Cola Company. The drink's name refers to two of its original ingredients, which were kola nuts (a source of caffeine) and coca leaves</li>
</ul>

</body>
</html>

## CSS Tables
Membuat tabel dengan berbagai warna dan style, serta size.
#### Table Border
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid;
}
</style>
</head>
<body>

<h2>Add a border to a table:</h2>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>

</body>
</html>

#### Table Size
<!DOCTYPE html>
<html>
<head>
<style>
table, td, th {
  border: 1px solid black;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th {
  height: 70px;
}
</style>
</head>
<body>

<h2>The width and height Properties</h2>

<p>Set the width of the table, and the height of the table header row:</p>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
    <td>$150</td>
  </tr>
  <tr>
    <td>Joe</td>
    <td>Swanson</td>
    <td>$300</td>
  </tr>
  <tr>
    <td>Cleveland</td>
    <td>Brown</td>
    <td>$250</td>
  </tr>
</table>

</body>
</html>

#### Table Aligment
Mengubah text atau tabel berada.
td {
  text-align: center;
}

#### Table Style
Memberikan jarak dan warna pada tabel.

th, td {
  padding: 15px;
  text-align: left;
}

th, td {
  border-bottom: 1px solid #ddd;
}

tr:nth-child(even) {background-color: #f2f2f2;}

tr:hover {background-color: coral;}

#### Table Responsive
<div style="overflow-x:auto;">

<table>
... table content ...
</table>

</div>

<!DOCTYPE html>
<html>
<head>
<style>
table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  text-align: left;
  padding: 8px;
}

tr:nth-child(even) {background-color: #f2f2f2;}
</style>
</head>
<body>

<h2>Responsive Table</h2>
<p>A responsive table will display a horizontal scroll bar if the screen is too 
small to display the full content. Resize the browser window to see the effect:</p>
<p>To create a responsive table, add a container element (like div) with <strong>overflow-x:auto</strong> around the table element:</p>

<div style="overflow-x: auto;">
  <table>
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
      <td>67</td>
    </tr>
  </table>
</div>

</body>
</html>

## CSS Display
<ul>
  <li>span></li>
  <li>a></li>
  <li>img></li>
</ul>

span {
  display: block;
}

a {
  display: block;
}

h1.hidden {
  display: none;
}

h1.hidden {
  visibility: hidden;
}

## CSS Max-width
<!DOCTYPE html>
<html>
<head>
<style>
div.ex1 {
  width: 500px;
  margin: auto;
  border: 3px solid #73AD21;
}

div.ex2 {
  max-width: 500px;
  margin: auto;
  border: 3px solid #73AD21;
}
</style>
</head>
<body>

<h2>CSS Max-width</h2>

<div class="ex1">This div element has width: 500px;</div>
<br>

<div class="ex2">This div element has max-width: 500px;</div>

<p><strong>Tip:</strong> Drag the browser window to smaller than 500px wide, to see the difference between 
the two divs!</p>

</body>
</html>

## CSS Position
div.static {
  position: static;
  border: 3px solid #73AD21;
}
<ul>
  <li>static</li>
  <li>relative</li>
  <li>fixed</li>
  <li>absolute</li>
  <li>sticky</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
div.static {
  position: static;
  border: 3px solid #73AD21;
}
</style>
</head>
<body>

<h2>position: static;</h2>

<p>An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:</p>

<div class="static">
This div element has position: static;
</div>

</body>
</html>

## CSS Z-index
apakah mau di taruh di depan atau belakang. Biasanya diguanakan pada media.
<!DOCTYPE html>
<html>
<head>
<style>
img {
  position: absolute;
  left: 0px;
  top: 0px;
  z-index: -1;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<img src="img_tree.png">
<p>Because the image has a z-index of -1, it will be placed behind the text.</p>

</body>
</html>

## CSS Overflow
Dapat menghialngkan bagian yang berlebihan, hal ini dapat digunakan untuk scroll ke arah bawah jiak di tambahin. Di dalam kolom/sebuah kolom text.
<ul>
  <li>visible - Default. The overflow is not clipped. The content renders outside the element's box</li>
  <li>hidden - The overflow is clipped, and the rest of the content will be invisible</li>
  <li>scroll - The overflow is clipped, and a scrollbar is added to see the rest of the content</li>
  <li>auto - Similar to scroll, but it adds scrollbars only when necessary</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
#overflowTest {
  background: #4CAF50;
  color: white;
  padding: 15px;
  width: 50%;
  height: 100px;
  overflow: scroll;
  border: 1px solid #ccc;
}
</style>
</head>
<body>

<h2>CSS Overflow</h2>

<p>The overflow property controls what happens to content that is too big to fit into an area.</p>

<div id="overflowTest">This text is really long and the height of its container is only 100 pixels. Therefore, a scrollbar is added to help the reader to scroll the content. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem.</div>

</body>
</html>

## CSS Float
Penempatan foto atau lain lain, agar lebih rapi.
<ul>
  <li>left - The element floats to the left of its container</li>
  <li>right - The element floats to the right of its container</li>
  <li>none - The element does not float (will be displayed just where it occurs in the text). This is default</li>
  <li>inherit - The element inherits the float value of its parent</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
img {
  float: right;
}
</style>
</head>
<body>

<h2>Float Right</h2>

<p>In this example, the image will float to the right in the paragraph, and the text in the paragraph will wrap around the image.</p>

<p><img src="pineapple.jpg" alt="Pineapple" style="width:170px;height:170px;margin-left:15px;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas odio, vitae scelerisque enim ligula venenatis dolor. Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Mauris ante ligula, facilisis sed ornare eu, lobortis in odio. Praesent convallis urna a lacus interdum ut hendrerit risus congue. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta. Cras ac leo purus. Mauris quis diam velit.</p>

</body>
</html>

#### Clear
div1 {
  float: left;
}

div2 {
  clear: left;
}

<ul>
  <li>none - The element is not pushed below left or right floated elements. This is default</li>
  <li>left - The element is pushed below left floated elements</li>
  <li>right - The element is pushed below right floated elements</li>
  <li>both - The element is pushed below both left and right floated elements</li>
  <li>inherit - The element inherits the clear value from its parent</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
.div1 {
  float: left;
  padding: 10px;
  border: 3px solid #73AD21;
}

.div2 {
  padding: 10px;
  border: 3px solid red;
}

.div3 {
  float: left;
  padding: 10px;  
  border: 3px solid #73AD21;
}

.div4 {
  padding: 10px;
  border: 3px solid red;
  clear: left;
}
</style>
</head>
<body>

<h2>Without clear</h2>
<div class="div1">div1</div>
<div class="div2">div2 - Notice that div2 is after div1 in the HTML code. However, since div1 floats to the left, the text in div2 flows around div1.</div>
<br><br>

<h2>With clear</h2>
<div class="div3">div3</div>
<div class="div4">div4 - Here, clear: left; moves div4 down below the floating div3. The value "left" clears elements floated to the left. You can also clear "right" and "both".</div>

</body>
</html>

## CSS Inline-block
Berbagai text penting di buat dalam kolom besar.
<!DOCTYPE html>
<html>
<head>
<style>
span.a {
  display: inline; /* the default for span */
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue;  
  background-color: yellow; 
}

span.b {
  display: inline-block;
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue;    
  background-color: yellow; 
}

span.c {
  display: block;
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue;    
  background-color: yellow; 
}
</style>
</head>
<body>

<h1>The display Property</h1>

<h2>display: inline</h2>
<div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. <span class="a">Aliquam</span> <span class="a">venenatis</span> gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet. </div>

<h2>display: inline-block</h2>
<div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. <span class="b">Aliquam</span> <span class="b">venenatis</span> gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet. </div>

<h2>display: block</h2>
<div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. <span class="c">Aliquam</span> <span class="c">venenatis</span> gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet. </div>

</body>
</html>

## CSS Align
.center {
  margin: auto;
  width: 50%;
  border: 3px solid green;
  padding: 10px;
}

<!DOCTYPE html>
<html>
<head>
<style>
.center {
  margin: auto;
  width: 60%;
  border: 3px solid #73AD21;
  padding: 10px;
}
</style>
</head>
<body>

<h2>Center Align Elements</h2>
<p>To horizontally center a block element (like div), use margin: auto;</p>

<div class="center">
  <p>Hello World!</p>
</div>

</body>
</html>

## CSS Combinators
<ul>
  <li>Descendant combinator (space)</li>
  <li>Child combinator (>)</li>
  <li>Next sibling combinator (+)</li>
  <li>Subsequent-sibling combinator (~)</li>
</ul>

div p {
  background-color: yellow;
}

div > p {
  background-color: yellow;
}

div ~ p {
  background-color: yellow;
}

## CSS Pseudo-classes
Mendesain bagaian dalam yang inggin di kunjungi, dengan warna menarik.
selector:pseudo-class {
  property: value;
}

<!DOCTYPE html>
<html>
<head>
<style>
/* unvisited link */
a:link {
  color: red;
}

/* visited link */
a:visited {
  color: green;
}

/* mouse over link */
a:hover {
  color: hotpink;
}

/* selected link */
a:active {
  color: blue;
}
</style>
</head>
<body>

<h2>Styling a link depending on state</h2>

<p><b><a href="default.asp" target="_blank">This is a link</a></b></p>
<p><b>Note:</b> a:hover MUST come after a:link and a:visited in the CSS definition in order to be effective.</p>
<p><b>Note:</b> a:active MUST come after a:hover in the CSS definition in order to be effective.</p>

</body>
</html>

## CSS Pseudo-elements
Mendesain text dengan mengubah lebih gede dan dengan warna indah.
selector::pseudo-element {
  property: value;
}

<ul>
  <li>font properties</li>
  <li>color properties</li>
  <li>background properties</li>
  <li>word-spacing</li>
  <li>letter-spacing</li>
  <li>text-decoration</li>
  <li>vertical-align</li>
  <li>text-transform</li>
  <li>line-height</li>
  clear
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
p::first-letter {
  color: #ff0000;
  font-size: xx-large;
}
</style>
</head>
<body>

<p>You can use the ::first-letter pseudo-element to add a special effect to the first character of a text!</p>

</body>
</html>

## CSS Opacity
img {
  opacity: 0.5;
}
Opacity digunakan untuk mengubah warna menjadi agak pudar atau sebaliknya.

<!DOCTYPE html>
<html>
<head>
<style>
img {
  opacity: 0.5;
}
</style>
</head>
<body>

<h1>Image Transparency</h1>
<p>The opacity property specifies the transparency of an element. The lower the value, the more transparent:</p>

<p>Image with 50% opacity:</p>
<img src="img_forest.jpg" alt="Forest" width="170" height="100">

</body>
</html>

## CSS Navigation Bar
Membuat halaman, menjadi bagian bagian yang dapat dikunjungi.

<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
</style>
</head>
<body>

<p>In this example, we remove the bullets from the list, and its default padding and margin.</p>

<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

</body>
</html>

#### Vertikal Navbar
<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
</style>
</head>
<body>

<p>In this example, we remove the bullets from the list, and its default padding and margin.</p>

<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

</body>
</html>

#### Horinzontal Navbar
<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #dddddd;
}

li {
  float: left;
}

li a {
  display: block;
  padding: 8px;
}
</style>
</head>
<body>

<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

<p>A background color is added to the list instead of each link to create a full-width background color.</p>
<p><b>Note:</b> overflow:hidden is added to the ul element to prevent li elements from going outside of the list.</p>

</body>
</html>

## CSS Dropdowns
<!DOCTYPE html>
<html>
<head>
<style>
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  padding: 12px 16px;
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
</head>
<body>

<h2>Hoverable Dropdown</h2>
<p>Move the mouse over the text below to open the dropdown content.</p>

<div class="dropdown">
  <span>Mouse over me</span>
  <div class="dropdown-content">
  <p>Hello World!</p>
  </div>
</div>

</body>
</html>

## CSS Image Gallery
Membuat galeri dan penjelasannya.
<!DOCTYPE html>
<html>
<head>
<style>
div.gallery {
  margin: 5px;
  border: 1px solid #ccc;
  float: left;
  width: 180px;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}
</style>
</head>
<body>

<div class="gallery">
  <a target="_blank" href="img_5terre.jpg">
    <img src="img_5terre.jpg" alt="Cinque Terre" width="600" height="400">
  </a>
  <div class="desc">Add a description of the image here</div>
</div>

<div class="gallery">
  <a target="_blank" href="img_forest.jpg">
    <img src="img_forest.jpg" alt="Forest" width="600" height="400">
  </a>
  <div class="desc">Add a description of the image here</div>
</div>

<div class="gallery">
  <a target="_blank" href="img_lights.jpg">
    <img src="img_lights.jpg" alt="Northern Lights" width="600" height="400">
  </a>
  <div class="desc">Add a description of the image here</div>
</div>

<div class="gallery">
  <a target="_blank" href="img_mountains.jpg">
    <img src="img_mountains.jpg" alt="Mountains" width="600" height="400">
  </a>
  <div class="desc">Add a description of the image here</div>
</div>

</body>
</html>

## CSS Image Sprites
Gambar Rumah dan arah.

<!DOCTYPE html>
<html>
<head>
<style>
#home {
  width: 46px;
  height: 44px;
  background: url(img_navsprites.gif) 0 0;
}

#next {
  width: 43px;
  height: 44px;
  background: url(img_navsprites.gif) -91px 0;
}
</style>
</head>
<body>

<img id="home" src="img_trans.gif" width="1" height="1">
<img id="next" src="img_trans.gif" width="1" height="1">

</body>
</html>

## CSS Attr Selectors
Memberikan Warna pada situs web yang akan di kunjungi.
<!DOCTYPE html>
<html>
<head>
<style>
#home {
  width: 46px;
  height: 44px;
  background: url(img_navsprites.gif) 0 0;
}

#next {
  width: 43px;
  height: 44px;
  background: url(img_navsprites.gif) -91px 0;
}
</style>
</head>
<body>

<img id="home" src="img_trans.gif" width="1" height="1">
<img id="next" src="img_trans.gif" width="1" height="1">

</body>
</html>

## CSS Forms
Membuat Daftar isi bagi pengunjung.
<ul>
  <li>input[type=text] - will only select text fields</li>
  <li>input[type=password] - will only select password fields</li>
  <li>input[type=number] - will only select number fields</li>
  <li>etc..</li>
</ul>

<!DOCTYPE html>
<html>
<style>
input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
<body>

<h3>Using CSS to style an HTML Form</h3>

<div>
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>

    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>

## CSS Counters
Memberikan nomor pada situs web yang ingin dikunjungi.
<ul>
  <li>counter-reset - Creates or resets a counter</li>
  <li>counter-increment - Increments a counter value</li>
  <li>content - Inserts generated content</li>
  <li>counter() or counters() function - Adds the value of a counter to an element</li>
</ul>

<!DOCTYPE html>
<html>
<head>
<style>
body {
  counter-reset: section;
}

h2::before {
  counter-increment: section;
  content: "Section " counter(section) ": ";
}
</style>
</head>
<body>

<h1>Using CSS Counters</h1>

<h2>HTML Tutorial</h2>
<h2>CSS Tutorial</h2>
<h2>JavaScript Tutorial</h2>
<h2>Python Tutorial</h2>
<h2>SQL Tutorial</h2>

</body>
</html>

## CSS Website Layout
Membuat Layeout pada setiap bagian yang ingin di kunjungi.

<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Website Layout</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
}

/* Style the header */
.header {
  background-color: #f1f1f1;
  padding: 20px;
  text-align: center;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 15px;
}

/* Clear floats after the columns */
.row::after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width:600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>Header</h1>
  <p>Resize the browser window to see the responsive effect.</p>
</div>

<div class="topnav">
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#">Link</a>
</div>

<div class="row">
  <div class="column">
    <h2>Column</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sit amet pretium urna. Vivamus venenatis velit nec neque ultricies, eget elementum magna tristique. Quisque vehicula, risus eget aliquam placerat, purus leo tincidunt eros, eget luctus quam orci in velit. Praesent scelerisque tortor sed accumsan convallis.</p>
  </div>
  
  <div class="column">
    <h2>Column</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sit amet pretium urna. Vivamus venenatis velit nec neque ultricies, eget elementum magna tristique. Quisque vehicula, risus eget aliquam placerat, purus leo tincidunt eros, eget luctus quam orci in velit. Praesent scelerisque tortor sed accumsan convallis.</p>
  </div>
  
  <div class="column">
    <h2>Column</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sit amet pretium urna. Vivamus venenatis velit nec neque ultricies, eget elementum magna tristique. Quisque vehicula, risus eget aliquam placerat, purus leo tincidunt eros, eget luctus quam orci in velit. Praesent scelerisque tortor sed accumsan convallis.</p>
  </div>
</div>

</body>
</html>

## CSS Units
Membuat Halaman dengan huruf, hampir sama dengan h1,h2, dan p. Yang ada di M.WORD
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  font-size: 60px;
}

p {
  font-size: 25px;
  line-height: 50px;
}
</style>
</head>
<body>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>

## CSS Specificity
Memberikan Spesifikasi pada text, dapat berupa text agak keburaman maupun pudar, dan cerah.

<!DOCTYPE html>
<html>
<head>
<style>
#demo {color: blue;}
.test {color: green;} 
p {color: red;} 
</style>
</head>
<body>

<p id="demo" class="test" style="color: pink;">Hello World!</p>

</body>
</html>

## CSS !important
Membuka halaman pada text, yang inggin di tuju. Tetapi langsung masuk ke dalam situs web orang tanpa harus dari halaman depan. Dan memberikan warna pada setiap web yang telah di kunjungi.

<!DOCTYPE html>
<html>
<head>
<style>
.button {
  background-color: #8c8c8c !important; 
  color: white !important;
  padding: 5px !important;
  border: 1px solid black !important; 
}

#myDiv a {
  color: red;
  background-color: yellow;  
}
</style>
</head>
<body>

<p>Standard button: <a class="button" href="default.asp">CSS Tutorial</a></p>

<div id="myDiv">
<p>A link text inside myDiv: <a href="/html/">HTML Tutorial</a></p>
<p>A link button inside myDiv: <a href="/html/" class="button">HTML Tutorial</a></p>
</div>

</body>
</html>

## CSS Math Functions
Memperluas bagian kolom, dan memperbaiki kolom. Dan memberikan kolom pada halaman tertentu.
<!DOCTYPE html>
<html>
<head>
<style>
#div1 {
  position: absolute;
  left: 50px;
  width: calc(100% - 100px);
  border: 1px solid black;
  background-color: yellow;
  padding: 5px;
}
</style>
</head>
<body>

<h1>The calc() Function</h1>

<p>Create a div that stretches across the window, with a 50px gap between both sides of the div and the edges of the window:</p>

<div id="div1">Some text...</div>

</body>
</html>


<!DOCTYPE html>
<html>
<head>
<style>
#div1 {
  background-color: yellow;
  height: 100px;
  width: max(50%, 300px);
}
</style>
</head>
<body>

<h1>The max() Function</h1>

<p>Use max() to set the width of #div1 to whichever value is largest, 50% or 300px:</p>

<div id="div1">Some text...</div>

<p>Resize the browser window to see the effect.</p>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<style>
#div1 {
  background-color: yellow;
  height: 100px;
  width: min(50%, 300px);
}
</style>
</head>
<body>

<h1>The min() Function</h1>

<p>Use min() to set the width of #div1 to whichever value is smallest, 50% or 300px:</p>

<div id="div1">Some text...</div>

<p>Resize the browser window to see the effect.</p>

</body>
</html>
