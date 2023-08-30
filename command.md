# 리눅스 커맨드를 모아보자!

```linux
dpkg -l(exit => q)
apt list(all list)
sudo apt-get update(packages update)
sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 8080(80 port => 8080 redirect)
ssh "service name"
killall -9 java(java service all kill)
date(날짜)
sudo ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime(date 서울로 변경 option -sf => 강제 덮어쓰기, 일반적으론 -s)
netstat -tnlp(port check)
nohup java -jar my.jar &(background jar실행)
rm -rf(rm -> 파일삭제, -r -> 디렉토리와 모든 파일 삭제 -f(강제적으로))
nohup {command} & exit => 백그라운드에서 실행시키고 터미널을 종료한다.

mv {옵션} {파일, 디렉토리} {이동 될 위치}
ex) mv log.txt folder
현재 디렉토리의 log.txt 파일을 folder 디렉토리로 이동

-b : 이동시킬 파일이 이미 존재하면 백업파일을 만든다.
-i : 이동시킬 파일이 이미 존재하면 사용자에게 덮어쓰기 여부를 묻는다.
-f : 이동시킬 파일이 이미 존재하면 강제로 덮어쓰기 한다.
-n : 이동시킬 파일이 이미 존재하면 덮어쓰기 하지 않는다.
-r : 하위 디렉토리까지 모두 이동한다.
-v : 이동 진행 상태를 출력한다.

```
