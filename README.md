# Projeto Calculadora Simples
Este projeto foi desenvolvido como parte do curso de Projetos de Análise de Dados com Linguagem Python pela DSA. Iniciei com uma calculadora simples em Python e, ao longo do aprendizado, fui aprimorando suas funcionalidades. A calculadora realiza operações básicas como adição, subtração, multiplicação e divisão, agora com melhorias significativas. Ela permite o uso de números decimais (float) para maior precisão e foi programada para detectar e evitar erros comuns, como a divisão por zero. Este projeto está disponível no meu portfólio como um exemplo do meu progresso em Python e na lógica de programação, evidenciando o processo de construção e aprimoramento de funções conforme as necessidades do projeto.

Este repositório contém uma calculadora básica desenvolvida em Python, criada como parte de um curso introdutório de programação. O projeto foi inicialmente projetado para realizar operações com números inteiros, mas foi aprimorado para aceitar números em ponto flutuante (float), ampliando a precisão e a aplicabilidade dos cálculos.

## Funcionalidades
Operações Matemáticas: Permite realizar as seguintes operações:

Soma  
Subtração  
Multiplicação  
Divisão  
Cálculo de Porcentagem  
Cálculo de Raiz Quadrada  
Tratamento de Erros: Inclui verificações para entradas inválidas e uma condição específica para evitar divisão por zero, garantindo maior robustez.

## Principais Ajustes
Entrada de Dados: Ajuste do tipo de entrada de int para float, permitindo cálculos mais precisos com valores decimais.  
Nova Funcionalidade: Adição da opção de calcular a porcetagem e raiz quadrada, permitindo que os usuários realizem operações mais avançadas.

### Explicação das Alterações  
Função percentage(x, y): Calcula a porcentagem de x em relação a y, utilizando a fórmula (x * y) / 100.  
Novo Menu de Opções: Adicionada a opção 5 para "Porcentagem" no menu inicial.

Função square_root(x): Calcula a raiz quadrada do número x utilizando math.sqrt().  
Opção de Menu: Adicionada a opção 6 para "Raiz Quadrada".  
Tratamento da Operação: Ao escolher a raiz quadrada, o programa solicita apenas um número.

## Tecnologias Utilizadas
Python 3  
Biblioteca Math (para cálculos de raiz quadrada)

Estrutura do Código
O código é dividido em funções, cada uma responsável por uma operação matemática específica. O programa apresenta um menu interativo para o usuário selecionar a operação desejada e processa as entradas de forma robusta.

### Contribuições
Contribuições são bem-vindas! Se você tem sugestões para melhorias ou correções, sinta-se à vontade para abrir uma issue ou enviar um pull request.


