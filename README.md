# Laboratório de Rotinas

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![Next.js](https://img.shields.io/badge/Next.js-13.5.6-black?logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.2.2-3178C6?logo=typescript&logoColor=white)

Um aplicativo web moderno para gerenciamento de rotinas de laboratório, desenvolvido com Next.js, React e TypeScript.

## ✨ Recursos

- 📝 Criação e gerenciamento de rotinas de laboratório
- 🔍 Busca e filtragem avançada de rotinas
- ⚡ Otimizado para desempenho
- 🎨 Interface de usuário moderna e intuitiva
- ✅ Validação de formulários
- 🔄 Atualização em tempo real com TanStack Query

## 🚀 Tecnologias

- **Framework**: Next.js 15 (App Router)
- **Linguagem**: TypeScript
- **Estilização**: Tailwind CSS
- **Gerenciamento de Estado**: Zustand
- **Requisições HTTP**: TanStack Query
- **Formulários**: React Hook Form
- **Componentes UI**: Radix UI + shadcn/ui
- **Ícones**: Lucide React
- **Notificações**: Sonner

## 🛠️ Pré-requisitos

- Node.js 18+
- npm ou pnpm
- Git

## 🏃‍♂️ Começando

1. **Clonar o repositório**
   ```bash
   git clone https://github.com/airtonsena10/lab-routine.git
   cd lab-routine
   ```

2. **Instalar dependências**
   ```bash
   npm install
   # ou
   pnpm install
   ```

3. **Abrir no navegador**
   Abra [http://localhost:3000](http://localhost:3000) no seu navegador.

## 📦 Estrutura do Projeto

```
src/
├── app/                 # Rotas da aplicação
├── components/          # Componentes reutilizáveis
│   ├── form/           # Componentes de formulário
│   ├── routines/        # Componentes específicos de rotinas
│   └── ui/             # Componentes de interface do usuário
├── lib/                # Utilitários e funções auxiliares
├── store/              # Gerenciamento de estado global
└── types/              # Definições de tipos TypeScript
```

## 🔧 Comandos Disponíveis

- `dev` - Inicia o servidor de desenvolvimento
- `build` - Constrói a aplicação para produção
- `start` - Inicia o servidor de produção
- `lint` - Executa o ESLint
- `format` - Formata o código com Prettier
