# Design Tokens

## Cores
```css
:root {
    /* Base */
    --color-bg: #050505;
    --color-text: #ffffff;
    --color-text-muted: rgba(255, 255, 255, 0.7);

    /* Primarias */
    --color-gold: #f3a02a;
    --color-blue: #3498db;

    /* Gradiente da marca */
    --gradient-brand: linear-gradient(135deg, var(--color-gold) 0%, var(--color-blue) 100%);

    /* UI */
    --color-border: rgba(255, 255, 255, 0.25);
    --color-surface: rgba(255, 255, 255, 0.05);
    --color-glow-blue: rgba(52, 152, 219, 0.3);
    --color-glow-gold: rgba(243, 160, 42, 0.15);
}
```

## Tipografia
```css
:root {
    --font-primary: 'Montserrat', sans-serif;
    --font-weight-regular: 400;
    --font-weight-bold: 700;
    --font-weight-black: 900;

    /* Escala */
    --text-xs: 0.7rem;
    --text-sm: 0.85rem;
    --text-base: 1rem;
    --text-lg: 1.2rem;
    --text-xl: 2rem;
    --text-hero: 6rem;        /* Desktop */
    --text-hero-mobile: 2.5rem; /* Mobile */
}
```

## Espacamento
```css
:root {
    --space-xs: 5px;
    --space-sm: 10px;
    --space-md: 20px;
    --space-lg: 40px;
    --space-xl: 80px;
    --space-section: 100vh;
}
```

## Efeitos
```css
:root {
    --blur-surface: blur(10px);
    --shadow-glow-blue: 0 0 60px var(--color-glow-blue);
    --shadow-glow-gold: 0 0 25px var(--color-glow-gold);
    --transition-default: all 0.3s ease;
    --border-radius-full: 30px;
}
```
