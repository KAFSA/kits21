# Changelog

This file is meant to keep track of which annotations were changed in each dataset version. Broadly, the *major* version will be incremented with any change to the postprocessing code that causes every region to be regenerated (starting at `v1.x.x`). The *minor* version will be incremented with the addition of new **imaging**, and the *patch* version will be incremented with new **annotations** for the existing imaging.

## [2.2.3] - Removed Duplicate Instance

The cyst region in 205 was an erroneous duplicate of a tumor

## [2.2.2] - Official Dataset Freeze

- Merged in work by Fabian and Dasha on example Docker submissions
- Revisions to
  - `case_00000`
  - `case_00006`
  - `case_00039`
  - `case_00050`
  - `case_00063`
  - `case_00076`
  - `case_00081`
  - `case_00113`
  - `case_00120`
  - `case_00127`
  - `case_00129`
  - `case_00133`
  - `case_00153`
  - `case_00154`
  - `case_00155`
  - `case_00176`
  - `case_00192`
  - `case_00194`
  - `case_00201`
  - `case_00205`
  - `case_00211`
  - `case_00214`
  - `case_00242`
  - `case_00246`
  - `case_00247`
  - `case_00254`
  - `case_00281`

## [2.2.1] - July 1st, 2021: Training Set Release

- Edits to nearly every case

## [2.2] - July 1st, 2021

- Code for evaluation of segmentations has been added. Have a look at kits21/evaluation/readme.md
- Sampling of realistic segmentations from instance annotations
- Code for computing the inter-rater disagreement between sampled segmentations

## [2.1.1] - June 28, 2021

- Complete revisions for
  - `case_00167`
  - `case_00170`
  - `case_00179`
  - `case_00181`
  - `case_00182`
  - `case_00186`
  - `case_00187`
  - cases 194-196
  - cases 199-201
  - cases 203-209
  - `case_00211`
  - `case_00212`
  - cases 216-233
  - `case_00235`
  - `case_00237`
  - `case_00238`
  - cases 240-245
  - `case_00247`
  - `case_00249`
  - `case_00255`
  - cases 258-263
  - `case_00266`
  - `case_00267`
  - `case_00269`
  - `case_00270`
  - `case_00272`
  - cases 274-277
  - `case_00279`
  - `case_00280`
  - cases 283-286
  - `case_00288`
  - `case_00290`
  - `case_00293`
  - `case_00295`
  - `case_00299`
- Incomplete revisions for
  - `case_00168`
  - `case_00169`
  - cases 171-178
  - `case_00180`
  - `case_00184`
  - `case_00185`
  - cases 188-190
  - `case_00193`
  - cases 197-198
  - `case_00202`
  - `case_00210`
  - `case_00213`
  - `case_00214`
  - `case_00234`
  - `case_00236`
  - `case_00239`
  - `case_00246`
  - `case_00248`
  - `case_00278`
  - `case_00281`
  - `case_00282`
  - `case_00287`
  - `case_00289`
  - `case_00291`
  - `case_00292`
  - `case_00294`
  - `case_00296`
  - `case_00297`
- Crowd-workers completed incomplete revisions in cases 0 - 200
  - cases 250-254
  - `case_00256`
  - `case_00257`
  - `case_00264`
  - `case_00265`
  - `case_00268`
  - `case_00271`
  - `case_00273`
  - `case_00278`
  - `case_00281`
  - `case_00282`
  - `case_00287`
  - `case_00289`
  - `case_00291`
  - `case_00292`
  - `case_00294`
  - `case_00296`
  - `case_00297`
- Crowd-workers completed incomplete revisions in cases 0 - 200

## [2.1.0]- June 28, 2021

- Restructured the project as a python package for easier import

## [2.0.6] - June 26, 2021

