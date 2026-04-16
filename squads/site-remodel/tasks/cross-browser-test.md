---
id: cross-browser-test
agent: qa
phase: 4
priority: high
status: pending
depends_on:
  - performance-audit
---

# Task: Teste Cross-Browser

## Objetivo
Validar que o site funciona corretamente em todos os browsers e dispositivos alvo.

## Matriz de Testes

### Desktop
| Browser | Versao | WebGL | Status |
|---------|--------|-------|--------|
| Chrome  | latest | 2.0   | [ ]    |
| Firefox | latest | 2.0   | [ ]    |
| Safari  | latest | 2.0   | [ ]    |
| Edge    | latest | 2.0   | [ ]    |

### Mobile
| Dispositivo    | Browser       | Status |
|----------------|---------------|--------|
| iPhone (iOS)   | Safari        | [ ]    |
| iPhone (iOS)   | Chrome        | [ ]    |
| Android        | Chrome        | [ ]    |
| Android        | Samsung Internet | [ ] |

## O que Testar
1. **Renderizacao 3D** — Particulas aparecem, morphing funciona
2. **Interacao** — Mouse parallax (desktop), touch (mobile)
3. **Layout** — Texto legivel, sem sobreposicao
4. **Navegacao** — Links, botoes, scroll
5. **Performance** — Sem travamentos ou lentidao excessiva
6. **Fallback** — Comportamento quando WebGL indisponivel

## Criterios de Aceitacao
- [ ] Funciona em 100% dos browsers desktop listados
- [ ] Funciona em pelo menos 3 dos 4 cenarios mobile
- [ ] Nenhum erro JS no console em nenhum browser
- [ ] Fallback exibe conteudo legivel sem WebGL
