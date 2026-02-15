# CHECKLIST DETALHADO - SushiFashion

Acompanhamento de todas as tarefas necessárias para a entrega completa do projeto.

---

## 📋 PRÉ-DESENVOLVIMENTO

### Descoberta & Planeamento
- [ ] Reunião de kickoff com cliente
- [ ] Definição final de cores/logo/brand guidelines
- [ ] Análise de requisitos de desempenho
- [ ] Estrutura de hosting/domínio decidida
- [ ] Credenciais de acesso (Lusobistro, etc.) obtidas
- [ ] Estrutura de preços do restaurante definida
- [ ] Horários de funcionamento confirmados
- [ ] Equipa SushiFashion designada para feedback

### Design
- [ ] Wireframes de todas as páginas
- [ ] Mockups de alta fidelidade
- [ ] Design de componentes reutilizáveis
- [ ] Design responsivo (mobile/tablet/desktop)
- [ ] Aprovação de design pelo cliente
- [ ] Guia de estilos criado

---

## 1️⃣ MÓDULO 1: WEBSITE INSTITUCIONAL

### Setup Inicial
- [ ] Repositório Git criado
- [ ] Estrutura de pastas definida
- [ ] Dependências instaladas (React/Vue, etc.)
- [ ] Configuração de build tools (Webpack, Vite, etc.)
- [ ] Variáveis de ambiente configuradas

### Desenvolvimento Frontend

#### Página Inicial
- [ ] Hero section implementada
- [ ] Destaques de menu criados
- [ ] Widget de avaliações
- [ ] CTAs funcionais
- [ ] Footer com contacto
- [ ] Responsividade testada

#### Página Sobre
- [ ] Conteúdo de história
- [ ] Galeria de fotos da equipa
- [ ] Valores/missão apresentados
- [ ] Layout responsivo

#### Menu Visual (Página Ver Menu)
- [ ] Categorias dinâmicas (BD)
- [ ] Filtros de categorias
- [ ] Cards de pratos com imagens
- [ ] Descrições completas
- [ ] Preços exibidos
- [ ] Ícones de alergias/dietas
- [ ] Responsividade em telemóvel

#### QuickBoxMenu (QR - Carta Digital Visual)
- [ ] Landing page QR separada
- [ ] Gerador de QR code integrado
- [ ] Versão otimizada para telemóvel
- [ ] Carta digital visual (sem pedidos)
- [ ] Cache de imagens otimizado

#### Pedidos/Encomendas (Página Única)
- [ ] Toggle entre Reservar/Pedido implementado
- [ ] Form de reserva (conecta a Lusobistro)
- [ ] Form de pedido (conecta a app de pedidos)
- [ ] Validação de campos
- [ ] Indicadores visuais de sucesso/erro

#### Área de Utilizador
- [ ] Autenticação/login implementados
- [ ] Registo de novo utilizador
- [ ] Perfil pessoal (nome, email, telefone)
- [ ] Edição de preferências (alergias, dietas)
- [ ] Histórico de pedidos exibido
- [ ] Histórico de reservas exibido
- [ ] Endereços salvos (CRUD)
- [ ] Logout funcionando

#### Página de Promoções
- [ ] Lista de promoções ativas exibida
- [ ] Descrição e termos de cada promoção
- [ ] Datas de validade visíveis
- [ ] Cupons/códigos de desconto exibidos
- [ ] Histórico de promoções antigas (arquivo/secção separada)
- [ ] Link para aplicar promoção no checkout
- [ ] Responsividade completa (mobile/desktop)
- [ ] Paginação ou scroll infinito (se muitas promoções)

### Desenvolvimento Backend
- [ ] API principal estruturada
- [ ] Autenticação JWT implementada
- [ ] BD de utilizadores criada
- [ ] BD de promoções criada (ativas + arquivo)
- [ ] BD de menu criada
- [ ] Endpoints de utilizador (GET, POST, PUT)
- [ ] Endpoints de menu (GET)
- [ ] Endpoints de promoções (GET ativas, GET arquivo)
- [ ] Limitação de taxa implementada
- [ ] Validação de input
- [ ] Error handling robusto

### Integração de Conteúdo
- [ ] Logo do restaurante integrado
- [ ] Imagens de alta qualidade importadas
- [ ] Textos de conteúdo aprovados
- [ ] Mapa/localização integrada
- [ ] Horários dinâmicos
- [ ] Informações de contacto

