
# Git 명령어 총정리

## 기본 설정
- `git config --global user.name "이름"`: 사용자 이름 설정
- `git config --global user.email "이메일"`: 사용자 이메일 설정

## 저장소 초기화
- `git init`: 새로운 Git 저장소 생성

## 파일 상태 확인
- `git status`: 현재 파일 상태 확인

## 파일 추가
- `git add <파일명>`: 특정 파일을 스테이징 영역에 추가
- `git add .`: 모든 변경 파일을 스테이징 영역에 추가

## 커밋
- `git commit -m "메시지"`: 변경 사항을 커밋
- `git commit -am "메시지"`: 스테이징과 커밋을 동시에 수행

## 변경 사항 확인
- `git diff`: 워킹 디렉토리와 스테이징 영역 간의 차이 확인
- `git diff --staged`: 스테이징 영역과 마지막 커밋 간의 차이 확인

## 로그 확인
- `git log`: 커밋 로그 확인
- `git log --oneline`: 간략한 커밋 로그 확인

## 브랜치
- `git branch`: 현재 브랜치 목록 확인
- `git branch <브랜치명>`: 새로운 브랜치 생성
- `git checkout <브랜치명>`: 특정 브랜치로 이동
- `git checkout -b <브랜치명>`: 브랜치 생성 후 이동

## 병합
- `git merge <브랜치명>`: 특정 브랜치를 현재 브랜치에 병합

## 원격 저장소
- `git remote add origin <URL>`: 원격 저장소 추가
- `git push -u origin <브랜치명>`: 원격 저장소에 푸시
- `git pull origin <브랜치명>`: 원격 저장소에서 변경 사항 가져오기

## 기타
- `git clone <URL>`: 원격 저장소 복제
- `git reset <파일명>`: 스테이징 영역에서 파일 제거
- `git rm <파일명>`: 파일 삭제 및 스테이징
- `git stash`: 현재 작업 내용 임시 저장
- `git stash pop`: 임시 저장된 작업 복원
- `git tag <태그명>`: 특정 커밋에 태그 추가
- `git show <태그명>`: 태그 정보 확인