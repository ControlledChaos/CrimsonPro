## FontSpector report

fontspector version: 1.5.4






## Check results




<details><summary>[15] CrimsonPro[wght].ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. (case_mapping)</summary>
    <div>








- 🔥 **FAIL** The following glyphs are missing case-swapping counterparts:

| Glyph present in the font          | Missing case-swapping counterpart |
|------------------------------------|-----------------------------------|
| U+03A3: GREEK CAPITAL LETTER SIGMA | U+03C3: GREEK SMALL LETTER SIGMA  | [code: missing-case-counterparts]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. (interpolation_issues)</summary>
    <div>








- ⚠️ **WARN** Glyph uni20B2.BRACKET.varAlt01 has interpolation issues:
* Wrong start point: contour 1 should start at 1 in wght=200
* Contour 1 becomes underweight in wght=200 compared to default
* Wrong start point: contour 2 should start at 3 in wght=200
* Contour 2 becomes underweight in wght=200 compared to default [code: glyph]
  
  


- ⚠️ **WARN** Glyph uni20B2.BRACKET.varAlt01 has interpolation issues:
* Wrong start point: contour 1 should start at 1 in wght=588.8428
* Contour 1 becomes underweight in wght=588.8428 compared to default
* Wrong start point: contour 2 should start at 3 in wght=588.8428
* Contour 2 becomes underweight in wght=588.8428 compared to default [code: glyph]
  
  


- ⚠️ **WARN** Glyph uni20B2.BRACKET.varAlt01 has interpolation issues:
* Wrong start point: contour 1 should start at 1 in wght=900
* Contour 1 becomes underweight in wght=900 compared to default
* Wrong start point: contour 2 should start at 3 in wght=900
* Contour 2 becomes underweight in wght=900 compared to default [code: glyph]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* j.alt
* uni006A0301.alt
* NULL
* uni0326.alt [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ |                              |
|   The following auxiliary characters are missing from the font: ǎ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ȟ |                              |
|   The following auxiliary characters are missing from the font: Ǩ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ȟ |                              |
|   The following auxiliary characters are missing from the font: ǩ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ |                              |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)           |
|   The following auxiliary characters are missing from the font: Ǔ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ǔ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̃
* į̀
* į̂
* į́
* į̌
* į̄
* ị̃
* ị̀
* ị̂
... and 2 othersThe dot of soft dotted characters _should_ disappear in other cases, for example:

