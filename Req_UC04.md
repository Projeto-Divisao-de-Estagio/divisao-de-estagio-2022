### UC04 - Trocar a senha
---
#### Pré-condições
"Usuario logado" deve estar logado no sistema.

---
#### Pós-condição
Senha alterada. 

---
#### Fluxo Principal
1. "Usuario Logado" escolhe opção "Trocar Senha";
2. É carregado uma tela onde o "Usuario Logado" preenche os campos de: "senha atual", "nova senha" e "repetir nova senha";
3. O sistema checa se a "senha atual" está correta, se a "nova senha" atende os requerimentos impostos pelo sistema e se "repetir nova senha" é igual a "nova senha";
4. Sistema envia um email informando a troca de senha;
5. Sistema retorna a mensagem "Senha alterada com sucesso".

---
#### Fluxo de Exceção
1. E1 - "Senha Atual" incorreta
2. E1.1 - Caso a "senha atual" informada esteja incorretos, o sistema retorna a mensagem "Senha incorrreta. Tente novamente." e o "Usuario Logado" continua no passo 2 do Fluxo Principal.
3. E2 - "Nova Senha" é curta
4. E2.1 - Caso a "nova senha" informada pelo "Usuario Não Logado" seja menor que o limite mínimo imposto pelo sistema, retornar a mensagem "Sua senha deve ter no minimo 8 caracteres" e o "Usuario Logado" continua no passo 2 do Fluxo Principal.
5. E3 - "Nova senha" e "repetir nova senha" com valores diferentes
6. E3.1 - Caso os campos de "nova senha" e "repetir nova senha" tenham valores diferentes, o sistema retorna a mensagem "Campos com valores diferentes." e o "Usuario Logado" continua no passo 2 do Fluxo Principal.
