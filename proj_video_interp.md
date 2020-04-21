---
layout: default_no_logo
---

## Video Interpolation: Warping Towards Middle Frames in Pyramids
Many video interpolation methods use optical flow explicitly or implicitly to synthesize the intermediate frame. However, the performance of these methods could suffer from the inaccuracy of estimated optical flows. In this paper, we propose a light but effective CNN model with a pyramid structure to generate the optical flows of the unknown middle frame with respect to the past and future known frame from coarse to fine scales. We warp CNN features of the input frames to the intermediate frame using the estimated flows and construct cost volumes at every pyramid level. The cost volume together with the warped pyramid features and input frames are processed by CNN to estimate the optical flows at the next finer scale. At the finest scale, the two warped frames are adaptively blended to generate the intermediate frame. We evaluate our framework on multiple datasets. The test results show our method achieves state-of-the-art performance. Moreover, the number of parameters in our network is more than three times smaller than previous state-of-the-art models, making the proposed model substantially easier to train and computationally less demanding for inference.

<iframe width="560" height="315"
src="https://www.youtube.com/embed/aWmoQm0E7hk" 
frameborder="0" 
allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>

<center><embed src="./assets/img/poster_video_interpolation.pdf" width="560" height="315"></center>
