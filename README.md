# FacialKeypointSSDV1TPU
### Training checkpoint of facial keypoints by model of mobilenetv1 SSD on TPU. 
### SETUP
##### batch size: 128
##### number of keypoints: 65 (created by macOS X)
##### Image Source: Open Image V4 (using test image for training. For the training images is too big to download(more than 100G))
##### Image Resize: 512x512

|    Input Data Sample I   |    Input Data Sample II   |    Input Data Sample III   |
:--------------------------:|:-------------------------:|:---------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/ImageDatasample1.png)  |  ![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/ImageDatasample2.png)|  ![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/ImageDatasample3.png)


### CheckPoint 140K
| DetectionBoxes_Precision/mAP/200K |DetectionBoxes_Precision/mAP (large)/200K|
:-------------------------------------:|:-----------------------------:
![](https://raw.githubusercontent.com/zoonewbie/FacialKeypointSSDV1TPU/master/140K/DetectionBoxes_Precision_mAP.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/blob/master/140K/DetectionBoxes_Precision_mAP%20(large).svg?sanitize=true)

|DetectionBoxes_Precision/mAP (medium)/200K|DetectionBoxes_Precision/mAP (small)/200K|
:-------------------------------------:|:-----------------------------:
![](https://raw.githubusercontent.com/zoonewbie/FacialKeypointSSDV1TPU/master/140K/DetectionBoxes_Precision_mAP%20(medium).svg
?sanitize=true)|![](https://raw.githubusercontent.com/zoonewbie/FacialKeypointSSDV1TPU/master/140K/DetectionBoxes_Precision_mAP%20(small).svg?sanitize=true)
