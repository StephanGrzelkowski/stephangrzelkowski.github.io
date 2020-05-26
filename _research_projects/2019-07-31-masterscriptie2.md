---
layout: post
title:  "Analysis of the latent variables in a RNN VAE fitting widefield data in a visual two-choice decision task"
date:   2019-07-31 00:00:00 +0200
categories: research_project
logo_url: /assets/icons/rikenlogo.png
---
We fit the LFADS model - a recurrent neural network model to encode spike trains - to widefield imaging data to analyze behavioral correlates of decision making in the parietal cortex. 

This project took 6 months, during which I worked at the Laboratory for Neural Circuits and Behavior at the Riken Center for Brain Science in Tokyo. I prepared the widefield data in MATLAB and ran the LFADS model through tensorflow in python with the pipeline provided by the original contributers of the model. After succesfully training the model we used different methods to analyze the network activity and how they might relate to simultaneous behavioral changes in the mice. I learned a great deal about applications of Machine Learning, tensorflow, interfacing MATLAB and Python, and debugging foreign code. A [full report](/assets/reports/MasterProject2Grzelkowski.pdf) of my work and the results is available. I was supervised by Javier Orlando and Andrea Benucci. 

#### Abstract
Widefield imaging allows us to simultaneously record multiple areas of the mouse brain. This enables the mapping of the different cortical processes that are involved in the decision-making process. Visual processing is affected by different task modalities, primarily by sensory information and motor components. It is unknown how dorsal-parietal regions separate these overlapping dynamics from visual areas and create relevant representations to make a decision. Using Latent Factor Analysis via Dynamical Systems (LFADS), we analyze the dynamics of widefield neural recordings in a two-alternative forced-choice orientation discrimination task in mice to find the latent space that encodes relevant information for decision making. We show that LFADS can reliably reproduce the activity of large scale recordings with single-trial precision and that the factor trajectories (the reduced dimensional components) reflect task-related processes. Further analyses of these factors indicate that cortical activity is governed by many behavioral components such as movements, pupil dilation, and task difficulty. We conclude that LFADS offers valuable insights into these interactions and their temporal and spatial dynamics.
