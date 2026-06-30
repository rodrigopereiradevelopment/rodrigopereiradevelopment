# Olá, eu sou o Rodrigo Pereira! 👋

**Desenvolvedor Full-Stack** | Foco em arquitetura de dados, performance e acessibilidade

Estudante de Técnico em Desenvolvimento de Sistemas na ETEC Pedro Ferreira Alves (conclusão jul/2026), ingressando em Análise e Desenvolvimento de Sistemas pela Fatec. Fiz a transição de carreira do trabalho braçal pra tecnologia, e hoje desenvolvo aplicações completas em domínios diferentes — comparador de preços, editor acadêmico desktop com IA local e sistemas de gestão.

---

## 🚀 Projetos em destaque

### 🛒 [ARCA](https://github.com/rodrigopereiradevelopment/arca-ionic) — Comparador de Preços Inteligente

Plataforma mobile e web que monitora preços de **6 supermercados em Mogi Mirim**, cobrindo **~58 mil produtos**. TCC apresentado em 2026.

- Pipeline de scraping em Python com estratégias específicas por mercado (GraphQL, Salesforce Commerce Cloud, REST, BeautifulSoup)
- Busca em três estágios: ILIKE com índice GIN → similaridade trigram → embeddings semânticos (pgvector)
- Sync otimizado de **27 minutos para ~2 minutos** via batch upsert + RPC com DISTINCT ON
- Push notifications (FCM), câmera, cupons, integração com Open Food Facts API
- Arquitetura: Ionic/Angular (mobile/web) · Next.js BFF (Vercel) · PostgreSQL/Supabase · MongoDB Atlas (camada bronze)

### 📝 [EditeCC](https://github.com/rodrigopereiradevelopment/editecc) — Editor Acadêmico com IA Local

Editor desktop open source para trabalhos acadêmicos em normas ABNT, com IA rodando **100% local** (sem APIs externas).

- Tauri + Next.js, build multiplataforma (Windows, Linux, macOS)
- Tradução offline (NLLB-200) e sumarização (DistilBART) via Transformers.js, cacheados em IndexedDB
- Geração automática de slides PowerPoint a partir do documento
- Acessibilidade conforme WCAG 2.2

### ☕ Quero Café Bar — Sistema de Gestão (Projeto Acadêmico)

API REST com NestJS + frontend Ionic, **235 testes automatizados** (146 backend + 89 frontend).

- Autenticação JWT, RBAC com bcrypt e RolesGuard
- Build Android via Capacitor

---

## 🛠️ Stack

| Categoria | Tecnologias |
|---|---|
| **Linguagens** | TypeScript, JavaScript, Python, SQL |
| **Front-end / Mobile** | Next.js, React, Ionic, Angular, HTML5, CSS3 |
| **Back-end** | Node.js, NestJS, APIs REST |
| **Banco de Dados** | PostgreSQL (Supabase, pgvector, RLS), MongoDB Atlas |
| **Desktop** | Tauri (Rust) |
| **IA & Embeddings** | Transformers.js, pgvector, NLLB-200, fastembed |
| **Ferramentas** | Git, Vercel, Termux, Linux Mint |

---

## 📊 Atividade recente

Mais de 700 contribuições no último ano, com desenvolvimento ativo simultâneo em múltiplos projetos — ARCA (frontend + backend), EditeCC e Quero Café Bar.

![GitHub stats](https://github-readme-stats.vercel.app/api?username=rodrigopereiradevelopment&show_icons=true&theme=default)

---

## 📫 Contato

[LinkedIn]https://www.linkedin.com/in/rodrigopereirarp
