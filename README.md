# Minish Landing Page

미니시(Minish) 앱의 공식 랜딩 페이지입니다. GitHub Pages를 통해 배포되며, Google AdMob 인증을 위한 app-ads.txt 파일을 포함합니다.

## 🌐 Live Site
- **URL**: https://happyreni.github.io/minish/
- **AdMob Verification**: https://happyreni.github.io/minish/app-ads.txt

## 📁 구조
```
page/
├── index.html          # 메인 랜딩 페이지
├── styles.css          # CSS 스타일시트
├── script.js           # JavaScript 기능
├── app-ads.txt         # AdMob 인증 파일
├── assets/
│   └── images/         # 이미지 파일들
└── README.md           # 이 파일
```

## 🎨 디자인 특징
- **테마**: 앱과 동일한 Teal/Emerald 컬러 팔레트
- **반응형**: 모바일, 태블릿, 데스크톱 모든 기기 지원
- **폰트**: Noto Sans KR (한글) + Inter (영문)
- **애니메이션**: 부드러운 스크롤 및 호버 효과

## 🚀 배포 방법

### 자동 배포 (권장)
1. `page/` 폴더 내 파일을 수정
2. Git으로 변경사항을 main 브랜치에 push
3. GitHub Actions가 자동으로 GitHub Pages에 배포

### 수동 배포
1. GitHub 저장소 Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: main, Folder: /page
4. Save

## 📝 주요 섹션

### 1. Hero Section
- 앱 소개 및 다운로드 링크
- 폰 목업으로 앱 미리보기

### 2. Features
- 6개 핵심 기능 소개
- 개인정보 보호, 미니멀 디자인 등

### 3. Screenshots
- 앱 스크린샷 갤러리 (현재는 플레이스홀더)

### 4. Download
- Google Play Store 다운로드 링크

### 5. Privacy
- 개인정보 보호 정책 요약

## 🔧 AdMob 인증

`app-ads.txt` 파일이 다음 경로에서 접근 가능합니다:
- https://happyreni.github.io/minish/app-ads.txt

내용:
```
google.com, pub-7755621074003955, DIRECT, f08c47fec0942fa0
```

## 📱 앱 정보
- **앱 이름**: Minish
- **개발자**: TacoDog
- **플랫폼**: Android
- **패키지명**: com.tacodog.minish

## 🛠 개발
- **프레임워크**: Vanilla HTML/CSS/JS
- **반응형**: CSS Grid & Flexbox
- **아이콘**: 이모지 및 SVG
- **애니메이션**: CSS Transitions & Intersection Observer

## 📈 SEO 최적화
- Meta tags (Open Graph, Twitter Cards)
- 구조화된 데이터
- 시맨틱 HTML
- 반응형 디자인
- 빠른 로딩 속도

## 🎯 향후 개선사항
- [ ] 실제 앱 스크린샷 추가
- [ ] 앱 아이콘 및 파비콘 추가
- [ ] Google Analytics 연동
- [ ] PWA 지원
- [ ] 다국어 지원 (영문)

---

Made with ❤️ for better habits# minish.github.io
