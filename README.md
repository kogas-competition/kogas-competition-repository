# kogas-competition-repository
## 규칙 및 일정
- 코드 및 데이터셋 공유 :  구글 드라이브 및 Slack, GitHub (보조)
- 이슈 / 논의 : Slack
- 회의 : 매주 1회 (상황에 따라 유동적으로 변경), 주말 예정, 구글 미팅
- 목표 : 10위권 내
## 방향 
- SOTA 모델(SciNet) 및 기타 모델(Transformer, Tree base model 등) 적용 => 트리 기반 모델(Catboost, xgboost, lgbm, 21.11.20)
- 외부 데이터 활용시 성능 확인(예: 기상 예보 데이터)
- 분류별 수요량 상관관계 분석 등 EDA 적용
- 데이터 : 외부 데이터 활용 유무는 class에 따른 가스 수요량 데이터와의 상관관계 분석 후 결정 예정
- 전처리 : 이상치 제거(iqr * 1.5), log 변환, Timestamp -> cos 형태의 주기 함수로 변환
- 코드 관리 : github organization
- 이후 일정 : Baseline code 구성, baseline을 분기점으로 다양한 방법론 적용 예정
