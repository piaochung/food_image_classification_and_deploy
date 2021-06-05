# food_image_classification_and_deploy
6가지 음식에 대해 분류가 가능한 모델을 만들고 API로 배포하는 프로그램입니다.

## 사용방법

<img src="https://github.com/piaochung/food_image_classification_and_deploy/blob/main/img/url_image.PNG" alt="url_image">

deploy_model.ipynb를 실행하게 되면 마지막 셀에서 위와 같은 결과를 받을 수 있습니다. 2개의 url 중에 bd573152d1d9.ngrok.io을 사용하여 제작한 모델의 결과를 받아볼 수 있습니다. 
<br>
```
http://bd573152d1d9.ngrok.io/predict?url=http://m.thefoodmarket.co.kr/file_data/thefoodmarket/2020/07/17/eb3528ca49858bd182733ef4dfbb14f9.jpg
```
요청은 get 방식을 사용하였고, 이미지 url의 뒷부분을 이름으로 사용하여 저장하기 때문에 .jpg, .png 등과 이미지 포맷으로 종료되어야합니다.
<br>
|테스트 이미지|결과 이미지|
|-|-|
|<img src="https://github.com/piaochung/food_image_classification_and_deploy/blob/main/img/steak_test.jpg" alt="test_image" width="350">|<img src="https://github.com/piaochung/food_image_classification_and_deploy/blob/main/img/test_result.PNG" alt="result_image" width="100%">|