### Testes & QA
- [ ] Testes unitários (funcionalidades críticas)
- [ ] Testes de integração
- [ ] Teste de responsividade (todos os breakpoints)
- [ ] Teste de performance (lighthouse score > 85)
- [ ] Teste de acessibilidade (WCAG 2.1)
- [ ] Teste de navegadores (Chrome, Firefox, Safari, Edge)
- [ ] Teste em dispositivos reais
- [ ] SEO configurado (meta tags, sitemap)

### Deployment
- [ ] Certificado SSL configurado
- [ ] Domínio apontado corretamente
- [ ] CDN configurada para imagens
- [ ] Backups automáticos
- [ ] Monitorização de uptime
- [ ] Logs configurados

---

## 2️⃣ MÓDULO 2: INTEGRAÇÃO LUSOBISTRO

### Análise & Preparação
- [ ] Documentação da API Lusobistro obtida
- [ ] Endpoints disponíveis mapeados
- [ ] Estrutura de resposta analisada
- [ ] Autenticação Lusobistro compreendida
- [ ] Credenciais de teste obtidas
- [ ] Exemplos de API testados em Postman/Insomnia

### Integração no Website
- [ ] Widget/iframe do Lusobistro obtido
- [ ] Estilo (CSS) customizado para coerência visual
- [ ] Widget integrado na página "Reservar"
- [ ] Testes de responsividade (telemóvel/tablet)
- [ ] Testes de navegação (antes/depois da integração)

### Testes
- [ ] Teste de carregamento da widget
- [ ] Teste de fluxo de reserva end-to-end
- [ ] Teste de timeout/erro na API
- [ ] Teste em múltiplos browsers
- [ ] Teste em dispositivos reais

### Documentação
- [ ] Documentação técnica de integração
- [ ] Guia de manutenção (como atualizar)
- [ ] Contacto para suporte Lusobistro

---

## 3️⃣ MÓDULO 3: INTEGRAÇÃO SISTEMA DE PEDIDOS ONLINE

### Análise & Preparação
- [ ] Documentação da API/Widget da app de pedidos obtida
- [ ] Endpoints disponíveis mapeados
- [ ] Estrutura de resposta analisada
- [ ] Autenticação compreendida
- [ ] Credenciais de teste obtidas
- [ ] Exemplos de API testados

### Integração no Website
- [ ] Widget/iframe da app de pedidos obtido
- [ ] Estilo (CSS) customizado para coerência visual
- [ ] Widget integrado na página "Fazer Pedido"
- [ ] Testes de responsividade (telemóvel/tablet)
- [ ] Testes de navegação


- [ ] Documentação técnica de integração
- [ ] Guia de manutenção
- [ ] Contacto para suporte da app de pedidos

---

## 4️⃣ MÓDULO 4: PAINEL ADMINISTRATIVO

### Setup Inicial
- [ ] Dashboard scaffolding criado
- [ ] Autenticação/autorização implementada
- [ ] Estrutura de BD de admin
- [ ] Perfis (admin, manager, staff) definidos

### Gestão de Menu (Visual + QuickBox)
- [ ] CRUD de categorias (Create, Read, Update, Delete)
- [ ] CRUD de pratos
- [ ] Upload de imagens com validação
- [ ] Otimização automática de imagens
- [ ] Editor de descrição com rich text
- [ ] Preços (únicos, aplicam ao Menu Visual e QuickBox)
- [ ] Toggle de disponibilidade
- [ ] Filtros de alergias/dietas selecionáveis
- [ ] Pré-visualização de menu
- [ ] Histórico de mudanças

### Gestão de QuickBoxMenu (QR)
- [ ] Fotos específicas para carta digital
- [ ] Descrições específicas para carta digital
- [ ] Ordenação rápida por categorias

### Gestão de Galeria
- [ ] Upload em batch de múltiplas imagens
- [ ] Organização em albuns/categorias
- [ ] Compressão automática de imagens
- [ ] Edição de metadados (alt text, descrição)
- [ ] Remoção/arquivamento
- [ ] Pré-visualização

