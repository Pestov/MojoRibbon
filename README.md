MojoRibbon
==========
DEMO: http://netcribe.com/MojoRibbon

Geometrically correct LESS ribbon

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
