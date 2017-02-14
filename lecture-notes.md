SVG on the Web
====

0. prep
  - tab with presentation https://docs.google.com/presentation/d/1EmAJWl0sZBjFZPICr0r6wCzf5aBy7NUScxa--86HrUo
  - tab with tiger bitmap
  - tab with tiger.svg#eye
  - tab with tiger.html
  - readable high-contrast editor theme
  - editor with sticks0.svg
  - editor with sticks1.svg - close fold on `<style>`
  - window with music png
  - window with music jpg
  - tab with music svgz
  - inkscape


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
  - show tiger.jpg (from http://www.motherrisingbirth.com/2011/11/349.html via https://www.pinterest.com/pin/479492691550183760/)
  - zoom in on an eye, pixels show
  - how big is the file? 97k
  - switch to drawing tiger.svg#eye (from http://commons.wikimedia.org/wiki/File:Ghostscript_Tiger.svg)
  - note the huge resolution for just the eye
  - click to zoom out
  - how big is the file? 69k
  - vector vs bitmap
- Tools
  - inkscape https://inkscape.org/en/
  - draw a stickman
  - with linked limbs
  - and a shaded head
  - drawing tools are boring
- Image file
  - switch to tiger.html tab
  - show source that includes tiger in <img>
  - look in tiger.svg, recognize some bits from HTML
  - change last #FFF on element with id g54 to #F00
- Basic SVG
  - spec http://www.w3.org/TR/SVG/
  - show sticks0.svg and play with it
  - look at style
  - show sticks1.svg, uncomment and tweak body and limbs
  - also, there are comments in the file!
  - include sticks1 in html: sticks1.html
  - but can't style it from html
- Embedding in HTML5
  - sticks2.html
  - make sure to validate, also change "line" to "lines" and show validator catches that
  - notice style is outside
  - and has an interaction with hover
- Styling with CSS when embedded
  - show sticks3.svg
  - play a bit with style in the file
  - include sticks3 in HTML: sticks3.html
  - show interactive buttons
  - control style from javascript
- Embedding SVG in CSS
  - show star.svg
  - a little star
  - CSS puts it where it wants
  - show stars.html
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
