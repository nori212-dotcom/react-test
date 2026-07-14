# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 리액트 앱 실행
- 개발서버 실행
  1. `npm run dev`
###### 리액트 앱 설치
- npm 모듈 설치
  1. `npm i`
---
#### 깃으로 관리하기

1. 현재 폴더를 Git 저장소로 초기화합니다.
   - `git init`
2. 현재 브랜치 이름을 `main`으로 변경합니다.
   - `git branch -M main`
3. GitHub 저장소를 원격 저장소로 등록합니다.
   - `git remote add origin https://github.com/[내깃사용자명]/react-test.git`
4. 변경된 파일을 커밋할 준비를 합니다.
   - `git add .`
   - `.`: 변경된 모든 파일을 선택합니다.
5. 커밋 메시지와 함께 변경 내용을 저장합니다.
   - `git commit -m "first commit"`
6. 로컬의 `main` 브랜치를 GitHub에 업로드합니다.
   - `git push -u origin main`