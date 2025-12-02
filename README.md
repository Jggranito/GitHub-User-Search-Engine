# 🔍 GitHub User Search Engine

![Project Preview](./src/screenshot/desktop_1.png)

> **Uma aplicação web performática para busca e análise de perfis de desenvolvedores utilizando a API pública do GitHub.**

## 📖 Sobre o Projeto
Este projeto foi desenvolvido para consolidar conhecimentos avançados em **JavaScript Vanilla (ES6+)**. O objetivo foi criar uma interface limpa e responsiva que consome dados reais, trata requisições assíncronas e manipula o DOM dinamicamente para exibir métricas detalhadas de usuários e repositórios.

Diferente de buscas simples, esta ferramenta foca em trazer uma "radiografia" da atividade recente do desenvolvedor, filtrando eventos específicos como Pushes e Criação de Repositórios.

## 🚀 Funcionalidades

- **Busca de Perfil Completa:** Exibição de Avatar, Bio, Localização e métricas sociais (Seguidores/Seguindo).
- **Análise de Repositórios:** Listagem dos principais repositórios com indicadores de qualidade:
  - ⭐ Stars (Estrelas)
  - 🍴 Forks
  - 👁️ Watchers
  - 💻 Linguagem predominante
- **Monitoramento de Atividades:** Feed dinâmico mostrando os últimos 10 eventos relevantes (Commits/Pushs e Criação de Repos).
- **Tratamento de Erros:** Feedback visual amigável caso o usuário não seja encontrado.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído sem frameworks, focando na pureza e performance do código:

- **Core:** HTML5 Semântico, CSS3 (Flexbox/Grid & Custom Properties).
- **Lógica:** JavaScript (ES6+).
- **Integração:** Fetch API & Async/Await para consumo de dados.
- **Arquitetura:** Manipulação direta do DOM e Modularização de código.

## 📱 Layout

O projeto é totalmente responsivo, adaptando-se a dispositivos móveis e desktops.

| Desktop View | Mobile View |
| :---: | :---: |
| ![Desktop](./src/screenshot/desktop_2.png) | ![Mobile](./src/screenshot/mobile_1.png) |

## 💡 Aprendizados e Desafios
Durante o desenvolvimento, os principais desafios técnicos superados foram:
1. **Orquestração de Chamadas Assíncronas:** Encadeamento de múltiplas requisições (Dados do User -> Repositórios -> Eventos) garantindo performance.
2. **Filtros de Eventos:** Lógica para limpar o JSON de retorno da API e exibir apenas eventos relevantes (PushEvent e CreateEvent).
3. **Validação de Dados:** Tratamento de campos nulos ou inexistentes na API para evitar quebras na UI.

## 🔗 Links

- **Repositório:** [Acesse o Código](https://github.com/Jggranito/Github-User-Search-Engine)
- **Live Preview:** [Ver Projeto Online](https://jggranito.github.io/Github-User-Search-Engine/)

---

Desenvolvido por **[João Gabriel Granito](https://www.linkedin.com/in/jo%C3%A3o-gabriel-granito-77666a262/)**
*Focado em Desenvolvimento Front-End e Mobile*
