# Notion 메인페이지 클론코딩
 
> 실제 서비스 중인 Notion 메인페이지를 분석하고 동일하게 구현한 클론코딩 프로젝트입니다.
 
<br>
 
## 프로젝트 개요
 
| 항목 | 내용 |
|------|------|
| 작업 기간 | 2025.04 – 2025.05 (4주) |
| 역할 | 마크업 · CSS 설계 · JS 인터랙션 전담 |
| 목표 | 원본 레이아웃 재현 및 JS 인터랙션 구현 |
| 사용 기술 | HTML / CSS / Vanilla JS |
 
<br>
 
## 사용 기술
 
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
 
<br>
 
## 구현 기능
 
### 레이아웃
- Flex / Grid 심화 활용
- `position` 을 활용한 이미지 레이어 구성
- `inner` 기반 반응형 너비 제어
 
### 인터랙션
- 아코디언 클릭 시 비디오 전환 (opacity 트랜지션)
- 체크리스트 선택 + 인원수 입력 → 가격 실시간 계산
- 유튜브 영상 모달 팝업 (ESC / 배경 클릭 닫기)
- 무한 마퀴 애니메이션 (호버 시 일시정지)
- 스크롤 기반 Fade-up 애니메이션 (IntersectionObserver)
- 언어 선택 드롭다운
 
### 반응형
- PC / 태블릿 (1024px) / 모바일 (480px) 3단계 대응
- 모바일 햄버거 메뉴
- 모바일 전용 비디오 슬라이더 (도트 네비게이션)
 
<br>
 
##파일 구조
 
```
notion-clone/
├── index.html
├── css/
│   └── main.css
├── img/
│   └── ...
└── video/
    └── ...
```
 
<br>
 
## 핵심 학습
 
- `Grid` / `Flex` 중첩 구조 설계
- `position: absolute` 를 활용한 이미지 자유 배치
- `IntersectionObserver` 를 활용한 스크롤 애니메이션
- Vanilla JS로 실시간 가격 계산 로직 구현
- `opacity` 트랜지션을 활용한 깜빡임 없는 비디오 전환
- `position: fixed` + `document.body.appendChild` 를 활용한 모달 구현
 
<br>
 
## 참고
 
- 원본 사이트: [notion.com](https://www.notion.com)
- 본 프로젝트는 학습 목적으로 제작되었습니다.
