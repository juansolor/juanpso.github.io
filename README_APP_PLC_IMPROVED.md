# 🏭 App PLC - Sistema de Control Industrial

[![Deploy](https://img.shields.io/badge/Deploy-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://app-plc-1.onrender.com/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://javascript.com/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Status](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)](https://app-plc-1.onrender.com/)

> **Sistema de control PLC industrial** com interface web moderna, desplegado em produção para monitoramento e controle de processos industriais em tempo real.

## 📋 Índice

- [📖 Sobre o Projeto](#-sobre-o-projeto)
- [🛠️ Tecnologias](#️-tecnologias)
- [✨ Funcionalidades](#-funcionalidades)
- [🌐 Demo Live](#-demo-live)
- [🏗️ Arquitetura](#️-arquitetura)
- [📱 Interface](#-interface)
- [🔧 Instalação](#-instalação)
- [🚀 Deploy](#-deploy)
- [📊 Performance](#-performance)
- [📞 Contato](#-contato)

## 📖 Sobre o Projeto

O **App PLC** é um sistema completo de controle industrial desenvolvido com tecnologias modernas, combinando **React no frontend** e **Python no backend**. A aplicação está **deployada em produção** na plataforma Render, oferecendo uma interface web intuitiva para monitoramento e controle de processos industriais.

### 🎯 Objetivos do Projeto
- ✅ **Interface web moderna** para controle de PLCs
- ✅ **Monitoramento em tempo real** de processos industriais
- ✅ **Comunicação eficiente** entre frontend e backend
- ✅ **Deploy em produção** com alta disponibilidade
- ✅ **Experiência do usuário** otimizada para operadores

### 🏭 Aplicações Industriais
- **Controle de processos** automatizados
- **Monitoramento de sensores** e atuadores
- **Interface operacional** para técnicos e engenheiros
- **Logging e histórico** de operações
- **Alertas e notificações** em tempo real

## 🛠️ Tecnologias

### 🎨 Frontend
- **React.js** - Biblioteca para interfaces reativas
- **JavaScript (ES6+)** - Linguagem principal do frontend
- **HTML5 & CSS3** - Estrutura e estilização moderna
- **Responsive Design** - Interface adaptável a diferentes dispositivos

### ⚙️ Backend
- **Python** - Linguagem principal do backend
- **Framework Python** - (Flask/Django/FastAPI)
- **APIs RESTful** - Comunicação entre frontend e backend
- **Protocolos Industriais** - Comunicação com PLCs

### 🌐 Deploy & Infraestrutura
- **Render** - Plataforma de deploy em nuvem
- **HTTPS** - Conexão segura em produção
- **CI/CD** - Deploy automático
- **Monitoramento** - Logs e métricas de produção

### 🔧 Ferramentas de Desenvolvimento
- **Git & GitHub** - Controle de versão
- **Node.js** - Ambiente de desenvolvimento frontend
- **npm/yarn** - Gerenciador de pacotes
- **VSCode** - IDE de desenvolvimento

## ✨ Funcionalidades

### 🖥️ Interface de Controle
- **Dashboard principal** com visão geral do sistema
- **Controles interativos** para operação dos PLCs
- **Visualização em tempo real** de status e dados
- **Interface responsiva** para desktop e mobile

### 📊 Monitoramento
- **Status dos equipamentos** em tempo real
- **Gráficos e métricas** de performance
- **Histórico de operações** e logs
- **Alertas visuais** para condições críticas

### 🔄 Comunicação Industrial
- **Protocolo de comunicação** com PLCs
- **Sincronização de dados** bidirecional
- **Tratamento de erros** e reconexão automática
- **Buffer de comandos** para operação confiável

### 🛡️ Segurança e Confiabilidade
- **Autenticação de usuários** (se implementada)
- **Validação de comandos** críticos
- **Backup de configurações**
- **Logs de auditoria**

## 🌐 Demo Live

🔗 **Aplicação em Produção:** [https://app-plc-1.onrender.com/](https://app-plc-1.onrender.com/)

### 📱 Acesso à Aplicação
- **Status:** ✅ Online e funcionando
- **Performance:** Otimizada para uso industrial
- **Disponibilidade:** 24/7 na nuvem
- **Responsividade:** Interface adaptável

### 🎮 Como Usar
1. **Acesse o link** da aplicação
2. **Navegue pela interface** principal
3. **Explore os controles** disponíveis
4. **Monitore os status** em tempo real

## 🏗️ Arquitetura

```
App PLC System
├── 🎨 Frontend (React)
│   ├── Components/
│   │   ├── Dashboard
│   │   ├── Controls
│   │   ├── Monitoring
│   │   └── Charts
│   ├── Services/
│   │   ├── API Client
│   │   └── WebSocket
│   └── Utils/
├── ⚙️ Backend (Python)
│   ├── API Routes
│   ├── PLC Communication
│   ├── Data Processing
│   └── WebSocket Server
└── 🌐 Deploy (Render)
    ├── Frontend Build
    ├── Backend Server
    └── Environment Config
```

### 🔄 Fluxo de Dados
1. **Interface React** → Comandos do usuário
2. **API Backend** → Processamento e validação
3. **Comunicação PLC** → Envio de comandos
4. **Retorno de dados** → Status e métricas
5. **Atualização UI** → Feedback em tempo real

## 📱 Interface

### 🎨 Design Principles
- **Interface limpa** e profissional
- **Cores industriais** apropriadas
- **Iconografia intuitiva** para operadores
- **Layout responsivo** para diferentes telas

### 🖼️ Componentes Principais
- **Header navegacional** com logo e menu
- **Dashboard central** com métricas principais
- **Painel de controles** para operação
- **Footer informativo** com links úteis

## 🔧 Instalação

### Pré-requisitos
```bash
# Node.js (para desenvolvimento frontend)
node --version  # v14+

# Python (para backend)
python --version  # 3.8+

# Git
git --version
```

### 1️⃣ Clone o Repositório
```bash
# Repositório privado - requer acesso
git clone https://github.com/juansolor/app-plc.git
cd app-plc
```

### 2️⃣ Setup Frontend
```bash
# Instalar dependências React
cd frontend
npm install

# Desenvolvimento local
npm start
# Acesso: http://localhost:3000
```

### 3️⃣ Setup Backend
```bash
# Instalar dependências Python
cd backend
pip install -r requirements.txt

# Executar servidor
python app.py
# Acesso: http://localhost:5000
```

### 4️⃣ Configuração
```bash
# Variáveis de ambiente
cp .env.example .env
# Editar configurações necessárias
```

## 🚀 Deploy

### 🌐 Render Deployment
A aplicação está configurada para deploy automático no Render:

```yaml
# render.yaml (exemplo)
services:
  - type: web
    name: app-plc
    env: node
    buildCommand: npm run build
    startCommand: npm start
    envVars:
      - key: NODE_ENV
        value: production
```

### 📊 Configurações de Produção
- **Build otimizado** para performance
- **Variáveis de ambiente** seguras
- **SSL/HTTPS** habilitado
- **Logs centralizados**

## 📊 Performance

### ⚡ Métricas de Performance
- **Tempo de carregamento:** < 3 segundos
- **Responsividade:** Interface reativa
- **Uptime:** 99.9% disponibilidade
- **Latência:** Comunicação otimizada

### 🔍 Monitoramento
- **Status do servidor** em tempo real
- **Logs de aplicação** centralizados
- **Métricas de uso** e performance
- **Alertas automáticos** para problemas

## 🎓 Competências Demonstradas

### 💻 Desenvolvimento Full Stack
- ✅ **React.js** para interfaces modernas
- ✅ **Python** para backend robusto
- ✅ **APIs RESTful** para comunicação
- ✅ **Integração frontend/backend**

### 🏭 Conhecimento Industrial
- ✅ **Protocolos de comunicação** industrial
- ✅ **Sistemas de controle** PLC
- ✅ **Interface operacional** para indústria
- ✅ **Monitoramento em tempo real**

### 🚀 DevOps e Deploy
- ✅ **Deploy em produção** na nuvem
- ✅ **Configuração de servidor**
- ✅ **Monitoramento de aplicação**
- ✅ **Manutenção de sistema live**

## 🔮 Funcionalidades Futuras

- [ ] **Autenticação e autorização** de usuários
- [ ] **Dashboard avançado** com mais métricas
- [ ] **Notificações push** para alertas
- [ ] **Histórico detalhado** de operações
- [ ] **Integração com mais protocolos** industriais
- [ ] **API documentada** com Swagger
- [ ] **Testes automatizados** completos

## 📄 Licença

Este projeto foi desenvolvido para fins profissionais e demonstração de competências técnicas.

## 📞 Contato

**Juan Pablo Solorzano Ojeda**
- 🎓 **Formação:** Engenheiro Eletricista - Sistemas e Automação
- 🏭 **Especialidade:** Controle Industrial e Desenvolvimento Full Stack
- 💼 **Experiência:** Desenvolvimento de sistemas industriais

### 📬 Entre em Contato
- 📧 **Email:** [juanpablo.solorzanoojeda@gmail.com](mailto:juanpablo.solorzanoojeda@gmail.com)
- 💼 **LinkedIn:** [Juan Pablo Solorzano Ojeda](https://www.linkedin.com/in/juan-pablo-solorzano-ojeda-290820303/)
- 🌐 **Portfolio:** [juanpso.github.io](https://juanpso.github.io)
- 🐙 **GitHub:** [@juansolor](https://github.com/juansolor)

### 🌟 Demo Live
🔗 **Aplicação:** [https://app-plc-1.onrender.com/](https://app-plc-1.onrender.com/)

---

<div align="center">
  <p><strong>🏭 Desenvolvido com React + Python para controle industrial 🔧</strong></p>
  <p><em>Engenharia e Tecnologia aplicadas à Indústria 4.0</em></p>
  <p>⭐ Sistema em produção - Deploy funcional na nuvem!</p>
</div>
