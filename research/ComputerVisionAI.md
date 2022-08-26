---
layout: page
title: Research
---

# Research on Deep Learning-based Computer Vision
- Computer Vision is one of the latest areas of computer science that studies the part of a machine's vision
- The DMS Vision team is working on an interactive healthcare cleaning robot system for the Silver Generation.
	- Object detection to detect people,
	- Face recognition to recognize a particular user,
	- Emotion Recognition for monitoring user emotions,
	- Action Recognition to recognize the user's motion,
	- Pose Estimation to perform the user's exercise assistance role.
![alt_text](../research/cvfolder/architecture.jpg)
 
## Face and Emotion Recognition
그림 1

### Multi-task Emotion Recognition Based on Context-aware and Attention Module
- Emotion recognition is an important research topic in the field of computer vision, and is the primary problem in affective computing, as well as the focus and difficulty of research. It would have a better impact on our lives if we could use inexpensive machines to monitor and understand the emotional information of others. However, there is currently no system that can do such a job. Because human emotional states are expressed in various ways, such as speech, expressions, actions, the environment in which a person is living, and various physiological signals, it is difficult to accurately reflect human emotions by relying on a single characteristic parameter and its features. We propose a framework, Muti-task Emotion Recognition (MTER), with four main models: face feature extraction model, body feature extraction model and context (scene) feature extraction model, and then fusion classification model. It is used to analyze images containing multiple people and recognize fused emotions based on face facial features, body features, and contextual information. The face feature and body feature extraction module takes the face and body parts of the image as input and the information implicit in the image such as facial expression, head position and body pose is extracted. In order to make the emotion recognition actively applied to real life, Fine-tuned Mobilenet lightweight network is utilized to reduce the computational effort and increase the recognition speed.

## Pose and Activity Recognition
![alt_text](../research/cvfolder/AiPE_architecture.jpg)
	
### Attention in Pose Estimation A transformer based pose estimation method
- We propose a bottom-up human pose estimation method that combines the latest achievements in computer vision-transformer. Compared with the original version using VGG, our method uses a multi-headed self-attention mechanism to better localize the key points of the human body and connect the limbs. Even for some blurred, low-resolution images we can still perform human pose estimation, and our method achieves very good results in single and few people situations. However, in dense crowd conditions, our method does not perform human pose estimation as well as VGG, which stems from the weakness of transformer in analyzing small targets. It may also be due to the fact that we did not use the four block stack like the original swin transformer in order to reduce the computational effort and control the downsampling.

### Current Studies
- Emotion Recognition(SOTA)
	- Multitask Emotion Recognition with Incomplete Labels
	- Deep-Emotion: Facial Expression Recognition Using Attentional Convolutional Network
- Activity Recognition(SOTA)
	- Multi-Label Activity Recognition using Activity-speciﬁc Features and Activity Correlations
	- Masked Autoencoders Are Scalable Vision Learners
- Spatial Transformer Networks
- Vision Transformer


## Research Results
- [Master Thesis] 장이나 석사논문 Multi-task Emotion Recognition Based on Context-aware and Attention Module,2022.06
- [Master Thesis] 루카이 석사논문 AiPE: Attention in Pose Estimation A transformer based pose estimation method, 2022.06


