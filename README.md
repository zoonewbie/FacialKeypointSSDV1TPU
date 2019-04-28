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





### CheckPoint 700K
| DetectionBoxes_Precision/mAP/700K |DetectionBoxes_Precision/mAP (large)/700K|
:-------------------------------------------------------:|:-----------------------------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Precision_mAP.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Precision_mAP%20(large).svg?sanitize=true)

|DetectionBoxes_Precision/mAP (medium)/700K|DetectionBoxes_Precision/mAP (small)/700K|
:-------------------------------------------------------:|:-----------------------------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Precision_mAP%20(medium).svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Precision_mAP%20(small).svg?sanitize=true)


|DetectionBoxes_Recall/AR@1/700K|DetectionBoxes_Recall/AR@10/700K|
:-------------------------------------------------------:|:-----------------------------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Recall_AR%401.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Recall_AR%4010.svg?sanitize=true)


|DetectionBoxes_Recall/AR@100/700K|DetectionBoxes_Recall/AR@100 (large)/700K|
:-------------------------------------------------------:|:-----------------------------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Recall_AR%40100.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/DetectionBoxes_Recall_AR%40100%20(large).svg?sanitize=true)


|loss_1/smooth 0.01/700K|loss_1/smooth 0.99/700K|
:-------------------------------------------------------:|:-----------------------------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/loss_1.svg?sanitize=true)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/loss_1099.svg?sanitize=true)


|eval I/700K|eval II/700K|
:-------------------------------------------------------:|:-----------------------------------------------:
![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/eval1.png)|![](https://github.com/zoonewbie/FacialKeypointSSDV1TPU/raw/master/700K/eval4.png)


