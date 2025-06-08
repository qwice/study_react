# React 학습 프로젝트

이 프로젝트는 React 학습을 위한 기본 템플릿입니다. [Create React App](https://github.com/facebook/create-react-app)을 사용하여 생성되었습니다.

## 📁 프로젝트 구조

```
react-app/
├── public/
│   ├── favicon.ico          # 웹사이트 파비콘
│   ├── index.html          # 메인 HTML 템플릿
│   ├── logo192.png         # PWA용 로고 (192x192)
│   ├── logo512.png         # PWA용 로고 (512x512)
│   ├── manifest.json       # PWA 매니페스트 파일
│   └── robots.txt          # 검색엔진 크롤러 가이드
├── src/
│   ├── App.css             # App 컴포넌트 스타일
│   ├── App.js              # 메인 App 컴포넌트
│   ├── App.test.js         # App 컴포넌트 테스트
│   ├── index.css           # 전역 스타일
│   ├── index.js            # React 앱 진입점
│   ├── logo.svg            # React 로고
│   ├── reportWebVitals.js  # 웹 성능 측정
│   └── setupTests.js       # 테스트 설정
├── package.json            # npm 패키지 설정
├── package-lock.json       # npm 의존성 잠금 파일
├── .gitignore             # Git 무시 파일 목록
└── README.md              # 프로젝트 문서
```

## 🛠️ 기술 스택

- **React**: 18.3.1
- **React DOM**: 18.3.1
- **React Scripts**: 5.0.1
- **Testing Library**: Jest DOM, React, User Event
- **Web Vitals**: 웹 성능 측정

## 🚀 시작하기

### 필수 요구사항
- Node.js (14.0.0 이상)
- npm 또는 yarn

### 설치 및 실행

1. **의존성 설치**
   ```bash
   npm install
   ```

2. **개발 서버 실행**
   ```bash
   npm start
   ```
   브라우저에서 [http://localhost:3000](http://localhost:3000)으로 접속하여 확인할 수 있습니다.

3. **테스트 실행**
   ```bash
   npm test
   ```

4. **프로덕션 빌드**
   ```bash
   npm run build
   ```
   `build` 폴더에 최적화된 프로덕션 빌드가 생성됩니다.

## 📝 사용 가능한 스크립트

| 명령어 | 설명 |
|--------|------|
| `npm start` | 개발 모드로 앱을 실행합니다 |
| `npm test` | 테스트를 실행합니다 |
| `npm run build` | 프로덕션용 빌드를 생성합니다 |
| `npm run eject` | 설정 파일들을 노출시킵니다 (되돌릴 수 없음) |

## 🎯 학습 목표

이 프로젝트를 통해 다음을 배울 수 있습니다:

- React 컴포넌트 기초
- JSX 문법
- React Hooks
- 상태 관리
- 이벤트 처리
- 조건부 렌더링
- 리스트 렌더링

## 🔧 개발 팁

1. **Hot Reload**: 코드를 수정하면 자동으로 브라우저가 새로고침됩니다.
2. **ESLint**: 코드 품질을 위한 린팅이 설정되어 있습니다.
3. **Testing**: Jest와 Testing Library가 설정되어 있어 테스트 코드를 작성할 수 있습니다.

## 📚 학습 리소스

- [React 공식 문서](https://ko.reactjs.org/)
- [Create React App 문서](https://create-react-app.dev/)
- [React 튜토리얼](https://ko.reactjs.org/tutorial/tutorial.html)

## 🤝 기여하기

이 프로젝트는 학습 목적으로 만들어졌습니다. 개선 사항이나 추가 기능에 대한 제안은 언제든 환영합니다!

---

**Happy Coding! 🎉**
