# LSTM을 활용한 비트코인 시세 예측하기

### 🔗 Link

**Source**

[소스코드와 데이터를 보시려면 여기를 클릭해주세요](https://github.com/yujeong0121/LSTM/tree/master/code)

**PPT**

[발표자료를 보시려면 여기를 클릭해주세요](https://github.com/yujeong0121/LSTM/blob/main/%EC%82%BC%EC%82%BC%EC%98%A4%EC%98%A4_LSTM%EC%9D%84%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%EB%B9%84%ED%8A%B8%EC%BD%94%EC%9D%B8%20%EC%8B%9C%EC%84%B8%20%EC%98%88%EC%B8%A1.pdf)

## ✍️ 요약

![요약](https://user-images.githubusercontent.com/94778140/151474602-bbda7dc0-fa46-40e3-9df3-695f1b3f85ed.png)


- Work Team & Member
    - 팀명: 삼삼오오
    - 팀원: 박유정, 김호준, 김찬희, 정새하, 정한슬
    
- Work Schedule
    - 1월 3일: 주제 선정 및 기획
    - 1월 4일: 데이터 수집 및 전처리/모델 구성
    - 1월 5일 ~ 6일: 모델 개선, 예측, 평가
    - 1월 7일: 결과 정리 및 발표
    
- Skills
    - Python
    - Colab
    - Slack

- Dataset
    - train: 업비트 사이트에서 API로 수집한 2021년 12월(한달 간)의 분당 종가
    - test: 2022년 1월 1일~ 1월 3일 분당 종가
    - 실시간 예측 데이터: 직전 30분간의 데이터로 1분 뒤의 시세 예측
    
  ![data](https://user-images.githubusercontent.com/94778140/151474667-eb808388-b853-47ff-931a-19f4e0338ee8.PNG)

    

## 🛠 사용 라이브러리

- `pyubit 0.2.22`
- `requests 2.23.0`
- `pandas 1.1.5`
- `tensorflow 2.7.0`
- `numpy 1.19.5`
- `matplotlib 3.5.1`
- `seaborn 0.11.2`

## 🖥 역할

- 모델 평가 및 결과 정리

## ✨ 결과

![결과 시각화](https://user-images.githubusercontent.com/94778140/151474877-f4e5d354-2e26-4605-8493-0b14086848c8.png)


직전  30분간의 누적 데이터로 1분 후 데이터 예측 (2022년 1월 4일 13:30분 기준)

![시세 예측 코드](https://user-images.githubusercontent.com/94778140/151474857-1c1a4176-3335-4563-9c6b-52b144723825.png)

![current](https://user-images.githubusercontent.com/94778140/151474746-5499eb6f-d274-4e8f-a7fb-3fbded5d281b.jpg)


## 💡 성장한 부분

- 머신러닝에 대한 이론을 배우고 간단한 예제들만 실습해보다 팀원들과 5일 정도의 단기 프로젝트를 해보았습니다. 첫 머신러닝 프로젝트였으며 팀원들과 주제 선정을 같이하고 그에 맞는 알맞은 모델을 주도적으로 찾는 첫 경험을 했습니다.  생소한 가상화폐의 용어들을 접해보니 원하는 데이터를 확실히 정하고 사전 지식과 각 변수에 맞는 특징을 먼저 파악해야 한다는 것을 깨달았습니다.
