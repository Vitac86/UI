# AGENTS.md

## Product context
This repository contains HTML screens for Fieldvance, a mobile-first AI workflow product for HVAC and plumbing field-service teams in Spain/EU.

## Core rules
- Keep the product focused on HVAC and plumbing only
- Keep the UI language in English
- Keep the market context Spain / EU
- Use 24-hour time and EU-friendly date formatting
- Prefer consistent technician and supervisor terminology across all screens
- Preserve folder names and file names unless explicitly instructed otherwise
- Avoid speculative features not already represented in the repo

## Canonical technician story
- Job ID: FV-88421
- Site: Hotel Gran Vía, Madrid
- Asset: Carrier rooftop HVAC unit AC-402
- Issue: intermittent cooling failure
- Likely cause: degraded run capacitor with abnormal pressure behavior
- Repair: capacitor replaced, pressure normalized, system tested successfully

## Editing expectations
- Prefer small, reviewable edits
- Keep HTML/CSS structure stable unless inconsistency requires changes
- Maintain visual polish while improving continuity
- Make technician flow and supervisor flow align to the same underlying job universe

## Done means
- no obvious contradictions across screens
- navigation is consistent within technician and supervisor surfaces
- validation logic matches captured evidence
- report content matches performed work
- screenshots are credible enough for formal documentation use

## Visual restyle direction
- Match the uploaded Fieldvance brand reference boards
- Use a corporate-industrial visual language, not a generic startup SaaS style
- Primary palette:
  - Field Service Slate / deep blue-gray for core surfaces
  - Precision Teal for active highlights, progress, AI/workflow accents
  - Safety Orange only for warnings, validation blockers, urgent items, and critical CTAs
  - White / very light gray for canvas backgrounds
- Typography:
  - Headings: Montserrat
  - Body/UI text: Inter
- Keep the product focused on HVAC/plumbing field operations in Spain/EU
- Preserve the existing product flow and content logic while upgrading visual language
- Prefer sharper, more structured enterprise layouts over soft playful SaaS styling
- Avoid neon, glassmorphism, consumer-app aesthetics, or futuristic AI visuals
