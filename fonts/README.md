# Poppins Font Files

DorkFi's primary typeface. Use these when Google Fonts is unavailable (sandboxed environments, local design tools, offline image generation).

## Files

| File | Weight | Use For |
|------|--------|---------|
| `Poppins-Regular-400.ttf` | 400 Regular | Body text, descriptions, captions |
| `Poppins-SemiBold-600.ttf` | 600 SemiBold | Subheadings, labels, card titles |
| `Poppins-Bold-700.ttf` | 700 Bold | Headlines, hero text, metric values |

## Usage in Design Tools

**Figma / Canva:** Upload TTF files via the font manager before starting your design.

**CSS:**
```css
@font-face {
  font-family: 'Poppins';
  font-weight: 400;
  src: url('./Poppins-Regular-400.ttf') format('truetype');
}
@font-face {
  font-family: 'Poppins';
  font-weight: 600;
  src: url('./Poppins-SemiBold-600.ttf') format('truetype');
}
@font-face {
  font-family: 'Poppins';
  font-weight: 700;
  src: url('./Poppins-Bold-700.ttf') format('truetype');
}
```

**Google Fonts (online):**
```
https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap
```

## License
Poppins is licensed under the [SIL Open Font License 1.1](https://scripts.sil.org/OFL). Free for commercial use.
