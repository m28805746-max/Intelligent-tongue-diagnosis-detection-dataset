# Intelligent-tongue-diagnosis-detection-dataset

This dataset is an open-source dataset from the paper "Tongue Images Dataset for Diagnosis Detection Applied in Chinese Medicine", which has been iteratively updated to the third version.

This dataset contains 21 disease categories that can be used for target detection in tongue diagnosis. The categories are jiankangshe (Healthy Tongue), botaishe (Tongue with peeling coating), hongshe (Red tongue), zishe (Purple tongue), pangdashe (Chubby tongue), shoushe (Thin tongue), hongdianshe (Red dot tongue), liewenshe (Cracked tongue), chihenshe (Dentate tongue), baitaishe (White coating tongue), huangtaishe (Yellow coating tongue), heitaishe (Black coating tongue), huataishe (Smooth coating tongue), shenquao (renal depression), shenqutu (renal protrusion), gandanao (Hepatobiliary depression), gandantu (Hepatobiliary protrusion), piweiao (spleen and stomach depression), xinfeiao (heart and lung depression), xinfeitu (heart and lung protrusion), corresponding numerical order is 0-19.

Among them, there are 5594 images in the training set, 572 images in the validation set, and 553 images in the test set. Contains three annotation formats: coco/. txt/. xml, which can be used for experiments using relevant object detection algorithms through configuration files. The dataset is now shared through Baidu Cloud.

The dataset address is: https://pan.baidu.com/s/17f7Etg0LGSNTudkimg1TRg?pwd=2x32
Extraction code: 2x32

And we also provide YOLOv11 code to validate the dataset.
The code format for "YOLO verification code" in this file is YAML file, which is applicable to YOLO series models. Create a new YAML file in the YOLO model, copy the code from the "YOLO verification code" file, and modify the path according to your computer configuration to use it. This document supports models such as YOLOv8/11/12
