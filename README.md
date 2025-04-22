# ✦ Projetos de Layout Responsivo - Flexbox vs Flexbox + Grid ✦

Este repositório contém **dois projetos de layout responsivo**, desenvolvidos com **HTML e CSS puro**, com o objetivo de estudo e comparação entre abordagens modernas de layout: **Flexbox** e a combinação de **Flexbox com CSS Grid**. Flexbox é ótimo para alinhar elementos em uma dimensão (linha ou coluna), enquanto o CSS Grid permite organizar conteúdo em duas dimensões (linhas e colunas). Juntos, oferecem controle total sobre o layout: Grid define a estrutura principal e Flexbox cuida dos detalhes internos. Essa combinação torna o design responsivo mais flexível e eficiente.

---

## 📁 Estrutura do Repositório

- `flexbox/`: Layout construído utilizando **apenas Flexbox**.
- `flexbox-and-grid/`: Layout desenvolvido com a combinação de **Flexbox e CSS Grid**.

---

## 📌 Projeto 1 – Apenas Flexbox

### Características:
- Utilização exclusiva do modelo Flexbox para organizar os elementos da página.
- Responsividade baseada em **direção e alinhamento de flex containers**.
- Mais controle linear (horizontal/vertical), exigindo estruturas adicionais para alinhamento mais complexo.
- Adapta-se responsivamente para dispositivos móveis por meio de `media queries` a partir da mudança de direção do flex.
- Uso do componente  `flex: x` para a distribuição entre o conteúdo principal e a sidebar.
---

## 📌 Projeto 2 – Flexbox + CSS Grid

### Características:
- Utiliza **CSS Grid** para o layout principal da página, permitindo uma divisão clara em colunas.
- **Flexbox** é aplicado em elementos internos como `header`, `nav`, seções dentro do `main`, e em `aside`, para controle de espaçamento e alinhamento.
- Garante **maior controle bidimensional** (linhas e colunas) sem comprometer a semântica do HTML.
- Adapta-se responsivamente para dispositivos móveis por meio de `media queries` com redefinições de grid e comportamento em colunas.
- Uso de `grid-template-columns: 9fr 4fr` para a distribuição entre o conteúdo principal e a sidebar.


