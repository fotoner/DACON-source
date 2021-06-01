# 파일별 설명

- NH_train.ipynb: 학습에 사용이 되었던 실제 소스코드가 포함이 되어 있는 노트북입니다.
- NH_test.ipynb: 제출을 할 소스코드가 포함되어 있는 노트북입니다.
- nh-model: train data를 기준으로 학습이된 모델이 저장되어 있는 폴더입니다.
- sample_submission.csv: 데이콘에서 제공 받았던 정답 제출 파일과 같은 파일입니다.
- tokenizer.json: predict를 할 시에 train data를 기준으로 토크나이징을 하기위해 생성한 토크나이저 변수 저장용 json 입니다

NH_test.ipynb 실행시 nh-model, sample_submission.csv, tokenizer.json들은 "/content/" 디렉터리에 포함되어 있다고 가정하여 실행해 주시기 바랍니다.