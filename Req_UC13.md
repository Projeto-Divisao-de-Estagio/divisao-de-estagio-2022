### UC13 - Listar Relatórios Finais
---
#### Pré-condições
O usuario precisa estar logado e constar no sistema como "ADM Divisao".

---
#### Pós-condição
O sistema apresenta uma tela com uma lista de todos os relatórios finais. 

---
#### Fluxo Principal
1. Na tela principal após o login, o "Usuario Logado" como "ADM Divisao" seleciona "Listar Relatórios Finais";
2. O sistema então seleciona todos os relatórios finais submetidos pelos alunos; 
3. O sistema apresenta na tela uma lista com todos os relatórios finais relacionados;

---
#### Fluxo de Exceção
1. E1 - Listagem vazia
2. E1.1 - Em caso de não houver nenhum relatório final submetido por qualquer usuário "Aluno", o sistema exibirá uma mensagem de erro. 