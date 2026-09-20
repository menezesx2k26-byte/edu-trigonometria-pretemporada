# 🪐 Órbita 14 — Pré-temporada IFSP

Campanha de 14 dias para entrar no semestre com **Trigonometria e Polinômios em funcionamento**, sem transformar as férias em uma segunda grade curricular.

A experiência combina progressão curta, feedback imediato, mapas visuais e prática fechada em uma interface mobile-first.

## 🎯 Estrutura da campanha

### 🌙 Órbita Trigonométrica

- 14 missões principais;
- sessões de aproximadamente 55–90 minutos;
- 112 questões;
- progressão orientada pelos tópicos centrais de trigonometria.

### 🔥 Forja Polinomial

- 14 side quests;
- sessões de aproximadamente 20–35 minutos;
- 56 questões;
- revisão progressiva de polinômios.

### ⚡ Modos de carga

**Combo normal:** 75–100 min na maior parte dos dias.

**Dias finais:** 105–125 min, divididos em rounds.

**Modo sobrevivência:** somente a side quest, para preservar consistência em dias ruins.

**Modo Boss:** campanha completa + captura explícita de erros.

## 📚 Princípios didáticos

- zero respostas longas obrigatórias;
- recuperação ativa;
- feedback imediato;
- exemplos sem entregar a resposta seguinte;
- mapas SVG autorais;
- 168 questões fechadas;
- progresso local;
- nenhuma missão concluída com pendências;
- domínio recalculado a partir do desempenho.

Os PDFs de referência permanecem privados e **não devem ser adicionados ao repositório**.

## 🧱 Stack

- Astro 7;
- React 19;
- TypeScript;
- Tailwind CSS 4;
- Vitest;
- Wrangler / Cloudflare Pages.

## 🎨 Interface

A aplicação é mobile-first e possui:

- mapas visuais;
- campanha em formato de jornada;
- feedback parcial;
- retomada de questões pendentes;
- **tema claro persistente**;
- estado salvo localmente.

## 🚀 Desenvolvimento

```bash
npm install
npm run dev
```

## ✅ Validação

```bash
npm test
npm run check
npm run build
npm run preview
```

O comando de build limpa `dist/` antes de gerar uma nova saída.

## ☁️ Cloudflare Pages

Configuração:

```text
Build command: npm run build
Output directory: dist
Node.js: 22+
```

Deploy manual:

```bash
npx wrangler pages deploy dist --project-name trigonometria-orbita-14
```

## 📁 Estrutura

```text
src/              aplicação e conteúdo
tests/            testes
AUDIT.md          auditoria do projeto
astro.config.mjs  configuração Astro
wrangler.jsonc    publicação Cloudflare
```

## 🔒 Conteúdo de referência

Os materiais de estudo externos servem como referência curricular, mas não fazem parte do artefato público.

O repositório deve conter apenas:

- implementação;
- conteúdo autoral permitido;
- exercícios incorporados de forma apropriada;
- testes;
- documentação.

---

**Status:** campanha completa de 14 dias, com Trigonometria + Polinômios e tema persistente. 🚀