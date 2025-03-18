# 💇‍♀️ Cabeleleila - Plataforma de Agendamento para Salões de Beleza

## 📝 Sobre o Projeto

Cabeleleila é uma plataforma web moderna desenvolvida para facilitar o agendamento de serviços em salões de beleza. O sistema permite que clientes encontrem e agendem serviços em diversos salões, enquanto oferece aos profissionais uma interface intuitiva para gerenciamento de horários.

### 🎯 Principais Funcionalidades

- **Para Clientes:**
  - Cadastro e autenticação de usuários
  - Busca de salões por serviço
  - Visualização detalhada dos serviços oferecidos
  - Agendamento de horários
  - Histórico de agendamentos

- **Para Profissionais:**
  - Painel administrativo
  - Gerenciamento de serviços
  - Controle de agendamentos
  - Perfil personalizado do salão

## 🛠️ Tecnologias Utilizadas

### Frontend
- **Next.js 14** - Framework React com SSR
- **Tailwind CSS** - Framework CSS utilitário
- **Shadcn/ui** - Componentes React estilizados
- **TypeScript** - Superset JavaScript com tipagem estática

### Backend
- **Node.js** - Ambiente de execução JavaScript
- **Prisma** - ORM para banco de dados
- **MySQL** - Banco de dados relacional
- **NextAuth.js** - Sistema de autenticação

### Ferramentas
- **Git** - Controle de versão
- **ESLint** - Linter para JavaScript/TypeScript
- **Prettier** - Formatador de código

## 📦 Pré-requisitos

- Node.js 18+
- MySQL
- Git
- XAMPP

## 🚀 Como Executar o Projeto

1. **Clone o repositório**
```bash
git clone https://github.com/giovannib6/cabeleleila.git
cd cabeleleila
```

2. **Instale as dependências e ative o banco de dados**
```bash
npm install
npm install mysql2
-------------------
Ative o MySQL no xampp
```

3. **Configure as variáveis de ambiente**
- Crie um arquivo `.env` na raiz do projeto
- Copie o conteúdo de `.env.example`
- Preencha com suas configurações

4. **Configure o banco de dados**
```bash
npx prisma migrate dev
npx prisma db seed
```

5. **Inicie o servidor de desenvolvimento**
```bash
npm run dev
```

O projeto estará disponível em `http://localhost:3000`

## 🏗️ Estrutura do Projeto

```
├── app/                    # Código fonte da aplicação
│   ├── _components/       # Componentes compartilhados
│   ├── (home)/           # Páginas públicas
│   ├── admin/            # Área administrativa
│   └── api/              # Rotas da API
├── prisma/               # Configuração do banco de dados
└── public/               # Arquivos estáticos
```

## 🔍 Observações Adicionais

- O projeto utiliza o novo App Router do Next.js 14
- Implementação completa de autenticação com NextAuth.js
- Design responsivo para todas as telas
- Integração com banco de dados MySQL via Prisma
- Sistema de agendamento em tempo real

## 🤝 Contribuição

Este projeto foi desenvolvido como parte de um teste técnico, demonstrando conhecimentos em:

- Desenvolvimento Full Stack
- Arquitetura de Software
- Boas práticas de programação
- UI/UX Design
- Integração com banco de dados
- Autenticação e Autorização

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Desenvolvido por Giovanni Breno como parte do processo seletivo.
