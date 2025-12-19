<h1>1만 시간의 법칙 웹 프로젝트

10,000 Hour Rule – Web Application</h1>

<h2>1. 프로젝트 개요</h2>
본 프로젝트는 ‘1만 시간의 법칙’을 주제로 제작한 정적(Static) 웹 랜딩 페이지입니다.
시각적 요소(시계 배경, 타이틀 이미지, 따옴표 장식, CTA 버튼, 결과 강조 텍스트)를 중심으로 사용자가 목표 분야와 하루 훈련 시간을 입력하는 흐름을 제공하며, HTML/CSS 기반의 레이아웃 설계 및 반응형 퍼블리싱 역량을 보여주는 것을 목적으로 제작되었습니다.

배포: GitHub Pages

목적: 퍼블리싱(레이아웃/타이포/반응형) 구현 역량 증명

<strong>🔗 배포 URL</strong>
https://sonenae10-blip.github.io/10000hour/
<img width="1376" height="882" alt="image" src="https://github.com/user-attachments/assets/fe108e6a-f1c5-4c04-9368-d14634f7ba61" />
<img width="250" height="500" alt="image" src="https://github.com/user-attachments/assets/a2a36ec3-b8f4-46b6-b8ad-ab64a229d300" />
<hr />
<h2>2. 기술 스택</h2>
| 구성 영역      | 기술/도구                        |<br>
| 프론트엔드     | HTML5, CSS3, JavaScript      |<br>
| 빌드/호스팅    | GitHub Pages (정적 페이지 호스팅)    |<br>
| 리소스 관리    | 이미지 리소스 파일 (PNG/SVG)         |<br>
| 코드 저장소    | Git + GitHub                 |<br>
| 사용자 입력/연산 | JavaScript 기반 DOM 조작 및 계산 로직 |<br>
<hr />
<h2>3. 폴더 구조</h2>
/one-million-hours
│
├─ index.html
├─ reset.css
├─ style.css
│
└─ img
   ├─ clock.png
   ├─ title.png
   ├─ quotes1.png
   ├─ quotes2.png
   ├─ click.png
   └─ logo.png
<hr />
<h2>4. 구현 포인트</h2>
1. 메인 비주얼 오버레이 레이아웃

시계 배경 이미지를 absolute로 중앙 정렬하고, 타이틀을 상대적 레이어로 상단 유지하여 디자인 의도 반영<br><br>
2. 타이포그래피 위계

제목/설명/강조/결과 텍스트에 서로 다른 폰트 패밀리와 크기 체계를 적용<br><br>
3. 일관된 컴포넌트 스타일

입력창(input-box), 버튼(button1/2/3)의 라운드/크기/정렬을 컴포넌트 단위로 통일<br><br>
4. 모바일 반응형

480px 기준으로 폰트, 버튼 크기, 이미지 크기, padding을 재정의하여 작은 화면에서도 사용 가능하도록 조정
