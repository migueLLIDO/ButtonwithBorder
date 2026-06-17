# 🌈 Button with Animated Border - Botão com Borda Degradê Dinâmica

Um botão de alta performance visual que utiliza gradientes lineares e animações de matiz (hue-rotate) para criar um efeito de borda colorida que parece ganhar vida quando o usuário passa o mouse.

## 🌟 Descrição

Este componente foca em estética futurista e "gaming", ideal para sites que buscam um visual moderno e impactante. O botão possui um fundo escuro que contrasta com uma borda multicolorida em gradiente.

**Principais efeitos:**
- **Borda de Gradiente:** O fundo do link é um gradiente multi-colorido que serve como a "borda" visível ao redor do elemento central.
- **Animação de Rotação de Cores:** Ao passar o mouse, a animação `@keyframes rotate` é ativada, utilizando `filter: hue-rotate` para ciclar rapidamente por todas as cores do espectro, criando um efeito psicodélico e dinâmico.
- **Contraste Elevado:** O centro do botão é um `span` escuro que se destaca sobre o fundo preto da página, dando a ilusão de uma borda fina e brilhante.

## 🛠️ Funcionalidades Técnicas

- **Filtros CSS:** Uso de `filter: hue-rotate()` para animação de cores sem mudar as propriedades de background.
- **Keyframe Animations:** Animação linear infinita ativada no estado de hover.
- **Centralização com Grid:** Uso de `display: grid` e `place-items: center` para posicionamento perfeito na tela.
- **Composição de Camadas:** Técnica de sobreposição (z-index implícito) entre o elemento pai (gradiente) e o filho (fundo sólido) para simular a borda.

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estrutura simples e semântica.
- **CSS3:** Gradientes lineares complexos, animações de keyframes, transformações e filtros.
- **Google Fonts:** Tipografia Poppins.

## 📂 Como Usar

1. Clone o repositório.
2. Certifique-se de manter a estrutura de pastas (`css/style.css`).
3. Abra o `index.html` em qualquer navegador moderno para ver o efeito.

## 👤 Autor

**Miguel Oliveira**
- [GitHub](https://github.com/migueLLIDO)
