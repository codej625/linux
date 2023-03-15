# 리눅스를 초기화 시켜보자


환경 설정이되지 않은 패키지들을 환경에 설정합니다.
```
sudo dpkg --configure -a
```

레포지토리들의 내용을 업데이트합니다.
```
sudo apt-get update
```

의존성을 빠뜨린 걸 고치기 위해 아래의 install 명령어를 실행합니다.
(Try to fix missing dependencies:)
```
sudo apt-get -f install
```

가능한 새로운 버전으로 모든 패키지들을 업데이트 합니다.
```
sudo apt-get full-upgrade
```

Ubuntu desktop을 재설치합니다.
```
sudo apt-get install --reinstall ubuntu-desktop
```

불필요한 패키지들을 제거합니다.
```
sudo apt-get autoremove
```

이미 설치된 다운로드한 패키지들을 삭제합니다.
```
sudo apt-get clean
```

이슈가 해결되었는지 보기 위해 시스템 재시작합니다.
```
sudo reboot
```