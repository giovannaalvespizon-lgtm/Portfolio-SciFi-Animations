# 🌌 Personal Portfolio Website - Sci-Fi Animations

Um website de **Portfólio Pessoal** com temática futurista/Sci-Fi e paleta de cores em azul neon elétrico. O grande diferencial técnico deste projeto é o uso avançado de engenharia de animações em CSS3 puro, implementando efeitos de revelação em blocos geométricos no carregamento da página e micro-interações de preenchimento fluido nos componentes de interface.

---

## 🚀 Tecnologias e Conceitos Aplicados

* **HTML5 Semântico:** Estruturação limpa baseada nas diretrizes modernas da web, utilizando tags como `<header>` fixa para navegação estrutural, `<nav>` para links institucionais e atributos de otimização de renderização (`IE-edge` e `viewport`).
* **CSS3 Avançado & Engenharia de Animações:**
  * **Animação de Revelação (Reveal Effect):** Uso coordenado da regra `@keyframes showRight` aplicada a pseudo-elementos (`::before` e `::after`). Os blocos cobrem os títulos, parágrafos e botões com a cor de fundo e encolhem gradualmente (`width: 0`), simulando uma varredura tecnológica de carregamento.
  * **Temporização Assíncrona (Animation Delays):** Escalonamento estratégico através de `animation-delay` (de `0.4s` a `4s`), garantindo que os elementos da interface surjam na tela em uma sequência lógica e fluida de cima para baixo.
  * **Preenchimento Líquido em Botões:** Efeito interativo avançado nos botões e ícones sociais através do crescimento lateral (`width: 100%`) de uma camada oculta no estado de `:hover`, criando uma transição suave e altamente responsiva.
  * **Manipulação de Eventos de Ponteiro:** Uso da propriedade `pointer-events: none` combinada com a transição dinâmica para `auto` via animação, prevenindo que o usuário interaja acidentalmente com elementos visuais de fundo antes do carregamento total da página.
* **Ecossistemas e Tipografia Externa:**
  * Integração nativa com a biblioteca de ícones **Boxicons v2.1.4** via CDN para amostragem dos vetores de redes sociais (Facebook, Twitter, LinkedIn).
  * Importação e renderização da família de fontes **Poppins** com múltiplos pesos (*weights* do 300 ao 900) diretamente do Google Fonts.

---

## 🛠️ Funcionalidades e Diferenciais do Layout

* **Navegação Fixa Inteligente:** Cabeçalho transparente fixado no topo (`position: fixed`) com links que alteram o estado visual dinamicamente para indicar a seção ativa.
* **Fundo Tecnológico Otimizado:** Imagem de plano de fundo configurada com posicionamento cirúrgico (`background-position: 90% center`) e dimensionamento inteligente (`background-size: contain`) para compor perfeitamente com o bloco de textos da esquerda.

---
Desenvolvido com dedicação e foco no crescimento profissional.

Giovanna Pizon

Desenvolvedora Frontend
