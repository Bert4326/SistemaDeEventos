# SistemaDeEventos
Atividade Pratique - Criar um sistema de cadastro e notificação de eventos.
# 📅 Sistema de Cadastro e Notificação de Eventos

Este é um sistema de cadastro e notificação de eventos, desenvolvido em Java no console, utilizando o paradigma de programação orientada a objetos (POO).

## 🎯 Funcionalidades

- Cadastro de usuários
- Cadastro de eventos
- Categorias de eventos (Show, Festa, Evento Esportivo, etc.)
- Listagem de eventos ordenados por data e horário
- Confirmação e cancelamento de participação em eventos
- Consulta de eventos em que o usuário confirmou participação
- Identificação de eventos já ocorridos e em andamento
- Salvamento e carregamento dos eventos através do arquivo `events.data`

## 🗂️ Estrutura de Pastas

/EventoApp
├── src
│ ├── Main.java
│ ├── models
│ │ ├── Usuario.java
│ │ └── Evento.java
│ └── services
│ └── GerenciadorDeEventos.java
└── events.data (arquivo salvo automaticamente)

bash
Copiar código

## 🚀 Como Executar

1. Clone este repositório:
 git clone https://github.com/seu-usuario/SistemaDeEventos.git

2. Abra o projeto na sua IDE (Eclipse, IntelliJ IDEA, NetBeans ou Replit).

3. Execute o arquivo Main.java.

O programa será executado no console, onde você pode interagir com o menu para cadastrar usuários, eventos e gerenciar participações.

💾 Salvamento dos Dados
Os eventos são salvos no arquivo events.data.

Ao abrir novamente o programa, os eventos cadastrados serão carregados automaticamente.