* į̉
* į̑
* į̈
* į̋
* į̆
* į̇
* į̒
* į̊
* į̏
... and 10 others [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Familyname must be unique according to namecheck.fontdata.com (fontdata_namecheck)</summary>
    <div>








- ℹ️ **INFO** The family name "Crimson Pro" seems to be already in use.
Please visit http://namecheck.fontdata.com/ for more info. [code: name-collision]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | CrimsonPro[wght].ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 266772 |
 | Hinted Size   | 266796   |
 | Increase      | 24      |
 | Change        | 0.0 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

    loca
    prep
    GPOS
    GSUB
    gasp [code: optional-tables]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table
set to optimize rendering? (googlefonts/gasp)</summary>
    <div>








- ℹ️ **INFO** These are the ppm ranges declared on the gasp table:

| PPM <= 65535 | - Use grid-fitting                                    |
|              | 	- Use grayscale rendering                            |
|              | 	- Use gridfitting with ClearType symmetric smoothing |
|              | 	- Use smoothing along multiple axes with ClearType®  |
|--------------|-------------------------------------------------------|
 [code: ranges]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.004 [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>


<details><summary>[4] </summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Fonts have equal codepoint coverage? (googlefonts/family/equal_codepoint_coverage)</summary>
    <div>








- 🔥 **FAIL** Font CrimsonPro-Italic[wght].ttf has codepoints not present in sibling fonts: U+0000 [code: glyphset-diverges]
  
  


- 🔥 **FAIL** Other fonts have codepoints not present in CrimsonPro-Italic[wght].ttf: U+01D0 [code: glyphset-diverges]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** CrimsonPro-Italic[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
* U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
* U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, todhri, malayalam, hebrew, duployan, math, tifinagh, syriac, canadian-aboriginal, coptic
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: tai-le, cherokee
... and 58 others

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin, vietnamese [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** CrimsonPro[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
* U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
* U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, todhri, malayalam, hebrew, duployan, math, tifinagh, syriac, canadian-aboriginal, coptic
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: tai-le, cherokee
... and 58 others

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin, vietnamese [code: unreachable-subsetting]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file (googlefonts/description/has_article)</summary>
    <div>








- ℹ️ **INFO** This font doesn't have an ARTICLE.en_us.html file. [code: missing-article]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. (googlefonts/STAT/axis_order)</summary>
    <div>








- ℹ️ **INFO** None of the fonts lack a STAT table.

	And these are the most common STAT axis orderings:
	wght-ital: 2 [code: summary]
  
  

</div>
</details>


</div>
</details>


<details><summary>[16] CrimsonPro-Italic[wght].ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. (case_mapping)</summary>
    <div>








- 🔥 **FAIL** The following glyphs are missing case-swapping counterparts:

| Glyph present in the font                 | Missing case-swapping counterpart       |
|-------------------------------------------|-----------------------------------------|
| U+03A3: GREEK CAPITAL LETTER SIGMA        | U+03C3: GREEK SMALL LETTER SIGMA        |
| U+01CF: LATIN CAPITAL LETTER I WITH CARON | U+01D0: LATIN SMALL LETTER I WITH CARON | [code: missing-case-counterparts]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni1E0D (U+1E0D): found 2, expected one of: {3, 4} [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* j.alt
* uni006A0301.alt
* uni0326.alt [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ |                              |
|   The following auxiliary characters are missing from the font: ǎ |                              |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)           |
|   The following auxiliary characters are missing from the font: Ǔ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ǔ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ȟ |                              |
|   The following auxiliary characters are missing from the font: Ǩ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ȟ |                              |
|   The following auxiliary characters are missing from the font: ǩ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̃
* į̄
* į́
* į̌
* į̀
* į̂
* ị̃
* ị̄
* ị́
... and 2 othersThe dot of soft dotted characters _should_ disappear in other cases, for example:

* į̒
* į̋
* į̉
* į̆
* į̊
* į̇
* į̈
* į̑
* į̏
... and 10 others [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Checking OS/2 fsSelection value. (opentype/xavgcharwidth)</summary>
    <div>








- ℹ️ **INFO** OS/2 xAvgCharWidth is 513 but it should be 512 which corresponds to the average of the widths of all glyphs in the font. These are similar values, which may be a symptom of the slightly different calculation of the xAvgCharWidth value in font editors. There's further discussion on this at https://github.com/fonttools/fontbakery/issues/1622 [code: xAvgCharWidth-close]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Familyname must be unique according to namecheck.fontdata.com (fontdata_namecheck)</summary>
    <div>








- ℹ️ **INFO** The family name "Crimson Pro" seems to be already in use.
Please visit http://namecheck.fontdata.com/ for more info. [code: name-collision]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | CrimsonPro-Italic[wght].ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 273616 |
 | Hinted Size   | 273640   |
 | Increase      | 24      |
 | Change        | 0.0 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

    loca
    prep
    GPOS
    GSUB
    gasp [code: optional-tables]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table
set to optimize rendering? (googlefonts/gasp)</summary>
    <div>








- ℹ️ **INFO** These are the ppm ranges declared on the gasp table:

| PPM <= 65535 | - Use grid-fitting                                    |
|              | 	- Use grayscale rendering                            |
|              | 	- Use gridfitting with ClearType symmetric smoothing |
|              | 	- Use smoothing along multiple axes with ClearType®  |
|--------------|-------------------------------------------------------|
 [code: ranges]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.004 [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 4 | 22 | 13 | 226 | 78 | 
| 1% | 6% | 4% | 67% | 23% | 



