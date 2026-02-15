# 🎨 Conceitos de Design - Site Imobiliária

## 🎯 Visão Geral

Este documento descreve os conceitos de design para o site imobiliária, incluindo paleta de cores, tipografia, layout e elementos visuais.

---

## 🎨 Paleta de Cores

### **Cores Principais**

#### **Azul Profissional** (Primary)
- **Hex:** #2563EB
- **RGB:** rgb(37, 99, 235)
- **Uso:** Botões principais, links, elementos de destaque
- **Variações:**
  - Light: #3B82F6
  - Dark: #1D4ED8
  - Lighter: #DBEAFE

#### **Cinza Neutro** (Secondary)
- **Hex:** #6B7280
- **RGB:** rgb(107, 114, 128)
- **Uso:** Textos secundários, bordas, elementos neutros
- **Variações:**
  - Light: #9CA3AF
  - Dark: #374151
  - Lighter: #F3F4F6

#### **Verde Sucesso** (Success)
- **Hex:** #10B981
- **RGB:** rgb(16, 185, 129)
- **Uso:** Propriedades vendidas, mensagens de sucesso
- **Variações:**
  - Light: #34D399
  - Dark: #059669

#### **Branco** (Background)
- **Hex:** #FFFFFF
- **RGB:** rgb(255, 255, 255)
- **Uso:** Fundo principal, cards, seções

#### **Preto** (Text)
- **Hex:** #111827
- **RGB:** rgb(17, 24, 39)
- **Uso:** Textos principais, títulos

### **Cores de Apoio**
- **Laranja/Amarelo:** #F59E0B (destaques, avisos)
- **Vermelho:** #EF4444 (erros, alertas)
- **Roxo:** #8B5CF6 (elementos especiais)

---

## 📝 Tipografia

### **Fontes Principais**

#### **Títulos (Headings)**
- **Fonte:** Inter, sans-serif
- **Pesos:** 600 (SemiBold), 700 (Bold)
- **Tamanhos:**
  - H1: 2.5rem (40px)
  - H2: 2rem (32px)
  - H3: 1.5rem (24px)
  - H4: 1.25rem (20px)

#### **Textos (Body)**
- **Fonte:** Inter, sans-serif
- **Peso:** 400 (Regular), 500 (Medium)
- **Tamanho:** 1rem (16px)
- **Line Height:** 1.6

#### **Textos Pequenos (Small)**
- **Fonte:** Inter, sans-serif
- **Peso:** 400 (Regular)
- **Tamanho:** 0.875rem (14px)

### **Hierarquia Tipográfica**
- **Títulos:** Negrito, maior, cor escura
- **Subtítulos:** Médio, tamanho médio
- **Textos:** Regular, tamanho padrão
- **Textos secundários:** Regular, cor cinza, tamanho pequeno

---

## 📐 Layout e Espaçamentos

### **Container**
- **Max Width:** 1200px
- **Padding:** 1rem (mobile), 2rem (desktop)
- **Margin:** 0 auto

### **Grid System**
- **Colunas:** 12 colunas
- **Gap:** 1rem (mobile), 2rem (desktop)
- **Breakpoints:**
  - Mobile: < 768px
  - Tablet: 768px - 1024px
  - Desktop: > 1024px

### **Espaçamentos**
- **Base Unit:** 0.5rem (8px)
- **Espaçamentos:**
  - XS: 0.5rem (8px)
  - SM: 1rem (16px)
  - MD: 1.5rem (24px)
  - LG: 2rem (32px)
  - XL: 3rem (48px)
  - 2XL: 4rem (64px)

---

## 🎭 Elementos Visuais

### **Cards**
- **Background:** Branco
- **Border:** 1px sólido, cinza claro
- **Border Radius:** 0.5rem (8px)
- **Shadow:** 0 1px 3px rgba(0, 0, 0, 0.1)
- **Hover:** Shadow aumentada, transição suave
- **Padding:** 1.5rem

### **Botões**
- **Primary:**
  - Background: Azul principal
  - Text: Branco
  - Border Radius: 0.5rem
  - Padding: 0.75rem 1.5rem
  - Hover: Background mais escuro
  - Transition: 200ms

- **Secondary:**
  - Background: Transparente
  - Text: Azul principal
  - Border: 1px sólido, azul principal
  - Hover: Background azul claro

### **Inputs**
- **Border:** 1px sólido, cinza claro
- **Border Radius:** 0.5rem
- **Padding:** 0.75rem 1rem
- **Focus:** Border azul, shadow
- **Error:** Border vermelho, texto de erro

