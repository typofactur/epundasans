## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[14] EpundaSans[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1003, but got 700 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- dotbelowcomb

- gravecomb

- tildecomb

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni0312

- uni0326

- uni0327

- uni0328

- uni032D

- uni0331

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A2 (CENT SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 start point differs in glyph 'bracketright' between location wght=300 and location wght=900

- Contour 0 start point differs in glyph 'exclam' between location wght=300 and location wght=900

- Contour 0 start point differs in glyph 'bracketleft' between location wght=300 and location wght=900
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, duployan, tifinagh, todhri, tai-le, malayalam, coptic, old-permic, canadian-aboriginal, syriac, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: syriac, sunuwar</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, cherokee, caucasian-albanian, thai, gothic, syriac, sunuwar</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: masaram-gondi, batak, dogra, gunjala-gondi, thai, newa, takri, cham, manichaean, yi, grantha, rejang, balinese, devanagari, mandaic, tagbanwa, avestan, psalter-pahlavi, gurmukhi, chakma, hanunoo, limbu, malayalam, myanmar, tai-le, phags-pa, syloti-nagri, tai-tham, mahajani, warang-citi, buhid, javanese, tai-viet, tamil, lepcha, hanifi-rohingya, hebrew, kayah-li, sharada, duployan, kaithi, khojki, buginese, tifinagh, zanabazar-square, brahmi, tirhuta, gujarati, sundanese, sogdian, lao, khmer, arabic, telugu, hatran, saurashtra, meetei-mayek, siddham, thaana, syriac, tagalog, tibetan, new-tai-lue, oriya, bengali, pahawh-hmong, sinhala, khudawadi, kharoshthi, nko, mongolian, kannada, modi, bhaiksuki</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: masaram-gondi, batak, dogra, old-hungarian, gunjala-gondi, thai, newa, takri, cham, manichaean, yi, grantha, rejang, balinese, devanagari, mandaic, tagbanwa, avestan, psalter-pahlavi, gurmukhi, chakma, hanunoo, limbu, malayalam, myanmar, tai-le, phags-pa, syloti-nagri, tai-tham, mahajani, warang-citi, buhid, javanese, tai-viet, tamil, lepcha, hanifi-rohingya, hebrew, kayah-li, sharada, duployan, kaithi, khojki, buginese, tifinagh, zanabazar-square, brahmi, tirhuta, gujarati, sundanese, sogdian, lao, khmer, arabic, telugu, saurashtra, siddham, meetei-mayek, thaana, syriac, tagalog, tibetan, new-tai-lue, oriya, bengali, pahawh-hmong, sinhala, khudawadi, kharoshthi, nko, mongolian, kannada, modi, bhaiksuki</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: phags-pa, nko, arabic, thaana, syriac, hebrew</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: phags-pa, nko, thaana, syriac, hebrew</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: math, yi, symbols, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: dogra, thai, newa, yi, manichaean, psalter-pahlavi, gurmukhi, chakma, marchen, tai-le, caucasian-albanian, mahajani, canadian-aboriginal, lepcha, miao, kaithi, sundanese, telugu, saurashtra, siddham, symbols, tibetan, new-tai-lue, oriya, osage, modi, gunjala-gondi, bassa-vah, takri, old-permic, rejang, mandaic, myanmar, ahom, tai-tham, warang-citi, tamil, tai-viet, adlam, music, kayah-li, armenian, sharada, khojki, tifinagh, zanabazar-square, sogdian, lao, khmer, syriac, tagalog, pahawh-hmong, sinhala, mende-kikakui, khudawadi, wancho, math, batak, grantha, devanagari, hanunoo, soyombo, syloti-nagri, buhid, elbasan, javanese, duployan, brahmi, tirhuta, meetei-mayek, thaana, bengali, kharoshthi, mongolian, kannada, bhaiksuki, masaram-gondi, cham, balinese, tagbanwa, limbu, malayalam, phags-pa, hanifi-rohingya, hebrew, buginese, gujarati, coptic, nko</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: nushu, chinese-traditional, phags-pa, yi, japanese, chinese-simplified, chinese-hongkong</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: chinese-simplified, japanese</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: math, yi, chinese-simplified, japanese</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: math, yi, chinese-simplified, japanese</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̣̒ į̦̀ į̦́</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Han (Latn, 6 speakers), Lithuanian (Latn, 2,357,094 speakers), Kaska (Latn, 125 speakers), Navajo (Latn, 166,319 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Nateni (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Heiltsuk (Latn, 300 speakers), Aghem (Latn, 38,843 speakers), Bafut (Latn, 158,146 speakers), Fur (Latn, 1,230,163 speakers), Igbo (Latn, 27,823,640 speakers), Nzakara (Latn, 50,000 speakers), Kom (Latn, 360,685 speakers), South Central Banda (Latn, 244,000 speakers), Gulay (Latn, 250,478 speakers), Vute (Latn, 21,000 speakers), Avokaya (Latn, 100,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Yala (Latn, 200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mfumte (Latn, 79,000 speakers), Mundani (Latn, 34,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Cicipu (Latn, 44,000 speakers), Sar (Latn, 500,000 speakers), Basaa (Latn, 332,940 speakers), Makaa (Latn, 221,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* exclamdown (U+00A1) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/variable/EpundaSans[wght].ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 4 | 11 | 95 | 8 | 133 | 0 | 
| 0% | 0% | 2% | 4% | 38% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
