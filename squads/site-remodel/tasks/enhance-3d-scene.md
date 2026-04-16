---
id: enhance-3d-scene
agent: webgl-dev
phase: 3
priority: high
status: pending
depends_on: setup-project-structure
---

# Task: Aprimorar Cena 3D

## Objetivo
Evoluir a cena Three.js com modelos GLTF reais, iluminacao avancada e efeitos visuais.

## Acoes
1. **Modelo GLTF real** — Substituir astronauta geometrico por modelo .glb de alta qualidade
2. **Post-processing** — Adicionar UnrealBloomPass para glow nas particulas
3. **Iluminacao** — Setup de luzes mais cinematografico (rim light, fill light)
4. **Textura da Terra** — Adicionar textura real ao globo (se houver secao de globo)
5. **Otimizacao** — Instanced particles, frustum culling, LOD

## Recursos Necessarios
- Modelo .glb de astronauta (baixar de Sketchfab/Poly Pizza)
- Texturas Earth (opcional, three-globe CDN)

## Criterios de Aceitacao
- [ ] Modelo GLTF carregando e morphing funcionando
- [ ] Bloom pass ativo sem queda de FPS
- [ ] 60fps em desktop, 30fps+ em mobile
- [ ] Memoria GPU estavel (sem leaks)
- [ ] Fallback geometrico ainda funciona se modelo falhar
