=== HEAD

=== 1.0.1 (November 06, 2015)

* HTML tags inline, paragraphs and list item change the font size from 16px, 1rem to inherit

=== 1.0.0 (November 04, 2015)

### Features
* A Simple Reset inspired by
	* Paul Irish's [* { Box-sizing: Border-box } FTW](http://www.paulirish.com/2012/box-sizing-border-box-ftw/)
	* Zero Box Model** * { margin:0; padding:0; } **
	* Nicolas Gallagher's [normalize.css](http://necolas.github.io/normalize.css/)
* Structure based on Containers & Items
* 2 Types of Containers:
	1. Container with page's width, use **.container-full** 
	2. Container with 1200px's maximum width, use **.container**
* A Mobile First Grid System with 12 Columns & 4 Media Queries Sizes:
	1. Phones &lt; (30em or 480px) use **.ph1 to .ph12**
	2. Small Devices &lt; (48em or 768px) use **.sm1 to .sm12**
	3. Medium Devices &lt; (64em or 1024px) use **.md1 to .md12**
	4. Large Devices &gt; (64em or 1024px) use **.lg1 to .lg12**
* Layout's Multiple Techniques
	1. Floats
	2. Display inline-block
	3. Flexbox
* Additional Features:
	* Vertical & Horizontal Alignments
	* Font Sizes
	* Margins & Paddings
	* Borders & Displays