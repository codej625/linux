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
mv {옵션} {파일, 디렉토리} {이동 될 위치} -> 파일을 이동시킨다.
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
