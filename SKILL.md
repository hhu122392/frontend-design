---
name: frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build web components, pages, artifacts, posters, or applications (examples include websites, landing pages, dashboards, React components, HTML/CSS layouts, or when styling/beautifying any web UI). Generates creative, polished code and UI design that avoids generic AI aesthetics.
license: Complete terms in LICENSE.txt
---

This skill guides creation of distinctive, production-grade frontend interfaces that avoid generic "AI slop" aesthetics. Implement real working code with exceptional attention to aesthetic details and creative choices.

The user provides frontend requirements: a component, page, application, or interface to build. They may include context about the purpose, audience, or technical constraints.

## Design Thinking

Before coding, understand the context and commit to a BOLD aesthetic direction:
- **Purpose**: What problem does this interface solve? Who uses it?
- **Tone**: Pick an extreme: brutally minimal, maximalist chaos, retro-futuristic, organic/natural, luxury/refined, playful/toy-like, editorial/magazine, brutalist/raw, art deco/geometric, soft/pastel, industrial/utilitarian, etc. There are so many flavors to choose from. Use these for inspiration but design one that is true to the aesthetic direction.
- **Constraints**: Technical requirements (framework, performance, accessibility).
- **Differentiation**: What makes this UNFORGETTABLE? What's the one thing someone will remember?

**CRITICAL**: Choose a clear conceptual direction and execute it with precision. Bold maximalism and refined minimalism both work - the key is intentionality, not intensity.

Then implement working code (HTML/CSS/JS, React, Vue, etc.) that is:
- Production-grade and functional
- Visually striking and memorable
- Cohesive with a clear aesthetic point-of-view
- Meticulously refined in every detail

## Frontend Aesthetics Guidelines

Focus on:
- **Typography**: Choose fonts that are beautiful, unique, and interesting. Avoid generic fonts like Arial and Inter; opt instead for distinctive choices that elevate the frontend's aesthetics; unexpected, characterful font choices. Pair a distinctive display font with a refined body font.
- **Icons**: Use real icon libraries like Lucide, Heroicons, or Phosphor - NEVER use emoji as icons. Import proper icon components or SVG for a professional, production-grade interface.
- **Images**: Always use real, high-quality images from sources like Unsplash, Pexels, or similar. NEVER use placeholder images, colored blocks with icons, or gradient backgrounds as image substitutes. When images are required, use actual photography that enhances the design narrative.
- **Color & Theme**: Commit to a cohesive aesthetic. Use CSS variables for consistency. Dominant colors with sharp accents outperform timid, evenly-distributed palettes.
- **Motion**: Use animations for effects and micro-interactions. Prioritize CSS-only solutions for HTML. Use Motion library for React when available. Focus on high-impact moments: one well-orchestrated page load with staggered reveals (animation-delay) creates more delight than scattered micro-interactions. Use scroll-triggering and hover states that surprise.
- **Spatial Composition**: Unexpected layouts. Asymmetry. Overlap. Diagonal flow. Grid-breaking elements. Generous negative space OR controlled density.
- **Backgrounds & Visual Details**: Create atmosphere and depth rather than defaulting to solid colors. Add contextual effects and textures that match the overall aesthetic. Apply creative forms like gradient meshes, noise textures, geometric patterns, layered transparencies, dramatic shadows, decorative borders, custom cursors, and grain overlays.

## Design Inspiration Reference

When seeking aesthetic direction, draw inspiration from legendary designers and artists. Sample 2-3 sources randomly, then translate their essence into web implementation - never copy directly.

**Graphic Design**: Saul Bass, Paula Scher, Neville Brody, April Greiman, David Carson, Massimo Vignelli, Josef Müller-Brockmann, Otl Aicher, Armin Hofmann

**Art**: Piet Mondrian, Sonia Delaunay, Josef Albers, Victor Vasarely, Bridget Riley, M.C. Escher, Paul Klee, Henri Matisse, Mark Rothko, Yayoi Kusama, Takashi Murakami, Katsushika Hokusai, Xu Bing, Zao Wou-Ki

**Digital Media**: John Maeda, Casey Reas, Zach Lieberman, Vera Molnár, Refik Anadol, Sougwen Chung

