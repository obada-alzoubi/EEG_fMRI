# EEG Microstates (EEG-ms) Dynamics Maps
## Content 
This repo includes supporting data for *Canonical EEG Microstates Transitions Reflect Switching Among BOLD Resting State Networks and Predict fMRI Signal* Manuscript. More importantly, it hosts the correlated maps of direct time courses, activity and transition regressors. Additionally, the repo might host supporting codes and data used to generate results.\
If you have questions or requests, please contact me at [obada.y.alzoubi@gmail.com](obada.y.alzoubi@gmail.com). 
## Introduction 
Electroencephalography microstates (MS), which reflect a large topographical representation of coherent electrophysiological brain activity, are widely adopted to study cognitive processes mechanisms and aberrant alterations in brain disorders. MS topographies are quasi-stable lasting between 60-120 milliseconds. Some evidence suggests that MS are the electrophysiological signature of resting-state networks (RSNs). 
## Motivation
Some evidence suggests that MS are the electrophysiological signature of resting-state networks (RSNs). However, the spatial and functional interpretation of MS and their association with functional MRI (fMRI) remains unclear
## Summary of Results
Our results using a generalized linear model showed that MS transitions were largely and negatively associated with blood-oxygenation-level dependent (BOLD) signals in the somatomotor, visual, dorsal attention, and ventral attention fMRI networks with limited association within the default mode network. Additionally, a novel recurrent neural network (RNN) confirmed the association between MS transitioning and fMRI signal while revealing that MS dynamics can model BOLD signals and vice versa. Significance. Results suggest that MS transitions may represent the deactivation of fMRI RSNs and provide evidence that both modalities measure common aspects of undergoing brain neuronal activities. These results may help to better understand the electrophysiological interpretation of MS.
# rsfMRI Maps 
Here you can download the correlated maps for direct time course of MS-A, MS-B, MS-C and MS-D when using 2-20 Hz and 1-40 Hz filtering. Also, you can download the correlated maps of activity regressors for MS-A, MS-B, MS-C and MS-D. We also included the pairwise transition correlated maps (16 regressors). Please note that the correlated maps are in nii format. Also, the correlated maps are uncorrected. The non-Gaussian spatial autocorrelation function (ACF) requires a minimum of *136* voxels to be deemed significant at *p<0.05*—using an uncorrected voxel-wise threshold of *p<0.005*.

The data are organized as follow:
```
Correlated-Maps
│── 2-20Hz_Filtering 
│    │── Activity
│    │── DirectTimeCourses
│    └── Transition
│        │── Transition_From_MS-A
│        │── Transition_From_MS-B
│        │── Transition_From_MS-C
│        └── Transition_From_MS-D
└── 1-40Hz_Filtering 
│    └── Activity
│    │── DirectTimeCourses
│    └── Transition
│        └── Transition_From_MS-A
│        └── Transition_From_MS-B
│        └── Transition_From_MS-C
│        └── Transition_From_MS-D
└── Readme.md

```
# Reference
[1] Al Zoubi, Obada, et al. "Canonical EEG Microstates Transitions Reflect Switching Among BOLD Resting State Networks and Predict fMRI Signal." Journal of neural engineering (2021).