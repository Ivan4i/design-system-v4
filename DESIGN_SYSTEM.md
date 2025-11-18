# Design System Documentation

## 📋 Содержание
- [Основы](#основы)
- [Цветовая палитра](#цветовая-палитра)
- [Типографика](#типографика)
- [Spacing & Layout](#spacing--layout)
- [Компоненты](#компоненты)
- [Паттерны](#паттерны)
- [Состояния](#состояния)
- [Иконки](#иконки)

---

## Основы

### Принципы дизайна

**Консистентность:**
Единообразие визуальных элементов и взаимодействий во всех продуктах

**Читаемость:**
Ясная иерархия и легкость восприятия информации

**Эффективность:**
Оптимизация пользовательского опыта для быстрого достижения целей

**Адаптивность:**
Гибкость системы для работы на всех устройствах и платформах

### Философия

Наша дизайн-система создана для обеспечения согласованности, масштабируемости и эффективности в разработке продуктов. Она объединяет дизайн и разработку, предоставляя единый источник истины для всех команд.

---

## Цветовая палитра

### Primary Colors

```css
/* Основной цвет бренда */
--color-primary: #3B82F6;
--color-primary-hover: #2563EB;
--color-primary-active: #1D4ED8;
--color-primary-light: #DBEAFE;
--color-primary-dark: #1E40AF;

/* Вторичный цвет */
--color-secondary: #8B5CF6;
--color-secondary-hover: #7C3AED;
--color-secondary-active: #6D28D9;
```

### Semantic Colors

```css
/* Success / Trend Up */
--color-success: #10B981;
--color-success-bg: #D1FAE5;
--color-success-border: #6EE7B7;

/* Error / Trend Down */
--color-error: #EF4444;
--color-error-bg: #FEE2E2;
--color-error-border: #FCA5A5;
--Colors-Red: #EF4444;

/* Warning / Hot */
--color-warning: #F59E0B;
--color-warning-bg: #FEF3C7;
--color-warning-border: #FCD34D;
--Colors-Orange: #EA580C;

/* Info */
--color-info: #3B82F6;
--color-info-bg: #DBEAFE;
--color-info-border: #93C5FD;
--Colors-Blue-Blue-100: #3582FF;
--Colors-Blue-2: rgba(53, 130, 255, 0.8);
```

### Neutral Colors

```css
/* Text */
--color-text-primary: #111827;
--color-text-secondary: #6B7280;
--color-text-tertiary: #9CA3AF;
--color-text-disabled: #D1D5DB;
--color-text-inverse: #FFFFFF;

/* Backgrounds */
--color-bg-primary: #FFFFFF;
--color-bg-secondary: #F9FAFB;
--color-bg-tertiary: #F3F4F6;
--color-bg-elevated: #FFFFFF;
--color-bg-overlay: rgba(0, 0, 0, 0.5);

/* Surface Colors (Interactive Elements) */
--Surface-01: #FEFEFE;
--Surface-02: #F5F5F5;
--Surface-03: #E5E5E5;

/* Stroke / Borders */
--color-border-primary: #E5E7EB;
--color-border-secondary: #D1D5DB;
--color-border-focus: #3B82F6;
--color-border-disabled: #F3F4F6;
--Stroke-01: #E0E0E0;
--Stroke-02: #D4D4D4;

/* Shades (Light) */
--Shade1-100: #FEFEFE;
--Shade-5-100: #F5F5F5;
--Shade-7-100: #3F3F3F;
--Shade-8-100: #262626;
--Shade-9-5: rgba(0, 0, 0, 0.05);

/* Shades (Tailwind-compatible) */
--color-gray-50: #F9FAFB;
--color-gray-100: #F3F4F6;
--color-gray-200: #E5E7EB;
--color-gray-300: #D1D5DB;
--color-gray-400: #9CA3AF;
--color-gray-500: #6B7280;
--color-gray-600: #4B5563;
--color-gray-700: #374151;
--color-gray-800: #1F2937;
--color-gray-900: #111827;
--color-zinc-100: #F4F4F5;
--color-zinc-800: #27272A;
--color-neutral-50: #FAFAFA;
--color-neutral-200: #E5E5E5;
--color-neutral-700: #404040;
--color-neutral-900: #171717;
```

### Chart Colors

```css
/* Для графиков и визуализации данных */
--color-chart-1: #3B82F6;
--color-chart-2: #10B981;
--color-chart-3: #F59E0B;
--color-chart-4: #EF4444;
--color-chart-5: #8B5CF6;
--color-chart-6: #EC4899;
--color-chart-7: #14B8A6;
--color-chart-8: #F97316;
```

### Gradients

```css
/* Градиенты для специальных элементов */
--gradient-primary: linear-gradient(135deg, #667EEA 0%, #764BA2 100%);
--gradient-secondary: linear-gradient(135deg, #F093FB 0%, #F5576C 100%);
--gradient-accent: linear-gradient(135deg, #4FACFE 0%, #00F2FE 100%);
```

### Brand Icon Colors

```css
/* Цвета для иконок брендов и социальных сетей */
--color-brand-facebook: #1877F2;
--color-brand-twitter: #1DA1F2;
--color-brand-instagram: #E4405F;
--color-brand-linkedin: #0A66C2;
--color-brand-youtube: #FF0000;
--color-brand-github: #181717;
```

---

## Типографика

### Font Family

```css
--font-primary: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
--font-secondary: 'Roboto', sans-serif;
--font-mono: 'JetBrains Mono', 'Fira Code', 'Courier New', monospace;
```

### Font Sizes

```css
--font-size-xs: 0.75rem;    /* 12px */
--font-size-sm: 0.875rem;   /* 14px */
--font-size-base: 1rem;     /* 16px */
--font-size-md: 1.125rem;   /* 18px */
--font-size-lg: 1.25rem;    /* 20px */
--font-size-xl: 1.5rem;     /* 24px */
--font-size-2xl: 1.875rem;  /* 30px */
--font-size-3xl: 2.25rem;   /* 36px */
--font-size-4xl: 3rem;      /* 48px */
--font-size-5xl: 3.75rem;   /* 60px */
```

### Font Weights

```css
--font-weight-thin: 100;
--font-weight-light: 300;
--font-weight-normal: 400;
--font-weight-medium: 500;
--font-weight-semibold: 600;
--font-weight-bold: 700;
--font-weight-extrabold: 800;
--font-weight-black: 900;
```

### Line Heights

```css
--line-height-tight: 1.25;
--line-height-snug: 1.375;
--line-height-normal: 1.5;
--line-height-relaxed: 1.625;
--line-height-loose: 2;
```

### Text Styles

#### Headings

| Элемент | Font Size | Font Weight | Line Height | Letter Spacing |
|---------|-----------|-------------|-------------|----------------|
| **H1** | 3rem (48px) | 700 | 1.2 | -0.02em |
| **H2** | 2.25rem (36px) | 700 | 1.3 | -0.01em |
| **H3** | 1.875rem (30px) | 600 | 1.3 | -0.01em |
| **H4** | 1.5rem (24px) | 600 | 1.4 | 0 |
| **H5** | 1.25rem (20px) | 600 | 1.5 | 0 |
| **H6** | 1.125rem (18px) | 600 | 1.5 | 0 |

#### Body Text

| Элемент | Font Size | Font Weight | Line Height |
|---------|-----------|-------------|-------------|
| **Body Large** | 1.125rem (18px) | 400 | 1.625 |
| **Body** | 1rem (16px) | 400 | 1.5 |
| **Body Small** | 0.875rem (14px) | 400 | 1.5 |
| **Caption** | 0.75rem (12px) | 400 | 1.375 |

### Tracking (Letter Spacing)

```css
--letter-spacing-tight: -0.02em;
--letter-spacing-normal: 0;
--letter-spacing-wide: 0.025em;
--letter-spacing-wider: 0.05em;
```

---

## Spacing & Layout

### Spacing Scale

```css
--space-0: 0;
--space-1: 0.25rem;   /* 4px */
--space-2: 0.5rem;    /* 8px */
--space-3: 0.75rem;   /* 12px */
--space-4: 1rem;      /* 16px */
--space-5: 1.25rem;   /* 20px */
--space-6: 1.5rem;    /* 24px */
--space-8: 2rem;      /* 32px */
--space-10: 2.5rem;   /* 40px */
--space-12: 3rem;     /* 48px */
--space-16: 4rem;     /* 64px */
--space-20: 5rem;     /* 80px */
--space-24: 6rem;     /* 96px */
```

### Border Radius

```css
--radius-none: 0;
--radius-sm: 0.125rem;    /* 2px */
--radius-base: 0.25rem;   /* 4px */
--radius-md: 0.375rem;    /* 6px */
--radius-lg: 0.5rem;      /* 8px */
--radius-xl: 0.75rem;     /* 12px */
--radius-2xl: 1rem;       /* 16px */
--radius-full: 9999px;
```

### Shadows

#### Card Shadows

```css
--shadow-xs: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
--shadow-sm: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.06);
--shadow-base: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
--shadow-md: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
--shadow-lg: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
--shadow-xl: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
```

#### Button Shadows

```css
--shadow-button: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
--shadow-button-hover: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
--shadow-button-active: inset 0 2px 4px 0 rgba(0, 0, 0, 0.06);
```

#### Hover Shadows

```css
--shadow-hover-sm: 0 2px 4px 0 rgba(0, 0, 0, 0.1);
--shadow-hover-md: 0 8px 12px -2px rgba(0, 0, 0, 0.15);
--shadow-hover-lg: 0 20px 30px -10px rgba(0, 0, 0, 0.2);
```

### Borders

#### Border Width

```css
--border-width-0: 0;
--border-width-1: 1px;
--border-width-2: 2px;
--border-width-4: 4px;
```

#### Border Offset

```css
--border-offset-0: 0;
--border-offset-1: 1px;
--border-offset-2: 2px;
```

### Opacity Scale

```css
--opacity-0: 0;
--opacity-10: 0.1;
--opacity-20: 0.2;
--opacity-30: 0.3;
--opacity-40: 0.4;
--opacity-50: 0.5;
--opacity-60: 0.6;
--opacity-70: 0.7;
--opacity-80: 0.8;
--opacity-90: 0.9;
--opacity-100: 1;
```

---

## Компоненты

### 1. Cards

#### Basic Card

- **Padding:** `var(--space-6)` (24px)
- **Border Radius:** `var(--radius-lg)` (8px)
- **Background:** `var(--color-bg-primary)`
- **Shadow:** `var(--shadow-sm)`
- **Border:** `1px solid var(--color-border-primary)`

**Варианты:**
- Elevated: `shadow: var(--shadow-md)`
- Outlined: `border: 2px solid var(--color-border-primary)`
- Flat: `shadow: none; border: none`

#### Пример использования

```css
.card {
  padding: var(--space-6);
  border-radius: var(--radius-lg);
  background: var(--color-bg-primary);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--color-border-primary);
}
```

---

### 2. Buttons

#### 2.1 Standard Buttons (Light Theme)

##### Default Button

**Sizes:**
- **Large (XL):** `padding: 10px 24px` (py-2.5 px-6), `border-radius: 12px`, `font-size: 14px`, `font-weight: 600`
- **Medium (LG):** `padding: 8px 20px` (py-2 px-5), `border-radius: 10px`, `font-size: 14px`, `font-weight: 600`
- **Small (MD):** `padding: 8px 16px` (py-2 px-4), `border-radius: 10px`, `font-size: 14px`, `font-weight: 600`

**Visual Style:**
```css
/* Default State */
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5);
box-shadow:
  0px 0px 0px 1px rgba(212, 212, 212, 1.00),
  0px 3px 4px -1px rgba(0, 0, 0, 0.15),
  inset 0px 1px 0px 0px rgba(255, 255, 255, 0.33);
color: var(--color-text-primary);
```

**States:**

1. **Default (Rest)**
   - Background: `linear-gradient(to bottom, #E5E5E5, #E5E5E5)`
   - Shadow: Border `1px rgba(212, 212, 212, 1)`, Drop `0px 3px 4px -1px rgba(0,0,0,0.15)`, Inset highlight `0px 1px 0px rgba(255,255,255,0.33)`

2. **Hover**
   - Background: `linear-gradient(to bottom, rgba(255,255,255,0.4), rgba(255,255,255,0.4))`
   - Shadow: Border `1px rgba(230, 230, 230, 1)`, Drop `0px 3px 8px -2px rgba(0,0,0,0.30)`, Inset `0px 1px 0px rgba(255,255,255,0.70)`

3. **Pressed/Active**
   - Background: `linear-gradient(to bottom, #E5E5E5, rgba(229,229,229,0.8))`
   - Shadow: Border `1px rgba(230, 230, 230, 1)`, Drop `0px 3px 4px -2px rgba(0,0,0,0.30)`, Inset `0px 1px 0px rgba(255,255,255,0.70)`

4. **Focus**
   - All default styles +
   - Additional shadow: `inset 0px 0px 0px 1.5px rgba(53, 130, 255, 1)` (blue focus ring inside)

5. **Disabled**
   - Opacity: `0.3`
   - Cursor: `not-allowed`
   - All other styles remain

##### Button with Icon

**Layout:**
- Icon + Text: `gap: 8px`, Icon size: `20px × 20px` (w-5 h-5)
- Icon-only: `padding: 8px` (square), Icon size: `20px × 20px`

**Example:**
```html
<!-- Medium with icon -->
<button class="px-4 py-2">
  <icon class="w-5 h-5" />
  <span>Button</span>
</button>
```

---

#### 2.2 Destructive Buttons (Delete/Remove)

**Color Scheme:** Orange/Red

##### States:

1. **Default**
   ```css
   background: linear-gradient(to bottom, #EA580C, #EA580C);
   box-shadow:
     0px 3px 4px -1px rgba(252, 96, 16, 0.95),
     0px 0px 0px 1px rgba(191, 74, 15, 1.00),
     inset 0px 1px 0px 0px rgba(255, 255, 255, 0.33);
   color: #FEFEFE;
   ```

2. **Hover**
   ```css
   background: linear-gradient(to bottom, #F97316, #EA580C);
   box-shadow:
     0px 3px 4px -1px rgba(226, 79, 5, 0.95),
     0px 0px 0px 1px rgba(191, 74, 15, 1.00),
     inset 0px 1px 0px 0px rgba(255, 255, 255, 0.33);
   ```

3. **Pressed/Active**
   ```css
   background: linear-gradient(to bottom, #EA580C, #F97316);
   /* Same shadows as hover */
   ```

4. **Focus**
   ```css
   /* All default styles + */
   outline: 1px solid #FC6010;
   box-shadow:
     0px 3px 4px -1px rgba(252, 96, 16, 0.95),
     0px 0px 0px 0px rgba(191, 74, 15, 1.00),
     inset 0px 1px 0px 0px rgba(255, 255, 255, 0.33),
     inset 0px 0px 0px 2.5px rgba(252, 252, 252, 1.00);
   ```

5. **Disabled**
   - Opacity: `0.4`
   - Same visual style as default

---

#### 2.3 Dark Theme Buttons

**Color Scheme:** Charcoal/Black

##### States:

1. **Default**
   ```css
   background: linear-gradient(to bottom, #3F3F3F, #262626);
   box-shadow:
     0px 0px 0px 1px rgba(51, 51, 51, 1.00),
     0px 2px 4px -1px rgba(13, 13, 13, 0.50),
     inset 0px -1px 1.2px 0.35px rgba(18, 18, 18, 1.00),
     inset 0px 0.5px 1px 0px rgba(255, 255, 255, 0.15);
   color: #FAFAFA;
   border-radius: 10px;
   ```

2. **Hover**
   ```css
   background: linear-gradient(to bottom, #3F3F3F, #262626);
   /* Same shadows */
   ```

3. **Pressed/Active**
   ```css
   background: linear-gradient(to bottom, #262626, #3F3F3F);
   /* Reversed gradient */
   ```

4. **Focus**
   ```css
   /* All default styles + */
   box-shadow:
     /* all default shadows +*/
     inset 0px 0px 0px 1px rgba(252, 252, 252, 1.00);
   ```

5. **Disabled**
   - Opacity: `0.3`

**Border Radius:**
- Large buttons (xl): `12px`
- Medium/Small buttons: `10px`

---

#### 2.4 Icon-Only Buttons

**Sizes:**

| Size | Button Size | Icon Size | Padding | Border Radius |
|------|-------------|-----------|---------|---------------|
| **XS** | 24px × 24px | 16px | 4px | 8px |
| **SM** | 32px × 32px | 20px | 6px | 10px |
| **MD** | 36px × 36px | 20px | 8px | 10px |
| **LG** | 40px × 40px | 20px | 10px | 12px |

##### Small Icon Button (16px)

```css
/* Default */
padding: 4px;
border-radius: 6px;
background: transparent;

/* Hover */
background: var(--Surface-03);

/* Focus/Selected */
background: var(--Surface-01);
outline: 1px solid var(--Colors-Blue-100);

/* Active/Pressed */
background: var(--Surface-03);
box-shadow: inset 0px 0px 2.1px 0px rgba(0, 0, 0, 0.15);

/* Disabled */
opacity: 0.3;
```

##### Medium Icon Button (20px)

```css
/* Default */
padding: 8px;
border-radius: 10px;
background: transparent;

/* Hover */
background: var(--Surface-03);

/* Focus/Selected */
outline: 1px solid var(--Colors-Blue-100);

/* Active/Pressed */
background: var(--Surface-03);
box-shadow: inset 0px 0px 2.1px 0px rgba(0, 0, 0, 0.15);

/* Disabled */
opacity: 0.3;
```

##### Large Icon Button (with border)

```css
/* Default */
padding: 12px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);

/* Hover */
outline: 1px solid var(--Stroke-02);
/* No background change */

/* Focus/Selected */
outline: 1px solid var(--Colors-Blue-100);

/* Active/Pressed */
background: var(--Surface-03);
outline: 1px solid var(--Stroke-02);
box-shadow: inset 0px 0px 4px 0px rgba(0, 0, 0, 0.10);

/* Disabled */
opacity: 0.5;
outline: 1px solid var(--Stroke-01);
```

---

#### 2.5 Toggle/Radio Button Groups

**Visual Style:** Horizontal or vertical group of icon buttons

##### States:

1. **Default (Unselected)**
   ```css
   padding: 4px; /* XS: p-1 */
   padding: 8px; /* MD: p-2 */
   border-radius: 8px;
   background: transparent;
   ```

2. **Hover**
   ```css
   background: var(--Surface-03);
   border-radius: 8px;
   ```

3. **Selected/Active**
   ```css
   background: var(--Surface-01);
   outline: 1px solid var(--Colors-Blue-100);
   border-radius: 8px;
   ```

4. **Pressed (when selected)**
   ```css
   background: var(--Surface-03);
   box-shadow: inset 0px 0px 2.1px 0px rgba(0, 0, 0, 0.15);
   outline: 1px solid var(--Stroke-02);
   ```

5. **Disabled**
   - Opacity: `0.3`

**Spacing:** Gap between buttons: `0` (touching) or `4px`

---

#### 2.6 Social Login Buttons

**Example:** "Sign in with Google"

##### States:

1. **Default**
   ```css
   width: 320px;
   height: 44px;
   padding: 8px 20px;
   border-radius: 10px;
   background: linear-gradient(to bottom, #E5E5E5, #E5E5E5);
   box-shadow:
     0px 0px 0px 1px rgba(212, 212, 212, 1.00),
     0px 3px 4px -1px rgba(0, 0, 0, 0.15),
     inset 0px 1px 0px 0px rgba(255, 255, 255, 0.33);
   display: flex;
   align-items: center;
   gap: 8px;
   ```

2. **Hover**
   ```css
   background: linear-gradient(to bottom, rgba(244,244,245,0.5), rgba(244,244,245,0.5));
   box-shadow:
     0px 0px 0px 1px rgba(212, 212, 212, 1.00),
     0px 3px 4px -1px rgba(0, 0, 0, 0.15),
     0px 1px 4px 0px rgba(0, 0, 0, 0.25),
     inset 0px 1px 0px 0px rgba(255, 255, 255, 0.33);
   ```

3. **Focus**
   ```css
   background: #FEFEFE;
   outline: 1.5px solid rgba(53, 130, 255, 0.8);
   box-shadow:
     0px 0px 0px 1px rgba(212, 212, 212, 1.00),
     0px 3px 4px -1px rgba(0, 0, 0, 0.15),
     0px 1px 4px 0px rgba(0, 0, 0, 0.25),
     inset 0px 1px 0px 0px rgba(255, 255, 255, 0.33);
   ```

4. **Active/Pressed**
   ```css
   background: linear-gradient(to bottom, #E5E5E5, #E4E4E7);
   /* Same shadows as default */
   ```

5. **Disabled**
   - Opacity: `0.3`

**Icon:** Brand icon (24px × 24px) positioned left

---

#### 2.7 Checkbox/Radio Styled Buttons

**Small Checkboxes (12px)**

```css
/* Default */
width: 12px;
height: 12px;
/* Icon stroke color: var(--Text-Secondary) */

/* Checked */
/* Icon stroke color: var(--Text-Primary) */
background: fill or checkmark visible
```

**Medium Checkboxes (16px)**

```css
/* Default */
width: 16px;
height: 16px;
padding: 2px;
border-radius: 4px;

/* Hover */
background: transparent;

/* Checked */
background: var(--Surface-01);
/* or rounded background */
```

---

#### 2.8 Segmented Controls / Button Groups

**Visual:** Group of related buttons

##### Elevated Style

```css
/* Container */
padding: 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow:
  0px 1px 3.2px -2px rgba(0, 0, 0, 0.99),
  inset 0px 2px 0px 0px rgba(255, 255, 255, 0.80);
outline: 1px solid var(--Stroke-02);
```

**Selected Item:**
```css
background: var(--Surface-01);
border-radius: 12px;
box-shadow:
  0px 1px 3.2px -1px rgba(0, 0, 0, 0.39),
  inset 0px 2px 0px 0px rgba(255, 255, 255, 0.80);
outline: 1px solid var(--Stroke-02);
```

**Pressed Selected Item:**
```css
background: var(--Surface-01);
box-shadow:
  0px 1px 3.2px -2px rgba(0, 0, 0, 0.99),
  inset 0px 2px 0px 0px rgba(255, 255, 255, 0.80),
  inset 0px 0px 3.3px 0px rgba(0, 0, 0, 0.25);
outline: 1px solid var(--Stroke-02);
```

**Focus State:**
```css
/* Elevated + Focus Ring */
outline: 1px solid var(--Colors-Blue-100);
box-shadow:
  0px 1px 3.2px -2px rgba(0, 0, 0, 0.99),
  inset 0px 0px 0px 3px rgba(225, 225, 225, 1.00),
  inset 0px 0px 0px 2px rgba(243, 243, 243, 1.00);
border-radius: 10px;
```

**Disabled:**
- Opacity: `0.5`

---

#### 2.9 Tab-Style Buttons

**Flat Tabs:**

```css
/* Default */
padding: 10px 20px;
border-radius: 12px;
background: transparent;

/* Hover */
background: var(--Surface-03);

/* Selected */
background: var(--Surface-01);
box-shadow: 0px 2px 8px -4px rgba(0, 0, 0, 0.25);
outline: 1px solid var(--Stroke-02);

/* Disabled */
opacity: 0.5;
```

**Dark Theme Tabs:**

```css
/* Selected */
background: linear-gradient(to bottom, #27272A, #18181B);
box-shadow: 0px 2px 8px -4px rgba(0, 0, 0, 0.25);
color: #FEFEFE;
```

---

#### 2.10 Specialized Buttons

##### Keyboard Shortcut Button

```css
/* Container for shortcut display (e.g., ⌘K) */
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0, 0, 0, 0.25),
  0px 0px 0px 1px rgba(0, 0, 0, 0.11),
  inset 0px -1px 0.6px 0px rgba(0, 0, 0, 0.20),
  inset 0px 2px 0.8px 0px rgba(255, 255, 255, 0.27);
font-size: 12px;
font-weight: 500;
color: var(--Text-Secondary);
```

**Nested Shortcut (darker):**
```css
min-width: 20px;
padding: 2px 4px;
background: #27272A;
border-radius: 4px;
box-shadow:
  0px 2px 2px 0px rgba(0, 0, 0, 0.74);
outline: 1px solid rgba(250, 250, 250, 0.05);
color: #FAFAFA;
```

##### Command Palette Button

```css
/* "Copy prompt" or "Undo" style */
padding-left: 4px;
padding-right: 2px;
padding-top: 2px;
padding-bottom: 2px;
background: var(--Text-Primary);
border-radius: 6px;
box-shadow: 0px 4px 4px -2px rgba(0, 0, 0, 0.40);
color: var(--Shade-5-100);
font-size: 12px;
font-weight: 500;
```

##### Badge/Counter Button

```css
/* Small button with icon + number */
padding: 14px 8px;
background: var(--Surface-01);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
gap: 8px;

/* Icon: 16px, Text: 12px semibold */
```

**States:**
- **Hover:** `background: var(--Surface-02)`
- **Focus:** `outline: 1px solid var(--Colors-Orange)`
- **Active:** `box-shadow: inset 0px 0px 4px 0px rgba(0,0,0,0.15)`

##### Reaction Button (Emoji)

```css
/* Default: emoji + count */
padding: 6px 8px;
border-radius: 8px;
outline: 1px solid var(--Stroke-02);
gap: 8px;
font-size: 12px;

/* Hover */
background: var(--Surface-03);

/* Selected/Active */
background: var(--Surface-02);

/* Focus */
outline: 1px solid var(--Colors-Blue-100);
```

##### Floating Action Button (FAB)

```css
/* Small floating icon button */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18, 18, 18, 0.10);
```

**Size variants:**
- **Small:** 32px × 32px (icon 16px)
- **Medium:** 40px × 40px (icon 20px)
- **Large:** 56px × 56px (icon 24px)

---

#### 2.11 Toggle Switch Buttons

##### Icon Toggle (Single)

```css
/* Default */
height: 40px;
padding: 4px 10px;
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
background: transparent;

/* Hover */
box-shadow: 0px 2px 8px -4px rgba(0, 0, 0, 0.25);
outline: 1px solid rgba(0,0,0,0.05);

/* Active/Pressed */
background: var(--Surface-01);
box-shadow:
  0px 1px 8px -4px rgba(0, 0, 0, 0.15),
  inset 0px 0.5px 2px 0px rgba(0, 0, 0, 0.25);
outline: 1px solid rgba(0,0,0,0.05);

/* Focus */
outline: 1.5px solid var(--Colors-Blue-100);

/* Disabled */
opacity: 0.5;
```

##### Multi-Icon Toggle Group

```css
/* Container - no background */
display: flex;
gap: 0;

/* Item - default */
height: 40px;
padding: 4px 10px;
border-radius: 12px;
background: transparent;

/* Item - hover */
background: var(--Surface-03);

/* Item - selected */
background: var(--Surface-03);
box-shadow: inset 0px 0px 6px -1px rgba(0, 0, 0, 0.25);

/* Item - focus */
outline: 1.5px solid var(--Colors-Blue-100);
```

---

#### 2.12 Link-Style Buttons

**Text-only, no background:**

```css
/* Default */
background: transparent;
color: var(--color-primary);
text-decoration: underline;
text-decoration-style: dotted;

/* Hover */
color: var(--color-primary-hover);
text-decoration-style: solid;

/* Active */
color: var(--color-primary-active);

/* Disabled */
opacity: 0.4;
cursor: not-allowed;
```

---

### 3. Inputs

#### Text Input

**Height:**
- **Small:** 32px
- **Medium:** 40px
- **Large:** 48px

**Padding:** `8px 12px`
**Radius:** `var(--radius-md)` (6px)
**Border:** `1px solid var(--color-border-primary)`

**States:**
- **Focus:** `border-color: var(--color-border-focus); box-shadow: 0 0 0 3px var(--color-primary-light)`
- **Error:** `border-color: var(--color-error); box-shadow: 0 0 0 3px var(--color-error-bg)`
- **Disabled:** `background: var(--color-bg-secondary); cursor: not-allowed; opacity: 0.6`

#### Textarea

- **Min Height:** 80px
- **Padding:** `8px 12px`
- **Radius:** `var(--radius-md)` (6px)
- **Resize:** `vertical`

#### Select

- **Height:** 40px
- **Padding:** `8px 12px`
- **Icon:** Chevron Down (right aligned)

---

### 4. Badges & Tags

#### Badge

- **Padding:** `4px 8px`
- **Radius:** `var(--radius-full)` (pill shape)
- **Font Size:** `var(--font-size-xs)` (12px)

**Variants:**
- **Success:** `background: var(--color-success-bg); color: var(--color-success); border: 1px solid var(--color-success-border)`
- **Error:** `background: var(--color-error-bg); color: var(--color-error); border: 1px solid var(--color-error-border)`
- **Warning:** `background: var(--color-warning-bg); color: var(--color-warning); border: 1px solid var(--color-warning-border)`
- **Info:** `background: var(--color-info-bg); color: var(--color-info); border: 1px solid var(--color-info-border)`
- **Neutral:** `background: var(--color-gray-100); color: var(--color-gray-700); border: 1px solid var(--color-gray-300)`

#### Tag

- **Padding:** `6px 12px`
- **Radius:** `var(--radius-md)` (6px)
- **Font Size:** `var(--font-size-sm)` (14px)
- **Close Button:** X icon with hover state

---

### 5. Forms

#### Form Layout

**Label:**
- **Margin Bottom:** `var(--space-2)` (8px)
- **Font Weight:** `var(--font-weight-medium)` (500)
- **Font Size:** `var(--font-size-sm)` (14px)

**Field Group:**
- **Margin Bottom:** `var(--space-4)` (16px)

**Helper Text:**
- **Margin Top:** `var(--space-1)` (4px)
- **Font Size:** `var(--font-size-xs)` (12px)
- **Color:** `var(--color-text-secondary)`

**Error Message:**
- **Color:** `var(--color-error)`
- **Font Size:** `var(--font-size-xs)` (12px)

---

### 6. Tables

#### Table Structure

**Row Height:**
- **Compact:** 32px
- **Default:** 48px
- **Comfortable:** 64px

**Cell Padding:** `12px 16px`

**Header:**
- **Background:** `var(--color-bg-secondary)`
- **Font Weight:** `var(--font-weight-semibold)` (600)
- **Border Bottom:** `2px solid var(--color-border-primary)`

**Row Borders:** `1px solid var(--color-border-primary)`

**Hover State:** `background: var(--color-bg-secondary)`

**Striped Rows:** Alternate rows with `background: var(--color-bg-secondary)`

---

### 7. Navigation

#### Main Navigation

- **Height:** 64px
- **Background:** `var(--color-bg-primary)`
- **Shadow:** `var(--shadow-sm)`
- **Item Padding:** `12px 16px`

**States:**
- **Default:** `color: var(--color-text-secondary)`
- **Hover:** `color: var(--color-text-primary); background: var(--color-bg-secondary)`
- **Active:** `color: var(--color-primary); border-bottom: 2px solid var(--color-primary)`

#### Sidebar Navigation

- **Width:** 240px
- **Item Height:** 40px
- **Item Padding:** `8px 16px`

**States:**
- Same as Main Navigation

---

### 8. Charts

#### Line Chart

- **Line Width:** 2px
- **Point Radius:** 4px
- **Grid Lines:** `color: var(--color-border-primary); opacity: 0.5`
- **Colors:** Use `--color-chart-*` variables

#### Bar Chart

- **Bar Spacing:** 8px
- **Border Radius:** `var(--radius-sm)` (2px top corners)
- **Colors:** Use `--color-chart-*` variables

#### Pie/Donut Chart

- **Border Width:** 2px white
- **Spacing:** 2px between segments
- **Colors:** Use `--color-chart-*` variables

---

### 9. Avatars

#### Sizes

| Size | Dimensions |
|------|------------|
| **XS** | 24px × 24px |
| **Small** | 32px × 32px |
| **Medium** | 40px × 40px |
| **Large** | 48px × 48px |
| **XL** | 64px × 64px |
| **2XL** | 96px × 96px |

#### Styles

- **Border Radius:** `var(--radius-full)` (circle)
- **Border:** `2px solid var(--color-bg-primary)` (for overlap)
- **Placeholder:** Icon or initials with `background: var(--color-gray-300)`
- **Status Indicator:** 8px dot, positioned bottom-right

---

### 10. List Items

#### List Item

- **Height:** 56px (default)
- **Padding:** `12px 16px`
- **Border Bottom:** `1px solid var(--color-border-primary)`

**States:**
- **Hover:** `background: var(--color-bg-secondary)`
- **Active:** `background: var(--color-primary-light)`
- **Selected:** `background: var(--color-primary-light); border-left: 4px solid var(--color-primary)`

---

### 11. Messages / Notifications

#### Toast Notification

- **Width:** 320px
- **Padding:** `16px`
- **Radius:** `var(--radius-lg)` (8px)
- **Shadow:** `var(--shadow-lg)`
- **Position:** Top-right, 16px from edges

**Variants:**
- Success, Error, Warning, Info (use semantic colors)

**Auto-dismiss:** 3-5 seconds

#### Alert Banner

- **Padding:** `12px 16px`
- **Border Left:** `4px solid` (variant color)
- **Background:** Semantic background color
- **Close Button:** X icon, top-right

---

### 12. Panels & Cards

#### Side Panel

- **Width:** 400px
- **Background:** `var(--color-bg-primary)`
- **Shadow:** `var(--shadow-xl)`
- **Padding:** `var(--space-6)` (24px)

**Header:**
- **Padding Bottom:** `var(--space-4)` (16px)
- **Border Bottom:** `1px solid var(--color-border-primary)`

#### Modal

- **Max Width:** 600px
- **Background:** `var(--color-bg-primary)`
- **Border Radius:** `var(--radius-xl)` (12px)
- **Shadow:** `var(--shadow-xl)`
- **Overlay:** `background: var(--color-bg-overlay)`
- **Padding:** `var(--space-8)` (32px)

---

### 13. Accordion / FAQ

#### Accordion Item

- **Padding:** `16px 20px`
- **Border:** `1px solid var(--color-border-primary)`
- **Border Radius:** `var(--radius-md)` (6px)
- **Margin Bottom:** `var(--space-2)` (8px)

**States:**
- **Collapsed:** Icon chevron-right
- **Expanded:** Icon chevron-down, content revealed with animation
- **Hover:** `background: var(--color-bg-secondary)`

---

### 14. Loading States

#### Skeleton Loader

- **Background:** `var(--color-gray-200)`
- **Animation:** Shimmer effect (gradient moving left to right)
- **Border Radius:** Match element being loaded
- **Sizes:** Match content dimensions

#### Spinner

- **Size:** 24px (small), 40px (medium), 64px (large)
- **Color:** `var(--color-primary)`
- **Animation:** Rotate 360deg, 1s linear infinite

---

### 15. Empty States

#### Empty State Layout

**Icon:**
- Size: 64px × 64px
- Color: `var(--color-gray-400)`

**Heading:**
- Font Size: `var(--font-size-xl)` (24px)
- Font Weight: `var(--font-weight-semibold)` (600)
- Color: `var(--color-text-primary)`

**Description:**
- Font Size: `var(--font-size-base)` (16px)
- Color: `var(--color-text-secondary)`

**Action Button:**
- Primary button variant

**Spacing:**
- **Icon → Heading:** `var(--space-4)` (16px)
- **Heading → Description:** `var(--space-2)` (8px)
- **Description → Button:** `var(--space-6)` (24px)

---

### 16. Special Effects

#### Focus Ring

```css
--focus-ring: 0 0 0 3px var(--color-primary-light);
```

#### Backdrop Blur

```css
--backdrop-blur-sm: blur(4px);
--backdrop-blur-base: blur(8px);
--backdrop-blur-md: blur(12px);
--backdrop-blur-lg: blur(16px);
```

---

### 17. Indicator Badges

#### Notification Count Badge

**Small Badge (with number):**

```css
/* Container */
padding: 14px 8px;
background: var(--Surface-01);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
display: flex;
align-items: center;
gap: 8px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;

/* Text */
font-size: 12px;
font-weight: 600;
color: var(--Text-Primary);
```

**States:**
- **Default:** Outlined with stroke-02
- **Hover:** `background: var(--Surface-02)`
- **Focus:** `outline: 1px solid var(--Colors-Orange)`
- **Active/Pressed:** `box-shadow: inset 0px 0px 4px 0px rgba(0,0,0,0.15)`
- **Disabled:** `opacity: 0.3`

#### Status Indicator Badge

**Color-coded status:**

```css
/* Container */
padding: 12px 12px;
background: var(--Surface-01);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
display: flex;
align-items: center;
gap: 8px;

/* Icon (colored) */
width: 16px;
height: 16px;
fill: var(--Colors-Red); /* or stroke */

/* Text */
font-size: 12px;
font-weight: 600;
```

**Icon Colors by State:**
- Error/Alert: `var(--Colors-Red)` (#EF4444)
- Warning: `var(--Colors-Orange)` (#EA580C)
- Success: `var(--color-success)` (#10B981)
- Info: `var(--Colors-Blue-Blue-100)` (#3582FF)

---

### 18. Notification Dot

**Small circular indicator:**

```css
/* Red notification dot */
width: 48px;
height: 48px;
background: var(--Colors-Red);
border-radius: 8px 0 0 8px; /* Left rounded */
display: flex;
align-items: center;
justify-content: center;

/* Icon inside */
width: 12px;
height: 12px;
fill: var(--Shade1-100); /* White */
```

**Usage:** Positioned on tabs, sidebar items, or buttons to indicate new notifications

---

### 19. Keyboard Shortcuts

#### Shortcut Display Badge

**Light background style:**

```css
/* Container */
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0, 0, 0, 0.25),
  0px 0px 0px 1px rgba(0, 0, 0, 0.11),
  inset 0px -1px 0.6px 0px rgba(0, 0, 0, 0.20),
  inset 0px 2px 0.8px 0px rgba(255, 255, 255, 0.27);
font-size: 12px;
font-weight: 500;
color: var(--Text-Secondary);
```

**Example:** `⌘K`, `⌘Z`, `Esc`

#### Nested Shortcut (Dark)

```css
/* Dark nested shortcut */
min-width: 20px;
padding: 2px 4px;
background: #27272A;
border-radius: 4px;
box-shadow: 0px 2px 2px 0px rgba(0, 0, 0, 0.74);
outline: 1px solid rgba(250, 250, 250, 0.05);
font-size: 12px;
font-weight: 500;
color: #FAFAFA;
```

**Usage in Command Palette:**

```html
<div class="command-item">
  <span>Copy prompt</span>
</div>

<div class="command-item">
  <span>Undo</span>
  <kbd class="shortcut-dark">⌘Z</kbd>
</div>
```

---

### 20. Reaction Components

#### Emoji Reaction Button

**Visual Style:**

```css
/* Container */
padding: 6px 8px;
border-radius: 8px;
outline: 1px solid var(--Stroke-02);
display: inline-flex;
align-items: center;
gap: 8px;

/* Emoji */
font-size: 12px;
font-weight: 600;

/* Count */
font-size: 12px;
font-weight: 600;
color: var(--Text-Primary);
```

**States:**
- **Default:** `outline: 1px solid var(--Stroke-02)`
- **Hover:** `background: var(--Surface-03)`
- **Active/Selected:** `background: var(--Surface-02)`
- **Focus:** `outline: 1px solid var(--Colors-Blue-100)`
- **Disabled:** `opacity: 0.3`

**Example:** 👍 2, ❤️ 5, 🎉 1

---

### 21. Command Palette / Quick Action Buttons

#### Dark Command Button

```css
/* Container */
padding: 2px 4px 2px 4px;
background: var(--Text-Primary);
border-radius: 6px;
box-shadow: 0px 4px 4px -2px rgba(0, 0, 0, 0.40);
display: inline-flex;
align-items: center;
gap: 4px;

/* Text */
font-size: 12px;
font-weight: 500;
color: var(--Shade-5-100);
padding: 2px 4px;
```

**Nested Shortcut Inside:**
```css
/* Shortcut badge */
min-width: 20px;
padding: 2px 4px;
background: #27272A;
border-radius: 4px;
box-shadow: 0px 2px 2px 0px rgba(0, 0, 0, 0.74);
outline: 1px solid rgba(250, 250, 250, 0.05);
```

**Example:**
```html
<button class="command-button">
  <span>Copy prompt</span>
</button>

<button class="command-button">
  <span>Undo</span>
  <kbd>⌘Z</kbd>
</button>
```

---

### 22. Checkbox & Radio Controls

#### Standard Checkbox

**Sizes:**

| Size | Dimensions | Icon Size | Border Radius |
|------|------------|-----------|---------------|
| **XS** | 12px × 12px | 8px | 2px |
| **SM** | 16px × 16px | 12px | 3px |
| **MD** | 20px × 20px | 14px | 4px |

**Visual States:**

```css
/* Unchecked */
width: 20px;
height: 20px;
border: 1.5px solid var(--Stroke-02);
border-radius: 4px;
background: transparent;

/* Unchecked Hover */
background: var(--Surface-03);

/* Checked */
background: var(--Colors-Blue-Blue-100);
border: none;
/* Checkmark icon visible */

/* Checked Hover */
background: var(--Colors-Blue-2);

/* Focus */
outline: 2px solid var(--Colors-Blue-2);
outline-offset: 2px;

/* Disabled */
opacity: 0.3;
cursor: not-allowed;
```

#### Radio Button

**Visual States:**

```css
/* Unchecked */
width: 20px;
height: 20px;
border: 1.5px solid var(--Stroke-02);
border-radius: 50%; /* Full circle */
background: transparent;

/* Checked */
background: var(--Surface-01);
border: 1.5px solid var(--Colors-Blue-Blue-100);
/* Inner dot */
position: relative;
&::after {
  content: '';
  width: 10px;
  height: 10px;
  background: var(--Colors-Blue-Blue-100);
  border-radius: 50%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

---

### 23. Loading Spinners & Overlays

#### Button Loading State

**Small Spinner (inside button):**

```css
/* Spinner container */
width: 40px;
height: 40px;
padding: 8px;
border-radius: 10px;
background: var(--Surface-03);
display: flex;
align-items: center;
justify-content: center;

/* Animated spinner icon */
width: 20px;
height: 20px;
animation: spin 1s linear infinite;

@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
```

**With Text:**
```css
/* Button in loading state */
opacity: 0.6;
cursor: wait;
pointer-events: none;

/* Replace icon with spinner */
```

---

### 24. Glass/Frosted UI Elements

#### Glass Button

```css
/* Semi-transparent with blur */
background: rgba(255, 255, 255, 0.4);
backdrop-filter: blur(8px);
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(230, 230, 230, 1.00),
  0px 3px 8px -2px rgba(0, 0, 0, 0.30),
  inset 0px 1px 0px 0px rgba(255, 255, 255, 0.70);

/* Hover */
background: rgba(255, 255, 255, 0.5);
backdrop-filter: blur(12px);
```

**Usage:** Overlays, floating panels, modals

---

### 25. Icon Sizes Reference

| Context | Icon Size | Stroke Width |
|---------|-----------|--------------|
| Small checkbox/radio | 12px | 1.5px |
| Medium checkbox/radio | 16px | 1.5px |
| Small button icon | 16px | 1.5px |
| Standard button icon | 20px | 1.5px |
| Large button icon | 24px | 1.5px |
| Social login icon | 24px | N/A (filled) |
| Badge/chip icon | 16px | 1.5px |
| Empty state icon | 64px | 2px |

---

### 26. Pricing / Plan Cards

#### Card Structure

**Container:**
```css
width: 320px;
background: var(--Surface-03);
border-radius: 20px;
display: flex;
flex-direction: column;
overflow: hidden;
```

**Header:**
```css
padding: 12px 24px;
border-radius: 20px;

/* Title */
font-size: 20px;
font-weight: 500;
line-height: 28px;
color: var(--Text-Primary);
```

**Content Container:**
```css
padding: 12px;
background: var(--Surface-01);
border-radius: 20px;
outline: 1px solid var(--Stroke-02);
display: flex;
flex-direction: column;
gap: 12px;
```

**Description:**
```css
padding: 12px;
font-size: 16px;
line-height: 24px;
color: var(--Text-Primary);
```

**Pricing Section:**
```css
padding: 12px;
background: var(--Surface-02);
border-radius: 20px;
box-shadow:
  0px 1px 1px 0px rgba(0,0,0,0.02),
  0px 3px 3px 0px rgba(0,0,0,0.02),
  0px 6px 3px 0px rgba(0,0,0,0.01),
  0px 10px 4px 0px rgba(0,0,0,0.00),
  0px 16px 4px 0px rgba(0,0,0,0.00),
  inset 0px 2px 2px 0px rgba(255,255,255,0.80);
outline: 1px solid var(--Stroke-02);
gap: 8px;
```

**Price Display:**
```css
/* Dollar sign */
font-size: 24px;
font-weight: 500;
line-height: 32px;
color: var(--Text-Secondary);

/* Amount */
font-size: 36px;
font-weight: 400;
line-height: 48px;
color: var(--Text-Primary);

/* Period */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
```

**CTA Button:**
- Standard button (default state or disabled)
- Dark theme button for premium plans

**Feature List:**
```css
padding: 8px 12px 12px;
display: flex;
flex-direction: column;
gap: 8px;

/* Feature Item */
display: flex;
align-items: center;
gap: 8px;

/* Checkmark Icon */
width: 16px;
height: 16px;
padding: 2px;
stroke-width: 1.5px;
color: var(--Text-Primary);

/* Feature Text */
font-size: 12px;
line-height: 20px;
color: var(--Text-Primary);
```

#### Premium Plan Variant (with gradient)

```css
background: linear-gradient(to left, rgba(2, 6, 23, 0.2), rgba(0, 0, 0, 0));
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
backdrop-filter: blur(6px);

/* Header Text Color */
color: var(--Shade1-100); /* White */
```

#### Shortened Plan Variant (Compact)

```css
/* Same structure but reduced height */
padding: 12px; /* header reduced */
/* No description section */
height: 478px; /* instead of full height */
```

---

### 27. Image Thumbnail Grid

#### Horizontal Scrollable Thumbnails

**Container:**
```css
display: inline-flex;
gap: 10px;
overflow-x: auto;

/* Gradient Fade Edges */
position: relative;

/* Left fade */
&::before {
  width: 56px;
  height: 48px;
  position: absolute;
  left: 52px;
  transform: rotate(90deg);
  background: linear-gradient(to bottom, rgba(250,250,250,0), rgba(250,250,250,1));
  backdrop-filter: blur(6px);
  pointer-events: none;
}

/* Right fade */
&::after {
  width: 56px;
  height: 48px;
  position: absolute;
  right: 0;
  transform: rotate(90deg);
  background: linear-gradient(to bottom, rgba(250,250,250,0), rgba(250,250,250,1));
  backdrop-filter: blur(6px);
  pointer-events: none;
}
```

**Thumbnail Item:**
```css
/* Default */
width: 52px;
height: 52px;
background: var(--Surface-01);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
overflow: hidden;

/* Hover */
outline: 1px solid var(--Stroke-02);

/* Active/Selected */
padding: 4px;
box-shadow:
  0px 1px 1px 0px rgba(0,0,0,0.02),
  0px 3px 3px 0px rgba(0,0,0,0.02),
  0px 6px 3px 0px rgba(0,0,0,0.01),
  0px 10px 4px 0px rgba(0,0,0,0.00),
  0px 16px 4px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
```

#### Vertical Scrollable Thumbnails

```css
display: inline-flex;
flex-direction: column;
gap: 10px;
overflow-y: auto;

/* Top fade */
&::before {
  width: 48px;
  height: 48px;
  position: absolute;
  top: 0;
  background: linear-gradient(to bottom, rgba(250,250,250,0), rgba(250,250,250,1));
  backdrop-filter: blur(6px);
}

/* Bottom fade */
&::after {
  width: 48px;
  height: 48px;
  position: absolute;
  bottom: 0;
  background: linear-gradient(to bottom, rgba(250,250,250,0), rgba(250,250,250,1));
  backdrop-filter: blur(6px);
}
```

---

### 28. Product / Asset Cards

#### Compact Product Card

**Structure:**
```css
min-width: 256px;
width: 288px;
padding: 8px;
background: var(--Surface-01);
border-radius: 24px;
outline: 1px solid var(--Stroke-01);
display: flex;
flex-direction: column;
gap: 8px;
```

**Image:**
```css
height: 210px;
border-radius: 16px;
object-fit: cover;
```

**Content:**
```css
padding: 12px;
display: flex;
flex-direction: column;
gap: 4px;

/* Title */
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Subtitle */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
opacity: 0.8;
```

**States:**

1. **Default**
   - Outline: `1px solid var(--Stroke-01)`

2. **Hover**
   - Shadow: Multi-layer elevation
   - Outline: `1px solid var(--color-gray-200)`
   - Backdrop-filter: `blur(6px)`

3. **Loading (Skeleton)**
   - Image: `background: var(--Surface-02); border-radius: 16px`
   - Title: `width: 128px; height: 8px; background: var(--Surface-03); border-radius: 2px`
   - Subtitle: `width: 64px; height: 8px; background: var(--Surface-03); border-radius: 2px`

---

### 29. Media Preview Cards

#### Large Image Card (256px)

**Container:**
```css
min-width: 256px;
width: 256px;
height: 256px;
padding: 24px;
background: var(--Surface-03);
border-radius: 20px;
position: relative;
overflow: hidden;
```

**Image:**
```css
width: 208px;
height: 208px;
object-fit: cover;
```

**Bookmark Icon (Top-Right):**
```css
position: absolute;
top: 8px;
right: 8px;
padding: 12px;
background: var(--Surface-01);
border-radius: 12px;
box-shadow:
  0px 1px 1px 0px rgba(0,0,0,0.02),
  0px 3px 3px 0px rgba(0,0,0,0.02),
  0px 6px 3px 0px rgba(0,0,0,0.01),
  0px 10px 4px 0px rgba(0,0,0,0.00),
  0px 16px 4px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--color-zinc-300);

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Primary);
```

**Bottom Gradient Overlay:**
```css
position: absolute;
bottom: 0;
left: 0;
width: 256px;
padding: 48px 8px 8px;
background: linear-gradient(to bottom, rgba(23,23,23,0), rgba(23,23,23,0), rgba(23,23,23,0.3));
display: flex;
justify-content: space-between;
align-items: flex-start;
```

**Action Buttons (in overlay):**
```css
/* Download Button */
padding: 12px;
border-radius: 12px;

/* Icon */
width: 16px;
height: 16px;
color: var(--Shade1-100); /* White */

/* Share Button */
padding: 12px;
border-radius: 12px;
display: flex;
align-items: center;
gap: 6px;

/* Icon + Text */
width: 16px;
height: 16px;
color: var(--Shade1-100);

/* Text */
font-size: 14px;
font-weight: 600;
color: var(--Shade1-100);
```

**Hover State:**
```css
/* Add checkmark icon overlay */
position: absolute;
top: 8px;
right: 8px;
background: var(--Shade1-15/20); /* Semi-transparent white */
border-radius: 10px;
outline: 1px solid rgba(250, 250, 250, 0.25);
```

#### Default State (No Overlay)

```css
background: var(--Surface-02);
outline: 1px solid var(--Stroke-01);
/* No gradient overlay */
/* No action buttons visible */
```

---

### 30. Category / Tag Cards

#### Horizontal Card with Icon

**Structure:**
```css
padding: 4px 12px 4px 4px;
background: var(--Surface-02);
border-radius: 20px;
outline: 1px solid var(--Stroke-01);
display: inline-flex;
align-items: center;
gap: 12px;
```

**Icon Container:**
```css
width: 64px;
height: 64px;
padding: 8px;
border-radius: 12px;
box-shadow:
  0px 12px 12px -5px rgba(0,0,0,0.25),
  0px 0px 2px 0px rgba(0,0,0,0.08),
  0px 0px 0px 1px rgba(236,236,236,1.00),
  inset 0px 0px 1px 1px rgba(255,255,255,0.35);
overflow: hidden;
```

**Text Content:**
```css
width: 128px;
display: flex;
flex-direction: column;
gap: 4px;

/* Title */
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);

/* Subtitle */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
opacity: 0.8;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

**Hover State:**
```css
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-02);
backdrop-filter: blur(6px);

/* Checkmark icon appears */
position: absolute;
top: 17px;
right: 0;
width: 32px;
height: 32px;
```

---

### 31. Aspect Ratio Selector

#### Ratio Buttons

**Default Ratio (Text Label):**
```css
min-width: 56px;
width: 56px;
height: 56px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: center;
align-items: center;
gap: 5px;

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
```

**Image Preview:**
```css
min-width: 56px;
width: 56px;
height: 56px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
display: flex;
justify-content: center;
align-items: center;
flex-wrap: wrap;

/* Image inside */
width: 44px;
height: 44px;
object-fit: cover;
```

**Just Image (No Border):**
```css
width: 60px;
height: 60px;
border-radius: 10px;
object-fit: cover;
/* No outline */
```

**Selected State:**
```css
background: var(--Surface-01);
box-shadow: inset 0px 0px 0px 2px rgba(252, 252, 252, 1.00);
outline: 1px solid rgba(39, 39, 42, 0.5); /* zinc-800/50 */

/* Dark theme badge */
position: absolute;
top: 1px;
right: 1px;
width: 20px;
height: 20px;
background: linear-gradient(to bottom, #27272A, #18181B);
border-radius: 50%;
```

---

### 32. Media Overlay Controls

#### Bottom Overlay Bar

**Container:**
```css
position: absolute;
bottom: 0;
left: 0;
width: 100%;
padding: 12px;
background: linear-gradient(to bottom,
  rgba(23,23,23,0),
  rgba(23,23,23,0),
  rgba(23,23,23,0.25));
backdrop-filter: blur(6.65px);
display: flex;
justify-content: space-between;
align-items: center;
```

**Author Info:**
```css
padding: 10px;
border-radius: 10px;
display: flex;
align-items: center;
gap: 8px;

/* Text */
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Shade1-100); /* White */
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

**Action Icons:**
```css
display: flex;
gap: 4px;

/* Icon Button */
padding: 10px;
border-radius: 10px;

/* Hover/Active */
background: rgba(254, 254, 254, 0.2); /* Shade1-15/20 */
outline: 1px solid rgba(250, 250, 250, 0.25);

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Shade1-100);
```

---

### 33. Asset Library Panel

#### Panel Container

**Structure:**
```css
width: 240px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;
overflow: hidden;
```

#### Tab Switcher (Segmented Control)

**Container:**
```css
padding: 16px;
border-top: 1px solid var(--Stroke-01);

/* Inner Container */
padding: 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 1px 1.9px 0px rgba(50,50,50,0.10);
outline: 1px solid var(--Stroke-02);
display: flex;
```

**Tab Item (Inactive):**
```css
flex: 1;
padding: 8px 12px;
border-radius: 8px;

/* Text */
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Secondary);
```

**Tab Item (Active):**
```css
flex: 1;
padding: 8px 12px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow:
  0px 1.25px 3px 0px rgba(50,50,50,0.10),
  inset 0px 1.25px 1px 0px rgba(255,255,255,1.00);

/* Text */
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
```

#### Section Header (Collapsible)

**Container:**
```css
width: 240px;
height: 48px;
padding: 12px 16px;
border-top: 1px solid var(--Stroke-01);
display: flex;
justify-content: space-between;
align-items: center;

/* Title */
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron Icon */
padding: 4px;
border-radius: 6px;
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

#### Asset Grid

**Container:**
```css
width: 240px;
padding: 0 16px 16px;
display: inline-flex;
flex-wrap: wrap;
gap: 8px;
```

**Asset Item (3D Object):**
```css
flex: 1;
height: 96px;
min-width: 96px;
background: var(--Surface-03);
border-radius: 16px;
position: relative;
overflow: hidden;

/* Image */
width: 88px;
height: 88px;
position: absolute;
top: 6px;
left: 6px;
```

**Asset Item (Material):**
```css
flex: 1;
height: 96px;
min-width: 96px;
padding: 4px;
background: var(--Surface-03);
border-radius: 16px;
position: relative;

/* Image */
width: 64px;
height: 64px;
position: absolute;
top: 18px;
left: 18px;
```

**Blur Effect (for collapsed sections):**
```css
filter: blur(8px);
height: 320px;
overflow: hidden;
```

#### Search Bar (Bottom)

**Container:**
```css
padding: 12px;
background: var(--Surface-01);
border-top: 1px solid var(--Stroke-01);
display: flex;
flex-direction: column;
gap: 4px;
```

**Search Input:**
```css
width: 208px;
height: 40px;
padding: 4px 10px 4px 4px;
background: var(--Surface-01);
border-radius: 12px;
display: flex;
justify-content: space-between;
align-items: center;

/* Icon */
width: 32px;
height: 32px;
padding: 8px;
border-radius: 8px;

/* Icon inside */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Placeholder Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);

/* Keyboard Shortcut Badge */
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.11),
  inset 0px -1px 0.6px 0px rgba(0,0,0,0.20),
  inset 0px 2px 0.8px 0px rgba(255,255,255,0.27);
font-size: 12px;
font-weight: 500;
color: var(--Text-Secondary);
```

---

### 34. Article / Blog Layout

#### Header Section

**Container:**
```css
display: inline-flex;
flex-direction: column;
gap: 6px;
```

**Title:**
```css
font-size: 20px;
font-weight: 500;
line-height: 28px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
```

**Date/Metadata:**
```css
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
```

#### Content Section

**Container:**
```css
display: flex;
flex-direction: column;
gap: 32px;
```

**Featured Image/Screenshot:**
```css
width: 692px;
height: 470px;
background: rgba(17, 24, 39, 0.5); /* gray-900/50 */
border-radius: 32px;
position: relative;
overflow: hidden;
```

**Body Text:**
```css
/* Bold Text */
font-size: 16px;
font-weight: 700;
line-height: 24px;
color: var(--Text-Primary);

/* Normal Text */
font-size: 16px;
font-weight: 400;
line-height: 24px;
color: var(--Text-Primary);

/* List items with line breaks */
display: block;
```

**Layout Grid:**
```css
display: inline-flex;
gap: 128px;

/* Sidebar (left) */
width: 224px;

/* Content (right) */
flex: 1;
```

---

### 35. Gradient Overlays & Effects

#### Dark Gradient Overlay (Bottom)

```css
background: linear-gradient(to bottom,
  rgba(23, 23, 23, 0),
  rgba(23, 23, 23, 0),
  rgba(23, 23, 23, 0.3));
```

#### Light Gradient Overlay (Premium Card)

```css
background: linear-gradient(to left,
  rgba(2, 6, 23, 0.2),
  rgba(0, 0, 0, 0));
backdrop-filter: blur(6px);
```

#### Fade Edge Gradients (Scrollable)

**Horizontal:**
```css
/* Left */
background: linear-gradient(to bottom,
  rgba(250, 250, 250, 0),
  rgba(250, 250, 250, 1));
backdrop-filter: blur(6px);

/* Right */
background: linear-gradient(to bottom,
  rgba(250, 250, 250, 0),
  rgba(250, 250, 250, 1));
backdrop-filter: blur(6px);
```

**Vertical:**
```css
/* Top */
background: linear-gradient(to bottom,
  rgba(250, 250, 250, 0),
  rgba(250, 250, 250, 1));
backdrop-filter: blur(6px);

/* Bottom */
background: linear-gradient(to bottom,
  rgba(250, 250, 250, 0),
  rgba(250, 250, 250, 1));
backdrop-filter: blur(6px);
```

---

### 36. Multi-Layer Shadows (Elevation System)

#### Level 1 (Subtle)

```css
box-shadow:
  0px 1px 1px 0px rgba(0,0,0,0.02),
  0px 3px 3px 0px rgba(0,0,0,0.02),
  0px 6px 3px 0px rgba(0,0,0,0.01),
  0px 10px 4px 0px rgba(0,0,0,0.00),
  0px 16px 4px 0px rgba(0,0,0,0.00);
```

#### Level 2 (Medium)

```css
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
```

#### Level 3 (High)

```css
box-shadow:
  0px 16px 32px -24px rgba(0,0,0,0.62),
  0px 80px 64px -64px rgba(0,0,0,0.20),
  0px 12px 11.1px -12px rgba(0,0,0,0.15);
```

**Usage:**
- Level 1: Thumbnails, subtle cards
- Level 2: Hover states, modals, panels
- Level 3: Premium cards, floating elements

---

### 37. Text Truncation & Line Clamping

#### Single Line Truncation

```css
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### Multi-Line Truncation (WebKit)

```css
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 2; /* Number of lines */
-webkit-box-orient: vertical;
```

**Common use cases:**
- 1 line: Titles in compact cards
- 2 lines: Headers, section titles
- 3 lines: Descriptions

---

### 38. Commenting & Collaboration System

#### Comment Indicators

**Point Indicator (Default):**
```css
width: 36px;
height: 36px;
display: flex;
justify-content: center;
align-items: center;

/* Icon Container */
width: 24px;
height: 24px;
box-shadow:
  0px 1px 1px 0px rgba(0,0,0,0.02),
  0px 3px 3px 0px rgba(0,0,0,0.02),
  0px 6px 3px 0px rgba(0,0,0,0.01),
  0px 10px 4px 0px rgba(0,0,0,0.00),
  0px 16px 4px 0px rgba(0,0,0,0.00);

/* Comment Bubble */
width: 20px;
height: 16px;
background: var(--Surface-01);
border-radius: 3px;
box-shadow: 0px 2px 4px 0px rgba(0,0,0,0.15);
border: 1.5px solid var(--Text-Primary);

/* Dot (inside) */
width: 6px;
height: 6px;
outline: 1.5px solid var(--Text-Secondary);
opacity: 0.5;
```

**Pinned Indicator:**
```css
width: 36px;
height: 36px;

/* Dark Theme Badge */
width: 28px;
height: 28px;
background: linear-gradient(to bottom, #27272A, #18181B);
border-radius: 4.5px;
box-shadow: 0px 4px 4px 0px rgba(18,18,18,0.15);
border: 1px solid white;

/* Pin Icon */
width: 8px;
height: 8px;
outline: 1.5px solid var(--Text-Secondary);
```

**Typing Indicator:**
```css
width: 36px;
height: 36px;

/* Blue Theme Badge */
width: 28px;
height: 28px;
background: linear-gradient(to bottom, #38BDF8, #2563EB);
border-radius: 4.5px;
box-shadow: 0px 2px 4px 0px rgba(18,18,18,0.15);
border: 1px solid white;

/* Three Dots */
width: 1.5px;
height: 1.5px;
background: var(--Shade1-100);
border-radius: 50%;
/* Repeated 3 times with gap */
```

**Uploading Indicator:**
```css
width: 36px;
height: 36px;

/* Blue Theme Badge */
width: 28px;
height: 28px;
background: linear-gradient(to bottom, #38BDF8, #2563EB);
border-radius: 4.5px;
box-shadow: 0px 2px 4px 0px rgba(18,18,18,0.15);
border: 1px solid white;

/* Upload Progress Circle */
width: 8px;
height: 8px;
outline: 1.5px solid var(--Surface-01);
```

**Single Comment Indicator:**
```css
width: 36px;
height: 36px;

/* Avatar Badge */
padding: 4px;
background: var(--Shade1-100);
border-radius: 20px 20px 1px 20px; /* Rounded top-left, top-right, bottom-right, sharp bottom-left */
box-shadow: 0px 2px 2px 0px rgba(0,0,0,0.15);
outline: 1.5px solid var(--Colors-Blue-Blue-100);

/* Avatar Image */
width: 24px;
height: 24px;
border-radius: 20px;
```

**Conversation Indicator (Avatar Stack):**
```css
width: 48px;
padding: 2px;
display: flex;
flex-direction: column;
gap: 8px;

/* Stack Container */
padding: 4px;
background: var(--Shade1-100);
border-radius: 20px 20px 1px 20px;
box-shadow: 0px 2px 2px 0px rgba(0,0,0,0.15);
outline: 1.5px solid var(--Stroke-01);

/* Avatars (overlapping) */
width: 24px;
height: 24px;
border-radius: 20px;
outline: 1.5px solid var(--Surface-01);
/* Stack with negative margin for overlap */
```

#### User List (Dropdown)

**Container:**
```css
width: 208px;
background: var(--Surface-01);
border-radius: 12px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;
overflow: hidden;
```

**User Item (Default):**
```css
padding: 12px 10px;
display: flex;
align-items: center;
gap: 12px;

/* Avatar */
width: 32px;
height: 32px;
border-radius: 32px;

/* Text Container */
flex: 1;
display: flex;
flex-direction: column;

/* Name */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Username */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

**User Item (Hover):**
```css
background: var(--Surface-03);
/* Rest same as default */
```

#### Comment Card

**Container:**
```css
width: 288px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 8px 16px -12px rgba(0,0,0,0.08),
  0px 18px 24px -20px rgba(0,0,0,0.12),
  inset 0px 2px 0px 0px rgba(255,255,255,1.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;
overflow: hidden;
```

**Comment Content:**
```css
padding: 16px;
border-top: 1px solid var(--Stroke-01);
display: flex;
gap: 16px;

/* Avatar */
width: 32px;
height: 32px;
border-radius: 32px;

/* Content Container */
flex: 1;
display: flex;
flex-direction: column;
gap: 4px;

/* Header (Name + Time) */
display: flex;
align-items: center;
gap: 8px;

/* Author Name */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Timestamp */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Comment Text */
font-size: 12px;
font-weight: 400;
line-height: 20px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 8;
-webkit-box-orient: vertical;
```

**Close Button (Top Right):**
```css
position: absolute;
top: 8px;
right: 8px;
width: 20px;
height: 20px;
padding: 2px;
background: linear-gradient(to bottom, #27272A, #18181B);
border-radius: 32px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Shade1-100);
```

**Active Comment Card (with blue outline):**
```css
outline: 3px solid var(--Colors-Blue-Blue-100);
```

#### Comment Input Field

**Simple Input:**
```css
width: 288px;
padding: 8px;
background: var(--Surface-01);
border-radius: 12px;
box-shadow:
  0px 8px 16px -12px rgba(0,0,0,0.08),
  0px 18px 24px -20px rgba(0,0,0,0.12),
  inset 0px 2px 0px 0px rgba(255,255,255,1.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);

/* Input Field */
padding: 8px;
position: relative;
display: flex;
gap: 8px;

/* Placeholder */
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Secondary);

/* Cursor */
width: 0;
height: 16px;
outline: 1px solid black;
```

**Expanded Input with Tools:**
```css
/* Container */
width: 288px;
padding: 16px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 8px 16px -12px rgba(0,0,0,0.08),
  0px 18px 24px -20px rgba(0,0,0,0.12),
  inset 0px 2px 0px 0px rgba(255,255,255,1.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);

/* Text Area */
padding: 16px;
font-size: 12px;
font-weight: 400;
line-height: 20px;
color: var(--Text-Primary);

/* Toolbar (Bottom) */
padding: 8px;
border-top: 1px solid var(--Stroke-01);
display: flex;
justify-content: space-between;
align-items: center;

/* Tool Icons Group */
display: flex;
gap: 4px;

/* Tool Icon Button */
width: 32px;
height: 32px;
padding: 32px;
border-radius: 10px;
/* Hover: add background */

/* Icon */
width: 20px;
height: 20px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Send Button */
width: 32px;
height: 32px;
padding: 32px 12px;
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5);
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);

/* Send Icon */
width: 20px;
height: 20px;
stroke-width: 1.5px;
color: var(--Text-Primary);
```

#### Reply Input (Inline)

**Container:**
```css
width: 288px;
padding: 16px;
border-top: 1px solid var(--Stroke-01);
display: flex;
gap: 16px;

/* Avatar */
width: 32px;
height: 32px;
border-radius: 32px;

/* Input Container */
flex: 1;
padding: 6px;
background: var(--Surface-03);
border-radius: 12px;
display: flex;
gap: 24px;

/* Text Input */
flex: 1;
padding: 8px;
position: relative;
display: flex;
gap: 8px;

/* Placeholder */
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Secondary);

/* Send Button (Small) */
width: 32px;
height: 32px;
padding: 32px 12px;
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5);
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
```

#### Conversation Thread

**Thread Card:**
```css
width: 288px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 8px 16px -12px rgba(0,0,0,0.08),
  0px 18px 24px -20px rgba(0,0,0,0.12),
  inset 0px 2px 0px 0px rgba(255,255,255,1.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;
overflow: hidden;

/* Multiple Comment Items */
/* Each separated by border-top: 1px solid var(--Stroke-01) */
```

#### Comment with Attachments

**Container:**
```css
padding: 16px;
display: flex;
flex-direction: column;
gap: 12px;

/* Text */
font-size: 12px;
font-weight: 400;
line-height: 20px;
color: var(--Text-Primary);

/* Image Thumbnails */
display: flex;
gap: 8px;

/* Thumbnail (Regular) */
width: 60px;
height: 60px;
padding: 4px;
border-radius: 12px;
object-fit: cover;

/* Thumbnail with Badge (More Images) */
width: 60px;
height: 60px;
position: relative;

/* Overlay */
padding: 4px;
background: rgba(254, 254, 254, 0.20);
border-radius: 10px;
backdrop-filter: blur(6px);

/* Badge (Top Right) */
position: absolute;
top: -6px;
right: -6px;
width: 20px;
height: 20px;
padding: 2px;
background: linear-gradient(to bottom, #27272A, #18181B);
border-radius: 32px;
outline: 2px solid var(--Surface-01);

/* Count Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Shade1-100);
```

#### File Upload State

**Upload Card:**
```css
width: 288px;
padding: 16px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 8px 16px -12px rgba(0,0,0,0.08),
  0px 18px 24px -20px rgba(0,0,0,0.12),
  inset 0px 2px 0px 0px rgba(255,255,255,1.00);
outline: 3px solid var(--Colors-Blue-Blue-100);
backdrop-filter: blur(6px);
display: flex;
justify-content: center;
align-items: center;
position: relative;

/* File Info */
display: flex;
align-items: center;
gap: 8px;

/* File Icon */
width: 20px;
height: 20px;
padding: 4px;
border-radius: 6px;

/* File Name */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Upload Progress Indicator (Top Right) */
position: absolute;
top: 9px;
right: 9px;
width: 32px;
height: 32px;

/* Progress Circle */
width: 16px;
height: 16px;
background: linear-gradient(to bottom, #84CC16, #15803D);
border-radius: 30px;
```

#### Status Badges (Small)

**Pinned Badge (Small):**
```css
width: 20px;
height: 20px;
padding: 2px;
background: linear-gradient(to bottom, #27272A, #18181B);
border-radius: 32px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Shade1-100);
```

**Active/Selected Badge (Small):**
```css
width: 20px;
height: 20px;
padding: 2px;
background: rgba(254, 254, 254, 0.10);
border-radius: 32px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Shade1-100);
```

**Usage Guidelines:**
- Use point indicators for new/unread comments
- Use pinned indicators for important comments
- Use typing indicators for real-time collaboration
- Use avatar stacks for conversations with multiple participants
- Show upload state with progress indicator
- Use blue outline for active/focused comment cards

---

### 39. Dropdown / Select / Combobox

#### Standard Dropdown (with Icon & Chevron)

**Default State:**
```css
padding: 8px 10px 8px 8px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
display: flex;
justify-content: space-between;
align-items: center;
gap: 8px;

/* Content Container */
flex: 1;
display: flex;
align-items: center;
gap: 6px;

/* Icon (Left) */
width: 16px;
height: 16px;
opacity: 0.7;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron (Right) */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Hover State:**
```css
background: var(--Surface-02);
outline: 1px solid var(--Stroke-02);
/* Rest same as default */
```

**Focus State:**
```css
background: var(--Surface-01);
box-shadow: inset 0px 0px 0px 1.5px rgba(53, 130, 255, 0.5);
outline: 1px solid transparent;

/* Icon (no opacity) */
opacity: 1;
```

**Disabled State:**
```css
opacity: 0.3;
background: var(--Surface-03);
outline: 1px solid var(--Stroke-01);
cursor: not-allowed;
```

#### Dropdown without Left Icon

**Default State:**
```css
padding: 10px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
display: flex;
justify-content: space-between;
align-items: center;
gap: 8px;

/* Text */
flex: 1;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron (Right) */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**States:** Same as standard dropdown (hover, focus, disabled)

#### Dropdown with Additional Info (Resolution/Size)

**Default State:**
```css
padding: 10px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
display: flex;
justify-content: space-between;
align-items: center;
gap: 8px;

/* Left Content */
flex: 1;
display: flex;
align-items: center;
gap: 6px;

/* Icon */
width: 16px;
height: 16px;
opacity: 0.7;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Right Content (Info + Chevron) */
display: flex;
align-items: center;
gap: 8px;

/* Info Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
opacity: 0.5;
text-align: right;

/* Chevron */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Hover State:**
```css
outline: 1px solid var(--Stroke-02);
/* No background change for this variant */
```

**Focus State:**
```css
background: var(--Surface-01);
box-shadow: inset 0px 0px 0px 1.5px rgba(53, 130, 255, 0.5);
outline: 1px solid transparent;
```

#### Simple Editable Field ("can edit")

**Default State:**
```css
padding: 8px;
border-radius: 8px;
display: flex;
justify-content: space-between;
align-items: center;

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Hover State:**
```css
background: var(--Surface-03);
/* Rest same */
```

**Focus State:**
```css
border-radius: 8px;
outline: 1px solid var(--Colors-Blue-Blue-100);
```

**Disabled State:**
```css
opacity: 0.3;
```

#### Elevated Dropdown ("can view")

**Default State:**
```css
padding: 8px 8px 8px 12px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18, 18, 18, 0.10);
display: flex;
justify-content: space-between;
align-items: center;

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Hover State:**
```css
outline: 1px solid var(--Stroke-02);
```

**Focus State:**
```css
outline: 1px solid var(--Colors-Blue-Blue-100);

/* Chevron */
color: var(--Text-Primary);
```

**Disabled State:**
```css
opacity: 0.3;
```

#### Dropdown Menu (Expanded)

**Trigger Button (Expanded):**
```css
padding: 8px;
background: var(--Surface-02);
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
display: flex;
justify-content: space-between;
align-items: center;

/* Icon Container */
padding: 4px;
display: flex;
align-items: center;
gap: 4px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron (Right) */
padding: 4px;
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Primary);
```

**Dropdown Panel:**
```css
width: 176px;
background: var(--Shade1-100);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;
overflow: hidden;
```

**Menu Section:**
```css
padding: 8px;
display: flex;
flex-direction: column;
position: relative;

/* Section Divider */
border-top: 1px solid var(--Stroke-01);
```

**Menu Item (Default):**
```css
height: 36px;
padding: 6px 8px 6px 6px;
border-radius: 10px;
display: flex;
justify-content: space-between;
align-items: center;
gap: 8px;

/* Left Content */
flex: 1;
display: flex;
align-items: center;
gap: 4px;

/* Icon Container */
padding: 4px;
border-radius: 6px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Keyboard Shortcut */
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.08),
  inset 0px -0.75px 0.5px 0px rgba(0,0,0,0.25),
  inset 0px 0.75px 0px 0px rgba(252,252,252,1.00);
opacity: 0; /* Hidden by default */

/* Shortcut Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
text-align: center;
```

**Menu Item (Hover):**
```css
background: var(--Surface-03);
/* Rest same */
```

**Menu Item (Active/Selected):**
```css
/* Icon Container */
padding: 4px;
border-radius: 6px;
background: transparent; /* Visible by default when active */

/* Icon */
color: var(--Text-Secondary);
```

#### Zoom/Percentage Dropdown

**Default State:**
```css
height: 40px;
padding: 4px 12px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid var(--Stroke-01);
display: flex;
justify-content: space-between;
align-items: center;

/* Text */
font-size: 14px;
font-weight: 500;
line-height: 20px;
color: var(--Text-Primary);

/* Chevron */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Hover State:**
```css
background: var(--Surface-01);
outline: 1px solid var(--Stroke-02);

/* Chevron */
color: var(--Text-Primary);
```

**Focus State (Expanded):**
```css
background: var(--Surface-03);
box-shadow: inset 0px 0px 2px 2px rgba(255, 255, 255, 1.00);
outline: 1px solid rgba(39, 39, 42, 0.1); /* Shade-9-10/10 */

/* Chevron */
color: var(--Text-Secondary);
```

**Disabled State:**
```css
opacity: 0.3;
```

#### Tag/Category Dropdown

**Default State:**
```css
height: 40px;
padding: 4px 10px;
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
display: flex;
align-items: center;
gap: 12px;

/* Left Content */
display: flex;
align-items: center;
gap: 8px;

/* Tag Icon Container */
padding: 2px;

/* Tag Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;

/* Tag Color Square */
width: 12px;
height: 14px;
border-radius: 0.5px;
outline: 1.5px solid var(--Colors-Green);

/* Text */
font-size: 14px;
font-weight: 500;
line-height: 20px;
color: var(--Text-Primary);

/* Chevron Container */
padding: 2px;

/* Chevron */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Focus State:**
```css
outline: 1.5px solid var(--Colors-Blue-Blue-100);
```

**Hover State:**
```css
box-shadow: 0px 2px 8px -4px rgba(0, 0, 0, 0.25);
outline: 1px solid var(--Stroke-02);
```

**Active State (Expanded):**
```css
background: var(--Surface-03);
outline: 1px solid var(--Stroke-02);

/* Chevron */
color: var(--Text-Primary);
```

**Disabled State:**
```css
opacity: 0.3;

/* Tag Icon */
color: var(--Text-Secondary);
```

#### Text-Only Dropdown (No Icon)

**Default State:**
```css
padding: 10px 12px;
border-radius: 12px;
outline: 1px solid transparent;
display: flex;
align-items: center;
gap: 12px;

/* Text */
font-size: 14px;
font-weight: 500;
line-height: 20px;
color: var(--Text-Primary);

/* Chevron Container */
padding: 2px;

/* Chevron */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Hover State:**
```css
background: var(--Surface-03);

/* Chevron */
color: var(--Text-Secondary);
```

**Focus State:**
```css
outline: 1.5px solid var(--Colors-Blue-Blue-100);

/* Chevron */
color: var(--Text-Secondary);
```

**Active State (Expanded):**
```css
/* Chevron */
color: var(--Text-Primary);
```

**Disabled State:**
```css
opacity: 0.3;
```

#### Sizes

**Small (Default):**
- Height: 32px (with padding: 8px 10px)
- Font size: 12px
- Icon: 16px

**Medium:**
- Height: 40px (with padding: 4px 12px)
- Font size: 14px
- Icon: 16px

**Usage Guidelines:**
- Use standard dropdown for filter selections with icons
- Use text-only dropdown for simple value selections
- Use tag dropdown for color-coded categories
- Use zoom dropdown for numeric values with units
- Show keyboard shortcuts only on hover in menu items
- Use blue outline for focus states
- Use elevated dropdowns for important selections that float above content
- Add chevron rotation animation when expanding (rotate 180deg)

---

### 40. Form Inputs / Text Fields

#### Email / Text Input

**Label:**
```css
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
margin-bottom: 8px;
```

**Default State:**
```css
padding: 16px 24px;
background: var(--Surface-01);
border-radius: 12px;
outline: 1.5px solid var(--Stroke-Stroke1);

/* Placeholder */
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Secondary);
```

**Hover State:**
```css
background: var(--Surface-01);
border-radius: 12px;
box-shadow: 0px 1px 4px -1px rgba(0,0,0,0.15);
outline: 1.5px solid var(--Stroke-02);
overflow: hidden;
```

**Focus State:**
```css
background: var(--Surface-01);
border-radius: 12px;
box-shadow: 0px 1px 4px -1px rgba(0,0,0,0.15);
outline: 1.5px solid var(--Colors-Blue-Blue-100);
overflow: hidden;
```

**Typing State:**
```css
/* Same as focus + cursor */
/* Cursor */
width: 0;
height: 16px;
outline: 1px solid var(--Text-Primary);

/* Placeholder (faded) */
opacity: 0.5;
```

**Filled State:**
```css
/* Same as default */
/* Text */
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Primary);

/* Clear Icon (Right) */
width: 20px;
height: 20px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Error State:**
```css
/* Same as default */
/* Error Message (below input) */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Colors-Red);
margin-top: 8px;
```

#### Password Input

**Label with Link:**
```css
display: flex;
justify-content: space-between;
align-items: center;
margin-bottom: 8px;

/* Label */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* "Forgot password?" Link */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
opacity: 0.7;
cursor: pointer;
```

**Default State (Masked):**
```css
height: 48px;
padding: 16px 24px;
background: var(--Surface-01);
border-radius: 12px;
outline: 1.5px solid var(--Stroke-Stroke1);
display: flex;
align-items: center;
gap: 8px;

/* Password Dots */
display: flex;
gap: 4px;
opacity: 0.5;

/* Dot */
width: 6px;
height: 6px;
background: var(--Text-Secondary);
border-radius: 50%;
```

**Filled with Toggle:**
```css
height: 48px;
padding-left: 24px;
padding-right: 14px;
background: var(--Surface-01);
border-radius: 12px;
box-shadow: 0px 1px 4px -1px rgba(0,0,0,0.15);
outline: 1.5px solid var(--Stroke-02);
display: flex;
justify-content: space-between;
align-items: center;

/* Password Content */
display: flex;
align-items: center;
gap: 1px;

/* Dots (filled) */
width: 6px;
height: 6px;
background: var(--Text-Primary);
border-radius: 50%;

/* Cursor */
width: 0;
height: 16px;
outline: 1px solid var(--Text-Primary);

/* Toggle Icon (Eye) */
width: 20px;
height: 20px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Filled with Text Visible:**
```css
/* Same as above */
/* Text instead of dots */
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Primary);

/* Cursor next to text */
width: 0;
height: 16px;
outline: 1px solid var(--Text-Primary);

/* Toggle Icon (Eye Slash) */
width: 20px;
height: 20px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

#### Numeric Input (Slider Value)

**Default State:**
```css
padding: 6px 8px 6px 10px;
background: var(--Surface-03);
border-radius: 10px;
display: flex;
align-items: center;
gap: 6px;

/* Icon (Left) */
width: 16px;
height: 16px;
opacity: 0.7;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Value Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
text-align: right;
```

**Hover State:**
```css
background: var(--Surface-02);
outline: 1px solid var(--Stroke-01);
```

**Focus/Active State:**
```css
background: var(--Surface-02);
outline: 1px solid var(--Stroke-02);

/* Value (highlighted) */
background: var(--Colors-Blue-Blue-20/20);
outline: 1px solid var(--Colors-Blue-Blue-50/50);
padding: 2px;
```

**Disabled State:**
```css
opacity: 0.3;
/* Icon */
opacity: 0.3;
```

#### Inline Username Editor

**Read-only State:**
```css
display: flex;
align-items: center;
gap: 8px;

/* Username Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Edit Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Disabled State:**
```css
opacity: 0.5;
```

**Editing State:**
```css
display: flex;
align-items: center;
gap: 8px;

/* Input Container */
display: flex;
align-items: center;

/* Cursor */
width: 0;
height: 12px;
outline: 1px solid black;

/* Placeholder */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
opacity: 0.3;

/* Collapse Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**Valid State:**
```css
/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Cursor */
width: 0;
height: 12px;
outline: 1px solid black;

/* Check Icon (Green) */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Colors-Green);
```

#### Avatar Upload

**Default State:**
```css
width: 48px;
height: 48px;
border-radius: 32px;
overflow: hidden;
```

**Hover State (with Delete Overlay):**
```css
width: 48px;
height: 48px;
background: rgba(0, 0, 0, 0.4);
border-radius: 32px;
overflow: hidden;
position: relative;

/* Delete Icon */
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
width: 20px;
height: 20px;
stroke-width: 1.5px;
color: var(--Shade1-100);
```

#### Color Picker Input

**Container:**
```css
padding: 4px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
display: flex;
align-items: center;
overflow: hidden;
```

**Color Section:**
```css
flex: 1;
border-right: 1px solid rgba(39, 39, 42, 0.1); /* Shade-7-10/10 */
display: flex;
align-items: center;
gap: 12px;
padding-right: 8px;

/* Color Swatch */
width: 28px;
height: 28px;
background: var(--Surface-01);
border-radius: 6px;
border: 1px solid rgba(39, 39, 42, 0.1);

/* Hex Code */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

**Opacity Section:**
```css
padding: 0 12px;
display: flex;
align-items: center;
gap: 8px;

/* Opacity Value */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Percent Symbol */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

**States:**

1. **Default**: `background: var(--Surface-03)`
2. **Hover**: `background: var(--Surface-02); outline: 1px solid var(--Stroke-02)`
3. **Focus (Hex)**: `background: var(--Surface-03); outline: 1px solid var(--Shade-9-10/10);` + hex highlighted with blue background
4. **Focus (Opacity)**: Same + opacity value highlighted
5. **Disabled**: `opacity: 0.3`

#### Share/Invite Input

**Container:**
```css
padding: 4px 4px 4px 16px;
background: var(--Surface-02);
border-radius: 12px;
box-shadow: inset 0px 1px 3px 0px rgba(18,18,18,0.10);
outline: 1px solid var(--Stroke-02);
display: flex;
justify-content: space-between;
align-items: center;
overflow: hidden;
```

**Input Section:**
```css
flex: 1;
display: flex;
align-items: center;
gap: 1px;

/* Cursor */
width: 0;
height: 12px;
outline: 1.5px solid var(--Colors-Blue-Blue-100);

/* Placeholder */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
opacity: 0.5;
```

**Permission Dropdown:**
```css
width: 96px;
padding: 8px 8px 8px 12px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: space-between;
align-items: center;

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);
```

**States:**

1. **Default**: Standard outline
2. **Hover**: `outline: 1px solid var(--Shade-7-5/5)`
3. **Focus**: `outline: 1px solid var(--Colors-Blue-Blue-100)`
4. **Filled**: Email text visible with active dropdown
5. **Disabled**: `opacity: 0.5`

**Dropdown Menu:**
```css
width: 96px;
padding: 4px;
background: var(--Surface-01);
border-radius: 12px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;

/* Menu Item (Hover) */
height: 32px;
padding: 8px 12px;
background: var(--Surface-03);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);

/* Menu Item (Default) */
height: 32px;
padding: 8px 12px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
```

#### Search Input

**With Icon and Keyboard Shortcut:**
```css
padding: 4px 10px 4px 4px;
background: var(--Surface-01);
border-radius: 12px;
display: flex;
justify-content: space-between;
align-items: center;
gap: 12px;

/* Icon Container */
width: 32px;
height: 32px;
padding: 8px;
border-radius: 8px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Placeholder */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);

/* Keyboard Shortcut Badge */
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.11),
  inset 0px -1px 0.6px 0px rgba(0,0,0,0.20),
  inset 0px 2px 0.8px 0px rgba(255,255,255,0.27);

/* Shortcut Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
```

**States:**

1. **Default**: No outline
2. **Hover**: `outline: 1px solid var(--Stroke-01)`
3. **Focus**: `background: var(--Surface-02); box-shadow: inset 0px 0px 0px 2px rgba(252,252,252,1.00); outline: 1px solid rgba(115,115,115,0.5)`

**With Back Button (Navigation):**
```css
padding: 4px 10px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 1px 3px 0px rgba(18,18,18,0.10);
outline: 1px solid var(--Stroke-02);

/* Back Icon Container */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);

/* Back Icon */
width: 16px;
height: 16px;
stroke-width: 2px;
color: var(--Text-Secondary);

/* Text + Cursor */
display: flex;
align-items: center;
gap: 1px;

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Cursor */
width: 0;
height: 12px;
outline: 1.5px solid black;
```

**Active Search State:**
```css
padding: 4px 10px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 1px 3px 0px rgba(18,18,18,0.10);
outline: 1px solid var(--Stroke-02);

/* Search Icon Container (Active) */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);

