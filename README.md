# MATres V2.0

MATres is a comprehensive, open-source software package designed to enable precise targeting of brain areas for stimulation and/or electrophysiological recording in therapeutic applications and fundamental neuroscience research. The software offers an all-inclusive solution for accurately localizing, visualizing, and targeting regions of interest (ROIs) utilizing standard atlases and skull implants. Version 2.0 supports various preprocessing, registration, warping procedures, and 3D reconstructions for macaque and human T1 MRI images, as well as marmoset T2 MRI images.

## Features

* In version 2.0, MATres introduces registration and warping capabilities for marmoset T2 MRI images. The software now includes marmoset T2 MRI atlases, accessible from the [Marmoset MRI-NA216 website](https://dataportal.brainminds.jp/marmoset-mri-na216) for T2 MRI images.
* Refined ROI visualization and selection tools
* Expanded compatibility with various imaging modalities and atlases
* Streamlined and accurate registration and warping processes
* Automatic pre-processing section to enhance MRI image quality, particularly for marmosets
* Manual parameter setting for adjusting MAX values to improve image appearance, specifically for the brain
* Reset section for reverting images to their original state before pre-processing
* Improved skull stripping and linear/non-linear warping capabilities

## Usage

MATres V2.0 is suitable for numerous applications, such as:

* Precise targeting of brain areas for stimulation and/or electrophysiological recording in therapeutic applications and fundamental neuroscience research
* Accurate localization, visualization, and targeting of regions of interest (ROIs) using standard atlases and skull implants
* A range of preprocessing, registration, warping procedures, and 3D reconstructions

In most cases, the pre-processing step may not be necessary, as the software already provides high-quality results. However, for MRI images of poor quality or those acquired with improper MRI imaging coils, the automatic pre-processing section can significantly improve the images.

Alternatively, users can manually adjust the MAX values in the manual parameter setting section to enhance the appearance quality of the images, especially for the brain.

To revert the image back to its original state before pre-processing, utilize the reset section.

To download and learn more about using MATres V2.0, visit our [GitHub repository](https://github.com/fmnh/MATres).

## Paper and Video Tutorial

For further information on the methodology and applications of MATres, consult our paper, "A novel methodology for exact targeting of human and non-human primate brain structures and skull implants using atlas-based 3D reconstruction," available at [https://doi.org/10.1016/j.jneumeth.2023.109851](https://www.sciencedirect.com/science/article/abs/pii/S0165027023000705).

We also offer a [video tutorial](https://www.youtube.com/watch?v=V7A9hZUE7-w) to help users get started with MATres V1.0.

## Contact Us

We believe that MATres V2.0 will prove valuable for researchers and clinicians in the field of neuroscience. If you have questions or suggestions for improvement, please don't hesitate to contact us at [fmnh11510@gmail.com](mailto:fmnh11510@gmail.com).


![matres1](https://github.com/fmnh/MATres-V2.0/assets/130893427/cc59d876-8086-4e8b-a0f7-ffbb136ef7cd)

![matres2](https://github.com/fmnh/MATres-V2.0/assets/130893427/7e54276d-d2c3-4c0b-afd5-3c1739c2d043)

![matres3](https://github.com/fmnh/MATres-V2.0/assets/130893427/62bff420-ccdc-4b05-b661-0682555281d3)



An example of pre-processing step:

![sada](https://github.com/fmnh/MATres-V2.0/assets/130893427/7f0ddb05-881a-4f8e-8581-f5f55562f2b2)

![sasdacc](https://github.com/fmnh/MATres-V2.0/assets/130893427/d774a728-056b-40bc-869f-abf84adfa298)

![qweqwwq](https://github.com/fmnh/MATres-V2.0/assets/130893427/d509314f-70a7-4fbf-86ac-fbc60b5fdbf1)

![dgdgfdg](https://github.com/fmnh/MATres-V2.0/assets/130893427/4b5a137e-4955-4509-86a2-9df2dbf34c0e)

