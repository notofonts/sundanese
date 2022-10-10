## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansSundanese/googlefonts/ttf', 'fonts/NotoSansSundanese/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[8] NotoSansSundanese-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/sundanese.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansSundanese/googlefonts/ttf/NotoSansSundanese-Bold.ttf);}
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

<li>Shaping did not match: <span class="tf">ᮓᮥᮑ ᮒᮨᮂᮞᮤᮖᮒ᮪ᮔ</span> (Attachments and spacing)</li>


<pre>Expected: uni1B93=0+712|uni1BA5=0@118,0+0|uni1B91=2+1077|space=3+260|uni1B92=4+861|uni1BA8=4@-176,30+0|uni1B82=4+387|uni1B9E=7+797|uni1BA4=7@-116,30+0|uni1B96=9+793|uni1B92=10+861|uni1BAA=10+264|uni1B94=12+721</pre>



<pre>Got     : uni1B93=0+890|uni1BA5=0@-60,0+0|uni1B91=2+1073|space=3+260|uni1B92=4+978|uni1BA8=4@-293,30+0|uni1B82=4+425|uni1B9E=7+860|uni1BA4=7@-179,30+0|uni1B96=9+849|uni1B92=10+978|uni1BAA=10+290|uni1B94=12+770</pre>



