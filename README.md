# Myndex Digital — Site Institucional

Site institucional da Myndex Digital, agência digital de Porto Alegre.

## Stack
- HTML5 semântico
- CSS moderno (Custom Properties, Flexbox, Grid)
- JavaScript vanilla (sem dependências)
- Google Fonts (Playfair Display + Plus Jakarta Sans)

## Estrutura
```
myndex-site/
├── index.html          # Página principal
├── assets/
│   ├── css/
│   │   └── style.css   # Estilos extraídos (referência)
│   ├── js/
│   │   └── main.js     # Scripts extraídos (referência)
│   └── img/            # Imagens e ícones
├── pages/              # Páginas futuras (sobre, projetos, etc.)
├── .gitignore
├── vercel.json         # Config de deploy
└── README.md
```

## Deploy

### GitHub + Vercel
1. Push para o repositório GitHub
2. Importar projeto no [vercel.com](https://vercel.com)
3. Deploy automático a cada `git push`

### Localmente
Abra `index.html` direto no navegador — sem servidor necessário.

## Desenvolvimento

```bash
# Clonar
git clone https://github.com/seu-usuario/myndex-site.git
cd myndex-site

# Abrir no VS Code
code .
```

## Contato
myndexdigital@gmail.com
