---
title: "Revisiting Near/Remote Sensing with Geospatial Attention"
collection: publications
permalink: /revisiting_nrs/
excerpt: 'We propose a novel architecture for the task of overhead image segmentation when auxiliary ground-level images are available'
date: 2022-03-03
venue: 'The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2022'
---

&emsp; &emsp; [Scott Workman](http://cs.uky.edu/~scott/),&emsp; [Muhammad Usman Rafique](http://urafique.com), &emsp; [Hunter Blanton](https://hblanton.github.io/), &emsp; [Nathan Jacobs](https://jacobsn.github.io/)

##  &emsp; &emsp; [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Workman_Revisiting_NearRemote_Sensing_With_Geospatial_Attention_CVPR_2022_paper.pdf) &emsp;  [Supplemental](https://openaccess.thecvf.com/content/CVPR2022/supplemental/Workman_Revisiting_NearRemote_Sensing_CVPR_2022_supplemental.pdf) &emsp;  [Talk](https://drive.google.com/file/d/1JCbT_o95YgZ4nDAsKTIfHQ5RhtO_UusU/view)

## Overview
![Problem overview](/images/nrs_problem.png)

## Abstract
This work addresses the task of overhead image segmentation when auxiliary ground-level images are available. Recent work has shown that performing joint inference over these two modalities, often called near/remote sensing, can yield significant accuracy improvements. Extending this line of work, we introduce the concept of geospatial attention, a geometry-aware attention mechanism that explicitly considers the geospatial relationship between the pixels in a ground-level image and a geographic location. We propose an approach for computing geospatial attention that incorporates geometric features and the appearance of the overhead and ground-level imagery. We introduce a novel architecture for near/remote sensing that is based on geospatial attention and demonstrate its use for five segmentation tasks. The results demonstrate that our method significantly outperforms the previous state-of-the-art methods.

## Approach
![Approach](/images/nrs_approach.png)
We propose a high-level neural network architecture for the task of near/remote sensing. Our architecture, visualized in Figure 3, has three primary components. First, we extract features from each image modality. Next, we use geospatial attention to generate a spatially consistent, dense grid of geo-informative features from the set of nearby ground-level images. Finally, we fuse the dense ground-level feature map with the overhead image feature map and use that as input to a decoder that generates the segmentation output. All components are differentiable, enabling end-to-end optimization of the low-level feature extraction networks and the attention model for the given segmentation task

Please refer to [the paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Workman_Revisiting_NearRemote_Sensing_With_Geospatial_Attention_CVPR_2022_paper.pdf) for more details.
## Results

![Quantitative Results](/images/nrs_results1.png)

![Qualitative Results](/images/nrs_results2.png)


## Recommended citation

<pre>
@inproceedings{workman2022revisiting,
  title={Revisiting Near/Remote Sensing with Geospatial Attention},
  author={Workman, Scott and Rafique, M. Usman and Blanton, Hunter and Jacobs, Nathan},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2022}
}
</pre>
