# Joint Analysis of Sound Events and Acoustic Scenes

Sound event detection (SED) and acoustic scene classification (ASC) are major research tasks in environmental sound analysis. Conventional methods have addressed these tasks separately; however, acoustic events and scenes are closely related to each other. For example, in the acoustic scene "office," the sound events "mouse clicking" and "keyboard typing" tend to occur. This repository provides metadata for joint analysis of sound events and acoustic scenes, which consists of the TUT Sound Events 2016/2017 and TUT Acoustic Scenes 2016/2017 [1][2].

## What are TUT Sound Events 2016/2017 & TUT Acoustic Scenes 2016/2017?

TUT Sound Events 2016/2017 & Acoustic Scenes 2016/2017 are environmental sound datasets for SED and ASC, which were originally recorded by Tampere University, Audio Research Group. Parts of sound clips in this dataset have strong event labels (e.g. TUT Sound Events 2016, TUT Sound Events 2017); however, many of sound clips have no strong labels. We have annotated some of these sound clips using the same protocol as in [1] and [2]. 

## Dataset discription

This dataset contains 266 min. of sounds (192 min. for training, 74 min. for evaluation) including 4 acoustic scenes (City center, Home, Office, Residential area) and 25 sound events. Evaluation experiments using this dataset is found in [3][4][5]. 


The meta data has almost same structure with that of TUT Sound Events/Acoustic Scenes as follows.
```
path	scene_label	event_start_time	event_end_time	event_label
TUT-sound-events-2017-development/audio/street/a124.wav	city_center	0.0	4.037666	people speaking
TUT-sound-events-2017-development/audio/street/a124.wav	city_center	0.0	21.850174	large vehicle
TUT-sound-events-2017-development/audio/street/a124.wav	city_center	1.772634	4.222315	people walking
...
TUT-sound-events-2016-development/audio/residential_area/b009.wav	residential_area	223.102353	226.805399	people walking
TUT-sound-events-2016-development/audio/residential_area/b009.wav	residential_area	227.484838	228.455759	bird singing
TUT-sound-events-2016-development/audio/residential_area/b009.wav	residential_area	228.468075	230.689081	bird singing
```

Note that sound files of the TUT Sound Events 2016/2017 and TUT Acoustic Scenes 2016/2017 are not included in this metadata. Please download them from the DCASE Challenge Web page (or directly Zenodo).

##

[1]  A. Mesaros, T. Heittola, and T. Virtanen, “TUT Database for Acoustic Scene Classification and Sound Event Detection," Proc. European Signal Processing Conference (EUSIPCO), pp. 1128-1132.  
[2]  A. Mesaros, T. Heittola, A. Diment, B. Elizalde, A. Shah, B. Raj, and T. Virtanen, “DCASE 2017 challenge setup: Tasks, datasets and baseline system,” Proc. Workshop on Detection and Classification of Acoustic Scenes and Events (DCASE) Workshop, pp. 85-92, 2017.   
[3] N. Tonami, K. Imoto, M. Niitsuma, R. Yamanishi, and Y. Yamashita, "Joint Analysis of Acoustic Events and Scenes Based on Multitask Learning," Proc. IEEE Workshop on Applications of Signal Processing to Audio and Acoustics (WASPAA), pp. 333-337, 2019.  
[4] K. Imoto, N. Tonami, Y. Koizumi, M. Yasuda, R. Yamanishi, and Y. Yamashita, "Sound Event Detection by Multitask Learning of Sound Events and Scenes with Soft Scene Labels," Proc. IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 621-625, 2020.  
[5] N. Tonami, K. Imoto, R. Yamanishi, and Y. Yamashita, "Joint Analysis of Sound Events and Acoustic Scenes Using Multitask Learning," IEICE Transactions on Information and Systems, Vol. E104-D, No. 02, pp. 294-301, 2021.
