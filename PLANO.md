# PLANO DO PROJETO: Projeto Profissional Full-Stack + Neon DB

> Gerado automaticamente pelo SK Code Editor em 23/06/2026, 03:43:52
> **40 arquivo(s)** | **~1.236 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React, TypeScript, Tailwind CSS
- **Versao:** 0.1.0

**Para rodar o projeto:**
```bash
npm install && npm run dev
```

---

## ESTRUTURA DE ARQUIVOS

```
Projeto Profissional Full-Stack + Neon DB/
├── .sk/
│   ├── memoria.json
│   └── perfil-jasmim.md
├── .vscode/
│   ├── extensions.json
│   ├── launch.json
│   └── settings.json
├── netlify/
│   └── edge-functions/
│       └── rewrite.js
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Alert.astro
│   │   ├── Diff.astro
│   │   ├── EdgeFunctionExplainer.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Logo.astro
│   │   └── Markdown.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── api/
│   │   │   ├── blob.ts
│   │   │   ├── blobs.ts
│   │   │   └── revalidate.ts
│   │   ├── blobs/
│   │   │   ├── _components/
│   │   │   │   ├── NewShape.tsx
│   │   │   │   ├── ShapeEditor.tsx
│   │   │   │   ├── ShapePreview.tsx
│   │   │   │   └── StoredShapes.tsx
│   │   │   └── index.astro
│   │   ├── edge/
│   │   │   ├── australia/
│   │   │   │   └── index.astro
│   │   │   ├── not-australia/
│   │   │   │   └── index.astro
│   │   │   └── index.astro
│   │   ├── image-cdn.astro
│   │   ├── index.astro
│   │   └── revalidation.astro
│   ├── styles/
│   │   └── globals.css
│   ├── utils/
│   │   └── highlighter.ts
│   ├── types.ts
│   └── utils.ts
├── .gitignore
├── .prettierrc
├── astro.config.mjs
├── package.json
├── README.md
├── renovate.json
└── tsconfig.json
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React, TypeScript, Tailwind CSS
- **Todos os pacotes (18):** @astrojs/netlify, @astrojs/react, @fontsource-variable/inter, @netlify/blobs, @netlify/functions, @tailwindcss/vite, astro, blobshape, marked, marked-shiki, react, react-dom, tailwindcss, unique-names-generator, @types/blobshape, @types/node, @types/react, @types/react-dom

---

## SCRIPTS DISPONIVEIS (package.json)

```bash
npm run dev           # astro dev
npm run start         # astro dev
npm run build         # astro build
npm run preview       # astro preview
npm run astro         # astro
```

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`.gitignore`** _(25 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`.prettierrc`** _(14 linhas)_
Arquivo PRETTIERRC — parte do projeto.

**`README.md`** _(44 linhas)_
Documentacao principal do projeto. Explica o que o projeto faz e como rodar.

**`astro.config.mjs`** _(18 linhas)_
Arquivo MJS — parte do projeto.

**`package.json`** _(35 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`renovate.json`** _(7 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`tsconfig.json`** _(10 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

---

### 📁 `.sk/`
> Pasta '.sk' — agrupamento de arquivos relacionados.

**`memoria.json`** _(1 linha)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`perfil-jasmim.md`** _(36 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

---

### 📁 `.vscode/`
> Pasta '.vscode' — agrupamento de arquivos relacionados.

**`extensions.json`** _(5 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`launch.json`** _(12 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`settings.json`** _(27 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

---

### 📁 `public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(31 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

---

### 📁 `src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`types.ts`** _(14 linhas)_
Arquivo de TIPOS — define as estruturas de dados (interfaces TypeScript) usadas no projeto.

**`utils.ts`** _(53 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `netlify/edge-functions/`
> Pasta 'edge-functions' — agrupamento de arquivos relacionados.

**`rewrite.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`Alert.astro`** _(17 linhas)_
Arquivo ASTRO — parte do projeto.

**`Diff.astro`** _(95 linhas)_
Arquivo ASTRO — parte do projeto.

**`EdgeFunctionExplainer.astro`** _(23 linhas)_
Arquivo ASTRO — parte do projeto.

**`Footer.astro`** _(10 linhas)_
Arquivo ASTRO — parte do projeto.

**`Header.astro`** _(31 linhas)_
Arquivo ASTRO — parte do projeto.

**`Logo.astro`** _(39 linhas)_
Arquivo ASTRO — parte do projeto.

**`Markdown.astro`** _(29 linhas)_
Arquivo ASTRO — parte do projeto.

---

### 📁 `src/layouts/`
> Estruturas de layout — esqueletos de pagina com cabecalho, sidebar, etc.

**`Layout.astro`** _(35 linhas)_
Arquivo ASTRO — parte do projeto.

---

### 📁 `src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`image-cdn.astro`** _(120 linhas)_
Arquivo ASTRO — parte do projeto.

**`index.astro`** _(20 linhas)_
Arquivo ASTRO — parte do projeto.

**`revalidation.astro`** _(63 linhas)_
Arquivo ASTRO — parte do projeto.

---

### 📁 `src/styles/`
> Arquivos de estilo visual — cores, fontes, layout.

**`globals.css`** _(79 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

---

### 📁 `src/utils/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`highlighter.ts`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `src/pages/api/`
> Comunicacao com servidor, banco de dados ou APIs externas.

**`blob.ts`** _(21 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`blobs.ts`** _(41 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`revalidate.ts`** _(20 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `src/pages/blobs/`
> Pasta 'blobs' — agrupamento de arquivos relacionados.

**`index.astro`** _(27 linhas)_
Arquivo ASTRO — parte do projeto.

---

### 📁 `src/pages/edge/`
> Pasta 'edge' — agrupamento de arquivos relacionados.

**`index.astro`** _(21 linhas)_
Arquivo ASTRO — parte do projeto.

---

### 📁 `src/pages/blobs/_components/`
> Pasta '_components' — agrupamento de arquivos relacionados.

**`NewShape.tsx`** _(59 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`ShapeEditor.tsx`** _(19 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`ShapePreview.tsx`** _(20 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`StoredShapes.tsx`** _(79 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `src/pages/edge/australia/`
> Pasta 'australia' — agrupamento de arquivos relacionados.

**`index.astro`** _(10 linhas)_
Arquivo ASTRO — parte do projeto.

---

### 📁 `src/pages/edge/not-australia/`
> Pasta 'not-australia' — agrupamento de arquivos relacionados.

**`index.astro`** _(10 linhas)_
Arquivo ASTRO — parte do projeto.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: Projeto Profissional Full-Stack + Neon DB
Tipo: Aplicacao Web Frontend (React)
Stack: React, TypeScript, Tailwind CSS
Arquivos: 40 | Linhas: ~1.236

Estrutura principal:
  .gitignore
  .prettierrc
  .sk/memoria.json
  .sk/perfil-jasmim.md
  .vscode/extensions.json
  .vscode/launch.json
  .vscode/settings.json
  README.md
  astro.config.mjs
  netlify/edge-functions/rewrite.js
  package.json
  public/favicon.svg
  renovate.json
  src/components/Alert.astro
  src/components/Diff.astro
  src/components/EdgeFunctionExplainer.astro
  src/components/Footer.astro
  src/components/Header.astro
  src/components/Logo.astro
  src/components/Markdown.astro
  src/layouts/Layout.astro
  src/pages/api/blob.ts
  src/pages/api/blobs.ts
  src/pages/api/revalidate.ts
  src/pages/blobs/_components/NewShape.tsx
  src/pages/blobs/_components/ShapeEditor.tsx
  src/pages/blobs/_components/ShapePreview.tsx
  src/pages/blobs/_components/StoredShapes.tsx
  src/pages/blobs/index.astro
  src/pages/edge/australia/index.astro
  src/pages/edge/index.astro
  src/pages/edge/not-australia/index.astro
  src/pages/image-cdn.astro
  src/pages/index.astro
  src/pages/revalidation.astro
  src/styles/globals.css
  src/types.ts
  src/utils.ts
  src/utils/highlighter.ts
  tsconfig.json
```

---

*Plano gerado pelo SK Code Editor — 23/06/2026, 03:43:52*