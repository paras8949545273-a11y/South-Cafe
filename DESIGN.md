---
name: Heritage Hearth
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#56423d'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#89726c'
  outline-variant: '#dcc1ba'
  surface-tint: '#9c432a'
  primary: '#812f18'
  on-primary: '#ffffff'
  primary-container: '#a0462d'
  on-primary-container: '#ffd4c9'
  inverse-primary: '#ffb5a1'
  secondary: '#7c5800'
  on-secondary: '#ffffff'
  secondary-container: '#ffc247'
  on-secondary-container: '#715000'
  tertiary: '#2c522d'
  on-tertiary: '#ffffff'
  tertiary-container: '#446a43'
  on-tertiary-container: '#bde8b8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a1'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#7d2c15'
  secondary-fixed: '#ffdea7'
  secondary-fixed-dim: '#f9bc41'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5e4200'
  tertiary-fixed: '#c2eebd'
  tertiary-fixed-dim: '#a7d2a3'
  on-tertiary-fixed: '#002105'
  on-tertiary-fixed-variant: '#2a4f2b'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 20px
---

## Brand & Style

The design system is rooted in the concept of "Modern Heritage." It balances the soulful, rhythmic traditions of South Indian culture with the frictionless efficiency of a contemporary digital ordering platform. The personality is hospitable and grounded, designed to evoke the warmth of a home-cooked meal served on a banana leaf, but presented through a polished, high-end editorial lens.

The visual style follows a **Tactile / Minimalist** hybrid approach. It utilizes high-quality imagery and organic textures—such as wood grains and hammered brass—to provide a sense of physical space, while maintaining generous whitespace and a structured grid to ensure the user journey remains focused and efficient. The goal is to make the user feel welcomed into a physical "South Cafe" location the moment the app or site loads.

## Colors

The palette is derived from the natural materials and spices of South India. 

- **Primary (Terracotta):** A deep, earthy red used for primary actions and brand presence. It signifies the clay pots and traditional architecture.
- **Secondary (Turmeric):** A vibrant yellow used for highlights, badges, and secondary buttons, reflecting the warmth of Indian spices.
- **Tertiary (Banana Leaf):** A muted, deep green used for success states and dietary indicators (e.g., vegetarian marks).
- **Neutral (Cream):** An off-white background color that provides a softer, more organic feel than pure white, reducing eye strain and enhancing the "traditional" paper-like aesthetic.
- **Rich Wood:** Used for high-contrast text and structural elements to provide grounding and depth.

## Typography

This design system employs a sophisticated typographic pairing to bridge the gap between tradition and modern utility.

- **Headlines (Noto Serif):** Chosen for its timeless, elegant proportions. The serif adds a literary and authoritative quality that evokes traditional South Indian signage and menus.
- **Body & Labels (Be Vietnam Pro):** This sans-serif is approachable and contemporary. It offers exceptional legibility at small sizes, crucial for menu descriptions and nutritional information.

Use all-caps for labels and captions with slight tracking (0.05em) to create a clean, organized hierarchy in the navigation and metadata sections.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model on desktop (12-column) and a **Fluid Grid** on mobile (4-column). A rhythmic 8px spacing system ensures consistency across all components.

- **Margins:** Large outer margins (48px+) on desktop are encouraged to create a premium, editorial feel.
- **Visual Rhythm:** Use `lg` and `xl` spacing for section breaks to allow the photography to "breathe." 
- **Information Density:** For the menu grid, use `md` (24px) gutters to prevent the interface from feeling cluttered, maintaining a relaxed, hospitable pace.

## Elevation & Depth

To maintain the tactile nature of the brand, depth is communicated through **Tonal Layers** and **Soft Ambient Shadows**.

- **Surfaces:** Use subtle shifts in background color (Cream to a slightly darker Sand) to define card areas instead of heavy shadows.
- **Shadows:** When used (e.g., on primary buttons or floating carts), shadows should be long, soft, and tinted with the Primary Terracotta or Wood Brown colors rather than pure black. This prevents the UI from looking "digital" and keeps it feeling organic.
- **Depth Cues:** Brass-colored dividers and subtle Kolam patterns in the background act as "low-depth" layers that anchor the content without distracting the user.

## Shapes

The shape language is **Soft (0.25rem - 0.75rem)**. 

While the food and culture are organic, the digital experience requires structure. We use "Soft" rounded corners to mimic the weathered edges of old wood or polished stone. 

- **Cards & Inputs:** Use `rounded-lg` (0.5rem) to provide a friendly but stable container.
- **Buttons:** Use `rounded-lg` for a solid, architectural feel.
- **Imagery:** High-quality food photography should occasionally use circular or "arched" masking, reminiscent of traditional temple doorways, to add a distinct brand signature.

## Components

- **Buttons:** Primary buttons use a solid Terracotta background with Cream text. Secondary buttons use a brass-colored outline. All buttons should have a slight 1px inner highlight to suggest a subtle 3D "pressed" quality.
- **Chips:** Used for dietary filters (e.g., Vegan, Spicy). These should have a subtle Banana Leaf Green border and a soft cream background.
- **Cards:** Menu item cards are the hero. They should feature a full-bleed image at the top, Noto Serif titles, and a Turmeric Yellow price label.
- **Input Fields:** Fields use a 1px Wood Brown border that thickens to 2px on focus. The background is a very faint cream tint to distinguish from the page background.
- **Kolam Dividers:** Use subtle, vector-based Kolam patterns as section dividers instead of simple lines to reinforce the South Indian identity.
- **Cart/Checkout:** The persistent "Floating Cart" should use a dark Wood Brown background with Turmeric Yellow text for high-contrast visibility and a premium "brass-accented" feel.