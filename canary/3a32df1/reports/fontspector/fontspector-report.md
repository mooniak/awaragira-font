## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[22] fonts/ttf/AwaragiraCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. (os2_metrics_match_hhea)</summary>
    <div>








- 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
  
  


- 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** No GF glyphset was found to be supported >80%, so language shaping support couldn't get checked. [code: no-glyphset-supported]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Directory name in GFonts repo structure must
    match NameID 1 of the regular. (googlefonts/repo/dirname_matches_nameid_1)</summary>
    <div>








- 🔥 **FAIL** Family name on the name table ('Awaragira CANARY') does not match directory name in the repo structure ('ttf'). Expected 'awaragiracanary'. [code: mismatch]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? (googlefonts/name/version_format)</summary>
    <div>








- 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000.

The "Version" prefix is a recommendation given by the OpenType spec.

Current version string is: "Version 0.500; [3a32df1]-dev" [code: bad-version-strings]
  
  


- 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000.

The "Version" prefix is a recommendation given by the OpenType spec.

Current version string is: "Version 0.500; [3a32df1]-dev" [code: bad-version-strings]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. (googlefonts/render_own_name)</summary>
    <div>








- 🔥 **FAIL** .notdef glyphs were found when attempting to render Awaragira CANARY [code: render-own-name]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (googlefonts/use_typo_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) was NOT set. [code: missing-os2-fsselection-bit7]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema (googlefonts/vertical_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.sTypoLineGap is 200; it should be 0 [code: bad-OS/2.sTypoLineGap]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

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
* uni0DB7 (U+0DB7): found 2, expected one of: [1, 3, 4]
* uni0DB9 (U+0DB9): found 1, expected one of: [2, 3]
* uni0DC4 (U+0DC4): found 2, expected one of: [1, 3, 4] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking Vertical Metric linegaps. (linegaps)</summary>
    <div>








- ⚠️ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

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
* NameMe.880
* mooniak
* iisignsinh.alt2
* iisignsinh.alt8 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* tRsinh
* shRsinh
* ksinh
* nysinh
* rIisinh
* bhRsinh
* hRsinh
* nsinh
* nnIisinh
* gRsinh
* rIsinh
* lsinh
* jnyRsinh
* nngsinh
* nyRsinh
* jnysinh
* bhsinh
* gsinh
* pUsinh
* shsinh
* tsinh
* kRsinh
* hsinh [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uni0DC2 (U+0DC2): from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* onehalf (U+00BD): from (803.0, 205.0) to (746.0, 144.0) is colinear with segment from (746.0, 144.0) to (675.0, 63.0)
* uni00B2 (U+00B2): from (271.0, 509.0) to (214.0, 447.0) is colinear with segment from (214.0, 447.0) to (143.0, 366.0)
* uni0DF4 (U+0DF4): from (1870.0, 349.0) to (1834.0, 168.0) is colinear with segment from (1834.0, 168.0) to (1832.0, 152.0)
* bUsinh: from (543.0, -136.0) to (543.0, 25.0) is colinear with segment from (543.0, 25.0) to (543.0, 26.0)
* bUusinh: from (543.0, -121.0) to (543.0, 25.0) is colinear with segment from (543.0, 25.0) to (543.0, 26.0)
* dUsinh: from (415.0, -136.0) to (415.0, 25.0) is colinear with segment from (415.0, 25.0) to (416.0, 44.0)
* dUusinh: from (415.0, -119.0) to (415.0, 25.0) is colinear with segment from (415.0, 25.0) to (416.0, 44.0)
* jnyUsinh: from (1008.0, -136.0) to (1008.0, 25.0) is colinear with segment from (1008.0, 25.0) to (1009.0, 44.0)
* jnyUusinh: from (1008.0, -119.0) to (1008.0, 25.0) is colinear with segment from (1008.0, 25.0) to (1009.0, 44.0)
* kSssinh: from (857.0, 389.0) to (857.0, 389.0) is colinear with segment from (857.0, 389.0) to (930.0, 389.0)
* kSsIsinh: from (857.0, 389.0) to (857.0, 389.0) is colinear with segment from (857.0, 389.0) to (930.0, 389.0)
* kSsIisinh: from (857.0, 389.0) to (857.0, 389.0) is colinear with segment from (857.0, 389.0) to (930.0, 389.0)
* kSsUsinh: from (857.0, 389.0) to (857.0, 389.0) is colinear with segment from (857.0, 389.0) to (930.0, 389.0)
* kSsUusinh: from (857.0, 389.0) to (857.0, 389.0) is colinear with segment from (857.0, 389.0) to (930.0, 389.0)
* kSsasinh: from (857.0, 389.0) to (857.0, 389.0) is colinear with segment from (857.0, 389.0) to (930.0, 389.0)
* nDUsinh: from (913.0, -136.0) to (913.0, 25.0) is colinear with segment from (913.0, 25.0) to (914.0, 44.0)
* nDUusinh: from (913.0, -119.0) to (913.0, 25.0) is colinear with segment from (913.0, 25.0) to (914.0, 44.0)
* ndUsinh: from (537.0, -136.0) to (537.0, 25.0) is colinear with segment from (537.0, 25.0) to (538.0, 44.0)
* ndUusinh: from (537.0, -119.0) to (537.0, 25.0) is colinear with segment from (537.0, 25.0) to (538.0, 44.0)
* nyUsinh: from (1115.0, -136.0) to (1115.0, 25.0) is colinear with segment from (1115.0, 25.0) to (1116.0, 44.0)
* nyUusinh: from (1115.0, -119.0) to (1115.0, 25.0) is colinear with segment from (1115.0, 25.0) to (1116.0, 44.0)
* rAaesinh: from (507.0, 257.0) to (507.0, 259.0) is colinear with segment from (507.0, 259.0) to (507.0, 278.0)
* rAesinh: from (507.0, 257.0) to (507.0, 261.0) is colinear with segment from (507.0, 261.0) to (507.0, 276.0)
* sssinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* ssIsinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* ssIisinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* ssRsinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* ssRasinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* ssUsinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* ssUusinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* kSsa_rephasinh: from (249.0, 406.0) to (212.0, 361.0) is colinear with segment from (212.0, 361.0) to (95.0, 222.0)
* kVa_rephasinh: from (249.0, 406.0) to (212.0, 361.0) is colinear with segment from (212.0, 361.0) to (151.0, 289.0)
* kVa_rephasinh: from (212.0, 361.0) to (151.0, 289.0) is colinear with segment from (151.0, 289.0) to (95.0, 222.0)
* ssa_rephasinh: from (347.0, 389.0) to (347.0, 389.0) is colinear with segment from (347.0, 389.0) to (420.0, 389.0)
* tTha_rephasinh: from (243.0, 400.0) to (211.0, 361.0) is colinear with segment from (211.0, 361.0) to (150.0, 287.0)
* tTha_rephasinh: from (211.0, 361.0) to (150.0, 287.0) is colinear with segment from (150.0, 287.0) to (96.0, 222.0)
* tVa_rephasinh: from (358.0, 540.0) to (313.0, 487.0) is colinear with segment from (313.0, 487.0) to (294.0, 463.0)
* tVa_rephasinh: from (242.0, 398.0) to (148.0, 284.0) is colinear with segment from (148.0, 284.0) to (95.0, 223.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D8A (U+0D8A): Quad(QuadBez { p0: (244.0, 512.0), p1: (235.0, 504.0), p2: (227.0, 497.0) })/Quad(QuadBez { p0: (227.0, 497.0), p1: (267.0, 520.0), p2: (315.0, 520.0) }) = 11.28702332709511 degrees
* uni0D9A (U+0D9A): Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* uni0D9A (U+0D9A): Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* uni0D9A (U+0D9A): Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* uni0DA3 (U+0DA3): Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* uni0DA3 (U+0DA3): Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* uni0DA3 (U+0DA3): Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* uni0DAD (U+0DAD): Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* uni0DAD (U+0DAD): Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* uni0DBA (U+0DBA): Quad(QuadBez { p0: (341.0, 86.0), p1: (335.0, 105.0), p2: (333.0, 117.0) })/Quad(QuadBez { p0: (333.0, 117.0), p1: (332.0, 105.0), p2: (326.0, 86.0) }) = 14.22596389875178 degrees
* uni0DBB (U+0DBB): Quad(QuadBez { p0: (240.5, 509.0), p1: (230.0, 500.0), p2: (220.0, 491.0) })/Quad(QuadBez { p0: (220.0, 491.0), p1: (244.0, 505.0), p2: (273.5, 512.5) }) = 11.730775332287395 degrees
* uni0DC6 (U+0DC6): Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* fsinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 431.0), p2: (341.0, 454.0) }) = 13.50980395328139 degrees
* fIsinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* fIisinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* fRsinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 431.0), p2: (341.0, 454.0) }) = 13.50980395328139 degrees
* fRIsinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* fRIisinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* fRasinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* fUsinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* fUusinh: Quad(QuadBez { p0: (324.0, 449.0), p1: (330.0, 430.0), p2: (331.0, 418.0) })/Quad(QuadBez { p0: (331.0, 418.0), p1: (333.0, 430.0), p2: (339.0, 449.0) }) = 14.22596389875178 degrees
* jhsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhIsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhIsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhIsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhIsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhIisinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhIisinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhIisinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhIisinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhRsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhRsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhRsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhRsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhRIsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhRIsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhRIsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhRIsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhRIisinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhRIisinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhRIisinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhRIisinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhRasinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhRasinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhRasinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhRasinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhUsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhUsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhUsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhUsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* jhUusinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jhUusinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jhUusinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jhUusinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* ksinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* ksinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* ksinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* ksinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kIsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kIsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kIsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kIsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kIisinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kIisinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kIisinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kIisinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kRsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kRsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kRsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kRsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kRIsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kRIsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kRIsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kRIsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kRIisinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kRIisinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kRIisinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kRIisinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kRasinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kRasinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kRasinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kRasinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kUsinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kUsinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kUsinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kUsinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kUusinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* kUusinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* kUusinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* kUusinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kVsinh: Line(Line { p0: (63.0, 130.0), p1: (65.0, 132.0) })/Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) = 0.0000012074182697257333 degrees
* kVsinh: Quad(QuadBez { p0: (258.5, 304.0), p1: (226.0, 295.0), p2: (191.0, 260.0) })/Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) }) = 11.309932474020195 degrees
* kVsinh: Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) })/Quad(QuadBez { p0: (193.0, 263.0), p1: (175.0, 244.0), p2: (155.0, 224.0) }) = 9.761774775042262 degrees
* kVIsinh: Line(Line { p0: (63.0, 130.0), p1: (65.0, 132.0) })/Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) = 0.0000012074182697257333 degrees
* kVIsinh: Quad(QuadBez { p0: (258.5, 304.0), p1: (226.0, 295.0), p2: (191.0, 260.0) })/Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) }) = 11.309932474020195 degrees
* kVIsinh: Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) })/Quad(QuadBez { p0: (193.0, 263.0), p1: (175.0, 244.0), p2: (155.0, 224.0) }) = 9.761774775042262 degrees
* kVIisinh: Line(Line { p0: (63.0, 130.0), p1: (65.0, 132.0) })/Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) = 0.0000012074182697257333 degrees
* kVIisinh: Quad(QuadBez { p0: (258.5, 304.0), p1: (226.0, 295.0), p2: (191.0, 260.0) })/Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) }) = 11.309932474020195 degrees
* kVIisinh: Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) })/Quad(QuadBez { p0: (193.0, 263.0), p1: (175.0, 244.0), p2: (155.0, 224.0) }) = 9.761774775042262 degrees
* kVUsinh: Line(Line { p0: (63.0, 130.0), p1: (65.0, 132.0) })/Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) = 0.0000012074182697257333 degrees
* kVUsinh: Quad(QuadBez { p0: (258.5, 304.0), p1: (226.0, 295.0), p2: (191.0, 260.0) })/Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) }) = 11.309932474020195 degrees
* kVUsinh: Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) })/Quad(QuadBez { p0: (193.0, 263.0), p1: (175.0, 244.0), p2: (155.0, 224.0) }) = 9.761774775042262 degrees
* kVUusinh: Line(Line { p0: (63.0, 130.0), p1: (65.0, 132.0) })/Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) = 0.0000012074182697257333 degrees
* kVUusinh: Quad(QuadBez { p0: (258.5, 304.0), p1: (226.0, 295.0), p2: (191.0, 260.0) })/Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) }) = 11.309932474020195 degrees
* kVUusinh: Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) })/Quad(QuadBez { p0: (193.0, 263.0), p1: (175.0, 244.0), p2: (155.0, 224.0) }) = 9.761774775042262 degrees
* kVasinh: Line(Line { p0: (63.0, 130.0), p1: (65.0, 132.0) })/Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) = 0.0000012074182697257333 degrees
* kVasinh: Quad(QuadBez { p0: (258.5, 304.0), p1: (226.0, 295.0), p2: (191.0, 260.0) })/Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) }) = 11.309932474020195 degrees
* kVasinh: Line(Line { p0: (191.0, 260.0), p1: (193.0, 263.0) })/Quad(QuadBez { p0: (193.0, 263.0), p1: (175.0, 244.0), p2: (155.0, 224.0) }) = 9.761774775042262 degrees
* rsinh: Quad(QuadBez { p0: (240.5, 509.0), p1: (230.0, 500.0), p2: (220.0, 491.0) })/Quad(QuadBez { p0: (220.0, 491.0), p1: (244.0, 505.0), p2: (273.5, 512.5) }) = 11.730775332287395 degrees
* rAaesinh: Quad(QuadBez { p0: (248.0, 513.0), p1: (240.0, 506.0), p2: (232.0, 500.0) })/Quad(QuadBez { p0: (232.0, 500.0), p1: (270.0, 520.0), p2: (315.0, 520.0) }) = 9.11135704478399 degrees
* rAesinh: Quad(QuadBez { p0: (248.0, 513.0), p1: (240.0, 506.0), p2: (232.0, 500.0) })/Quad(QuadBez { p0: (232.0, 500.0), p1: (270.0, 520.0), p2: (315.0, 520.0) }) = 9.11135704478399 degrees
* rIsinh: Quad(QuadBez { p0: (240.5, 509.0), p1: (230.0, 500.0), p2: (220.0, 491.0) })/Quad(QuadBez { p0: (220.0, 491.0), p1: (244.0, 505.0), p2: (273.5, 512.5) }) = 11.730775332287395 degrees
* rIisinh: Quad(QuadBez { p0: (240.5, 509.0), p1: (230.0, 500.0), p2: (220.0, 491.0) })/Quad(QuadBez { p0: (220.0, 491.0), p1: (244.0, 505.0), p2: (273.5, 512.5) }) = 11.730775332287395 degrees
* rUsinh: Quad(QuadBez { p0: (240.5, 509.0), p1: (230.0, 500.0), p2: (220.0, 491.0) })/Quad(QuadBez { p0: (220.0, 491.0), p1: (244.0, 505.0), p2: (273.5, 512.5) }) = 11.730775332287395 degrees
* rUusinh: Quad(QuadBez { p0: (240.5, 509.0), p1: (230.0, 500.0), p2: (220.0, 491.0) })/Quad(QuadBez { p0: (220.0, 491.0), p1: (244.0, 505.0), p2: (273.5, 512.5) }) = 11.730775332287395 degrees
* tsinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tsinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tIsinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tIsinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tIisinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tIisinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tRsinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tRsinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tRIsinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tRIsinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tRIisinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tRIisinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tRasinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tRasinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tThsinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tThsinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tThIsinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tThIsinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tThIisinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tThIisinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tThUsinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tThUsinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tThUusinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tThUusinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tThasinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tThasinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tUsinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tUsinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tUusinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* tUusinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* tVsinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tVsinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tVIsinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tVIsinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tVIisinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tVIisinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tVUsinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tVUsinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tVUusinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tVUusinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* tVasinh: Line(Line { p0: (67.0, 146.0), p1: (63.0, 142.0) })/Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) }) = 0.0000012074182697257333 degrees
* tVasinh: Line(Line { p0: (63.0, 142.0), p1: (65.0, 144.0) })/Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) = 0.0000012074182697257333 degrees
* ysinh: Quad(QuadBez { p0: (341.0, 86.0), p1: (335.0, 105.0), p2: (333.0, 117.0) })/Quad(QuadBez { p0: (333.0, 117.0), p1: (332.0, 105.0), p2: (326.0, 86.0) }) = 14.22596389875178 degrees
* yIsinh: Quad(QuadBez { p0: (341.0, 86.0), p1: (335.0, 105.0), p2: (333.0, 117.0) })/Quad(QuadBez { p0: (333.0, 117.0), p1: (332.0, 105.0), p2: (326.0, 86.0) }) = 14.22596389875178 degrees
* yIisinh: Quad(QuadBez { p0: (341.0, 86.0), p1: (335.0, 105.0), p2: (333.0, 117.0) })/Quad(QuadBez { p0: (333.0, 117.0), p1: (332.0, 105.0), p2: (326.0, 86.0) }) = 14.22596389875178 degrees
* yUsinh: Quad(QuadBez { p0: (341.0, 86.0), p1: (335.0, 105.0), p2: (333.0, 117.0) })/Quad(QuadBez { p0: (333.0, 117.0), p1: (332.0, 105.0), p2: (326.0, 86.0) }) = 14.22596389875178 degrees
* yUusinh: Quad(QuadBez { p0: (341.0, 86.0), p1: (335.0, 105.0), p2: (333.0, 117.0) })/Quad(QuadBez { p0: (333.0, 117.0), p1: (332.0, 105.0), p2: (326.0, 86.0) }) = 14.22596389875178 degrees
* yasign_repha_aasignsinh: Quad(QuadBez { p0: (190.0, 723.5), p1: (155.0, 709.0), p2: (137.0, 681.0) })/Quad(QuadBez { p0: (137.0, 681.0), p1: (150.0, 694.0), p2: (169.0, 700.5) }) = 12.26477372789237 degrees
* yasign_repha_usignsinh: Quad(QuadBez { p0: (190.0, 723.5), p1: (155.0, 709.0), p2: (137.0, 681.0) })/Quad(QuadBez { p0: (137.0, 681.0), p1: (150.0, 694.0), p2: (169.0, 700.5) }) = 12.26477372789237 degrees
* yasign_repha_uusignsinh: Quad(QuadBez { p0: (193.0, 723.5), p1: (158.0, 709.0), p2: (140.0, 681.0) })/Quad(QuadBez { p0: (140.0, 681.0), p1: (153.0, 694.0), p2: (172.0, 700.5) }) = 12.26477372789237 degrees
* jha_rephasinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* jha_rephasinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* jha_rephasinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* jha_rephasinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* kSsa_rephasinh: Quad(QuadBez { p0: (264.5, 64.5), p1: (261.0, 73.0), p2: (260.0, 81.0) })/Quad(QuadBez { p0: (260.0, 81.0), p1: (259.0, 66.0), p2: (248.0, 48.0) }) = 10.9390911831921 degrees
* ka_rephasinh: Line(Line { p0: (87.0, 134.0), p1: (83.0, 130.0) })/Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) }) = 0.0000012074182697257333 degrees
* ka_rephasinh: Line(Line { p0: (83.0, 130.0), p1: (85.0, 132.0) })/Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) = 0.0000012074182697257333 degrees
* ka_rephasinh: Quad(QuadBez { p0: (278.5, 304.0), p1: (246.0, 295.0), p2: (211.0, 260.0) })/Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) }) = 11.309932474020195 degrees
* ka_rephasinh: Line(Line { p0: (211.0, 260.0), p1: (213.0, 263.0) })/Quad(QuadBez { p0: (213.0, 263.0), p1: (195.0, 244.0), p2: (175.0, 224.0) }) = 9.761774775042262 degrees
* ta_rephasinh: Line(Line { p0: (87.0, 146.0), p1: (83.0, 142.0) })/Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) }) = 0.0000012074182697257333 degrees
* ta_rephasinh: Line(Line { p0: (83.0, 142.0), p1: (85.0, 144.0) })/Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) = 0.0000012074182697257333 degrees
* ya_rephasinh: Quad(QuadBez { p0: (341.0, 86.0), p1: (335.0, 105.0), p2: (333.0, 117.0) })/Quad(QuadBez { p0: (333.0, 117.0), p1: (332.0, 105.0), p2: (326.0, 86.0) }) = 14.22596389875178 degrees
* yasign_rephasinh: Quad(QuadBez { p0: (190.0, 723.5), p1: (155.0, 709.0), p2: (137.0, 681.0) })/Quad(QuadBez { p0: (137.0, 681.0), p1: (150.0, 694.0), p2: (169.0, 700.5) }) = 12.26477372789237 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* uni0D9A (U+0D9A): Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* uni0DAD (U+0DAD): Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* jhsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhIsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhIisinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhRsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhRIsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhRIisinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhRasinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhUsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* jhUusinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* ksinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kIsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kIisinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kRsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kRIsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kRIisinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kRasinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kUsinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kUusinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* kVsinh: Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) has the same coordinates as a previous segment.
* kVIsinh: Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) has the same coordinates as a previous segment.
* kVIisinh: Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) has the same coordinates as a previous segment.
* kVUsinh: Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) has the same coordinates as a previous segment.
* kVUusinh: Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) has the same coordinates as a previous segment.
* kVasinh: Quad(QuadBez { p0: (65.0, 132.0), p1: (64.0, 131.0), p2: (63.0, 130.0) }) has the same coordinates as a previous segment.
* tsinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tIsinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tIisinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tRsinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tRIsinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tRIisinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tRasinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tThsinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tThIsinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tThIisinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tThUsinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tThUusinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tThasinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tUsinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tUusinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment.
* tVsinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tVIsinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tVIisinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tVUsinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tVUusinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* tVasinh: Quad(QuadBez { p0: (65.0, 144.0), p1: (64.0, 143.0), p2: (63.0, 142.0) }) has the same coordinates as a previous segment.
* jha_rephasinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* ka_rephasinh: Quad(QuadBez { p0: (85.0, 132.0), p1: (84.0, 131.0), p2: (83.0, 130.0) }) has the same coordinates as a previous segment.
* ta_rephasinh: Quad(QuadBez { p0: (85.0, 144.0), p1: (84.0, 143.0), p2: (83.0, 142.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* uni0D85 (U+0D85): Line(Line { p0: (364.0, -185.0), p1: (363.0, -9.0) }) (angle: 90.33 degrees, expected: 90.00 degrees)
* uni0D85 (U+0D85): Line(Line { p0: (363.0, 57.0), p1: (361.0, 317.0) }) (angle: 90.44 degrees, expected: 90.00 degrees)
* uni0D86 (U+0D86): Line(Line { p0: (364.0, -190.0), p1: (363.0, -14.0) }) (angle: 90.33 degrees, expected: 90.00 degrees)
* uni0D86 (U+0D86): Line(Line { p0: (363.0, 52.0), p1: (361.0, 312.0) }) (angle: 90.44 degrees, expected: 90.00 degrees)
* uni0D87 (U+0D87): Line(Line { p0: (364.0, -185.0), p1: (363.0, -9.0) }) (angle: 90.33 degrees, expected: 90.00 degrees)
* uni0D87 (U+0D87): Line(Line { p0: (363.0, 57.0), p1: (361.0, 317.0) }) (angle: 90.44 degrees, expected: 90.00 degrees)
* uni0D88 (U+0D88): Line(Line { p0: (364.0, -185.0), p1: (363.0, -9.0) }) (angle: 90.33 degrees, expected: 90.00 degrees)
* uni0D88 (U+0D88): Line(Line { p0: (363.0, 57.0), p1: (361.0, 317.0) }) (angle: 90.44 degrees, expected: 90.00 degrees)
* uni0DE6 (U+0DE6): Line(Line { p0: (120.0, 126.0), p1: (121.0, 529.0) }) (angle: 89.86 degrees, expected: 90.00 degrees)
* four (U+0034): Line(Line { p0: (316.0, 176.0), p1: (5.0, 177.0) }) (angle: 179.82 degrees, expected: 180.00 degrees)
* four.osf: Line(Line { p0: (316.0, 176.0), p1: (5.0, 177.0) }) (angle: 179.82 degrees, expected: 180.00 degrees)
* onequarter (U+00BC): Line(Line { p0: (744.0, 107.0), p1: (531.0, 106.0) }) (angle: -179.73 degrees, expected: -180.00 degrees)
* threequarters (U+00BE): Line(Line { p0: (778.0, 107.0), p1: (565.0, 106.0) }) (angle: -179.73 degrees, expected: -180.00 degrees)
* uni2074 (U+2074): Line(Line { p0: (251.0, 414.0), p1: (38.0, 413.0) }) (angle: -179.73 degrees, expected: -180.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'MNIK' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[4] fonts/ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent (family/win_ascent_and_descent)</summary>
    <div>








- 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 323, but got 200 instead. The lowest point is in glyph 'uusignsinh.sub'. [code: descent]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** fonts/ttf/AwaragiraCANARY-Regular.ttf missing required codepoints:

* 0x0022: QUOTATION MARK
* 0x0023: NUMBER SIGN
* 0x0024: DOLLAR SIGN
* 0x0025: PERCENT SIGN
* 0x0026: AMPERSAND
* 0x0027: APOSTROPHE
* 0x002B: PLUS SIGN
* 0x003C: LESS-THAN SIGN
* 0x003D: EQUALS SIGN
* 0x003E: GREATER-THAN SIGN
* 0x0040: COMMERCIAL AT
* 0x0041: LATIN CAPITAL LETTER A
* 0x0042: LATIN CAPITAL LETTER B
* 0x0043: LATIN CAPITAL LETTER C
* 0x0044: LATIN CAPITAL LETTER D
* 0x0045: LATIN CAPITAL LETTER E
* 0x0046: LATIN CAPITAL LETTER F
* 0x0047: LATIN CAPITAL LETTER G
* 0x0048: LATIN CAPITAL LETTER H
* 0x0049: LATIN CAPITAL LETTER I
* 0x004A: LATIN CAPITAL LETTER J
* 0x004B: LATIN CAPITAL LETTER K
* 0x004C: LATIN CAPITAL LETTER L
* 0x004D: LATIN CAPITAL LETTER M
* 0x004E: LATIN CAPITAL LETTER N
* 0x004F: LATIN CAPITAL LETTER O
* 0x0050: LATIN CAPITAL LETTER P
* 0x0051: LATIN CAPITAL LETTER Q
* 0x0052: LATIN CAPITAL LETTER R
* 0x0053: LATIN CAPITAL LETTER S
* 0x0054: LATIN CAPITAL LETTER T
* 0x0055: LATIN CAPITAL LETTER U
* 0x0056: LATIN CAPITAL LETTER V
* 0x0057: LATIN CAPITAL LETTER W
* 0x0058: LATIN CAPITAL LETTER X
* 0x0059: LATIN CAPITAL LETTER Y
* 0x005A: LATIN CAPITAL LETTER Z
* 0x005B: LEFT SQUARE BRACKET
* 0x005C: REVERSE SOLIDUS
* 0x005D: RIGHT SQUARE BRACKET
* 0x005E: CIRCUMFLEX ACCENT
* 0x005F: LOW LINE
* 0x0060: GRAVE ACCENT
* 0x0061: LATIN SMALL LETTER A
* 0x0062: LATIN SMALL LETTER B
* 0x0063: LATIN SMALL LETTER C
* 0x0064: LATIN SMALL LETTER D
* 0x0065: LATIN SMALL LETTER E
* 0x0066: LATIN SMALL LETTER F
* 0x0067: LATIN SMALL LETTER G
* 0x0068: LATIN SMALL LETTER H
* 0x0069: LATIN SMALL LETTER I
* 0x006A: LATIN SMALL LETTER J
* 0x006B: LATIN SMALL LETTER K
* 0x006C: LATIN SMALL LETTER L
* 0x006D: LATIN SMALL LETTER M
* 0x006E: LATIN SMALL LETTER N
* 0x006F: LATIN SMALL LETTER O
* 0x0070: LATIN SMALL LETTER P
* 0x0071: LATIN SMALL LETTER Q
* 0x0072: LATIN SMALL LETTER R
* 0x0073: LATIN SMALL LETTER S
* 0x0074: LATIN SMALL LETTER T
* 0x0075: LATIN SMALL LETTER U
* 0x0076: LATIN SMALL LETTER V
* 0x0077: LATIN SMALL LETTER W
* 0x0078: LATIN SMALL LETTER X
* 0x0079: LATIN SMALL LETTER Y
* 0x007A: LATIN SMALL LETTER Z
* 0x007B: LEFT CURLY BRACKET
* 0x007C: VERTICAL LINE
* 0x007D: RIGHT CURLY BRACKET
* 0x007E: TILDE
* 0x00A2: CENT SIGN
* 0x00A3: POUND SIGN
* 0x00A5: YEN SIGN
* 0x00A7: SECTION SIGN
* 0x00A8: DIAERESIS
* 0x00A9: COPYRIGHT SIGN
* 0x00AA: FEMININE ORDINAL INDICATOR
* 0x00AE: REGISTERED SIGN
* 0x00AF: MACRON
* 0x00B0: DEGREE SIGN
* 0x00B4: ACUTE ACCENT
* 0x00B6: PILCROW SIGN
* 0x00B8: CEDILLA
* 0x00BA: MASCULINE ORDINAL INDICATOR
* 0x00C0: LATIN CAPITAL LETTER A WITH GRAVE
* 0x00C1: LATIN CAPITAL LETTER A WITH ACUTE
* 0x00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX
* 0x00C3: LATIN CAPITAL LETTER A WITH TILDE
* 0x00C4: LATIN CAPITAL LETTER A WITH DIAERESIS
* 0x00C5: LATIN CAPITAL LETTER A WITH RING ABOVE
* 0x00C6: LATIN CAPITAL LETTER AE
* 0x00C7: LATIN CAPITAL LETTER C WITH CEDILLA
* 0x00C8: LATIN CAPITAL LETTER E WITH GRAVE
* 0x00C9: LATIN CAPITAL LETTER E WITH ACUTE
* 0x00CA: LATIN CAPITAL LETTER E WITH CIRCUMFLEX
* 0x00CB: LATIN CAPITAL LETTER E WITH DIAERESIS
* 0x00CC: LATIN CAPITAL LETTER I WITH GRAVE
* 0x00CD: LATIN CAPITAL LETTER I WITH ACUTE
* 0x00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX
* 0x00CF: LATIN CAPITAL LETTER I WITH DIAERESIS
* 0x00D0: LATIN CAPITAL LETTER ETH
* 0x00D1: LATIN CAPITAL LETTER N WITH TILDE
* 0x00D2: LATIN CAPITAL LETTER O WITH GRAVE
* 0x00D3: LATIN CAPITAL LETTER O WITH ACUTE
* 0x00D4: LATIN CAPITAL LETTER O WITH CIRCUMFLEX
* 0x00D5: LATIN CAPITAL LETTER O WITH TILDE
* 0x00D6: LATIN CAPITAL LETTER O WITH DIAERESIS
* 0x00D7: MULTIPLICATION SIGN
* 0x00D8: LATIN CAPITAL LETTER O WITH STROKE
* 0x00D9: LATIN CAPITAL LETTER U WITH GRAVE
* 0x00DA: LATIN CAPITAL LETTER U WITH ACUTE
* 0x00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX
* 0x00DC: LATIN CAPITAL LETTER U WITH DIAERESIS
* 0x00DD: LATIN CAPITAL LETTER Y WITH ACUTE
* 0x00DE: LATIN CAPITAL LETTER THORN
* 0x00DF: LATIN SMALL LETTER SHARP S
* 0x00E0: LATIN SMALL LETTER A WITH GRAVE
* 0x00E1: LATIN SMALL LETTER A WITH ACUTE
* 0x00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX
* 0x00E3: LATIN SMALL LETTER A WITH TILDE
* 0x00E4: LATIN SMALL LETTER A WITH DIAERESIS
* 0x00E5: LATIN SMALL LETTER A WITH RING ABOVE
* 0x00E6: LATIN SMALL LETTER AE
* 0x00E7: LATIN SMALL LETTER C WITH CEDILLA
* 0x00E8: LATIN SMALL LETTER E WITH GRAVE
* 0x00E9: LATIN SMALL LETTER E WITH ACUTE
* 0x00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX
* 0x00EB: LATIN SMALL LETTER E WITH DIAERESIS
* 0x00EC: LATIN SMALL LETTER I WITH GRAVE
* 0x00ED: LATIN SMALL LETTER I WITH ACUTE
* 0x00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX
* 0x00EF: LATIN SMALL LETTER I WITH DIAERESIS
* 0x00F0: LATIN SMALL LETTER ETH
* 0x00F1: LATIN SMALL LETTER N WITH TILDE
* 0x00F2: LATIN SMALL LETTER O WITH GRAVE
* 0x00F3: LATIN SMALL LETTER O WITH ACUTE
* 0x00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX
* 0x00F5: LATIN SMALL LETTER O WITH TILDE
* 0x00F6: LATIN SMALL LETTER O WITH DIAERESIS
* 0x00F7: DIVISION SIGN
* 0x00F8: LATIN SMALL LETTER O WITH STROKE
* 0x00F9: LATIN SMALL LETTER U WITH GRAVE
* 0x00FA: LATIN SMALL LETTER U WITH ACUTE
* 0x00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX
* 0x00FC: LATIN SMALL LETTER U WITH DIAERESIS
* 0x00FD: LATIN SMALL LETTER Y WITH ACUTE
* 0x00FE: LATIN SMALL LETTER THORN
* 0x00FF: LATIN SMALL LETTER Y WITH DIAERESIS
* 0x0100: LATIN CAPITAL LETTER A WITH MACRON
* 0x0101: LATIN SMALL LETTER A WITH MACRON
* 0x0102: LATIN CAPITAL LETTER A WITH BREVE
* 0x0103: LATIN SMALL LETTER A WITH BREVE
* 0x0104: LATIN CAPITAL LETTER A WITH OGONEK
* 0x0105: LATIN SMALL LETTER A WITH OGONEK
* 0x0106: LATIN CAPITAL LETTER C WITH ACUTE
* 0x0107: LATIN SMALL LETTER C WITH ACUTE
* 0x010A: LATIN CAPITAL LETTER C WITH DOT ABOVE
* 0x010B: LATIN SMALL LETTER C WITH DOT ABOVE
* 0x010C: LATIN CAPITAL LETTER C WITH CARON
* 0x010D: LATIN SMALL LETTER C WITH CARON
* 0x010E: LATIN CAPITAL LETTER D WITH CARON
* 0x010F: LATIN SMALL LETTER D WITH CARON
* 0x0110: LATIN CAPITAL LETTER D WITH STROKE
* 0x0111: LATIN SMALL LETTER D WITH STROKE
* 0x0112: LATIN CAPITAL LETTER E WITH MACRON
* 0x0113: LATIN SMALL LETTER E WITH MACRON
* 0x0116: LATIN CAPITAL LETTER E WITH DOT ABOVE
* 0x0117: LATIN SMALL LETTER E WITH DOT ABOVE
* 0x0118: LATIN CAPITAL LETTER E WITH OGONEK
* 0x0119: LATIN SMALL LETTER E WITH OGONEK
* 0x011A: LATIN CAPITAL LETTER E WITH CARON
* 0x011B: LATIN SMALL LETTER E WITH CARON
* 0x011E: LATIN CAPITAL LETTER G WITH BREVE
* 0x011F: LATIN SMALL LETTER G WITH BREVE
* 0x0120: LATIN CAPITAL LETTER G WITH DOT ABOVE
* 0x0121: LATIN SMALL LETTER G WITH DOT ABOVE
* 0x0122: LATIN CAPITAL LETTER G WITH CEDILLA
* 0x0123: LATIN SMALL LETTER G WITH CEDILLA
* 0x0126: LATIN CAPITAL LETTER H WITH STROKE
* 0x0127: LATIN SMALL LETTER H WITH STROKE
* 0x012A: LATIN CAPITAL LETTER I WITH MACRON
* 0x012B: LATIN SMALL LETTER I WITH MACRON
* 0x012E: LATIN CAPITAL LETTER I WITH OGONEK
* 0x012F: LATIN SMALL LETTER I WITH OGONEK
* 0x0130: LATIN CAPITAL LETTER I WITH DOT ABOVE
* 0x0131: LATIN SMALL LETTER DOTLESS I
* 0x0136: LATIN CAPITAL LETTER K WITH CEDILLA
* 0x0137: LATIN SMALL LETTER K WITH CEDILLA
* 0x0139: LATIN CAPITAL LETTER L WITH ACUTE
* 0x013A: LATIN SMALL LETTER L WITH ACUTE
* 0x013B: LATIN CAPITAL LETTER L WITH CEDILLA
* 0x013C: LATIN SMALL LETTER L WITH CEDILLA
* 0x013D: LATIN CAPITAL LETTER L WITH CARON
* 0x013E: LATIN SMALL LETTER L WITH CARON
* 0x0141: LATIN CAPITAL LETTER L WITH STROKE
* 0x0142: LATIN SMALL LETTER L WITH STROKE
* 0x0143: LATIN CAPITAL LETTER N WITH ACUTE
* 0x0144: LATIN SMALL LETTER N WITH ACUTE
* 0x0145: LATIN CAPITAL LETTER N WITH CEDILLA
* 0x0146: LATIN SMALL LETTER N WITH CEDILLA
* 0x0147: LATIN CAPITAL LETTER N WITH CARON
* 0x0148: LATIN SMALL LETTER N WITH CARON
* 0x0150: LATIN CAPITAL LETTER O WITH DOUBLE ACUTE
* 0x0151: LATIN SMALL LETTER O WITH DOUBLE ACUTE
* 0x0152: LATIN CAPITAL LIGATURE OE
* 0x0153: LATIN SMALL LIGATURE OE
* 0x0154: LATIN CAPITAL LETTER R WITH ACUTE
* 0x0155: LATIN SMALL LETTER R WITH ACUTE
* 0x0158: LATIN CAPITAL LETTER R WITH CARON
* 0x0159: LATIN SMALL LETTER R WITH CARON
* 0x015A: LATIN CAPITAL LETTER S WITH ACUTE
* 0x015B: LATIN SMALL LETTER S WITH ACUTE
* 0x015E: LATIN CAPITAL LETTER S WITH CEDILLA
* 0x015F: LATIN SMALL LETTER S WITH CEDILLA
* 0x0160: LATIN CAPITAL LETTER S WITH CARON
* 0x0161: LATIN SMALL LETTER S WITH CARON
* 0x0164: LATIN CAPITAL LETTER T WITH CARON
* 0x0165: LATIN SMALL LETTER T WITH CARON
* 0x016A: LATIN CAPITAL LETTER U WITH MACRON
* 0x016B: LATIN SMALL LETTER U WITH MACRON
* 0x016E: LATIN CAPITAL LETTER U WITH RING ABOVE
* 0x016F: LATIN SMALL LETTER U WITH RING ABOVE
* 0x0170: LATIN CAPITAL LETTER U WITH DOUBLE ACUTE
* 0x0171: LATIN SMALL LETTER U WITH DOUBLE ACUTE
* 0x0172: LATIN CAPITAL LETTER U WITH OGONEK
* 0x0173: LATIN SMALL LETTER U WITH OGONEK
* 0x0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX
* 0x0175: LATIN SMALL LETTER W WITH CIRCUMFLEX
* 0x0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
* 0x0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX
* 0x0178: LATIN CAPITAL LETTER Y WITH DIAERESIS
* 0x0179: LATIN CAPITAL LETTER Z WITH ACUTE
* 0x017A: LATIN SMALL LETTER Z WITH ACUTE
* 0x017B: LATIN CAPITAL LETTER Z WITH DOT ABOVE
* 0x017C: LATIN SMALL LETTER Z WITH DOT ABOVE
* 0x017D: LATIN CAPITAL LETTER Z WITH CARON
* 0x017E: LATIN SMALL LETTER Z WITH CARON
* 0x0218: LATIN CAPITAL LETTER S WITH COMMA BELOW
* 0x0219: LATIN SMALL LETTER S WITH COMMA BELOW
* 0x021A: LATIN CAPITAL LETTER T WITH COMMA BELOW
* 0x021B: LATIN SMALL LETTER T WITH COMMA BELOW
* 0x0237: LATIN SMALL LETTER DOTLESS J
* 0x02C6: MODIFIER LETTER CIRCUMFLEX ACCENT
* 0x02C7: CARON
* 0x02D8: BREVE
* 0x02D9: DOT ABOVE
* 0x02DA: RING ABOVE
* 0x02DB: OGONEK
* 0x02DC: SMALL TILDE
* 0x02DD: DOUBLE ACUTE ACCENT
* 0x0300: COMBINING GRAVE ACCENT
* 0x0301: COMBINING ACUTE ACCENT
* 0x0302: COMBINING CIRCUMFLEX ACCENT
* 0x0303: COMBINING TILDE
* 0x0304: COMBINING MACRON
* 0x0306: COMBINING BREVE
* 0x0307: COMBINING DOT ABOVE
* 0x0308: COMBINING DIAERESIS
* 0x030A: COMBINING RING ABOVE
* 0x030B: COMBINING DOUBLE ACUTE ACCENT
* 0x030C: COMBINING CARON
* 0x0326: COMBINING COMMA BELOW
* 0x0327: COMBINING CEDILLA
* 0x0328: COMBINING OGONEK
* 0x1E80: LATIN CAPITAL LETTER W WITH GRAVE
* 0x1E81: LATIN SMALL LETTER W WITH GRAVE
* 0x1E82: LATIN CAPITAL LETTER W WITH ACUTE
* 0x1E83: LATIN SMALL LETTER W WITH ACUTE
* 0x1E84: LATIN CAPITAL LETTER W WITH DIAERESIS
* 0x1E85: LATIN SMALL LETTER W WITH DIAERESIS
* 0x1E9E: LATIN CAPITAL LETTER SHARP S
* 0x1EF2: LATIN CAPITAL LETTER Y WITH GRAVE
* 0x1EF3: LATIN SMALL LETTER Y WITH GRAVE
* 0x2013: EN DASH
* 0x2014: EM DASH
* 0x2022: BULLET
* 0x20AC: EURO SIGN
* 0x2122: TRADE MARK SIGN
* 0x2212: MINUS SIGN [code: missing-codepoints]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/ttf/AwaragiraCANARY-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+0021 EXCLAMATION MARK: try adding one of: khmer, cham, math, gunjala-gondi, thaana, latin, syriac, adlam, mongolian, masaram-gondi
* U+0028 LEFT PARENTHESIS: try adding one of: syriac, mongolian, thaana, cham, adlam, khmer, wancho, latin, masaram-gondi, gunjala-gondi, math
* U+0029 RIGHT PARENTHESIS: try adding one of: gunjala-gondi, math, cham, mongolian, adlam, syriac, wancho, khmer, masaram-gondi, latin, thaana
* U+002A ASTERISK: try adding one of: syriac, math, symbols, latin, masaram-gondi, khmer, adlam, gunjala-gondi
* U+002C COMMA: try adding one of: cham, adlam, nushu, thaana, masaram-gondi, coptic, math, wancho, gunjala-gondi, khmer, latin
* U+002D HYPHEN-MINUS: try adding one of: khmer, coptic, syriac, kayah-li, nushu, hebrew, kaithi, masaram-gondi, mongolian, armenian, sora-sompeng, adlam, cham, latin, gunjala-gondi, kharoshthi, lisu, math, sundanese, wancho
* U+002E FULL STOP: try adding one of: avestan, cham, masaram-gondi, thaana, math, syriac, gunjala-gondi, coptic, latin, khmer, nushu, wancho, adlam
* U+002F SOLIDUS: try adding one of: gunjala-gondi, masaram-gondi, syriac, adlam, wancho, khmer, cham, latin, math
* U+0030 DIGIT ZERO: try adding one of: khmer, symbols, latin, nushu, math
* U+0031 DIGIT ONE: try adding one of: khmer, latin, math, nushu, symbols
* U+0032 DIGIT TWO: try adding one of: nushu, symbols, math, khmer, latin
* U+0033 DIGIT THREE: try adding one of: latin, math, khmer, nushu, symbols
* U+0034 DIGIT FOUR: try adding one of: math, latin, nushu, symbols, khmer
* U+0035 DIGIT FIVE: try adding one of: nushu, symbols, math, khmer, latin
* U+0036 DIGIT SIX: try adding one of: symbols, nushu, latin, math, khmer
* U+0037 DIGIT SEVEN: try adding one of: nushu, khmer, math, symbols, latin
* U+0038 DIGIT EIGHT: try adding one of: khmer, nushu, symbols, latin, math
* U+0039 DIGIT NINE: try adding one of: math, latin, symbols, nushu, khmer
* U+003A COLON: try adding one of: math, meroitic, cham, syriac, masaram-gondi, coptic, gunjala-gondi, thaana, latin, adlam, khmer
* U+003B SEMICOLON: try adding one of: cham, thaana, math, adlam, coptic, latin, masaram-gondi, khmer
* U+003F QUESTION MARK: try adding one of: gunjala-gondi, adlam, khmer, balinese, cham, math, masaram-gondi, latin, mongolian
* U+00A1 INVERTED EXCLAMATION MARK: try adding latin
* U+00AB LEFT-POINTING DOUBLE ANGLE QUOTATION MARK: try adding one of: latin, syriac, hanifi-rohingya, adlam, khmer
* U+00AD SOFT HYPHEN: try adding one of: khmer, cham, latin
* U+00B2 SUPERSCRIPT TWO: try adding latin
* U+00B3 SUPERSCRIPT THREE: try adding latin
* U+00B7 MIDDLE DOT: try adding one of: georgian, gunjala-gondi, gothic, latin, glagolitic, carian, coptic, newa, avestan, lydian, old-permic, duployan, elbasan, shavian, mahajani
* U+00B9 SUPERSCRIPT ONE: try adding latin
* U+00BB RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK: try adding one of: hanifi-rohingya, latin, khmer, syriac, adlam
* U+00BC VULGAR FRACTION ONE QUARTER: try adding latin
* U+00BD VULGAR FRACTION ONE HALF: try adding latin
* U+00BE VULGAR FRACTION THREE QUARTERS: try adding latin
* U+00BF INVERTED QUESTION MARK: try adding latin
* U+2018 LEFT SINGLE QUOTATION MARK: try adding one of: adlam, thaana, latin, gunjala-gondi, masaram-gondi
* U+2019 RIGHT SINGLE QUOTATION MARK: try adding one of: thaana, gunjala-gondi, latin, masaram-gondi, adlam
* U+201A SINGLE LOW-9 QUOTATION MARK: try adding one of: adlam, latin
* U+201C LEFT DOUBLE QUOTATION MARK: try adding one of: adlam, thaana, masaram-gondi, latin, mongolian, wancho, gunjala-gondi
* U+201D RIGHT DOUBLE QUOTATION MARK: try adding one of: adlam, masaram-gondi, gunjala-gondi, thaana, latin, mongolian, wancho
* U+201E DOUBLE LOW-9 QUOTATION MARK: try adding one of: adlam, latin
* U+2026 HORIZONTAL ELLIPSIS: try adding one of: latin, meroitic, phags-pa, gunjala-gondi, syriac, masaram-gondi, adlam
* U+2039 SINGLE LEFT-POINTING ANGLE QUOTATION MARK: try adding one of: adlam, latin
* U+203A SINGLE RIGHT-POINTING ANGLE QUOTATION MARK: try adding one of: latin, adlam
* U+2044 FRACTION SLASH: try adding one of: syriac, latin, devanagari, adlam
* U+2074 SUPERSCRIPT FOUR: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: sinhala [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 11 | 18 | 12 | 89 | 86 | 
| 5% | 8% | 6% | 41% | 40% | 



