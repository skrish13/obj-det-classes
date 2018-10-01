# Object Detection Dataset-Classes

- PASCAL VOC - 20 classes - [link](https://github.com/NVIDIA/DIGITS/blob/master/examples/semantic-segmentation/pascal-voc-classes.txt)
- MSCOCO - 80 classes - [link](https://github.com/amikelive/coco-labels/blob/master/coco-labels-2014_2017.txt)
- ImageNet - 200 classes - [link](https://github.com/salman-h-khan/ZSD_Release/blob/master/ImageNet2017/cls_names.txt), [official-link](website.down)
- OpenImages - 545 classes - [link](https://storage.googleapis.com/openimages/web/download.html), [link 2](https://storage.googleapis.com/openimages/2017_11/classes_2017_11.tar.gz), [better link](coming.soon)
- COCO-Stuff - 182 classes - [link](https://github.com/nightrome/cocostuff/blob/master/labels.txt)

### Driving Domain

- KITTI - 8 classes - [link](https://github.com/utiasSTARS/pykitti/blob/3661c441026f84519ded0bbfd7db5592d6e20b41/pykitti/tracking.py#L223)
- CityScapes - 30 classes (8 groups) - [link](https://www.cityscapes-dataset.com/dataset-overview/)
- Udacity - 4 classes - [link](https://github.com/udacity/self-driving-car/tree/master/annotations)


# ETL and Eval codes for Standard Datasets in Python

### [Kitti](http://www.cvlibs.net/datasets/kitti/index.php)

- Dataloader -- [PyKitti](https://github.com/utiasSTARS/pykitti)
  - This package provides a minimal set of tools for working with the KITTI dataset [1] in Python. So far only the raw datasets and odometry benchmark datasets are supported, but we're working on adding support for the others. 
- Dataloader 2 -- [kitti](https://github.com/pratikac/kitti)
  - This is a data loader for KITTI. It publishes the RGB image data, velodyne pointclouds and IMU data at 10 Hz. We use LCM to publish these messages. Also, we publish the tracklet information as a set of tracked objects, their position and classes (both in velodyne coordinate frame and as bounding boxes in each camera) at 10 Hz.
- Useful EDA -- [Kitti-EDA](https://github.com/navoshta/KITTI-Dataset)


### [MOT](https://motchallenge.net/)

- Evaluation -- general multi-object tracking -- [MOTMetrics](https://github.com/cheind/py-motmetrics#Metrics)
