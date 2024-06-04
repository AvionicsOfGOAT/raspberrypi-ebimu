# raspberrypi-ebimu

## 센서 
EBIMU_9DOF
![KakaoTalk_Photo_2023-09-23-18-51-39](https://github.com/taeseokyang/arduino-ebimu-sensor/assets/136783693/c5f34991-6b49-4232-9669-e9451e0ed461)
<img width="423" alt="image" src="https://github.com/taeseokyang/arduino-ebimu-sensor/assets/136783693/c77a135e-a92b-49fd-aa26-529e0a934bb2">

## 설명
EBIMU_9DOFV2 센서를 이용한 roll,pitch,yaw 데이터를 Matplot 그래프로 시각화.</br>

## 회로

### case 1 - USB로 시리얼 통신
|Raspberry pi|센서|
|---|---|
|USB PORT|5PIN PORT|

### case 2 - 4, 5번 핀으로 시리얼 통신
|Raspberry pi|센서|
|---|---|
|5V|VIN|
|GND|GND|
|RX(5)|TX|
|TX(4)|RX|

#### 시리얼 핀 설정 방법 
https://m.blog.naver.com/emperonics/222039301356

### Serial Moniter
<img width="204" alt="Screenshot 2023-09-27 at 1 13 55 AM" src="https://github.com/taeseokyang/raspberrypi-ebimu-sensor/assets/136783693/2ba39273-0ef7-4761-8f2c-3d21aafac87f">

### Serial Plotter
<img width="688" alt="Screenshot 2023-09-27 at 1 13 31 AM" src="https://github.com/taeseokyang/raspberrypi-ebimu-sensor/assets/136783693/a0663fc1-d1b0-4893-9f66-81a67862cdbd">



