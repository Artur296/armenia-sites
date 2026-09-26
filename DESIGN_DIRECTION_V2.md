# Armenia Sites — Agency Design Direction v2

## Creative brief

Replace the default SaaS/template feeling with 20 credible, presentation-ready digital brands. Every site gets its own art direction, but all share a professional UX foundation.

## Six design directions

### 01 — Quiet Editorial
**References:** Aesop-style restraint, luxury editorial commerce, architectural whitespace.
- Warm neutrals, serif + restrained sans
- Oversized editorial headlines
- Still-life / tactile photography
- Thin rules, generous margins, subtle motion
- Best for: KOVA/07, MORA, AURA/01, MÅRÉ

### 02 — Precision Utility
**References:** Polestar-like restraint and engineering interfaces.
- Monochrome / steel palette
- Strong grid and numerical hierarchy
- Functional cards, specification rows, direct CTAs
- Dense desktop information, simplified mobile
- Best for: TORQ/AM, VOLT/AM, LEX/AM, MTR/88

### 03 — Fashion Gallery
**References:** contemporary fashion/editorial ecommerce.
- Full-bleed imagery
- Asymmetric grids
- Large crop-driven product/service storytelling
- Minimal chrome; navigation disappears into the composition
- Best for: SOLE/ATELIER, LUNE/08

### 04 — Kinetic Performance
**References:** automotive/performance digital experiences.
- High contrast
- Large numerical typography
- Motion-led transitions
- Sticky conversion controls
- Best for: SØL/AM, FORM/01, ROAM/24

### 05 — Modern Hospitality
**References:** destination storytelling and premium hospitality.
- Cinematic photography
- Warm material palette
- Story-first navigation
- Conversational booking/inquiry flow
- Best for: MELA, FIRE/27, ARARAT/9

### 06 — Clinical Clarity
**References:** modern healthcare/education interfaces.
- Calm neutral palette
- Exceptional information hierarchy
- Trust signals, process diagrams, FAQs
- Clear booking / assessment journeys
- Best for: FORMA/DM, FLUENT/AM

## Internal design review

### CEO
> “Would I confidently put this in front of a paying client?”

**Decision:** No generic templates. Every page needs a memorable brand idea and a clear commercial action.

### CTO
> “Can the visual system scale without becoming 20 different codebases?”

**Decision:** Shared tokens for spacing, breakpoints, motion and accessibility; unique brand tokens for type, color, radius and composition.

### Designer
> “Where is the art direction? Right now some sections still read as UI blocks.”

**Decision:** Images become structural elements. Hero, editorial split, gallery, proof and CTA sections must create rhythm, not just fill space.

### Engineer
> “What is actually reusable?”

**Decision:** Reuse behavior, not appearance:
- navigation behavior
- buttons
- responsive grid primitives
- motion primitives
- cards
- accessibility patterns

Do not reuse the same visual composition across categories.

### Final CEO review
> “Does this look like a real company, or like a website template?”

**Acceptance rule:** if the answer is “template”, redesign the section.

## Copy system

Never use generic copy such as:
- Learn More
- Our Services
- We provide high-quality services
- Contact Us
- Welcome to our website

Instead use:
**specific promise → context → concrete action**

Examples:
- “Reserve your chair”
- “Build my package”
- “Find my level”
- “Discuss my case”
- “Explore the route”

## Responsive rule

Desktop and mobile are separate compositions.

Desktop:
- editorial scale
- asymmetric layouts
- large photography
- multi-column discovery

Mobile:
- single-flow narrative
- priority CTA
- touch-friendly controls
- intentional image crops
- reduced navigation
- no horizontal overflow

## Quality gate

A page is not finished until:
1. The brand is recognizable without the logo.
2. The CTA explains the next action.
3. Copy sounds written for this business.
4. Photography supports the positioning.
5. Desktop has deliberate composition.
6. Mobile feels designed, not compressed.
7. Components have visible interaction states.
8. No section looks like a default SaaS template.
9. The first screen communicates what the business is and why it matters.
10. The page would be credible as a professional design-agency case study.

## Research note

The direction is informed by current premium web patterns: Aesop's restrained editorial system, fashion sites' image-led/asymmetric layouts, automotive sites' engineering-oriented interfaces, and Aman-style destination storytelling. These are reference principles, not pixel-copy targets.
