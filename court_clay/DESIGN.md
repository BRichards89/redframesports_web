---
name: Court & Clay
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#414846'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#717976'
  outline-variant: '#c1c8c4'
  surface-tint: '#43655c'
  primary: '#01261f'
  on-primary: '#ffffff'
  primary-container: '#1a3c34'
  on-primary-container: '#83a69c'
  inverse-primary: '#aacec3'
  secondary: '#8e4e11'
  on-secondary: '#ffffff'
  secondary-container: '#fda865'
  on-secondary-container: '#753c00'
  tertiary: '#361812'
  on-tertiary: '#ffffff'
  tertiary-container: '#4f2d26'
  on-tertiary-container: '#c4948a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c5eadf'
  primary-fixed-dim: '#aacec3'
  on-primary-fixed: '#00201a'
  on-primary-fixed-variant: '#2b4d44'
  secondary-fixed: '#ffdcc4'
  secondary-fixed-dim: '#ffb780'
  on-secondary-fixed: '#2f1400'
  on-secondary-fixed-variant: '#6f3800'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#efbab0'
  on-tertiary-fixed: '#30130d'
  on-tertiary-fixed-variant: '#623d36'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is engineered for **Red Frame Sports**, a tennis tech startup that balances logistics-driven efficiency with the vibrant energy of the tennis community. The brand personality is athletic, authoritative, yet approachable, mirroring the focused intensity of a match and the social camaraderie of the clubhouse.

The visual style is **Corporate / Modern** with a **Tactile** edge. It utilizes clean lines and high-performance typography while subtly nodding to the textures of the sport—the fuzz of a ball, the grit of a clay court, and the crisp white lines of the grass. The aesthetic is professional and utilitarian, ensuring that data-heavy logistics feel organized and frictionless.

**Core Principles:**
- **Precision:** Alignment and spacing must reflect the exactitude of the court.
- **Vibrancy:** The "Volt" accent is used sparingly to draw focus to primary actions and live status updates.
- **Stability:** Deep greens and earth tones provide a grounded, trustworthy foundation.

## Colors

The palette is derived directly from the physical environments of tennis. 

- **Primary (Forest Green):** Used for headers, primary navigation backgrounds, and deep structural elements. It represents the traditional grass court and provides a professional, "club" feel.
- **Secondary (Clay Brown):** Used for supporting elements, categories, or specialized "clay-season" features. It adds warmth and groundedness to the UI.
- **Accent (Volt Yellow):** Reserved strictly for call-to-action buttons, active states, and critical notifications. Its high visibility against the dark green ensures immediate recognition.
- **Neutrals:** An off-white (#F9F8F6) serves as the primary canvas to reduce glare, while charcoal gray (#2D2D2D) provides high-legibility for body text.

## Typography

This design system uses **Hanken Grotesk** as its primary typeface. It is a sharp, contemporary sans-serif that communicates precision and technical efficiency. For headlines, tighter letter-spacing and heavier weights are used to mimic the bold impact of sports broadcasting.

**JetBrains Mono** is introduced for labels, data points, and logistical "meta" information (e.g., match times, court numbers, scores). This monospaced choice reinforces the "tech" aspect of the startup and ensures that numerical data is perfectly aligned and readable at a glance.

**Hierarchy Guidance:**
- Use **Display** for landing page heroes and major section headers.
- Use **Label-Caps** for category tags, overlines, and table headers.
- Maintain ample line-height in body text to ensure readability during active, on-the-go use.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** approach for desktop to maintain the organized, "logistics-first" feel, while transitioning to a fluid model on mobile. 

**Grid System:**
- **Desktop:** 12-column grid with a 1280px max-width. Gutters are fixed at 24px to provide "breathing room" between data modules.
- **Tablet:** 8-column grid with 20px gutters and 24px side margins.
- **Mobile:** 4-column fluid grid. Side margins are reduced to 16px to maximize horizontal space for scoreboards and schedules.

**Rhythm:**
All spacing is based on an **8px baseline grid**. Components like cards and inputs should use 16px or 24px internal padding to maintain a consistent athletic "heft" without feeling cramped.

## Elevation & Depth

This design system uses **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows to maintain a clean, modern aesthetic. 

- **Surface Levels:** The base background is the off-white neutral. "Cards" and "Containers" sit one level above, using pure white (#FFFFFF) with a very thin (1px) border in a lightened version of the Primary Green at 10% opacity.
- **Depth:** High-priority elements (like the current active match card) use a subtle **Ambient Shadow**: a soft, 12% opacity forest green tint that feels like a natural shadow on a court surface.
- **Interactive States:** Hovering over an interactive element should not increase its shadow, but rather shift its background color or add a 2px Volt Yellow bottom border to signal "focus."

## Shapes

The shape language is **Rounded**, reflecting the geometry of the tennis ball and the curves of the "Double Bagel" logo. 

- **Standard Elements:** Buttons, input fields, and small cards use a 0.5rem (8px) corner radius. This provides a friendly, approachable feel while remaining structured.
- **Feature Elements:** Large dashboard containers or profile avatars use `rounded-xl` (1.5rem) to create a softer, "lifestyle" look.
- **Circular Accents:** Status indicators, notification badges, and the logo itself are kept perfectly circular (pill-shaped or full circles) to emphasize the tennis ball motif.

## Components

**Buttons:**
- **Primary:** Forest Green background with White text. Bold weight.
- **CTA:** Volt Yellow background with Forest Green text. Used for "Book Now" or "Start Match."
- **Ghost:** Transparent background with a 2px Forest Green border.

**Inputs & Fields:**
- Use a solid white background with a 1px border. On focus, the border thickens to 2px and changes to the Clay Brown color to provide a clear, warm focus state.

**Chips & Tags:**
- Used for "Court Surface" or "Skill Level." These should have a slight background tint (e.g., a very light tan for clay, a light green for grass) with the Primary or Secondary color for the text.

**Cards:**
- Main layout containers for matches and events. Use a white background, 8px radius, and a subtle border. Headers within cards should use the Forest Green background for high-contrast separation.

**Progress Indicators:**
- Linear bars use a light gray track with a Volt Yellow fill to represent match progress or capacity.