/* Cursor next to placeholder */
width: 0;
height: 12px;
outline: 1.5px solid black;
position: absolute;
```

#### Sign In / Sign Up Forms

**Form Container:**
```css
width: 640px;
height: 900px;
padding: 0 160px;
background: var(--Surface-01);
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
gap: 40px;
```

**Title:**
```css
font-size: 30px;
font-weight: 500;
line-height: 40px;
color: var(--Text-Primary);
text-align: center;
```

**Google Sign In Button:**
```css
width: 320px;
height: 44px;
padding: 8px 20px;
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5);
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Google Icon */
width: 24px;
height: 24px;

/* Text */
font-size: 14px;
font-weight: 600;
line-height: 20px;
color: var(--Text-Primary);
text-align: center;
```

**Divider Text:**
```css
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Tertiary);
text-align: center;
```

**Submit Button (Dark):**
```css
width: 100%;
padding: 12px 20px;
background: linear-gradient(to bottom, var(--Shade-7-100), var(--Shade-8-100));
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(51,51,51,1.00),
  0px 2px 4px -1px rgba(13,13,13,0.50),
  inset 0px -1px 1.2px 0.35px rgba(18,18,18,1.00),
  inset 0px 0.5px 1px 0px rgba(255,255,255,0.15);

/* Text */
font-size: 14px;
font-weight: 600;
line-height: 20px;
color: var(--neutral-50);
text-align: center;
```

**Footer Text:**
```css
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
text-align: center;
```

**Usage Guidelines:**
- Always include clear labels for inputs
- Show error states with red text below the field
- Use blue outline (1.5px) for focus states
- Password fields should include "Forgot password?" link
- Provide toggle visibility for password fields (eye icon)
- Search inputs should include keyboard shortcuts (⌘ K)
- Share/invite inputs should combine text input with permission dropdown
- Use cursor indicator (1px vertical line) for typing states
- Numeric inputs should highlight the value when editing
- Avatar upload should show delete overlay on hover

---

### 41. Menu Items / List Items

#### Standard Menu Item (with Keyboard Shortcut)

**Container:**
```css
width: 192px; /* or self-stretch */
height: 36px;
padding: 6px 8px 6px 6px;
border-radius: 10px;
display: flex;
align-items: center;
gap: 8px;
overflow: hidden;
```

**Content Section:**
```css
flex: 1;
display: flex;
align-items: center;
gap: 4px;

