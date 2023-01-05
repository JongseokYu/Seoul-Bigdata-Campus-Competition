# Seoul-Bigdata-Campus-Competition
# 서울시 빅데이터캠퍼스 공모전 최우수상🏆

탄소중립 선도를 위한 서울시 종합에너지스테이션(TES) 우선 입지 선정
: Optimal Location Selection of Total Energy Station(TES) for Leading Carbon Neutrality in Seoul

1. Preprocessing
- 개괄 : 2021년 데이터를 기준으로 데이터 전처리 진행
- 사용데이터 
: 2021년 기준 행정동별 생활인구, 거주인구, 생활금융통계(KCB), 전력사용 데이터
: 2021년 기준 전기차 충전소 입지 데이터, 및 전기차 소유주 데이터
: 2021년 기준 주유소 입지 데이터

2. EDA
- 행정동별 인구 특성 및 전기차, 주유소 입지 관련 EDA 및 시각화

3. Clustering
- 전기사용량과 생활인구를 기준으로 한 클러스터링 진행으로 종합에너지스테이션이 우선적으로 필요한 행정동 타켓 클러스터 선정 및 세부 분석 진행

4. Feature Seletion
- 머신러닝 모델을 사용하여 전기차 충전소 개수에 가장 큰 영향을 미치는 요소를 파악하였고, 이러한 요소들을 이후 입지선정에 중요한 판단기준으로 반영

5. Location Selection
- 행정동별 한 명의 생활인구 당 사용할 수 있는 충전소 개수, 전기차 개수, 충전소 인프라(충전소 주변의 상권 활성화 정도 파악)를 판단준거로 삼아 최종적인 우선입지 행정동을 도출
- 추가적으로 주유소 주변 상권 활성화 정도를 기준으로 삼아 최종적인 세부 위치 결정

6. (추가) 최종 본선 프리젠테이션 자료 첨부
