# 📄 Product Requirements Document (PRD) - GRIP

## 1. Visão Geral e Objetivo

O **GRIP** é uma aplicação web didática voltada para a **montagem e organização de treinos de musculação**.

O sistema permite que o usuário consulte exercícios de acordo com o grupo muscular desejado, selecione os exercícios que deseja utilizar e monte treinos personalizados, definindo informações como séries e repetições.

**O grande diferencial (Regra de Negócio Principal):** O GRIP facilita a criação de treinos a partir da seleção de grupos musculares. Ao escolher um grupo muscular, o sistema consulta a API e apresenta os exercícios relacionados, permitindo que o usuário selecione um ou mais exercícios para compor seu treino.

## 2. Atores do Sistema

* **Usuário:** Pessoa que utiliza o GRIP para consultar exercícios e montar seus próprios treinos.
* **O Sistema:** Responsável por consultar os exercícios, organizar os treinos e armazenar as informações cadastradas através da API.

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

### 🏋️ Épico 1: Exercícios

* **US01 - Cadastro de Exercício:** Como um Usuário, quero cadastrar um exercício informando seu nome, grupo muscular e equipamento, para disponibilizá-lo no GRIP.

  * *Critérios de Aceitação:* O nome e o grupo muscular são obrigatórios; os dados devem ser validados antes do cadastro.

* **US02 - Consulta de Exercícios:** Como um Usuário, quero selecionar um grupo muscular para visualizar os exercícios relacionados, para encontrar exercícios que possam fazer parte do meu treino.

  * *Critérios de Aceitação:* O sistema deve consultar a API e exibir somente os exercícios relacionados ao grupo muscular selecionado.

### 💪 Épico 2: Montagem de Treinos

* **US03 - Criação de Treino:** Como um Usuário, quero criar um treino informando seu nome e descrição, para organizar uma rotina de exercícios.

* **US04 - Seleção de Exercícios:** Como um Usuário, quero selecionar um ou mais exercícios disponíveis, para adicioná-los ao treino que estou montando.

* **US05 - Configuração dos Exercícios:** Como um Usuário, quero definir a quantidade de séries e repetições de cada exercício, para personalizar meu treino.

* **US06 - Associação de Exercícios:** Como um Usuário, quero associar os exercícios selecionados ao meu treino, para definir quais exercícios fazem parte daquela rotina.

### 📋 Épico 3: Consulta e Organização dos Treinos

* **US07 - Visualização de Treinos:** Como um Usuário, quero visualizar os treinos que criei, para consultar minhas rotinas de exercícios.

* **US08 - Visualização de Treino:** Como um Usuário, quero visualizar os exercícios, séries e repetições de um treino, para saber como ele está estruturado.

* **US09 - Edição de Treino:** Como um Usuário, quero editar um treino existente, para alterar seus exercícios, séries, repetições ou informações gerais.

### 🏠 Épico 4: Dashboard

* **US10 - Visualização do Dashboard:** Como um Usuário, quero visualizar um resumo dos meus treinos e exercícios, para acessar rapidamente as principais informações do sistema.

  * *Critérios de Aceitação:* O dashboard deve apresentar informações como quantidade de treinos cadastrados, quantidade de exercícios disponíveis e acesso rápido à montagem de um novo treino.
