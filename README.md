# **NOTE**
We are currently updating this repository. We are preparing training and testing launchers, will be pushed soon. Moreover, we will very soon upload some pre-trained models for different benchmarks.   


# Pedestron
Pedestron is an [MMetection](https://github.com/open-mmlab/mmdetection) based repository that focuses on the advancement of reserach on pedestrian detection.
We provide processed annotations and scripts to process the annotation of different pedestrian detection benchmarks.


### Installation
We refer to the installation and list of dependencies of MMdetection to the official [installation](https://github.com/open-mmlab/mmdetection/blob/master/docs/INSTALL.md) file.
[Clone](https://github.com/open-mmlab/mmdetection) and [install](https://github.com/open-mmlab/mmdetection/blob/master/docs/INSTALL.md) mmdetection following the instructions.

### List of detectors

*Currently we provide configurations for Cascade Mask-RCNN  


### Following datasets are currently supported 
* [Caltech](http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/)
* [CityPersons](https://bitbucket.org/shanshanzhang/citypersons/src/default/)
* [EuroCity Persons](https://eurocity-dataset.tudelft.nl/)
* [CrowdHuman](https://www.crowdhuman.org/)
* [WiderPedestrian Challenge](https://competitions.codalab.org/competitions/20132)


### Preparation
1. Download the datasets from the official sites. Fill in the copyright forms where applicable. 
2. Place them in ./datasets folder in the follwoing heararchy, for example CityPersons should be (./datsets/CityPersons/images/) and (./datsets/CityPersons/annotations/) for images and annotations respectively.
3. Use our pre-processing script to convert the annotations into Pedestron acceptable format.




### Pre-Trained models
1) CityPersons.
2) Caltech.
3) EuroCity Persons


### Please cite the following work
```
@article{irtiza20elephant,
  title={Pedestrian Detection: The Elephant In The Room},
  author={Hasan, Irtiza and Liao, Shengcai and Li, Jinpeng and Akram, Saad Ullah and Ling, Shao},
  journal={arXiv preprint},
  year={2020}}
```
