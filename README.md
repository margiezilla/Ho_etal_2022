# Ho_etal_2022
Additional FlyZZZs post-processing scripts used in Ho et al. 2022


**Analyzing Sleep During Activation and Sleep Rebound (ZT0-6)**  
.xlsx files are data output from FlyZZZs (https://github.com/marknwulab/Blum-et-al.-2020/blob/master/Fly%20ZZZs.zip) run using MATLAB  
Raw Sleep Data is saved as .txt file and input into  
Raw Sleep data is post-processed with *_sleepduringabsONLY.ipynb to calculate sleep during activation Day 2.5-3 (Day ZT12-24)  
Raw Sleep data is post-processed with *_sleepreboundZT0-6.ipynb to calculate sleep rebound (sleep amount Day3 ZT0-6 minus Day2 ZT0-6)   

**Analyzing Arousal Threshold within Genotype following Stimulus**  
Beam counts per 1 minute for each individual fly are reported in .txt files recorded by monitor and channel using DAMSystem311 (Trikinetics https://trikinetics.com/)  
Beam counts is post-processed with ArousalThreshold_withinGenotype_v2.ipynb to calculate percentage of flies "responding" to stimulus with beam crosses in interval following stimulus for asleep flies and awake flies.  Asleep flies were defined as flies not moving for the 5 minutes (no beam crosses detected) prior to stimulus, whereas awake flies were those observed to be moving.  Aroused flies were identified as flies moving within the 3 min interval following the stimulus.
