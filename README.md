# Scrum Manager - Aplicativo de Gerenciamento Ágil

Uma aplicação web desenvolvida com **React** e **Vite**, criada como trabalho da disciplina de **Métodos Ágeis em Scrum**.

## 🎯 Objetivo

Demonstrar os conceitos principais e a estrutura do framework Scrum de forma prática e interativa.

## 📱 Funcionalidades Principais

### 1. **Painel de Controle**
- Visão geral da sprint atual
- Métricas em tempo real (Velocity, Tamanho do time, Taxa de conclusão)
- Progresso visual da sprint

### 2. **Sprint**
- Visualização de todas as tarefas
- Filtros por status (A Fazer, Em Progresso, Concluído)
- Cards com detalhes completos (Título, Descrição, Prioridade, Pontos, Atribuição)
- Estatísticas da sprint

### 3. **Product Backlog**
- Lista de histórias de usuário
- Organização por status (Na Sprint, Backlog)
- Formato: "Como [tipo de usuário], quero [funcionalidade], para que [benefício]"
- Pontuação e priorização

### 4. **Configurações**
- Informações sobre pilares do Scrum (Transparência, Inspeção, Adaptação)
- Papéis (Product Owner, Scrum Master, Time)
- Eventos (Planning, Daily, Review, Retrospective)
- Controles de notificações

## 🏗️ Estrutura do Projeto

```
src/
├── screens/
│   ├── DashboardScreen.jsx
│   ├── SprintScreen.jsx
│   ├── BacklogScreen.jsx
│   └── SettingsScreen.jsx
├── components/
│   └── Navigation.jsx
├── App.jsx
└── App.css
```

## 🚀 Como Executar

### Pré-requisitos
- Node.js 16+

### Instalação e Execução

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev
```

O navegador abrirá automaticamente em `http://localhost:5173`

### Build para Produção

```bash
npm run build
```

## 🔑 Conceitos de Scrum Implementados

### **Pilares do Scrum:**
1. **Transparência** - Todas as informações são visíveis
2. **Inspeção** - Métricas e progresso são monitorados
3. **Adaptação** - O sistema permite ajustes

### **Papéis:**
- **Product Owner** - Responsável pelo backlog
- **Scrum Master** - Facilita o processo
- **Time de Desenvolvimento** - Executa as tarefas

### **Eventos:**
- **Sprint Planning** - Planejamento da sprint
- **Daily Standup** - Sincronização diária
- **Sprint Review** - Revisão do concluído
- **Sprint Retrospective** - Reflexão sobre o processo

### **Artefatos:**
- **Product Backlog** - Lista priorizada de funcionalidades
- **Sprint Backlog** - Tarefas da sprint
- **Incremento** - Produto funcional

## 📊 Dados de Exemplo

O aplicativo inclui dados fictícios para demonstração:
- Sprint 1: "Implementar autenticação"
- 5 membros no time
- Tarefas em diferentes estados
- Histórias de usuário com pontuação

## 🎨 Design

- **Cores**: Azul (#007AFF), Laranja (#FF9500), Verde (#34C759), Ciano (#5AC8FA)
- **Responsivo**: Funciona em mobile e desktop
- **Interface clara**: Navegação intuitiva

## 📚 Tecnologias

- **React 18.2.0** - Biblioteca UI
- **Vite 5.0.0** - Build tool
- **CSS puro** - Estilos responsivos

## 👨‍💻 Autor

Desenvolvido como trabalho acadêmico para Métodos Ágeis em Scrum.

---

**Versão**: 1.0.0  
**Data**: Junho 2026
