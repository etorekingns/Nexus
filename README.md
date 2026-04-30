# Nexus — Site Landing Page

Inspirado no estilo do Dala, com visual dark premium, Three.js no hero e animações suaves.

## Como rodar

### Pré-requisitos
- [Node.js](https://nodejs.org/) instalado (versão 16 ou superior)

### Passos

1. **Descompacte** o arquivo ZIP em uma pasta
2. **Abra o terminal** na pasta do projeto (no VS Code: `Ctrl+`` ` `` `)
3. **Instale as dependências:**
   ```bash
   npm install
   ```
4. **Inicie o servidor:**
   ```bash
   npm start
   ```
5. **Abra no navegador:** [http://localhost:3000](http://localhost:3000)

## Tecnologias usadas

- **Three.js** — animação 3D no hero (partículas + torus + grid)
- **Express.js** — servidor local simples
- **CSS puro** — animações, scroll reveal, cursor customizado
- **Google Fonts** — Playfair Display, Syne, DM Mono

## Estrutura

```
nexus-site/
├── public/
│   └── index.html     ← todo o site (HTML + CSS + JS)
├── server.js          ← servidor Express
├── package.json
└── README.md
```

## Features do site

- 🎨 Tema dark com cores teal/roxo/violeta
- ✨ Cursor customizado animado
- 🌐 Background 3D com Three.js (partículas, torus giratório, grid)
- 📜 Ticker animado
- 🎯 Scroll reveal nas seções
- 📱 Responsivo para mobile
- 🏃 Nav com blur ao scrollar
