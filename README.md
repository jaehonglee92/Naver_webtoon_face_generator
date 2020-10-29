# 네이버웹툰 캐릭터 얼굴 생성하기 (Editing)

## 데이터 확보

* 웹툰 캐릭터 얼굴 데이터 확보를 위하여 우선적으로 네이버웹툰에서 크롤링할 웹툰 선정 (예시. 유미의 세포들)

![yumisepo](https://user-images.githubusercontent.com/22866802/97528285-af5ec080-19f0-11eb-9717-327cc1fb3c39.png)

* 웹툰 이미지 크롤링
  * [allieus](https://gist.github.com/allieus/13c1a80ef5648c2b9b112e1c58f9727b)님이 만들어주신 웹툰 이미지 크롤러 사용
  
  
* 얼굴 인식 및 추출
  * [ageitgey](https://github.com/ageitgey/face_recognition)의 face_recognition 참조
  * 웹툰 캐릭터 얼굴 인식 후 추 샘플
    
![yumisepo_sample](https://user-images.githubusercontent.com/22866802/97533007-cdc9b980-19fa-11eb-86ce-439f24c4471e.png)


## Training

### pytorch version DCGAN 사용
#### Training process
![yumisepo_training](https://user-images.githubusercontent.com/22866802/97538280-7bd96180-1a03-11eb-8115-b8173f6c2c99.gif)

#### Training loss

![yumisepo_loss](https://user-images.githubusercontent.com/22866802/97539232-f5258400-1a04-11eb-9cf2-a65a03851f29.png)
