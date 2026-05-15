# Maehyangi Guideline Kit HTML

Generated-image analysis translated into HTML/CSS.

Key visual elements:

- Warm desk background
- Multiple paper sheets with soft shadows
- Large serif cover title
- Pink character identity accents
- Turnaround pose strip
- Color palette and usage ratio
- Expression grid
- Goods application grid
- Do / Don't / clear space / minimum size guidelines

Screen and print behavior:

- Each guideline sheet is now a separate A4 landscape-proportioned page.
- The top navigation jumps to each page on screen.
- Print CSS uses `@page { size: A4 landscape; margin: 0; }`.
- Each `.sheet` prints as one page with `break-after: page`.
- Visible document copy is Korean.
- Print output preserves the same visual design as the web view with `print-color-adjust: exact`.

This folder is separate from the earlier `매향이` and `curated-supply` HTML work.
