# Git & Github
## Git 이란?
- 버전 관리 시스템
- 파일의 변경 이력을 관리함.

## GitHub 란?
- Git 저장소를 온라인에서 관리하는 서비스
- Git 으로 관리하는 프로젝트를 업로드하고 협업할 수 있음

## 1. 저장소 생성
```
git init
```

- 현재 폴더를 Git 저장소로 초기화 한다.

## 2. 저장소 상태 확인
```
git status
```
- 파일의 변경 사항과 현재 상태를 확인한다.

## 3. 파일 추가
```
git add 파일명
```
- 변경된 파일을 Staging Area 에 추가한다.

## 4. 커밋
```
git commit -m "커밋 메시지"
```
- 스테이징된 변경 사항을 하나의 버전(커밋)으로 저장한다.

## 5. 원격 저장소(GitHub) 연결
```
git remote add origin 저장소 주소
```

- GitHub 저장소와 로컬 저장소 연결

```
git remote -v
```
- 연결 확인

## 6. 브랜치 확인 (사본생성느낌)
```
git branch
```
- 현재 브랜치를 확인한다.

## 7. GitHub에 업로드
```
git push origin main
```
- 로컬 저장소의 내용을 GitHub 원격 저장소로 업로드한다.

