---
id: performance-audit
agent: qa
phase: 4
priority: high
status: pending
depends_on:
  - enhance-3d-scene
  - implement-responsive
---

# Task: Auditoria de Performance

## Objetivo
Garantir que o site atinge metricas de performance aceitaveis em todos os dispositivos.

## Checklist

### Lighthouse
- [ ] Performance score > 80
- [ ] Accessibility score > 90
- [ ] Best Practices score > 90
- [ ] SEO score > 90

### Core Web Vitals
- [ ] LCP (Largest Contentful Paint) < 2.5s
- [ ] FID (First Input Delay) < 100ms
- [ ] CLS (Cumulative Layout Shift) < 0.1

### Three.js Specifico
- [ ] FPS desktop: 60fps estavel
- [ ] FPS mobile: 30fps+ estavel
- [ ] Memoria GPU: sem crescimento continuo (leak)
- [ ] Draw calls: < 50 por frame
- [ ] Geometrias/materiais dispostos no cleanup

### Network
- [ ] Total page weight < 1MB (sem modelos 3D)
- [ ] Modelo .glb < 2MB
- [ ] TTFB < 600ms
- [ ] Todas as CDNs com preconnect

## Ferramentas
- Chrome DevTools (Performance tab, Memory tab)
- Lighthouse (Chrome ou CLI)
- WebGL Inspector
- stats.js (FPS monitor em dev)
