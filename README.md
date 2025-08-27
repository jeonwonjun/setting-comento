SETTING Database

1. 오류
IntelliJ에서 mongoDB가 아니라 mysql로 연결하려고 하는데 데이터베이스 여결에 실패합니다.

2. 오류 과정
- 우선 처음에는 의존성 및 datasource.xml파일의 문제였어서 해당 코드를 다시 수정했습니다.
- 이후에 #1-4 결과값을 구하기 위해 mysql에 statistic 스키마를 설정하고 sample 데이터베이스를 만들어서 샘플 값들을 입력하였습니다.
- 하지만 localhost:9080/requests에 접속했을 때 아래와 같은 오류가 나와 데이터베이스에 연결되지 않았습니다.

<img width="1938" height="945" alt="1주차 데이터베이스 연결실패" src="https://github.com/user-attachments/assets/d4d48f5d-c8d1-4f99-8e3e-969d2d186046" />
