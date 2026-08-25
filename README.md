# 🏋️ GRIP

### **Autores:** Leonardo Lopes Dzevenka

Este projeto tem como objetivo desenvolver progressivamente e de forma didática uma aplicação web voltada para o **registro e acompanhamento de treinos de musculação**.

O **GRIP** permite cadastrar exercícios, criar treinos, associar exercícios às rotinas e registrar informações de desempenho, como carga, repetições e séries.

O diferencial da aplicação é o acompanhamento da evolução do usuário por meio do histórico dos exercícios, identificando automaticamente **Recordes Pessoais (PRs)** quando uma nova carga supera a maior carga anteriormente registrada para determinado exercício.

O frontend da aplicação é desenvolvido com **HTML, CSS e JavaScript**, utilizando um framework CSS para construção de layouts responsivos. O backend é simulado por uma **API Fake utilizando JSON Server**.

## 📚 Documentação do Projeto

Para entender as regras de negócio, o escopo e a arquitetura técnica da aplicação, consulte os documentos abaixo:

* [📄 Product Requirements Document (PRD)](./architecture.md) - Visão geral, atores, histórias de usuário, escopo e requisitos do sistema.
* [🛠️ Especificação Técnica (Tech Spec)](./spec.md) - Diagrama de banco de dados (DER), dicionário de dados, regras de negócio, estrutura do `db.json` e rotas da API.

## 🎨 Design

* [🎨 Design System](./docs/design-system.md) - Identidade visual, cores, tipografia e padrões de componentes da aplicação.
* [🖼️ Protótipo no Figma](#) - Telas e protótipo interativo da aplicação.

## 🌐 Site em Produção - GitHub Pages

> Em desenvolvimento.

<!-- Quando o projeto estiver publicado, substituir pelo endereço:
https://SEU-USUARIO.github.io/grip/
-->

## 💻 Tecnologias e Dependências

* **HTML5** - Estrutura das páginas.
* **CSS3** - Estilização e responsividade.
* **Framework CSS:** Bootstrap / MaterializeCSS
* **JavaScript** - Lógica da aplicação e consumo da API.
* **jQuery** - Manipulação do DOM e interatividade.
* **JSON Server** - Simulação de uma API REST.
* **Node.js** - Ambiente de desenvolvimento.
* **NPM** - Gerenciamento de dependências.
* **Git / GitHub** - Versionamento e hospedagem do projeto.

## ✅ Checklist | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

#### RA1 - Utilizar Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos.

* [ ] ID 01 - Prototipa interfaces adaptáveis para no mínimo os tamanhos de tela mobile e desktop, usando ferramentas de design tradicionais (Figma, Quant UX ou Sketch) ou IA (Stitch).
* [ ] ID 02 - Implementa layout responsivo com Framework CSS (Bootstrap, Materialize) usando Flexbox ou Grid do próprio framework.
* [ ] ID 03 - Implementa layout responsivo com CSS puro, usando Flexbox ou Grid Layout.
* [ ] ID 04 - Utiliza componentes prontos de um Framework CSS (ex.: card, button) e componentes JavaScript do framework (ex.: modal, carousel).
* [ ] ID 05 - Cria layout fluido usando unidades relativas (vw, vh, %, em, rem) no lugar de unidades fixas (px).
* [ ] ID 06 - Aplica um Design System consistente (cores, tipografia, padrões de componentes) em toda a aplicação.
* [ ] ID 07 - Utiliza Sass (SCSS) com ou sem framework, aplicando variáveis, mixins e funções para modularizar o código.
* [ ] ID 08 - Aplica tipografia responsiva (media queries mobile first) ou tipografia fluida (função clamp() + unidades relativas).
* [ ] ID 09 - Aplica técnicas de responsividade de imagens usando CSS (object-fit, containers com unidades relativas).
* [ ] ID 10 - Otimiza imagens usando formatos modernos (WebP) e carregamento adaptativo (srcset, picture, ou parâmetros do Cloudinary).

#### RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente.

* [ ] ID 11 - Implementa validação HTML nativa (campos obrigatórios, tipos, limites de caracteres) com mensagens de erro/sucesso no lado cliente.
* [ ] ID 12 - Aplica expressões regulares (REGEX) para validações customizadas (e-mail, telefone, datas, etc.).
* [ ] ID 13 - Utiliza elementos de seleção em formulários (checkbox, radio, select) para coleta de dados.
* [ ] ID 14 - Implementa leitura e escrita no Web Storage (localStorage/sessionStorage) para persistir dados localmente.

#### RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web.

* [ ] ID 15 - Configura ambiente com Node.js e NPM para gerenciamento de pacotes e dependências.
* [ ] ID 16 - Utiliza boas práticas de versionamento no Git/GitHub (branch main ou branches específicos, uso de `.gitignore`).
* [ ] ID 17 - Mantém um README.md padronizado, conforme template da disciplina, com checklist preenchido.
* [ ] ID 18 - Organiza arquivos do projeto de forma modular, seguindo padrão de exemplo fornecido.
* [ ] ID 19 - Configura linters e formatadores (ESLint, Prettier) para manter qualidade e padronização do código.

#### RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web.

* [ ] ID 20 - Utiliza jQuery para manipulação do DOM e interatividade (eventos, animações, manipulação de elementos).
* [ ] ID 21 - Integra e configura um plugin jQuery relevante (ex.: jQuery Mask Plugin).

#### RA5 - Efetuar requisições assíncronas para uma API fake e APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente.

* [ ] ID 22 - Realiza requisições assíncronas para uma API fake (ex.: JSON Server) para persistir dados de um formulário.
* [ ] ID 23 - Realiza requisições assíncronas para uma API fake para exibir dados na página.
* [ ] ID 24 - Realiza requisições assíncronas para APIs públicas reais (OpenWeather, ViaCEP etc.), exibindo os dados e tratando erros.

## 🚀 Manual de execução

> 🚧 **Em andamento.** As instruções para instalação, configuração das dependências, execução do JSON Server e inicialização da aplicação serão adicionadas conforme o ambiente do projeto for configurado.

## 📌 Status do Projeto

🚧 **Em desenvolvimento**

> O projeto será desenvolvido progressivamente, com novas funcionalidades e melhorias sendo adicionadas conforme o andamento da implementação.

## 📱 Telas da aplicação

> 🚧 **Em andamento.** As telas da aplicação serão adicionadas conforme forem desenvolvidas e implementadas no projeto.

## 👨‍💻 Projeto

**GRIP — Sistema de Registro e Acompanhamento de Treinos**

Projeto desenvolvido para fins acadêmicos e didáticos.
