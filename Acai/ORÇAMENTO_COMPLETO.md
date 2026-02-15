# Orçamento Completo - Sistema para 3 Lojas de Açaí

## 📋 Informação do Cliente

- **Cliente**: [Nome do Cliente]
- **Data**: [Data]
- **Nível**: Desenvolvedor Júnior
- **Valor por hora**: **20€/hora** (faixa júnior: 15-25€/hora)
- **Valor por dia**: **160€/dia** (8 horas × 20€)

---

## 🎯 Descrição do Projeto

Sistema completo de gestão e vendas online para 3 lojas de açaí, incluindo:
1. Website único (açai.com) com apresentação das 3 lojas e navegação para /loja1, /loja2, /loja3
2. Sistema de pedidos online (takeaway e delivery) com cálculo de taxas por distância
3. Aplicação de gestão para o salão (dashboard administrativo)
4. Aplicação móvel para estafetas com sistema simplificado de gestão de entregas
5. Sistema de notificações: WhatsApp Business para clientes (estado do pedido) e push notifications para estafetas

---

## 💰 RESUMO EXECUTIVO

**Valor Original**: **12.000€**  
**Desconto Aplicado**: **-3.000€**  
**Valor Total Final**: **9.000€**  
**Prazo Estimado**: 124.5 dias úteis (aproximadamente 6 meses)  
**Horas Totais**: 996 horas

### Breakdown do Investimento

| Componente | Dias | Horas | Valor |
|------------|------|-------|-------|
| Website Multi-Loja (SASS) | 11.5 | 92 | 833€ |
| Sistema de Pedidos Online | 25.5 | 204 | 1.845€ |
| App de Gestão (Dashboard) | 25 | 200 | 1.808€ |
| App para Estafetas | 8 | 64 | 578€ |
| Funcionalidades Extras | 22.5 | 180 | 1.628€ |
| **Funcionalidades Adicionais** | **33** | **264** | **2.308€** |
| **TOTAL** | **124.5** | **996** | **9.000€** |

### Fases de Pagamento

1. **30% no início**: 2.700€
2. **40% na entrega parcial**: 3.600€ (Website + Sistema de Pedidos + App Gestão)
3. **30% na conclusão**: 2.700€ (App Estafetas + Funcionalidades Extras + Funcionalidades Adicionais)

---

## PARTE 1: Website Multi-Loja (SASS)

### 1.1 Página Inicial Principal (açai.com)
**Estrutura de URLs**:
- `açai.com` - Página inicial
- `açai.com/loja1` - Loja 1
- `açai.com/loja2` - Loja 2
- `açai.com/loja3` - Loja 3

**Funcionalidades**:
- Hero section com apresentação do negócio
- Cards/seções para cada uma das 3 lojas
- Navegação intuitiva para cada loja
- Design responsivo (mobile, tablet, desktop)
- SEO básico otimizado
- Animações e transições suaves
- Desenvolvido com SASS para estilização modular

**Tempo estimado**: 2.5 dias (20 horas)

### 1.2 Páginas Individuais por Loja
**Páginas por loja** (3 lojas × 4 páginas = 12 páginas):

#### a) Página Inicial da Loja
- Apresentação da loja específica
- Destaques e promoções
- Link para fazer pedido
- Galeria de imagens
- Horários de funcionamento
**Tempo**: 1 dia por loja = 3 dias (24 horas)

#### b) Página Sobre
- História da loja
- Missão e valores
- Equipa
- Diferenciais
**Tempo**: 0.5 dias por loja = 1.5 dias (12 horas)

#### c) Página Endereço/Contactos
- Mapa interativo (Google Maps)
- Endereço completo
- Telefone e email
- Horários de funcionamento detalhados
- Instruções de como chegar
- Formulário de contacto
**Tempo**: 0.5 dias por loja = 1.5 dias (12 horas)

#### d) Página Encomendas
- Link direto para o sistema de pedidos
- Informações sobre takeaway e delivery
- Áreas de entrega
- Tempos estimados
- Política de cancelamento
**Tempo**: 0.5 dias por loja = 1.5 dias (12 horas)

**Subtotal**: 6.5 dias (52 horas)

### 1.3 Funcionalidades Adicionais do Website
- Sistema de navegação entre lojas
- Menu de navegação global
- Footer com informações gerais
- Integração com redes sociais
- Formulários de contacto funcionais
- Página de política de privacidade e termos
- Sistema de cookies/GDPR compliance
- Configuração de rotas dinâmicas
- Arquitetura SASS modular

**Tempo estimado**: 2.5 dias (20 horas)

**TOTAL PARTE 1**: 11.5 dias (92 horas) = **1.840€**

---

## PARTE 2: Sistema de Pedidos Online (Takeaway e Delivery)

