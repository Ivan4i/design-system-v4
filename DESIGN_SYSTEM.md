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

### 46. Notification Panel / Activity Feed

Панель уведомлений с аватарами, badge иконками, различными типами уведомлений и action buttons.

#### 46.1. Notification Panel Container

```css
/* Panel Container */
width: 384px;
height: 800px;
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
align-items: center;
overflow: hidden;
```

#### 46.2. Panel Header

```css
/* Header Container */
width: 100%;
padding: 16px 20px;
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Title */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 14px;
font-weight: 600;
line-height: 20px;
color: black;

/* Tab Container */
display: flex;
justify-content: start;
align-items: center;
gap: 4px;
```

#### 46.3. Tab Button - Active State

```css
/* Tab - Active */
padding: 4px 8px;
background: var(--Surface-03);
border-radius: 10px;
display: inline-flex;
flex-direction: column;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Tab Text */
width: 100%;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: center;
color: var(--Text-Primary);
```

#### 46.4. Tab Button - Default State

```css
/* Tab - Default */
padding: 4px 8px;
border-radius: 10px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Tab Text */
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: center;
color: var(--Text-Secondary);
```

#### 46.5. Notification Item - Unread with Comment

```css
/* Item Container - Unread */
width: 384px;
padding: 20px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: start;
align-items: start;
gap: 16px;

/* Avatar Container */
width: 48px;
height: 48px;
position: relative;

/* Avatar Image */
width: 48px;
height: 48px;
left: 0;
top: 0;
position: absolute;
border-radius: 32px;

/* Badge Icon Container (Comment) */
width: 16px;
height: 16px;
left: 32px;
top: 32px;
position: absolute;
background: #8B5CF6; /* violet-500 */
border-radius: 16px;
outline: 2px solid var(--Surface-01);
outline-offset: 0px;
overflow: hidden;

/* Badge Icon */
width: 12px;
height: 12px;
left: 3px;
top: 3px;
position: absolute;
overflow: hidden;

/* Icon Shape (Comment Bubble) */
width: 8px;
height: 10px;
left: 1.50px;
top: 1.50px;
position: absolute;
background: var(--Surface-01);
```

#### 46.6. Content Area

```css
/* Content Container */
width: 288px;
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 8px;

/* Header Section */
width: 100%;
height: 40px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 8px;
```

#### 46.7. Content Header Row

```css
/* Header Row */
width: 100%;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Left Side Container */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Username/Title */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);

/* Timestamp */
opacity: 0.5;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);

/* Unread Indicator Dot */
width: 8px;
height: 8px;
background: var(--Colors-Green);
border-radius: 50%;
```

#### 46.8. Content Description Row

```css
/* Description Row */
width: 100%;
justify-start: start;

/* Mixed Text (Normal + Secondary + Semibold) */
/* Example: "Commented on Classic Car in Studio" */

/* Action Text (Normal) */
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Connector Text (Secondary) */
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 400;
line-height: 16px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

/* Target Text (Semibold) */
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

#### 46.9. Comment Text / Prompt Text

```css
/* Comment/Prompt Container */
width: 100%;
opacity: 0.8;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 400;
line-height: 20px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
```

#### 46.10. Notification Item - Read (without unread dot)

```css
/* Item Container - Read */
width: 384px;
padding: 20px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-start: start;
align-items: center;
gap: 16px;

/* No unread indicator dot */
/* Rest matches unread state */
```

#### 46.11. Notification with Invite Actions

```css
/* Content Container with Actions */
width: 288px;
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 16px;

/* Header Section (same as above) */
/* ... */

/* Action Buttons Container */
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Decline Button */
padding: 8px 20px;
background: linear-gradient(180deg, rgb(229, 229, 229) 0%, rgb(229, 229, 229) 100%);
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Decline Text */
font-family: 'Inter', sans-serif;
font-size: 14px;
font-weight: 600;
line-height: 20px;
text-align: center;
color: var(--Text-Primary);

/* Accept Button */
padding: 8px 20px;
background: linear-gradient(180deg, var(--Shade-7-100) 0%, var(--Shade-8-100) 100%);
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(51,51,51,1.00),
  0px 2px 4px -1px rgba(13,13,13,0.50),
  inset 0px -1px 1.2px 0.35px rgba(18,18,18,1.00),
  inset 0px 0.5px 1px 0px rgba(255,255,255,0.15);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Accept Text */
font-family: 'Inter', sans-serif;
font-size: 14px;
font-weight: 600;
line-height: 20px;
text-align: center;
color: rgb(250, 250, 250); /* neutral-50 */
```

#### 46.12. Badge Icon Types

**Comment Badge (violet-500):**
```css
background: #8B5CF6;
/* Icon: Comment bubble 8×10px */
```

**3D Badge (yellow-600):**
```css
background: #CA8A04;
/* Icon: 3D cube 8×10px */
```

**Invite Badge (Colors-Green):**
```css
background: var(--Colors-Green);
/* Icon: User add 8×8px circle outline */
```

**Like Badge (Colors-Red):**
```css
background: var(--Colors-Red);
/* Icon: Heart 10×10px */
```

**Video Badge (sky-500):**
```css
background: #0EA5E9;
/* Icon: Play triangle 10×12px */
```

#### 46.13. Fade Gradient Overlay

```css
/* Bottom Fade Gradient */
width: 384px;
height: 96px;
left: 0;
top: 696px;
position: absolute;
background: linear-gradient(180deg, rgba(250, 250, 250, 0) 0%, rgba(250, 250, 250, 1) 100%);
```

#### 46.14. Notification Types Summary

| Type | Badge Color | Icon | Unread Dot | Actions |
|------|-------------|------|------------|---------|
| **Comment** | violet-500 | Comment bubble | Green dot | None |
| **3D Generated** | yellow-600 | 3D cube | Green dot | None |
| **Invite** | Colors-Green | User add | Green dot | Decline/Accept |
| **Like** | Colors-Red | Heart | Optional | None |
| **Video** | sky-500 | Play | Optional | None |

#### 46.15. Content Layout Variations

**With Comment/Prompt (3 lines):**
- Header row: username + timestamp + unread dot
- Description row: action text + connector + target
- Comment text: 2-line clamp, 80% opacity

**Simple Notification (2 lines):**
- Header row: title + timestamp + unread dot
- Description row: single line info

**With Actions (4 lines):**
- Header row: title + timestamp + unread dot
- Description row: action text + connector + target
- Action buttons: Decline (light) + Accept (dark)
- Gap: 16px between content and actions

#### 46.16. Usage Guidelines

**Notification Panel:**
- Use Shade1-100 background for glassmorphism effect
- Backdrop blur: 6px for floating panel effect
- Panel width: 384px (fixed)
- Panel max height: 800px (scrollable)
- Border-radius: 20px for container
- Outline: 1px solid Stroke-01

**Header:**
- Title: 14px semibold, black color
- Tabs: "All" (active) and "Unread"
- Active tab: Surface-03 background
- Default tab: transparent, Text-Secondary

**Notification Items:**
- Padding: 20px
- Border-top: 1px solid Stroke-01 for all items
- Avatar: 48×48px, rounded-32px
- Badge: 16×16px, positioned at (32px, 32px)
- Badge outline: 2px solid Surface-01
- Content width: 288px (384px - 48px avatar - 20px padding × 2 - 16px gap)

**Avatar Badge:**
- Size: 16×16px circle
- Position: bottom-right corner (left: 32px, top: 32px)
- Outline: 2px solid Surface-01
- Icon: 12×12px container with 8-10px shapes
- Border-radius: 16px (full circle)

**Unread Indicator:**
- Size: 8×8px circle
- Color: Colors-Green
- Position: top-right of header row
- Only show for unread notifications

**Text Styles:**
- Username/Title: 12px semibold, Text-Primary
- Timestamp: 12px medium, Text-Secondary, 50% opacity
- Action text: 12px normal, Text-Primary
- Connector text: 12px normal, Text-Secondary
- Target text: 12px semibold, Text-Primary
- Comment/Prompt: 12px normal, Text-Secondary, 80% opacity, line-clamp: 2

**Action Buttons:**
- Decline: light gray gradient, Text-Primary
- Accept: dark gradient, neutral-50 text
- Padding: 8px 20px (small variant: 6px 20px)
- Font: 14px semibold
- Border-radius: 10px
- Gap between buttons: 8px

**Badge Colors by Type:**
- Comment: violet-500 (#8B5CF6)
- 3D: yellow-600 (#CA8A04)
- Invite: Colors-Green
- Like: Colors-Red
- Video: sky-500 (#0EA5E9)

**Fade Overlay:**
- Position: absolute at bottom
- Height: 96px
- Gradient: transparent → neutral-50
- Indicates more content below

**Interactive States:**
- Tabs toggle between All/Unread
- Action buttons have hover/pressed states
- Items can be clicked to view details
- Unread items can be marked as read
- Scrollable content with fade indicator

---

### 47. Image Variations Panel / Image Detail Card

Панель вариаций изображений с grid layout и карточка детальной информации об изображении.

#### 47.1. Variations Panel Container

```css
/* Panel Container */
width: 208px;
background: rgba(var(--Shade1-95), 0.95);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;
```

#### 47.2. Variations Panel Header

```css
/* Header Container */
width: 100%;
padding: 12px 16px;
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Title */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);

/* Right Side Container */
display: flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Counter Text */
text-align: right;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);

/* Close/More Icon Button */
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

/* Icon Shape (X or dots) */
width: 6px;
height: 6px;
left: 5.17px;
top: 5.17px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

#### 47.3. Variations Grid Container

```css
/* Grid Container */
width: 100%;
padding: 0px 16px 16px 16px;
display: inline-flex;
justify-content: start;
align-items: start;
gap: 8px;
flex-wrap: wrap;
align-content: start;
```

#### 47.4. Variation Thumbnail - Default State

```css
/* Thumbnail - Default */
flex: 1;
height: 80px;
min-width: 64px;
padding: 4px;
border-radius: 12px;
```

#### 47.5. Variation Thumbnail - Hover State

```css
/* Thumbnail - Hover */
flex: 1;
height: 80px;
min-width: 64px;
padding: 4px;
border-radius: 12px;
box-shadow: inset 0px 0px 0px 3px rgba(252,252,252,1.00);
border: 1.5px solid var(--Shade-6-100);
```

#### 47.6. Image Detail Card Container

```css
/* Card Container */
padding: 8px;
background: var(--Surface-01);
border-radius: 32px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: center;
align-items: start;
overflow: hidden;
```

#### 47.7. Image Preview Container

```css
/* Preview Container */
width: 384px;
height: 384px;
min-width: 256px;
min-height: 256px;
padding: 24px;
background: var(--Surface-02);
border-radius: 24px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
overflow: hidden;

/* Image Wrapper */
width: 100%;
height: 320px;
position: relative;
overflow: hidden;

/* Image */
width: 332px;
height: 332px;
left: 0;
top: 0;
position: absolute;
```

#### 47.8. Card Content Section

```css
/* Content Container */
width: 100%;
padding: 16px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 24px;
```

#### 47.9. Card Info Section

```css
/* Info Container */
width: 100%;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 12px;

/* Title */
width: 100%;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 18px;
font-weight: 400;
line-height: 28px;
color: var(--Text-Primary);
```

#### 47.10. Metadata Row

```css
/* Metadata Container */
display: inline-flex;
justify-content: start;
align-items: center;
gap: 16px;

/* Author Section */
display: flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Avatar */
width: 20px;
height: 20px;
position: relative;
border-radius: 32px;

/* Username */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 600;
line-height: 16px;
color: var(--Text-Primary);

/* Date Section */
display: flex;
justify-content: start;
align-items: center;
gap: 4px;

/* Calendar Icon Container */
width: 20px;
height: 20px;
position: relative;
border-radius: 32px;
overflow: hidden;

/* Calendar Icon */
width: 16px;
height: 16px;
left: 2px;
top: 2px;
position: absolute;
opacity: 0.7;
overflow: hidden;

/* Icon Shape */
width: 12px;
height: 12px;
left: 1.83px;
top: 1.83px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Date Text */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
```

#### 47.11. Action Buttons Row

```css
/* Actions Container */
width: 100%;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Icon Button */
width: 40px;
height: 40px;
padding: 8px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: center;
align-items: center;
gap: 12px;
overflow: hidden;

/* Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape (varies by action) */
width: 16px;
height: 16px;
left: 2.47px;
top: 1.25px;
position: absolute;
background: black;

/* Primary Button (Copy link) */
flex: 1;
padding: 10px 24px;
background: linear-gradient(180deg, rgb(229, 229, 229) 0%, rgb(229, 229, 229) 100%);
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
font-family: 'Inter', sans-serif;
font-size: 14px;
font-weight: 600;
line-height: 20px;
text-align: center;
color: var(--Text-Primary);
```

#### 47.12. Component Dimensions Summary

| Component | Width | Height | Border Radius | Padding |
|-----------|-------|--------|---------------|---------|
| **Variations Panel** | 208px | auto | 20px | 16px (sides), 12px (top) |
| **Variation Thumbnail** | flex: 1, min 64px | 80px | 12px | 4px |
| **Image Card** | auto (384px image) | auto | 32px | 8px |
| **Image Preview** | 384×384px (min 256×256) | - | 24px | 24px |
| **Icon Button** | 40×40px | - | 10px | 8px |
| **Copy Button** | flex: 1 | 40px | 12px | 10px 24px |

#### 47.13. Variations Grid Layout

| Breakpoint | Columns | Gap | Thumbnail Width |
|------------|---------|-----|-----------------|
| **Default (208px)** | 2 columns | 8px | ~84px (flex: 1) |
| **Wrap** | 2×2 grid | 8px | min-width: 64px |

#### 47.14. Usage Guidelines

**Variations Panel:**
- Use Shade1-95 with 95% opacity for semi-transparent background
- Backdrop blur: 6px for glassmorphism effect
- Panel width: 208px (fixed)
- Grid: 2 columns with 8px gap
- Thumbnails: flex: 1, min-width 64px, height 80px
- Default thumbnail: 4px padding, 12px border-radius
- Hover thumbnail: inset white border 3px + Shade-6-100 border 1.5px
- Counter format: "2 of 4" in Text-Secondary

**Image Detail Card:**
- Container padding: 8px
- Border-radius: 32px for outer card
- Image preview: 384×384px (responsive min 256×256)
- Preview background: Surface-02
- Preview border-radius: 24px
- Preview outline: 1px solid Stroke-01

**Card Content:**
- Padding: 16px
- Gap between sections: 24px
- Title: 18px normal weight, line-height 28px
- Author section: 20×20px avatar + username (semibold)
- Date section: calendar icon + date text (medium)

**Action Buttons:**
- Icon buttons: 40×40px, 8px padding, Stroke-02 outline
- Primary button: flex: 1, 10px 24px padding
- Gap between buttons: 8px
- Button text: 14px semibold

**Thumbnail States:**
- Default: no border, 4px padding
- Hover: inset 3px white shadow + 1.5px Shade-6-100 border
- Selected: similar to hover (can add additional styling)

**Metadata:**
- Avatar: 20×20px circle
- Calendar icon: 16×16px in 20×20px container, 70% opacity
- Username: 12px semibold, Text-Primary
- Date: 12px medium, Text-Secondary
- Gap between author and date: 16px

**Interactive States:**
- Thumbnails scale/highlight on hover
- Icon buttons have hover/active states
- Copy button has hover/pressed states
- Close button in panel header dismisses panel

**Image Preview:**
- Centered within container
- Surface-02 background for contrast
- 1px outline for definition
- Image scales to fit container
- Maintains aspect ratio

---

### 48. Settings Panel / Preferences

Панель настроек с sidebar navigation, toggle switches, dropdowns и subscription card.

#### 48.1. Settings Panel Container

```css
/* Panel Container */
background: var(--Surface-01);
border-radius: 24px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
backdrop-filter: blur(6px);
display: inline-flex;
justify-content: start;
align-items: start;
overflow: hidden;
```

#### 48.2. Sidebar Navigation

```css
/* Sidebar Container */
width: 176px;
align-self: stretch;
padding: 12px;
background: var(--Surface-01);
border-right: 1px solid var(--Stroke-01);
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 2px;
```

#### 48.3. Sidebar Item - Active State

```css
/* Item Container - Active */
width: 100%;
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
top: 2.39px;
position: absolute;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Label */
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

#### 48.4. Sidebar Item - Default State

```css
/* Item Container - Default */
width: 100%;
height: 40px;
padding: 4px 12px 4px 4px;
border-radius: 12px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 12px;

/* Icon Container - Default */
padding: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Icon Shape - Default */
outline-color: var(--Text-Secondary);

/* Label */
/* Same as active */
```

#### 48.5. Content Area

```css
/* Content Container */
width: 384px;
padding-bottom: 80px;
display: inline-flex;
flex-direction: column;
justify-content: start;
align-items: start;
```

#### 48.6. Content Header

```css
/* Header Container */
width: 100%;
padding: 16px 24px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 5px;

