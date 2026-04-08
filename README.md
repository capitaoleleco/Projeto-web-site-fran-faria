# 🦋 Redesign: Site Fran Faria - Estética & Bem-Estar

Bem-vindo ao repositório do site oficial da **Fran Faria**, profissional especializada em Gestão de Saúde, Estética e Tricologia. 

Este projeto passou por um processo completo de **Modernização de Interface (UI)** e **Experiência do Usuário (UX)**, evoluindo de um layout estático básico para uma experiência premium, fluida e alinhada com o mercado de alto padrão de beleza e autocuidado.

---

## 🔄 Resumo das Atualizações (Antes ➡️ Depois)

O código original possuía uma excelente estrutura HTML semântica. O foco desta atualização foi 100% no CSS, trazendo requinte visual, leveza e interatividade, sem quebrar a lógica de navegação existente.

### 🎨 1. Nova Identidade Visual (Soft Luxury)
* **Antes:** Cores mais fortes e chapadas (Fundo `#e8e3d9`, Sidebar `#F4A79D`, Texto `#59423b`).
* **Depois:** Transição para uma paleta *nude/blush* mais suave, transmitindo calma e sofisticação.
  * **Background:** Off-white quente (`#FDFBF7`).
  * **Texto principal:** Marrom escuro elegante (`#4A3A35`).
  * **Acentos:** Tom bege/dourado (`#D4A373`).

### ✍️ 2. Tipografia de Alto Padrão
* **Antes:** Apenas a fonte `Montserrat` em todo o projeto.
* **Depois:** Combinação clássica de design editorial. Mantivemos a `Montserrat` para textos corridos (trazendo legibilidade e um toque moderno) e introduzimos a **`Cormorant Garamond`** (fonte serifada) para títulos e citações, entregando um aspecto de "revista de beleza".

### ✨ 3. Efeitos Modernos e Fluidez (UI/UX)
* **Glassmorphism na Sidebar:** A barra lateral deixou de ter uma cor sólida opaca e ganhou um efeito translúcido (com `backdrop-filter: blur`), integrando-se melhor com o fundo da página.
* **Ícone Menu Animado:** O botão de menu sanduíche (`☰`) agora possui uma transição suave que se transforma em um "X" (`✕`) quando a sidebar é aberta.
* **Animações de Entrada:** Implementação de `keyframes` (`fade-in`) em todas as páginas. O conteúdo agora surge suavemente de baixo para cima ao carregar, eliminando a sensação de carregamento "travado".

### 📐 4. Refatoração de Layouts por Página
* **Página Inicial (`index.html`):** Remoção de recortes poligonais abruptos na imagem de destaque. Adição de bordas arredondadas e controle de quebra de texto (`text-wrap: balance`) para a frase principal, mantendo-a alinhada em qualquer tamanho de tela.
* **Avaliações e Premiações:** Os textos soltos foram convertidos em **Cards Flutuantes** com sombras suaves (`box-shadow`) e efeitos de elevação no *hover* do mouse.
* **Procedimentos (Galeria):** Substituição das pesadas bordas pretas por um grid moderno com espaçamento harmônico, cantos arredondados e legendas imersivas que surgem elegantemente no *hover*.
* **Sobre Mim:** Centralização aprimorada da foto de perfil, adição de uma borda fina e sofisticada, e melhor espaçamento entre parágrafos para leitura fluida.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Semântico e estruturado.
* **CSS3:** Variáveis (`:root`), Flexbox, Grid Layout, Animações (`@keyframes`), Transições e Filtros CSS.
* **Google Fonts:** Importação das fontes *Montserrat* e *Cormorant Garamond*.
* **FontAwesome:** Ícones vetoriais para a seção de contato.

---

## 🚀 Como Executar o Projeto

Como o projeto é construído inteiramente com HTML e CSS puros (Vanilla), não é necessário nenhum processo de *build* ou instalação de dependências.

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/nome-do-repositorio.git](https://github.com/SEU-USUARIO/nome-do-repositorio.git)
