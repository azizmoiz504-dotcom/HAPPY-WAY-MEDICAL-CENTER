---
name: Happy Way Medical Center Design System
colors:
  surface: '#f8f9ff'
  surface-dim: '#d1dbec'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dfe9fa'
  surface-container-highest: '#d9e3f4'
  on-surface: '#121c28'
  on-surface-variant: '#424752'
  inverse-surface: '#27313e'
  inverse-on-surface: '#eaf1ff'
  outline: '#727783'
  outline-variant: '#c2c6d4'
  surface-tint: '#005db6'
  primary: '#00478d'
  on-primary: '#ffffff'
  primary-container: '#005eb8'
  on-primary-container: '#c8daff'
  inverse-primary: '#a9c7ff'
  secondary: '#006a6a'
  on-secondary: '#ffffff'
  secondary-container: '#8cf3f3'
  on-secondary-container: '#007070'
  tertiary: '#41484f'
  on-tertiary: '#ffffff'
  tertiary-container: '#596067'
  on-tertiary-container: '#d4dbe2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#a9c7ff'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#00468c'
  secondary-fixed: '#8cf3f3'
  secondary-fixed-dim: '#6fd7d6'
  on-secondary-fixed: '#002020'
  on-secondary-fixed-variant: '#004f4f'
  tertiary-fixed: '#dce3eb'
  tertiary-fixed-dim: '#c0c7cf'
  on-tertiary-fixed: '#151c22'
  on-tertiary-fixed-variant: '#40484e'
  background: '#f8f9ff'
  on-background: '#121c28'
  surface-variant: '#d9e3f4'
typography:
  h1:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin: 32px
  section-gap: 80px
---

## Brand & Style
The design system is anchored in the balance between clinical precision and human empathy. It is designed to evoke a sense of immediate relief and long-term trust for patients and healthcare providers alike. The visual language avoids the cold, sterile atmosphere of traditional medicine, opting instead for a "Soft Minimalism" approach—where high-quality white space meets gentle, approachable UI elements.

The style is **Modern Corporate**, refined through the lens of accessibility. It prioritizes clarity and ease of navigation to reduce cognitive load for users who may be under stress. By utilizing soft shadows and generous padding, the design system creates a tactile, comforting environment that feels both professional and caring.

## Colors
This design system utilizes a primary palette of "Medical Blue" (#005EB8) to establish institutional authority and "Professional Teal" (#008B8B) to inject a sense of vitality and modern care. 

White is the most critical component of this palette, used as a functional color to represent cleanliness and organization. Tertiary blues are used for background washes to separate content sections without introducing harsh lines. High-contrast slate grays are reserved for typography to ensure AAA accessibility standards are met across all digital touchpoints.

## Typography
The typography strategy employs **Manrope** for its unique blend of geometric purity and organic warmth. Its wide apertures and modern proportions make it highly legible for older demographics while maintaining a contemporary clinical aesthetic. 

Headlines use a semi-bold weight to project confidence, while body text is set with generous line heights to improve readability during long-form reading, such as medical articles or patient records. **Inter** is utilized for functional labels and micro-copy to ensure maximum clarity in densley populated interfaces like appointment schedules.

## Layout & Spacing
The layout follows a **Fixed Grid** model centered on the screen to provide a stable and predictable viewing experience. A 12-column system is used for desktop environments, transitioning to a flexible single-column layout for mobile. 

The spacing rhythm is based on an 8px base unit. To achieve the "friendly and accessible" goal, the design system utilizes "Airy" padding—internal component spacing is intentionally larger than industry standards to prevent the UI from feeling cramped. Section transitions should use significant vertical gaps to allow the eye to rest.

## Elevation & Depth
Depth is communicated through **Ambient Shadows** rather than stark borders. Surfaces should feel like they are gently floating above the background. Shadows should be highly diffused, using a low-opacity tint of the primary medical blue rather than pure black (e.g., `rgba(0, 94, 184, 0.08)`) to maintain a clean, vibrant look.

Tonal layering is used for lower-priority depth: secondary information containers use a subtle tertiary blue background instead of a shadow to indicate they are "sunken" or secondary to the main content cards.

## Shapes
The shape language is defined by a **Rounded** aesthetic (0.5rem base radius). This specific level of roundedness is chosen to soften the "clinical" edge of the medical field, making the software feel more like a lifestyle or wellness tool. 

Cards and large containers should use `rounded-xl` (1.5rem) to emphasize the "gentle, caring vibe," while buttons and input fields use the standard `rounded-md` (0.5rem) for a more structured, functional appearance.

## Components
- **Buttons:** Primary buttons use a solid Medical Blue fill with white text. Secondary buttons use a Teal outline. Both feature subtle transitions and a soft shadow on hover.
- **Cards:** White backgrounds with `rounded-xl` corners and ambient shadows. They are the primary vehicle for patient info and service highlights.
- **Inputs:** Large, clear touch targets with 16px internal padding and a 1px soft gray border. The border transitions to Medical Blue on focus.
- **Chips:** Used for medical categories or status tags (e.g., "Available," "In-Network"). These should use rounded-pill shapes and low-saturation background tints.
- **Lists:** Clean, borderless rows separated by subtle 1px dividers or alternating tonal backgrounds.
- **Progress Indicators:** Soft, rounded bars used for "Steps to Appointment" to make the process feel manageable and less clinical.