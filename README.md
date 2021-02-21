# MTMC
A paper list of Multi target Multi Camera (MTMC) tracking and related topics

## Multi target Single Camera Tracking Paper

### 2021
- TrackFormer: Multi-Object Tracking with Transformers, Meinhardt et al. 
> Transformer, detection and tracking simultaneously

### 2020
- How To Train Your Deep Multi-Object Tracker, Xu et al. 
> Deep Hungarian Net, approximate MOTA, MOTP for loss function directly

- Learning a Neural Solver for Multiple Object Tracking, Braso & Leal-Taixe
> apperance embedding (node) and geometry distance embedding (edge) for graph, edge classification with cross entropy loss 

### 2019
- Spatial-Temporal Relation Networks for Multi-Object Tracking, Xu et al. 
> use appearance, location and topology cues for similarity score, then graph solved by Hungarian algorithm

- Graph convolutional tracking, Gao et al.
> GNN, Siamese network

- Tracking without bells and whistles, Bergmann et al. 
> motion and appearance extention -> Tracktor++

### 2018

- Exploit the Connectivity: Multi-Object Tracking with TrackletNet, Wang et al. 
> use epipolar geometry, tracklet as node in graph

### 2017
- Multi-Object Tracking with Quadruplet Convolutional Neural Networks, Son et al. 
> learn statistics to normalize effect of camera poses, temporal adjacent constraint for data association 

- Real-Time Multiple Object Tracking, Murray.
> not use appearance feature, very fast, not accurate

- High-Speed Tracking-by-Detection Without Using Image Information, Bochinski et al. 
> IoU tracker, no visual cues used, fast  

### 2016
- Learning by tracking: Siamese CNN for robust target association, Leal-Taixe et al.
> use Siamese CNN to learn similarity, for data association, graph solved by Linear Programming 
- 

### 2014
- Learning an image-based motion context for multiple people tracking, Leal-Taixe et al.
> interaction between objects, relax the dependency of tracking on detections


## Multi target Multi Camera Tracking Paper

### 2020
- Real-time 3D Deep Multi-Camera Tracking, You & Jiang
> fusion all views into ground-plane occupancy heatmap 

- City-Scale Multi-Camera Vehicle Tracking by Semantic Attribute Parsing and Cross-Camera Tracklet Matching, He et al. 
> tracklet representation with spatial-temporal attention, then tracklet-to-target assignment

- Multi-Target Multi-Camera Tracking by Tracklet-to-Target Assignment, He et al.
> tracklet-to-target assignment

### 2018
- Features for Multi-Target Multi-Camera Tracking and Re-Identification, Ristani & Tomasi
> tracklet -> single camera trajectory (correlation clustering) -> multi camera trajectory

### 2017
- Multi-Camera Multi-Target Tracking with Space-Time-View Hyper-graph, Wen et al. 
> 3D position for affinity computation, need know camera parameters, cross-view coupling before trajectory


## Useful Github Repo
- [Multi-Camera Live Object Tracking](https://github.com/LeonLok/Multi-Camera-Live-Object-Tracking)
> based on DeepSORT and YOLO v4

- [2018 NVIDIA AI City Challenge Team iamai](https://github.com/cw1204772/AIC2018_iamai)<br/>
> Vehicle Re-Identification with the Space-Time Prior

- [Resource collection about multi camera network](https://github.com/YanLu-nyu/Awesome-Multi-Camera-Network)<br/>

- [UAV detection and tracking](https://github.com/tau-adl/Detection_Tracking_JetsonTX2)<br/>

- [Resource collection about person reid dataset](https://github.com/NEU-Gou/awesome-reid-dataset)<br/>

- [OpenMMLab: toolbox for SOT, MOT](https://github.com/open-mmlab/mmtracking)

## Famous Group or Researchers

- [Dynamic Vision and Learning Group, TUM](https://dvl.in.tum.de/research/)
> TrackFormer, Tracktor++, Siamese


<!--
[DeepSORT](https://github.com/nwojke/deep_sort) <br/>
<br/>
<br/>
-->
