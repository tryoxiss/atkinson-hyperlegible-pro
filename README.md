# [Atkinson Hyperlegible Pro](https://jacobxperez.github.io/atkinson-hyperlegible-pro/)

With Alternative Flipped Zero, Improved Kerning and Ligatures

---

![Brochure Overview](docs/BIA_Brochure-Overview.jpg)

## Overview

Atkinson Hyperlegible Pro is an update to the original typeface designed for The Braille Institute and named after its founder J. Robert Atkinson. What makes it different from traditional typography design is that it focuses on letterform distinction to increase character recognition, ultimately improving legibility and readability for low-vision readers. The typeface was a Winner of Fast Company’s 2019 Innovation By Design Award.

* Four fonts, including two weights (regular, bold, italics, italics bold)
* 1,340 total glyphs across all fonts, 335 per font
* Accent characters supporting 27 languages
* Improve legibility and readability for low vision readers
* Improve kerning across all characters
* Includes ligatures for `fi ff ffi fl ffl`
* Alternative reversed number zero `0`
* Grate for body text, headings and UI

## Installing the Font

* **[Download](https://github.com/jacobxperez/atkinson-hyperlegible-pro/archive/refs/heads/main.zip)** the font from this Github repository.
* Extract the file to reveal additional folders inside. Find the Open Type Format (.otf) files for the four Atkinson Hyperlegible Pro fonts (regular, italic, bold, bold italic) inside the “fonts/otf” folder.
* Note that only the otf files are needed to install the font on a computer.
* On Windows 10: Double-click the font file, then click the “Install” button in the font preview window that opens. The font will be installed. Alternatively, right-click on the file and choose “Install” from the pop-up menu.
* On Mac: Double-click the font file in the Finder, then click “Install Font” in the font preview window that opens. After your Mac validates the font and opens the Font Book app, the font is installed and available for use.

## Flipping the Zero

By default the zero remains as it is however you can flip the zero by adding
`font-variant-numeric: slashed-zero;` to your CSS file.

    body {
      font-size: 100%;
      font-family: "Atkinson Hyperlegible Pro", sans-serif;
      font-weight: 400;
      font-variant-numeric: slashed-zero;
    }

And thats it the zero has been flipped!!

## Change Log

* Added `l` `w` `x` to kern class
* Kern quotes class pairs
* Moved `Æ` to kern class
* Kern `Y` and `m n p r` pairs
* Kern `V` and `g` pairs
* Added `B` `V` `W` `X` to kern class
* Added `m p r` to kern with `n` group
* Moved `T` and `f` parings to kern class
* Kern `T` and `v w x y z` pairs
* Added `K Ķ k ķ` to kern class
* Slightly reduced the left and right bearings by -2 (only regular and italic)
* Added auto hint
* Added ligatures to kern class
* Added ligatures for `fi ff ffi fl ffl`
* Added copyleft glyph `U+1F12F`
* Added alternative reversed number zero `0`

## Unique design features

For Low vision readers, certain letters and numbers can be hard to distinguish from one another.
Atkinson Hyperlegible differentiates common misinterpreted letters and numbers using various design techniques: B vs 8, 1 vs L vs l vs I. Recognizable Footprints: Character boundaries clearly defined, ensuring understanding across the visual-ability spectrum.

Differentiated letterforms: Similar letter pairs are differentiated from each other to dramatically increase legibility.

> `Q vs G, E vs F, p vs q, i vs r, O vs 0`

Unambiguous Characters: designed to increase legibility and distinction

> `ER79jr Vsa36`

Exaggerated forms: Shaping of letters is exaggerated to provide better clarity

Opened Counterspace: Open areas of certain letters are expanded to provide greater distinction

> `aGbgrpqu Åö8ij%?¡,:`

Angled spurs and differentiated tails: Increase recognition and define distinctive style

Circular Details: Links to the history of Braille Institute and braille dots

## License

SIL Open Font License, v1.1. See [OFL.txt](OFL.txt) for details.

---

Learn more at [brailleinstitute.org/freefont](https://brailleinstitute.org/freefont).
