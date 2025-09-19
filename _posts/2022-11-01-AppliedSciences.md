---
title: Deep 3D Convolutional Neural Network for Facial Micro-Expression Analysis from Video Images
#description: We present a deep learning-based method for pain analysis using Long Short-Term Memory (LSTM) architecture to classify facial expressions of pain, demonstrating high accuracy in detecting various pain intensities, including subtle changes, with particular potential for clinical applications in assessing pain for non-verbal patients such as infants or those with cognitive impairments.
#background: /assets/theme/images/header-img.png
background: /assets/theme/images/IMG_9993.jpg
image: /assets/theme/images/applsci-12-11078-g002.png
categories: [Publication]
tags: [Journal, MDPI]

---

## Deep 3D Convolutional Neural Network for Facial Micro-Expression Analysis from Video Images

Micro-expression is the involuntary emotion of the human that reflects the genuine feelings that cannot be hidden. Micro-expression is exhibited by facial expressions that last for a short duration and have very low intensity. Because of these reasons, micro-expression recognition is a challenging task. Recent research on the application of 3D convolutional neural networks (CNNs) has gained much popularity for video-based micro-expression analysis. For this purpose, both spatial as well as temporal features are of great importance to achieve high accuracies. The real possibly suppressed emotions of a person are valuable information for a variety of applications, such as in security, psychology, neuroscience, medicine and many other disciplines. This paper proposes a 3D CNN model architecture which is able to extract spatial and temporal features simultaneously. Thereby, the selection of the frame sequence plays a crucial role, since the emotions are only distinctive in a subset of the frames. Thus, we employ a novel pre-processing technique to select the Apex frame sequence from the entire video, where the timestamp of the most pronounced emotion is centered within this sequence. After an extensive evaluation including many experiments, the results show that the train–test split evaluation is biased toward a particular split and cannot be recommended in case of small and imbalanced datasets. Instead, a stratified K-fold evaluation technique is utilized to evaluate the model, which proves to be much more appropriate when using the three benchmark datasets CASME II, SMIC, and SAMM. Moreover, intra-dataset as well as cross-dataset evaluations were conducted in a total of eight different scenarios. For comparison purposes, two networks from the state of the art were reimplemented and compared with the presented architecture. In stratified K-fold evaluation, our proposed model outperforms both reimplemented state-of-the-art methods in seven out of eight evaluation scenarios.
![](/vitalsigns/assets/theme/images/applsci-12-11078-g002.png)

## Fulltext Access
[https://www.mdpi.com/2076-3417/12/21/11078](https://www.mdpi.com/2076-3417/12/21/11078)

## Citing
```bibtex
@Article{Talluri2022,

  author={Talluri, Kranthi Kumar and Fiedler, Marc-André and Al-Hamadi, Ayoub},

  journal={Applied Sciences}, 

  title={Deep 3D Convolutional Neural Network for Facial Micro-Expression Analysis from Video Images}, 

  year={2022},

  doi={10.3390/app122111078}}

```