# VGG16_YOLO_-V1_implementation

Python = 3.7.13 , Tensorflow = 2.8.2

This model is fire detection made by yolo v1 paper.
but it has very poor performance because of high loss value.
i tried so many times, but it didn't work well

![img_2022-07-12_16-01-39_AdobeExpress](https://user-images.githubusercontent.com/93965016/178448209-0aaf5eda-6f80-4f87-84af-4c5bd03e9e30.gif)

# model

At first, i had built original YOLO_v1 layers in paper by a way of trial. as expected it was not trained well. <br> So i took VGG16 model at keras and then concatenate with yolo's inference layers.<br>
i trained this model for alomost 24 hours, but loss value has stocked at 3 for some hours. and even i trained only one class, sometimes it predict other class( i named it unknown) <br>
I'm still improving this model.

# dataset

i trained with almost 5,900 fire pictures.<br>

https://www.kaggle.com/datasets/phylake1337/fire-dataset <br>
https://www.kaggle.com/datasets/ankan1998/fire-detection-in-yolo-format<br>
https://github.com/spacewalk01/Yolov5-Fire-Detection

# reference

https://arxiv.org/abs/1506.02640 <br>
https://www.maskaravivek.com/post/yolov1/

