## Como Utilizar

### Primeiro Acesso
1. Abrir o arquivo `login.html` no navegador  
2. Registrar um novo usuário  
3. Após o registro, o sistema redireciona automaticamente para a área principal

### Login
1. Inserir email e senha cadastrados  
2. Acesso autorizado redireciona para `index.html`

### Cadastro de Reserva
1. Acessar a aba **“Gerenciar Reservas”**  
2. Preencher todos os campos obrigatórios  
3. Clicar em **“Salvar Reserva”**

### Visualização no Calendário
1. Acessar a aba **“Calendário”**  
2. Visualizar todas as reservas em tempo real  
3. Clicar em qualquer evento para ver os detalhes

### Edição/Exclusão
- Clique no ícone de lápis para modificar
- Clique na lixeira para excluir com confirmação

---

## Segurança e Validações

- Acesso restrito a usuários autenticados
- Bloqueio de reservas em datas passadas
- Validação de horário (início deve ser anterior ao fim)
- Rastreamento de criação e modificações por usuário
- Redirecionamento automático ao sair ou expirar a sessão

---

## Configuração Firebase

**Projeto:** `suasalacravinhos`

### Serviços utilizados:
- **Firebase Authentication** (email/senha)
- **Firebase Firestore**

  ## Compatibilidade

- Responsivo para **desktops**, **tablets** e **smartphones**
- Compatível com navegadores modernos com suporte a:
  - JavaScript ES6+
  - CSS Flexbox e Grid
  - Firebase SDK 9.x

---

## Melhorias Futuras

- Notificações por email
- Verificação de disponibilidade (evitar conflitos de horário)
- Relatórios em PDF e Excel
- Níveis de permissão (admin/usuário)
- Suporte a reservas recorrentes
- Integração com Google Calendar
- Aprovação de reservas via workflow

---

## Licença

Este projeto está disponível sob a licença [MIT](LICENSE).
---

### Estrutura da coleção `reservations`:

```plaintext
clientName      # Nome do cliente
roomName        # Sala escolhida
reservationDate # Data da reserva
startTime       # Horário de início
endTime         # Horário de término
scheduledBy     # Responsável pela reserva
description     # Descrição (opcional)
createdAt       # Data de criação
createdBy       # Usuário criador
updatedAt       # Última modificação
updatedBy       # Usuário que modificou

