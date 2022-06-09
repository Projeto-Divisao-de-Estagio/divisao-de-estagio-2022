### UC15 - Consultar Requerimento
---
#### Pré-condições
O usuário precisa estar logado e constar no sistema como "ADM Divisao".

---
#### Pós-condição
Retorna o requerimento requisitado pelo usuário.  

---
#### Fluxo Principal
1. Na tela principal após login, o "Usuario Logado" como "ADM Divisao" seleciona "Listar Requerimentos";
2. O sistema então lista todos os requerimentos submetidos pelos alunos;
3. O usuário seleciona um requerimento da lista clicando no botão "Consultar";
4. O sistema faz uma busca pelo detalhamento do requerimento selecionado em seu repositório;
5. O sistema exibe o requerimento correspondente na tela juntamente com todas as informações referentes ao mesmo;

---
#### Fluxo de Exceção
1. E1 - Listagem vazia
2. E2 - Requerimento não encontrado
3. E2.1 - Em caso do sistema não localizar requerimento, será exibida uma mensagem na tela de "Requerimento não encontrado".
