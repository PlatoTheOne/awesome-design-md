# Design System: Cash App

## 1. Visual Theme & Atmosphere

Cash App's visual language lives in the tension between strict structure and expressive energy. The public guidelines describe the brand as balancing "structuring order" with "explosive freedom," and that framing is useful: the foundation is orderly, with disciplined grids, large typographic anchors, strong contrast, and a practical neutral scale. The expression comes from saturated functional colors, organic curves, and typography that feels warmer and more human than a cold geometric sans. The result is modern fintech UI that feels direct, confident, and culturally aware instead of sterile.

The signature color is **Cash Green** (`#00E013`), but the system does not rely on one green plus gray. It is a full palette family: cool blues, cobalt, citron yellow-green, orange, magenta, purple, aqua, and layered grayscale neutrals. These colors are used deliberately to create distinction, hierarchy, and legibility. The brand documents emphasize contrast and accessibility over decoration.

Typography is the strongest identity marker. Cash App's main typeface is **Cash Sans**, a customized version of **Sohne**, with rounded punctuation and subtle glyph changes that make the voice warmer and more approachable while keeping the clarity of a neo-grotesque sans. **Cash Sans Wide** is reserved for headlines and short copy. **Cash Sans Mono** is reserved for technical labels and eyebrows, and should not be used for expressive headlines. The source also makes it clear that product surfaces are not only visual; they are behavioral. Empty states, logged-out experiences, confirmation messages, transactional email, and lifecycle surfaces are all part of the same system voice.

The embedded page data is also broader than a simple token dump. It includes dedicated source sections for **Accessibility**, **Color Modes**, **Color Naming**, **Everyday usage**, **Expressive usage**, **Motion**, **Iconography**, **Graphic UI**, **Logo Variant Selector**, **Language support**, **Documentation**, **Libraries**, and **Downloads**. That matters because a correct Cash App-inspired UI is not just color-and-type matching. It should also preserve the product tone, information hierarchy, asset discipline, and behavioral clarity present in the original system.

**Key Characteristics:**
- Cash Green (`#00E013`) as the hero brand accent
- Warmed neo-grotesque typography: Cash Sans over a Sohne base
- Rounded punctuation and organic curves instead of rigid geometric harshness
- Strong neutral ladder from `#F1F4F6` down to `#2C2C2C`
- Large editorial headline sizes paired with rigorous body copy
- Saturated supporting palettes for campaigns, categories, and contrast systems
- Typography and color must meet accessibility contrast targets
- Mono is functional, not decorative
- Expressive layouts are encouraged, but legibility stays non-negotiable
- The brand voice should still feel approachable in low-attention moments like empty and logged-out states
- Product UI should make users feel control, safety, and confidence through information, metaphor, and social proof

## 2. Color Palette & Roles

### Core Brand
- **Cash Green** (`#00E013`): Primary brand accent. Use for hero CTAs, key status, active emphasis, and brand recall.
- **Cash Green Strong** (`#00BF2C`): Slightly darker green for hover or stronger contrast states.
- **Cash Green Bright** (`#00F53A`): High-energy highlight for celebratory or high-visibility moments.
- **Cash Green Soft** (`#91FFB0`): Light supportive green for badges, soft surfaces, and secondary emphasis.

### Neutral Scale
- **Gray 1** (`#F1F4F6`): Light page background, large soft surfaces
- **Gray 2** (`#E7EAED`): Secondary background, sections, cards on white
- **Gray 4** (`#D8DBE1`): Borders, dividers, inactive UI
- **Gray 8** (`#B8BDC3`): Disabled controls, quiet metadata
- **Gray 12** (`#939A9E`): Muted body copy
- **Gray 15** (`#707678`): Secondary text
- **Gray 17** (`#4A4F4F`): Strong body text on light surfaces
- **Gray 18** (`#353838`): Dark utility text, dark UI chrome
- **Dark Slate Gray** (`#2C2C2C`): Primary dark surface
- **Black** (`#000000`): Maximum contrast text, dark mode backgrounds
- **White** (`#FFFFFF`): Primary light surface and inverted text