/* Icon Container */
padding: 4px;
border-radius: 6px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

**Keyboard Shortcut Badge:**
```css
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.08),
  inset 0px -0.75px 0.5px 0px rgba(0,0,0,0.25),
  inset 0px 0.75px 0px 0px rgba(252,252,252,1.00);

/* Text */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
text-align: center;
```

**States:**

1. **Default**:
```css
/* Icon opacity: 0 (hidden) */
opacity: 0;
```

2. **Hover**:
```css
background: var(--Surface-03);
/* Icon becomes visible */
```

3. **Active/Selected**:
```css
/* Icon visible by default */
padding: 4px;
border-radius: 6px;
opacity: 1;
```

4. **Focus**:
```css
outline: 1px solid var(--Colors-Blue-Blue-100);
```

#### Menu Item with Value Display (Zoom Control)

**Header Item:**
```css
width: 192px;
height: 36px;
padding: 6px 8px 6px 6px;
background: var(--Surface-02);
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
display: flex;
align-items: center;
gap: 4px;

/* Icon Container */
padding: 4px;
border-radius: 6px;

/* Icon */
width: 16px;
height: 16px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Value Badge */
background: rgba(59, 130, 246, 0.3); /* blue-500/30 */
border-radius: 2px;
padding: 2px;

/* Value Text */
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
text-align: right;
```

