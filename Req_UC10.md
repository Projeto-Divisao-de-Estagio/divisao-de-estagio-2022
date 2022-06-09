### UC10 - Avaliar Relatório Final do Aluno
---
#### Pré-condições
O usuario precisa estar logado e constar no sistema como "Professor Orientador".

---
#### Pós-condição
O sistema apresenta um campo onde deve ser preenchido com o ID do documento, então o sistema faráuma busca pelo identificador digitado na listagem de relatórios finais em seu repositório e exibirá o documento selecionado na tela juntamente com os botões "Aprovar Relatório" e "Reprovar Relatório" embaixo.

---
#### Fluxo Principal
1. Na tela principal após login, o usuário seleciona "Avaliar Relatório Final do Aluno";
2. O sistema carrega uma tela com um campo "ID" a ser preenchido, e um botão "Consultar"; 
3. O usuário escreve o número de identificação do relatório no campo "ID"; 
4. O usuário após preencher o campo "ID", clica no botão "Consultar";
5. O sistema faz uma busca pelo identificador digitado na listagem de relatórios finais em seu repositório;
6. O sistema exibe o relatório final correspondente na tela juntamente com os botões "Aprovar Relatório" e "Reprovar Relatório" embaixo;

---
#### Fluxo de Exceção
1. E1 - ID inválido
2. E1.1 - Em caso de o usuário digitar um número de identificação em um formato que seja fora dos padrões estabelecidos, o sistema irá exibir na tela uma mensagem de "ID inválido".
3. E2 - ID não encontrado
4. E2.1 - Em caso do sistema não localizar o número de identificação digitado, será exibido uma mensagem na tela de "Identificador não encontrado".