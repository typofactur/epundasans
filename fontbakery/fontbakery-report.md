## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Make sure all font files have the same version value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.head.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Version info differs among font files of the same font project.
These were the version values found:</p>
<ul>
<li>fonts/variable/EpundaSans-Italic[wght].ttf: 2.100006103515625</li>
<li>fonts/variable/EpundaSans[wght].ttf: 2.0030059814453125</li>
</ul>
 [code: mismatch]



</div>
</details>
</div>
</details>

<details><summary>[11] EpundaSans-Italic[wght].ttf</summary>
<div>
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
<td align="left">U+1EAC: LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW</td>
<td align="left">U+1EAD: LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, tifinagh, todhri, coptic, hebrew, canadian-aboriginal, old-permic, tai-le, malayalam, duployan, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, gothic, tifinagh, caucasian-albanian, thai, cherokee, syriac</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: lepcha, hanunoo, kharoshthi, avestan, buhid, newa, siddham, telugu, tai-viet, yi, tai-le, zanabazar-square, tagbanwa, buginese, psalter-pahlavi, duployan, phags-pa, gunjala-gondi, kayah-li, khojki, myanmar, arabic, thaana, new-tai-lue, tai-tham, modi, thai, takri, meetei-mayek, oriya, warang-citi, bengali, javanese, sundanese, syriac, tamil, sinhala, dogra, tifinagh, sharada, lao, hatran, khmer, bhaiksuki, cham, mandaic, devanagari, mahajani, balinese, pahawh-hmong, saurashtra, tibetan, tirhuta, khudawadi, chakma, kannada, masaram-gondi, mongolian, sogdian, rejang, brahmi, nko, tagalog, hebrew, limbu, kaithi, batak, malayalam, syloti-nagri, gujarati, gurmukhi, hanifi-rohingya, manichaean, grantha</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: lepcha, hanunoo, kharoshthi, avestan, buhid, newa, siddham, telugu, yi, zanabazar-square, tai-le, tagbanwa, buginese, psalter-pahlavi, duployan, phags-pa, gunjala-gondi, kayah-li, khojki, myanmar, arabic, thaana, new-tai-lue, tai-tham, modi, thai, takri, meetei-mayek, oriya, warang-citi, bengali, javanese, sundanese, syriac, tamil, sinhala, dogra, tifinagh, sharada, lao, khmer, tai-viet, bhaiksuki, cham, mandaic, devanagari, mahajani, balinese, pahawh-hmong, saurashtra, tibetan, tirhuta, khudawadi, chakma, kannada, masaram-gondi, mongolian, sogdian, rejang, brahmi, nko, tagalog, hebrew, limbu, old-hungarian, kaithi, batak, malayalam, syloti-nagri, gujarati, gurmukhi, hanifi-rohingya, manichaean, grantha</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: arabic, nko, hebrew, phags-pa, thaana, syriac</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, phags-pa, thaana, syriac</li>
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
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, math, yi, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: lepcha, telugu, psalter-pahlavi, gunjala-gondi, khojki, myanmar, modi, takri, sundanese, dogra, tifinagh, sharada, lao, pahawh-hmong, mahajani, tirhuta, tibetan, music, khudawadi, miao, soyombo, rejang, tagalog, grantha, ahom, old-permic, yi, tagbanwa, tai-tham, adlam, thai, warang-citi, syriac, sinhala, balinese, armenian, chakma, kannada, masaram-gondi, wancho, brahmi, nko, marchen, osage, hanifi-rohingya, thaana, siddham, buhid, newa, zanabazar-square, tai-le, buginese, duployan, phags-pa, new-tai-lue, symbols, bengali, bassa-vah, bhaiksuki, cham, caucasian-albanian, sogdian, hebrew, limbu, batak, syloti-nagri, mongolian, math, hanunoo, kharoshthi, kayah-li, mende-kikakui, coptic, meetei-mayek, javanese, tamil, khmer, tai-viet, manichaean, mandaic, devanagari, saurashtra, canadian-aboriginal, kaithi, malayalam, elbasan, gujarati, gurmukhi, oriya</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, yi, phags-pa, nushu, japanese</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: chinese-simplified, japanese</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: chinese-simplified, math, japanese, yi</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: chinese-simplified, math, japanese, yi</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers), Kaska (Latn, 125 speakers), Han (Latn, 6 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Cicipu (Latn, 44,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Ma’di (Latn, 584,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Basaa (Latn, 332,940 speakers), Lugbara (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Avokaya (Latn, 100,000 speakers), Nateni (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Aghem (Latn, 38,843 speakers), Vute (Latn, 21,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Igbo (Latn, 27,823,640 speakers), Yala (Latn, 200,000 speakers), Ejagham (Latn, 120,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour
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

<details><summary>[8] EpundaSans[wght].ttf</summary>
<div>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, tifinagh, todhri, coptic, hebrew, canadian-aboriginal, old-permic, tai-le, malayalam, duployan, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, gothic, tifinagh, caucasian-albanian, thai, cherokee, syriac</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: lepcha, hanunoo, kharoshthi, avestan, buhid, newa, siddham, telugu, tai-viet, yi, tai-le, zanabazar-square, tagbanwa, buginese, psalter-pahlavi, duployan, phags-pa, gunjala-gondi, kayah-li, khojki, myanmar, arabic, thaana, new-tai-lue, tai-tham, modi, thai, takri, meetei-mayek, oriya, warang-citi, bengali, javanese, sundanese, syriac, tamil, sinhala, dogra, tifinagh, sharada, lao, hatran, khmer, bhaiksuki, cham, mandaic, devanagari, mahajani, balinese, pahawh-hmong, saurashtra, tibetan, tirhuta, khudawadi, chakma, kannada, masaram-gondi, mongolian, sogdian, rejang, brahmi, nko, tagalog, hebrew, limbu, kaithi, batak, malayalam, syloti-nagri, gujarati, gurmukhi, hanifi-rohingya, manichaean, grantha</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: lepcha, hanunoo, kharoshthi, avestan, buhid, newa, siddham, telugu, yi, zanabazar-square, tai-le, tagbanwa, buginese, psalter-pahlavi, duployan, phags-pa, gunjala-gondi, kayah-li, khojki, myanmar, arabic, thaana, new-tai-lue, tai-tham, modi, thai, takri, meetei-mayek, oriya, warang-citi, bengali, javanese, sundanese, syriac, tamil, sinhala, dogra, tifinagh, sharada, lao, khmer, tai-viet, bhaiksuki, cham, mandaic, devanagari, mahajani, balinese, pahawh-hmong, saurashtra, tibetan, tirhuta, khudawadi, chakma, kannada, masaram-gondi, mongolian, sogdian, rejang, brahmi, nko, tagalog, hebrew, limbu, old-hungarian, kaithi, batak, malayalam, syloti-nagri, gujarati, gurmukhi, hanifi-rohingya, manichaean, grantha</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: arabic, nko, hebrew, phags-pa, thaana, syriac</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, phags-pa, thaana, syriac</li>
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
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, math, yi, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: lepcha, telugu, psalter-pahlavi, gunjala-gondi, khojki, myanmar, modi, takri, sundanese, dogra, tifinagh, sharada, lao, pahawh-hmong, mahajani, tirhuta, tibetan, music, khudawadi, miao, soyombo, rejang, tagalog, grantha, ahom, old-permic, yi, tagbanwa, tai-tham, adlam, thai, warang-citi, syriac, sinhala, balinese, armenian, chakma, kannada, masaram-gondi, wancho, brahmi, nko, marchen, osage, hanifi-rohingya, thaana, siddham, buhid, newa, zanabazar-square, tai-le, buginese, duployan, phags-pa, new-tai-lue, symbols, bengali, bassa-vah, bhaiksuki, cham, caucasian-albanian, sogdian, hebrew, limbu, batak, syloti-nagri, mongolian, math, hanunoo, kharoshthi, kayah-li, mende-kikakui, coptic, meetei-mayek, javanese, tamil, khmer, tai-viet, manichaean, mandaic, devanagari, saurashtra, canadian-aboriginal, kaithi, malayalam, elbasan, gujarati, gurmukhi, oriya</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, yi, phags-pa, nushu, japanese</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: chinese-simplified, japanese</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: chinese-simplified, japanese, yi</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: chinese-simplified, math, japanese, yi</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: chinese-simplified, math, japanese, yi</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers), Kaska (Latn, 125 speakers), Han (Latn, 6 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Sar (Latn, 500,000 speakers), Heiltsuk (Latn, 300 speakers), Cicipu (Latn, 44,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Ma’di (Latn, 584,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Basaa (Latn, 332,940 speakers), Lugbara (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Avokaya (Latn, 100,000 speakers), Nateni (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Aghem (Latn, 38,843 speakers), Vute (Latn, 21,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Igbo (Latn, 27,823,640 speakers), Yala (Latn, 200,000 speakers), Ejagham (Latn, 120,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
 [code: soft-dotted]



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




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 18 | 183 | 15 | 266 | 0 | 
| 0% | 0% | 0% | 4% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
