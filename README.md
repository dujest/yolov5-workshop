# yolov5-workshop

<p>
<img src="https://github.com/dujest/yolov5-workshop/blob/main/results/port.gif" width="45%" />
<img src="https://github.com/dujest/yolov5-workshop/blob/main/results/windturbine.gif" width="45%" />
</p>

The YOLOv5 workshop comprises several Jupiter Notebook files with different applications of [YOLOv5](https://github.com/ultralytics/yolov5), and each has a link to Google Colab which provides computing on GPU ([NVIDIA Tesla T4 16GB for AI inference](https://www.nvidia.com/en-us/data-center/tesla-t4/)).

To run successfuly all the files, use Google Colab mounted on your Google Drive or otherwise just remove the part `drive/MyDrive/colab/` from the all available paths.

The available files are:

`YOLOv5_Custom_Training`, based on the [YOLOv5 Custom Training Notebook](https://colab.research.google.com/github/roboflow-ai/yolov5-custom-training-tutorial/blob/main/yolov5-custom-training.ipynb), examines the performance of the SGD, Adam and AadamW optimization algorithms, provided by YOLOv5, and impact of different batch sizes on the metrics.

`Deep_CNN_Image_Classifier` applies a custom CNN for classification of corrosion affected objects.

`YOLOv5_Hyperparameter_Evolution` performes an evolution of the YOLOv5 hyperparameters with GA (genetic algorithm).

<p>
<img src="https://github.com/dujest/yolov5-workshop/blob/main/results/cruise_ship.gif" width="45%" />
<img src="https://github.com/dujest/yolov5-workshop/blob/main/results/portofsingapore.gif" width="45%" />
</p>

`Yolov5_DeepSort` deploys the [StrongSORT algorithm](https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet) for multi object tracking, based on [DeepSORT](https://arxiv.org/abs/1703.07402) and [Kalman filtering](https://www.kalmanfilter.net/default.aspx).

<p>
<img src="https://drive.google.com/uc?id=1QqcmxwlpTGn1TSTeNlWZX8HJjJRao6Mc" width="70%" >
</p>
