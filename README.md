# Prezzy-tsa 🎥

Um prezzy-tsa construído inteiramente com **HTML5 Canvas** e **Vanilla JavaScript** (sem bibliotecas externas). Este projeto simula o comportamento central de apresentações que faça integração com o canva (como a matriz Prezi integrando todos os codigos fontes em aberto), utilizando um espaço cartesiano 2.5D infinito.

## 🚀 Funcionalidades

* **Câmera Virtual (Viewport):** Navegação por um canvas infinito usando coordenadas `x`, `y` e `scale`.
* **Zoom Logarítmico:** Implementação de cálculo exponencial/logarítmico para garantir a percepção de velocidade constante durante a aproximação.
* **Física e Suavização (Easing):** Transições de câmera utilizando a curva `ease-in-out cúbica` para movimentos naturais e fluidos.
* **Culling Rudimentar:** Otimização de performance que impede a renderização de elementos que estão fora do campo de visão da câmera atual.
* **Leitura baseada em JSON:** Toda a estrutura de apresentação e o plano de animação são consumidos a partir de um objeto de dados estruturado.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura da página.
* **CSS3:** Estilização embutida para a Interface do Usuário (Botões e reset visual).
* **JavaScript Puro (ES6):** Toda a lógica de matemática, vetores, interpolação e manipulação do Canvas API via `requestAnimationFrame`.

## ⚙️ Como executar o projeto

Como o projeto não possui dependências externas (Zero dependências), rodar o código é extremamente simples:

1. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/tsa88/prezzy-tsa.git](https://github.com/tsa88/prezzy-tsa.git)
