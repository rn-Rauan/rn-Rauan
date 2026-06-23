# 👋 Olá, eu sou Rauan dos Santos Bandeira

**Desenvolvedor Backend Júnior** em formação em **Análise e Desenvolvimento de Sistemas** pelo IFPI.
Tenho foco em **TypeScript, Node.js, NestJS, PostgreSQL e APIs REST**, com interesse em arquitetura de software, SaaS, testes automatizados e desenvolvimento de produtos digitais.

Atualmente estou desenvolvendo o **Movy**, um sistema SaaS multi-tenant para gestão e reserva de viagens de transporte universitário/intermunicipal, composto por **backend/API** e **cliente web mobile-first**.

---

## Sobre mim

Sou desenvolvedor júnior com experiência prática em projetos acadêmicos e aplicados, envolvendo backend, frontend, mobile, IA generativa e sistemas web.

Tenho trabalhado principalmente com:

* Desenvolvimento de APIs REST com Node.js, NestJS e Fastify
* Modelagem de banco de dados com PostgreSQL e Prisma ORM
* Clean Architecture, DDD, SOLID e separação por camadas
* Autenticação, autorização, JWT, RBAC e multi-tenancy
* Testes automatizados com Jest e Supertest
* Documentação de APIs com Swagger/OpenAPI
* Desenvolvimento frontend com React, TypeScript e arquitetura modular
* Integração entre frontend e backend
* Desenvolvimento assistido por IA com Claude Code, Lovable e Claude Design

---

## Stack principal

### Backend

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge\&logo=typescript\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge\&logo=nestjs\&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge\&logo=fastify\&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge\&logo=prisma\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge\&logo=postgresql\&logoColor=white)

### Frontend e Mobile

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge\&logo=expo\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?style=for-the-badge\&logo=react-query\&logoColor=white)

### Qualidade, ferramentas e práticas

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge\&logo=jest\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger/OpenAPI-85EA2D?style=for-the-badge\&logo=swagger\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge\&logo=cloudflare\&logoColor=white)

---

## Projetos em destaque

### 🚍 Movy

**Sistema SaaS multi-tenant para gestão e reserva de viagens de transporte universitário/intermunicipal**
Projeto em fase final de desenvolvimento como TCC.

O Movy é um sistema completo para organizações que gerenciam transporte universitário/intermunicipal, incluindo passageiros, motoristas, administradores, veículos, viagens, reservas, pagamentos, planos e assinaturas.

O sistema é composto por:

* **Backend/API:** desenvolvido com NestJS, TypeScript, Prisma e PostgreSQL
* **Cliente Web:** Mobile-first desenvolvido com React, TypeScript, TanStack Start, TanStack Router, Tailwind CSS e shadcn/ui
* **Integração frontend/backend:** consumo da API, autenticação, controle de acesso e fluxos separados por perfil de usuário

#### Backend/API

Principais pontos técnicos:

* API REST com NestJS, TypeScript, Prisma e PostgreSQL
* Arquitetura baseada em Clean Architecture e DDD
* Autenticação com JWT, refresh token, bcrypt e recuperação de senha
* Controle de acesso com RBAC e isolamento multi-tenant por organização
* Regras de negócio para viagens, reservas, pagamentos, assinaturas e limites por plano
* Testes automatizados com Jest e Supertest
* Documentação com Swagger/OpenAPI
* Ambiente com Docker e docker-compose

#### Cliente Web

Principais pontos técnicos:

* PWA mobile-first com React 19 e TypeScript em modo strict
* Roteamento com TanStack Start e TanStack Router
* Interface com Tailwind CSS v4 e shadcn/ui
* Validação com Zod
* Estrutura baseada em feature modules
* Rotas como thin controllers e lógica concentrada em hooks de feature
* Camada de services para chamadas à API, seguindo repository pattern
* Controle de acesso por papéis: passageiro, motorista e admin
* Guards por rotas públicas, autenticadas, administrativas e de motorista
* Renovação automática de token no cliente HTTP
* Deploy preparado para Cloudflare Workers via Wrangler

#### Desenvolvimento assistido por IA

O cliente web do Movy foi desenvolvido com apoio de ferramentas modernas de desenvolvimento assistido por IA, incluindo:

* Claude Code
* Lovable
* Claude Design

Essas ferramentas foram utilizadas para acelerar prototipação, implementação de interface, organização de padrões e refinamento da integração com a API.

**Stack:** NestJS · TypeScript · Prisma · PostgreSQL · JWT · Jest · Docker · Swagger · React · TanStack Start · TanStack Router · Tailwind CSS · shadcn/ui · Cloudflare Workers

🔗 [API](https://github.com/rn-Rauan/movy-api)
🔗 [Cliente](https://github.com/rn-Rauan/movy_web)

---

### 🤖 PedagogIA — Sistema de Apoio Docente com IA

Aplicação criada para auxiliar professores na geração automatizada de materiais didáticos, como planos de aula, atividades e slides.

O projeto utiliza IA generativa e RAG para recuperar informações da BNCC e diretrizes educacionais como contexto antes da geração dos materiais.

Principais pontos técnicos:

* Backend com Node.js, TypeScript e Fastify
* Integração com LLMs
* Uso de RAG para recuperação de contexto educacional
* Geração de planos de aula, atividades e slides
* Projeto premiado com 2º lugar no Hackathon IFPI

**Stack:** TypeScript · React · Node.js · Fastify · Prisma · PostgreSQL · IA Generativa · RAG

🔗 [Repositório](https://github.com/rn-Rauan/AI-ASSISTANT-FOR-TEACHER.git)
🌐 [Aplicação](https://pedagoia.vercel.app/)

---

### 📱 Amim Doces e Salgados — Catálogo Mobile e API REST

Solução de catálogo digital desenvolvida para uma microempresa do ramo de panificação e confeitaria artesanal.

O projeto conta com aplicativo mobile e API REST para gerenciamento de produtos e apoio ao processo de pedidos.

Principais pontos técnicos:

* API REST com Node.js, TypeScript e Fastify
* Persistência com PostgreSQL e Prisma ORM
* Arquitetura baseada em Clean Architecture e DDD
* 137 testes unitários e de integração com Jest
* 80,57% de cobertura de código
* Deploy da API em AWS Lightsail
* Aplicativo mobile em teste fechado na Google Play
* Refatoração do frontend mobile para arquitetura MVVM
* Integração de checkout via WhatsApp

**Stack:** React Native · TypeScript · Node.js · Fastify · PostgreSQL · Prisma · Jest

🔗 [Repositório](https://github.com/MaYaOlly/CatalogoAmimMobile.git)

---

## Estudos e interesses atuais

Atualmente venho aprofundando meus estudos em:

* Arquitetura de software
* SaaS e sistemas multi-tenant
* Testes automatizados
* Segurança em APIs
* Desenvolvimento backend com NestJS
* Integração frontend/backend
* Desenvolvimento frontend com React e TanStack
* Desenvolvimento assistido por IA
* Modelagem de produtos digitais

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=rn-Rauan\&show_icons=true\&theme=tokyonight\&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rn-Rauan\&layout=compact\&theme=tokyonight\&hide_border=true)

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/rauan-bandeira-525a73322)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:rauanbandeira911@gmail.com)

---

> Construindo software com foco em clareza, organização e evolução contínua.
