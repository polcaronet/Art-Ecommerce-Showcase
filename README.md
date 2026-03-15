# 🛒 Art E-commerce

<div align="center">
  <img width="400" alt="Art E-commerce App" src="https://github.com/user-attachments/assets/ad763802-0662-40d0-8c31-2ad82593af96" />

  ### Sistema completo de E-commerce multiplataforma

  [![Private Repository](https://img.shields.io/badge/code-private-red?style=for-the-badge)](https://github.com)
  [![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=for-the-badge)](https://github.com)
  [![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
  [![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
  [![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com)
  [![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
</div>

---

## 📋 Sobre o Projeto

**Art E-commerce** é uma plataforma completa de comércio eletrônico desenvolvida com arquitetura moderna e separação de responsabilidades. Combina o poder do **Flutter** para criar uma experiência mobile fluida e nativa com um **backend Node.js** robusto e escalável.

### ✨ Diferenciais
- 📱 **Android Nativo**: Desenvolvido com Flutter para performance nativa
- 🚀 **Performance**: Interface fluida com Flutter + API REST otimizada
- 🔒 **Segurança**: Autenticação JWT e criptografia de dados sensíveis
- 🎨 **UI/UX Moderna**: Material Design com animações fluidas

---

## 🎯 Funcionalidades

<table>
  <tr>
    <td width="50%">

### 🔐 Autenticação
- Login e registro de usuários
- Autenticação JWT segura
- Níveis de permissão (Admin/Cliente)
- Recuperação de senha

### 🛍️ Catálogo de Produtos
- Listagem com filtros avançados
- Busca inteligente em tempo real
- Categorias organizadas
- Visualização detalhada com galeria

### 🛒 Carrinho de Compras
- Adicionar/remover produtos
- Atualização de quantidades
- Cálculo automático de totais
- Persistência de dados

</td>
<td width="50%">

### 💳 Pagamentos
- Integração com gateways
- Múltiplas formas de pagamento
- Confirmação por email
- Histórico de transações

### 📦 Gestão de Pedidos
- Rastreamento em tempo real
- Status detalhado
- Notificações push
- Histórico completo

### ⚙️ Painel Admin
- Dashboard com métricas
- Gestão de produtos e estoque
- Controle de pedidos
- Relatórios detalhados

</td>
  </tr>
</table>

---

## 🚀 Stack Tecnológica

### 🔧 Backend (API REST)
```javascript
// Tecnologias principais
Node.js      →  Runtime JavaScript performático
Express      →  Framework web minimalista
MongoDB      →  Banco de dados NoSQL
Mongoose     →  ODM elegante para MongoDB
JWT          →  Tokens de autenticação seguros
Bcrypt       →  Hash de senhas
Multer       →  Upload de arquivos
Nodemailer   →  Envio de emails
```

### 📱 Frontend (Mobile App)
```dart
// Stack Flutter
Flutter                  →  Framework multiplataforma Google
Dart                     →  Linguagem otimizada para UI
Provider/BLoC            →  Gerenciamento de estado
Dio                      →  Cliente HTTP avançado
Shared Preferences       →  Storage local
Flutter Secure Storage   →  Armazenamento seguro
Image Picker             →  Seleção de imagens
```

### 🛠️ DevOps & Tools

- **Git & GitHub** - Controle de versão
- **Postman** - Testes de API
- **VS Code / Android Studio** - Desenvolvimento
- **ESLint / Dart Analyzer** - Code quality

---

## 🏗️ Arquitetura do Projeto
```
Art-Ecommerce/
│
├── 🔙 Backend/                    # API REST (Node.js + Express)
│   ├── src/
│   │   ├── controllers/          # Lógica de negócio
│   │   ├── models/               # Schemas MongoDB
│   │   ├── routes/               # Endpoints da API
│   │   ├── middlewares/          # Auth, validação, etc
│   │   ├── config/               # Configurações (DB, JWT)
│   │   └── utils/                # Helpers e utilitários
│   ├── .env.example
│   ├── package.json
│   └── server.js                 # Entry point
│
└── 📱 Frontend/                   # Mobile App (Flutter)
    ├── lib/
    │   ├── main.dart             # Entry point
    │   ├── models/               # Data models
    │   ├── screens/              # UI Screens
    │   │   ├── auth/            # Login, Register
    │   │   ├── home/            # Home screen
    │   │   ├── products/        # Product list/details
    │   │   ├── cart/            # Shopping cart
    │   │   ├── checkout/        # Checkout flow
    │   │   └── admin/           # Admin panel
    │   ├── widgets/              # Reusable widgets
    │   ├── services/             # API communication
    │   ├── providers/            # State management
    │   ├── utils/                # Helpers
    │   └── constants/            # Colors, URLs, etc
    ├── assets/                   # Images, fonts, icons
    └── pubspec.yaml              # Dependencies
```

---

## 📱 Plataforma Suportada

| Plataforma | Status | Versão Mínima |
|------------|--------|---------------|
| 🤖 Android | ✅ Suportado | 5.0 (API 21+) |

---

## 🔒 Código Privado

> **Por que o código é privado?**

O repositório principal contém:
- ✅ Lógica de negócio proprietária e estratégias comerciais
- ✅ Configurações sensíveis de produção
- ✅ Integrações com APIs de terceiros (chaves, tokens)
- ✅ Credenciais de bancos de dados e serviços

### 💼 Interessado no projeto?

Estou totalmente aberto a:
- 🤝 Discutir arquitetura e decisões técnicas
- 📊 Apresentar demonstrações do código
- 💡 Compartilhar aprendizados e desafios
- 🎯 Conversar sobre oportunidades profissionais

**Entre em contato comigo!** 👇

---

## 🎓 Aprendizados & Conquistas

### 🏆 Habilidades Desenvolvidas

| Área | Competências |
|------|--------------|
| **Frontend Mobile** | Flutter, Dart, Material Design, State Management, Responsive UI |
| **Backend** | Node.js, Express, RESTful APIs, MongoDB, Autenticação (JWT) |
| **DevOps** | Git/GitHub, Testes de API, Gerenciamento de Ambientes |
| **Soft Skills** | Arquitetura de Software, Resolução de Problemas, Documentação |

### 💪 Desafios Superados

- ✓ Arquitetura full-stack escalável e manutenível
- ✓ Comunicação eficiente Flutter ↔ API REST
- ✓ Gerenciamento de estado complexo (Provider/BLoC)
- ✓ Sistema de autenticação JWT + refresh tokens
- ✓ Upload otimizado de imagens (compressão + storage)
- ✓ Carrinho persistente com sincronização
- ✓ Dashboard admin com gráficos e métricas
- ✓ Tratamento robusto de erros e loading states
- ✓ Animações fluidas e transições nativas

---

## 🚀 Roadmap Futuro

### Em Planejamento

- [ ] 🔔 **Notificações Push** - Firebase Cloud Messaging
- [ ] ⭐ **Sistema de Avaliações** - Reviews e ratings de produtos
- [ ] 🎫 **Cupons e Descontos** - Sistema promocional
- [ ] 🔗 **Deep Linking** - Compartilhamento de produtos
- [ ] ❤️ **Wishlist** - Lista de desejos persistente
- [ ] 📊 **Comparação** - Compare até 4 produtos
- [ ] 📴 **Modo Offline** - Sincronização inteligente
- [ ] 🌍 **Internacionalização** - Multi-idioma (i18n)
- [ ] 🌙 **Dark Mode** - Tema escuro
- [ ] 🤖 **Recomendações IA** - Sugestões personalizadas

---

## 💡 Motivação

### Por que desenvolvi este projeto?

1. **🎯 Demonstrar expertise full-stack** em um projeto real e comercial
2. **📱 Dominar Flutter** e suas melhores práticas de desenvolvimento
3. **💼 Construir portfólio técnico** com código de qualidade profissional
4. **🚀 Entender e-commerce end-to-end** da autenticação ao pagamento
5. **📈 Crescimento profissional** aplicando padrões de mercado

---

## 📄 Licença

🔒 **Código Privado** - Todos os direitos reservados.

---

<div align="center">

### 💼 Desenvolvido como Projeto de Portfólio Profissional

**🎯 Flutter + Node.js = Performance Multiplataforma**

<br>

⭐ **Gostou do projeto? Deixe uma estrela!**

💬 **Dúvidas ou feedback? Estou à disposição!**

📧 **Oportunidades profissionais? Vamos conversar!**

<br>

---
</div>
