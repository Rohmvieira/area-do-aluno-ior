# Instituto OSNI - Sistema de Gestão Acadêmica

Sistema completo de gestão acadêmica para o Instituto OSNI de Reflexologia.

## 🚀 Funcionalidades

### 👨‍💼 Área Administrativa
- ✅ Gestão completa de alunos
- ✅ Criação e gerenciamento de cursos
- ✅ Controle de matérias e materiais
- ✅ Sistema de notas e avaliações
- ✅ Controle financeiro flexível com juros e multas
- ✅ Sistema de convites por email
- ✅ Backup e restauração de dados
- ✅ Dashboard com estatísticas

### 👨‍🎓 Área do Aluno
- ✅ Visualização de notas e boletim
- ✅ Acesso a materiais do curso (PDFs e vídeos)
- ✅ Consulta de situação financeira
- ✅ Histórico acadêmico personalizado
- ✅ Acesso via convite por email
- ✅ Interface responsiva

### 📱 Recursos Técnicos
- ✅ PWA (Progressive Web App)
- ✅ Interface responsiva para mobile
- ✅ Sistema de backup/export/import
- ✅ Persistência de dados local (localStorage)
- ✅ Suporte offline básico
- ✅ Sistema de notificações (toast)

## 🛠️ Tecnologias

- **Framework**: Next.js 14 (App Router)
- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Components**: Radix UI
- **Icons**: Lucide React
- **PWA**: Service Worker, Web App Manifest

## 📦 Instalação

\`\`\`bash
# Clone o repositório
git clone [URL_DO_REPOSITORIO]

# Entre no diretório
cd instituto-osni-sistema

# Instale as dependências
npm install

# Execute em desenvolvimento
npm run dev

# Build para produção
npm run build

# Execute em produção
npm start
\`\`\`

## 🌐 Deploy

### Vercel (Recomendado)
1. Conecte seu repositório GitHub à Vercel
2. Configure as variáveis de ambiente (se necessário)
3. Deploy automático a cada push

### Outras plataformas
O projeto é compatível com qualquer plataforma que suporte Next.js.

## 📱 PWA - Progressive Web App

O sistema pode ser instalado como aplicativo:

### Mobile
1. Acesse o site no navegador
2. Toque no menu do navegador
3. Selecione "Adicionar à tela inicial" ou "Instalar app"

### Desktop
1. Acesse o site no Chrome/Edge
2. Clique no ícone de instalação na barra de endereços
3. Confirme a instalação

## 🔐 Credenciais de Acesso

### Administrador
- **URL**: `/admin`
- **Email**: `pedagogico@metodoior.com.br`
- **Senha**: `admin123`

### Aluno
- **URL**: `/student`
- **Acesso**: Via convite por email (senha criada pelo aluno)

## 📊 Estrutura do Projeto

\`\`\`
/
├── app/                    # App Router (Next.js 14)
│   ├── admin/             # Área administrativa
│   ├── student/           # Área do aluno
│   ├── globals.css        # Estilos globais
│   └── layout.tsx         # Layout principal
├── components/            # Componentes reutilizáveis
│   └── ui/               # Componentes UI (shadcn/ui)
├── hooks/                # Hooks customizados
├── lib/                  # Utilitários
├── public/               # Arquivos estáticos
└── ...                   # Arquivos de configuração
\`\`\`

## 🎯 Como Usar

### 1. Primeiro Acesso
1. Acesse a página inicial
2. Clique em "Área Administrativa"
3. Faça login com as credenciais
4. Clique em "🧪 Criar Dados de Teste" para popular o sistema

### 2. Cadastrar Alunos
1. Vá em "Alunos" → "Cadastrar Aluno"
2. Preencha os dados pessoais
3. Configure o plano de pagamento flexível
4. Marque "Enviar convite por email" se desejar
5. Salve o aluno

### 3. Gerenciar Cursos
1. Vá em "Cursos" → "Criar Curso"
2. Configure as informações básicas
3. Adicione as matérias do curso
4. Salve o curso

### 4. Controle Financeiro
1. Acesse "Financeiro"
2. Visualize a situação de todos os alunos
3. Clique em um aluno para ver detalhes
4. Registre pagamentos com o sistema flexível

### 5. Backup dos Dados
1. Vá em "Backup dos Dados"
2. Exporte todos os dados em JSON
3. Importe dados quando necessário
4. Use para migração entre ambientes

## 🔧 Configurações Avançadas

### Personalização
- Edite `app/globals.css` para alterar cores e estilos
- Modifique `public/manifest.json` para configurar o PWA
- Ajuste `tailwind.config.js` para personalizar o tema

### Integrações Futuras
O sistema está preparado para integrar:
- Banco de dados real (PostgreSQL, MySQL)
- Sistema de email (SendGrid, Mailgun)
- Pagamentos online (Stripe, PagSeguro)
- Autenticação avançada (NextAuth.js)

## 📞 Suporte

**Instituto OSNI de Reflexologia**
- 📱 WhatsApp: (11) 96575-0027
- 📧 Email: pedagogico@metodoior.com.br

## 📄 Licença

Este projeto foi desenvolvido especificamente para o Instituto OSNI de Reflexologia.

---

**Desenvolvido com ❤️ para o Instituto OSNI de Reflexologia**
\`\`\`

```plaintext file="next-env.d.ts"
/// <reference types="next" />
/// <reference types="next/image-types/global" />

// NOTE: This file should not be edited
// see https://nextjs.org/docs/basic-features/typescript for more information.
