Faba Sources
============

### Using the Source

There are scripts to simplify the rendering process; to run them (and edit icons) you will need:

 * inkscape
 * ruby

- - -

### Symbolic Sources

For symbolic icons, these sources are "plates" that are split into the individual icons using the **render-symbolic.rb** script.

To render the symbolic icons from their respective source SVG files, run the following from the main source folder:

    ./render-symbolic.rb

This script will look in the source directory (../src/symbolic/*) and render the respective icons (provided there are changes).