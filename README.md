# Voice-Activity-Detection

## Table of contents
* [RealVAD: A Real-world Dataset for Voice Activity Detection](#dataset)
* [Voice Activity Detection by Upper Body Motion Analysis and Unsupervised Domain Adaptation](#code)
 
## RealVAD: A Real-world Dataset for Voice Activity Detection
The task of automatically detecting “Who is Speaking and When” is broadly named as Voice Activity Detection (VAD). 
Automatic VAD is a very important task and also the foundation of several domains, e.g., human-human, human-computer/ robot/ virtual-agent interaction analyses, 
and industrial applications.

RealVAD dataset is constructed from a YouTube video composed of a panel discussion lasting approx. 83 minutes. 
The audio is available from a single channel. There is one static camera capturing all panelists, the moderator and audiences. 
The field-of-the-view of the camera while the panelists are shown with the assigned identification numbers are as follow.

![Alt text](img.png)
<sub> Image was adapted from Privacy camp 2018: Round-table, government hacking in different national contexts and strategies 
https://www.youtube.com/watch?v=51pRTOIso4U </sub>

 Particular aspects of RealVAD dataset are:

* [ ] It is composed of panelists with different nationalities (British, Dutch, French, German, Italian, American, Mexican, Columbian, Thai). This aspect allows studying the effect of ethnic origin variety to the automatic VAD.
* [ ]	There is a gender balance such that there are four female and five male panelists.
* [ ]	The panelists are sitting in two rows and they can be gazing audience, other panelists, their laptop, the moderator or anywhere in the room while speaking or not-speaking. Therefore, they were captured not only from frontal-view but also from side-view varying based on their instant posture and head orientation.
* [ ] The panelists are moving freely and are doing various spontaneous actions (e.g., drinking water, checking their cell phone, using their laptop, etc.), resulting in different postures. 
* [ ] The panelists’ body parts are sometimes partially occluded by their/other's body part or belongings (e.g., laptop).
* [ ] There are also natural changes of illumination and shadow rising on the wall behind the panelists in the back row.
* [ ] Especially, for the panelists sitting in the front row, there is sometimes background motion occurring when the person(s) behind them moves.

You can reach the annotations from: http://doi.org/10.5281/zenodo.3928151, which includes:

* [ ] The upper body detection of nine panelists in bounding box form
* [ ] Associated VAD ground-truth (speaking, not-speaking) for nine panelists 
* [ ] Acoustic features extracted from the video: MFCC and raw filterbank energies
* [ ] The corresponding video can be accessed from: https://www.youtube.com/watch?v=51pRTOIso4U

## When using this dataset for your research, please cite the related papers in your publication:
1) C. Beyan, M. Shahid and V. Murino, "RealVAD: A Real-world Dataset and A Method for
Voice Activity Detection by Body Motion Analysis", in IEEE Transactions on Multimedia, IN PRESS.


## Voice Activity Detection by Upper Body Motion Analysis and Unsupervised Domain Adaptation (https://github.com/shahid313/Visual-VAD-Unsupervised-Domain-Adaptation)
