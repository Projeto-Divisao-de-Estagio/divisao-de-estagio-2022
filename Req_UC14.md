### UC14 - Listar Requerimentos
---
#### Pré-condições
O usuario precisa estar logado e constar no sistema como "ADM Divisao".

---
#### Pós-condição
O sistema apresenta uma tela com uma lista de todos os requerimentos submetidos. 

---
#### Fluxo Principal
1. Na tela principal após login, o "Usuario Logado" como "ADM Divisao" seleciona "Listar Requerimentos";
2. O sistema então seleciona todos os requerimentos submetidos pelos alunos; 
3. O sistema apresenta na tela uma lista com todos os requerimentos relacionados;

---
#### Fluxo de Exceção
1. E1 - Listagem vazia
2. E1.1 - Em caso de não houver nenhum requerimento submetido por qualquer usuário "Aluno", o sistema exibirá uma mensagem de erro. 
