### UC02 - Login
---
#### Pré-condições
"Usuario Não Logado" não estar logado no sistema

---
#### Pós-condição
"Usuario não logado" loga efetivamente no sistema e passa a ser um "Usuario Logado" do tipo: "Aluno", "Professor" ou "ADM Divisão", com suas devidas funções disponiveis. 

---
#### Fluxo Principal
1. Na tela de principal o "Usuario não logado" seleciona "Login";
2. É carregado uma tela onde o "Usuario não logado" informa seu email e senha;
3. O sistema checa se o par email-senha está correto;
4. "Login efetuado com sucesso" e o agora "Usuario Logado" é redirecionado para área logada do sistema.

---
#### Fluxo de Exceção
1. E1 - Email/senha incorreto(s)
2. E1.1 - Caso email ou senha estejam incorretos, o sistema retorna a mensagem "Email/senha incorrreto(s). Tente novamente." e o "Usuario Não Logado" continua no passo 2 do Fluxo Principal.
3. E2 - Email/senha não informado(s)
4. E2.1 - Caso email ou senha não tenham sido informados, o sistema retorna a mensagem "Email/senha não informado(a). Tente novamente." e o "Usuario Não Logado" continua no passo 2 do Fluxo Principal.
