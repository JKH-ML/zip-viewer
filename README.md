# ZIP Viewer

ZIP 파일 안의 이미지와 동영상을 브라우저에서 바로 확인할 수 있는 뷰어입니다.

**[GitHub Pages에서 열기](https://jkh-ml.github.io/study-zip-viewer/)**

## 기능

- ZIP 파일 드래그 앤 드롭 또는 클릭으로 열기
- **폴더 열기** — 폴더를 선택하면 안의 ZIP 파일 목록을 표시하고, 클릭해서 바로 열기 (Chrome / Edge 지원)
- 이미지 / 동영상 필터
- 라이트박스로 크게 보기 (키보드 방향키, ESC 지원)
- 개별 파일 다운로드 및 전체 ZIP으로 묶어서 다운로드

## 지원 형식

| 종류 | 형식 |
|------|------|
| 이미지 | jpg, jpeg, png, gif, webp, bmp, svg, avif, tiff, ico |
| 동영상 | mp4, webm, ogg, mov, mkv, avi, m4v, 3gp, flv |

## 브라우저 호환성

| 기능 | Chrome | Edge | Firefox | Safari |
|------|--------|------|---------|--------|
| ZIP 파일 열기 | ✓ | ✓ | ✓ | ✓ |
| 폴더 열기 | ✓ | ✓ | — | — |

> 폴더 열기는 File System Access API를 사용하므로 Chrome / Edge 에서만 동작합니다.
