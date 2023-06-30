# water_potability
수질음용 여부 분류 머신러닝

## Data
Kaggle 데이터 활용 (https://www.kaggle.com/datasets/adityakadiwal/water-potability)
![image](https://github.com/JHeok9/water_potability/assets/121952545/695d96c2-a08f-4012-928f-bea6c3097b50)

ph : 물의 산성 또는 알칼리성을 나타내는 지표, 0~14 범위, 7은 중성 7보다 낮으면 산성, 높으면 알칼리성
Hardness : 물의 경도, 칼슘과 마그네슘의 양을 나타냄, 경도가 높을시 침전물 형성
Solids : 물 내의 전체 용해성 고형물의 농도, 깨끗한과 탁함을 나타냄
Chloramines : 염소와 암모니아의 결합체, 물의 소독수준을 나타냄
Sulfate : 황산염, 물에 포함된 황의 양을 나타냄
Conductivity : 전도도, 물의 전기 전도 능력을 나타냄
Organic_carbon : 유기탄소, 물에 표함된 유기물의 양을 나타냄
Trihalomethanes : 클로로폼, 브로모디클로로메탄 등과 같은 클로로포름 계열의 화합물
Turbidity : 탁도, 물 내의 불순물로 인해 빛의 투과력이 얼마나 감소하는지를 나타냄
Potability : 물의 음용 가능성 또는 마실 수 있는 상태를 나타내는 지표

### 기술통계 및 상관계수 확인
![image](https://github.com/JHeok9/water_potability/assets/121952545/52544d9f-a133-4842-9367-7fcc11fcc9d2)

![image](https://github.com/JHeok9/water_potability/assets/121952545/c47c0ea1-5ba2-4761-a2a4-02049a8cebf4)

![image](https://github.com/JHeok9/water_potability/assets/121952545/526c299b-2374-4e12-b2a9-d60568be0f05)

![image](https://github.com/JHeok9/water_potability/assets/121952545/8c31cbde-ae4d-495e-bdb8-bfe0af536c10)

### Data 전처리
![image](https://github.com/JHeok9/water_potability/assets/121952545/e571cf84-f5d4-4666-8d5f-04ee9afd558c)


## Modelling
### RandomForest 와 GridSearchCV 활용하여 모델 설계
![image](https://github.com/JHeok9/water_potability/assets/121952545/ff7f24a6-6428-40a6-8ec1-5b5356d1f6d8)

### 훈련 및 테스트
![image](https://github.com/JHeok9/water_potability/assets/121952545/70b44985-ccfc-47ed-83a5-ad31867f9272)
![image](https://github.com/JHeok9/water_potability/assets/121952545/13c8bf9c-b7bc-4eed-85c6-8994bedd7fda)

## 시각화
### 특성중요도
![image](https://github.com/JHeok9/water_potability/assets/121952545/f34f6b7d-e2be-49f4-bad8-e149dbd87626)

### 오차 행렬
![image](https://github.com/JHeok9/water_potability/assets/121952545/0a2965df-cb1d-41c2-a0ce-e1b970481c5c)


