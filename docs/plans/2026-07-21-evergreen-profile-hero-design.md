# Evergreen profile hero design

## Goal

Replace the project-dependent hero diagram with a durable explanation of Mickaël's Data Engineering practice. The result must remain relevant when projects and technologies change.

## Content

The left side identifies Mickaël, his role, availability across French-speaking Switzerland, and the concise promise: "Building governed data systems, from ingestion to intelligent delivery."

The diagram presents `INGEST / Collect`, `TRANSFORM / Model`, and `DELIVER / Serve`. It resolves into three stable outcomes: `ANALYTICS`, `AI`, and `DATA PRODUCTS`. Governance is a cross-cutting rail labeled `GOVERNANCE · QUALITY · SECURITY · LINEAGE`, not a final pipeline step.

## Visual direction

Use a dark system-blueprint composition with the established navy, teal, blue, and violet palette. Use simple monoline vector icons rather than vendor marks. Keep the desktop canvas at 1200×400. Provide a dedicated mobile composition so labels remain readable at 390 px rather than shrinking the desktop diagram beyond legibility.

## Motion

The six-second, 30 FPS loop reveals the three stages in order, then the three outcomes. Governance remains active across the flow. The complete diagram holds still for approximately 1.8 seconds before a calm exit and seamless reset. The SVG fallback shows the complete settled state.

## Acceptance criteria

- No project names, vendor logos, or technology names in either hero.
- No clipped or overflowing text.
- Desktop, GitHub-width, and 390 px captures inspected visually.
- GIF and SVG dimensions agree.
- First and last GIF frames match.
- The settled state is pixel-still.
- Reduced-motion sources are present for desktop and mobile.
