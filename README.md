# Machine Learning and Computer Vision in Tennis Performance Analysis

This repository contains the implementation of a model training on image dataset and testing on video dataset. Here there is 3 different models. Tracknet model is used for ball detection , Resnet model is used for court-key-point detection , Yolo model is used for player detection.

Here in "train" folder there are 3 notebook files to train or fine tuned models also note that while traing itself we do testing and printed matrix (like precision , accuracy, recall , F1-score). For "eval" folder, there is 1 notebook file which test these models on video dataset.

## Direction for use

### For training :

To train each model , you have to download these datasets :

For ball detection (zip file) : [Dataset](https://drive.google.com/file/d/1mcsZDjBdRJ91dJiZ7eXTCdvLPJ_P9LFt/view?usp=sharing)

For court-key-point detectio : []()

For player detection : []()

Note : here assure that you have changes dataset path into notebook as per your requirement (downloaded dataset path).
As an output you get model (.pth) into "exp/default" folder. 

After training of each model, we get model files (which can be accessible via below links) :

For ball detection : [model_best.pth](https://drive.google.com/file/d/1kNwgy7nAiKn9IJU1qYUfbiuVwnCbPPBM/view?usp=sharing)

For court-key-point detection : []()

For player detection : []()
 

### For testing / eval :

To test models , assure that you have added all model files (.pth) to your "kaggle/input" folder (inshort add models into kaggle notebook) and also add video dataset for which you want to test these models. 

This "eval.ipynb" file just use that model on input video (assure while testing change video dataset path) and provides output with analysis and ball, court-key-point, player detection. You can see output video (which will be available inside "kaggle/working" folder) by downloading it.

After testing on input video , we get output video can be accessible via below links (you can give input video as your choice but make sure video path is correct) :

input video : [input_video.mp4](https://drive.google.com/file/d/1H0FNu3gpKHrlxCWOv1aImdkOaha59Q26/view?usp=sharing)

output video : [output_video.mp4](https://drive.google.com/file/d/13ilxhBdU2KCpxK01PEbdXrpRBgPOVeX5/view?usp=sharing)