<pre>                    ^^^           ^^^                  ^                        ++            ^^^                ^^^           ^^^             ^^                ^ +             ++             ^^             ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7373 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L672.0,714.0L625.0,555.0L347.0,555.0L217.0,163.0L367.0,163.0L454.0,419.0L714.0,419.0L860.0,0.0L665.0,0.0L575.0,257.0L493.0,0.0L-22.0,0.0Z"  transform="translate(0, 868)"/>
<path d="M-505.0,-248.0L-452.0,-111.0L-554.0,-111.0L-554.0,-40.0L-342.0,-40.0L-424.0,-248.0L-505.0,-248.0Z"  transform="translate(830, 868)"/>
<path d="M35.0,0.0L218.0,555.0L10.0,555.0L63.0,714.0L455.0,714.0L272.0,159.0L401.0,159.0L506.0,474.0L645.0,474.0L788.0,245.0L896.0,565.0L728.0,565.0L712.0,519.0L530.0,519.0L593.0,714.0L1130.0,714.0L892.0,0.0L740.0,0.0L611.0,216.0L540.0,0.0L35.0,0.0Z"  transform="translate(890, 868)"/>
<path d=""  transform="translate(1963, 868)"/>
<path d="M13.0,0.0L140.0,377.0L9.0,377.0L62.0,536.0L380.0,536.0L253.0,159.0L360.0,159.0L540.0,714.0L727.0,714.0L669.0,536.0L992.0,536.0L816.0,0.0L628.0,0.0L751.0,377.0L617.0,377.0L493.0,0.0L13.0,0.0Z"  transform="translate(2223, 868)"/>
<path d="M-291.0,756.0L-426.0,990.0L-325.0,990.0L-248.0,848.0L-171.0,990.0L-70.0,990.0L-205.0,756.0L-291.0,756.0Z"  transform="translate(2908, 898)"/>
<path d="M81.0,0.0L-12.0,284.0L90.0,284.0L183.0,0.0L81.0,0.0ZM246.0,0.0L153.0,284.0L255.0,284.0L348.0,0.0L246.0,0.0Z"  transform="translate(3201, 868)"/>
<path d="M484.0,0.0L564.0,238.0L464.0,238.0L517.0,397.0L617.0,397.0L671.0,555.0L472.0,555.0L525.0,714.0L909.0,714.0L803.0,397.0L893.0,397.0L840.0,238.0L750.0,238.0L671.0,0.0L484.0,0.0ZM42.0,0.0L122.0,238.0L23.0,238.0L76.0,397.0L175.0,397.0L229.0,555.0L28.0,555.0L81.0,714.0L467.0,714.0L361.0,397.0L451.0,397.0L398.0,238.0L308.0,238.0L229.0,0.0L42.0,0.0Z"  transform="translate(3626, 868)"/>
<path d="M-246.0,742.0L-417.0,788.0L-399.0,858.0L-307.0,845.0L-271.0,927.0L-397.0,927.0L-397.0,1005.0L-146.0,1005.0L-246.0,742.0Z"  transform="translate(4307, 898)"/>
<path d="M58.0,0.0L240.0,555.0L45.0,555.0L98.0,714.0L473.0,714.0L290.0,163.0L544.0,163.0L726.0,714.0L906.0,714.0L670.0,0.0L58.0,0.0Z"  transform="translate(4486, 868)"/>
<path d="M13.0,0.0L140.0,377.0L9.0,377.0L62.0,536.0L380.0,536.0L253.0,159.0L360.0,159.0L540.0,714.0L727.0,714.0L669.0,536.0L992.0,536.0L816.0,0.0L628.0,0.0L751.0,377.0L617.0,377.0L493.0,0.0L13.0,0.0Z"  transform="translate(5335, 868)"/>
<path d="M127.0,-153.0Q98.0,-153.0 70.0,-146.0Q42.0,-139.0 23.5,-121.0Q5.0,-103.0 5.0,-71.0Q5.0,-33.0 30.5,-6.0Q56.0,21.0 91.0,49.0Q120.0,72.0 139.0,89.5Q158.0,107.0 158.0,123.0Q158.0,143.0 131.5,153.0Q105.0,163.0 25.0,163.0L-14.0,163.0L2.0,211.0L81.0,271.0L-20.0,271.0L8.0,349.0L239.0,349.0L239.0,302.0L143.0,222.0Q166.0,219.0 190.5,208.0Q215.0,197.0 231.5,176.5Q248.0,156.0 248.0,124.0Q248.0,88.0 228.0,62.0Q208.0,36.0 182.0,16.0Q151.0,-9.0 127.5,-27.5Q104.0,-46.0 104.0,-60.0Q104.0,-78.0 146.0,-78.0Q172.0,-78.0 196.5,-69.5Q221.0,-61.0 236.0,-53.0L258.0,-117.0Q230.0,-133.0 195.5,-143.0Q161.0,-153.0 127.0,-153.0Z"  transform="translate(6313, 868)"/>
<path d="M143.0,0.0L326.0,555.0L50.0,555.0L102.0,714.0L569.0,714.0L388.0,169.0L770.0,169.0L715.0,0.0L143.0,0.0Z"  transform="translate(6603, 868)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6733 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L672.0,714.0L625.0,555.0L347.0,555.0L217.0,163.0L367.0,163.0L454.0,419.0L714.0,419.0L860.0,0.0L665.0,0.0L575.0,257.0L493.0,0.0L-22.0,0.0Z"  transform="translate(0, 868)"/>
<path d="M-505.0,-248.0L-452.0,-111.0L-554.0,-111.0L-554.0,-40.0L-342.0,-40.0L-424.0,-248.0L-505.0,-248.0Z"  transform="translate(830, 868)"/>
<path d="M35.0,0.0L218.0,555.0L10.0,555.0L63.0,714.0L455.0,714.0L272.0,159.0L401.0,159.0L506.0,474.0L645.0,474.0L788.0,245.0L896.0,565.0L728.0,565.0L712.0,519.0L530.0,519.0L593.0,714.0L1130.0,714.0L892.0,0.0L740.0,0.0L611.0,216.0L540.0,0.0L35.0,0.0Z"  transform="translate(712, 868)"/>
<path d=""  transform="translate(1789, 868)"/>
<path d="M13.0,0.0L140.0,377.0L9.0,377.0L62.0,536.0L380.0,536.0L253.0,159.0L360.0,159.0L540.0,714.0L727.0,714.0L669.0,536.0L992.0,536.0L816.0,0.0L628.0,0.0L751.0,377.0L617.0,377.0L493.0,0.0L13.0,0.0Z"  transform="translate(2049, 868)"/>
<path d="M-291.0,756.0L-426.0,990.0L-325.0,990.0L-248.0,848.0L-171.0,990.0L-70.0,990.0L-205.0,756.0L-291.0,756.0Z"  transform="translate(2734, 898)"/>
<path d="M81.0,0.0L-12.0,284.0L90.0,284.0L183.0,0.0L81.0,0.0ZM246.0,0.0L153.0,284.0L255.0,284.0L348.0,0.0L246.0,0.0Z"  transform="translate(2910, 868)"/>
<path d="M484.0,0.0L564.0,238.0L464.0,238.0L517.0,397.0L617.0,397.0L671.0,555.0L472.0,555.0L525.0,714.0L909.0,714.0L803.0,397.0L893.0,397.0L840.0,238.0L750.0,238.0L671.0,0.0L484.0,0.0ZM42.0,0.0L122.0,238.0L23.0,238.0L76.0,397.0L175.0,397.0L229.0,555.0L28.0,555.0L81.0,714.0L467.0,714.0L361.0,397.0L451.0,397.0L398.0,238.0L308.0,238.0L229.0,0.0L42.0,0.0Z"  transform="translate(3297, 868)"/>
<path d="M-246.0,742.0L-417.0,788.0L-399.0,858.0L-307.0,845.0L-271.0,927.0L-397.0,927.0L-397.0,1005.0L-146.0,1005.0L-246.0,742.0Z"  transform="translate(3978, 898)"/>
<path d="M58.0,0.0L240.0,555.0L45.0,555.0L98.0,714.0L473.0,714.0L290.0,163.0L544.0,163.0L726.0,714.0L906.0,714.0L670.0,0.0L58.0,0.0Z"  transform="translate(4094, 868)"/>
<path d="M13.0,0.0L140.0,377.0L9.0,377.0L62.0,536.0L380.0,536.0L253.0,159.0L360.0,159.0L540.0,714.0L727.0,714.0L669.0,536.0L992.0,536.0L816.0,0.0L628.0,0.0L751.0,377.0L617.0,377.0L493.0,0.0L13.0,0.0Z"  transform="translate(4887, 868)"/>
<path d="M127.0,-153.0Q98.0,-153.0 70.0,-146.0Q42.0,-139.0 23.5,-121.0Q5.0,-103.0 5.0,-71.0Q5.0,-33.0 30.5,-6.0Q56.0,21.0 91.0,49.0Q120.0,72.0 139.0,89.5Q158.0,107.0 158.0,123.0Q158.0,143.0 131.5,153.0Q105.0,163.0 25.0,163.0L-14.0,163.0L2.0,211.0L81.0,271.0L-20.0,271.0L8.0,349.0L239.0,349.0L239.0,302.0L143.0,222.0Q166.0,219.0 190.5,208.0Q215.0,197.0 231.5,176.5Q248.0,156.0 248.0,124.0Q248.0,88.0 228.0,62.0Q208.0,36.0 182.0,16.0Q151.0,-9.0 127.5,-27.5Q104.0,-46.0 104.0,-60.0Q104.0,-78.0 146.0,-78.0Q172.0,-78.0 196.5,-69.5Q221.0,-61.0 236.0,-53.0L258.0,-117.0Q230.0,-133.0 195.5,-143.0Q161.0,-153.0 127.0,-153.0Z"  transform="translate(5748, 868)"/>
<path d="M143.0,0.0L326.0,555.0L50.0,555.0L102.0,714.0L569.0,714.0L388.0,169.0L770.0,169.0L715.0,0.0L143.0,0.0Z"  transform="translate(6012, 868)"/>
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* And 63 more.

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

	* And 63 more.

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

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[7] NotoSansSundanese-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/sundanese.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansSundanese/googlefonts/ttf/NotoSansSundanese-Medium.ttf);}
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

