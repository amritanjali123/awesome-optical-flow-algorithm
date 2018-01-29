[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# Optical Flow Algorithm Resources
A curated list of resources dedicated to optical flow algorithms. Any suggestions and pull requests are welcome.

## Papers & Code

### Classical methods
- [1981-IJCAI, Lucas-Kanade method] An iterative image registration technique with an application to stereo vision
- [1981-AI, Horn-Schunck method] Determining optical flow [`paper`](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.66.562&rep=rep1&type=pdf)
- [2005-IJCV] Lucas/Kanade meets Horn/Schunck: Combining local and global optic flow methods [`paper`](http://www.mia.uni-saarland.de/Publications/bruhn-ijcv05c.pdf)
- [2007-DAGM, TVL1 method] A duality based approach for realtime tv-l1 optical flow [`paper`](A duality based approach for realtime tv-l1 optical flow) [`code`](https://docs.opencv.org/master/d6/d39/classcv_1_1cuda_1_1OpticalFlowDual__TVL1.html)

### Deep learning based methods
- [2015-ICCV, FlowNet1] FlowNet: Learning Optical Flow with Convolutional Networks [`paper`](https://arxiv.org/abs/1504.06852) [`new code`](https://github.com/liruoteng/FlowNet)  [`old code`](https://lmb.informatik.uni-freiburg.de/resources/software.php)
- [2017-CVPR, FlowNet2] FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks [`paper`](https://arxiv.org/abs/1612.01925) [`code`](https://github.com/lmb-freiburg/flownet2) [`homepage`](https://lmb.informatik.uni-freiburg.de/Publications/2017/IMKDB17/)

### Optical flow in severe environment (haze, rain)
- [2017-Xiv] Robust Optical Flow Estimation in Rainy Scenes [`paper`](https://arxiv.org/pdf/1704.05239.pdf)

### Others


## Datasets
- [`Flying Chairs (Vision group, Uni-Freiburg)`](https://lmb.informatik.uni-freiburg.de/resources/datasets/FlyingChairs.en.html) `2015`
  - 22872 image pairs, a synthetic dataset with optical flow ground truth
  - Task: optical flow.

- [`ChairsSDHom (Vision group, Uni-Freiburg)`](https://lmb.informatik.uni-freiburg.de/resources/datasets/FlyingChairs.en.html) `2015`
  - 22872 image pairs, a synthetic dataset with optical flow ground truth
  - Task: optical flow
  - Designed to be robust to untextured regions and to produce flow magnitude histograms close to those of the UCF101 dataset (small displacement, less than 1 pixel).

## Open source implementation
- [Optical Flow with OpenCV 3](https://docs.opencv.org/master/d7/d3f/group__cudaoptflow.html) [Extra modules](https://docs.opencv.org/master/d2/d84/group__optflow.html)