### 2.1 Sistema de Autenticação e Área do Cliente
- Registro de clientes
- Login/Logout
- Recuperação de senha
- **Área do Cliente**:
  - Login na área de pedidos
  - Perfil do cliente
  - Gestão de endereços de entrega
  - **Histórico de últimas encomendas**:
    - Lista de todos os pedidos anteriores
    - Status de cada pedido
    - Detalhes do pedido
    - Possibilidade de repetir pedido
- Histórico de pedidos

**Tempo estimado**: 3 dias (24 horas)

### 2.2 Catálogo de Produtos
- Gestão de produtos por loja
- Categorias de produtos
- Imagens dos produtos
- Descrições e preços
- Personalização de produtos (tamanhos, extras, etc.)
- Disponibilidade por loja
- Gestão de estoque básico
- **Tempo médio de preparo** configurável por produto ou categoria
- Sistema calcula tempo estimado baseado em tempo de preparo dos produtos

**Tempo estimado**: 4.5 dias (36 horas)
*Aumentado devido ao sistema de tempo médio de preparo*

### 2.3 Carrinho de Compras
- Adicionar/remover produtos
- Editar quantidades
- Cálculo automático de totais
- Seleção de loja
- Seleção de tipo de pedido:
  - **Takeaway (Cliente busca na loja)**: Cliente vai buscar pessoalmente
  - **Delivery**: Entrega em casa
- **Sistema de Takeaway (Cliente busca)**:
  - Cliente seleciona "Vou buscar na loja"
  - **Estafeta NÃO é notificado** (não precisa de entrega)
  - Espaço recebe notificação que cliente vai buscar
  - Espaço sabe que é takeaway e prepara para retirada
  - Cliente recebe notificação quando pedido está pronto
  - Cliente vai buscar na loja
- Seleção de horário de retirada/entrega
- Cálculo de taxas de entrega (apenas para delivery)
- Cálculo de distância para delivery (apenas para delivery)
- **Cálculo de tempo estimado**: Tempo médio de preparo dos produtos

**Tempo estimado**: 4 dias (32 horas)
*Aumentado devido ao sistema de takeaway (cliente busca)*

### 2.4 Checkout e Pagamento
- Processo de checkout em etapas
- Validação de dados
- Seleção de método de pagamento:
  - **MB Way** (integração com API MB Way)
  - **Dinheiro na entrega**:
    - Cliente informa se precisa de troco ou não
    - Se precisa troco: cliente informa valor que vai dar
    - Sistema calcula troco necessário
    - **Estafeta é notificado sobre valor exato para dar de troco**
    - Exemplo: Pedido 15€, cliente dá 20€, estafeta leva 5€ de troco
  - Pagamento na loja (takeaway)
- Confirmação de pedido
- Geração de recibo/comprovante
- Envio de email de confirmação

**Tempo estimado**: 4 dias (32 horas)

### 2.5 Sistema de Delivery Avançado

#### Validação de Área de Entrega
- Cliente insere endereço de entrega
- Sistema calcula distância do endereço até a loja selecionada (Google Maps API)
- Verifica se endereço está dentro da área de entrega configurada
- Se estiver fora: mostra mensagem "Não entregamos nesta área"
- Se estiver dentro: continua com o pedido

#### Cálculo de Taxas por Distância (Sistema Dinâmico)
- Sistema calcula distância exata (Google Maps Distance Matrix API)
- Classifica em 3 zonas:
  - **Zona Próxima** (0-3km): Taxa base X, métodos de pagamento A, B
  - **Zona Média** (3-6km): Taxa base Y (maior), métodos A, B, C
  - **Zona Distante** (6-10km): Taxa base Z (ainda maior), métodos limitados
- Taxa aumenta progressivamente com a distância
- Cliente vê taxa antes de confirmar pedido

#### Sistema de Pagamento
- **Métodos disponíveis**: MB Way ou Dinheiro
- **Cálculo do total**: Valor do pedido + Taxa de entrega = Total
- **Integração MB Way**: Verificar API e documentação para integração
- **Pagamento em dinheiro**: Sistema calcula troco e notifica estafeta

#### Configuração de Áreas de Entrega por Loja
- Cada loja tem raio máximo de entrega configurável
- Exemplo: Loja 1 entrega até 10km, Loja 2 até 8km
- Sistema valida automaticamente se endereço está dentro do raio

**Fluxo Completo:**
1. Cliente seleciona loja
2. Cliente insere endereço de entrega
3. Sistema calcula distância endereço-loja
4. Sistema verifica se está dentro da área de entrega
5. Se NÃO estiver: "Não entregamos nesta área. Por favor, escolha outra loja ou endereço."
6. Se estiver: Sistema classifica em zona (Próxima/Média/Distante)
7. Sistema calcula taxa baseada na zona e distância
8. Sistema mostra métodos de pagamento disponíveis para aquela zona
9. Cliente vê taxa total antes de confirmar

