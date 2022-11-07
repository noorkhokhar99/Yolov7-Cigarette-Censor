# Yolov7-cigarette-censor-and-smokers-face-recorder





### Steps to run Code
- Clone the repository.
```
git clone https://github.com/noorkhokhar99/Yolov7-Cigarette-Censor.git
```
- Goto the cloned folder.
```
cd Yolov7-Cigarette-Censor

```
- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Run the code with mentioned command below.

`python detect.py --weights best_cigarette.pt --conf 0.1 --source testing.jpeg --cigarette_blurrate 50 --shape_detector shape_predictor_68_face_landmarks.dat`

 - run for webcam
 python detect.py --weights best_cigarette.pt --conf 0.1 --source 0 --cigarette_blurrate 50 --shape_detector shape_predictor_68_face_landmarks.dat



<p align="center">
<img src="https://github.com/noorkhokhar99/Object-Tracking-Dashboard-YOLOv7/blob/main/Screen%20Shot%201444-04-11%20at%2011.08.33%20PM.png">
</p>






### Inference on a video:
https://www.youtube.com/c/pyresearch
