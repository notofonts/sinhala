## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[3] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[14] NotoSerifSinhala[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerifSinhala[wght].ttf' must be renamed to 'NotoSerifSinhala[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 283. [code: invalid-default-instance-subfamily-nameid:283]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 70 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* tarephsinh
	* u111F0
	* yiivowelsinh
	* fahalantsinh
	* kahalantsinh
	* thahalantsinh
	* karephsinh
	* ssivowelsinh
	* miivowelsinh
	* ssiivowelsinh and 340 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifSinhala-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* tarephsinh
	* u111F0
	* yiivowelsinh
	* kahalantsinh
	* thahalantsinh
	* karephsinh
	* ssivowelsinh
	* miivowelsinh
	* ssiivowelsinh
	* tthiivowelsinh and 306 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 76 more.

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

	* And u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] NotoSerifSinhala-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* tarephsinh
	* u111F0
	* yiivowelsinh
	* kahalantsinh
	* thahalantsinh
	* karephsinh
	* ssivowelsinh
	* miivowelsinh
	* ssiivowelsinh
	* tthiivowelsinh and 325 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 61 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jasinh (U+0DA2): L<<490.0,442.0>--<521.0,442.0>> -> L<<521.0,442.0>--<522.0,442.0>>

	* nyjasinh (U+0DA6): L<<651.0,442.0>--<682.0,442.0>> -> L<<682.0,442.0>--<683.0,442.0>>

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> 

	* And uni0DEA (U+0DEA): L<<490.0,442.0>--<521.0,442.0>> -> L<<521.0,442.0>--<522.0,442.0>> [code: found-colinear-vectors]
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

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<444.0,335.0>--<285.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u111F0
	* jhuuvowelsinh
	* tathuuvowelsinh
	* nadahalantsinh
	* kassuvowelsinh
	* u111F1
	* tathasinh
	* nyaavowelsinh
	* kavarephsinh
	* jhiivowelsinh and 52 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 81 more.

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

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u111F0
	* tthiivowelsinh
	* jhuuvowelsinh
	* jhasinh
	* nnahalantsinh
	* tathuuvowelsinh
	* ddhiivowelsinh
	* nadahalantsinh
	* kavivowelsinh
	* pharephsinh and 131 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 85 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u111F2 (U+111F2): L<<722.0,589.0>--<754.0,589.0>> -> L<<754.0,589.0>--<754.0,589.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ausinh (U+0D96): B<<551.5,486.5>-<532.0,515.0>-<504.0,529.0>>/B<<504.0,529.0>-<522.0,515.0>-<529.0,496.0>> = 11.309932474020162

	* chasinh (U+0DA1): B<<570.0,660.5>-<503.0,612.0>-<465.0,542.0>>/B<<465.0,542.0>-<508.0,589.0>-<568.0,589.0>> = 13.959557001941919

	* masinh (U+0DB8): B<<531.5,486.5>-<512.0,515.0>-<483.0,529.0>>/B<<483.0,529.0>-<501.0,515.0>-<508.5,496.0>> = 12.105656026759448

	* mbasinh (U+0DB9): B<<556.5,486.5>-<537.0,515.0>-<509.0,529.0>>/B<<509.0,529.0>-<527.0,515.0>-<534.5,496.0>> = 11.309932474020162

	* oosinh (U+0D95): B<<551.5,486.5>-<532.0,515.0>-<504.0,529.0>>/B<<504.0,529.0>-<522.0,515.0>-<529.0,496.0>> = 11.309932474020162

	* osinh (U+0D94): B<<551.5,486.5>-<532.0,515.0>-<504.0,529.0>>/B<<504.0,529.0>-<522.0,515.0>-<529.0,496.0>> = 11.309932474020162

	* u111E1 (U+111E1): B<<624.0,504.0>-<723.0,419.0>-<763.0,252.0>>/B<<763.0,252.0>-<757.0,302.0>-<754.5,360.5>> = 6.627004816933202 

	* And u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* tarephsinh
	* u111F0
	* kahalantsinh
	* thahalantsinh
	* ssivowelsinh
	* ssiivowelsinh
	* tthiivowelsinh
	* jhuuvowelsinh
	* ndiivowelsinh
	* tuuvowelsinh and 236 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 82 more.

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

	* And u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifSinhala-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
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