- Tempo estimado de entrega baseado em distância
- Seleção de endereço no mapa (Google Maps)
- **Validação de endereços**:
  - Verificação se endereço existe (geocodificação Google Maps)
  - Validação de CEP/Código Postal
  - Sugestões de endereço (autocompletar)
  - Se endereço não existe: mostra erro e pede correção
- Mensagens claras para o cliente sobre área e taxas

**Tempo estimado**: 6 dias (48 horas)

### 2.6 Notificações e Comunicação
- Email de confirmação de pedido
- Email de atualização de status
- **Integração com WhatsApp Business (APENAS para clientes)**:
  - Notificação quando estafeta aceita pedido (apenas delivery)
  - Notificação quando pedido concluído pelo espaço (vai a caminho)
  - Notificação quando pedido está pronto (takeaway)
  - Notificação quando pedido foi entregue/retirado
  - Mensagens automáticas de atualização de status do pedido
  - **IMPORTANTE**: Notificações WhatsApp são APENAS para clientes, não para estafetas
- Notificações push no app do cliente
- Sistema de mensagens via WhatsApp Business API

**Tempo estimado**: 4 dias (32 horas)

**TOTAL PARTE 2**: 25.5 dias (204 horas) = **4.080€**
*Aumentado devido à área do cliente, validação de endereços, tempo médio de preparo e sistema takeaway*

*Cálculo: 3 + 4.5 + 4 + 4 + 6 + 4 = 25.5 dias (204 horas)*

---

## PARTE 3: Aplicação de Gestão (Dashboard Administrativo)

### 3.1 Autenticação e Gestão de Utilizadores
- Login para funcionários/gerentes
- Diferentes níveis de acesso (admin, gerente, funcionário)
- Gestão de utilizadores
- Permissões por função

**Tempo estimado**: 2 dias (16 horas)

### 3.2 Dashboard Principal
- Visão geral de pedidos do dia
- Estatísticas (pedidos, receitas, etc.)
- Gráficos e métricas
- Alertas e notificações
- Filtros por loja

**Tempo estimado**: 3 dias (24 horas)

### 3.3 Gestão de Pedidos (Core Feature)
- Lista de pedidos em tempo real
- Filtros (por loja, status, data, tipo: takeaway/delivery)
- Visualização detalhada de cada pedido
- **Diferenciação visual entre Takeaway e Delivery**
- Atualização de status (Estados do Pedido):
  - **Pedido Pendente** (cliente fez pedido, aguardando espaço aceitar)
  - **Pedido Aceito** (espaço aceitou, começou preparação)
  - **Pedido Pronto** (espaço terminou preparação):
    - Se **Delivery**: Pronto para estafeta buscar
    - Se **Takeaway**: Pronto para cliente buscar na loja
  - **Pedido Saiu para Entrega** (apenas delivery - estafeta pegou e está a caminho)
  - **Pedido Retirado** (apenas takeaway - cliente buscou na loja)
  - **Pedido Entregue** (apenas delivery - estafeta entregou ao cliente)
  - **Cancelado** (cliente ou espaço cancelou)
- **Sistema de Takeaway (Cliente busca)**:
  - Espaço vê que é pedido takeaway
  - Espaço sabe que cliente vai buscar pessoalmente
  - **Estafeta NÃO é notificado** (não precisa de entrega)
  - Quando pedido fica pronto, cliente é notificado
  - Cliente vai buscar na loja
  - Espaço marca como "Retirado" quando cliente busca

#### Sistema de Cancelamento e Reembolsos
- **Cliente pode cancelar a qualquer momento ANTES do pedido ser aceito pelo espaço**
- **Após espaço aceitar**: Cliente não pode mais cancelar (ou política específica)
- **Loja pode cancelar a qualquer momento** com motivo obrigatório
- **Motivos de cancelamento** (espaço seleciona):
  - Produto sem estoque
  - Problema técnico
  - Fora do horário de entrega
  - Outro (com descrição)
- **Quando espaço cancela por "produto sem estoque"**:
  - Espaço informa qual produto
  - Produto desaparece automaticamente da página OU fica sinalizado como "Sem estoque"
  - Cliente é notificado sobre cancelamento e motivo
- **Reembolso automático** se pagamento já foi processado
- **Política de cancelamento** clara e visível para o cliente
- Notificação ao cliente sobre cancelamento com motivo

#### Timeout de Pedidos
- **IMPORTANTE**: Só descontamos valor do cliente quando pedido é ACEITO pelo espaço
- **Antes do espaço aceitar**: Cliente pode cancelar livremente, sem cobrança
- **Após espaço aceitar**: Pedido é confirmado e valor é processado
- Se nenhum estafeta aceitar em 5 minutos, sistema **re-notifica todos os estafetas disponíveis**
- Sistema continua re-notificando até alguém aceitar ou espaço cancelar
- Loja pode cancelar pedido a qualquer momento se necessário

