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

/* Warning / Hot */
--color-warning: #F59E0B;
--color-warning-bg: #FEF3C7;
--color-warning-border: #FCD34D;

/* Info */
--color-info: #3B82F6;
--color-info-bg: #DBEAFE;
--color-info-border: #93C5FD;
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

/* Stroke / Borders */
--color-border-primary: #E5E7EB;
--color-border-secondary: #D1D5DB;
--color-border-focus: #3B82F6;
--color-border-disabled: #F3F4F6;

/* Shades */
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

#### Primary Button

**Size:**
- **Small:** Height 32px, Padding 8px 12px, Font-size 14px
- **Medium:** Height 40px, Padding 10px 16px, Font-size 16px
- **Large:** Height 48px, Padding 12px 24px, Font-size 18px

**Radius:** `var(--radius-md)` (6px)

**States:**
- **Default:** `background: var(--color-primary); color: white`
- **Hover:** `background: var(--color-primary-hover); shadow: var(--shadow-button-hover)`
- **Active:** `background: var(--color-primary-active); shadow: var(--shadow-button-active)`
- **Disabled:** `opacity: 0.5; cursor: not-allowed`

#### Secondary Button

**Size:** Same as Primary
**Radius:** `var(--radius-md)` (6px)

**States:**
- **Default:** `background: var(--color-secondary); color: white`
- **Hover:** `background: var(--color-secondary-hover)`

#### Outline Button

- **Border:** `2px solid var(--color-primary)`
- **Background:** `transparent`

**States:**
- **Hover:** `background: var(--color-primary-light)`

#### Ghost Button

- **Background:** `transparent`

**States:**
- **Hover:** `background: var(--color-bg-secondary)`

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

**Версия:** 1.0.0
**Последнее обновление:** 2025-11-18
**Мейнтейнеры:** Design & Engineering Team
