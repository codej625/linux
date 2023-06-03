# 리눅스 커맨드를 모아보자!

```linux
dpkg -l(exit => q)
apt list(all list)
sudo apt-get update(packages update)
sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 8080(80 port => 8080 redirect)
ssh "service name"
killall -9 java(java service all kill)
date
sudo ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime(date 서울로 변경 option -sf => 강제 덮어쓰기, 일반적으론 -s)
netstat -tnlp(port check)
nohup java -jar my.jar &(background jar실행)
```
