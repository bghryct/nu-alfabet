# Nu Alfabet

This is a family of fonts that clone Wim Crouwel’s [New Alphabet](https://en.wikipedia.org/wiki/New_Alphabet) parametric typesetting system. It is the culmination of an [exercise](https://github.com/rdazvd/new-alphabet-generator) for learning how to use Python and the [Glyphs](https://glyphsapp.com/) font editor API. The family consists of several variations in the glyphs proportions automatically generated from a high level description of the design in Python code (or a “metafont” in the broad sense that Donald Knuth defined in the [Metafontbook](https://www.amazon.com/Metafont-Book-Donald-Knuth/dp/0201134446), that is, “a schematic description of the shapes in a family of related fonts”).

Each font has in its name a sequence of five numbers that describe its proportions, in order:
1. number of vertical units (odd progression, defines glyph width)
2. number of [UPMs](http://luc.devroye.org/ump.html) per vertical unit (that is, the unit width)
3. number of horizontal units (odd progression, defines glyph height, at least x-height + 4)
4. number of UPMs per horizontal unit (that is, the unit height)
5. number of horizontal units that comprise the x-height (odd progression)

This abides by the manner in which Crouwel conceived the system variations.

All fonts published in this repository are licensed under the [SIL Open Font License](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL).
