# Belli Store - Site de Pets do Adopt Me

## Sobre o Projeto

A Belli Store é um site completo e responsivo para uma loja fictícia especializada na venda de pets e acessórios do jogo Adopt Me do Roblox. O site foi desenvolvido com foco em um design colorido, fofo e encantador, inspirado na estética do jogo.

## Características Principais

### 🎨 Design
- **Paleta de Cores**: Tons pastel (rosa, lilás, azul bebê, branco)
- **Tipografia**: Baloo 2 para títulos e Poppins para texto
- **Estilo**: Visual infantil, fofo e acolhedor
- **Animações**: Hover effects, fade-in, e micro-interações

### 📱 Responsividade
- Design mobile-first
- Menu hambúrguer em telas pequenas
- Layout adaptável para diferentes tamanhos de tela
- Otimizado para desktop, tablet e mobile

### 🏠 Páginas Incluídas

#### Página Inicial
- Banner principal com chamada atrativa
- Seção de pets em destaque
- Explicação de como funciona o processo
- Estatísticas da loja (500+ pets, 1000+ clientes, 100% seguro)

#### Página de Produtos
- Grid completo com 12 pets diferentes
- Sistema de filtros por raridade (Comum, Raro, Épico, Ultra Raro, Lendário)
- Busca por nome ou descrição
- Cards interativos com informações detalhadas

#### Página Como Comprar
- Guia passo a passo detalhado
- Seções de segurança e confiabilidade
- Depoimentos de clientes
- FAQ (Perguntas Frequentes)

#### Página de Contato
- Formulário de contato funcional
- Informações de contato direto (Discord, WhatsApp, E-mail)
- Horários de atendimento
- Seção "Belli World" com mapa fictício
- Depoimentos de clientes

### ⚡ Funcionalidades

#### Navegação
- Menu fixo no topo
- Navegação entre páginas via JavaScript
- Links funcionais no rodapé
- Scroll suave entre seções

#### Interatividade
- Filtros funcionais na página de produtos
- Busca em tempo real
- Formulário de contato com validação
- Botões "Quero esse!" em todos os pets
- Efeitos hover em cards e botões

#### Componentes
- Header com logo e navegação
- Cards de produtos com badges de raridade
- Seções informativas com ícones
- Footer completo com links úteis
- Formulários estilizados

## Tecnologias Utilizadas

- **React 18**: Framework principal
- **Tailwind CSS**: Estilização e responsividade
- **Lucide Icons**: Ícones modernos e consistentes
- **Vite**: Build tool e desenvolvimento
- **shadcn/ui**: Componentes de interface

## Estrutura do Projeto

```
belli-store/
├── src/
│   ├── components/
│   │   ├── ui/           # Componentes base (shadcn/ui)
│   │   ├── Header.jsx    # Cabeçalho e navegação
│   │   ├── Hero.jsx      # Banner principal
│   │   ├── FeaturedPets.jsx    # Pets em destaque
│   │   ├── HowItWorks.jsx      # Como funciona
│   │   ├── ProductsPage.jsx    # Página de produtos
│   │   ├── HowToBuyPage.jsx    # Página como comprar
│   │   ├── ContactPage.jsx     # Página de contato
│   │   ├── Footer.jsx          # Rodapé
│   │   └── Navigation.jsx      # Sistema de navegação
│   ├── assets/          # Imagens e recursos
│   ├── App.jsx         # Componente principal
│   ├── App.css         # Estilos customizados
│   └── main.jsx        # Ponto de entrada
├── public/             # Arquivos públicos
└── package.json        # Dependências
```

## Como Executar

1. **Instalar dependências:**
   ```bash
   cd belli-store
   pnpm install
   ```

2. **Executar em desenvolvimento:**
   ```bash
   pnpm run dev
   ```

3. **Build para produção:**
   ```bash
   pnpm run build
   ```

## Recursos Visuais

### Pets Disponíveis
O site inclui uma variedade de pets categorizados por raridade:

- **Lendário**: Unicórnio Dourado, Leão Real
- **Ultra Raro**: Dragão de Gelo, Panda Gigante, Águia Dourada
- **Épico**: Cachorrinho Dourado, Gato Ninja, Tartaruga Sábia
- **Raro**: Gatinho Arco-íris, Peixinho Dourado
- **Comum**: Coelhinho Rosa, Hamster Fofo

### Elementos de Design
- Gradientes coloridos em botões e backgrounds
- Badges de raridade com cores específicas
- Ícones temáticos (corações, estrelas, coroas)
- Animações suaves e transições
- Elementos decorativos (emojis de pets flutuantes)

## Funcionalidades Especiais

### Sistema de Filtros
- Filtro por raridade com contadores dinâmicos
- Busca em tempo real por nome e descrição
- Resultados atualizados instantaneamente

### Responsividade Avançada
- Menu hambúrguer funcional em mobile
- Layout flexível que se adapta a qualquer tela
- Imagens e textos otimizados para diferentes resoluções

### Experiência do Usuário
- Feedback visual em todas as interações
- Loading states e animações suaves
- Navegação intuitiva e acessível
- Conteúdo organizado e fácil de encontrar

## Considerações de Segurança

O site simula uma loja real mas inclui avisos apropriados:
- Disclaimer sobre não ser afiliado ao Roblox Corporation
- Ênfase em trocas seguras e moderação
- Informações sobre proteção de menores
- Transparência sobre o processo de compra

## Futuras Melhorias

- Sistema de carrinho de compras
- Área de login/registro de usuários
- Blog com dicas de Adopt Me
- Sistema de avaliações de produtos
- Chat ao vivo para suporte
- Integração com APIs de pagamento (simulada)

---

**Nota**: Este é um projeto fictício criado para fins educacionais e demonstração de habilidades de desenvolvimento web. Não representa uma loja real e não está afiliado ao Roblox Corporation ou ao jogo Adopt Me.