- Notificações automáticas ao cliente
- Histórico completo de pedidos
- Impressão de pedidos/comandas

**Tempo estimado**: 6 dias (48 horas)

### 3.4 Gestão de Produtos
- CRUD completo de produtos
- Gestão por loja
- Upload de imagens
- Gestão de categorias
- Gestão de preços
- Gestão de disponibilidade
- **Configuração de tempo médio de preparo**:
  - Tempo configurável por produto (ex: 10 minutos, 15 minutos)
  - Tempo configurável por categoria (ex: Açaí: 10min, Smoothies: 5min)
  - Sistema calcula tempo total baseado nos produtos do pedido
  - Cliente vê tempo estimado de preparo

#### Gestão de Estoque Simplificada
- **NÃO há gestão complexa de estoque**
- **Se produto acabou e saiu pedido**:
  - Espaço pode cancelar o pedido com motivo "produto sem estoque"
  - OU entrar em contacto com cliente para resolver (substituir produto, etc.)
- **Quando espaço cancela por falta de estoque**:
  - Espaço seleciona motivo "produto sem estoque"
  - Espaço informa qual produto específico
  - **Produto desaparece automaticamente da página** OU fica sinalizado como "Sem estoque"
  - Produto não aparece mais no catálogo até espaço reativar
- **Espaço pode reativar produto** quando tiver estoque novamente

**Tempo estimado**: 4 dias (32 horas)

### 3.5 Gestão de Lojas
- Informações de cada loja

#### Horários de Funcionamento Avançados
- Horários diferentes por dia da semana
- Horários especiais (feriados)
- Fechamento temporário (ex: férias)
- Sistema não aceita pedidos fora do horário

#### Configuração de Áreas de Entrega
- Raio máximo de entrega por loja (em km)
- Configuração de zonas (Próxima, Média, Distante)
- Taxas de entrega por zona
- Métodos de pagamento por zona

- Taxas de entrega
- Contactos

**Tempo estimado**: 3 dias (24 horas)

### 3.6 Gestão de Clientes
- Lista de clientes
- Histórico de pedidos por cliente
- Informações de contacto
- Endereços salvos

**Tempo estimado**: 2 dias (16 horas)

### 3.7 Relatórios e Analytics
- Relatórios de vendas
- Relatórios por loja
- Relatórios por período
- Produtos mais vendidos
- Exportação de dados (PDF, Excel)
- Métricas de performance

**Tempo estimado**: 3 dias (24 horas)

### 3.8 Configurações
- Configurações gerais do sistema
- Configurações de pagamento
- Configurações de notificações
- Configurações de delivery
- Gestão de utilizadores

**Tempo estimado**: 2 dias (16 horas)

**TOTAL PARTE 3**: 25 dias (200 horas) = **4.000€**

---

## PARTE 4: Aplicação para Estafetas (App Móvel)

### 4.1 Autenticação e Perfil de Estafeta
- Login para estafetas
- Perfil do estafeta
- Gestão de informações pessoais
- Status online/offline

**Tempo estimado**: 1 dia (8 horas)

### 4.2 Sistema de Gestão de Estafetas (Simplificado)
- Gestão de 3 estafetas

#### Sistema de Notificação para Todos
- Quando pedido fica pronto, **todos os estafetas disponíveis recebem notificação**
- Estafetas veem pedido disponível na lista
- **Primeiro estafeta que aceitar, pega o pedido**
- Se nenhum aceitar em X minutos, pedido volta para fila ou notifica novamente

#### Gestão de Folgas e Horários
- Calendário de folgas por estafeta
- Horários de trabalho configuráveis (ex: 9h-18h)
- Status de disponibilidade (online, offline, em pausa)
- Sistema só notifica estafetas online, não em folga, dentro do horário

#### Cálculo de Tempo Estimado
- Tempo fixo baseado em distância cliente-loja
- Fórmula: Tempo de preparação + Tempo médio de entrega

**Como funciona na prática:**
1. Pedido fica pronto na loja
2. Sistema busca estafetas disponíveis (online, não em folga, dentro do horário)
3. **Notifica TODOS os estafetas disponíveis** via app (push notifications)
4. Estafetas veem pedido na lista de "Pedidos Disponíveis"
5. **Primeiro estafeta que clicar "Aceitar" pega o pedido**
6. Outros estafetas recebem notificação que pedido foi aceito
7. **Cliente é notificado via WhatsApp** quando estafeta aceita
8. Se ninguém aceitar em 5 minutos, sistema pode notificar novamente

**Tempo estimado**: 3 dias (24 horas)

