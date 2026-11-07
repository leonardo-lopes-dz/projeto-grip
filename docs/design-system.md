# 🎨 Design System - GRIP

Neste projeto, utilizamos um framework UI e aplicamos customizações para refletir a identidade visual do GRIP, combinando uma estética esportiva, moderna e tecnológica com foco em musculação.

### 1. Framework Base

- **Framework escolhido:** Bootstrap
- **Motivação:** Oferece componentes responsivos e prontos, permitindo uma implementação rápida e consistente de elementos como botões, cards, formulários e grids, além de facilitar a adaptação da aplicação para dispositivos móveis e desktop.

### 2. Paleta de Cores (Customização)

A identidade visual do GRIP utiliza uma base escura em grafite profundo, contrastada com um verde-limão neon que cria um efeito de "brilho". A paleta é construída sobre contraste extremo, com texto principal mantendo proporção mínima de 7:1 sobre o fundo, para garantir leitura em ambientes de treino de alta intensidade.

- **Cor Primária (Electric Lime):** `#C3F400`
  - _Uso:_ Botões principais, ações importantes, estados ativos e destaques críticos de dados. Representa energia e sinal de "go".
- **Cor Primária Escura:** `#ABD600`
  - _Uso:_ Estados de interação, variações da cor primária e início do gradiente da barra de progresso.
- **Cor Secundária (Cinza Claro):** `#C8C6C5`
  - _Uso:_ Elementos de apoio, ícones inativos e ações neutras. Sua variação `#474746` é usada em fundos de elementos secundários.
- **Cor de Fundo (Background):** `#111317`
  - _Uso:_ Fundo principal das páginas. Um grafite levemente quente, que evita o "preto esmagado" do `#000000` e permite profundidade sutil por camadas.
- **Cor de Superfície:** `#1E2023`
  - _Uso:_ Cards, formulários e principais áreas de conteúdo, criando separação clara do fundo.
- **Cor de Superfície Elevada:** `#282A2E`
  - _Uso:_ Elementos que precisam de maior destaque em relação às superfícies padrão, como modais e overlays.
- **Cor de Texto Principal:** `#E2E2E7`
  - _Uso:_ Títulos, textos principais e informações de maior importância.
- **Cor de Texto Secundário:** `#C4C9AC`
  - _Uso:_ Textos auxiliares, descrições e informações de menor destaque.
- **Cor de Erro:** `#FFB4AB`
  - _Uso:_ Mensagens de erro e validações de formulários.

### 3. Tipografia

A tipografia do GRIP combina uma fonte geométrica de alto impacto para títulos com fontes voltadas à legibilidade e à apresentação de dados.

- **Títulos e Destaques:** `Plus Jakarta Sans, sans-serif` (Peso: 600 a 800). Espaçamento entre letras apertado (-0.01em a -0.02em) e pesos altos transmitem força.
- **Textos Corridos e Formulários:** `Inter, sans-serif` (Peso: 400).
- **Dados e Informações Numéricas:** `Space Grotesk, sans-serif` (Peso: 700). Também usada em rótulos: 12px, caixa alta e espaçamento de 0.08em.
- **Destaques:** Títulos importantes podem utilizar letras maiúsculas para reforçar a identidade esportiva e transmitir maior impacto visual.
- **Escala:** Display 40px/48px, Headline 32px/40px (28px/34px no mobile), Title 20px/28px, Corpo 16px/24px e 14px/20px.

### 4. Diretrizes de Uso de Componentes

Os componentes da interface devem manter a identidade esportiva e tecnológica do GRIP, utilizando contrastes fortes, formas geométricas limpas e elementos visuais simples.

