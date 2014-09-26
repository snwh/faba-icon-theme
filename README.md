Faba Icon Theme
===============

Faba is a sexy and modern icon theme with Tango influences. All variations and supplementary themes for Faba, require this base theme.

Faba Icon Theme is distributed under the terms of the GNU LGPL-3.0+ or CC-BY-SA-4.0

###Preamble

If you find any bugs or issues with Faba or if you have a question, you can visit Faba's issue tracker on [GitHub](https://github.com/moka-project/faba-icon-theme/issues).

If you're feeling awesome, you may suggest or [request](http://mokaproject.com/requests) icons I've missed or make a [donation](http://www.mokaproject.com/donate/ "Donate") to the project to fuel its development. :smile:

###Getting Faba

Faba and all its supplementary themes can be downloaded [here](http://mokaproject.com/faba-icon-theme/download).

###Installing Faba
To install Faba, you can copy the main theme folder (Faba) into ```~/.local/share/icons``` or copy it into ```/usr/share/icons``` to make it available system-wide. Or run the provided installation script:

    bash install.sh

###Supplementary Themes 

 * [Faba Mono Icons](https://github.com/moka-project/faba-mono-icons)
 * [Extra Faba Icons](https://github.com/moka-project/faba-icon-theme-extras)

###Getting the Source

The source for Faba Icon Theme can be downloaded as an archive [here](https://github.com/moka-project/faba-icon-theme/archive/master.zip) or, you can clone the latest version from the git repository:

    git clone https://github.com/moka-project/faba-icon-theme.git

###Using the Source

There are scripts to simplify the rendering process; to run them (and edit icons) you will need:

 * inkscape
 * ruby

To render new icons from their source SVG files, run the following:

    ./render-bitmaps.rb
    ./render-symbolic.rb

This script will look in the source directories (../src/*) and render the respective icons (provided there are changes).

See the [source README](src/) for more info.

-----------