# 소개
- 사진이나 움짤을 모니터에 스티커처럼 붙여놓을 수 있는 프로그램입니다.

### 추가 작업 예정
- 새창 : [Ctrl + 드래그] 이미지 뷰어를 복제하여 여러개 사진 띄울 수 있게 하기
- 복사 : [Ctrl + C ] 클립보드로 이미지 복사
- 복붙 : [Ctrl + V ] 클립보드의 이미지로 사진 교체


# 사용법 
- 위치조절 : 좌클릭 + 드래그
- 크기조절 : 우클릭 + 드래그
- 사용종료 : 중클릭
- 사진교체 : 드래그 앤 드롭
- 기본사진 : 같은 파일위치 내 image.jpg

# 설명 
Image-Sticker (이하 App)
- App.py : 메모장 등으로 script 확인
- App.pyw: python으로 프로그램 실행(pyw : 콘솔창 숨기고 실행)
- App.exe: 실행파일 (최상단 윈도우. 여러게 띄우면 메모리 누수 나는 것 같음)
- App_light.exe: 실행파일 (일반 윈도우, 원하는 만큼 많이 띄울 수 있음)

# exe로 저장 
- cmd로 App.py까지 이동
- pyinstaller -w -F -i=icon.ico Image-Sticker.py

- F : 하나의 실행파일로 만들기
- w : 콘솔 안뜨게 하기
- n : 만들어지는 실행파일의 제목 정하는 옵션
- i : icon 이미지 넣기

- 참고 : https://wikidocs.net/21952
