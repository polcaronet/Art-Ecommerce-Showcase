# 🛒 Art E-commerce

> Sistema completo de E-commerce desenvolvido com tecnologias modernas

[![Private Repository](https://img.shields.io/badge/code-private-red)](https://github.com)
[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)](https://github.com)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org)

## 📋 Sobre o Projeto

Art E-commerce é uma plataforma completa de comércio eletrônico desenvolvida com arquitetura separada entre Backend (Node.js) e Frontend (Flutter), garantindo escalabilidade, manutenibilidade e performance multiplataforma.

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

### Backend (API REST)

- **Node.js** - Ambiente de execução JavaScript
- **Express** - Framework web minimalista e rápido
- **MongoDB** - Banco de dados NoSQL
- **Mongoose** - ODM para MongoDB
- **JWT** - Autenticação segura
- **Bcrypt** - Criptografia de senhas
- **Multer** - Upload de arquivos e imagens
- **Nodemailer** - Envio de emails

### Frontend (Mobile/Desktop)

- **Flutter** - Framework multiplataforma do Google
- **Dart** - Linguagem de programação otimizada para UI
- **Provider / BLoC** - Gerenciamento de estado
- **HTTP / Dio** - Requisições HTTP
- **Shared Preferences** - Armazenamento local
- **Image Picker** - Seleção de imagens
- **Flutter Secure Storage** - Armazenamento seguro de tokens

### DevOps & Tools

- **Git** - Controle de versão
- **Postman** - Testes de API
- **Android Studio / VS Code** - IDEs de desenvolvimento

## 🏗️ Arquitetura

```
Art-Ecommerce/
├── Backend/                    # API REST (Node.js)
│   ├── src/
│   │   ├── controllers/       # Lógica de negócio
│   │   ├── models/            # Schemas do MongoDB
│   │   ├── routes/            # Rotas da API
│   │   ├── middlewares/       # Autenticação, validação
│   │   ├── config/            # Configurações (DB, JWT, etc)
│   │   └── utils/             # Funções auxiliares
│   ├── .env.example           # Exemplo de variáveis
│   ├── package.json
│   └── server.js              # Entrada da aplicação
│
└── Frontend/                   # App Flutter
    ├── lib/
    │   ├── main.dart          # Ponto de entrada
    │   ├── models/            # Modelos de dados
    │   ├── screens/           # Telas da aplicação
    │   │   ├── home/
    │   │   ├── products/
    │   │   ├── cart/
    │   │   ├── checkout/
    │   │   └── admin/
    │   ├── widgets/           # Widgets reutilizáveis
    │   ├── services/          # Comunicação com API
    │   ├── providers/         # Gerenciamento de estado
    │   ├── utils/             # Funções auxiliares
    │   └── constants/         # Constantes (cores, URLs)
    ├── assets/                # Imagens, fontes, ícones
    ├── android/               # Configurações Android
    ├── ios/                   # Configurações iOS
    └── pubspec.yaml           # Dependências Flutter
```

## 📱 Plataformas Suportadas

- ✅ **Android** (5.0+)
- ✅ **iOS** (11.0+)
- ✅ **Web** (opcional)
- ✅ **Windows / macOS / Linux** (Desktop)

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

- ✅ **Desenvolvimento Multiplataforma**: Um único código Flutter para Android, iOS e Web
- ✅ **Arquitetura Full-Stack**: Backend Node.js + Frontend Flutter
- ✅ **APIs RESTful**: Desenvolvimento de endpoints escaláveis e bem documentados
- ✅ **Autenticação e Segurança**: Implementação de JWT, bcrypt e proteção de rotas
- ✅ **Integração de Pagamentos**: Trabalho com gateways de pagamento
- ✅ **Gerenciamento de Estado Flutter**: Provider/BLoC pattern
- ✅ **Programação Assíncrona em Dart**: Futures, Streams e async/await
- ✅ **UI/UX Mobile**: Design responsivo e material design
- ✅ **Git & GitHub**: Versionamento profissional com commits semânticos

### Desafios Superados

- Comunicação eficiente entre Flutter e API REST
- Implementação de sistema de carrinho persistente
- Gerenciamento de estado complexo no Flutter
- Upload e otimização de imagens de produtos
- Criação de dashboard administrativo mobile-first
- Tratamento de erros e loading states

## 🚀 Próximos Passos

- [ ] Sistema de avaliações e comentários de produtos
- [ ] Notificações push (Firebase Cloud Messaging)
- [ ] Integração com mais gateways de pagamento
- [ ] Deep linking para compartilhamento de produtos
- [ ] Sistema de cupons e descontos promocionais
- [ ] Wishlist (lista de desejos)
- [ ] Comparação de produtos
- [ ] Modo offline com sincronização
- [ ] Internacionalização (i18n)
- [ ] Dark mode

## 💡 Por que este projeto?

Desenvolvi este e-commerce para:

1. **Demonstrar habilidades full-stack** em um projeto real e completo
2. **Dominar Flutter** para desenvolvimento multiplataforma
3. **Criar um portfólio sólido** com código de qualidade
4. **Entender o fluxo completo** de uma aplicação comercial moderna

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

**🎯 Flutter + Node.js = Performance Multiplataforma**

⭐ **Gostou do projeto? Deixe uma estrela!**

💬 **Tem alguma dúvida ou feedback? Entre em contato!**

</div>
