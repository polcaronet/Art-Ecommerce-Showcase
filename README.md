# 🛒 Art E-commerce

> Sistema completo de E-commerce desenvolvido com tecnologias modernas

[![Private Repository](https://img.shields.io/badge/code-private-red)](https://github.com)
[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)](https://github.com)

## 📋 Sobre o Projeto

Art E-commerce é uma plataforma completa de comércio eletrônico desenvolvida com arquitetura separada entre Backend e Frontend, garantindo escalabilidade, manutenibilidade e performance.

## 🎯 Funcionalidades

### 🔐 Autenticação e Autorização

- Sistema de login e registro de usuários
- Autenticação JWT
- Diferentes níveis de permissão (Admin/Cliente)

### 🛍️ Catálogo de Produtos

- Listagem de produtos com filtros avançados
- Busca inteligente
- Categorização de produtos
- Detalhes completos com imagens

### 🛒 Carrinho de Compras

- Adicionar/remover produtos
- Atualizar quantidades em tempo real
- Cálculo automático de totais e descontos

### 💳 Sistema de Pagamento

- Integração com gateway de pagamento
- Múltiplas formas de pagamento
- Confirmação de pedidos por email

### 📦 Gestão de Pedidos

- Histórico completo de compras
- Rastreamento de pedidos
- Status em tempo real
- Notificações de atualização

### ⚙️ Painel Administrativo

- Gerenciamento completo de produtos
- Controle de estoque
- Gestão de pedidos e clientes
- Relatórios e estatísticas detalhadas
- Dashboard com métricas

## 🚀 Tecnologias Utilizadas

### Backend

- **Node.js** - Ambiente de execução JavaScript
- **Express** - Framework web minimalista e rápido
- **MongoDB** - Banco de dados NoSQL
- **Mongoose** - ODM para MongoDB
- **JWT** - Autenticação segura
- **Bcrypt** - Criptografia de senhas
- **Multer** - Upload de arquivos e imagens
- **Nodemailer** - Envio de emails

### Frontend

- **React** - Biblioteca JavaScript para interfaces
- **TypeScript** - Superset JavaScript com tipagem estática
- **Tailwind CSS** - Framework CSS utilitário
- **Axios** - Cliente HTTP para requisições
- **React Router** - Navegação entre páginas
- **Context API** - Gerenciamento de estado global
- **React Hook Form** - Gerenciamento de formulários
- **React Query** - Cache e sincronização de dados

### DevOps & Tools

- **Git** - Controle de versão
- **ESLint** - Linting de código
- **Prettier** - Formatação de código
- **Docker** - Containerização (opcional)

## 🏗️ Arquitetura

```
Art-Ecommerce/
├── Backend/                 # API REST
│   ├── src/
│   │   ├── controllers/    # Lógica de negócio
│   │   ├── models/         # Schemas do banco de dados
│   │   ├── routes/         # Definição de rotas
│   │   ├── middlewares/    # Autenticação, validação
│   │   ├── config/         # Configurações (DB, JWT, etc)
│   │   └── utils/          # Funções auxiliares
│   ├── .env.example        # Exemplo de variáveis
│   ├── package.json
│   └── server.js           # Entrada da aplicação
│
└── Frontend/               # Interface do usuário
    ├── public/             # Arquivos públicos
    ├── src/
    │   ├── components/     # Componentes reutilizáveis
    │   │   ├── common/    # Botões, Cards, etc
    │   │   ├── layout/    # Header, Footer, Sidebar
    │   │   └── products/  # Componentes de produtos
    │   ├── pages/          # Páginas da aplicação
    │   │   ├── Home/
    │   │   ├── Products/
    │   │   ├── Cart/
    │   │   ├── Checkout/
    │   │   └── Admin/
    │   ├── services/       # Chamadas à API
    │   ├── hooks/          # Custom hooks
    │   ├── context/        # Contextos globais
    │   ├── utils/          # Funções auxiliares
    │   └── assets/         # Imagens, ícones
    ├── .env.example
    └── package.json
```

## 📱 Screenshots

> 🚧 Em breve: capturas de tela da aplicação em funcionamento

<!-- Descomente quando adicionar as imagens
### Página Inicial
![Home](./screenshots/home.png)

### Catálogo de Produtos
![Products](./screenshots/products.png)

### Carrinho de Compras
![Cart](./screenshots/cart.png)

### Painel Administrativo
![Admin Dashboard](./screenshots/admin.png)
-->

## 🔒 Código Privado

O código-fonte completo está em repositório privado por conter:

- ✅ Lógica de negócio proprietária
- ✅ Configurações sensíveis de produção
- ✅ Integrações com serviços terceiros
- ✅ Chaves de API e credenciais

**💼 Interessado em conhecer o código ou discutir o projeto?**  
Entre em contato comigo! Estou aberto a conversas sobre o desenvolvimento, arquitetura e decisões técnicas.

## 🎓 Aprendizados e Desafios

Este projeto me permitiu desenvolver e aprimorar habilidades em:

- ✅ **Arquitetura Full-Stack**: Separação clara de responsabilidades entre frontend e backend
- ✅ **APIs RESTful**: Desenvolvimento de endpoints escaláveis e bem documentados
- ✅ **Autenticação e Segurança**: Implementação de JWT, bcrypt e proteção de rotas
- ✅ **Integração de Pagamentos**: Trabalho com gateways de pagamento
- ✅ **Gerenciamento de Estado**: Context API e otimização de re-renders
- ✅ **Responsividade**: Design mobile-first com Tailwind CSS
- ✅ **Boas Práticas**: Clean Code, componentização, reutilização
- ✅ **Git & GitHub**: Versionamento profissional com commits semânticos

### Desafios Superados

- Implementação de sistema de carrinho persistente
- Gerenciamento de estoque em tempo real
- Upload e otimização de imagens de produtos
- Criação de dashboard administrativo intuitivo

## 🚀 Próximos Passos

- [ ] Sistema de avaliações e comentários de produtos
- [ ] Notificações em tempo real (WebSockets)
- [ ] Integração com mais gateways de pagamento
- [ ] Aplicativo mobile com React Native ou Flutter
- [ ] Sistema de cupons e descontos promocionais
- [ ] Wishlist (lista de desejos)
- [ ] Comparação de produtos
- [ ] Recomendações personalizadas com IA

## 💡 Por que este projeto?

Desenvolvi este e-commerce para:

1. **Demonstrar habilidades full-stack** em um projeto real e completo
2. **Aprender tecnologias modernas** do mercado
3. **Criar um portfólio sólido** com código de qualidade
4. **Entender o fluxo completo** de uma aplicação comercial

## 👨‍💻 Autor

**Anselmo Polcaro Ribeiro**

- 🐙 GitHub: [@polcaronet](https://github.com/polcaronet)
- 📧 Email: polcaronet@gmail.com
- 💼 LinkedIn: [Adicione seu LinkedIn aqui]
- 🌐 Portfolio: [Adicione seu site aqui]

## 📄 Licença

Este projeto é de código fechado. Todos os direitos reservados.

---

<div align="center">

**💼 Desenvolvido como projeto de portfólio profissional**

⭐ **Gostou do projeto? Deixe uma estrela!**

💬 **Tem alguma dúvida ou feedback? Entre em contato!**

</div>