/* Title */
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 18px;
font-weight: 500;
line-height: 24px;
color: var(--Text-Primary);
```

#### 48.7. Settings Row - Simple (Label + Value + Edit)

```css
/* Row Container */
width: 100%;
padding: 16px 24px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Label */
width: 56px;
height: 24px;
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Value Container */
display: flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Value Text */
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Edit Icon */
width: 16px;
height: 16px;
position: relative;

/* Icon Shape */
width: 12px;
height: 12px;
left: 2px;
top: 2px;
position: absolute;
overflow: hidden;

/* Icon Detail */
width: 10px;
height: 10px;
left: 1.38px;
top: 1.41px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

#### 48.8. Settings Row - Disabled (Grayed Value)

```css
/* Value Text - Disabled */
opacity: 0.3;
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* No edit icon */
```

#### 48.9. Settings Row - Toggle Switch

```css
/* Row Container */
width: 100%;
padding: 16px 24px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Label */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

#### 48.10. Toggle Switch - ON State

```css
/* Toggle Container - ON */
width: 40px;
padding: 2px;
background: rgba(var(--Shade-9-70), 0.7);
border-radius: 24px;
box-shadow: inset 0px 1px 0.6px 0px rgba(18,18,18,0.30);
display: flex;
justify-content: flex-end;
align-items: center;
gap: 8px;
overflow: hidden;

/* Toggle Knob */
width: 16px;
height: 16px;
position: relative;
background: var(--Surface-02);
border-radius: 24px;
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px 0px rgba(0,0,0,0.25),
  inset 0px 1px 0.5px 0px rgba(255,255,255,0.82);
```

#### 48.11. Toggle Switch - OFF State

```css
/* Toggle Container - OFF */
width: 40px;
padding: 2px;
background: var(--Shade-4-100);
border-radius: 24px;
box-shadow: inset 0px 0px 1px 0.5px rgba(18,18,18,0.10);
display: flex;
justify-content: flex-start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Toggle Knob - Same as ON */
```

#### 48.12. Settings Row - Dropdown

```css
/* Row Container */
width: 100%;
padding: 16px 24px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Dropdown */
width: 128px;
padding: 10px 12px 10px 12px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
justify-content: start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Dropdown Content Container */
flex: 1;
display: flex;
justify-content: start;
align-items: center;
gap: 6px;

/* Dropdown Text */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Chevron Icon */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Chevron Shape */
width: 6px;
height: 2.39px;
left: 5.33px;
top: 6.67px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

#### 48.13. Settings Row - With Description (Avatar Upload)

```css
/* Row Container */
width: 100%;
padding: 16px 24px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-start: start;
align-items: center;
gap: 48px;

/* Description Container */
flex: 1;
display: inline-flex;
flex-direction: column;
justify-content: center;
align-items: start;
gap: 8px;

/* Label */
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Description Text */
width: 100%;
opacity: 0.8;
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);

/* Avatar */
width: 48px;
height: 48px;
position: relative;
border-radius: 32px;
```

#### 48.14. Settings Row - With Button

```css
/* Row Container */
width: 100%;
padding: 16px 24px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-start: start;
align-items: center;
gap: 48px;

/* Description Container */
flex: 1;
display: inline-flex;
flex-direction: column;
justify-content: center;
align-items: start;
gap: 8px;

/* Button */
padding: 10px 24px;
background: linear-gradient(180deg, rgb(229, 229, 229) 0%, rgb(229, 229, 229) 100%);
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
font-family: 'Inter', sans-serif;
font-size: 14px;
font-weight: 600;
line-height: 20px;
text-align: center;
color: var(--Text-Primary);
```

#### 48.15. Subscription Card Container

```css
/* Card Section */
width: 100%;
padding: 12px;
border-top: 1px solid var(--Stroke-01);
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;

/* Header Row */
width: 100%;
padding: 16px 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Header Text */
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);

/* Info Icon */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape */
width: 12px;
height: 14px;
left: 4.07px;
top: 2.29px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

#### 48.16. Pricing Card

```css
/* Card Container */
width: 100%;
border-radius: 20px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
overflow: hidden;

/* Pricing Section */
width: 100%;
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
outline-offset: -1px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 8px;
overflow: hidden;
```

#### 48.17. Price Display

```css
/* Price Container */
width: 384px;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Amount Container */
display: flex;
justify-content: start;
align-items: center;

/* Currency Symbol */
width: 20px;
height: 48px;
position: relative;

/* Symbol */
left: 2px;
top: 4px;
position: absolute;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 24px;
font-weight: 500;
line-height: 32px;
color: var(--Text-Secondary);
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;

/* Amount */
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 36px;
font-weight: 400;
line-height: 48px;
color: var(--Text-Primary);
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;

/* Period Text */
justify-center: center;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Secondary);
```

#### 48.18. Action Buttons Row (Cancel/Upgrade)

```css
/* Buttons Container */
width: 100%;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Cancel Button */
flex: 1;
padding: 10px 24px;
background: linear-gradient(180deg, rgb(229, 229, 229) 0%, rgb(229, 229, 229) 100%);
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Upgrade Button */
flex: 1;
height: 40px;
padding: 8px 20px;
background: linear-gradient(180deg, var(--Shade-7-100) 0%, var(--Shade-8-100) 100%);
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(51,51,51,1.00),
  0px 2px 4px -1px rgba(13,13,13,0.50),
  inset 0px -1px 1.2px 0.35px rgba(18,18,18,1.00),
  inset 0px 0.5px 1px 0px rgba(255,255,255,0.15);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
font-family: 'Inter', sans-serif;
font-size: 14px;
font-weight: 600;
line-height: 20px;
text-align: center;
color: rgb(250, 250, 250); /* neutral-50 */
```

#### 48.19. Feature List

```css
/* Features Container */
width: 100%;
padding: 12px;
display: flex;
flex-direction: column;
justify-content: start;
align-items: start;
gap: 8px;

/* Feature Item */
width: 100%;
display: inline-flex;
justify-content: start;
align-items: center;
gap: 8px;

/* Checkmark Icon Container */
padding: 2px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Checkmark Icon */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Checkmark Shape */
width: 10px;
height: 8px;
left: 3px;
top: 4px;
position: absolute;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Feature Text */
flex: 1;
justify-start: start;
font-family: 'Inter', sans-serif;
font-size: 12px;
font-weight: 500;
line-height: 16px;
color: var(--Text-Primary);
```

#### 48.20. Settings Row Types Summary

| Type | Left Side | Right Side | Border |
|------|-----------|------------|--------|
| **Simple** | Label (12px medium) | Value + Edit icon | Top 1px |
| **Disabled** | Label | Grayed value (30% opacity) | Top 1px |
| **Toggle** | Label | Toggle switch (40px) | Top 1px |
| **Dropdown** | Label | Dropdown (128px) | Top 1px |
| **Avatar** | Label + description | 48×48px avatar | Top 1px |
| **Button** | Label + description | Action button | Top 1px |

#### 48.21. Toggle Switch States

| State | Background | Knob Position | Shadow |
|-------|-----------|---------------|--------|
| **ON** | Shade-9-70 70% opacity | Right (justify-end) | Inset dark |
| **OFF** | Shade-4-100 | Left (justify-start) | Inset light |

#### 48.22. Usage Guidelines

**Settings Panel Layout:**
- Sidebar: 176px width, 12px padding, border-right
- Content: 384px width, 80px bottom padding
- Container border-radius: 24px
- Sidebar items gap: 2px

**Sidebar Navigation:**
- Active state: Surface-03 background + Stroke-01 outline + elevated icon
- Default state: transparent background + no icon elevation
- Icon container (active): Surface-01 + 4px shadow + 8px border-radius
- Icon size: 20×20px
- Label: 12px semibold, truncate with ellipsis
- Item height: 40px

**Content Header:**
- Padding: 16px 24px
- Title: 18px medium weight, line-height 24px
- Gap: 5px

**Settings Rows:**
- Padding: 16px 24px
- Border-top: 1px solid Stroke-01 for all rows
- Label: 12px medium weight
- Value: 12px medium weight
- Gap between description rows: 48px

**Toggle Switch:**
- Width: 40px
- Knob: 16×16px circle
- Container padding: 2px
- Border-radius: 24px (full circle)
- ON: dark background (Shade-9-70 70%), knob on right
- OFF: light background (Shade-4-100), knob on left
- Knob shadows: multi-layer for elevation

**Dropdown:**
- Width: 128px
- Padding: 10px 12px
- Background: Surface-03
- Outline: 1px solid Stroke-01
- Chevron: 6×2.39px
- Border-radius: 10px

**Subscription Card:**
- Container: 20px border-radius, Stroke-02 outline
- Pricing section: Surface-02 background, inset white shadow
- Price display: $20 (36px amount) + USD/month (12px)
- Currency symbol: 24px, Text-Secondary
- Buttons: Cancel (light) + Upgrade (dark), flex: 1 each
- Features: checkmark icon (10×8px) + text (12px medium)
- Feature items gap: 8px

**Edit Icon:**
- Size: 12×12px in 16×16px container
- Color: Text-Secondary
- Outline: 1.5px

**Disabled State:**
- Opacity: 0.3
- No edit icon
- Same text styling

**Avatar Upload:**
- Avatar: 48×48px circle
- Description: 80% opacity, Text-Secondary
- Label + description vertical gap: 8px

**Action Buttons:**
- Medium size: 10px 24px padding
- Border-radius: 12px
- Text: 14px semibold
- Light button: neutral-200 gradient
- Dark button: Shade-7 → Shade-8 gradient

**Pricing Card Features:**
- Checkmark icon: 16×16px container, 10×8px shape
- Feature text: 12px medium, Text-Primary
- Vertical gap: 8px between features
- Padding: 12px for features section

**Interactive States:**
- Sidebar items change icon color/elevation on active
- Toggle switches animate knob position
- Dropdowns expand on click
- Edit icons trigger inline editing
- Buttons have hover/pressed states

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

## 49. 3D Object Card / Report Dialog / Image Placement Variants

### 49.1 3D Object Card Container

Карточка для отображения 3D объектов с превью, метаданными и действиями.

```css
/* Card Container */
width: 256px;
padding: 8px;
background: rgba(var(--Shade1-95), 0.95);
border-radius: 24px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
gap: 8px;
overflow: hidden;
```

### 49.2 3D Object Preview Area

Область превью с центрированием изображения.

```css
/* Preview Container */
width: 100%; /* self-stretch */
height: 192px;
background: var(--Surface-03);
border-radius: 16px;
position: relative;
overflow: hidden;

/* Preview Image */
width: 192px;
height: 192px;
position: absolute;
left: 32px; /* Центрирование: (256px - 16px padding) / 2 - 96px = 32px */
top: 0;
object-fit: cover;
```

**Примечание:** Изображение смещено на 32px влево для визуального центрирования в контейнере шириной 240px (256px - 16px padding).

### 49.3 3D Object Metadata Section

Блок с заголовком и категорией объекта.

```css
/* Content Container */
padding: 8px;
display: flex;
flex-direction: column;
gap: 16px;

/* Metadata Block */
display: flex;
flex-direction: column;
gap: 4px;

/* Title */
width: 100%;
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Category Label */
width: 100%;
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
```

### 49.4 3D Object Action Buttons

Кнопки действий: иконка-кнопка и основная кнопка "Insert Object".

```css
/* Buttons Container */
width: 100%;
display: inline-flex;
justify-content: flex-end;
align-items: center;
gap: 8px;

/* Icon Button - Default */
width: 36px;
height: 36px;
padding: 8px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Icon Button - Icon Container */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Button - Icon Shape */
width: 16px;
height: 16px;
position: absolute;
left: 2.29px;
top: 2.29px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Primary Button - Default */
flex: 1;
padding: 8px 20px;
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5); /* neutral-200 */
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Primary Button - Text */
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

### 49.5 Report Dialog Container

Диалоговое окно для выбора причины репорта изображения.

```css
/* Dialog Container */
padding: 24px;
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
gap: 16px;
overflow: hidden;
```

### 49.6 Report Dialog Title

Заголовок диалога репорта.

```css
/* Title */
width: 100%;
color: #000000;
font-size: 16px;
font-weight: 600;
font-family: 'Inter';
line-height: 24px;
```

### 49.7 Report Reason Tags

Теги с причинами репорта (выбираемые опции).

```css
/* Tags Container */
display: inline-flex;
gap: 8px;

/* Reason Tag */
padding: 12px;
background: var(--Surface-03);
border-radius: 12px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;
cursor: pointer;

/* Tag Text */
color: #000000;
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;
white-space: nowrap;
```

**Доступные причины:**
- "Nudity & Sexual Content"
- "Child Exploitation"
- (могут быть добавлены другие)

### 49.8 Image Placement Variants Container

Контейнер для демонстрации различных вариантов размещения изображений.

```css
/* Variants Container */
width: 288px;
height: 459px;
border-radius: 5px;
border: 1px solid #A855F7; /* purple-500 - для демонстрации */
position: relative;
overflow: hidden;
```

**Примечание:** Граница purple-500 используется только для визуальной демонстрации в макете.

### 49.9 Image Placement Variant - Large Centered (192×192)

Вариант размещения с большим изображением 192×192px.

```css
/* Variant Card - Top */
width: 256px;
height: 192px;
position: absolute;
left: 16px;
top: 16px;
background: var(--Surface-03);
border-radius: 16px;
overflow: hidden;

/* Image - Large */
width: 192px;
height: 192px;
position: absolute;
left: 32px; /* Центрирование: (256px / 2) - (192px / 2) = 32px */
top: 0;
object-fit: cover;
```

**Центрирование:** Изображение 192×192px центрируется по горизонтали в карточке 256px.

### 49.10 Image Placement Variant - Medium Centered (128×128)

Вариант размещения с меньшим изображением 128×128px.

```css
/* Variant Card - Bottom */
width: 256px;
height: 192px;
position: absolute;
left: 16px;
top: 251px; /* Позиция второй карточки */
background: var(--Surface-03);
border-radius: 16px;
overflow: hidden;

/* Image - Medium */
width: 128px;
height: 128px;
position: absolute;
left: 64px; /* Центрирование: (256px / 2) - (128px / 2) = 64px */
top: 32px; /* Вертикальное центрирование: (192px / 2) - (128px / 2) = 32px */
object-fit: cover;
```

**Центрирование:** Изображение 128×128px центрируется как по горизонтали, так и по вертикали в карточке 256×192px.

### 49.11 Summary: 3D Object Card Specifications

| Элемент | Размер | Padding | Border Radius | Background | Особенности |
|---------|--------|---------|---------------|------------|-------------|
| Card Container | 256px | 8px | 24px | Shade1-95 95% | backdrop-blur: 6px, 5 теней |
| Preview Area | 100%×192px | - | 16px | Surface-03 | - |
| Preview Image | 192×192px | - | - | - | left: 32px (центрирование) |
| Content Block | 100% | 8px | - | - | gap: 16px |
| Metadata Block | 100% | - | - | - | gap: 4px |
| Title | 100% | - | - | Text-Primary | 14px/600, line-clamp: 1 |
| Category | 100% | - | - | Text-Secondary | 12px/500, opacity: 0.8 |
| Buttons Row | 100% | - | - | - | gap: 8px, justify: flex-end |
| Icon Button | 36×36px | 8px | 10px | - | outline: 1px Stroke-02 |
| Primary Button | flex: 1 | 8px 20px | 10px | neutral-200 gradient | 3 тени, inset highlight |

### 49.12 Summary: Report Dialog Specifications

| Элемент | Размер | Padding | Border Radius | Background | Особенности |
|---------|--------|---------|---------------|------------|-------------|
| Dialog Container | auto | 24px | 20px | Shade1-100 | backdrop-blur: 6px, outline: 1px Stroke-01 |
| Title | 100% | - | - | #000000 | 16px/600/24px |
| Tags Container | auto | - | - | - | inline-flex, gap: 8px |
| Reason Tag | auto | 12px | 12px | Surface-03 | 12px/600/16px |

### 49.13 Summary: Image Placement Variants

| Вариант | Размер изображения | Позиция | Центрирование | Card Size |
|---------|-------------------|---------|---------------|-----------|
| Large (Top) | 192×192px | left: 32px, top: 0 | Горизонтальное | 256×192px |
| Medium (Bottom) | 128×128px | left: 64px, top: 32px | Горизонтальное + вертикальное | 256×192px |

**Формула центрирования:**
- Горизонтально: `left = (container_width - image_width) / 2`
- Вертикально: `top = (container_height - image_height) / 2`

### 49.14 Usage Guidelines

**3D Object Card:**
- Используйте для отображения 3D объектов, иконок, иллюстраций в библиотеке ресурсов
- Превью всегда 192×192px с центрированием в карточке 256px
- Title должен обрезаться с ellipsis (line-clamp: 1)
- Category отображается с opacity 0.8 для визуальной иерархии
- Кнопки всегда выровнены по правому краю

**Report Dialog:**
- Используйте для модального окна репорта контента
- Теги причин должны быть интерактивными (hover/active состояния)
- Backdrop blur создает ощущение модального окна
- Outline Stroke-01 обеспечивает четкие границы на светлом фоне

