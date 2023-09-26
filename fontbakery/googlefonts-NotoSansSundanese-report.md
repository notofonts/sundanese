## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[11] NotoSansSundanese-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, tai-le, coptic, malayalam, old-permic, canadian-aboriginal, syriac, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `sundanese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni1BA1 (U+1BA1) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+1BA1 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=236.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=343.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=440.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=545.0,Y=713.0 (should be at cap-height 714?)

	* six (U+0036): X=489.0,Y=715.0 (should be at cap-height 714?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=543.0,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

	* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=295.0,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=288.5,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=481.0,Y=536.5 (should be at x-height 536?)

	* m (U+006D): X=627.5,Y=537.0 (should be at x-height 536?)

	* n (U+006E): X=291.5,Y=537.0 (should be at x-height 536?)

	* sterling (U+00A3): X=444.5,Y=712.5 (should be at cap-height 714?)

	* Ccedilla (U+00C7): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=758.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=0.5 (should be at baseline 0?)

	* ccedilla (U+00E7): X=394.5,Y=-0.5 (should be at baseline 0?)

	* egrave (U+00E8): X=432.5,Y=-0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=432.5,Y=-0.5 (should be at baseline 0?)

	* abreve (U+0103): X=249.0,Y=713.5 (should be at cap-height 714?)

	* abreve (U+0103): X=348.5,Y=714.5 (should be at cap-height 714?)

	* Cacute (U+0106): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cacute (U+0107): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=394.5,Y=-0.5 (should be at baseline 0?)

	* emacron (U+0113): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=432.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gbreve (U+011F): X=555.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=261.0,Y=713.5 (should be at cap-height 714?)

	* gbreve (U+011F): X=360.5,Y=714.5 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gdotaccent (U+0121): X=555.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=527.5,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=543.0,Y=712.0 (should be at cap-height 714?)

	* uni0123 (U+0123): X=555.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=591.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

	* ubreve (U+016D): X=276.0,Y=713.5 (should be at cap-height 714?)

	* ubreve (U+016D): X=375.5,Y=714.5 (should be at cap-height 714?)

	* breve (U+02D8): X=179.0,Y=713.5 (should be at cap-height 714?)

	* breve (U+02D8): X=278.5,Y=714.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=-50.0,Y=713.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=49.5,Y=714.5 (should be at cap-height 714?)

	* uni1B8E (U+1B8E): X=212.5,Y=0.5 (should be at baseline 0?)

	* uni1B8E (U+1B8E): X=33.5,Y=1.0 (should be at baseline 0?)

	* uni1B8E (U+1B8E): X=557.0,Y=1.0 (should be at baseline 0?)

	* uni1BB0 (U+1BB0): X=419.0,Y=-2.0 (should be at baseline 0?)

	* uni1BB0 (U+1BB0): X=419.0,Y=716.0 (should be at cap-height 714?)

	* uni1BB0 (U+1BB0): X=419.0,Y=-2.0 (should be at baseline 0?)

	* uni1BB8 (U+1BB8): X=221.5,Y=1.0 (should be at baseline 0?)

	* uni1BB8 (U+1BB8): X=42.5,Y=1.0 (should be at baseline 0?)

	* uni1BB8 (U+1BB8): X=530.0,Y=1.0 (should be at baseline 0?)

	* uni1BBC (U+1BBC): X=814.0,Y=-370.0 (should be at descender -368?)

	* uni1BBC (U+1BBC): X=1149.0,Y=-370.0 (should be at descender -368?)

	* uni1BBC (U+1BBC): X=814.0,Y=-370.0 (should be at descender -368?)

	* uni1CC4 (U+1CC4): X=1232.0,Y=-370.0 (should be at descender -368?)

	* uni1CC4 (U+1CC4): X=1567.0,Y=-370.0 (should be at descender -368?)

	* uni1CC4 (U+1CC4): X=1232.0,Y=-370.0 (should be at descender -368?)

	* uni1CC4 (U+1CC4): X=905.0,Y=2.0 (should be at baseline 0?)

	* uni1CC4 (U+1CC4): X=1254.0,Y=2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=371.5,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<228.0,134.0>--<228.0,127.0>>

	* at (U+0040) contains a short segment B<<636.0,296.0>-<635.0,286.0>-<635.0,275.5>>

	* at (U+0040) contains a short segment B<<635.0,275.5>-<635.0,265.0>-<635.0,262.0>>

	* at (U+0040) contains a short segment B<<646.5,207.5>-<658.0,194.0>-<672.0,194.0>>

	* M (U+004D) contains a short segment L<<220.0,560.0>--<216.0,560.0>>

	* M (U+004D) contains a short segment L<<465.0,168.0>--<468.0,168.0>>

	* N (U+004E) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* N (U+004E) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* Q (U+0051) contains a short segment L<<409.0,-10.0>--<398.0,-10.0>>

	* W (U+0057) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* a (U+0061) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* d (U+0064) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* m (U+006D) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* n (U+006E) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* p (U+0070) contains a short segment L<<220.0,475.0>--<227.0,475.0>>

	* r (U+0072) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* u (U+0075) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ordfeminine (U+00AA) contains a short segment L<<242.0,589.0>--<242.0,597.0>>

	* Ntilde (U+00D1) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Ntilde (U+00D1) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* agrave (U+00E0) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aacute (U+00E1) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* acircumflex (U+00E2) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* atilde (U+00E3) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* adieresis (U+00E4) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aring (U+00E5) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* ntilde (U+00F1) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* ugrave (U+00F9) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uacute (U+00FA) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ucircumflex (U+00FB) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* udieresis (U+00FC) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* amacron (U+0101) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* abreve (U+0103) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aogonek (U+0105) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* dcaron (U+010F) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* dcroat (U+0111) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* hbar (U+0127) contains a short segment L<<227.0,584.0>--<227.0,575.0>>

	* Nacute (U+0143) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Nacute (U+0143) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* nacute (U+0144) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* uni0145 (U+0145) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* uni0145 (U+0145) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* uni0146 (U+0146) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* Ncaron (U+0147) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Ncaron (U+0147) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* ncaron (U+0148) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* Eng (U+014A) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Eng (U+014A) contains a short segment L<<591.0,274.0>--<594.0,274.0>>

	* eng (U+014B) contains a short segment L<<212.0,476.0>--<221.0,476.0>>

	* racute (U+0155) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* uni0157 (U+0157) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* rcaron (U+0159) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* umacron (U+016B) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ubreve (U+016D) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uring (U+016F) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uogonek (U+0173) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* Wcircumflex (U+0174) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* uni1B85 (U+1B85) contains a short segment B<<623.5,251.0>-<615.0,246.0>-<615.0,239.0>>

	* uni1BB3 (U+1BB3) contains a short segment B<<623.5,251.0>-<615.0,246.0>-<615.0,239.0>>

	* uni1BB6 (U+1BB6) contains a short segment B<<517.5,251.0>-<509.0,246.0>-<509.0,239.0>>

	* uni1BB8 (U+1BB8) contains a short segment L<<818.0,556.0>--<795.0,556.0>>

	* uni1BB9 (U+1BB9) contains a short segment B<<592.5,251.0>-<584.0,246.0>-<584.0,239.0>>

	* Wgrave (U+1E80) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Wacute (U+1E82) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Wdieresis (U+1E84) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Euro (U+20AC) contains a short segment B<<237.0,378.0>-<237.0,374.0>-<236.5,367.5>>

	* Euro (U+20AC) contains a short segment B<<236.5,367.5>-<236.0,361.0>-<236.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<236.0,352.0>-<236.0,345.0>-<236.0,337.5>>

	* Euro (U+20AC) contains a short segment B<<236.0,337.5>-<236.0,330.0>-<237.0,322.0>>

	* Euro (U+20AC) contains a short segment B<<88.0,352.0>-<88.0,360.0>-<88.0,367.0>>

	* Euro (U+20AC) contains a short segment B<<88.0,367.0>-<88.0,374.0>-<89.0,378.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wdieresis (U+1E84): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wgrave (U+1E80): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* uni1B86 (U+1B86): L<<829.0,584.0>--<690.0,496.0>>/B<<690.0,496.0>-<705.0,501.0>-<729.0,506.5>> = 13.902687114220551 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSansSundanese-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, tai-le, coptic, malayalam, old-permic, canadian-aboriginal, syriac, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `sundanese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Sundanese Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni1BA1 (U+1BA1) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+1BA1 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<170.0,92.0>--<170.0,87.0>>

	* at (U+0040) contains a short segment B<<617.0,293.0>-<616.0,277.0>-<616.0,269.0>>

	* at (U+0040) contains a short segment B<<616.0,269.0>-<616.0,261.0>-<616.0,258.0>>

	* M (U+004D) contains a short segment L<<184.0,616.0>--<180.0,616.0>>

	* M (U+004D) contains a short segment L<<452.0,135.0>--<456.0,135.0>>

	* N (U+004E) contains a short segment L<<183.0,585.0>--<179.0,585.0>>

	* N (U+004E) contains a short segment L<<583.0,132.0>--<587.0,132.0>>

	* Q (U+0051) contains a short segment B<<415.0,-9.0>-<409.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<398.0,-10.0>-<392.0,-10.0>>

	* a (U+0061) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* d (U+0064) contains a short segment L<<441.0,72.0>--<436.0,72.0>>

	* m (U+006D) contains a short segment L<<176.0,465.0>--<181.0,465.0>>

	* n (U+006E) contains a short segment L<<176.0,465.0>--<181.0,465.0>>

	* p (U+0070) contains a short segment L<<177.0,465.0>--<181.0,465.0>>

	* r (U+0072) contains a short segment L<<174.0,441.0>--<179.0,441.0>>

	* u (U+0075) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<183.0,585.0>--<179.0,585.0>>

	* Ntilde (U+00D1) contains a short segment L<<583.0,132.0>--<587.0,132.0>>

	* germandbls (U+00DF) contains a short segment B<<396.0,411.0>-<396.0,398.0>-<403.0,387.0>>

	* agrave (U+00E0) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aacute (U+00E1) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* acircumflex (U+00E2) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* atilde (U+00E3) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* adieresis (U+00E4) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aring (U+00E5) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* ntilde (U+00F1) contains a short segment L<<176.0,465.0>--<181.0,465.0>>

	* ugrave (U+00F9) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* amacron (U+0101) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* abreve (U+0103) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aogonek (U+0105) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* dcaron (U+010F) contains a short segment L<<441.0,72.0>--<436.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<440.0,72.0>--<436.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<183.0,585.0>--<179.0,585.0>>

	* Nacute (U+0143) contains a short segment L<<583.0,132.0>--<587.0,132.0>>

	* nacute (U+0144) contains a short segment L<<176.0,465.0>--<181.0,465.0>>

	* uni0145 (U+0145) contains a short segment L<<183.0,585.0>--<179.0,585.0>>

	* uni0145 (U+0145) contains a short segment L<<583.0,132.0>--<587.0,132.0>>

	* uni0146 (U+0146) contains a short segment L<<176.0,465.0>--<181.0,465.0>>

	* Ncaron (U+0147) contains a short segment L<<183.0,585.0>--<179.0,585.0>>

	* Ncaron (U+0147) contains a short segment L<<583.0,132.0>--<587.0,132.0>>

	* ncaron (U+0148) contains a short segment L<<176.0,465.0>--<181.0,465.0>>

	* Eng (U+014A) contains a short segment L<<183.0,585.0>--<179.0,585.0>>

	* Eng (U+014A) contains a short segment L<<583.0,163.0>--<587.0,163.0>>

	* eng (U+014B) contains a short segment L<<177.0,465.0>--<182.0,465.0>>

	* racute (U+0155) contains a short segment L<<174.0,441.0>--<179.0,441.0>>

	* uni0157 (U+0157) contains a short segment L<<174.0,441.0>--<179.0,441.0>>

	* rcaron (U+0159) contains a short segment L<<174.0,441.0>--<179.0,441.0>>

	* umacron (U+016B) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* uring (U+016F) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<542.0,-157.0>-<554.0,-155.0>-<562.0,-153.0>>

	* uogonek (U+0173) contains a short segment L<<448.0,71.0>--<443.0,71.0>>

	* uni1B85 (U+1B85) contains a short segment B<<518.0,258.0>-<510.0,247.0>-<510.0,236.0>>

	* uni1B86 (U+1B86) contains a short segment B<<875.5,494.5>-<886.0,478.0>-<886.0,464.0>>

	* uni1B86 (U+1B86) contains a short segment B<<842.0,422.0>-<825.0,422.0>-<813.5,430.0>>

	* uni1B86 (U+1B86) contains a short segment B<<813.5,430.0>-<802.0,438.0>-<790.0,448.5>>

	* uni1BB3 (U+1BB3) contains a short segment B<<518.0,258.0>-<510.0,247.0>-<510.0,236.0>>

	* uni1BB6 (U+1BB6) contains a short segment B<<405.0,258.0>-<397.0,247.0>-<397.0,236.0>>

	* uni1BB9 (U+1BB9) contains a short segment B<<496.0,258.0>-<488.0,247.0>-<488.0,236.0>>

	* Euro (U+20AC) contains a short segment B<<192.0,388.0>-<192.0,379.0>-<191.5,370.5>>

	* Euro (U+20AC) contains a short segment B<<191.5,370.5>-<191.0,362.0>-<191.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<191.0,352.0>-<191.0,343.0>-<191.5,333.0>>

	* Euro (U+20AC) contains a short segment B<<191.5,333.0>-<192.0,323.0>-<192.0,313.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,313.0>-<93.0,324.0>-<93.0,332.0>>

	* Euro (U+20AC) contains a short segment B<<93.0,332.0>-<93.0,340.0>-<93.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<93.0,352.0>-<93.0,362.0>-<93.5,372.0>>

	* Euro (U+20AC) contains a short segment B<<93.5,372.0>-<94.0,382.0>-<94.0,388.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSansSundanese-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/sundanese.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansSundanese/googlefonts/ttf/NotoSansSundanese-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/sundanese.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ᮘᮢᮧᮀ ᮘᮣᮧᮀ ᮘᮡᮧᮀ</span> (#1)</li>


<pre>Expected: uni1B98=0+970|uni1BA2=0@-179,0+0|uni1B80=0@-275,30+0|uni1BA7=0+375|space=4+260|uni1B98=5+970|uni1BA3=5@80,0+0|uni1B80=5@-275,30+0|uni1BA7=5+375|space=9+260|uni1B98=10+970|uni1B80=10@-275,30+0|uni1BA1=10+212|uni1BA7=10+375</pre>



<pre>Got     : uni1B98=0+970|uni1BA2=0@-179,0+0|uni1B80=0@-275,30+0|uni1BA7=0+375|space=4+260|uni1B98=5+970|uni1BA3=5@80,0+0|uni1B80=5@-275,30+0|uni1BA7=5+375|space=9+260|uni1B98=10+970|uni1B80=10@-275,30+0|uni1BA1=10@-13,0+212|uni1BA7=10+375</pre>



<pre>                                                                                                                                                                                                                    ^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4767 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L402.0,714.0L377.0,635.0L284.0,635.0L101.0,79.0L298.0,79.0L430.0,474.0L473.0,474.0L716.0,135.0L885.0,635.0L587.0,635.0L571.0,589.0L475.0,589.0L517.0,714.0L1008.0,714.0L770.0,0.0L708.0,0.0L474.0,323.0L368.0,0.0L-22.0,0.0Z" transform="translate(0, 868)"/>
<path d="M-126.0,-271.0Q-169.0,-271.0 -208.5,-255.0Q-248.0,-239.0 -283.5,-214.0Q-319.0,-189.0 -350.5,-161.0Q-382.0,-133.0 -408.0,-110.0L-554.0,-185.0L-585.0,-124.0L-397.0,-30.0Q-378.0,-47.0 -346.5,-77.0Q-315.0,-107.0 -277.5,-138.0Q-240.0,-169.0 -201.0,-190.5Q-162.0,-212.0 -128.0,-212.0Q-90.0,-212.0 -72.0,-197.0Q-54.0,-182.0 -54.0,-157.0Q-54.0,-129.0 -71.0,-108.0Q-88.0,-87.0 -107.0,-65.0L-63.0,-25.0Q-35.0,-48.0 -11.5,-83.5Q12.0,-119.0 12.0,-155.0Q12.0,-197.0 -7.5,-222.5Q-27.0,-248.0 -58.0,-259.5Q-89.0,-271.0 -126.0,-271.0Z" transform="translate(791, 868)"/>
<path d="M-216.0,756.0Q-260.0,756.0 -291.5,787.5Q-323.0,819.0 -323.0,863.0Q-323.0,907.0 -291.5,938.5Q-260.0,970.0 -216.0,970.0Q-172.0,970.0 -140.5,938.5Q-109.0,907.0 -109.0,863.0Q-109.0,819.0 -140.5,787.5Q-172.0,756.0 -216.0,756.0ZM-216.0,814.0Q-196.0,814.0 -182.0,828.5Q-168.0,843.0 -168.0,863.0Q-168.0,883.0 -182.0,897.0Q-196.0,911.0 -216.0,911.0Q-236.0,911.0 -250.5,897.0Q-265.0,883.0 -265.0,863.0Q-265.0,843.0 -250.5,828.5Q-236.0,814.0 -216.0,814.0Z" transform="translate(695, 898)"/>
<path d="M35.0,0.0L102.0,151.0L4.0,151.0L21.0,205.0L126.0,205.0L164.0,288.0L-3.0,288.0L19.0,356.0L263.0,356.0L136.0,68.0L325.0,68.0L303.0,0.0L35.0,0.0Z" transform="translate(970, 868)"/>
<path d="" transform="translate(1345, 868)"/>
<path d="M-22.0,0.0L214.0,714.0L402.0,714.0L377.0,635.0L284.0,635.0L101.0,79.0L298.0,79.0L430.0,474.0L473.0,474.0L716.0,135.0L885.0,635.0L587.0,635.0L571.0,589.0L475.0,589.0L517.0,714.0L1008.0,714.0L770.0,0.0L708.0,0.0L474.0,323.0L368.0,0.0L-22.0,0.0Z" transform="translate(1605, 868)"/>
<path d="M-581.0,-248.0L-517.0,-53.0L-343.0,-53.0L-390.0,-195.0L-313.0,-195.0L-328.0,-240.0L-460.0,-240.0L-414.0,-98.0L-476.0,-98.0L-525.0,-248.0L-581.0,-248.0Z" transform="translate(2655, 868)"/>
<path d="M-216.0,756.0Q-260.0,756.0 -291.5,787.5Q-323.0,819.0 -323.0,863.0Q-323.0,907.0 -291.5,938.5Q-260.0,970.0 -216.0,970.0Q-172.0,970.0 -140.5,938.5Q-109.0,907.0 -109.0,863.0Q-109.0,819.0 -140.5,787.5Q-172.0,756.0 -216.0,756.0ZM-216.0,814.0Q-196.0,814.0 -182.0,828.5Q-168.0,843.0 -168.0,863.0Q-168.0,883.0 -182.0,897.0Q-196.0,911.0 -216.0,911.0Q-236.0,911.0 -250.5,897.0Q-265.0,883.0 -265.0,863.0Q-265.0,843.0 -250.5,828.5Q-236.0,814.0 -216.0,814.0Z" transform="translate(2300, 898)"/>
<path d="M35.0,0.0L102.0,151.0L4.0,151.0L21.0,205.0L126.0,205.0L164.0,288.0L-3.0,288.0L19.0,356.0L263.0,356.0L136.0,68.0L325.0,68.0L303.0,0.0L35.0,0.0Z" transform="translate(2575, 868)"/>
<path d="" transform="translate(2950, 868)"/>
<path d="M-22.0,0.0L214.0,714.0L402.0,714.0L377.0,635.0L284.0,635.0L101.0,79.0L298.0,79.0L430.0,474.0L473.0,474.0L716.0,135.0L885.0,635.0L587.0,635.0L571.0,589.0L475.0,589.0L517.0,714.0L1008.0,714.0L770.0,0.0L708.0,0.0L474.0,323.0L368.0,0.0L-22.0,0.0Z" transform="translate(3210, 868)"/>
<path d="M-216.0,756.0Q-260.0,756.0 -291.5,787.5Q-323.0,819.0 -323.0,863.0Q-323.0,907.0 -291.5,938.5Q-260.0,970.0 -216.0,970.0Q-172.0,970.0 -140.5,938.5Q-109.0,907.0 -109.0,863.0Q-109.0,819.0 -140.5,787.5Q-172.0,756.0 -216.0,756.0ZM-216.0,814.0Q-196.0,814.0 -182.0,828.5Q-168.0,843.0 -168.0,863.0Q-168.0,883.0 -182.0,897.0Q-196.0,911.0 -216.0,911.0Q-236.0,911.0 -250.5,897.0Q-265.0,883.0 -265.0,863.0Q-265.0,843.0 -250.5,828.5Q-236.0,814.0 -216.0,814.0Z" transform="translate(3905, 898)"/>
<path d="M-578.0,-241.0L-542.0,-129.0L-480.0,-129.0L-497.0,-181.0L-159.0,-181.0L-6.0,284.0L182.0,284.0L133.0,133.0L71.0,133.0L102.0,228.0L47.0,228.0L-108.0,-241.0L-578.0,-241.0Z" transform="translate(4167, 868)"/>
<path d="M35.0,0.0L102.0,151.0L4.0,151.0L21.0,205.0L126.0,205.0L164.0,288.0L-3.0,288.0L19.0,356.0L263.0,356.0L136.0,68.0L325.0,68.0L303.0,0.0L35.0,0.0Z" transform="translate(4392, 868)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4767 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L402.0,714.0L377.0,635.0L284.0,635.0L101.0,79.0L298.0,79.0L430.0,474.0L473.0,474.0L716.0,135.0L885.0,635.0L587.0,635.0L571.0,589.0L475.0,589.0L517.0,714.0L1008.0,714.0L770.0,0.0L708.0,0.0L474.0,323.0L368.0,0.0L-22.0,0.0Z" transform="translate(0, 868)"/>
<path d="M-126.0,-271.0Q-169.0,-271.0 -208.5,-255.0Q-248.0,-239.0 -283.5,-214.0Q-319.0,-189.0 -350.5,-161.0Q-382.0,-133.0 -408.0,-110.0L-554.0,-185.0L-585.0,-124.0L-397.0,-30.0Q-378.0,-47.0 -346.5,-77.0Q-315.0,-107.0 -277.5,-138.0Q-240.0,-169.0 -201.0,-190.5Q-162.0,-212.0 -128.0,-212.0Q-90.0,-212.0 -72.0,-197.0Q-54.0,-182.0 -54.0,-157.0Q-54.0,-129.0 -71.0,-108.0Q-88.0,-87.0 -107.0,-65.0L-63.0,-25.0Q-35.0,-48.0 -11.5,-83.5Q12.0,-119.0 12.0,-155.0Q12.0,-197.0 -7.5,-222.5Q-27.0,-248.0 -58.0,-259.5Q-89.0,-271.0 -126.0,-271.0Z" transform="translate(791, 868)"/>
<path d="M-216.0,756.0Q-260.0,756.0 -291.5,787.5Q-323.0,819.0 -323.0,863.0Q-323.0,907.0 -291.5,938.5Q-260.0,970.0 -216.0,970.0Q-172.0,970.0 -140.5,938.5Q-109.0,907.0 -109.0,863.0Q-109.0,819.0 -140.5,787.5Q-172.0,756.0 -216.0,756.0ZM-216.0,814.0Q-196.0,814.0 -182.0,828.5Q-168.0,843.0 -168.0,863.0Q-168.0,883.0 -182.0,897.0Q-196.0,911.0 -216.0,911.0Q-236.0,911.0 -250.5,897.0Q-265.0,883.0 -265.0,863.0Q-265.0,843.0 -250.5,828.5Q-236.0,814.0 -216.0,814.0Z" transform="translate(695, 898)"/>
<path d="M35.0,0.0L102.0,151.0L4.0,151.0L21.0,205.0L126.0,205.0L164.0,288.0L-3.0,288.0L19.0,356.0L263.0,356.0L136.0,68.0L325.0,68.0L303.0,0.0L35.0,0.0Z" transform="translate(970, 868)"/>
<path d="" transform="translate(1345, 868)"/>
<path d="M-22.0,0.0L214.0,714.0L402.0,714.0L377.0,635.0L284.0,635.0L101.0,79.0L298.0,79.0L430.0,474.0L473.0,474.0L716.0,135.0L885.0,635.0L587.0,635.0L571.0,589.0L475.0,589.0L517.0,714.0L1008.0,714.0L770.0,0.0L708.0,0.0L474.0,323.0L368.0,0.0L-22.0,0.0Z" transform="translate(1605, 868)"/>
<path d="M-581.0,-248.0L-517.0,-53.0L-343.0,-53.0L-390.0,-195.0L-313.0,-195.0L-328.0,-240.0L-460.0,-240.0L-414.0,-98.0L-476.0,-98.0L-525.0,-248.0L-581.0,-248.0Z" transform="translate(2655, 868)"/>
<path d="M-216.0,756.0Q-260.0,756.0 -291.5,787.5Q-323.0,819.0 -323.0,863.0Q-323.0,907.0 -291.5,938.5Q-260.0,970.0 -216.0,970.0Q-172.0,970.0 -140.5,938.5Q-109.0,907.0 -109.0,863.0Q-109.0,819.0 -140.5,787.5Q-172.0,756.0 -216.0,756.0ZM-216.0,814.0Q-196.0,814.0 -182.0,828.5Q-168.0,843.0 -168.0,863.0Q-168.0,883.0 -182.0,897.0Q-196.0,911.0 -216.0,911.0Q-236.0,911.0 -250.5,897.0Q-265.0,883.0 -265.0,863.0Q-265.0,843.0 -250.5,828.5Q-236.0,814.0 -216.0,814.0Z" transform="translate(2300, 898)"/>
<path d="M35.0,0.0L102.0,151.0L4.0,151.0L21.0,205.0L126.0,205.0L164.0,288.0L-3.0,288.0L19.0,356.0L263.0,356.0L136.0,68.0L325.0,68.0L303.0,0.0L35.0,0.0Z" transform="translate(2575, 868)"/>
<path d="" transform="translate(2950, 868)"/>
<path d="M-22.0,0.0L214.0,714.0L402.0,714.0L377.0,635.0L284.0,635.0L101.0,79.0L298.0,79.0L430.0,474.0L473.0,474.0L716.0,135.0L885.0,635.0L587.0,635.0L571.0,589.0L475.0,589.0L517.0,714.0L1008.0,714.0L770.0,0.0L708.0,0.0L474.0,323.0L368.0,0.0L-22.0,0.0Z" transform="translate(3210, 868)"/>
<path d="M-216.0,756.0Q-260.0,756.0 -291.5,787.5Q-323.0,819.0 -323.0,863.0Q-323.0,907.0 -291.5,938.5Q-260.0,970.0 -216.0,970.0Q-172.0,970.0 -140.5,938.5Q-109.0,907.0 -109.0,863.0Q-109.0,819.0 -140.5,787.5Q-172.0,756.0 -216.0,756.0ZM-216.0,814.0Q-196.0,814.0 -182.0,828.5Q-168.0,843.0 -168.0,863.0Q-168.0,883.0 -182.0,897.0Q-196.0,911.0 -216.0,911.0Q-236.0,911.0 -250.5,897.0Q-265.0,883.0 -265.0,863.0Q-265.0,843.0 -250.5,828.5Q-236.0,814.0 -216.0,814.0Z" transform="translate(3905, 898)"/>
<path d="M-578.0,-241.0L-542.0,-129.0L-480.0,-129.0L-497.0,-181.0L-159.0,-181.0L-6.0,284.0L182.0,284.0L133.0,133.0L71.0,133.0L102.0,228.0L47.0,228.0L-108.0,-241.0L-578.0,-241.0Z" transform="translate(4180, 868)"/>
<path d="M35.0,0.0L102.0,151.0L4.0,151.0L21.0,205.0L126.0,205.0L164.0,288.0L-3.0,288.0L19.0,356.0L263.0,356.0L136.0,68.0L325.0,68.0L303.0,0.0L35.0,0.0Z" transform="translate(4392, 868)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, tai-le, coptic, malayalam, old-permic, canadian-aboriginal, syriac, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `sundanese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni1BA1 (U+1BA1) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+1BA1 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* a (U+0061) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* d (U+0064) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* m (U+006D) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* n (U+006E) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* p (U+0070) contains a short segment L<<169.0,463.0>--<173.0,463.0>>

	* r (U+0072) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* u (U+0075) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ntilde (U+00D1) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* germandbls (U+00DF) contains a short segment B<<382.0,412.0>-<382.0,399.0>-<388.5,388.0>>

	* agrave (U+00E0) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aacute (U+00E1) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* acircumflex (U+00E2) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* atilde (U+00E3) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* adieresis (U+00E4) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aring (U+00E5) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* ntilde (U+00F1) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* ugrave (U+00F9) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* amacron (U+0101) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* abreve (U+0103) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aogonek (U+0105) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* dcaron (U+010F) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<445.0,72.0>--<441.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Nacute (U+0143) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* nacute (U+0144) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* uni0145 (U+0145) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* uni0145 (U+0145) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* uni0146 (U+0146) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Ncaron (U+0147) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ncaron (U+0147) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* ncaron (U+0148) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Eng (U+014A) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Eng (U+014A) contains a short segment L<<582.0,142.0>--<586.0,142.0>>

	* eng (U+014B) contains a short segment L<<170.0,463.0>--<175.0,463.0>>

	* racute (U+0155) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* uni0157 (U+0157) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* rcaron (U+0159) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* umacron (U+016B) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uring (U+016F) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<539.5,-158.5>-<551.0,-156.0>-<559.0,-155.0>>

	* uogonek (U+0173) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Wcircumflex (U+0174) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* uni1B86 (U+1B86) contains a short segment B<<875.5,498.5>-<886.0,482.0>-<886.0,468.0>>

	* uni1B86 (U+1B86) contains a short segment B<<886.0,468.0>-<886.0,449.0>-<874.0,438.0>>

	* uni1B86 (U+1B86) contains a short segment B<<842.0,427.0>-<826.0,427.0>-<814.5,435.0>>

	* uni1B86 (U+1B86) contains a short segment B<<814.5,435.0>-<803.0,443.0>-<791.5,453.5>>

	* uni1BB3 (U+1BB3) contains a short segment B<<498.0,259.5>-<490.0,247.0>-<490.0,236.0>>

	* uni1BB9 (U+1BB9) contains a short segment B<<478.0,259.5>-<470.0,247.0>-<470.0,236.0>>

	* Wgrave (U+1E80) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wacute (U+1E82) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wdieresis (U+1E84) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Euro (U+20AC) contains a short segment B<<184.0,390.0>-<183.0,380.0>-<183.0,371.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,371.0>-<183.0,362.0>-<183.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,352.0>-<183.0,343.0>-<183.0,332.5>>

	* Euro (U+20AC) contains a short segment B<<183.0,332.5>-<183.0,322.0>-<184.0,311.0>>

	* Euro (U+20AC) contains a short segment B<<95.0,311.0>-<94.0,323.0>-<94.0,331.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,331.0>-<94.0,339.0>-<94.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,352.0>-<94.0,363.0>-<94.5,373.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,373.5>-<95.0,384.0>-<95.0,390.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansSundanese-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, tai-le, coptic, malayalam, old-permic, canadian-aboriginal, syriac, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `sundanese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Sundanese SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni1BA1 (U+1BA1) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+1BA1 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=241.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=333.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=451.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=540.0,Y=713.0 (should be at cap-height 714?)

	* three (U+0033): X=135.5,Y=-1.0 (should be at baseline 0?)

	* four (U+0034): X=342.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=460.0,Y=716.0 (should be at cap-height 714?)

	* six (U+0036): X=480.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=91.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=486.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=504.5,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=543.5,Y=712.0 (should be at cap-height 714?)

	* S (U+0053): X=399.0,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=387.0,Y=-1.5 (should be at baseline 0?)

	* e (U+0065): X=421.5,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=126.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=439.5,Y=712.0 (should be at cap-height 714?)

	* section (U+00A7): X=129.0,Y=1.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=486.0,Y=-2.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=504.5,Y=712.0 (should be at cap-height 714?)

	* Oslash (U+00D8): X=489.5,Y=715.0 (should be at cap-height 714?)

	* ae (U+00E6): X=736.5,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=308.0,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=387.0,Y=-1.5 (should be at baseline 0?)

	* egrave (U+00E8): X=421.5,Y=-1.0 (should be at baseline 0?)

	* eacute (U+00E9): X=421.5,Y=-1.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=421.5,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=421.5,Y=-1.0 (should be at baseline 0?)

	* yacute (U+00FD): X=217.0,Y=1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=1.0 (should be at baseline 0?)

	* Cacute (U+0106): X=486.0,Y=-2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=504.5,Y=712.0 (should be at cap-height 714?)

	* cacute (U+0107): X=387.0,Y=-1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=486.0,Y=-2.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=504.5,Y=712.0 (should be at cap-height 714?)

	* cdotaccent (U+010B): X=387.0,Y=-1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=486.0,Y=-2.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=504.5,Y=712.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=387.0,Y=-1.5 (should be at baseline 0?)

	* emacron (U+0113): X=421.5,Y=-1.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=421.5,Y=-1.0 (should be at baseline 0?)

	* ecaron (U+011B): X=421.5,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=543.5,Y=712.0 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=543.5,Y=712.0 (should be at cap-height 714?)

	* uni0122 (U+0122): X=543.5,Y=712.0 (should be at cap-height 714?)

	* Eng (U+014A): X=586.0,Y=1.0 (should be at baseline 0?)

	* oe (U+0153): X=805.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=399.0,Y=712.0 (should be at cap-height 714?)

	* sacute (U+015B): X=126.0,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=399.0,Y=712.0 (should be at cap-height 714?)

	* scedilla (U+015F): X=126.0,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=399.0,Y=712.0 (should be at cap-height 714?)

	* scaron (U+0161): X=126.0,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=217.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=399.0,Y=712.0 (should be at cap-height 714?)

	* uni0219 (U+0219): X=126.0,Y=-2.0 (should be at baseline 0?)

	* uni1BB0 (U+1BB0): X=419.0,Y=-2.0 (should be at baseline 0?)

	* uni1BB0 (U+1BB0): X=419.0,Y=716.0 (should be at cap-height 714?)

	* uni1BB0 (U+1BB0): X=419.0,Y=-2.0 (should be at baseline 0?)

	* uni1BB8 (U+1BB8): X=360.5,Y=-2.0 (should be at baseline 0?)

	* uni1BBC (U+1BBC): X=1134.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=350.5,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=217.0,Y=1.0 (should be at baseline 0?)

	* Euro (U+20AC): X=471.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<197.0,111.0>--<197.0,106.0>>

	* at (U+0040) contains a short segment B<<626.0,295.0>-<625.0,281.0>-<625.0,272.0>>

	* at (U+0040) contains a short segment B<<625.0,272.0>-<625.0,263.0>-<625.0,260.0>>

	* M (U+004D) contains a short segment L<<201.0,590.0>--<197.0,590.0>>

	* M (U+004D) contains a short segment L<<458.0,150.0>--<462.0,150.0>>

	* N (U+004E) contains a short segment L<<200.0,564.0>--<196.0,564.0>>

	* N (U+004E) contains a short segment L<<587.0,154.0>--<590.0,154.0>>

	* Q (U+0051) contains a short segment B<<412.0,-10.0>-<408.0,-10.0>-<403.5,-10.0>>

	* Q (U+0051) contains a short segment B<<403.5,-10.0>-<399.0,-10.0>-<395.0,-10.0>>

	* a (U+0061) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* d (U+0064) contains a short segment L<<427.0,71.0>--<422.0,71.0>>

	* m (U+006D) contains a short segment L<<193.0,470.0>--<199.0,470.0>>

	* n (U+006E) contains a short segment L<<193.0,470.0>--<199.0,470.0>>

	* p (U+0070) contains a short segment L<<197.0,470.0>--<203.0,470.0>>

	* r (U+0072) contains a short segment L<<192.0,447.0>--<198.0,447.0>>

	* u (U+0075) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* Ntilde (U+00D1) contains a short segment L<<200.0,564.0>--<196.0,564.0>>

	* Ntilde (U+00D1) contains a short segment L<<587.0,154.0>--<590.0,154.0>>

	* germandbls (U+00DF) contains a short segment B<<430.0,409.0>-<430.0,396.0>-<438.5,385.5>>

	* agrave (U+00E0) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aacute (U+00E1) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* acircumflex (U+00E2) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* atilde (U+00E3) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* adieresis (U+00E4) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aring (U+00E5) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* ntilde (U+00F1) contains a short segment L<<193.0,470.0>--<199.0,470.0>>

	* ugrave (U+00F9) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* uacute (U+00FA) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* ucircumflex (U+00FB) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* udieresis (U+00FC) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* amacron (U+0101) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* abreve (U+0103) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aogonek (U+0105) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* dcaron (U+010F) contains a short segment L<<427.0,71.0>--<422.0,71.0>>

	* dcroat (U+0111) contains a short segment L<<427.0,71.0>--<422.0,71.0>>

	* Nacute (U+0143) contains a short segment L<<200.0,564.0>--<196.0,564.0>>

	* Nacute (U+0143) contains a short segment L<<587.0,154.0>--<590.0,154.0>>

	* nacute (U+0144) contains a short segment L<<193.0,470.0>--<199.0,470.0>>

	* uni0145 (U+0145) contains a short segment L<<200.0,564.0>--<196.0,564.0>>

	* uni0145 (U+0145) contains a short segment L<<587.0,154.0>--<590.0,154.0>>

	* uni0146 (U+0146) contains a short segment L<<193.0,470.0>--<199.0,470.0>>

	* Ncaron (U+0147) contains a short segment L<<200.0,564.0>--<196.0,564.0>>

	* Ncaron (U+0147) contains a short segment L<<587.0,154.0>--<590.0,154.0>>

	* ncaron (U+0148) contains a short segment L<<193.0,470.0>--<199.0,470.0>>

	* Eng (U+014A) contains a short segment L<<200.0,564.0>--<196.0,564.0>>

	* Eng (U+014A) contains a short segment L<<587.0,214.0>--<590.0,214.0>>

	* eng (U+014B) contains a short segment L<<193.0,470.0>--<200.0,470.0>>

	* racute (U+0155) contains a short segment L<<192.0,447.0>--<198.0,447.0>>

	* uni0157 (U+0157) contains a short segment L<<192.0,447.0>--<198.0,447.0>>

	* rcaron (U+0159) contains a short segment L<<192.0,447.0>--<198.0,447.0>>

	* umacron (U+016B) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* ubreve (U+016D) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* uring (U+016F) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* Uogonek (U+0172) contains a short segment B<<548.0,-153.0>-<561.0,-150.0>-<571.0,-148.0>>

	* uogonek (U+0173) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* uni1B85 (U+1B85) contains a short segment B<<567.0,254.5>-<559.0,246.0>-<559.0,238.0>>

	* uni1B86 (U+1B86) contains a short segment B<<842.0,409.0>-<824.0,409.0>-<811.0,417.0>>

	* uni1B86 (U+1B86) contains a short segment B<<811.0,417.0>-<798.0,425.0>-<785.0,436.0>>

	* uni1BB3 (U+1BB3) contains a short segment B<<567.0,254.5>-<559.0,246.0>-<559.0,238.0>>

	* uni1BB6 (U+1BB6) contains a short segment B<<457.0,254.5>-<449.0,246.0>-<449.0,238.0>>

	* uni1BB9 (U+1BB9) contains a short segment B<<541.0,254.5>-<533.0,246.0>-<533.0,238.0>>

	* Euro (U+20AC) contains a short segment B<<213.0,383.0>-<213.0,377.0>-<212.5,369.0>>

	* Euro (U+20AC) contains a short segment B<<212.5,369.0>-<212.0,361.0>-<212.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<212.0,352.0>-<212.0,344.0>-<212.0,335.0>>

	* Euro (U+20AC) contains a short segment B<<212.0,335.0>-<212.0,326.0>-<213.0,317.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wacute (U+1E82): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wcircumflex (U+0174): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wdieresis (U+1E84): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wgrave (U+1E80): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 38 | 473 | 25 | 404 | 0 |
| 0% | 1% | 4% | 50% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
