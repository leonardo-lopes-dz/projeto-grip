# 📄 Product Requirements Document (PRD) - GRIP

## 1. Visão Geral e Objetivo

O **GymTrack** é uma aplicação web didática voltada para o registro e acompanhamento de treinos de musculação.

O sistema permite que o usuário cadastre exercícios, organize seus treinos e registre informações de desempenho, como número de séries, repetições e carga utilizada.

**O grande diferencial (Regra de Negócio Principal):** O GymTrack utiliza o histórico dos exercícios para acompanhar a evolução do usuário e identificar **Recordes Pessoais (PRs)**. Sempre que uma nova carga superar a maior carga anteriormente registrada para determinado exercício, o sistema identifica a evolução como um novo PR.

## 2. Atores do Sistema

* **Visitante:** Usuário que acessa a aplicação e deseja cadastrar e organizar seus treinos.
* **Usuário:** Pessoa que utiliza o GymTrack para cadastrar exercícios, criar treinos e registrar seu desempenho.
* **O Sistema:** Responsável por armazenar os dados, processar os registros e identificar novos recordes pessoais.

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

### 🏋️ Épico 1: Exercícios

* **US01 - Cadastro de Exercício:** Como um Usuário, quero preencher um formulário com os dados de um exercício (Nome, Grupo Muscular, Equipamento) para cadastrá-lo no GymTrack.

  * *Critérios de Aceitação:* O nome e o grupo muscular são obrigatórios; os dados devem ser validados antes do cadastro.

* **US02 - Visualização de Exercícios:** Como um Usuário, quero visualizar uma lista dos exercícios cadastrados, para consultar os exercícios disponíveis.

### 💪 Épico 2: Treinos

* **US03 - Criação de Treino:** Como um Usuário, quero criar um treino informando seu nome e descrição, para organizar meus exercícios em diferentes rotinas.

* **US04 - Associação de Exercícios:** Como um Usuário, quero associar exercícios cadastrados a um treino, para definir quais exercícios fazem parte daquela rotina.

* **US05 - Visualização de Treinos:** Como um Usuário, quero visualizar meus treinos e os exercícios associados a cada um, para saber como minha rotina está organizada.

### 📊 Épico 3: Registro e Evolução

* **US06 - Registro de Desempenho:** Como um Usuário, quero registrar a carga, número de repetições e séries realizadas em um exercício, para acompanhar meu desempenho.

* **US07 - Visualização do Histórico:** Como um Usuário, quero visualizar os registros anteriores de um exercício, para comparar minha evolução ao longo dos treinos.

* **US08 - Identificação de PR:** Como um Usuário, quero que o sistema identifique quando eu superar minha maior carga anterior em um exercício, para acompanhar meus recordes pessoais.

### 🏠 Épico 4: Dashboard

* **US09 - Visualização do Dashboard:** Como um Usuário, quero visualizar um resumo dos meus treinos e exercícios, para acompanhar rapidamente minha evolução.

  * *Critérios de Aceitação:* O dashboard deve apresentar informações como quantidade de treinos, exercícios cadastrados, último treino e PRs registrados.

