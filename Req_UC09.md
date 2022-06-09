### UC09 - Envio de Relatório Final
---
#### Pré-condições
O usuario precisa estar logado e constar no sistema como "Aluno".

---
#### Pós-condição
O sistema apresenta uma tela com um campo onde o aluno deve fazer o upload do relatorio final com a avaliação da empresa em anexo. Ao final do upload, o aluno deve clicar em enviar. Após o envio, o professor orientador selecionado pelo aluno deve ser notificado para posterior avaliação e mediante aprovação, submeter sua assinatura digital.

---
#### Fluxo Principal
1. Na tela principal após login, o usuário seleciona "Envio de Relatório Final";
2. O sistema então apresenta uma janela com um campo onde o aluno deve fazer o upload do relatorio final com a avaliação da empresa em anexo;
3. Após o aluno clicar em enviar, o relatório final será registrado com um "ID" que é um número de identificação daquele documento e o professor orientador selecionado pelo aluno será notificado para posterior avaliação e mediante aprovação, submeter sua assinatura digital;

---
#### Fluxo de Exceção
1. E1 - O sistema só deve permitir o envio, caso o aluno tenha realizado o requerimento e se o seu termo de compromisso tiver sido assinado pelo seu professor orientador.