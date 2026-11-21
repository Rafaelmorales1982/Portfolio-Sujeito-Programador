# Portfólio — Sujeito Programador

Página de portfólio pessoal desenvolvida com HTML5 e CSS3 puro, criada durante o curso **Sujeito Programador**. O projeto apresenta uma landing page de página única (one-page), com navegação por âncoras, seções de apresentação, sobre e projetos, além de layout responsivo.

![Preview do projeto](./img/programador.png)

## 📋 Sobre o projeto

O site simula o portfólio de um desenvolvedor, com o objetivo de praticar conceitos fundamentais de estruturação HTML e estilização CSS: flexbox, posicionamento, pseudo-classes, transições, responsividade com media queries e uso de fontes externas.

Todo o conteúdo é estático — não há JavaScript nem dependências de build. Basta abrir o `index.html` no navegador.

## ✨ Funcionalidades

- **Header fixo (sticky)** com menu de navegação por âncoras para as seções Home, Sobre e Projetos
- **Seção Home (hero)** em tela cheia, com imagem de fundo, chamada principal e botão de atalho para os projetos
- **Seção Sobre** com texto descritivo e imagem ilustrativa
- **Seção de Projetos** com galeria de imagens em duas linhas e efeito de opacidade no hover
- **Botão "Faça um orçamento"** com destaque visual no hover
- **Botão flutuante "Topo"** fixo no canto da tela para retornar ao início
- **Rolagem suave** entre as seções (`scroll-behavior: smooth`)
- **Layout responsivo** para telas de até 1050px (menu, hero, seção sobre e rodapé se adaptam)
- **Rodapé** com nome do autor e direitos reservados

## 🛠️ Tecnologias utilizadas

| Tecnologia | Uso |
| --- | --- |
| HTML5 | Estrutura e conteúdo da página |
| CSS3 | Estilização, layout com Flexbox, transições e responsividade |
| Google Fonts (Roboto) | Tipografia do site |

Nenhuma biblioteca, framework ou ferramenta de build é necessária.

## 📁 Estrutura do projeto

```
Projeto-portfolio/
├── index.html          # Página principal (única página do site)
├── css/
│   └── style.css       # Todos os estilos, incluindo media queries
├── img/
│   ├── programador.png # Imagem de fundo da seção Home
│   ├── foto-pc.png     # Imagem da seção Sobre
│   ├── projeto1.png    # Imagem de projeto
│   ├── projeto2.png    # Imagem de projeto
│   └── projeto3.png    # Imagem de projeto
└── README.md
```

## 🚀 Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/Rafaelmorales1982/Portfolio-Sujeito-Programador.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd Portfolio-Sujeito-Programador
   ```

3. Abra o arquivo `index.html` no navegador — basta dar um duplo clique nele ou arrastá-lo para uma aba do navegador.

> Opcional: para servir via servidor local, use a extensão **Live Server** do VS Code ou execute `npx serve` na raiz do projeto.

## 🎨 Detalhes de estilo

- **Paleta de cores:** preto (`#000`), grafite (`#181818`), azul (`#1e96fc`), branco (`#fff`) e cinza (`#aaa` / `#ddd`)
- **Fonte:** Roboto (Google Fonts), com variações de peso e itálico
- **Breakpoint:** `max-width: 1050px`, onde a seção Sobre passa para layout em coluna, o rodapé é empilhado e os tamanhos de fonte/imagens são ajustados
- **Animações:** transições em botões (escala e troca de cor) e nas imagens da galeria (opacidade)

## 🔗 Navegação por âncoras

| Link | Destino |
| --- | --- |
| `#home` | Seção inicial (hero) |
| `#sobre` | Seção Sobre |
| `#projetos` | Seção de Projetos |

## 💡 Possíveis melhorias futuras

- Substituir os textos *Lorem ipsum* por conteúdo real
- Adicionar links reais para os projetos e redes sociais
- Incluir menu hambúrguer para telas menores (mobile)
- Criar uma seção de contato com formulário
- Melhorar a acessibilidade (foco visível, contraste e textos alternativos mais descritivos)
- Adicionar animações de entrada nas seções com JavaScript ou CSS

## 👤 Autor

**Rafael Morales**

- GitHub: [@Rafaelmorales1982](https://github.com/Rafaelmorales1982)

## 📄 Licença

Projeto desenvolvido para fins de estudo. Todos os direitos reservados © Rafael Morales.