- **Botões:** Ações principais devem ser sólidas na cor primária (Electric Lime) com texto preto, em largura total quando possível, para máxima visibilidade. Ações secundárias utilizam o estilo ghost, sem preenchimento e com borda na cor primária. Ações menos importantes podem utilizar texto simples, sem preenchimento e sem borda.
- **Cards:** Utilizados para exibir exercícios, treinos e informações resumidas. Devem utilizar a cor de superfície, um gradiente sutil de cima para baixo e borda de 1px. Os títulos dentro dos cards usam o estilo Title (20px). Alta densidade de informação é permitida dentro dos cards.
- **Formulários:** Os campos devem utilizar fundo mais escuro que o do card, com destaque sutil e brilho em Electric Lime quando estiverem em foco. Os rótulos usam o estilo de rótulo (Space Grotesk, caixa alta) para reforçar o visual técnico.
- **Chips:** Utilizados para identificar grupos musculares (ex.: Peito, Tríceps) e outras categorias relacionadas aos exercícios. Devem ter fundo escuro, texto branco e nenhuma borda, para manter o foco no layout principal.
- **Indicadores Numéricos:** Informações como séries, repetições e carga devem utilizar Space Grotesk para facilitar a leitura e reforçar a identidade técnica do sistema.
- **Barra de Progresso:** Deve ter trilho fino e de alto contraste, com preenchimento em gradiente do verde escuro (`#ABD600`) para o Electric Lime (`#C3F400`), simulando movimento e energia.
- **Navbar:** Deve utilizar a base escura da identidade visual, com fundo desfocado (blur alto), e apresentar o nome/logo do GRIP junto aos principais caminhos de navegação. A cor primária fica reservada ao ícone e ao indicador do item ativo.

### 5. Layout e Responsividade

A aplicação utiliza um layout fluido e um sistema de espaçamento baseado em uma grade de **8px**, garantindo consistência entre os diferentes elementos da interface.

- **Espaçamento base:** `4px`
- **Margem do container:** `20px` no mobile, ampliada para `40px` em tablet e desktop
- **Espaçamento entre elementos:** `16px` na vertical e `12px` na horizontal
- **Espaçamento entre seções:** `32px` ou mais, para evitar fadiga visual

O desenvolvimento deve seguir o conceito de **Mobile First**, considerando que o sistema pode ser utilizado durante a realização de treinos.

- **Mobile:** Organização dos conteúdos em uma única coluna, com empilhamento vertical, e elementos de interação com áreas de toque de pelo menos `44px`.
- **Desktop:** Utilização do grid do framework para distribuir cards e conteúdos em múltiplas colunas. O conteúdo é alinhado à esquerda, com gráficos e botões principais podendo usar centralização ou largura total.

### 6. Formas e Elevação

A interface utiliza bordas arredondadas e camadas tonais para criar hierarquia visual sem depender de sombras pesadas, mantendo um perfil limpo e moderno.

- **Border Radius padrão:** `8px`
- **Border Radius médio:** `12px` (botões e campos de formulário)
- **Border Radius grande:** `16px` (cards)
- **Border Radius extra grande:** `24px`
- **Elementos especiais:** Chips e tags utilizam bordas totalmente arredondadas (`9999px`), para se diferenciarem dos containers acionáveis.

A profundidade dos componentes deve ser criada principalmente através da diferença entre tons de superfície e bordas sutis.

- **Background:** `#111317`
- **Surface:** `#1E2023`
- **Surface elevada:** `#282A2E`, com desfoque de fundo (`blur` de 12px) em modais e overlays
- **Bordas:** `1px` em `#444933`, discretas, para separar elementos sem adicionar volume.
- **Estados ativos:** Utilizam, no lugar de sombras, um brilho (glow) na cor primária com 20% a 30% de opacidade.
- **Indicadores visuais:** Barras verticais de `4px` de largura na cor primária marcam itens ativos de lista e títulos de seção.

### 7. Identidade Visual

A identidade do GRIP busca transmitir intensidade, disciplina e avanço tecnológico:

- **Força:** através de títulos pesados e contrastes elevados.
- **Energia:** através do uso do Electric Lime em ações e elementos importantes.
- **Precisão:** através da utilização da Space Grotesk em dados e informações de treino.
- **Tecnologia:** através da combinação de superfícies escuras, verde neon com efeito de brilho e elementos modernos.
- **Performance:** através de uma interface objetiva, com foco nas informações necessárias para a montagem dos treinos.
