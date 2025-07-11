---
title: VITAL SIGNS ESTIMATION 
description: "Development and systematic validation of a system for contactless, camera-based measurement of heart rate (variability)."
background: /assets/theme/images/IMG_9993.jpg
#image: /assets/theme/images/sample_video.gif
categories: [Project]
tags: ["VITAL SIGNS"]
                                 
permalink: /project/
---

{: .alert .alert-warning}




## Motivation and Goals
The aim of this research project is the optical measurement of vital signs (heart rate, respiratory rate & heart rate variability) from video images using photoplethysmography (PPG). Vital signs provide important information for the medical analysis of the cardiovascular system, as well as for the diagnosis and prevention of diseases and is an essential marker for the evaluation of the activity of the autonomic nervous system. PPG is an optical, non-invasive technology that uses light to record the volumetric variations of blood circulation in the skin. In recent years, this method has also been realized contactlessly at a distance through the use of cameras and has already been successfully used to determine heart rate from video data. The PPG signal can be measured both in the visible spectrum using RGB cameras and in the near-infrared range.

![image](/vitalsigns/assets/theme/images/pipeline_vital_signs_estimation.png)

In order to measure heart rate variability, it is necessary to determine the heartbeats (peaks) in the PPG signal with temporal precision. One challenge here is that even the smallest movements and facial expressions of the test subjects can lead to artifacts in the PPG signal, which are mainly due to the changing reflection behavior of the observed skin areas. Thus, the high measurement accuracy of heart rate in the state of the art can only be achieved through strong temporal filtering. However, this means that precise temporal localization of the heartbeats is no longer possible, although this is essential for determining heart rate variability.
This is where this research project comes in, in which these artifacts in the PPG signal are systematically recorded and then effectively compensated for in order to avoid strong filtering of the PPG signal after extraction from the video data. To date, almost all methods for measuring the PPG signal have been based on color averaging of (partial) areas of the skin on the face. Motion compensation is not possible with these methods, as position information is lost. Deep neural networks are suitable for training models that are invariant to movement. Using methods for 3D head pose estimation and action unit recognition (facial muscle movements), a system is to be trained to obtain motion-invariant PPG signals from the video data. For this purpose, information about the detected skin regions is generated in each image and used for motion compensation. The data obtained from this network will be further processed with a deep neural network optimized for temporal signal processing in order to determine the heartbeat peaks in the PPG signal with temporal precision. In addition, new CNN-based segmentation methods will be used to achieve more accurate detection of the skin in the video images and thus reduce sources of interference. The approaches described are to be developed both for the RGB videos prevalent in the state of the art and for combinations of different multispectral wavelength ranges of visible and near-infrared light. The measurement in the near-infrared range offers advantages for future application-related use, in particular the possibility of irritation-free lighting for the human eye, with the help of which the influence of external lighting fluctuations can be minimized, thus enabling measurement in the dark, which has advantages for monitoring patients in hospitals, for example.

 <!-- gif can be used instead mp4, converter for example  https://ezgif.com/  -->
![image](/vitalsigns/assets/theme/images/pipeline_FaSeNet_HR-LSTM.png)

## Funding

This project is supported by the German Research Foundation (DFG) under grants AL 638/14-1 (project no. 502438143).

![image](/vitalsigns/assets/theme/images/dfg_logo_englisch_blau_en.gif)
