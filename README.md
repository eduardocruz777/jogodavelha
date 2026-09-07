# ❌ Jogo da Velha (Tic-Tac-Toe) - Lógica de Matrizes e Manipulação de Eventos no DOM

## 📌 Visão Geral do Projeto
Esta aplicação consiste no desenvolvimento de um **Jogo da Velha interativo** em JavaScript puro (Vanilla JS). O objetivo central do projeto foi aplicar estruturas lógicas de matrizes bidimensionais para o gerenciamento de estados, controle rigoroso de fluxo de jogo alternado por turnos, tratamento de exceções de empate (*velha*) e validação algorítmica de padrões de vitória com feedback visual imediato ao usuário.

Projeto prático desenvolvido durante a formação de Engenharia Front-End da **OneBitCode**.

---

## 🛠️ Tecnologias, Recursos Lógicos e Engenharia de Código
* **JavaScript Estrutural e Funcional:** Uso avançado de funções isoladas e variáveis globais limpas (`vBoard`, `turnPlayer`) para controle de estado da aplicação.
* **Lógica de Matrizes Avançada:** Criação de um tabuleiro virtual em memória estruturado em uma matriz bidimensional `3x3` cruzando linhas e colunas para rastrear e registrar os movimentos de 'X' e 'O'.
* **Algoritmo de Mapeamento de Vitória (`getWinRegions`):** Implementação de uma esteira de validação lógica para auditar simultaneamente as 8 combinações matemáticas de vitória (horizontais, verticais e diagonais), acionando rotinas específicas de congelamento de cliques e destaque de interface.
* **Gestão de Ciclo de Vida de Eventos:** Manipulação dinâmica de escutadores de eventos (`addEventListener` e `removeEventListener`), garantindo que regiões já marcadas fiquem desabilitadas e impedindo fraudes ou cliques redundantes no tabuleiro.
* **Layout Responsivo via CSS Grid:** Estruturação do tabuleiro com propriedades modernas de posicionamento em CSS Grid (`grid-template-columns` e `grid-template-rows`) e efeitos visuais utilitários condicionais.

---

## 📂 Organização Estrutural do Repositório
* `css/`: Folha de estilos contendo as regras de grid estruturais e as estilizações de vitória (`.win`).
* `js/`: Scripts contendo toda a lógica do motor computacional do jogo e interações do DOM.
* `index.html`: Estrutura semântica contendo as tags de entrada para os nomes dos competidores e o layout de blocos [source: 0.1.20, 5].
* `README.md`: Documentação técnica, executiva e de negócios do projeto.
  <img width="415" height="437" alt="jogo" src="https://github.com/user-attachments/assets/2d0ac588-db66-4d5f-b9eb-0fdfd4a865dd" />

---

## 👤 Autor
* **Eduardo Cruz**
* LinkedIn: [eduardo-cruz777](https://linkedin.com)
* Email: edufracruz@gmail.com
