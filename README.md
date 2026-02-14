# 🍎 Fruit Run!


## 🎮 Sobre o Projeto

**Fruit Run** é um jogo de plataforma desenvolvido como projeto prático para a disciplina de **Jogos Digitais** no Ensino Médio. O jogo desafia o usuário a desviar de obstáculos e coletar itens (moedas) em um ambiente de progressão contínua.

Este projeto marca o início da minha jornada no desenvolvimento de software, onde explorei pela primeira vez a lógica de programação visual e a publicação de aplicações web.

## 🕹️ Como Jogar
- **Pular:** ⬆️ Seta para cima.
- **Reiniciar:** Tecla **R**.

## 🛠️ Tecnologias e Arquitetura
O jogo foi desenvolvido no **Construct 3** e exportado como uma aplicação **HTML5/PWA**, o que permite rodar diretamente no navegador.

- **Engine:** Construct 3.
- **Lógica:** Event Sheets (Folha de Eventos) com foco em comportamentos de física e colisão.
- **Web Tech:** O projeto utiliza um `Service Worker` (`sw.js`) e um `manifest.json`, permitindo que o jogo seja instalado como um Aplicativo Web Progressivo (PWA).
- **Hospedagem:** Netlify, com integração contínua (CI/CD) via este repositório no GitHub.

## 📁 Estrutura do Repositório
* `/images`: Sprites e elementos gráficos do jogo.
* `/media`: Efeitos sonoros e trilha sonora.
* `scripts/`: Arquivos JavaScript responsáveis pela engine e lógica do jogo.
* `index.html`: Ponto de entrada da aplicação web.

## 🚀 Onde Jogar
## **Deploy:** [Acesse o Jogo no Netlify](https://fruit-run.netlify.app/)