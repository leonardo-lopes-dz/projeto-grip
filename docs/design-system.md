# 🎨 Design System - GRIP

Neste projeto, utilizamos um framework UI e aplicamos customizações para refletir a identidade visual do GRIP, combinando uma estética esportiva, moderna e tecnológica com foco em musculação.

### 1. Framework Base

- **Framework escolhido:** Bootstrap
- **Motivação:** Oferece componentes responsivos e prontos, permitindo uma implementação rápida e consistente de elementos como botões, cards, formulários e grids, além de facilitar a adaptação da aplicação para dispositivos móveis e desktop.

### 2. Paleta de Cores (Customização)

A identidade visual do GRIP utiliza uma base escura em tons de preto e cinza, combinada com cores vibrantes para destacar ações e informações importantes.

- **Cor Primária (Volt Green):** `#C5F400`
  - _Uso:_ Botões principais, ações importantes, estados ativos e elementos de destaque. Representa energia, força e ação.
- **Cor Primária Escura:** `#ACD600`
  - _Uso:_ Estados de interação e variações da cor primária.
- **Cor Secundária (Electric Blue):** `#00E3FD`
  - _Uso:_ Ações secundárias, informações, destaques e elementos relacionados a dados.
- **Cor de Fundo (Background):** `#131313`
  - _Uso:_ Fundo principal das páginas.
- **Cor de Superfície:** `#1C1B1B`
  - _Uso:_ Cards, formulários e principais áreas de conteúdo.
- **Cor de Superfície Elevada:** `#2A2A2A`
  - _Uso:_ Elementos que precisam de maior destaque em relação às superfícies padrão.
- **Cor de Texto Principal:** `#E5E2E1`
  - _Uso:_ Títulos, textos principais e informações de maior importância.
- **Cor de Texto Secundário:** `#C4C9AC`
  - _Uso:_ Textos auxiliares, descrições e informações de menor destaque.
- **Cor de Erro:** `#FFB4AB`
  - _Uso:_ Mensagens de erro e validações de formulários.

### 3. Tipografia

A tipografia do GRIP combina uma fonte de alto impacto para títulos com fontes voltadas à legibilidade e apresentação de dados.

- **Títulos e Destaques:** `Montserrat, sans-serif` (Peso: 700 a 900).
- **Textos Corridos e Formulários:** `Inter, sans-serif` (Peso: 400).
- **Dados e Informações Numéricas:** `JetBrains Mono, monospace` (Peso: 600 a 700).
- **Destaques:** Títulos importantes podem utilizar letras maiúsculas para reforçar a identidade esportiva e transmitir maior impacto visual.

### 4. Diretrizes de Uso de Componentes

Os componentes da interface devem manter a identidade esportiva e tecnológica do GRIP, utilizando contrastes fortes e elementos visuais simples.

- **Botões:** Ações principais devem utilizar a cor primária (Volt Green) com texto escuro. Ações secundárias podem utilizar bordas na cor secundária (Electric Blue) ou na cor branca. Ações menos importantes podem utilizar o estilo Ghost, sem preenchimento.
- **Cards:** Utilizados para exibir exercícios, treinos e informações resumidas. Devem utilizar superfícies escuras e bordas discretas, mantendo uma hierarquia visual clara.
- **Formulários:** Os campos devem utilizar fundo escuro, bordas sutis e destaque em Volt Green quando estiverem em foco.
- **Chips:** Utilizados para identificar grupos musculares e outras categorias relacionadas aos exercícios. Devem possuir cores de destaque sem comprometer a legibilidade.
- **Indicadores Numéricos:** Informações como séries e repetições devem utilizar `JetBrains Mono` para facilitar a leitura e reforçar a identidade técnica do sistema.
- **Barra de Progresso:** Deve utilizar a combinação das cores Electric Blue e Volt Green para representar progresso e evolução.
- **Navbar:** Deve utilizar a base escura da identidade visual e apresentar o nome/logo do GRIP junto aos principais caminhos de navegação.

### 5. Layout e Responsividade

A aplicação utiliza um sistema de espaçamento baseado em uma grade de **8px**, garantindo consistência entre os diferentes elementos da interface.

- **Espaçamento base:** `8px`
- **Margem do container:** `20px`
- **Espaçamento entre elementos:** `16px`
- **Espaçamento entre seções:** `40px`

O desenvolvimento deve seguir o conceito de **Mobile First**, considerando que o sistema pode ser utilizado durante a realização de treinos.

- **Mobile:** Organização dos conteúdos em uma única coluna e elementos de interação com áreas de toque de pelo menos `44px`.
- **Desktop:** Utilização do grid do framework para distribuir cards e conteúdos em múltiplas colunas.

### 6. Formas e Elevação

A interface utiliza bordas arredondadas e diferentes níveis de superfície para criar hierarquia visual sem depender de sombras excessivas.

- **Border Radius padrão:** `8px`
- **Border Radius médio:** `12px`
- **Border Radius grande:** `16px`
- **Elementos especiais:** Podem utilizar bordas totalmente arredondadas (`9999px`).

A profundidade dos componentes deve ser criada principalmente através da diferença entre tons de superfície e bordas sutis.

- **Background:** `#131313`
- **Surface:** `#1C1B1B`
- **Surface elevada:** `#2A2A2A`
- **Bordas:** Tons escuros e discretos para separar elementos visualmente.
- **Estados ativos:** Podem utilizar um brilho sutil baseado na cor primária ou secundária.

### 7. Identidade Visual

A identidade do GRIP busca transmitir:

- **Força:** através de títulos pesados e contrastes elevados.
- **Energia:** através do uso do Volt Green em ações e elementos importantes.
- **Precisão:** através da utilização da JetBrains Mono em dados e informações de treino.
- **Tecnologia:** através da combinação de superfícies escuras, Electric Blue e elementos modernos.
- **Performance:** através de uma interface objetiva, com foco nas informações necessárias para a montagem dos treinos.
