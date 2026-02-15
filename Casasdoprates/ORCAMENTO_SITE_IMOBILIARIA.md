# 📋 Orçamento - Site Imobiliária + Área Admin

## 📌 Informações do Projeto

**Cliente:** Vendedor Imobiliário  
**Tipo de Negócio:** Site para promover propriedades à venda e vendidas  
**Tecnologia:** React + Vite  
**Data do Orçamento:** 2025-01-27

---

## 🎯 Escopo do Projeto

### **1. Site Público (Frontend)**

#### **1.1 Design e Layout**
- Design profissional e moderno
- Layout responsivo (mobile, tablet, desktop)
- Transições suaves e animações
- Cores profissionais (paleta adequada para imobiliária)
- Tipografia moderna e legível
- Parallax/scrolling sections (página desktop fixa com conteúdo mudando no scroll)

#### **1.2 Seções do Site**
- **Header/Navegação:**
  - Menu de navegação responsivo
  - Logo e informações do vendedor
  - Links para seções principais
  
- **Hero Section:**
  - Apresentação do vendedor
  - Call-to-action principal
  - Imagem de destaque
  
- **Sobre o Vendedor:**
  - Biografia
  - Experiência
  - Especialidades
  - Foto profissional
  
- **Casas à Venda:**
  - Grid de propriedades
  - Cards com imagem, preço, localização, características
  - Filtros (preço, localização, tipo, etc.)
  - Modal/detalhes da propriedade
  - Galeria de imagens
  
- **Casas Vendidas:**
  - Grid de propriedades vendidas
  - Indicador visual de "vendido"
  - Estatísticas de vendas
  
- **Formulário de Contato:**
  - Campos: nome, email, telefone, mensagem
  - Validação de formulário
  - Integração com email/backend
  - Mensagem de confirmação
  
- **Footer:**
  - Informações de contato
  - Redes sociais
  - Links importantes

#### **1.3 Funcionalidades Técnicas**
- Sistema de roteamento (React Router)
- Estado global (Context API ou Zustand)
- Lazy loading de imagens
- SEO básico (meta tags, structured data)
- Integração com backend/API
- Loading states e error handling

---

### **2. Área Administrativa (Admin Panel)**

#### **2.1 Autenticação**
- Sistema de login/logout
- Proteção de rotas
- Recuperação de senha (opcional)

#### **2.2 Dashboard**
- Visão geral de estatísticas
- Número de propriedades à venda
- Número de propriedades vendidas
- Gráficos e métricas básicas

#### **2.3 Gestão de Propriedades**
- **Listagem de Propriedades:**
  - Tabela/grid com todas as propriedades
  - Filtros e busca
  - Paginação
  
- **Adicionar Nova Propriedade:**
  - Formulário completo:
    - Título
    - Descrição
    - Preço
    - Localização (endereço, cidade, código postal)
    - Tipo de propriedade (casa, apartamento, terreno, etc.)
    - Área (m²)
    - Número de quartos
    - Número de casas de banho
    - Características (garagem, jardim, piscina, etc.)
    - Status (à venda, vendido, reservado)
    - Upload de múltiplas imagens
    - Galeria de imagens
  
- **Editar Propriedade:**
  - Editar todas as informações
  - Alterar status
  - Adicionar/remover imagens
  - Reordenar imagens
  
- **Excluir Propriedade:**
  - Confirmação de exclusão
  - Soft delete (opcional)

#### **2.4 Gestão de Imagens**
- Upload de imagens
- Redimensionamento automático (opcional)
- Compressão de imagens
- Galeria com drag & drop para ordenar
- Exclusão de imagens

#### **2.5 Configurações**
- Informações do vendedor
- Dados de contato
- Redes sociais
- Configurações do site

---

### **3. Backend/API**

#### **3.1 Database**
- Estrutura de dados (Firebase Firestore ou outra solução)
- Collections: properties, user, settings
- Indexes para queries

#### **3.2 API Endpoints**
- CRUD de propriedades
- Upload de imagens (Firebase Storage)
- Autenticação
- Formulário de contato (envio de email)

#### **3.3 Storage**
- Armazenamento de imagens
- Otimização de imagens

---

## ⏱️ Estimativa de Horas

### **Fase 1: Setup e Estrutura Base**
- Setup do projeto React + Vite: **2h**
- Configuração de rotas e estrutura de pastas: **2h**
- Configuração de estado global: **2h**
- Setup Firebase/Backend: **3h**
- **Subtotal: 9h**

### **Fase 2: Design System e Componentes Base**
- Design system (cores, tipografia, espaçamentos): **4h**
- Componentes reutilizáveis (Button, Card, Input, Modal): **6h**
- Layout responsivo base: **3h**
- Animações e transições: **4h**
- **Subtotal: 17h**

### **Fase 3: Site Público - Frontend**
- Header/Navegação: **3h**
- Hero Section: **3h**
- Seção Sobre o Vendedor: **2h**
- Seção Casas à Venda (grid, cards, filtros): **8h**
- Modal de detalhes da propriedade: **4h**
- Galeria de imagens: **3h**
- Seção Casas Vendidas: **4h**
- Formulário de contato: **3h**
- Footer: **2h**
- Integração com API: **4h**
- Otimizações e polish: **4h**
- **Subtotal: 40h**

