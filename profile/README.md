# Mobo

> Automatização de colheita de safra de lichia através de um braço mecânico utilizando tecnologias de IoT e Inteligência Artificial.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![License](https://img.shields.io/badge/license-MIT-green)
![Node.js](https://img.shields.io/badge/Node.js-backend-339933?logo=node.js)
![TypeScript](https://img.shields.io/badge/TypeScript-linguagem-3178C6?logo=typescript)
![Express](https://img.shields.io/badge/Express-API-000000?logo=express)
![Swagger](https://img.shields.io/badge/Swagger-OpenAPI%203.0-85EA2D?logo=swagger&logoColor=black)
![Vitest](https://img.shields.io/badge/Vitest-testes-6E9F18?logo=vitest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-container-2496ED?logo=docker&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-web-000000?logo=nextdotjs)
![React Native](https://img.shields.io/badge/React%20Native-mobile-61DAFB?logo=react)
![Expo](https://img.shields.io/badge/Expo-mobile-000020?logo=expo)
![Arduino](https://img.shields.io/badge/Arduino-hardware-00979D?logo=arduino)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb)
![Render](https://img.shields.io/badge/Render-Deploy-46E3B7?logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-Deploy-000000?logo=vercel&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-Storage-3448C5?logo=cloudinary&logoColor=white)

---

## 📋 Sobre o Projeto

O **Projeto Mobo** é uma solução multiplataforma para a colheita automatizada de lichia, integrando **IoT** e **Inteligência Artificial**. O sistema combinará visão computacional baseada em **redes neurais convolucionais**, sensoriamento remoto via IoT e automação robótica aplicada especificamente à cultura da lichia — fruta delicada que exige cuidados especiais durante a colheita.

O protótipo é composto por um **braço mecânico fabricado em impressora 3D** com pinça automatizada controlada por Arduino e aplicação multiplataforma para gestão e visualização dos dados.

> 📊 **Pesquisa de campo com 4 produtores do Vale do Ribeira (SP)** revelou perdas médias de **17,4%** da produção na colheita manual — equivalentes a mais de **R$ 32.000,00** de prejuízo entre os produtores pesquisados nas regiões de Jacupiranga, Eldorado e Iguape.

O projeto se alinha aos seguintes **Objetivos de Desenvolvimento Sustentável (ODS)**:

| ODS | Descrição |
|-----|-----------|
| 🌾 ODS 2 | Fome Zero e Agricultura Sustentável |
| 🏭 ODS 9 | Indústria, Inovação e Infraestrutura |
| ♻️ ODS 12 | Consumo e Produção Responsáveis |

---

## 📦 Repositórios

O Projeto Mobo é dividido em diferentes repositórios, cada um responsável por um dos módulos principais do sistema.

| Repositório                                                     | Descrição                                                                                           |
| --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ⚙ [.github](https://github.com/CW-Mobo/.github) | Configurações compartilhadas do GitHub, templates de Issues e Pull Requests, workflows e demais recursos de organização do projeto |
| 🔧 [API](https://github.com/CW-Mobo/backend)   | API REST, autenticação, regras de negócio e integração com o banco de dados                         |
| 🌐 [Web](https://github.com/CW-Mobo/web)           | Aplicação web, dashboard e gerenciamento do sistema                                                 |
| 📱 [Mobile](https://github.com/CW-Mobo/mobile)     | Aplicativo mobile para controle e interação com o braço mecânico                                    |
| 🤖 [Firmware](https://github.com/CW-Mobo/firmware) | Firmware do ESP e controle dos componentes do braço mecânico                                        |
| 🧠 [IA](https://github.com/CW-Mobo/ai)             | Modelos de Inteligência Artificial e visão computacional para reconhecimento da maturação da lichia |

> Cada repositório possui seu próprio README com instruções específicas de instalação, configuração e execução.

---

## ✨ Funcionalidades

- 🤖 **Braço Mecânico Automatizado** — colheita controlada remotamente com câmera integrada
- 🧠 **IA para Reconhecimento de Maturação** — modelo treinado para identificar o estágio ideal de colheita
- 📡 **Monitoramento IoT** — sensores de temperatura, umidade do ar e umidade do solo em tempo real
- 📊 **Dashboard Analytics** — visualização de gráficos e indicadores de qualidade e quantidade da colheita
- 📅 **Previsão de Colheita** — estimativa baseada em dados dos sensores e condições climáticas
- 📝 **Relatórios Gerenciais** — geração e exportação de relatórios por período, campo e qualidade
- 🗺️ **Mapa de Sensores** — localização geográfica dos sensores e braços mecânicos
- 👤 **Gestão de Usuários** — perfis de Administrador e Agricultor com permissões distintas
- 📱 **Aplicativo Mobile** — versão mobile com todas as funcionalidades principais e controle da garra mecânica

---

## 🛠️ Tecnologias Utilizadas

### Backend
- [Node.js](https://nodejs.org/) + [TypeScript](https://www.typescriptlang.org/) — plataforma e tipagem estática
- [Express](https://expressjs.com/) — framework para APIs RESTful
- [Mongoose](https://mongoosejs.com/) — ODM para MongoDB
- [MongoDB Atlas](https://www.mongodb.com/atlas) — banco de dados NoSQL na nuvem
- [JWT](https://jwt.io/) — autenticação via tokens
- [Swagger / OpenAPI](https://swagger.io/) — documentação e exploração interativa da API
- [Vitest](https://vitest.dev/) — testes automatizados e cobertura de código
- [Docker](https://www.docker.com/) — containerização e padronização do ambiente de execução
- [Render](https://render.com/) — hospedagem do backend
- [Cloudinary](https://cloudinary.com/) — armazenamento e gerenciamento de imagens

### Web
- [Next.js](https://nextjs.org/) + [TypeScript](https://www.typescriptlang.org/) — framework React com SSR/SSG
- [Vercel](https://vercel.com/) — hospedagem do frontend

### Mobile
- [React Native](https://reactnative.dev/) + [Expo](https://expo.dev/) + [TypeScript](https://www.typescriptlang.org/) — app multiplataforma (iOS e Android)

### Design
- [Figma](https://www.figma.com/design/xTZIWXjrK5TRtYm3Csh8h8/Mobo---UI?node-id=1-6998&t=Y23Z0Rf7ffm81J15-1) — prototipação e design de interfaces

### Inteligência Artificial 
- **Redes Neurais Convolucionais (CNN)** — classificação do estágio de maturação da lichia
- **Transfer Learning** — arquitetura pré-treinada com ajuste fino para a tarefa específica
- **Data Augmentation** — técnica para aumentar a robustez do modelo em variações de iluminação e ângulo
- Meta de acurácia mínima: **85%**

### Hardware
- [Arduino](https://www.arduino.cc/) — controle e movimentação do braço mecânico
- **Impressora 3D** — fabricação do protótipo físico do braço com pinça automatizada
- **Servomotores** — movimentação dos eixos com precisão para aproximação e posicionamento
- **Sensores IoT** — temperatura, umidade do solo e umidade do ar *(não implementado)*

### Banco de Dados
- **MongoDB Atlas** — armazenamento principal (dados de IoT, colheitas, usuários)

### Ferramentas & Metodologia
- **Scrum** — metodologia ágil com Sprints iterativos
- [LucidChart](https://www.lucidchart.com/) — fluxogramas
- [Draw.io](https://www.drawio.com/) — diagramas UML, modelagem conceitual e lógica do banco de dados

---

## 🏗️ Arquitetura do Sistema

```
┌──────────────────────────────────────────────────────────────┐
│                        APLICAÇÃO MOBO                        │
├──────────────────┬──────────────────┬────────────────────────┤
│    Frontend      │     Backend      │    Hardware / IoT      │
│                  │                  │                        │
│  React (Web) +   │  Node.js +       │  Sensores IoT          │
│     Vercel       │  TypeScript      │  (temp, umidade)       │
│                  │  APIs RESTful    │                        │
│  React Native    │                  │  Braço Mecânico 3D     │
│  (Mobile / TS)   │  MongoDB Atlas   │  (Arduino + Servos)    │
│                  │ (nuvem / Render) │                        │
│  Figma (UX)      │  + Cloudinary    │  CNN / Visão Comp.     │
│                  │                  │  (maturação da lichia) │
└──────────────────┴──────────────────┴────────────────────────┘
```

---

## 👥 Equipe

| Nome | Função | GitHub |
|------|--------|--------|
| Bárbara Vitória Ferreira dos Santos | Frontend & UI/UX e Mobile | [@babi-s4ntos](https://github.com/babi-s4ntos) |
| Lucas de Lima Santana | IoT / IA / Mobile | [@LucasLiSan](https://github.com/LucasLiSan) |
| Pedro Henrique Venâncio | Backend & DevOps / Front | [@phvenancio](https://github.com/phvenancio) |

---

## 📊 Estado Atual do Desenvolvimento

- [x] Pesquisa de campo com produtores do Vale do Ribeira
- [x] Protótipo das interfaces (Web e Mobile)
- [x] CRUD completo via API RESTful (Node.js + TypeScript)
- [x] Integração com MongoDB Atlas
- [x] Dashboard com gráficos e tabelas
- [x] Modelagem conceitual e lógica do banco de dados
- [x] Diagramas UML (Classe, Objeto, Caso de Uso, Fluxograma)
- [x] Protótipo físico do braço mecânico (impresso em 3D + Arduino)
- [x] Testes iniciais de movimentação em ambiente controlado
- [x] Modelo de IA (CNN) para reconhecimento do estágio de maturação *(próximo semestre)*
- [x] Coleta do dataset de imagens de lichia em campo
- [ ] Integração completa IoT + visão computacional + braço mecânico
- [ ] Versão acessível para pequenos produtores

---

## 🔭 Trabalhos Futuros

- Aprimorar Mobile, integrando ele a API
- Correção de Bugs
- Integrar Web e IA
- Integrar Mobile e Garra
- Reconhecimento de Maturação diretamente pela câmera

---

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🎓 Instituição

Desenvolvido na **Faculdade de Tecnologia (FATEC) — Campus Registro**
Curso: Desenvolvimento de Software Multiplataforma
Ministério da Educação — 2026

---

<p align="center">
  Feito com ❤ pela equipe Mobo
</p>
