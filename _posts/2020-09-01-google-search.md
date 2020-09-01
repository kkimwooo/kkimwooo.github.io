---
title: "구글 검색 노출 되는 방법 (작성중)"
date: 2020-09-01 00:26:28 -0400
categories: blog
---

- 네이버, 구글 블로그 같은 건 각 포털에서 검색이 가능하나, github 블로그는 각 포탈에 검색 가능하도록 등록해주어야함

1. Google Search Console에 블로그 url 등록
(https://search.google.com/search-console/welcome?hl=ko)
1) URL 접두에 블로그 주소 입력
2) 소유권 확인
- html 다운 받아 깃헙 블로그 루트 폴더에 업로드
3) 확인 클릭(업로드 확인 된 경우 소유권 확인)

2. sitemap.xml 생성 (웹 크롤러에 내 블로그 정보 전달)
1) root경로에 sitemap.xml 생성
    
 3. robots.txt 생성(웹 크롤러가 내 사이트의 정보를 크롤링 하려고 할 때 크롤링 할 정책을 결정해주기 위한 파일)
 1) 루트 경로에 robots.txt 생성
 
 4. 구글 서치 콘솔에 sitemap 추가
 1) 구글 서치 콘솔에서 1번에서 등록한 url 정보 선택
 2) 색인>Sitemaps>새 사이트맵 추가에 sitemap.xml 입력 후 제출
 
 5. 구글 검색 테스트
- 검색창에 site:등록한url 입력 ex) site:kkimwooo.github.io

참고 : https://yammong.github.io/blog/Githubio%EA%B5%AC%EA%B8%80%EA%B2%80%EC%83%89%EB%85%B8%EC%B6%9C%EC%8B%9C%ED%82%A4%EA%B8%B0
