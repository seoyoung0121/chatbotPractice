# chatbotPractice

colab으로 챗봇 실행하는 방법: 

1. 구글 드라이브에 폴더를 생성하고 ChatbotData.csv와 bar.csv를 넣는다.


2. 다음 경로명을 코드의 빈칸에 넣어준다.

  /content/drive/MyDrive/생성한 폴더이름/ChatbotData.csv
  /content/drive/MyDrive/생성한 폴더이름/bar.csv

  #기존 챗봇 데이터셋 불러오기
  data = pd.read_csv('____________')

  #칵테일 추천을 위한 데이터셋 불러오기
  bar_data=pd.read_csv('____________')

  예시

<img width="613" alt="스크린샷 2022-12-08 오후 5 19 52" src="https://user-images.githubusercontent.com/88281319/206395329-9730f043-d641-413c-99d0-371fe88cc32e.png">


3. 런타임-런타임 유형 변경으로 들어가 하드웨어 가속기를 GPU로 설정해준다.

  <img width="379" alt="스크린샷 2022-12-08 오후 5 21 06" src="https://user-images.githubusercontent.com/88281319/206395534-672a1785-b219-45c9-b8d0-6c8289a3f6fe.png">


4. 실행 버튼을 눌러 실행해준다.
