---
title: '독립 웹사이트를 직접 구축하기 시작했다'
description: 'GitHub와 Cloudflare Pages, Astro를 이용해 독립 웹사이트를 구축하는 기록'
pubDate: 'Sep 07 2026'
heroImage: '../../assets/blog-placeholder-3.jpg'
---

오늘부터 특정 플랫폼에 종속되지 않는 독립 웹사이트를 직접 구축하기 시작했다.

처음에는 HTML 파일 하나를 GitHub에 올리고 Cloudflare Pages로 배포하는 아주 단순한 구조에서 시작했다.

## 처음 만든 구조

처음에는 다음과 같은 방식으로 사이트를 만들었다.

- GitHub에 `index.html` 저장
- Cloudflare Pages와 GitHub 연결
- GitHub에서 수정 후 Commit
- Cloudflare가 변경사항을 자동으로 감지
- 사이트 자동 재배포

이 과정을 통해 웹사이트가 실제로 어떤 구조로 동작하는지 직접 확인할 수 있었다.

## Astro로 넘어온 이유

HTML 파일만으로도 사이트는 충분히 만들 수 있다.

하지만 글이 많아질수록 문제가 생긴다.

예를 들어 메뉴를 하나 수정하려면 모든 HTML 파일을 각각 수정해야 한다.

Astro에서는 공통 Header와 Footer를 별도의 컴포넌트로 관리할 수 있기 때문에 한 번만 수정해도 전체 사이트에 반영된다.

또한 게시글은 HTML 전체를 작성할 필요 없이 Markdown 파일로 관리할 수 있다.

## 앞으로의 목표

앞으로 이 사이트에는 다음과 같은 기능을 순차적으로 추가할 예정이다.

- 글 목록 자동 관리
- 카테고리 분류
- 검색 기능
- 개인 도메인 연결
- Google Search Console 등록
- SEO 설정
- Google Analytics
- Google AdSense

현재 목표는 월 호스팅 비용 없이 안정적으로 운영할 수 있는 완전한 독립 사이트를 구축하는 것이다.