- Full Annotations for cases 277 - 299
- Complete revisions for
  - cases 146-148
  - cases 151-155
  - cases 159-165`
- Incomplete revisions for
  - `case_00149`
  - `case_00151`
  - `case_00157`
  - `case_00158`
  - `case_00166`

## [2.0.5] - June 25, 2021

- Full Annotations for cases 250 - 276
- Complete revisions for
  - `case_00082`
  - `case_00083`
  - cases 85-88
  - `case_00090`
  - `case_00092`
  - `case_00094`
  - `case_00095`
  - `case_00096`
  - `case_00099`
  - cases 101-107
  - `case_00109`
  - `case_00110`
  - cases 112-116
  - cases 120-122
  - `case_00125`
  - `case_00126`
  - `case_00130`
  - `case_00131`
  - `case_00134`
  - `case_00136`
  - `case_00138`
  - `case_00144`
- Incomplete revisions for
  - `case_00084`
  - `case_00091`
  - `case_00093`
  - `case_00097`
  - `case_00098`
  - `case_00100`
  - `case_00108`
  - `case_00111`
  - cases 117-119
  - `case_00123`
  - `case_00124`
  - `case_00127`
  - `case_00129`
  - `case_00132`
  - `case_00135`
  - `case_00137`
  - cases 139-143
  - `case_00145`

## [2.0.4] - June 24, 2021

- Full annotations for cases 226 - 249
- Complete revisions for
  - `case_00041`
  - `case_00075`
  - `case_00076`
  - `case_00077`
  - `case_00078`
  - `case_00079`
  - `case_00080`
  - `case_00081`

## [2.0.3] - June 23, 2021

- Full annotations for cases 200 - 225
- Incomplete revisions for
  - `case_00017`
  - `case_00019`
  - `case_00021`
  - `case_00023`
  - `case_00026`
  - `case_00033`
  - `case_00051`
  - `case_00056`
  - `case_00057`
  - `case_00058`
  - `case_00060`
  - `case_00065`
  - `case_00066`
  - `case_00068`
  - `case_00071`
  - `case_00150`
- Complete revisions for
  - `case_00016`
  - `case_00018`
  - `case_00020`
  - `case_00022`
  - `case_00024`
  - `case_00025`
  - `case_00027`
  - `case_00028`
  - `case_00029`
  - `case_00030`
  - `case_00031`
  - `case_00032`
  - `case_00034`
  - `case_00035`
  - `case_00036`
  - `case_00038`
  - `case_00039`
  - `case_00042`
  - `case_00050`
  - `case_00052`
  - `case_00053`
  - `case_00054`
  - `case_00055`
  - `case_00059`
  - `case_00061`
  - `case_00062`
  - `case_00064`
  - `case_00067`
  - `case_00069`
  - `case_00070`
  - `case_00072`
  - `case_00073`
  - `case_00074`

## [2.0.2] - June 22, 2021

- Full annotations for cases 150 - 199
- Incomplete revisions for
  - `case_00000`
  - `case_00001`
  - `case_00015`
  - `case_00100`
- Complete revisions for
  - cases 2 - 14
  - `case_00101`
  - `case_00102`

## [2.0.1] - June 18, 2021

- Full annotations for cases 93 - 149

## [2.0.0] - June 17, 2021

- Changed import and aggregation code to ignore ureter, artery, and vein regions
- Deleted existing ureter, artery, and vein instances that were segmented
- New annotations for cases 50 - 92

## [1.0.3] - May 21, 2021

- Full annotations for
  - `case_00036`
  - `case_00037`
  - `case_00038`
  - `case_00039`
  - `case_00041`
  - `case_00042`
  - `case_00044`
  - `case_00046`
- Added cleanup function to import script which deletes unused save files

## [1.0.2] - May 7, 2021

- Full annotations for
  - `case_00034`
  - `case_00035`

## [1.0.1] - May 6, 2021

- Full annotations for
  - `case_00030`
  - `case_00031`
  - `case_00032`

## [1.0.0] - May 5, 2021

- Full annotations for
  - `case_00008`
  - `case_00025`
  - `case_00026`
  - `case_00027`
  - `case_00028`
  - `case_00029`
- Two new methods for aggregation ("and" and "majority voting") and their associated files

## [0.0.8] - April 29, 2021

- Full annotations for
  - `case_00005`
  - `case_00023`
  - `case_00024`

## [0.0.7] - April 15, 2021

- Full annotations for
  - `case_00020`
  - `case_00021`
  - `case_00022`

## [0.0.6] - April 14, 2021

- Full annotations for
  - `case_00017`
  - `case_00018`
  - `case_00019`

## [0.0.5] - April 13, 2021

- Full annotations for
  - `case_00014`
  - `case_00015` sans one artery segmentation -- will include next time
  - `case_00016`

## [0.0.4] - April 12, 2021

- Full annotations for
  - `case_00011` - sans one kidney annotation -- will get on next round
  - `case_00012`
  - `case_00013`

## [0.0.3] - April 9, 2021

- Full annotations for
  - `case_00006`
  - `case_00007`
  - `case_00009`
  - `case_00010`

## [0.0.2] - April 8, 2021

- Full annotations for:
  - `case_00002`
  - `case_00003`
  - `case_00004`
- Added `pull_request_template.md`

## [0.0.1] - April 7, 2021

- Includes all imaging from the KiTS19 Challenge
- Preliminary postprocessing and aggregation -- still subject to change
- Full annotations for:
  - `case_00000`
  - `case_00001`
  - `case_00006`
- Partial annotations for
  - `case_00002`
