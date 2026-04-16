---
id: implement-responsive
agent: fullstack-dev
phase: 2
priority: high
status: pending
depends_on: setup-project-structure
---

# Task: Implementar Responsividade

## Objetivo
Garantir que o site funcione perfeitamente em todos os tamanhos de tela.

## Breakpoints
- **Mobile:** 375px (base)
- **Tablet:** 768px
- **Desktop:** 1024px
- **Wide:** 1440px

## Acoes
1. Reduzir font-size do H1 em mobile (6rem -> 2.5rem)
2. Ajustar particle count em mobile (10000 -> 3000)
3. Menu de navegacao adaptativo
4. Touch events para interacao 3D em mobile
5. Reduzir pixel ratio em mobile para performance

## Criterios de Aceitacao
- [ ] Site usavel em 375px sem scroll horizontal
- [ ] Texto legivel em todas as telas
- [ ] Three.js roda a 30fps+ em mobile medio
- [ ] Touch funciona para parallax/interacao
- [ ] Nenhum elemento cortado ou sobreposto
