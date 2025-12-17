# 🚀 Bernardo Antoniolli - Portfolio

Um portfólio moderno e impressionante com design futurista, animações fluidas e efeitos visuais de alta qualidade.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- 🎨 **Design Futurista** - Estética cyberpunk com gradientes vibrantes
- 🌟 **Animações Fluidas** - Transições suaves e efeitos de hover impressionantes
- 📱 **100% Responsivo** - Funciona perfeitamente em todos os dispositivos
- 🖱️ **Cursor Personalizado** - Interação visual única no desktop
- ⚡ **Performance Otimizada** - Carregamento rápido e animações suaves
- 🎭 **Loader Animado** - Tela de carregamento com efeito de digitação
- 🌈 **Efeitos de Background** - Orbs animados e grid overlay

## 🛠️ Tecnologias

- HTML5 Semântico
- CSS3 Moderno (Custom Properties, Grid, Flexbox)
- JavaScript Vanilla (ES6+)
- Google Fonts (Playfair Display, Outfit, JetBrains Mono)

## 📁 Estrutura do Projeto

```
portfolio/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos completos
├── js/
│   └── main.js         # Scripts e animações
├── assets/             # Imagens e recursos (se necessário)
├── vercel.json         # Configuração do Vercel
├── .gitignore          # Arquivos ignorados pelo Git
└── README.md           # Este arquivo
```

## 🚀 Deploy no Vercel

### Opção 1: Deploy via GitHub

1. Faça upload do projeto para um repositório GitHub
2. Acesse [vercel.com](https://vercel.com) e faça login
3. Clique em "New Project"
4. Importe o repositório do GitHub
5. Clique em "Deploy"

### Opção 2: Deploy via CLI

```bash
# Instale o Vercel CLI
npm i -g vercel

# Na pasta do projeto, execute:
vercel

# Siga as instruções no terminal
```

### Opção 3: Drag & Drop

1. Acesse [vercel.com](https://vercel.com)
2. Arraste a pasta do projeto para a área de deploy
3. Aguarde o deploy automático

## 🎨 Personalização

### Cores
Edite as variáveis CSS em `css/style.css`:

```css
:root {
    --color-accent-1: #6366f1;  /* Roxo principal */
    --color-accent-2: #8b5cf6;  /* Roxo médio */
    --color-accent-3: #a855f7;  /* Roxo claro */
    --color-accent-4: #ec4899;  /* Rosa */
    --color-accent-5: #06b6d4;  /* Ciano */
}
```

### Conteúdo
Edite diretamente o `index.html` para alterar:
- Nome e título
- Descrições
- Skills
- Links de contato
- Informações de educação

### Textos do Typing Effect
Edite o array em `js/main.js`:

```javascript
const texts = [
    'Back-End Developer',
    'Python Enthusiast',
    'AI Explorer',
    // Adicione mais textos aqui
];
```

## 📱 Responsividade

O site é totalmente responsivo com breakpoints em:
- `1024px` - Tablets e laptops pequenos
- `768px` - Tablets em modo retrato e celulares grandes
- `480px` - Celulares

## ⚡ Performance

- Sem dependências externas de JavaScript
- CSS otimizado com variáveis
- Animações usando `transform` e `opacity` para melhor performance
- Fontes com `display: swap` para carregamento otimizado

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar!

---

Feito com 💜 por Bernardo Antoniolli