### 4.3 Interface de Pedidos para Estafetas
- Lista de pedidos atribuídos
- Visualização detalhada do pedido
- Endereço da loja e do cliente
- Aceitar/Rejeitar pedido
- Atualizar status de entrega:
  - Pedido aceito
  - A caminho da loja
  - A caminho do cliente
  - Entregue
- **Notificação automática ao cliente**: "Seu pedido saiu para entrega" (quando estafeta marca "a caminho do cliente")
- Histórico de entregas
- **Histórico detalhado de entregas**:
  - Lista de todas as entregas do estafeta
  - **Quilómetros percorridos por entrega**
  - Distância de cada entrega
  - Tempo de entrega
  - Data e hora
  - **Preparação para sistema de pagamento**:
    - Em Portugal estafetas ganham por valor fixo OU por kms
    - Sistema registra kms para cálculo futuro
    - Preparado para implementar sistema de pagamento por kms depois
- Estatísticas pessoais (entregas, ganhos, etc.)

**Tempo estimado**: 3 dias (24 horas)

### 4.4 Notificações ao Cliente (Simplificado)
- **Notificação simples ao cliente**: "Seu pedido saiu para entrega"
- Notificação quando estafeta aceita pedido

**Tempo estimado**: 0.5 dias (4 horas)

### 4.5 Notificações para Estafetas
- Notificação de novo pedido disponível (via app e push notifications)
- Notificação de pedido atribuído
- Notificação de atualização de status
- **IMPORTANTE**: Estafetas recebem notificações APENAS via app (push notifications), NÃO via WhatsApp
- Sistema de notificações push nativas do app

**Tempo estimado**: 1.5 dias (12 horas)

**TOTAL PARTE 4**: 8 dias (64 horas) = **1.280€**

---

## PARTE 5: Funcionalidades Adicionais e Integrações

### 5.1 Integrações de Pagamento
- **Integração com MB Way**:
  - Verificar API e documentação MB Way
  - Configuração de integração
  - Processamento de pagamentos MB Way
  - Confirmação de pagamento
- **Sistema de pagamento em dinheiro**:
  - Cliente informa se precisa troco
  - Cálculo automático de troco
  - Notificação ao estafeta sobre valor de troco
- Gestão de reembolsos
- Histórico de transações
- **IMPORTANTE**: Valor só é processado quando espaço aceita pedido

**Tempo estimado**: 3 dias (24 horas)

### 5.2 Integração com Mapas (Simplificada)
- Google Maps API
- Geocodificação de endereços (converter endereço em coordenadas)
- Cálculo de distância cliente-loja para taxas de entrega
- Mapas estáticos no website (apenas mostrar localização das lojas)

**Tempo estimado**: 1 dia (8 horas)

### 5.3 Integração WhatsApp Business
- Configuração da API do WhatsApp Business
- **Envio de mensagens automáticas APENAS para clientes**:
  - Confirmação de pedido
  - Estafeta aceitou pedido (apenas delivery)
  - Pedido concluído (vai a caminho)
  - Pedido está pronto (takeaway)
  - Pedido entregue/retirado
- Templates de mensagens
- Notificações de status via WhatsApp (apenas clientes)
- **IMPORTANTE**: Estafetas NÃO recebem notificações via WhatsApp, apenas via app

**Tempo estimado**: 3 dias (24 horas)

### 5.4 Sistema de Notificações em Tempo Real
- Firestore listeners para atualizações em tempo real
- Notificações push (Firebase Cloud Messaging)
- Sistema de alertas sonoros
- Notificações para cliente, loja e estafeta
- Sincronização em tempo real entre todos os sistemas

**Tempo estimado**: 3 dias (24 horas)

### 5.5 Configuração Firebase
- Setup do projeto Firebase
- Configuração de Firestore (base de dados)
- Configuração de Firebase Authentication
- Configuração de Firebase Cloud Messaging (notificações push)
- Configuração de Firebase Storage (imagens)
- Configuração de Firebase Hosting (se necessário)
- Regras de segurança do Firestore
- Índices otimizados
- Backup e sincronização em tempo real

**Tempo estimado**: 3 dias (24 horas)

### 5.6 Otimizações e Performance
- Otimização de imagens
- Cache de dados (Firebase)
- Lazy loading
- Compressão de assets
- CDN (se necessário)
- Otimização de queries Firestore
- Paginação de dados

**Tempo estimado**: 2 dias (16 horas)

### 5.7 Testes e Qualidade
- Testes de funcionalidades
- Testes de usabilidade
- Testes do sistema de estafetas
- Testes de cálculo de distâncias
- Testes de notificações WhatsApp
- Correção de bugs
- Testes em diferentes dispositivos
- Testes de performance

**Tempo estimado**: 4 dias (32 horas)

