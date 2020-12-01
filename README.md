# Stock-price-prediction

## 학력
- 2020.08 인천대학교 무역학부 졸업
- 2015.03 인천대학교 무역학부 입학

## 수상경력
- 2020년 
- 2018 한국서비스경영학회 추계학술대회 대학생 공모전 최우수상
  - 주제: '포용성장 시대를 위한 신서비스 제안'
  - 내용 : IoT를 통한 교통약자 대중교통 접근 개선
        - 버스 승하차 예약 
        - 보행 시간 조절 시스템
        
- 2018 한국산업단지공단 중단기 뉴비즈니스모델링 프로젝트 경진대회 대상
  - 주제: 중소기업 경쟁력 강화를 위한 신사업 제안
  - 내용: 아마존 FBA를 통한 미국 애견시장 진출
  
- 2017 제2차 SK 청년비상 창업경진대회 우수상
  - 창업아이템: 고령 인구 체온 유지를 위한 온열지팡이
  
## 포트폴리오
### 1. 고양시 공공자전거 스테이션 최적화
- 작업툴 : Python(version:3.8.3), QGIS(version:2.86.321.0), 
- 기간 : 20.08.19 ~ 20.09.11
- 참여인원 : 6명
- 역할 : 데이터 전처리 및 기획
- 데이터셋 : 501.95MB
- 내용 : 고양시 인구 증가와 대중교통 이용현황을 기반으로 고양시 공공 자전거 스테이션 접근성 개선을 위한 위치 재배치
- [Github_bike_station](https://github.com/KIM-CHAEYOUNG/PROJECT_bike_station)

### 2. LSTM기반 코로나 이후 주가예측
- 작업툴 : Python(version:3.7.9), Power BI(version:3.10), Scikit-learn(version: 0.23.2), 
- 기간 : 20.09.23 ~ 20.10.16
- 참여인원 : 3명
- 역할 : 기획 및 예측 모델 개발
- 내용 : 
  - 주식시장 분석
    - 공공데이터를 통해 코로나 이후 국내외 증시 데이터를 수집
    - PowerBI를 통한 국내외 주식 시장 분석
  - 금융기사 토픽모델링
    - 웹크롤링을 통해 금융 기사 및 커뮤니티 게시글수집
    - Kkma 사전 튜닝을 통한 토픽 모델링
  - 전염병 주기 학습을 퉁한 주가 예측 개발
    - 주요 전염병(사스, 신종플루, 메르스) 학습을 통한 코로나 주가 변화 패턴 예측
    - [데이터 튜닝] 주요 경제 위기(IMF, IT버블, 서브프라임 모기지) 당시 주가 데이터 추가 

  - LSTM 기반 주가 예측 모델 개발
    - activation :relu
    - optimizer : adam
    - loss : mse
