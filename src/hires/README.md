Hires Sources
================

Faba's hires icons are rendered from these source "plates". The using the **render-hires.rb** script, looks for a "Baseplate" layer in the SVG and renders a hires PNG icon from that.

To render the hires icons from their respective source SVG files, run the following from the main source folder:

    ./render-hires.rb

This script will look in the source directory (../src/hires/*) and render the respective icons (provided there are changes).

-----------