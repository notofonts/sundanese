## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansSundanese/googlefonts/ttf', 'fonts/NotoSansSundanese/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Sundanese' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[9] NotoSansSundanese-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
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

	* 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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

	* 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
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

	* 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[8] NotoSansSundanese-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Sundanese Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
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

	* 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[8] NotoSansSundanese-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
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



<pre>Got     : uni1B98=0+970|uni1BA2=0@-179,0+0|uni1B80=0@-275,30+0|uni1BA7=0+375|space=4+260|uni1B98=5+970|uni1BA3=5@80,0+0|uni1B80=5@-275,30+0|uni1BA7=5+375|space=9+260|uni1B98=10+970|uni1B80=10@-275,30+0|uni1BA1=10+424|uni1BA7=10+375</pre>



<pre>                                                                                                                                                                                                                     ^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4979 2437" transform="matrix(1 0 0 -1 0 0)">
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
<path d="M35.0,0.0L102.0,151.0L4.0,151.0L21.0,205.0L126.0,205.0L164.0,288.0L-3.0,288.0L19.0,356.0L263.0,356.0L136.0,68.0L325.0,68.0L303.0,0.0L35.0,0.0Z" transform="translate(4604, 868)"/>
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
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

	* 66 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[10] NotoSansSundanese-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Sundanese SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
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

	* 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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

	* 57 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wacute (U+1E82): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wcircumflex (U+0174): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wdieresis (U+1E84): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818 

	* Wgrave (U+1E80): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] NotoSansSundanese[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 13 | 29 | 567 | 32 | 517 | 0 |
| 0% | 1% | 2% | 49% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