### 5.8 Deploy e Configuração
- Configuração de servidor/hosting
- Configuração de domínio (açai.com)
- Configuração de SSL
- Deploy do website
- Deploy das aplicações (web e mobile)
- Configuração Firebase em produção
- Backup automático
- Monitoramento

**Tempo estimado**: 3 dias (24 horas)

### 5.9 Documentação e Treino
- Documentação técnica
- Manual do utilizador (cliente)
- Manual do utilizador (loja)
- Manual do utilizador (estafeta)
- Treino para funcionários das lojas
- Treino para estafetas
- Suporte inicial

**Tempo estimado**: 3 dias (24 horas)

**TOTAL PARTE 5**: 22.5 dias (180 horas) = **3.600€**
*Aumentado devido a integração MB Way*

---

## PARTE 6: Funcionalidades Adicionais (Incluídas no Orçamento)

### 6.1 Sistema de Avaliações
- Cliente pode avaliar pedido após entrega/retirada
- Cliente pode avaliar estafeta (apenas delivery)
- Espaço pode ver avaliações recebidas
- Sistema de rating (estrelas) e comentários
- Média de avaliações por loja e estafeta

**Tempo estimado**: 3 dias (24 horas)

### 6.2 Sistema de Cupons e Descontos
- Criação de cupons de desconto
- Códigos promocionais
- Descontos percentuais ou valores fixos
- Validação de cupons
- Aplicação automática no checkout
- Histórico de cupons utilizados
- Limite de uso por cupom

**Tempo estimado**: 3 dias (24 horas)

### 6.3 Programa de Fidelidade
- Sistema de pontos por pedido
- Cliente ganha pontos conforme valor gasto
- Conversão de pontos em descontos
- Histórico de pontos
- Níveis de fidelidade (Bronze, Prata, Ouro)
- Benefícios por nível
- Dashboard de pontos para cliente

**Tempo estimado**: 4 dias (32 horas)

### 6.4 Chat em Tempo Real
- Chat entre cliente e espaço
- Suporte ao cliente
- Resolução de dúdidas
- Histórico de conversas
- Notificações de novas mensagens

**Tempo estimado**: 3 dias (24 horas)

### 6.5 App Mobile Nativo
- App iOS nativo
- App Android nativo
- Notificações push nativas
- Melhor performance
- Funcionalidades offline
- Instalação via App Store e Google Play

**Tempo estimado**: 10 dias (80 horas)

### 6.6 Multi-idioma
- Suporte a múltiplos idiomas
- Tradução de conteúdo
- Seleção de idioma pelo cliente
- Tradução de emails e notificações
- Tradução de interface completa

**Tempo estimado**: 3 dias (24 horas)

### 6.7 Analytics Avançado
- Google Analytics integrado
- Heatmaps de navegação
- A/B testing
- Métricas de conversão
- Análise de comportamento do cliente
- Relatórios de performance

**Tempo estimado**: 2 dias (16 horas)

### 6.8 Login Social
- Login com Google
- Login com Facebook
- Autenticação social rápida
- Redução de fricção no registro
- Vinculação de contas sociais

**Tempo estimado**: 2 dias (16 horas)

### 6.9 Sistema de Pagamento de Estafetas por Kms
- Cálculo automático de pagamento baseado em kms
- Configuração de valor por km
- Relatórios de pagamento
- Histórico de ganhos por estafeta
- Sistema já preparado (kms registrados), só falta implementar cálculo
- Dashboard de ganhos para estafeta

**Tempo estimado**: 3 dias (24 horas)

**TOTAL PARTE 6**: 33 dias (264 horas) = **5.280€**

---

## 🔧 TECNOLOGIAS UTILIZADAS

- **Frontend Website**: React/Next.js com **SASS** para estilização
- **Backend**: Firebase Functions (serverless) ou Node.js/Express
- **Base de Dados**: **Firebase Firestore** (tempo real, escalável, NoSQL)
- **Autenticação**: Firebase Authentication
- **Storage**: Firebase Storage (imagens e ficheiros)
- **Notificações Push**: Firebase Cloud Messaging (FCM)
- **Pagamentos**: MB Way, Dinheiro na entrega
- **Mapas**: Google Maps API
- **Mensagens**: WhatsApp Business API
- **Hosting**: Firebase Hosting ou Vercel/Netlify
- **Real-time**: Firestore listeners (substitui WebSockets tradicional)
- **App Mobile**: React Native ou PWA (Progressive Web App)

### Por Que Firebase?

1. **Tempo Real Nativo** - Firestore sincroniza automaticamente dados entre todos os dispositivos
2. **Escalabilidade Automática** - Cresce automaticamente com o número de pedidos
3. **Desenvolvimento Mais Rápido** - Autenticação, Storage e Cloud Messaging prontos
4. **Segurança Integrada** - Regras de segurança do Firestore, SSL/HTTPS automático
5. **Custo-Benefício** - Plano gratuito generoso, pay-as-you-go
6. **Ideal para Apps Móveis** - SDKs nativos, offline-first

