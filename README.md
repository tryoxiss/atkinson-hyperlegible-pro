# [Atkinson Hyperlegible Pro](https://jacobxperez.github.io/atkinson-hyperlegible-pro/)

With Alternative Flipped Zero, Improved Kerning and Ligatures

---

![Brochure Overview](docs/BIA_Brochure-Overview.jpg)

## Overview

Atkinson Hyperlegible Pro is an update to the original typeface designed for The Braille Institute and named after its founder J. Robert Atkinson. What makes it different from traditional typography design is that it focuses on letterform distinction to increase character recognition, ultimately improving legibility and readability for low-vision readers. The typeface was a Winner of Fast Company’s 2019 Innovation By Design Award.

* Four fonts, including two weights (regular, bold, italics, italics bold)
* 1,604 total glyphs across all fonts, 401 per font
* Accent characters supporting 82 languages
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

## Added Characters and Glyphs

* T with dot above `Ṫ` `U+1E6A` and `ṫ` `U+1E6B`
* S with dot above `Ṡ` `U+1E60` and `ṡ` `U+1E61`
* P with dot above `Ṗ` `U+1E56` and `ṗ` `U+1E57`
* M with dot above `Ṁ` `U+1E40` and `ṁ` `U+1E41`
* Y with circumflex `Ŷ` `U+0176` and `ŷ` `U+0177`
* Y with grave `Ỳ` `U+1EF2` and `ỳ` `U+1EF3`
* W with circumflex `Ŵ` `U+0174` and `ŵ` `U+0175`
* W with diaeresis `Ẅ` `U+1E84` and `ẅ` `U+1E85`
* W with grave `Ẁ` `U+1E80` and `ẁ` `U+1E81`
* W with acute `Ẃ` `U+1E82` and `ẃ` `U+1E83`
* F with dot above `Ḟ` `U+1E1E` and `ḟ` `U+1E1F`
* D with dot above `Ḋ` `U+1E0A` and `ḋ` `U+1E0B`
* B with dot above `Ḃ` `U+1E02` and `ḃ` `U+1E03`
* Dong `₫` `U+20AB`
* Ligatures for `fi ff ffi fl ffl`
* Copyleft `U+1F12F`
* Alternative reversed number zero `0`

## Change Log

* kern `l` and `ṗ` pairs
* Kern `SY` `SV` `ST` pairs
* Kern `K` and `c d e o g q` pairs
* Kern `Y` and `c d e o g q m n p r` pairs
* Kern `W` and `c d e o g q m n p r` pairs
* Kern `V` and `c d e o g q m n p r` pairs
* Kern `T` and `c d e o g q m n p r v w x y z` pairs
* Kern `ľ ť ď` class group
* Added `m p r` to kern with `n` group
* Kern quotes class pairs
* Added auto hint

## Contribute

Help us extend Atkinson Hyperlegible Pro to other languages, I am currently working on adding more glyphs to cover the unicode block of “[latin extended additional](https://www.compart.com/en/unicode/block/U+1E00)” this will also include new diacritic and marks.

## Language Support (82)

Afrikaans Albanian Asu Basque Bemba Bena Breton Catalan Chiga Colognian Cornish Croatian Czech Danish Dutch English Estonian Faroese Filipino Finnish French Friulian Galician German Gusii Hungarian Icelandic Indonesian Irish Italian Kabuverdianu Kalenjin Kinyarwanda Latvian Lithuanian Lower Sorbian Luo Luxembourgish Luyia Machame Makhuwa-Meetto Makonde Malagasy Maltese Manx Morisyen North Ndebele Norwegian Bokmål Norwegian Nynorsk Nyankole Oromo Polish Portuguese Quechua Romanian Romansh Rombo Rundi Rwa Samburu Sango Sangu Scottish Gaelic Sena Serbian Shambala Shona Soga Somali Spanish Swahili Swedish Swiss German Taita Teso Upper Sorbian Uzbek (Latin) Volapük Vunjo Welsh Western Frisian Zulu.

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
