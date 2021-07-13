# Awesome Scene Change Detections [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
A curated list of datasets, codes, and papers related to scene change detection (SCD).

_NOTE. This repository covers scene change detection based on robot vision (for autonomous driving, drones, mobile robots, etc.).
If you are looking for remote sensing change detection (i.e., finding changes between two satellite images), see [awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection)._

## What is scene change detection?
Scene change detection (SCD) refers to the task of localizing changes and identifying change-categories given two scenes, where the two scenes are captured in the same place with a time difference. 
Often, the scene captured first is called the _reference_ scene (captured at _t0_), and the scene captured later is called the _query_ scene (captured at _t1_). 
A scene can be either an RGB (+D) image, video, or a 3D reconstruction (point cloud). If the scene is an image, SCD is a form of pixel-level prediction because each pixel in the image is classified according to a category. On the other hand, if the scene is point cloud, SCD is a form of point-level prediction because each point in the cloud is classified according to a category.



<p align="center">
  <img src="./fig/github_main_gif.gif">    
    <br>
  <em> 
    An example of SCDs from ChangeSim dataset. Detecting scene changes, models are required to distinghish aimed changes (changed objects) from non-targeted changes, i.e., environmental variations (lowered illumination). Changed objects are marked in color.
  </em>
</p>



## Datasets

