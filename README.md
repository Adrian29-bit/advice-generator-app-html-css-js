# Advice Generator App

Este projeto é um app simples de geração de conselhos, baseado em um desafio do [Frontend Mentor](https://www.frontendmentor.io/). Ele consome dados da API pública [Advice Slip JSON API](https://api.adviceslip.com/), que retorna frases motivacionais ou conselhos aleatórios.

## 🖼️ Visão geral

A aplicação mostra um conselho aleatório na tela e permite que o usuário atualize esse conselho ao clicar no botão de dado.

## 🔧 Tecnologias utilizadas

- **HTML5** – Estrutura da aplicação
- **CSS3** – Estilização responsiva com `@media` e flexbox
- **JavaScript (ES6+)** – Requisição de API e manipulação do DOM
- **Google Fonts** – Tipografia personalizada com a fonte *Manrope*

## 📁 Estrutura de pastas

```

├── index.html
├── src/
│   ├── css/
│   │   ├── reset.css
│   │   └── style.css
│   ├── js/
│   │   └── index.js
│   └── images/
│       ├── icon-dice.svg
│       ├── pattern-divider-desktop.svg
│       └── pattern-divider-mobile.svg

```

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/Adrian29-bit/advice-generator-app-html-css-js.git]

2. Acesse a pasta do projeto:

   ```bash
   cd advice-generator-app
   ```
3. Abra o arquivo `index.html` no seu navegador de preferência.

> Nenhuma instalação de dependências é necessária.

## 🧠 Funcionalidade principal

* Geração automática de um conselho ao carregar a página.
* Geração manual ao clicar no botão de dado (`advice-update`).
* Requisição assíncrona com `fetch()` à [API de conselhos](https://api.adviceslip.com/advice).

## 📌 Layout responsivo

O layout se adapta a diferentes larguras de tela. Utiliza imagens diferentes para divisores (desktop e mobile) via `<picture>` e media queries no CSS.

## 🧪 Melhorias possíveis

* Adicionar estados de loading e erro mais visíveis.
* Criar um histórico de conselhos gerados.
* Compartilhar conselhos em redes sociais.

## 📝 Licença

Este projeto foi desenvolvido como prática. Sinta-se livre para usá-lo, modificar ou sugerir melhorias!

---

Feito com 💡 por Adrian Mindelo
