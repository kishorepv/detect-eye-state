# detect-eye-state
A deep learning model to detect state of eye (open/close) in image/video


### About the model
The model was trained on [this][1] dataset of closed and open eyes.

To predict for a video use function `predict_on_video` and to predict for an image use `predict_on_image` in the Jupyter notebook

### Demo
Below is a sample prediction for the ["Coca-Cola | Eyes Closed"][2] video by Coca-Cola:
   
![prediction on video](coca_cola_labelled.gif)

### Downside of the model
The model is trained only to detect open and closed eyes. Hence it gives a closed eye prediction when the image/video frame does not have a face

[1]: http://parnec.nuaa.edu.cn/xtan/data/datasets/dataset_B_Facial_Images.rar
[2]: https://www.youtube.com/watch?v=ZiGWZRDXCLc
