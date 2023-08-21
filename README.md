# K-water 대국민 물 빅데이터 공모전 💧
## 실시간 하수도 손상 유형 탐지 및 자동 분류화: Real-time AI & 드론 자율 주행

<div align="left">
   <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
   <img src="https://img.shields.io/badge/Ultralytics-024DA1?style=flat-square&logo=Ultralytics&logoColor=white"/>
   <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/>
</div>

### 📄Code Description
### Real Time 객체 인식.ipynb
이 코드는 **같은 네트워크에 접속한 기기들끼리 real-time으로 연결**할 수 있는 기능을 부여해줍니다. 저희 프로젝트의 목표는, 실시간으로 하수간 손상 유형을 탐지해주는 것이므로, 저희의 데이터셋으로 **학습된 YOLOv8 모델을 로드**해줍니다. 로드된 모델을 이용해 real-time으로 하수도의 파손부(객체)를 인식할 수 있도록, cv2 라이브러리를 활용해 카메라로 영상을 캡쳐합니다. 노트북을 들고 하수도에 들어가서 영상을 촬영하는 것에는 한계가 있는 관계로, **노트북과 같은 서버로 접속되어있는 스마트폰의 카메라를 이용해 두 기기를 연결**시킵니다.
* **두 기기를 연결시키는 방법**
  1. 스마트폰에 **'iPCamera - High-End Network Cam'** 애플리케이션 설치
  2. 스마트폰과 노트북이 **같은 네트워크(WiFi)에 접속시키기**

두 기기의 연결이 완료되면, 노트북에는 **'YOLOv8 Inference'이라는 팝업창**이 떠, 스마트폰으로 촬영된 영상 속 하수도의 손상 유형이 정확히 탐지하는지 확인하면 됩니다.

-----
