CHANGE LOG
==========

** June 2014 **
- [digitaltoast] removed X-UA-Compatible meta tag from header (as it's not needed anymore these days)
- [digitaltoast] removed protocol in jQuery URL (modern way to load external files, making it independent to protocol change)
- [digitaltoast] downgraded jQuery from 2.1 to 1.11 to avoid problems when working with IE7/8 (jQuery 2 dropped IE7/8 support)

** April 2014 **
- updated jQuery link to 2.1
- more than 3 parameters (arguments to be concrete) are possible
- cleaner way of parameter handling
- smaller cleanings and improvements
- Apache 2.4 install information

**January 4th 2014**
- fixed .htaccess issue when there's a controller named "index" and a base index.php (which collide)

**December 29th 2013**
- [grrnikos] fixed case-sensitive model file loading
