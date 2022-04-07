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

#### https://dacon.io/competitions/official/235832/overview/description
