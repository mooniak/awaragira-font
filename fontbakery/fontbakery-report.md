## FontBakery report

fontbakery version: 0.12.6



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Awaragira-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[22] Awaragira-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 323, but got 200 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the ufo profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.</p>
<p>No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.</p>
 [code: drm]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0022 (QUOTATION MARK)


- 0x0023 (NUMBER SIGN)


- 0x0024 (DOLLAR SIGN)


- 0x0025 (PERCENT SIGN)


- 0x0026 (AMPERSAND)


- 0x0027 (APOSTROPHE)


- 0x002B (PLUS SIGN)


- 0x003C (LESS-THAN SIGN)


- 0x003D (EQUALS SIGN)


- 0x003E (GREATER-THAN SIGN)


- 0x0040 (COMMERCIAL AT)


- 0x0041 (LATIN CAPITAL LETTER A)


- 0x0042 (LATIN CAPITAL LETTER B)


- 0x0043 (LATIN CAPITAL LETTER C)


- 0x0044 (LATIN CAPITAL LETTER D)


- 0x0045 (LATIN CAPITAL LETTER E)


- 0x0046 (LATIN CAPITAL LETTER F)


- 0x0047 (LATIN CAPITAL LETTER G)


- 0x0048 (LATIN CAPITAL LETTER H)


- 0x0049 (LATIN CAPITAL LETTER I)


- 0x004A (LATIN CAPITAL LETTER J)


- 0x004B (LATIN CAPITAL LETTER K)


- 0x004C (LATIN CAPITAL LETTER L)


- 0x004D (LATIN CAPITAL LETTER M)


- 0x004E (LATIN CAPITAL LETTER N)


- 0x004F (LATIN CAPITAL LETTER O)


- 0x0050 (LATIN CAPITAL LETTER P)


- 0x0051 (LATIN CAPITAL LETTER Q)


- 0x0052 (LATIN CAPITAL LETTER R)


- 0x0053 (LATIN CAPITAL LETTER S)


- 0x0054 (LATIN CAPITAL LETTER T)


- 0x0055 (LATIN CAPITAL LETTER U)


- 0x0056 (LATIN CAPITAL LETTER V)


- 0x0057 (LATIN CAPITAL LETTER W)


- 0x0058 (LATIN CAPITAL LETTER X)


- 0x0059 (LATIN CAPITAL LETTER Y)


- 0x005A (LATIN CAPITAL LETTER Z)


- 0x005B (LEFT SQUARE BRACKET)


- 0x005C (REVERSE SOLIDUS)


- 0x005D (RIGHT SQUARE BRACKET)


- 0x005E (CIRCUMFLEX ACCENT)


- 0x005F (LOW LINE)


- 0x0060 (GRAVE ACCENT)


- 0x0061 (LATIN SMALL LETTER A)


- 0x0062 (LATIN SMALL LETTER B)


- 0x0063 (LATIN SMALL LETTER C)


- 0x0064 (LATIN SMALL LETTER D)


- 0x0065 (LATIN SMALL LETTER E)


- 0x0066 (LATIN SMALL LETTER F)


- 0x0067 (LATIN SMALL LETTER G)


- 0x0068 (LATIN SMALL LETTER H)


- 0x0069 (LATIN SMALL LETTER I)


- 0x006A (LATIN SMALL LETTER J)


- 0x006B (LATIN SMALL LETTER K)


- 0x006C (LATIN SMALL LETTER L)


- 0x006D (LATIN SMALL LETTER M)


- 0x006E (LATIN SMALL LETTER N)


- 0x006F (LATIN SMALL LETTER O)


- 0x0070 (LATIN SMALL LETTER P)


- 0x0071 (LATIN SMALL LETTER Q)


- 0x0072 (LATIN SMALL LETTER R)


- 0x0073 (LATIN SMALL LETTER S)


- 0x0074 (LATIN SMALL LETTER T)


- 0x0075 (LATIN SMALL LETTER U)


- 0x0076 (LATIN SMALL LETTER V)


- 0x0077 (LATIN SMALL LETTER W)


- 0x0078 (LATIN SMALL LETTER X)


- 0x0079 (LATIN SMALL LETTER Y)


- 0x007A (LATIN SMALL LETTER Z)


- 0x007B (LEFT CURLY BRACKET)


- 0x007C (VERTICAL LINE)


- 0x007D (RIGHT CURLY BRACKET)


