                                                                                          Manipulador de Árvore Binária de Busca (BST) — C

Este projeto implementa uma Árvore Binária de Busca (Binary Search Tree — BST) em linguagem C, permitindo inserir valores, pesquisar, exibir em diferentes ordens e encontrar valores mínimo e máximo.
Foi desenvolvido como parte de um trabalho de faculdade, servindo como base prática para compreender estruturas de dados e operações em árvores.

- FUNCIONALIDADES:
O programa oferece um menu interativo que permite:
Inserir valores na árvore
Pesquisar um valor
Exibir a árvore em:
• Pré-ordem
• Em-ordem
• Pós-ordem
Encontrar o menor valor da árvore
Encontrar o maior valor da árvore
Encerrar o programa

- COMO FUNCIONA UMA BST:
Uma árvore binária de busca segue três regras principais:
Cada nó possui um valor, um ponteiro para a subárvore esquerda e outro para a direita.
Valores menores vão para a esquerda.
Valores maiores ou iguais vão para a direita.

- ESTRUTURA DO PROJETO:
faculdade.c → Código-fonte principal
README.txt → Documentação

- COMO COMPILAR:
Utilizando GCC no Linux:
gcc faculdade.c -o arvore

Ou com warnings ativados:
gcc faculdade.c -Wall -Wextra -o arvore

- COMO EXECUTAR:
./arvore

- EXEMPLO DO MENU:
1 - Inserir valor
2 - Buscar valor
3 - Exibir em pre-ordem
4 - Exibir em em-ordem
5 - Exibir em pos-ordem
6 - Exibir o menor valor
7 - Exibir o maior valor
0 - Sair

- TECNOLOGIAS UTILIZADAS:
Linguagem C
Ponteiros
Alocação dinâmica
Árvores binárias (BST)

- AUTOR:
Fabrício Almeida
Estudante de Segurança da Informação e apaixonado por programação e estrutura de dados.
