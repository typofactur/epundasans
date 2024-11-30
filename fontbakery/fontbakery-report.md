## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] EpundaSans[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 837, but got 700 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[23] EpundaSans[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> STAT table has Axis Value tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.stat.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '500.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '800.0'</p>
 [code: missing-axis-value-table]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Lcaron uses component uni030C.</p>
 [code: wrong-mark]



* 🔥 **FAIL** <p>lcaron uses component uni030C.</p>
 [code: wrong-mark]



* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+01DF: LATIN SMALL LETTER A WITH DIAERESIS AND MACRON</td>
<td align="left">U+01DE: LATIN CAPITAL LETTER A WITH DIAERESIS AND MACRON</td>
</tr>
<tr>
<td align="left">U+1EA1: LATIN SMALL LETTER A WITH DOT BELOW</td>
<td align="left">U+1EA0: LATIN CAPITAL LETTER A WITH DOT BELOW</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 265, but got 200 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (700) and hhea ascent (1000) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 250 font units wide, non-breaking space named (uni00A0) is 200 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



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
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;300&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



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
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- uni030C.alt
</code></pre>
 [code: unreachable-glyphs]



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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, hebrew, math, tai-le, duployan, malayalam, syriac, todhri, tifinagh, old-permic, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, thai, caucasian-albanian, sunuwar, gothic, syriac, tifinagh</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: bhaiksuki, tai-tham, gunjala-gondi, devanagari, newa, nko, chakma, gujarati, masaram-gondi, syloti-nagri, meetei-mayek, telugu, mongolian, javanese, tagalog, yi, arabic, takri, thaana, avestan, kharoshthi, buhid, modi, manichaean, cham, phags-pa, sogdian, sharada, hanifi-rohingya, oriya, sinhala, tirhuta, psalter-pahlavi, siddham, hebrew, thai, batak, khmer, khudawadi, sundanese, saurashtra, malayalam, tagbanwa, syriac, limbu, tai-le, dogra, tamil, tifinagh, lao, new-tai-lue, balinese, bengali, kaithi, khojki, grantha, hanunoo, duployan, kannada, mandaic, myanmar, pahawh-hmong, hatran, mahajani, rejang, tai-viet, zanabazar-square, warang-citi, kayah-li, tibetan, gurmukhi, buginese, brahmi, lepcha</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: bhaiksuki, tai-tham, gunjala-gondi, devanagari, newa, nko, chakma, gujarati, masaram-gondi, syloti-nagri, meetei-mayek, old-hungarian, telugu, mongolian, javanese, tagalog, yi, arabic, takri, thaana, avestan, kharoshthi, buhid, modi, manichaean, cham, phags-pa, sogdian, sharada, hanifi-rohingya, oriya, sinhala, tirhuta, psalter-pahlavi, siddham, hebrew, thai, batak, khmer, khudawadi, sundanese, saurashtra, malayalam, tagbanwa, syriac, limbu, tai-le, dogra, tamil, tifinagh, lao, new-tai-lue, balinese, bengali, kaithi, khojki, grantha, hanunoo, duployan, kannada, mandaic, myanmar, pahawh-hmong, rejang, mahajani, tai-viet, zanabazar-square, warang-citi, kayah-li, tibetan, gurmukhi, buginese, brahmi, lepcha</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: thaana, hebrew, nko, syriac, phags-pa, arabic</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, hebrew, nko, syriac, phags-pa</li>
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
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, tai-tham, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: nko, masaram-gondi, osage, adlam, manichaean, cham, math, tai-le, tagbanwa, saurashtra, malayalam, limbu, tamil, new-tai-lue, duployan, rejang, tai-viet, buginese, lepcha, elbasan, armenian, devanagari, telugu, canadian-aboriginal, yi, marchen, sharada, siddham, hebrew, thai, batak, sundanese, tifinagh, grantha, mandaic, myanmar, bassa-vah, warang-citi, gurmukhi, mahajani, bhaiksuki, gunjala-gondi, newa, chakma, soyombo, meetei-mayek, old-permic, mende-kikakui, javanese, kharoshthi, buhid, sogdian, music, sinhala, tirhuta, wancho, khmer, lao, balinese, khojki, symbols, kannada, pahawh-hmong, zanabazar-square, gujarati, tibetan, ahom, syloti-nagri, mongolian, takri, thaana, modi, phags-pa, miao, hanifi-rohingya, oriya, psalter-pahlavi, khudawadi, syriac, dogra, bengali, kaithi, coptic, caucasian-albanian, hanunoo, kayah-li, tagalog, brahmi, tai-tham</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-simplified, nushu, chinese-hongkong, phags-pa, chinese-traditional, japanese, yi</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: japanese, chinese-simplified</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: japanese, yi, math, chinese-simplified</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: japanese, yi, math, chinese-simplified</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Han (Latn, 6 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Kaska (Latn, 125 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Heiltsuk (Latn, 300 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Nateni (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Basaa (Latn, 332,940 speakers), Belarusian (Cyrl, 10,064,517 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ejagham (Latn, 120,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Igbo (Latn, 27,823,640 speakers), Zapotec (Latn, 490,000 speakers), Fur (Latn, 1,230,163 speakers), Bete-Bendi (Latn, 100,000 speakers), Southern Kisi (Latn, 360,000 speakers), Makaa (Latn, 221,000 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Ekpeye (Latn, 226,000 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Sar (Latn, 500,000 speakers), Mundani (Latn, 34,000 speakers), Yala (Latn, 200,000 speakers), Dii (Latn, 71,000 speakers), Aghem (Latn, 38,843 speakers), Bafut (Latn, 158,146 speakers), Nzakara (Latn, 50,000 speakers), Ngbaka (Latn, 1,020,000 speakers), South Central Banda (Latn, 244,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglleft (U+2039) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour

* uniFF01 (U+FF01) has a counter-clockwise outer contour

* uniFF3B (U+FF3B) has a counter-clockwise outer contour

* uniFF3D (U+FF3D) has a counter-clockwise outer contour
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

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



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
| 0 | 0 | 14 | 11 | 96 | 8 | 122 | 0 | 
| 0% | 0% | 6% | 4% | 38% | 3% | 49% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
