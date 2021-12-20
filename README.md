# KUIAI_Hackathon
- KUIAI(고려대학교) 1회 해커톤 - Anomaly Detection in Inducstrail Environment에서 사용한 코드입니다.

## 주제: Anomaly Detection in Industrial Environment
- 좋은 머신러닝 모델을 만들기 위해선 양질의 데이터가 필요. 하지만 제조 데이터의 특성상 자동으로 방대한 데이터가 쏟아져 나오기에 라벨링이 어려움
- 제조 현장의 경우 비정상 데이터가 극히 적기에 라벨링이 성공적으로 진행되었다 해도 데이터 불균형의 문제가 발생. (오류율 1%미만)
- 딥러닝 기반의 모델은 무거워 학습시간이 오래걸린다. 만약 공장에서 센서위치가 바뀔 경우 재학습이 필요한데, 이 때 빠른학습과 가벼운 모델이어야 서비스가 가능.
- 활용데이터: https://www.kamp-ai.kr/front/dataset/AiData.jsp

## 프로젝트 목표
- 사출공정 및 용해공정 각각에 대하여 정상 데이터셋만 가지고 학습한 후 비정상 데이터 식별 (Anomaly Detection Using Non-supervised learning)
- 오류율 최소화 및 학습 속도 최소화


## 리뷰
- Novelty Detection을 처음 해봐서 모델 성능이 예상보다 낮았습니다.
- 인상깊었던 점은 다른 팀들 중 한 팀에서 마치 랜덤 포레스트처럼 SVM에 앙상블을 혼합하여 사용해서 높은 성능을 보였던 것입니다. 
