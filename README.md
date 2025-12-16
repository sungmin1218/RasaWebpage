🍛 Curry House RasaWebpage
커리하우스 라사의 메뉴, 매장 위치, 공지사항을 안내하는 웹 프로젝트입니다.
Python의 경량 웹 프레임워크인 Flask를 사용하여 구축되어있으며, 모던하고 깔끔한 UI와 디자인을 제공합니다.

📅 프로젝트 개요
프로젝트명: Curry House Website
개발 기간: 2025.09~
주요 기능: 매장 소개, 메뉴판 조회, 공지사항 검색 및 필터링, 위치 안내
개발 목적: 매장 홍보 및 고객 소통을 위한 웹 서비스 구축

✨ Key Features (주요 기능)
1. 메인 페이지 
- 매장 슬로건 및 히어로 이미지 섹션
- 주요 메뉴 미리보기 및 영업시간 안내

2. 메뉴 페이지
- 키마 커리, 치킨 커리 등 대표 메뉴 이미지와 가격을 카드 형태로 제공
- 사이드 추가 예정
- 직관적인 그리드 레이아웃 적용

3. 공지사항 게시판 
- 검색 기능: 제목, 태그, 내용 기반의 검색 
- 필터링: 중요 공지 상단 고정 노출
-모달 뷰: 게시글 클릭 시 상세 내용을 팝업(Alert)으로 확인 가능

4.위치 안내 
- Google Maps Embed API를 활용한 매장 위치 지도 표시


📂 Directory Structure
📦 CurryHouse-Project
  📂 static
  📂 images        # 메뉴 및 매장 이미지 
   📜 style.css     # 공통 스타일시트
  📂 templates       # HTML 파일 모음
   📜 index.html
   📜 menu.html
   📜 notice.html
   📜 location.html
  📜 app.py          # Flask 실행 파일
