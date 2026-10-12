# 🔥 Herói das Chamas — Resgate Imediato (Casa Virtual)

> Um jogo interativo de aventura e escolhas baseado em texto, construído puramente com **fundamentos de HTML5** e navegação por hiperlinks.

---

## 📖 Sobre o Projeto

O **Herói das Chamas** é um projeto prático desenvolvido como parte do módulo de **Fundamentos de HTML** da Formação Front-end. 

O jogador assume o papel de um bombeiro em uma corrida contra o tempo: uma casa está tomada pelas chamas e um gatinho está preso em algum cômodo! O objetivo é explorar os ambientes da casa, tomar decisões em cada bifurcação e resgatar o felino em segurança.

---

## 🎮 Como Funciona o Jogo

A dinâmica segue o estilo clássico de *text adventure* / *livro-jogo*:
1. **Ponto de Partida (`index.html`)**: Você chega à rua em frente à residência em chamas e escolhe por onde iniciar a invasão (porta da frente ou janela).
2. **Navegação pelos Cômodos**: Cada decisão leva a uma página HTML dedicada representando um cômodo da casa (Sala, Corredores, Quartos, Cozinha, Banheiro).
3. **Decisões e Rotas**: Em cada cômodo, links hipertexto (`<a>`) apresentam caminhos possíveis e desafios.
4. **Resgate e Vitória**: Ao alcançar o cômodo correto, a missão é cumprida com sucesso e o jogador pode reiniciar a partida.

---

## 🗺️ Mapa dos Cômodos e Estrutura

- 📍 **Rua (Início)**: Ponto de entrada (`index.html`)
- 📍 **Sala**: Acesso principal para o corredor e o segundo quarto (`comudos/sala.html`)
- 📍 **Corredor**: Ligação intermediária entre a sala e a cozinha (`comudos/corredor.html`)
- 📍 **Cozinha**: Área crítica conectada ao banheiro e ao quarto principal (`comudos/cozinha.html`)
- 📍 **Banheiro**: Cômodo sem saída com alta concentração de fumaça (`comudos/banheiro.html`)
- 📍 **Quarto 2**: Entrada alternativa via janela (`comudos/quato-2.html`)
- 🏆 **Quarto 1 (Objetivo)**: Local onde o gatinho é encontrado e resgatado (`comudos/quarto-1.html`)

---

## 🛠️ Conceitos Praticados

- **Estruturação Semântica HTML5**: Uso de tags semânticas e estruturais (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<h1>`, `<h2>`, `<h3>`, `<p>`, `<b>`).
- **Navegação por Hiperlinks (`<a>`)**: Prática intensiva de caminhos relativos (`./`, `../`, subpastas) para navegação fluida entre páginas estáticas.
- **Mídia e Imagens (`<img>`)**: Inclusão de imagens representativas para cada cenário com atributos de dimensão e acessibilidade (`alt`).
- **Listas Não-Ordenadas (`<ul>`, `<li>`)**: Estruturação dos menus de escolha do jogador.
- **Metatags e SEO Básico**: Configuração de `charset`, `viewport`, `title`, `author`, `description` e favicon.

---

## 📁 Estrutura de Arquivos

```plaintext
Desafio-HTML/
├── asset/                 # Imagens dos cômodos e elementos visuais
│   ├── banheiro.png
│   ├── corredor.png
│   ├── cozinha.png
│   ├── logo.png
│   ├── quarto1.png
│   ├── quarto2.png
│   ├── rua.png
│   └── sala.png
├── comudos/               # Páginas HTML de cada cômodo da casa
│   ├── banheiro.html
│   ├── corredor.html
│   ├── cozinha.html
│   ├── quarto-1.html      # Tela de vitória / resgate
│   ├── quato-2.html
│   └── sala.html
├── referencia/            # Imagens de referência do desafio
│   └── desafio.png
├── index.html             # Página inicial do jogo
└── README.md              # Documentação do projeto
```

---

## 🚀 Como Executar

Por ser um projeto web puramente estático em HTML, não requer instalação de dependências ou build:

1. Clone o repositório:
   ```bash
   git clone https://github.com/nivano-studio/Desafio-HTML---casa-virtual.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd Desafio-HTML---casa-virtual
   ```
3. Abra o arquivo `index.html` em qualquer navegador web (Chrome, Firefox, Edge, Safari) ou utilize a extensão **Live Server** no VS Code.

---

## 👤 Autor

Desenvolvido por **José Roberto Barbosa Pessoa**  
Projeto de estudos — *Formação Front-end / Fundamentos de HTML*
