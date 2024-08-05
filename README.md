# 인공위성 데이터 이용해 쿨루프 시공 대상 여부 분류
---
## ✔️프로젝트 개요
- 주제 : 인공위성 데이터로 도시 환경 개선
- 학습과목 : 시각지능 딥러닝
- 데이터 출처 : 자체 제작
- 데이터 구분 : image
- 중점사항 : Object Detection 모델에 적합한 데이터 전처리, 모델을 통한 Object 탐지
- 목표 : 쿨루프 시공 대상 여부를 분류하기 위해 인공위성 데이터를 적절하게 전처리, 모델링 진행
---

## ✔️도메인 이해
![image](https://github.com/user-attachments/assets/f84b4d6e-070d-4f74-a025-73e96a1c0f21)
![image](https://github.com/user-attachments/assets/c75cdc7f-86f6-49d3-8f01-82cfc5ef9d39)
![image](https://github.com/user-attachments/assets/0830b2a4-347a-4456-aa57-b4bfc1c329d2)
![image](https://github.com/user-attachments/assets/ecf91113-793a-4fc3-9821-2b30ba010c1c)

---
## ✔️데이터 소개
![image](https://github.com/user-attachments/assets/96a223bb-2a75-4cc6-ac09-83842470e08a)
![image](https://github.com/user-attachments/assets/854df60a-890c-4c4c-b042-32259722a5a7)
![image](https://github.com/user-attachments/assets/0fb08b9f-28f4-41a9-b041-024c6d74231c)

---
## ✔️YOLO 모델 사용하기
1) 폴더 생성

![image](https://github.com/user-attachments/assets/7d2f2d31-930c-4757-b544-ab21aadf2904)

2) 이미지 데이터들과, 라벨 데이터들을 train_test_split, 생성한 폴더로 이동

![image](https://github.com/user-attachments/assets/4cc8b11f-19b1-46d9-85bb-e4670263592c)

3) Yolo모델에 적용할 YAML 생성

![image](https://github.com/user-attachments/assets/8175e2b2-f2da-4c6a-88fd-340e4345ce94)

4) Yolo v8모델 이용(task = detect)

![image](https://github.com/user-attachments/assets/38f34fc8-b9ff-461d-ad03-370b57478a17)

