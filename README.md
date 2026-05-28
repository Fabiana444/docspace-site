# DocSpace — Documentação do Projeto

**Proprietária:** Fabiana Nonjah  
**Site:** https://docspace.tec.br  
**Repositório:** https://github.com/Fabiana444/docspace-site

**Início do projeto:** Maio 2025  
**Status atual:** Fase 1 — Fundação & Segurança  

---

## O que é o DocSpace

O DocSpace é uma plataforma multi-ambiente de Gestão de Conhecimento e Experiência (LXP/CMS) construída como ativo profissional estratégico. O site demonstra, na prática, as minhas competências de uma Analista de Documentação de Software Sênior que domina não apenas documentação SaaS, mas também automação, uso de IA e desenvolvimento de código para produtividade.

**Tecnologias principais:**
- Frontend: HTML/CSS/JS (MVP) → Next.js 14 (evolução planejada)
- Backend/Auth/DB: Supabase (PostgreSQL + RLS + Auth)
- Hospedagem: GitHub Pages / Vercel
- Integrações: Google AI Studio, Swagger UI, DeepL API, i18next

---

## Estrutura desta Documentação

```
DocSpace-Documentacao/
│
├── README.md                          ← Este arquivo (índice geral)
│
├── Arquitetura-do-Site/
│   ├── visao-geral-arquitetura.md     ← Diagrama e descrição da arquitetura
│   ├── fluxo-de-acesso-e-rbac.md     ← Como funciona o controle de acesso
│   └── decisoes-tecnicas.md          ← Por que cada tecnologia foi escolhida
│
├── API-Supabase/
│   ├── schema-banco-de-dados.sql     ← SQL completo das tabelas e RLS
│   ├── politicas-rls.md              ← Documentação das Row Level Security policies
│   ├── endpoints-e-funcoes.md        ← Edge Functions e chamadas de API
│   └── guia-configuracao-supabase.md ← Passo a passo para configurar o projeto
│
├── Autenticacao-e-Seguranca/
│   ├── fluxo-autenticacao.md         ← Login, cadastro, logout, sessão
│   ├── perfis-e-permissoes.md        ← Roles: admin, editor, validator, user
│   ├── seguranca-frontend.md         ← Boas práticas e o que NÃO fazer
│   └── anti-spam-e-bloqueios.md      ← Proteção contra bots e spam
│
├── Layout/
│   ├── design-system.md              ← Paleta, tipografia, componentes
│   ├── estrutura-html-css.md         ← Organização do index.html
│   └── responsividade-mobile.md      ← Breakpoints e comportamento mobile
│
├── GitHub/
│   ├── estrutura-repositorio.md      ← Como o repo está organizado
│   ├── fluxo-de-deploy.md            ← Como publicar atualizações
│   └── controle-de-versoes.md        ← Convenção de commits e branches
│
├── Ambientes/
│   ├── Portfolio/
│   │   └── especificacao-portfolio.md
│   ├── Docs-SaaS/
│   │   ├── especificacao-docs-saas.md
│   │   ├── workflow-editorial.md      ← Rascunho → Privado → Público
│   │   └── sistema-versionamento.md
│   └── Academy/
│       ├── especificacao-academy.md
│       └── estrutura-lms.md
│
├── Analytics-e-Admin/
│   ├── painel-admin.md
│   ├── captura-de-dados-usuarios.md
│   └── relatorios-e-dashboards.md
│
├── Features-Avancadas/
│   ├── faq-dinamico.md
│   ├── api-docs-swagger.md
│   ├── traducao-i18next-deepl.md
│   ├── busca-global.md
│   └── integracoes-externas.md
│
└── Changelog/
    └── CHANGELOG.md                  ← Registro de todas as versões e mudanças
```

---

## Roadmap de Fases

| Fase | Nome | Status |
|------|------|--------|
| 01 | Fundação & Segurança (Supabase + Auth real) | ✅ Em andamento |
| 02 | Portfólio completo | ⏳ Aguardando fase 01 |
| 03 | Motor de Documentação SaaS | ⏳ Aguardando fase 02 |
| 04 | Academy LMS | ⏳ Aguardando fase 03 |
| 05 | Analytics & Painel Admin | ⏳ Aguardando fase 04 |
| 06 | Features Avançadas & Integrações | ⏳ Aguardando fase 05 |

---

## Contato e Créditos

**Fabiana Nonjah**  
Senior Technical Writer & Documentation Analyst  
E-mails: fabiana.nonjah@outlook.com / fnonjah@yahoo.com.br

LinkedIn: [linkedin.com/in/fabiana-nonjah-techwriter/ ](https://www.linkedin.com/in/fabiana-nonjah-techwriter/) 

