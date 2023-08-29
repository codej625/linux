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
```
