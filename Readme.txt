a업종전처리.ipynb:

DATA_PATH = 기존 train 데이터 경로 
현재 디렉토리
저장 경로 =현재디렉토리/"a_business_time1_edit.csv"
저장 경로 =현재디렉토리/"a_business_time2_edit.csv"
저장 경로 =현재디렉토리/"a_business_time3_edit.csv"
저장 경로 =현재디렉토리/"a_business_time4_edit.csv"
저장 경로 =현재디렉토리/"a_business_time5_edit.csv"

b업종전처리.ipynb:

DATA_PATH = 기존 train 데이터 경로 
현재 디렉토리
저장 경로 =현재디렉토리/"b_business_time1_edit.csv"
저장 경로 =현재디렉토리/"b_business_time2_edit.csv"
저장 경로 =현재디렉토리/"b_business_time3_edit.csv"
저장 경로 =현재디렉토리/"b_business_time4_edit.csv"
저장 경로 =현재디렉토리/"b_business_time5_edit.csv"

c업종전처리.ipynb:

DATA_PATH = 기존 train 데이터 경로 
현재 디렉토리
저장 경로 =현재디렉토리/"c_business_time1_edit.csv"
저장 경로 =현재디렉토리/"c_business_time2_edit.csv"
저장 경로 =현재디렉토리/"c_business_time3_edit.csv"
저장 경로 =현재디렉토리/"c_business_time4_edit.csv"
저장 경로 =현재디렉토리/"c_business_time5_edit.csv"

d업종전처리.ipynb:

DATA_PATH = 기존 train 데이터 경로 
현재 디렉토리
저장 경로 ="d_business_time1_edit.csv"
저장 경로 ="d_business_time2_edit.csv"
저장 경로 ="d_business_time3_edit.csv"
저장 경로 ="d_business_time4_edit.csv"
저장 경로 ="d_business_time5_edit.csv"

윗 부분의 코드에서 종목 data를 시간대로 나누고 튀는 부분을 변경

running.ipynb:

위의 전처리한 데이터로
LSTM모델 생성 및 학습

20개의 모델 사용 (a종목 5개, b종목 5개, c종목 5개, d종목 5개)

prediction.ipynb:

모델을 통해 예측

MODEL_PATH = 현재디렉토리/ 'modela_1.pth' ,'modela_2.pth' ,'modela_3.pth','modela_4.pth', 'modela_5.pth',
                           'modelb_1.pth' ,'modelb_2.pth' ,'modelb_3.pth','modelb_4.pth', 'modelb_5.pth'
                           'modelc_1.pth' ,'modelc_2.pth' ,'modelc_3.pth','modelc_4.pth', 'modelc_5.pth'
                           'modeld_1.pth' ,'modeld_2.pth' ,'modeld_3.pth','modeld_4.pth', 'modeld_5.pth'


결과 저장 경로 =현재디렉토리/'submission_a.csv','submission_b.csv','submission_c.csv','submission_d.csv'


