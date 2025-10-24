# 무요요 (Muyoyo) - App Landing Page

요요 없는 체중 관리를 위한 챌린지 앱의 소개 페이지입니다.

## 🎯 Overview

**무요요**는 비만치료제 단약 후 체중 요요 현상을 방지하기 위한 습관 형성 챌린지 앱입니다.
7일 단위의 작은 챌린지를 통해 건강한 생활 습관을 만들고, 게임화 요소(뱃지, Streak)로 동기부여를 제공합니다.

## 📁 Files

- `index.html` - 메인 랜딩 페이지
- `style.css` - 스타일시트 (vibrant/playful 디자인)
- `README.md` - 이 문서

## 🚀 GitHub Pages 배포 방법

### 1. 파일을 GitHub 저장소에 업로드

```bash
# 저장소 클론 (아직 클론하지 않은 경우)
git clone https://github.com/poteamfive/muyoyo.git
cd muyoyo

# 랜딩 페이지 파일들을 저장소 루트에 복사
# index.html, style.css, README.md 파일을 복사

# Git에 추가 및 커밋
git add index.html style.css README.md
git commit -m "Add landing page for app introduction"
git push origin main
```

### 2. GitHub Pages 활성화

1. GitHub 저장소 페이지로 이동: https://github.com/poteamfive/muyoyo
2. **Settings** 탭 클릭
3. 왼쪽 메뉴에서 **Pages** 선택
4. **Source** 섹션에서:
   - Branch: `main` 선택
   - Folder: `/ (root)` 선택
5. **Save** 버튼 클릭

### 3. 배포 확인

약 1-2분 후 다음 URL에서 페이지가 활성화됩니다:
```
https://poteamfive.github.io/muyoyo/
```

상단에 초록색 배너로 "Your site is live at..." 메시지가 표시되면 배포 완료!

## 🎨 Design Features

- **Vibrant & Playful**: 활기찬 그라데이션과 컬러풀한 디자인
- **Compact Layout**: 한 화면에 모든 정보가 보이는 간결한 레이아웃
- **Responsive**: 모바일/태블릿/데스크톱 모두 지원
- **Animated**: 부드러운 호버 효과와 애니메이션
- **Emoji-Rich**: 친근한 느낌의 이모지 활용

## 📝 Customization

### 앱 스토어 링크 업데이트

`index.html` 파일의 다운로드 버튼 섹션을 수정하세요:

```html
<!-- App Store 링크 -->
<a href="YOUR_APP_STORE_URL" class="store-button app-store">

<!-- Google Play 링크 -->
<a href="YOUR_GOOGLE_PLAY_URL" class="store-button google-play">
```

### 스크린샷 추가

1. `images/` 폴더를 생성하고 스크린샷 이미지를 추가
2. `index.html`의 mockup-placeholder 섹션을 수정:

```html
<div class="phone-screen">
    <img src="images/screenshot.png" alt="App Screenshot" style="width: 100%; height: 100%; object-fit: cover; border-radius: 20px;">
</div>
```

### 색상 변경

`style.css` 파일의 그라데이션 색상을 원하는 색으로 변경:

```css
/* 배경 그라데이션 */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* 기능 카드 색상 */
.card-1 { background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); }
.card-2 { background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%); }
.card-3 { background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%); }
.card-4 { background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%); }
```

## 📚 Reference Documents

이 랜딩 페이지는 다음 기획 문서를 기반으로 제작되었습니다:

- `과제1_유저스토리.md` - 유저 스토리 & 시나리오
- `과제2_유저플로우맵.md` - 유저 플로우 다이어그램

## 🎯 Key Features Highlighted

1. **요요 위험도 진단** - 5가지 질문으로 맞춤 목표 설정
2. **나만의 챌린지 선택** - 운동/식단/생활습관 카테고리별 7일 챌린지
3. **매일 체크인 & 보상** - 자동/수동 체크인과 즉각적인 격려
4. **성취 & 지속 성장** - 뱃지 수집과 지속적인 도전

## 🛠️ Tech Stack

- HTML5
- CSS3 (Gradient, Flexbox, Grid, Animations)
- Responsive Design
- No JavaScript dependencies

## 📱 Browser Support

- Chrome/Edge (latest)
- Safari (latest)
- Firefox (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact

GitHub: [@poteamfive](https://github.com/poteamfive)

---

Made with 💚 by Team Five