#### Dropdown Menu with Sections

**Container:**
```css
width: 208px;
background: var(--Shade1-100);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;
overflow: hidden;
```

**Section:**
```css
padding: 8px;
border-bottom: 1px solid var(--Stroke-01);
/* or border-top for subsequent sections */
display: flex;
flex-direction: column;
```

**Section Divider:**
```css
border-top: 1px solid var(--Stroke-01);
```

#### Single-line Menu Item (Icon + Text)

**Default State:**
```css
padding: 8px;
border-radius: 12px;
display: flex;
align-items: center;
gap: 10px;

/* Icon Container */
padding: 2px;

/* Icon */
width: 20px;
height: 20px;
stroke-width: 1.5px;
color: var(--Text-Secondary);

/* Text */
flex: 1;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

**Hover State:**
```css
background: var(--Surface-03);
```

**Focus State:**
```css
outline: 1.5px solid var(--Colors-Blue-Blue-100);
```

**Pressed State:**
```css
background: var(--Surface-02);
box-shadow: inset 0px 0px 2.7px 0px rgba(0,0,0,0.25);
```

**Disabled State:**
```css
opacity: 0.3;
```

**Alternative Pressed State (Light):**
```css
border-radius: 12px;
box-shadow: inset 0px 0px 0px 2px rgba(255,255,255,0.50);
outline: 1px solid var(--Stroke-02);
overflow: hidden;
```

#### Two-line List Item (Title + Subtitle)

**Default State:**
```css
padding: 10px 12px;
border-radius: 12px;
display: flex;
flex-direction: column;
gap: 4px;

