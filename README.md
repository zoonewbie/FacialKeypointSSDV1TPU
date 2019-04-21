# FacialKeypointSSDV1TPU
### Training checkpoint of facial keypoints by model of mobilenetv1 SSD on TPU. 
### SETUP
##### batch size: 128
##### number of keypoints: 65 (created by macOS X)
##### Image Source: Open Image V4 (using test image for training. For the training images is too big to download(more than 100G))
##### Image Resize: 512x512

|    GroudTruth Sample I   |    GroudTruth Sample II   |    GroudTruth Sample III   |
:--------------------------:|:-------------------------:|:---------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/groundtruth1.png)  |  ![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/groundtruth2.png)|  ![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/groundtruth3.png)





### CheckPoint 200K
| DetectionBoxes_Precision/mAP/200K |DetectionBoxes_Precision/mAP (large)/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Precision_mAP.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Precision_mAP%20(large).svg?sanitize=true)

|DetectionBoxes_Precision/mAP (medium)/200K|DetectionBoxes_Precision/mAP (small)/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Precision_mAP%20(medium).svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Precision_mAP%20(small).svg?sanitize=true)


|DetectionBoxes_Recall/AR@1/200K|DetectionBoxes_Recall/AR@10/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Recall_AR%401.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Recall_AR%4010.svg?sanitize=true)


|DetectionBoxes_Recall/AR@100/200K|DetectionBoxes_Recall/AR@100 (large)/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Recall_AR%40100.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/DetectionBoxes_Recall_AR%40100%20(large).svg?sanitize=true)


|loss_1/smooth 0.01/200K|loss_1/smooth 0.99/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/loss_1.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/loss_1099.svg?sanitize=true)


|eval I/200K|eval II/200K|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/eval1.png)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/200K/eval4.png)



### CheckPoint 1M
| DetectionBoxes_Precision/mAP/1M |DetectionBoxes_Precision/mAP (large)/1M|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Precision_mAP.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Precision_mAP%20(large).svg?sanitize=true)

|DetectionBoxes_Precision/mAP (medium)/1M|DetectionBoxes_Precision/mAP (small)/1M|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Precision_mAP%20(medium).svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Precision_mAP%20(small).svg?sanitize=true)


|DetectionBoxes_Recall/AR@1/1M|DetectionBoxes_Recall/AR@10/1M|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Recall_AR%401.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Recall_AR%4010.svg?sanitize=true)


|DetectionBoxes_Recall/AR@100/1M|DetectionBoxes_Recall/AR@100 (large)/1M|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Recall_AR%40100.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/DetectionBoxes_Recall_AR%40100%20(large).svg?sanitize=true)


|loss_1/smooth 0.01/1M|loss_1/smooth 0.99/1M|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/loss_1.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/loss_1099.svg?sanitize=true)


|eval I/1M|eval II/1M|
:-------------------------------------:|:-----------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/eval1.png)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/1M/eval4.png)


### (To be continued...)
