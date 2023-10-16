# Multi-Grained Contrastive Representation Learning for Label-efficient Lesion Segmentation and Onset Time Classification of Acute Ischemic Stroke.
We propose a multi-grained contrastive representation learning (MGCL) framework to learn lesion-related representations from both coarse-grained and fine-grained levels, which aims to facilitate the downstream AIS analysis task including ischemic lesion segmentation and the time since stroke (TSS) onset classification. In this work, we constructed a standard multi-center MRI acute ischemic stroke dataset (MMIS), hoping it can promote future related studies on the AIS analysis. Currently, we are further organizing data and transforming the data format so that it can be accessed more conveniently and quickly. Soon the data will be uploaded.

# Dataset
## Inclusion Criteria
MMIS includes multiple inclusion criteria: (a) The AIS patients are within 24 hours of clear symptom onset. (b) The volume of the ischemic lesions needs to be greater than 1 cc (c) The time of the stroke symptom onset and MRI imaging on admission are recorded (d) The images with severe artifacts were excluded.
## Data Modal
MMIS includes the paired multi-modal MRI pre-treatment imaging for unwitnessed AIS patients, DWI, FLAIR, and PWI. 
## Annotation categories
MMIS includes two annotation categories: (1) pixel-level annotations for ischemic lesions on each MRI modal for lesion segmentation (2) patient-level TSS classification labels (ie., TSS < 4.5h or TSS ≥ 4.5h ) for TSS classification.
## Annotation Demo
<img src="https://github.com/JiaRuiS/MGCL/blob/main/data/data demo.png" width="900" height="500" alt="demo"/><br/>