- 0x007E (TILDE)


- 0x00A0 (NO-BREAK SPACE)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B6 (PILCROW SIGN)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x2022 (BULLET)


- 0x20AC (EURO SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. Current version string is: &quot;Version 0.010; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font can render its own name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>.notdef glyphs were found when attempting to render Awaragira</p>
 [code: render-own-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;200&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
sinAnusvara (U+0D82), sinMatraAa (U+0DCF), sinMatraAae (U+0DD1), sinMatraAe (U+0DD0), sinMatraAi (U+0DDB), sinMatraAu (U+0DDE), sinMatraE (U+0DD9), sinMatraEe (U+0DDA), sinMatraLl (U+0DF3), sinMatraLs (U+0DDF), sinMatraO (U+0DDC), sinMatraOo (U+0DDD), sinMatraR (U+0DD8), sinMatraRr (U+0DF2), sinVirama (U+0DCA) and sinVisarga (U+0D83)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+0D82, U+0D83, U+0DCF, U+0DD0, U+0DD1, U+0DD8, U+0DD9, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF, U+0DF2 and U+0DF3</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4

- Glyph name: uni00AD	Contours detected: 1	Expected: 0
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NameMe.880

- eight.osf

- five.osf

- four.osf

- nine.osf

- one.osf

- seven.osf

- six.osf

- three.osf

- two.osf

- zero.osf
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* onehalf (U+00BD): L&lt;&lt;803.0,205.0&gt;--&lt;746.0,144.0&gt;&gt; -&gt; L&lt;&lt;746.0,144.0&gt;--&lt;675.0,63.0&gt;&gt;

* sinBU: L&lt;&lt;525.0,-136.0&gt;--&lt;525.0,25.0&gt;&gt; -&gt; L&lt;&lt;525.0,25.0&gt;--&lt;525.0,26.0&gt;&gt;

* sinBUu: L&lt;&lt;543.0,-121.0&gt;--&lt;543.0,25.0&gt;&gt; -&gt; L&lt;&lt;543.0,25.0&gt;--&lt;543.0,26.0&gt;&gt;

* sinDU: L&lt;&lt;415.0,-136.0&gt;--&lt;415.0,25.0&gt;&gt; -&gt; L&lt;&lt;415.0,25.0&gt;--&lt;416.0,44.0&gt;&gt;

* sinDUu: L&lt;&lt;415.0,-119.0&gt;--&lt;415.0,25.0&gt;&gt; -&gt; L&lt;&lt;415.0,25.0&gt;--&lt;416.0,44.0&gt;&gt;

* sinJnyU: L&lt;&lt;1008.0,-136.0&gt;--&lt;1008.0,25.0&gt;&gt; -&gt; L&lt;&lt;1008.0,25.0&gt;--&lt;1009.0,44.0&gt;&gt;

* sinJnyUu: L&lt;&lt;1008.0,-119.0&gt;--&lt;1008.0,25.0&gt;&gt; -&gt; L&lt;&lt;1008.0,25.0&gt;--&lt;1009.0,44.0&gt;&gt;

* sinKSsa.reph: L&lt;&lt;269.0,406.0&gt;--&lt;232.0,361.0&gt;&gt; -&gt; L&lt;&lt;232.0,361.0&gt;--&lt;115.0,222.0&gt;&gt;

* sinKVa.reph: L&lt;&lt;232.0,361.0&gt;--&lt;171.0,289.0&gt;&gt; -&gt; L&lt;&lt;171.0,289.0&gt;--&lt;115.0,222.0&gt;&gt;

* sinKVa.reph: L&lt;&lt;269.0,406.0&gt;--&lt;232.0,361.0&gt;&gt; -&gt; L&lt;&lt;232.0,361.0&gt;--&lt;171.0,289.0&gt;&gt;

* sinNDU: L&lt;&lt;913.0,-136.0&gt;--&lt;913.0,25.0&gt;&gt; -&gt; L&lt;&lt;913.0,25.0&gt;--&lt;914.0,44.0&gt;&gt;

* sinNDUu: L&lt;&lt;913.0,-119.0&gt;--&lt;913.0,25.0&gt;&gt; -&gt; L&lt;&lt;913.0,25.0&gt;--&lt;914.0,44.0&gt;&gt;

* sinNdU: L&lt;&lt;537.0,-136.0&gt;--&lt;537.0,25.0&gt;&gt; -&gt; L&lt;&lt;537.0,25.0&gt;--&lt;538.0,44.0&gt;&gt;

* sinNdUu: L&lt;&lt;537.0,-119.0&gt;--&lt;537.0,25.0&gt;&gt; -&gt; L&lt;&lt;537.0,25.0&gt;--&lt;538.0,44.0&gt;&gt;

* sinNyU: L&lt;&lt;1115.0,-136.0&gt;--&lt;1115.0,25.0&gt;&gt; -&gt; L&lt;&lt;1115.0,25.0&gt;--&lt;1116.0,44.0&gt;&gt;

* sinNyUu: L&lt;&lt;1115.0,-119.0&gt;--&lt;1115.0,25.0&gt;&gt; -&gt; L&lt;&lt;1115.0,25.0&gt;--&lt;1116.0,44.0&gt;&gt;

* sinTTha.reph: L&lt;&lt;231.0,361.0&gt;--&lt;170.0,287.0&gt;&gt; -&gt; L&lt;&lt;170.0,287.0&gt;--&lt;116.0,222.0&gt;&gt;

* sinTTha.reph: L&lt;&lt;263.0,400.0&gt;--&lt;231.0,361.0&gt;&gt; -&gt; L&lt;&lt;231.0,361.0&gt;--&lt;170.0,287.0&gt;&gt;

* sinTVa.reph: L&lt;&lt;262.0,398.0&gt;--&lt;168.0,284.0&gt;&gt; -&gt; L&lt;&lt;168.0,284.0&gt;--&lt;115.0,223.0&gt;&gt;

* sinTVa.reph: L&lt;&lt;378.0,540.0&gt;--&lt;333.0,487.0&gt;&gt; -&gt; L&lt;&lt;333.0,487.0&gt;--&lt;314.0,463.0&gt;&gt;

* sinkundaliya (U+0DF4): L&lt;&lt;1870.0,349.0&gt;--&lt;1834.0,168.0&gt;&gt; -&gt; L&lt;&lt;1834.0,168.0&gt;--&lt;1832.0,152.0&gt;&gt;

* uni00B2 (U+00B2): L&lt;&lt;271.0,509.0&gt;--&lt;214.0,447.0&gt;&gt; -&gt; L&lt;&lt;214.0,447.0&gt;--&lt;143.0,366.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* sinDDha.reph: B&lt;&lt;382.0,880.0&gt;-&lt;373.0,872.0&gt;-&lt;367.0,862.0&gt;&gt;/L&lt;&lt;367.0,862.0&gt;--&lt;368.0,863.0&gt;&gt; = 14.036243467926457

* sinDVa.reph: B&lt;&lt;378.0,880.0&gt;-&lt;369.0,872.0&gt;-&lt;363.0,862.0&gt;&gt;/L&lt;&lt;363.0,862.0&gt;--&lt;364.0,863.0&gt;&gt; = 14.036243467926457

* sinF: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,431.0&gt;-&lt;341.0,454.0&gt;&gt; = 13.509803953281363

* sinFI: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinFIi: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinFR: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,431.0&gt;-&lt;341.0,454.0&gt;&gt; = 13.509803953281363

* sinFRI: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinFRIi: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinFRa: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinFU: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinFUu: B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinFa (U+0DC6): B&lt;&lt;324.0,449.0&gt;-&lt;330.0,430.0&gt;-&lt;331.0,418.0&gt;&gt;/B&lt;&lt;331.0,418.0&gt;-&lt;333.0,430.0&gt;-&lt;339.0,449.0&gt;&gt; = 14.22596389875178

* sinIi (U+0D8A): B&lt;&lt;244.0,512.0&gt;-&lt;235.0,504.0&gt;-&lt;227.0,497.0&gt;&gt;/B&lt;&lt;227.0,497.0&gt;-&lt;267.0,520.0&gt;-&lt;315.0,520.0&gt;&gt; = 11.287023327095078

* sinJh: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJh: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhI: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhI: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhIi: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhIi: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhR: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhR: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhRI: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhRI: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhRIi: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhRIi: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhRa: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhRa: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhU: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhU: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJhUu: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJhUu: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJha (U+0DA3): B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJha (U+0DA3): L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinJha.reph: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinJha.reph: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinK: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinK: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKI: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKI: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKIi: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKIi: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKR: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKR: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKRI: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKRI: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKRIi: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKRIi: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKRa: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKRa: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKSsa.reph: B&lt;&lt;284.5,64.5&gt;-&lt;281.0,73.0&gt;-&lt;280.0,81.0&gt;&gt;/B&lt;&lt;280.0,81.0&gt;-&lt;279.0,66.0&gt;-&lt;268.0,48.0&gt;&gt; = 10.939091183192135

* sinKU: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKU: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKUu: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKUu: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKV: B&lt;&lt;258.5,304.0&gt;-&lt;226.0,295.0&gt;-&lt;191.0,260.0&gt;&gt;/L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt; = 11.309932474020195

* sinKV: L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt;/B&lt;&lt;193.0,263.0&gt;-&lt;175.0,244.0&gt;-&lt;155.0,224.0&gt;&gt; = 9.761774775042225

* sinKVI: B&lt;&lt;258.5,304.0&gt;-&lt;226.0,295.0&gt;-&lt;191.0,260.0&gt;&gt;/L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt; = 11.309932474020195

* sinKVI: L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt;/B&lt;&lt;193.0,263.0&gt;-&lt;175.0,244.0&gt;-&lt;155.0,224.0&gt;&gt; = 9.761774775042225

* sinKVIi: B&lt;&lt;258.5,304.0&gt;-&lt;226.0,295.0&gt;-&lt;191.0,260.0&gt;&gt;/L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt; = 11.309932474020195

* sinKVIi: L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt;/B&lt;&lt;193.0,263.0&gt;-&lt;175.0,244.0&gt;-&lt;155.0,224.0&gt;&gt; = 9.761774775042225

* sinKVU: B&lt;&lt;258.5,304.0&gt;-&lt;226.0,295.0&gt;-&lt;191.0,260.0&gt;&gt;/L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt; = 11.309932474020195

* sinKVU: L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt;/B&lt;&lt;193.0,263.0&gt;-&lt;175.0,244.0&gt;-&lt;155.0,224.0&gt;&gt; = 9.761774775042225

* sinKVUu: B&lt;&lt;258.5,304.0&gt;-&lt;226.0,295.0&gt;-&lt;191.0,260.0&gt;&gt;/L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt; = 11.309932474020195

* sinKVUu: L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt;/B&lt;&lt;193.0,263.0&gt;-&lt;175.0,244.0&gt;-&lt;155.0,224.0&gt;&gt; = 9.761774775042225

* sinKVa.reph: B&lt;&lt;752.0,880.0&gt;-&lt;743.0,872.0&gt;-&lt;737.0,862.0&gt;&gt;/L&lt;&lt;737.0,862.0&gt;--&lt;738.0,863.0&gt;&gt; = 14.036243467926457

* sinKVa: B&lt;&lt;258.5,304.0&gt;-&lt;226.0,295.0&gt;-&lt;191.0,260.0&gt;&gt;/L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt; = 11.309932474020195

* sinKVa: L&lt;&lt;191.0,260.0&gt;--&lt;193.0,263.0&gt;&gt;/B&lt;&lt;193.0,263.0&gt;-&lt;175.0,244.0&gt;-&lt;155.0,224.0&gt;&gt; = 9.761774775042225

* sinKa (U+0D9A): B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKa (U+0D9A): L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinKa.reph: B&lt;&lt;278.5,304.0&gt;-&lt;246.0,295.0&gt;-&lt;211.0,260.0&gt;&gt;/L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt; = 11.309932474020195

* sinKa.reph: L&lt;&lt;211.0,260.0&gt;--&lt;213.0,263.0&gt;&gt;/B&lt;&lt;213.0,263.0&gt;-&lt;195.0,244.0&gt;-&lt;175.0,224.0&gt;&gt; = 9.761774775042225

* sinNDha.reph: B&lt;&lt;712.0,880.0&gt;-&lt;703.0,872.0&gt;-&lt;697.0,862.0&gt;&gt;/L&lt;&lt;697.0,862.0&gt;--&lt;698.0,863.0&gt;&gt; = 14.036243467926457

* sinR: B&lt;&lt;240.5,509.0&gt;-&lt;230.0,500.0&gt;-&lt;220.0,491.0&gt;&gt;/B&lt;&lt;220.0,491.0&gt;-&lt;244.0,505.0&gt;-&lt;273.5,512.5&gt;&gt; = 11.730775332287365

* sinRAae: B&lt;&lt;248.0,513.0&gt;-&lt;240.0,506.0&gt;-&lt;232.0,500.0&gt;&gt;/B&lt;&lt;232.0,500.0&gt;-&lt;270.0,520.0&gt;-&lt;315.0,520.0&gt;&gt; = 9.111357044784032

* sinRAe: B&lt;&lt;248.0,513.0&gt;-&lt;240.0,506.0&gt;-&lt;232.0,500.0&gt;&gt;/B&lt;&lt;232.0,500.0&gt;-&lt;270.0,520.0&gt;-&lt;315.0,520.0&gt;&gt; = 9.111357044784032

* sinRI: B&lt;&lt;240.5,509.0&gt;-&lt;230.0,500.0&gt;-&lt;220.0,491.0&gt;&gt;/B&lt;&lt;220.0,491.0&gt;-&lt;244.0,505.0&gt;-&lt;273.5,512.5&gt;&gt; = 11.730775332287365

* sinRIi: B&lt;&lt;240.5,509.0&gt;-&lt;230.0,500.0&gt;-&lt;220.0,491.0&gt;&gt;/B&lt;&lt;220.0,491.0&gt;-&lt;244.0,505.0&gt;-&lt;273.5,512.5&gt;&gt; = 11.730775332287365

* sinRU: B&lt;&lt;240.5,509.0&gt;-&lt;230.0,500.0&gt;-&lt;220.0,491.0&gt;&gt;/B&lt;&lt;220.0,491.0&gt;-&lt;244.0,505.0&gt;-&lt;273.5,512.5&gt;&gt; = 11.730775332287365

* sinRUu: B&lt;&lt;240.5,509.0&gt;-&lt;230.0,500.0&gt;-&lt;220.0,491.0&gt;&gt;/B&lt;&lt;220.0,491.0&gt;-&lt;244.0,505.0&gt;-&lt;273.5,512.5&gt;&gt; = 11.730775332287365

* sinRa (U+0DBB): B&lt;&lt;240.5,509.0&gt;-&lt;230.0,500.0&gt;-&lt;220.0,491.0&gt;&gt;/B&lt;&lt;220.0,491.0&gt;-&lt;244.0,505.0&gt;-&lt;273.5,512.5&gt;&gt; = 11.730775332287365

* sinTVa.reph: B&lt;&lt;724.0,880.0&gt;-&lt;715.0,872.0&gt;-&lt;709.0,862.0&gt;&gt;/L&lt;&lt;709.0,862.0&gt;--&lt;710.0,863.0&gt;&gt; = 14.036243467926457

* sinY: B&lt;&lt;341.0,86.0&gt;-&lt;335.0,105.0&gt;-&lt;333.0,117.0&gt;&gt;/B&lt;&lt;333.0,117.0&gt;-&lt;332.0,105.0&gt;-&lt;326.0,86.0&gt;&gt; = 14.22596389875178

* sinYI: B&lt;&lt;341.0,86.0&gt;-&lt;335.0,105.0&gt;-&lt;333.0,117.0&gt;&gt;/B&lt;&lt;333.0,117.0&gt;-&lt;332.0,105.0&gt;-&lt;326.0,86.0&gt;&gt; = 14.22596389875178

* sinYIi: B&lt;&lt;341.0,86.0&gt;-&lt;335.0,105.0&gt;-&lt;333.0,117.0&gt;&gt;/B&lt;&lt;333.0,117.0&gt;-&lt;332.0,105.0&gt;-&lt;326.0,86.0&gt;&gt; = 14.22596389875178

* sinYU: B&lt;&lt;341.0,86.0&gt;-&lt;335.0,105.0&gt;-&lt;333.0,117.0&gt;&gt;/B&lt;&lt;333.0,117.0&gt;-&lt;332.0,105.0&gt;-&lt;326.0,86.0&gt;&gt; = 14.22596389875178

* sinYUu: B&lt;&lt;341.0,86.0&gt;-&lt;335.0,105.0&gt;-&lt;333.0,117.0&gt;&gt;/B&lt;&lt;333.0,117.0&gt;-&lt;332.0,105.0&gt;-&lt;326.0,86.0&gt;&gt; = 14.22596389875178

* sinYa (U+0DBA): B&lt;&lt;341.0,86.0&gt;-&lt;335.0,105.0&gt;-&lt;333.0,117.0&gt;&gt;/B&lt;&lt;333.0,117.0&gt;-&lt;332.0,105.0&gt;-&lt;326.0,86.0&gt;&gt; = 14.22596389875178

* sinYa.reph: B&lt;&lt;341.0,86.0&gt;-&lt;335.0,105.0&gt;-&lt;333.0,117.0&gt;&gt;/B&lt;&lt;333.0,117.0&gt;-&lt;332.0,105.0&gt;-&lt;326.0,86.0&gt;&gt; = 14.22596389875178

* sinYansaya.reph: B&lt;&lt;190.0,723.5&gt;-&lt;155.0,709.0&gt;-&lt;137.0,681.0&gt;&gt;/B&lt;&lt;137.0,681.0&gt;-&lt;150.0,694.0&gt;-&lt;169.0,700.5&gt;&gt; = 12.26477372789237

* sinYansaya_Reph_MatraAa: B&lt;&lt;190.0,723.5&gt;-&lt;155.0,709.0&gt;-&lt;137.0,681.0&gt;&gt;/B&lt;&lt;137.0,681.0&gt;-&lt;150.0,694.0&gt;-&lt;169.0,700.5&gt;&gt; = 12.26477372789237

* sinYansaya_Reph_MatraU: B&lt;&lt;190.0,723.5&gt;-&lt;155.0,709.0&gt;-&lt;137.0,681.0&gt;&gt;/B&lt;&lt;137.0,681.0&gt;-&lt;150.0,694.0&gt;-&lt;169.0,700.5&gt;&gt; = 12.26477372789237

* sinYansaya_Reph_MatraUu: B&lt;&lt;190.0,723.5&gt;-&lt;155.0,709.0&gt;-&lt;137.0,681.0&gt;&gt;/B&lt;&lt;137.0,681.0&gt;-&lt;150.0,694.0&gt;-&lt;169.0,700.5&gt;&gt; = 12.26477372789237
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* four (U+0034): L&lt;&lt;316.0,176.0&gt;--&lt;5.0,177.0&gt;&gt;

* four.osf: L&lt;&lt;316.0,176.0&gt;--&lt;5.0,177.0&gt;&gt;

* onequarter (U+00BC): L&lt;&lt;744.0,107.0&gt;--&lt;531.0,106.0&gt;&gt;

* sinA (U+0D85): L&lt;&lt;363.0,57.0&gt;--&lt;361.0,317.0&gt;&gt;

* sinA (U+0D85): L&lt;&lt;364.0,-185.0&gt;--&lt;363.0,-9.0&gt;&gt;

* sinAa (U+0D86): L&lt;&lt;363.0,52.0&gt;--&lt;361.0,312.0&gt;&gt;

* sinAa (U+0D86): L&lt;&lt;364.0,-190.0&gt;--&lt;363.0,-14.0&gt;&gt;

* sinAae (U+0D88): L&lt;&lt;363.0,57.0&gt;--&lt;361.0,317.0&gt;&gt;

* sinAae (U+0D88): L&lt;&lt;364.0,-185.0&gt;--&lt;363.0,-9.0&gt;&gt;

* sinAe (U+0D87): L&lt;&lt;363.0,57.0&gt;--&lt;361.0,317.0&gt;&gt;

* sinAe (U+0D87): L&lt;&lt;364.0,-185.0&gt;--&lt;363.0,-9.0&gt;&gt;

* sinZerolith (U+0DE6): L&lt;&lt;120.0,126.0&gt;--&lt;121.0,529.0&gt;&gt;

* threequarters (U+00BE): L&lt;&lt;778.0,107.0&gt;--&lt;565.0,106.0&gt;&gt;

* uni2074 (U+2074): L&lt;&lt;251.0,414.0&gt;--&lt;38.0,413.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* sinNg has a counter-clockwise outer contour

* sinNg has a counter-clockwise outer contour

* sinNg has a counter-clockwise outer contour

* sinNgI has a counter-clockwise outer contour

* sinNgI has a counter-clockwise outer contour

* sinNgIi has a counter-clockwise outer contour

* sinNgIi has a counter-clockwise outer contour

* sinNgIi has a counter-clockwise outer contour

* sinNga (U+0D9E) has a counter-clockwise outer contour

* sinNga (U+0D9E) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



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







* ⚠️ **WARN** <p>OS/2 VendorID value 'MNIK' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
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







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Awaragira-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 11 | 13 | 120 | 7 | 100 | 0 | 
| 0% | 0% | 4% | 5% | 48% | 3% | 40% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
