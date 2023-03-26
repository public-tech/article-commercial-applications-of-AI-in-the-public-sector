# PUBLICS Interactive Article framework

## Introduction 

This is a template repository for building interactive and engaging articles for mobile, tablet and web. 

## Article Outline 

A plain text version of the article goes here

## Tech Stack 

This framework is built using:

- [Next.js](https://nextjs.org/)
- Tailwind
- Jest 
- Cypress 
- AWS Amplify

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Testing 

To run unit tests: 

```bash
npm test 
```

To run end-to-end tests: 

```bash
npm run e2e
# in headless mode
npm run e2e:headless
```

To run component tests: 

```bash
npm run component
# in headless mode
npm run component:headless
```