**Image Placement Variants:**
- Используйте для демонстрации различных размеров изображений в одном контейнере
- Всегда центрируйте изображения математически
- Поддерживайте aspect ratio 1:1 для 3D объектов
- Меньшие изображения (128×128) центрируются как горизонтально, так и вертикально

---

## 50. Export Panel / Media Type Tabs / Export Settings

### 50.1 Export Panel Container

Панель экспорта с боковой навигацией и настройками для разных типов медиа.

```css
/* Panel Container */
width: 549px;
height: 320px;
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
overflow: hidden;
```

### 50.2 Sidebar Navigation

Боковая навигация с табами типов медиа (Images, Video, 3D Object).

```css
/* Sidebar Container */
width: 144px; /* w-36 */
height: 100%; /* self-stretch */
padding: 8px;
border-right: 1px solid var(--Stroke-01);
display: inline-flex;
flex-direction: column;
justify-content: space-between;
```

### 50.3 Sidebar Tab Item - Active State

Активный таб с поднятой иконкой и индикатором chevron.

```css
/* Tab Container - Active */
width: 100%;
height: 40px;
padding-left: 4px;
padding-right: 8px;
padding-top: 4px;
padding-bottom: 4px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Content Row */
flex: 1;
display: flex;
gap: 12px;
align-items: center;

/* Icon Container - Active (elevated) */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: center;
align-items: center;

/* Icon */
width: 16px;
height: 16px;
/* Иконка в зависимости от типа медиа */

/* Icon Stroke - Active */
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Tab Label */
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Chevron Indicator (только на active) */
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape */
width: 4px;
height: 8px;
background: var(--Text-Secondary);
```

**Примечание:** Chevron indicator появляется только в активном состоянии таба.

### 50.4 Sidebar Tab Item - Default State

Неактивный таб без elevation и без chevron.

```css
/* Tab Container - Default */
width: 100%;
height: 40px;
padding: 4px;
background: var(--Surface-01);
border-radius: 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Content Row */
flex: 1;
display: flex;
gap: 12px;
align-items: center;

/* Icon Container - Default (без elevation) */
padding: 8px;
background: var(--Surface-03);
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;

/* Icon Stroke - Default */
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Tab Label */
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Примечание:** В default состоянии chevron indicator отсутствует.

### 50.5 Sidebar Close Button

Кнопка закрытия панели внизу sidebar.

```css
/* Close Button Container */
width: 128px;
height: 96px;
padding: 6px;
border-radius: 12px;
outline: 1px solid rgba(var(--Shade-7-10), 0.1);
outline-offset: -1px;
display: inline-flex;
justify-content: flex-end;
align-items: flex-start;

/* Close Icon Button */
width: 24px;
height: 24px;
padding: 12px 8px;
background: var(--Surface-01);
border-radius: 6px;
box-shadow:
  0px 1.25px 3px 0px rgba(50,50,50,0.10),
  inset 0px 1.25px 1px 0px rgba(255,255,255,1.00);
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Close Icon */
width: 16px;
height: 16px;
/* или 12×12px в зависимости от варианта */

/* Icon Fill */
background: var(--Text-Secondary);
```

### 50.6 Content Area

Основная область с настройками экспорта (384px).

```css
/* Content Area */
width: 384px; /* w-96 */
height: 100%;
display: inline-flex;
flex-direction: column;
overflow: hidden;
```

### 50.7 Section Header (Collapsible)

Заголовок секции с иконкой сворачивания.

```css
/* Header Container */
width: 100%;
height: 56px;
padding: 16px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Header Title */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Collapse Icon Button */
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;

/* Collapse Icon */
width: 16px;
height: 16px;

/* Icon Shape (dot/cross) */
width: 8px;
height: 8px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

### 50.8 Dropdown Control (with Icon)

Выпадающий список с иконкой и chevron.

```css
/* Dropdown Container */
width: 160px; /* w-40 */
padding: 10px;
background: var(--Surface-01);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
gap: 8px;
overflow: hidden;

/* Content Row */
flex: 1;
display: flex;
gap: 6px;

/* Icon Container */
width: 16px;
height: 16px;
opacity: 0.7;
overflow: hidden;

/* Icon Stroke */
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Dropdown Text */
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape */
width: 6px;
height: 2.39px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

### 50.9 Toggle Switch Control (2 Options)

Переключатель между двумя опциями (PNG/JPG, MP4/GIF, etc).

```css
/* Toggle Container */
width: 112px; /* w-28 */
padding: 4px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
overflow: hidden;

/* Option - Active */
flex: 1;
padding: 6px 12px;
background: var(--Surface-01);
border-radius: 6px;
box-shadow: 0px 1px 4px 0px rgba(0,0,0,0.14);
display: flex;
justify-content: center;
align-items: center;

/* Option Text - Active */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Option - Inactive */
flex: 1;
padding: 6px 12px;
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;

/* Option Text - Inactive */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
```

### 50.10 Settings Row (Label + Control)

Строка с лейблом и контролом справа.

```css
/* Settings Row Container */
width: 100%;
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Label */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Control (dropdown/toggle) - see 50.8 or 50.9 */
width: 160px; /* varies */
```

### 50.11 Compression Slider

Слайдер компрессии с процентом.

```css
/* Slider Row Container */
width: 100%;
display: inline-flex;
gap: 6px;

/* Slider Track Container */
flex: 1;
height: 36px;
position: relative;

/* Slider Track Background */
width: 288px; /* w-72 */
height: 36px;
position: absolute;
left: 0;
top: 0;
background: var(--Surface-03);
border-radius: 10px;
overflow: hidden;

/* Slider Fill (progress) */
width: 224px; /* w-56 - example at 80% */
height: 36px;
position: absolute;
left: 0;
top: 0;
background: rgba(var(--Shade-6-30), 0.3);

/* Slider Thumb */
width: 24px;
height: 36px;
position: absolute;
left: 220px; /* positioned at fill end */
top: 0;
background: var(--Surface-02);
border-radius: 8px;
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px -1px rgba(0,0,0,0.17),
  inset 0px -1px 4px -2px rgba(0,0,0,0.20);

/* Percentage Display Container */
padding: 10px 8px 10px 10px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
gap: 6px;
overflow: hidden;

/* Percentage Icon */
width: 16px;
height: 16px;
opacity: 0.7;

/* Icon Shape */
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Percentage Text */
width: 32px;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
```

### 50.12 Resolution Display Text

Текст отображения разрешения (вспомогательный).

```css
/* Resolution Text */
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 10px;
font-weight: 400;
font-family: 'Inter';
line-height: 16px;
text-align: center;
```

**Пример:** "3840px × 2160px"

### 50.13 Estimation Text (Video Export)

Текст с оценкой времени и размера экспорта.

```css
/* Estimation Text */
width: 100%;
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 10px;
font-weight: 400;
font-family: 'Inter';
line-height: 16px;
text-align: center;
```

**Пример:** "Estimation — Export time 30 seconds — Output size 35MB"

### 50.14 Export Button

Основная кнопка экспорта с темным градиентом.

```css
/* Export Button - Default */
width: 100%;
padding: 8px 20px;
background: linear-gradient(to bottom, var(--Shade-7-100), var(--Shade-8-100));
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(51,51,51,1.00),
  0px 2px 4px -1px rgba(13,13,13,0.50),
  inset 0px -1px 1.2px 0.35px rgba(18,18,18,1.00),
  inset 0px 0.5px 1px 0px rgba(255,255,255,0.15);
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
color: #FAFAF9; /* neutral-50 */
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

**Текст:** "Export Robot 2.0"

### 50.15 Settings Section Container (Images Export)

Контейнер настроек для экспорта изображений.

```css
/* Settings Section */
width: 100%;
padding: 16px;
display: flex;
flex-direction: column;
gap: 6px;
```

### 50.16 Export Row (Multi-Control)

Строка с несколькими контролами (Scale + Color Space + Format).

```css
/* Export Row Container */
width: 100%;
display: inline-flex;
gap: 12px;

/* Controls Group */
flex: 1;
display: flex;
gap: 6px;

/* Scale Dropdown */
width: 80px; /* w-20 */
padding-left: 8px;
padding-right: 10px;
padding-top: 10px;
padding-bottom: 10px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
/* Structure: Icon (opacity 70%) + Text + Chevron */

/* Color Space Dropdown */
flex: 1;
padding: 10px;
background: var(--Surface-01);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
/* Structure: Icon (opacity 70%) + Text + Chevron */

/* Format Toggle */
width: 112px; /* w-28 */
/* См. 50.9 Toggle Switch Control */

/* Collapse Button (minus icon) */
padding: 4px;
border-radius: 6px;
/* Icon: horizontal line (minus) */
```

### 50.17 Compression Section

Секция с заголовком, resolution display и слайдером компрессии.

```css
/* Compression Section Container */
width: 100%;
padding: 16px;
border-top: 1px solid var(--Stroke-01);
display: flex;
flex-direction: column;
gap: 8px;

/* Header Row */
width: 100%;
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Label */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;

/* Resolution Display */
/* См. 50.12 */

/* Slider Row */
/* См. 50.11 */
```

### 50.18 Export Footer

Нижняя часть панели с кнопкой экспорта.

```css
/* Footer Container */
width: 100%;
padding: 16px;
display: flex;
flex-direction: column;
gap: 8px;

/* Estimation Text (опционально для Video) */
/* См. 50.13 */

/* Export Button */
/* См. 50.14 */
```

### 50.19 Summary: Export Panel Structure

| Элемент | Размер | Padding | Border Radius | Background | Особенности |
|---------|--------|---------|---------------|------------|-------------|
| Panel Container | 549×320px | - | 20px | Shade1-100 | backdrop-blur: 6px, 5 теней, outline Stroke-01 |
| Sidebar | 144px×100% | 8px | - | - | border-right: Stroke-01 |
| Tab Active | 100%×40px | 4px 8px 4px 4px | 12px | Surface-03 | outline Stroke-02, chevron visible |
| Tab Default | 100%×40px | 4px | 12px | Surface-01 | chevron hidden |
| Icon Container Active | - | 8px | 8px | Surface-01 | box-shadow elevation |
| Icon Container Default | - | 8px | 8px | Surface-03 | no shadow |
| Content Area | 384px×100% | - | - | - | - |
| Section Header | 100%×56px | 16px | - | - | border-top: Stroke-01 |
| Dropdown | 160px | 10px | 10px | Surface-01 | outline Stroke-01, icon opacity 70% |
| Toggle Switch | 112px | 4px | 10px | Surface-03 | outline Stroke-01 |
| Toggle Option Active | flex: 1 | 6px 12px | 6px | Surface-01 | shadow, 12px/600 |
| Toggle Option Inactive | flex: 1 | 6px 12px | 8px | - | 12px/500 Secondary |

### 50.20 Summary: Slider & Text Specifications

| Элемент | Размер | Цвет | Font | Особенности |
|---------|--------|------|------|-------------|
| Slider Track | 288px×36px | Surface-03 | - | border-radius: 10px |
| Slider Fill | varies | Shade-6-30 30% | - | positioned left: 0 |
| Slider Thumb | 24×36px | Surface-02 | - | 3 shadows, radius: 8px |
| Percentage Display | auto | - | 12px/500 | outline Stroke-02, icon 70% opacity |
| Resolution Text | auto | Text-Secondary 80% | 10px/400 | text-align: center |
| Estimation Text | 100% | Text-Secondary 80% | 10px/400 | text-align: center |

### 50.21 Summary: Export Configurations

| Type | Settings Available | Toggle Switches | Dropdowns | Special Controls |
|------|-------------------|----------------|-----------|------------------|
| **Images** | Scale, Color Space, Format, Compression | PNG/JPG | 1x/2x, sRGB/Adobe Color | Compression slider (0-100%) |
| **Video** | Camera, Format, Frame Rate, Resolution | MP4/GIF, 1080p/4K | Camera 1, 60 FPS | Estimation text |
| **3D Object** | Format, Camera, Material | Yes/No (Material) | OBJ, Camera 1 | - |

### 50.22 Media Type Icons

Три типа иконок для табов навигации:

```css
/* Images Icon */
width: 12px;
height: 10px;
outline: 1.5px solid [color];
outline-offset: -0.75px;

/* Video Icon */
width: 12px;
height: 10px;
outline: 1.5px solid [color];
outline-offset: -0.75px;

/* 3D Object Icon */
width: 10px;
height: 12px;
outline: 1.5px solid [color];
outline-offset: -0.75px;
```

**Цвет иконки:**
- Active tab: `var(--Text-Primary)`
- Default tab: `var(--Text-Secondary)`

### 50.23 Usage Guidelines

**Export Panel:**
- Используйте для экспорта различных типов медиа (изображения, видео, 3D объекты)
- Sidebar всегда 144px, content area всегда 384px
- Активный таб имеет elevation на иконке и chevron indicator справа
- Неактивные табы без elevation и без chevron

**Tab Navigation:**
- Только один таб может быть активным одновременно
- Active состояние: Surface-03 background + outline Stroke-02
- Icon container в active: Surface-01 + shadow elevation
- Default состояние: Surface-01 background, icon без elevation

**Dropdowns:**
- Всегда с иконкой слева (opacity 70%) и chevron справа
- Width обычно 160px (w-40)
- Outline Stroke-01, background Surface-01 или Surface-03

**Toggle Switches:**
- Используйте для бинарного выбора (PNG/JPG, MP4/GIF, Yes/No)
- Active опция: Surface-01 + shadow, текст 600 weight, Text-Primary
- Inactive опция: transparent, текст 500 weight, Text-Secondary

**Compression Slider:**
- Slider fill показывает процент компрессии (0-100%)
- Thumb позиционируется на конце fill области
- Процент отображается справа в отдельном контейнере

**Export Button:**
- Всегда темный градиент (Shade-7 → Shade-8)
- Текст neutral-50 (светлый)
- 4 слоя теней для объема
- Текст "Export Robot 2.0" или аналогичный

**Estimation Text:**
- Используйте для Video и других длительных операций
- Opacity 80%, Text-Secondary, 10px font size
- Формат: "Estimation — Export time X — Output size Y"

**Resolution Display:**
- Вспомогательный текст 10px, opacity 80%
- Формат: "ШШШШpx × ВВВВpx"
- Обычно под toggle switch разрешения

---

## 51. Sharing Panel / Delete Confirmation Modal / Swipe Actions

### 51.1 Sharing Panel Container

Панель управления доступом к файлу с приглашением пользователей.

```css
/* Panel Container */
width: 384px;
background: var(--Shade1-100);
border-radius: 24px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid #E5E7EB; /* gray-200 */
outline-offset: -1px;
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
overflow: hidden;
```

### 51.2 Invite Input Section

Секция с input для email и кнопкой приглашения.

```css
/* Section Container */
width: 100%;
padding: 16px;
display: inline-flex;
gap: 6px;

/* Input Container */
width: 320px; /* w-80 */
padding-left: 16px;
padding-right: 4px;
padding-top: 4px;
padding-bottom: 4px;
background: var(--Surface-02);
border-radius: 12px;
box-shadow: inset 0px 1px 3px 0px rgba(18,18,18,0.10);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Input Content Row */
flex: 1;
display: flex;
justify-content: space-between;
align-items: center;

/* Cursor (Text Cursor Indicator) */
width: 0;
height: 12px;
outline: 1.5px solid var(--Colors-Blue-Blue-100);
outline-offset: -0.75px;

/* Placeholder Text */
opacity: 0.5;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
```

**Placeholder:** "Email, name..."

### 51.3 Permission Dropdown (Inside Input)

Выпадающий список прав доступа внутри input.

```css
/* Dropdown Container */
width: 96px; /* w-24 */
padding-left: 12px;
padding-right: 8px;
padding-top: 8px;
padding-bottom: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Dropdown Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape */
width: 6px;
height: 2.39px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Опции:** "can view", "can edit"

### 51.4 Invite Button

Кнопка отправки приглашения.

```css
/* Invite Button - Default */
padding: 8px 20px;
background: linear-gradient(to bottom, var(--Shade-7-100), var(--Shade-8-100));
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(51,51,51,1.00),
  0px 2px 4px -1px rgba(13,13,13,0.50),
  inset 0px -1px 1.2px 0.35px rgba(18,18,18,1.00),
  inset 0px 0.5px 1px 0px rgba(255,255,255,0.15);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
color: #FAFAF9; /* neutral-50 */
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

### 51.5 Access Section Container

Контейнер для секций General Access и People with Access.

```css
/* Section Container */
width: 100%;
padding: 16px 16px 10px 16px; /* px-4 py-2.5 */
border-top: 1px solid var(--Stroke-01);
display: flex;
flex-direction: column;

/* Section Header */
width: 100%;
padding-top: 8px;
padding-bottom: 8px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Section Title */
flex: 1;
opacity: 0.7;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

### 51.6 Radio Button Item (General Access)

Radio-style кнопка для выбора типа доступа.

```css
/* Radio Item Container */
width: 384px; /* w-96 */
height: 48px;
padding-top: 10px;
padding-bottom: 10px;
display: inline-flex;
gap: 12px;
align-items: center;

/* Icon Container - Active */
padding: 8px;
background: var(--Surface-02);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: center;
align-items: center;

