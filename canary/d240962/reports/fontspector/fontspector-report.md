## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[14] fonts/ttf/AwaragiraCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that format 12 cmap subtables are correctly constituted. (cmap/format_12)</summary>
    <div>








- ⚠️ **WARN** The format 12 subtable did not contain all codepoints from the format 4 subtable:

* U+FFFF [code: missing-format-4]
  
  


- ⚠️ **WARN** The format 12 subtable did not contain all codepoints from the format 4 subtable:

* U+FFFF [code: missing-format-4]
  
  

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
* uni0D92 (U+0D92): found 2, expected one of: [3, 4, 5]
* uni0D93 (U+0D93): found 3, expected one of: [4, 5, 6]
* uni0D95 (U+0D95): found 2, expected one of: [3, 4]
* uni0D9B (U+0D9B): found 1, expected one of: [2, 3]
* uni0DA3 (U+0DA3): found 2, expected one of: [3, 4]
* uni0DA4 (U+0DA4): found 2, expected one of: [3, 4, 6]
* uni0DA5 (U+0DA5): found 1, expected one of: [2, 3, 5]
* uni0DB9 (U+0DB9): found 1, expected one of: [2, 3] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

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

* iisignsinh.alt2
* iisignsinh.alt8
* NameMe.880
* zero.osf
* one.osf
* two.osf
* three.osf
* four.osf
* five.osf
* six.osf
* seven.osf
* eight.osf
* nine.osf
* mooniak [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* tsinh
* nnIisinh
* jnysinh
* shsinh
* kRsinh
* gRsinh
* tRsinh
* bhRsinh
* gsinh
* rIsinh
* bhsinh
* rIisinh
* nsinh
* nysinh
* nngsinh
* ksinh
* hsinh
* nyRsinh
* jnyRsinh
* lsinh
* pUsinh
* shRsinh
* hRsinh [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uni0DB7 (U+0DB7): from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* uni0DB7 (U+0DB7): from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* uni0DC4 (U+0DC4): from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* uni0DC4 (U+0DC4): from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* kVasinh: from (70.0, 142.0) to (69.0, 141.0) is colinear with segment from (69.0, 141.0) to (67.0, 139.0)
* thsinh: from (556.0, 640.0) to (550.0, 700.0) is colinear with segment from (550.0, 700.0) to (550.0, 785.0)
* bhsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* kVsinh: from (70.0, 142.0) to (69.0, 141.0) is colinear with segment from (69.0, 141.0) to (67.0, 139.0)
* tThsinh: from (1090.0, 640.0) to (1084.0, 700.0) is colinear with segment from (1084.0, 700.0) to (1084.0, 785.0)
* nThsinh: from (1093.0, 640.0) to (1087.0, 700.0) is colinear with segment from (1087.0, 700.0) to (1087.0, 785.0)
* bhIsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhIsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hIsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hIsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* kVIsinh: from (70.0, 142.0) to (69.0, 141.0) is colinear with segment from (69.0, 141.0) to (67.0, 139.0)
* bhIisinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhIisinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hIisinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hIisinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* kVIisinh: from (70.0, 142.0) to (69.0, 141.0) is colinear with segment from (69.0, 141.0) to (67.0, 139.0)
* nyUsinh: from (1188.0, -145.0) to (1188.0, 27.0) is colinear with segment from (1188.0, 27.0) to (1189.0, 47.0)
* jnyUsinh: from (1074.0, -145.0) to (1074.0, 27.0) is colinear with segment from (1074.0, 27.0) to (1075.0, 47.0)
* dUsinh: from (442.0, -145.0) to (442.0, 27.0) is colinear with segment from (442.0, 27.0) to (443.0, 46.0)
* ndUsinh: from (572.0, -145.0) to (572.0, 27.0) is colinear with segment from (572.0, 27.0) to (573.0, 46.0)
* bUsinh: from (579.0, -145.0) to (579.0, 27.0) is colinear with segment from (579.0, 27.0) to (579.0, 28.0)
* bhUsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhUsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hUsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hUsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* kVUsinh: from (70.0, 142.0) to (69.0, 141.0) is colinear with segment from (69.0, 141.0) to (67.0, 139.0)
* nDUsinh: from (973.0, -145.0) to (973.0, 27.0) is colinear with segment from (973.0, 27.0) to (974.0, 47.0)
* nyUusinh: from (1188.0, -127.0) to (1188.0, 27.0) is colinear with segment from (1188.0, 27.0) to (1189.0, 47.0)
* jnyUusinh: from (1074.0, -127.0) to (1074.0, 27.0) is colinear with segment from (1074.0, 27.0) to (1075.0, 47.0)
* dUusinh: from (442.0, -126.0) to (442.0, 27.0) is colinear with segment from (442.0, 27.0) to (443.0, 46.0)
* ndUusinh: from (572.0, -126.0) to (572.0, 27.0) is colinear with segment from (572.0, 27.0) to (573.0, 46.0)
* bUusinh: from (579.0, -129.0) to (579.0, 27.0) is colinear with segment from (579.0, 27.0) to (579.0, 28.0)
* hUusinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hUusinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* kVUusinh: from (70.0, 142.0) to (69.0, 141.0) is colinear with segment from (69.0, 141.0) to (67.0, 139.0)
* nDUusinh: from (973.0, -127.0) to (973.0, 27.0) is colinear with segment from (973.0, 27.0) to (974.0, 47.0)
* rAesinh: from (540.0, 275.0) to (540.0, 278.0) is colinear with segment from (540.0, 278.0) to (540.0, 294.0)
* rAaesinh: from (540.0, 275.0) to (540.0, 276.0) is colinear with segment from (540.0, 276.0) to (540.0, 296.0)
* bhRasinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhRasinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hRasinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hRasinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* bhRsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhRsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hRsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hRsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* bhRIsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhRIsinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hRIsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hRIsinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* bhRIisinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bhRIisinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* hRIisinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* hRIisinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* bha_rephasinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* bha_rephasinh: from (389.0, 344.0) to (389.0, 344.0) is colinear with segment from (389.0, 344.0) to (389.0, 344.0)
* ha_rephasinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* ha_rephasinh: from (368.0, 344.0) to (368.0, 344.0) is colinear with segment from (368.0, 344.0) to (368.0, 344.0)
* kSsa_rephasinh: from (266.0, 433.0) to (226.0, 385.0) is colinear with segment from (226.0, 385.0) to (102.0, 236.0)
* kVa_rephasinh: from (265.0, 432.0) to (226.0, 385.0) is colinear with segment from (226.0, 385.0) to (161.0, 308.0)
* kVa_rephasinh: from (226.0, 385.0) to (161.0, 308.0) is colinear with segment from (161.0, 308.0) to (101.0, 237.0)
* tVa_rephasinh: from (381.0, 575.0) to (333.0, 519.0) is colinear with segment from (333.0, 519.0) to (313.0, 493.0)
* tVa_rephasinh: from (257.0, 423.0) to (158.0, 303.0) is colinear with segment from (158.0, 303.0) to (102.0, 238.0)
* tTha_rephasinh: from (259.0, 426.0) to (225.0, 385.0) is colinear with segment from (225.0, 385.0) to (160.0, 306.0)
* tTha_rephasinh: from (225.0, 385.0) to (160.0, 306.0) is colinear with segment from (160.0, 306.0) to (102.0, 237.0)
* onehalf (U+00BD): from (856.0, 218.0) to (795.0, 153.0) is colinear with segment from (795.0, 153.0) to (719.0, 67.0)
* uni00B2 (U+00B2): from (289.0, 542.0) to (228.0, 476.0) is colinear with segment from (228.0, 476.0) to (152.0, 390.0)
* uni0DF4 (U+0DF4): from (1992.0, 372.0) to (1954.0, 179.0) is colinear with segment from (1954.0, 179.0) to (1952.0, 162.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* uni0DB7 (U+0DB7) has a path with no bounds (probably a single point)
* uni0DC4 (U+0DC4) has a path with no bounds (probably a single point)
* bhsinh has a path with no bounds (probably a single point)
* hsinh has a path with no bounds (probably a single point)
* bhIsinh has a path with no bounds (probably a single point)
* hIsinh has a path with no bounds (probably a single point)
* bhIisinh has a path with no bounds (probably a single point)
* hIisinh has a path with no bounds (probably a single point)
* bhUsinh has a path with no bounds (probably a single point)
* hUsinh has a path with no bounds (probably a single point)
* bhUusinh has a path with no bounds (probably a single point)
* hUusinh has a path with no bounds (probably a single point)
* bhRasinh has a path with no bounds (probably a single point)
* hRasinh has a path with no bounds (probably a single point)
* bhRsinh has a path with no bounds (probably a single point)
* hRsinh has a path with no bounds (probably a single point)
* bhRIsinh has a path with no bounds (probably a single point)
* hRIsinh has a path with no bounds (probably a single point)
* bhRIisinh has a path with no bounds (probably a single point)
* hRIisinh has a path with no bounds (probably a single point)
* bha_rephasinh has a path with no bounds (probably a single point)
* ha_rephasinh has a path with no bounds (probably a single point) [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D8A (U+0D8A): Quad(QuadBez { p0: (260.0, 545.5), p1: (251.0, 537.0), p2: (242.0, 530.0) })/Quad(QuadBez { p0: (242.0, 530.0), p1: (285.0, 554.0), p2: (336.0, 554.0) }) = 8.707370271520347 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* uni0D9A (U+0D9A): Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* uni0DA3 (U+0DA3): Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* uni0DAD (U+0DAD): Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* uni0DAD (U+0DAD): Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* uni0DB1 (U+0DB1): Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* uni0DB1 (U+0DB1): Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* uni0DBA (U+0DBA): Quad(QuadBez { p0: (363.5, 92.0), p1: (357.0, 113.0), p2: (355.0, 125.0) })/Quad(QuadBez { p0: (355.0, 125.0), p1: (354.0, 113.0), p2: (347.5, 92.0) }) = 14.22596389875178 degrees
* uni0DBB (U+0DBB): Quad(QuadBez { p0: (256.0, 542.5), p1: (245.0, 533.0), p2: (235.0, 524.0) })/Quad(QuadBez { p0: (235.0, 524.0), p1: (261.0, 539.0), p2: (292.0, 546.5) }) = 12.005573126967311 degrees
* kVasinh: Quad(QuadBez { p0: (275.0, 324.0), p1: (240.0, 315.0), p2: (203.0, 277.0) })/Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) }) = 10.546034013090223 degrees
* kVasinh: Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) })/Quad(QuadBez { p0: (205.0, 280.0), p1: (185.0, 260.0), p2: (164.5, 238.5) }) = 11.309932474020227 degrees
* nDasinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nDasinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* ksinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* ksinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tsinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tsinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* nsinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nsinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* ysinh: Quad(QuadBez { p0: (363.5, 92.0), p1: (357.0, 113.0), p2: (355.0, 125.0) })/Quad(QuadBez { p0: (355.0, 125.0), p1: (354.0, 113.0), p2: (347.5, 92.0) }) = 14.22596389875178 degrees
* rsinh: Quad(QuadBez { p0: (256.0, 542.5), p1: (245.0, 533.0), p2: (235.0, 524.0) })/Quad(QuadBez { p0: (235.0, 524.0), p1: (261.0, 539.0), p2: (292.0, 546.5) }) = 12.005573126967311 degrees
* kVsinh: Quad(QuadBez { p0: (275.0, 324.0), p1: (240.0, 315.0), p2: (203.0, 277.0) })/Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) }) = 10.546034013090223 degrees
* kVsinh: Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) })/Quad(QuadBez { p0: (205.0, 280.0), p1: (185.0, 260.0), p2: (164.5, 238.5) }) = 11.309932474020227 degrees
* nDsinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nDsinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* kIsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kIsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhIsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhIsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tIsinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tIsinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* nIsinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nIsinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* yIsinh: Quad(QuadBez { p0: (363.5, 92.0), p1: (357.0, 113.0), p2: (355.0, 125.0) })/Quad(QuadBez { p0: (355.0, 125.0), p1: (354.0, 113.0), p2: (347.5, 92.0) }) = 14.22596389875178 degrees
* rIsinh: Quad(QuadBez { p0: (256.0, 542.5), p1: (245.0, 533.0), p2: (235.0, 524.0) })/Quad(QuadBez { p0: (235.0, 524.0), p1: (261.0, 539.0), p2: (292.0, 546.5) }) = 12.005573126967311 degrees
* kVIsinh: Quad(QuadBez { p0: (275.0, 324.0), p1: (240.0, 315.0), p2: (203.0, 277.0) })/Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) }) = 10.546034013090223 degrees
* kVIsinh: Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) })/Quad(QuadBez { p0: (205.0, 280.0), p1: (185.0, 260.0), p2: (164.5, 238.5) }) = 11.309932474020227 degrees
* tThIsinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* tThIsinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* nDIsinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nDIsinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* kIisinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kIisinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhIisinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhIisinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tIisinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tIisinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* nIisinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nIisinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* yIisinh: Quad(QuadBez { p0: (363.5, 92.0), p1: (357.0, 113.0), p2: (355.0, 125.0) })/Quad(QuadBez { p0: (355.0, 125.0), p1: (354.0, 113.0), p2: (347.5, 92.0) }) = 14.22596389875178 degrees
* rIisinh: Quad(QuadBez { p0: (256.0, 542.5), p1: (245.0, 533.0), p2: (235.0, 524.0) })/Quad(QuadBez { p0: (235.0, 524.0), p1: (261.0, 539.0), p2: (292.0, 546.5) }) = 12.005573126967311 degrees
* kVIisinh: Quad(QuadBez { p0: (275.0, 324.0), p1: (240.0, 315.0), p2: (203.0, 277.0) })/Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) }) = 10.546034013090223 degrees
* kVIisinh: Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) })/Quad(QuadBez { p0: (205.0, 280.0), p1: (185.0, 260.0), p2: (164.5, 238.5) }) = 11.309932474020227 degrees
* tThIisinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* tThIisinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* nDIisinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nDIisinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* kUsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kUsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhUsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhUsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tUsinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tUsinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* nUsinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nUsinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* yUsinh: Quad(QuadBez { p0: (363.5, 92.0), p1: (357.0, 113.0), p2: (355.0, 125.0) })/Quad(QuadBez { p0: (355.0, 125.0), p1: (354.0, 113.0), p2: (347.5, 92.0) }) = 14.22596389875178 degrees
* rUsinh: Quad(QuadBez { p0: (256.0, 542.5), p1: (245.0, 533.0), p2: (235.0, 524.0) })/Quad(QuadBez { p0: (235.0, 524.0), p1: (261.0, 539.0), p2: (292.0, 546.5) }) = 12.005573126967311 degrees
* kVUsinh: Quad(QuadBez { p0: (275.0, 324.0), p1: (240.0, 315.0), p2: (203.0, 277.0) })/Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) }) = 10.546034013090223 degrees
* kVUsinh: Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) })/Quad(QuadBez { p0: (205.0, 280.0), p1: (185.0, 260.0), p2: (164.5, 238.5) }) = 11.309932474020227 degrees
* nDUsinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nDUsinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* kUusinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kUusinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhUusinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhUusinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tUusinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tUusinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* nUusinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nUusinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* yUusinh: Quad(QuadBez { p0: (363.5, 92.0), p1: (357.0, 113.0), p2: (355.0, 125.0) })/Quad(QuadBez { p0: (355.0, 125.0), p1: (354.0, 113.0), p2: (347.5, 92.0) }) = 14.22596389875178 degrees
* rUusinh: Quad(QuadBez { p0: (256.0, 542.5), p1: (245.0, 533.0), p2: (235.0, 524.0) })/Quad(QuadBez { p0: (235.0, 524.0), p1: (261.0, 539.0), p2: (292.0, 546.5) }) = 12.005573126967311 degrees
* kVUusinh: Quad(QuadBez { p0: (275.0, 324.0), p1: (240.0, 315.0), p2: (203.0, 277.0) })/Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) }) = 10.546034013090223 degrees
* kVUusinh: Line(Line { p0: (203.0, 277.0), p1: (205.0, 280.0) })/Quad(QuadBez { p0: (205.0, 280.0), p1: (185.0, 260.0), p2: (164.5, 238.5) }) = 11.309932474020227 degrees
* nDUusinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nDUusinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* rAesinh: Quad(QuadBez { p0: (264.0, 547.0), p1: (255.0, 539.0), p2: (246.0, 532.0) })/Quad(QuadBez { p0: (246.0, 532.0), p1: (288.0, 554.0), p2: (336.0, 554.0) }) = 10.229008287359505 degrees
* rAaesinh: Quad(QuadBez { p0: (264.0, 547.0), p1: (255.0, 539.0), p2: (246.0, 532.0) })/Quad(QuadBez { p0: (246.0, 532.0), p1: (288.0, 554.0), p2: (336.0, 554.0) }) = 10.229008287359505 degrees
* kRasinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kRasinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhRasinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhRasinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tRasinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tRasinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* nDRasinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* nDRasinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* kRsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kRsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhRsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhRsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tRsinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tRsinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* kRIsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kRIsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhRIsinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhRIsinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tRIsinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tRIsinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* kRIisinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* kRIisinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jhRIisinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jhRIisinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* tRIisinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* tRIisinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* ka_rephasinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* ka_rephasinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* jha_rephasinh: Quad(QuadBez { p0: (297.0, 324.0), p1: (262.0, 315.0), p2: (225.0, 277.0) })/Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) }) = 7.366203893225962 degrees
* jha_rephasinh: Line(Line { p0: (225.0, 277.0), p1: (228.0, 281.0) })/Quad(QuadBez { p0: (228.0, 281.0), p1: (208.0, 261.0), p2: (186.5, 239.0) }) = 8.130102354156005 degrees
* ta_rephasinh: Quad(QuadBez { p0: (93.0, 156.0), p1: (90.0, 153.0), p2: (88.0, 151.0) })/Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) }) = 0.0000012074182697257333 degrees
* ta_rephasinh: Line(Line { p0: (88.0, 151.0), p1: (90.0, 153.0) })/Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) = 0.0000012074182697257333 degrees
* na_rephasinh: Quad(QuadBez { p0: (328.0, 320.0), p1: (304.0, 313.0), p2: (287.0, 281.0) })/Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) }) = 9.544525565558107 degrees
* na_rephasinh: Line(Line { p0: (287.0, 281.0), p1: (288.0, 284.0) })/Quad(QuadBez { p0: (288.0, 284.0), p1: (268.0, 251.0), p2: (238.0, 225.5) }) = 12.783453941424375 degrees
* ya_rephasinh: Quad(QuadBez { p0: (363.5, 92.0), p1: (357.0, 113.0), p2: (355.0, 125.0) })/Quad(QuadBez { p0: (355.0, 125.0), p1: (354.0, 113.0), p2: (347.5, 92.0) }) = 14.22596389875178 degrees
* kSsa_rephasinh: Quad(QuadBez { p0: (291.0, 50.0), p1: (278.0, 70.0), p2: (277.0, 86.0) })/Quad(QuadBez { p0: (277.0, 86.0), p1: (275.0, 69.0), p2: (264.0, 51.0) }) = 10.28617118275434 degrees
* kVa_rephasinh: Quad(QuadBez { p0: (291.0, 50.0), p1: (278.0, 70.0), p2: (277.0, 86.0) })/Quad(QuadBez { p0: (277.0, 86.0), p1: (276.0, 79.0), p2: (273.5, 70.0) }) = 11.70643672915336 degrees
* dDha_rephasinh: Quad(QuadBez { p0: (515.0, 91.0), p1: (506.0, 110.0), p2: (503.0, 128.0) })/Quad(QuadBez { p0: (503.0, 128.0), p1: (502.0, 112.0), p2: (492.0, 91.0) }) = 13.038656583022993 degrees
* yasign_rephasinh: Quad(QuadBez { p0: (202.0, 771.0), p1: (165.0, 756.0), p2: (146.0, 726.0) })/Quad(QuadBez { p0: (146.0, 726.0), p1: (160.0, 740.0), p2: (180.5, 746.5) }) = 12.652556500557937 degrees
* yasign_repha_aasignsinh: Quad(QuadBez { p0: (202.0, 771.0), p1: (165.0, 756.0), p2: (146.0, 726.0) })/Quad(QuadBez { p0: (146.0, 726.0), p1: (160.0, 740.0), p2: (180.5, 746.5) }) = 12.652556500557937 degrees
* yasign_repha_usignsinh: Quad(QuadBez { p0: (202.0, 771.0), p1: (165.0, 756.0), p2: (146.0, 726.0) })/Quad(QuadBez { p0: (146.0, 726.0), p1: (160.0, 740.0), p2: (180.5, 746.5) }) = 12.652556500557937 degrees
* yasign_repha_uusignsinh: Quad(QuadBez { p0: (205.0, 771.0), p1: (168.0, 756.0), p2: (149.0, 726.0) })/Quad(QuadBez { p0: (149.0, 726.0), p1: (163.0, 740.0), p2: (183.5, 746.5) }) = 12.652556500557937 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* uni0D85 (U+0D85): Line(Line { p0: (388.0, -197.0), p1: (387.0, -10.0) }) (angle: 90.31 degrees, expected: 90.00 degrees)
* uni0D85 (U+0D85): Line(Line { p0: (387.0, 62.0), p1: (385.0, 337.0) }) (angle: 90.42 degrees, expected: 90.00 degrees)
* uni0D86 (U+0D86): Line(Line { p0: (388.0, -202.0), p1: (387.0, -15.0) }) (angle: 90.31 degrees, expected: 90.00 degrees)
* uni0D86 (U+0D86): Line(Line { p0: (387.0, 57.0), p1: (385.0, 332.0) }) (angle: 90.42 degrees, expected: 90.00 degrees)
* uni0D87 (U+0D87): Line(Line { p0: (388.0, -197.0), p1: (387.0, -10.0) }) (angle: 90.31 degrees, expected: 90.00 degrees)
* uni0D87 (U+0D87): Line(Line { p0: (387.0, 62.0), p1: (385.0, 337.0) }) (angle: 90.42 degrees, expected: 90.00 degrees)
* uni0D88 (U+0D88): Line(Line { p0: (388.0, -197.0), p1: (387.0, -10.0) }) (angle: 90.31 degrees, expected: 90.00 degrees)
* uni0D88 (U+0D88): Line(Line { p0: (387.0, 62.0), p1: (385.0, 337.0) }) (angle: 90.42 degrees, expected: 90.00 degrees)
* uni0DE6 (U+0DE6): Line(Line { p0: (128.0, 134.0), p1: (129.0, 564.0) }) (angle: 89.87 degrees, expected: 90.00 degrees)
* four (U+0034): Line(Line { p0: (337.0, 188.0), p1: (5.0, 189.0) }) (angle: 179.83 degrees, expected: 180.00 degrees)
* four.osf: Line(Line { p0: (337.0, 188.0), p1: (5.0, 189.0) }) (angle: 179.83 degrees, expected: 180.00 degrees)
* onequarter (U+00BC): Line(Line { p0: (793.0, 114.0), p1: (566.0, 113.0) }) (angle: -179.75 degrees, expected: -180.00 degrees)
* threequarters (U+00BE): Line(Line { p0: (829.0, 114.0), p1: (602.0, 113.0) }) (angle: -179.75 degrees, expected: -180.00 degrees)
* uni2074 (U+2074): Line(Line { p0: (267.0, 441.0), p1: (40.0, 440.0) }) (angle: -179.75 degrees, expected: -180.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* uni0DAD (U+0DAD): Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* uni0DB7 (U+0DB7): Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* uni0DC4 (U+0DC4): Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* tVasinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tThasinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tsinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bhsinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* hsinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* tVsinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tThsinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tIsinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bhIsinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* hIsinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* tVIsinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tThIsinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* jhIisinh: Line(Line { p0: (1208.0, 737.0), p1: (1208.0, 737.0) }) has the same coordinates as a previous segment.
* ddIisinh: Line(Line { p0: (655.0, 737.0), p1: (655.0, 737.0) }) has the same coordinates as a previous segment.
* tIisinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* dhIisinh: Line(Line { p0: (641.0, 737.0), p1: (641.0, 737.0) }) has the same coordinates as a previous segment.
* bhIisinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* mIisinh: Line(Line { p0: (626.0, 737.0), p1: (626.0, 737.0) }) has the same coordinates as a previous segment.
* mbIisinh: Line(Line { p0: (656.0, 737.0), p1: (656.0, 737.0) }) has the same coordinates as a previous segment.
* vIisinh: Line(Line { p0: (622.0, 737.0), p1: (622.0, 737.0) }) has the same coordinates as a previous segment.
* hIisinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* kVIisinh: Line(Line { p0: (1164.0, 737.0), p1: (1164.0, 737.0) }) has the same coordinates as a previous segment.
* tVIisinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tThIisinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* nDhIisinh: Line(Line { p0: (1178.0, 737.0), p1: (1178.0, 737.0) }) has the same coordinates as a previous segment.
* dVIisinh: Line(Line { p0: (772.0, 737.0), p1: (772.0, 737.0) }) has the same coordinates as a previous segment.
* tUsinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bhUsinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* hUsinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* tVUsinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tThUsinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tUusinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bhUusinh: Line(Line { p0: (389.0, 344.0), p1: (388.0, 344.0) }) has the same coordinates as a previous segment.
* hUusinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* tVUusinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tThUusinh: Quad(QuadBez { p0: (71.0, 155.0), p1: (69.0, 154.0), p2: (67.0, 151.0) }) has the same coordinates as a previous segment.
* tRasinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bhRasinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* hRasinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* tRsinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bhRsinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* hRsinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* tRIsinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bhRIsinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* hRIsinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* jhRIisinh: Line(Line { p0: (1208.0, 737.0), p1: (1208.0, 737.0) }) has the same coordinates as a previous segment.
* ddRIisinh: Line(Line { p0: (655.0, 737.0), p1: (655.0, 737.0) }) has the same coordinates as a previous segment.
* tRIisinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* dhRIisinh: Line(Line { p0: (641.0, 737.0), p1: (641.0, 737.0) }) has the same coordinates as a previous segment.
* bhRIisinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* mRIisinh: Line(Line { p0: (626.0, 737.0), p1: (626.0, 737.0) }) has the same coordinates as a previous segment.
* vRIisinh: Line(Line { p0: (622.0, 737.0), p1: (622.0, 737.0) }) has the same coordinates as a previous segment.
* hRIisinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment.
* ta_rephasinh: Quad(QuadBez { p0: (90.0, 153.0), p1: (89.0, 152.0), p2: (88.0, 151.0) }) has the same coordinates as a previous segment.
* bha_rephasinh: Line(Line { p0: (389.0, 344.0), p1: (389.0, 344.0) }) has the same coordinates as a previous segment.
* ha_rephasinh: Line(Line { p0: (368.0, 344.0), p1: (368.0, 344.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>


<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 16 | 13 | 79 | 50 | 
| 10% | 8% | 50% | 32% | 



