## Welcome to iCurb Project Pages

RAL & ICRA2021 paper "iCurb: Imitation Learning-based Detection of Road Curbs using Aerial Images for Autonomous Driving"

Authors: Zhenhua Xu, Yuxiang Sun, Ming Liu

## Abstract

Detection of road curbs is an essential capability for autonomous driving. It can be used for autonomous vehicles to determine drivable areas on roads. Usually, road curbs are detected on-line using vehicle-mounted sensors, such as video cameras and 3-D Lidars. However, on-line detection using video cameras may suffer from challenging illumination conditions, and Lidar-based approaches may be difficult to detect far-away road curbs due to the sparsity issue of point clouds. In recent years, aerial images are becoming more and more worldwide available. We find that the visual appearances between road areas and off-road areas are usually different in aerial images, so we propose a novel solution to detect road curbs off-line using aerial images. The input to our method is an aerial image, and the output is directly a graph (i.e., vertices and edges) representing road curbs. To this end, we formulate the problem as an imitation learning problem, and design a novel network and an innovative training strategy to train an agent to iteratively find the road-curb graph. The experimental results on a public dataset confirm the effectiveness and superiority of our method. This work is accompanied with a demonstration video and a supplementary document at https://sites.google.com/view/icurb.

## Demo video
[![Watch the video](https://img.youtube.com/vi/Yvk4xYA4JrI/0.jpg)](https://youtu.be/Yvk4xYA4JrI)


## Supplymentary document
More details of our implementation and extra visualization are provided.
### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
