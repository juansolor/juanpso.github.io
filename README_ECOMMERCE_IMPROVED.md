# 🛒 E-Commerce Toti - Projeto Full Stack (Grupo 3)

[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/juansolor/projeto_final_fullstack_grupo_3)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Stars](https://img.shields.io/github/stars/juansolor/projeto_final_fullstack_grupo_3?style=for-the-badge)](https://github.com/juansolor/projeto_final_fullstack_grupo_3/stargazers)

> **E-Commerce completo inspirado em Kabum!** desenvolvido pelo Grupo 3 da Toti. Aplicação full stack com carrinho persistente, upload de imagens e fluxo real de compra.

## 📋 Índice

- [📖 Sobre o Projeto](#-sobre-o-projeto)
- [🛠️ Tecnologias](#️-tecnologias)
- [✨ Funcionalidades](#-funcionalidades)
- [🚀 Como Executar](#-como-executar)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [🌐 Endpoints da API](#-endpoints-da-api)
- [📱 Screenshots](#-screenshots)
- [👥 Equipe](#-equipe)
- [📞 Contato](#-contato)

## 📖 Sobre o Projeto

Este projeto é um **e-commerce completo** desenvolvido como trabalho final do curso Full Stack da Toti. A aplicação permite gerenciamento completo de produtos, carrinho de compras persistente e uma interface moderna inspirada no Kabum!.

### 🎯 Objetivos Alcançados
- ✅ Desenvolvimento de API REST robusta
- ✅ Interface responsiva e intuitiva
- ✅ Integração completa Front-end/Back-end
- ✅ Trabalho colaborativo em equipe
- ✅ Aplicação de boas práticas de desenvolvimento

## 🛠️ Tecnologias

### Backend
- **Node.js** - Ambiente de execução JavaScript
- **Express.js** - Framework web minimalista
- **Sequelize** - ORM para banco de dados
- **SQLite** - Banco de dados relacional
- **Multer** - Middleware para upload de arquivos
- **CORS** - Controle de acesso entre domínios

### Frontend
- **React.js** - Biblioteca para interfaces de usuário
- **Axios** - Cliente HTTP para requisições
- **Bootstrap** - Framework CSS responsivo
- **React Router** - Roteamento para SPA

## ✨ Funcionalidades

### 🛍️ Gestão de Produtos
- **CRUD completo** de produtos
- **Upload de imagens** com preview
- **Listagem dinâmica** com filtros
- **Interface administrativa** para super usuários

### 🛒 Carrinho de Compras
- **Carrinho persistente** no banco de dados
- **Adicionar/remover** produtos
- **Alterar quantidades** dinamicamente
- **Cálculo automático** de totais
- **Simulação de pagamento**

### 👤 Experiência do Usuário
- **Interface moderna** inspirada no Kabum!
- **Design responsivo** para todos os dispositivos
- **Navegação intuitiva** com navbar personalizada
- **Feedback visual** com alertas e confirmações

## 🚀 Como Executar

### Pré-requisitos
- Node.js (versão 14 ou superior)
- npm ou yarn
- Git

### 1️⃣ Clone o repositório
```bash
git clone https://github.com/juansolor/projeto_final_fullstack_grupo_3.git
cd projeto_final_fullstack_grupo_3
```

### 2️⃣ Configure o Backend
```bash
cd backend
npm install
node server.js
```
🌐 **Backend rodando em:** `http://localhost:3001`

### 3️⃣ Configure o Frontend
```bash
cd ../frontend
npm install
npm start
```
🌐 **Frontend rodando em:** `http://localhost:3000`

## 📁 Estrutura do Projeto

```
projeto_final_fullstack_grupo_3/
├── 📂 backend/
│   ├── 📂 models/          # Modelos do banco de dados
│   │   ├── index.js
│   │   ├── Imagem.js
│   │   ├── Usuario.js
│   │   └── Carrinho.js
│   ├── 📂 routes/          # Rotas da API
│   │   └── 📂 api/
│   │       ├── imagens.js
│   │       ├── usuarios.js
│   │       └── carrinho.js
│   ├── 📂 uploads/         # Imagens dos produtos
│   ├── server.js           # Servidor principal
│   └── database.sqlite     # Banco de dados
├── 📂 frontend/
│   ├── 📂 src/
│   │   ├── 📂 components/  # Componentes reutilizáveis
│   │   ├── 📂 pages/       # Páginas da aplicação
│   │   └── App.js          # Componente principal
│   └── package.json
├── 📂 figma/              # Designs e protótipos
├── README.md
└── package.json
```

## 🌐 Endpoints da API

### 👤 Usuários
```http
GET    /api/usuarios       # Listar usuários
POST   /api/usuarios       # Criar usuário
PUT    /api/usuarios/:id   # Atualizar usuário
DELETE /api/usuarios/:id   # Deletar usuário
```

### 🖼️ Imagens/Produtos
```http
GET    /api/imagens        # Listar produtos
POST   /api/imagens        # Criar produto
PUT    /api/imagens/:id    # Atualizar produto
DELETE /api/imagens/:id    # Deletar produto
```

### 🛒 Carrinho
```http
GET    /api/carrinho       # Listar itens do carrinho
POST   /api/carrinho       # Adicionar item ao carrinho
PATCH  /api/carrinho/:id   # Atualizar quantidade
DELETE /api/carrinho/:id   # Remover item do carrinho
```

## 📱 Screenshots

![Interface Principal](image.png)

*Interface principal do e-commerce com design moderno e responsivo*

## 👥 Equipe

Este projeto foi desenvolvido colaborativamente pelo **Grupo 3** da Toti Diversidade:

| Nome | Papel | LinkedIn |
|------|-------|----------|
| **Juan Pablo Solorzano Ojeda** | Full Stack Developer | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-pablo-solorzano-ojeda-290820303/) |
| **Gabriel M. López** | Frontend Developer | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](#) |
| **Rimaud Djidonou** | Backend Developer | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](#) |
| **Daniel Villegas** | Full Stack Developer | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](#) |
| **Alvaro Mauricio Gomez** | Frontend Developer | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](#) |

## 🎨 Design e UX

- **Visual inspirado** no Kabum! e design personalizado
- **Carrossel dinâmico** na página inicial
- **Cards de produtos** com informações detalhadas
- **Navbar responsiva** com acesso rápido ao carrinho
- **Layout mobile-first** para melhor experiência

## 🔮 Próximos Passos

- [ ] Integração com gateway de pagamento real
- [ ] Sistema de autenticação JWT
- [ ] Painel administrativo avançado
- [ ] Notificações em tempo real
- [ ] Testes automatizados
- [ ] Deploy em produção

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais como parte do curso Full Stack da Toti.

## 📞 Contato

**Juan Pablo Solorzano Ojeda**
- 📧 Email: [juanpablo.solorzanoojeda@gmail.com](mailto:juanpablo.solorzanoojeda@gmail.com)
- 💼 LinkedIn: [Juan Pablo Solorzano Ojeda](https://www.linkedin.com/in/juan-pablo-solorzano-ojeda-290820303/)
- 🐙 GitHub: [@juansolor](https://github.com/juansolor)

---

<div align="center">
  <p><strong>Desenvolvido com ❤️ pelo Grupo 3 - Toti Diversidade</strong></p>
  <p>⭐ Se este projeto te ajudou, não esqueça de dar uma estrela!</p>
</div>
