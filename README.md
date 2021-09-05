# TravelStory
## 텍스트 생성 모델을 통한 가상인물 여행기 생성 및 오디오북 서비스   #방구석 여행담

### 프로젝트 구성도
- 블로그, 브런치, 여행서적 등에서 데이터 수집
- 데이터 정제/처리 후 
- 키워드 추출 모델을 통해 키워드 추출
- 여행기 생성 모델 (텍스트 생성 모델)을 통한 텍스트 생성
- 말투 변환 모델을 통한 텍스트 어체 변환
- TTS 엔진을 통한 가상인물여행기 생성
- 웹 애플리케이션 제작

1. 키워드 추출 모델 : 응집도 점수 기반으로 빈도수 높은 키워드 추출
2. 여행기 생성 모델 : KoGPT2 파인튜닝을 통한 여행기 텍스트 생성
3. 말투 변환 모델 : Transformer를 통한 텍스트 어체 학습