---
layout: article
teaser: teaser_autonomous_image_localization.jpg
title: "Autonomous Image Localization"
categories: research
modified: 1/2/2017 3:59:07 PM 
comments: false
ads: false
image:
  teaser: teaser_autonomous_image_localization.jpg
   
---

Autonomous Image Localization for Visual Inspection of Civil Infrastructure

![](overview.jpg)

## Description
Low-cost, high-performance vision sensors in conjunction with aerial sensing platforms are providing new possibilities for achieving autonomous visual inspection in civil engineering structures. **A large volume of images** of a given structure can readily be collected for use in visual inspection, overcoming spatial and temporal limitations associated with human-based inspection. Although researchers have explored several algorithms and techniques for vision-based inspection in recent decades, a major challenge in past implementations lies in dealing with **a high volume of images while only a small fraction of them are important for actual inspection.** Because processing irrelevant images can generate a significant number of false-positives, **automated visual inspection techniques should be used in coordination with methods to localize relevant regions on the images**. When combined, automated visual inspection will be able to meet the objectives and quality of human visual inspection. To enable this technology, **we develop and validate a novel automated image localization technique to extract regions of interest (ROIs) on each of the images before utilizing vision-based damage detection techniques.** ROIs are the portions of an image that contain the physical region of the structure that is targeted for visual interrogation, denoted as the targeted region of interest (TRI). ROIs are computed based on the geometric relationship between the collected images and the TRIs. Analysis of such highly relevant and localized images would enable efficient and reliable visual inspection. We successfully demonstrate the capability of the technique to extract the ROIs using a full-scale highway sign structure in the case where weld connections serve as the TRIs. 

## Source Code & Data
* All source code are released in **my Github repository** [[**Link**]](https://github.com/chulminy/Autonomous_Image_Localization)
* You can download original images and result files from this link [[**Link**]](https://www.amazon.com/clouddrive/share/EXfufKpHtAIS22ewYNi7q7p30yr4woC9sS09ShYE8zB?ref_=cd_ph_share_link_copy).  
* All three datasets are published through this link, but, result images of 'dataset1' are only inlcluded.  
* If you use the codes and images for your publication, **please cite my paper(s).**

## Publication
* **Chul Min Yeum**, Jongseong Choi, and Shirley J. Dyke. “Autonomous image localization for visual inspection of civil infrastructure” ***accepted for Smart Materials and Structures*** (December,2016). **Please send me an email to read this paper before it is available in online.** 

* **Chul Min Yeum**,  Jongseong Choi, and Shirley J. Dyke. “Image localization for computer-enhanced visual inspection of civil infrastructure," ***submitted to Engineering Mechanics Institute (EMI) Conference***, San Diego, CA, June 4-7 2017. 

* **Chul Min Yeum**. “Computer Vision-Based Structural Assessment Exploiting Large Volumes of Images,"  (Doctoral dissertation), Lyles School of Civil Engineering, Purdue University, West Lafayette, Indiana, USA, December 2016. [**[PPT]**](Files\Dissertation\2016_PhD_Defence_CM_Final.pdf).

## Collaborators
* [**Shirley J. Dyke**](https://engineering.purdue.edu/IISL/)
* Chul Min Yum

## Acknowledgment
The authors thank Kevin Brower and Harry Tidrick at the Bowen lab for placing and assembling the full-scale truss and Prof. Robert Connor at Purdue University for helping to acquire the truss used in this study. 

## Key Results

### Localized Region-of-interest on each images

<iframe width="854" height="480" src="https://www.youtube.com/embed/ippPJZJjJI4?list=PLa1nAPP8qUX8bBfN8ZCufGaL4M5sYeOXL" frameborder="0" allowfullscreen></iframe>

Note that due to the fixed frame size, the original images in the video are cropped. Thus, some red boxes appear to be located at the boundary of the images. However, the ROIs that are fully included in each image are only extracted in this study.

### Regions-of-interest (ROIs) corresponding to the identical TRI, which are extracted from different images

<iframe width="854" height="480" src="https://www.youtube.com/embed/876qzwDhuWY?list=PLa1nAPP8qUX8bBfN8ZCufGaL4M5sYeOXL" frameborder="0" allowfullscreen></iframe>


**More information are posted in the my Github repository** [[**Link**]](https://github.com/chulminy/Acceleration_Based_Automated_Vehicle). 