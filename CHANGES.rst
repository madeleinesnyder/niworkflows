Version 0.1.8
-------------

* [ENH] Add NKI template data grabber (#200)
* [ENH] Enable sbref to be passed to EstimateReferenceImage (#199)
* [ENH] Add utilities for fixing NIfTI qform/sform matrices (#202)
* [ENH] Upgrade internal Nipype

Version 0.1.7
-------------

* [ENH] Reporting interface for `mri_coreg`
* [ENH] Upgrade internal Nipype

Version 0.1.6
-------------

* [ENH] Add BIDS example getters (#189)
* [ENH] Add NormalizeMotionParams interface (#190)
* [ENH] Add ICA-AROMA reporting interface (#193)
* [FIX] Correctly handle temporal units in MELODIC plotting (#192)
* [ENH] Upgrade internal Nipype

Version 0.1.5
-------------

* [ENH] Do not enforce float precision for ANTs (#187)
* [ENH] Clear header extensions when making ref image (#188)
* [ENH] Upgrade internal Nipype

Version 0.1.4
-------------

* [ENH] Upgrade internal Nipype

Version 0.1.3
-------------

* [ENH] Upgrade internal Nipype

Version 0.1.2
-------------

* Hotfix release (updated manifest)

Version 0.1.1
-------------

* Hotfix release (updated manifest)

Version 0.1.0
-------------

* [ENH] Improve dependency management for users unable to use Docker/Singularity containers (#174)
* [DEP] Removed RobustMNINormalization `testing` input; use `flavor='testing'` instead (#172)

Version 0.0.7
-------------

* [ENH] Use AffineInitializer in RobustMNIRegistration (#169, #171)
* [ENH] Add CopyHeader interface (#168)
* [ENH] Add 3dUnifize to skull-stripping workflow (#167, #170)
* [ENH] Give access to num_threads in N4BiasFieldCorrection (#166)
* [ENH] Add a simple interface for visualising masks (#161)
* [ENH] Add a family of faster registration settings (#157)
* [ENH] More flexible settings for RobustMNIRegistration (#155)
* [ENH] Add EstimateReferenceImage interface (#148)
* [ENH] Add a SimpleBeforeAfter report capable interface (#144)
* [ENH] Add MELODIC report interface (#134)

Version 0.0.6
-------------

* [FIX] Python 2.7 issues and testing (#130, #135)
* [ENH] Compress surface segmentation reports (#133)
* [ENH] Write bias image in skull-stripping workflow (#131)
* [FIX] BBRegisterRPT: Use `inputs.subjects_dir` to find structurals (#128)
* [ENH] Fetch full 2009c from OSF (#126)
* [ENH] Coregistration tweaks (#125)
* [FIX] Be more robust in detecting SVGO (#124)
* [ENH] Enable Lanczos interpolation (#122)

Version 0.0.5
-------------


Version 0.0.3
-------------

* Add parcellation derived from Harvard-Oxford template, to be
  used with the nonlinear-asym-09c template for the carpetplot
* Add headmask and normalize tpms in mni_icbm152_nlin_asym_09c
* Update MNI ICBM152 templates (linear and nonlinear-asym)
* Add MNI152 2009c nonlinear-symetric template (LAS)
* Add MNI152 nonlinear-symmetric template
* Add MNI EPI template and parcellation
* Switch data downloads from GDrive to OSF
* Fixed installer, now compatible with python 3

Version 0.0.2
-------------

* Added MRI reorient workflow (based on AFNI)


Version 0.0.1
-------------

* Added skull-stripping workflow based on AFNI
* Rewritten most of the shablona-derived names and description files
* Copied project structure from Shablona
