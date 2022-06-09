### UC16 - Cadastrar professor para a orientação de alunos
---
#### Pré-condições
O usuário precisa estar logado e constar no sistema como "ADM Divisao".

---
#### Pós-condição
O "Novo professor" é efetivamente registrado como "Professor Orientador" no sistema.  

---
#### Fluxo Principal
1. Na tela principal após login, o "Usuario Logado" como "ADM Divisao" seleciona "Cadastrar professor orientador";
2. O sistema abre um espaço com campos para adicionar as informações do novo usuário "Professor Orientador" que será cadastrado;
3. O sistema checa se o novo usuário já não existe no sistema e se as informações respeitam todas as validações;
4. O sistema cadastra o novo "Professor Orientador";
5. O sistema exibe uma mensagem de "Cadastro feito com sucesso";
6. O sistema envia um email de boas vindas para o email do novo usuário cadastrado.
7. O usuário atual é redirecionado para a tela principal pós login; 

---
#### Fluxo de Exceção
1. E1 - Usuário já existe no sistema
2. E1.1 - Em caso das informações únicas do novo usuário já existirem no sistema, será exibida na tela uma mensagem de erro "Usuário já cadastrado".
3. E2 - Validações não foram atendidas
4. E2.1 - Em caso dos campos não serem preenchidos com os formatos corretos estabelecidos pelo sistema, ou houver campos obrigatórios faltantes, será exibida na tela uma mensagem de erro específica para a validação não atendida.
