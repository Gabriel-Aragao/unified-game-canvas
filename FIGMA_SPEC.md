# Unified Game Canvas — Especificação de Arquitetura no Figma
**Autor:** @Maya (UI/UX Designer)  
**Projeto:** Game Design Canvas Template  
**Solicitante:** @domaragao  

---

## 1. Estrutura de Frames & Auto-Layout

```
[Frame: Unified Game Canvas] (Width: 1920px, Height: Hug / 1080px, Direction: Vertical, Padding: 32px, Gap: 16px)
 ├── [Frame: Header Bar] (Width: Fill, Height: Hug, Direction: Horizontal, Justify: Space Between)
 │    ├── [Frame: Brand/Title] (Title: 28px Bold, Subtitle: 14px Regular)
 │    └── [Frame: Meta Badges] (Version, Author, Date)
 │
 ├── [Frame: Section - Game Impact] (Width: Fill, Direction: Vertical, Padding: 20px, Gap: 12px, Stroke: Primary)
 │    ├── [Frame: Section Header] (Badge: "PROPÓSITO", Title: "1. GAME IMPACT")
 │    └── [Frame: Impact Grid] (Direction: Horizontal, Gap: 12px)
 │         ├── [Component: Pillar Card - Emotion & Enjoyment] (Width: Fill)
 │         ├── [Component: Pillar Card - Learning & Behavior] (Width: Fill)
 │         ├── [Component: Pillar Card - Sociability] (Width: Fill)
 │         └── [Component: Pillar Card - Metrics & Retention] (Width: Fill)
 │
 ├── [Frame: Section - 6 Columns Flow] (Width: Fill, Direction: Horizontal, Gap: 14px)
 │    ├── [Component: Canvas Column - 01. Game Concept] (Width: Fill, Height: Fill)
 │    ├── [Component: Flow Chevron Indicator]
 │    ├── [Component: Canvas Column - 02. Game Player] (Width: Fill, Height: Fill)
 │    ├── [Component: Flow Chevron Indicator]
 │    ├── [Component: Canvas Column - 03. Game Play (Core Focus)] (Width: Fill, Height: Fill)
 │    ├── [Component: Flow Chevron Indicator]
 │    ├── [Component: Canvas Column - 04. Game Flow] (Width: Fill, Height: Fill)
 │    ├── [Component: Flow Chevron Indicator]
 │    ├── [Component: Canvas Column - 05. Game Core] (Width: Fill, Height: Fill)
 │    ├── [Component: Flow Chevron Indicator]
 │    └── [Component: Canvas Column - 06. Game Interaction] (Width: Fill, Height: Fill)
 │
 └── [Frame: Section - Game Business] (Width: Fill, Direction: Vertical, Padding: 20px, Gap: 12px, Stroke: Emerald)
      ├── [Frame: Section Header] (Badge: "VIABILIDADE", Title: "7. GAME BUSINESS")
      └── [Frame: Business Grid] (Direction: Horizontal, Gap: 12px)
           ├── [Component: Pillar Card - Minimum Viable Prototype] (Width: Fill)
           ├── [Component: Pillar Card - Costs & Budget] (Width: Fill)
           ├── [Component: Pillar Card - Revenues & ROI] (Width: Fill)
           ├── [Component: Pillar Card - Channels & Positioning] (Width: Fill)
           └── [Component: Pillar Card - Bonus Material & Live-Ops] (Width: Fill)
```

---

## 2. Coleção de Variáveis (Figma Design Tokens)

### Paleta Semântica (Cores)
| Token | Modo Dark (Padrão) | Modo Light | Descrição |
| :--- | :--- | :--- | :--- |
| `surface/base` | `#0B0D13` | `#F8FAFC` | Fundo geral do canvas |
| `surface/card` | `#161922` | `#FFFFFF` | Fundo dos cards e colunas |
| `surface/card-inner`| `#1D2230` | `#F1F5F9` | Fundo dos blocos de campos |
| `border/subtle` | `#262B38` | `#E2E8F0` | Linhas delimitadoras |
| `border/focus` | `#6366F1` | `#4F46E5` | Borda em destaque / seleção |
| `text/primary` | `#F8FAFC` | `#0F172A` | Títulos e rótulos principais |
| `text/secondary` | `#94A3B8` | `#475569` | Descrições e placeholders |
| `accent/primary` | `#6366F1` | `#4F46E5` | Acentos e marcadores de fluxo |
| `accent/success` | `#10B981` | `#059669` | Borda da seção Game Business |

### Tipografia
| Estilo | Fonte | Tamanho | Peso | Line Height |
| :--- | :--- | :--- | :--- | :--- |
| `Heading / Canvas Title` | Inter / Plus Jakarta Sans | 28px | 800 (Bold) | 36px |
| `Heading / Section Title`| Inter / Plus Jakarta Sans | 20px | 700 (Bold) | 28px |
| `Heading / Column Title` | Inter / Plus Jakarta Sans | 16px | 700 (Bold) | 22px |
| `Body / Pillar Title`    | Inter / Plus Jakarta Sans | 12px | 700 (SemiBold)| 16px |
| `Body / Prompt Text`     | Inter / Plus Jakarta Sans | 11px | 500 (Regular)| 15px |
| `Badge / Tag Mono`       | JetBrains Mono / Inter    | 10px | 700 (Bold) | 12px |

---

## 3. Guia de Importação Rápida no Figma
1. Baixe o arquivo vetorial otimizado: `unified_game_canvas.svg`.
2. Arraste o arquivo `.svg` diretamente para a tela do seu projeto no Figma.
3. O Figma converterá automaticamente todos os nós em **Layers vetoriais e Textos editáveis**, preservando a hierarquia de agrupamento (`Header`, `Columns`, `Cards`, `Footer`).
4. Para ativar o Auto-Layout nos frames importados: selecione qualquer coluna/card e pressione `Shift + A`.
