<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Guia de TypeScript</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadetypescript?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadetypescript?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadetypescript?style=flat-square" alt="Último commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadetypescript?style=flat-square" alt="Licença">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Guia completo de TypeScript: trilhas, cursos, livros, canais, ferramentas e comunidades
> para você entrar e evoluir na área. Última revisão: setembro/2026.

## 🌍 Idiomas
🇧🇷 Português (você está aqui) · [🇺🇸 English](./translations/README.en.md)

## 📚 Sumário
- [🎯 Sobre este guia](#-sobre-este-guia)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Por onde começar](#-por-onde-começar)
- [🎓 Cursos gratuitos](#-cursos-gratuitos)
- [💰 Cursos pagos](#-cursos-pagos)
- [📖 Documentação e apostilas](#-documentação-e-apostilas)
- [📚 Livros](#-livros)
- [🎥 Canais no YouTube](#-canais-no-youtube)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters)
- [🛠️ Ferramentas](#-ferramentas)
- [🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios)
- [🤖 IA na prática](#-ia-na-prática)
- [📜 Certificações](#-certificações)
- [💼 Carreira e vagas](#-carreira-e-vagas)
- [👥 Comunidades](#-comunidades)
- [🚨 Como contribuir](#-como-contribuir)
- [📄 Licença](#-licença)
- [💙 Apoie o projeto](#-apoie-o-projeto)

## 🎯 Sobre este guia
TypeScript é o JavaScript com **tipos estáticos**: você escreve código que o compilador verifica antes de rodar, ganha autocompletar de verdade no editor e refatora sem medo. Criado pela Microsoft em 2012 e open source, hoje é a linguagem padrão do front-end (React, Angular, Vue), do back-end em Node.js e dos SDKs de IA — e, desde julho de 2026, tem um compilador nativo em Go (TypeScript 7) até 12× mais rápido.

Este guia é para quem já sabe (ou está aprendendo) JavaScript e quer dominar TypeScript, do primeiro `tsc --init` a tipos avançados. Os recursos em **português e gratuitos** vêm primeiro em cada seção; 💰 marca conteúdo pago, 🇺🇸 conteúdo em inglês e 🆕 material publicado ou atualizado entre 2024 e 2026. Todo link foi verificado na data da última revisão.

## 🗺️ Roadmap
- [roadmap.sh — TypeScript Roadmap](https://roadmap.sh/typescript) — Roadmap visual e interativo da comunidade: o que estudar, em que ordem, com links por tópico. 🇺🇸
- [TypeScript for the New Programmer (Handbook)](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html) — Página oficial que explica o que é TypeScript sem pressupor experiência prévia. 🇺🇸
- [TypeScript for JavaScript Programmers (Handbook)](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) — Introdução oficial de 5 minutos para quem já vem do JavaScript. 🇺🇸
- [TypeScript Cheat Sheets (oficiais)](https://www.typescriptlang.org/cheatsheets/) — Folhas de cola oficiais: Types, Interfaces, Classes e Control Flow em uma página cada. 🇺🇸

**Trilha resumida** (siga na ordem; cada etapa tem recursos nas seções abaixo):

1. **JavaScript moderno (ES6+)** — `let/const`, arrow functions, destructuring, módulos, `Promise`/`async-await`. Sem isso, TypeScript só vai parecer "JavaScript com erros a mais".
2. **Setup** — Node.js LTS, `npm install -D typescript`, `npx tsc --init`, `"strict": true` desde o primeiro dia.
3. **Tipos básicos** — primitivos, arrays, tuplas, `object`, `unknown` vs `any`, `never`, union e literal types, narrowing.
4. **Estruturas** — `interface` × `type`, funções tipadas, classes, `enum` (e quando evitá-lo), módulos ES.
5. **Tipos avançados** — generics, utility types, `keyof`/`typeof`, indexed access, conditional e mapped types, template literal types.
6. **Ecossistema** — `tsconfig`, ESLint/Biome, testes com Vitest, bundlers, `@types` e arquivos `.d.ts`.
7. **Aplicação** — React + TS, Node + TS (Hono/Express/NestJS), validação com Zod, tRPC.
8. **Avançado** — programação em nível de tipos (Type Challenges), publicação de bibliotecas, TypeScript 7 nativo.

## 🚀 Por onde começar
1. **Domine o JavaScript primeiro.** Use o [Guia de JavaScript da MDN (PT-BR)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) — TypeScript é JavaScript por baixo.
2. **Instale o ambiente:** [Node.js](https://nodejs.org/) (versão LTS) e o [Visual Studio Code](https://code.visualstudio.com/), que já entende TypeScript sem extensões.
3. **Experimente sem instalar nada** no [TypeScript Playground](https://www.typescriptlang.org/play): escreva à esquerda, veja o JavaScript gerado à direita.
4. **Faça um curso rápido** de 1 hora: [Matheus Battisti](https://www.youtube.com/watch?v=lCemyQeSCV8) ou [Felipe Rocha](https://www.youtube.com/watch?v=ppDsxbUNtNQ).
5. **Leia o Handbook oficial**, começando por [TypeScript for JavaScript Programmers](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) e seguindo o [Handbook](https://www.typescriptlang.org/docs/handbook/intro.html).
6. **Aprofunde com um curso completo:** [TypeScript — Zero to Hero](https://www.youtube.com/playlist?list=PLb2HQ45KP0Wsk-p_0c6ImqBAEFEY-LU9H) (PT-BR) ou o livro gratuito [Total TypeScript Essentials](https://www.totaltypescript.com/books/total-typescript-essentials) (🇺🇸).
7. **Pratique todo dia:** [typescript-exercises](https://typescript-exercises.github.io/) e os desafios *easy* do [Type Challenges](https://github.com/type-challenges/type-challenges).
8. **Construa e publique um projeto** no GitHub: uma [API com Node + TypeScript](https://www.youtube.com/playlist?list=PL29TaWXah3iaaXDFPgTHiFMBF6wQahurP) ou um app [React + TypeScript](https://www.youtube.com/playlist?list=PL29TaWXah3iZktD5o1IHbc7JDqG_80iOm).

Seu primeiro projeto em 30 segundos:

```bash
mkdir ola-ts && cd ola-ts
npm init -y && npm install -D typescript
npx tsc --init          # gera o tsconfig.json (mantenha "strict": true)
```

```ts
// ola.ts
function saudacao(nome: string): string {
  return `Olá, ${nome}!`;
}
console.log(saudacao("Guia Dev Brasil"));
```

```bash
npx tsc ola.ts && node ola.js   # compila e executa
node ola.ts                     # Node.js 24+ executa .ts direto (type stripping)
```

## 🎓 Cursos gratuitos
### Em português
- [Curso: TypeScript — Zero to Hero (Glaucia Lemos)](https://www.youtube.com/playlist?list=PLb2HQ45KP0Wsk-p_0c6ImqBAEFEY-LU9H) — Playlist completa e gratuita, do zero até tópicos avançados, com repositório de apoio.
- [Repositório do curso TypeScript — Zero to Hero](https://github.com/glaucia86/curso-typescript-zero-to-hero) — Código-fonte, exercícios e materiais de cada aula da série da Glaucia Lemos.
- [Curso de TypeScript na prática — aprenda em 1 hora (Matheus Battisti)](https://www.youtube.com/watch?v=lCemyQeSCV8) — Aula única e direta para sair do zero com tipos, interfaces e classes.
- [Curso de TypeScript para Completos Iniciantes (Felipe Rocha)](https://www.youtube.com/watch?v=ppDsxbUNtNQ) — Explicação didática de por que TypeScript existe e como usá-lo no dia a dia.
- [TypeScript, o início, de forma prática — MasterClass #07 (Rocketseat)](https://www.youtube.com/watch?v=0mYq5LrQN1s) — Masterclass gratuita da Rocketseat com projeto prático.
- [Código da MasterClass de TypeScript da Rocketseat](https://github.com/rocketseat-content/masterclass-typescript) — Repositório com o código produzido na masterclass, para acompanhar e praticar.
- [Curso de TypeScript (CFB Cursos)](https://www.youtube.com/playlist?list=PLx4x_zx8csUhtPMrkiGvFJVE5LX8Qat5s) — Playlist em português com aulas curtas, um conceito por vídeo.
- [Curso gratuito de TypeScript 2025 (dev.to, Leandro Lopes)](https://dev.to/portugues/curso-gratuito-de-typescript-2025-5b3c) — Curso em texto publicado em 2025, aula a aula, com código no GitHub. 🆕
- [Introdução ao TypeScript (DIO)](https://www.dio.me/courses/introducao-ao-typescript) — Curso gratuito da DIO com certificado, ideal para o primeiro contato.
- [TypeScript — Aprendendo Junto (DevDojo)](https://www.youtube.com/playlist?list=PL62G310vn6nGg5OzjxE8FbYDzCs_UqrUs) — Série do DevDojo cobrindo a linguagem passo a passo.
- [Curso TypeScript do básico ao avançado (PogCast)](https://www.youtube.com/playlist?list=PL4iwH9RF8xHlxBrCZImFELtiew3TneihE) — Começa na tipagem de dados e avança até generics e decorators.
- [Curso de TypeScript (Daniel Bergholz)](https://www.youtube.com/playlist?list=PLbV6TI03ZWYWwU5p9ZBH8oJTCjgneX53u) — Curso gratuito em português começando por 'o que é TypeScript'.
- [Curso de API REST, Node e TypeScript (Lucas Souza Dev)](https://www.youtube.com/playlist?list=PL29TaWXah3iaaXDFPgTHiFMBF6wQahurP) — Construção de uma API completa do zero com Node.js e TypeScript.
- [Curso de React com TypeScript (Lucas Souza Dev)](https://www.youtube.com/playlist?list=PL29TaWXah3iZktD5o1IHbc7JDqG_80iOm) — Curso de React já tipado com TypeScript desde a primeira aula.
- [Do zero a produção: API Node.js com TypeScript (Waldemar Neto)](https://www.youtube.com/playlist?list=PLz_YTBuxtxt6_Zf1h-qzNsvVt46H8ziKh) — Projeto real com TypeScript, testes (Jest/TDD) e integração contínua.
- [TypeScript para Desenvolvedores C# (Glaucia Lemos)](https://www.youtube.com/playlist?list=PLb2HQ45KP0Wt32eCnju3lyncXUvDV5Nob) — Pensado para quem vem do C#/.NET e quer migrar o raciocínio para TypeScript.
- [POO TypeScript para Iniciantes (Noob Code)](https://www.youtube.com/playlist?list=PLnV7i1DUV_zMKEBTQ-wwlbyop8yVAh2tc) — Orientação a objetos explicada com TypeScript para quem está começando.
- [Curso de Orientação a Objetos com TypeScript (Especializa TI)](https://www.youtube.com/playlist?list=PLVSNL1PHDWvQ8vKE5T2JTlLE4rXpFH3fM) — Classes, herança, interfaces e abstração na prática.
- [Curso de TypeScript (João Ribeiro)](https://www.youtube.com/playlist?list=PLXik_5Br-zO9SEz-3tuy1UIcU6X0GZo4i) — Curso em português de Portugal, bem estruturado por capítulos.
- [TypeScript, TDD e Clean Architecture (Mango)](https://www.youtube.com/playlist?list=PL9aKtVrF05DxIrtD3CuXGnzq8Q0IZ-t8J) — Arquitetura limpa aplicada com TypeScript, TDD e boas práticas.
- [Intensivão de Clean Architecture e TypeScript (Full Cycle)](https://www.youtube.com/watch?v=yLPxkIxbNDg) — Imersão gratuita de várias horas sobre arquitetura com TypeScript.
- [Curso NodeJS com TypeScript (Andrew Rosário)](https://www.youtube.com/playlist?list=PLn3kOoc0oI2cQDdUEQxj75sxgRH53DmSc) — Ambiente Node + TypeScript configurado do zero, com API prática.
- [Node.js com TypeScript (Erick Wendel)](https://www.youtube.com/watch?v=3kMnv46J2X8) — Aula do Erick Wendel sobre como usar TypeScript no Node.js.
- [Curso de TypeScript online grátis (Cursa)](https://cursa.com.br/curso-de-typescript-online-gr%C3%A1tis/581) — Curso gratuito com certificado, do básico ao intermediário.
- [Learn X in Y minutes — TypeScript (PT-BR)](https://learnxinyminutes.com/pt-br/typescript/) — A sintaxe inteira da linguagem num único arquivo comentado, em português.

### Em inglês
- [Learn TypeScript – Full Tutorial (freeCodeCamp)](https://www.youtube.com/watch?v=30LWjhZzg50) — Curso completo em vídeo do freeCodeCamp. 🇺🇸
- [TypeScript Crash Course (Traversy Media)](https://www.youtube.com/watch?v=BCg4U1FzODs) — Visão geral rápida e prática da linguagem. 🇺🇸
- [TypeScript Course for Beginners (Academind)](https://www.youtube.com/watch?v=BwuLxPH8IDs) — Curso introdutório de Maximilian Schwarzmüller. 🇺🇸
- [TypeScript Tutorial for Beginners (Programming with Mosh)](https://www.youtube.com/watch?v=d56mG7DezGs) — Fundamentos em uma hora, com exemplos claros. 🇺🇸
- [React & TypeScript – Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=FJDVKeh7RJI) — React + TypeScript para quem está começando. 🇺🇸
- [TypeScript Course – Beginner to Advanced (Cloudaffle)](https://www.youtube.com/watch?v=vcNtrYfroDY) — Curso longo cobrindo até tipos avançados. 🇺🇸
- [Total TypeScript — tutoriais gratuitos (Matt Pocock)](https://www.totaltypescript.com/tutorials) — Exercícios interativos gratuitos do educador de TypeScript mais influente da atualidade. 🆕 🇺🇸
- [Beginner's TypeScript Tutorial (Total TypeScript)](https://www.totaltypescript.com/tutorials/beginners-typescript) — Tutorial gratuito com 18 exercícios para iniciantes, direto no editor. 🇺🇸
- [Learn TypeScript (Codecademy)](https://www.codecademy.com/learn/learn-typescript) — Curso interativo no navegador; a trilha básica é gratuita. 🇺🇸
- [TypeScript Tutorial (typescripttutorial.net)](https://www.typescripttutorial.net/) — Tutorial em texto, por tópicos, bom como referência rápida. 🇺🇸
- [W3Schools — TypeScript Tutorial](https://www.w3schools.com/typescript/) — Tutorial curto com exercícios para fixar a sintaxe básica. 🇺🇸

## 💰 Cursos pagos
- [Formação TypeScript (Alura)](https://www.alura.com.br/formacao-typescript) — Formação completa em português, do básico às boas práticas. 💰
- [Aplique TypeScript no front-end (Alura)](https://www.alura.com.br/formacao-typescript-desenvolva-front-end-produtividade) — Formação focada em TypeScript aplicado ao front-end. 💰
- [TypeScript para Iniciantes (Origamid)](https://www.origamid.com/curso/typescript-para-iniciantes/) — Curso da Origamid focado em TypeScript puro, muito bem avaliado. 💰
- [React com TypeScript (Origamid)](https://www.origamid.com/curso/react-com-typescript/) — Tipagem dos principais hooks e padrões de React com TypeScript. 💰
- [Formação TypeScript Essencial (Lucas Santos)](https://formacaots.com.br/) — Formação brasileira dedicada a TypeScript, com comunidade ativa no Discord. 🆕 💰
- [Curso TypeScript Fullstack Developer (DIO)](https://www.dio.me/curso-typescript) — Formação da DIO com TypeScript no front (React) e no back (Node). 💰
- [TypeScript 5+ Fundamentals (Frontend Masters)](https://frontendmasters.com/courses/typescript-v4/) — Curso de Mike North, atualizado para TypeScript 5. 🆕 💰 🇺🇸
- [Execute Program — TypeScript](https://www.executeprogram.com/courses/typescript) — Curso interativo com repetição espaçada; primeiras lições gratuitas. 💰 🇺🇸

## 📖 Documentação e apostilas
- [TypeScript Handbook (documentação oficial)](https://www.typescriptlang.org/docs/handbook/intro.html) — O ponto de partida oficial: leia do começo ao fim pelo menos uma vez. 🇺🇸
- [Documentação oficial em português](https://www.typescriptlang.org/pt/docs/) — Tradução oficial (parcial) da documentação para PT-BR.
- [TSConfig Reference](https://www.typescriptlang.org/tsconfig/) — Todas as opções do `tsconfig.json` explicadas, com exemplos. 🇺🇸
- [Utility Types](https://www.typescriptlang.org/docs/handbook/utility-types.html) — `Partial`, `Pick`, `Omit`, `Record`, `ReturnType`… a lista oficial com exemplos. 🇺🇸
- [Declaration Files (arquivos .d.ts)](https://www.typescriptlang.org/docs/handbook/declaration-files/introduction.html) — Como escrever e publicar tipos para bibliotecas JavaScript. 🇺🇸
- [Notas de versão (What's new)](https://www.typescriptlang.org/docs/handbook/release-notes/overview.html) — Histórico de cada versão do TypeScript com exemplos das novidades. 🇺🇸
- [Blog oficial do TypeScript](https://devblogs.microsoft.com/typescript/) — Anúncios de versões, betas e RCs direto do time da Microsoft. 🇺🇸
- [Announcing TypeScript 7.0](https://devblogs.microsoft.com/typescript/announcing-typescript-7-0/) — O compilador nativo em Go, lançado em julho de 2026: builds 8–12× mais rápidos. 🆕 🇺🇸
- [Announcing TypeScript 5.9](https://devblogs.microsoft.com/typescript/announcing-typescript-5-9/) — `import defer`, `--module node20` e o novo `tsc --init` enxuto (2025). 🆕 🇺🇸
- [microsoft/typescript-go](https://github.com/microsoft/typescript-go) — Repositório do port nativo do TypeScript em Go, base do TypeScript 7. 🆕 🇺🇸
- [Node.js — Modules: TypeScript (type stripping)](https://nodejs.org/api/typescript.html) — Documentação oficial de como o Node executa `.ts` nativamente removendo os tipos. 🆕 🇺🇸
- [Node.js — Running TypeScript Natively](https://nodejs.org/en/learn/typescript/run-natively) — Guia oficial: rodar TypeScript sem passo de build no Node 22+/24. 🆕 🇺🇸
- [TypeScript Deep Dive (Basarat)](https://basarat.gitbook.io/typescript) — Livro-referência gratuito e aberto, ótima segunda leitura após o Handbook. 🇺🇸
- [TypeScript Deep Dive — tradução PT-BR](https://jorgedacostaza.gitbook.io/typescript-pt) — Tradução comunitária do Deep Dive para português.
- [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped) — Repositório dos pacotes `@types/*`: tipos para bibliotecas JavaScript. 🇺🇸
- [Type Search](https://www.typescriptlang.org/dt/search) — Descubra se uma biblioteca já tem tipos embutidos ou em `@types`. 🇺🇸
- [typescript-eslint — documentação](https://typescript-eslint.io/) — Regras de lint específicas para TypeScript e guia de configuração. 🇺🇸

## 📚 Livros
- [Total TypeScript Essentials (Matt Pocock) — gratuito](https://www.totaltypescript.com/books/total-typescript-essentials) — Livro online 100% gratuito (2024), 16 capítulos com exercícios: do setup a generics. 🆕 🇺🇸
- [Guia prático de TypeScript (Thiago Adriano, Casa do Código)](https://www.casadocodigo.com.br/products/livro-typescript) — Livro brasileiro que vai da instalação até uma API com Node.js, MongoDB e Docker. 💰
- [Aprendendo TypeScript (Josh Goldberg, Novatec)](https://novatec.com.br/livros/aprendendo-typescript/) — Tradução em português do 'Learning TypeScript' da O'Reilly. 💰
- [Effective TypeScript, 2ª edição (Dan Vanderkam)](https://effectivetypescript.com/) — 83 formas específicas de melhorar seu TypeScript; edição de 2024 atualizada para o TS 5. 🆕 💰 🇺🇸
- [Código-fonte do Effective TypeScript](https://github.com/danvk/effective-typescript) — Repositório oficial com todos os exemplos do livro, útil mesmo sem comprá-lo. 🆕 🇺🇸
- [Learning TypeScript (Josh Goldberg, O'Reilly)](https://www.learningtypescript.com/) — Site oficial do livro, com projetos e artigos gratuitos de apoio. 💰 🇺🇸
- [TypeScript Cookbook (Stefan Baumgartner, O'Reilly)](https://typescript-cookbook.com/) — Receitas práticas para problemas reais de tipagem (2023). 💰 🇺🇸
- [Total TypeScript (Matt Pocock, No Starch Press)](https://nostarch.com/total-typescript) — Versão impressa e expandida do Essentials, publicada em 2024. 🆕 💰 🇺🇸

## 🎥 Canais no YouTube
### Em português
- [Rocketseat](https://www.youtube.com/@rocketseat) — React, Node e TypeScript, com eventos gratuitos frequentes.
- [Matheus Battisti — Hora de Codar](https://www.youtube.com/@MatheusBattisti) — Cursos completos gratuitos, vários deles em TypeScript.
- [Felipe Rocha — Full Stack Club](https://www.youtube.com/@dicasparadevs) — Explicações diretas para iniciantes, incluindo TypeScript.
- [Otávio Miranda](https://www.youtube.com/@otaviomiranda) — Aulas longas e aprofundadas de JavaScript, TypeScript e Python.
- [Lucas Souza Dev](https://www.youtube.com/@LucasSouzaDev) — Projetos completos em React e Node, sempre com TypeScript.
- [Glaucia Lemos](https://www.youtube.com/@GlauciaLemos) — Developer Advocate na Microsoft; autora do curso Zero to Hero.
- [Full Cycle](https://www.youtube.com/@FullCycle) — Arquitetura, DDD e Clean Architecture, com muito TypeScript.
- [Erick Wendel](https://www.youtube.com/@ErickWendelAcademy) — Node.js avançado, performance e novidades da plataforma.
- [Código Fonte TV](https://www.youtube.com/@codigofontetv) — Notícias, comparativos e conceitos explicados de forma acessível.
- [Filipe Deschamps](https://www.youtube.com/@FilipeDeschamps) — Fundamentos e carreira, com projeto open source (TabNews).
- [Dev Soutinho (Mario Souto)](https://www.youtube.com/@DevSoutinho) — Front-end moderno, React e TypeScript com foco em carreira.
- [DevDojo](https://www.youtube.com/@DevDojoBrasil) — Séries longas 'Aprendendo Junto', incluindo TypeScript.

### Em inglês
- [Matt Pocock](https://www.youtube.com/@mattpocockuk) — Dicas curtas e avançadas de TypeScript; o canal mais influente sobre o tema. 🇺🇸
- [Jack Herrington](https://www.youtube.com/@jherr) — TypeScript, React e ferramentas modernas explicadas com profundidade. 🇺🇸
- [Fireship](https://www.youtube.com/@Fireship) — Vídeos de 100 segundos e tutoriais rápidos, incluindo TypeScript. 🇺🇸
- [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified) — Tutoriais claros de JavaScript/TypeScript e React. 🇺🇸
- [Theo — t3.gg](https://www.youtube.com/@t3dotgg) — Opiniões e análises sobre o ecossistema TypeScript full-stack. 🇺🇸
- [Traversy Media](https://www.youtube.com/@TraversyMedia) — Crash courses de praticamente toda tecnologia web. 🇺🇸
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Cursos completos gratuitos com horas de duração. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech #207 — O Hype do TypeScript](https://www.hipsters.tech/o-hype-do-typescript-hipsters-207/) — História e motivação do TypeScript, com Loiane Groner.
- [Hipsters Ponto Tech #378 — TechGuide: TypeScript](https://www.hipsters.tech/techguide-typescript-hipsters-ponto-tech-378/) — Como aprender, adotar e usar TypeScript no dia a dia (2023).
- [Syntax.fm](https://syntax.fm/) — Podcast de Wes Bos e Scott Tolinski; episódios frequentes sobre TypeScript. 🇺🇸
- [JS Party (Changelog)](https://changelog.com/jsparty) — Painel semanal sobre JavaScript e TypeScript. 🇺🇸

## 📰 Sites, blogs e newsletters
- [Total TypeScript — artigos](https://www.totaltypescript.com/articles) — Artigos e dicas de Matt Pocock sobre padrões e armadilhas do TypeScript. 🆕 🇺🇸
- [Effective TypeScript — blog](https://effectivetypescript.com/) — Blog de Dan Vanderkam com análises profundas do sistema de tipos. 🆕 🇺🇸
- [Marius Schulz — blog](https://mariusschulz.com/blog) — Série 'TypeScript Evolution' explicando cada recurso da linguagem. 🇺🇸
- [oida.dev (Stefan Baumgartner)](https://oida.dev/) — Artigos do autor do TypeScript Cookbook. 🇺🇸
- [Goldblog (Josh Goldberg)](https://www.joshuakgoldberg.com/blog/) — Posts do mantenedor do typescript-eslint e autor do Learning TypeScript. 🇺🇸
- [dev.to — tag TypeScript](https://dev.to/t/typescript) — Milhares de artigos da comunidade; muitos em português. 🇺🇸
- [Tipos básicos do TypeScript — Parte 1 (Marcelo Sarinho)](https://dev.to/marcelosarinho/tipos-basicos-do-typescript-parte-1-1fod) — Artigo em português (2024) sobre os tipos fundamentais. 🆕
- [Tipos básicos do TypeScript — Parte 2 (Marcelo Sarinho)](https://dev.to/marcelosarinho/tipos-basicos-do-typescript-parte-2-lop) — Continuação (2025): literal types, unions e mais. 🆕
- [TypeScript Avançado: tipos genéricos e utilitários (Nicolaaz)](https://dev.to/nicolaazdev/typescript-avancado-tipos-genericos-e-utilitarios-que-transformam-seu-codigo-ekf) — Artigo em português (2025) sobre generics e utility types. 🆕
- [TypeScript Avançado (trinity_)](https://dev.to/trinity_/typescript-avancado-2f84) — Tipos utilitários e transformações de tipos explicados em português.
- [TypeScript Weekly (newsletter)](https://typescript-weekly.com/) — Newsletter semanal com os melhores links sobre TypeScript. 🇺🇸
- [Bytes (newsletter)](https://bytes.dev/) — Newsletter bem-humorada sobre o ecossistema JavaScript/TypeScript. 🇺🇸

## 🛠️ Ferramentas
### Executar, compilar e empacotar
- [TypeScript Playground](https://www.typescriptlang.org/play) — Editor online oficial: teste tipos e compartilhe exemplos por link. 🇺🇸
- [tsx](https://github.com/privatenumber/tsx) — Execute arquivos TypeScript direto no Node, sem configurar nada. 🆕 🇺🇸
- [ts-node](https://typestrong.org/ts-node/) — Executor clássico de TypeScript para Node.js. 🇺🇸
- [esbuild](https://esbuild.github.io/) — Bundler/transpilador extremamente rápido com suporte a TS. 🇺🇸
- [Vite](https://vite.dev/) — Ferramenta de build padrão do front-end moderno; TypeScript funciona sem configuração. 🆕 🇺🇸
- [Vitest](https://vitest.dev/) — Framework de testes rápido com suporte nativo a TypeScript. 🆕 🇺🇸
- [Deno](https://deno.com/) — Runtime que executa TypeScript nativamente, com toolchain completo. 🆕 🇺🇸
- [Bun](https://bun.sh/) — Runtime e bundler ultrarrápido que roda `.ts` sem build. 🆕 🇺🇸
- [tsup](https://tsup.egoist.dev/) — Empacote bibliotecas TypeScript com zero configuração. 🇺🇸
- [tsdown](https://tsdown.dev/) — Bundler de bibliotecas baseado em Rolldown, sucessor espiritual do tsup. 🆕 🇺🇸
- [tsconfig/bases](https://github.com/tsconfig/bases) — `tsconfig.json` base recomendados para Node, React, Vite etc. 🇺🇸

### Qualidade de código e editor
- [typescript-eslint](https://typescript-eslint.io/) — Integração oficial entre ESLint e TypeScript. 🇺🇸
- [Biome](https://biomejs.dev/) — Linter e formatador em Rust, alternativa a ESLint + Prettier. 🆕 🇺🇸
- [Prettier](https://prettier.io/) — Formatador de código opinativo, com suporte a TypeScript. 🇺🇸
- [TypeDoc](https://typedoc.org/) — Gere documentação a partir dos comentários e tipos do código. 🇺🇸
- [ts-morph](https://ts-morph.com/) — Manipule e analise código TypeScript programaticamente. 🇺🇸
- [Are the types wrong?](https://arethetypeswrong.github.io/) — Verifica se os tipos de um pacote npm estão publicados corretamente. 🆕 🇺🇸
- [Pretty TypeScript Errors (extensão VS Code)](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors) — Torna os erros do TypeScript legíveis no editor. 🆕 🇺🇸
- [TypeScript Error Translator (extensão VS Code)](https://github.com/mattpocock/ts-error-translator) — Traduz erros crípticos para linguagem humana. 🇺🇸

### Bibliotecas TypeScript-first e utilitários
- [Zod](https://zod.dev/) — Validação de esquemas com inferência de tipos: valide dados e ganhe os tipos de graça. 🆕 🇺🇸
- [Valibot](https://valibot.dev/) — Alternativa modular e leve ao Zod. 🆕 🇺🇸
- [ArkType](https://arktype.io/) — Validação com sintaxe idêntica à do TypeScript e performance altíssima. 🆕 🇺🇸
- [tRPC](https://trpc.io/) — APIs com tipagem ponta a ponta sem gerar código. 🆕 🇺🇸
- [Hono](https://hono.dev/) — Framework web pequeno, TypeScript-first, roda em qualquer runtime. 🆕 🇺🇸
- [Prisma](https://www.prisma.io/) — ORM com cliente totalmente tipado gerado a partir do schema. 🇺🇸
- [Drizzle ORM](https://orm.drizzle.team/) — ORM leve, SQL-like e TypeScript-first. 🆕 🇺🇸
- [Effect](https://effect.website/) — Biblioteca para código TypeScript robusto: erros tipados, concorrência e mais. 🆕 🇺🇸
- [type-fest](https://github.com/sindresorhus/type-fest) — Coleção de tipos utilitários essenciais. 🇺🇸
- [ts-reset](https://github.com/mattpocock/ts-reset) — 'CSS reset' para TypeScript: corrige tipos ruins da lib padrão. 🇺🇸
- [ts-pattern](https://github.com/gvergnaud/ts-pattern) — Pattern matching com verificação de exaustividade. 🇺🇸
- [transform.tools — JSON to TypeScript](https://transform.tools/json-to-typescript) — Cole um JSON e receba as interfaces prontas. 🇺🇸
- [quicktype](https://quicktype.io/) — Gera tipos a partir de JSON, JSON Schema e GraphQL. 🇺🇸

## 🧪 Projetos práticos e desafios
- [Type Challenges](https://github.com/type-challenges/type-challenges) — Desafios de tipos do fácil ao extremo; o clássico para dominar o sistema de tipos. 🇺🇸
- [TypeHero](https://typehero.dev/) — Plataforma interativa de desafios de TypeScript com ranking. 🆕 🇺🇸
- [Advent of TypeScript](https://www.adventofts.com/) — Calendário de desafios de tipos no estilo Advent of Code (edições 2023 e 2024). 🆕 🇺🇸
- [typescript-exercises](https://typescript-exercises.github.io/) — Exercícios progressivos no navegador para aprender a tipar código real. 🇺🇸
- [Beginner's TypeScript Tutorial — repositório](https://github.com/total-typescript/beginners-typescript-tutorial) — Exercícios do Total TypeScript para rodar localmente. 🇺🇸
- [Codewars — katas em TypeScript](https://www.codewars.com/kata/search/typescript) — Pratique algoritmos em TypeScript com correção automática. 🇺🇸
- [Frontend Mentor](https://www.frontendmentor.io/) — Desafios de front-end com design pronto; ótimo para praticar React + TS. 🇺🇸
- [Learning TypeScript — projetos](https://www.learningtypescript.com/projects) — Projetos guiados gratuitos do livro de Josh Goldberg. 🇺🇸
- [app-ideas](https://github.com/florinpop17/app-ideas) — Ideias de apps por nível de dificuldade para construir seu portfólio. 🇺🇸
- [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) — Recrie tecnologias do zero (interpretadores, bancos, git…) — vários em TypeScript. 🇺🇸
- [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) — Lista curada de recursos, bibliotecas e ferramentas. 🇺🇸

## 🤖 IA na prática
TypeScript e assistentes de IA formam uma dupla especialmente boa: a IA escreve rápido, e o **compilador é um revisor independente** que pega o que ela errou. Use isso a seu favor.

**Para aprender**
- Cole um erro do compilador (ex.: `TS2322: Type 'string' is not assignable to type 'number'`) junto com o trecho de código e peça: *"explique a causa e mostre duas formas de corrigir sem usar `any`"*.
- Peça para **converter um arquivo JavaScript seu para TypeScript com `strict: true`** e, depois, para justificar cada tipo escolhido.
- Cole um JSON de uma API e peça as `interface`s correspondentes — depois compare com o que o [quicktype](https://quicktype.io/) gera.
- Peça um tipo avançado "explicado linha a linha" (ex.: um `conditional type` com `infer`) e verifique no [Playground](https://www.typescriptlang.org/play) se o comportamento bate.
- Peça **exercícios com gabarito** sobre o tópico que está estudando (generics, narrowing, mapped types).

**Para trabalhar**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) ou [Claude Code](https://code.claude.com/docs/en/overview) para: trocar `any` por tipos precisos, escrever testes com Vitest, gerar arquivos `.d.ts` para uma biblioteca JavaScript legada e migrar projetos JS→TS de forma incremental (arquivo a arquivo).
- Depois de **cada** sugestão aceita, rode `npx tsc --noEmit` e o linter. Se o código só compila com `as`, `!` ou `// @ts-ignore`, a sugestão provavelmente está errada.
- Ative `"strict": true` e `"noUncheckedIndexedAccess": true`: quanto mais rigoroso o compilador, mais erros de IA ele intercepta.

**Limites e boas práticas**
- IA **inventa APIs e tipos** de bibliotecas (principalmente versões recentes). Confirme na documentação oficial e no `node_modules/@types`.
- Ela tende a abusar de `any`, `as unknown as X` e de tipos desnecessariamente complexos. Prefira o tipo mais simples que resolve.
- Não cole código proprietário, segredos ou dados de clientes em ferramentas sem a política da sua empresa.
- Entenda o que você aceita: em entrevista e em produção, o código é seu.

**TypeScript é a linguagem dos SDKs de IA.** Aprender TS abre a porta para construir aplicações com LLMs — as principais bibliotecas são TypeScript-first:
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete e chat com IA no editor; gratuito para estudantes e com plano free. 🆕 🇺🇸
- [Cursor](https://cursor.com/) — Editor baseado no VS Code com IA integrada ao fluxo de trabalho. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Agente de código no terminal: refatora, escreve testes e explica tipos complexos. 🆕 🇺🇸
- [Vercel AI SDK](https://ai-sdk.dev/) — SDK TypeScript para construir apps com LLMs (streaming, tools, agentes). 🆕 🇺🇸
- [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) — SDK oficial para usar os modelos Claude em TypeScript. 🆕 🇺🇸
- [OpenAI Node/TypeScript SDK](https://github.com/openai/openai-node) — SDK oficial da OpenAI, totalmente tipado. 🆕 🇺🇸
- [LangChain.js](https://js.langchain.com/) — Framework para aplicações com LLMs em TypeScript. 🆕 🇺🇸
- [Mastra](https://mastra.ai/) — Framework TypeScript para agentes de IA, workflows e RAG. 🆕 🇺🇸
- [Model Context Protocol — SDK TypeScript](https://github.com/modelcontextprotocol/typescript-sdk) — Crie servidores MCP em TypeScript para conectar ferramentas a assistentes de IA. 🆕 🇺🇸

## 📜 Certificações
Não existe certificação oficial de TypeScript — nem da Microsoft, que mantém a linguagem. Empregadores avaliam **projetos publicados e domínio prático**. Os certificados abaixo são de conclusão de curso: ajudam no currículo, mas não substituem portfólio.
- [Introdução ao TypeScript (DIO) — com certificado](https://www.dio.me/courses/introducao-ao-typescript) — Curso gratuito que emite certificado de conclusão.
- [Curso de TypeScript online grátis (Cursa) — com certificado](https://cursa.com.br/curso-de-typescript-online-gr%C3%A1tis/581) — Certificado digital gratuito ao concluir.
- [Learn TypeScript (Codecademy)](https://www.codecademy.com/learn/learn-typescript) — Emite certificado de conclusão no plano Pro. 💰 🇺🇸
- [Formação TypeScript (Alura)](https://www.alura.com.br/formacao-typescript) — Certificado da Alura reconhecido por empresas brasileiras. 💰

## 💼 Carreira e vagas
TypeScript aparece como requisito na maior parte das vagas de front-end (React, Angular, Vue), Node.js e mobile (React Native) no Brasil. Dica: nos repositórios de vagas do GitHub abaixo, pesquise por "TypeScript" nas issues abertas.
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — TypeScript segue entre as linguagens mais usadas e admiradas do mundo. 🆕 🇺🇸
- [State of JavaScript 2024](https://2024.stateofjs.com/en-US/) — Pesquisa anual sobre o ecossistema JS/TS: ferramentas, tendências e salários. 🆕 🇺🇸
- [Programathor — vagas TypeScript](https://programathor.com.br/jobs-typescript) — Vagas de tecnologia no Brasil filtradas por TypeScript.
- [GeekHunter](https://www.geekhunter.com.br/) — Plataforma brasileira onde empresas fazem propostas a devs.
- [Coodesh](https://coodesh.com/) — Vagas tech no Brasil com processos seletivos padronizados.
- [Remotar](https://remotar.com.br/) — Vagas 100% remotas para brasileiros.
- [frontendbr/vagas](https://github.com/frontendbr/vagas) — Vagas de front-end publicadas como issues no GitHub.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Vagas de back-end (muitas com Node + TypeScript) no GitHub.
- [react-brasil/vagas](https://github.com/react-brasil/vagas) — Vagas de React, quase todas com TypeScript.
- [RemoteOK — vagas TypeScript](https://remoteok.com/remote-typescript-jobs) — Vagas remotas internacionais com TypeScript. 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Preparação completa para entrevistas técnicas. 🇺🇸

## 👥 Comunidades
- [TypeScript Community Discord (oficial)](https://discord.com/invite/typescript) — Servidor oficial da comunidade, com canais de ajuda e especialistas em tipos. 🇺🇸
- [Issues do repositório do TypeScript](https://github.com/microsoft/TypeScript/issues) — Acompanhe bugs, propostas e o roadmap discutido diretamente com o time. 🇺🇸
- [r/typescript](https://www.reddit.com/r/typescript/) — Subreddit da comunidade TypeScript. 🇺🇸
- [TabNews](https://www.tabnews.com.br/) — Comunidade brasileira de conteúdo técnico criada por Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Comunidade brasileira open source com Discord ativo e projetos em TypeScript.
- [Frontend BR — fórum](https://github.com/frontendbr/forum) — Fórum brasileiro de front-end no GitHub Discussions.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Comunidade brasileira com dicas, cursos, mentorias e vagas.
- [DEV Community — devs brasileiros](https://dev.to/t/braziliandevs) — Tag com artigos em português da comunidade brasileira.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Diretório de grupos brasileiros no Telegram, incluindo JavaScript/TypeScript.
- [Rocketseat — comunidade](https://www.rocketseat.com.br/) — Uma das maiores comunidades de devs do Brasil, com Discord aberto.

## 🚨 Como contribuir
Achou um link quebrado, um curso novo ou uma ferramenta que merece estar aqui? Abra uma issue usando os templates do repositório ou envie um pull request. Critérios: link funcionando, conteúdo legal e gratuito ou claramente marcado como pago, com uma linha de descrição. Detalhes em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença
Este projeto está sob a licença [MIT](./LICENSE). Feito com 💙 por [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) e pela comunidade do [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil).

## 💙 Apoie o projeto
Dê uma ⭐ neste repositório e no [guia principal](https://github.com/arthurspk/guiadevbrasil), compartilhe com quem está começando e siga o projeto nas redes:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
