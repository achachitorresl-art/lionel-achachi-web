---
name: Lionel Professional Web Systems
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
  on-surface-variant: '#434653'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#737784'
  outline-variant: '#c3c6d5'
  surface-tint: '#2559bd'
  primary: '#00327d'
  on-primary: '#ffffff'
  primary-container: '#0047ab'
  on-primary-container: '#a5bdff'
  inverse-primary: '#b1c5ff'
  secondary: '#3d5ca2'
  on-secondary: '#ffffff'
  secondary-container: '#94b2fe'
  on-secondary-container: '#204287'
  tertiary: '#363636'
  on-tertiary: '#ffffff'
  tertiary-container: '#4d4d4d'
  on-tertiary-container: '#bebebe'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b1c5ff'
  on-primary-fixed: '#001946'
  on-primary-fixed-variant: '#00419e'
  secondary-fixed: '#dae2ff'
  secondary-fixed-dim: '#b1c5ff'
  on-secondary-fixed: '#001946'
  on-secondary-fixed-variant: '#224489'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 60px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
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
  section-gap-desktop: 128px
  section-gap-mobile: 64px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style
The design system is anchored in a philosophy of "Utilitarian Luxury"—a fusion of high-end editorial aesthetics and rigorous professional engineering. It targets local business owners who value reliability, clarity, and a modern edge. 

The visual direction is **Minimalist-Corporate**, utilizing heavy whitespace to signal premium service and solid, high-contrast foundations to build trust. The "Lionel" brand persona is characterized by precision, directness, and an absence of unnecessary decorative fluff. Every element serves a functional purpose, ensuring the UI feels intentional and authoritative.

## Colors
The palette is restricted to a tight range of "Power Blues" and absolute neutrals to maintain a professional atmosphere. 

- **Primary Blue (#0047AB):** Used for primary actions and key brand moments. It represents modern energy.
- **Deep Navy (#002D72):** Used for hover states of primary elements and secondary navigation accents.
- **Pure White & Solid Black:** These form the core of the high-contrast typography and layout structure, ensuring maximum readability.
- **Soft Gray (#F8F9FA):** Used exclusively for section background alternates to break up long-form content without introducing visual clutter.

## Typography
This design system utilizes **Inter** for its systematic, clean, and highly legible characteristics. 

The typographic hierarchy is aggressive. Large headlines use "Extra Bold" weights with tight letter spacing to create a sense of scale and confidence. Body text utilizes a generous 1.6x to 1.7x line-height to ensure local business clients can easily digest service descriptions and value propositions. Labels are capitalized and tracked out slightly to differentiate from standard body copy.

## Layout & Spacing
The system follows a **Fixed Grid** approach for Desktop to maintain the "Lionel" brand's structured feel, while transitioning to a fluid single-column layout for Mobile.

- **Desktop:** 12-column grid with a 1200px max-width. Large vertical gaps (128px) between sections are mandatory to signify "premium" positioning through whitespace.
- **Mobile:** Elements should occupy the full width of the screen minus the 16px side margins. 
- **Rhythm:** All spacing (padding, margins) must be a multiple of the 8px base unit to ensure mathematical harmony.

## Elevation & Depth
To maintain the minimalist aesthetic, depth is used sparingly. 

The system relies on **Tonal Layers** (White surfaces on Gray backgrounds) and **Subtle Ambient Shadows**. Shadows should have a large blur radius (20px+) but very low opacity (3-5%) to avoid looking "heavy" or dated. Outlines are avoided; instead, depth is created by the contrast between white containers and the #F8F9FA background.

## Shapes
A "Rounded" strategy (8px - 12px) is applied to soften the professional edges of the deep blue and black palette. This makes the agency feel approachable rather than overly institutional.

- **Buttons & Inputs:** 8px radius.
- **Cards & Containers:** 12px radius.
- **Interactive States:** Subtle scale-up transitions (1.02x) reinforce the tactile nature of the UI.

## Components
- **Buttons:** Primary buttons are Solid Blue (#0047AB) with White text, using an 8px radius. Secondary buttons use a Solid Black border with no fill.
- **Input Fields:** Use a subtle #F8F9FA background with an 8px radius and a 2px blue border only on focus.
- **Cards:** White backgrounds, 12px radius, and a "Soft Ambient Shadow" to separate them from the light gray page background.
- **Chips/Tags:** Used for "Services" or "Industries," featuring a light blue tint (#E6EFFF) with navy text for high legibility.
- **Icons:** Use 2px stroke-width minimalist line icons. Icons should always be the Primary Blue or Solid Black.
- **Lists:** Bullet points are replaced with custom Blue checkmarks to emphasize "completion" and "results" for business clients.