# Ralky-Tech

## Desenvolvimento de Software e Soluções Digitais

A **Ralky-Tech** é uma iniciativa acadêmica criada por estudantes do curso de **Desenvolvimento de Software Multiplataforma da FATEC Registro**, com o objetivo de aplicar, de forma prática, conhecimentos relacionados ao desenvolvimento de software e à criação de soluções digitais.

Esta organização reúne os repositórios desenvolvidos pela equipe para o projeto **Reveste Kids**, permitindo o acesso ao código-fonte, à documentação e ao histórico de desenvolvimento do projeto.

---

## Reveste Kids

O **Reveste Kids** é uma plataforma digital desenvolvida para facilitar a troca de roupas infantis entre usuários, incentivando a reutilização de peças e os princípios da economia circular.

A aplicação permite o cadastro de roupas, a visualização de peças disponibilizadas por outros usuários e a interação entre pessoas interessadas em realizar trocas.

### Principais funcionalidades

- Cadastro e autenticação tradicional com JWT
- Login com Google no frontend web
- Cadastro de roupas com imagens e vídeos
- Feed interativo inspirado no TikTok
- Curtidas, interesses e matches
- Chat e notificações em tempo real
- Busca de closets, pesquisa de peças e filtros
- Tema claro e escuro
- Interface web responsiva
- Aplicativo mobile desenvolvido com React Native, Expo e TypeScript

---

## Repositórios

### Reveste Kids

Aplicação principal do projeto, contendo o desenvolvimento da plataforma.

[Repositório Reveste Kids](https://github.com/Ralky-Tech/reveste_kids)

[Acesso Site Reveste Kids](https://reveste-kids-sepia.vercel.app/)

### Ralky-Tech

Landing page institucional desenvolvida para apresentação da iniciativa acadêmica e do projeto Reveste Kids.

[Repositório Ralky-Tech](https://github.com/Ralky-Tech/ralkytech)

[Acesso Landing Page](https://ralkytech.vercel.app/)


---

## Tecnologias utilizadas

| Camada / finalidade | Tecnologias / serviços |
| --- | --- |
| Frontend web | React, Vite e React Router; JavaScript, HTML e CSS |
| Mobile | React Native, Expo, Expo Router e TypeScript |
| Backend | Node.js, Express e Mongoose |
| Autenticação | JWT e Google OAuth 2.0 com validação de ID Token no login Google do frontend web |
| Banco de dados | MongoDB Atlas |
| Armazenamento de mídia | Cloudinary (imagens e vídeos) |
| Comunicação em tempo real | Socket.IO |
| Documentação da API | Swagger / OpenAPI |
| Hospedagem | Vercel (frontend web) e Render (API backend) |
| Desenvolvimento local | Docker e Docker Compose |
| Integração contínua | GitHub Actions para testes, lint, build e validações Docker |
| Qualidade | ESLint, Husky e testes automatizados |
| Desenvolvimento e versionamento | Git, GitHub e Visual Studio Code |

---

## Arquitetura

O projeto foi desenvolvido utilizando uma arquitetura com separação entre frontend web, aplicativo mobile, API backend e banco de dados.

O **frontend web**, desenvolvido com React e Vite, é hospedado na **Vercel**. O **aplicativo mobile** é desenvolvido com React Native, Expo e TypeScript. Ambos consomem a **API backend**, desenvolvida com Node.js e Express e hospedada no **Render**, que disponibiliza os serviços e as regras de negócio.

O **MongoDB Atlas** é utilizado para persistência dos dados da aplicação, enquanto o **Cloudinary** armazena as imagens e os vídeos das peças.

Para funcionalidades de comunicação em tempo real, como o chat e as notificações, a aplicação utiliza **Socket.IO**.

No ambiente local, **Docker Compose** executa o frontend web e o backend. O MongoDB Atlas e o Cloudinary permanecem como serviços externos, e o aplicativo Expo é executado separadamente.

O **GitHub Actions** executa as verificações de integração contínua, incluindo testes, lint, build e validações Docker, sem realizar deploy automático.

---

## Objetivo Acadêmico

O projeto **Reveste Kids** foi desenvolvido como parte das atividades acadêmicas do curso de **Desenvolvimento de Software Multiplataforma da FATEC Registro**.

O desenvolvimento busca aplicar, de forma integrada, conhecimentos relacionados a desenvolvimento web, APIs, banco de dados, experiência do usuário, versionamento de código, implantação de aplicações e trabalho colaborativo.

Os repositórios desta organização disponibilizam o código-fonte e o histórico de desenvolvimento utilizados para acompanhamento e avaliação acadêmica do projeto.

---

## Equipe

O projeto foi desenvolvido pela equipe **Ralky-Tech**, composta pelos seguintes integrantes:

- Camila Machado de Souza
- Felipe Cunha Guedes
- Kaio Toshiyuki Pereira Sumikawa
- Ricardo Nobuo Sugano
- Rogerio Pupo Toledo

**Curso:** Desenvolvimento de Software Multiplataforma  
**Instituição:** FATEC Registro

---

## Projeto Acadêmico

Esta organização e os projetos nela disponibilizados possuem finalidade acadêmica e educacional.