### **Modals**
- **Background:** Overlay escuro (rgba(0, 0, 0, 0.5))
- **Content:** Branco, centralizado
- **Border Radius:** 1rem
- **Shadow:** Grande shadow
- **Max Width:** 90% (mobile), 600px (desktop)
- **Animation:** Fade in + scale

---

## 🎬 Animações e Transições

### **Transições Padrão**
- **Duração:** 200ms - 300ms
- **Easing:** ease-in-out
- **Propriedades:** opacity, transform, color, background

### **Animações**
- **Fade In:** opacity 0 → 1
- **Slide Up:** transform translateY(20px) → translateY(0)
- **Scale:** transform scale(0.95) → scale(1)
- **Hover:** transform scale(1.05), shadow aumentada

### **Loading States**
- **Skeleton:** Placeholder com animação shimmer
- **Spinner:** Loading spinner animado
- **Progress Bar:** Barra de progresso

---

## 📱 Responsividade

### **Mobile First**
- Design pensado primeiro para mobile
- Progressive enhancement para desktop
- Breakpoints bem definidos
- Touch-friendly (botões maiores, espaçamentos adequados)

### **Breakpoints**
- **Mobile:** < 768px
  - Colunas: 1
  - Padding: 1rem
  - Font sizes: Menores
  - Menu: Hamburger

- **Tablet:** 768px - 1024px
  - Colunas: 2-3
  - Padding: 1.5rem
  - Font sizes: Médios
  - Menu: Horizontal

- **Desktop:** > 1024px
  - Colunas: 3-4
  - Padding: 2rem
  - Font sizes: Maiores
  - Menu: Horizontal completo

---

## 🏠 Seções Específicas

### **Hero Section**
- **Background:** Imagem de propriedade ou gradiente
- **Overlay:** Escuro semi-transparente
- **Text:** Branco, grande, negrito
- **CTA:** Botão grande, destacado
- **Height:** 100vh (desktop), 70vh (mobile)

### **Property Cards**
- **Image:** Ratio 16:9, object-fit cover
- **Badge:** Status (à venda, vendido)
- **Price:** Grande, negrito, cor destaque
- **Location:** Ícone + texto
- **Features:** Ícones + texto pequeno
- **Hover:** Scale up, shadow aumentada

### **Gallery**
- **Layout:** Grid responsivo
- **Images:** Lazy loading
- **Lightbox:** Fullscreen, navegação
- **Thumbnails:** Pequenas, abaixo da imagem principal

### **Formulário**
- **Layout:** Vertical, labels acima
- **Inputs:** Full width, espaçamento adequado
- **Submit:** Botão grande, destacado
- **Validation:** Mensagens de erro visíveis
- **Success:** Mensagem de sucesso destacada

---

## 🎯 Princípios de Design

### **Simplicidade**
- Design limpo e minimalista
- Foco no conteúdo
- Sem elementos desnecessários

### **Consistência**
- Cores, tipografia e espaçamentos consistentes
- Componentes reutilizáveis
- Padrões bem definidos

### **Hierarquia Visual**
- Títulos grandes e destacados
- Textos secundários menores
- Uso de cores para destacar elementos importantes

### **Acessibilidade**
- Contrastes adequados (WCAG AA)
- Tamanhos de fonte legíveis
- Navegação por teclado
- Textos alternativos em imagens

### **Performance**
- Imagens otimizadas
- Lazy loading
- Animações leves
- Código otimizado

---

## 🖼️ Exemplos de Referência

### **Sites de Referência**
- Zillow (EUA)
- Idealista (Europa)
- Remax (Internacional)
- Century 21 (Internacional)

### **Elementos a Inspirar**
- Cards de propriedades limpos
- Galeria de imagens profissional
- Filtros intuitivos
- Formulários bem estruturados

---

## 📋 Checklist de Design

### **Cores**
- [ ] Paleta definida
- [ ] Contrastes adequados
- [ ] Cores consistentes
- [ ] Cores de estado (hover, active, disabled)

### **Tipografia**
- [ ] Fontes escolhidas
- [ ] Tamanhos definidos
- [ ] Hierarquia clara
- [ ] Line heights adequados

### **Layout**
- [ ] Grid system definido
- [ ] Breakpoints definidos
- [ ] Espaçamentos consistentes
- [ ] Container max-width definido

### **Componentes**
- [ ] Cards estilizados
- [ ] Botões estilizados
- [ ] Inputs estilizados
- [ ] Modals estilizados

### **Animações**
- [ ] Transições definidas
- [ ] Animações leves
- [ ] Performance testada
- [ ] Acessibilidade considerada

---

**Data:** 27 de Janeiro de 2025

