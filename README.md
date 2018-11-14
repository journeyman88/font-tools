# font-tools
A set of Shell scripts to manipulate fonts and create webfonts

The scripts are the following:
 * font2ttf: to convert a fontforge supported font file to ttf
 * font2otf: to convert a fontforge supported font file to otf
 * font2svg: to convert a fontforge supported font file to svg
 * font2woff: to convert a fontforge supported font file to woff
 * mkwebfont: a tool that can take several font files, converts them into various formats (EOT, TTF, OTF, WOFF, WOFF2, SVG), and creates a CSS file that aims to be compatible with all browsers and to be efficent (checking local files and matching lighter file formats first) binding them togheter into a unified font-family guessing font-weight and font-style parameters.

This script set needs the following tools:
 * fontforge
 * ttf2eot
 * woff2-tools
