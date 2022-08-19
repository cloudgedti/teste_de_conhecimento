# Teste de Conhecimento

Este teste consiste em uma série de desafios de programação para entender melhor os conhecimentos dos candidatos(as).

Critérios de avaliação:

* Entendimento do problema
* Solução do problema
* Legibilidade
* Otimização
* Organização

## Desafios

### Desafio 1 - Conversor de Base Númerica

O desafio consiste em desenvolver um programa que recebe uma string com a base númerica de origem, um valor na base númerica de origem, e a base númerica de destino. Converter o valor da base númerica de origem para a base númerica de destino especificada na entrada. E por fim retornar uma string com o valor na base númerica de destino.

Exemplos:
| Entrada | Saída |
|---------|-------|
|"DEC,10,HEX"|"A"|
|"DEC,7,BIN"|"111"|
|"HEX,8,OCT"|"10"|
|"BIN,1111,HEX"|"15"|
|"OCT,10,DEC"|"8"|
|"OCT,16,BIN"|"1110"|

### Desafio 2 - Lista de Tarefas

O desafio consiste em criar uma página HTML onde o usuário possa adicionar, concluir e deletar tarefas em uma lista. A página deve funcionar com as seguintes regras:

* Uma tarefa é uma string de até 30 caracteres escrita pelo usuário em um input;
* A lista de tarefas em aberto deve ficar abaixo do input de tarefas;
* Sempre que o usuário adicionar uma nova tarefa, ela deve ser acrescentada ao topo da lista de tarefas em aberto;
* Cada tarefa na lista de tarefas em aberto deve ter 2 botões, um para concluir a tarefa, e outro para deletar a tarefa;
* Abaixo da lista de tarefas em aberto deverá ter uma lista de tarefas concluídas;
* Sempre que uma tarefa for concluída ela deve ser removida da lista de tarefas em aberto e acrescentada ao topo da lista de tarefas concluídas;
* O usuário não pode modificar nada na lista de tarefas concluídas.
* Sempre que uma tarefa for deletada ela deve ser removida da lista de tarefas em aberto.

Observação 1: **A página deve ser responsiva, e funcionar bem em dispositivos mobile e em computadores.**

Observação 2: **O design da página não é critério avaliativo, mas caso o candidato(a) queira fazer uma página estilizada, isso pode ser levado em consideração na hora da avaliação.**

### Desafio 3 - Modelagem de Dados

O desafio consiste em criar um programa onde uma pessoa possa escrever cartas e saber se elas foram recebidas e quanto foram recebidas. O programa deve funcionar seguindo o seguinte diagrama UML:

![Diagrama UML do Desafio 3](https://raw.githubusercontent.com/cloudgedti/teste_de_conhecimento/main/diagrama_uml_desafio_3.png)

### Submição

Os desafios devem ser colocados em um repositório e cada desafio deve ser colocado em uma pasta, por exemplo: "desafio_1", "desafio_2" e "desafio_3". O repositório com os desafios pode ser um Fork deste repositório ou não, o candidato pode criar o repositório como achar melhor.

Observação: **Os desafios devem ser enviados obrigatoriamente em um repositório no GitHub.**
