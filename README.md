# Casa de Apostas Moderna

Uma aplicação web moderna e elegante para casa de apostas esportivas, desenvolvida com React, Node.js e MongoDB.

## Funcionalidades

- 🎯 Interface moderna e responsiva
- 🔐 Autenticação segura de usuários
- 💰 Gerenciamento de saldo e transações
- 🏆 Apostas em diversos esportes
- 📊 Histórico de apostas
- 🔔 Notificações em tempo real
- 🌐 Suporte a múltiplos idiomas
- 💳 Integração com gateways de pagamento

## Tecnologias Utilizadas

### Frontend
- React.js
- Material-UI
- React Router
- Axios
- Socket.io-client

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Socket.io
- Bcrypt

## Pré-requisitos

- Node.js (v14 ou superior)
- MongoDB
- NPM ou Yarn

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/casa-de-apostas.git
cd casa-de-apostas
```

2. Instale as dependências do backend:
```bash
npm install
```

3. Instale as dependências do frontend:
```bash
cd client
npm install
cd ..
```

4. Configure as variáveis de ambiente:
- Copie o arquivo `.env.example` para `.env`
- Preencha as variáveis com seus valores

5. Inicie o servidor de desenvolvimento:
```bash
# Terminal 1 - Backend
npm run dev

# Terminal 2 - Frontend
npm run client
```

## Estrutura do Projeto

```
casa-de-apostas/
├── client/                 # Frontend React
│   ├── public/            # Arquivos estáticos
│   └── src/               # Código fonte React
│       ├── components/    # Componentes React
│       ├── pages/         # Páginas da aplicação
│       ├── context/       # Contexto React
│       └── services/      # Serviços e APIs
├── models/                # Modelos Mongoose
├── routes/                # Rotas da API
├── middleware/            # Middlewares
├── config/               # Configurações
└── server.js             # Entrada do servidor
```

## API Endpoints

### Autenticação
- POST /api/auth/register - Registrar novo usuário
- POST /api/auth/login - Login de usuário
- GET /api/auth/usuario - Obter dados do usuário

### Usuários
- GET /api/usuarios/perfil - Obter perfil
- PUT /api/usuarios/perfil - Atualizar perfil
- PUT /api/usuarios/senha - Alterar senha
- POST /api/usuarios/deposito - Realizar depósito
- POST /api/usuarios/saque - Solicitar saque
- GET /api/usuarios/saldo - Obter saldo

### Apostas
- POST /api/apostas - Criar nova aposta
- GET /api/apostas - Listar apostas
- GET /api/apostas/:id - Obter aposta específica
- PUT /api/apostas/:id/cancelar - Cancelar aposta
- GET /api/apostas/ativas - Listar apostas ativas
- GET /api/apostas/historico - Obter histórico

## Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

## Contato

Seu Nome - [@seutwitter](https://twitter.com/seutwitter) - email@exemplo.com

Link do Projeto: [https://github.com/seu-usuario/casa-de-apostas](https://github.com/seu-usuario/casa-de-apostas) 