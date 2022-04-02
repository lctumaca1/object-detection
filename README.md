# Object Detection

YOLO (ver. 3)를 이용한 사물 인식 프로젝트입니다. \
프로젝트 구동하기 전에 아래 사항들을 읽어주세요

### INDEX

* 프로젝트 사용 기술
* 시범 영상


## 프로젝트 사용 기술

| #  | Name. | Version. |
| ------------- |:-------------:|:-------------:|
| 1 | Python | 3.10.4 |
| 2 | YOLO | 3 |

> YOLO는 사물을 인식할 수있도록 해주는 객체 인식 모델이며 YOLO를 구동하기 위해서 Python(v. 3.10.4)를 베이스로 프로젝트를 제작하였습니다.



## 시범 영상

[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://github.com/lctumaca1/object-detection/blob/master/demo-vid.mp4)

> 현재 프로젝트에 반영되고 있는 데이터레이블 파일의 데이터가 적어서 가끔 사물을 다른 사물로 제대로 인식을 못할 때가 있습니다. 이 점 참고하시고 영상을 시청해주시면 감사하겠습니다.


## 마치며

프로젝트에 쓰인 YOLO 파일들이 무거워서 git에 담지못하였는데, 구동하고 싶으시면 ``https://pjreddie.com/darknet/yolo/``에 접속하여 yolov3.cfg, yolov3.weights, yolo.names 파일 받아 주셔서 data 폴더 아래에 넣어주세요. 소스코드에 쓰인 파일명을 수정하여 확장에 맞게 수정하시면 정상 작동할 겁니다. 그리고 웹캠 또는 카메라를 연결하셔야 정상 작동합니다.