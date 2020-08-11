---
title: "Weakly Supervised Fusion of Multiple Overhead Images"
collection: publications
permalink: /publication/2019-Fusion-CVPRW
excerpt: 'This paper proposes an image fusion method to combine multiple overhead images to make a single good looking image. Our method is weakly supervised; it learns to removes clouds and other artifacts from images with limited labels.'
date: 2019-06-01
venue: 'IEEE Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), EarthVision'
---
&emsp; &emsp; [Muhammad Usman Rafique](http://urafique.com), &emsp; [Hunter Blanton](hblanton.github.io/), &emsp; [Nathan Jacobs](https://jacobsn.github.io/)

##  &emsp;  &emsp; &emsp;  &emsp;  &emsp; &emsp;  &emsp; &emsp;  &emsp;   &emsp; [[Paper]](http://openaccess.thecvf.com/content_CVPRW_2019/papers/EarthVision/Rafique_Weakly_Supervised_Fusion_of_Multiple_Overhead_Images_CVPRW_2019_paper.pdf)   &emsp;  &emsp;      [[Code]](https://github.com/UkyVision/weakly-supervised-image-fusion)

## Overview
![Fusion overview](/images/fusion19.png)
 We present a fusion method which can fuse multiple images of a region: these images might have artifacts like missing data or occlusion by clouds. Our method is weakly supervised as we do not need labels for missing data or clouds, we just need dense labels for semantic segmentation.
 
## Abstract
This work addresses the problem of combining noisy overhead images to make a single high-quality image of a region. Existing fusion methods rely on supervised learning, which requires image quality annotations, or ad hoc criteria, which do not generalize well. We formulate a weakly supervised method, which learns to predict image quality at the pixel-level by optimizing for semantic segmentation. This means our method only requires semantic segmentation labels, not explicit artifact annotations in the input images. We evaluate our method under varying levels of occlusions and clouds. Experimental results show that our method is significantly better than a baseline fusion approach and nearly as good as the ideal case, a single noise-free image.

## Recommended citation
<pre>
@inproceedings{usman2019weakly,
  title={Weakly Supervised Fusion of Multiple Overhead Images},
  author={Rafique, M. Usman and Blanton, Hunter and Jacobs, Nathan},
  booktitle={The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
  year={2019}
}
</pre>
