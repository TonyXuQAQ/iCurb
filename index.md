## Welcome to iCurb Project Pages

RAL & ICRA2021 paper "iCurb: Imitation Learning-based Detection of Road Curbs using Aerial Images for Autonomous Driving"

Authors: Zhenhua Xu, Yuxiang Sun, Ming Liu

## Abstract

Detection of road curbs is an essential capability for autonomous driving. It can be used for autonomous vehicles to determine drivable areas on roads. Usually, road curbs are detected on-line using vehicle-mounted sensors, such as video cameras and 3-D Lidars. However, on-line detection using video cameras may suffer from challenging illumination conditions, and Lidar-based approaches may be difficult to detect far-away road curbs due to the sparsity issue of point clouds. In recent years, aerial images are becoming more and more worldwide available. We find that the visual appearances between road areas and off-road areas are usually different in aerial images, so we propose a novel solution to detect road curbs off-line using aerial images. The input to our method is an aerial image, and the output is directly a graph (i.e., vertices and edges) representing road curbs. To this end, we formulate the problem as an imitation learning problem, and design a novel network and an innovative training strategy to train an agent to iteratively find the road-curb graph. The experimental results on a public dataset confirm the effectiveness and superiority of our method.

## Demo video
[![Watch the video](https://img.youtube.com/vi/fMhcZm_MPUE/0.jpg)](https://youtu.be/fMhcZm_MPUE)


## Supplymentary document
More details of our implementation and extra visualization are provided in our [supplementary document](https://github.com/TonyXuQAQ/iCurb.github.io/blob/main/2020_RAL_ICRA_supplementary_v2.pdf).

## Contact
Any questons, comments and suggestions are welcomed! Please send email to **zxubg at connect dot ust dot hk**.

## Citation
