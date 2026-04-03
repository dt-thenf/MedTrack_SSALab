# MedTrack Design System — "Clinical Sanctuary"

## 1. Overview & Creative North Star
**Creative North Star: "The Clinical Sanctuary"**

A High-End Editorial approach. We aim for a "Clinical Sanctuary"—a space that feels as sterile and precise as an operating room, yet as calm and supportive as a recovery suite.

---

## 2. Colors & Tonal Architecture

### Primary & Feedback Tokens
- **Primary (`#005296`):** The "Anchor." Navigation and primary actions.
- **Primary Container (`#1E6BB8`):** Active states and hero interactions.
- **Tertiary/Normal (`#005E3F`):** "Stasis." Stable patient vitals.
- **Error/Critical (`#BA1A1A`):** Reserved strictly for life-critical data.
- **Secondary/Watch (`#545F73`):** "Observation" states and non-critical warnings.

### Surface Hierarchy & Nesting
- **Base:** `surface` (#F7F9FB)
- **Secondary Sections:** `surface-container-low` (#F2F4F6)
- **Interactive Cards:** `surface-container-lowest` (#FFFFFF)
- **High-Intensity Overlays:** `surface-bright` (#F7F9FB) with 80% opacity and 20px Backdrop Blur.

---

## 3. Typography
Font: **Inter** (variable)

| Level | Size | Weight | Role |
|:---|:---|:---|:---|
| Display-LG | 3.5rem (56px) | 700 | Hero Stats |
| Headline-MD | 1.75rem (28px) | 600 | Patient Name / Section |
| Title-MD | 1.125rem (18px) | 600 | Card Headers |
| Body-LG | 1.0rem (16px) | 400 | Clinical Notes |
| Label-MD | 0.75rem (12px) | 500 | Metadata / Units |

---

## 4. Elevation & Depth
- **Ambient Shadows:** `0px 20px 40px` at 4% opacity.
- **Glassmorphism:** Summary cards use semi-transparent surface (85% alpha) with 16px backdrop blur.

---

## 5. Components

### Clinical Card
- Radius: `lg` (2rem) for containers; `md` (1.5rem) for nested.
- Min 24px internal padding.

### Buttons
- Primary: `primary` bg, `on-primary` text, radius `full`, 12px 28px padding.
- Secondary: Transparent + ghost border.

### Critical Alert State
- Pulse `error-container` background with 10% opacity "breathing" animation.

---

## 6. Design System Notes for Stitch Generation

**DESIGN SYSTEM (REQUIRED):**
- Platform: Web, Desktop-first, responsive for tablets
- Palette: Medical Blue (#1E6BB8) primary, White (#FFFFFF) surfaces, Light Gray (#F8FAFC) background, Red (#BA1A1A) for critical, Green (#005E3F) for normal, Slate (#545F73) for watch
- Font: Inter — Display 56px bold, Headline 28px semibold, Title 18px semibold, Body 16px regular, Label 12px medium
- Styles: Generously rounded (2rem / full), whisper-soft shadows, subtle glassmorphism on stat cards only, generous whitespace, no 1px borders
- Vibe: Clinical Sanctuary — sterile precision meets calm support. High-end editorial medical SaaS.
