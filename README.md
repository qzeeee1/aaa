# Toy Project 1 template

이 프로젝트는 토이 프로젝트 1 을 위한 템플릿 프로젝트입니다.   
템플릿에는 vite 기반 프론트앤드 프로젝트 구조와 express 기반 node 서버를 포함하고 있습니다.

## ✅ 설치

```
npm install
```

## ✅ 실행

### ✔️ 서버 실행

```
npm run server
```

### ✔️ 클라이언트 실행

```
npm run dev
```

# 📢 토이프로젝트 1 : 병원 인트라넷 서비스



## 👋 구성원 소개

| <img width="150px" src="https://avatars.githubusercontent.com/u/94222592?v=4" style="max-width: 100%;"> | <img width="150px" src="https://avatars.githubusercontent.com/u/103170787?v=4" style="max-width: 100%;"> | <img width="150px" src="https://avatars.githubusercontent.com/u/148299246?v=4" style="max-width: 100%;"> | <img width="150px" src="https://avatars.githubusercontent.com/u/180731689?v=4" style="max-width: 100%;">|
| :-----------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
|                                               **정지윤**                                                |                                                **박현수**                                                |                                                **조유나**                                                |                                                **이혜림**                                                |
|                                [@jiyoon04](https://github.com/jiyoon04)                                |                               [@redbuttonking](https://github.com/redbuttonking)                               |                                  [@j0n0m2](https://github.com/j0n0m2)                                  |                             [@qzeeee1](https://github.com/qzeeee1)                              |
|                                     **알고보니조장**                                      |                                          **오류맨**                                          |                                          **조각가**                                          |                                        **곁들임**                                        |


## 📌 팀 규칙

1. 오전 10시 데일리 스크럼으로 본인 작업 진행상황 및 의견 공유합니다.
2. 주요 회의 시간 : 일주일 2회 진행 합니다. (화, 목요일)
3. 출결이슈는 팀원에게 사전에 미리 공유유 해주세요.
4. Slack에서 코멘트 및 이모지 활용하여 읽음을 표시 해주세요.
5. 모르는 것은 팀원에게 질문하며 서로 협력합니다.


## 🤝 컨벤션

코드의 일관성을 통해 불필요한 논쟁을 줄이고 팀의 생산성을 향상 합니다.

### 커밋메세지

- 커밋 메세지 구조
- 각 파트 사이에 엔터 하나를 둡니다.
- <태그>: <제목> 순서로 기입 합니다.(”:” 뒤에만 스페이스 남깁니다.)
- 태그의 첫글자는 대문자로 씁니다.
- Subject에 마침표 찍지 않습니다.
- 맨 뒤 괄호에 Github Issue 번호를 기입합니다.
- 만약에 이슈가 없으면 - - - ISSUE 번호 안써도 됩니다.

- 커밋 메세지 예시

  💡 feat: 새로운 기능 추가, 기능 로직 변경    
  🐛 fix: 버그 수정    
  📚 docs: 문서 수정, 주석    
  💄 style: 코드 포맷팅, 코드 변경이 없는 경우    
  🔧 refactor: 코드 리팩토링 (기능 변화 X)    
  ✏️ chore: 빌드 업무 수정, 패키지 매니저 수정    
  ✨ merge: main 브랜치에 반영     


### 코드 스타일

ESLint, Prettier를 활용해 공통 포맷팅 규칙을 사용합니다.
lit-html 플러그인 설치하여 페이지를 컴포넌화 하여 관리합니다.


### 브랜치

정확하고 효율적인 브랜치 관리를 위한 네이밍을 설정합니다.
브랜치를 페이지 단위로 구분하여 각 페이지를 표현 했습니다.

- 브랜치명 예시

  🎨 design    
  🔐 feat/login-mypage    
  🏖️ feat/absence-filter    
  ⏰ feat/work-status    
  📋 feat/board    



## 📅 진행 일정


### 1️⃣ 기획: 2025.01.06 - 2025.01.09

프로젝트의 첫 단계로 프로젝트트 요구사항을 면밀히 검토하고,
와이어프레임 설계를 통해 구체적인 UI/UX를 시각화했습니다.
팀원 개개인의 역량량을 고려하여 역할을 분담 했습니다.

### 2️⃣ 마크업: 2025.01.10 - 2025.01.13

HTML과 CSS를 활용하여 페이지의 기본 골격을 구성하기 시작했습니다.

### 3️⃣ 페이지 개발 part.1: 2025.01.14 - 2025.01.17

01/16 프로젝트 중간 리뷰와 멘토링을 거쳤으며,
일부 코드 병합과 브랜치 업데이트를 통해 개개인의 개발 현황을 점검했습니다.

### 4️⃣ 페이지 개발 part.2: 2025.01.18 - 2025.01.22

신규 기능과 개선사항은 소규모 PR(Pull Request)을 통해 검증하고 통합했습니다.
공통 CSS 을 정리하여 각자 제작한 페이지에 적용하였습니다.

### 5️⃣ 발표자료 점검

팀원들과 함께 발표 자료를 준비하고 리허설을 진행합니다.
필수 구현 내용뿐만 아니라 문제 해결 과정과 협업 경험을 포함합니다.

### 6️⃣ 리팩토링: 2025.01.31 - 2025.02.04

미완성된 기능들을 보완하고, 수렴된 피드백을 적용하는 작업을 진행합니다.

## 📥 설치 방법

### 저장소 복제

```bash
git clone https://github.com/Dev-FE-2/toy-project1-team1-intranet-project.git
```

### 의존성 패키지 설치

```bash
npm install
```

### 로컬 실행

```bash
npm run dev
```

## 🎯 활용 스택

### Front

<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

### Comm.

<img src="https://camo.githubusercontent.com/236fcd63f5c7932c0928a86fb7ebdbb5e8876cc4c03779cd1fc8aa9c0196aab2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769746875622d3138313731373f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/github-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" style="max-width: 100%;"><img src="https://camo.githubusercontent.com/fbe73eb0c50a7d491503c4e14d0a949a96f862997da5110f7ff0b9d28ef49a37/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f736c61636b2d3441313534423f7374796c653d666f722d7468652d6261646765266c6f676f3d736c61636b266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&amp;logo=slack&amp;logoColor=white" style="max-width: 100%;"><img src="https://camo.githubusercontent.com/cfd00850da7d61d06eedd66f38d007989ed62131e6b920e99016ed95de13c9a5/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e6f74696f6e2d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d6e6f74696f6e266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/notion-000000?style=for-the-badge&amp;logo=notion&amp;logoColor=white" style="max-width: 100%;">

## 📂 프로젝트 구조

```
toy-project1-team1-hospital-intranet-project
├─ public
├─ server
├─ src
│  ├─ common.css
│  ├─ reset.css
│  ├─ components
│  │  └─ Navbar.js
│  ├─ pages
│  │  ├─ admin
│  │  │  └─ MypageAdmin.js
│  │  └─ front
│  ├─ Download.js
│  ├─ Home.js
│  ├─ Login.js
│  │─ MyPage.js
│  ├─ Page.js
│  ├─ PageNotFound.js
│  └─ Support.js
├─ constants
├─ main.js
└─ utils
...
```

## 📝 프로젝트 자료

- [와이어프레임](https://www.figma.com/design/tC7kcB0CvAaa6luIpFNvVs/%EB%B3%91%EC%9B%90-%EC%9D%B8%ED%8A%B8%EB%9D%BC%EB%84%B7-%EC%84%9C%EB%B9%84%EC%8A%A4?node-id=0-1&p=f&t=Pg6jj0v5NCZftNpW-0)
- [팀컨벤션션](https://www.notion.so/I-1503259dc0c281ae998cede30c3b0a46?p=cd643144fe0b4e8cbbbc99b704bc228c&pm=s)
- [회의록](https://www.notion.so/I-1503259dc0c281ae998cede30c3b0a46?p=ee67966ea27347a5a8550e41b7ed9fb8&pm=s)
- [회고]()

## 🔍 페이지 별 기능
![image](https://github.com/user-attachments/assets/170d96af-df09-45c2-aa22-871730204e5c)

### 로그인 (이혜림)

- **로그인**

  - 로그인 탭을 사용자자용과 관리자용으로 구분했습니다.
  - 관리자로 로그인 탭 클릭시 아이디와 비밀번호를 입력하면 관리자 전용 페이지로 이동합니다.
  - 사용자로 로그인 탭 클릭시 아이디와 비밀번호를 입력하면 사용자자 전용 페이지로 이동합니다.

### 사용자용 페이지 초기화면 (조유나)

- 프로필 이미지, 이름, 팀, 직급이 표시됩니다.
- 실시간으로 현재 시간이 표시됩니다.
- 근무 시작/종료 버튼이 토글형식으로 작동하며 클릭하게 되면 현재시각이 화면에 표시되고 근무상태가 변경됩니다.


![image](https://github.com/user-attachments/assets/a30c4d03-14ed-4e8e-8707-a2d63dbdd4d3)

### 사용자용 마이페이지 (이혜림)
- 사용자의 프로필 이미지가 표시되며 이미지 파일을 등록 및 수정, 삭제 할수 있습니다.
- 등록 및 수정, 삭제 버튼은 아이콘을 사용하여 사용자에게 시각적으로 효과적으로 다가갑니다.
- 깔끔한 디자인을 위해 해당 버튼은 토글 기능을 구현 하였습니다.
- 사용자의 이름, 직급, 근무 상태가 표시됩니다.
- 사용자의 근무상태는 사용자용 페이지 초기화면의 근무시간 및 근무종료 토글 기능과 연결됩니다.
- 사용자의 개인 정보가 표시됩니다.

### 부재 내역 및 신청(박현수)

- **주요 기능**

- 부재 신청 버튼 클릭 시 신청 화면이 나타납니다.
- 다른 페이지로 이동하는 것이 아닌 한 페이지 안에서 작업 할 수 있는 모달 창을 구현했습니다.
- 사용자 입력 값으로 휴가 종류 , 시작일 , 종료일 , 휴가 사유가 있습니다.
- 휴가 신청하기 버튼 클릭 시 부재 신청 내역에 업로드 됩니다.
- 토글 버튼을 통해 휴가 종류에 대한 필터링이 가능합니다.
- 잔여 휴가 확인창을 구현하여 시각적으로 현재 남은 휴가 일수를 확인 할 수 있습니다.
- 달력차을 구현하여 시각적으로 해당 날짜의 달력을 확인 할 수 있습니다.
- 추후 달력 일자 클릭 시 해당 날짜 휴가 신청 내역을 볼 수 있는 기능을 추가할 예정입니다.

### 공지사항(영훈)

- **초기화면**

  - 공지사항 컬렉션에 저장된 정보를 가져와서 표시

- **페이지네이션**

  - 페이지네이션을 통한 게시물 탐색 가능
  - 첫페이지 인 경우 이전 버튼 없음/마지막 페이지인 경우 다음 버튼 없음
  - 페이지 이동 시 쿼리 스트링을 통해 뒤로가기/앞으로가기 가능

- **검색 기능**

  - 검색창에 키워드 입력 시 게시물 필터링 후 검색 결과 출력
  - 일치하는 검색어가 없는 경우 없음 화면 표기 및 쿼리스트링 변경

- **공지사항 상세**
  - 클릭 시 해당하는 공지사항의 상세 페이지를 노출

### 공지사항 관리(승건)

- **초기화면**
  - 공지사항 리스트 출력
- **검색 기능**

  - 검색어 입력 시 제목, 내용, 작성자 일치 여부 확인 후 리스트 표시
  - 검색 결과 없음 시 결과 없음 페이지 표시 및 경로에 `?search=검색어` 추가

- **페이지네이션**

  - 원하는 페이지 번호 클릭 시 해당 데이터 렌더링(`?pagination=페이지번호`)

- **수정/등록/삭제**
  - 수정 할 공지사항 클릭 시 상세 정보로 이동
  - 이미지, 제목, 내용 수정 가능(이미지 미수정 시 기존 이미지로 유지)
  - 로직 진행 중인 경우 수정 및 삭제 버튼 비활성화, 완료 후 DB 업데이트
  - 공지사항 삭제 기능 제공

### 직원 관리(승건)

- **초기화면**

  - 직원 리스트를 스크롤 형태로 확인 가능 합니다.
  - 상단에서 총 직원 수, 근무중인 직원 수, 승인 대기 중인 직원 수 확인 가능
  - 직원의 정렬 순서는 미승인-근무중-근무중 아님-계정삭제 직원 순이며, 이름 순 정렬

- **직원 상세**

  - 직원 목록에서 특정 직원 클릭 시 해당하는 직원의 상세 페이지 노출
  - 상세 페이지에서는 목록에 제공되는 정보 외에 주소, 연락처 등의 더 다양한 정보를 확인 가능
  - 정보 수정 버튼 클릭 시 직원 정보 수정 팝업 노출

- **직원 정보 수정**
  - 직원의 이미지, 입사일, 직급, 이메일주소, 전화번호, 자택주소, 생년월일이 표시됩니다.
  - 상단의 개인정보 수정 버튼을 클릭하면 이미지를 제외한 나머지 정보를 수정할 수 있습니다.
  - 로컬 스토리지를 사용하여 데이터 저장기능을 구현하였습니다.
  - 깔끔한 디자인을 위해 수정과 저장버튼을 토글 기능으로 구현하였습니다.


