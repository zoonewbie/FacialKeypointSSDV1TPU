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
![](https://raw.githubusercontent.com/zoonewbie/FacialKeypointSSDV1TPU/master/140K/DetectionBoxes_Precision_mAP%20(medium).svg?sanitize=true)|![](https://raw.githubusercontent.com/zoonewbie/FacialKeypointSSDV1TPU/master/140K/DetectionBoxes_Precision_mAP%20(small).svg?sanitize=true)


|DetectionBoxes_Recall/AR@1/200K|DetectionBoxes_Recall/AR@10/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/DetectionBoxes_Recall_AR%401.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/DetectionBoxes_Recall_AR%4010.svg?sanitize=true)


|DetectionBoxes_Recall/AR@100/200K|DetectionBoxes_Recall/AR@100 (large)/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/DetectionBoxes_Recall_AR%40100.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/DetectionBoxes_Recall_AR%40100%20(large).svg?sanitize=true)


|loss_1/smooth 0.01/200k|loss_1/smooth 0.99/200k|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/loss_1_smooth001.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/loss_1_smooth99.svg?sanitize=true)


|eval I/200k|eval II/200k|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/eval1Image216446.png)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/eval2Image216446.png)



### CheckPoint 300K
| DetectionBoxes_Precision/mAP/300K |DetectionBoxes_Precision/mAP (large)/300K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Precision_mAP.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Precision_mAP%20(large).svg?sanitize=true)

|DetectionBoxes_Precision/mAP (medium)/300K|DetectionBoxes_Precision/mAP (small)/300K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Precision_mAP%20(medium).svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Precision_mAP%20(small).svg?sanitize=true)


|DetectionBoxes_Recall/AR@1/300K|DetectionBoxes_Recall/AR@10/300K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Recall_AR%401.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Recall_AR%4010.svg?sanitize=true)


|DetectionBoxes_Recall/AR@100/300K|DetectionBoxes_Recall/AR@100 (large)/300K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Recall_AR%40100.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/DetectionBoxes_Recall_AR%40100%20(large).svg?sanitize=true)


|loss_1/smooth 0.01/300K|loss_1/smooth 0.99/300K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/loss_1_smooth001.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/140K/loss_1_smooth99.svg?sanitize=true)


|eval I/300K|eval II/300K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/eval1.png)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/300K/eval2.png)