**Architecture**: Zaha Hadid, Bjarke Ingels, Thomas Heatherwick, Olafur Eliasson, Le Corbusier, Mies van der Rohe, Frank Lloyd Wright, Tadao Ando, SANAA, Kengo Kuma, Lina Bo Bardi

**Industrial Design**: Dieter Rams, Jony Ive, Naoto Fukasawa, Jasper Morrison, Marc Newson, Yves Béhar, Charles & Ray Eames, Sori Yanagi, Nendo, Philippe Starck

## Translation Guidelines

Convert artistic inspiration into concrete web implementation:

| Aspect | Web Implementation |
|--------|-------------------|
| Layout | Asymmetric columns, oversized headlines, grid-breaking elements, cinematic section headers |
| Color | High-contrast clashes, primary color geometry, industrial stripes, gradients with light scatter |
| Form | Curved cuts, overlapping blocks, modular cards, paper textures, fine grain |
| Motion | 200-300ms entrance/reveal/scroll feedback; support `prefers-reduced-motion` fallback |
| Semantics | Minimal symbols, variable font axes (weight/width transitions), monospaced numbers/metrics |

**Critical**: Never replicate specific composition, color schemes, font pairings, taglines, or brand elements from original works. Avoid generating layouts highly similar to source material.

## Technical Implementation Checklist

**HTML Structure**:
- Use semantic HTML5: `header`, `main`, `section`, `nav`, `footer`
- Correct heading hierarchy (h1-h6)
- Essential meta tags: `viewport`, `color-scheme`

**Typography & Icons**:
- Import Google Fonts with Chinese/English fallback stacks
- Use icon libraries: Lucide, Heroicons, Tabler Icons, Phosphor

**Image Resources** (use real links only):
| Source | Base URL | Example |
|--------|----------|---------|
| Unsplash | https://images.unsplash.com/photo- | https://images.unsplash.com/photo-1515886657613-9f3515b0c78f |
| Pexels | https://images.pexels.com/photos/ | https://images.pexels.com/photos/1234567 |
| Picsum | https://picsum.photos/ | https://picsum.photos/id/157/800/600 |

**Responsive Design**:
- Three breakpoint strategy (mobile, tablet, desktop)
- Minimum touch target: 44×44px
- Tables and charts need small-screen strategies

## Resource References

**Component Libraries** - Reference for implementation patterns and code structure:
- [UIverse](https://uiverse.io/) - Community-driven open-source UI components
- [shadcn/ui](https://ui.shadcn.com/) - Re-usable components built with Radix UI and Tailwind CSS

**Icon Libraries** - Use these for all icon needs:
- [Lucide](https://lucide.dev/) - Clean & consistent icon toolkit (recommended)
- [Heroicons](https://heroicons.com/) - SVG icons by Tailwind Labs
- [Tabler Icons](https://tabler.io/icons) - Open-source icon set
- [Phosphor Icons](https://phosphoricons.com/) - Flexible icon system

**Image Resources** - Use actual photography, never placeholders:
| Source | Base URL | Usage |
|--------|----------|-------|
| Unsplash | https://images.unsplash.com/photo- | High-quality professional photography |
| Pexels | https://images.pexels.com/photos/ | Free stock photos |
| Picsum | https://picsum.photos/ | Random placeholder images |

NEVER use generic AI-generated aesthetics like overused font families (Inter, Roboto, Arial, system fonts), cliched color schemes (particularly purple gradients on white backgrounds), predictable layouts and component patterns, cookie-cutter design that lacks context-specific character, emoji as icons (always use real icon libraries like Lucide), or placeholder images/substitutes (colored blocks, gradients with icons, etc. - always use real photography).

Interpret creatively and make unexpected choices that feel genuinely designed for the context. No design should be the same. Vary between light and dark themes, different fonts, different aesthetics. NEVER converge on common choices (Space Grotesk, for example) across generations.

**IMPORTANT**: Match implementation complexity to the aesthetic vision. Maximalist designs need elaborate code with extensive animations and effects. Minimalist or refined designs need restraint, precision, and careful attention to spacing, typography, and subtle details. Elegance comes from executing the vision well.

Remember: Claude is capable of extraordinary creative work. Don't hold back, show what can truly be created when thinking outside the box and committing fully to a distinctive vision.