<li>Shaping did not match: <span class="tf">ᮓᮥᮑ ᮒᮨᮂᮞᮤᮖᮒ᮪ᮔ</span> (Attachments and spacing)</li>


<pre>Expected: uni1B93=0+712|uni1BA5=0@118,0+0|uni1B91=2+1077|space=3+260|uni1B92=4+861|uni1BA8=4@-176,30+0|uni1B82=4+387|uni1B9E=7+797|uni1BA4=7@-116,30+0|uni1B96=9+793|uni1B92=10+861|uni1BAA=10+264|uni1B94=12+721</pre>



<pre>Got     : uni1B93=0+740|uni1BA5=0@90,0+0|uni1B91=2+1076|space=3+260|uni1B92=4+879|uni1BA8=4@-194,30+0|uni1B82=4+393|uni1B9E=7+807|uni1BA4=7@-126,30+0|uni1B96=9+802|uni1B92=10+879|uni1BAA=10+268|uni1B94=12+729</pre>



<pre>                     ^^           ^^^                  ^                        ^^             ^^                 ^^           ^^              ^                 ^^^             ^^              ^              ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6833 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L538.0,714.0L509.0,622.0L294.0,622.0L119.0,92.0L317.0,92.0L430.0,415.0L549.0,415.0L693.0,0.0L582.0,0.0L488.0,280.0L397.0,0.0L-22.0,0.0Z"  transform="translate(0, 868)"/>
<path d="M-485.0,-248.0L-428.0,-103.0L-541.0,-103.0L-541.0,-51.0L-346.0,-51.0L-424.0,-248.0L-485.0,-248.0Z"  transform="translate(830, 868)"/>
<path d="M76.0,0.0L282.0,622.0L66.0,622.0L96.0,714.0L423.0,714.0L217.0,92.0L404.0,92.0L531.0,474.0L589.0,474.0L817.0,152.0L976.0,624.0L698.0,624.0L682.0,578.0L573.0,578.0L618.0,714.0L1117.0,714.0L879.0,0.0L802.0,0.0L585.0,306.0L484.0,0.0L76.0,0.0Z"  transform="translate(740, 868)"/>
<path d=""  transform="translate(1816, 868)"/>
<path d="M30.0,0.0L180.0,444.0L32.0,444.0L62.0,536.0L321.0,536.0L171.0,92.0L329.0,92.0L532.0,714.0L643.0,714.0L585.0,536.0L874.0,536.0L698.0,0.0L586.0,0.0L731.0,444.0L555.0,444.0L409.0,0.0L30.0,0.0Z"  transform="translate(2076, 868)"/>
<path d="M-266.0,756.0L-392.0,960.0L-317.0,960.0L-240.0,830.0L-163.0,960.0L-87.0,960.0L-213.0,756.0L-266.0,756.0Z"  transform="translate(2761, 898)"/>
<path d="M98.0,0.0L-1.0,284.0L71.0,284.0L170.0,0.0L98.0,0.0ZM238.0,0.0L139.0,284.0L211.0,284.0L310.0,0.0L238.0,0.0Z"  transform="translate(2955, 868)"/>
<path d="M494.0,0.0L597.0,305.0L477.0,305.0L507.0,397.0L627.0,397.0L704.0,622.0L478.0,622.0L508.0,714.0L843.0,714.0L737.0,397.0L850.0,397.0L820.0,305.0L707.0,305.0L605.0,0.0L494.0,0.0ZM84.0,0.0L187.0,305.0L67.0,305.0L97.0,397.0L217.0,397.0L294.0,622.0L68.0,622.0L98.0,714.0L433.0,714.0L327.0,397.0L440.0,397.0L410.0,305.0L297.0,305.0L195.0,0.0L84.0,0.0Z"  transform="translate(3348, 868)"/>
<path d="M-231.0,752.0L-377.0,791.0L-366.0,842.0L-269.0,828.0L-233.0,919.0L-364.0,919.0L-364.0,971.0L-147.0,971.0L-231.0,752.0Z"  transform="translate(4029, 898)"/>
<path d="M88.0,0.0L292.0,622.0L70.0,622.0L101.0,714.0L435.0,714.0L229.0,92.0L524.0,92.0L731.0,714.0L841.0,714.0L605.0,0.0L88.0,0.0Z"  transform="translate(4155, 868)"/>
<path d="M30.0,0.0L180.0,444.0L32.0,444.0L62.0,536.0L321.0,536.0L171.0,92.0L329.0,92.0L532.0,714.0L643.0,714.0L585.0,536.0L874.0,536.0L698.0,0.0L586.0,0.0L731.0,444.0L555.0,444.0L409.0,0.0L30.0,0.0Z"  transform="translate(4957, 868)"/>
<path d="M110.0,-131.0Q67.0,-131.0 34.5,-116.0Q2.0,-101.0 2.0,-60.0Q2.0,-29.0 25.0,-5.0Q48.0,19.0 77.0,43.0Q103.0,65.0 123.5,85.5Q144.0,106.0 144.0,126.0Q144.0,158.0 111.0,170.0Q78.0,182.0 14.0,182.0L-12.0,182.0L-2.0,213.0L79.0,282.0L-20.0,282.0L-3.0,332.0L195.0,332.0L195.0,307.0L97.0,222.0Q147.0,217.0 179.0,194.0Q211.0,171.0 211.0,127.0Q211.0,87.0 190.5,65.5Q170.0,44.0 147.0,23.0Q120.0,-1.0 96.5,-19.5Q73.0,-38.0 73.0,-53.0Q73.0,-64.0 82.5,-70.5Q92.0,-77.0 116.0,-77.0Q147.0,-77.0 170.5,-68.0Q194.0,-59.0 204.0,-53.0L222.0,-103.0Q199.0,-117.0 167.5,-124.0Q136.0,-131.0 110.0,-131.0Z"  transform="translate(5836, 868)"/>
<path d="M160.0,0.0L365.0,622.0L72.0,622.0L102.0,714.0L509.0,714.0L304.0,93.0L695.0,93.0L664.0,0.0L160.0,0.0Z"  transform="translate(6104, 868)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6733 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L538.0,714.0L509.0,622.0L294.0,622.0L119.0,92.0L317.0,92.0L430.0,415.0L549.0,415.0L693.0,0.0L582.0,0.0L488.0,280.0L397.0,0.0L-22.0,0.0Z"  transform="translate(0, 868)"/>
<path d="M-485.0,-248.0L-428.0,-103.0L-541.0,-103.0L-541.0,-51.0L-346.0,-51.0L-424.0,-248.0L-485.0,-248.0Z"  transform="translate(830, 868)"/>
<path d="M76.0,0.0L282.0,622.0L66.0,622.0L96.0,714.0L423.0,714.0L217.0,92.0L404.0,92.0L531.0,474.0L589.0,474.0L817.0,152.0L976.0,624.0L698.0,624.0L682.0,578.0L573.0,578.0L618.0,714.0L1117.0,714.0L879.0,0.0L802.0,0.0L585.0,306.0L484.0,0.0L76.0,0.0Z"  transform="translate(712, 868)"/>
<path d=""  transform="translate(1789, 868)"/>
<path d="M30.0,0.0L180.0,444.0L32.0,444.0L62.0,536.0L321.0,536.0L171.0,92.0L329.0,92.0L532.0,714.0L643.0,714.0L585.0,536.0L874.0,536.0L698.0,0.0L586.0,0.0L731.0,444.0L555.0,444.0L409.0,0.0L30.0,0.0Z"  transform="translate(2049, 868)"/>
<path d="M-266.0,756.0L-392.0,960.0L-317.0,960.0L-240.0,830.0L-163.0,960.0L-87.0,960.0L-213.0,756.0L-266.0,756.0Z"  transform="translate(2734, 898)"/>
<path d="M98.0,0.0L-1.0,284.0L71.0,284.0L170.0,0.0L98.0,0.0ZM238.0,0.0L139.0,284.0L211.0,284.0L310.0,0.0L238.0,0.0Z"  transform="translate(2910, 868)"/>
<path d="M494.0,0.0L597.0,305.0L477.0,305.0L507.0,397.0L627.0,397.0L704.0,622.0L478.0,622.0L508.0,714.0L843.0,714.0L737.0,397.0L850.0,397.0L820.0,305.0L707.0,305.0L605.0,0.0L494.0,0.0ZM84.0,0.0L187.0,305.0L67.0,305.0L97.0,397.0L217.0,397.0L294.0,622.0L68.0,622.0L98.0,714.0L433.0,714.0L327.0,397.0L440.0,397.0L410.0,305.0L297.0,305.0L195.0,0.0L84.0,0.0Z"  transform="translate(3297, 868)"/>
<path d="M-231.0,752.0L-377.0,791.0L-366.0,842.0L-269.0,828.0L-233.0,919.0L-364.0,919.0L-364.0,971.0L-147.0,971.0L-231.0,752.0Z"  transform="translate(3978, 898)"/>
<path d="M88.0,0.0L292.0,622.0L70.0,622.0L101.0,714.0L435.0,714.0L229.0,92.0L524.0,92.0L731.0,714.0L841.0,714.0L605.0,0.0L88.0,0.0Z"  transform="translate(4094, 868)"/>
<path d="M30.0,0.0L180.0,444.0L32.0,444.0L62.0,536.0L321.0,536.0L171.0,92.0L329.0,92.0L532.0,714.0L643.0,714.0L585.0,536.0L874.0,536.0L698.0,0.0L586.0,0.0L731.0,444.0L555.0,444.0L409.0,0.0L30.0,0.0Z"  transform="translate(4887, 868)"/>
<path d="M110.0,-131.0Q67.0,-131.0 34.5,-116.0Q2.0,-101.0 2.0,-60.0Q2.0,-29.0 25.0,-5.0Q48.0,19.0 77.0,43.0Q103.0,65.0 123.5,85.5Q144.0,106.0 144.0,126.0Q144.0,158.0 111.0,170.0Q78.0,182.0 14.0,182.0L-12.0,182.0L-2.0,213.0L79.0,282.0L-20.0,282.0L-3.0,332.0L195.0,332.0L195.0,307.0L97.0,222.0Q147.0,217.0 179.0,194.0Q211.0,171.0 211.0,127.0Q211.0,87.0 190.5,65.5Q170.0,44.0 147.0,23.0Q120.0,-1.0 96.5,-19.5Q73.0,-38.0 73.0,-53.0Q73.0,-64.0 82.5,-70.5Q92.0,-77.0 116.0,-77.0Q147.0,-77.0 170.5,-68.0Q194.0,-59.0 204.0,-53.0L222.0,-103.0Q199.0,-117.0 167.5,-124.0Q136.0,-131.0 110.0,-131.0Z"  transform="translate(5748, 868)"/>
<path d="M160.0,0.0L365.0,622.0L72.0,622.0L102.0,714.0L509.0,714.0L304.0,93.0L695.0,93.0L664.0,0.0L160.0,0.0Z"  transform="translate(6012, 868)"/>
</svg>


