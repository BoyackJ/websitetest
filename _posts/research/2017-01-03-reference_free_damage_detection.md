---
layout: article
teaser: teaser_reference_free_damage_detection.jpg
title: "Reference-free Damage Detection"
categories: research
modified: 1/2/2017 3:59:07 PM 
comments: false
ads: false
image:
  teaser: teaser_reference_free_damage_detection.jpg
   
---

Reference-free Delamination Detection Using Lamb Waves

![](overview.jpg)

## Description
A new Lamb wave based delamination detection technology is proposed to allow detection of delamination in a single wave propagation path without using prior baseline data or a predetermined decision boundary. **This study shows that, if delamination exists along a wave propagation path, the first arrival anti-symmetric (A0) mode is followed by other A0 modes reflected off from the “inside” delamination (figure below).** Unlike other conventional Lamb wave techniques, the proposed technique takes advantage of the first A0 mode reflected off from the inside delamination to instantly identify the existence of delamination. First, the proposed study employs a dual PZT, which is composed of concentric ring and disk PZT segments, for Lamb wave excitation and a circular PZT for sensing. By activating either the circular or ring PZT segment separately, two pitch-catch Lamb wave signals are obtained from the single wave propagation path. Then, a normalized A0 mode signal is decomposed from the measured Lamb wave signals using a previously developed mode decomposition technique, and the first A0 mode reflected off from the delamination is further extracted using a matching pursuit algorithm. Finally, a reference-free damage classifier is built on the extracted A0 mode reflection from the delamination. **Because the proposed technique does not require baseline signals during the entire delamination detection process, robust delamination detection has been achieved even under varying temperature conditions.** 

### Effects of the Delamination on Lamb Wave Propagation
![](effect_of_the_delaniation.jpg)

## Source Code & Data
* All source code are released in **my Github repository**  [[**Link**]](https://github.com/chulminy/Reference_Free_Damage_Detection). 
* If you use the codes and data for you publication, **please cite my paper(s).**

## Publication

* **Chul Min Yeum**, Hoon Sohn, Hyung Jin Lim, and Jeong Beom Ihn. “Reference-Free Delamination Detection Using Lamb Waves.” Structural Control and Health Monitoring 21, no. 5 (May 1, 2014): 675–84. [**[Web]**](http://onlinelibrary.wiley.com/doi/10.1002/stc.1594/abstract).

* **Chul Min Yeum**, Hoon Sohn, Jeong Beom Ihn, Hyung Jin Lim, “Reference-free delamination detection using Lamb wave time delay,” the 8h International Workshop on Structural Health Monitoring, Stanford, CA, September 13-15, 2011. [**[Paper]**](http://chulminy.github.io/cv/Files/Conference/2011_IWSHM_Paper.pdf),[**[PPT]**](http://chulminy.github.io/cv/Files/Conference/2011_IWSHM_PPT.pdf). 

## Collaborators
* Hoon Sohn
* Jeon Beom Ihn

## Acknowledgment
This work is supported by the Boeing Company, the Radiation Technology Program (M20703000015-07N0300-01510) and the Nuclear Research & Development Program (2009-0083489) of National Research Foundation of Korea (NRF) funded by Ministry of Education, Science & Technology (MEST).

**More information are posted in the my Github repository** [[**Link**]](https://github.com/chulminy/Reference_Free_Damage_Detection). 