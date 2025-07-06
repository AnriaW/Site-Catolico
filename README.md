# Kanban - Site Auxílio dos Cristãos (React + Spring Boot + MongoDB/MySQL)

## 🔧 Backlog (Setup Inicial)
- [ ] Configurar ambiente React + Vite (Deadline: **20/08/2024**) ⭐⭐  
- [ ] Instalar Spring Boot com MongoDB + MySQL (Deadline: **22/08/2024**) ⭐⭐⭐  
- [ ] Criar esquema MongoDB: `santos`, `orações`, `posts` (Deadline: **25/08/2024**) ⭐⭐  
- [ ] Criar tabelas MySQL: `usuários`, `cidades`, `missas` (Deadline: **25/08/2024**) ⭐⭐⭐  

## 📋 To Do (Tarefas Prioritárias)
### 🏠 Homepage (Front-end)
- [ ] Criar componente Navbar (React) (Deadline: **28/08/2024**) ⭐  
- [ ] Banner rotativo (JavaScript) (Deadline: **28/08/2024**) ⭐⭐  
- [ ] Layout: 2 posts grandes + 6 pequenos (CSS Grid) (Deadline: **30/08/2024**) ⭐⭐  

### 🟢 MySQL (Back-end)
- [ ] API para cadastro de usuários (Spring Boot) (Deadline: **05/09/2024**) ⭐⭐⭐  
- [ ] API para cidades/confissões (com Google Maps) (Deadline: **10/09/2024**) ⭐⭐⭐⭐  

### 🔵 MongoDB (Back-end)
- [ ] API CRUD para santos (Deadline: **30/08/2024**) ⭐⭐⭐  
- [ ] API para orações/liturgia (Deadline: **03/09/2024**) ⭐⭐⭐  

## 🚧 In Progress (Em Andamento)
*(Puxe tarefas do "To Do" quando iniciar)*  
- [ ] Página de listagem de santos (React + MongoDB API) (Deadline: **05/09/2024**) ⭐⭐⭐  

## ✅ Done (Concluído)
- [x] Definir arquitetura (React + Spring Boot + MongoDB/MySQL) (Deadline: **15/08/2024**)  

---

## 📅 Cronograma Detalhado

### Fase 1: Setup (Até 25/08)
- Ambiente dev + configuração dos bancos

### Fase 2: Core (Até 10/09)
- Homepage + APIs básicas (santos, usuários)

### Fase 3: Admin (Até 20/09)
- Painel de controle (autenticação JWT + CRUDs)

### Fase 4: Integrações (Até 10/10)
- Google Maps (missas), PagSeguro (doações)

---

## 🗂 Divisão dos Bancos
| MongoDB (Conteúdo)       | MySQL (Dados Estruturados)  |
|--------------------------|-----------------------------|
| - Santos                 | - Usuários                  |
| - Orações                | - Cidades                   |
| - Meditações             | - Locais de missa           |
| - Posts (blog)           | - Intenções de oração       |

---

## 💡 Próximos Passos
1. Comece pela **homepage estática** (React)  
2. Implemente **1 API por vez** (ex: MongoDB para santos primeiro)  
3. Use `@Repository` no Spring Boot para separar MongoDB/MySQL:
   
   

### Observações:
1. Os prazos assumem **~2-3 horas de trabalho por dia** (ajuste conforme sua disponibilidade).  
2. Marcadores visuais (🔵 MongoDB / 🟢 MySQL) ajudam a rastrear qual banco está sendo usado.  
3. Incluí todas as páginas do escopo original, mas foquei no **MVP** (homepage + santos + orações).  