/* Title */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Subtitle */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
opacity: 0.7;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

**Hover State:**
```css
background: var(--Surface-03);
```

**Focus State:**
```css
outline: 1.5px solid var(--Colors-Blue-Blue-100);
```

**Pressed State (Dark):**
```css
background: var(--Surface-02);
box-shadow: inset 0px 0px 2.7px 0px rgba(0,0,0,0.25);
```

**Pressed State (Light):**
```css
border-radius: 12px;
box-shadow: inset 0px 0px 0px 2px rgba(255,255,255,0.50);
outline: 1px solid var(--Stroke-02);
overflow: hidden;
```

**Disabled State:**
```css
opacity: 0.3;
```

#### Menu Item Variations

**With Icon (Always Visible):**
```css
/* Icon */
padding: 4px;
border-radius: 6px;
opacity: 1; /* Always visible */

/* Icon on active item */
color: var(--Text-Secondary);
```

**With Icon (Hidden by Default):**
```css
/* Icon */
padding: 4px;
border-radius: 6px;
opacity: 0;

/* Show on hover/active */
opacity: 1;
```

**With Long Keyboard Shortcut:**
```css
/* Shortcut Badge */
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.08),
  inset 0px -0.75px 0.5px 0px rgba(0,0,0,0.25),
  inset 0px 0.75px 0px 0px rgba(252,252,252,1.00);

/* Examples: "⌘ +", "⌘ 0", "Shift C", "Shift" */
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
```

