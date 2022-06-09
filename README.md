# SGDE
Sistema de gerenciamento para a Divisão de Estágio da POLI-UPE

## Diagrama de Casos de Uso
![DiagramaCasoDeUso](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/Projeto-Divisao-de-Estagio/divisao-de-estagio-2022/master/DiagramaCasoDeUso.iuml)

## Especificação dos Requisitos do SGDE
#### Lista de Requisitos Funcionais
- RF01 - O sistema requer uma página de login com usuário e senha
- RF02 - Caso o usuario não seja cadastrado, o sistema deve fornecer uma forma de cadastramento
- RF03 - O sistema deve ser capaz de enviar um link para o email do usuário para recuperar a sua senha
- RF04 - O sistema deve permitir a troca de senha, mediante o acesso pelo link enviado previamente ao email do usuario
- RF05 - O sistema deve permitir a saída do usuario via logoff
- RF06 - O sistema deve permitir ao usuario logado, como aluno, o preenchimento do requerimento para autorizar a realização de estagio na empresa informada
- RF07 - O sistema deve permitir ao usuario logado, como aluno, acompanhar o andamento do requerimento realizado anteriormente
- RF08 - O sistema deve permitir ao usuario logado, como aluno, o envio do termo de compromisso assinado pela empresa
- RF09 - O sistema deve permitir ao usuario logado, como aluno, o envio do relatorio final de estagio com a avaliação da empresa
- RF10 - O sistema deve permitir ao usuario logado, como professor orientador, listar os alunos que ele está orientando
- RF11 - O sistema deve permitir ao usuario logado, como professor orientador, avaliar o relatorio final enviado por um dos alunos que ele está acompanhando
- RF12 - O sistema deve permitir ao usuario logado, como divisão de estagio, consultar e assinar relatorio final enviado por aluno
- RF13 - O sistema deve permitir ao usuario logado, como divisão de estagio, listar os relatorios finais enviados por alunos
- RF14 - O sistema deve permitir ao usuario logado, como divisão de estagio, listar requerimentos solicitados por alunos
- RF15 - O sistema deve permitir ao usuario logado, como divisão de estagio, consultar requerimento
- RF16 - O sistema deve permitir ao usuario logado, como divisão de estagio, cadastar professor para a orientação de alunos
- RF17 - O sistema deve permitir ao usuario logado, como divisão de estagio, remover professor da lista de professores orientadores

#### Lista de Requisitos Não-Funcionais
- RNF01 - O sistema será acessado através de um login e senha cadastrados pelo proprio usuario. O usuário possuirá um login e senha de uso individual e unico.
- RNF02 - Dados dos usuários devem ser protegidos. Devem ser criptografados e inseridos em um banco de dados seguro.
- RNF03 - O sistema possuirá três níveis de acesso, sendo eles aluno, professor e divisão de estágio (administrador), com privilégios distintos. O nível de acesso definirá as permissões de cada usuário, sendo divisão de estágio, o usuário com mais privilégios no sistema.
- RNF04 - O sistema deve tornar o acesso o mais amigavel possivel, para o correto desempenho das tarefas
- RNF05 - O sistema deve prover comunicação entre as partes envolvidas de forma segura
- RNF06 - O sistema deve fornecer mecanismos para a realização de assinatura digital e envio de documentos

#### Especificicações de Casos de Uso
- [UC_01](Req_UC01.md)
- [UC_02](Req_UC02.md)
- [UC_03](Req_UC03.md)
- [UC_04](Req_UC04.md)
- [UC_05](Req_UC05.md)
- [UC_11](Req_UC11.md)
