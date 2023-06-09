# windows에 wsl2를 설치해보자!

1. WSL 관련 기능 활설화
```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```

2. VirtualMachinePlatform 기능을 활성화합니다.
```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

3. wsl2 linux 커널 업데이트
공식사이트
```
https://learn.microsoft.com/ko-kr/windows/wsl/install#step-4---download-the-linux-kernel-update-package
```
패키지 다운 링크
```
https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi
```

4. default wsl2 set
```
wsl --set-default-version 2
```

5. windows store => ubuntu setup

6. wsl version check
```
wsl -l -v
```

7. 기본값 변경 wsl2로 변경
```
wsl --set-version Ubuntu 2
```

8. 6번 명령어 재실행(버전확인)