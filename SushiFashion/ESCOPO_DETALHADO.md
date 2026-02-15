# ESCOPO DETALHADO - SushiFashion

---

## 1️⃣ MÓDULO 1: WEBSITE INSTITUCIONAL

### Descrição
Website completo do restaurante SushiFashion com interface moderna, intuitiva e responsiva (mobile-first).

### Páginas e Funcionalidades

#### **Página Inicial**
- Hero section com imagem/vídeo do restaurante
- Destaques do menu
- Testemunhos de clientes
- CTA para reservar ou fazer pedido
- Horários de funcionamento
- Localização e contacto

#### **Página Sobre**
- História do restaurante
- Filosofia culinária
- Equipa (chefs, staff)
- Galeria de fotos de alta qualidade
- Valores e compromissos

#### **Sistema de Pedidos/Encomendas** (Página Única com Abas)
- Single Page com toggle entre "Reservar" e "Fazer Pedido"
- Integração com Lusobistro (aba Reservar)
- Integração com Sistema de Pedidos (aba Fazer Pedido)
- Acesso direto aos sistemas de reserva e pedido

#### **Ver Menu (Menu Visual do Site)**
- Menu interativo por categorias (Entradas, Pratos, Bebidas, etc.)
- Visualização expandida de cada prato com descrição
- Acesso responsivo (telemóvel/desktop)

#### **QuickBoxMenu (Carta Digital via QR Code)**
- Página acessível por QR Code
- Carta digital apenas visual (sem pedidos)
- Visualização otimizada para telemóvel
- Imagens de alta qualidade de cada prato
- Navegação rápida por categorias

#### **Área de Utilizador**
- Login/Registo
- Perfil pessoal
- Histórico de pedidos
- Histórico de reservas
- Preferências (alergias, dietas especiais)
- Endereços salvos

#### **Página de Promoções**
- Lista de promoções ativas com descrição
- Cupons ou códigos para desconto
- Data de validade visível
- Histórico de promoções antigas (arquivo)
- Link para aplicar promoção no pedido/reserva
- Responsivo e fácil de atualizar via admin

### Tecnologias Recomendadas
- **Frontend:** React/Vue.js + Responsive Design
- **Backend:** Node.js/Python
- **Banco de Dados:** PostgreSQL/MongoDB
- **Hosting:** Vercel, Netlify ou similar

### Entregáveis
- [x] Design (UI/UX mockups)
- [x] Desenvolvimento frontend
- [x] Desenvolvimento backend
- [x] Integração de imagens/conteúdo
- [x] Testes responsivos
- [x] Deployment e configuração de domínio

---

## 2️⃣ MÓDULO 2: INTEGRAÇÃO LUSOBISTRO (RESERVAS)

### Descrição
Integração com a plataforma Lusobistro (já existente e do fornecedor) para permitir que clientes façam reservas online através do website do SushiFashion. **Não desenvolvemos o Lusobistro, apenas fazemos a interligação.**

### O que fazemos (APENAS INTEGRAÇÃO)
- ✅ Análise da API Lusobistro
- ✅ Customização visual do iframe/widget do Lusobistro
- ✅ Integração da widget de reservas no website
- ✅ Testes de funcionalidade da integração
- ✅ Documentação técnica

### O que o Lusobistro (do fornecedor) fornece & gere (não está no escopo)
- ❌ Desenvolvimento da plataforma Lusobistro
- ❌ Gestão de reservas (backend do Lusobistro)
- ❌ Disponibilidade de mesas
- ❌ Confirmações e notificações
- ❌ Sincronização de promoções (Lusobistro já tem isto nativo)

### Fluxo
1. Cliente no website clica em "Reservar"
2. Carrega iframe/widget do Lusobistro (customizado visualmente)
3. Cliente preenche dados no Lusobistro
4. Lusobistro processa e envia confirmação (não passa por nós)

### Entregáveis
- [x] Análise da API/documentação Lusobistro
- [x] CSS customizado para match visual
- [x] Integração da widget no website
- [x] Testes de funcionalidade
- [x] Guia de manutenção (simples)

---

## 3️⃣ MÓDULO 3: INTEGRAÇÃO SISTEMA DE PEDIDOS ONLINE

### Descrição
Integração com a app de pedidos online (já existente, operacional e do fornecedor) para permitir que clientes façam pedidos/encomendas através do website do SushiFashion. **Não desenvolvemos a app de pedidos, apenas fazemos a interligação.**

### O que fazemos (APENAS INTEGRAÇÃO)
- ✅ Análise da API/documentação da app de pedidos
- ✅ Customização visual/branding do iframe/widget
- ✅ Integração da app de pedidos no website
- ✅ Testes de funcionalidade
- ✅ Documentação técnica

### O que a App de Pedidos (do fornecedor) fornece (não está no escopo)
- ❌ Desenvolvimento da app de pedidos
- ❌ Gestão de carrinho
- ❌ Processamento de pagamentos (responsabilidade da app)
- ❌ Notificações de pedidos
- ❌ Histórico de pedidos
- ❌ Dashboard de pedidos para restaurante

