# Enhanced Braille Code Tool

A web application for converting between text and Braille using the Unified English Braille (UEB) standard.

## Features

- **Bidirectional conversion** - Text ↔ Braille with live preview
- **Grade-2 contractions** - 10 whole-word signs (and, for, of, the, with...) + 12 group signs (ch, sh, th, ing...)
- **Interactive cell composer** - Click dots or use keys 1-6
- **File operations** - Import/export .txt and .brl files
- **Learning mode** - Shows contraction analysis with tooltips
- **Full accessibility** - Keyboard shortcuts, screen readers, high contrast

## Quick Start

1. Open the HTML file in a web browser
2. Type text in the left panel → see Braille conversion
3. Paste Braille in the right panel → see text conversion
4. Switch between Grade-1, Numbers, and Grade-2 modes
<img width="1455" height="823" alt="Screenshot 2025-09-09 220533" src="https://github.com/user-attachments/assets/04d08514-28c7-49f4-9c2a-b9a0b0fc84dd" />
<img width="1507" height="741" alt="Screenshot 2025-09-09 220552" src="https://github.com/user-attachments/assets/6650fbf8-d6a7-429a-8f27-dbd91badf59b" />
<img width="1395" height="1000" alt="Screenshot 2025-09-09 220610" src="https://github.com/user-attachments/assets/846d8d92-3b08-4aca-b0f1-9b26beda6b9a" />

## Keyboard Shortcuts

- `Ctrl+B` - Copy Braille
- `Ctrl+T` - Copy Text  
- `Ctrl+I` - Import file
- `Ctrl+E` - Export file
- `1-6` - Toggle cell dots
- `Enter` - Insert cell
- `Backspace` - Clear cell

## Usage Examples

```
Text: "Hello, world!"
Braille: ⠓⠑⠇⠇⠕⠂ ⠺⠕⠗⠇⠙⠖

Grade-2: "The quick brown fox"
Result: ⠮ ⠟⠥⠊⠉⠅ ⠃⠗⠕⠺⠝ ⠋⠕⠭
        ↑ (contraction for "the")
```

## Grade-2 Contractions

**Whole Words:** and (⠯), for (⠿), of (⠷), the (⠮), with (⠾), to, be, his, in, was

**Letter Groups:** ch (⠡), sh (⠩), th (⠹), ing (⠬), er (⠻), st, ed, ar, en, ou, wh, in

## Browser Support

Works in all modern browsers. No dependencies required - pure HTML/CSS/JavaScript.

## Technical Details

- **Standard:** UEB (Unified English Braille)
- **Unicode:** Braille Patterns U+2800–U+28FF  
- **Accessibility:** WCAG 2.1 AA compliant
- **Offline:** Works without internet connection

## License / Permissions

© 2025 Ashna Mariyam Shaji — All rights reserved.

This project is proprietary.  
Do not copy, reuse, or redistribute any part of this repository without explicit written permission from the author.  

Contact: ashna12shaji@gmail.com

🌟 **Acknowledgments**

Braille Authority of North America (BANA) for UEB standards
Unicode Consortium for Braille Patterns block
Web Accessibility Initiative (WAI) for accessibility guidelines
Braille community for feedback and testing


🔗 Resources

UEB Guidelines
Unicode Braille Patterns
Web Accessibility Guidelines
Braille Authority of North America
---

Built for accessibility and Braille literacy education.
