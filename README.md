# 3th_setting
3주차 개발환경 구축


1. cygwin/home/user 안에 원하는 이름의 폴더를 만들고 (ex. 3th_setting) 해당 폴더 안에 소스코드를 푼다.  

2. cygwin.bat 에서 소스 코드 경로로 이동하고 make를 입력한다. (컴파일이 되면서 소스코드 경로에 BUILD 폴더 생성된다.)
  - cygwin 에서 현재 위치 알기 : pwd
  - cygwin 에서 현재 목록 출력 : ls
  - cygwin 에서 이동 : cd 

3. usb를 연결한다. -> D 드라이브가 뜬다.

4. putty 를 연결한다. ( serial , COM3 => open )

5. cygwin/home/user/ 생성한 폴더 (ex. 3th_setting ) / BUILD / ARQEntity.bin 을 D 드라이브에 복붙한다.

6. putty 화면에 node : 가 보인다.

7. 출발 노드, 도착 노드, 보낼 메시지 순서로 입력하면 소통 준비 완료!
