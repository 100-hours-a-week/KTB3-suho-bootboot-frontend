# KTB3-suho-bootboot-frontend

## 프로젝트 소개
부트캠프 수강생들을 위한 커뮤니티 플랫폼 프론트엔드 프로젝트입니다.

## 소개 영상
https://github.com/user-attachments/assets/ecc1d80e-27ce-41d9-b32e-6b1e123a0e3f

## 개발 인원 및 기간
- 개발기간 : 2025-11-03 ~ 2025-12-07 (약 1개월) 
- 개발 인원 : 프론트엔드/백엔드 1명 (개인 프로젝트)
- 백엔드 GitHub: https://github.com/100-hours-a-week/KTB3-suho-bootboot-backend
  
## 기술 스택
### 🔧 Framework & Language
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
    <details>
  <summary><h2>📁 프로젝트 구조</h2></summary>
  
  ```

  bootboot/
    ├── package.json             # 프로젝트 설정 파일
    │
    ├── pages/                   # 페이지별 HTML 파일
    │   ├── auth/
    │   │   ├── login.html       # 로그인 페이지
    │   │   └── signup.html      # 회원가입 페이지
    │   ├── posts/
    │   │   ├── list.html        # 게시글 목록
    │   │   ├── detail.html      # 게시글 상세
    │   │   ├── create.html      # 게시글 작성
    │   │   └── edit.html        # 게시글 수정
    │   └── profile/
    │       ├── edit.html        # 프로필 수정
    │       └── change-password.html  # 비밀번호 변경
    │
    └── src/
        ├── js/
        │   ├── api/             # API 통신 모듈
        │   │   ├── auth.js      # 인증 API (로그인/로그아웃)
        │   │   ├── user.js      # 사용자 API
        │   │   ├── post.js      # 게시글 API
        │   │   ├── comment.js   # 댓글 API
        │   │   └── like.js      # 좋아요 API
        │   │
        │   ├── common/          # 공통 유틸리티
        │   │   ├── navbar.js    # 네비게이션 바
        │   │   ├── auth-check.js # 인증 상태 확인
        │   │   └── error-handler.js # 에러 처리
        │   │
        │   ├── utils/           # 유틸리티 함수
        │   │   ├── validator.js      # 입력값 검증
        │   │   ├── formatter.js      # 데이터 포맷팅
        │   │   └── storage.js        # 로컬스토리지 관리
        │   │
        │   └── pages/           # 페이지별 스크립트
        │       ├── auth/
        │       │   ├── login.js
        │       │   └── signup.js
        │       ├── posts/
        │       │   ├── list.js
        │       │   ├── detail.js
        │       │   ├── create.js
        │       │   └── edit.js
        │       └── profile/
        │           ├── edit.js
        │           └── change-password.js
        │
        ├── css/
        │   ├── common/          # 공통 스타일
        │   │   ├── reset.css    # CSS 초기화
        │   │   ├── variables.css # CSS 변수
        │   │   └── navbar.css   # 네비게이션 바
        │   │
        │   └── pages/           # 페이지별 스타일
        │       ├── auth.css     # 로그인/회원가입
        │       ├── posts.css    # 게시글 관련
        │       └── profile.css  # 프로필 관련
        │
        └── components/          # 재사용 컴포넌트
            ├── navbar.html      # 네비게이션 바
            └── login-required-modal.html  # 로그인 필요 모달
  ```

  </details>

## 기능

- 사용자 관리 (회원가입, 로그인, 정보 수정)
- 게시글 관리 (CRUD, 페이지네이션)
- 댓글 관리
- 좋아요 기능
