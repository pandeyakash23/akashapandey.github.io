---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Prediction of Mechanical Properties of Spider Silk using deep learning
### Jan 2022 - Present
Spider silk's mechanical properties are dependent on various repetitive regions of amino acids within the major and minor ampullate spidroin. As the part of this research,
* Developed an interpretable ML model to predict the mechanical properties of the spider silk just based on the primary sequence of spidroins. 
* Showed that including the information about the dynamics of residues in spidroins helps in improving the predictive capability.
* Identified different motifs in spider silk which are the major driving force for mechanical properties and laid down various design rules for designing future fiber-based biomaterials. 
* Manuscript is under preparation.

## Prediction of B-factor in proteins using deep learning
### Aug 2022 - Dec 2022
B-factor of the atom in protein is the measure of its displacement about its mean position. It has been found that B-factor correlates well with many properties of protein such as flexibility, stability, and mechanical properties. Therefore, it is important to have a good predictive model for the B-factor. Hence, as part of this work, we did the following:
* Developed an LSTM-based deep learning model to predict the B-factor of residues in proteins just based on the primary sequence. We were able to achieve a better fit than the state-of-the-art. Additionally, as the prediction is just based on the primary sequence, the developed model can be used for the B-factor prediction in *de novo* proteins.
* Used the trained model to study the impact of Euclidean distance between the atoms on their B-factor. We concluded that atoms within 15 angstrom of distance impact each other profoundly. 
* Work accepted in *Cell Patterns*.
  

## Characterizing the fatigue behavior of Smart Piezoelectric Composite
### Jan 2015 - April 2017
Macro-Fiber Composite (MFC) is a smart piezoelectric composite with high flexibility and piezoelectric coupling. To increase its usage in various applications, it is important to study its fatigue behavior. As part of this research, we did the following:
* Developed a Finite Element (FE) code to predict the actuation performance of MFC in a uni-morph and bi-morph configuration 
* Developed experimental setups to study the fatigue behavior of MFC under mechanical, thermal, and electrical loads
* Developed FE-based fatigue models to predict the degradation in MFC's performance based on the input loading


# Projects
## Emotion share prediction on a Computational Paralinguistic ChallengE ([**ComParE**](http://www.compare.openaudio.eu/)) dataset
### June-July 2023
* As a part of ACM MM'23 challenge, me and my other two teammate developed a deep learning model to predict the emotion share. We outperformed the baseline by 4% and our has been accepted to be presented in the conference.
* As a part of this challenge, we showed the effect of different embeddings (wav2vec & HuBERT) on the prediction. 
* We also studied the effect of Attention in the downstream model and found that it can improve the performance by 1.8%. My contribution was towards writing the downstream model as well as the attention mechanism. 

## Person Identification using wearable signals from the smart watch
### Jan-Feb 2023
* As a part of ICASSP'23 challenge, me and my other teammate developed a deep learning model to identify person based on their wearable signals. We secured 3rd place in the challenge.
* This was done as the first step towards identifying the signals to detect early signals of psycotic disorders.
* Our model used the embeddings from wav2vec and we used 1D convulation layers along with a LSTM layer as the downstream model. We pushed the baseline from 64% to 91.6%. 

