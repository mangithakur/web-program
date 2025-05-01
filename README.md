# web-program
<!-- 3. Use HTML5 for performing following tasks: 
I. Draw a square using HTML5 SVG , fill the square with green color and make 6px brown 
stroke width 
II. Write the following mathematical expression by using HTML5 MathML. 
d=x2-y2 
III. Redirecting current page to another page after 5 seconds using HTML5 metatag
-->


<!DOCTYPE html>
 <html>
 <head>
 <meta charset="utf-8" />
 <title>HTML5 Demo</title>
 <meta http-equiv="refresh" content="5; URL=https://pescemandya.org/ise/ise.php">
 </head>
 <body>
 <h3>HTML5 SVG</h3>
 <svg height="300" width="300" align="center"> 
 <rect x="50" y="50" width="100" height="100" fill="green" stroke="brown"
stroke-width="6px"/>
 </svg>

 <h3>HTML5 MathML</h3>

 <math xmlns = "http://www.w3.org/1998/Math/MathML">
<mrow>
 <mi>d</mi>
 <mo> = </mo>
 <msup><mi>x</mi><mn>2</mn></msup>
 <mo>-</mo>
<msup><mi>y</mi><mn>2</mn></msup>
 </mrow>
</math>

 <h3>This page redirects in 5 seconds</h3>
</body>
 </html>


 <!-- 4. Demonstrate the following HTML5 Semantic tags- <article>, <aside>, <details>, <figcaption>, <figure>, <footer>, <header>, <main>, <mark>, <section> 
for a webpage that gives informationabout travel experience. -->


<!DOCTYPE html>
 <html>
 <head> 
<metacharset="utf-8"/> 
 <title>HTML5SemanticTagsDemo</title>
<style>
body{background-color:#FFFDD0;}
aside{float:right;width:25%;background-color:cyan;font-style:italic;padding:15px;}
main{float:left;width:70%;}
footer{position:fixed;left:0;bottom:0;width:100%;text-align:center;}
mark{background-color:yellow;color:black; }
figure{display:inline-block;margin:auto;}
 figcaption{font-style:italic; }
</style> 
</head>
 <body>
<article>
<header>
<h1>My Travelogue</h1>
<p>Random Escapades</p>
</header>
 <main>
<figure>
<img src="Desert.jpg"alt="ExampleImage"width="350" height="235">
<figcaption>The road never ends</figcaption>
</figure>
<section>
  <h2>Mandya</h2>
<p>Mandya is a popular city located in the Karnataka. It is popularly called the"Sugar city ".</p>
 </section> 
<section> 
 <h2>Mysore</h2>
<p> The city is also known as the City of Palaces, Mysuru has always enchanted its visitors with its quaint charm.</p>
 </section> 
</main> 
<aside> 
<section>
 <p>UpcomingTrekked planned to <mark> KunthiBetta </mark> will be sharing details soon</p>
 <details>
<summary>TentativeDates</summary>
<p>07thJuly2023</p>
   </details> 
   </section>
 </aside>
<footer>
<p>&copy;2023author</p>
</footer>
 </article>
 </body> 
 </html>


 


 
