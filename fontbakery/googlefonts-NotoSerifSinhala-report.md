## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifSinhala/googlefonts/ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Serif Sinhala' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[16] NotoSerifSinhala-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aaesinh
	* aasinh
	* aisinh
	* asinh
	* barephsinh
	* bhahalantsinh
	* bhiivowelsinh
	* bhivowelsinh
	* bhuvowelsinh
	* biivowelsinh and 340 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202

	* u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 

	* ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSerifSinhala-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aaesinh
	* aasinh
	* asinh
	* barephsinh
	* bhiivowelsinh
	* bhivowelsinh
	* biivowelsinh
	* carephsinh
	* chahalantsinh
	* charephsinh and 306 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.sinh (U+002C): X=138.0,Y=0.5 (should be at baseline 0?)

	* one.sinh (U+0031): X=112.5,Y=613.0 (should be at cap-height 612?)

	* three.sinh (U+0033): X=346.0,Y=1.0 (should be at baseline 0?)

	* five.sinh (U+0035): X=340.0,Y=1.5 (should be at baseline 0?)

	* six.sinh (U+0036): X=506.0,Y=614.0 (should be at cap-height 612?)

	* semicolon.sinh (U+003B): X=144.0,Y=0.5 (should be at baseline 0?)

	* J (U+004A): X=282.0,Y=-2.0 (should be at baseline 0?)

	* V (U+0056): X=85.0,Y=613.0 (should be at cap-height 612?)

	* W (U+0057): X=251.0,Y=613.0 (should be at cap-height 612?)

	* W (U+0057): X=892.0,Y=614.0 (should be at cap-height 612?) 

	* 75 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<566.0,454.5>-<559.0,473.0>-<549.0,487.0>>/B<<549.0,487.0>-<557.0,470.0>-<557.0,451.0>> = 10.336554146499246

	* masinh (U+0DB8): B<<541.5,454.5>-<535.0,473.0>-<524.0,487.0>>/B<<524.0,487.0>-<532.0,470.0>-<532.0,451.0>> = 12.95610294189398

	* mbasinh (U+0DB9): B<<570.0,454.5>-<563.0,473.0>-<553.0,487.0>>/B<<553.0,487.0>-<561.0,470.0>-<561.0,451.0>> = 10.336554146499246

	* oosinh (U+0D95): B<<566.0,454.5>-<559.0,473.0>-<549.0,487.0>>/B<<549.0,487.0>-<557.0,470.0>-<557.0,451.0>> = 10.336554146499246

	* osinh (U+0D94): B<<566.0,454.5>-<559.0,473.0>-<549.0,487.0>>/B<<549.0,487.0>-<557.0,470.0>-<557.0,451.0>> = 10.336554146499246

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202 

	* u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aaesinh
	* aasinh
	* asinh
	* barephsinh
	* bhahalantsinh
	* bhiivowelsinh
	* bhivowelsinh
	* biivowelsinh
	* carephsinh
	* chahalantsinh and 325 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* one.sinh (U+0031): X=105.0,Y=613.0 (should be at cap-height 612?)

	* three.sinh (U+0033): X=351.5,Y=1.0 (should be at baseline 0?)

	* nine.sinh (U+0039): X=61.0,Y=610.0 (should be at cap-height 612?)

	* nine.sinh (U+0039): X=212.0,Y=613.5 (should be at cap-height 612?)

	* less.sinh (U+003C): X=498.0,Y=614.0 (should be at cap-height 612?)

	* greater.sinh (U+003E): X=69.0,Y=614.0 (should be at cap-height 612?)

	* J (U+004A): X=120.0,Y=-1.0 (should be at baseline 0?)

	* P (U+0050): X=424.0,Y=613.0 (should be at cap-height 612?)

	* Q (U+0051): X=319.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=509.0,Y=2.0 (should be at baseline 0?) 

	* 61 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jasinh (U+0DA2): L<<490.0,442.0>--<521.0,442.0>> -> L<<521.0,442.0>--<522.0,442.0>>

	* nyjasinh (U+0DA6): L<<651.0,442.0>--<682.0,442.0>> -> L<<682.0,442.0>--<683.0,442.0>>

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> 

	* uni0DEA (U+0DEA): L<<490.0,442.0>--<521.0,442.0>> -> L<<521.0,442.0>--<522.0,442.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<568.5,447.5>-<564.0,463.0>-<556.0,476.0>>/B<<556.0,476.0>-<560.0,464.0>-<560.0,451.0>> = 13.172553423326871

	* ausinh (U+0D96): L<<379.0,229.0>--<397.0,229.0>>/B<<397.0,229.0>-<311.0,238.0>-<270.5,280.0>> = 5.9743232864805735

	* masinh (U+0DB8): B<<543.5,447.5>-<539.0,463.0>-<531.0,476.0>>/B<<531.0,476.0>-<535.0,464.0>-<535.0,451.0>> = 13.172553423326871

	* mbasinh (U+0DB9): B<<572.5,447.5>-<568.0,463.0>-<560.0,476.0>>/B<<560.0,476.0>-<564.0,464.0>-<564.0,451.0>> = 13.172553423326871

	* oosinh (U+0D95): B<<568.5,447.5>-<564.0,463.0>-<556.0,476.0>>/B<<556.0,476.0>-<560.0,464.0>-<560.0,451.0>> = 13.172553423326871

	* oosinh (U+0D95): L<<379.0,229.0>--<397.0,229.0>>/B<<397.0,229.0>-<311.0,238.0>-<270.5,280.0>> = 5.9743232864805735

	* osinh (U+0D94): B<<568.5,447.5>-<564.0,463.0>-<556.0,476.0>>/B<<556.0,476.0>-<560.0,464.0>-<560.0,451.0>> = 13.172553423326871

	* osinh (U+0D94): L<<379.0,229.0>--<397.0,229.0>>/B<<397.0,229.0>-<311.0,238.0>-<270.5,280.0>> = 5.9743232864805735

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202

	* u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<444.0,335.0>--<285.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifSinhala-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* gadharephsinh
	* jhahalantsinh
	* jharephsinh
	* jhiivowelsinh
	* jhivowelsinh
	* jhuuvowelsinh
	* jhuvowelsinh
	* kassahalantsinh
	* kassarephsinh
	* kassasinh and 52 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft.sinh (U+0028): X=93.5,Y=1.5 (should be at baseline 0?)

	* parenright.sinh (U+0029): X=266.0,Y=2.0 (should be at baseline 0?)

	* six.sinh (U+0036): X=176.0,Y=613.5 (should be at cap-height 612?)

	* nine.sinh (U+0039): X=89.0,Y=611.0 (should be at cap-height 612?)

	* question.sinh (U+003F): X=35.0,Y=611.0 (should be at cap-height 612?)

	* C (U+0043): X=530.0,Y=610.0 (should be at cap-height 612?)

	* G (U+0047): X=486.5,Y=-1.0 (should be at baseline 0?)

	* R (U+0052): X=442.5,Y=614.0 (should be at cap-height 612?)

	* S (U+0053): X=437.0,Y=614.0 (should be at cap-height 612?)

	* w (U+0077): X=411.0,Y=535.0 (should be at x-height 536?) 

	* 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<546.0,497.5>-<522.0,528.0>-<488.0,540.0>>/B<<488.0,540.0>-<510.0,527.0>-<519.0,506.0>> = 11.139192044312798

	* chasinh (U+0DA1): B<<553.5,664.5>-<484.0,609.0>-<446.0,532.0>>/B<<446.0,532.0>-<467.0,559.0>-<497.0,574.0>> = 11.608345294015082

	* ddasinh (U+0DA9): B<<89.5,330.5>-<131.0,390.0>-<212.0,415.0>>/B<<212.0,415.0>-<187.0,413.0>-<158.5,412.0>> = 12.578500480310963

	* ddhasinh (U+0DAA): B<<89.5,330.5>-<131.0,390.0>-<212.0,415.0>>/B<<212.0,415.0>-<187.0,413.0>-<158.5,412.0>> = 12.578500480310963

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648

	* ghasinh (U+0D9D): B<<89.5,330.0>-<131.0,390.0>-<212.0,415.0>>/B<<212.0,415.0>-<187.0,413.0>-<158.5,412.0>> = 12.578500480310963

	* masinh (U+0DB8): B<<529.0,497.5>-<505.0,528.0>-<470.0,540.0>>/B<<470.0,540.0>-<492.0,527.0>-<501.0,506.0>> = 11.654582456437772

	* mbasinh (U+0DB9): B<<553.0,497.5>-<529.0,528.0>-<494.0,540.0>>/B<<494.0,540.0>-<516.0,527.0>-<525.0,506.0>> = 11.654582456437772

	* nnddasinh (U+0DAC): B<<224.5,330.5>-<266.0,390.0>-<347.0,415.0>>/B<<347.0,415.0>-<322.0,413.0>-<293.5,412.0>> = 12.578500480310963

	* oosinh (U+0D95): B<<546.0,497.5>-<522.0,528.0>-<488.0,540.0>>/B<<488.0,540.0>-<510.0,527.0>-<519.0,506.0>> = 11.139192044312798 

	* 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSerifSinhala-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* barephsinh
	* carephsinh
	* charephsinh
	* chiivowelsinh
	* dadharephsinh
	* davarephsinh
	* ddarephsinh
	* ddharephsinh
	* ddhiivowelsinh
	* dharephsinh and 131 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=184.5,Y=611.0 (should be at cap-height 612?)

	* one.sinh (U+0031): X=153.5,Y=611.0 (should be at cap-height 612?)

	* nine.sinh (U+0039): X=147.0,Y=1.0 (should be at baseline 0?)

	* question.sinh (U+003F): X=34.0,Y=610.0 (should be at cap-height 612?)

	* C (U+0043): X=551.0,Y=611.0 (should be at cap-height 612?)

	* G (U+0047): X=599.0,Y=610.0 (should be at cap-height 612?)

	* N (U+004E): X=185.0,Y=611.0 (should be at cap-height 612?)

	* S (U+0053): X=449.0,Y=613.0 (should be at cap-height 612?)

	* V (U+0056): X=161.5,Y=611.0 (should be at cap-height 612?)

	* W (U+0057): X=515.0,Y=610.0 (should be at cap-height 612?) 

	* 85 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<551.5,486.5>-<532.0,515.0>-<504.0,529.0>>/B<<504.0,529.0>-<522.0,515.0>-<529.0,496.0>> = 11.309932474020162

	* chasinh (U+0DA1): B<<570.0,660.5>-<503.0,612.0>-<465.0,542.0>>/B<<465.0,542.0>-<508.0,589.0>-<568.0,589.0>> = 13.959557001941919

	* masinh (U+0DB8): B<<531.5,486.5>-<512.0,515.0>-<483.0,529.0>>/B<<483.0,529.0>-<501.0,515.0>-<508.5,496.0>> = 12.105656026759446

	* mbasinh (U+0DB9): B<<556.5,486.5>-<537.0,515.0>-<509.0,529.0>>/B<<509.0,529.0>-<527.0,515.0>-<534.5,496.0>> = 11.309932474020162

	* oosinh (U+0D95): B<<551.5,486.5>-<532.0,515.0>-<504.0,529.0>>/B<<504.0,529.0>-<522.0,515.0>-<529.0,496.0>> = 11.309932474020162

	* osinh (U+0D94): B<<551.5,486.5>-<532.0,515.0>-<504.0,529.0>>/B<<504.0,529.0>-<522.0,515.0>-<529.0,496.0>> = 11.309932474020162

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202 

	* u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSerifSinhala-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aaesinh
	* aasinh
	* asinh
	* barephsinh
	* carephsinh
	* chahalantsinh
	* charephsinh
	* chiivowelsinh
	* chivowelsinh
	* chuuvowelsinh and 236 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.sinh (U+002C): X=133.0,Y=1.0 (should be at baseline 0?)

	* one.sinh (U+0031): X=126.5,Y=613.0 (should be at cap-height 612?)

	* three.sinh (U+0033): X=336.0,Y=1.0 (should be at baseline 0?)

	* four.sinh (U+0034): X=311.0,Y=610.0 (should be at cap-height 612?)

	* six.sinh (U+0036): X=123.5,Y=613.5 (should be at cap-height 612?)

	* nine.sinh (U+0039): X=360.0,Y=610.0 (should be at cap-height 612?)

	* semicolon.sinh (U+003B): X=139.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=593.0,Y=611.0 (should be at cap-height 612?)

	* G (U+0047): X=642.0,Y=611.0 (should be at cap-height 612?)

	* G (U+0047): X=528.0,Y=2.0 (should be at baseline 0?) 

	* 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<561.0,466.0>-<550.0,489.0>-<534.0,504.0>>/B<<534.0,504.0>-<543.0,492.0>-<546.5,478.0>> = 9.97771262015058

	* masinh (U+0DB8): B<<537.0,466.0>-<526.0,489.0>-<509.0,504.0>>/B<<509.0,504.0>-<518.0,492.0>-<522.0,478.0>> = 11.706436729153328

	* mbasinh (U+0DB9): B<<565.0,466.0>-<554.0,489.0>-<538.0,504.0>>/B<<538.0,504.0>-<547.0,492.0>-<550.5,478.0>> = 9.97771262015058

	* oosinh (U+0D95): B<<561.0,466.0>-<550.0,489.0>-<534.0,504.0>>/B<<534.0,504.0>-<543.0,492.0>-<546.5,478.0>> = 9.97771262015058

	* osinh (U+0D94): B<<561.0,466.0>-<550.0,489.0>-<534.0,504.0>>/B<<534.0,504.0>-<543.0,492.0>-<546.5,478.0>> = 9.97771262015058

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202 

	* u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSerifSinhala-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/sinhala.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf);}
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

