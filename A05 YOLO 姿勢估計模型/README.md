## YOLO 姿勢估計模型 即時估計高爾夫球員的擊球姿勢

## 訓練一個高爾夫姿勢估計模型

1.基本模型 (YOLO Pose Base Model)

在 COCO8-pose 資料集上訓練 YOLO26-pose 模型。 COCO8-pose 資料集是一個小型樣本資料集，非常適合用於測試和調試姿態估計模型。

2. 標註高爾夫姿勢估計模型

OLO姿態資料集格式的詳細資訊請參閱資料集指南。若要將現有資料集從其他格式（例如COCO等）轉換為YOLO格式，請使用Ultralytics的JSON2YOLO工具。對於自訂姿態估計任務，您還可以探索一些專用資料集，例如用於動物姿態估計的Tiger-Pose資料集、用於手部追蹤的Hand Keypoints資料集以及用於犬類姿態分析的Dog-Pose資料集。



YOLO Golfer Pose Estimation Model。
![YOLO Golfer Pose Estimation Model。](https://github.com/TRexTW/GolfPhys/blob/main/figure/YOLO-Golfer-Pose-Estimation-Golfer-Person.gif)

YOLO Golfer Pose Estimation Model with OBS 3 cameras 。
![YOLO Golfer Pose Estimation Model  with OBS 3 cameras 。](https://github.com/TRexTW/GolfPhys/blob/main/figure/YOLO-Pose-Estimation-Golf-Person-3camera.gif)


YOLO Pose Estimation Model - Person 。
![YOLO Pose Estimation Model - Person](https://github.com/TRexTW/GolfPhys/blob/main/figure/YOLO-Pose-Estimation-Golf-2-Person-CCU.PNG)


YOLO Pose Estimation Model - Person with OBS 3 cameras 。
![YOLO Pose Estimation Model - Personwith OBS 3 cameras 。](https://github.com/TRexTW/GolfPhys/blob/main/figure/YOLO-Pose-Estimation-Golf-3-Person-3-Camera-CCU.PNG)

YOLO Golfer Pose Estimation Model - YOLO-Golfer-Pose-Estimation-Model-Home-simple-golf-driving-range
![YOLO Golfer Pose Estimation Model](https://github.com/TRexTW/GolfPhys/blob/main/figure/YOLO-Golfer-Pose-Estimation-Model-Home-simple-golf-driving-range.gif)

