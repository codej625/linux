# 리눅스 커맨드를 모아보자!

<br/>

```
sudo apt-get update -> 패키지 업데이트
```

```
killall -9 java -> 자바서비스 전체 종료
```

```
date -> 날짜 확인
```

```
nohup {command} {filename} & exit -> 백그라운드에서 파일을 실행시키고 터미널을 종료한다.
ex) nohup java -jar service.jar & exit  
```

```
mv {옵션(제외가능)} {파일, 디렉토리} {이동 될 위치} -> 파일을 이동시킨다.
ex) mv file.txt /Documents/folder

* option
-b : 이동시킬 파일이 이미 존재하면 백업파일을 만든다.
-i : 이동시킬 파일이 이미 존재하면 사용자에게 덮어쓰기 여부를 묻는다.
-f : 이동시킬 파일이 이미 존재하면 강제로 덮어쓰기 한다.
-n : 이동시킬 파일이 이미 존재하면 덮어쓰기 하지 않는다.
-r : 하위 디렉토리까지 모두 이동한다.
-v : 이동 진행 상태를 출력한다.
```

```
rm {filename} -> 파일을 삭제한다.
ex) rm file.txt

* option
rm -r {foldername} -> 폴더를 삭제 할때
rm -f {filename} -> 폴더, 파일을 확인하지 않고 삭제한다.
rm file1.txt file2.txt file3.txt -> 공백을 사용하면 여러 파일을 한번에 삭제한다.
rm -rf {filename} -> file, folder를 무조건 삭제한다.
```

```
iptables -A PREROUTING -t nat -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 8080 -> 80포트 접속시 8080포트로 리다이렉트 설정 추가
iptables -D PREROUTING -t nat -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 8080 -> 80포트 접속시 8080포트로 리다이렉트 설정 삭제
iptables -t nat -L -> 확인
```

```
chmod +x {filename} -> 파일 권한 변경 커맨드(chmod) + +x(실행 권한 추가) + {filename}
```

```
codesign --force --deep --sign - /Applications/SpringToolSuite4.app/Contents/MacOS/SpringToolSuite4 -> STS4 인증이 깨졌을 때 설치되어 있는 경로를 수정하여 사용
```
