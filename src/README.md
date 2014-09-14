Hires Sources
================

Faba's hires icons are rendered from these source "plates". The using the **render-hires.rb** script, looks for a "Baseplate" layer in the SVG and renders a hires PNG icon from that.

To render the hires icons from their respective source SVG files, run the following from the main source folder:

    ./render-hires.rb

This script will look in the source directory (../src/hires/*) and render the respective icons (provided there are changes).

Symbolic Sources
================

For symbolic icons, these sources are "plates" that are split into the individual icons using the **render-symbolic.rb** script.

To render the symbolic icons from their respective source SVG files, run the following from the main source folder:

    ./render-symbolic.rb

This script will look in the source directory (../src/symbolic/*) and render the respective icons (provided there are changes).

Vector Sources
==============

These icon sources are simply the unscoured, bloated versions of the final icons. They have extra data (layers, etc.) for ease of development. 

They are simply copied out of the source folder (../src/vector/*) into the main theme folder and scoured for production.

-----------