# Voxblox++

[![Build Status](https://jenkins.asl.ethz.ch/buildStatus/icon?subject=ubuntu%2016.04%20%2B%20ROS%20kinetic&job=voxblox-plusplus-nightly%2Flabel%3Dubuntu-xenial)](https://jenkins.asl.ethz.ch/job/voxblox-plusplus-nightly/label=ubuntu-xenial/)
[![Build Status](https://jenkins.asl.ethz.ch/buildStatus/icon?subject=ubuntu%2018.04%20%2B%20ROS%20melodic&job=voxblox-plusplus-nightly%2Flabel%3Dubuntu-bionic)](https://jenkins.asl.ethz.ch/job/voxblox-plusplus-nightly/label=ubuntu-bionic/)

**Voxblox++** is a framework for incrementally building volumetric object-centric maps during online scanning with a localized RGB-D camera. Besides accurately describing the geometry of the reconstructed scene, the built maps contain information about the individual object instances observed in the scene. In particular, the proposed framework retrieves the dense shape and pose of recognized semantic objects, as well as of newly discovered, previously unobserved object-like instances.

<img src="https://github.com/ethz-asl/voxblox-plusplus/wiki/images/office_floor_map.png" width=700>


## Getting started
- [Installing on Ubuntu](https://github.com/ethz-asl/voxblox_gsm/wiki/Installation-on-Ubuntu)
- [Basic usage](https://github.com/ethz-asl/voxblox-plusplus/wiki/Basic-usage)

More information can be found in the [wiki pages](https://github.com/ethz-asl/voxblox-plusplus/wiki).

## Citing
If you use **Voxblox++** in your research, please cite the following publication:

- Margarita Grinvald, Fadri Furrer, Tonci Novkovic, Jen Jen Chung, Cesar Cadena, Roland Siegwart, Juan Nieto, **Volumetric Instance-Aware Semantic Mapping and 3D Object Discovery**, _IEEE Robotics and Automation Letters_, 2019. [[PDF](https://arxiv.org/abs/1903.00268)] [[Video](https://www.youtube.com/watch?v=Jvl42VJmYxg)]


```bibtex
@article{grinvald2019volumetric,
  title={{Volumetric Instance-Aware Semantic Mapping and 3D Object Discovery}},
  author={Grinvald, Margarita and Furrer, Fadri and Novkovic, Tonci and Chung, Jen Jen and Cadena, Cesar and Siegwart, Roland and Nieto, Juan},
  journal={IEEE Robotics and Automation Letters},
  year={2019},
  note={Under review}
}
```

If you use **Voxblox++** without the semantic instance-aware segmentation enabled, please additionally cite:
```bibtex
@INPROCEEDINGS{8594391,
  author={F. {Furrer} and T. {Novkovic} and M. {Fehr} and A. {Gawel} and M. {Grinvald} and T. {Sattler} and R. {Siegwart} and J. {Nieto}},
  booktitle={2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  title={{Incremental Object Database: Building 3D Models from Multiple Partial Observations}},
  year={2018},
  pages={6835-6842},
  keywords={feature extraction;image colour analysis;image reconstruction;image representation;image segmentation;mobile agents;object detection;solid modelling;multiple partial observations;incremental object database;indoor scenes;merged models;object model;observed instances;segmented RGB-D images;global segmentation map;3D models;mobile agent;Image segmentation;Databases;Three-dimensional displays;GSM;Shape;Image reconstruction;Solid modeling},
  doi={10.1109/IROS.2018.8594391},
  ISSN={2153-0866},
  month={Oct},}
}
```

## License
The code is available under the [BSD-3-Clause license](https://github.com/ethz-asl/voxblox-plusplus/blob/master/LICENSE).
