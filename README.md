
### Ubuntu 서버 명령어
- (*추가)한국 기준으로 서버 시간 설정: sudo ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime
- 현재 경로 상세 출력: ls -al
- 경로 이동: cd 경로
- vim 에디터로 파일 열기: vim bitcoinAutoTrade.py
- vim 에디터 입력: i
- vim 에디터 저장: :wq!
- vim 에디터 나가기: :q
- 패키지 목록 업데이트: sudo apt update
- pip3 설치: sudo apt install python3-pip
- pip3로 pyupbit 설치: pip3 install pyupbit
- 백그라운드 실행: nohup python3 UpbitAutoTradeMA.py > output.log &
-                 nohup python3 DiscordBot.py > output2.log &
-                 nohup python3 UpbitPythonSet.py > output3.log &
- 실행되고 있는지 확인: ps -ef|grep py
- 프로세스 종료(PID는 ps -ef|grep py를 했을때 확인 가능): kill -9 PID
- 파일 삭제 rm hello.txt
- exit()

![PID설명](https://user-images.githubusercontent.com/58558338/115999411-9133ef00-a626-11eb-8aa0-82a1114936e8.PNG)

### Discord
- pip install -U discord.py
- pip install -U python-dotenv

