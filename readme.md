# Next.js Notion Starter Kit

> The perfect starter kit for building websites with Next.js and Notion.

This project is forked from [https://github.com/transitive-bullshit/nextjs-notion-starter-kit](https://github.com/transitive-bullshit/nextjs-notion-starter-kit)
It uses **Notion** as a CMS, [react-notion-x](https://github.com/NotionX/react-notion-x), [Next.js](https://nextjs.org/), and [Vercel](https://vercel.com).

---
# 커스텀 내역
- 도메인 설정 : [career.over.ist](https://career.over.ist/)
- 포트폴리오 용도의 안티 크롤링 블로그를 배포하기 위해 sitemap.xml, robots.txt 비활성화
- css minor 버그 수정
- vercel CI/CD

# How to set-up
**version**
- node v18.18.2
- npm v10.8.3 or pnpm v10.4.1

**dependency install**
```
$ npm install
```

**debug**
```
$ npm run dev
```

**deploy**
```
$ npm run build
$ npm run start
```
\* tip : vercel을 사용하여 Github Repository를 연동하면 간단한 CI/CD를 구축할 수 있습니다.