---
layout: default
---

# About me

Hi! I'm currently a second-year PhD student co-advised by Prof. [Yao Wang](https://engineering.nyu.edu/faculty/yao-wang) (ECE department, NYU) and Dr. [Hiroshi Ishikawa](https://med.nyu.edu/faculty/hiroshi-ishikawa) (School of Medicine, NYU). I'm interested in medical image processing, machine learning, and computer vision. [CV](./assets/img/CV_20200421.pdf)

# Projects

### [Video Interpolation: Warping Toward Middle Frames in Pyramids](./posts/proj_video_interp.html).
Many video interpolation methods use optical flow explicitly or implicitly to synthesize the intermediate frame. However, the performance of these methods could suffer from the inaccuracy of estimated optical flows. In this paper, we propose a light but effective CNN model with a pyramid structure to generate the optical flows of the unknown middle frame with respect to the past and future known frame from coarse to fine scales. We warp CNN features of the input frames to the intermediate frame using the estimated flows and construct cost volumes at every pyramid level. The cost volume together with the warped pyramid features and input frames are processed by CNN to estimate the optical flows at the next finer scale. At the finest scale, the two warped frames are adaptively blended to generate the intermediate frame. We evaluate our framework on multiple datasets. The test results show our method achieves state-of-the-art performance. Moreover, the number of parameters in our network is more than three times smaller than previous state-of-the-art models, making the proposed model substantially easier to train and computationally less demanding for inference.

### [Video Prediction via Dynamic Deformable Neural Netowrk](https://github.com/zhiqiiiiiii/deform-dfn)
Video prediction is useful in daily life, like getting early warning of possible danger, video coding and etc. However, the variance in different videos, like different motion patterns, object scales, poses, and viewpoints, raises challenge in this task. In this paper, we propose a sample-specific deformable framework, the Dynamic Deformable Filter Network (Deform-DFN), where deformable filters are generated conditionally on the input. Not like traditional convolutional neural networks (CNNs), the learned filters parameters and geometric structures stay fixed after training. Our model is able to adapt to different samples so that it enhances the transformation modeling capability of CNNs. The Deform-DFN consists of a parameter filter generating network that learns to produce sample specific filter and offsets, and a dynamic deformable filtering layer that applied those sample-specific filters and offsets on the input to get the predicted frames. We demonstrated the effectiveness of our framework in video prediction tasks on Moving MNIST dataset. Our deform-DFN is able to produce better prediction than dynamic filter networks with smaller kernel size.

### [Macular GCIPL Thickness Map Prediction via Time-Aware Convolutional LSTM](./posts/proj_gcipl.html)
Macular ganglion cell inner plexiform layer (GCIPL) thickness is an important biomarker for clinical managements of glaucoma. Clinical analysis of GCIPL progression uses averaged thickness only, which easily washes out small changes and reveals no spatial patterns. This is the first work to predict the 2D GCIPL thickness map. We propose a novel Time-aware Convolutional Long Short-Term Memory (TC-LSTM) unit to decompose memories into the short-term and long-term memories and exploit time intervals to penalize the short-term memory. TC-LSTM unit is incorporated into an auto-encoder-decoder so that the end-to-end model can handle irregular sampling intervals of longitudinal GCIPL thickness map sequences and capture both spatial and temporal correlations. Experiments show the superiority of the proposed model over the traditional method.

# My BFFs!

[Feiran Yang](https://feirany.github.io/) - M.S. Candidate, Dept. of Bioengineering, University of Washington.

[Jing Zhang](https://jingzhang2011.wordpress.com/) - Ph.D. Candidate, Dept. of Biomedical Engineering, Boston University.
!(./assets/img/bff.jpeg)

<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?d=UQmLHErLJySUu8_Q1ma0Ahp9NJ0lh5_nMo6oNvcIH5w&cl=ffffff&w=a"></script>
