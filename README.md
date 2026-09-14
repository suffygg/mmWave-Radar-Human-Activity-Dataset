# mmWave-Radar-Human-Activity-Dataset
A self-collected 77-GHz mmWave radar dataset for indoor human activity recognition, including isolated and continuous activity recordings from 15 participants across 4 environments, covering 8 activity categories and 9 spatial sensing regions.

This repository provides a self-collected millimeter-wave (mmWave) radar dataset for human activity sensing and recognition in indoor environments. The dataset was acquired using a TI IWR1843 FMCW radar with a DCA1000EVM data acquisition board at 77 GHz. The radar system uses one transmitting channel and four receiving channels, and the acquired signals are processed into range-Doppler and micro-Doppler representations.

The dataset contains recordings from **15 participants** across **four acquisition environments**, covering **eight human activity categories** and **nine spatial sensing subregions**. The activity categories include BOWING, BOXING, FALLING DOWN, HAND WAVING, SITTING-TO-STANDING, SITTING DOWN, WALKING, and BENDING-TO-STANDING.

Two complementary data protocols are provided. The **isolated-activity dataset** contains 890 independent activity recordings, corresponding to 3560 processed radar images generated from the four receiving channels. Each isolated recording contains approximately 2 s of radar data. The sensing area is divided into nine subregions to provide spatially distributed activity samples.

The **continuous-activity dataset** consists of untrimmed radar sequences in which multiple target activities are performed consecutively with natural transitions and pauses. After activity segmentation and exclusion of non-target transition intervals, **680 target activity instances** are retained, corresponding to **2720 processed radar images** from the four receiving channels. The continuous sequences include different activity combinations and durations to provide a more realistic setting for continuous activity analysis.

The dataset is intended to support research on mmWave radar-based human activity recognition, continuous activity segmentation, robust activity classification, and generalization across subjects and indoor environments.