### Criação de Promoções (Website)
- [ ] Novo cupom/promoção
- [ ] Código gerado automaticamente
- [ ] Tipo: Percentagem / Valor fixo
- [ ] Valor/Percentagem definível
- [ ] Data de validade selecionável
- [ ] Uso limitado (máx de usos)
- [ ] Um uso por cliente (toggle)
- [ ] Descrição e termos da promoção
- [ ] Ativação/desativação rápida
- [ ] Lista de promoções ativas/expiradas
- [ ] Possibilidade de arquivar promoções antigas
- [ ] Histórico mantém promoções antigas visíveis no website

### Promoções QuickBoxMenu (QR)
- [ ] Aba específica para promoções do QuickBox
- [ ] Promoções exibidas apenas na carta digital
- [ ] Histórico de promoções do QuickBox

### Gestão de Conteúdo
- [ ] Editor de página "Sobre"
- [ ] Editor de página "Inicial" (hero, destaques)
- [ ] Horários de funcionamento (visão semanal)
- [ ] Contactos (telefone, email, endereço)
- [ ] Redes sociais (links)
- [ ] Notícias/blog (opcional)
- [ ] Histórico de versões

### Dashboard de Desempenho
- [ ] Números-chave (total pedidos, revenue, pedidos hoje)
- [ ] Gráfico de pedidos por período (dia/semana/mês)
- [ ] Gráfico de revenue por período
- [ ] Pratos mais populares (top 5)
- [ ] Horários de picos (heatmap)
- [ ] Taxa de conversão (cliques → pedido)
- [ ] Feedback/ratings médios
- [ ] Exportação de relatórios (PDF/CSV)

### Gestão de Utilizadores
- [ ] Lista de utilizadores (clientes)
- [ ] Remoção/bloqueio de conta
- [ ] Histórico de pedidos de cliente específico
- [ ] Preferências do cliente (alergias)
- [ ] Contacto direto (se necessário)

### Gestão de Equipa (Opcional)
- [ ] Criar utilizador admin/manager/staff
- [ ] Atribuir permissões por role
- [ ] Remoção de utilizador
- [ ] Logs de atividade

### Segurança
- [ ] Autenticação com JWT
- [ ] 2FA (two-factor authentication) opcional
- [ ] Password reset seguro
- [ ] Logs de atividade completos
- [ ] HTTPS obrigatório
- [ ] CORS configurado
- [ ] Limitação de taxa

### Testes & QA
- [ ] Teste de CRUD em todas as secções
- [ ] Teste de permissões por perfil
- [ ] Teste de upload de imagens (tamanho, formato)
- [ ] Teste de performance (muitos itens no menu)
- [ ] Teste de responsividade (tablet OK)
- [ ] Teste de segurança (SQL injection, XSS)

### Documentação & Formação
- [ ] Manual de utilizador em PDF
- [ ] Screenshots tutorial de funções-chave
- [ ] Vídeo tutorial (opcional)
- [ ] FAQ
- [ ] Suporte técnico acordado

---

## 🔗 INÍCIO INTEGRAÇÃO CRUZADA

- [ ] Website acede ao Menu do Admin (visual apenas)
- [ ] Sistema de Pedidos funciona de forma independente
- [ ] Lusobistro integrado sem dados compartilhados
- [ ] Testes de fluxo completo (Website → Reserva + Pedido independentes)

---

## ✅ QA FINAL

- [ ] Teste end-to-end de utilizador novo (reserva + pedido)
- [ ] Teste end-to-end de cliente existente (login, histórico)
- [ ] Performance global (lighthouse score > 85 primeiras cargas)
- [ ] Compatibilidade de browsers
- [ ] Teste de carga (simular múltiplos usuários simultâneos)
- [ ] Segurança (pentest leve ou checklist OWASP)

---

## 📦 ENTREGA

- [ ] Documentação técnica completa
- [ ] Código bem documentado
- [ ] Repositório Git com histórico limpo
- [ ] Credenciais e configurações entregues com segurança
- [ ] Documentação de deployment
- [ ] Plano de suporte/manutenção definido
- [ ] Formação da equipa concluída

---

## 📊 MÉTRICAS DE SUCESSO

| Métrica | Target |
|---------|--------|
| Lighthouse Score | > 85 |
| Tempo de carregamento | < 3s (FCP) |
| Uptime | > 99.5% |
| Taxan de conversão | > 2% |
| Satisfação de cliente | > 4/5 |
| Bugs em produção (primeiros 3 meses) | < 5 |

