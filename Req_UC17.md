### UC17 - Remover professor da lista de professores orientadores
---
#### Pré-condições
O usuário precisa estar logado e constar no sistema como "ADM Divisao".

---
#### Pós-condição
O usuário "Professor Orientador" selecionado é efetivamente removido do sistema.  

---
#### Fluxo Principal
1. Na tela principal após login, o "Usuario Logado" como "ADM Divisao" seleciona "Remover professor orientador";
2. O sistema abre uma lista com todos os usuários do tipo "Professor Orientador";
3. O usuário seleciona um professor da lista e clica em remover;
4. O sistema mostra um modal de confirmação se o usuário deseja realmente remover o professor;
5. O usuário clica no botão de confirmação para remover o professor.
6. O sistema checa se o usuário "Professor Orientador" existe e o remove;
7. O sistema exibe uma mensagem de "Professor removido com sucesso";
8. O usuário atual é redirecionado para a tela principal pós login;

---
#### Fluxos Alternativos
1. Na tela principal após login, o "Usuario Logado" como "ADM Divisao" seleciona "Remover professor orientador";
2. O sistema abre uma lista com todos os usuários do tipo "Professor Orientador";
3. O usuário seleciona um professor da lista e clica em remover;
4. O sistema mostra um modal de confirmação se o usuário deseja realmente remover o professor;
5. O usuário clica no botão de cancelar do modal.
6. O sistema volta para a tela com a listagem de usuários do tipo "Professor Orientador";

---
#### Fluxo de Exceção
1. E1 - Usuário não encontrado no sistema
2. E1.1 - Em caso do usuário selecionado não ser encontrado no sistema, será exibida na tela uma mensagem de erro "Usuário não encontrado".