#### Menu Item Sizes

**Compact (Height: 32px):**
```css
height: 32px;
padding: 6px 8px 6px 6px;
border-radius: 10px;

/* Icon: 16px */
/* Font size: 12px */
```

**Standard (Height: 36px):**
```css
height: 36px;
padding: 6px 8px 6px 6px;
border-radius: 10px;

/* Icon: 16px */
/* Font size: 12px */
```

**Large (Height: 40px):**
```css
height: 40px;
padding: 8px;
border-radius: 12px;

/* Icon: 20px */
/* Font size: 12px */
```

**Two-line (Height: auto):**
```css
padding: 10px 12px;
border-radius: 12px;

/* Title: 12px */
/* Subtitle: 12px */
/* Gap: 4px */
```

#### Icon Behavior

**Option 1 - Hidden until hover:**
```css
/* Default */
.icon-container {
  padding: 4px;
  border-radius: 6px;
  opacity: 0;
}

/* Hover/Active */
.menu-item:hover .icon-container,
.menu-item[data-active="true"] .icon-container {
  opacity: 1;
}
```

**Option 2 - Always visible on active:**
```css
/* Default */
.icon-container {
  padding: 4px;
  border-radius: 6px;
}

/* Icon visible only on active items */
.menu-item[data-active="true"] .icon-container {
  opacity: 1;
}
```

**Usage Guidelines:**
- Use keyboard shortcuts for frequently used actions
- Hide icons by default (opacity: 0), show on hover or when active
- Use blue outline (1px or 1.5px) for focus states
- Group related items in sections with dividers (1px solid Stroke-01)
- Two-line items should truncate subtitle with ellipsis
- Pressed states can use either dark inset shadow or light white inset shadow
- Disabled items should have 30% opacity
- Menu items with values (like zoom) should highlight the value
- Use backdrop-filter: blur(6px) for floating menus

---

### 42. Context Menus & Folder Navigation

Контекстные меню с секциями, клавиатурными сокращениями и навигация по папкам с поиском.

#### 42.1. Menu Item with Keyboard Shortcut - Default State

Стандартный пункт меню с текстом и клавиатурным сокращением, без фона.

```css
/* Menu Item Container */
width: 224px;
height: 36px;
padding: 6px 8px 6px 8px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text Container */
flex: 1;
height: 24px;
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Text */
flex: 1;
justify-content: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Keyboard Shortcut Badge */
padding: 2px 4px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.08),
  inset 0px -0.75px 0.5px 0px rgba(0,0,0,0.25),
  inset 0px 0.75px 0px 0px rgba(252,252,252,1.00);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Shortcut Text */
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: center;
color: var(--Text-Secondary);
```

#### 42.2. Menu Item with Keyboard Shortcut - Hover State

```css
/* Menu Item Container - Hover */
width: 192px;
height: 36px;
padding: 6px 8px 6px 8px;
background: var(--Surface-03);
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Rest matches default state */
```

#### 42.3. Context Menu - Full Structure

Выпадающее меню с секциями, разделителями и клавиатурными сокращениями.

```css
/* Menu Container */
width: 208px;
background: var(--Shade1-100);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;

/* Menu Section - Top (with shortcuts) */
width: 100%;
padding: 8px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;

/* Menu Item in Section - Default */
width: 100%;
height: 36px;
padding: 6px 8px 6px 8px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Menu Item Text Container */
flex: 1;
height: 24px;
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Menu Item Text */
flex: 1;
justify-content: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Keyboard Shortcut Badge */
padding: 2px 6px;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.08),
  inset 0px -0.75px 0.5px 0px rgba(0,0,0,0.25),
  inset 0px 0.75px 0px 0px rgba(252,252,252,1.00);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Shortcut Text */
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: center;
color: var(--Text-Secondary);
```

#### 42.4. Context Menu - Section Divider

