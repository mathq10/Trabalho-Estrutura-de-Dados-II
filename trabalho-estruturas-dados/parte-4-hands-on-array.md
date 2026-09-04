# Parte 4 — Hands On 1: Investigação do Array

*Responsável: Rhuann Pabllo Ferreira Magalhães*

**Quantidade de operações de percurso do array:**
O vetor de 10 posições foi percorrido em 4 blocos separados, para ficar mais fácil de codar: um `for` para preencher (10 leituras), outro para mostrar na tela (10 impressões), mais um para somar e achar o maior e o menor (mais 10 acessos) e o último para ver quem estava acima da média (outros 10). No fim das contas, deu um total de umas 40 operações de percurso.

**Complexidade do algoritmo desenvolvido:**
O(n), linear pura. Mesmo com vários `for` no código, eles ficam soltos, um depois do outro, sem loop dentro de loop. Então o tempo de execução sobe de forma direta conforme o tamanho do vetor cresce.

---

## 💬 Comentários

**Matheus Queirós - 04/09:**
Nesta parte, o Rhuann Pabllo Ferreira Magalhães ficou responsável pela investigação do percurso de um array. Foram analisadas as operações realizadas durante o preenchimento, a exibição dos valores, o cálculo da soma, a identificação do maior e menor elemento e a verificação dos valores acima da média. Dessa forma, foi possível perceber que, mesmo utilizando vários laços for, como eles são executados separadamente, a complexidade do algoritmo continua sendo O(n), apresentando um crescimento linear conforme aumenta a quantidade de elementos do vetor.

