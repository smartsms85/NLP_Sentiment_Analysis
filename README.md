# ELECTRA 모델 기반 영어 및 한국어 감정 분석기 개발
/NSMC/NLP_NSMC_KoELECTRA.ipynb

## ① 한국어 감정 분석기 개발
- 사용 모델 : KoELECTRA Base v3
- 개발 환경 : <br> 
  Google Corab (GPU 사용)<br>
  Base모델 기준 1Epoch 당 약 10~15분 소요<br>
- 데이터 출처 : https://github.com/e9t/nsmc.git
- 실행 방법 : 모든 셀 실행 -> 데이터 전처리, 모델 학습 및 검증, 테스트 결과 확인 및 CSV 파일 Fileout 가능
- 모델 및 데이터는 구글드라이브 기준으로 작성되었습니다.

## ② 영어 감정 분석기 개발
- 사용 모델 : ELECTRA Base
- 개발 환경 : <br> 
  Google Corab (GPU 사용)<br>
  Base모델 기준 1Epoch 당 약 1~2분 소요<br>
- 데이터 출처 : http://doraemon.iis.sinica.edu.tw/emotionlines/index.html (/FRIENDS/json 폴더 확인)
- 실행 방법 : 모든 셀 실행 -> 데이터 전처리, 모델 학습 및 검증, 테스트 결과 확인 및 CSV 파일 Fileout 가능
- 모델 및 데이터는 구글드라이브 기준으로 작성되었습니다. 

## (Ko)ELECTRA 외 추가 연구 내용

- NSMC, FRIENDS 폴더 내 파일 확인

### 소스코드 및 주요 References

- https://github.com/monologg/KoELECTRA
- https://huggingface.co/transformers/training.html
- http://wikidocs.net/book/2155
- https://github.com/jiwonny/nlp_emotion_classification
- https://colab.research.google.com/drive/1JZ-pXlmgRIYHm8yPLYY68Q28l9OYAL6H?usp=sharing
- 세부 내용은 각 모델 파일 별로 기술해두었으니 참조바랍니다.
