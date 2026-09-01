<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="../images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">TypeScript Guide</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadetypescript?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadetypescript?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadetypescript?style=flat-square" alt="Last commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadetypescript?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Complete TypeScript guide: learning paths, courses, books, channels, tools and communities
> to get into the field and grow. Last review: September 2026.
>
> This is a translation of the Brazilian Portuguese guide. Resources are curated for the Brazilian community, so many are in Portuguese; 🇺🇸 marks English-language content.

## 🌍 Languages
[🇧🇷 Português](../README.md) · 🇺🇸 English (you are here)

## 📚 Table of contents
- [🎯 About this guide](#-about-this-guide)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Where to start](#-where-to-start)
- [🎓 Free courses](#-free-courses)
- [💰 Paid courses](#-paid-courses)
- [📖 Documentation](#-documentation)
- [📚 Books](#-books)
- [🎥 YouTube channels](#-youtube-channels)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs and newsletters](#-sites-blogs-and-newsletters)
- [🛠️ Tools](#-tools)
- [🧪 Hands-on projects and challenges](#-hands-on-projects-and-challenges)
- [🤖 AI in practice](#-ai-in-practice)
- [📜 Certifications](#-certifications)
- [💼 Career and jobs](#-career-and-jobs)
- [👥 Communities](#-communities)
- [🚨 How to contribute](#-how-to-contribute)
- [📄 License](#-license)
- [💙 Support the project](#-support-the-project)

## 🎯 About this guide
TypeScript is JavaScript with **static types**: you write code the compiler checks before it runs, get real autocomplete in the editor and refactor without fear. Created by Microsoft in 2012 and open source, it is now the default language of the front-end (React, Angular, Vue), of Node.js back-ends and of AI SDKs — and, since July 2026, it has a native Go compiler (TypeScript 7) up to 12× faster.

This guide is for people who already know (or are learning) JavaScript and want to master TypeScript, from the first `tsc --init` to advanced types. **Portuguese and free** resources come first in every section; 💰 marks paid content, 🇺🇸 English-language content and 🆕 material published or updated between 2024 and 2026. Every link was verified on the date of the last review.

## 🗺️ Roadmap
- [roadmap.sh — TypeScript Roadmap](https://roadmap.sh/typescript) — Community-made visual, interactive roadmap: what to study, in which order, with links per topic. 🇺🇸
- [TypeScript for the New Programmer (Handbook)](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html) — Official page explaining what TypeScript is without assuming prior experience. 🇺🇸
- [TypeScript for JavaScript Programmers (Handbook)](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) — Official 5-minute introduction for people coming from JavaScript. 🇺🇸
- [TypeScript Cheat Sheets (oficiais)](https://www.typescriptlang.org/cheatsheets/) — Official cheat sheets: Types, Interfaces, Classes and Control Flow, one page each. 🇺🇸

**Summary path** (follow in order; each step has resources in the sections below):

1. **Modern JavaScript (ES6+)** — `let/const`, arrow functions, destructuring, modules, `Promise`/`async-await`. Without this, TypeScript will just look like "JavaScript with extra errors".
2. **Setup** — Node.js LTS, `npm install -D typescript`, `npx tsc --init`, `"strict": true` from day one.
3. **Basic types** — primitives, arrays, tuples, `object`, `unknown` vs `any`, `never`, union and literal types, narrowing.
4. **Structures** — `interface` × `type`, typed functions, classes, `enum` (and when to avoid it), ES modules.
5. **Advanced types** — generics, utility types, `keyof`/`typeof`, indexed access, conditional and mapped types, template literal types.
6. **Ecosystem** — `tsconfig`, ESLint/Biome, testing with Vitest, bundlers, `@types` and `.d.ts` files.
7. **Application** — React + TS, Node + TS (Hono/Express/NestJS), validation with Zod, tRPC.
8. **Advanced** — type-level programming (Type Challenges), publishing libraries, native TypeScript 7.

## 🚀 Where to start
1. **Master JavaScript first.** Use the [MDN JavaScript Guide](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) — TypeScript is JavaScript underneath.
2. **Install the environment:** [Node.js](https://nodejs.org/) (LTS version) and [Visual Studio Code](https://code.visualstudio.com/), which understands TypeScript with no extensions.
3. **Try it without installing anything** in the [TypeScript Playground](https://www.typescriptlang.org/play): write on the left, see the generated JavaScript on the right.
4. **Take a quick 1-hour course:** [Matheus Battisti](https://www.youtube.com/watch?v=lCemyQeSCV8) or [Felipe Rocha](https://www.youtube.com/watch?v=ppDsxbUNtNQ) (both in Portuguese).
5. **Read the official Handbook**, starting with [TypeScript for JavaScript Programmers](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) and continuing with the [Handbook](https://www.typescriptlang.org/docs/handbook/intro.html).
6. **Go deeper with a full course:** [TypeScript — Zero to Hero](https://www.youtube.com/playlist?list=PLb2HQ45KP0Wsk-p_0c6ImqBAEFEY-LU9H) (Portuguese) or the free book [Total TypeScript Essentials](https://www.totaltypescript.com/books/total-typescript-essentials) (🇺🇸).
7. **Practice every day:** [typescript-exercises](https://typescript-exercises.github.io/) and the *easy* [Type Challenges](https://github.com/type-challenges/type-challenges).
8. **Build and publish a project** on GitHub: an [API with Node + TypeScript](https://www.youtube.com/playlist?list=PL29TaWXah3iaaXDFPgTHiFMBF6wQahurP) or a [React + TypeScript](https://www.youtube.com/playlist?list=PL29TaWXah3iZktD5o1IHbc7JDqG_80iOm) app.

Your first project in 30 seconds:

```bash
mkdir hello-ts && cd hello-ts
npm init -y && npm install -D typescript
npx tsc --init          # generates tsconfig.json (keep "strict": true)
```

```ts
// hello.ts
function greeting(name: string): string {
  return `Hello, ${name}!`;
}
console.log(greeting("Guia Dev Brasil"));
```

```bash
npx tsc hello.ts && node hello.js   # compile and run
node hello.ts                       # Node.js 24+ runs .ts directly (type stripping)
```

## 🎓 Free courses
### In Portuguese
- [Curso: TypeScript — Zero to Hero (Glaucia Lemos)](https://www.youtube.com/playlist?list=PLb2HQ45KP0Wsk-p_0c6ImqBAEFEY-LU9H) — Complete free playlist, from zero to advanced topics, with a companion repository.
- [Repositório do curso TypeScript — Zero to Hero](https://github.com/glaucia86/curso-typescript-zero-to-hero) — Source code, exercises and materials for every lesson of Glaucia Lemos' series.
- [Curso de TypeScript na prática — aprenda em 1 hora (Matheus Battisti)](https://www.youtube.com/watch?v=lCemyQeSCV8) — Single, straight-to-the-point lesson to start from scratch with types, interfaces and classes.
- [Curso de TypeScript para Completos Iniciantes (Felipe Rocha)](https://www.youtube.com/watch?v=ppDsxbUNtNQ) — Didactic explanation of why TypeScript exists and how to use it day to day.
- [TypeScript, o início, de forma prática — MasterClass #07 (Rocketseat)](https://www.youtube.com/watch?v=0mYq5LrQN1s) — Free Rocketseat masterclass with a hands-on project.
- [Código da MasterClass de TypeScript da Rocketseat](https://github.com/rocketseat-content/masterclass-typescript) — Repository with the code written during the masterclass, to follow along and practice.
- [Curso de TypeScript (CFB Cursos)](https://www.youtube.com/playlist?list=PLx4x_zx8csUhtPMrkiGvFJVE5LX8Qat5s) — Portuguese playlist with short lessons, one concept per video.
- [Curso gratuito de TypeScript 2025 (dev.to, Leandro Lopes)](https://dev.to/portugues/curso-gratuito-de-typescript-2025-5b3c) — Text-based course published in 2025, lesson by lesson, with code on GitHub. 🆕
- [Introdução ao TypeScript (DIO)](https://www.dio.me/courses/introducao-ao-typescript) — Free DIO course with certificate, ideal as a first contact.
- [TypeScript — Aprendendo Junto (DevDojo)](https://www.youtube.com/playlist?list=PL62G310vn6nGg5OzjxE8FbYDzCs_UqrUs) — DevDojo series covering the language step by step.
- [Curso TypeScript do básico ao avançado (PogCast)](https://www.youtube.com/playlist?list=PL4iwH9RF8xHlxBrCZImFELtiew3TneihE) — Starts with data typing and moves up to generics and decorators.
- [Curso de TypeScript (Daniel Bergholz)](https://www.youtube.com/playlist?list=PLbV6TI03ZWYWwU5p9ZBH8oJTCjgneX53u) — Free course in Portuguese starting from 'what is TypeScript'.
- [Curso de API REST, Node e TypeScript (Lucas Souza Dev)](https://www.youtube.com/playlist?list=PL29TaWXah3iaaXDFPgTHiFMBF6wQahurP) — Building a complete API from scratch with Node.js and TypeScript.
- [Curso de React com TypeScript (Lucas Souza Dev)](https://www.youtube.com/playlist?list=PL29TaWXah3iZktD5o1IHbc7JDqG_80iOm) — React course typed with TypeScript from the very first lesson.
- [Do zero a produção: API Node.js com TypeScript (Waldemar Neto)](https://www.youtube.com/playlist?list=PLz_YTBuxtxt6_Zf1h-qzNsvVt46H8ziKh) — Real-world project with TypeScript, tests (Jest/TDD) and continuous integration.
- [TypeScript para Desenvolvedores C# (Glaucia Lemos)](https://www.youtube.com/playlist?list=PLb2HQ45KP0Wt32eCnju3lyncXUvDV5Nob) — Designed for people coming from C#/.NET who want to port their thinking to TypeScript.
- [POO TypeScript para Iniciantes (Noob Code)](https://www.youtube.com/playlist?list=PLnV7i1DUV_zMKEBTQ-wwlbyop8yVAh2tc) — Object-oriented programming explained with TypeScript for beginners.
- [Curso de Orientação a Objetos com TypeScript (Especializa TI)](https://www.youtube.com/playlist?list=PLVSNL1PHDWvQ8vKE5T2JTlLE4rXpFH3fM) — Classes, inheritance, interfaces and abstraction in practice.
- [Curso de TypeScript (João Ribeiro)](https://www.youtube.com/playlist?list=PLXik_5Br-zO9SEz-3tuy1UIcU6X0GZo4i) — Course in European Portuguese, well structured by chapters.
- [TypeScript, TDD e Clean Architecture (Mango)](https://www.youtube.com/playlist?list=PL9aKtVrF05DxIrtD3CuXGnzq8Q0IZ-t8J) — Clean Architecture applied with TypeScript, TDD and best practices.
- [Intensivão de Clean Architecture e TypeScript (Full Cycle)](https://www.youtube.com/watch?v=yLPxkIxbNDg) — Free multi-hour immersion on architecture with TypeScript.
- [Curso NodeJS com TypeScript (Andrew Rosário)](https://www.youtube.com/playlist?list=PLn3kOoc0oI2cQDdUEQxj75sxgRH53DmSc) — Node + TypeScript environment set up from scratch, with a practical API.
- [Node.js com TypeScript (Erick Wendel)](https://www.youtube.com/watch?v=3kMnv46J2X8) — Erick Wendel's lesson on using TypeScript with Node.js.
- [Curso de TypeScript online grátis (Cursa)](https://cursa.com.br/curso-de-typescript-online-gr%C3%A1tis/581) — Free course with certificate, from basic to intermediate.
- [Learn X in Y minutes — TypeScript (PT-BR)](https://learnxinyminutes.com/pt-br/typescript/) — The whole language syntax in a single commented file, in Portuguese.

### In English
- [Learn TypeScript – Full Tutorial (freeCodeCamp)](https://www.youtube.com/watch?v=30LWjhZzg50) — Complete video course from freeCodeCamp. 🇺🇸
- [TypeScript Crash Course (Traversy Media)](https://www.youtube.com/watch?v=BCg4U1FzODs) — Quick, practical overview of the language. 🇺🇸
- [TypeScript Course for Beginners (Academind)](https://www.youtube.com/watch?v=BwuLxPH8IDs) — Introductory course by Maximilian Schwarzmüller. 🇺🇸
- [TypeScript Tutorial for Beginners (Programming with Mosh)](https://www.youtube.com/watch?v=d56mG7DezGs) — Fundamentals in one hour, with clear examples. 🇺🇸
- [React & TypeScript – Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=FJDVKeh7RJI) — React + TypeScript for beginners. 🇺🇸
- [TypeScript Course – Beginner to Advanced (Cloudaffle)](https://www.youtube.com/watch?v=vcNtrYfroDY) — Long course going all the way to advanced types. 🇺🇸
- [Total TypeScript — tutoriais gratuitos (Matt Pocock)](https://www.totaltypescript.com/tutorials) — Free interactive exercises from today's most influential TypeScript educator. 🆕 🇺🇸
- [Beginner's TypeScript Tutorial (Total TypeScript)](https://www.totaltypescript.com/tutorials/beginners-typescript) — Free tutorial with 18 beginner exercises, right in the editor. 🇺🇸
- [Learn TypeScript (Codecademy)](https://www.codecademy.com/learn/learn-typescript) — Interactive in-browser course; the basic track is free. 🇺🇸
- [TypeScript Tutorial (typescripttutorial.net)](https://www.typescripttutorial.net/) — Text tutorial organized by topic, good as a quick reference. 🇺🇸
- [W3Schools — TypeScript Tutorial](https://www.w3schools.com/typescript/) — Short tutorial with exercises to nail down basic syntax. 🇺🇸

## 💰 Paid courses
- [Formação TypeScript (Alura)](https://www.alura.com.br/formacao-typescript) — Complete learning path in Portuguese, from basics to best practices. 💰
- [Aplique TypeScript no front-end (Alura)](https://www.alura.com.br/formacao-typescript-desenvolva-front-end-produtividade) — Learning path focused on TypeScript applied to the front-end. 💰
- [TypeScript para Iniciantes (Origamid)](https://www.origamid.com/curso/typescript-para-iniciantes/) — Highly rated Origamid course focused on pure TypeScript. 💰
- [React com TypeScript (Origamid)](https://www.origamid.com/curso/react-com-typescript/) — Typing the main hooks and React patterns with TypeScript. 💰
- [Formação TypeScript Essencial (Lucas Santos)](https://formacaots.com.br/) — Brazilian training program dedicated to TypeScript, with an active Discord community. 🆕 💰
- [Curso TypeScript Fullstack Developer (DIO)](https://www.dio.me/curso-typescript) — DIO learning path with TypeScript on the front-end (React) and back-end (Node). 💰
- [TypeScript 5+ Fundamentals (Frontend Masters)](https://frontendmasters.com/courses/typescript-v4/) — Mike North's course, updated for TypeScript 5. 🆕 💰 🇺🇸
- [Execute Program — TypeScript](https://www.executeprogram.com/courses/typescript) — Interactive course with spaced repetition; first lessons are free. 💰 🇺🇸

## 📖 Documentation
- [TypeScript Handbook (documentação oficial)](https://www.typescriptlang.org/docs/handbook/intro.html) — The official starting point: read it cover to cover at least once. 🇺🇸
- [Documentação oficial em português](https://www.typescriptlang.org/pt/docs/) — Official (partial) translation of the docs into Brazilian Portuguese.
- [TSConfig Reference](https://www.typescriptlang.org/tsconfig/) — Every `tsconfig.json` option explained, with examples. 🇺🇸
- [Utility Types](https://www.typescriptlang.org/docs/handbook/utility-types.html) — `Partial`, `Pick`, `Omit`, `Record`, `ReturnType`… the official list with examples. 🇺🇸
- [Declaration Files (arquivos .d.ts)](https://www.typescriptlang.org/docs/handbook/declaration-files/introduction.html) — How to write and publish types for JavaScript libraries. 🇺🇸
- [Notas de versão (What's new)](https://www.typescriptlang.org/docs/handbook/release-notes/overview.html) — History of every TypeScript version with examples of what's new. 🇺🇸
- [Blog oficial do TypeScript](https://devblogs.microsoft.com/typescript/) — Release, beta and RC announcements straight from the Microsoft team. 🇺🇸
- [Announcing TypeScript 7.0](https://devblogs.microsoft.com/typescript/announcing-typescript-7-0/) — The native Go compiler, released in July 2026: 8–12× faster builds. 🆕 🇺🇸
- [Announcing TypeScript 5.9](https://devblogs.microsoft.com/typescript/announcing-typescript-5-9/) — `import defer`, `--module node20` and the new minimal `tsc --init` (2025). 🆕 🇺🇸
- [microsoft/typescript-go](https://github.com/microsoft/typescript-go) — Repository of the native Go port of TypeScript, the basis of TypeScript 7. 🆕 🇺🇸
- [Node.js — Modules: TypeScript (type stripping)](https://nodejs.org/api/typescript.html) — Official docs on how Node runs `.ts` natively by stripping types. 🆕 🇺🇸
- [Node.js — Running TypeScript Natively](https://nodejs.org/en/learn/typescript/run-natively) — Official guide: run TypeScript without a build step on Node 22+/24. 🆕 🇺🇸
- [TypeScript Deep Dive (Basarat)](https://basarat.gitbook.io/typescript) — Free, open reference book — a great second read after the Handbook. 🇺🇸
- [TypeScript Deep Dive — tradução PT-BR](https://jorgedacostaza.gitbook.io/typescript-pt) — Community translation of Deep Dive into Portuguese.
- [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped) — Home of the `@types/*` packages: types for JavaScript libraries. 🇺🇸
- [Type Search](https://www.typescriptlang.org/dt/search) — Find out whether a library ships its own types or has them in `@types`. 🇺🇸
- [typescript-eslint — documentação](https://typescript-eslint.io/) — TypeScript-specific lint rules and setup guide. 🇺🇸

## 📚 Books
- [Total TypeScript Essentials (Matt Pocock) — gratuito](https://www.totaltypescript.com/books/total-typescript-essentials) — 100% free online book (2024), 16 chapters with exercises: from setup to generics. 🆕 🇺🇸
- [Guia prático de TypeScript (Thiago Adriano, Casa do Código)](https://www.casadocodigo.com.br/products/livro-typescript) — Brazilian book going from installation to an API with Node.js, MongoDB and Docker. 💰
- [Aprendendo TypeScript (Josh Goldberg, Novatec)](https://novatec.com.br/livros/aprendendo-typescript/) — Portuguese translation of O'Reilly's 'Learning TypeScript'. 💰
- [Effective TypeScript, 2ª edição (Dan Vanderkam)](https://effectivetypescript.com/) — 83 specific ways to improve your TypeScript; 2024 edition updated for TS 5. 🆕 💰 🇺🇸
- [Código-fonte do Effective TypeScript](https://github.com/danvk/effective-typescript) — Official repository with every example from the book, useful even without buying it. 🆕 🇺🇸
- [Learning TypeScript (Josh Goldberg, O'Reilly)](https://www.learningtypescript.com/) — Official book site, with free companion projects and articles. 💰 🇺🇸
- [TypeScript Cookbook (Stefan Baumgartner, O'Reilly)](https://typescript-cookbook.com/) — Practical recipes for real-world typing problems (2023). 💰 🇺🇸
- [Total TypeScript (Matt Pocock, No Starch Press)](https://nostarch.com/total-typescript) — Printed, expanded edition of Essentials, published in 2024. 🆕 💰 🇺🇸

## 🎥 YouTube channels
### In Portuguese
- [Rocketseat](https://www.youtube.com/@rocketseat) — React, Node and TypeScript, with frequent free events.
- [Matheus Battisti — Hora de Codar](https://www.youtube.com/@MatheusBattisti) — Complete free courses, several of them in TypeScript.
- [Felipe Rocha — Full Stack Club](https://www.youtube.com/@dicasparadevs) — Straightforward explanations for beginners, TypeScript included.
- [Otávio Miranda](https://www.youtube.com/@otaviomiranda) — Long, in-depth lessons on JavaScript, TypeScript and Python.
- [Lucas Souza Dev](https://www.youtube.com/@LucasSouzaDev) — Complete React and Node projects, always in TypeScript.
- [Glaucia Lemos](https://www.youtube.com/@GlauciaLemos) — Developer Advocate at Microsoft; author of the Zero to Hero course.
- [Full Cycle](https://www.youtube.com/@FullCycle) — Architecture, DDD and Clean Architecture, with lots of TypeScript.
- [Erick Wendel](https://www.youtube.com/@ErickWendelAcademy) — Advanced Node.js, performance and platform news.
- [Código Fonte TV](https://www.youtube.com/@codigofontetv) — News, comparisons and concepts explained in an accessible way.
- [Filipe Deschamps](https://www.youtube.com/@FilipeDeschamps) — Fundamentals and career, with an open-source project (TabNews).
- [Dev Soutinho (Mario Souto)](https://www.youtube.com/@DevSoutinho) — Modern front-end, React and TypeScript with a career focus.
- [DevDojo](https://www.youtube.com/@DevDojoBrasil) — Long 'Aprendendo Junto' series, including TypeScript.

### In English
- [Matt Pocock](https://www.youtube.com/@mattpocockuk) — Short, advanced TypeScript tips; the most influential channel on the topic. 🇺🇸
- [Jack Herrington](https://www.youtube.com/@jherr) — TypeScript, React and modern tooling explained in depth. 🇺🇸
- [Fireship](https://www.youtube.com/@Fireship) — 100-second videos and quick tutorials, TypeScript included. 🇺🇸
- [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified) — Clear JavaScript/TypeScript and React tutorials. 🇺🇸
- [Theo — t3.gg](https://www.youtube.com/@t3dotgg) — Opinions and analysis on the full-stack TypeScript ecosystem. 🇺🇸
- [Traversy Media](https://www.youtube.com/@TraversyMedia) — Crash courses on virtually every web technology. 🇺🇸
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Complete, hours-long free courses. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech #207 — O Hype do TypeScript](https://www.hipsters.tech/o-hype-do-typescript-hipsters-207/) — History and motivation behind TypeScript, with Loiane Groner.
- [Hipsters Ponto Tech #378 — TechGuide: TypeScript](https://www.hipsters.tech/techguide-typescript-hipsters-ponto-tech-378/) — How to learn, adopt and use TypeScript day to day (2023).
- [Syntax.fm](https://syntax.fm/) — Wes Bos and Scott Tolinski's podcast; frequent TypeScript episodes. 🇺🇸
- [JS Party (Changelog)](https://changelog.com/jsparty) — Weekly panel on JavaScript and TypeScript. 🇺🇸

## 📰 Sites, blogs and newsletters
- [Total TypeScript — artigos](https://www.totaltypescript.com/articles) — Matt Pocock's articles and tips on TypeScript patterns and pitfalls. 🆕 🇺🇸
- [Effective TypeScript — blog](https://effectivetypescript.com/) — Dan Vanderkam's blog with deep dives into the type system. 🆕 🇺🇸
- [Marius Schulz — blog](https://mariusschulz.com/blog) — 'TypeScript Evolution' series explaining each language feature. 🇺🇸
- [oida.dev (Stefan Baumgartner)](https://oida.dev/) — Articles by the author of the TypeScript Cookbook. 🇺🇸
- [Goldblog (Josh Goldberg)](https://www.joshuakgoldberg.com/blog/) — Posts by the typescript-eslint maintainer and author of Learning TypeScript. 🇺🇸
- [dev.to — tag TypeScript](https://dev.to/t/typescript) — Thousands of community articles; many in Portuguese. 🇺🇸
- [Tipos básicos do TypeScript — Parte 1 (Marcelo Sarinho)](https://dev.to/marcelosarinho/tipos-basicos-do-typescript-parte-1-1fod) — Portuguese article (2024) on the fundamental types. 🆕
- [Tipos básicos do TypeScript — Parte 2 (Marcelo Sarinho)](https://dev.to/marcelosarinho/tipos-basicos-do-typescript-parte-2-lop) — Follow-up (2025): literal types, unions and more. 🆕
- [TypeScript Avançado: tipos genéricos e utilitários (Nicolaaz)](https://dev.to/nicolaazdev/typescript-avancado-tipos-genericos-e-utilitarios-que-transformam-seu-codigo-ekf) — Portuguese article (2025) on generics and utility types. 🆕
- [TypeScript Avançado (trinity_)](https://dev.to/trinity_/typescript-avancado-2f84) — Utility types and type transformations explained in Portuguese.
- [TypeScript Weekly (newsletter)](https://typescript-weekly.com/) — Weekly newsletter with the best TypeScript links. 🇺🇸
- [Bytes (newsletter)](https://bytes.dev/) — Witty newsletter about the JavaScript/TypeScript ecosystem. 🇺🇸

## 🛠️ Tools
### Run, compile and bundle
- [TypeScript Playground](https://www.typescriptlang.org/play) — Official online editor: test types and share examples via link. 🇺🇸
- [tsx](https://github.com/privatenumber/tsx) — Run TypeScript files directly on Node with zero config. 🆕 🇺🇸
- [ts-node](https://typestrong.org/ts-node/) — The classic TypeScript executor for Node.js. 🇺🇸
- [esbuild](https://esbuild.github.io/) — Extremely fast bundler/transpiler with TS support. 🇺🇸
- [Vite](https://vite.dev/) — The default build tool of the modern front-end; TypeScript works out of the box. 🆕 🇺🇸
- [Vitest](https://vitest.dev/) — Fast test framework with native TypeScript support. 🆕 🇺🇸
- [Deno](https://deno.com/) — Runtime that executes TypeScript natively, with a complete toolchain. 🆕 🇺🇸
- [Bun](https://bun.sh/) — Ultra-fast runtime and bundler that runs `.ts` without a build step. 🆕 🇺🇸
- [tsup](https://tsup.egoist.dev/) — Bundle TypeScript libraries with zero configuration. 🇺🇸
- [tsdown](https://tsdown.dev/) — Rolldown-based library bundler, spiritual successor to tsup. 🆕 🇺🇸
- [tsconfig/bases](https://github.com/tsconfig/bases) — Recommended base `tsconfig.json` files for Node, React, Vite etc. 🇺🇸

### Code quality and editor
- [typescript-eslint](https://typescript-eslint.io/) — Official integration between ESLint and TypeScript. 🇺🇸
- [Biome](https://biomejs.dev/) — Rust-based linter and formatter, an alternative to ESLint + Prettier. 🆕 🇺🇸
- [Prettier](https://prettier.io/) — Opinionated code formatter with TypeScript support. 🇺🇸
- [TypeDoc](https://typedoc.org/) — Generate documentation from code comments and types. 🇺🇸
- [ts-morph](https://ts-morph.com/) — Manipulate and analyze TypeScript code programmatically. 🇺🇸
- [Are the types wrong?](https://arethetypeswrong.github.io/) — Checks whether an npm package's types are published correctly. 🆕 🇺🇸
- [Pretty TypeScript Errors (extensão VS Code)](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors) — Makes TypeScript errors readable in the editor. 🆕 🇺🇸
- [TypeScript Error Translator (extensão VS Code)](https://github.com/mattpocock/ts-error-translator) — Translates cryptic errors into human language. 🇺🇸

### TypeScript-first libraries and utilities
- [Zod](https://zod.dev/) — Schema validation with type inference: validate data and get the types for free. 🆕 🇺🇸
- [Valibot](https://valibot.dev/) — Modular, lightweight alternative to Zod. 🆕 🇺🇸
- [ArkType](https://arktype.io/) — Validation with TypeScript-identical syntax and very high performance. 🆕 🇺🇸
- [tRPC](https://trpc.io/) — End-to-end typesafe APIs without code generation. 🆕 🇺🇸
- [Hono](https://hono.dev/) — Small, TypeScript-first web framework that runs on any runtime. 🆕 🇺🇸
- [Prisma](https://www.prisma.io/) — ORM with a fully typed client generated from the schema. 🇺🇸
- [Drizzle ORM](https://orm.drizzle.team/) — Lightweight, SQL-like, TypeScript-first ORM. 🆕 🇺🇸
- [Effect](https://effect.website/) — Library for robust TypeScript: typed errors, concurrency and more. 🆕 🇺🇸
- [type-fest](https://github.com/sindresorhus/type-fest) — Collection of essential utility types. 🇺🇸
- [ts-reset](https://github.com/mattpocock/ts-reset) — A 'CSS reset' for TypeScript: fixes bad types in the standard lib. 🇺🇸
- [ts-pattern](https://github.com/gvergnaud/ts-pattern) — Pattern matching with exhaustiveness checking. 🇺🇸
- [transform.tools — JSON to TypeScript](https://transform.tools/json-to-typescript) — Paste a JSON and get the interfaces ready. 🇺🇸
- [quicktype](https://quicktype.io/) — Generates types from JSON, JSON Schema and GraphQL. 🇺🇸

## 🧪 Hands-on projects and challenges
- [Type Challenges](https://github.com/type-challenges/type-challenges) — Type challenges from easy to extreme; the classic way to master the type system. 🇺🇸
- [TypeHero](https://typehero.dev/) — Interactive TypeScript challenge platform with rankings. 🆕 🇺🇸
- [Advent of TypeScript](https://www.adventofts.com/) — Advent-of-Code-style calendar of type challenges (2023 and 2024 editions). 🆕 🇺🇸
- [typescript-exercises](https://typescript-exercises.github.io/) — Progressive in-browser exercises to learn how to type real code. 🇺🇸
- [Beginner's TypeScript Tutorial — repositório](https://github.com/total-typescript/beginners-typescript-tutorial) — Total TypeScript exercises to run locally. 🇺🇸
- [Codewars — katas em TypeScript](https://www.codewars.com/kata/search/typescript) — Practice algorithms in TypeScript with automatic grading. 🇺🇸
- [Frontend Mentor](https://www.frontendmentor.io/) — Front-end challenges with ready-made designs; great for practicing React + TS. 🇺🇸
- [Learning TypeScript — projetos](https://www.learningtypescript.com/projects) — Free guided projects from Josh Goldberg's book. 🇺🇸
- [app-ideas](https://github.com/florinpop17/app-ideas) — App ideas by difficulty level to build your portfolio. 🇺🇸
- [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) — Recreate technologies from scratch (interpreters, databases, git…) — several in TypeScript. 🇺🇸
- [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) — Curated list of resources, libraries and tools. 🇺🇸

## 🤖 AI in practice
TypeScript and AI assistants make an especially good pair: the AI writes fast, and the **compiler is an independent reviewer** that catches what it got wrong. Use that to your advantage.

**For learning**
- Paste a compiler error (e.g. `TS2322: Type 'string' is not assignable to type 'number'`) together with the code snippet and ask: *"explain the cause and show two ways to fix it without `any`"*.
- Ask it to **convert one of your JavaScript files to TypeScript with `strict: true`**, then to justify every type it chose.
- Paste a JSON from an API and ask for the matching `interface`s — then compare with what [quicktype](https://quicktype.io/) generates.
- Ask for an advanced type "explained line by line" (e.g. a `conditional type` with `infer`) and check in the [Playground](https://www.typescriptlang.org/play) that the behavior matches.
- Ask for **exercises with answer keys** on the topic you are studying (generics, narrowing, mapped types).

**For work**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) or [Claude Code](https://code.claude.com/docs/en/overview) to: replace `any` with precise types, write Vitest tests, generate `.d.ts` files for a legacy JavaScript library and migrate JS→TS projects incrementally (file by file).
- After **every** accepted suggestion, run `npx tsc --noEmit` and the linter. If the code only compiles with `as`, `!` or `// @ts-ignore`, the suggestion is probably wrong.
- Turn on `"strict": true` and `"noUncheckedIndexedAccess": true`: the stricter the compiler, the more AI mistakes it intercepts.

**Limits and good practices**
- AI **makes up library APIs and types** (especially for recent versions). Confirm in the official docs and in `node_modules/@types`.
- It tends to overuse `any`, `as unknown as X` and needlessly complex types. Prefer the simplest type that solves the problem.
- Do not paste proprietary code, secrets or customer data into tools without your company's policy.
- Understand what you accept: in interviews and in production, the code is yours.

**TypeScript is the language of AI SDKs.** Learning TS opens the door to building applications with LLMs — the main libraries are TypeScript-first:
- [GitHub Copilot](https://github.com/features/copilot) — AI autocomplete and chat in the editor; free for students and with a free tier. 🆕 🇺🇸
- [Cursor](https://cursor.com/) — VS Code-based editor with AI built into the workflow. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Terminal coding agent: refactors, writes tests and explains complex types. 🆕 🇺🇸
- [Vercel AI SDK](https://ai-sdk.dev/) — TypeScript SDK for building LLM apps (streaming, tools, agents). 🆕 🇺🇸
- [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) — Official SDK for using Claude models from TypeScript. 🆕 🇺🇸
- [OpenAI Node/TypeScript SDK](https://github.com/openai/openai-node) — OpenAI's official, fully typed SDK. 🆕 🇺🇸
- [LangChain.js](https://js.langchain.com/) — Framework for LLM applications in TypeScript. 🆕 🇺🇸
- [Mastra](https://mastra.ai/) — TypeScript framework for AI agents, workflows and RAG. 🆕 🇺🇸
- [Model Context Protocol — SDK TypeScript](https://github.com/modelcontextprotocol/typescript-sdk) — Build MCP servers in TypeScript to connect tools to AI assistants. 🆕 🇺🇸

## 📜 Certifications
There is no official TypeScript certification — not even from Microsoft, which maintains the language. Employers assess **published projects and hands-on skill**. The certificates below are course-completion certificates: they help on a résumé but do not replace a portfolio.
- [Introdução ao TypeScript (DIO) — com certificado](https://www.dio.me/courses/introducao-ao-typescript) — Free course that issues a completion certificate.
- [Curso de TypeScript online grátis (Cursa) — com certificado](https://cursa.com.br/curso-de-typescript-online-gr%C3%A1tis/581) — Free digital certificate upon completion.
- [Learn TypeScript (Codecademy)](https://www.codecademy.com/learn/learn-typescript) — Issues a completion certificate on the Pro plan. 💰 🇺🇸
- [Formação TypeScript (Alura)](https://www.alura.com.br/formacao-typescript) — Alura certificate recognized by Brazilian companies. 💰

## 💼 Career and jobs
TypeScript is a requirement in most front-end (React, Angular, Vue), Node.js and mobile (React Native) job posts in Brazil. Tip: in the GitHub job repositories below, search open issues for "TypeScript".
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — TypeScript remains among the most used and admired languages worldwide. 🆕 🇺🇸
- [State of JavaScript 2024](https://2024.stateofjs.com/en-US/) — Annual survey of the JS/TS ecosystem: tools, trends and salaries. 🆕 🇺🇸
- [Programathor — vagas TypeScript](https://programathor.com.br/jobs-typescript) — Tech jobs in Brazil filtered by TypeScript.
- [GeekHunter](https://www.geekhunter.com.br/) — Brazilian platform where companies make offers to developers.
- [Coodesh](https://coodesh.com/) — Tech jobs in Brazil with standardized hiring processes.
- [Remotar](https://remotar.com.br/) — 100% remote jobs for Brazilians.
- [frontendbr/vagas](https://github.com/frontendbr/vagas) — Front-end jobs posted as GitHub issues.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Back-end jobs (many with Node + TypeScript) on GitHub.
- [react-brasil/vagas](https://github.com/react-brasil/vagas) — React jobs, almost all with TypeScript.
- [RemoteOK — vagas TypeScript](https://remoteok.com/remote-typescript-jobs) — International remote TypeScript jobs. 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Complete preparation for technical interviews. 🇺🇸

## 👥 Communities
- [TypeScript Community Discord (oficial)](https://discord.com/invite/typescript) — Official community server, with help channels and type experts. 🇺🇸
- [Issues do repositório do TypeScript](https://github.com/microsoft/TypeScript/issues) — Follow bugs, proposals and the roadmap discussed directly with the team. 🇺🇸
- [r/typescript](https://www.reddit.com/r/typescript/) — The TypeScript community subreddit. 🇺🇸
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical-content community created by Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Brazilian open-source community with an active Discord and TypeScript projects.
- [Frontend BR — fórum](https://github.com/frontendbr/forum) — Brazilian front-end forum on GitHub Discussions.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Brazilian community with tips, courses, mentoring and job posts.
- [DEV Community — devs brasileiros](https://dev.to/t/braziliandevs) — Tag with Portuguese articles from the Brazilian community.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Directory of Brazilian Telegram groups, including JavaScript/TypeScript.
- [Rocketseat — comunidade](https://www.rocketseat.com.br/) — One of Brazil's largest developer communities, with an open Discord.

## 🚨 How to contribute
Found a broken link, a new course or a tool that deserves to be here? Open an issue using the repository templates or send a pull request. Criteria: working link, legal content that is free or clearly marked as paid, with a one-line description. Details in [CONTRIBUTING.md](../CONTRIBUTING.md).

## 📄 License
This project is under the [MIT](../LICENSE) license. Made with 💙 by [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) and the [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) community.

## 💙 Support the project
Star this repository and the [main guide](https://github.com/arthurspk/guiadevbrasil), share it with someone who is starting out and follow the project on social media:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