/* Radio Icon */
width: 16px;
height: 16px;

/* Radio Icon Shape (varies by type) */
/* "Only those invited": 14×10px */
width: 14px;
height: 10px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* "Link access": 12×12px */
width: 12px;
height: 12px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Text Column */
flex: 1;
display: inline-flex;
flex-direction: column;

/* Primary Text */
width: 100%;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Secondary Text */
width: 100%;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Опции:**
- "Only those invited" → "4 people"
- "Link access" → "Only users have shared the link"

### 51.7 User List Item

Элемент списка пользователей с доступом к файлу.

```css
/* User Item Container */
width: 384px; /* w-96 */
height: 48px;
padding-top: 10px;
padding-bottom: 10px;
display: inline-flex;
justify-content: space-between;
align-items: center;

/* User Info Group */
display: flex;
gap: 12px;
align-items: center;

/* Avatar */
width: 32px;
height: 32px;
border-radius: 32px;
object-fit: cover;

/* User Info Column */
width: 160px; /* w-40 */
display: inline-flex;
flex-direction: column;

/* User Name */
width: 100%;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* User Email */
width: 100%;
opacity: 0.7;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Permission Dropdown */
width: 96px; /* w-24 */
padding: 8px;
border-radius: 8px;
display: flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Permission Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape */
width: 6px;
height: 2.39px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Permission Options:** "can edit", "Owner" (с иконкой замка зеленого цвета)

### 51.8 Owner Badge (Special)

Специальный бадж для владельца файла.

```css
/* Owner Dropdown Container */
width: 96px; /* w-24 */
padding: 8px;
border-radius: 8px;
display: flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Owner Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;

/* Lock Icon Container */
width: 16px;
height: 16px;
position: relative;

/* Lock Icon Inner */
width: 12px;
height: 12px;

/* Lock Icon Shape */
width: 8px;
height: 10px;
outline: 1.5px solid var(--Colors-Green);
outline-offset: -0.75px;
```

### 51.9 Swipe Delete Action

Действие удаления при свайпе влево.

```css
/* Delete Strip Container */
width: 20px; /* w-5 */
height: 48px;
position: absolute;
left: 400px; /* за краем панели 384px */
top: 94px; /* позиция второго юзера */

/* Red Background Strip */
width: 20px;
height: 48px;
position: absolute;
left: 0;
top: 0;
background: var(--Colors-Red);
border-top-left-radius: 8px;
border-bottom-left-radius: 8px;

/* Delete Icon Container */
width: 12px;
height: 12px;
position: absolute;
left: 4px;
top: 20px; /* вертикальное центрирование */
overflow: hidden;

/* Delete Icon (X shape) */
width: 4px;
height: 4px;
outline: 1.5px solid var(--Shade1-100); /* white */
outline-offset: -0.75px;
```

**Анимация:** При свайпе влево панель сдвигается, открывая красную полосу с иконкой удаления.

### 51.10 Delete Tooltip

Всплывающая подсказка для действия удаления.

```css
/* Tooltip Container */
padding-left: 4px;
padding-right: 2px;
padding-top: 2px;
padding-bottom: 2px;
background: var(--Text-Primary);
border-radius: 6px;
box-shadow: 0px 4px 4px -2px rgba(0,0,0,0.40);
display: inline-flex;
justify-content: center;
align-items: center;
gap: 4px;
overflow: hidden;
position: absolute;
left: 428px; /* рядом с delete action */
top: 336px;

/* Tooltip Inner Padding */
padding: 4px 4px 2px 4px; /* px-1 py-0.5 */
display: flex;
justify-content: center;
align-items: center;

/* Tooltip Text */
color: var(--Shade-5-100);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
text-align: center;
```

**Текст:** "Remove"

### 51.11 Link Footer

Нижняя секция с ссылкой и кнопкой копирования.

```css
/* Footer Container */
width: 100%;
height: 64px;
padding-left: 20px;
padding-right: 16px;
padding-top: 16px;
padding-bottom: 16px;
background: var(--Surface-02);
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
gap: 44px; /* gap-11 */
align-items: center;

/* Link Text */
flex: 1;
opacity: 0.5;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 400;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Пример ссылки:** "https://brainwave.co/file/k373nH"

### 51.12 Copy Link Button

Кнопка копирования ссылки в буфер обмена.

```css
/* Copy Button - Default */
padding: 8px 16px;
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5); /* neutral-200 */
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Copy Icon */
width: 20px;
height: 20px;

/* Icon Shape */
width: 16px;
height: 16px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Button Text */
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

### 51.13 Delete Confirmation Modal Container

Модальное окно подтверждения удаления файла с превью.

```css
/* Modal Wrapper */
width: 384px; /* w-96 */
height: 320px; /* h-80 */
display: inline-flex;
flex-direction: column;
justify-content: flex-end;
align-items: center;

/* Image Preview Container */
width: 384px;
height: 384px;
position: relative;

/* Gradient Overlay */
width: 320px; /* w-80 */
height: 320px; /* h-80 */
position: absolute;
left: 6px;
top: 6px;
background: linear-gradient(to bottom, #000000, rgba(0,0,0,0));

/* Preview Image */
width: 384px;
height: 384px;
position: absolute;
left: 0;
top: 0;
object-fit: cover;
```

### 51.14 Delete Modal Content

Контейнер модального окна с контентом и действиями.

```css
/* Modal Container */
width: 100%;
padding-top: 128px; /* pt-32 - для overlap с изображением */
background: var(--Shade1-100);
border-radius: 32px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
backdrop-filter: blur(6px);
display: flex;
flex-direction: column;
overflow: hidden;
```

### 51.15 Delete Modal Text Content

Текстовая часть модального окна.

```css
/* Content Section */
width: 100%;
padding: 24px;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
gap: 8px;

/* Modal Title */
width: 100%;
color: var(--Text-Primary);
font-size: 24px;
font-weight: 500;
font-family: 'Inter';
line-height: 32px;
text-align: center;

/* Modal Description */
width: 256px; /* w-64 */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 400;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

**Текст:**
- Title: "Delete this file?"
- Description: "This action cannot be undone. Blinky is a bit nervous about it too."

### 51.16 Delete Modal Actions Footer

Нижняя часть модального окна с кнопками действий.

```css
/* Footer Container */
width: 100%;
padding: 24px;
background: var(--Surface-02);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 12px;

/* Cancel Button */
flex: 1;
padding: 10px 24px; /* px-6 py-2.5 */
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5); /* neutral-200 */
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Cancel Text */
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;

/* Delete Button (Destructive) */
flex: 1;
padding: 10px 24px; /* px-6 py-2.5 */
background: linear-gradient(to bottom, #EA580C, #EA580C); /* orange-600 */
border-radius: 12px;
box-shadow:
  0px 3px 4px -1px rgba(252,96,16,0.95),
  0px 0px 0px 1px rgba(191,74,15,1.00),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Delete Text */
color: var(--Shade1-100); /* white text */
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

**Buttons:**
- "Cancel" (neutral gray)
- "Yes, delete it" (destructive orange)

### 51.17 Summary: Sharing Panel Structure

| Элемент | Размер | Padding | Border Radius | Background | Особенности |
|---------|--------|---------|---------------|------------|-------------|
| Panel Container | 384px | - | 24px | Shade1-100 | backdrop-blur: 6px, outline gray-200 |
| Invite Input | 320px | 16px 4px 4px | 12px | Surface-02 | inset shadow, outline Stroke-02 |
| Permission Dropdown | 96px | 12px 8px | 8px | Surface-01 | shadow elevation |
| Invite Button | auto | 8px 20px | 12px | Shade-7→Shade-8 gradient | 4 тени, neutral-50 text |
| Section Header | 100% | 8px | - | - | opacity 70%, Text-Secondary |
| Radio Icon Container | - | 8px | 8px | Surface-02 | shadow, outline Stroke-02 |
| User Avatar | 32×32px | - | 32px | - | rounded-full |
| User Info Column | 160px | - | - | - | name + email |
| Permission Button | 96px | 8px | 8px | - | can edit / Owner |
| Delete Strip | 20×48px | - | 8px (left) | Colors-Red | left: 400px (offscreen) |
| Footer | 100%×64px | 20px 16px | - | Surface-02 | border-top Stroke-01 |
| Copy Button | auto | 8px 16px | 12px | neutral-200 | 3 тени |

### 51.18 Summary: Delete Modal Structure

| Элемент | Размер | Padding | Border Radius | Background | Особенности |
|---------|--------|---------|---------------|------------|-------------|
| Modal Wrapper | 384×320px | - | - | - | flex-end alignment |
| Image Preview | 384×384px | - | - | - | absolute positioning |
| Gradient Overlay | 320×320px | - | - | black→transparent | left: 6px, top: 6px |
| Modal Container | 100% | top: 128px | 32px | Shade1-100 | backdrop-blur: 6px, 5 теней |
| Content Section | 100% | 24px | - | - | gap: 8px |
| Title | 100% | - | - | Text-Primary | 24px/500/32px, text-center |
| Description | 256px | - | - | Text-Secondary | 12px/400/20px, text-center |
| Footer | 100% | 24px | - | Surface-02 | outline Stroke-02 |
| Cancel Button | flex: 1 | 10px 24px | 12px | neutral-200 | 3 тени |
| Delete Button | flex: 1 | 10px 24px | 12px | orange-600 | 3 тени (оранжевые) |

### 51.19 Summary: Interactive States

| Элемент | Default | Hover | Active | Special |
|---------|---------|-------|--------|---------|
| Invite Input | Surface-02, inset shadow | - | Blue cursor visible | Placeholder opacity 50% |
| Permission Dropdown | 96px, rounded-lg | - | - | Chevron icon right |
| Radio Item | Surface-02, outline Stroke-02 | - | Icon Text-Primary | Shadow elevation |
| User Item | - | - | - | Swipe reveals delete |
| Delete Strip | left: 400px (hidden) | - | - | Swipe animation |
| Delete Tooltip | Text-Primary bg | - | - | Shadow, Shade-5-100 text |
| Copy Button | neutral-200 | - | - | Icon + text |
| Modal Cancel | neutral-200 | - | - | 3 тени |
| Modal Delete | orange-600 | - | - | Destructive, white text |

### 51.20 Usage Guidelines

**Sharing Panel:**
- Используйте для управления доступом к файлам, документам, проектам
- Input всегда с dropdown разрешений внутри
- Invite button темный градиент для главного действия
- Section headers с opacity 70% для визуальной иерархии
- General Access для глобальных настроек (invited only / link access)
- People with Access для списка конкретных пользователей

**Radio Items (General Access):**
- Иконка в контейнере с elevation (Surface-02 + shadow)
- Primary text (название) + secondary text (описание/количество)
- Только один вариант может быть активным

**User List Items:**
- Avatar 32×32px округлый
- Name (Text-Primary) + Email (Text-Secondary, opacity 70%)
- Permission dropdown справа (can edit / Owner)
- Owner имеет специальную иконку замка зеленого цвета

**Swipe Delete Action:**
- Красная полоса 20px шириной скрыта за краем панели (left: 400px)
- При свайпе влево открывается delete action
- Иконка удаления белая на красном фоне
- Tooltip "Remove" появляется при свайпе

**Delete Confirmation Modal:**
- Превью изображения 384×384px с gradient overlay (black→transparent)
- Modal контейнер с padding-top 128px для overlap с превью
- Title 24px centered, description 12px secondary
- Footer с двумя равными кнопками (Cancel + Delete)
- Delete button всегда оранжевый (orange-600) для destructive действия

**Color Usage:**
- Invite button: темный градиент (Shade-7→Shade-8)
- Copy button: светлый градиент (neutral-200)
- Delete action strip: Colors-Red
- Delete button: orange-600 (destructive)
- Owner lock icon: Colors-Green

**Typography:**
- Section headers: 12px/500, opacity 70%
- User names: 12px/500, Text-Primary
- User emails: 12px/500, Text-Secondary, opacity 70%
- Permissions: 12px/500
- Modal title: 24px/500
- Modal description: 12px/400
- Buttons: 14px/600

---

## 52. Comment Card / Profile Card / Action Icons

### 52.1 Comment Card Container

Карточка с превью объекта и комментариями.

```css
/* Card Container */
width: 384px;
padding: 8px;
background: var(--Surface-01);
border-radius: 20px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
gap: 8px;
overflow: hidden;
```

### 52.2 Object Header (Comment Card)

Заголовок с иконкой, названием и категорией объекта.

```css
/* Header Container */
width: 100%;
padding: 12px;
display: inline-flex;
gap: 12px;
align-items: center;

/* Icon Button */
width: 36px;
height: 36px;
padding: 8px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Icon Container */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Shape */
width: 8px;
height: 8px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Text Column */
flex: 1;
display: inline-flex;
flex-direction: column;

/* Object Title */
width: 100%;
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Object Category */
width: 100%;
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
```

**Пример:** "Shop House Icon" / "3D Objects"

### 52.3 Object Preview Area (Comment Card)

Область превью объекта с центрированным изображением.

```css
/* Preview Container */
width: 100%;
height: 256px;
min-width: 96px;
min-height: 80px;
background: var(--Surface-03);
border-radius: 16px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
position: relative;
overflow: hidden;

/* Preview Image */
width: 265px;
height: 265px;
position: absolute;
left: 44.12px; /* Центрирование */
top: -0.38px;
object-fit: cover;
```

**Примечание:** Изображение 265×265px центрируется в контейнере 384px (с учетом padding 16px).

### 52.4 Comments Section Container

Секция со списком комментариев и input для ответа.

```css
/* Comments Container */
width: 100%;
padding: 12px;
display: flex;
flex-direction: column;
gap: 16px;
```

### 52.5 Comment Item

Отдельный комментарий пользователя.

```css
/* Comment Container */
width: 100%;
display: inline-flex;
gap: 12px;

/* Avatar */
width: 36px;
height: 36px;
border-radius: 32px;
object-fit: cover;

/* Comment Content Column */
flex: 1;
display: inline-flex;
flex-direction: column;
gap: 8px;

/* Comment Text Block */
width: 100%;
display: flex;
flex-direction: column;
gap: 4px;

/* Comment Header Row */
width: 100%;
height: 16px;
display: inline-flex;
gap: 4px;
align-items: center;

/* Author Name */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Timestamp */
opacity: 0.5;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;

/* Comment Text */
width: 100%;
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 400;
font-family: 'Inter';
line-height: 20px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 3; /* макс 3 строки */
-webkit-box-orient: vertical;
```

**Пример timestamp:** "1h", "2m", "3d"

### 52.6 Reaction Badge (Emoji Counter)

Бадж с emoji реакцией и счетчиком.

```css
/* Reaction Badge */
padding: 6px 8px; /* px-2 py-1.5 */
border-radius: 8px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Emoji */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Counter */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;
```

**Пример:** 👍 2

### 52.7 Reply Comment Item

Комментарий-ответ с упоминанием пользователя.

```css
/* Reply Container */
width: 100%;
display: inline-flex;
gap: 12px;

/* Avatar */
width: 36px;
height: 36px;
border-radius: 32px;
object-fit: cover;

/* Reply Content Column */
flex: 1;
display: inline-flex;
flex-direction: column;
gap: 4px;

/* Author Name */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Reply Text with Mention */
width: 100%;
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 400;
font-family: 'Inter';
line-height: 20px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
```

**Пример:** "Reply to @randomfash"

### 52.8 Comment Action Icons Row

Строка с иконками действий и кнопкой Send.

```css
/* Actions Row Container */
width: 100%;
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Icons Group */
display: flex;
gap: 4px;

/* Action Icon Button */
padding: 8px;
border-radius: 10px;
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Icon Container */
width: 20px;
height: 20px;
opacity: 0.7;
position: relative;
overflow: hidden;

/* Icon Shape (varies) */
width: 16px;
height: 16px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Send Button */
height: 36px;
padding: 10px 20px; /* px-5 py-2.5 */
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5); /* neutral-200 */
border-radius: 10px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Send Button Text */
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

**Icons:** 4 action icons (emoji, attach, mention, etc.)

### 52.9 Profile Card Container

Карточка профиля пользователя с галереей и информацией.

```css
/* Profile Card Container */
width: 384px;
padding: 8px;
background: var(--Surface-01);
border-radius: 32px;
box-shadow:
  0px 10px 21px 0px rgba(0,0,0,0.07),
  0px 38px 38px 0px rgba(0,0,0,0.06),
  0px 86px 52px 0px rgba(0,0,0,0.04),
  0px 153px 61px 0px rgba(0,0,0,0.01),
  0px 239px 67px 0px rgba(0,0,0,0.00);
backdrop-filter: blur(6px);
display: inline-flex;
flex-direction: column;
justify-content: center;
gap: 8px;
overflow: hidden;
```

### 52.10 Image Gallery Grid (Profile Card)

Галерея из трех изображений с разными border-radius.

