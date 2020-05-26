---
layout: post
title:  "Eye-tracking measuring arousal in mice under 2-photon imaging"
date:   2015-06-31 00:42:06 +0200
categories: research_project
logo_url: /assets/icons/uvalogo.jpg
---
I implemented an eye-tracking algorithm in Matlab to track pupil diameter and applied it to a mice 2-alternative choice decision task to measure arousal. With these data I analyzed the effects of arousal on sensory processing in the primary visual cortices with 2-photon calcium imaging. 

This project formed my Bachelor thesis and the accompanying report can be found [here](/assets/reports/BachelorThesisGrzelkowski.pdf). It was my first experience working on a research project in MATLAB. During the 5 months, I implemented a new eyetracking algorithm in the data pipeline developed by a previous intern in the lab and created some analysis scripts for 2-photon imaging data. I was supervised by Guido Meijer and Carien Lansink at the Swammerdam Institute for Life Sciences, University of Amsterdam. 

#### Abstract
Arousal affects the cortical mechanisms of information encoding, influencing the way an organism processes the stimuli in its surroundings. Complex tasks show best performance at intermediate levels of arousal, the optimal state. Although recent studies have looked at several neuronal correlates of different states of arousal, most classify arousal in two distinct states. Since optimal state of arousal is observed at intermediate levels, which is not considered when discriminating between two states, the neuronal correlates of arousal at optimal level are not well understood. The effect of optimal state of arousal on population coding in the primary visual cortex was investigated using two-photon calcium imaging in awake and behaving mice. These measurements were combined with eye-tracking of the pupil of the mouse as a measurement of arousal. Earlier results of a u-shaped curve of activity and variability to levels of arousal in the mouse auditory cortex were replicated in the visual cortex. Noise correlations area mechanism shown to be involved in sensory processing. We found noise correlationsto be increased at high pupil sizes compared to low and intermediate levels. More interestingly we also observed a significant decrease of noise correlation at optimal state of arousal comparing hit against miss trials. These results implicate that a decorrelation of the activity of neurons have a positive effect on information encoding. Our findings suggest a neuronal basis for optimal task performance at intermediate levels of arousal.

![Eyetracking](/assets/reports/thumbnails/bachelor_eye_tracking.png)
*Overview of the algorithm behind tracking pupil diameter* 