# Voron-2.4_High_Contrast_Manual
A modified version of the Voron 2.4 build manual for accessibility.

**2026-10-10:** Made high contrast version of the [Stealthchanger Assembly Guide](https://github.com/DraftShift/StealthChanger/blob/main/Manual/Stealthchanger_Assembly_Guide.pdf). Also darken the images slightly; the compression noise in the images has become more obvious unfortunately, so this is about as dark as I can make them without a lot of manual processing.

If this was helpful, please drop a comment on https://github.com/VoronDesign/Voron-2/issues/443 so VoronDesign can see that users need this on future versions. A star on the repo would also be appreciated.

## Background

The StealthBurner manual has a "high contrast" version with normal solid black text which is much more accessible for many people. The light grey text on white is nearly impossibe for me and others to read comfortably, or in my case, at all.

Since I am cursed to work in IT and unfortunately have access to a license for Acrobat Pro, I've preformed the Preflight ritual and converted text from `42,39,31,0` CMYK to `0,0,0,100`. Since Github does not allow attaching PDFs or ZIP'd PDFs to issue comments, I am sharing it here in its own repo.

If you prefer to make this change yourself and have access to Acrobat Pro, [here is how to remap a color to black using Preflight](https://community.adobe.com/t5/acrobat-discussions/how-to-convert-all-text-in-a-book-from-cmyk-to-black-only/m-p/13295438#M384375), or [archived link](https://web.archive.org/web/20261010083233/https://community.adobe.com/questions-9/how-to-convert-all-text-in-a-book-from-cmyk-to-black-only-1275663?postid=288594#post288594). The CMYK values for the grey text are `42,39,31,0`. Depending on the PDF, it may be necessary to first covert the color space of the document from, for example, DeviceRGB to CMYK.
