# Caso de Uso: UC.1 - Logar

## Descrição
Este caso de uso descreve as ações necessárias para que um usuário não logado faça o login no sistema.

---

## Ator Principal
- Usuário não Logado

---

## Pré-condições
- Cadastro existente
- Credenciais válidas

---

## Fluxo Principal
1. O ator acessa a tela de **Login**.  
2. O ator fornece suas credenciais: usuário e senha.  
3. O ator clica em **Login**.  
4. O sistema verifica a validade das credenciais fornecidas.  
5. O sistema autentica o usuário, concedendo acesso ao sistema.  
6. O caso de uso se encerra.

---

## Fluxos Alternativos (FA)

### FA.1 - Esqueci minha senha
1. O ator clica em **Esqueci minha senha**.  
2. O sistema redireciona o usuário para o Caso de Uso **UC.3 – Recuperar Senha**.  
3. O fluxo retorna para o passo 1 do Fluxo Principal.

---

## Exceções
- Se as credenciais fornecidas forem inválidas ou não existirem no sistema, o sistema exibe uma mensagem informando o erro e solicita nova tentativa.  
- Se houver falha no envio do e-mail, ou o link de redefinição estiver expirado ou inválido, o sistema notifica o ator e oferece a opção de reiniciar o processo.  
- Se a nova senha não atender aos critérios de segurança, o sistema exibe uma mensagem com os requisitos necessários e solicita nova tentativa.

---

## Pós-condições
- O ator concluiu a autenticação da sua conta e tem acesso ao sistema.

---

## Pontos de Extensão
- N/A

---

## Referências
- RF001  
- RF003  
- UC.3

---

## Observações
Consultar as regras de negócio e as mensagens exibidas pelo sistema durante a interação com o ator.