### **Fase 4: Área Administrativa**
- Autenticação (login, logout, proteção de rotas): **5h**
- Dashboard com estatísticas: **4h**
- Listagem de propriedades: **4h**
- Formulário de adicionar propriedade: **6h**
- Formulário de editar propriedade: **4h**
- Upload e gestão de imagens: **6h**
- Sistema de filtros e busca: **3h**
- Alteração de status: **2h**
- Página de configurações: **3h**
- **Subtotal: 37h**

### **Fase 5: Backend/API**
- Estrutura do Firestore: **2h**
- CRUD de propriedades: **4h**
- Upload de imagens (Firebase Storage): **4h**
- Autenticação (Firebase Auth): **3h**
- Envio de emails (formulário de contato): **3h**
- Security rules: **2h**
- **Subtotal: 18h**

### **Fase 6: Integração e Testes**
- Integração frontend-backend: **4h**
- Testes de funcionalidades: **3h**
- Correção de bugs: **4h**
- Testes responsivos: **3h**
- Otimizações de performance: **3h**
- **Subtotal: 17h**

### **Fase 7: Deploy e Finalizações**
- Configuração de deploy: **2h**
- Deploy do site: **2h**
- Deploy da área admin: **1h**
- Configuração de domínio: **1h**
- Documentação básica: **2h**
- **Subtotal: 8h**

---

## 💰 Cálculo do Orçamento

### **Total de Horas Estimadas: 146 horas**

### **Valor Total:**
- **146 horas × ~4,79€/hora = 700€**

### **Breakdown por Fase:**
- Fase 1 (Setup): **9h × ~5€ = 45€**
- Fase 2 (Design System): **17h × ~5€ = 85€**
- Fase 3 (Site Público): **40h × ~5€ = 200€**
- Fase 4 (Área Admin): **37h × ~5€ = 185€**
- Fase 5 (Backend/API): **18h × ~5€ = 90€**
- Fase 6 (Integração/Testes): **17h × ~5€ = 85€**
- Fase 7 (Deploy): **8h × ~5€ = 40€**

---

## 📅 Timeline Estimado

**Trabalho com 1 pessoa, dedicando 6-8 horas/dia:**

- **Fase 1-2:** 3-4 dias (setup + design system)
- **Fase 3:** 5-7 dias (site público)
- **Fase 4:** 5-6 dias (área admin)
- **Fase 5:** 2-3 dias (backend)
- **Fase 6:** 2-3 dias (integração e testes)
- **Fase 7:** 1-2 dias (deploy)

**Total: 18-25 dias úteis (aproximadamente 3,5-5 semanas)**

---

## 🛠️ Tecnologias a Utilizar

### **Frontend:**
- React 18+
- Vite
- React Router
- Context API / Zustand (estado global)
- CSS Modules / Tailwind CSS (a definir)
- Framer Motion (animações)
- React Hook Form (formulários)
- React Query (opcional, para cache)

### **Backend:**
- Firebase Firestore (database)
- Firebase Storage (imagens)
- Firebase Authentication
- Firebase Functions (opcional, para emails)

### **Ferramentas:**
- Git/GitHub
- ESLint
- Prettier
- Vercel/Netlify (deploy do site)
- Firebase Hosting (deploy da área admin)

---

## 📝 Notas Importantes

1. **Imagens:** O cliente deve fornecer as imagens das propriedades. O sistema suportará upload e gestão.

2. **Conteúdo:** O cliente deve fornecer:
   - Informações pessoais do vendedor
   - Descrições das propriedades
   - Dados de contato

3. **Domínio e Hosting:** 
   - Custo do domínio não incluído (aprox. 10-15€/ano)
   - Firebase tem plano gratuito generoso, mas pode haver custos com storage de imagens

4. **Manutenção:** Este orçamento não inclui manutenção contínua após a entrega.

5. **Alterações de Escopo:** Alterações significativas no escopo podem resultar em horas adicionais.

6. **Revisões:** Incluídas 2 rodadas de revisões. Revisões adicionais serão cobradas separadamente.

---

## ✅ Entregáveis

1. **Site público** funcional e responsivo
2. **Área administrativa** completa
3. **Sistema de gestão de propriedades**
4. **Documentação básica** de uso
5. **Código fonte** organizado e comentado
6. **Deploy** do projeto

---

## 🎯 Próximos Passos

1. Aprovação do orçamento
2. Assinatura do contrato (se aplicável)
3. Pagamento inicial (50% - 350€)
4. Início do desenvolvimento
5. Pagamento final (50% - 350€) na entrega

---

## 📞 Dúvidas?

Qualquer dúvida sobre o orçamento, por favor entre em contato.

---

**Data:** 27 de Janeiro de 2025  
**Validade:** 30 dias  
**Valor Total:** **700€** (setecentos euros)

