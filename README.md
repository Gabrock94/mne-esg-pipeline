# mne-esg-pipeline
**A Pipeline for the processing of electrospinography data built on MNE-Python**

Inspired by [mne-bids-pipeline](https://github.com/mne-tools/mne-bids-pipeline), this pipeline provides support for the analysis of electrospinography (ESG) data using mne-python.

## Features ## 
 - Removal of trials contaminated by cardiac (ECG) artifacts
 - Filtering of data
 - Removal of trials contaminated by other artifacts (e.g. EMG) based on thresholds
 - Generation of evoked objects
 - Generation of topographies with simultaneous EEG and ESG maps. 

