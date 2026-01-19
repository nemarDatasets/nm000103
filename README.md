## Overview
This is **NOT for Commercial-Use Release** of HBN-EEG, the EEG and (soon-released) Eye-Tracking Section of the Child Mind Network Healthy Brain Network (HBN) Project, curated into the Brain Imaging Data Structure (BIDS) format. This dataset is part of a larger initiative to advance the understanding of child and adolescent mental health through collecting and analyzing neuroimaging, behavioral, and genetic data (Alexander et al., Sci Data 2017).
## Data Description
This dataset comprises electroencephalogram (EEG) data and behavioral responses collected during EEG experiments from participants involved in the HBN project.
### Contents
* **EEG Data:** High-resolution EEG recordings capture a wide range of neural activity during various tasks.
* **Behavioral Responses:** Participant responses during EEG tasks, including reaction times and accuracy. This data was originally recorded within the behavior directory of the HBN data. This data is now included with the EEG data within the_events. tsv` files.

### Special Features
* **Hierarchical Event Descriptors (HED):** Events, including the original EEG events and the included behavioral events, have clear explanations, including proper HED annotation suitable for systematic meta and mega analysis of the data.
* **P-Factor, Attention, Internalization and Externalization:** Derived from behavioral questionnaires, these factors provide valuable insights into the internalizing and externalizing behaviors of participants, adding a rich layer of psychological interpretation to the EEG and behavioral data.
* **Data quality and availability:** We performed minimal quality control to ensure that the data was not corrupted, each task had its necessary events, and was ready for preprocessing. The results of this quality control are available in the `participants.tsv` file.

## Copyright and License
This dataset is licensed under the non-commercial version of the Creative Common Attributions version 4.0 license (CC BY NC SA 4.0) based on the participant's consent. Subjects (or their legal gurdians) did NOT provide consent for their data to be used for any commercial pourposes.

## Acknowledgments
We would like to express our gratitude to all participants and their families, whose contributions have made this project possible. We also thank our dedicated team of researchers and clinicians for their efforts in collecting, processing, and curating this data.