### Supporting Accent Families
- **Azure**: `#0978FA`, `#0FB3FF`, `#66CFFF`, `#E0F5FF`
- **Cobalt**: `#0020C2`, `#3859FF`, `#9EACFF`, `#E3E7FF`
- **Citron**: `#D8FF14`, `#C3EB00`, `#ECFF8A`, `#F7FFD6`
- **Orange**: `#FF713A`, `#F26129`, `#D64813`, `#FFF6E3`
- **Magenta**: `#B800B8`, `#FF2ACC`, `#FF8FE5`, `#FFEBFA`
- **Purple**: `#8B07C4`, `#AB30F7`, `#CB85FF`, `#F2E6FF`
- **Gold**: `#FED31C`, `#F5AB00`, `#FFF554`, `#FFFDC4`
- **Aqua**: `#17F0F0`, `#0F8585`, `#65F7F7`, `#DEFFFF`

### Usage Guidance
- Keep Cash Green as the primary brand recall color
- Use accent families to create category separation, editorial emphasis, and campaign energy
- On informational screens, favor neutrals first and accents second
- Always verify text and control contrast; the brand guidelines explicitly call accessibility out as a requirement
- Treat the palette as a full system, not a random rainbow. The source material groups colors into gateway-style palettes and extended variants, so accent families should be internally coherent when used together
- Preserve strong pass/fail contrast logic. The source includes explicit accessibility examples, including AAA-level pairings

## 3. Typography Rules

### Font Family
- **Primary**: `Cash Sans`, fallback `Sohne, Inter, system-ui, sans-serif`
- **Display Wide**: `Cash Sans Wide`, fallback `Cash Sans, Sohne, Inter, system-ui, sans-serif`
- **Monospace**: `Cash Sans Mono`, fallback `ui-monospace, SFMono-Regular, Menlo, monospace`
- **Secondary / Support**: `Sohne Buch` and related Sohne cuts can still appear in explanatory and editorial support text
- **Editorial Accent**: `Exact Block` can appear in occasional display moments, but should be rare and intentional

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Page Title | Cash Sans / Wide | 90px | Regular to Bold | 1.00 | -3% | Brand page titles, hero moments |
| Section Heading | Cash Sans / Wide | 48px | Regular to Medium | 1.00 | -1px to 0 | Strong section anchors |
| Feature Heading | Cash Sans | 24px | Medium | 1.21 | 0 | Product cards, callouts |
| Intro Copy | Cash Sans | 22px | Regular | 1.18 | 0 | Intro paragraphs, hero support |
| Navigation | Cash Sans | 14px to 16px | Regular / Medium | 1.35 | 0 to -0.3px | Compact, disciplined nav |
| Body | Cash Sans | 14px to 16px | Regular | 1.20 to 1.35 | 0 | Standard product and marketing text |
| Eyebrow / Spec | Cash Sans Mono | 10px to 14px | Regular | 1.30 to 1.40 | 0 | Labels, specs, short technical tags |
| Mono Callout | Cash Sans Mono | 18px | Regular | 1.06 | 0 | Short utility moments only |

### Principles
- Use **Regular** and **Medium** as the default weights for most UI
- Keep tracking between **-3% and 0%** for large display type; loosen only when smaller text needs clarity
- Leading should usually land between **85% and 120%** of the type size
- Use **Cash Sans Wide** for headlines and short blocks only
- Do not use **Cash Sans Mono** for expressive headlines; the source guidelines explicitly warn against this
- Preserve legibility for ambiguous characters like `O / 0` and `I / l`; slashed zero is encouraged where confusion matters
- Expression is welcome, but type must still feel integral to the layout, not pasted on top of it
- The system explicitly encourages typographic experimentation in display moments. Spacing, dimensionality, repetition, contrast, orientation, and legibility are all valid levers
- The support system must handle broad language coverage. The source includes extensive language support examples, so layouts should avoid brittle assumptions about short English-only text

## 4. Component Stylings

### Buttons

**Primary CTA**
- Background: `#00E013`
- Text: `#000000`
- Radius: 9999px or 12px depending on context
- Padding: 12px 20px
- Font: Cash Sans Medium, 14px to 16px
- Use: Main action, conversion point, payoff moment

**Secondary Dark Button**
- Background: `#000000`
- Text: `#FFFFFF`
- Radius: 9999px or 12px
- Padding: 12px 20px
- Use: Dense UI, dark emphasis, inverted layouts

**Ghost / Utility Button**
- Background: transparent
- Text: `#353838` on light or `#FFFFFF` on dark
- Border: `1px solid #D8DBE1` on light or `1px solid rgba(255,255,255,0.18)` on dark
- Radius: 12px
- Use: Secondary actions, filter controls, segmented choices

