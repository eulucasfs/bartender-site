# Lucas Ferreira — Bartender & Garçom Profissional

Landing page premium, dark mode, com efeitos glassmorphism, animações suaves e design responsivo.

## 📂 Estrutura

```
bartender-site/
├── index.html        → Página principal (HTML semântico)
├── style.css         → Todo o design system e responsividade
├── script.js         → Navbar, animações reveal e formulário
├── assets/
│   └── icons.css     → Ícones SVG inline (sem dependências)
└── img/              → Imagens (hero, sobre, galeria de drinks)
    ├── hero.jpg
    ├── about.jpg
    ├── drink1.jpg ... drink6.jpg
```

## 🚀 Como abrir

1. Descompacte o arquivo `.zip`.
2. Abra **`index.html`** diretamente no navegador (clique duplo).
3. Pronto — funciona 100% offline, sem build, sem dependências.

> Dica: para hot-reload durante edição, use a extensão **Live Server** do VS Code.

## ✏️ Como editar

| O que mudar | Onde |
|---|---|
| Nome, frases, textos | `index.html` |
| Cores, fontes, espaçamentos | `style.css` → variáveis em `:root` |
| Imagens | substitua arquivos em `img/` mantendo os nomes |
| Links de redes sociais / WhatsApp | `index.html` (seções `#contato` e `footer`) |
| Comportamento do formulário | `script.js` |

### Paleta principal
- `--bg` preto profundo `#0a0a0c`
- `--gold` dourado suave `#d4af6a`
- `--wine` vinho `#5b1a2b`
- `--neon` rosa neon `#ff5577`

## 🎨 Tecnologias
- HTML5 semântico
- CSS3 moderno (Grid, Flex, Backdrop-filter, Custom Properties)
- JavaScript puro (IntersectionObserver, sem frameworks)
- Google Fonts: Cormorant Garamond + Inter

## 📱 Responsivo
Layout otimizado para desktop, tablet e mobile com menu hamburguer.

---
© Lucas Ferreira — feito com ♥ e gelo bem batido.
