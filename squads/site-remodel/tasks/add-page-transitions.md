---
id: add-page-transitions
agent: webgl-dev
phase: 3
priority: medium
status: pending
depends_on:
  - enhance-3d-scene
  - create-page-sections
---

# Task: Transicoes 3D entre Secoes

## Objetivo
Criar transicoes visuais 3D quando o usuario navega entre secoes do site.

## Ideias de Transicao
- **Hero -> About:** Particulas se dispersam e reagrupam em nova forma
- **About -> Portfolio:** Camera faz dolly/zoom pela cena 3D
- **Portfolio -> Contact:** Particulas formam um envelope/icone de contato
- **Scroll-driven:** Animacoes vinculadas ao scroll (ScrollTrigger do GSAP)

## Implementacao
1. Detectar secao visivel via Intersection Observer
2. Trigger morph para forma correspondente a secao
3. Mover camera com GSAP ScrollTrigger
4. Transicao de cores das particulas por secao

## Criterios de Aceitacao
- [ ] Transicao suave entre pelo menos 3 secoes
- [ ] Scroll-driven animation funciona em mobile
- [ ] Nenhum jank/stutter durante transicoes
- [ ] Fallback gracioso se ScrollTrigger nao carregar
