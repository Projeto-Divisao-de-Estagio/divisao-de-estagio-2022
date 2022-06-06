# SGDE
Sistema de gerenciamento para a Divisão de Estágio da POLI-UPE

# Especificação dos Requisitos do SGDE
## Requisitos Funcionais
### Lista de Requisitos Funcionais
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

### Lista de Requisitos Não-Funcionais
## Diagrama de Casos de Uso
![DiagramaCasoDeUso](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/Projeto-Divisao-de-Estagio/divisao-de-estagio-2022/master/DiagramaCasoDeUso.iuml)