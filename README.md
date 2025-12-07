# Taehyun Kim - Portfolio Website

This is a personal portfolio website for **Taehyun Kim**, Systems Software Engineer.
It is built with **Jekyll** and features a **Single Page Scroll** layout with a fixed sidebar.

## 🚀 How to Run Locally (내 컴퓨터에서 실행하기)

1. **Install Dependencies** (First time only)
   ```bash
   bundle install
   ```

2. **Start Server**
   ```bash
   bundle exec jekyll serve
   ```
   
3. **Preview**
   Open your browser and go to `http://localhost:4000`

---

## 📝 Editing Guide (수정 가이드)

이 사이트는 크게 두 개의 파일만 수정하면 됩니다.

### 1. 내용 수정 (Content) → `index.md`
대부분의 텍스트(소개, 경력, 논문, 프로젝트 등)는 **`index.md`** 파일에 있습니다.
이 파일을 열어서 해당 섹션의 텍스트를 수정하면 바로 반영됩니다.

- **About Me**: 자기소개 수정
- **Experience**: 경력 추가/수정 (Timeline 형태)
- **Education**: 학력 수정
- **Skills**: 기술 스택 수정
- **Publications**: 논문 목록 수정
- **Projects**: 프로젝트 설명 수정

### 2. 사이드바 및 레이아웃 (Sidebar & Layout) → `_layouts/default.html`
좌측 사이드바의 프로필, 메뉴, 디자인 스타일(CSS)은 **`_layouts/default.html`** 파일에 있습니다.

- **프로필 사진/이름**: 사이드바 상단부 HTML 수정
- **소셜 링크**: GitHub, LinkedIn, Email 링크 수정
- **색상/폰트**: 파일 상단의 `<style>` 태그 내부 수정
  - `--primary-color`: 메인 색상
  - `--accent-color`: 강조 색상 (링크, 밑줄 등)

### 3. 프로필 사진 교체
- 사진 파일 위치: `assets/portfolio.png`
- 새로운 사진을 위 경로에 덮어쓰거나, `_layouts/default.html`에서 파일 경로를 수정하세요.

### 4. 사이트 기본 설정
- `_config.yml`: 사이트 제목, 기본 설정 등 (크게 건드릴 일은 없습니다.)

---

## 📂 Project Structure

```
.
├── index.md             # [MAIN] 메인 콘텐츠 (About, Experience, Publications...)
├── _layouts/
│   └── default.html     # [LAYOUT] 사이드바, HTML 구조, CSS 스타일
├── _config.yml          # [CONFIG] Jekyll 설정
├── assets/              # [ASSETS] 이미지 등 리소스 저장소
└── README.md            # 매뉴얼 (This file)
```