</div> [code: shaping-regression]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* And 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[5] NotoSansSundanese-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* And 66 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[9] NotoSansSundanese-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/sundanese.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansSundanese/googlefonts/ttf/NotoSansSundanese-SemiBold.ttf);}
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

<li>Shaping did not match: <span class="tf">ᮓᮥᮑ ᮒᮨᮂᮞᮤᮖᮒ᮪ᮔ</span> (Attachments and spacing)</li>


<pre>Expected: uni1B93=0+712|uni1BA5=0@118,0+0|uni1B91=2+1077|space=3+260|uni1B92=4+861|uni1BA8=4@-176,30+0|uni1B82=4+387|uni1B9E=7+797|uni1BA4=7@-116,30+0|uni1B96=9+793|uni1B92=10+861|uni1BAA=10+264|uni1B94=12+721</pre>



<pre>Got     : uni1B93=0+810|uni1BA5=0@20,0+0|uni1B91=2+1075|space=3+260|uni1B92=4+925|uni1BA8=4@-240,30+0|uni1B82=4+408|uni1B9E=7+832|uni1BA4=7@-151,30+0|uni1B96=9+824|uni1B92=10+925|uni1BAA=10+278|uni1B94=12+748</pre>



<pre>                    ^ ^           ^^^                  ^                       ^^^            ^^^                ^ +           ^^^              +                ^^^            ^^^             ^^             ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7085 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L600.0,714.0L563.0,591.0L319.0,591.0L165.0,125.0L340.0,125.0L441.0,417.0L626.0,417.0L771.0,0.0L621.0,0.0L529.0,269.0L442.0,0.0L-22.0,0.0Z"  transform="translate(0, 868)"/>
<path d="M-494.0,-248.0L-439.0,-106.0L-547.0,-106.0L-547.0,-46.0L-344.0,-46.0L-424.0,-248.0L-494.0,-248.0Z"  transform="translate(830, 868)"/>
<path d="M57.0,0.0L252.0,591.0L40.0,591.0L81.0,714.0L438.0,714.0L243.0,123.0L402.0,123.0L520.0,474.0L615.0,474.0L803.0,195.0L939.0,597.0L712.0,597.0L696.0,551.0L553.0,551.0L607.0,714.0L1123.0,714.0L885.0,0.0L773.0,0.0L597.0,264.0L510.0,0.0L57.0,0.0Z"  transform="translate(810, 868)"/>
<path d=""  transform="translate(1885, 868)"/>
<path d="M22.0,0.0L161.0,413.0L21.0,413.0L62.0,536.0L348.0,536.0L209.0,123.0L343.0,123.0L535.0,714.0L682.0,714.0L624.0,536.0L929.0,536.0L753.0,0.0L605.0,0.0L740.0,413.0L584.0,413.0L448.0,0.0L22.0,0.0Z"  transform="translate(2145, 868)"/>
<path d="M-277.0,756.0L-408.0,974.0L-320.0,974.0L-243.0,839.0L-166.0,974.0L-79.0,974.0L-210.0,756.0L-277.0,756.0Z"  transform="translate(2830, 898)"/>
<path d="M90.0,0.0L-6.0,284.0L80.0,284.0L176.0,0.0L90.0,0.0ZM241.0,0.0L145.0,284.0L232.0,284.0L328.0,0.0L241.0,0.0Z"  transform="translate(3070, 868)"/>
<path d="M489.0,0.0L582.0,274.0L471.0,274.0L512.0,397.0L622.0,397.0L689.0,591.0L475.0,591.0L516.0,714.0L874.0,714.0L768.0,397.0L870.0,397.0L829.0,274.0L727.0,274.0L636.0,0.0L489.0,0.0ZM65.0,0.0L157.0,274.0L46.0,274.0L87.0,397.0L198.0,397.0L264.0,591.0L49.0,591.0L90.0,714.0L449.0,714.0L343.0,397.0L445.0,397.0L404.0,274.0L302.0,274.0L211.0,0.0L65.0,0.0Z"  transform="translate(3478, 868)"/>
<path d="M-238.0,747.0L-395.0,789.0L-381.0,849.0L-287.0,836.0L-251.0,922.0L-379.0,922.0L-379.0,987.0L-146.0,987.0L-238.0,747.0Z"  transform="translate(4159, 898)"/>
<path d="M74.0,0.0L268.0,591.0L59.0,591.0L99.0,714.0L453.0,714.0L258.0,125.0L533.0,125.0L729.0,714.0L871.0,714.0L635.0,0.0L74.0,0.0Z"  transform="translate(4310, 868)"/>
<path d="M22.0,0.0L161.0,413.0L21.0,413.0L62.0,536.0L348.0,536.0L209.0,123.0L343.0,123.0L535.0,714.0L682.0,714.0L624.0,536.0L929.0,536.0L753.0,0.0L605.0,0.0L740.0,413.0L584.0,413.0L448.0,0.0L22.0,0.0Z"  transform="translate(5134, 868)"/>
<path d="M118.0,-141.0Q89.0,-141.0 63.0,-134.5Q37.0,-128.0 20.5,-111.5Q4.0,-95.0 4.0,-65.0Q4.0,-31.0 28.0,-5.5Q52.0,20.0 83.0,46.0Q110.0,68.0 130.0,87.5Q150.0,107.0 150.0,125.0Q150.0,151.0 120.0,162.0Q90.0,173.0 19.0,173.0L-13.0,173.0L0.0,212.0L80.0,277.0L-20.0,277.0L2.0,340.0L216.0,340.0L216.0,305.0L118.0,222.0Q161.0,217.0 194.5,194.5Q228.0,172.0 228.0,125.0Q228.0,88.0 207.5,64.0Q187.0,40.0 163.0,20.0Q134.0,-5.0 110.5,-23.5Q87.0,-42.0 87.0,-56.0Q87.0,-78.0 130.0,-78.0Q159.0,-78.0 183.0,-69.0Q207.0,-60.0 219.0,-53.0L239.0,-109.0Q214.0,-124.0 180.5,-132.5Q147.0,-141.0 118.0,-141.0Z"  transform="translate(6059, 868)"/>
<path d="M152.0,0.0L347.0,591.0L62.0,591.0L102.0,714.0L537.0,714.0L343.0,128.0L730.0,128.0L688.0,0.0L152.0,0.0Z"  transform="translate(6337, 868)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6733 2437" transform="matrix(1 0 0 -1 0 0)">
<path d="M-22.0,0.0L214.0,714.0L600.0,714.0L563.0,591.0L319.0,591.0L165.0,125.0L340.0,125.0L441.0,417.0L626.0,417.0L771.0,0.0L621.0,0.0L529.0,269.0L442.0,0.0L-22.0,0.0Z"  transform="translate(0, 868)"/>
<path d="M-494.0,-248.0L-439.0,-106.0L-547.0,-106.0L-547.0,-46.0L-344.0,-46.0L-424.0,-248.0L-494.0,-248.0Z"  transform="translate(830, 868)"/>
<path d="M57.0,0.0L252.0,591.0L40.0,591.0L81.0,714.0L438.0,714.0L243.0,123.0L402.0,123.0L520.0,474.0L615.0,474.0L803.0,195.0L939.0,597.0L712.0,597.0L696.0,551.0L553.0,551.0L607.0,714.0L1123.0,714.0L885.0,0.0L773.0,0.0L597.0,264.0L510.0,0.0L57.0,0.0Z"  transform="translate(712, 868)"/>
<path d=""  transform="translate(1789, 868)"/>
<path d="M22.0,0.0L161.0,413.0L21.0,413.0L62.0,536.0L348.0,536.0L209.0,123.0L343.0,123.0L535.0,714.0L682.0,714.0L624.0,536.0L929.0,536.0L753.0,0.0L605.0,0.0L740.0,413.0L584.0,413.0L448.0,0.0L22.0,0.0Z"  transform="translate(2049, 868)"/>
<path d="M-277.0,756.0L-408.0,974.0L-320.0,974.0L-243.0,839.0L-166.0,974.0L-79.0,974.0L-210.0,756.0L-277.0,756.0Z"  transform="translate(2734, 898)"/>
<path d="M90.0,0.0L-6.0,284.0L80.0,284.0L176.0,0.0L90.0,0.0ZM241.0,0.0L145.0,284.0L232.0,284.0L328.0,0.0L241.0,0.0Z"  transform="translate(2910, 868)"/>
<path d="M489.0,0.0L582.0,274.0L471.0,274.0L512.0,397.0L622.0,397.0L689.0,591.0L475.0,591.0L516.0,714.0L874.0,714.0L768.0,397.0L870.0,397.0L829.0,274.0L727.0,274.0L636.0,0.0L489.0,0.0ZM65.0,0.0L157.0,274.0L46.0,274.0L87.0,397.0L198.0,397.0L264.0,591.0L49.0,591.0L90.0,714.0L449.0,714.0L343.0,397.0L445.0,397.0L404.0,274.0L302.0,274.0L211.0,0.0L65.0,0.0Z"  transform="translate(3297, 868)"/>
<path d="M-238.0,747.0L-395.0,789.0L-381.0,849.0L-287.0,836.0L-251.0,922.0L-379.0,922.0L-379.0,987.0L-146.0,987.0L-238.0,747.0Z"  transform="translate(3978, 898)"/>
<path d="M74.0,0.0L268.0,591.0L59.0,591.0L99.0,714.0L453.0,714.0L258.0,125.0L533.0,125.0L729.0,714.0L871.0,714.0L635.0,0.0L74.0,0.0Z"  transform="translate(4094, 868)"/>
<path d="M22.0,0.0L161.0,413.0L21.0,413.0L62.0,536.0L348.0,536.0L209.0,123.0L343.0,123.0L535.0,714.0L682.0,714.0L624.0,536.0L929.0,536.0L753.0,0.0L605.0,0.0L740.0,413.0L584.0,413.0L448.0,0.0L22.0,0.0Z"  transform="translate(4887, 868)"/>
<path d="M118.0,-141.0Q89.0,-141.0 63.0,-134.5Q37.0,-128.0 20.5,-111.5Q4.0,-95.0 4.0,-65.0Q4.0,-31.0 28.0,-5.5Q52.0,20.0 83.0,46.0Q110.0,68.0 130.0,87.5Q150.0,107.0 150.0,125.0Q150.0,151.0 120.0,162.0Q90.0,173.0 19.0,173.0L-13.0,173.0L0.0,212.0L80.0,277.0L-20.0,277.0L2.0,340.0L216.0,340.0L216.0,305.0L118.0,222.0Q161.0,217.0 194.5,194.5Q228.0,172.0 228.0,125.0Q228.0,88.0 207.5,64.0Q187.0,40.0 163.0,20.0Q134.0,-5.0 110.5,-23.5Q87.0,-42.0 87.0,-56.0Q87.0,-78.0 130.0,-78.0Q159.0,-78.0 183.0,-69.0Q207.0,-60.0 219.0,-53.0L239.0,-109.0Q214.0,-124.0 180.5,-132.5Q147.0,-141.0 118.0,-141.0Z"  transform="translate(5748, 868)"/>
<path d="M152.0,0.0L347.0,591.0L62.0,591.0L102.0,714.0L537.0,714.0L343.0,128.0L730.0,128.0L688.0,0.0L152.0,0.0Z"  transform="translate(6012, 868)"/>
</svg>


</div> [code: shaping-regression]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* And 55 more.

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

	* And 57 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wacute (U+1E82): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wcircumflex (U+0174): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818

	* Wdieresis (U+1E84): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818 

	* And Wgrave (U+1E80): B<<481.0,529.0>-<475.0,558.0>-<473.0,572.0>>/B<<473.0,572.0>-<472.0,558.0>-<466.0,529.5>> = 12.215719134130818 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[6] NotoSansSundanese[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 9 | 24 | 535 | 32 | 472 | 0 |
| 0% | 1% | 2% | 50% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
