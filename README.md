![image](https://user-images.githubusercontent.com/81956540/162143650-09dd5f53-11a0-4cda-b33e-1542ae099e19.png)

## [한양대 ERICA] 신용카드 사용자 연체 예측 AI 경진대회
- **주제**  : 신용카드 사용자 데이터를 보고 사용자의 대금 연체 정도를 예측하는 알고리즘 개발
- **유형**  : Classification
- **개발**  : Google Colab, Python, Pandas, Scikit-Learn

## 데이터
- **Data** : 신용카드 사용자들의 개인 신상정보
- **Shape** : (26457, 17)
- **출처**: https://mp.weixin.qq.com/s/upjzuPg5AMIDsGxlpqnoCg

## 학습 모델
- **Train** : 2 LGBMClassifier, 1 XGBClassifier
- **Stacking** : LGBMClassifier

## 평가
- **Metric** : Logloss
- **Public Score** : 0.69909
- **Private Score** : 0.67894 (7th)

<img src="https://user-images.githubusercontent.com/81956540/162151479-406d382a-0451-4851-8ee4-b484b92611d5.jpg" width="70%" height="70%"/>
<img src="https://user-images.githubusercontent.com/81956540/162151479-406d382a-0451-4851-8ee4-b484b92611d5.jpg" width="70%" height="70%"/>
<img src="https://user-images.githubusercontent.com/81956540/162151536-5f78bfd6-65f8-4836-90b7-2d9fd9736b25.jpg" width="70%" height="70%"/>
<img src="https://user-images.githubusercontent.com/81956540/162151563-cc35a91d-a5df-4c21-94a8-2a3f50d21607.jpg" width="70%" height="70%"/>

#### https://dacon.io/competitions/official/235832/overview/description
