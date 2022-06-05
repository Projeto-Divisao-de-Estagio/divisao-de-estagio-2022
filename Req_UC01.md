### UC01 - Trocar a Senha
---
#### Pré-condições
Ator precisa estar cadastrado no sistema

---
#### Pós-condição
Link com redefinição de senha é enviado para o email

---
#### Fluxo Principal
1. Na tela de login o "Usuario não logado" seleciona "Esqueceu a senha";
2. É carregado um sistema onde o "Usuario não logado" informa seu email;
3. O sistema envia um link para redefinição de senha

---
#### Fluxo de Exceção
1. E1 - Email não cadastrado
2. E1.1 - Caso o email não esteja presente no banco de dados, o sistema informa "Este email não esta no nosso sistema" e o usurio continua no passo 2 do Fluxo Principal.
