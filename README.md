# Trampar de Casa 👨💻🏠

> Conexão definitiva entre desenvolvedores brasileiros e oportunidades de trabalho remoto.

---

## Sobre o Projeto 🎯 
O Trampar de Casa é uma iniciativa open-source dedicada a conectar desenvolvedores brasileiros a oportunidades de trabalho remoto, incentivando a inclusão, diversidade e quebrando barreiras geográficas.  

Semanalmente, compartilhamos um boletim via e-mail, contendo vagas selecionadas que correspondem ao perfil de nossos inscritos.

---

## 🚧 Funcionalidades em Desenvolvimento 🚧

Estamos trabalhando para implementar novas funcionalidades que vão tornar o Trampar de Casa ainda melhor. Aqui estão algumas que estão em nosso roadmap:

[ ] **Cron Job para Envio de Emails**: Implementação de um Cron Job que enviará emails semanalmente (quarta-feira 11:00) para nossos usuários com as melhores oportunidades de trabalho remoto. 

Pretendemos usar a combinação de Vercel (conforme este [guia](https://vercel.com/guides/how-to-setup-cron-jobs-on-vercel)), react.email para construção dos emails e Supabase para o banco de dados.

[ ] **Formulário de Cadastro para Empresas**: Desenvolvimento de um formulário de cadastro de empresas para tornar o processo de postagem de vagas mais eficiente. As empresas poderão preencher seus dados, como nome, site e link do logo.

[ ] **Login de Usuários**: Adição de um sistema de login para usuários utilizando a plataforma Clerk para tornar a busca por empregos remotos ainda mais eficiente.

---

## Como Contribuir 🚀

1. **Fork** do repositório.
2. **Clone** do fork em seu ambiente de desenvolvimento local.
3. **Criação** de uma nova branch para sua funcionalidade ou correção.
4. **Implementação** de suas alterações e adição de testes, se aplicável.
5. **Push** para a sua branch no seu fork.
6. Envio de um **Pull Request** para o repositório principal.

---

## Rodando o Projeto via Docker


Aqui estão alguns comandos úteis que podem ser utilizados em ambientes linux:

  ```
  make run-build
  ```
  Esse comando inicia os contêineres definidos no arquivo docker-compose.yml, reconstruindo as imagens se necessário.

  ```
  make run
  ```
  Esse comando inicia os contêineres definidos no arquivo docker-compose.yml.

---

## Contribuidores ✨
Qualquer contribuição é bem-vinda!

[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
