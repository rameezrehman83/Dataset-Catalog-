# Dataset-Catalog
A catalog for `/data3`.

| Dataset Name                                  | Path                                 | Size               | Home Page                                                    | Keywords                                                     | Miscellaneous                                                |
| --------------------------------------------- | ------------------------------------ | ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| DukeMTMC                                      | `/data3/DukeMTMC`                    | 1.4T               | http://vision.cs.duke.edu/DukeMTMC/                          | Multi-Track Multi-Camera Tracking                            |                                                              |
| LFW                                           | `/data3/LFW`                         | 472.6G             | http://vis-www.cs.umass.edu/lfw/                             | Face Verification                                            | Including RGB imgs, gray-scale imgs, extracted features.     |
| PRW                                           | `/data3/PRW`                         | 152.2G             | http://www.liangzheng.com.cn/Project/project_prw.html        | Person Search/Re-identification                              | Including imgs, bboxes, masks                                |
| CUHK-SYSU                                     | `/data3/CUHK_Person_Search`          | 98.1G              | http://www.ee.cuhk.edu.hk/~xgwang/PS/dataset.html            | Person Search/Re-identification                              | Including imgs, bboxes, masks                                |
| MPII                                          | `/data3/MPII`                        | 24G                | http://human-pose.mpi-inf.mpg.de/                            | 2D Pose Estimation                                           | Including images, processed masks and keypoint anntations    |
| AIchallenge                                   | `/data3/AIchallenge`                 | 29G                | https://challenger.ai/competition/keypoint/subject           | 2D Multi-Person Pose Estimation                              | The dataset of AIchallenge for human pose estimation, including images, bboxes and keypoint annotations. |
| Kitti                                         | `/data3/Kitti`                       | 357G               | http://www.cvlibs.net/datasets/kitti/                        | Autonomous Driving                                           | Including stereo and optical flow image pairs, stereo visual odometry sequences, and 3D object annotations |
| COCO                                          | `/data3/MSCOCO`                      | 140G               | http://cocodataset.org/#home                                 | Detection/ Pose Estimation/ Segmentation                     |                                                              |
| XJTU2017                                      | `/data3/XJTU2017`                    | 25.9G              | http://ccvai.xjtu.edu.cn/qxkz/yhdl.jsp?urltype=tree.TreeTempUrl&wbtreeid=1035&wbnewsid=1300 | Traffic Line Detection; Traffic Sign Detection; Vehicle Detection; Lane Keeping Monitoring; Vehicle Distance Estimation | Including Images, traffic lines, traffic sign bboxes and types, vehicle bboxes, vehicle distances |
| DeepInsight                                   | `/data3/DeepInsight`                 | 296G               | (no website)                                                 | Self-constructed dataset for traffic line detection (under development) | Including images, hand-labeled traffic lines (still going on), some codes for processing images and labels, several pre-trained models |
| ImageNet/ILSVRC2015                           | `/data3/ImageNet/ILSVRC2015`         | 179G               | http://image-net.org/challenges/LSVRC/2015/                  | Object Detection; Object Tracking                            | Including competitions: Object detection and Object detection from video (VID). Same folder name for different tasks, feel free to search the files for what you want. |
| ImageNet/ILSVRC2017                           | `/data3/Imagenet/ILSVRC2017`         | 359G               | http://image-net.org/challenges/LSVRC/2017/                  | Object detection from video                                  | Including all data from the Imagenet 2017 Challenge for video object detection, composed of DET and VID subsets. |
| ALOV                                          | `/data3/alov`                        | 11G                | http://alov300pp.joomlafree.it/                              | Object Tracking                                              | Including annotations and images                             |
| Cityscapes                                    | `/data3/Cityscapes`                  | 31G                | https://www.cityscapes-dataset.com/                          | Segmentation; Detection                                      |                                                              |
| KAIST_Infrared_Pedestrain                     | `/data3/KAIST_Infrared_Pedestrain`   | 36G                | https://sites.google.com/site/pedestrianbenchmark/           | Pedestrian Detection                                         | Including RGB images, infrared images, and labeled bounding box |
| RESIDE                                        | `/data3/RESIDE`                      | 98G                | https://sites.google.com/view/reside-dehaze-datasets         | Single Image Dehazing                                        | Including RGB pairs(haze & clean), gray scale images(transmission maps). |
| pku_Rain                                      | `/data3/pku_Rain/rainALL_ALL`        | 8.6G               | http://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html?jekfcbimoppphdba | Deraining, rain removal from a single image                  | Including RGB pairs(rain & clean), labeled rain steaks.      |
| Snow100K                                      | `/data3/Snow`                        | 16G                | https://sites.google.com/view/yunfuliu/desnownet             | Desnow/ Snow Removal                                         | Including RGB pairs(snow & clean), labeled snow locations.   |
| NYU depth v2                                  | `/data3/NYU_depth`                   | 428G               | https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html     | Depth Estimation from RGB Image                              |                                                              |
| PASCAL VOC                                    | `/data3/PASCAL/VOCdevkit`            | 3G                 | http://host.robots.ox.ac.uk/pascal/VOC/index.html            | Object Detection; Segmentation                               | Including VOC2007 and VOC2012                                |
| CIFAR 10                                      | `/data3/cifar10`                     | 236M               | http://www.cs.toronto.edu/~kriz/cifar.html                   | Object Recognition                                           |                                                              |
| CIFAR 100                                     | `/data3/cifar100`                    | 939M               | http://www.cs.toronto.edu/~kriz/cifar.html                   | Object Recognition                                           |                                                              |
| SVHN                                          | `/data3/SVHN`                        | 2.5G               | http://ufldl.stanford.edu/housenumbers/                      | Number Recognition                                           |                                                              |
| HMDB-51                                       | `/data3/hmdb51`                      | 2.1G               | http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/ | Human Motion Recognition                                     |                                                              |
| DAVIS 17                                      | `/data3/DAVIS17`                     | 12G                | http://davischallenge.org/code.html                          | Video Segmentation                                           |                                                              |
| DAVIS 16                                      | `/data3/DAVIS-data-origin`           | 7.2G               | http://davischallenge.org/code.html                          | Video Segmentation                                           |                                                              |
| Tsinghua-Tencent 100K                         | `/data3/Tsinghua_Tencent_100K`       | 24.5G              | http://cg.cs.tsinghua.edu.cn/traffic-sign/tutorial.html      | Traffic Sign Detection                                       |                                                              |
| Traffic Light Datasets                        | `/data3/TrafficLight`                | 36G                | https://github.com/udacity/self-driving-car/tree/master/annotations， https://hci.iwr.uni-heidelberg.de/node/6132 | Traffic Sign Detection                                       |                                                              |
| SUN RGBD                                      | `/data3/SUNRGBD`                     | 7.39G              | http://rgbd.cs.princeton.edu/                                | Depth Estimation; RGBD object classification                 |                                                              |
| VOT                                           | `/data3/VOT`                         | 1.9G               | http://www.votchallenge.net/                                 | Video Object Tracking                                        | Including vot2014 and vot 2015                               |
| Charades                                      | `/data3/Charades`                    | 396G               | http://allenai.org/plato/charades/                           | Video Recognition & Video Caption                            | Including videos, flows of original size as well as those scaled into 480p, along with two-stream features computed by frames and optical flows in the frequency of 8fps. Evaluation codes were also provided |
| MOT                                           | `/data3/MOT`                         | 1.9G               | https://motchallenge.net/                                    | Multiple-Object Tracking                                     | Including training and testing data of mot dataset for multi object tracking, also including optical flow extracted by flownet2.0 if any help for tracking. |
| MPI-Sintel                                    | `/data3/MPI_Sintel`                  | 12G                | http://sintel.is.tue.mpg.de/                                 | Optical flow estimation                                      | Including all training and testing data of MPI-Sintel dataset, especially for evaluating the performance of optical flow algorithms |
| FlyingThings                                  | `/data3/FlyingThings`                | 1.3T               | https://lmb.informatik.uni-freiburg.de/resources/datasets/SceneFlowDatasets.en.html | Optical flow estimation                                      | Including training and testing data along with those transformed into tensorflow tfrecords files, where optical flow was only transformed from left view as well as in the order of into_future |
| FlyingChairs                                  | `/data3/FlyingChairs/FlyingChairs`   | 1.1T               | https://lmb.informatik.uni-freiburg.de/resources/datasets/FlyingChairs.en.html | Optical flow estimation                                      | Including training and testing data along with those transformed into tensorflow tfrecords files |
| Broden                                        | `/data3/Broden`                      | 1G                 | https://github.com/CSAILVision/NetDissect                    | CNN Interpretbility; Network Dissection                      | Dataset for interpreting disentangled representation in CNN  |
| CASIA WebFace                                 | `/data3/CASIA_WebFace`               | 8.9G               | http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html | Face Recognition/Verification                                |                                                              |
| Market1501                                    | `/data3/Market1501`                  | 2.6G               | http://www.liangzheng.org/Project/project_reid.html          | Person Re-identification                                     |                                                              |
| MARS                                          | `/data3/MARS`                        | 19G                | http://www.liangzheng.com.cn/Project/project_mars.html       | Video-based Person Re-identification                         |                                                              |
| CUHK03                                        | `/data3/CUHK03`                      | 8.7G               | http://www.ee.cuhk.edu.hk/~xgwang/CUHK_identification.html   | Person Re-identification                                     |                                                              |
| GraspingRectangleDataset                      | `/data3/GraspingRectangle/`          | 10G                | http://pr.cs.cornell.edu/deepgrasping/                       | RGBD detection                                               | A dataset for detecting robotic grasps.                      |
| Visual Genome                                 | `  /data3/Visual_Genome`             | 15G                | http://visualgenome.org/                                     | Visual Relationship Detection                                | Visual Genome is a dataset, a knowledge base, an ongoing effort to connect structured image concepts to language. |
| Human 3.6M                                    | `  /data3/Human36M`                  | 32G                | http://vision.imar.ro/human3.6m/description.php              | RGBD Human Pose Estimation                                   | A dataset for detecting human keypoints from RGBD data       |
| UCF-101                                       | `/data3/UCF-all-in-one`              | 94G                | http://crcv.ucf.edu/data/UCF101.php                          | Video analysis                                               | Including UCF-101(the original video), ucf_frame(video frames) and ucf_transed(optical flow) |
| DiDi Self-Driving Dataset                     | `/data3/DiDi`                        | ~500G              | http://research.xiaojukeji.com/                              | 3D Object Detection with multiple sensors                    |                                                              |
| DOTA                                          | `/data3/DOTA`                        | 20G                | http://captain.whu.edu.cn/DOTAweb/                           | Aerial Images; Small Object Detection                        | A Large-scale Dataset for Object Detection in Aerial Images  |
| PoseTrack                                     | `/data3/Posetrack`                   | 33G                | https://posetrack.net/                                       | Pose estimation; Tracking.                                   | PoseTrack is a new large-scale benchmark for human pose estimation and tracking in video. |
| WIDER Person Search                           | `/data3/WIDER_Person_Search`         | 12G                | https://competitions.codalab.org/competitions/19055#participate | Person Search; Person Detection; Re-identification           | WIDER Face & Pedestrain Challenge - Track 3: Person Search   |
| VisDrone                                      | ` /data3/VisDrone`                   | 14G                | http://www.aiskyeye.com/views/index                          | Bird-view detection; Drone survallence detection.            | *Pengfei Zhu, Longyin Wen, Xiao Bian, Haibin Ling and Qinghua Hu, arXiv 2018.* **Vision Meets Drones: A Challenge.** |
| SmartCity                                     | `/data3/smartcity`                   | 28G                | https://cpipc.chinadegrees.cn/cw/hp/1                        | Action Recognition                                           |                                                              |
| RGBT234                                       | `/data3/RGBT234`                     | 7.76G              | https://sites.google.com/view/ahutracking001                 | RGB-T tracking, Thermal image                                | Including RGB images and Thermal images                      |
| TB-100                                        | `/data3/TB-100`                      | 2.76G              | http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html   | Visual Tracker                                               | Including RGB images and ground truth                        |
| Youtube-8M                                    | `/data3/Youtube-8M`                  | 1.8T               | https://research.google.com/youtube8m                        |                                                              |                                                              |
| CUB-200-2011                                  | `/data3/CUB_200_2011`                | 1.1G               | http://www.vision.caltech.edu/visipedia/CUB-200-2011.html    | Bird Classification                                          |                                                              |
| Online Product                                | `/data3/Online_Product`              | 2.9G               | http://cvgl.stanford.edu/projects/lifted_struct/             | Product Retrieval                                            |                                                              |
| Automated Driving 3D Point Cloud Segmentation | `/data3/3D_Point_Cloud_Segmentation` | 86.5G              | https://www.datafountain.cn/competitions/314/details/data-evaluation?tdsourcetag=s_pctim_aiomsg | Dataset for automated driving 3D point cloud segmentation    |                                                              |
| LaSOT                                         | `/data3/LaSOT`                       | 227G               | https://cis.temple.edu/lasot                                 | Large-scale Single Object Tracking (LaSOT)                   | Including images and labels                                  |
| AIChallenger Caption                          | `/data3/ai_challenger_caption`       | 21.7G              | -                                                            | -                                                            | -                                                            |
| UCF_Crime                                     | `/data3/UCF_Crime`                   | 208G               | <http://crcv.ucf.edu/projects/real-world/>                   |                                                              | a dataset for anomaly detection, including initial video, generated images and optical flows |
| KTH                                           | `/data3/KTH`                         | 1G                 | http://www.nada.kth.se/cvap/actions/                         |                                                              | The current video database containing six types of human actions (walking, jogging, running, boxing, hand waving and hand clapping). |
| AirbusShipDetection                           | `/data3/Ship_detection`              | 29G                | https://www.kaggle.com/c/airbus-ship-detection/data          | Satellite images, ships are varying in angles.               | Kaggle Ship Detection Challenge                              |
| 跨越险阻                                      | `/data3/Kuayuexianzu`                | 2.86G              | None                                                         | Self-labeled dataset.                                        |                                                              |
| GOT-10k                                       | `/data3/GOT`                         | 68G                | [http://got-10k.aitestunion.com](http://got-10k.aitestunion.com/) | Generic object tracking dataset by CASIA                     |                                                              |
| CULane                                        | `/data3/CULane/`                     | 120G               | <http://xingangpan.github.io/projects/CULane.html>           | lane marking detection                                       |                                                              |
| Cloth1M                                       | `/data3/Cloth1M/`                    | TBD                | <https://github.com/Cysu/noisy_label>                        | label noise robust learning                                  | images, ground true labels and noisy labels                  |
| NTU RGB+D                                     | `/data3/NTU_RGB+D/`                  | 437G               | <http://rose1.ntu.edu.sg/Datasets/actionRecognition.asp>     | RGB+D action recognition                                     | including rgb videos and skeletons and depth maps            |
| Taskonomy sample dataset                      | `/data3/Taskonomy-sample-model-1`    | 46.4G              | <https://github.com/alexsax/taskonomy-sample-model-1>        | An official sub-set of the full dataset proposed by the Taskonomy paper. |                                                              |
| Mlt synthetic dataset                         | `/data3/Mlt_synthetic_dataset`       | 500G               | <http://pbrs.cs.princeton.edu/>                              | A synthetic dataset for vision tasks on indoor scenes.       |                                                              |
| Virtual Kitti                                 | `/data3/Virtual_Kitti/`              | 27.2G              | <http://www.europe.naverlabs.com/Research/Computer-Vision/Proxy-Virtual-Worlds> | Virtual KITTI is a **photo-realistic synthetic video dataset** designed to learn and evaluate computer vision models for several **video understanding** tasks: object detection and multi-object tracking, scene-level and instance-level semantic segmentation, optical flow, and depth estimation. |                                                              |
| SBU and ISTD                                  | `/data3/shadow`                      | 10G                | <https://www3.cs.stonybrook.edu/~minhhoai/projects/shadow.html>, <https://github.com/DeepInsight-PCALab/ST-CGAN> | DeShadow/ shadow detection/ shadow removal                   | Including RGB pairs, RGB triplets.                           |
| DIV2K                                         | `/data3/DIV2K`                       | 230G               | <https://data.vision.ee.ethz.ch/cvl/DIV2K/>                  | dataset for single image super resolution tasks              |                                                              |
| Scene Flow                                    | `/data3/SceneFlow`                   | 15.1G              | <https://lmb.informatik.uni-freiburg.de/resources/datasets/SceneFlowDatasets.en.html> | This dataset collection has been used to train convolutional networks in our CVPR 2016 paper [A Large Dataset to Train Convolutional Networks for Disparity, Optical Flow, and Scene Flow Estimation](https://lmb.informatik.uni-freiburg.de/Publications/2016/MIFDB16/). |                                                              |
| PKU-MMD                                       | `/data3/PKUMMD/`                     | 20G                | <http://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html>     | A Large Scale Benchmark for Continuous Multi-Modal Human Action Understanding |                                                              |
| HD1K                                          | `/data3/HD1K/`                       | 8G                 | <http://hci-benchmark.org/>                                  | A dataset for optical flow with more than 1000 images with resolution of 2560*1080 |                                                              |
| CUHK03-NP                                     | `/data3/CUHK03-NP`                   | 2.3G               | <https://github.com/zhunzhong07/person-re-ranking/tree/master/CUHK03-NP> | The new training/testing protocol for CUHK03 (CUHK03-NP), used for person re-identification |                                                              |
| GTOT                                          | `/data3/GTOT`                        | 1.6G               | <http://chenglongli.cn/people/lcl/dataset-code.html>         | Learning Collaborative Sparse Representation for Grayscale-thermal Tracking |                                                              |
| PARD                                          | `/data3/PARD`                        | 29G                | (haven't released yet)                                       | Pedestrian action recognition dataset                        | Including video clips and corresponding heatmap.             |
| PartialREID & Partial-iLIDS                   | `/data3/PartialREID`                 | 6.7M (not a typo!) | <https://github.com/lingxiao-he/Partial-Person-ReID>         | A small dataset for partial person re-identification         |                                                              |






