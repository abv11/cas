# Cigarettes After Sex - Website

Um site moderno e melancólico sobre a banda Cigarettes After Sex, com design P&B e tema escuro elegante.

## 📋 Estrutura do Projeto

- **index.html** - Página inicial
- **sobre.html** - Informações sobre a banda
- **discografia.html** - Álbuns e singles
- **contato.html** - Links para redes sociais
- **styles.css** - Estilos do site
- **script.js** - Funcionalidades JavaScript (menu hamburger, interações)

## 🖼️ Como Adicionar Imagens

O site foi preparado para receber imagens dos álbuns e singles. Siga os passos abaixo:

### Imagens dos Álbuns

Na página **discografia.html**, encontre as seções dos álbuns:

```html
<img src="URL_DA_IMAGEM" alt="Capa do álbum" />
```

Substitua `URL_DA_IMAGEM` por:
- URL completa: `https://exemplo.com/imagem.jpg`
- Caminho local: `imagens/cigarettes-after-sex.jpg`

### Imagens dos Singles

Na página **discografia.html**, encontre a seção de singles:

```html
<img src="" alt="Capa de Affection" class="single-image" />
```

Faça o mesmo procedimento acima.

### Imagem do Álbum na Página Inicial

Na página **index.html**, na seção "Álbum Mais Recente":

```html
<img src="" alt="Capa do álbum X's" />
```

## 🎨 Estrutura de Pastas Recomendada

```
cas/
├── index.html
├── sobre.html
├── discografia.html
├── contato.html
├── styles.css
├── script.js
└── imagens/
    ├── cigarettes-after-sex.jpg
    ├── cry.jpg
    ├── xs.jpg
    ├── affection.jpg
    ├── k.jpg
    └── ... (outros singles)
```

## 🌙 Design

- **Fundo:** Cinza escuro (#1a1a1a)
- **Cores primárias:** Preto e branco
- **Acentos:** Cinza (#2a2a2a, #3a3a3a)
- **Estilo:** Minimalista e melancólico

## 📱 Responsividade

O site é totalmente responsivo:
- Desktop: Layout completo com menu horizontal
- Tablet: Layout adaptado
- Mobile: Menu hamburger (3 barrinhas)

## 🧭 Navegação

Menu com links para:
- Início
- Sobre
- Discografia
- Contato (redes sociais)

## 🔧 Funcionalidades

- Menu hamburger funcional
- Transições suaves
- Efeitos hover elegantes
- Tema escuro ao longo de todo o site
- Suporte a imagens em capas de álbuns e singles

## 📝 Notas

Todas as seções com imagem possuem `src=""` vazio. Preencha com suas imagens conforme necessário.

As imagens podem ser em formatos: JPG, PNG, WebP, etc.

Tamanhos recomendados:
- Álbuns: 200x200px mínimo
- Singles: 150x150px mínimo
