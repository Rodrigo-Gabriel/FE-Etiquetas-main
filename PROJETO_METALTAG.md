# MetalTag - Site de Etiquetas Metálicas

## Visão Geral
Site profissional para empresa especializada em etiquetas metálicas para roupas, desenvolvido com React, TypeScript e Tailwind CSS.

## Estrutura do Site

### 1. Página Inicial (/)
**Componentes principais:**
- Hero Section com imagem de etiquetas metálicas premium
- Estatísticas da empresa (15+ anos, 500+ marcas, 1M+ etiquetas)
- Seção de características principais
- Preview dos produtos (Gold, Silver, Black Edition)
- Depoimentos de clientes
- Call-to-action para orçamento

### 2. Produtos (/produtos)
**Catálogo completo:**
- **Etiqueta Premium Gold**: R$ 2,50+ (Mais Popular)
- **Etiqueta Classic Silver**: R$ 1,80+ (Econômica)  
- **Etiqueta Black Edition**: R$ 3,20+ (Exclusiva)

**Recursos destacados:**
- Cards com badges de categoria
- Lista de características por produto
- Seção de diferenciais (Resistência, Produção Rápida, Personalização, Qualidade)

### 3. Sobre (/sobre)
**Conteúdo institucional:**
- História da empresa (fundada em 2008)
- Números de impacto em grid visual
- 4 valores principais (Precisão, Inovação, Parceria, Qualidade)
- Missão corporativa

### 4. Serviços (/servicos)
**6 serviços principais:**
- Design Personalizado (Grátis)
- Gravação a Laser (Premium)
- Acabamentos Especiais (Exclusivo)
- Produção em Lote (Industrial)
- Produção Express (Urgente)
- Logística Integrada (Nacional)

**Processo de trabalho:**
5 etapas claras (Briefing → Orçamento → Aprovação → Produção → Entrega)

### 5. Contato (/contato)
**Formulário de orçamento:**
- Campos: Nome, Empresa, Email, Telefone, Tipo de Produto, Mensagem
- Validação de campos obrigatórios

**Informações de contato:**
- Endereço: Rua da Indústria, 1234 - São Paulo
- Telefone: (11) 3456-7890
- WhatsApp: (11) 98765-4321
- Email: contato@metaltag.com.br
- Horário: Seg-Sex 8h-18h, Sáb 8h-12h

## Design System

### Cores da Marca
```css
/* Cores Principais */
--primary: Preto profundo (hsl(0 0% 8%))
--accent: Amarelo vibrante (hsl(51 100% 50%))

/* Cores Complementares */
--yellow-bright: hsl(51 100% 50%)
--yellow-light: hsl(51 100% 95%)
--black-deep: hsl(0 0% 8%)
--black-light: hsl(0 0% 15%)
```

### Gradientes Personalizados
- **gradient-primary**: Degradê preto elegante
- **gradient-accent**: Degradê amarelo dinâmico  
- **gradient-hero**: Combinação preto-amarelo para hero sections

### Sombras Especiais
- **shadow-elegant**: Sombra sutil para cards
- **shadow-yellow**: Sombra amarela para destaque
- **shadow-card**: Sombra padrão para elementos

### Componentes Customizados

#### Botões Especiais
```tsx
// Botão Hero - Amarelo com hover animado
<Button variant="hero" size="xl">Solicitar Orçamento</Button>

// Botão Premium - Degradê preto elegante
<Button variant="premium" size="lg">Ver Produtos</Button>
```

#### Navegação
- Header fixo com backdrop blur
- Logo personalizado "MT" com fundo degradê
- Menu responsivo para mobile
- Estados ativos nos links

## Estrutura de Arquivos

```
src/
├── components/
│   ├── Navigation.tsx         # Navegação principal
│   └── ui/                   # Componentes shadcn/ui customizados
├── pages/
│   ├── Index.tsx             # Página inicial
│   ├── Produtos.tsx          # Catálogo de produtos
│   ├── Sobre.tsx             # Página institucional
│   ├── Servicos.tsx          # Serviços oferecidos
│   └── Contato.tsx           # Formulário e contatos
├── assets/
│   └── hero-metal-labels.jpg # Imagem hero gerada
└── lib/
    └── utils.ts              # Utilitários
```

## Recursos Técnicos

### SEO Otimizado
- Title tags descritivos
- Meta descriptions
- Open Graph tags
- Estrutura semântica HTML5

### Performance
- Lazy loading de imagens
- Transições suaves (transition-smooth)
- Componentes otimizados
- Bundle size reduzido

### Responsividade
- Design mobile-first
- Breakpoints: sm, md, lg, xl
- Menu hambúrguer para mobile
- Grid adaptativo

### Acessibilidade
- Contraste adequado (preto/amarelo)
- Navegação por teclado
- Labels semânticos
- Estados de foco visíveis

## Tecnologias Utilizadas

- **React 18** - Framework principal
- **TypeScript** - Tipagem estática
- **Tailwind CSS** - Framework CSS
- **Shadcn/ui** - Componentes base
- **Lucide React** - Ícones
- **React Router** - Roteamento
- **Vite** - Build tool

## Próximos Passos Sugeridos

1. **Integração com Backend:**
   - API para formulário de contato
   - Sistema de orçamentos
   - Dashboard administrativo

2. **Funcionalidades Avançadas:**
   - Galeria de produtos com zoom
   - Calculadora de preços online
   - Chat ao vivo

3. **Marketing Digital:**
   - Blog de conteúdo
   - Cases de sucesso
   - Certificações e prêmios

4. **E-commerce:**
   - Carrinho de compras
   - Pagamento online
   - Área do cliente

## Contato para Desenvolvimento
Site desenvolvido com foco em conversão, experiência do usuário e representação premium da marca MetalTag no mercado de etiquetas metálicas.