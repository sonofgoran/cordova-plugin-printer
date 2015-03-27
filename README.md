Cordova Print Plugin - Son of Goran
====================

This plugin is just a fork of the <a href="https://github.com/katzer/cordova-plugin-printer">katzer/cordova-plugin-print</a>.

I needed some extra functionality out of the android side of things, ie. to print a pdf

To start with, I am just using the Intent class from android to get the application to send the pdf to a pdf viewing application on the device which will take care of the printing.  I think this is reasonably slick and in my applications I always prefer a preview before printing anyway, so this works ok for now until I find a better way.
