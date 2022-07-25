<!Doctype>
<html><title> Rajasarath DEmo Html </title>
<head> title
</head>
<body>
<h1>welcome to demo</h1>
<h2>html</h2>
<h3>all tags</h3>
<h4>using</h4>
<h5>here</h5>
<h6>without dots</h6>
<hr>
<p>welcome to html demo class and written in paragraph using tag
 'p', for breaking paragraph use 'br' tag <br> then it automatically comes to next line</p>
<hr><hr><hr>
<marquee bgcolor="yellow"> Rajasarath </marquee>
<hr>
<h1><font color="red"> The abbr element </font></h1>
<h5> <abbr title="Sriram">God</abbr>here</h5>
<img src="https://www.hindugodwallpaper.com/images/gods/zoom/359_016.jpg" width="100px" height="100px">
<hr>

<h1><p><font color="green">for address use tag address</font></p></h1>
<address> 
illuru rajasarth<br>
s/o.Ramakrishna<br>
6-59,kottala, gadeguduru,<br>
rajuapalem , proddatur,<br>
ysrkadapa-516359.<br>
mobile- 9985887686.<br>
visit here-- <a href="https://www.google.com/maps/place/Charminar/@17.375173,78.4859013,12.6z/data=!4m5!3m4!1s0x3bcb978a6e1a939b:0xcb5a69e4aaf113fb!8m2!3d17.3615546!4d78.4746552"> Charminar</a> 
</address>

<hr>
<h3><font color="blue"> for bold use 'b' tag</font></h3>
<p>interested in -- <b> mobilephones </b></p>
<hr><hr>
<h3><font color="orange"> for BDI elements </font></h3>
<ol>
<li>one-<bdi>two</bdi>:001score</li>
<li>three-<bdi>four</bdi>:002score</li>
<li>five-<bdi>six</bdi>:003score</li>
<li>seven-<bdi>eight</bdi>:004score</li>
</ol>
<hr>
<h2><font color="yellow"> for BDO elements use "(bdo dir="rlt")"</font></h2>
<p> This is wrong</p>
<p><bdo dir="rtl">This is wrong</bdo></p>
<hr>
<h2><font color="red">Blockquote element</font></h2>
<blockquote>
Looking for a way to lift someone’s spirits? Positive quotes or words of encouragement can inspire anyone. Whether it’s your lifelong best friend or a stranger you pass on the street, taking a moment to deliver a positive and inspirational message can have a long-lasting effect on the well-being of both individuals. Lift someone’s spirits by checking out these special positive quotes of the day.
</blockquote>
<hr><hr>

<h2> Cite elements</h2>
<img src="https://www.hindugodwallpaper.com/images/gods/zoom/359_016.jpg" width="150" height="150" alt="the god">
<p><cite>the god </cite>sri ram is Ram</p>
<hr><hr>

<h5>code element</h5>
<p>this is <code> Rajasarath illuru</code> also calls</p>
<hr>
<h2>DEL Elements</h2>
<p>faviorate god <del>balaji </del><ins> sri ram</ins></p>
<hr>
<h2>STyle Elements</h2>
<p><dfn>name </dfn>rajasarath</p>
<p><em>name </em>illuru</p>
<p><i>name </i>kottala</p>
<hr>
<h2> Kbd element </h2>
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (sarath).</p>

<p>Press <kbd>Ctrl</kbd> + <kbd>V</kbd> to Paste text (illuru).</p>
<hr><hr>

<h2>mark element</h2>
<p> This is <mark>Illuru </mark></p>

<hr>
<h2><font color="blue">meter element</font></h2>
<p>The meter element is used to display a gauge:</p>

<lable for="disk_c">Data usage E:</lable>
<meter id="disk_c" value="20" min="0" max="25">20 out of 25</meter><br>

<lable for="raja">illuru:</lable>
<meter id="illuru" value="1">40%</meter><br>
<hr>
<h2>pre element</h2>
<pre>
illuru
sarath
raja
king
</pre>
<hr><hr>
<h2> progress element</h2>
<lable for="file"> sri ram:</lable>
<progress id="file" value="70" max="100">70%</progress>
<hr>
<h2> q element</h2>
<p>my favorite god:
<q>god is god</q> illuru</p>
<hr>
<h2> S element</h2>
<p><s>Sarath</s></p>
<p>Raja!</p>

<hr>
<h2> Type style </h2>
<p><small>sarath</small></p>
<p><strong>saarth</strong></p>
<p><sub>my actaul name sarath</sub></p>
<p><sup>my  name sarath</sup></p>
<hr><hr>

<h1>Template element</h1>

<p>Click the button below to display the hidden content from the template element.</p>

<button onclick="showContent()">show hidden data</button>

<template>
  <h2>ram</h2>
  <img src="https://www.hindugodwallpaper.com/images/gods/zoom/359_016.jpg" width="214" height="204">
</template>

<script>
function showContent() {
  var temp = document.getElementsByTagName("template")[0];
  var clon = temp.content.cloneNode(true);
  document.body.appendChild(clon);
}
</script>

<hr>
<h2>Time element</h2>
<p>Open from <time>10:00</time> to <time>21:00</time> every weekday.</p>

<p>I have a date on <time datetime="2008-02-14 20:00">Valentines day</time>.</p>

<hr>
<h2> U element</h2>
<p> my name is <u> sri ram</u></p>
<hr>
<h2> Var element </h2>
<p>The area of a triangle is: 3/5 x <var>b</var> x <var>h</var>, 
where <var>b</var> is the base, and <var>h</var>
 is the vertical height.</p>
<hr>

<h2>WBR element</h2>
<p>this is a
poem of html and css javascript<wbr>angulartypeofrepo</wbr>herecomewith reposite
</p><hr><hr>
<marquee> Illuru </marquee>
<hr><hr>

</body>

</html>