```css
/* Divider Section */
width: 100%;
padding: 8px;
border-top: 1px solid var(--Stroke-01);
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;
```

#### 42.5. Context Menu Item - Without Shortcut (Default)

```css
/* Menu Item - No Shortcut */
width: 100%;
height: 36px;
padding: 6px 8px 6px 8px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text Container */
flex: 1;
height: 24px;
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Text */
flex: 1;
justify-content: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

#### 42.6. Context Menu Item - Without Shortcut (Hover)

```css
/* Menu Item - Hover */
width: 100%;
height: 36px;
padding: 6px 8px 6px 8px;
background: var(--Surface-03);
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;
```

#### 42.7. Folder Navigation Menu - Container

Меню навигации по папкам с поиском и цветными иконками.

```css
/* Folder Menu Container */
width: 224px;
background: var(--Shade1-100);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;
```

#### 42.8. Folder Navigation - Search Input (Active)

```css
/* Search Section */
width: 100%;
padding: 8px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 8px;
overflow: hidden;

/* Search Input Container - Active */
width: 100%;
padding: 4px 4px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 1px 3px 0px rgba(18,18,18,0.10);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Search Content Container */
flex: 1;
position: relative;
display: flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Search Icon Button */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Search Icon (Magnifying Glass) */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Search Icon Circle */
width: 10px;
height: 10px;
left: 2.5px;
top: 2.5px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
border-radius: 50%;

/* Search Placeholder Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);

/* Cursor (Blinking Line) */
width: 0px;
height: 12px;
left: 43px;
top: 10px;
position: absolute;
outline: 1.5px solid black;
outline-offset: -0.75px;
```

#### 42.9. Folder List Section

```css
/* Folder List Section */
width: 100%;
padding: 0px 8px 8px 8px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
```

#### 42.10. Folder Item - Default State

```css
/* Folder Item Container */
width: 100%;
height: 40px;
padding: 4px 12px 4px 4px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Folder Content */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Folder Icon Container */
padding: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Folder Icon (Generic) */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Folder Icon - Bottom Part */
width: 16px;
height: 6px;
left: 2px;
top: 10px;
position: absolute;
opacity: 0.2;
background: var(--Colors-Orange); /* or Green, Blue, Red */

/* Folder Icon - Top Part */
width: 16px;
height: 12px;
left: 2.29px;
top: 3.12px;
position: absolute;
border-radius: 2px;
outline: 1.5px solid var(--Colors-Orange); /* or Green, Blue, Red */
outline-offset: -0.75px;

/* Folder Name */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 42.11. Folder Item - Hover State

```css
/* Folder Item Container - Hover */
width: 100%;
height: 40px;
padding: 4px 12px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Rest matches default state */
```

#### 42.12. Folder Color Variants

**Orange Folder:**
```css
/* Folder Icon - Bottom */
background: var(--Colors-Orange);

/* Folder Icon - Top */
outline-color: var(--Colors-Orange);
```

**Green Folder:**
```css
/* Folder Icon - Bottom */
background: var(--Colors-Green);

/* Folder Icon - Top */
outline-color: var(--Colors-Green);
```

**Blue Folder:**
```css
/* Folder Icon - Bottom */
background: var(--Colors-Blue-Blue-100);

/* Folder Icon - Top */
outline-color: var(--Colors-Blue-Blue-100);
```

**Red Folder:**
```css
/* Folder Icon - Bottom */
background: var(--Colors-Red);

/* Folder Icon - Top */
outline-color: var(--Colors-Red);
```

#### 42.13. Folder Item States Summary

| Состояние | Фон | Иконка | Текст |
|-----------|-----|--------|-------|
| **Default** | Transparent | Colored outline + opacity 0.2 fill | Text-Primary, weight 600 |
| **Hover** | Surface-03 | Same as default | Same as default |

#### 42.14. Usage Guidelines

**Context Menus:**
- Use backdrop-filter: blur(6px) for floating menus
- Separate sections with 1px solid Stroke-01 divider
- Show keyboard shortcuts only for frequently used actions (data-show-shortcut="true")
- Menu items without shortcuts should have simpler layout
- Use 12px rounded corners for menu items, 20px for menu container
- Hover state should use Surface-03 background

**Folder Navigation:**
- Use color-coded folder icons for visual categorization
- Orange, Green, Blue, Red are the standard folder colors
- Folder names should truncate with ellipsis if too long
- Search input should have active state with outline and inset shadow
- Show blinking cursor (1.5px solid black) in active search field
- Folder list should be scrollable if content overflows

**Search Input:**
- Active state: Surface-03 background, Stroke-02 outline
- Magnifying glass icon in rounded Surface-01 button
- Placeholder text in Text-Secondary color
- Cursor positioned after last character

**Interactive States:**
- Default: no background
- Hover: Surface-03 background
- Active (search): Surface-03 background + Stroke-02 outline + inset shadow

---

### 43. File & Folder Icons / List Items / Permission Selector

Иконки файлов и папок, list items с различными состояниями, селектор прав доступа.

#### 43.1. File Icon - Active State (Standalone)

Активная иконка файла с фоном и тенью.

```css
/* Icon Container - Active */
padding: 6px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape (Document) */
width: 14px;
height: 16px;
left: 3.12px;
top: 2.51px;
position: absolute;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

#### 43.2. File Icon - Default State (Standalone)

Неактивная иконка файла без фона.

```css
/* Icon Container - Default */
padding: 6px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape (Document) */
width: 14px;
height: 16px;
left: 3.12px;
top: 2.51px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

#### 43.3. Folder Icon - Active State (Standalone)

```css
/* Icon Container - Active */
padding: 6px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape (Folder) */
width: 14px;
height: 12px;
left: 2.50px;
top: 3.96px;
position: absolute;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

#### 43.4. Folder Icon - Default State (Standalone)

```css
/* Icon Container - Default */
padding: 6px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape (Folder) */
width: 14px;
height: 12px;
left: 2.50px;
top: 3.96px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

#### 43.5. File List Item - Default State

```css
/* List Item Container */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Content Container */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Icon Container */
padding: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape */
width: 14px;
height: 16px;
left: 3.12px;
top: 2.51px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* File Name */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 43.6. File List Item - Active State

```css
/* List Item Container - Active */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Content Container */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Icon Container - Active */
padding: 6px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape - Active */
width: 14px;
height: 16px;
left: 3.12px;
top: 2.51px;
position: absolute;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* File Name */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 43.7. File List Item - Hover State

```css
/* List Item Container - Hover */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Rest matches default state (icon stays Text-Secondary) */
```

#### 43.8. Folder List Item - Editing State (with Cursor)

```css
/* List Item Container - Editing */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 12px;

/* Icon Container */
padding: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Folder Icon - Bottom Part */
width: 16px;
height: 6px;
left: 2px;
top: 10px;
position: absolute;
opacity: 0.2;
background: #8B5CF6; /* violet-600 */

/* Folder Icon - Top Part */
width: 16px;
height: 12px;
left: 2.29px;
top: 3.12px;
position: absolute;
border-radius: 2px;
outline: 1.5px solid #8B5CF6; /* violet-600 */
outline-offset: -0.75px;

/* Text Container */
flex: 1;
height: 16px;
padding: 2px 0px;
display: flex;
justify-content: start;
align-items: center;
gap: 1px;

/* Folder Name */
opacity: 0.5;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Cursor (Blinking Line) */
width: 0px;
height: 12px;
left: 48px;
top: 14px;
position: absolute;
outline: 1.5px solid black;
outline-offset: -0.75px;
```

#### 43.9. Folder List Item - Pressed/Editing State (with Inset Shadow)

```css
/* List Item Container - Pressed */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 0px 3px 0px rgba(18,18,18,0.08);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 12px;

/* Icon Container */
padding: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Folder Icon - Bottom Part */
width: 16px;
height: 6px;
left: 2px;
top: 10px;
position: absolute;
opacity: 0.2;
background: #8B5CF6; /* violet-600 */

/* Folder Icon - Top Part */
width: 16px;
height: 12px;
left: 2.29px;
top: 3.12px;
position: absolute;
border-radius: 2px;
outline: 1.5px solid #8B5CF6; /* violet-600 */
outline-offset: -0.75px;

/* Text Container with Cursor */
flex: 1;
height: 16px;
padding: 2px 0px;
display: flex;
justify-content: start;
align-items: center;
gap: 0px;

/* Edited Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Cursor (Inline) */
width: 0px;
height: 12px;
outline: 1.5px solid black;
outline-offset: -0.75px;
```

#### 43.10. Permission Selector Button - Default State

```css
/* Permission Button - Default */
width: 96px;
height: 32px;
padding: 8px 12px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

#### 43.11. Permission Selector Button - Hover State

```css
/* Permission Button - Hover */
width: 96px;
height: 32px;
padding: 8px 12px;
background: var(--Surface-03);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

#### 43.12. Permission Dropdown Menu

```css
/* Dropdown Container */
width: 96px;
padding: 4px;
background: var(--Surface-01);
border-radius: 12px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: center;

/* Permission Item - Hover */
width: 96px;
height: 32px;
padding: 8px 12px;
background: var(--Surface-03);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Permission Item - Default */
width: 96px;
height: 32px;
padding: 8px 12px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Item Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

#### 43.13. List Item States Summary

| Состояние | Фон | Outline | Icon Container | Icon Color | Text Color | Inset Shadow |
|-----------|-----|---------|----------------|------------|------------|--------------|
| **Default** | Transparent | None | Transparent | Text-Secondary | Text-Primary | None |
| **Hover** | Surface-03 | None | Transparent | Text-Secondary | Text-Primary | None |
| **Active** | Surface-03 | 1px Stroke-01 | Surface-01 + shadow | Text-Primary | Text-Primary | None |
| **Editing** | Surface-03 | 1px Stroke-01 | Transparent | Colored (violet) | Text-Secondary 50% opacity | None |
| **Pressed** | Surface-03 | 1px Stroke-01 | Transparent | Colored (violet) | Text-Primary | inset 0px 0px 3px rgba(18,18,18,0.08) |

#### 43.14. Icon Variants

**File Icon (Document):**
- Width: 14px, Height: 16px
- Outline: 1.5px solid
- Position: left 3.12px, top 2.51px

**Folder Icon (Square variant):**
- Width: 14px, Height: 12px
- Outline: 1.5px solid
- Position: left 2.50px, top 3.96px

**Folder Icon (Colored variant with fill):**
- Top Part: 16px × 12px with colored outline
- Bottom Part: 16px × 6px with 20% opacity fill
- Colors: violet-600 (#8B5CF6), or any folder color

#### 43.15. Usage Guidelines

**File/Folder List Items:**
- Default state: no background, icon in Text-Secondary
- Hover state: Surface-03 background, icon stays Text-Secondary
- Active state: Surface-03 background + Stroke-01 outline + icon in elevated container with Text-Primary color
- Editing state: outline appears, cursor visible, text has reduced opacity
- Pressed/typing state: inset shadow appears, text returns to full opacity

**Icon Containers:**
- Default/Hover: no background or shadow
- Active: Surface-01 background + 4px shadow + 8px border-radius
- Always 6px padding for icon containers

**Permission Selector:**
- Two states: can view, can edit (or custom permissions)
- Default: Surface-01 background
- Hover: Surface-03 background
- Always has 4px shadow and 8px border-radius
- Dropdown uses same styling as context menus (backdrop blur, multi-layer shadows)

**Text Editing:**
- Show cursor (1.5px solid black) when editing
- Reduce text opacity to 50% in initial editing state
- Full opacity when typing (pressed state)
- Add inset shadow to indicate active typing

**Interactive States:**
- Cursor should blink at insertion point
- Text should truncate with ellipsis if too long
- Folder names can be inline-edited with click
- File icons change from Secondary to Primary when active

---

### 44. Dropdown Menus with Sections / List Menus

Выпадающие меню с секциями, иконками, клавиатурными сокращениями и различные типы popup меню.

#### 44.1. Dropdown Menu Container (with backdrop blur)

```css
/* Menu Container */
width: 176px;
background: var(--Shade1-100);
border-radius: 16px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;
```

#### 44.2. Menu Section

```css
/* Section Container */
width: 100%;
padding: 8px;
position: relative;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
```

#### 44.3. Menu Item - Active State (with hidden icon & shortcut)

```css
/* Menu Item - Active */
width: 100%;
height: 36px;
padding: 6px 8px 6px 6px;
border-radius: 10px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Content Container */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Icon Container (visible on active) */
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Icon Shape (Folder) */
width: 10px;
height: 8px;
left: 3px;
top: 4px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Keyboard Shortcut Badge (hidden by default - opacity: 0) */
width: 32px;
padding: 2px 6px;
opacity: 0;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.08),
  inset 0px -0.75px 0.5px 0px rgba(0,0,0,0.25),
  inset 0px 0.75px 0px 0px rgba(252,252,252,1.00);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Shortcut Text */
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: center;
color: var(--Text-Secondary);
```

#### 44.4. Menu Item - Hover State

```css
/* Menu Item - Hover */
width: 100%;
height: 36px;
padding: 6px 8px 6px 6px;
background: var(--Surface-03);
border-radius: 10px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Content Container */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Icon Container (hidden - opacity: 0) */
padding: 4px;
opacity: 0;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Icon Shape */
width: 10px;
height: 8px;
left: 3px;
top: 4px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Keyboard Shortcut Badge (hidden - opacity: 0) */
width: 32px;
padding: 2px 6px;
opacity: 0;
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.08),
  inset 0px -0.75px 0.5px 0px rgba(0,0,0,0.25),
  inset 0px 0.75px 0px 0px rgba(252,252,252,1.00);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;
```

#### 44.5. Menu Item - Default State

```css
/* Menu Item - Default */
width: 100%;
height: 36px;
padding: 6px 8px 6px 6px;
border-radius: 10px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Content Container */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Icon Container (hidden - opacity: 0) */
padding: 4px;
opacity: 0;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Keyboard Shortcut Badge (hidden - opacity: 0) */
opacity: 0;
```

#### 44.6. Section Divider

```css
/* Divider Section */
width: 100%;
padding: 8px;
border-top: 1px solid var(--Stroke-01);
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
```

#### 44.7. Popup Menu Container (elevated style with inset border)

```css
/* Popup Container */
width: 208px;
padding: 8px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 4px 10px 0px rgba(0,0,0,0.06),
  0px 18px 18px 0px rgba(0,0,0,0.05),
  0px 39px 24px 0px rgba(0,0,0,0.03),
  0px 70px 28px 0px rgba(0,0,0,0.01),
  0px 110px 31px 0px rgba(0,0,0,0.00),
  inset 0px 0px 0px 2px rgba(255,255,255,1.00);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;
```

#### 44.8. Single-line Menu Item with Icon - Default

```css
/* Item Container */
width: 192px;
height: 40px;
padding: 8px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 10px;

/* Icon Container */
padding: 2px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape (Image) */
width: 14px;
height: 14px;
left: 3.12px;
top: 3.12px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Icon Shape (Document) */
width: 14px;
height: 16px;
left: 3.12px;
top: 2.51px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Icon Shape (File) */
width: 12px;
height: 16px;
left: 3.96px;
top: 2.29px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Text */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

#### 44.9. Two-line Menu Item - Default

```css
/* Item Container */
width: 100%;
padding: 12px;
border-radius: 12px;
display: flex;
flex-direction: column;
justify-content: center;
align-items: start;
gap: 4px;

/* Title */
width: 100%;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Subtitle */
width: 100%;
opacity: 0.7;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 44.10. Two-line Menu Item - Hover

```css
/* Item Container - Hover */
width: 100%;
padding: 12px;
background: var(--Surface-03);
border-radius: 12px;
display: flex;
flex-direction: column;
justify-content: center;
align-items: start;
gap: 4px;

