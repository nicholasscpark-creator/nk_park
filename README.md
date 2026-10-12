# nk_park - Nicholas Park 개인 사이트

Jekyll + [al-folio](https://github.com/alshedivat/al-folio) 테마, GitHub Pages 배포.

## 내용 수정
- About: `_pages/about.md` / CV: `_pages/cv.md` / Activities: `_pages/activities.md`
- Projects: `_projects/*.md` (카드 순서는 `importance` 숫자, 작을수록 앞)
- Publications: `_bibliography/papers.bib`
- 연락처 아이콘: `_data/socials.yml`
- 한·영: 같은 파일 안의 `<div class="lang-ko">` / `<div class="lang-en">` 블록을 함께 고침

## 사진
- 프로필: `assets/img/prof_pic.jpg` 저장 후 `_pages/about.md`의 `image:`에 파일명 기입
- 프로젝트: `assets/img/`에 저장 후 각 `_projects/*.md` 상단 주석의 형식으로 삽입, 카드 썸네일은 `img:`에 경로

## 배포
`main`에 푸시하면 GitHub Actions(`.github/workflows/deploy.yml`)가 빌드해 `gh-pages` 브랜치에 올림.
저장소 Settings → Pages → Source: Deploy from a branch, Branch: `gh-pages` / (root).
