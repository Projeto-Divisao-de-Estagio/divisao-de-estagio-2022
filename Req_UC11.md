### UC11 - Listar Alunos Orientados
---
#### Pré-condições
O usuario precisa estar logado e constar no sistema como "Professor Orientador".

---
#### Pós-condição
O sistema apresenta uma tela com uma lista de alunos que estão sendo orientados pelo "Professor Orientador". 

---
#### Fluxo Principal
1. Na tela principal após login, o usuário seleciona "Listar Alunos Orientados";
2. O sistema então seleciona todos os usuários registrados como "Aluno" e que estão sendo orientados pelo professor orientador; 
3. O sistema apresenta na tela uma lista com todos os alunos relacionados;

---
#### Fluxo de Exceção
1. E1 - Listagem vazia
2. E1.1 - Caso o "Professor Orientador" não possua nenhum aluno que esteja sendo orientado por ele, o sistema exibirá uma mensagem de erro. 