**Navigation / Index Row**
- Height: typically `33px` to `35px`
- Radius: often `0px`
- Padding: left-biased, commonly `40px` or `70px` for nested levels
- Text: muted gray by default (`#848484` / `#898989`), darker or inverted on active/hover
- Use: side navigation, resource lists, hierarchical guide indexes

### Cards & Containers
- Light cards: `#FFFFFF` or `#F1F4F6` with border `#D8DBE1`
- Dark cards: `#2C2C2C` with subtle inner contrast and white text
- Radius: 12px for standard cards, 20px+ for featured surfaces
- Use high contrast numeric or text focal points inside cards
- Cards can carry accent surfaces, but core data should remain readable at a glance

### Inputs & Form Elements
- Light input background: `#FFFFFF`
- Dark input background: `#2C2C2C`
- Border: `#D8DBE1` light / `rgba(255,255,255,0.18)` dark
- Focus ring: Cash Green or a clearly accessible accent
- Labeling should stay plain and unambiguous

### Navigation
- Simple, compact, direct
- Thin top-level nav with restrained spacing
- Favor black, white, and gray surfaces with one accent highlight
- Buttons and account actions should feel obvious, not ornamental
- The source includes multiple nav patterns: standard nav, dark nav, and mobile nav
- Nested information architecture is normal. Indented rows and dropdown-like controls are part of the system
- Compact nav controls commonly use 14px to 16px text with 19px line-height

### Messaging & Behavioral Surfaces
- Empty states, logged-out states, timeouts, footers, confirmation messages, transactional email, and lifecycle marketing should all feel like part of the same brand system
- Low-attention moments should feel approachable, often through unexpected diction rather than decorative visuals
- High-stakes product moments should increase confidence through clarity, information density, metaphors, and social proof

### Iconography & Graphic UI
- Icons should be simple, sharp, and product-linked rather than ornamental
- Graphic UI should use color to explain, categorize, and direct attention, not just decorate empty space
- Metaphor is a real part of the system. Use data, simple visual analogies, and familiar patterns to make product information easier to act on

### Logo & Asset Use
- The source system includes a **Logo Variant Selector**, plus symbol-only and stacked logo treatments
- Use approved variants appropriate to the surface and contrast level
- Keep brand marks clean, high-contrast, and well-spaced; avoid improvised alternate logo behavior

### Imagery & Graphic Treatment
- High-contrast product crops on black, white, or vivid color fields
- Organic curves and rounded punctuation should be echoed in icons and graphic forms
- It is acceptable to place UI fragments onto color or texture for dramatic focus, but contrast must remain intact

## 5. Layout Principles

### Spacing System
- Base rhythm: 4px and 8px increments
- Common spacing steps: 8, 12, 16, 24, 32, 48, 64, 80
- Section padding should feel generous enough for editorial pacing
- Dense fintech data can exist inside the system, but major page sections should still breathe

### Grid & Composition
- Clear block-based composition
- Large headline zones paired with modular content rails
- Use distinct bands of content rather than noisy collage
- On campaign pages, one saturated field can carry the section while the layout stays orderly
- Allow specimen-like sections for typography, swatches, logo variants, and graphic UI references. The source is comfortable presenting design rules as large modular exhibits

### Whitespace Philosophy
- Cash App is not minimal in the sterile sense; it is intentional
- Large type needs enough room to feel powerful
- Accent color should feel placed with purpose, not sprayed around the page
- Negative space is used to make expressive moments land harder
- The source clearly separates **Everyday usage** from **Expressive usage**. Standard product screens should stay calmer than editorial, campaign, or brand-demo screens

### Radius & Shape
- Small utility corners: 4px to 8px
- Standard UI corners: 12px
- Feature surfaces: 16px to 24px
- Pills: 9999px for key actions, tags, and highlighted controls

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Flat | Pure surface color only | Large brand fields, simple layouts |
| Border Lift | `1px` border with mild contrast | Cards, utility containers |
| Soft Lift | Border + soft shadow (`0 10px 30px rgba(0,0,0,0.08)`) | Marketing cards, featured modules |
| Strong Lift | Dense shadow or color-block contrast | High-priority hero modules |

**Depth Philosophy:** Cash App gets most of its punch from contrast, color blocks, and type scale instead of heavy shadow stacks. Depth should support clarity, not make surfaces feel frosted or decorative.

