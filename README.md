# Kairós - Gestor de Hábitos Diários

## Resumo do Projeto
O Kairós é uma aplicação para acompanhamento de metas e rotinas diárias. O objetivo é permitir que os usuários criem hábitos, acompanhem sua frequência diária e visualizem estatísticas de consistência ao longo do tempo. A plataforma conta com um aplicativo Mobile nativo para marcação rápida de tarefas no dia a dia e uma interface Web voltada para gestão de hábitos e visualização de relatórios.

## Funcionalidades

### Autenticação e Usuário
* Cadastro e login de usuários (Web e Mobile).
* Edição de perfil básico e preferências.

### Gestão de Hábitos
* Criação, edição e exclusão de hábitos (ex.: "Beber 2L de água", "Ler 15 min", "Exercício").
* Definição de frequência (diária ou dias específicos da semana).
* Categorização de hábitos por tags/cores (ex.: Saúde, Estudo, Produtividade).

### Registro e Check-in (Core Mobile)
* Lista diária de hábitos para marcação simples (check/uncheck).
* Contador de ofensivas/sequência de dias consecutivos (streaks).

### Relatórios e Histórico (Core Web)
* Painel com calendário visual mostrando os dias concluídos.
* Gráfico de taxa de conclusão semanal e mensal.

## Tecnologias Propostas
* **Backend:** Node.js (Express ou NestJS) com SQLite/PostgreSQL.
* **Frontend Web:** React (Vite).
* **Frontend Mobile:** React Native (Expo).
