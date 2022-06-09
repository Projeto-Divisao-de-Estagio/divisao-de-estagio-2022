### UC06 - Preencher Requerimento
---
#### Pré-condições
O usuario precisa estar logado e constar no sistema como "Aluno".

---
#### Pós-condição
O sistema apresenta uma tela com campos para preenchimento de um formulário com os dados da empresa em que deseja estagiar e deve indicar quem será seu professor orientador. Ao final do preenchimento, o aluno deve clicar em enviar.

---
#### Fluxo Principal
1. Na tela principal após login, o usuário seleciona "Preencher Requerimento";
2. O sistema então apresenta uma janela com um formulário para ser preenchido;
3. Após o aluno clicar em enviar, o sistema deve notificar o professor requerido pelo aluno, sobre a solicitação para ser seu orientador;

---
#### Fluxo de Exceção
1. E1 - Todos os campos devem ser preenchidos, caso não, o sistema exibirá uma mensagem de erro