### Motion
- Motion exists in the source as a first-class section, but it should reinforce understanding rather than add spectacle
- Use animation to clarify sequence, state change, or focus
- Keep transitions brisk and direct; motion should feel like product feedback, not ambient decoration

## 7. Do's and Don'ts

### Do
- Use Cash Green deliberately for decisive moments
- Keep typography crisp, large, and disciplined
- Use Cash Sans Wide for short, high-impact headlines
- Use Cash Sans Mono for labels, specs, and utility moments
- Check accessibility contrast on every text/background pairing
- Let expressive color and editorial composition appear in controlled bursts
- Preserve rounded punctuation and human warmth in the typographic voice
- Make low-attention product states feel approachable, not robotic
- Use information, metaphor, and social proof to help users feel in control
- Keep navigation patterns hierarchical and easy to scan when the content system grows
- Preserve the distinction between everyday product behavior and more expressive campaign behavior
- Respect logo variants, icon discipline, and reusable asset rules as part of the system, not as separate brand paperwork

### Don't
- Don't turn the system into generic neon-fintech UI
- Don't use mono for big expressive headlines
- Don't run long paragraphs in Cash Sans Wide
- Don't let supporting accent colors overpower Cash Green's brand role
- Don't use washed-out gray-on-gray text pairings
- Don't overcomplicate cards with unnecessary shadow and chrome
- Don't sacrifice legibility for graphic experimentation
- Don't treat brand voice as hero-copy only; utility states and transactional surfaces count too
- Don't ignore ambiguous characters in product contexts like cashtags, codes, or passwords
- Don't use motion as decoration when it is not helping orientation or comprehension
- Don't invent casual logo treatments or inconsistent icon styles

## 8. Responsive Behavior

### Breakpoints
| Name | Width | Key Changes |
|------|-------|-------------|
| Mobile | <640px | Single column, compact nav, stacked CTAs |
| Tablet | 640px-1024px | Two-column content blocks, reduced headline scale |
| Desktop | >1024px | Full editorial composition, larger display type |

### Responsive Rules
- Step 90px display down aggressively on smaller screens
- Keep headline impact, but reduce width before reducing contrast
- Collapse multi-card color systems into stacked cards on mobile
- Preserve CTA clarity above fold
- Keep labels and specs readable; do not shrink mono tags into noise
- Preserve hierarchical navigation on mobile, even when moving from side rails to collapsed menus
- Account for longer strings and broader language support when reducing widths

## 9. Agent Prompt Guide

### Quick Color Reference
- Primary CTA: Cash Green `#00E013`
- Primary Light Background: Gray 1 `#F1F4F6` or White `#FFFFFF`
- Primary Dark Background: Black `#000000` or Dark Slate Gray `#2C2C2C`
- Primary Text on Light: `#000000` or `#353838`
- Primary Text on Dark: `#FFFFFF`
- Border Light: `#D8DBE1`
- Secondary Text: `#707678`

### Example Component Prompts
- "Create a fintech hero section with Cash App energy: white background, 90px Cash Sans Wide headline, 22px supporting copy, black secondary CTA, and Cash Green primary CTA."
- "Design a product card system using soft gray surfaces, 12px radii, strong numeric hierarchy, and one accent family per card for categorization."
- "Build a compact top navigation with monochrome styling, one green accent button, and restrained spacing."
- "Create a dark feature section using `#000000` and `#2C2C2C`, with white text, Cash Green highlights, and one supporting accent family for data visualization."
- "Use Cash Sans Mono only for small labels and specs. Keep the main headlines in Cash Sans or Cash Sans Wide."
- "Design an empty state that feels approachable and on-brand: quiet neutral surface, concise unexpected copy, one clear action, and restrained use of Cash Green."
- "Create a confirmation module that makes the user feel informed and safe through strong hierarchy, direct labels, and one supportive metaphor or data point."
- "Create two versions of the same screen: an everyday product version and an expressive campaign version. Keep the everyday version calmer, and push color and composition only in the expressive version."
- "Design a dark-mode panel with high-contrast text, restrained borders, one Cash Green action, and motion only where it clarifies a state change."

### Iteration Guide
1. Start with neutral structure first: black, white, gray
2. Add Cash Green at the conversion or focus point
3. Introduce one supporting accent family only if it improves hierarchy
4. Keep display type bold in scale, not noisy in styling
5. Re-check contrast before shipping
6. Audit utility states, not just hero sections, for brand consistency
7. Decide whether the screen is everyday or expressive before styling it
