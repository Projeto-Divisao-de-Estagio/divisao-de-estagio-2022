# Especificação dos Requisitos do SGDE

### Diagrama de Casos de Uso
<div hidden>
```
@startuml diagrama_de_caso_de_uso
skinparam actorStyle awesome
left to right direction

"Usuario Nao Logado" as NLogado
"Usuario Logado" as Logado
"Aluno" as Aluno
"Professor Orientador" as Professor	
"ADM Divisao" as Admin

Logado <|-- Aluno
Logado <|-- Professor
Logado <|-- Admin

package Acesso_Publico {
  NLogado --> (Cadastrar)
  NLogado --> (Login)
  NLogado --> (Esqueceu a senha)
}

package Acesso_Restrito {
  usecase "Trocar a senha" as UC1
  usecase "Logoff" as UC2 
  usecase "Requisitar Formulario" as UC3
  usecase "Acompanhar Requirimento" as UC4
  usecase "Upload de Termo de Compromisso" as UC5
  usecase "Submeter Relatorio" as UC6
  usecase "Avaliar Relatorio Final do Aluno" as UC7
  usecase "Consultar Acompanhamento de Alunos" as UC8
  usecase "Consultar Relatorio Final" as UC9
  usecase "Listar Relatorios Finais" as UC10
  usecase "Listar Requerimentos" as UC11
  usecase "Consultar Requerimento" as UC12
  usecase "Cadastrar Professor" as UC13
  usecase "Remover Professor" as UC14
  UC7 .> (Assinar Relatorio) : include
  UC9 .> (Assinar Relatorio) : include
  UC3 .> (Solicitar Professor) : dependency 
}

Logado --> UC1
Logado --> UC2
Aluno --> UC3
Aluno --> UC4
Aluno --> UC5
Aluno --> UC6 
Professor --> UC7
Professor --> UC8
Admin --> UC9
Admin --> UC10
Admin --> UC11
Admin --> UC12
Admin --> UC13
Admin --> UC14
@enduml
```
</div>

![](diagrama_de_caso_de_uso.svg)