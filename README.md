# Agência de Turismo Seilatour – Guia de Navegação do Site


## Funcionalidades do Site

- **Cabeçalho:** Contém o nome da agência.
- **Navegação:** Links para as páginas principais do site.
- **Rodapé:** Exibe o ano atual e o nome da agência.

Ambas as seções descritas acima estão contidas em todas as páginas do site.

### 1. Página Inicial
   - **Objetivo:** Página de introdução, onde você encontra informações resumidas sobre a agência e caminhos para as outras partes do site.
   - **Conteúdo:** Exibe uma breve descrição da agência, dos destinos, e fotos para ilustrar cada possível lugar de viagem.

### 2. Sobre Nós
   - **Objetivo:** Descreve mais detalhadamente como é a agência.
   - **Conteúdo:** Contém histórico da agência, localização e valores da mesma.

### 3. Pacotes
   - **Objetivo:** Página contendo tabelas descritivas de cada pacote de viagem, fotos e vídeos dos locais.
   - **Conteúdo:** Essa página é dividida em 3 seções, cada qual equivalente a um destino de viagem, onde se encontram todas as informações necessárias, além de foto e vídeo de cada localidade.

### 4. Contato
   - **Objetivo:** Página de contato, onde você pode enviar um formulário para a agência e ser respondido.
   - **Conteúdo:** Contém um formulário que pede algumas informações pessoais e permite você pedir orçamentos, enviar feedback, críticas e sugestões.

## Funcionalidades de Acessibilidade

### 1. Navegação por Teclado
   - Todo o site é navegável utilizando apenas o teclado. Os usuários podem usar as teclas `Tab` para navegar entre os elementos interativos e `Enter` para ativar os links e botões.

### 2. Breadcrumbs
   - Implementamos uma navegação de breadcrumbs (migalhas de pão) nas seções de navegação para ajudar os usuários a entenderem sua localização dentro do site e facilitarem a navegação entre páginas.

### 3. Diretrizes WCAG
   - **Contraste de Cores:** Utilizamos uma paleta de cores que oferece contraste suficiente para garantir a legibilidade do texto.
   - **Tamanhos de Fonte:** Os tamanhos das fontes são ajustáveis e legíveis.
   - **Texto Alternativo:** Todas as imagens têm atributos `alt` que descrevem o conteúdo visual para usuários de leitores de tela.

### 4. ARIA Landmarks e Roles
   - Utilizamos ARIA landmarks (como `<header>`, `<nav>`, `<main>`, `<footer>`) para identificar as diferentes seções do site e facilitar a navegação com leitores de tela.
   - Roles apropriados são aplicados aos elementos interativos para fornecer informações adicionais sobre sua função.

### 5. Formulários Acessíveis
   - Formulários têm labels associadas a cada campo de entrada para garantir que os leitores de tela possam identificar o propósito de cada campo.
   - Os campos de formulário são claramente agrupados com legendas (`<legend>`) e descritores apropriados.

### 6. Design Responsivo
   - O site é projetado para ser responsivo e acessível em dispositivos móveis e desktop, garantindo uma boa experiência de usuário em diferentes tamanhos de tela.

---