<h4>qa/shaping_tests/sinhala.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ආර්‍ය්‍</span></li>


<pre>Expected: aasinh=0+1081|yahalantsinh=1+792|space=1+0|rephsinh=1+0</pre>



<pre>Got     : aasinh=0+1081|yarephsinh=1+792|viramasinh=1+0|space=1+0</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1873 2304" transform="matrix(1 0 0 -1 0 0)">
<path d="M327.0,-10.0Q185.0,-10.0 110.5,51.0Q36.0,112.0 36.0,212.0Q36.0,281.0 64.5,326.0Q93.0,371.0 141.5,396.5Q190.0,422.0 251.0,432.0Q312.0,442.0 376.0,442.0L443.0,442.0Q437.0,480.0 413.0,507.0Q389.0,534.0 336.0,534.0Q302.0,534.0 291.0,517.0Q280.0,500.0 280.0,481.0Q280.0,464.0 284.0,452.0L206.0,442.0Q202.0,450.0 198.5,461.0Q195.0,472.0 195.0,490.0Q195.0,539.0 231.0,564.0Q267.0,589.0 321.0,589.0Q381.0,589.0 419.5,565.5Q458.0,542.0 477.0,499.0Q505.0,551.0 549.0,590.0L596.0,551.0Q588.0,545.0 581.0,539.0Q580.0,535.0 580.0,531.0Q580.0,519.0 587.0,504.0Q594.0,489.0 623.0,456.0Q652.0,423.0 667.0,398.0Q682.0,373.0 682.0,345.0Q682.0,296.0 650.5,273.0Q619.0,250.0 573.0,250.0Q554.0,250.0 535.0,255.0Q516.0,260.0 498.0,268.0L498.0,68.0Q548.0,83.0 606.0,113.0L628.0,60.0Q594.0,44.0 562.5,31.5Q531.0,19.0 498.0,10.0L498.0,-226.0L440.0,-226.0L440.0,-2.0Q389.0,-10.0 327.0,-10.0ZM498.0,366.0L498.0,326.0Q513.0,315.0 531.0,308.5Q549.0,302.0 571.0,302.0Q622.0,302.0 622.0,345.0Q622.0,365.0 613.0,381.5Q604.0,398.0 582.0,421.0Q560.0,445.0 550.0,462.0Q540.0,479.0 536.0,493.0Q498.0,440.0 498.0,366.0ZM337.0,48.0Q365.0,48.0 390.5,49.5Q416.0,51.0 440.0,55.0L440.0,351.0Q440.0,371.0 443.0,391.0L373.0,391.0Q254.0,391.0 195.5,351.5Q137.0,312.0 137.0,217.0Q137.0,144.0 187.5,96.0Q238.0,48.0 337.0,48.0ZM1039.0,248.0Q1039.0,109.0 991.5,49.5Q944.0,-10.0 862.0,-10.0Q804.0,-10.0 765.5,19.0Q727.0,48.0 702.0,100.0L753.0,125.0Q771.0,89.0 793.0,64.5Q815.0,40.0 852.0,40.0Q902.0,40.0 926.5,89.0Q951.0,138.0 951.0,248.0Q951.0,358.0 926.5,406.0Q902.0,454.0 852.0,454.0Q815.0,454.0 792.5,430.5Q770.0,407.0 754.0,373.0L702.0,398.0Q729.0,445.0 767.5,474.5Q806.0,504.0 862.0,504.0Q944.0,504.0 991.5,445.0Q1039.0,386.0 1039.0,248.0Z" transform="translate(0, 807)"/>
<path d="M574.0,-10.0Q498.0,-10.0 456.5,29.5Q415.0,69.0 395.0,128.0Q383.0,92.0 359.0,60.5Q335.0,29.0 299.0,9.5Q263.0,-10.0 215.0,-10.0Q136.0,-10.0 88.0,42.0Q40.0,94.0 40.0,201.0Q40.0,277.0 71.5,331.5Q103.0,386.0 158.5,416.0Q214.0,446.0 286.0,446.0Q297.0,446.0 311.5,445.5Q326.0,445.0 334.0,443.0L329.0,392.0Q317.0,394.0 307.0,394.0Q297.0,394.0 284.0,394.0Q236.0,394.0 194.0,376.5Q152.0,359.0 126.0,322.0Q100.0,285.0 100.0,226.0Q100.0,163.0 133.5,129.0Q167.0,95.0 226.0,95.0Q273.0,95.0 301.5,110.0Q330.0,125.0 346.0,150.0Q362.0,175.0 369.0,204.0L422.0,204.0Q428.0,153.0 465.0,124.0Q502.0,95.0 560.0,95.0Q622.0,95.0 656.5,126.5Q691.0,158.0 691.0,219.0Q691.0,269.0 664.5,308.0Q638.0,347.0 581.5,369.0Q525.0,391.0 434.0,391.0L421.0,391.0L421.0,396.0Q421.0,488.0 470.0,538.5Q519.0,589.0 593.0,589.0Q663.0,589.0 694.0,555.0Q725.0,521.0 725.0,468.0Q725.0,445.0 721.5,427.5Q718.0,410.0 713.0,397.0L662.0,413.0Q667.0,424.0 669.0,437.0Q671.0,450.0 671.0,460.0Q671.0,495.0 648.0,512.0Q625.0,529.0 584.0,529.0Q538.0,529.0 512.5,504.0Q487.0,479.0 479.0,441.0Q552.0,438.0 614.0,412.5Q676.0,387.0 713.5,336.0Q751.0,285.0 751.0,205.0Q751.0,107.0 705.5,48.5Q660.0,-10.0 574.0,-10.0ZM390.0,865.0Q458.0,865.0 503.0,848.0Q548.0,831.0 574.5,803.5Q601.0,776.0 612.0,743.5Q623.0,711.0 623.0,681.0Q623.0,629.0 606.0,596.0Q589.0,563.0 564.0,537.0L521.0,574.0Q541.0,590.0 555.0,613.5Q569.0,637.0 569.0,675.0Q569.0,705.0 552.0,733.5Q535.0,762.0 496.0,781.0Q457.0,800.0 390.0,800.0Q300.0,800.0 262.0,767.0Q224.0,734.0 224.0,688.0Q224.0,650.0 246.5,623.0Q269.0,596.0 322.0,589.0Q306.0,602.0 299.5,618.5Q293.0,635.0 293.0,653.0Q293.0,692.0 321.0,715.5Q349.0,739.0 394.0,739.0Q444.0,739.0 471.0,712.0Q498.0,685.0 498.0,644.0Q498.0,598.0 461.5,568.0Q425.0,538.0 356.0,538.0Q262.0,538.0 215.0,581.0Q168.0,624.0 168.0,694.0Q168.0,742.0 193.5,781.0Q219.0,820.0 268.5,842.5Q318.0,865.0 390.0,865.0ZM348.0,642.0Q348.0,622.0 359.5,609.0Q371.0,596.0 395.0,596.0Q415.0,596.0 428.5,608.5Q442.0,621.0 442.0,643.0Q442.0,661.0 432.0,675.0Q422.0,689.0 396.0,689.0Q373.0,689.0 360.5,676.5Q348.0,664.0 348.0,642.0Z" transform="translate(1081, 807)"/>
<path d="M-88.0,963.0Q-46.0,963.0 -23.5,935.5Q-1.0,908.0 -1.0,866.0Q-1.0,824.0 -22.5,796.5Q-44.0,769.0 -89.0,769.0Q-102.0,769.0 -116.5,773.5Q-131.0,778.0 -143.0,788.0Q-142.0,773.0 -142.0,758.0Q-142.0,743.0 -142.0,728.0L-142.0,489.0L-194.0,489.0L-194.0,848.0Q-194.0,886.0 -209.0,898.5Q-224.0,911.0 -239.0,911.0Q-248.0,911.0 -254.0,910.5Q-260.0,910.0 -263.0,909.0L-271.0,954.0Q-263.0,958.0 -252.5,960.5Q-242.0,963.0 -224.0,963.0Q-206.0,963.0 -190.0,953.5Q-174.0,944.0 -163.0,926.0Q-132.0,963.0 -88.0,963.0ZM-96.0,919.0Q-113.0,919.0 -124.5,909.0Q-136.0,899.0 -142.0,882.0L-142.0,849.0Q-136.0,833.0 -125.0,823.5Q-114.0,814.0 -94.0,814.0Q-53.0,814.0 -53.0,865.0Q-53.0,919.0 -96.0,919.0Z" transform="translate(1873, 807)"/>
<path d="" transform="translate(1873, 807)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1873 2304" transform="matrix(1 0 0 -1 0 0)">
<path d="M327.0,-10.0Q185.0,-10.0 110.5,51.0Q36.0,112.0 36.0,212.0Q36.0,281.0 64.5,326.0Q93.0,371.0 141.5,396.5Q190.0,422.0 251.0,432.0Q312.0,442.0 376.0,442.0L443.0,442.0Q437.0,480.0 413.0,507.0Q389.0,534.0 336.0,534.0Q302.0,534.0 291.0,517.0Q280.0,500.0 280.0,481.0Q280.0,464.0 284.0,452.0L206.0,442.0Q202.0,450.0 198.5,461.0Q195.0,472.0 195.0,490.0Q195.0,539.0 231.0,564.0Q267.0,589.0 321.0,589.0Q381.0,589.0 419.5,565.5Q458.0,542.0 477.0,499.0Q505.0,551.0 549.0,590.0L596.0,551.0Q588.0,545.0 581.0,539.0Q580.0,535.0 580.0,531.0Q580.0,519.0 587.0,504.0Q594.0,489.0 623.0,456.0Q652.0,423.0 667.0,398.0Q682.0,373.0 682.0,345.0Q682.0,296.0 650.5,273.0Q619.0,250.0 573.0,250.0Q554.0,250.0 535.0,255.0Q516.0,260.0 498.0,268.0L498.0,68.0Q548.0,83.0 606.0,113.0L628.0,60.0Q594.0,44.0 562.5,31.5Q531.0,19.0 498.0,10.0L498.0,-226.0L440.0,-226.0L440.0,-2.0Q389.0,-10.0 327.0,-10.0ZM498.0,366.0L498.0,326.0Q513.0,315.0 531.0,308.5Q549.0,302.0 571.0,302.0Q622.0,302.0 622.0,345.0Q622.0,365.0 613.0,381.5Q604.0,398.0 582.0,421.0Q560.0,445.0 550.0,462.0Q540.0,479.0 536.0,493.0Q498.0,440.0 498.0,366.0ZM337.0,48.0Q365.0,48.0 390.5,49.5Q416.0,51.0 440.0,55.0L440.0,351.0Q440.0,371.0 443.0,391.0L373.0,391.0Q254.0,391.0 195.5,351.5Q137.0,312.0 137.0,217.0Q137.0,144.0 187.5,96.0Q238.0,48.0 337.0,48.0ZM1039.0,248.0Q1039.0,109.0 991.5,49.5Q944.0,-10.0 862.0,-10.0Q804.0,-10.0 765.5,19.0Q727.0,48.0 702.0,100.0L753.0,125.0Q771.0,89.0 793.0,64.5Q815.0,40.0 852.0,40.0Q902.0,40.0 926.5,89.0Q951.0,138.0 951.0,248.0Q951.0,358.0 926.5,406.0Q902.0,454.0 852.0,454.0Q815.0,454.0 792.5,430.5Q770.0,407.0 754.0,373.0L702.0,398.0Q729.0,445.0 767.5,474.5Q806.0,504.0 862.0,504.0Q944.0,504.0 991.5,445.0Q1039.0,386.0 1039.0,248.0Z" transform="translate(0, 807)"/>
<path d="M574.0,-10.0Q498.0,-10.0 456.5,29.5Q415.0,69.0 395.0,128.0Q383.0,92.0 359.0,60.5Q335.0,29.0 299.0,9.5Q263.0,-10.0 215.0,-10.0Q136.0,-10.0 88.0,42.0Q40.0,94.0 40.0,201.0Q40.0,277.0 71.5,331.5Q103.0,386.0 158.5,416.0Q214.0,446.0 286.0,446.0Q297.0,446.0 311.5,445.5Q326.0,445.0 334.0,443.0L329.0,392.0Q317.0,394.0 307.0,394.0Q297.0,394.0 284.0,394.0Q236.0,394.0 194.0,376.5Q152.0,359.0 126.0,322.0Q100.0,285.0 100.0,226.0Q100.0,163.0 133.5,129.0Q167.0,95.0 226.0,95.0Q273.0,95.0 301.5,110.0Q330.0,125.0 346.0,150.0Q362.0,175.0 369.0,204.0L422.0,204.0Q428.0,153.0 465.0,124.0Q502.0,95.0 560.0,95.0Q622.0,95.0 656.5,126.5Q691.0,158.0 691.0,219.0Q691.0,269.0 664.5,308.0Q638.0,347.0 581.5,369.0Q525.0,391.0 434.0,391.0L421.0,391.0L421.0,396.0Q421.0,488.0 470.0,538.5Q519.0,589.0 593.0,589.0Q596.0,589.0 599.0,589.0L599.0,848.0Q599.0,886.0 584.0,898.5Q569.0,911.0 554.0,911.0Q545.0,911.0 539.0,910.5Q533.0,910.0 530.0,909.0L522.0,954.0Q530.0,958.0 540.5,960.5Q551.0,963.0 569.0,963.0Q587.0,963.0 603.0,953.5Q619.0,944.0 630.0,926.0Q661.0,963.0 705.0,963.0Q747.0,963.0 769.5,935.5Q792.0,908.0 792.0,866.0Q792.0,824.0 770.5,796.5Q749.0,769.0 704.0,769.0Q691.0,769.0 676.5,773.5Q662.0,778.0 650.0,788.0Q651.0,773.0 651.0,758.0Q651.0,743.0 651.0,728.0L651.0,581.0Q690.0,568.0 707.5,538.0Q725.0,508.0 725.0,468.0Q725.0,445.0 721.5,427.5Q718.0,410.0 713.0,397.0L662.0,413.0Q667.0,424.0 669.0,437.0Q671.0,450.0 671.0,460.0Q671.0,495.0 648.0,512.0Q625.0,529.0 584.0,529.0Q538.0,529.0 512.5,504.0Q487.0,479.0 479.0,441.0Q552.0,438.0 614.0,412.5Q676.0,387.0 713.5,336.0Q751.0,285.0 751.0,205.0Q751.0,107.0 705.5,48.5Q660.0,-10.0 574.0,-10.0ZM697.0,919.0Q680.0,919.0 668.5,909.0Q657.0,899.0 651.0,882.0L651.0,849.0Q657.0,833.0 668.0,823.5Q679.0,814.0 699.0,814.0Q740.0,814.0 740.0,865.0Q740.0,919.0 697.0,919.0Z" transform="translate(1081, 807)"/>
<path d="" transform="translate(1873, 807)"/>
<path d="M-310.0,865.0Q-242.0,865.0 -197.0,848.0Q-152.0,831.0 -125.5,803.5Q-99.0,776.0 -88.0,743.5Q-77.0,711.0 -77.0,681.0Q-77.0,629.0 -94.0,596.0Q-111.0,563.0 -136.0,537.0L-179.0,574.0Q-159.0,590.0 -145.0,613.5Q-131.0,637.0 -131.0,675.0Q-131.0,705.0 -148.0,733.5Q-165.0,762.0 -204.0,781.0Q-243.0,800.0 -310.0,800.0Q-400.0,800.0 -438.0,767.0Q-476.0,734.0 -476.0,688.0Q-476.0,650.0 -453.5,623.0Q-431.0,596.0 -378.0,589.0Q-394.0,602.0 -400.5,618.5Q-407.0,635.0 -407.0,653.0Q-407.0,692.0 -379.0,715.5Q-351.0,739.0 -306.0,739.0Q-256.0,739.0 -229.0,712.0Q-202.0,685.0 -202.0,644.0Q-202.0,598.0 -238.5,568.0Q-275.0,538.0 -344.0,538.0Q-438.0,538.0 -485.0,581.0Q-532.0,624.0 -532.0,694.0Q-532.0,742.0 -506.5,781.0Q-481.0,820.0 -431.5,842.5Q-382.0,865.0 -310.0,865.0ZM-352.0,642.0Q-352.0,622.0 -340.5,609.0Q-329.0,596.0 -305.0,596.0Q-285.0,596.0 -271.5,608.5Q-258.0,621.0 -258.0,643.0Q-258.0,661.0 -268.0,675.0Q-278.0,689.0 -304.0,689.0Q-327.0,689.0 -339.5,676.5Q-352.0,664.0 -352.0,642.0Z" transform="translate(1873, 807)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aaesinh
	* aasinh
	* asinh
	* barephsinh
	* carephsinh
	* chahalantsinh
	* charephsinh
	* chiivowelsinh
	* chivowelsinh
	* chuuvowelsinh and 217 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.sinh (U+002C): X=131.0,Y=1.0 (should be at baseline 0?)

	* one.sinh (U+0031): X=131.5,Y=613.0 (should be at cap-height 612?)

	* three.sinh (U+0033): X=331.5,Y=1.0 (should be at baseline 0?)

	* six.sinh (U+0036): X=127.0,Y=612.5 (should be at cap-height 612?)

	* nine.sinh (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* nine.sinh (U+0039): X=363.5,Y=613.0 (should be at cap-height 612?)

	* semicolon.sinh (U+003B): X=137.0,Y=1.0 (should be at baseline 0?)

	* question.sinh (U+003F): X=126.5,Y=610.0 (should be at cap-height 612?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?) 

	* 49 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<559.0,470.5>-<546.0,495.0>-<527.0,510.0>>/B<<527.0,510.0>-<539.0,497.0>-<543.5,481.0>> = 9.00044685039543

	* masinh (U+0DB8): B<<535.0,470.5>-<522.0,495.0>-<503.0,510.0>>/B<<503.0,510.0>-<515.0,497.0>-<519.5,481.0>> = 9.00044685039543

	* mbasinh (U+0DB9): B<<563.0,470.5>-<550.0,495.0>-<531.0,510.0>>/B<<531.0,510.0>-<543.0,497.0>-<547.5,481.0>> = 9.00044685039543

	* oosinh (U+0D95): B<<559.0,470.5>-<546.0,495.0>-<527.0,510.0>>/B<<527.0,510.0>-<539.0,497.0>-<543.5,481.0>> = 9.00044685039543

	* osinh (U+0D94): B<<559.0,470.5>-<546.0,495.0>-<527.0,510.0>>/B<<527.0,510.0>-<539.0,497.0>-<543.5,481.0>> = 9.00044685039543

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202 

	* u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aaesinh
	* aasinh
	* asinh
	* barephsinh
	* bhiivowelsinh
	* carephsinh
	* chahalantsinh
	* charephsinh
	* chasinh
	* chatouchsinh and 281 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.sinh (U+002C): X=135.5,Y=0.5 (should be at baseline 0?)

	* one.sinh (U+0031): X=120.0,Y=613.0 (should be at cap-height 612?)

	* three.sinh (U+0033): X=340.5,Y=1.0 (should be at baseline 0?)

	* seven.sinh (U+0037): X=422.0,Y=614.0 (should be at cap-height 612?)

	* seven.sinh (U+0037): X=166.0,Y=614.0 (should be at cap-height 612?)

	* semicolon.sinh (U+003B): X=141.5,Y=0.5 (should be at baseline 0?)

	* less.sinh (U+003C): X=496.0,Y=610.0 (should be at cap-height 612?)

	* greater.sinh (U+003E): X=67.0,Y=610.0 (should be at cap-height 612?)

	* Q (U+0051): X=470.0,Y=-1.0 (should be at baseline 0?)

	* asciicircum.sinh (U+005E): X=280.0,Y=611.0 (should be at cap-height 612?) 

	* 66 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<563.5,460.5>-<555.0,481.0>-<541.0,496.0>>/B<<541.0,496.0>-<553.0,475.0>-<553.0,450.0>> = 13.28018469217573

	* masinh (U+0DB8): B<<539.0,460.5>-<530.0,481.0>-<517.0,496.0>>/B<<517.0,496.0>-<529.0,475.0>-<529.0,450.0>> = 11.169501923082867

	* mbasinh (U+0DB9): B<<567.5,460.5>-<559.0,481.0>-<545.0,496.0>>/B<<545.0,496.0>-<557.0,475.0>-<557.0,450.0>> = 13.28018469217573

	* ngasinh (U+0D9E): B<<80.5,272.0>-<113.0,311.0>-<174.0,339.0>>/B<<174.0,339.0>-<158.0,336.0>-<141.0,336.0>> = 14.036243467926457

	* oosinh (U+0D95): B<<563.5,460.5>-<555.0,481.0>-<541.0,496.0>>/B<<541.0,496.0>-<553.0,475.0>-<553.0,450.0>> = 13.28018469217573

	* osinh (U+0D94): B<<563.5,460.5>-<555.0,481.0>-<541.0,496.0>>/B<<541.0,496.0>-<553.0,475.0>-<553.0,450.0>> = 13.28018469217573

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202 

	* u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<419.0,336.0>--<262.0,337.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- gravecomb 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jharephsinh
	* kassiivowelsinh
	* kavarephsinh
	* nadharephsinh
	* natharephsinh
	* navarephsinh
	* nyarephsinh
	* tatharephsinh
	* u111EA
	* u111ED and 5 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.sinh	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* zero.sinh (U+0030): X=428.5,Y=613.5 (should be at cap-height 612?)

	* zero.sinh (U+0030): X=129.0,Y=611.0 (should be at cap-height 612?)

	* two.sinh (U+0032): X=402.0,Y=612.5 (should be at cap-height 612?)

	* nine.sinh (U+0039): X=92.0,Y=612.5 (should be at cap-height 612?)

	* question.sinh (U+003F): X=35.0,Y=611.0 (should be at cap-height 612?)

	* C (U+0043): X=516.0,Y=610.0 (should be at cap-height 612?)

	* C (U+0043): X=407.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=477.5,Y=-1.5 (should be at baseline 0?)

	* S (U+0053): X=429.0,Y=614.0 (should be at cap-height 612?)

	* g (U+0067): X=394.0,Y=537.5 (should be at x-height 536?) 

	* 67 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* aisinh (U+0D93): B<<694.0,341.5>-<731.0,395.0>-<816.0,421.0>>/B<<816.0,421.0>-<790.0,418.0>-<759.0,417.5>> = 10.426002300229321

	* ausinh (U+0D96): B<<543.5,504.0>-<517.0,536.0>-<478.0,547.0>>/B<<478.0,547.0>-<502.0,534.0>-<512.0,512.0>> = 12.691754960910313

	* basinh (U+0DB6): B<<127.5,67.5>-<154.0,40.0>-<185.0,23.0>>/B<<185.0,23.0>-<170.0,34.0>-<159.0,53.0>> = 7.514042445756763

	* bhasinh (U+0DB7): B<<96.0,341.5>-<133.0,395.0>-<218.0,421.0>>/B<<218.0,421.0>-<192.0,418.0>-<161.0,417.5>> = 10.426002300229321

	* casinh (U+0DA0): B<<93.0,341.5>-<130.0,395.0>-<215.0,421.0>>/B<<215.0,421.0>-<189.0,418.0>-<158.0,417.5>> = 10.426002300229321

	* chasinh (U+0DA1): B<<541.5,666.0>-<470.0,605.0>-<434.0,524.0>>/B<<434.0,524.0>-<455.0,554.0>-<487.5,571.5>> = 11.029531223980502

	* ddasinh (U+0DA9): B<<93.0,337.5>-<138.0,400.0>-<230.0,422.0>>/B<<230.0,422.0>-<204.0,419.0>-<172.5,418.0>> = 6.866670396508532

	* ddhasinh (U+0DAA): B<<93.0,337.5>-<138.0,400.0>-<230.0,422.0>>/B<<230.0,422.0>-<204.0,419.0>-<172.5,418.0>> = 6.866670396508532

	* eesinh (U+0D92): B<<93.0,341.5>-<130.0,395.0>-<215.0,421.0>>/B<<215.0,421.0>-<189.0,418.0>-<158.0,417.5>> = 10.426002300229321

	* esinh (U+0D91): B<<93.0,341.5>-<130.0,395.0>-<215.0,421.0>>/B<<215.0,421.0>-<189.0,418.0>-<158.0,417.5>> = 10.426002300229321 

	* 15 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.sinh (U+0021): L<<129.0,167.0>--<126.0,714.0>>

	* exclam.sinh (U+0021): L<<155.0,714.0>--<154.0,167.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<124.0,370.0>> 

	* exclamdown (U+00A1): L<<149.0,370.0>--<152.0,-177.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerifSinhala[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B 

	- 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- asciicircum

	- asciitilde

	- asterisk

	- backslash

	- bar

	- braceleft

	- braceright

	- bracketleft

	- bracketright

	- colon 

	- 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD) and uni0DDE (U+0DDE) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0DDA, U+0DDC, U+0DDD and U+0DDE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.sinh (U+002C): X=131.0,Y=1.0 (should be at baseline 0?)

	* one.sinh (U+0031): X=131.5,Y=613.0 (should be at cap-height 612?)

	* three.sinh (U+0033): X=331.5,Y=1.0 (should be at baseline 0?)

	* five.sinh (U+0035): X=329.0,Y=0.5 (should be at baseline 0?)

	* six.sinh (U+0036): X=127.0,Y=612.5 (should be at cap-height 612?)

	* eight.sinh (U+0038): X=385.5,Y=613.5 (should be at cap-height 612?)

	* nine.sinh (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon.sinh (U+003B): X=137.0,Y=1.0 (should be at baseline 0?)

	* question.sinh (U+003F): X=126.5,Y=610.0 (should be at cap-height 612?)

	* C (U+0043): X=457.5,Y=0.5 (should be at baseline 0?) 

	* 70 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 35 | 125 | 1129 | 62 | 922 | 0 |
| 0% | 2% | 5% | 50% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**