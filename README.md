# GIR 과 GITHUB
## GIT
- GIT : **분산** 버전 관리 시스템
- GITHUB **원격 GIT 저장소**

### Local Git
- 저장소 생성
``` bash
git init
```

- git 설정
```bash
git config user.name"Seungkyun Nam"
git git config user.email "hhk3950@naver.com"
# 공용 git 설정을 하려면 -g
# 예) git config -g user.name 이름
```

-git 상태 확인
```bash
git status
```
- staging
```bash
git add .
```

- 저장소에 반영 (commit)
```bash
git commit -m "First Commit"
```

-상태 확인과 로고 확인
```bash
git status # 상태 확인
git log # 로그 확인
```
### Local Git to GITHUB
- Github에서 저장소 생성
- 저장소 주소
        - https://github.com/KimGyeongBln/GITTEST.git

- 원격지 등록
```bash
git remote add oriein https://github.com/KimGyeongBln/GITTEST.git
# git remota add 저장소 이름 저장소 주소
```
- push
```bash
git push -u oriein master # 첫 번째 푸시
git push # 기본 원격지 현재 브랜치를 푸시
```

### From GitHub to Local Git
- 복제할 원격 저장소 주소 확보
- 복제
```bash
git clone https://github.com/KimGyeongBln/GITTEST.git
# git clone 원격지 주소
```

- 저장소 설정

- 원격지 변경사항 fetch (확인)

- 원격지 변경사항 pull (내려받기)






- 저장소 설정

- 원격지 변경사항 FETCH (확인)

- 원격지 변경사항 PULL (내려받기)