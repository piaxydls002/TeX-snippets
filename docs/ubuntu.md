Install Ubuntu on Windows
=========================
관리자 권한으로 터미널/PowerShell 실행 후
```
wsl--install
```
입력 후 재부팅

<!--
https://docs.microsoft.com/ko-kr/windows/wsl/install

Error Messages
--------------
+ `WSL optional component is not enabled`
  - 제어판-프로그램-windows 기능 켜기/끄기-Linux용 Windows 하위 시스템 체크 후 확인 및 재부팅
+ `Error: 0x800701bc WSL 2?????????https://aka.ms/wsl2kernel??????`
  - https://docs.microsoft.com/ko-kr/windows/wsl/install-manual 의 4번 항목에 있는 Linux 커널 업데이트 패키지를 다운받아 설치
-->