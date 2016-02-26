=== Actions ===

Contributors: WPDevHQ
Tags: translation-ready, theme-options, custom-menu, post-formats, threaded-comments

Requires at least: 4.0
Tested up to: 4.5.beta1
Stable tag: 1.0.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A parent theme called Actions.
Copyright (C) 2016 WPDevHQ http://www.wpdevhq.com/

== Description ==

Hi. I'm a parent theme called Actions. I'm a theme meant to be used as a Parent for rapid development - so don't hack me please. 
Instead extend me by hooking in to my actions via a child theme and/or a functionality plugin.

== Installation ==
	
1. In your admin panel, go to Appearance > Themes and click the Add New button.
2. Click Upload and Choose File, then select the theme's .zip file. Click Install Now.
3. Click Activate to use your new theme right away.

== Frequently Asked Questions ==

= Does this theme support any plugins? =

Not at the moment.

== Changelog ==

= 1.0.3 =
* New: Added support for the upcoming WordPress v4.5 support for site logo - Files: styles.css, inc/functions/setup.php @lines 78-83 &  and inc/structure/header.php @line 21 
* Further refinement of the footer copyright/credit link output - File: inc/structure/footer.php @ lines 20 & 24
* Escaping menu and sidebar registration - File: inc/functions/setup.php @Lines 59 and 100
* Cleaned up unused code - File(s): inc/structure/header.php
* Updated screenshot - File(s): screenshot.png
* Tested theme againt the upcoming WordPress v4.5 release - tested on v4.5.beta1

= 1.0.2 =
* Switch to "<?php bloginfo( 'name' ); ?>" instead of a predefined $title for site title - File: inc/structure/header.php @line 30
* Refined Footer credits to automagically populate theme name, theme url and author depending on active theme (Parent or Child) - File: inc/structure/footer.php @lines All
* Added action hooks for the footer wrapper as part of above refinement - Files: inc/structure/hooks.php @lines 56 to 62 and inc/structure/markup-functions.php @lines 113 to 141
* Removed Genericons so that child theme authors are free to choose their preferred icon set.
* Minor CSS adjustments and general clean up of unused elements.

= 1.0.1 - February 13 2016 =
* Added site description as a title to the site name - File: header.php @lines 24 and 30
* Added "the_post_navigation" from TwentySixteen - File: inc/structure/header.php code @lines 90 to 104
* Minor CSS adjustments - added :focus to all :hover states - File: styles.css

= 1.0.0 - February 01 2016 =
* Initial release

== Credits ==

* Based on Underscores http://underscores.me/, (C) 2012-2015 Automattic, Inc., [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html)
* normalize.css http://necolas.github.io/normalize.css/, (C) 2012-2015 Nicolas Gallagher and Jonathan Neal, [MIT](http://opensource.org/licenses/MIT)
* CSS/JS snippets from:
	Twenty Sixteen - Copyright (C) the WordPress team https://wordpress.org/themes/twentysixteen/
	Presentation Lite - Copyright (C) 2014 Sean Davis - SDavis Media LLC http://seandavis.co/ (Menu system)