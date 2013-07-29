MojoRibbon
==========
DEMO: http://netcribe.com/MojoRibbon

<img src="http://habr.habrastorage.org/post_images/a7d/413/646/a7d4136469ac7974426d13f02c5624c0.png"> 
 	
This Ribbon is an image inside a link with <code>position: absolute</code>. Why I don't like this option? First: I love the modern standards of CSS, with which you can create nice design, using a minimum of images, as in this case, the ribbon can be a HTML block with the <code>transform: rotate</code>. Secondly: recently, I look on the web through the Retina display and sub-optimal img immediately catch the eye, but the developers to pay attention to what the ribbon, optimize their display with media queries, it seems to me, even a little bit funny.

<h4>I am a perfectionist and I'm lazy :) So I create geometrically correct LESS ribbon snippet:</h4>

A = sin(a) * C or A = sin(65) * 500; <br>
B = sin(b) * C or B = sin(25) * 500; <br>
<br>
A2 = sin(a2) * C2 or A2 = sin(65) * 50; <br>
B2 = sin(b2) * C2 or B2 = sing(25) * 50; <br>
<img src="http://img-fotki.yandex.ru/get/9154/188626415.0/0_c0d90_2a74afc9_orig">

<h3>Usage:</h3>

<pre><code>
.ribbon {
  .MojoRibbon(@width: 500px, @height: 50px, @deg: -45deg, @valign: top);
	display: inline-block;
	background-color: #cc0000;
	position: absolute;
	z-index: 5;
	box-shadow: 0 0 10px #000;
}

&lt;a href="https://github.com/Pestov/MojoRibbon" class="ribbon"&gt; Fork me on Github&lt;/a&gt;
</code></pre>