### Indoor
- 2021 | **ChangeSim** `IROS`
[![page](https://img.shields.io/badge/page-blue)](https://github.com/SAMMiCA/ChangeSim) 
[![paper](https://img.shields.io/badge/paper-red)](https://arxiv.org/pdf/2103.05368.pdf)

- 2020 | **Langer et al.** `IROS` 
[![page](https://img.shields.io/badge/page-blue)](https://www.acin.tuwien.ac.at/en/vision-for-robotics/software-tools/object-change-detection-dataset-of-indoor-environments/) 
[![paper](https://img.shields.io/badge/paper-red)](http://ras.papercept.net/images/temp/IROS/files/1295.pdf)

- 2019 | **3RScan** `ICCV`
[![page](https://img.shields.io/badge/page-blue)](https://github.com/WaldJohannaU/3RScan) 
[![paper](https://img.shields.io/badge/paper-red)](https://arxiv.org/pdf/1908.06109.pdf)

- 2019 | **Mallscape** `CVPR`
[![github](https://img.shields.io/badge/page-blue)](https://europe.naverlabs.com/blog/making-maps-evergreen/) 
[![paper](https://img.shields.io/badge/paper-red)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Revaud_Did_It_Change_Learning_to_Detect_Point-Of-Interest_Changes_for_Proactive_CVPR_2019_paper.pdf)

- 2017 | **Fehr et al.** `ICRA`
[![github](https://img.shields.io/badge/page-blue)](https://github.com/ethz-asl/change_detection_ds) 
[![paper](https://img.shields.io/badge/paper-red)](https://www.researchgate.net/profile/Marius-Fehr/publication/318697735_TSDF-based_change_detection_for_consistent_long-term_dense_reconstruction_and_dynamic_object_discovery/links/59b52b4b458515a5b4937b68/TSDF-based-change-detection-for-consistent-long-term-dense-reconstruction-and-dynamic-object-discovery.pdf)


### Outdoor

- 2020 | **HD map & Localization Dataset** (only accessible for Korean researchers due to legal issues)  `IROS`
[![page](https://img.shields.io/badge/page-blue)](https://hdmap.naverlabs.com/dataset.html) 
[![paper](https://img.shields.io/badge/paper-red)](http://ras.papercept.net/images/temp/IROS/files/0934.pdf)

- 2018 | **VL-CMU-CD** `Autonomous Robots`
[![page](https://img.shields.io/badge/googledrive-blue)](https://drive.google.com/file/d/0B-IG2NONFdciOWY5QkQ3OUgwejQ/view?resourcekey=0-rEzCjPFmDFjt4UMWamV4Eg) 
[![paper](https://img.shields.io/badge/paper-red)](http://www.robesafe.com/personal/roberto.arroyo/docs/Alcantarilla16rss.pdf)

- 2015 | **PCD** `BMVC` 
[![page](https://img.shields.io/badge/page-blue)](https://kensakurada.github.io/pcd_dataset.html) 
[![paper](https://img.shields.io/badge/paper-red)](http://www.vision.is.tohoku.ac.jp/files/9814/3947/4830/71-Sakurada-BMVC15.pdf)

- 2014 | **CD2014** `CVPRW`
[![page](https://img.shields.io/badge/page-blue)](http://changedetection.net/) 
[![paper](https://img.shields.io/badge/paper-red)](https://ieeexplore.ieee.org/document/6238919?arnumber=6238919)

## Survey Papers
- TBU.

## Papers with code
- 2021 | **DR-TANet: Dynamic Receptive Temporal Attention Network for Street Scene Change Detection** `IV`
[![page](https://img.shields.io/badge/page-blue)](https://github.com/Herrccc/DR-TANet) 
[![paper](https://img.shields.io/badge/paper-red)](https://arxiv.org/abs/2103.00879)
- 2020 | **Weakly Supervised Silhouette-based Semantic Scene Change Detection** `ICRA`
[![page](https://img.shields.io/badge/page-blue)](https://github.com/kensakurada/sscdnet) 
[![paper](https://img.shields.io/badge/paper-red)](https://arxiv.org/abs/1811.11985)
- 2018 | **Learning to measure change: Fully convolutional siamese metric networks for scene change detection** `arXiv`
[![page](https://img.shields.io/badge/page-blue)](https://github.com/gmayday1997/SceneChangeDet) 
[![paper](https://img.shields.io/badge/paper-red)](https://arxiv.org/pdf/1810.09111.pdf)
- 2018 | **ChangeNet: A Deep Learning Architecture for Visual Change Detection** `ECCVW`
[![page](https://img.shields.io/badge/page-blue)](https://github.com/leonardoaraujosantos/ChangeNet) 
[![paper](https://img.shields.io/badge/paper-red)](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11130/Varghese_ChangeNet_A_Deep_Learning_Architecture_for_Visual_Change_Detection_ECCVW_2018_paper.pdf)
## Papers without code
- 2021 | **Scene change detection: semantic and depth information** `MULTIMED TOOLS APPL`
[![paper](https://img.shields.io/badge/paper-red)](https://link.springer.com/article/10.1007/s11042-021-10793-4)
- 2021 | **3DCD: Scene Independent End-to-End Spatiotemporal Feature Learning Framework for Change Detection in Unseen Videos** `T-IP`
[![paper](https://img.shields.io/badge/paper-red)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9263106)
- 2020 | **Self-supervised simultaneous alignment and change detection** `IROS`
[![paper](https://img.shields.io/badge/paper-red)](http://ras.papercept.net/images/temp/IROS/files/1888.pdf)
- 2020 | **Better Together: Online Probabilistic Clique Change Detection in 3D Landmark-Based Maps** `IROS`
[![paper](https://img.shields.io/badge/paper-red)](http://ras.papercept.net/images/temp/IROS/files/2170.pdf)
- 2020 | **Hierarchical Paired Channel Fusion Network for Street Scene Change Detection** `T-IP`
[![paper](https://img.shields.io/badge/paper-red)](https://arxiv.org/abs/2010.09925)
- 2020 | **Mask-CDNet: A mask based pixel change detection networ** `Neurocomputing`
[![paper](https://img.shields.io/badge/paper-red)](https://www.sciencedirect.com/science/article/pii/S0925231219313979)
- 2020 | **Scene independency matters: An empirical study of scene dependent and scene independent evaluation for CNN-based change detection** `T-ITS`
[![paper](https://img.shields.io/badge/paper-red)](https://ieeexplore.ieee.org/abstract/document/9238403)
- 2020 | **CDNet++: Improved Change Detection with Deep Neural Network Feature Correlation** `IJCNN`
[![paper](https://img.shields.io/badge/paper-red)](https://ieeexplore.ieee.org/abstract/document/9207306)
- 2019 | **Histogram Shape-Based Scene-Change Detection Algorithm** `Access`
[![paper](https://img.shields.io/badge/paper-red)](https://ieeexplore.ieee.org/abstract/document/8653285)

## Contact & Feedback
If you have any suggestions about papers, feel free to contact me :)
- [e-mail](mailto:jmpark@rit.kaist.ac.kr)
- [pull request](https://github.com/chickenbestlover/awesome-scene-change-detections/pulls)

