# NiWrap wrappers for [FastSurfer](https://github.com/Deep-MI/FastSurfer)

FastSurfer is a fast and accurate deep-learning based neuroimaging pipeline. It provides a full FreeSurfer alternative for volumetric analysis (FastSurferVINN) and surface-based thickness analysis (recon-surf). The deep learning models were trained on 60+ manually annotated brain scans and provide state-of-the-art accuracy. FastSurfer can segment a full brain scan in less than 1 minute, is robust against changes in input scanner contrasts, and generalizes well to non-training data.

FastSurfer includes three main components:
1. FastSurferVINN - A deep learning architecture for whole brain segmentation
2. CerebNet - For detailed cerebellum sub-segmentation
3. HypVINN - For hypothalamus sub-segmentation

The pipeline produces FreeSurfer-compatible outputs and can be used as a drop-in replacement for FreeSurfer's recon-all pipeline, while being orders of magnitude faster.

FastSurfer is made by https://github.com/Deep-MI/FastSurfer.

This package contains wrappers only and has no affiliation with the original authors.
