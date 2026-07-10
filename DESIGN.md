# Design System Specification: Al-Haq Studio

## 1. Overview & Identity
**Creative North Star: The Ethical Architect**

Al-Haq Studio is the commercial and software production engine of Al-Haq. The design system represents **Engineering Excellence**, **Digital Integrity**, and **Professional Craftsmanship**. It avoids flashy tech startup gimmicks, focusing instead on high-contrast structures, clean professional grids, and premium editorial styling. It presents the studio's portfolio, software consulting capabilities, and operational values in a clear, trustworthy layout.

## 2. Color Palette & Tonal Depth

The corporate color palette establishes trust and reliability through deep blue and warm gold accents.

### Tonal Hierarchy (Tailwind Config)
*   **Primary:** `#0A2540` (Deep Blue) — Establishes corporate authority and stability. Used for primary branding elements and solid backgrounds.
*   **Secondary:** `#D4AF37` (Gold) — Represents premium ethical values, craftsmanship, and active link states.
*   **Background Base:** `#f8f9fc` — Clean base canvas.
*   **Surface Lowest:** `#ffffff` — Used for case studies, product columns, and testimonials.
*   **Surface Low:** `#f5f7fb` — Neutral alternate panels.
*   **Outline-Variant:** `#d1d5db` — Structural borders.

### Dark Mode Mapping
*   **Background Base:** `#0b1220` (Dark Space)
*   **Surface Lowest:** `#1e293b` (Active container)
*   **Surface Low:** `#0f172a` (Inner panels)
*   **Text Primary (`text-on-surface`):** `#f8fafc` (Bright white)
*   **Text Secondary (`text-on-surface-variant`):** `#94a3b8` (Muted Slate)
*   **CTA Contrast Swap:** In dark mode, `.bg-primary` transitions to Gold (`#D4AF37`) with Deep Blue text (`#0A2540`) to maintain high contrast for call-to-actions.

## 3. Typography
The typography contrasts classic editorial serif headings with an accessible, highly legible body font.

*   **Display & Headlines (`Source Serif 4`):** Used for titles, section headings, and core value statements. Reflects corporate longevity and integrity.
*   **Body & Labels (`Inter`):** Used for description lists, case study details, pricing matrices, and form labels.
*   **Arabic Text (`Amiri`):** Fallback font for any script or quotes of Arabic origin.

## 4. Spacing & Structure
*   **Layout Grid:** Standard 1280px max-width container, featuring flexible 3-column benefit grids and staggered 2-column alternating text/screenshot splits.
*   **Mockups & Frames:** Product mockups are presented in simplified flat structures with thin outlines and soft shadows.
*   **Borders & Radius:**
    *   Default Radius: `0px` to `0.125rem` (very sharp parameters) to represent structure and discipline.
    *   Mockups: `0.5rem` to reflect physical devices.

## 5. Key Components

### Product Portfolio Grid
*   Structured grid showcasing products like AmnShield, focus apps, and utilities.
*   Uses cards with elevated white containers and thin outlines.

### Services & Value Callouts
*   Clear alternating sections using `bg-surface-container` background shifts to separate consultancy offerings (mobile dev, privacy audits).

### Contact & Consultation Form
*   Clean border-bottom inputs that transition focus states to primary color highlights.

## 6. Motion & Animations
*   **Transitions:** Standard interactive transitions (hovers, active states) use a duration of `300ms` with `transition-colors` or `transition-opacity`.
*   **Micro-interactions:** Buttons shift opacity slightly on hover, and active navigation links highlight in Gold.
