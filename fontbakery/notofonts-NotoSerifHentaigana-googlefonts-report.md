## FontBakery report

fontbakery version: 0.11.2

<h2>Experimental checks</h2><p>These won't break the CI job for now, but will become effective after some time if nobody raises any concern.</p><details><summary><b>[1] NotoSerifHentaigana[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check tabular widths don't have kerning. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/tabular_kerning">com.google.fonts/check/tabular_kerning</a>)</summary><div>


* 💔 **ERROR** Failed with KeyError: None
```
  File "/home/runner/work/hentaigana/hentaigana/venv/lib/python3.11/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
                   ^^^^^^^^^^^^
  File "/home/runner/work/hentaigana/hentaigana/venv/lib/python3.11/site-packages/fontbakery/profiles/universal.py", line 2341, in com_google_fonts_check_tabular_kerning
    glyph_widths = [
                   ^
  File "/home/runner/work/hentaigana/hentaigana/venv/lib/python3.11/site-packages/fontbakery/profiles/universal.py", line 2342, in <listcomp>
    glyph_width(ttFont, glyph_name_for_character(ttFont, str(i)))
  File "/home/runner/work/hentaigana/hentaigana/venv/lib/python3.11/site-packages/fontbakery/profiles/universal.py", line 2240, in glyph_width
    return ttFont["hmtx"].metrics[glyph_name][0]
           ~~~~~~~~~~~~~~~~~~~~~~^^^^^^^^^^^^

``` [code: failed-check]
</div></details><br></div></details><h2>All other checks</h2><details><summary><b>[12] NotoSerifHentaigana[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0021 (EXCLAMATION MARK)


	- 0x0022 (QUOTATION MARK)


	- 0x0023 (NUMBER SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0026 (AMPERSAND)


	- 0x0027 (APOSTROPHE)


	- 0x0028 (LEFT PARENTHESIS)


	- 0x0029 (RIGHT PARENTHESIS)


	- 0x002A (ASTERISK)


	- 0x002B (PLUS SIGN)


	- 0x002C (COMMA)


	- 0x002D (HYPHEN-MINUS)


	- 0x002E (FULL STOP)


	- 0x002F (SOLIDUS)


	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)


	- 0x003A (COLON)


	- 0x003B (SEMICOLON)


	- 0x003C (LESS-THAN SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003F (QUESTION MARK)


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


	- 0x00A1 (INVERTED EXCLAMATION MARK)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A8 (DIAERESIS)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AA (FEMININE ORDINAL INDICATOR)


	- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


	- 0x00AE (REGISTERED SIGN)


	- 0x00AF (MACRON)


	- 0x00B0 (DEGREE SIGN)


	- 0x00B4 (ACUTE ACCENT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00B7 (MIDDLE DOT)


	- 0x00B8 (CEDILLA)


	- 0x00BA (MASCULINE ORDINAL INDICATOR)


	- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


	- 0x00BF (INVERTED QUESTION MARK)


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


	- 0x2018 (LEFT SINGLE QUOTATION MARK)


	- 0x2019 (RIGHT SINGLE QUOTATION MARK)


	- 0x201A (SINGLE LOW-9 QUOTATION MARK)


	- 0x201C (LEFT DOUBLE QUOTATION MARK)


	- 0x201D (RIGHT DOUBLE QUOTATION MARK)


	- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


	- 0x2022 (BULLET)


	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


	- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


	- 0x20AC (EURO SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x2212 (MINUS SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** No GF glyphset was found to be supported >80%, so language shaping support couldn't get checked. [code: no-glyphset-supported]
</div></details><details><summary>🔥 <b>FAIL:</b> Combined length of family and style must not exceed 32 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* 🔥 **FAIL** Variable font instance name 'ExtraLight Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 257 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'ExtraLight Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 257 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Light Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 258 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Light Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 258 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Regular Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 259 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Regular Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 259 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Medium Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 260 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Medium Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 260 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'SemiBold Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 261 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'SemiBold Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 261 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Bold Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 262 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Bold Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 262 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'ExtraBold Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 263 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'ExtraBold Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 263 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Black Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 264 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* 🔥 **FAIL** Variable font instance name 'Black Noto Serif Hentaigana ExtraLight' formed by space-separated concatenation of instance subfamily nameID 264 and font family name (nameID 1) exceeds 32 characters.

This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11. [code: instance-too-long]
* ⚠ **WARN** Name ID 6 'NotoSerifHentaigana-ExtraLight' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms. [code: nameid6-too-long]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Serif Hentaigana ExtraLight [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 291 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.43%) have a different width. You should check the widths of: ['space', 'uni00A0'] [code: mono-outliers]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/example.json: Expected and actual shaping not matching
* Shaping did not match: ๰

      Expected: None
      Got     : .notdef=0+500
  Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -1151 550 2302" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g0" d="M50.0,-286.0L50.0,1151.0L450.0,1151.0L450.0,-286.0L50.0,-286.0ZM100.0,-236.0L400.0,-236.0L400.0,1101.0L100.0,1101.0L100.0,-236.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g0"/> </g> </svg>  [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+3099 COMBINING KATAKANA-HIRAGANA VOICED SOUND MARK: try adding one of: japanese, chinese-simplified
 * U+309A COMBINING KATAKANA-HIRAGANA SEMI-VOICED SOUND MARK: try adding one of: japanese, chinese-simplified
 * U+1B000 KATAKANA LETTER ARCHAIC E: not included in any glyphset definition
 * U+1B001 HIRAGANA LETTER ARCHAIC YE: not included in any glyphset definition
 * U+1B002 HENTAIGANA LETTER A-1: not included in any glyphset definition
 * U+1B003 HENTAIGANA LETTER A-2: not included in any glyphset definition
 * U+1B004 HENTAIGANA LETTER A-3: not included in any glyphset definition
 * U+1B005 HENTAIGANA LETTER A-WO: not included in any glyphset definition
 * U+1B006 HENTAIGANA LETTER I-1: not included in any glyphset definition
 * U+1B007 HENTAIGANA LETTER I-2: not included in any glyphset definition
 * U+1B008 HENTAIGANA LETTER I-3: not included in any glyphset definition
 * U+1B009 HENTAIGANA LETTER I-4: not included in any glyphset definition
 * U+1B00A HENTAIGANA LETTER U-1: not included in any glyphset definition
 * U+1B00B HENTAIGANA LETTER U-2: not included in any glyphset definition
 * U+1B00C HENTAIGANA LETTER U-3: not included in any glyphset definition
 * U+1B00D HENTAIGANA LETTER U-4: not included in any glyphset definition
 * U+1B00E HENTAIGANA LETTER U-5: not included in any glyphset definition
 * U+1B00F HENTAIGANA LETTER E-2: not included in any glyphset definition
 * U+1B010 HENTAIGANA LETTER E-3: not included in any glyphset definition
 * U+1B011 HENTAIGANA LETTER E-4: not included in any glyphset definition
 * U+1B012 HENTAIGANA LETTER E-5: not included in any glyphset definition
 * U+1B013 HENTAIGANA LETTER E-6: not included in any glyphset definition
 * U+1B014 HENTAIGANA LETTER O-1: not included in any glyphset definition
 * U+1B015 HENTAIGANA LETTER O-2: not included in any glyphset definition
 * U+1B016 HENTAIGANA LETTER O-3: not included in any glyphset definition
 * U+1B017 HENTAIGANA LETTER KA-1: not included in any glyphset definition
 * U+1B018 HENTAIGANA LETTER KA-2: not included in any glyphset definition
 * U+1B019 HENTAIGANA LETTER KA-3: not included in any glyphset definition
 * U+1B01A HENTAIGANA LETTER KA-4: not included in any glyphset definition
 * U+1B01B HENTAIGANA LETTER KA-5: not included in any glyphset definition
 * U+1B01C HENTAIGANA LETTER KA-6: not included in any glyphset definition
 * U+1B01D HENTAIGANA LETTER KA-7: not included in any glyphset definition
 * U+1B01E HENTAIGANA LETTER KA-8: not included in any glyphset definition
 * U+1B01F HENTAIGANA LETTER KA-9: not included in any glyphset definition
 * U+1B020 HENTAIGANA LETTER KA-10: not included in any glyphset definition
 * U+1B021 HENTAIGANA LETTER KA-11: not included in any glyphset definition
 * U+1B022 HENTAIGANA LETTER KA-KE: not included in any glyphset definition
 * U+1B023 HENTAIGANA LETTER KI-1: not included in any glyphset definition
 * U+1B024 HENTAIGANA LETTER KI-2: not included in any glyphset definition
 * U+1B025 HENTAIGANA LETTER KI-3: not included in any glyphset definition
 * U+1B026 HENTAIGANA LETTER KI-4: not included in any glyphset definition
 * U+1B027 HENTAIGANA LETTER KI-5: not included in any glyphset definition
 * U+1B028 HENTAIGANA LETTER KI-6: not included in any glyphset definition
 * U+1B029 HENTAIGANA LETTER KI-7: not included in any glyphset definition
 * U+1B02A HENTAIGANA LETTER KI-8: not included in any glyphset definition
 * U+1B02B HENTAIGANA LETTER KU-1: not included in any glyphset definition
 * U+1B02C HENTAIGANA LETTER KU-2: not included in any glyphset definition
 * U+1B02D HENTAIGANA LETTER KU-3: not included in any glyphset definition
 * U+1B02E HENTAIGANA LETTER KU-4: not included in any glyphset definition
 * U+1B02F HENTAIGANA LETTER KU-5: not included in any glyphset definition
 * U+1B030 HENTAIGANA LETTER KU-6: not included in any glyphset definition
 * U+1B031 HENTAIGANA LETTER KU-7: not included in any glyphset definition
 * U+1B032 HENTAIGANA LETTER KE-1: not included in any glyphset definition
 * U+1B033 HENTAIGANA LETTER KE-2: not included in any glyphset definition
 * U+1B034 HENTAIGANA LETTER KE-3: not included in any glyphset definition
 * U+1B035 HENTAIGANA LETTER KE-4: not included in any glyphset definition
 * U+1B036 HENTAIGANA LETTER KE-5: not included in any glyphset definition
 * U+1B037 HENTAIGANA LETTER KE-6: not included in any glyphset definition
 * U+1B038 HENTAIGANA LETTER KO-1: not included in any glyphset definition
 * U+1B039 HENTAIGANA LETTER KO-2: not included in any glyphset definition
 * U+1B03A HENTAIGANA LETTER KO-3: not included in any glyphset definition
 * U+1B03B HENTAIGANA LETTER KO-KI: not included in any glyphset definition
 * U+1B03C HENTAIGANA LETTER SA-1: not included in any glyphset definition
 * U+1B03D HENTAIGANA LETTER SA-2: not included in any glyphset definition
 * U+1B03E HENTAIGANA LETTER SA-3: not included in any glyphset definition
 * U+1B03F HENTAIGANA LETTER SA-4: not included in any glyphset definition
 * U+1B040 HENTAIGANA LETTER SA-5: not included in any glyphset definition
 * U+1B041 HENTAIGANA LETTER SA-6: not included in any glyphset definition
 * U+1B042 HENTAIGANA LETTER SA-7: not included in any glyphset definition
 * U+1B043 HENTAIGANA LETTER SA-8: not included in any glyphset definition
 * U+1B044 HENTAIGANA LETTER SI-1: not included in any glyphset definition
 * U+1B045 HENTAIGANA LETTER SI-2: not included in any glyphset definition
 * U+1B046 HENTAIGANA LETTER SI-3: not included in any glyphset definition
 * U+1B047 HENTAIGANA LETTER SI-4: not included in any glyphset definition
 * U+1B048 HENTAIGANA LETTER SI-5: not included in any glyphset definition
 * U+1B049 HENTAIGANA LETTER SI-6: not included in any glyphset definition
 * U+1B04A HENTAIGANA LETTER SU-1: not included in any glyphset definition
 * U+1B04B HENTAIGANA LETTER SU-2: not included in any glyphset definition
 * U+1B04C HENTAIGANA LETTER SU-3: not included in any glyphset definition
 * U+1B04D HENTAIGANA LETTER SU-4: not included in any glyphset definition
 * U+1B04E HENTAIGANA LETTER SU-5: not included in any glyphset definition
 * U+1B04F HENTAIGANA LETTER SU-6: not included in any glyphset definition
 * U+1B050 HENTAIGANA LETTER SU-7: not included in any glyphset definition
 * U+1B051 HENTAIGANA LETTER SU-8: not included in any glyphset definition
 * U+1B052 HENTAIGANA LETTER SE-1: not included in any glyphset definition
 * U+1B053 HENTAIGANA LETTER SE-2: not included in any glyphset definition
 * U+1B054 HENTAIGANA LETTER SE-3: not included in any glyphset definition
 * U+1B055 HENTAIGANA LETTER SE-4: not included in any glyphset definition
 * U+1B056 HENTAIGANA LETTER SE-5: not included in any glyphset definition
 * U+1B057 HENTAIGANA LETTER SO-1: not included in any glyphset definition
 * U+1B058 HENTAIGANA LETTER SO-2: not included in any glyphset definition
 * U+1B059 HENTAIGANA LETTER SO-3: not included in any glyphset definition
 * U+1B05A HENTAIGANA LETTER SO-4: not included in any glyphset definition
 * U+1B05B HENTAIGANA LETTER SO-5: not included in any glyphset definition
 * U+1B05C HENTAIGANA LETTER SO-6: not included in any glyphset definition
 * U+1B05D HENTAIGANA LETTER SO-7: not included in any glyphset definition
 * U+1B05E HENTAIGANA LETTER TA-1: not included in any glyphset definition
 * U+1B05F HENTAIGANA LETTER TA-2: not included in any glyphset definition
 * U+1B060 HENTAIGANA LETTER TA-3: not included in any glyphset definition
 * U+1B061 HENTAIGANA LETTER TA-4: not included in any glyphset definition
 * U+1B062 HENTAIGANA LETTER TI-1: not included in any glyphset definition
 * U+1B063 HENTAIGANA LETTER TI-2: not included in any glyphset definition
 * U+1B064 HENTAIGANA LETTER TI-3: not included in any glyphset definition
 * U+1B065 HENTAIGANA LETTER TI-4: not included in any glyphset definition
 * U+1B066 HENTAIGANA LETTER TI-5: not included in any glyphset definition
 * U+1B067 HENTAIGANA LETTER TI-6: not included in any glyphset definition
 * U+1B068 HENTAIGANA LETTER TI-7: not included in any glyphset definition
 * U+1B069 HENTAIGANA LETTER TU-1: not included in any glyphset definition
 * U+1B06A HENTAIGANA LETTER TU-2: not included in any glyphset definition
 * U+1B06B HENTAIGANA LETTER TU-3: not included in any glyphset definition
 * U+1B06C HENTAIGANA LETTER TU-4: not included in any glyphset definition
 * U+1B06D HENTAIGANA LETTER TU-TO: not included in any glyphset definition
 * U+1B06E HENTAIGANA LETTER TE-1: not included in any glyphset definition
 * U+1B06F HENTAIGANA LETTER TE-2: not included in any glyphset definition
 * U+1B070 HENTAIGANA LETTER TE-3: not included in any glyphset definition
 * U+1B071 HENTAIGANA LETTER TE-4: not included in any glyphset definition
 * U+1B072 HENTAIGANA LETTER TE-5: not included in any glyphset definition
 * U+1B073 HENTAIGANA LETTER TE-6: not included in any glyphset definition
 * U+1B074 HENTAIGANA LETTER TE-7: not included in any glyphset definition
 * U+1B075 HENTAIGANA LETTER TE-8: not included in any glyphset definition
 * U+1B076 HENTAIGANA LETTER TE-9: not included in any glyphset definition
 * U+1B077 HENTAIGANA LETTER TO-1: not included in any glyphset definition
 * U+1B078 HENTAIGANA LETTER TO-2: not included in any glyphset definition
 * U+1B079 HENTAIGANA LETTER TO-3: not included in any glyphset definition
 * U+1B07A HENTAIGANA LETTER TO-4: not included in any glyphset definition
 * U+1B07B HENTAIGANA LETTER TO-5: not included in any glyphset definition
 * U+1B07C HENTAIGANA LETTER TO-6: not included in any glyphset definition
 * U+1B07D HENTAIGANA LETTER TO-RA: not included in any glyphset definition
 * U+1B07E HENTAIGANA LETTER NA-1: not included in any glyphset definition
 * U+1B07F HENTAIGANA LETTER NA-2: not included in any glyphset definition
 * U+1B080 HENTAIGANA LETTER NA-3: not included in any glyphset definition
 * U+1B081 HENTAIGANA LETTER NA-4: not included in any glyphset definition
 * U+1B082 HENTAIGANA LETTER NA-5: not included in any glyphset definition
 * U+1B083 HENTAIGANA LETTER NA-6: not included in any glyphset definition
 * U+1B084 HENTAIGANA LETTER NA-7: not included in any glyphset definition
 * U+1B085 HENTAIGANA LETTER NA-8: not included in any glyphset definition
 * U+1B086 HENTAIGANA LETTER NA-9: not included in any glyphset definition
 * U+1B087 HENTAIGANA LETTER NI-1: not included in any glyphset definition
 * U+1B088 HENTAIGANA LETTER NI-2: not included in any glyphset definition
 * U+1B089 HENTAIGANA LETTER NI-3: not included in any glyphset definition
 * U+1B08A HENTAIGANA LETTER NI-4: not included in any glyphset definition
 * U+1B08B HENTAIGANA LETTER NI-5: not included in any glyphset definition
 * U+1B08C HENTAIGANA LETTER NI-6: not included in any glyphset definition
 * U+1B08D HENTAIGANA LETTER NI-7: not included in any glyphset definition
 * U+1B08E HENTAIGANA LETTER NI-TE: not included in any glyphset definition
 * U+1B08F HENTAIGANA LETTER NU-1: not included in any glyphset definition
 * U+1B090 HENTAIGANA LETTER NU-2: not included in any glyphset definition
 * U+1B091 HENTAIGANA LETTER NU-3: not included in any glyphset definition
 * U+1B092 HENTAIGANA LETTER NE-1: not included in any glyphset definition
 * U+1B093 HENTAIGANA LETTER NE-2: not included in any glyphset definition
 * U+1B094 HENTAIGANA LETTER NE-3: not included in any glyphset definition
 * U+1B095 HENTAIGANA LETTER NE-4: not included in any glyphset definition
 * U+1B096 HENTAIGANA LETTER NE-5: not included in any glyphset definition
 * U+1B097 HENTAIGANA LETTER NE-6: not included in any glyphset definition
 * U+1B098 HENTAIGANA LETTER NE-KO: not included in any glyphset definition
 * U+1B099 HENTAIGANA LETTER NO-1: not included in any glyphset definition
 * U+1B09A HENTAIGANA LETTER NO-2: not included in any glyphset definition
 * U+1B09B HENTAIGANA LETTER NO-3: not included in any glyphset definition
 * U+1B09C HENTAIGANA LETTER NO-4: not included in any glyphset definition
 * U+1B09D HENTAIGANA LETTER NO-5: not included in any glyphset definition
 * U+1B09E HENTAIGANA LETTER HA-1: not included in any glyphset definition
 * U+1B09F HENTAIGANA LETTER HA-2: not included in any glyphset definition
 * U+1B0A0 HENTAIGANA LETTER HA-3: not included in any glyphset definition
 * U+1B0A1 HENTAIGANA LETTER HA-4: not included in any glyphset definition
 * U+1B0A2 HENTAIGANA LETTER HA-5: not included in any glyphset definition
 * U+1B0A3 HENTAIGANA LETTER HA-6: not included in any glyphset definition
 * U+1B0A4 HENTAIGANA LETTER HA-7: not included in any glyphset definition
 * U+1B0A5 HENTAIGANA LETTER HA-8: not included in any glyphset definition
 * U+1B0A6 HENTAIGANA LETTER HA-9: not included in any glyphset definition
 * U+1B0A7 HENTAIGANA LETTER HA-10: not included in any glyphset definition
 * U+1B0A8 HENTAIGANA LETTER HA-11: not included in any glyphset definition
 * U+1B0A9 HENTAIGANA LETTER HI-1: not included in any glyphset definition
 * U+1B0AA HENTAIGANA LETTER HI-2: not included in any glyphset definition
 * U+1B0AB HENTAIGANA LETTER HI-3: not included in any glyphset definition
 * U+1B0AC HENTAIGANA LETTER HI-4: not included in any glyphset definition
 * U+1B0AD HENTAIGANA LETTER HI-5: not included in any glyphset definition
 * U+1B0AE HENTAIGANA LETTER HI-6: not included in any glyphset definition
 * U+1B0AF HENTAIGANA LETTER HI-7: not included in any glyphset definition
 * U+1B0B0 HENTAIGANA LETTER HU-1: not included in any glyphset definition
 * U+1B0B1 HENTAIGANA LETTER HU-2: not included in any glyphset definition
 * U+1B0B2 HENTAIGANA LETTER HU-3: not included in any glyphset definition
 * U+1B0B3 HENTAIGANA LETTER HE-1: not included in any glyphset definition
 * U+1B0B4 HENTAIGANA LETTER HE-2: not included in any glyphset definition
 * U+1B0B5 HENTAIGANA LETTER HE-3: not included in any glyphset definition
 * U+1B0B6 HENTAIGANA LETTER HE-4: not included in any glyphset definition
 * U+1B0B7 HENTAIGANA LETTER HE-5: not included in any glyphset definition
 * U+1B0B8 HENTAIGANA LETTER HE-6: not included in any glyphset definition
 * U+1B0B9 HENTAIGANA LETTER HE-7: not included in any glyphset definition
 * U+1B0BA HENTAIGANA LETTER HO-1: not included in any glyphset definition
 * U+1B0BB HENTAIGANA LETTER HO-2: not included in any glyphset definition
 * U+1B0BC HENTAIGANA LETTER HO-3: not included in any glyphset definition
 * U+1B0BD HENTAIGANA LETTER HO-4: not included in any glyphset definition
 * U+1B0BE HENTAIGANA LETTER HO-5: not included in any glyphset definition
 * U+1B0BF HENTAIGANA LETTER HO-6: not included in any glyphset definition
 * U+1B0C0 HENTAIGANA LETTER HO-7: not included in any glyphset definition
 * U+1B0C1 HENTAIGANA LETTER HO-8: not included in any glyphset definition
 * U+1B0C2 HENTAIGANA LETTER MA-1: not included in any glyphset definition
 * U+1B0C3 HENTAIGANA LETTER MA-2: not included in any glyphset definition
 * U+1B0C4 HENTAIGANA LETTER MA-3: not included in any glyphset definition
 * U+1B0C5 HENTAIGANA LETTER MA-4: not included in any glyphset definition
 * U+1B0C6 HENTAIGANA LETTER MA-5: not included in any glyphset definition
 * U+1B0C7 HENTAIGANA LETTER MA-6: not included in any glyphset definition
 * U+1B0C8 HENTAIGANA LETTER MA-7: not included in any glyphset definition
 * U+1B0C9 HENTAIGANA LETTER MI-1: not included in any glyphset definition
 * U+1B0CA HENTAIGANA LETTER MI-2: not included in any glyphset definition
 * U+1B0CB HENTAIGANA LETTER MI-3: not included in any glyphset definition
 * U+1B0CC HENTAIGANA LETTER MI-4: not included in any glyphset definition
 * U+1B0CD HENTAIGANA LETTER MI-5: not included in any glyphset definition
 * U+1B0CE HENTAIGANA LETTER MI-6: not included in any glyphset definition
 * U+1B0CF HENTAIGANA LETTER MI-7: not included in any glyphset definition
 * U+1B0D0 HENTAIGANA LETTER MU-1: not included in any glyphset definition
 * U+1B0D1 HENTAIGANA LETTER MU-2: not included in any glyphset definition
 * U+1B0D2 HENTAIGANA LETTER MU-3: not included in any glyphset definition
 * U+1B0D3 HENTAIGANA LETTER MU-4: not included in any glyphset definition
 * U+1B0D4 HENTAIGANA LETTER ME-1: not included in any glyphset definition
 * U+1B0D5 HENTAIGANA LETTER ME-2: not included in any glyphset definition
 * U+1B0D6 HENTAIGANA LETTER ME-MA: not included in any glyphset definition
 * U+1B0D7 HENTAIGANA LETTER MO-1: not included in any glyphset definition
 * U+1B0D8 HENTAIGANA LETTER MO-2: not included in any glyphset definition
 * U+1B0D9 HENTAIGANA LETTER MO-3: not included in any glyphset definition
 * U+1B0DA HENTAIGANA LETTER MO-4: not included in any glyphset definition
 * U+1B0DB HENTAIGANA LETTER MO-5: not included in any glyphset definition
 * U+1B0DC HENTAIGANA LETTER MO-6: not included in any glyphset definition
 * U+1B0DD HENTAIGANA LETTER YA-1: not included in any glyphset definition
 * U+1B0DE HENTAIGANA LETTER YA-2: not included in any glyphset definition
 * U+1B0DF HENTAIGANA LETTER YA-3: not included in any glyphset definition
 * U+1B0E0 HENTAIGANA LETTER YA-4: not included in any glyphset definition
 * U+1B0E1 HENTAIGANA LETTER YA-5: not included in any glyphset definition
 * U+1B0E2 HENTAIGANA LETTER YA-YO: not included in any glyphset definition
 * U+1B0E3 HENTAIGANA LETTER YU-1: not included in any glyphset definition
 * U+1B0E4 HENTAIGANA LETTER YU-2: not included in any glyphset definition
 * U+1B0E5 HENTAIGANA LETTER YU-3: not included in any glyphset definition
 * U+1B0E6 HENTAIGANA LETTER YU-4: not included in any glyphset definition
 * U+1B0E7 HENTAIGANA LETTER YO-1: not included in any glyphset definition
 * U+1B0E8 HENTAIGANA LETTER YO-2: not included in any glyphset definition
 * U+1B0E9 HENTAIGANA LETTER YO-3: not included in any glyphset definition
 * U+1B0EA HENTAIGANA LETTER YO-4: not included in any glyphset definition
 * U+1B0EB HENTAIGANA LETTER YO-5: not included in any glyphset definition
 * U+1B0EC HENTAIGANA LETTER YO-6: not included in any glyphset definition
 * U+1B0ED HENTAIGANA LETTER RA-1: not included in any glyphset definition
 * U+1B0EE HENTAIGANA LETTER RA-2: not included in any glyphset definition
 * U+1B0EF HENTAIGANA LETTER RA-3: not included in any glyphset definition
 * U+1B0F0 HENTAIGANA LETTER RA-4: not included in any glyphset definition
 * U+1B0F1 HENTAIGANA LETTER RI-1: not included in any glyphset definition
 * U+1B0F2 HENTAIGANA LETTER RI-2: not included in any glyphset definition
 * U+1B0F3 HENTAIGANA LETTER RI-3: not included in any glyphset definition
 * U+1B0F4 HENTAIGANA LETTER RI-4: not included in any glyphset definition
 * U+1B0F5 HENTAIGANA LETTER RI-5: not included in any glyphset definition
 * U+1B0F6 HENTAIGANA LETTER RI-6: not included in any glyphset definition
 * U+1B0F7 HENTAIGANA LETTER RI-7: not included in any glyphset definition
 * U+1B0F8 HENTAIGANA LETTER RU-1: not included in any glyphset definition
 * U+1B0F9 HENTAIGANA LETTER RU-2: not included in any glyphset definition
 * U+1B0FA HENTAIGANA LETTER RU-3: not included in any glyphset definition
 * U+1B0FB HENTAIGANA LETTER RU-4: not included in any glyphset definition
 * U+1B0FC HENTAIGANA LETTER RU-5: not included in any glyphset definition
 * U+1B0FD HENTAIGANA LETTER RU-6: not included in any glyphset definition
 * U+1B0FE HENTAIGANA LETTER RE-1: not included in any glyphset definition
 * U+1B0FF HENTAIGANA LETTER RE-2: not included in any glyphset definition
 * U+1B100 HENTAIGANA LETTER RE-3: not included in any glyphset definition
 * U+1B101 HENTAIGANA LETTER RE-4: not included in any glyphset definition
 * U+1B102 HENTAIGANA LETTER RO-1: not included in any glyphset definition
 * U+1B103 HENTAIGANA LETTER RO-2: not included in any glyphset definition
 * U+1B104 HENTAIGANA LETTER RO-3: not included in any glyphset definition
 * U+1B105 HENTAIGANA LETTER RO-4: not included in any glyphset definition
 * U+1B106 HENTAIGANA LETTER RO-5: not included in any glyphset definition
 * U+1B107 HENTAIGANA LETTER RO-6: not included in any glyphset definition
 * U+1B108 HENTAIGANA LETTER WA-1: not included in any glyphset definition
 * U+1B109 HENTAIGANA LETTER WA-2: not included in any glyphset definition
 * U+1B10A HENTAIGANA LETTER WA-3: not included in any glyphset definition
 * U+1B10B HENTAIGANA LETTER WA-4: not included in any glyphset definition
 * U+1B10C HENTAIGANA LETTER WA-5: not included in any glyphset definition
 * U+1B10D HENTAIGANA LETTER WI-1: not included in any glyphset definition
 * U+1B10E HENTAIGANA LETTER WI-2: not included in any glyphset definition
 * U+1B10F HENTAIGANA LETTER WI-3: not included in any glyphset definition
 * U+1B110 HENTAIGANA LETTER WI-4: not included in any glyphset definition
 * U+1B111 HENTAIGANA LETTER WI-5: not included in any glyphset definition
 * U+1B112 HENTAIGANA LETTER WE-1: not included in any glyphset definition
 * U+1B113 HENTAIGANA LETTER WE-2: not included in any glyphset definition
 * U+1B114 HENTAIGANA LETTER WE-3: not included in any glyphset definition
 * U+1B115 HENTAIGANA LETTER WE-4: not included in any glyphset definition
 * U+1B116 HENTAIGANA LETTER WO-1: not included in any glyphset definition
 * U+1B117 HENTAIGANA LETTER WO-2: not included in any glyphset definition
 * U+1B118 HENTAIGANA LETTER WO-3: not included in any glyphset definition
 * U+1B119 HENTAIGANA LETTER WO-4: not included in any glyphset definition
 * U+1B11A HENTAIGANA LETTER WO-5: not included in any glyphset definition
 * U+1B11B HENTAIGANA LETTER WO-6: not included in any glyphset definition
 * U+1B11C HENTAIGANA LETTER WO-7: not included in any glyphset definition
 * U+1B11D HENTAIGANA LETTER N-MU-MO-1: not included in any glyphset definition
 * U+1B11E HENTAIGANA LETTER N-MU-MO-2: not included in any glyphset definition
 * U+1B120 KATAKANA LETTER ARCHAIC YI: not included in any glyphset definition
 * U+1B121 KATAKANA LETTER ARCHAIC YE: not included in any glyphset definition
 * U+1B122 KATAKANA LETTER ARCHAIC WU: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 150 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 2 CJK glyphs when there needs to be at least 150 in order to support the smallest CJK writing system, Kana.
The following CJK glyphs were found:
['uni3099', 'uni309A']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 1 | 0 | 7 | 5 | 105 | 9 | 133 | 0 |
| 0% | 0% | 3% | 2% | 40% | 3% | 51% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
