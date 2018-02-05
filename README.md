SVG on the Web
====

This is a set of examples for a lecture on SVG on the Web:


Musical score
----

the-game-is-on.svgz
  - a musical score as a drawing
  - compressed losslessly as text
the-game-is-on.png
  - 300dpi bitmap version of the above
the-game-is-on.jpg
  - same bitmap JPG-compressed with quality level to match the PNG file size
  - shows lossy compression artifacts


Tigers
----

tiger.jpg
  - a normal bitmap
  - from http://www.motherrisingbirth.com/2011/11/349.html via https://www.pinterest.com/pin/479492691550183760/
tiger.svg
  - from http://commons.wikimedia.org/wiki/File:Ghostscript_Tiger.svg
  - zooms on click if opened as tiger.svg#zooming
tiger.html
  - includes tiger.svg in <img>
tigers.html
  - links to tiger.svg at various levels of zoom


Stick figures
----

sticks1.html
  - contains a stick figure as in slides
  - validate HTML5!
  - notice style is outside

sticks-bad.svg
  - external-file version of stick figures from above
  - doesn't work because XML is more strict
  - needs at least quoted attributes and the namespace

sticks2.html
  - demonstrates styling by class: the face has an interaction with hover
  - also shows order of drawing (body overwrites the chin)

sticks3.html
  - adds a hyperlink and text

sticks4.html
sticks4.svg
  - like sticks3, but in an external file
  - we can't style the SVG from html
  - we can't interact with it (no hover, no hyperlinks)

sticks-dbprin.html
  - contains a lot of stick figures working at desks, and waiting in lines
  - by default shows only one
  - interactive buttons reveal various combinations
  - controlling style from javascript, nothing SVG-specific


Stars
----

star.svg
  - a little star (zoomed 10x)
stars.html
  - embeds the star in CSS to decorate HTML elements


Charts
----

chart.svg
  - population data for Portsmouth, York from Wikipedia
  - shows how easy it is to generate SVG (by hand or programmatically)
