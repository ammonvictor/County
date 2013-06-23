County
======

County is a symbol font that makes is easy to create a map of the Republic of Kenya using only HTML and CSS. Each county can be styled independently with CSS for making simple visualizations. County is inspired by Ben Markowitz symbol font Stately, [Stately Microsite](http://intridea.github.com/stately/)



##Files
    counties.svg	- SVG map used to create the font
    assets\font		- Folder containing the web-font files
    assets\css		- Folder containing compiled CSS files
    county.html		- Basic Demo
    county.ttf		- TrueType font file
    

##What is County?
Each county is a glyph within the font. Each county is positioned and sized relative to the the rest of the counties, so that when each character is stacked on top of one another, it creates a full map.
The pertinent characters are uppercase A-U and lowercase a-z with uppercase Z generating a full map of Kenya.

##Basic Use Case
You can use county however you like, but some base CSS and HTML is included.
Download and add the County folder to your project which includes the base CSS and the web font files. Grab the county folder and add it to your project. Then add the county.css to the head of your document.

```html
<link rel="stylesheet" href="assets/css/county.css">
```

Then add this markup to the page:

```html
	<ul class="county"> 
		<li data-state="ksm" class="ksm">A</li>
		<li data-state="mrg" class="mrg">B</li>
		<li data-state="lmu" class="lmu">C</li>						
		<li data-state="sya" class="sya">D</li>
		<li data-state="nrb" class="nrb">E</li>
		<li data-state="kch" class="kch">F</li>
		<li data-state="nmr" class="nmr">G</li>
		<li data-state="emb" class="emb">H</li>
		<li data-state="tnz" class="tnz">I</li>
		<li data-state="tni" class="tni">J</li>
		<li data-state="hba" class="hba">K</li>
		<li data-state="nyd" class="nyd">L</li>
		<li data-state="ksi" class="ksi">M</li>
		<li data-state="trr" class="trr">N</li>
		<li data-state="nkr" class="nkr">O</li>
		<li data-state="ugu" class="ugu">P</li>
		<li data-state="nyr" class="nyr">Q</li>
		<li data-state="mki" class="mki">R</li>
		<li data-state="mru" class="mru">S</li>
		<li data-state="kmu" class="kmu">T</li>
		<li data-state="mhk" class="mhk">U</li>
		<li data-state="mdr" class="mdr">a</li>
		<li data-state="wjr" class="wjr">b</li>
		<li data-state="msb" class="msb">c</li>
		<li data-state="tuk" class="tuk">d</li>
		<li data-state="nrk" class="nrk">e</li>
		<li data-state="kjd" class="kjd">f</li>
		<li data-state="sbr" class="sbr">g</li>
		<li data-state="kwe" class="kwe">h</li>
		<li data-state="isl" class="isl">i</li>
		<li data-state="tta" class="tta">j</li>			
		<li data-state="wpt" class="wpt">k</li>
		<li data-state="brg" class="brg">l</li>
		<li data-state="bga" class="bga">m</li>
		<li data-state="mgi" class="mgi">n</li>
		<li data-state="kkg" class="kkg">o</li>
		<li data-state="kti" class="kti">p</li>
		<li data-state="bsa" class="bsa">q</li>
		<li data-state="emt" class="emt">r</li>
		<li data-state="gis" class="gis">s</li>
		<li data-state="ndi" class="ndi">t</li>
		<li data-state="kiy" class="kiy">u</li>			
		<li data-state="bmt" class="bmt">v</li>
		<li data-state="lkp" class="lkp">w</li>
		<li data-state="vhg" class="vhg">x</li>
		<li data-state="mbs" class="mbs">y</li>
		<li data-state="klf" class="klf">z</li>	
	</ul>
```
    
Set the size and base map color in your CSS:

```css
.county {
    width: 300px;     /* width and font size must match */
    font-size: 300px; /*width and font size must match */
    color: #f0f0f0;
}
```
    
Style Individual State:

```css
.county .nrb,
.county .mbs,
.county .ksm { 
   color: #FF0000;
}
```
    
##Credits

Created by Ammon Victor.

Ammon Victor  
[twitter](http://www.twitter.com/ammonvictor)  
[website](http://www.be.net/vammon)  