```css
/* Gallery Container */
width: 100%;
height: 144px;
display: inline-flex;
gap: 4px;

/* Image - Left */
flex: 1;
height: 100%;
border-top-left-radius: 24px; /* rounded-tl-3xl */
border-top-right-radius: 8px; /* rounded-tr-lg */
border-bottom-left-radius: 24px; /* rounded-bl-3xl */
border-bottom-right-radius: 8px; /* rounded-br-lg */
object-fit: cover;

/* Image - Center */
flex: 1;
height: 100%;
border-radius: 8px; /* rounded-lg */
object-fit: cover;

/* Image - Right */
flex: 1;
height: 100%;
border-top-left-radius: 8px; /* rounded-tl-lg */
border-top-right-radius: 24px; /* rounded-tr-3xl */
border-bottom-left-radius: 8px; /* rounded-bl-lg */
border-bottom-right-radius: 24px; /* rounded-br-3xl */
object-fit: cover;
```

**Примечание:** Крайние изображения имеют скругление 24px с внешней стороны, центральное изображение полностью 8px.

### 52.11 Profile Info Section

Секция с аватаром, именем и статистикой.

```css
/* Info Container */
width: 100%;
display: flex;
flex-direction: column;
align-items: center;
gap: 16px;

/* Profile Avatar */
width: 80px;
height: 80px;
border-radius: 80px;
outline: 4px solid var(--Surface-01);
object-fit: cover;

/* Text Block */
width: 100%;
display: flex;
flex-direction: column;
align-items: center;
gap: 4px;

/* User Name */
width: 100%;
color: var(--Text-Primary);
font-size: 18px;
font-weight: 400;
font-family: 'Inter';
line-height: 28px;
text-align: center;

/* Stats Row */
display: inline-flex;
gap: 20px; /* gap-5 */

/* Stat Label */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;
```

**Пример:** "Sophie Bennett ®" / "159 scenes"

### 52.12 Profile Actions Section

Секция с социальными действиями (иконки + кнопка).

```css
/* Actions Container */
width: 100%;
padding: 16px;
display: flex;
flex-direction: column;
align-items: center;
gap: 24px;

/* Icons Row */
display: inline-flex;
gap: 8px;

/* Icon Button */
width: 40px;
height: 40px;
padding: 8px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Icon Container */
width: 20px;
height: 20px;
position: relative;
overflow: hidden;

/* Icon Fill (varies by type) */
width: 16px;
height: 16px;
background: #000000;

/* Share Button */
padding: 10px 24px; /* px-6 py-2.5 */
background: linear-gradient(to bottom, #E5E5E5, #E5E5E5); /* neutral-200 */
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600;
font-family: 'Inter';
line-height: 20px;
text-align: center;
```

**Button:** "Copy link"

### 52.13 Summary: Comment Card Structure

| Элемент | Размер | Padding | Border Radius | Background | Особенности |
|---------|--------|---------|---------------|------------|-------------|
| Card Container | 384px | 8px | 20px | Surface-01 | backdrop-blur: 6px, 5 теней |
| Object Header | 100% | 12px | - | - | gap: 12px |
| Icon Button | 36×36px | 8px | 10px | - | outline Stroke-02 |
| Object Title | 100% | - | - | Text-Primary | 14px/600, line-clamp: 1 |
| Object Category | 100% | - | - | Text-Secondary | 12px/500, opacity 80% |
| Preview Area | 100%×256px | - | 16px | Surface-03 | outline Stroke-02 |
| Preview Image | 265×265px | - | - | - | centered (left: 44.12px) |
| Comments Section | 100% | 12px | - | - | gap: 16px |
| Comment Item | 100% | - | - | - | gap: 12px |
| Avatar | 36×36px | - | 32px | - | rounded-full |
| Author Name | - | - | - | Text-Primary | 12px/600 |
| Timestamp | - | - | - | Text-Secondary | 12px/500, opacity 50% |
| Comment Text | 100% | - | - | Text-Secondary | 12px/400/20px, line-clamp: 3 |
| Reaction Badge | auto | 6px 8px | 8px | - | outline Stroke-02 |
| Action Icons Row | 100% | - | - | - | justify-between |
| Icon Button | - | 8px | 10px | - | opacity 70% |
| Send Button | h: 36px | 10px 20px | 10px | neutral-200 | 3 тени |

### 52.14 Summary: Profile Card Structure

| Элемент | Размер | Padding | Border Radius | Background | Особенности |
|---------|--------|---------|---------------|------------|-------------|
| Card Container | 384px | 8px | 32px | Surface-01 | backdrop-blur: 6px, 5 теней |
| Image Gallery | 100%×144px | - | - | - | gap: 4px, 3 изображения |
| Gallery Image Left | flex: 1 | - | 24/8/24/8px | - | outer corners 24px |
| Gallery Image Center | flex: 1 | - | 8px | - | all corners 8px |
| Gallery Image Right | flex: 1 | - | 8/24/8/24px | - | outer corners 24px |
| Profile Avatar | 80×80px | - | 80px | - | outline: 4px Surface-01 |
| User Name | 100% | - | - | Text-Primary | 18px/400/28px, text-center |
| Stats Label | - | - | - | Text-Secondary | 12px/600 |
| Actions Section | 100% | 16px | - | - | gap: 24px |
| Icon Button | 40×40px | 8px | 10px | - | outline Stroke-02 |
| Icon Fill | 16×16px | - | - | #000000 | varies by type |
| Copy Link Button | auto | 10px 24px | 12px | neutral-200 | 3 тени |

### 52.15 Summary: Text Styles

| Element | Font Size | Weight | Line Height | Color | Special |
|---------|-----------|--------|-------------|-------|---------|
| Object Title | 14px | 600 | 20px | Text-Primary | line-clamp: 1 |
| Object Category | 12px | 500 | 16px | Text-Secondary | opacity: 0.8 |
| Author Name | 12px | 600 | 16px | Text-Primary | - |
| Timestamp | 12px | 500 | 16px | Text-Secondary | opacity: 0.5 |
| Comment Text | 12px | 400 | 20px | Text-Secondary | opacity: 0.8, line-clamp: 3 |
| Reply Text | 12px | 400 | 20px | Text-Secondary | opacity: 0.8, line-clamp: 2 |
| Reaction Emoji | 12px | 600 | 16px | Text-Primary | - |
| Reaction Count | 12px | 600 | 16px | Text-Primary | - |
| Profile Name | 18px | 400 | 28px | Text-Primary | text-center |
| Profile Stats | 12px | 600 | 16px | Text-Secondary | - |
| Button Text | 14px | 600 | 20px | Text-Primary | text-center |

### 52.16 Usage Guidelines

**Comment Card:**
- Используйте для отображения объекта с комментариями
- Preview area всегда 256px высотой с outline Stroke-02
- Изображение центрируется математически (left: 44.12px для 265px изображения)
- Object header с иконкой, названием и категорией
- Comments section с неограниченным количеством комментариев

**Comment Items:**
- Avatar всегда 36×36px rounded-full
- Author name + timestamp в одной строке (gap: 4px)
- Timestamp с opacity 50% для визуальной иерархии
- Comment text обрезается после 3 строк (line-clamp: 3)
- Reply text обрезается после 2 строк (line-clamp: 2)

**Reaction Badges:**
- Emoji + counter в одном badge
- Outline Stroke-02 для четких границ
- Padding 6px 8px, border-radius 8px
- Font weight 600 для emoji и counter

**Action Icons Row:**
- Justify-between для разделения иконок и кнопки
- Icons group слева с gap 4px
- Send button справа с neutral-200 gradient
- Icons с opacity 70% в default состоянии

**Profile Card:**
- Используйте для отображения профиля пользователя
- Image gallery из 3 изображений с равной шириной (flex: 1)
- Крайние изображения: outer corners 24px, inner corners 8px
- Центральное изображение: все углы 8px
- Profile avatar 80×80px с outline 4px Surface-01

**Profile Info:**
- Avatar всегда по центру с outline (не shadow!)
- User name 18px centered
- Stats labels в одной строке с gap 20px
- Можно добавить несколько stats (followers, scenes, likes)