<li>Shaping did not match: <span class="tf">සුරැරු</span></li>


<pre>Expected: suvowelsinh=0+824|rasinh=2+702|raevowelsinh=2+248|rasinh=4+702|aevowelsignsinh=4+309</pre>



<pre>Got     : suvowelsinh=0+800|raevowelsinh=2+908|rasinh=4+680|aevowelsignsinh=4+299</pre>



<pre>                         +++++++++++++ ^                ^^           ^ +                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2687 2304" transform="matrix(1 0 0 -1 0 0)">
<path d="M67.0,-161.0Q67.0,-107.0 102.5,-74.5Q138.0,-42.0 196.0,-42.0Q225.0,-42.0 250.0,-48.5Q275.0,-55.0 295.0,-66.0L276.0,-111.0Q262.0,-104.0 242.5,-98.5Q223.0,-93.0 198.0,-93.0Q159.0,-93.0 141.5,-112.0Q124.0,-131.0 124.0,-158.0Q124.0,-204.0 163.5,-216.0Q203.0,-228.0 274.0,-228.0L654.0,-228.0L654.0,-117.0Q654.0,-86.0 655.5,-55.5Q657.0,-25.0 659.0,6.0Q625.0,-10.0 582.0,-10.0Q506.0,-10.0 464.5,29.5Q423.0,69.0 403.0,129.0Q392.0,94.0 368.5,62.0Q345.0,30.0 309.0,10.0Q273.0,-10.0 223.0,-10.0Q144.0,-10.0 96.0,41.5Q48.0,93.0 48.0,187.0Q48.0,262.0 82.0,313.0Q116.0,364.0 171.0,393.0Q148.0,392.0 121.0,391.5Q94.0,391.0 72.0,391.0L24.0,391.0L24.0,442.0L338.0,442.0Q331.0,477.0 308.5,505.5Q286.0,534.0 236.0,534.0Q176.0,534.0 176.0,481.0Q176.0,477.0 177.0,470.5Q178.0,464.0 179.0,459.0L97.0,452.0Q94.0,460.0 92.5,472.0Q91.0,484.0 91.0,490.0Q91.0,539.0 128.0,564.0Q165.0,589.0 219.0,589.0Q304.0,589.0 349.5,538.5Q395.0,488.0 395.0,405.0L395.0,391.0L278.0,391.0Q192.0,372.0 151.0,324.0Q110.0,276.0 110.0,214.0Q110.0,154.0 143.0,124.5Q176.0,95.0 237.0,95.0Q283.0,95.0 311.0,110.0Q339.0,125.0 354.5,150.0Q370.0,175.0 377.0,204.0L430.0,204.0Q436.0,153.0 473.0,124.0Q510.0,95.0 568.0,95.0Q630.0,95.0 664.5,126.5Q699.0,158.0 699.0,219.0Q699.0,294.0 639.0,342.5Q579.0,391.0 443.0,391.0L427.0,391.0L427.0,397.0Q427.0,456.0 449.0,499.0Q471.0,542.0 509.0,565.5Q547.0,589.0 595.0,589.0Q663.0,589.0 694.0,555.0Q725.0,521.0 725.0,468.0Q725.0,449.0 721.5,431.5Q718.0,414.0 712.0,397.0L662.0,413.0Q667.0,424.0 669.0,437.0Q671.0,450.0 671.0,460.0Q671.0,495.0 648.5,512.0Q626.0,529.0 588.0,529.0Q543.0,529.0 518.0,504.0Q493.0,479.0 485.0,441.0Q558.0,438.0 620.5,413.0Q683.0,388.0 721.0,337.0Q759.0,286.0 759.0,205.0Q759.0,103.0 712.0,46.0L712.0,-284.0L259.0,-284.0Q159.0,-284.0 113.0,-253.0Q67.0,-222.0 67.0,-161.0Z"  transform="translate(0, 807)"/>
<path d="M344.0,-10.0Q199.0,-10.0 120.0,68.5Q41.0,147.0 41.0,282.0Q41.0,386.0 98.0,459.5Q155.0,533.0 248.0,559.0Q354.0,633.0 436.5,701.0Q519.0,769.0 582.0,825.0L733.0,825.0L765.0,784.0Q720.0,640.0 688.5,510.5Q657.0,381.0 657.0,247.0Q657.0,172.0 671.0,133.5Q685.0,95.0 708.0,81.0Q731.0,67.0 758.0,67.0Q802.0,67.0 824.5,93.5Q847.0,120.0 855.0,178.0L906.0,169.0Q896.0,86.0 857.0,38.0Q818.0,-10.0 751.0,-10.0Q699.0,-10.0 659.0,19.5Q619.0,49.0 604.0,127.0Q538.0,-10.0 344.0,-10.0ZM641.0,772.0L624.0,772.0Q563.0,722.0 494.0,669.5Q425.0,617.0 358.0,572.0Q454.0,569.0 518.0,527.0Q582.0,485.0 611.0,414.0Q625.0,512.0 652.0,597.0Q679.0,682.0 712.0,773.0Q695.0,773.0 675.5,772.5Q656.0,772.0 641.0,772.0ZM345.0,95.0Q408.0,95.0 462.5,115.0Q517.0,135.0 550.5,182.0Q584.0,229.0 584.0,310.0Q584.0,379.0 550.0,426.5Q516.0,474.0 461.5,498.0Q407.0,522.0 344.0,522.0Q278.0,522.0 223.5,496.5Q169.0,471.0 136.5,423.0Q104.0,375.0 104.0,307.0Q104.0,228.0 138.0,181.5Q172.0,135.0 227.0,115.0Q282.0,95.0 345.0,95.0Z"  transform="translate(800, 807)"/>
<path d="M344.0,-10.0Q199.0,-10.0 120.0,68.5Q41.0,147.0 41.0,282.0Q41.0,386.0 97.5,459.5Q154.0,533.0 248.0,559.0Q321.0,611.0 390.0,665.0Q459.0,719.0 517.0,768.5Q575.0,818.0 616.0,856.0L664.0,800.0Q629.0,768.0 578.0,728.5Q527.0,689.0 470.0,648.0Q413.0,607.0 359.0,572.0Q448.0,569.0 513.0,529.5Q578.0,490.0 612.5,425.5Q647.0,361.0 647.0,282.0Q647.0,142.0 565.5,66.0Q484.0,-10.0 344.0,-10.0ZM345.0,95.0Q408.0,95.0 462.5,115.0Q517.0,135.0 550.5,182.0Q584.0,229.0 584.0,310.0Q584.0,379.0 550.0,426.5Q516.0,474.0 461.5,498.0Q407.0,522.0 344.0,522.0Q278.0,522.0 223.5,496.5Q169.0,471.0 136.5,423.0Q104.0,375.0 104.0,307.0Q104.0,228.0 138.0,181.5Q172.0,135.0 227.0,115.0Q282.0,95.0 345.0,95.0Z"  transform="translate(1708, 807)"/>
<path d="M10.0,391.0L254.0,391.0L283.0,337.0Q198.0,252.0 152.5,177.5Q107.0,103.0 107.0,12.0Q107.0,-58.0 138.0,-91.5Q169.0,-125.0 223.0,-125.0Q249.0,-125.0 269.0,-118.0Q289.0,-111.0 313.0,-95.0L336.0,-139.0Q303.0,-160.0 270.0,-170.5Q237.0,-181.0 198.0,-181.0Q149.0,-181.0 108.5,-163.0Q68.0,-145.0 44.0,-104.5Q20.0,-64.0 20.0,4.0Q20.0,55.0 38.5,106.0Q57.0,157.0 100.5,214.0Q144.0,271.0 218.0,340.0Q190.0,338.0 148.0,338.0L10.0,338.0L10.0,391.0Z"  transform="translate(2388, 807)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2785 2304" transform="matrix(1 0 0 -1 0 0)">
<path d="M67.0,-161.0Q67.0,-107.0 102.5,-74.5Q138.0,-42.0 196.0,-42.0Q225.0,-42.0 250.0,-48.5Q275.0,-55.0 295.0,-66.0L276.0,-111.0Q262.0,-104.0 242.5,-98.5Q223.0,-93.0 198.0,-93.0Q159.0,-93.0 141.5,-112.0Q124.0,-131.0 124.0,-158.0Q124.0,-204.0 163.5,-216.0Q203.0,-228.0 274.0,-228.0L654.0,-228.0L654.0,-117.0Q654.0,-86.0 655.5,-55.5Q657.0,-25.0 659.0,6.0Q625.0,-10.0 582.0,-10.0Q506.0,-10.0 464.5,29.5Q423.0,69.0 403.0,129.0Q392.0,94.0 368.5,62.0Q345.0,30.0 309.0,10.0Q273.0,-10.0 223.0,-10.0Q144.0,-10.0 96.0,41.5Q48.0,93.0 48.0,187.0Q48.0,262.0 82.0,313.0Q116.0,364.0 171.0,393.0Q148.0,392.0 121.0,391.5Q94.0,391.0 72.0,391.0L24.0,391.0L24.0,442.0L338.0,442.0Q331.0,477.0 308.5,505.5Q286.0,534.0 236.0,534.0Q176.0,534.0 176.0,481.0Q176.0,477.0 177.0,470.5Q178.0,464.0 179.0,459.0L97.0,452.0Q94.0,460.0 92.5,472.0Q91.0,484.0 91.0,490.0Q91.0,539.0 128.0,564.0Q165.0,589.0 219.0,589.0Q304.0,589.0 349.5,538.5Q395.0,488.0 395.0,405.0L395.0,391.0L278.0,391.0Q192.0,372.0 151.0,324.0Q110.0,276.0 110.0,214.0Q110.0,154.0 143.0,124.5Q176.0,95.0 237.0,95.0Q283.0,95.0 311.0,110.0Q339.0,125.0 354.5,150.0Q370.0,175.0 377.0,204.0L430.0,204.0Q436.0,153.0 473.0,124.0Q510.0,95.0 568.0,95.0Q630.0,95.0 664.5,126.5Q699.0,158.0 699.0,219.0Q699.0,294.0 639.0,342.5Q579.0,391.0 443.0,391.0L427.0,391.0L427.0,397.0Q427.0,456.0 449.0,499.0Q471.0,542.0 509.0,565.5Q547.0,589.0 595.0,589.0Q663.0,589.0 694.0,555.0Q725.0,521.0 725.0,468.0Q725.0,449.0 721.5,431.5Q718.0,414.0 712.0,397.0L662.0,413.0Q667.0,424.0 669.0,437.0Q671.0,450.0 671.0,460.0Q671.0,495.0 648.5,512.0Q626.0,529.0 588.0,529.0Q543.0,529.0 518.0,504.0Q493.0,479.0 485.0,441.0Q558.0,438.0 620.5,413.0Q683.0,388.0 721.0,337.0Q759.0,286.0 759.0,205.0Q759.0,103.0 712.0,46.0L712.0,-284.0L259.0,-284.0Q159.0,-284.0 113.0,-253.0Q67.0,-222.0 67.0,-161.0Z"  transform="translate(0, 807)"/>
<path d="M344.0,-10.0Q199.0,-10.0 120.0,68.5Q41.0,147.0 41.0,282.0Q41.0,386.0 97.5,459.5Q154.0,533.0 248.0,559.0Q321.0,611.0 390.0,665.0Q459.0,719.0 517.0,768.5Q575.0,818.0 616.0,856.0L664.0,800.0Q629.0,768.0 578.0,728.5Q527.0,689.0 470.0,648.0Q413.0,607.0 359.0,572.0Q448.0,569.0 513.0,529.5Q578.0,490.0 612.5,425.5Q647.0,361.0 647.0,282.0Q647.0,142.0 565.5,66.0Q484.0,-10.0 344.0,-10.0ZM345.0,95.0Q408.0,95.0 462.5,115.0Q517.0,135.0 550.5,182.0Q584.0,229.0 584.0,310.0Q584.0,379.0 550.0,426.5Q516.0,474.0 461.5,498.0Q407.0,522.0 344.0,522.0Q278.0,522.0 223.5,496.5Q169.0,471.0 136.5,423.0Q104.0,375.0 104.0,307.0Q104.0,228.0 138.0,181.5Q172.0,135.0 227.0,115.0Q282.0,95.0 345.0,95.0Z"  transform="translate(824, 807)"/>
<path d="M344.0,-10.0Q199.0,-10.0 120.0,68.5Q41.0,147.0 41.0,282.0Q41.0,386.0 98.0,459.5Q155.0,533.0 248.0,559.0Q354.0,633.0 436.5,701.0Q519.0,769.0 582.0,825.0L733.0,825.0L765.0,784.0Q720.0,640.0 688.5,510.5Q657.0,381.0 657.0,247.0Q657.0,172.0 671.0,133.5Q685.0,95.0 708.0,81.0Q731.0,67.0 758.0,67.0Q802.0,67.0 824.5,93.5Q847.0,120.0 855.0,178.0L906.0,169.0Q896.0,86.0 857.0,38.0Q818.0,-10.0 751.0,-10.0Q699.0,-10.0 659.0,19.5Q619.0,49.0 604.0,127.0Q538.0,-10.0 344.0,-10.0ZM641.0,772.0L624.0,772.0Q563.0,722.0 494.0,669.5Q425.0,617.0 358.0,572.0Q454.0,569.0 518.0,527.0Q582.0,485.0 611.0,414.0Q625.0,512.0 652.0,597.0Q679.0,682.0 712.0,773.0Q695.0,773.0 675.5,772.5Q656.0,772.0 641.0,772.0ZM345.0,95.0Q408.0,95.0 462.5,115.0Q517.0,135.0 550.5,182.0Q584.0,229.0 584.0,310.0Q584.0,379.0 550.0,426.5Q516.0,474.0 461.5,498.0Q407.0,522.0 344.0,522.0Q278.0,522.0 223.5,496.5Q169.0,471.0 136.5,423.0Q104.0,375.0 104.0,307.0Q104.0,228.0 138.0,181.5Q172.0,135.0 227.0,115.0Q282.0,95.0 345.0,95.0Z"  transform="translate(1526, 807)"/>
<path d="M344.0,-10.0Q199.0,-10.0 120.0,68.5Q41.0,147.0 41.0,282.0Q41.0,386.0 97.5,459.5Q154.0,533.0 248.0,559.0Q321.0,611.0 390.0,665.0Q459.0,719.0 517.0,768.5Q575.0,818.0 616.0,856.0L664.0,800.0Q629.0,768.0 578.0,728.5Q527.0,689.0 470.0,648.0Q413.0,607.0 359.0,572.0Q448.0,569.0 513.0,529.5Q578.0,490.0 612.5,425.5Q647.0,361.0 647.0,282.0Q647.0,142.0 565.5,66.0Q484.0,-10.0 344.0,-10.0ZM345.0,95.0Q408.0,95.0 462.5,115.0Q517.0,135.0 550.5,182.0Q584.0,229.0 584.0,310.0Q584.0,379.0 550.0,426.5Q516.0,474.0 461.5,498.0Q407.0,522.0 344.0,522.0Q278.0,522.0 223.5,496.5Q169.0,471.0 136.5,423.0Q104.0,375.0 104.0,307.0Q104.0,228.0 138.0,181.5Q172.0,135.0 227.0,115.0Q282.0,95.0 345.0,95.0Z"  transform="translate(1774, 807)"/>
<path d="M10.0,391.0L254.0,391.0L283.0,337.0Q198.0,252.0 152.5,177.5Q107.0,103.0 107.0,12.0Q107.0,-58.0 138.0,-91.5Q169.0,-125.0 223.0,-125.0Q249.0,-125.0 269.0,-118.0Q289.0,-111.0 313.0,-95.0L336.0,-139.0Q303.0,-160.0 270.0,-170.5Q237.0,-181.0 198.0,-181.0Q149.0,-181.0 108.5,-163.0Q68.0,-145.0 44.0,-104.5Q20.0,-64.0 20.0,4.0Q20.0,55.0 38.5,106.0Q57.0,157.0 100.5,214.0Q144.0,271.0 218.0,340.0Q190.0,338.0 148.0,338.0L10.0,338.0L10.0,391.0Z"  transform="translate(2476, 807)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u111F0
	* kahalantsinh
	* thahalantsinh
	* ssivowelsinh
	* ssiivowelsinh
	* tthiivowelsinh
	* jhuuvowelsinh
	* tuuvowelsinh
	* kivowelsinh
	* jhasinh and 217 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 49 more.

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

	* And u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] NotoSerifSinhala-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* tarephsinh
	* u111F0
	* yiivowelsinh
	* kahalantsinh
	* thahalantsinh
	* karephsinh
	* ssivowelsinh
	* ssiivowelsinh
	* tthiivowelsinh
	* jhuuvowelsinh and 281 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 66 more.

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

	* And u111E9 (U+111E9): B<<1151.0,437.5>-<1232.0,338.0>-<1267.0,192.0>>/B<<1267.0,192.0>-<1260.0,245.0>-<1257.5,311.0>> = 5.957069376294162 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<419.0,336.0>--<262.0,337.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] NotoSerifSinhala-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u111F0
	* u111F1
	* kavarephsinh
	* tatharephsinh
	* nadharephsinh
	* kassiivowelsinh
	* u111F2
	* nyarephsinh
	* u111F4
	* jharephsinh and 5 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Sinhala Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 67 more.

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

	* And 15 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.sinh (U+0021): L<<129.0,167.0>--<126.0,714.0>>

	* exclam.sinh (U+0021): L<<155.0,714.0>--<154.0,167.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<124.0,370.0>> 

	* And exclamdown (U+00A1): L<<149.0,370.0>--<152.0,-177.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerifSinhala[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifSinhala/googlefonts/slim-variable-ttf/NotoSerifSinhala[wght].ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Black.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Bold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-ExtraLight.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Light.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Medium.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Regular.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-SemiBold.ttf', 'fonts/NotoSerifSinhala/googlefonts/ttf/NotoSerifSinhala-Thin.ttf', 'fonts/NotoSerifSinhala/googlefonts/variable-ttf/NotoSerifSinhala[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.sinh": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 283. [code: invalid-default-instance-subfamily-nameid:283]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- five

	- parenright

	- quoteright

	- divide

	- comma

	- equal

	- ellipsis

	- plus

	- parenleft

	- multiply 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignsinh (U+0DCF), aivowelsignsinh (U+0DDB), llvocalicvowelsignsinh (U+0DF3), lvocalicvowelsignsinh (U+0DDF), rvocalicvowelsignsinh (U+0DD8), uni0DDA (U+0DDA), uni0DDC (U+0DDC), uni0DDD (U+0DDD), uni0DDE (U+0DDE) and visargasinh (U+0D83) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D83, U+0DCF, U+0DD8, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF and U+0DF3 [code: non-mark-chars]
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

	* And 70 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 73 | 112 | 1241 | 78 | 931 | 0 |
| 0% | 3% | 5% | 51% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
