# -L-gica-JS-7-7-Fun-es-em-Javascript
Para o exercício de hoje: você já parou para pensar como uma calculadora funciona?

Calculadora Científica 📟

Este projeto é uma Calculadora Científica Interativa, desenvolvida como parte do desafio #7DaysOfCode. O objetivo foi criar uma calculadora funcional que realiza operações matemáticas básicas e avançadas, organizando o código de forma modular, utilizando funções específicas para cada operação.

🎨 Interface

A calculadora possui um design moderno e minimalista, com:

Botões interativos e efeitos de hover.

Cores diferenciadas para cada tipo de operação (aritmética, científica, etc.).

Layout responsivo, garantindo boa experiência em diferentes dispositivos.
![Captura de tela_4-3-2025_183845_](https://github.com/user-attachments/assets/c4e676ca-c5e3-4703-9200-354b9af8aa8f)



⚙️ Funcionalidades

✅ Operações básicas (soma, subtração, multiplicação, divisão).✅ Operações científicas (seno, cosseno, tangente, logaritmo, exponenciação, raiz quadrada, valor absoluto).✅ Constantes matemáticas como π (Pi) e a base dos logaritmos naturais (e).✅ Cálculo dinâmico, atualizando os resultados instantaneamente na tela.✅ Botão de limpar (C) para resetar os valores.✅ Modo de saída, onde o usuário pode encerrar a calculadora.

![Captura de tela_4-3-2025_183857_](https://github.com/user-attachments/assets/c0e792b5-e8e8-4ccd-ae44-5abd0d7e5934)


🛠️ Organização do Código

O código foi estruturado da seguinte forma:

Cada operação matemática foi encapsulada dentro de uma função específica.

Uso de switch/case para selecionar a operação desejada.

Função para atualizar a tela, garantindo que o resultado seja exibido corretamente.

Eventos JavaScript para captura de cliques nos botões.

📌 Exemplo de Estrutura de Código:


function somar(a, b) {
    return a + b;
}

function subtrair(a, b) {
    return a - b;
}

function multiplicar(a, b) {
    return a * b;
}

function dividir(a, b) {
    return b !== 0 ? a / b : 'Erro: Divisão por zero';
}



🚀 Melhorias Futuras

🔹 Adicionar suporte a entrada via teclado.🔹 Implementar um modo noturno/dia para personalização.🔹 Criar um histórico de operações realizadas.🔹 Implementar suporte para cálculos encadeados.



Este projeto foi uma ótima oportunidade para praticar lógica de programação, funções em JavaScript e manipulação do DOM. Além disso, trouxe um aprendizado valioso sobre organização de código e interatividade com o usuário.

🔹 Desenvolvido por Jaine 💡
