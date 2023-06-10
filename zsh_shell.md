# linux에 zsh shell을 설치해보자!

1. 먼저 시스템 패키지 목록을 최신 상태로 업데이트한다.
```
sudo apt update
```

2. zsh 설치
```
sudo apt install zsh
```

3. zsh를 기본 셸로 변경
```
chsh -s $(which zsh)
```

4. Oh My Zsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```