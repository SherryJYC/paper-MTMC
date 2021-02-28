# MTMC
A paper list of Multi target Multi Camera (MTMC) tracking and related topics

<details><summary>Click to show menu</summary>
<p>

1. <a href="#multi-target-single-camera-tracking-paper">Multi Target Single Camera Tracking Paper </a> <br/>
2. <a href="#multi-target-multi-camera-tracking-paper">Multi Target Multi Camera Tracking Paper </a> <br/>
3. <a href="#related-github-repo">Related Github Repo</a> <br/>
4. <a href="#related-competition">Related Competition</a> <br/>
5. <a href="#related-group-or-researcher">Related Group or Researcher</a>

</p>
</details>

## Multi Target Single Camera Tracking Paper 

### 2021
- TrackFormer: Multi-Object Tracking with Transformers, Meinhardt et al. [[paper]](https://arxiv.org/abs/2101.02702)
> Transformer, detection and tracking simultaneously

### 2020
- How To Train Your Deep Multi-Object Tracker, Xu et al. :rainbow: [[paper]](https://arxiv.org/abs/1906.06618)
> Deep Hungarian Net, approximate MOTA, MOTP for loss function directly

- Learning a Neural Solver for Multiple Object Tracking, Braso & Leal-Taixe :rainbow: [[paper]](https://arxiv.org/abs/1912.07515)
> apperance embedding (node) and geometry distance embedding (edge) for graph, edge classification with cross entropy loss 

- Deep learning in video multi-object tracking: A survey, Ciaparrone et al. [[paper]](https://arxiv.org/abs/1907.12740)
> pipeline: detection, feature extraction, affinity, association

### 2019
- Spatial-Temporal Relation Networks for Multi-Object Tracking, Xu et al. [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Spatial-Temporal_Relation_Networks_for_Multi-Object_Tracking_ICCV_2019_paper.pdf)
> use appearance, location and topology cues for similarity score, then graph solved by Hungarian algorithm

- Graph convolutional tracking, Gao et al. [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Gao_Graph_Convolutional_Tracking_CVPR_2019_paper.pdf)
> GNN, Siamese network

- Tracking without bells and whistles, Bergmann et al. [[paper]](https://arxiv.org/abs/1903.05625) [[code]](https://github.com/phil-bergmann/tracking_wo_bnw)
> motion and appearance extention -> Tracktor++

- Deep Learning for Visual Tracking: A Comprehensive Survey, Marvasti-Zadeh et al. [[paper]](https://arxiv.org/abs/1912.00535)
> traditional and deep visual trackers 

- A Review of Visual Trackers and Analysis of its Application to Mobile Robot, You et al. [[paper]](https://arxiv.org/abs/1910.09761)
> correlation filter, deep learning and convolutional features

### 2018

- Exploit the Connectivity: Multi-Object Tracking with TrackletNet, Wang et al. [[paper]](https://arxiv.org/abs/1811.07258)
> use epipolar geometry, tracklet as node in graph

- Real-time Multiple People Tracking with Deeply Learned Candidate Selection and Person Re-Identification, Chen et al. [[paper]](https://arxiv.org/abs/1809.04427)[[code]](https://github.com/longcw/MOTDT)
> online MOT tracker

### 2017
- Multi-Object Tracking with Quadruplet Convolutional Neural Networks, Son et al. [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Son_Multi-Object_Tracking_With_CVPR_2017_paper.pdf)
> learn statistics to normalize effect of camera poses, temporal adjacent constraint for data association 

- Real-Time Multiple Object Tracking, Murray. [[paper]](https://www.diva-portal.org/smash/get/diva2:1146388/FULLTEXT01.pdf)
> not use appearance feature, very fast, not accurate

- High-Speed Tracking-by-Detection Without Using Image Information, Bochinski et al. [[paper]](http://elvera.nue.tu-berlin.de/files/1517Bochinski2017.pdf) [[code]](https://github.com/bochinski/iou-tracker)
> IoU tracker, no visual cues used, fast  

- Online Multi-Target Tracking Using Recurrent Neural Networks, Milan et al. [[paper]](https://arxiv.org/abs/1604.03635)
> RNN as tracker, LSTM for data association

### 2016
- Learning by tracking: Siamese CNN for robust target association, Leal-Taixe et al. [[paper]](https://arxiv.org/abs/1604.07866)
> use Siamese CNN to learn similarity, for data association, graph solved by Linear Programming 

### 2014
- Learning an image-based motion context for multiple people tracking, Leal-Taixe et al. [[paper]](https://ieeexplore.ieee.org/document/6909848)
> interaction between objects, relax the dependency of tracking on detections


## Multi Target Multi Camera Tracking Paper

### 2020
- Real-time 3D Deep Multi-Camera Tracking, You & Jiang [[paper]](https://arxiv.org/abs/2003.11753)
> fusion all views into ground-plane occupancy heatmap 

- City-Scale Multi-Camera Vehicle Tracking by Semantic Attribute Parsing and Cross-Camera Tracklet Matching, He et al. [[paper]](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w35/He_City-Scale_Multi-Camera_Vehicle_Tracking_by_Semantic_Attribute_Parsing_and_Cross-Camera_CVPRW_2020_paper.pdf)
> tracklet representation with spatial-temporal attention, then tracklet-to-target assignment

- Multi-Target Multi-Camera Tracking by Tracklet-to-Target Assignment, He et al. [[paper]](https://ieeexplore.ieee.org/document/9042858)
> tracklet-to-target assignment

- AI City Challenge 2020 – Computer Vision for Smart Transportation Applications, Chang et al. [[paper]](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w35/Chang_AI_City_Challenge_2020_-_Computer_Vision_for_Smart_Transportation_CVPRW_2020_paper.pdf)
> single camera tracklet -> multi-camera tracklet fusion with appearance and physical features

- Multi-Camera Tracking of Vehicles based on Deep Features Re-ID and Trajectory-Based Camera Link Models, Hsu et al. [[paper]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/AI%20City/Hsu_Multi-Camera_Tracking_of_Vehicles_based_on_Deep_Features_Re-ID_and_CVPRW_2019_paper.pdf)
> use TrackletNet for single camera trajectory -> inter-camera tracking

- ELECTRICITY: An Efficient Multi-camera Vehicle Tracking System for Intelligent City, Qian et al. [[paper]](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w35/Qian_ELECTRICITY_An_Efficient_Multi-Camera_Vehicle_Tracking_System_for_Intelligent_City_CVPRW_2020_paper.pdf)
> single camera tracking -> match tracklets across camera views

- Pose-Assisted Multi-Camera Collaboration for Active Object Tracking, Li et al. [[paper]](https://arxiv.org/abs/2001.05161) [[code]](https://github.com/LilJing/pose-assisted-collaboration)
> Reinforcement learning, collaborative multi-camera

- Reconstruction of 3D flight trajectories from ad-hoc camera networks, Li et al. [[paper]](https://arxiv.org/abs/2003.04784) [[code]](https://github.com/CenekAlbl/mvus)
> camera synchronization, SfM, Bundle Adjustment, spline representation for drone trajectory  

### 2019
- People tracking in multi-camera systems: a review, Iguernaissi et al. [[paper]](https://link.springer.com/article/10.1007/s11042-018-6638-5)
> Centralized (combine cross-camera views before tracking, like Wen et al.) and Distributed methods (single-camera tracking before fusion)

- CityFlow: A City-Scale Benchmark for Multi-Target Multi-Camera Vehicle Tracking and Re-Identification, Tang et al. [[paper]](https://arxiv.org/abs/1903.09254)

- Real-Time Multi-Target Multi-Camera Tracking with Spatial-Temporal Information, Zhang & Izquierdo :rainbow: [[paper]](https://ieeexplore.ieee.org/document/8965845)
> single camera detection -> create/match to track, with apperance, motion, spatial-temporal cues (cross-camera)

### 2018
- Features for Multi-Target Multi-Camera Tracking and Re-Identification, Ristani & Tomasi [[paper]](https://arxiv.org/abs/1803.10859) [[code]](https://github.com/SamvitJ/Duke-DeepCC)
> tracklet -> single camera trajectory (correlation clustering) -> multi camera trajectory

- Vehicle Re-Identification with the Space-Time Prior, Wu et al. [[paper]](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Wu_Vehicle_Re-Identification_With_CVPR_2018_paper.pdf) [[code]](https://github.com/cw1204772/AIC2018_iamai)
> single camera tracking -> CNN feature extraction -> multi camera tracking (KMeans)

### 2017
- Multi-Camera Multi-Target Tracking with Space-Time-View Hyper-graph, Wen et al. :rainbow: [[paper]](https://link.springer.com/article/10.1007/s11263-016-0943-0)
> 3D position for affinity computation, need know camera parameters, cross-view coupling before trajectory

### 2014
- Persistent Tracking for Wide Area Aerial Surveillance, Prokaj & Medioni :rainbow: [[paper]](https://ieeexplore.ieee.org/document/6909551)
> two tracker (detection and regression) in parallel, measure their correspondence

### 2013
- Hypergraphs for joint multi-view reconstruction and multi-object tracking, Hofmann et al. :rainbow: [[paper]](https://ieeexplore.ieee.org/document/6619312) [[code]](https://github.com/neohanju/HYPERGRAPH_TRACKING)
> detection as node in hypergraph to find 3d reconstruction, which is node in a min-cost flow graph, solved by binary linear programming

## Related Github Repo
- [Multi-camera live object tracking](https://github.com/LeonLok/Multi-Camera-Live-Object-Tracking)

- [Resource collection about multi camera network](https://github.com/YanLu-nyu/Awesome-Multi-Camera-Network)<br/>

- [Recource collection about multi object tracking](https://github.com/nightmaredimple/Multi-object-Tracking-paper-code-list)

- [UAV detection and tracking](https://github.com/tau-adl/Detection_Tracking_JetsonTX2)<br/>

- [Resource collection about person reid dataset](https://github.com/NEU-Gou/awesome-reid-dataset)<br/>

- [OpenMMLab: toolbox for SOT, MOT](https://github.com/open-mmlab/mmtracking)

- [DeepOcculusion](https://github.com/pierrebaque/DeepOcclusion)

- [MOT Metrics library (Python)](https://github.com/cheind/py-motmetrics)

## Related Competition
- [AI City Challenge](https://www.aicitychallenge.org/)

- [Anti-UAV Challenge](https://anti-uav.github.io/)

- [Waymo Open Dataset Challenge](https://waymo.com/open/challenges)

## Related Group or Researcher

- [Dynamic Vision and Learning Group, TUM](https://dvl.in.tum.de/research/)
> TrackFormer, Tracktor++, Siamese

- [CVLab, EPFL](https://www.epfl.ch/labs/cvlab/research/research-surv/research-body-surv-index-php/)
> Probabilistic Occupancy Map


<!--
[DeepSORT](https://github.com/nwojke/deep_sort) <br/>
<br/>
<br/>
-->