### Fluxo
1. Cliente no website clica em "Fazer Pedido"
2. Carrega iframe/widget da app de pedidos (customizado)
3. Cliente seleciona itens, endereço, etc. (na app de pedidos)
4. App de pedidos processa pagamento e envia confirmação (não passa por nós)

### Entregáveis
- [x] Análise da API/documentação da app de pedidos
- [x] CSS customizado para match visual
- [x] Integração da widget no website
- [x] Testes de funcionalidade
- [x] Guia de manutenção

---

## 4️⃣ MÓDULO 4: PAINEL ADMINISTRATIVO

### Descrição
Dashboard web para que a equipa SushiFashion gerencie conteúdos, promoções, Menu Visual do site e QuickBoxMenu (QR), além de visualizar dados de desempenho.

### Funcionalidades Principais

#### **Gestão de Conteúdos**
- Editor de páginas (Sobre, Inicial, etc.)
- Gestão de horários de funcionamento
- Informações de contacto e localização
- Gestão de eventos/notícias

#### **Gestão de Menu (Visual do Site)**
- CRUD de categorias e pratos (cartão visual do website)
- Upload de imagens
- Descrições detalhadas
- Preços
- Disponibilidade (prato disponível/indisponível)
- Filtros por alergias/dietas
- **IMPORTANTE:** Preços e categorias do Menu Visual alimentam o QuickBoxMenu.

#### **Gestão de QuickBoxMenu (QR)**
- Usa a mesma base de preços do Menu Visual
- Permite adicionar fotos e descrições específicas para a carta digital
- Ordenação rápida por categorias para leitura no telemóvel

#### **Gestão de Galeria**
- Upload em batch de fotos
- Organização por albuns/categorias
- Otimização automática de imagens
- Permissões de visualização

#### **Criação de Promoções (Website)**
- Criação de cupons de desconto (para comunicação no website)
- Definição de datas válidas
- Controlo de uso (máx 1 vez, múltiplas vezes, etc.)
- **NOTA:** Promoções do website NÃO se sincronizam automaticamente com pedidos/Lusobistro
- Cliente gere promoções separadamente em cada plataforma

#### **Promoções QuickBoxMenu (QR)**
- Aba específica para promoções do QuickBoxMenu
- Promoções exibidas apenas na carta digital
- Histórico de promoções próprias do QuickBoxMenu

#### **Dashboard de Desempenho**
- Número de pedidos por período
- Receita total
- Pratos mais populares
- Taxa de conversão (visualizações → reserva/pedido)
- Análise de picos de horário
- Feedback de clientes

#### **Gestão de Utilizadores**
- Permissões por role (admin, manager, staff)
- Logs de atividade
- Segurança (2FA, password resets)

### Entregáveis
- [x] Desenvolvimento do dashboard
- [x] Autenticação e autorização
- [x] UI intuitiva e responsiva
- [x] Relatórios exportáveis
- [x] Documentação de utilizador
- [x] Formação para equipa SushiFashion

---

## 📊 INTEGRAÇÃO ENTRE MÓDULOS

```
Website (Módulo 1)
    ├── Integra Lusobistro (Módulo 2) [widget de reservas]
    ├── Integra Pedidos (Módulo 3) [widget de pedidos - independente]
    ├── Menu Visual (Módulo 4) [cartão visual apenas]
    └── QuickBoxMenu (Módulo 4) [carta digital visual via QR]

Admin (Módulo 4)
    ├── Gerencia Menu Visual + QuickBoxMenu (preços partilhados)
    ├── Gerencia Conteúdos e Imagens
    └── Gerencia Promoções (Website e QuickBoxMenu)

Sistema Pedidos (Módulo 3)
    └── Completamente independente (gerido separadamente pelo restaurante)
```

---

## 🗓️ CRONOGRAMA ESTIMADO (A DEFINIR)

| Fase | Duração | Dependências |
|------|---------|--------------|
| Design & Arquitetura | 1-2 semanas | - |
| Módulo 1 (Website) | 3-4 semanas | Design |
| Módulo 2 (Integração Lusobistro) | 3-5 dias | Website pronto |
| Módulo 3 (Integração Pedidos) | 3-5 dias | Website pronto |
| Módulo 4 (Admin) | 2-3 semanas | Módulo 1 pronto |
| Testes & QA | 1 semana | Todos os módulos |
| **TOTAL** | **8-12 semanas** | - |

---

## 📌 NOTAS IMPORTANTES

- Todas as integrações externas (Lusobistro, Pagamentos) requerem coordenação com o cliente
- Design deve ser coerente em todos os módulos
- Será necessário acesso a credenciais do Lusobistro e gateway de pagamento
- Recomenda-se começar com uma fase de discovery de 1-2 semanas para refinar cronograma