---

## ⚠️ OBSERVAÇÕES IMPORTANTES

1. **Hosting e Domínio**: Não incluído no orçamento. O cliente deve adquirir separadamente.
2. **Manutenção**: Este orçamento cobre apenas o desenvolvimento inicial. Manutenção futura será cotada separadamente.
3. **Alterações de Escopo**: Alterações significativas durante o desenvolvimento podem afetar o prazo e custo.
4. **Conteúdo**: O cliente deve fornecer textos, imagens e informações das lojas.
5. **Prazo**: Estimativa de 124.5 dias úteis (aproximadamente 6 meses considerando 5 dias úteis por semana).
6. **Tempo médio de preparo**: Sistema configurável por produto/categoria para cálculo de tempo estimado.
7. **Sistema Takeaway (Cliente busca)**: Cliente pode buscar na loja, estafeta não é notificado, espaço sabe que é takeaway.
8. **Notificações WhatsApp**: Apenas para clientes sobre estado do pedido. Estafetas recebem notificações apenas via app.

---

## 💰 ESTIMATIVA DE CUSTOS MENSAIS (APÓS DESENVOLVIMENTO)

**IMPORTANTE**: Estes custos são mensais e recorrentes, pagos diretamente pelo cliente aos fornecedores. NÃO estão incluídos no orçamento de desenvolvimento.

### APIs e Serviços Externos

#### 1. WhatsApp Business API
- **Custo**: Variável conforme número de conversas
- **Modelo de cobrança**: 
  - Cobrança por **conversa** (não por mensagem)
  - **1 conversa = 24 horas** (todas as mensagens enviadas/recebidas dentro de 24h contam como 1 conversa)
  - Preços variam por país/região (Portugal: ~0,05€ - 0,10€ por conversa)
  - **Não há mais plano gratuito** de 1.000 conversas
- **Estimativa mensal**: 
  - Depende do número de conversas (pedidos + interações)
  - Exemplo: 500 pedidos/mês = ~500-800 conversas (incluindo notificações de status)
  - **Estimativa para 3 lojas com volume médio**: **~40-80€/mês**
  - Volume alto (1000+ pedidos/mês): **~80-150€/mês**

#### 2. Google Maps API
- **Custo**: 
  - Primeiros $200/mês: **Grátis** (créditos mensais)
  - Após isso: pay-as-you-go
- **Estimativa mensal**: 
  - Volume baixo/médio: **0-15€/mês** (provavelmente grátis)
  - Volume alto: 15€ - 50€/mês
  - **Estimativa para 3 lojas**: **0-20€/mês**

#### 3. Firebase (Google Cloud)
- **Custo**: 
  - Plano gratuito generoso (Spark) - inclui:
    - Firestore: 50.000 leituras/dia, 20.000 escritas/dia, 20.000 exclusões/dia
    - Storage: 5GB
    - Cloud Functions: 2 milhões de invocações/mês
    - Authentication: Ilimitado
    - Cloud Messaging: Ilimitado
  - Após isso: pay-as-you-go (muito barato)
- **Estimativa mensal** (baseada em projeto similar com 500 salões = ~100€/mês):
  - **Volume baixo/médio**: **0€ - 15€/mês** (provavelmente dentro do plano gratuito)
  - **Volume médio/alto**: **15€ - 30€/mês**
  - **Volume muito alto**: 30€ - 50€/mês
  - **Estimativa para 3 lojas de açaí**: **0€ - 20€/mês** (muito provavelmente grátis ou muito barato)
  - **Nota**: Firebase é extremamente econômico. Projeto com 500 salões paga ~100€, então 3 lojas deve ser muito menos

#### 4. MB Way (Pagamentos)
- **Custo**: Taxas por transação
- **Estimativa**: 
  - Taxa por transação: ~0,5% - 1,5% (verificar com banco/fornecedor)
  - **Estimativa mensal**: Depende do volume de vendas
  - Exemplo: 10.000€ em vendas = 50€ - 150€ em taxas
  - **Estimativa**: **Variável conforme vendas**

#### 5. Hosting e Domínio
- **Domínio (.com)**: ~10€ - 15€/ano (~1€/mês)
- **Hosting Website**: 
  - Opção básica: 5€ - 15€/mês
  - Opção profissional: 20€ - 50€/mês
  - **Estimativa**: **10-30€/mês**

### Resumo de Custos Mensais Estimados

| Serviço | Estimativa Mensal |
|---------|-------------------|
| WhatsApp Business API | 40€ - 80€ |
| Google Maps API | 0€ - 20€ |
| Firebase | 0€ - 20€ |
| MB Way (taxas) | Variável (0,5% - 1,5% das vendas) |
| Hosting e Domínio | 10€ - 30€ |
| **TOTAL ESTIMADO** | **50€ - 130€/mês** (sem contar taxas MB Way) |

