---
id: setup-project-structure
agent: fullstack-dev
phase: 2
priority: high
status: pending
depends_on: create-page-sections
---

# Task: Estruturar o Projeto

## Objetivo
Organizar o projeto de single-file HTML para uma estrutura modular e escalavel.

## Estrutura Alvo
```
index.html              # HTML semantico com secoes
css/
  variables.css         # Design tokens (Custom Properties)
  base.css              # Reset, tipografia, global
  sections.css          # Estilos por secao
  responsive.css        # Media queries
js/
  main.js               # Entry point (ES module)
  scene.js              # Setup Three.js (scene, camera, renderer)
  particles.js          # Sistema de particulas + morphing
  shapes.js             # Definicoes de formas (esfera, astronauta)
  loader.js             # GLTF/OBJ loader
  interaction.js        # Mouse, scroll, resize
assets/
  models/               # .glb, .gltf
  textures/             # Imagens, texturas
  fonts/                # Fontes locais (se necessario)
```

## Entregaveis
1. index.html refatorado com HTML semantico
2. CSS extraido e modularizado
3. JS extraido em ES modules separados
4. Meta tags completas (SEO, OG, Twitter Card)
5. Preconnect para CDNs

## Criterios de Aceitacao
- [ ] Zero CSS/JS inline no HTML (tudo em arquivos externos)
- [ ] ES modules funcionando via importmap
- [ ] Site funciona identico ao original apos refatoracao
- [ ] Meta tags OG e Twitter Card presentes
- [ ] Lighthouse SEO > 90
