---
name: Hydro-Professional Service System
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
  on-surface-variant: '#43474e'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#73777f'
  outline-variant: '#c3c6cf'
  surface-tint: '#436084'
  primary: '#002444'
  on-primary: '#ffffff'
  primary-container: '#1a3a5c'
  on-primary-container: '#87a4cc'
  inverse-primary: '#abc9f2'
  secondary: '#835500'
  on-secondary: '#ffffff'
  secondary-container: '#feae2c'
  on-secondary-container: '#6b4500'
  tertiary: '#002152'
  on-tertiary: '#ffffff'
  tertiary-container: '#00367b'
  on-tertiary-container: '#7ba2f2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#abc9f2'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#2a486b'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#ffb955'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#aec6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#12448f'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
  emergency-red: '#D13131'
  surface-gray: '#F8FAFC'
  deep-navy: '#102A43'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Open Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1200px
---

## Brand & Style
The brand personality is rooted in **unwavering reliability** and **technical precision**. As a professional plumbing service, the UI must project expertise and urgency without sacrificing calm authority. The target audience includes homeowners and businesses in Santiago who require immediate, trustworthy solutions for critical infrastructure.

The design style is **Corporate / Modern**, leaning into high-utility layouts and structural clarity. It emphasizes high-contrast visual hierarchies to ensure that emergency contact information and service categories are instantly digestible. The aesthetic is clean and "tech-savvy," utilizing subtle gradients and crisp iconography to bridge the gap between traditional manual trade and modern digital service excellence.

## Colors
The palette is dominated by **Navy Blue (#1A3A5C)**, a color chosen to evoke stability, professionalism, and depth. This is paired with an energetic **Yellow-Orange (#F5A623)**, reserved strictly for action-oriented elements and urgent calls to action. 

A secondary blue (#204D98) is used for decorative accents and iconography to provide tonal variety. The background remains a crisp white to ensure maximum readability, while the neutral near-black (#2C2C2C) is utilized for body text to maintain high contrast. The "Emergency Red" is introduced as a functional utility color for critical alerts or "24/7" indicators.

## Typography
The typographic system uses a pairing of **Montserrat** for headlines and **Open Sans** for body copy. Montserrat’s geometric construction provides a modern, architectural feel that reinforces the "professional" and "tech-savvy" brand pillars. Headlines should utilize bold weights and tight letter-spacing to convey impact and urgency.

Open Sans is used for all long-form content and UI labels to ensure accessibility and legibility. For mobile devices, headline sizes scale down to prevent excessive line-breaking, ensuring that critical service titles remain visible "above the fold." All labels use uppercase styling with increased letter-spacing to create a clear distinction from body text.

## Layout & Spacing
The design system employs a **Fixed Grid** model for desktop to maintain a structured, organized appearance, transitioning to a fluid layout for mobile devices. A 12-column grid is used for desktop (64px margins), while a 4-column grid is used for mobile (16px margins).

Spacing follows a strict 8px base unit rhythm. Generous vertical padding between sections (80px - 120px) is used to create a sense of premium service and organized information architecture. Contact modules and "Request a Quote" forms should be anchored or pinned in prominent positions to facilitate quick user conversion during plumbing emergencies.

## Elevation & Depth
Depth is communicated through **Tonal Layers** and **Ambient Shadows**. Surfaces are primarily flat, but key interactive elements like service cards and booking forms use soft, diffused shadows (0px 4px 20px rgba(26, 58, 92, 0.08)) to lift them from the background.

To reinforce the tech-savvy positioning, use "Surface-Container" tiers: the main background is white, while secondary functional areas (like calculators or testimonials) use a subtle "Surface-Gray" tint. Borders are kept thin and low-contrast except when defining the primary call-to-action area, where the secondary orange color provides the visual "pop."

## Shapes
The shape language is **Soft (0.25rem)**, striking a balance between the precision of engineering and the approachability of a home service. While circular elements (pill shapes) are used for "Emergency" tags and small badges, the primary containers and buttons use subtle rounding. This architectural approach feels more grounded and "serious" than fully rounded, playful designs.

## Components
- **Buttons:** The primary button is Solid Orange (#F5A623) with white Montserrat Bold text, designed for maximum visibility. The secondary button is an "Outline Navy" style for less urgent actions.
- **Service Cards:** Use a white background with a subtle 1px border. Feature a clean line icon in Navy Blue at the top, followed by a Bold Headline and a short description.
- **Input Fields:** Use a 1px solid gray border that transitions to Navy Blue on focus. Labels should always be visible above the field for clarity during stressful (emergency) user flows.
- **Urgency Banner:** A thin, high-contrast bar at the very top of the viewport (Primary Navy background) containing a clicking phone number and "Available 24/7" status.
- **Trust Badges:** Small, monochromatic icons placed near conversion points to highlight "Certified Technicians" or "Guaranteed Work."
- **Status Indicators:** Use a pulse animation for "Active Now" or "Technician Nearby" indicators to enhance the tech-driven service feel.