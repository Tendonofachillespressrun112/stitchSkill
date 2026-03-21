# Design System Template

> **Usage:** Fill this template during Step 3, combining system_context.md + style_references.md.
> Save as: `projects/<project-name>/design_system.md`
> This content is injected as PART 1 of every screen prompt for visual consistency.

---

## App Identity

- **App Name:** <!-- e.g., TaskLens -->
- **Tagline:** <!-- e.g., "Insight-driven project management" -->
- **Logo:** <!-- Description or reference -->
- **Favicon:** <!-- Description -->

---

## Color Palette

### Primary Colors
| Name | Hex | Usage |
|---|---|---|
| Primary | `#` | Buttons, active states, links |
| Primary Dark | `#` | Hover states, headers |
| Primary Light | `#` | Backgrounds, badges |

### Neutral Colors
| Name | Hex | Usage |
|---|---|---|
| Background | `#` | Page background |
| Surface | `#` | Cards, panels |
| Border | `#` | Dividers, input borders |
| Text Primary | `#` | Headings, body text |
| Text Secondary | `#` | Labels, hints |
| Text Muted | `#` | Placeholders, disabled |

### Semantic Colors
| Name | Hex | Usage |
|---|---|---|
| Success | `#` | Positive states |
| Warning | `#` | Caution states |
| Error | `#` | Error states |
| Info | `#` | Information states |

### Theme
- **Mode:** <!-- Light / Dark / Both -->
- **Overall feel:** <!-- e.g., "Modern, clean, professional" -->

---

## Typography

| Role | Font Family | Size | Weight | Color |
|---|---|---|---|---|
| H1 | | 28px | Bold | Text Primary |
| H2 | | 22px | Semibold | Text Primary |
| H3 | | 18px | Semibold | Text Primary |
| Body | | 14px | Regular | Text Primary |
| Caption | | 12px | Regular | Text Secondary |
| Button | | 14px | Medium | White / Primary |

---

## Navigation Structure

> ⚠️ **CRITICAL**: This navigation is FIXED across ALL screens. Every screen prompt must include this exact structure.

### Sidebar (Left)
<!-- Define the exact menu items, icons, and groupings -->

| Group | Item | Icon | Target Screen |
|---|---|---|---|
| Main | Dashboard | 📊 | S01 |
| Main | Tasks | ✅ | S04 |
| | | | |
| Settings | Settings | ⚙️ | S10 |

### Top Bar
<!-- Define what appears in the top bar -->

| Element | Position | Description |
|---|---|---|
| App Logo | Left | Logo + app name |
| Search | Center | Global search bar |
| Notifications | Right | Bell icon with badge |
| User Avatar | Right | Profile dropdown |

---

## Layout Grid

- **Container max-width:** <!-- e.g., 1440px -->
- **Sidebar width:** <!-- e.g., 260px collapsed / 60px expanded -->
- **Content area padding:** <!-- e.g., 24px -->
- **Card padding:** <!-- e.g., 20px -->
- **Grid columns:** <!-- e.g., 12-column grid -->
- **Grid gap:** <!-- e.g., 16px -->

---

## Spacing Scale

| Token | Value | Usage |
|---|---|---|
| xs | 4px | Inline spacing |
| sm | 8px | Between related elements |
| md | 16px | Between sections |
| lg | 24px | Between major blocks |
| xl | 32px | Page margins |
| 2xl | 48px | Major separations |

---

## Component Patterns

### Cards
- Border radius: <!-- e.g., 12px -->
- Shadow: <!-- e.g., 0 1px 3px rgba(0,0,0,0.1) -->
- Background: Surface color
- Padding: Card padding from layout

### Buttons
| Variant | Background | Text | Border | Border Radius |
|---|---|---|---|---|
| Primary | Primary | White | None | 8px |
| Secondary | Transparent | Primary | 1px Primary | 8px |
| Ghost | Transparent | Text Secondary | None | 8px |
| Danger | Error | White | None | 8px |

### Tables
- Header: Background lighter, text bold
- Rows: Alternating subtle background
- Hover: Highlight row
- Borders: Horizontal dividers only

### Forms
- Input height: <!-- e.g., 40px -->
- Border radius: <!-- e.g., 8px -->
- Label position: Above input
- Error state: Error color border + message below

### Badges / Tags
- Border radius: <!-- e.g., 16px (pill) -->
- Size: Small padding
- Colors: Semantic or custom per status

---

## Iconography

- **Icon set:** <!-- e.g., Lucide, Material Icons, Heroicons -->
- **Default size:** <!-- e.g., 20px -->
- **Color:** Matches text color of context

---

## Sample Data (Cross-Screen Consistency)

> Use these names/values consistently across ALL screen prompts.

### Users
| Name | Role | Avatar Initial |
|---|---|---|
| | | |

### Projects / Items
| Name | Status | Key Metric |
|---|---|---|
| | | |

### Dates
- Current date shown: <!-- e.g., March 15, 2026 -->
- Date range: <!-- e.g., Q1 2026 -->
