# 케이엠텍(주) 홈페이지

주소 https://replay121678.github.io/website/

이 저장소는 케이엠텍(주) 공식 홈페이지의 메인 페이지 소스코드입니다. 회사의 주요 장비와 정보를 소개하는 정적 웹사이트입니다.

## 주요 특징
- 상단 네비게이션 바 및 로고
- 주요 메뉴(배터리장비, 혼합분산장비, 건식장비, 습식장비, 실험장비)
- 장비 이미지 및 설명 섹션
- 반응형 레이아웃

## 폴더 구조
```
Website/
  ├─ assets/
  │    ├─ logo/
  │    │    └─ logo.ico
  │    └─ image/
  │         ├─ storage.png
  │         └─ storage2.png
  ├─ index.html
  └─ README.md
```

## 실행 방법
1. `main.html` 파일을 더블 클릭하거나 브라우저에서 엽니다.
2. 모든 이미지는 `assets` 폴더 내에 위치해야 정상적으로 표시됩니다.

## 사용 이미지 및 저작권 안내
- 로고: `assets/logo/logo.ico` (케이엠텍(주) 소유)
- 장비 이미지: `assets/image/storage.png`, `assets/image/storage2.png` (아무거나 구글링해서 박은것임 반드시 교체 필요)




####### 네비게이션 링크 연결 방법

HTML에서 다른 페이지로 이동하려면 `<a>` 태그의 `href` 속성에 이동할 파일명을 입력하면 됩니다.

예시:
```html
<nav>
  <a href="about.html">회사소개</a>
  <a href="#">제품</a>
</nav>
```
위와 같이 작성하면, '회사소개' 버튼을 클릭 시 `about.html` 페이지로 이동합니다.



## 나머지 페이지 제작 방법.
- 제미나이가 알고 있음 
