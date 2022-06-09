### UC12 - Consultar Relatório Final
---
#### Pré-condições
O usuário precisa estar logado e constar no sistema como "ADM Divisao".

---
#### Pós-condição
Retorna o relatório requisitado pelo usuário, e após análise do mesmo, atualiza o status do relatório final no sistema.  

---
#### Fluxo Principal
1. Na tela principal após o login, o administrador seleciona "Consultar Relatório Final";
2. O sistema carrega uma tela com um campo "ID" a ser preenchido somente por números, e um botão "Consultar"; 
3. O usuário escreve o número de identificação do relatório no campo "ID"; 
4. O usuário após preencher o campo "ID", clica no botão "Consultar";
5. O sistema faz uma busca pelo identificador digitado na listagem de relatórios finais em seu repositório;
6. O sistema exibe o relatório final correspondente na tela juntamente com os botões "Assinar relatório" e "Recusar Assinatura" embaixo;    
7. O administrador verifica o relatório final;
8. Caso aprove o relatório, o administrador então clica no botão "Assinar relatório";
9. O sistema então abrirá uma nova tela onde uma assinatura eletrônica será acrescentada ao relatório final;
10. O sistema exibirá uma mensagem escrita "Relatório assinado com sucesso" na tela;
11. O status do relatório final constará como aprovado e será atualizado no sistema;

---
#### Fluxos Alternativos
1. Na tela principal após o login, o administrador seleciona "Consultar Relatório Final";
2. O sistema carrega uma tela com um campo "ID" a ser preenchido somente por números, e um botão "Consultar"; 
3. O usuário escreve o número de identificação do relatório no campo "ID"; 
4. O usuário após preencher o campo "ID", clica no botão "Consultar";
5. O sistema faz uma busca pelo identificador digitado na listagem de relatórios finais em seu repositório;
6. O sistema exibe o relatório final correspondente na tela juntamente com os botões "Assinar relatório" e "Recusar Assinatura" embaixo;    
7. O administrador verifica o relatório final;
8. Caso desaprove o relatório por constatar alguma irregularidade, o administrador então clica no botão "Recusar Assinatura";
9. O sistema então mostrará uma campo de texto a ser preenchido especificando o motivo pelo qual o relatório foi recusado e um botão "Enviar";
10. O usuário preenche o campo de texto com o motivo;
11. O usuário após preencher o campo de texto com o motivo, clica no botão "Enviar";
12. O sistema irá exibir uma mensagem informando que o "Relatório foi devolvido";
13. O status do relatório final constará como devolvido e será atualizado no sistema;

---
#### Fluxo de Exceção
1. E1 - ID inválido
2. E1.1 - Em caso de o usuário digitar um número de identificação em um formato que seja fora dos padrões estabelecidos, o sistema irá exibir na tela uma mensagem de "ID inválido".
3. E2 - ID não encontrado
4. E2.1 - Em caso do sistema não localizar o número de identificação digitado, será exibido uma mensagem na tela de "Identificador não encontrado".
