# Baeguni Guideline Kit HTML

Baeguni character guideline kit assets for the delivery HTML.

Key visual elements:

- Warm desk background
- Multiple paper sheets with soft shadows
- Large serif cover title
- Green character identity accents
- Character identity and expression pose strip
- Color palette with HEX, RGB, and CMYK values
- Expression grid
- Goods application grid
- Type logo and symbol combination examples

Screen and print behavior:

- Each guideline sheet is now a separate A4 landscape-proportioned page.
- The top navigation jumps to each page on screen.
- Print CSS uses `@page { size: A4 landscape; margin: 0; }`.
- Each `.sheet` prints as one page with `break-after: page`.
- Visible document copy is Korean.
- Print output preserves the same visual design as the web view with `print-color-adjust: exact`.

This folder is self-contained for the Baeguni delivery HTML.
