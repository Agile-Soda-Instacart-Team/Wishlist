[![image](https://user-images.githubusercontent.com/95989232/166428931-1ee9948f-cc1c-42a2-b0a9-47dae9b8b90d.png)](https://www.kaggle.com/competitions/instacart-market-basket-analysis/overview)

## 🛒위시리스트 팀 소개
|이름|역할|담당 업무|
|---|:---:|
|박산들|팀장|데이처 전처리, EDA, 모델링|
|김아네스|팀원||
|장병용|팀원|일정관리, 업무분장, EDA|
|정경환|팀원|모델링|

<br/>

## 일정표
|단계|내용|M1|M2|H1|H2|H3|H4|H5|H6|  
|:---:|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|  
|1|에자일 소다 OT|☑️|☑️|◾|◾|◾|◾|◾|◾|  
|2|주제 및 계획 설정|◾|☑️|☑️|◾|◾|◾|◾|◾|  
|3|데이터 구성 및 EDA|◾|◾|☑️|☑️|☑️|☑️|◾|◾|   
|4|모델 개발|◾|◾|◾|◾|◾|☑️|☑️|☑️|   
|5|최종 보고|◾|◾|◾|◾|◾|◾|◾|☑️|

<br/>

## 프로젝트 소개

Instacart는 미국과 캐나다에서 웹과 앱을 통해 식료품 배달과 픽업 서비스를 운영하는 미국 회사입니다. instacart에서 제공한 익명화 된 고객의 구매내역 데이터를 기반으로 다시 주문할 제품을 예측하는 모델을 개발합니다.

<br/>

## 목표
### 정량적 목표
- 캐글 리더보드 점수 0.40311 이상 달성
### 정성적 목표
- 제공된 데이터 분석
- 더 나은 교차 판매 및 상향 판매를 위한 제품 간의 연관성 찾기
- 타겟 마케팅을 위한 고객 세분화 수행 및 고객 행동 예측
- 고객 주문에 대한 익명 데이터를 사용하여 이전에 구매한 제품이 사용자의 다음 주문목록에 포함될지를 예측하는 최적의 모델을 개발

<br/>

## [데이터 설명](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data)
***

- aisles: 제품의 소 분류가 총 134개 나열되어 있습니다.
- Departments: 이 파일에는 제품의 대 분류가 총 21개 나열되어 있습니다.
- orders: 이 파일에는 총 206209명의 사용자가 주문한 총 3421083개의 주문이 있습니다.
    - Order_number: 고객별 주문 횟수는 0에서 100까지입니다.
    - Order_dow(day of week): 0, 1, 2, 3, 4, 5, 6이 각각 토일월화수목금으로 매핑할 수 있습니다. 토요일과 일요일 주문이 다수를 차지합니다.
    - Order_hour_of_day: 대부분의 주문은 낮 시간에 이루어집니다.
    - Days_since_prior_order: 이전 주문 이후 경과 일수를 보면 7, 14, 21, 30이 많으므로 일주일에 한 번 주문하는 추이를 보입니다.
- order_products_prior: 이 파일은 주문한 제품과 장바구니에 추가된 순서에 대한 정보를 제공하며 제품이 재 주문 되었는지 여부도 알려줍니다. 이 파일에는 총 49677개의 제품이 주문된 총 3214874개의 주문 정보가 있습니다.
- order_products_train: order_products_prior파일과 마찬가지로 주문한 제품과 장바구니에 추가된 순서에 대한 정보와 제품이 재 주문 되었는지 여부를 알려줍니다. 이 파일에는 총 39123개의 제품이 주문된 총 131209개의 주문 정보가 있습니다.
- Products: 이 파일에는 총 49688개의 제품 목록과 해당 카테고리 및 부서가 포함되어 있습니다. 다른 카테고리와 다른 부서에 있는 제품의 수는 다릅니다.

<br/>

## 탐색적 데이터 분석

데이터 설명 단계에서 확인한 특징들을 토대로 EDA와 가설검정을 진행했습니다.

![image](https://user-images.githubusercontent.com/69462995/172520774-1098403a-a62e-4c96-a70a-0430e17db306.png)

### 가설1. 요일과 시간에 따른 고객 구매패턴이 있는지 확인
* 요일별 트랜드 랭킹을 확인하여 요일과 제품 판매량의 변화 체크
![image](https://user-images.githubusercontent.com/69462995/172520920-fb29b811-db73-47b9-8024-743597b2183d.png)

* 시간별 트랜드 랭킹을 확인하여 시간과 제품 판매량의 변화 체크
![image](https://user-images.githubusercontent.com/69462995/172520935-662b96b5-f025-4b58-af81-e76ce3c371f5.png)

* 특정 요일 & 시간에만 주문을 진행하는 유저가 있는지 확인
![image](https://user-images.githubusercontent.com/69462995/172521868-87332421-179a-4796-877c-1afe94e83e0a.png)


### 가설2. Order에서 구매패턴 확인
* order_number가 높은 주문일수록 재구매율의 변화량 체크
![image](https://user-images.githubusercontent.com/69462995/172521479-81b18df9-51c4-4648-9e18-1db471019eda.png)

* order_number가 40이 넘는 회원들의 요일-시간 패턴 확인
![image](https://user-images.githubusercontent.com/69462995/172522206-6e73b080-dc18-4b98-bde7-90e5de5396aa.png)

* days_since_prior_order와 재주문율의 변화량 체크
* ![image](https://user-images.githubusercontent.com/69462995/172522432-7e5406d5-af61-454f-beea-c124fc9a5b63.png)

### 가설3. 고객별 구매패턴 확인하기
* 유저마다 선호하는 제품이 있는지 확인
![image](https://user-images.githubusercontent.com/69462995/172522530-f435c08c-6e98-4bc6-867b-05f8cc61c0f6.png)

* 같은 제품을 선호하는 유저들은 비슷한 구매패턴을 보이는지 확인
![image](https://user-images.githubusercontent.com/69462995/172523104-b4677cb6-0a1d-4cf2-a897-2086f9dc2222.png)

### 가설4. 제품별 구매패턴 확인하기
* 고객들이 선호하는 제품 키워드가 있는지 워드 클라우드로 확인
![image](https://user-images.githubusercontent.com/69462995/172523495-d60698a1-1fa0-4766-bbfd-42f340ac9d4c.png)

* 선호 키워드들의 재주문율 확인
![image](https://user-images.githubusercontent.com/69462995/172523553-ca9d92be-e172-4bc0-be44-f3f6f7f4ef91.png)



<br/>

## ML 모델

대용량 데이터를 처리하고 병렬화할 수 있으며 변수 중요도를 제공하는 XGBoost모델을 선정하였습니다. 성능지표는 F1 score를 사용합니다.
