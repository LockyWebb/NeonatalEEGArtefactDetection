# NeonatalEEGArtefactDetection

This respository holds data used in Webb, L. et al., Automated detection of artefacts in neonatal EEG with residual neural networks, Computer Methods and Programs in Biomedicine (208), 2021. 

The EEG data is publicly available in:
Tapani, KT. et al., Time-Varying EEG Correlations Improve Automated Neonatal Seizure Detection, Int. J. Neural Syst. 29 (4), 2019, 1850030   
Stevenson, NJ. et al., A dataset of neonatal EEG recordings with seizure annotations, Sci. Data 6 (1), 2019, 190039 

The zip file contains details for the annotations used Webb et al. (2021). Each text file is for a seperate EEG recording (numbered 1 through 79). 
The original annotations that are in the files are coded as followed:
1 – Clean EEG
2 – Device Interference
3 – EMG
4 – Movement
5 – Electrode
6 – HF ventilation
7 – Biological Rhythm (ECG/respiration/pulse)

A code of 0 means no annotation on that channel. Because there were so few HF ventilation annotations, these were dropped from use. Hence any 7 in the annotations is biological rhythm, and the 6s should be ignored.
