# Design Directions

## Approach 1 — Archive of Earth
Very Brief Intro: A tactile museum interface rooted in mineral pigments, paper grain, and archival labels. It balances excavation-era warmth with an editorial digital rhythm.
Probability: 0.03

## Approach 2 — Monsoon Modernism
Very Brief Intro: A brighter, more contemporary direction using indigo, chalk, and vermilion with bold asymmetry inspired by Indian modernist poster composition. It feels energetic, accessible, and present-day.
Probability: 0.07

## Approach 3 — Night at the Gallery
Very Brief Intro: A dark, cinematic exhibition with brass details and restrained light, designed to make each artifact feel like a spotlighted discovery. It is immersive but intentionally avoids neon or sci-fi styling.
Probability: 0.02

# Chosen Approach — Archive of Earth

## Design Movement
Contemporary museum editorial design with references to Indian archaeological field notes, hand-pulled pigment studies, and quiet gallery interpretation panels.

## Core Principles
1. **Material memory:** warm paper, mineral red, muted indigo, and ink-like borders should make the interface feel handled and collected.
2. **Editorial asymmetry:** use offset columns, staggered timeline markers, and generous left margins instead of centered application chrome.
3. **Evidence before ornament:** visual motifs remain subtle; labels, dates, and provenance are always clear and legible.
4. **Slow looking:** interactions reveal depth through calm transitions, progressive detail, and deliberate pacing.

## Color Philosophy
The palette treats color as historical residue rather than decoration. A bone-paper ground creates the feeling of an archive; iron-oxide terracotta marks chronology and human touch; indigo carries the authority of ink and evening; antique gold is reserved for active discoveries and key metadata.

## Layout Paradigm
A vertical editorial spine anchors the page. Content flows from a broad, offset hero into a split timeline: a fixed-feeling era rail on the left and artifact stories on the right. Detail views use a wide image-led panel with a narrow museum label column.

## Signature Elements
- A fine indigo chronology rule with terracotta nodes and small date stamps.
- “Field note” labels set in uppercase monospace with hairline rules.
- Soft paper grain and cropped pigment swatches used as restrained transitions between sections.

## Interaction Philosophy
Every interaction should feel like turning an archive card or moving a gallery rail. Hover states lift cards by a few pixels, timeline selection changes the active node and scroll position, and modals open as a considered exhibition drawer rather than a generic dialog.

## Animation
Use 180–260ms ease-out transitions for controls and cards. Reveal timeline content with a short opacity/translate entrance, staggered by 40ms. Use a 220ms modal fade with a 0.97 scale start. Respect reduced-motion preferences and keep timeline movement smooth rather than elastic.

## Typography System
Display: Cormorant Garamond, 600–700, for period names and editorial headlines. Body: Source Sans 3, 400–600, for readable interpretation. Metadata: IBM Plex Mono, 500, uppercase with letter spacing. Hierarchy uses large serif contrast, not excessive weight.

## Brand Essence
Indian art history, reframed as a tactile digital archive for curious university learners who want context, not just chronology. Personality: **observant, grounded, luminous**.

## Brand Voice
Headlines sound inviting and precise; CTAs are active but unhurried; microcopy explains why a detail matters. Avoid generic filler.

Example lines:
- “Begin with the marks left on stone.”
- “Trace the idea, then meet the object.”

## Wordmark & Logo
A compact symbol built from a terracotta circle intersected by a single indigo vertical timeline stroke, suggesting both a seal and a chronological axis. The wordmark uses a custom-spaced serif treatment and is never rendered as default body text.

## Signature Brand Color
Iron Oxide — `#A94F36`, used sparingly for chronology nodes, active states, and editorial emphasis.

## Style Decisions
- Use the Archive of Earth system consistently across all pages and components.
- Prefer subtle texture, asymmetry, and editorial labels over ornamental patterns.
- Never use generic purple gradients, default Inter typography, or uniformly rounded cards.
