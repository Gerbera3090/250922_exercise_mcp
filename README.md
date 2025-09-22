# 김개발 - 소프트웨어 엔지니어 포트폴리오

> 사용자 경험을 중시하며, 확장 가능하고 유지보수가 용이한 소프트웨어를 개발하는 것을 목표로 하는 풀스택 소프트웨어 엔지니어의 개인 포트폴리오 웹사이트입니다.

## 📋 프로젝트 개요

이 프로젝트는 김개발이라는 소프트웨어 엔지니어의 개인 포트폴리오 웹사이트로, 현대적이고 반응형 디자인을 적용한 정적 웹사이트입니다. 타이핑 애니메이션, 스무스 스크롤, 인터랙티브 요소들이 포함되어 있어 사용자에게 매력적인 경험을 제공합니다.

## ✨ 주요 기능

### 🎨 UI/UX 기능

- **반응형 디자인**: 데스크톱, 태블릿, 모바일 모든 기기에서 최적화된 경험
- **타이핑 애니메이션**: 멀티 텍스트 타이핑 효과로 역동적인 첫인상 제공
- **스무스 스크롤**: 부드러운 페이지 내 네비게이션
- **스크롤 애니메이션**: 요소들이 화면에 나타날 때 페이드인 효과
- **인터랙티브 스킬 바**: 프로그레스 바 애니메이션으로 기술 수준 시각화

### 🧭 네비게이션

- **고정 헤더**: 스크롤 시 투명도와 그림자 효과 변화
- **모바일 햄버거 메뉴**: 작은 화면에서의 최적화된 네비게이션
- **활성 섹션 표시**: 현재 보고 있는 섹션에 따른 네비게이션 하이라이트
- **키보드 접근성**: ESC 키로 모바일 메뉴 닫기 지원

### 📱 반응형 기능

- **모바일 우선 설계**: 768px 이하에서 모바일 레이아웃으로 전환
- **적응형 그리드**: 화면 크기에 따른 콘텐츠 레이아웃 자동 조정
- **터치 친화적**: 모바일 기기에서의 터치 인터랙션 최적화

## 🛠️ 기술 스택

### Frontend

- **HTML5**: 시맨틱 마크업, 접근성 고려
- **CSS3**:
  - CSS Grid & Flexbox 레이아웃
  - CSS 애니메이션 & 트랜지션
  - CSS 변수 활용
  - 미디어 쿼리 반응형 디자인
- **Vanilla JavaScript (ES6+)**:
  - DOM 조작
  - 이벤트 처리
  - Intersection Observer API
  - 스크롤 최적화 (throttle/debounce)

### 폰트 & 아이콘

- **Google Fonts**: Noto Sans KR (한글 최적화)
- **이모지**: 크로스 플랫폼 호환 이모지 사용

## 📁 프로젝트 구조

```
250922_exercise_mcp/
├── index.html          # 메인 HTML 파일
├── style.css           # 스타일시트
├── script.js           # JavaScript 로직
└── README.md           # 프로젝트 문서
```

## 🎯 섹션 구성

### 1. **홈 (Hero Section)**

- 개인 소개 및 타이핑 애니메이션
- CTA 버튼 (연락하기, 프로젝트 보기)
- 프로필 이미지 플레이스홀더

### 2. **소개 (About Section)**

- 개인 경력 및 전문성 소개
- 통계 정보 (경력, 완료 프로젝트, 고객 만족도)

### 3. **기술 (Skills Section)**

- Frontend, Backend, Database, DevOps 기술 분류
- 프로그레스 바로 숙련도 시각화
- 카테고리별 기술 스택 정리

### 4. **경력 (Experience Section)**

- 타임라인 형태의 경력 이력
- 회사별 주요 업무 및 성과
- 기술 스택 및 프로젝트 경험

### 5. **프로젝트 (Projects Section)**

- 주요 프로젝트 3개 소개
- 기술 스택 태그
- 데모 및 GitHub 링크

### 6. **연락처 (Contact Section)**

- 연락처 정보 (이메일, 전화번호, 위치)
- 소셜 미디어 링크
- 연락처 폼 (유효성 검사 포함)

## 🚀 시작하기

### 설치 및 실행

1. **저장소 클론**

   ```bash
   git clone [repository-url]
   cd 250922_exercise_mcp
   ```

2. **로컬 서버 실행**

   ```bash
   # Python 3 사용
   python -m http.server 8000

   # 또는 Node.js 사용
   npx serve .

   # 또는 Live Server 확장 프로그램 사용 (VS Code)
   ```

3. **브라우저에서 확인**
   ```
   http://localhost:8000
   ```

### 개발 환경 설정

- **에디터**: VS Code 권장
- **확장 프로그램**: Live Server, Prettier, ESLint
- **브라우저**: Chrome, Firefox, Safari, Edge (최신 버전)

## 🎨 커스터마이징

### 색상 테마 변경

`style.css`에서 CSS 변수를 수정하여 색상 테마를 변경할 수 있습니다:

```css
:root {
  --primary-color: #3498db;
  --secondary-color: #2ecc71;
  --text-color: #333;
  --background-color: #ffffff;
}
```

### 콘텐츠 수정

- **개인 정보**: `index.html`의 텍스트 내용 수정
- **기술 스택**: Skills 섹션의 기술 항목 및 숙련도 조정
- **프로젝트**: Projects 섹션의 프로젝트 정보 업데이트
- **연락처**: Contact 섹션의 연락처 정보 변경

### 애니메이션 설정

`script.js`에서 애니메이션 속도를 조정할 수 있습니다:

```javascript
// 타이핑 애니메이션 속도
multiTypeWriter(typingText, texts, 80, 40, 2000);
//                              ↑   ↑    ↑
//                           타이핑 삭제 대기시간
```

## 📱 브라우저 지원

- **Chrome**: 60+
- **Firefox**: 55+
- **Safari**: 12+
- **Edge**: 79+

## 🔧 성능 최적화

- **이미지 최적화**: WebP 형식 사용 권장
- **폰트 최적화**: Google Fonts preconnect 사용
- **CSS 최적화**: 미사용 CSS 제거
- **JavaScript 최적화**: 이벤트 리스너 최적화 (throttle/debounce)

## 📄 라이선스

이 프로젝트는 개인 포트폴리오 목적으로 제작되었습니다.

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 연락처

- **이메일**: kim.developer@email.com
- **전화**: +82 10-1234-5678
- **위치**: 서울, 대한민국

---

⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!
