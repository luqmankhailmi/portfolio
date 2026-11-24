# Design Direction — Luqman Khailmi Portfolio

## Identity & Audience
Personal portfolio for a CS/data developer student. Audience: hiring managers, recruiters, collaborators in tech and data roles.

## Dials
ENERGY 1 / RHYTHM 1 / MOTION 1

Calm, uniform, hover-only motion. The design should not shout; the content is the credential.

## Palette
- Background: `#ffffff` — neutral canvas, keeps focus on content
- Background alt: `#f7f7f8` — subtle surface differentiation for certs and skill tags
- Text: `#1a1a1a` — near-black, strong legibility without pure-black harshness
- Text medium: `#555555` — body prose, reduced weight relative to headings
- Text light: `#6b6b6b` — metadata, secondary labels
- Border: `#e2e2e5` — structural lines, low prominence
- Accent: `#2d6a4f` — forest green, chosen for distinctiveness (avoids AI-default blue/purple) and relevance to a Malaysian context (national colour association)
- Accent light: `#e9f5ef` — accent tint for tag fills and selection highlights
- Amber one-off: `#b45309` — used only for the "Current" project label to signal active/live status

Palette is 2 core (white, near-black) + 1 accent (forest green) + 1 functional one-off (amber). Neutrals not counted.

## Typography
- **Inter** (body): Chosen for high readability at small sizes and professional neutrality. Widely tested in product interfaces; appropriate for a technical audience who reads dense information quickly.
- **IBM Plex Mono** (metadata): Chosen to visually separate metadata from prose (section sub-labels, dates, stack tags, skill group titles). The monospace voice signals technical fluency without decorating the layout. Used only at small size (0.65–0.8rem) in uppercase with moderate tracking.

## Key Decisions

| Decision | Reason |
|---|---|
| Forest green accent | Avoids AI-default blue/purple palette; distinctive and personally associated |
| IBM Plex Mono for metadata labels | Separates data/classification text from narrative prose; signals technical identity |
| Uniform card radius (6px) | Consistent, tight, professional — not pill-shaped, not sharp |
| Pill radius (100px) on tags and filter buttons | Tags and filters are classification tokens, not content blocks; pill shape signals "label" vs "container" |
| Featured dashboard card | A pale green surface, stronger title, and single accent edge make the live stakeholder-facing dashboard the first project to scan. Other project cards stay neutral. |
| No dark mode toggle | Light theme is deliberate for a professional/academic portfolio context; dark default has no branding justification here |
| Scroll-reveal (fade up 16px) on sections | MOTION 1 with a single subtle cue; keeps page from feeling static without competing with content. No stacked animations. |
| IBM Plex Mono + Inter pairing | Monospace/sans pairing creates a clear two-tier type hierarchy without a third typeface |
| KL window backdrop (`assets/kl-window-hero.png`) behind hero | The requested view from a Kuala Lumpur office gives the introduction a sense of place. The generated architectural scene is decorative; a white left-side fade keeps the name and links legible. The image stays static, so MOTION stays 1. |
| Full-width section bands | Soft neutral bands behind Skills and Experience separate dense lists from the white narrative sections. A pale green contact band marks the final action. The sections retain the same content width and calm RHYTHM 1 spacing. |
| Experience timeline | A single forest-green rail makes the dated roles read as a progression. The current role has a filled marker; earlier roles use open markers. Removing the card boxes lets the chronology lead without adding visual weight. |
