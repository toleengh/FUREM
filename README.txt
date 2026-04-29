FURĒM LONDON — WEBSITE
========================

To view the site:
  Double-click  index.html  (it opens in your browser)

What's included:
  - index.html                       The full site (single file, no build step)
  - assets/video/logo-reveal.mp4     Your logo reveal video (used as the hero)
  - assets/img/                      Drop your photos here (filenames below)

The site already works. If image files are missing, the site shows
elegant cinematic placeholders in the brand palette so nothing looks broken.
As you drop in photos with the names below, they replace the placeholders.

PHOTO FILENAMES (drop into  assets/img/  — JPG or PNG):

  Lookbook (rail of model shots — 8 frames, portrait 3:4)
    look-01.jpg   The Westminster   silver fox · cropped
    look-02.jpg   The Pall Mall     russian sable · long
    look-03.jpg   The Mayfair       chinchilla · cape
    look-04.jpg   The Bruton        scandinavian mink
    look-05.jpg   The Embankment    black fox · bomber
    look-06.jpg   The Belgravia     cashmere & mink
    look-07.jpg   The Knightsbridge sable · tuxedo
    look-08.jpg   The St. James     mink · greatcoat

  Texture macros (close-ups of fur — 3 images)
    texture-01.jpg   sable macro      4:5 portrait
    texture-02.jpg   cream mink       1:1 square
    texture-03.jpg   auburn fox       5:4 landscape

  Editorial campaign frames (3 large story images)
    edit-01.jpg   Westminster, January   4:5 portrait
    edit-02.jpg   Regent Street, dusk    4:5 portrait
    edit-03.jpg   Studio, Bruton Place   4:5 portrait

You can also add the six "vault" pieces if you want — they currently
use cinematic gradient placeholders so they look intentional even empty.
To add real shots, paste these into index.html where each piece's
.ph element lives, replacing  <div class="ph"></div>  with
  <img src="assets/img/piece-01.jpg" alt="">
…and so on for piece-02 … piece-06.

DESIGN NOTES
------------
  Palette  : #cfcfcf  #d9d9d9  #404040  #727272 + true black + warm paper #f5f1ea
  Display  : Italiana (logo-style) and Cormorant Garamond (italic accents)
  Body     : Inter

INTERACTIONS / SCROLL MOVES
---------------------------
  · Logo-reveal video as the hero, with a layered title and "Scroll" cue
  · Edge-to-edge marquee strip under the hero
  · Sticky-pinned manifesto with word-by-word reveal as you scroll
  · Horizontal lookbook rail (mouse wheel scrolls horizontally on desktop)
  · Sticky craft column with flowing macro images on the right
  · Editorial split-screen rows (alternating image/copy sides)
  · Featured-pieces grid with hover zoom and label reveal
  · Big quote moment, contact + newsletter, footer
  · Custom dot/ring cursor on desktop
  · Scroll-progress bar at the very top
  · Mix-blend-mode navigation that inverts over light/dark sections
