### UC01 - Cadastrar
---
#### Pré-condições
"Usuario Não Logado" não tem registro prévio no sistema

---
#### Pós-condição
"Usuario não logado" é efetivamente registrado como "Aluno" no sistema. 

---
#### Fluxo Principal
1. Na tela de principal o "Usuario não logado" seleciona "Cadastrar";
2. É carregado uma tela onde o "Usuario não logado" informa seus dados;
3. O sistema checa se o email informado é válido e se a senha atende todos os requerimentos;
4. Sistema envia um email de confirmação de cadastro para o email informado pelo "Usuario Não Logado";
5. O sistema retorna uma mensagem de "Cadastro feito com sucesso".

---
#### Fluxo de Exceção
1. E1 - Email já cadastrado
2. E1.1 - Caso o email já esteja presente no banco de dados, o sistema informa "Este email já está em uso" e o "Usuario Não Logado" continua no passo 2 do Fluxo Principal.
3. E2 - Senha Curta
4. E2.1 - Caso a senha informada pelo "Usuario Não Logado" seja menor que o limite mínimo imposto pelo sistema, retornar a mensagem "Sua senha deve ter no minimo 8 caracteres" e o "Usuario Não Logado" continua no passo 2 do Fluxo Principal.
