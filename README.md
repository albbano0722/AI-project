# AI-project

주제 선정 이유 및 목적 : 정보 보안 관련 주제를 찾다가 스팸 분류하는것에서 부터 시작하면 좋을 것 같아 프로그램 주제로 선정


프로젝트 개요 : 이메일 중 스팸 내용을 가진 이메일과 회사에서든 일상적으로 주고 받는 햄 이메일을 분류하기

![image](https://github.com/albbano0722/AI-project/assets/144203755/8d985040-56a1-4fbe-9245-469e91570860)

가장 기본적인 데이터를 가지고 전처리를 진행하였다. 

![project png1](https://github.com/albbano0722/AI-project/assets/144203755/99dbd7c2-e1b0-479c-8793-51f7b10a4a81)


그 다음 데이터 전처리가 잘 됐는지 확인 한 후

![project png2](https://github.com/albbano0722/AI-project/assets/144203755/ad272635-3482-4290-8729-1c44a6b98596)

모델로 잘 학습시키는 과정이다.

처음은 RNN 모델을 사용하였다.

![image](https://github.com/albbano0722/AI-project/assets/144203755/e75e4a65-1836-48e5-b1d3-fed0e6553c8c)

오버피팅을 해결하고자 다른 모델로 변경하여 프로젝트를 다시 시작하였다.

![image](https://github.com/albbano0722/AI-project/assets/144203755/0357ab38-7108-412a-8b4c-c8a8428c09f8)

모델은 AveragePooling을 사용하였다.




데이터 셋 출처 : https://www.kaggle.com/uciml/sms-spam-collection-dataset


결과 : ![image](https://github.com/albbano0722/AI-project/assets/144203755/d61bae7f-6c84-46ed-b426-7f9debce4999)


중간 평가 이후 개선한 점 :
1. 그래프의 모양이 심각하게 오버피팅이 난 모습
   --> 오버피팅을 해결하고 성능도 높이는 방향으로 진행
![image](https://github.com/albbano0722/AI-project/assets/144203755/3fe4bb5c-446d-4503-a664-2adb4138ac95)
   --> 성능은 줄어들었지만 그래프의 모양이 많이 개선 됨

아쉬웠던 점 : 열심히 한 것 만큼 결과가 좋지 않았고
오버피팅과 성능을 둘 다 확인하며 높이려니 쉽지 않았다.



추후 개선 사항 : accuracy의 값을 더 올리고 그래프의 모양도 조금 더 이쁘게 잡아보고 싶다.


