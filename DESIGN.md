---
name: Synthetic Intelligence
colors:
  surface: '#0d1515'
  surface-dim: '#0d1515'
  surface-bright: '#333b3b'
  surface-container-lowest: '#080f10'
  surface-container-low: '#151d1e'
  surface-container: '#192122'
  surface-container-high: '#232b2c'
  surface-container-highest: '#2e3637'
  on-surface: '#dce4e5'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#dce4e5'
  inverse-on-surface: '#2a3233'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#b7c8e1'
  on-secondary: '#213145'
  secondary-container: '#3a4a5f'
  on-secondary-container: '#a9bad3'
  tertiary: '#fff5de'
  on-tertiary: '#3b2f00'
  tertiary-container: '#fed639'
  on-tertiary-container: '#715d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffe179'
  tertiary-fixed-dim: '#eac324'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#554500'
  background: '#0d1515'
  on-background: '#dce4e5'
  surface-variant: '#2e3637'
typography:
  headline-xl:
    fontFamily: JetBrains Mono
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: JetBrains Mono
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: JetBrains Mono
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  code-snippet:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.7'
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 80px
---

## Brand & Style
The design system embodies the "Synthetic Intelligence" narrative, a high-tech, advanced aesthetic tailored for a Cloud/DevOps specialist. The visual identity is rooted in **Cyberpunk-Minimalism**, stripping away unnecessary decorative elements to focus on terminal-like clarity and high-performance data visualization.

The target audience consists of technical recruiters, engineering leads, and CTOs. The UI should evoke a sense of "Mission Control"—an interface that feels like a sophisticated terminal for managing global cloud infrastructure. It balances a dark, immersive "midnight" environment with sharp, luminous accents that guide the eye toward critical technical proficiencies like Terraform, AWS, and CI/CD pipelines. Key characteristics include precision, technical transparency, and futuristic efficiency.

## Colors
This design system utilizes a high-contrast dark mode palette to simulate a developer's IDE environment.

- **Primary (#00f0ff):** Vibrant Cyan. Used exclusively for "active" states, terminal prompts, primary action buttons, and critical cloud skill highlights. It should appear to "emit light" against the dark background.
- **Secondary (#64748b):** Slate Gray. Reserved for metadata, helper text, and secondary UI elements to maintain a clear visual hierarchy between "code/data" and "labels."
- **Neutral/Surface (#0b0f10 & #161b1d):** Deep Midnight. The foundational layers. The primary background is nearly pitch-black, while surfaces use a slightly lighter slate-tinted black to define depth.
- **Accents:** Use a low-opacity cyan glow for borders and "active" indicators to reinforce the synthetic, electric feel.

## Typography
Typography is strictly monospaced using **JetBrains Mono** to reinforce the developer-centric aesthetic. This choice creates a "code-first" atmosphere where information feels structured and parsed.

- **Headlines:** Use a bold weight and tight letter spacing for a modern, impactful look.
- **Body Text:** Standard weight with increased line height for readability during technical deep-dives.
- **Labels:** Small, all-caps labels are used for technical tags (e.g., [AWS], [TERRAFORM]) to mimic terminal output syntax.
- **Mobile Scaling:** Headline sizes should drop by roughly 25% on mobile devices to prevent excessive line-breaking.

## Layout & Spacing
The layout follows a **structured grid model** that feels like a technical schematic. 

- **Grid:** A 12-column fluid grid for desktop, transitioning to a 4-column grid for mobile.
- **Background Pattern:** Implement a subtle 32px square grid pattern in the background using a 2% opacity stroke of the Primary color to reinforce the "Synthetic" theme.
- **Spacing Rhythm:** Based on a 4px baseline. Use generous section gaps (80px+) to ensure the "Minimalist" side of the aesthetic is preserved, allowing high-density technical cards to breathe.
- **Alignment:** Content is predominantly left-aligned, mimicking the flow of code in a script.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and **Tonal Layering** rather than traditional shadows.

1.  **Surfaces:** Cards use a semi-transparent background (`rgba(22, 27, 29, 0.7)`) with a `backdrop-filter: blur(12px)`.
2.  **Borders:** Instead of shadows, use 1px "Neon Outlines." Inactive states use a subtle slate-gray border; active or hovered states use a 1px cyan border with a `box-shadow: 0 0 10px rgba(0, 240, 255, 0.3)`.
3.  **Z-Index:** High-priority cloud architecture diagrams should appear on the top-most visual layer, using the strongest blur and brightest borders.

## Shapes
The shape language is **strictly geometric and sharp**.

- **Zero Radius:** All buttons, cards, and input fields utilize 0px border radius. This "sharp" look communicates precision and fits the terminal/architectural aesthetic.
- **Angled Accents:** Use 45-degree clipped corners (dog-ear corners) for primary buttons or section headers to add a futuristic, "cyber" flair without sacrificing the minimalist ethos.

## Components
- **Buttons:** Sharp-edged. Primary buttons are solid Cyan with black text. Secondary buttons are ghost-style with Cyan outlines and glowing hover effects.
- **Cloud Proficiency Chips:** Small, rectangular tags with a Primary Cyan outline. For critical skills (AWS, Docker), use a subtle pulsing animation or a background fill.
- **Terminal Cards:** Used for project descriptions. Should include a "header bar" with three dots (mimicking a window) and display tech stacks as a JSON-like array.
- **Status Indicators:** Use small glowing dots to indicate "Live" projects or "Current" roles.
- **Input Fields:** Bottom-border only, using the Cyan Primary color. The cursor should be a blinking block character (`_`) to maintain the JetBrains Mono terminal vibe.
- **Progress Bars:** For technical skills, use "segmented" progress bars (blocks) rather than smooth fills, suggesting a loading sequence or system resource monitor.