SVG on the Web
====

0. prep
  - tab with tiger bitmap
  - tab with tiger.svg#eye
  - tab with tiger.svg
  - editor with sticks1.svg - close fold on `<style>`


2. scalable vector graphics
  - image tech is cool - png, jpg...
  - but normal pictures don't scale well
    - either take too much space for the resolution,
    - or have insufficient resolution
  - problem with unexpected sizes for pictures
    - we want to print a picture
    - we want to use it as a little icon
  - problem with unexpectedly high/low res displays
    - 400+ dpi phones
    - 200+ dpi "retina" screens
    - 100 dpi normal screens
    - it's a bother to cater for everything
  - therefore vector graphics
    - not "this pixel has this color"
    - rather "draw this curve from here to here"
    - good for drawings/paintings, not photographs
      - look at your computer - mostly drawings, few photos
      - show atom icon on disk, 1.2M, 1024x1024 - 3in print
    - similar to old fonts vs new ones


- What is SVG?
  - picture of an awesome tiger, huge tiger.svg from http://commons.wikimedia.org/wiki/File:Ghostscript_Tiger.svg
    - tiger.svg#eye
  - zoom out
  - how big is the file? 69k
  - vector vs bitmap
  - compare with tiger.jpg from http://www.motherrisingbirth.com/2011/11/349.html via https://www.pinterest.com/pin/479492691550183760/
- Tools
  - inkscape https://inkscape.org/en/
  - draw a stickman
  - with linked limbs
  - and a shaded head
  - drawing tools are boring
- Image file
  - show tiger
  - include tiger in HTML in tiger.html
  - look in tiger.svg
  - change last #FFF on element with id g54 to #F00
- Basic SVG
  - spec http://www.w3.org/TR/SVG/
  - show sticks0.svg
  - look at style
  - show sticks1.svg, uncomment and tweak body and limbs
  - also, there are comments in the file!
  - include sticks1 in html: sticks1.html
  - but the style doesn't work
- Embedding in HTML5
  - sticks2.html
  - make sure to validate
  - notice style is outside
  - and has an interaction with hover
- Styling with CSS when embedded
  - show sticks3.svg
  - show interactive buttons
  - play a bit with style
  - include sticks3 in HTML: sticks3.html
- Embedding in CSS (to be done)
  - a little star
  - CSS puts it where it wants
- why svg:
  - scalability of vector graphics
  - size of image
  - css styling
  - generating of graphics, e.g. charts
- diagram
  - get population data for Portsmouth, York from wikipedia
  - only from 1801
- todo:
  - graceful degradation
  - using svg for diagrams


- next time:
  - show a title (SVG) and the expansion of it
  - show the spec
  - show the coordinate system
    - this can be tested - given this code, which picture do you think will come out?
  - start with stick figures with inline style: `<line stroke=...>` and then move on to using CSS, separating style from content
  - make sure to show :hover
  - maybe show impress.js svg on one side, zoom in for detail; png on the other side, zoom in for pixelation
  - maybe expand JPG, PNG, GIF, then SVG
