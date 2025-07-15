# Sistema de Reservas de Salas

Uma solução completa para gerenciamento de reservas de salas comerciais, com autenticação segura, visualização em calendário e interface responsiva. Ideal para coworkings, escritórios e centros de eventos.

---

## Visão Geral

Este sistema oferece uma plataforma moderna para agendamento de salas, combinando praticidade, segurança e controle. Permite o gerenciamento completo de reservas com acesso restrito a usuários autenticados.

---

## Principais Funcionalidades

### Autenticação
- Login e registro de usuários com **Firebase Authentication**
- Controle de sessão com redirecionamento seguro
- Proteção de rotas: apenas usuários autenticados acessam o sistema

### Calendário de Reservas
- Visualização em formatos **mensal**, **semanal** e **diário**
- Interface com **FullCalendar** (localizada em português)
- Eventos com **cores distintas** para facilitar a identificação
- Acesso rápido aos **detalhes das reservas**

### Gerenciamento de Reservas (CRUD)
- Cadastro de novas reservas com **validação de dados**
- Edição de reservas existentes via **modal**
- Exclusão com confirmação
- Listagem completa em formato de **tabela**

### Campos da Reserva
- Nome do cliente
- Sala (cinco opções fixas)
- Data da reserva
- Horário de início e término
- Responsável pelo agendamento
- Descrição (opcional)

---

## Salas Disponíveis

1. Sala de Reunião A  
2. Sala de Reunião B  
3. Sala de Conferência  
4. Auditório  
5. Sala de Treinamento

---

## Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Framework CSS**: Bootstrap 5
- **Calendário**: FullCalendar 6.1.8
- **Autenticação**: Firebase Authentication
- **Banco de Dados**: Firebase Firestore (NoSQL)
- **Ícones**: Font Awesome 6

---

## Estrutura de Arquivos

```plaintext
reservas-salas/
├── index.html          # Página principal
├── login.html          # Tela de login e cadastro
└── README.md           # Documentação