### Observações Importantes:
- **Custos variam conforme volume**: Quanto mais pedidos, maior o custo
- **Plano gratuito disponível**: Muitos serviços têm planos gratuitos generosos
- **Primeiros meses podem ser mais baratos**: Dentro dos limites dos planos gratuitos
- **Taxas MB Way**: Dependem diretamente do volume de vendas
- **Recomendação**: Orçamento mensal de **70€ - 150€** para começar (sem contar taxas de pagamento)
- **Nota sobre Firebase**: Baseado em projeto similar (500 salões = ~100€), 3 lojas de açaí provavelmente ficará dentro do plano gratuito ou muito barato (0-20€/mês)
- **Nota sobre WhatsApp**: Cada conversa dura 24 horas. Todas as notificações de um pedido (confirmação, aceito, pronto, entregue) dentro de 24h contam como 1 conversa

---

## ✅ FUNCIONALIDADES INCLUÍDAS

### Website
- ✅ Página inicial com 3 lojas
- ✅ Navegação entre lojas (/loja1, /loja2, /loja3)
- ✅ Páginas completas por loja (Inicial, Sobre, Endereço, Encomendas)
- ✅ Design responsivo desenvolvido com SASS
- ✅ SEO básico
- ✅ Integração com redes sociais
- ✅ Formulários de contacto
- ✅ Política de privacidade e termos

### Sistema de Pedidos
- ✅ Registro e login de clientes
- ✅ **Área do Cliente** com login e histórico de encomendas
- ✅ Catálogo de produtos por loja
- ✅ Carrinho de compras
- ✅ Checkout completo
- ✅ **Métodos de pagamento: MB Way e Dinheiro** (com cálculo de troco)
- ✅ Validação de área de entrega
- ✅ Validação de endereços (verifica se existe)
- ✅ Cálculo dinâmico de taxas por distância
- ✅ Sistema de takeaway (cliente busca na loja - estafeta não notificado)
- ✅ Tempo médio de preparo configurável
- ✅ Seleção de horário
- ✅ Confirmação por email e WhatsApp
- ✅ Histórico de pedidos
- ✅ Possibilidade de repetir pedido

### App de Gestão
- ✅ Login para funcionários
- ✅ Dashboard com estatísticas
- ✅ Gestão de pedidos em tempo real
- ✅ Atualização de status de pedidos (incluindo "Retirado" para takeaway)
- ✅ Diferenciação entre Takeaway e Delivery
- ✅ Sistema de cancelamento e reembolsos
- ✅ Timeout de pedidos
- ✅ Gestão de produtos com estoque avançado
- ✅ Gestão de lojas com horários avançados
- ✅ Configuração de áreas de entrega
- ✅ Gestão de clientes
- ✅ Relatórios e analytics
- ✅ Configurações do sistema
- ✅ Notificações em tempo real

### App para Estafetas
- ✅ Login para estafetas
- ✅ Sistema de notificação para todos (primeiro que aceita, pega)
- ✅ Gestão de folgas e horários
- ✅ Cálculo de tempo estimado (simplificado)
- ✅ Aceitar/Rejeitar pedidos
- ✅ Lista de pedidos disponíveis
- ✅ Notificação ao cliente "pedido saiu para entrega"
- ✅ **Histórico detalhado de entregas com quilómetros percorridos**
- ✅ Estatísticas pessoais
- ✅ Preparação para sistema de pagamento por kms (futuro)

### Funcionalidades Extras
- ✅ Integração com Firebase (Firestore, Auth, Storage, FCM)
- ✅ Integração com WhatsApp Business
- ✅ Integração com mapas (Google Maps)
- ✅ Cálculo de distâncias
- ✅ Sistema de pagamento (MB Way e Dinheiro com troco)
- ✅ Notificações push (Firebase Cloud Messaging)
- ✅ Notificações WhatsApp automáticas (apenas para clientes)
- ✅ Otimizações de performance
- ✅ Testes e qualidade
- ✅ Deploy e configuração
- ✅ Documentação completa

### Funcionalidades Adicionais (Incluídas)
- ✅ Sistema de avaliações de pedidos e estafetas
- ✅ Sistema de cupons e descontos
- ✅ Programa de fidelidade (pontos por pedido)
- ✅ Chat em tempo real com suporte
- ✅ App mobile nativo (iOS/Android)
- ✅ Multi-idioma
- ✅ Analytics avançado (Google Analytics, heatmaps)
- ✅ Login social (Google/Facebook)
- ✅ Sistema de pagamento de estafetas por kms

---

**Data de criação**: [Data]  
**Validade do orçamento**: 30 dias

