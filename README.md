🏢 Sistema de Reservas de Salas
Um sistema completo de gerenciamento de reservas de salas com autenticação via Firebase, interface moderna, calendário interativo e funcionalidades CRUD.

🚀 Funcionalidades
🔐 Autenticação
Login e registro de usuários com Firebase Authentication

Proteção de rotas: apenas usuários autenticados acessam o sistema

Interface de login/registro moderna e responsiva

📅 Calendário de Reservas
Visualização em calendário mensal, semanal e diário

Interface com FullCalendar (versão 6.1.8) com suporte a português

Eventos com cores distintas para fácil identificação

Clique em eventos para ver detalhes da reserva

🧾 CRUD de Reservas
Criar: formulário com validações

Ler: listagem em tabela organizada

Atualizar: edição via modal

Deletar: exclusão com confirmação

📋 Campos da Reserva
Nome do Cliente

Sala (5 opções fixas)

Data da reserva

Horário de início e fim

Responsável pelo agendamento

Descrição (opcional)

🎨 Interface Moderna
Design com Bootstrap 5

Navegação por abas: Calendário / Gerenciar Reservas

Gradientes, efeitos visuais e feedback de ações

🛠️ Tecnologias Utilizadas
| Área              | Tecnologias                    |
| ----------------- | ------------------------------ |
| **Frontend**      | HTML5, CSS3, JavaScript (ES6+) |
| **Framework CSS** | Bootstrap 5                    |
| **Calendário**    | FullCalendar 6.1.8             |
| **Backend**       | Firebase Firestore (NoSQL)     |
| **Autenticação**  | Firebase Authentication        |
| **Ícones**        | Font Awesome 6                 |

📁 Estrutura de Arquivos
reservas-salas/
├── index.html          # Página principal do sistema
├── login.html          # Página de login/registro
└── README.md           # Este arquivo

🔧 Como Usar
1. Primeiro Acesso
Abra login.html no navegador

Clique em Registrar para criar conta

Preencha os dados e aceite os termos

Após registrar, você será redirecionado ao sistema

2. Login
Informe email e senha na tela de login

Clique em Entrar

Você será redirecionado para index.html

3. Gerenciar Reservas
Acesse a aba Gerenciar Reservas

Preencha os campos obrigatórios

Clique em Salvar Reserva

4. Visualizar no Calendário
Vá para a aba Calendário

Veja reservas como eventos coloridos

Clique para visualizar os detalhes

5. Editar ou Excluir
Clique no ícone de lápis para editar (modal)

Clique na lixeira para excluir (com confirmação)

🔒 Segurança
Autenticação obrigatória com Firebase

Validação de dados no formulário

Rastreamento de quem criou/atualizou a reserva

Logout com redirecionamento seguro

🧪 Validações
❌ Datas passadas são bloqueadas

⏰ Horário de início deve ser antes do fim

✅ Todos os campos são obrigatórios (exceto descrição)

🔐 Redirecionamento automático se o usuário não estiver autenticado

🗂️ Configuração do Firebase
Projeto Firebase: suasalacravinhos

Authentication: Email/Senha

Firestore: Coleção reservations com campos:
clientName      # Nome do cliente
roomName        # Nome da sala
reservationDate # Data
startTime       # Início
endTime         # Fim
scheduledBy     # Quem agendou
description     # (Opcional)
createdAt       # Data de criação
createdBy       # Usuário que criou
updatedAt       # (Se editado)
updatedBy       # (Se editado)

🏢 Salas Disponíveis
Sala de Reunião A

Sala de Reunião B

Sala de Conferência

Auditório

Sala de Treinamento

📱 Responsividade e Compatibilidade
✔️ Compatível com:

Desktops

Tablets

Smartphones

✔️ Suporte a navegadores modernos:

JavaScript ES6+

CSS Grid e Flexbox

Firebase SDK v9+

📈 Melhorias Futuras Sugeridas
📩 Notificações por email

❗ Verificação de conflitos de horário

📊 Relatórios em PDF/Excel

🔐 Níveis de acesso (admin/usuário)

🔁 Reservas recorrentes

📆 Integração com Google Calendar

✅ Workflow de aprovação de reservas
