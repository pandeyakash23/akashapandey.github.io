---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

**_(2025) Interpretable Model for temporal attribution in time-series data_**  
Developed `TimeSliver`, an _interpretable deep learning model_ that integrates raw and symbolically binned time-series data to capture temporal interactions and compute temporal attribution scores, achieving a _11% performance improvement_ over state-of-the-art explainable methods.

<br>

**_(2025) Interpretable Model for monomeric attribution in protein sequences_**  
Developed an _interpretable_ deep learning model, `COLOR`, that transforms higher-dimensional _protein sequences_ into a lower-dimensional _interpretable representation_ to estimate the contribution of each monomer to a given property. `COLOR` achieves _22% higher explainability_ than the existing gradient- and attention-based methods.

<br>

**_(2025) EMG-to-Text conversion with LLMs_**  
Developed an _`LlaMA 3`-based model_ to convert surface electromyography (EMG) signals, which capture muscle activations, into speech. On a closed vocabulary task, our model achieves approximately _20% lower word error rate (WER)_ compared to specialized models.

<br>

**_(2024) Predictive model for spider silk's mechanical property_**  
Developed an _interpretable feature-based deep_ _learning framework_ to predict the properties of spider silk and _identify important motifs_ in a data-constrained setting. We showed that using the B-factor as a motif descriptor improves prediction performance by 15% compared to traditional descriptors such as hydrophobicity, charge, and others.

<br>

**_(2023) B-factor prediction in proteins_**  
Developed a _many-to-many LSTM model_ to predict the B-factor (atomic flexibility) of alpha-carbon atoms in proteins, achieving a _30% improvement_ over the CNN-based state-of-the-art model. Analysis revealed that atoms within 15 Å contribute most significantly to B-factor values.

<br>

**_(2023) Audio-based emotion prediction_**  
As part of an _ACM Multimedia Challenge_, we developed an emotion prediction model based on an _audio foundation model_. We found that using `HuBERT-Large` as the audio foundation significantly _improved performance by 4%_.

<br>

**_(2023) Person identification based on the biosignals_**  
As part of the ICASSP'23 Challenge, we developed a _wav2vec-based deep learning model_ to identify individuals based on their biosignals, _securing 3rd place_. We employed a _late fusion strategy_ to effectively handle both time-varying and static features.


<!-- ## Prediction of Mechanical Properties of Spider Silk using deep learning
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
* As a part of the ACM MM'23 challenge, me and my other two teammates developed a deep learning model to predict the emotion share. We outperformed the baseline by 4% and our has been accepted to be presented at the conference.
* As a part of this challenge, we showed the effect of different embeddings (wav2vec & HuBERT) on the prediction.
* We also studied the effect of Attention in the downstream model and found that it can improve performance by 1.8%. My contribution was towards writing the downstream model as well as the attention mechanism.

## Person Identification using wearable signals from the smart watch
### Jan-Feb 2023
* As a part of the ICASSP'23 challenge, me and my other teammate developed a deep learning model to identify person based on their wearable signals. We secured 3rd place in the challenge.
* This was done as the first step towards identifying the signals to detect early signals of psychotic disorders.
* Our model used the embeddings from wav2vec and we used 1D convolution layers along with an LSTM layer as the downstream model. We pushed the baseline from 64% to 91.6%. 
 -->