/* Rest matches default state */
```

#### 44.11. Menu Item States Summary

| Состояние | Фон | Icon Opacity | Shortcut Opacity | Padding |
|-----------|-----|--------------|------------------|---------|
| **Default** | Transparent | 0 (hidden) | 0 (hidden) | 6px 8px 6px 6px |
| **Hover** | Surface-03 | 0 (hidden) | 0 (hidden) | 6px 8px 6px 6px |
| **Active** | Transparent | 1 (visible) | 0 (hidden) | 6px 8px 6px 6px |

#### 44.12. Icon Types in Menus

**Folder Icon:**
- Width: 10px, Height: 8px
- Position: left 3px, top 4px
- Outline: 1.5px solid Text-Secondary

**Image Icon (Square):**
- Width: 14px, Height: 14px
- Position: left 3.12px, top 3.12px
- Outline: 1.5px solid Text-Secondary

**Document Icon:**
- Width: 14px, Height: 16px
- Position: left 3.12px, top 2.51px
- Outline: 1.5px solid Text-Secondary

**File Icon (Narrow):**
- Width: 12px, Height: 16px
- Position: left 3.96px, top 2.29px
- Outline: 1.5px solid Text-Secondary

#### 44.13. Usage Guidelines

**Dropdown Menus with Sections:**
- Use backdrop-filter: blur(6px) for floating menus
- Divide sections with border-top: 1px solid Stroke-01
- Icons are hidden by default (opacity: 0), visible only on active state
- Keyboard shortcuts hidden by default (opacity: 0)
- Show icons only for visual feedback on active state, not on hover
- 16px border-radius for menu container
- 10px border-radius for menu items

**Popup Menus (Elevated Style):**
- Use Surface-01 background (not Shade1-100)
- Add inset 2px white border for elevation effect
- Use Stroke-02 for outline (stronger than Stroke-01)
- 20px border-radius for container
- 12px border-radius for items
- Multi-layer shadows for elevation

**Single-line Items:**
- Use with icons for different file types
- Icon padding: 2px
- Item padding: 8px
- Height: 40px
- Gap between icon and text: 10px

**Two-line Items:**
- Padding: 12px
- Title in Text-Primary, weight 500
- Subtitle in Text-Secondary with 70% opacity
- Subtitle truncates with ellipsis
- Gap between lines: 4px
- Hover state adds Surface-03 background

**Interactive Behavior:**
- Icons appear only when item becomes active
- Shortcuts remain hidden (can be shown on hover if needed)
- Hover adds background but keeps icon hidden
- Use overflow: hidden and text-overflow: ellipsis for long text

**Menu Container Variations:**
- **Backdrop blur style**: Shade1-100 + blur(6px) + lighter shadows
- **Elevated style**: Surface-01 + inset white border + stronger shadows + no blur

---

### 45. Navigation Menu with Icons / Tree List / Prompt Suggestions

Навигационные меню с иконками, древовидные списки с chevron индикаторами и prompt suggestions.

#### 45.1. Folder/File List Item - Collapsed (with chevron)

```css
/* List Item Container */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Icon Container (Thumbnail) */
width: 32px;
height: 32px;
position: relative;

/* Folder Thumbnail - Collapsed */
width: 16px;
height: 20px;
left: 16px;
top: -6px;
position: absolute;
border-radius: 8px;
outline: 1.5px solid var(--Shade-4-100);
outline-offset: -0.75px;

/* Folder Name */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 45.2. Folder/File List Item - Expanded (with chevron)

```css
/* List Item Container */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Icon Container (Thumbnail) */
width: 32px;
height: 32px;
position: relative;

/* Folder Thumbnail - Expanded */
width: 16px;
height: 48px;
left: 16px;
top: -35px;
position: absolute;
border-radius: 8px;
outline: 1.5px solid var(--Shade-4-100);
outline-offset: -0.75px;

/* Folder Name */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 45.3. Folder List Item - Collapsed with Chevron Icon

```css
/* List Item Container */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Thumbnail Container */
width: 32px;
height: 32px;
position: relative;

/* Folder Thumbnail */
width: 16px;
height: 20px;
left: 16px;
top: -6px;
position: absolute;
border-radius: 8px;
outline: 1.5px solid var(--Shade-4-100);
outline-offset: -0.75px;

/* Folder Name */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Chevron Icon (Right) */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Chevron Shape */
width: 4px;
height: 8px;
left: 5.71px;
top: 4.04px;
position: absolute;
background: var(--Text-Secondary);
```

#### 45.4. Folder List Item - Expanded with Chevron Icon

```css
/* List Item Container */
width: 176px;
height: 40px;
padding: 4px 12px 4px 4px;
border-radius: 12px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 12px;

/* Thumbnail Container */
width: 32px;
height: 32px;
position: relative;

/* Folder Thumbnail - Expanded */
width: 16px;
height: 48px;
left: 16px;
top: -35px;
position: absolute;
border-radius: 8px;
outline: 1.5px solid var(--Shade-4-100);
outline-offset: -0.75px;

/* Folder Name */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Chevron Icon (Down) */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Chevron Shape */
width: 4px;
height: 8px;
left: 5.71px;
top: 4.04px;
position: absolute;
background: var(--Text-Secondary);
```

#### 45.5. Navigation Menu Container

```css
/* Menu Container */
width: 224px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid rgb(229, 229, 229); /* neutral-200 */
outline-offset: -1px;
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;
```

#### 45.6. Navigation Section

```css
/* Section Container */
width: 100%;
padding: 8px;
position: relative;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
```

#### 45.7. Navigation Menu Item - Default State

```css
/* Menu Item Container */
width: 208px;
height: 40px;
padding: 8px;
border-radius: 12px;
outline: 1px solid transparent;
outline-offset: -1px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Icon Container */
width: 24px;
height: 24px;
position: relative;

/* Icon (20x20) */
width: 20px;
height: 20px;
left: 2px;
top: 2px;
position: absolute;
overflow: hidden;

/* Icon Shape - User */
width: 12px;
height: 14px;
left: 4.07px;
top: 2.29px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Icon Shape - Inbox */
width: 20px;
height: 14px;
left: 0.83px;
top: 3.12px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Icon Shape - Lightbulb */
width: 14px;
height: 12px;
left: 3.12px;
top: 4.79px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Icon Shape - Settings */
width: 16px;
height: 10px;
left: 1.46px;
top: 4.79px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Icon Shape - Info Circle */
width: 16px;
height: 16px;
left: 2.29px;
top: 2.29px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Icon Shape - Logout */
width: 16px;
height: 12px;
left: 2.29px;
top: 3.96px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Menu Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
```

#### 45.8. Navigation Menu Item - Active State

```css
/* Menu Item Container - Active */
width: 208px;
height: 40px;
padding: 8px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid transparent;
outline-offset: -1px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 12px;

/* Icon Container */
width: 24px;
height: 24px;
position: relative;

/* Icon (20x20) */
width: 20px;
height: 20px;
left: 2px;
top: 2px;
position: absolute;
overflow: hidden;

/* Icon Shape - Active */
width: 14px;
height: 12px;
left: 3.12px;
top: 4.79px;
position: absolute;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Menu Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
```

#### 45.9. Navigation Section Divider

```css
/* Section Divider */
width: 100%;
padding: 8px;
border-top: 1px solid rgb(244, 244, 245); /* zinc-100 */
display: flex;
flex-direction: column;
justify-start: start;
align-items: start;
gap: 8px;
```

#### 45.10. Menu Item - Active with Background

```css
/* Menu Item - Active */
width: 208px;
height: 40px;
padding: 8px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid transparent;
outline-offset: -1px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 12px;

/* Icon Shape */
outline-color: var(--Text-Primary);
```

#### 45.11. Menu Item - Focus State (with Stroke-02 outline)

```css
/* Menu Item - Focus */
width: 208px;
height: 40px;
padding: 8px;
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 12px;

/* Icon Shape */
outline-color: var(--Text-Secondary);
```

#### 45.12. Menu Item - Default with Outline

```css
/* Menu Item - Default (with visible outline) */
width: 208px;
height: 40px;
padding: 8px;
border-radius: 12px;
outline: 1px solid transparent;
outline-offset: -1px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 12px;
```

#### 45.13. Prompt Suggestion - Default State

```css
/* Suggestion Container */
width: 518px;
height: auto;
padding: 12px;
border-radius: 10px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Suggestion Text */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 45.14. Prompt Suggestion - Active/Focus State

```css
/* Suggestion Container - Active */
width: 518px;
height: auto;
padding: 12px;
background: var(--Surface-02);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
justify-start: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Suggestion Text */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 45.15. Navigation Menu States Summary

| Состояние | Фон | Outline | Icon Color | Text Weight |
|-----------|-----|---------|------------|-------------|
| **Default** | Transparent | 1px transparent | Text-Secondary | 600 |
| **Active** | Surface-03 | 1px transparent | Text-Primary | 600 |
| **Focus** | Transparent | 1px Stroke-02 | Text-Secondary | 600 |

#### 45.16. Folder Thumbnail States

| Состояние | Thumbnail Height | Text Color | Chevron |
|-----------|------------------|------------|---------|
| **Collapsed** | 20px (top: -6px) | Text-Secondary | Right (4×8px) |
| **Expanded** | 48px (top: -35px) | Text-Primary | Down (4×8px) |
| **With Chevron (Collapsed)** | 20px | Text-Primary | Right (visible) |
| **With Chevron (Expanded)** | 48px | Text-Primary | Down (visible) |

#### 45.17. Icon Types in Navigation

**User Icon:**
- Width: 12px, Height: 14px
- Position: left 4.07px, top 2.29px

**Inbox Icon:**
- Width: 20px, Height: 14px
- Position: left 0.83px, top 3.12px

**Lightbulb Icon:**
- Width: 14px, Height: 12px
- Position: left 3.12px, top 4.79px

**Settings Icon:**
- Width: 16px, Height: 10px
- Position: left 1.46px, top 4.79px

**Info Circle Icon:**
- Width: 16px, Height: 16px
- Position: left 2.29px, top 2.29px

**Logout Icon:**
- Width: 16px, Height: 12px
- Position: left 2.29px, top 3.96px

#### 45.18. Usage Guidelines

**Navigation Menu:**
- Use Surface-01 background for menu container
- Icon size: 20×20px in 24×24px container (2px offset)
- Default state: transparent outline, icon in Text-Secondary
- Active state: Surface-03 background, icon in Text-Primary
- Focus state: Stroke-02 outline, icon in Text-Secondary
- Text weight: 600 (semibold) for all states
- Section divider: 1px solid zinc-100
- Menu item height: 40px, padding: 8px, gap: 12px

**Folder Tree List:**
- Collapsed: thumbnail 20px height, positioned at top: -6px
- Expanded: thumbnail 48px height, positioned at top: -35px
- Chevron indicates expand/collapse state
- Chevron size: 4×8px in 16×16px container
- Text color changes: Text-Secondary (collapsed) → Text-Primary (expanded/with chevron)
- Thumbnail outline: 1.5px solid Shade-4-100

**Prompt Suggestions:**
- Default: transparent background, no outline
- Active/Focus: Surface-02 background + Stroke-01 outline
- Text: font-weight 400 (normal), not semibold
- Truncate with ellipsis for long prompts
- Padding: 12px, border-radius: 10px
- Full width of container

**Interactive States:**
- Navigation items change icon color on active
- Folder items expand/collapse on click
- Chevron rotates to indicate state
- Prompt suggestions highlight on hover/focus
- All text truncates with ellipsis

**Visual Hierarchy:**
- Navigation uses semibold text (600)
- Prompts use normal text (400)
- Active states use colored icons (Text-Primary vs Text-Secondary)
- Focus states use stronger outline (Stroke-02)

---

## Паттерны

### Dashboard Layouts

#### Grid Dashboard

- **Grid:** 12-column grid, gap 24px
- **Card Spacing:** `var(--space-6)` (24px)
- **Responsive:**
  - Desktop: 3-4 columns
  - Tablet: 2 columns
  - Mobile: 1 column

#### Sidebar + Content

- **Sidebar Width:** 240px (fixed)
- **Content Area:** `calc(100% - 240px)`
- **Gap:** `var(--space-6)` (24px)
- **Responsive:** Collapsible sidebar on mobile

---

### Form Patterns

#### Single Column Form

- **Max Width:** 480px
- **Field Spacing:** `var(--space-4)` (16px)
- **Button Group:** Aligned right, gap 12px
- **Layout:** Centered

#### Multi Column Form

- **Grid:** 2 columns, gap 24px
- **Full Width Fields:** Span both columns for textarea, submit buttons
- **Responsive:** Stack to single column on mobile

#### Wizard / Stepper Form

**Steps Indicator:**
- Horizontal on desktop, vertical on mobile
- Active step highlighted

**Content Area:**
- Max width 600px, centered

**Navigation:**
- Previous/Next buttons at bottom
- Progress indicator

**Progress:**
- Linear progress bar showing completion %

---

### Data Visualization

#### Dashboard Card with Chart

**Header:**
- **Title:** Font size 18px, weight 600
- **Subtitle:** Font size 14px, color secondary
- **Actions:** Dropdown or icon buttons aligned right

**Chart Area:**
- Padding: 24px
- Min height: 300px

**Footer:**
- Legend or summary stats
- Border top: 1px solid border-primary

#### Table with Filters

**Filter Bar:**
- **Height:** 56px
- **Background:** `var(--color-bg-secondary)`
- **Padding:** `12px 16px`
- **Border Bottom:** `1px solid var(--color-border-primary)`

**Table:**
- Scrollable if overflow

**Pagination:**
- Aligned right, showing page numbers and totals

---

## Состояния

### Interactive States

| Состояние | Описание | Визуальное представление |
|-----------|----------|--------------------------|
| **Default** | Начальное состояние элемента | Базовые стили |
| **Hover** | Наведение курсора | `opacity: 0.9` или изменение фона |
| **Active/Focus** | Клик или фокус | Border highlight, shadow |
| **Disabled** | Неактивный элемент | `opacity: 0.5; cursor: not-allowed` |
| **Loading** | Процесс загрузки | Spinner или skeleton |
| **Error** | Ошибка валидации | Красная граница, сообщение об ошибке |
| **Success** | Успешное действие | Зеленая граница или иконка |

---

## Иконки

### Icon System

- **Library:** Lucide Icons / Heroicons / Feather Icons
- **Sizes:**
  - **XS:** 12px
  - **SM:** 16px
  - **Base:** 20px
  - **MD:** 24px
  - **LG:** 32px
  - **XL:** 48px
- **Stroke Width:** 2px
- **Style:** Outline (primary), Filled (for specific use cases)
- **Color:** Inherit from parent text color

### Common Icons

| Название | Использование | Размер по умолчанию |
|----------|---------------|---------------------|
| **Search** | Поиск, поле ввода | 20px |
| **Close / X** | Закрытие модалов, удаление тегов | 20px |
| **Chevron Down** | Раскрывающиеся списки | 16px |
| **Arrow Right** | Навигация, ссылки | 20px |
| **Check** | Подтверждение, успех | 20px |
| **Alert Circle** | Предупреждения | 20px |
| **X Circle** | Ошибки | 20px |
| **Menu / Hamburger** | Мобильное меню | 24px |
| **User** | Профиль пользователя | 20px |
| **Settings** | Настройки | 20px |
| **Plus** | Добавление элементов | 20px |
| **Trash** | Удаление | 20px |
| **Edit / Pencil** | Редактирование | 20px |

---

## Как использовать эту дизайн-систему

### Для дизайнеров

1. **Используйте токены** из этого документа в Figma/Sketch/Adobe XD
2. **Создавайте компоненты** на основе описанных спецификаций
3. **Поддерживайте консистентность** — не отклоняйтесь от системы без согласования
4. **Документируйте изменения** — обновляйте этот файл при добавлении новых паттернов

### Для разработчиков

1. **Импортируйте CSS-переменные** в ваш проект
2. **Используйте готовые классы** или создавайте компоненты на основе токенов
3. **Следуйте именованию** переменных для легкой поддержки
4. **Тестируйте адаптивность** на всех устройствах

### Для продуктовой команды

1. **Ссылайтесь на паттерны** при создании новых фич
2. **Обеспечивайте согласованность** UX на всех платформах
3. **Предлагайте улучшения** — система должна эволюционировать с продуктом
4. **Проводите аудит** интерфейсов на соответствие дизайн-системе

---

**Версия:** 2.0.0
**Последнее обновление:** 2025-11-18
**Мейнтейнеры:** Design & Engineering Team

---

## Changelog

### Version 2.0.0 (2025-11-18)

**Добавлено:**
- Детальная спецификация кнопок (12+ вариантов)
- Состояния для всех interactive элементов
- Destructive buttons (Delete/Remove)
- Dark theme компоненты
- Icon-only buttons (4 размера)
- Toggle/Radio button groups
- Social login buttons
- Segmented controls
- Tab-style buttons
- Keyboard shortcut badges
- Command palette components
- Reaction buttons (emoji)
- Indicator badges
- Notification dots
- Checkbox & Radio controls
- Loading states
- Glass/Frosted UI effects
- Surface colors (--Surface-01, 02, 03)
- Stroke colors (--Stroke-01, 02)
- Accent colors (--Colors-Blue, Orange, Red)
- Icon sizes reference table
- 25 компонентов с детальными спецификациями
