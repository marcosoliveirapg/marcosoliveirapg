# Olá, eu sou o Marcos 👋

Estudante de **Análise e Desenvolvimento de Sistemas** na Uniasselvi. Desenvolvo **sistemas web com IA e automação** que resolvem problemas reais de operação: gestão pública, vendas e serviços em campo. Sou sócio da [Grafo.Studio](https://grafostudio.com.br), em Aracaju/SE.

Antes de qualquer título, sou vendedor. Comecei a programar para criar soluções melhores para os meus clientes, e hoje construo os sistemas de ponta a ponta: interface, banco de dados, segurança, deploy e os agentes de IA que trabalham dentro deles.

## 🚀 Sistemas em produção

Repositórios privados (código de clientes). Posso apresentar em uma conversa.

### Measure · Gestão de Contratos Públicos
Sistema em uso na Secretaria Municipal de Saúde de Aracaju para contratos, notas fiscais e atestos, empenhos, fornecedores, patrimônio, estoque, ordens de serviço e demandas.
- **Agente de IA "Monitor de Notas Fiscais"** com a API do Claude e *tool use*: busca os dados por uma ferramenta e aponta notas ausentes no mês, variações acima de 20% da média de 6 meses, duplicidades e contratos perto do vencimento.
- Multi-tenant por coordenação com **Row Level Security** no Postgres, perfis de acesso e testes automatizados das regras do banco.
- Automações com Edge Functions e pg_cron: alertas de vencimento, notificações por e-mail, consulta de CNPJ e CEP.
- Cuidados de **LGPD** e CI com build, testes e auditoria de dependências.

`React` `Vite` `Tailwind` `Supabase` `PostgreSQL` `Claude API` `Vercel` `GitHub Actions`

### Qyro One · CRM para empresas de consórcio
- Funil **Kanban** automatizado, agenda, tarefas, simulador de contratos com PDF, auditoria e login com 2FA.
- **Atendente de IA no WhatsApp** (n8n + Evolution API + LLM): responde o lead, cadastra no CRM, distribui para um consultor, agenda a reunião e avisa o consultor.
- API própria para o n8n com operações idempotentes, testes de banco (pgTAP) e unitários (Vitest).

`Next.js` `TypeScript` `Supabase` `n8n` `Evolution API` `Zod` `Vitest`

### Frivonx · SaaS para empresas de refrigeração
- Ordens de serviço, agenda com aviso de conflito, clientes e equipamentos com histórico, orçamentos que viram OS e contratos preventivos que geram OS sozinhos.
- Feito para o técnico em campo: conclui a OS no celular, colhe a assinatura do cliente e envia o recibo em PDF.
- Multi-empresa com testes de isolamento entre contas e área administrativa com 2FA.

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `pdf-lib` `Vercel`

## 🤖 Como eu trabalho com IA

- Agentes com a **Claude API** e chamada de ferramentas dentro dos sistemas
- Agentes de atendimento no WhatsApp com **n8n**
- Desenvolvimento assistido por IA com **Claude Code** e subagentes especializados (banco, front-end, segurança)

## 🛠️ Tecnologias

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

## 🌐 Outros projetos

- Sites para clientes da Grafo.Studio: hamburgueria, barbearia, pizzaria, evento de e-sports e marca de moda masculina
- [Calculadora de IMC](https://github.com/marcosoliveirapg/calcimcJ): meu primeiro projeto em HTML, CSS e JavaScript. [Ver online](https://calcimc-j.vercel.app)

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcos-oliveira-32b896408)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:hi.marcosoliveira@gmail.com)
[![Site](https://img.shields.io/badge/grafostudio.com.br-111111?style=flat&logo=googlechrome&logoColor=white)](https://grafostudio.com.br)
