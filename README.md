----


# Epunda Sans

[![][Fontbakery]](https://typofactur.github.io/epundasans/fontbakery/fontbakery-report.html)
[![][Universal]](https://typofactur.github.io/epundasans/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://typofactur.github.io/epundasans/fontbakery/fontbakery-report.html)
[![][Shaping]](https://typofactur.github.io/epundasans/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundasans%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundasans%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundasans%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundasans%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundasans%2Fgh-pages%2Fbadges%2FUniversal.json

Epunda Sans is a simple, space-saving font with a friendly appearance and good legibility. It's characteristic features are the slanted incisions, a high x-height, round and open letter shapes and large interior spaces.

Epunda Sans was originally designed by Simon Atzbach in 2007, based on the completely symmetric Epunda. In 2022 it was redesigned as a variable font.

The variable font has a weight axis that ranges from Light (300) to Black (900).


![Sample Image](documentation/epundasans_cover.png)
![Sample Image](documentation/epundasans_alphabet.png)
![Sample Image](documentation/epundasansitalic_alphabet.png)
![Sample Image](documentation/epundasans_weights.png)

## About

typofactur is a German type foundry run by the graphic designer Simon Atzbach.
Find out more at https://typofactur.de

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://typofactur.github.io/epundasans.git.

## Changelog

**30 Nov 2024. Version 2.001**
- initial release

**25 December 2024. Version 2.103**
- including Italic
- analog to Epunda Slab

**31 December 2024. Version 2.200**
- kerning with kern on

**03 January 2025. Version 2.201**
- a and e without alternative
- a.salt and e.salt

**03 January 2025. Version 2.202**
- ogonek, eogonek
- path direction guillemot right
- vendor identification
- no ligatures
- contour order guillemotright

**28 February 2025. Version 2.203**
- commaturnedabovecomb
- ogonekcomb, Aogonek, Eogonek, aogonek, eogonek, uogonek, oogonek
- a italic
- periodcentered.loclCAT and periodcentered.loclCAT.case added
- lcaron kerning
- dcaroncomb.alt, kerning Lcaron, dcaron, lcaron, tcaron 
- acutecomb, gravecomb
- dcroat
- eth italic

**02 March 2025. Version 2.204**
- Dcroat = Eth

**29 June 2025. Version 2.205**
- lozenge added
- .notdef added


## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at https://openfontlicense.org

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
