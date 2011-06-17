# The Paravel ConvergeSE Workshop

The fonts and assets here are for demonstration purposes. 

## Start

The sample project has our base frame for the little one-pager. BONUS: it's an hCalendar microformat!

* Download the `v1` sample project from [Github](http://github.com/paravel/convergeSE)

## Lvl 1
In this step we'll add some web font typography and some lettering.js. We'll also layout the basic vibe of our site.

### Install our font face kits into the `<head>`
* [Ostrich Sans by The League of Movable Type](http://www.theleagueofmoveabletype.com/fonts/18-ostrich-sans)
* [Learning Curve Pro by Blue Vinyl](http://www.bvfonts.com/fonts/details.php?id=76)


	<link rel="stylesheet" href="fonts/ostrich-sans/stylesheet.css" type="text/css" />
	<link rel="stylesheet" href="fonts/learning-curve-pro/stylesheet.css" type="text/css" />

Download `@font-face` kits from Font Squirrel
* http://www.fontsquirrel.com/fonts/Learning-Curve-Pro
* http://www.fontsquirrel.com/fonts/ostrich-sans

### Install jQuery and Lettering.js into the `<head>`.

	<script src="js/jquery-1.6.1.min.js"></script>
	<script src="js/jquery.lettering.min.js"></script>
	<script type="text/javascript">
		$(document).ready(function(){
			$("header h1, .features").lettering('words');
		});
	</script>
	
Now it's up to you to CSS this mess.