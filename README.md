# 🎮 Unified Game Canvas — Interactive Pro Studio

> **Framework Visual e Interativo para Concepção, Engenharia de Jogos, Game Flow e Sustentabilidade de Negócios.**  
> Inspirado na metodologia unificada de Game Design Canvas (*Figura 11: Unified Game Canvas*).

---

## 📌 Visão Geral

O **Unified Game Canvas** é uma ferramenta de design de jogos de prancheta contínua (*Continuous Blueprint*) que integra em uma única matriz todas as etapas críticas para o desenvolvimento de um jogo: desde o propósito psicológico e emocional até a arquitetura de mecânicas, ritmo de loops e estratégia comercial.

```
┌─────────────────────────────────────────────────────────────────────────────────────────────┐
│                                    GAME IMPACT (Topo)                                       │
│          Emotion, Fun, Enjoyment, Learning, Behavioral Changes, Sociability, Metrics         │
├──────────────┬──────────────┬──────────────┬──────────────┬──────────────┬──────────────────┤
│ 01. Conceito │ 02. Jogador  │ 03. Gameplay │ 04. Fluxo    │ 05. Núcleo   │ 06. Interação    │
│ Game Concept │ Game Player  │ Game Play    │ Game Flow    │ Game Core    │ Game Interaction │
├──────────────┴──────────────┴──────────────┴──────────────┴──────────────┴──────────────────┤
│                                   GAME BUSINESS (Base)                                      │
│        Minimum Viable Prototype, Costs, Revenues, ROI, Channels, Positioning, Bonus         │
└─────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Funcionalidades da Aplicação Web (`index.html`)

- 📐 **Arquitetura em Envelope Contínuo (Blueprint Master Frame):**
  - Borda mestra compartilhada que delimita o topo (*Game Impact*), o núcleo central (*6 Colunas de Fluxo*) e a base (*Game Business*).
- 🌓 **Temas Dark & Light:**
  - Alternância instantânea com suporte a modo Blueprint Dark e Studio Light com contraste WCAG 2.1 AA.
- 🖼️ **Exportação de Alta Resolução:**
  - **PNG (Dark & Light):** Renderização nítida em Retina 2x (300 DPI) para apresentações e documentação de GDD.
  - **PDF (Dark & Light):** Geração de prancha técnica em formato paisagem (16:9 / A3) para impressão.
- 💾 **Persistência & Portabilidade:**
  - **Exportar/Importar JSON:** Salve e compartilhe arquivos `.json` com todos os 33 campos preenchidos.
  - **Autosave Local:** Salvamento contínuo em tempo real no `localStorage` do navegador.
- 🎨 **Compatibilidade com Figma:**
  - Acompanha arquivo vetorial otimizado (`unified_game_canvas.svg`) que pode ser arrastado diretamente para o Figma, convertendo-se em frames e caixas de texto 100% editáveis.

---

## 🏛️ Estrutura Metodológica dos 3 Pilares

### 1. Nível Superior — GAME IMPACT (Envelope de Propósito)
Define o impacto humano e ressonância emocional que o jogo causa:
- **Emotion & Enjoyment:** Diversão (*Fun*), tensão, alívio, alegria, empatia e humor.
- **Learning & Behavior:** Habilidades cognitivas/motoras adquiridas e mudanças de hábitos.
- **Sociability:** Dinâmicas comunitárias, co-op, rivalidades, guilds e compartilhamento social.
- **Metrics & Retention:** KPIs chave (*DAU/MAU, Retenção D1/D7/D30, CSAT, Tempo de Sessão*).

### 2. Núcleo Central — 6 Colunas de Fluxo Consecutivo
Guia o ciclo completo de game design:
1. **Game Concept:** Identidade (*Name, Title, Version*), intenção autoral (*Objective, Intention, Idea*), lore (*Theme, Story, Inspiration*) e taxonomia (*Genre, Type*).
2. **Game Player:** Demografia (*Age*), arquétipos (*Type, Segment / Bartle*), modos de jogo (*Number of Players*) e persona (*Community, Character*).
3. **Game Play (Core Loop):** Condições de partida e vitória (*Start, Flow, Win Condition*), regras e restrições (*Rules, Options, Powers*), missões e mundo (*Goals, World, Enemies, Bosses*) e penalidades (*Punishment & Reward*).
4. **Game Flow:** Cadência temporal (*Loops: Micro, Meso, Macro*), aleatoriedade (*Time, Randomness, AI*), dilemas e incerteza (*Choices & Uncertainty*) e retenção (*Challenges & Longevity*).
5. **Game Core:** Verbos fundamentais e física (*Actions & Mechanics*), sinergias e respostas emergentes (*Effects & Dynamics*) e estética audiovisual (*Elements, Aesthetics, Cutscenes*).
6. **Game Interaction:** Plataformas e A11y (*Platform & Accessibility*), esquemas de input (*Controls, I/O*), UI e câmera (*HUD, Menus & Cameras*) e sensação tátil (*Feedback & Scoring / Juice*).

### 3. Nível Inferior — GAME BUSINESS (Envelope de Viabilidade)
Garante a sustentabilidade comercial e produtiva do projeto:
- **Minimum Viable Prototype:** Escopo do Vertical Slice, teste de core loop e marcos de entrega (*Milestones*).
- **Costs & Budget:** Custos de desenvolvimento, licenças de engine/ferramentas e orçamento de marketing.
- **Revenues & ROI:** Modelo de monetização (*Premium, F2P, Subscriptions*), projeção de vendas e breakeven.
- **Channels & Positioning:** Lojas (*Steam, Epic, Consoles, Mobile*), assessoria de imprensa e influenciadores.
- **Bonus Material & Live-Ops:** Trilha sonora, Artbook, expansões, passes de temporada e suporte a Mods.

---

## 🛠️ Como Utilizar

### Execução Local
Basta abrir o arquivo `index.html` em qualquer navegador moderno:
```bash
# Clone o repositório
git clone https://github.com/Gabriel-Aragao/unified-game-canvas.git
cd unified-game-canvas

# Abra no navegador
open index.html # macOS
xdg-open index.html # Linux
start index.html # Windows
```

---

## 📄 Arquivos do Repositório

- `index.html` — Aplicação web interativa com renderizador de blueprint, suporte a temas e motores de exportação PNG/PDF/JSON.
- `unified_game_canvas.svg` — Vetor estruturado em camadas e agrupamentos limpos para uso direto no Figma.
- `FIGMA_SPEC.md` — Especificações técnicas de Auto-Layout, Tokens de Design (Light/Dark) e tipografia para Figma.

---

## 👩‍💻 Autoria & Créditos

- **Design de Interface & Sistema de Tokens:** @Maya (UI/UX Designer)
- **Metodologia Original:** Baseado no framework *Unified Game Canvas*
- **Projeto:** @domaragao / Gabriel Aragão
