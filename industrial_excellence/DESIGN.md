---
name: Industrial Excellence
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#43474e'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#50606f'
  on-secondary: '#ffffff'
  secondary-container: '#d1e1f4'
  on-secondary-container: '#556474'
  tertiary: '#000707'
  on-tertiary: '#ffffff'
  tertiary-container: '#002323'
  on-tertiary-container: '#2c9494'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#d4e4f6'
  secondary-fixed-dim: '#b8c8da'
  on-secondary-fixed: '#0d1d2a'
  on-secondary-fixed-variant: '#394857'
  tertiary-fixed: '#93f2f2'
  tertiary-fixed-dim: '#76d6d5'
  on-tertiary-fixed: '#002020'
  on-tertiary-fixed-variant: '#004f4f'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max-width: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 80px
---

## Brand & Style

This design system is engineered for a global B2B chemical supplier, prioritizing authority, precision, and high-trust communication. The brand personality is rooted in industrial reliability and scientific expertise. 

The visual style follows a **Corporate Modern** aesthetic with **Minimalist** influences. It utilizes a structured hierarchy and generous whitespace to convey transparency and efficiency, essential for international trade and hazardous material documentation. The interface should feel "export-ready"—stable, organized, and devoid of unnecessary decorative flourishes. Every element serves a functional purpose, reflecting the rigorous standards of the chemical industry.

## Colors

The color palette is anchored in a deep **Dark Navy (#001F3F)**, representing corporate stability and institutional trust. **Slate Grey (#708090)** provides a neutral, industrial bridge for secondary information and UI borders. 

A controlled application of **Teal (#008080)** serves as the primary action and accent color, subtly referencing laboratory environments and chemical innovation. The background remains a pristine **White (#FFFFFF)** to ensure maximum legibility for technical data, with a very light neutral grey used for section layering. This palette avoids "salesy" vibrancy in favor of a professional, subdued tone.

## Typography

The design system utilizes **Inter** exclusively to maintain a systematic and utilitarian feel. As a high-trust sans-serif, it provides exceptional legibility for complex chemical names and logistical data. 

Headlines are set with tighter letter spacing and heavier weights to command authority. Body text utilizes a standard 16px base for optimal reading comfort. Labels and technical metadata are occasionally rendered in uppercase with increased letter spacing to differentiate them from prose, mimicking the look of industrial packaging and specification sheets.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop to maintain a consistent, authoritative structure across different viewports. A 12-column grid is used with 24px gutters to allow for complex data layouts—such as product specifications and safety data sheets—without visual clutter.

On mobile devices, the layout reflows into a single column with 20px side margins. Spacing follows a strict 8px base unit, ensuring a mathematical rhythm throughout the interface. Generous section padding (80px+) is used to separate distinct service areas, preventing the dense information from feeling overwhelming to the user.

## Elevation & Depth

Visual hierarchy is established through **low-contrast outlines** and **tonal layering** rather than aggressive shadows. This reinforces the "sharp" and "precise" industrial theme.

Surfaces use a 1px border in Slate Grey at low opacity (20%) to define boundaries. Where depth is required—such as for hovering over product cards or technical modules—a subtle, "stamped" shadow is applied: 
- **Shadow:** `0px 4px 12px rgba(0, 31, 63, 0.08)`
This shadow is tinted with the Primary Navy color to ensure it feels integrated with the brand palette. Backdrop blurs are used sparingly for navigation overlays to maintain focus on the content beneath.

## Shapes

To align with the "sharp borders" requirement of an industrial supplier, this design system uses a **Soft (0.25rem / 4px)** roundedness level. This subtle rounding prevents the UI from feeling dated or hostile while maintaining a precise, engineered appearance.

Higher radius values (like pill shapes) are strictly prohibited, as they evoke a consumer-grade friendliness that conflicts with the serious nature of chemical distribution. Containers and large cards may use a slightly larger `rounded-lg` (8px) for structural definition, but standard components like inputs and buttons must remain at the 4px standard.

## Components

### Buttons
Primary buttons use the Dark Navy background with White text for maximum contrast. Secondary buttons use a Slate Grey outline. Action-oriented "Contact" or "Inquiry" buttons may use the Teal accent. All buttons feature a 4px corner radius and no gradients.

### Inputs & Search
Form fields are defined by a 1px Slate Grey border. The focus state uses a 2px Dark Navy border. Label text is positioned strictly above the field in a bold, `label-sm` style.

### Data Cards
Product modules (Chemical compounds, Industry solutions) are housed in cards with a white background and a subtle 1px border. They do not display prices; instead, they focus on "Technical Specifications" and "Request Quote/Inquiry" calls to action.

### Status Indicators
For chemical safety or availability, small rectangular chips are used. They use the Teal accent for positive status and a muted Slate for neutral/archived data.

### Lists
Technical lists (CAS numbers, physical properties) use a striped row format (Zebra striping) with a 5% opacity Navy fill for alternate rows, ensuring high readability for tabular data.