**Profile Actions:**
- 3 icon buttons + 1 main button
- Icon buttons 40×40px с outline Stroke-02
- Icons заполненные (#000000) для social actions
- Copy link button справа от иконок

**Image Gallery Border Radius Pattern:**
```
Left:   TL=24, TR=8,  BL=24, BR=8
Center: TL=8,  TR=8,  BL=8,  BR=8
Right:  TL=8,  TR=24, BL=8,  BR=24
```

**Avatars:**
- Comment avatars: 36×36px
- Profile avatar: 80×80px с outline 4px
- Всегда rounded-full
- object-fit: cover

**Text Truncation:**
- Object title: line-clamp 1
- Comment text: line-clamp 3
- Reply text: line-clamp 2
- User name: не обрезается (но может быть центрирован)

---

## 53. Editor UI Elements / Layer Panel / Timeline / Sliders

### 53.1 Icon Button - Small (16×16 Icon)

Маленькая иконка-кнопка для тулбаров.

```css
/* Button Container - Default */
padding: 4px;
border-radius: 6px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Container - Active */
padding: 4px;
background: var(--Surface-03);
border-radius: 6px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Icon Shape */
width: 8px;
height: 8px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Total size:** 24×24px (16px icon + 4px padding × 2)

### 53.2 Icon Button - Medium (20×20 Icon)

Средняя иконка-кнопка с большей зоной клика.

```css
/* Button Container - Default */
padding: 6px;
border-radius: 6px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Container - Active */
padding: 6px;
background: var(--Surface-03);
border-radius: 6px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon Container */
width: 20px;
height: 20px;
opacity: 0.8;
position: relative;
overflow: hidden;

/* Icon Shape */
width: 14px;
height: 14px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

**Total size:** 32×32px (20px icon + 6px padding × 2)

### 53.3 Breadcrumb / Navigation Item - Default

Навигационный элемент без фона.

```css
/* Container */
border-radius: 6px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;

/* Text Container */
padding: 0 6px; /* px-1.5 */
display: flex;
overflow: hidden;

/* Text */
max-width: 176px; /* max-w-44 */
color: var(--Text-Primary);
font-size: 16px;
font-weight: 600;
font-family: 'Inter';
line-height: 24px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Chevron Container */
padding: 4px;
display: flex;
justify-content: center;
align-items: center;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape */
width: 6px;
height: 2.39px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

### 53.4 Breadcrumb / Navigation Item - Active

Навигационный элемент с фоном Surface-03.

```css
/* Container - Active */
background: var(--Surface-03);
border-radius: 6px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;

/* Text Container */
padding: 0 6px; /* px-1.5 */
display: flex;
overflow: hidden;

/* Text */
max-width: 176px; /* max-w-44 */
color: var(--Text-Primary);
font-size: 16px;
font-weight: 600;
font-family: 'Inter';
line-height: 24px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Chevron Container - With Background */
padding: 4px;
background: rgba(var(--Shade-7-5), 0.05);
display: flex;
justify-content: center;
align-items: center;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape */
width: 6px;
height: 2.39px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

**Отличия:** Chevron container имеет фон Shade-7-5/5.

### 53.5 Breadcrumb / Label - Small

Маленький текстовый лейбл для навигации.

```css
/* Container - Default */
padding: 2px 6px; /* px-1.5 py-0.5 */
border-radius: 6px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text */
max-width: 208px; /* max-w-52 */
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Container - Active */
padding: 2px 6px; /* px-1.5 py-0.5 */
background: var(--Surface-03);
border-radius: 6px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text - Active */
opacity: 0.7;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
```

**Пример:** "3D Design Project"

### 53.6 Toolbar Icon Button Group

Группа иконок-кнопок для тулбара (3 варианта состояний).

```css
/* Icon Button - Default (Surface-03) */
padding: 8px;
background: var(--Surface-03);
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Icon Button - Active (Surface-01 + Shadow) */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Icon Button - Hover (Surface-01, No Shadow) */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;

/* Icon */
width: 16px;
height: 16px;

/* Icon Shape */
width: 10px;
height: 12px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

**Total size:** 32×32px (16px icon + 8px padding × 2)

### 53.7 Layer Panel Item - Active

Элемент панели слоев в активном состоянии с дополнительными иконками.

```css
/* Container - Active */
width: 208px; /* w-52 */
padding-left: 4px;
padding-right: 12px;
padding-top: 4px;
padding-bottom: 4px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Content Row */
flex: 1;
display: flex;
gap: 12px;
align-items: center;

/* Icon Container - Active */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: center;
align-items: center;

/* Layer Icon */
width: 16px;
height: 16px;

/* Icon Shape */
width: 10px;
height: 12px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Layer Name */
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;

/* Actions Icons Group */
display: flex;
justify-content: center;
align-items: center;
gap: 12px;

/* Action Icon (lock/hide/variation) */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Icon Shape (varies) */
/* Lock: 10×12px */
/* Eye: 14×10px */
/* Variations: 12×12px */
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Actions Icons:** lock, hide, variations (всегда Text-Secondary)

### 53.8 Layer Panel Item - Default

Элемент панели слоев в обычном состоянии.

```css
/* Container - Default */
width: 208px; /* w-52 */
padding-left: 4px;
padding-right: 12px;
padding-top: 4px;
padding-bottom: 4px;
background: var(--Surface-01);
border-radius: 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Icon Container - Default */
padding: 8px;
background: var(--Surface-03);
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;

/* Layer Icon */
width: 16px;
height: 16px;

/* Icon Shape */
width: 10px;
height: 12px;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;

/* Layer Name */
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Отличия:** Surface-01 background, icon container Surface-03, нет outline, нет action icons.

### 53.9 Layer Panel Item - Hover

Элемент панели слоев в hover состоянии.

```css
/* Container - Hover */
width: 208px; /* w-52 */
padding-left: 4px;
padding-right: 12px;
padding-top: 4px;
padding-bottom: 4px;
background: var(--Surface-03);
border-radius: 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Icon Container - Hover */
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
/* No shadow in hover state */
```

**Отличия:** Surface-03 background, icon container Surface-01 БЕЗ shadow, нет outline.

### 53.10 Layer Panel Item - Compact

Компактный элемент с chevron (без action icons).

```css
/* Container - Active Compact */
width: 128px; /* w-32 */
height: 40px;
padding-left: 4px;
padding-right: 8px;
padding-top: 4px;
padding-bottom: 4px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;

/* Chevron Container */
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape */
width: 4px;
height: 8px;
background: var(--Text-Secondary);
```

**Используется:** для свернутых/развернутых элементов в layer panel.

### 53.11 Toggle Switch - ON State

Переключатель во включенном состоянии.

```css
/* Toggle Container - ON */
width: 40px;
padding: 2px;
background: rgba(var(--Shade-9-70), 0.7);
border-radius: 24px;
box-shadow: inset 0px 1px 0.6px 0px rgba(18,18,18,0.30);
display: inline-flex;
justify-content: flex-end; /* Knob on right */
align-items: center;
gap: 8px;
overflow: hidden;

/* Toggle Knob */
width: 16px;
height: 16px;
background: var(--Surface-02);
border-radius: 24px;
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px 0px rgba(0,0,0,0.25),
  inset 0px 1px 0.5px 0px rgba(255,255,255,0.82);
```

### 53.12 Toggle Switch - OFF State

Переключатель в выключенном состоянии.

```css
/* Toggle Container - OFF */
width: 40px;
padding: 2px;
background: var(--Shade-4-100);
border-radius: 24px;
box-shadow: inset 0px 0px 1px 0.5px rgba(18,18,18,0.10);
display: inline-flex;
justify-content: flex-start; /* Knob on left */
align-items: center;
gap: 8px;
overflow: hidden;

/* Toggle Knob */
width: 16px;
height: 16px;
background: var(--Surface-02);
border-radius: 24px;
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px 0px rgba(0,0,0,0.25),
  inset 0px 1px 0.5px 0px rgba(255,255,255,0.82);
```

### 53.13 Slider - Style 1 (Light Fill)

Слайдер с легкой заливкой.

```css
/* Slider Container */
width: 112px; /* w-28 */
height: 36px;
position: relative;

/* Track Background */
width: 112px;
height: 36px;
position: absolute;
left: 0;
top: 0;
background: var(--Surface-03);
border-radius: 8px;

/* Fill (Progress) */
width: 56px; /* flex: 1, пример 50% */
height: 36px;
position: absolute;
left: 0;
top: 0;
background: rgba(var(--Shade-6-30), 0.3);
border-radius: 8px;
display: inline-flex;
justify-content: flex-start;
align-items: center;

/* Thumb */
width: 24px;
height: 36px;
background: var(--Surface-02);
border-radius: 6px;
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px -1px rgba(0,0,0,0.17),
  inset 0px -1px 4px -2px rgba(0,0,0,0.20);
```

**Примечание:** Fill и thumb двигаются вместе.

### 53.14 Slider - Style 2 (Dark Fill with Border)

Слайдер с темной заливкой и border.

```css
/* Slider Container */
width: 112px; /* w-28 */
height: 36px;
position: relative;

/* Track Background */
width: 112px;
height: 36px;
position: absolute;
left: 0;
top: 0;
background: var(--Surface-03);
border-radius: 8px;
border: 1px solid var(--Stroke-01);

/* Fill (Progress) */
width: 56px; /* flex: 1, пример 50% */
height: 36px;
position: absolute;
left: 0;
top: 0;
background: rgba(var(--Shade-6-50), 0.5);
border-radius: 8px;
display: inline-flex;
justify-content: flex-start;
align-items: center;

/* Thumb */
width: 24px;
height: 36px;
background: var(--Surface-02);
border-radius: 6px;
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px -1px rgba(0,0,0,0.40),
  inset 0px -1px 4px -2px rgba(0,0,0,0.20);
```

**Отличия:** border Stroke-01, fill Shade-6-50/50, thumb shadow более интенсивная.

### 53.15 Timeline / Film Strip Container

Временная шкала с превью кадров.

```css
/* Timeline Container */
width: 208px; /* w-52 */
border-radius: 12px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
overflow: hidden;

/* Frame Thumbnail */
flex: 1;
height: 56px; /* h-14 */
object-fit: cover;
```

**Thumbnails:** 6 изображений с flex: 1 (равная ширина).

### 53.16 Timeline Scrubber (Playhead)

Курсор воспроизведения на timeline.

```css
/* Scrubber Container */
width: 48px;
height: 56px;
position: absolute;
left: 0; /* или 156px для правого */
top: 0;

/* Backdrop Overlay */
width: 48px;
height: 56px;
position: absolute;
left: 0; /* или 4px для правого */
top: 0;
background: rgba(23, 23, 23, 0.3); /* neutral-900/30 */
backdrop-filter: blur(2px);

/* Vertical Line */
width: 0;
height: 56px;
position: absolute;
left: 48px; /* или 4px для левого */
top: 3px; /* отступ от края */
outline: 1.5px solid var(--Shade1-100);
outline-offset: -0.75px;

/* Top Marker */
width: 8px;
height: 5px;
position: absolute;
left: 44px; /* или 0 для левого */
top: 1px;
background: var(--Shade1-100);
border-radius: 0.75px;

/* Bottom Marker */
width: 8px;
height: 5px;
position: absolute;
left: 44px; /* или 0 для левого */
top: 54px;
background: var(--Shade1-100);
border-radius: 0.75px;
```

**Позиции:** left: 0 (start) или left: 156px (end, для timeline 208px с 6 frames).

### 53.17 Section Header with Collapse Icon

Заголовок секции со сворачиванием.

```css
/* Header Container */
width: 240px; /* w-60 */
padding: 12px 16px; /* px-4 py-3 */
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Header Title */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Collapse Icon Button */
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;

/* Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Icon Shape (dot/cross) */
width: 8px;
height: 8px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Пример:** "Effects"

### 53.18 Summary: Icon Buttons & Navigation

| Элемент | Icon Size | Padding | Total Size | Background | Особенности |
|---------|-----------|---------|------------|------------|-------------|
| Small Icon Button | 16×16px | 4px | 24×24px | Surface-03 active | radius: 6px |
| Medium Icon Button | 20×20px | 6px | 32×32px | Surface-03 active | opacity: 0.8, radius: 6px |
| Toolbar Icon (Surface-03) | 16×16px | 8px | 32×32px | Surface-03 | radius: 8px |
| Toolbar Icon (Active) | 16×16px | 8px | 32×32px | Surface-01 | shadow elevation, radius: 8px |
| Toolbar Icon (Hover) | 16×16px | 8px | 32×32px | Surface-01 | no shadow, radius: 8px |
| Breadcrumb Default | - | 0 6px | auto | - | 16px/600/24px |
| Breadcrumb Active | - | 0 6px | auto | Surface-03 | chevron bg Shade-7-5/5 |
| Label Small Default | - | 2px 6px | auto | - | 12px/500, opacity 80% |
| Label Small Active | - | 2px 6px | auto | Surface-03 | 12px/500, opacity 70% |

### 53.19 Summary: Layer Panel Items

| State | Container Bg | Icon Container Bg | Outline | Shadow | Actions Icons |
|-------|--------------|-------------------|---------|--------|---------------|
| Active | Surface-03 | Surface-01 | Stroke-02 | Yes | Yes (3 icons) |
| Hover | Surface-03 | Surface-01 | No | No | Yes (3 icons) |
| Default | Surface-01 | Surface-03 | No | No | No |
| Compact Active | Surface-03 | Surface-01 | Stroke-02 | Yes | Chevron only |
| Compact Hover | Surface-03 | Surface-01 | No | No | No |
| Compact Default | Surface-01 | Surface-03 | No | No | No |

**Layer name:** 12px/500, Text-Primary, line-clamp: 1
**Action icons:** lock, hide, variations (всегда Text-Secondary)

### 53.20 Summary: Toggle & Sliders

| Element | Width | Background | Knob Position | Shadow/Border | Special |
|---------|-------|------------|---------------|---------------|---------|
| Toggle ON | 40px | Shade-9-70 70% | justify-end (right) | inset shadow | radius: 24px |
| Toggle OFF | 40px | Shade-4-100 | justify-start (left) | inset shadow | radius: 24px |
| Knob | 16×16px | Surface-02 | - | 3 shadows | radius: 24px |
| Slider 1 Track | 112×36px | Surface-03 | - | - | radius: 8px |
| Slider 1 Fill | flex: 1 | Shade-6-30 30% | - | - | radius: 8px |
| Slider 1 Thumb | 24×36px | Surface-02 | - | 3 shadows | radius: 6px |
| Slider 2 Track | 112×36px | Surface-03 | - | border Stroke-01 | radius: 8px |
| Slider 2 Fill | flex: 1 | Shade-6-50 50% | - | - | radius: 8px |
| Slider 2 Thumb | 24×36px | Surface-02 | - | 3 shadows (darker) | radius: 6px |

### 53.21 Summary: Timeline Components

| Element | Size | Background | Position | Special |
|---------|------|------------|----------|---------|
| Timeline Container | 208px | - | - | outline Stroke-01, radius: 12px |
| Frame Thumbnail | flex: 1×56px | - | - | 6 frames total |
| Scrubber Overlay | 48×56px | neutral-900/30 | absolute | backdrop-blur: 2px |
| Vertical Line | 0×56px | - | left: 4px or 48px | outline 1.5px Shade1-100 |
| Top Marker | 8×5px | Shade1-100 | top: 1px | radius: 0.75px |
| Bottom Marker | 8×5px | Shade1-100 | top: 54px | radius: 0.75px |

### 53.22 Usage Guidelines

**Icon Buttons:**
- Small (24×24px): для компактных UI и тулбаров с ограниченным пространством
- Medium (32×32px): для основных тулбаров и панелей
- Toolbar icons (32×32px): всегда padding 8px для большей зоны клика
- Active state: Surface-03 background или Surface-01 + shadow

**Breadcrumbs/Navigation:**
- Default: без фона, только текст
- Active: Surface-03 background
- Chevron в active state имеет фон Shade-7-5/5
- Max-width для текста: 176px (breadcrumb) или 208px (label)
- Всегда line-clamp: 1 для truncation

**Layer Panel Items:**
- Width всегда 208px (w-52) для full или 128px (w-32) для compact
- Active: Surface-03 + outline Stroke-02 + icon shadow
- Hover: Surface-03 + NO outline + NO icon shadow
- Default: Surface-01 + NO outline + NO icon shadow
- Icon container: Surface-01 в active/hover, Surface-03 в default
- Action icons (lock/hide/variations) появляются только в active/hover
- Compact version с chevron вместо action icons

**Toggle Switches:**
- Width всегда 40px, height auto (зависит от knob 16px + padding 4px)
- ON: Shade-9-70 70%, knob справа (justify-end)
- OFF: Shade-4-100, knob слева (justify-start)
- Knob всегда Surface-02 с 3 слоями теней
- inset shadow на контейнере для глубины

**Sliders:**
- Width обычно 112px, height 36px
- Style 1: light fill (Shade-6-30 30%), без border
- Style 2: dark fill (Shade-6-50 50%), с border Stroke-01
- Thumb всегда 24×36px Surface-02 с 3 тенями
- Fill и thumb двигаются вместе

**Timeline / Film Strip:**
- Container с outline Stroke-01, radius 12px
- Frames: flex: 1 для равной ширины, height 56px
- Scrubber с backdrop-blur 2px для читаемости
- Vertical line 1.5px Shade1-100 для четкости
- Markers сверху и снизу (8×5px) для точности позиционирования
- Два scrubber показывают in/out points

**Section Headers:**
- Border-top Stroke-01 для разделения секций
- Title 12px/600, Text-Primary
- Collapse icon 16×16px, Text-Secondary
- Padding 12px 16px для визуального баланса

**Icon Shapes in Layer Panel:**
- Lock: 10×12px (vertical)
- Eye: 14×10px (horizontal)
- Variations: 12×12px (square)
- Chevron: 4×8px (small vertical)
- All: 1.5px outline, Text-Secondary или Text-Primary

---

## 54. Segmented Controls / Tab Buttons / Asset Grids / Thumbnails

### 54.1 Tab Button - Active (Standalone)

Активная кнопка-таб без контейнера.

```css
/* Button - Active */
width: 96px; /* w-24 */
padding: 8px 12px; /* px-3 py-2 */
background: var(--Surface-01);
border-radius: 8px;
box-shadow:
  0px 1.25px 3px 0px rgba(50,50,50,0.10),
  inset 0px 1.25px 1px 0px rgba(255,255,255,1.00);
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Tab Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;
```

### 54.2 Tab Button - Default (Standalone)

Неактивная кнопка-таб без фона.

```css
/* Button - Default */
width: 112px; /* w-28 */
padding: 8px 12px; /* px-3 py-2 */
border-radius: 8px;
display: inline-flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Tab Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;
```

**Отличия:** нет фона, нет shadow, текст Text-Secondary.

### 54.3 Segmented Control - Container (Style 1)

Контейнер для segmented control с rounded-xl.

```css
/* Container */
flex: 1;
padding: 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 1px 1.9px 0px rgba(50,50,50,0.10);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
overflow: hidden;

/* Active Item */
flex: 1;
padding: 8px 12px; /* px-3 py-2 */
background: var(--Surface-01);
border-radius: 8px;
box-shadow:
  0px 1.25px 3px 0px rgba(50,50,50,0.10),
  inset 0px 1.25px 1px 0px rgba(255,255,255,1.00);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Active Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Inactive Item */
flex: 1;
padding: 8px 12px; /* px-3 py-2 */
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Inactive Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;
```

**Пример:** "Scene" / "Assets"

### 54.4 Segmented Control - Standalone (Style 1)

Segmented control без внешнего контейнера (padding).

```css
/* Container */
width: 208px; /* w-52 */
padding: 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 1px 1.9px 0px rgba(50,50,50,0.10);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
overflow: hidden;

/* Items styling - Same as 54.3 */
```

### 54.5 Segmented Control - Style 2 (Rounded-md)

Segmented control с меньшим border-radius (10px вместо 12px).

```css
/* Container */
width: 208px; /* w-52 */
padding: 4px;
background: var(--Surface-03);
border-radius: 10px;
box-shadow: inset 0px 1px 1.9px 0px rgba(50,50,50,0.10);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
overflow: hidden;

/* Active Item */
flex: 1;
padding: 6px 12px; /* px-3 py-1.5 */
background: var(--Surface-01);
border-radius: 6px;
box-shadow: 0px 1px 4px 0px rgba(0,0,0,0.14);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Active Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Inactive Item */
flex: 1;
padding: 6px 12px; /* px-3 py-1.5 */
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Inactive Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
font-family: 'Inter';
line-height: 16px;
```

**Отличия:**
- Container: radius 10px, outline Stroke-01
- Active: radius 6px, padding 6px 12px, shadow 0px 1px 4px
- Inactive: radius 8px, font weight 500

**Пример:** "Isometric" / "Perspective"

### 54.6 Asset Thumbnail - 3D Object (Default)

Превью 3D объекта в grid.

```css
/* Thumbnail Container */
flex: 1;
height: 96px; /* h-24 */
min-width: 96px; /* min-w-24 */
background: var(--Surface-03);
border-radius: 16px;
position: relative;
overflow: hidden;

/* Preview Image (Large - 88×88) */
width: 88px; /* w-20 = 80px, но в коде 88 */
height: 88px;
position: absolute;
left: 6px;
top: 6px;
object-fit: cover;
```

**Image size:** 88×88px с отступом 6px от краев контейнера 96px.

### 54.7 Asset Thumbnail - 3D Object (Selected/Hover)

Превью с border и inset shadow.

```css
/* Thumbnail Container - Selected */
flex: 1;
height: 96px; /* h-24 */
min-width: 96px; /* min-w-24 */
background: var(--Surface-03);
border-radius: 16px;
box-shadow: inset 0px 0px 0px 4px rgba(252,252,252,1.00);
outline: 1.5px solid rgba(var(--Shade-6-50), 0.5);
outline-offset: -1.5px;
position: relative;
overflow: hidden;

/* Preview Image */
width: 88px;
height: 88px;
position: absolute;
left: 6px;
top: 6px;
object-fit: cover;
```

**Selection indicator:**
- inset shadow: 4px white
- outline: 1.5px Shade-6-50/50

### 54.8 Asset Thumbnail - Material (Default)

Превью материала с меньшим изображением.

```css
/* Thumbnail Container */
flex: 1;
height: 96px; /* h-24 */
min-width: 96px; /* min-w-24 */
padding: 4px;
background: var(--Surface-03);
border-radius: 16px;
position: relative;
display: flex;
flex-wrap: wrap;
align-content: center;
overflow: hidden;

/* Preview Image (Medium - 64×64) */
width: 64px; /* w-16 */
height: 64px;
position: absolute;
left: 18px; /* centered: (96 - 64) / 2 = 16, но в коде 18 */
top: 18px;
object-fit: cover;
```

**Image size:** 64×64px центрировано в контейнере 96px.

### 54.9 Asset Grid Section (3D Objects)

Секция с заголовком и grid из thumbnails.

```css
/* Section Container */
display: inline-flex;
flex-direction: column;
overflow: hidden;

/* Section Header */
width: 240px; /* w-60 */
height: 48px; /* h-12 */
padding: 12px 16px; /* px-4 py-3 */
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Header Title */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600;
font-family: 'Inter';
line-height: 16px;

/* Chevron Icon Button */
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;

/* Chevron Icon */
width: 16px;
height: 16px;

/* Chevron Shape (down) */
width: 6px;
height: 2.99px;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Grid Container */
width: 240px; /* w-60 */
padding: 0 16px 16px 16px; /* px-4 pb-4 */
display: inline-flex;
flex-wrap: wrap;
align-content: flex-start;
gap: 8px;
```

**Grid pattern:** flex-wrap с gap 8px, thumbnails flex: 1 min-width 96px.

### 54.10 Asset Grid Section (Materials) - Blurred

Секция материалов с blur effect на grid.

```css
/* Grid Container - Blurred */
width: 240px; /* w-60 */
height: 320px; /* h-80 */
padding: 0 16px 16px 16px; /* px-4 pb-4 */
filter: blur(8px); /* blur-lg */
display: inline-flex;
flex-wrap: wrap;
align-content: flex-start;
gap: 8px;
```

**Special:** blur-lg (8px) применен для демонстрации.

### 54.11 Image Thumbnail - Small (64×64)

Маленький thumbnail изображения.

```css
/* Thumbnail - Default */
width: 64px; /* w-16 */
height: 64px; /* h-16 */
min-width: 64px; /* min-w-16 */
padding: 4px;
border-radius: 12px;
object-fit: cover;

/* Thumbnail - Hover/Selected */
width: 64px;
height: 64px;
min-width: 64px;
padding: 4px;
border-radius: 12px;
box-shadow: inset 0px 0px 0px 3px rgba(252,252,252,1.00);
border: 1.5px solid var(--Shade-6-100);
object-fit: cover;
```

**Selection indicator:**
- inset shadow: 3px white
- border: 1.5px Shade-6-100 (solid, не outline)

### 54.12 Image Thumbnail - Large (96×96)

Большой thumbnail изображения.

```css
/* Thumbnail - Default */
width: 96px; /* w-24 */
height: 96px; /* h-24 */
min-width: 64px; /* min-w-16 */
min-height: 64px; /* min-h-16 */
padding: 4px;
border-radius: 16px;
object-fit: cover;

/* Thumbnail - Hover/Selected */
width: 96px;
height: 96px;
min-width: 64px;
min-height: 64px;
padding: 4px;
border-radius: 16px;
box-shadow: inset 0px 0px 0px 3px rgba(252,252,252,1.00);
border: 1.5px solid var(--Shade-6-100);
object-fit: cover;
```

**Selection indicator:** аналогичен small, но с radius 16px.

### 54.13 Summary: Tab Buttons & Segmented Controls

| Type | Container Bg | Padding | Border Radius | Outline | Shadow | Special |
|------|--------------|---------|---------------|---------|--------|---------|
| **Tab Active** | Surface-01 | 8px 12px | 8px | - | 2 shadows | 12px/600 Primary |
| **Tab Default** | - | 8px 12px | 8px | - | - | 12px/600 Secondary |
| **Segmented Container 1** | Surface-03 | 4px | 12px | Stroke-02 | inset shadow | rounded-xl |
| **Segmented Active 1** | Surface-01 | 8px 12px | 8px | - | 2 shadows | 12px/600 Primary |
| **Segmented Inactive 1** | - | 8px 12px | 8px | - | - | 12px/600 Secondary |
| **Segmented Container 2** | Surface-03 | 4px | 10px | Stroke-01 | inset shadow | rounded-md |
| **Segmented Active 2** | Surface-01 | 6px 12px | 6px | - | 1 shadow | 12px/600 Primary |
| **Segmented Inactive 2** | - | 6px 12px | 8px | - | - | 12px/500 Secondary |

**Key differences:**
- Style 1: rounded-xl (12px), outline Stroke-02, padding 8px 12px
- Style 2: rounded-md (10px), outline Stroke-01, padding 6px 12px, inactive weight 500

### 54.14 Summary: Asset Thumbnails

| Type | Size | Image Size | Image Position | Border Radius | Selection Style |
|------|------|------------|----------------|---------------|-----------------|
| 3D Object Default | 96×96px | 88×88px | left: 6px, top: 6px | 16px | - |
| 3D Object Selected | 96×96px | 88×88px | left: 6px, top: 6px | 16px | inset 4px white + outline 1.5px Shade-6-50/50 |
| Material Default | 96×96px | 64×64px | left: 18px, top: 18px (centered) | 16px | - |
| Image Small Default | 64×64px | full | padding: 4px | 12px | - |
| Image Small Selected | 64×64px | full | padding: 4px | 12px | inset 3px white + border 1.5px Shade-6-100 |
| Image Large Default | 96×96px | full | padding: 4px | 16px | - |
| Image Large Selected | 96×96px | full | padding: 4px | 16px | inset 3px white + border 1.5px Shade-6-100 |

**Container:** всегда Surface-03 background

**Selection pattern:**
- inset shadow: 3px или 4px white
- outline/border: 1.5px Shade-6-50/50 или Shade-6-100

### 54.15 Summary: Grid Sections

| Element | Width | Padding | Border | Layout | Special |
|---------|-------|---------|--------|--------|---------|
| Section Header | 240px | 12px 16px | border-top Stroke-01 | justify-between | 12px/600 title + chevron |
| Grid Container | 240px | 0 16px 16px | - | flex-wrap, gap: 8px | align-content: flex-start |
| Grid Container Blurred | 240px×320px | 0 16px 16px | - | flex-wrap, gap: 8px | blur-lg (8px) |
| Thumbnail | flex: 1 | - | - | min-width: 96px | height: 96px |

### 54.16 Usage Guidelines

**Tab Buttons (Standalone):**
- Используйте без контейнера для простых табов
- Active: Surface-01 + 2 shadows + Text-Primary 600
- Default: transparent + Text-Secondary 600
- Padding: 8px 12px, radius: 8px
- Подходит для 2-3 табов без группировки

**Segmented Controls:**
- Используйте для переключения между 2-3 опциями
- Style 1 (rounded-xl): для основных UI элементов
- Style 2 (rounded-md): для компактных UI элементов
- Container всегда Surface-03 + inset shadow + outline
- Active item всегда Surface-01 + shadow + Text-Primary
- Inactive item transparent + Text-Secondary
- Items всегда flex: 1 для равной ширины

**Style 1 vs Style 2:**
- Style 1: radius 12/8px, Stroke-02, padding 8px 12px, inactive weight 600
- Style 2: radius 10/6px, Stroke-01, padding 6px 12px, inactive weight 500
- Style 2 более компактный и легкий

**Asset Thumbnails:**
- 3D Objects: изображение 88×88px с отступом 6px
- Materials: изображение 64×64px центрировано
- Всегда Surface-03 background
- Border-radius: 16px для 96px thumbnails, 12px для 64px
- Flex: 1 для адаптивности в grid
- Min-width: 96px для предотвращения сжатия

**Selection State:**
- 3D Objects: inset 4px white + outline 1.5px Shade-6-50/50
- Images: inset 3px white + border 1.5px Shade-6-100
- inset shadow создает "вырезанный" эффект
- outline/border для цветового акцента

**Grid Sections:**
- Width: 240px (w-60) стандарт для side panels
- Padding: 0 16px 16px для grid content
- Flex-wrap с gap: 8px для responsive layout
- Thumbnails автоматически переносятся на новую строку
- Section header: border-top + 12px/600 title + chevron icon

**Chevron Icons:**
- Down chevron: 6×2.99px для collapsed sections
- Up chevron: для expanded sections
- Всегда Text-Secondary, outline 1.5px

**Blur Effect:**
- blur-lg (8px) для демонстрации locked/disabled content
- Применяется к grid container, не к отдельным items

**Grid Layout Math:**
- 240px container - 32px padding (16px × 2) = 208px content
- 208px ÷ 2 items per row = 104px per item
- 104px - 8px gap = 96px thumbnail size
- Perfect fit для 2 columns с gap

---

## Section 55: 3D Editor Panels / Scene & Design Controls / Animation Settings

**Описание:**
Комплексная панельная система для 3D редактора включает следующие компоненты: панель Scene с иерархией объектов, панель Assets с 3D объектами и материалами, панели Design и Animation с настройками камеры, фона, эффектов и анимации, а также специализированные контролы для артборда и Tilt navigation. Все панели имеют единую ширину 240px с закругленными углами 20px и поддерживают различные состояния элементов (default, hover, active). Включены toggle switches для включения/выключения функций, segmented controls для переключения режимов, slider для distortion, timeline preview для loop анимации, и многоуровневые dropdown списки для lens и artboard настроек.

### 55.1. Panel Container

**Panel Container:**
```css
width: 240px;
height: 876px;
background: var(--Surface-01);
border-radius: 20px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
flex-direction: column;
justify-content: flex-start; /* Или space-between для Scene panel */
align-items: center;
overflow: hidden;
```

**Usage:**
- Контейнер для всех панелей редактора
- Высота 876px фиксированная для consistency
- Закругление 20px для modern look
- Outline внутри границ (offset -1px)

### 55.2. Panel Header

**Panel Header Container:**
```css
width: 100%; /* 240px */
padding: 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;
```

**Overlapping Avatars Group:**
```css
/* Container */
padding-left: 4px;
padding-right: 4px;
display: flex;
justify-content: flex-start;
align-items: center;

/* Avatar Image */
width: 32px;
height: 32px;
border-radius: 32px;
border: 2px solid var(--Surface-01);
position: relative;
margin-left: -8px; /* Для overlap, кроме первого */
```

**Share Button:**
```css
padding: 10px 24px; /* 2.5 × 6 */
background: linear-gradient(to bottom, #D4D4D4, #D4D4D4); /* neutral-200 */
border-radius: 12px;
box-shadow:
  0px 0px 0px 1px rgba(212,212,212,1.00),
  0px 3px 4px -1px rgba(0,0,0,0.15),
  inset 0px 1px 0px 0px rgba(255,255,255,0.33);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Button Text */
color: var(--Text-Primary);
font-size: 14px;
font-weight: 600; /* semibold */
line-height: 20px;
text-align: center;
```

**Usage:**
- Avatars overlap на 8px для компактности
- Border Surface-01 создает separation между avatars
- Share button с gradient и multiple shadows для elevation

### 55.3. Segmented Tab Control (Design/Animation, Scene/Assets)

**Tab Container:**
```css
width: 100%; /* 240px */
padding: 12px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;
```

**Segmented Control Wrapper:**
```css
flex: 1;
padding: 4px;
background: var(--Surface-03);
border-radius: 12px;
box-shadow: inset 0px 1px 1.9px 0px rgba(50,50,50,0.10);
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;
```

**Tab Item - Active:**
```css
flex: 1;
padding: 8px 12px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow:
  0px 1.25px 3px 0px rgba(50,50,50,0.10),
  inset 0px 1.25px 1px 0px rgba(255,255,255,1.00);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600; /* semibold */
line-height: 16px;
```

**Tab Item - Inactive:**
```css
flex: 1;
padding: 8px 12px;
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 600; /* semibold */
line-height: 16px;
```

**Usage:**
- Active tab имеет Surface-01 background + 2 shadows
- Inactive tab transparent с Text-Secondary
- Одинаковый font-weight (600) для обоих состояний

### 55.4. Section Header

**Section Header - Default:**
```css
width: 100%; /* 240px */
height: 48px;
padding: 12px 16px;
border-top: 1px solid var(--Stroke-01);
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Section Title */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600; /* semibold */
line-height: 16px;
```

**Collapse Icon Button:**
```css
padding: 4px;
border-radius: 6px; /* md */
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Plus Icon (collapsed) */
width: 8px;
height: 8px;
left: 4px;
top: 4px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Collapse Icon Button - Hover:**
```css
padding: 4px;
background: var(--Surface-03);
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;
```

**Usage:**
- Иконка появляется справа от section title
- Hover state добавляет Surface-03 background
- Opacity 0 можно использовать для скрытия иконки

### 55.5. Toggle Switch ON/OFF

**Toggle Container - ON:**
```css
width: 40px;
padding: 2px; /* 0.5 */
background: rgba(var(--Shade-9-70), 0.7);
border-radius: 24px; /* 3xl */
box-shadow: inset 0px 1px 0.6px 0px rgba(18,18,18,0.30);
display: flex;
justify-content: flex-end; /* Knob справа */
align-items: center;
gap: 8px;
overflow: hidden;
```

**Toggle Knob - ON:**
```css
width: 16px;
height: 16px;
background: var(--Surface-02);
border-radius: 24px;
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px 0px rgba(0,0,0,0.25),
  inset 0px 1px 0.5px 0px rgba(255,255,255,0.82);
```

**Toggle Container - OFF:**
```css
width: 40px;
padding: 2px;
background: var(--Shade-4-100);
border-radius: 24px;
box-shadow: inset 0px 1px 0.6px 0px rgba(18,18,18,0.30);
display: flex;
justify-content: flex-start; /* Knob слева */
align-items: center;
gap: 8px;
overflow: hidden;
```

**Usage:**
- ON: Shade-9-70/70 background, justify-end
- OFF: Shade-4-100 background, justify-start
- Knob одинаковый для обоих состояний

### 55.6. Project Header (Scene Panel)

**Project Header Container:**
```css
width: 100%; /* 240px */
padding: 12px 10px; /* 3 × 2.5 */
display: flex;
flex-direction: column;
justify-content: flex-start;
align-items: flex-start;
gap: 8px;
```

**Top Row (Logo + Settings):**
```css
width: 100%;
padding: 4px 6px; /* 1 × 1.5 */
display: inline-flex;
justify-content: space-between;
align-items: center;

/* Logo Container */
width: 32px;
height: 32px;
position: relative;
overflow: hidden;

/* Logo Fill (Square) */
width: 28px;
height: 28px;
left: 1px;
top: 1px;
position: absolute;
background: var(--Text-Primary);
outline: 0.25px solid var(--Text-Primary);
```

**Settings Icon Button:**
```css
padding: 6px; /* 1.5 */
border-radius: 6px;
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

/* Icon Shape */
width: 14px;
height: 14px;
left: 3.12px;
top: 3.12px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Project Info Section:**
```css
width: 100%;
display: flex;
flex-direction: column;
justify-content: flex-start;
align-items: flex-start;
```

**Project Title Row:**
```css
width: 100%;
border-radius: 6px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;

/* Title Container */
padding-left: 6px;
padding-right: 6px;
display: flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;

/* Title Text */
max-width: 176px; /* 44 × 4 */
color: var(--Text-Primary);
font-size: 16px;
font-weight: 600; /* semibold */
line-height: 24px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Chevron Icon (Title):**
```css
padding: 4px; /* 1 */
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Chevron Shape */
width: 6px;
height: 2.39px;
left: 5.33px;
top: 6.67px;
position: absolute;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

**Project Subtitle Row:**
```css
width: 100%;
padding: 2px 6px; /* 0.5 × 1.5 */
border-radius: 6px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
gap: 8px;
overflow: hidden;

/* Subtitle Text */
max-width: 208px; /* 52 × 4 */
opacity: 0.8;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Usage:**
- Logo 32×32px с fill 28×28px
- Title max-width 176px с line-clamp 1
- Subtitle opacity 80%, max-width 208px
- Settings icon справа вверху

### 55.7. Scene Item List

**Scene Item - Default:**
```css
width: 208px; /* 52 × 4 */
height: 40px;
padding: 4px 12px 4px 4px; /* 1 × 3 × 1 */
background: var(--Surface-01);
border-radius: 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;
```

**Scene Item - Hover:**
```css
width: 208px;
height: 40px;
padding: 4px 12px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;
```

**Scene Item - Active:**
```css
width: 208px;
height: 40px;
padding: 4px 12px 4px 4px;
background: var(--Surface-03);
border-radius: 12px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;
```

**Icon Container - Default:**
```css
padding: 8px; /* 2 */
background: var(--Surface-03);
border-radius: 8px;
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
```

**Icon Container - Hover:**
```css
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;
```

**Icon Container - Active:**
```css
padding: 8px;
background: var(--Surface-01);
border-radius: 8px;
box-shadow: 0px 0px 4px 0px rgba(18,18,18,0.10);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;
```

**Item Label:**
```css
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Action Icons Group (только на hover/active):**
```css
display: flex;
justify-content: center;
align-items: center;
gap: 12px; /* 3 */

/* Lock Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Lock Icon Shape */
width: 10px;
height: 12px;
left: 3.17px;
top: 1.83px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Eye Icon Shape */
width: 14px;
height: 10px;
left: 1.49px;
top: 3.17px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Variation Icon Shape */
width: 12px;
height: 12px;
left: 1.83px;
top: 1.83px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Usage:**
- **Default:** Surface-01, icon bg Surface-03
- **Hover:** Surface-03, icon bg Surface-01, NO outline
- **Active:** Surface-03, icon bg Surface-01 + shadow, WITH outline Stroke-02
- Action icons (lock/eye/variation) появляются только на hover/active

### 55.8. Search Bar with Keyboard Shortcut

**Search Bar Container:**
```css
width: 208px;
height: 40px;
padding: 4px 10px 4px 4px; /* 1 × 2.5 × 1 */
background: var(--Surface-01);
border-radius: 12px;
display: inline-flex;
justify-content: space-between;
align-items: center;
overflow: hidden;
```

**Search Input Area:**
```css
flex: 1;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 12px; /* 3 */

/* Icon Container */
width: 32px;
height: 32px;
border-radius: 8px;
overflow: hidden;

/* Search Icon */
width: 16px;
height: 16px;
left: 8px;
top: 8px;
position: absolute;
overflow: hidden;

/* Icon Shape */
width: 10px;
height: 10px;
left: 2.5px;
top: 2.5px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Placeholder Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
```

**Keyboard Shortcut Badge:**
```css
padding: 2px 6px; /* 0.5 × 1.5 */
background: var(--Surface-03);
border-radius: 6px;
box-shadow:
  0px 1px 4.2px -1px rgba(0,0,0,0.25),
  0px 0px 0px 1px rgba(0,0,0,0.11),
  inset 0px -1px 0.6px 0px rgba(0,0,0,0.20),
  inset 0px 2px 0.8px 0px rgba(255,255,255,0.27);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Shortcut Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
```

**Usage:**
- Keyboard shortcut badge с 4 layers shadows для depth
- "⌘ K" или другие shortcuts
- Icon opacity через Text-Secondary color

### 55.9. Camera Control (Isometric/Perspective)

**Camera Segmented Control Container:**
```css
width: 100%; /* full width of panel content */
height: 36px;
padding: 4px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;
```

**Camera Option - Active:**
```css
flex: 1;
padding: 6px 12px; /* 1.5 × 3 */
background: var(--Surface-01);
border-radius: 6px; /* md */
box-shadow: 0px 1px 4px 0px rgba(0,0,0,0.14);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600; /* semibold */
line-height: 16px;
```

**Camera Option - Inactive:**
```css
flex: 1;
padding: 6px 12px;
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
```

**Usage:**
- Отличается от Design/Animation tabs outline цветом (Stroke-01 вместо Stroke-02)
- Active border-radius 6px вместо 8px
- Inactive font-weight 500 вместо 600

### 55.10. Distortion Slider

**Slider Group Container:**
```css
width: 100%;
display: inline-flex;
justify-content: flex-start;
align-items: center;
gap: 6px; /* 1.5 */
```

**Slider Container:**
```css
width: 112px;
height: 36px;
position: relative;
```

**Slider Track:**
```css
width: 112px;
height: 36px;
left: 0;
top: 0;
position: absolute;
background: var(--Surface-03);
border-radius: 8px;
```

**Slider Fill + Thumb Group:**
```css
width: 56px; /* 50% fill */
height: 36px;
left: 0;
top: 0;
position: absolute;
display: inline-flex;
justify-content: flex-start;
align-items: center;
```

**Slider Fill:**
```css
flex: 1;
height: 36px;
background: rgba(var(--Shade-6-30), 0.3);
border-radius: 8px;
```

**Slider Thumb:**
```css
width: 24px;
height: 36px;
background: var(--Surface-02);
border-radius: 6px; /* md */
box-shadow:
  0px 1px 4px 0px rgba(0,0,0,0.14),
  0px 0px 2.6px -1px rgba(0,0,0,0.17),
  inset 0px -1px 4px -2px rgba(0,0,0,0.20);
```

**Value Display:**
```css
padding: 10px 12px 10px 10px; /* 2.5 × 3 × 2.5 × 2.5 */
background: var(--Surface-03);
border-radius: 10px;
display: flex;
justify-content: center;
align-items: center;
gap: 6px;
overflow: hidden;

/* Icon Container */
width: 16px;
height: 16px;
opacity: 0.7;
position: relative;
overflow: hidden;

/* Icon Shape (minus) */
width: 14px;
height: 6px;
left: 1.28px;
top: 5.33px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Value Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
text-align: right;
```

**Usage:**
- Slider width 112px, height 36px
- Fill width динамический (например 56px = 50%)
- Thumb 24px wide, 3 shadows для depth
- Icon opacity 70%

### 55.11. Background Color Picker

**Color Picker Container:**
```css
flex: 1;
padding: 4px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;
```

**Color Section (Left):**
```css
flex: 1;
border-right: 1px solid rgba(var(--Shade-7-10), 0.1);
display: flex;
justify-content: flex-start;
align-items: center;
gap: 12px; /* 3 */

/* Color Swatch */
width: 28px;
height: 28px;
background: #F4F4F4; /* zinc-100 или другой цвет */
border-radius: 6px;
border: 1px solid rgba(var(--Shade-7-10), 0.1);

/* Hex Value Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
```

**Opacity Section (Right):**
```css
padding-left: 12px;
padding-right: 12px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;

/* Opacity Number */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;

/* Percent Symbol */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
line-height: 16px;
```

**Usage:**
- Color swatch 28×28px с border
- Hex value слева от opacity
- Border-right разделяет секции

### 55.12. Artboard Preset Dropdown

**Artboard Preset Container:**
```css
width: 176px; /* 44 × 4 */
padding: 10px;
border-radius: 10px;
outline: 1px solid var(--Stroke-02);
outline-offset: -1px;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 8px;
overflow: hidden;
```

**Preset Content Area:**
```css
flex: 1;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 6px;

/* Icon Container */
width: 16px;
height: 16px;
opacity: 0.7;
position: relative;
overflow: hidden;

/* Icon Shape (artboard) */
width: 12px;
height: 10px;
left: 1.83px;
top: 2.5px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Dot (small circle in artboard icon) */
width: 0.67px;
height: 0.67px;
left: 11.33px;
top: 4.67px;
position: absolute;
background: var(--Text-Secondary);
border-radius: 24px;
outline: 0.5px solid var(--Text-Secondary);

/* Preset Name */
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Dimensions Display:**
```css
display: flex;
justify-content: flex-start;
align-items: center;
gap: 8px;

/* Dimensions Text (800x600) */
opacity: 0.5;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: right;
```

**Chevron Icon:**
```css
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Chevron Shape */
width: 6px;
height: 2.39px;
left: 5.33px;
top: 6.67px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Lock Icon Button:**
```css
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Lock Icon */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Lock Shape */
width: 10px;
height: 12px;
left: 3.17px;
top: 2px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Usage:**
- Preset dropdown 176px wide
- Dimensions opacity 50%
- Icon opacity 70%
- Chevron справа

### 55.13. Artboard Dimensions Input

**Dimensions Group:**
```css
width: 176px;
display: flex;
justify-content: flex-start;
align-items: flex-start;
gap: 6px;
```

**Dimension Input (W/H):**
```css
flex: 1;
padding: 10px 12px 10px 10px;
background: var(--Surface-03);
border-radius: 10px;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 6px;
overflow: hidden;

/* Label Icon Container */
width: 16px;
height: 16px;
opacity: 0.7;
position: relative;
overflow: hidden;

/* Label Text (W or H) */
left: 2px; /* или 3px для H */
top: 0;
position: absolute;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: right;

/* Value Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: right;
```

**Unit Icon Button:**
```css
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Unit Text (px) */
left: 1px;
top: 0;
position: absolute;
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: right;
```

**Usage:**
- W и H inputs равной ширины (flex: 1)
- Label icon opacity 70%
- Unit button справа

### 55.14. Loop Timeline Preview

**Timeline Container:**
```css
width: 100%; /* full width of section */
height: 56px;
border-radius: 12px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: inline-flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;
```

**Timeline Frame:**
```css
flex: 1;
height: 56px;
position: relative;

/* Frame Image */
flex: 1;
height: 56px;
object-fit: cover;
```

**Playhead Container (positioned over frames):**
```css
width: 48px;
height: 56px;
left: 156px; /* Позиция playhead, например 156px */
top: 0;
position: absolute;
```

**Playhead Background Blur:**
```css
width: 48px;
height: 56px;
left: 4px;
top: 0;
position: absolute;
background: rgba(23,23,23,0.3); /* neutral-900/30 */
backdrop-filter: blur(2px);
```

**Playhead Vertical Line:**
```css
width: 0;
height: 56px;
left: 4px;
top: 3px;
position: absolute;
outline: 1.5px solid var(--Shade1-100);
outline-offset: -0.75px;
```

**Playhead Top Marker:**
```css
width: 8px;
height: 5px;
left: 0;
top: 1px;
position: absolute;
background: var(--Shade1-100);
border-radius: 0.75px;
```

**Playhead Bottom Marker:**
```css
width: 8px;
height: 5px;
left: 0;
top: 54px;
position: absolute;
background: var(--Shade1-100);
border-radius: 0.75px;
```

**Timeline Start/End Markers (left: 0):**
```css
width: 48px;
height: 56px;
left: 0;
top: 0;
position: absolute;

/* Blur Background */
width: 48px;
height: 56px;
left: 0;
top: 0;
position: absolute;
background: rgba(23,23,23,0.3);
backdrop-filter: blur(2px);

/* Vertical Line */
width: 0;
height: 56px;
left: 48px; /* Справа для start, слева для end */
top: 3px;
position: absolute;
outline: 1.5px solid var(--Shade1-100);
outline-offset: -0.75px;

/* Top Marker */
width: 8px;
height: 5px;
left: 44px;
top: 1px;
position: absolute;
background: var(--Shade1-100);
border-radius: 0.75px;

/* Bottom Marker */
width: 8px;
height: 5px;
left: 44px;
top: 54px;
position: absolute;
background: var(--Shade1-100);
border-radius: 0.75px;
```

**Play Icon (на playhead):**
```css
width: 32px;
height: 32px;
left: -13px; /* Смещение для центрирования */
top: 13px;
position: absolute;

/* Icon Background (white) */
width: 16px;
height: 12px;
left: 9px;
top: 11px;
position: absolute;
background: white;

/* Icon Shape (black triangle) */
width: 14px;
height: 8px;
left: 10.41px;
top: 13.41px;
position: absolute;
background: black;
```

**Usage:**
- 6 frames (flex: 1 each) для равномерного распределения
- Playhead с backdrop-blur 2px
- Markers 8×5px сверху и снизу
- Vertical line Shade1-100

### 55.15. Loop Duration Control

**Duration Control Group:**
```css
width: 100%;
display: inline-flex;
justify-content: flex-start;
align-items: center;
gap: 6px;
```

**Segmented Control (Short/Long):**
```css
flex: 1;
padding: 4px;
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
justify-content: flex-start;
align-items: center;
overflow: hidden;

/* Active Item */
flex: 1;
padding: 6px 12px;
background: var(--Surface-01);
border-radius: 6px;
box-shadow: 0px 1px 4px 0px rgba(0,0,0,0.14);
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Active Text */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 600; /* semibold */
line-height: 16px;

/* Inactive Item */
flex: 1;
padding: 6px 12px;
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Inactive Text */
color: var(--Text-Secondary);
font-size: 12px;
font-weight: 500; /* medium */
line-height: 16px;
```

**Duration Value Display:**
```css
padding: 10px 12px 10px 10px;
background: var(--Surface-03);
border-radius: 10px;
display: flex;
justify-content: center;
align-items: center;
gap: 6px;
overflow: hidden;

/* Icon Container */
width: 16px;
height: 16px;
opacity: 0.7;
position: relative;
overflow: hidden;

/* Icon Shape (clock) */
width: 12px;
height: 12px;
left: 1.83px;
top: 1.83px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;

/* Duration Text (8s) */
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
line-height: 16px;
text-align: right;
```

**Usage:**
- Segmented control flex: 1 для заполнения пространства
- Value display справа с иконкой часов

### 55.16. Effects Grid (Small Thumbnails)

**Effects Grid Container:**
```css
width: 100%; /* full width of section */
padding: 16px;
padding-bottom: 16px;
display: inline-flex;
justify-content: flex-start;
align-items: flex-start;
gap: 8px;
flex-wrap: wrap;
align-content: flex-start;
```

**Effect Thumbnail - Small:**
```css
flex: 1;
height: 64px;
min-width: 64px;
padding: 4px;
border-radius: 12px;
object-fit: cover;
```

**Usage:**
- Small size: 64×64px (h-16, min-w-16)
- Padding 4px для внутреннего spacing
- Gap 8px между thumbnails
- Flex-wrap для grid layout

### 55.17. Lens Dropdown Options

**Lens Option - Default (Surface-01):**
```css
width: 176px;
padding: 10px;
background: var(--Surface-01);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 8px;
overflow: hidden;
```

**Lens Option - Selected (Surface-03):**
```css
width: 176px;
padding: 10px 8px 10px 10px; /* Разные отступы для иконок */
background: var(--Surface-03);
border-radius: 10px;
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 8px;
overflow: hidden;
```

**Option Content Area:**
```css
flex: 1;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 6px;

/* Inner Flex для текста */
flex: 1;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 6px;

/* Icon Container */
width: 16px;
height: 16px;
opacity: 0.7;
position: relative;
overflow: hidden;

/* Option Label */
flex: 1;
color: var(--Text-Primary);
font-size: 12px;
font-weight: 500;
line-height: 16px;
overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 1;
-webkit-box-orient: vertical;
```

**Chevron Icon (Right):**
```css
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Chevron Shape */
width: 6px;
height: 2.39px;
left: 5.33px;
top: 6.67px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Action Button (Eye Icon):**
```css
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Eye Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Eye Shape */
width: 14px;
height: 10px;
left: 1.49px;
top: 3.17px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Action Button (Minus Icon):**
```css
padding: 4px;
border-radius: 6px;
display: flex;
justify-content: center;
align-items: center;
gap: 8px;
overflow: hidden;

/* Minus Icon Container */
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Minus Shape */
width: 8px;
height: 0;
left: 4px;
top: 8px;
position: absolute;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Usage:**
- Default: Surface-01 background, outline Stroke-01
- Selected: Surface-03 background, outline Stroke-01
- Icon opacity 70%
- Action buttons справа

### 55.18. Tilt Control (Rotated)

**Tilt Control Container:**
```css
padding: 14px 20px; /* 3.5 × 5 */
transform: rotate(-90deg);
transform-origin: top left;
background: var(--Surface-01);
border-radius: 24px; /* 3xl */
box-shadow:
  0px 1px 1px 0px rgba(0,0,0,0.02),
  0px 3px 3px 0px rgba(0,0,0,0.02),
  0px 6px 3px 0px rgba(0,0,0,0.01),
  0px 10px 4px 0px rgba(0,0,0,0.00),
  0px 16px 4px 0px rgba(0,0,0,0.00);
outline: 1px solid var(--Stroke-01);
outline-offset: -1px;
display: flex;
justify-content: flex-start;
align-items: center;
gap: 12px;
```

**Left Arrow Icon:**
```css
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Arrow Shape (vertical line rotated) */
width: 0;
height: 8px;
left: 3.86px;
top: 2.53px;
position: absolute;
transform: rotate(-90deg);
transform-origin: top left;
outline: 1.5px solid var(--Text-Secondary);
outline-offset: -0.75px;
```

**Scale Ticks Group:**
```css
display: flex;
justify-content: flex-start;
align-items: center;
gap: 10px; /* 2.5 */
```

**Tick Mark - Small (opacity 30%):**
```css
width: 6px;
height: 0;
opacity: 0.3;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

**Tick Mark - Large (active):**
```css
width: 12px;
height: 0;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

**Right Arrow Icon:**
```css
width: 16px;
height: 16px;
position: relative;
overflow: hidden;

/* Arrow Shape (vertical line rotated) */
width: 0;
height: 8px;
left: 12.19px;
top: 2.53px;
position: absolute;
transform: rotate(90deg);
transform-origin: top left;
outline: 1.5px solid var(--Text-Primary);
outline-offset: -0.75px;
```

**Usage:**
- Rotated -90deg для vertical orientation
- Multiple box-shadows для subtle elevation
- Tick pattern: small (6px) - large (12px) - small - small - small - large - small
- Active ticks opacity 100%, inactive 30%

### 55.19. Summary Tables

**Panel Header Components:**
| Component | Width | Height | Background | Border/Outline | Notable Details |
|-----------|-------|--------|------------|----------------|-----------------|
| Avatar | 32px | 32px | - | 2px Surface-01 | Overlap -8px margin |
| Share Button | auto | 40px | gradient neutral-200 | 3 shadows | padding 10px 24px |

**Section Components:**
| Component | Width | Height | Background | State Indicator |
|-----------|-------|--------|------------|-----------------|
| Section Header | 240px | 48px | - | border-top Stroke-01 |
| Toggle ON | 40px | 20px | Shade-9-70/70 | justify-end |
| Toggle OFF | 40px | 20px | Shade-4-100 | justify-start |

**Scene Item States:**
| State | Background | Icon BG | Outline | Shadow | Actions Visible |
|-------|------------|---------|---------|--------|-----------------|
| Default | Surface-01 | Surface-03 | - | - | ❌ |
| Hover | Surface-03 | Surface-01 | - | - | ✅ |
| Active | Surface-03 | Surface-01 | Stroke-02 | 0px 0px 4px rgba(18,18,18,0.10) | ✅ |

**Slider Components:**
| Element | Width | Height | Background | Shadows |
|---------|-------|--------|------------|---------|
| Track | 112px | 36px | Surface-03 | - |
| Fill | variable | 36px | Shade-6-30/30 | - |
| Thumb | 24px | 36px | Surface-02 | 3 layers |

**Timeline Components:**
| Element | Width | Height | Background | Blur |
|---------|-------|--------|------------|------|
| Timeline | full | 56px | - | outline Stroke-01 |
| Frame | flex-1 | 56px | image | - |
| Playhead | 48px | 56px | neutral-900/30 | backdrop-blur 2px |
| Marker | 8px | 5px | Shade1-100 | - |

### 55.20. Usage Guidelines

**Panel Structure:**
```
Panel Container (240×876px)
├─ Panel Header (avatars + Share button)
├─ Tab Control (Design/Animation или Scene/Assets)
├─ Section 1 (border-top)
│  ├─ Section Header (title + collapse icon)
│  └─ Section Content
├─ Section 2 (border-top)
│  ├─ Section Header
│  └─ Section Content
└─ Bottom Section (например Search)
```

**Scene Item Hierarchy:**
1. **Default State:** Surface-01 bg, Surface-03 icon bg, NO action icons
2. **Hover State:** Surface-03 bg, Surface-01 icon bg, action icons VISIBLE
3. **Active State:** Surface-03 bg + outline Stroke-02, Surface-01 icon bg + shadow, action icons VISIBLE

**Slider Implementation:**
- Track всегда 112×36px, Surface-03
- Fill width = (value / max) × 112px
- Fill background Shade-6-30/30
- Thumb всегда 24px wide, позиция = fill width

**Timeline Loop:**
- Frames распределяются равномерно (flex: 1)
- Playhead width 48px с backdrop-blur
- Vertical line слева от playhead (offset 4px)
- Markers сверху (1px) и снизу (54px)

**Toggle Switch States:**
- **ON:** Shade-9-70/70 background, justify-end (knob справа)
- **OFF:** Shade-4-100 background, justify-start (knob слева)
- Knob одинаковый: 16×16px, Surface-02, 3 shadows

**Lens/Dropdown Options:**
- Default: Surface-01 + Stroke-01 outline
- Selected/Background: Surface-03 + Stroke-01 outline
- Icon opacity всегда 70%
- Action buttons только на selected items

**Color Picker:**
- Swatch 28×28px слева
- Hex value посередине
- Opacity справа (число + %)
- Border-right Shade-7-10/10 разделяет секции

**Artboard Controls:**
- Preset dropdown 176px с icon + name + dimensions
- Dimensions opacity 50%
- W/H inputs равной ширины (flex: 1)
- Lock icon и Unit icon справа

**Keyboard Shortcuts:**
- Badge: Surface-03 bg, 4 layers shadows
- Text: Text-Secondary, 12px medium
- Placement: справа в search bar

**Tilt Control:**
- Rotation: -90deg для vertical display
- Scale pattern: small-large-small-small-small-large-small
- Active ticks: 12px wide, opacity 100%
- Inactive ticks: 6px wide, opacity 30%

**Effects Grid:**
- Small thumbnails: 64×64px (h-16, min-w-16)
- Padding: 4px внутри thumbnail
- Gap: 8px между items
- Flex-wrap для responsive layout

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
