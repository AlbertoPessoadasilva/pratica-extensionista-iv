# Práticas Extensionistas IV

## Descrição do Projeto
Problema/Domínio: Este projeto modela um **Sistema de Gerenciamento de Tarefas Online**, uma aplicação web onde usuários podem criar, editar, deletar e priorizar tarefas, com autenticação de login e armazenamento em banco de dados. A solução abrange interface de usuário, lógica de negócios e persistência de dados, sendo um exemplo prático de sistema de informação escalável.

## Diagramas
- [Diagrama UML de Pacotes](diagrama_uml.png)  
  Descrição: Representa a arquitetura em camadas (MVC) da aplicação, com pacotes Frontend, Backend e Data Layer, incluindo dependências como `<<depends>>` e `<<import>>`.
- [Diagrama de Implantação](diagrama_implantacao.png)  
  Descrição: Mostra a infraestrutura física com nodes para Cliente Usuário (browser.exe), Servidor Aplicação (backend.jar) e Servidor Banco de Dados (tarefas.db), conectados por `<<HTTP>>` e `<<SQL>>`.
- [Diagrama de Arquitetura DevOps](diagrama_devops.png)  
  Descrição: Ilustra o pipeline CI/CD com etapas Code, Build, Test, Deploy e Monitor, incluindo ferramentas como GitHub e AWS, e fluxo de correção (`Se falhar`).

## Escolha de Infraestrutura Cloud
Escolha: AWS (Amazon Web Services) por oferecer free tier de 1 ano, e possuir liderança de mercado (30% em 2025) e escalabilidade. 

## Aluno
- Alberto Pessoa da Silva
