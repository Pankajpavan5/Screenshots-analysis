# Screen Analysis — `SCR-00 · <Screen Name>`

> **Source screenshot:** `screenshots/<filename>`
> **Analyst pass:** Screenshot-to-Project Analyzer · maximum depth
> **Target stack:** Native Android · Kotlin · Jetpack Compose · Material 3
> **Doc status:** Draft / Reviewed
>
> **Legend — confidence tags used throughout**
> `[OBSERVED]` = directly visible pixel evidence, not an inference.
> `[H]` High confidence inference · `[M]` Medium confidence · `[L]` Low confidence / speculative.
> Every non-`[OBSERVED]` statement carries a confidence tag. Nothing is presented as fact unless it is visible.

---

## 0. At-a-Glance Summary

| Field | Value | Confidence |
|---|---|---|
| Screen ID | `SCR-00` | — |
| Screen name (inferred) | | |
| Internal route name (proposed) | `Route.<Name>` | |
| Primary purpose | | |
| Primary user goal | | |
| Screen category | *(landing / list / detail / form / auth / settings / modal / utility / onboarding / dashboard / empty-state)* | |
| Navigation level | *(L0 root tab / L1 / L2 / L3 / overlay)* | |
| Parent screen | | |
| Child screens | | |
| Workflow position | *(step N of M in <flow>)* | |
| Screen state captured | *(default / loading / empty / error / populated / selected / expanded)* | |
| Device frame evidence | *(status bar, nav mode, aspect ratio, density estimate)* | |

**One-paragraph description.**
<What this screen is, who uses it, and why it exists — written for a developer who has never seen the screenshot.>

---

## 1. Screen Identification

### 1.1 Evidence inventory
Raw visual evidence used to classify this screen, listed before any conclusion is drawn.

| # | Evidence | Where on screen | What it implies | Confidence |
|---|---|---|---|---|
| E1 | | | | |
| E2 | | | | |

### 1.2 Classification reasoning
- **Why this screen name:**
- **Why this category:**
- **Why this navigation level:**
- **Rejected alternative interpretations:** *(what else it could be, and why that reading is weaker)*

### 1.3 Entry points into this screen
| From | Trigger | Transition | Confidence |
|---|---|---|---|

### 1.4 Exit points out of this screen
| To | Trigger | Transition | Confidence |
|---|---|---|---|

---

## 2. Layout Analysis

### 2.1 Structural skeleton
```
┌─ status bar (h ≈ 24dp) ───────────────────┐
│ <ASCII wireframe of the screen, to scale> │
└───────────────────────────────────────────┘
```

### 2.2 Vertical rhythm (top → bottom, measured in dp)
| Band | Region | Height (dp est.) | Fixed / Scrolls | Notes |
|---|---|---|---|---|

### 2.3 Grid & spacing system
- **Assumed canvas:** *(e.g. 1080×2400 px @ xxhdpi → 360×800 dp)* `[?]`
- **Horizontal page margin:**
- **Column grid:**
- **Gutter:**
- **Spacing scale detected:**
- **Base unit:**

### 2.4 Alignment & optical corrections
### 2.5 Safe areas & insets
### 2.6 Scroll regions vs. fixed chrome
| Region | Behavior | Evidence |
|---|---|---|

### 2.7 Responsive behavior projection
| Window size class | Layout adaptation | Confidence |
|---|---|---|
| Compact (<600dp) | | |
| Medium (600–840dp) | | |
| Expanded (>840dp) | | |

---

## 3. Component Detection (exhaustive)

> Every visible element, including dividers, 1dp hairlines, shadows, badge dots, and icon padding. Nothing is too small to list.

### C-01 · <Component name>
| Property | Value | Confidence |
|---|---|---|
| Type / M3 equivalent | | |
| Position (x, y from top-left, dp) | | |
| Size (w × h, dp) | | |
| Shape | | |
| Corner radius | | |
| Elevation / shadow | | |
| Fill color | | |
| Stroke | | |
| Typography | | |
| Icon(s) | | |
| State shown | | |
| Enabled / disabled | | |
| Selected | | |
| Purpose | | |
| Interaction | | |
| Visual hierarchy rank | | |
| Compose implementation | | |

*(repeat C-02, C-03, … for every element)*

### 3.x Component inventory roll-up
| ID | Component | M3 mapping | Reusable? | Appears on other screens |
|---|---|---|---|---|

---

## 4. Color Analysis
| Token | HEX (est.) | Where observed | Role | Confidence |
|---|---|---|---|---|

- **Palette harmony notes:**
- **Light/dark theme evidence:**
- **Derived M3 color roles:** *(primary, onPrimary, primaryContainer, surface, surfaceVariant, outline, error…)*

---

## 5. Typography
| Style token | Size (sp) | Weight | Line height | Letter spacing | Color | Used for | Confidence |
|---|---|---|---|---|---|---|---|

- **Font family estimate & reasoning:**
- **Type scale ratio:**
- **Heading hierarchy:**

---

## 6. Icon Analysis
| Icon | Glyph description | Library estimate | Size (dp) | Optical padding | Color | Meaning | Expected action | Confidence |
|---|---|---|---|---|---|---|---|---|

- **Icon style:** *(outlined / filled / rounded / sharp / two-tone / custom)*
- **Stroke weight consistency:**

---

## 7. Navigation Analysis
- **Back behavior:**
- **Up vs. back distinction:**
- **Tab/drawer participation:**
- **Deep link proposal:** `app://…`
- **Local navigation graph:**
```mermaid
graph LR
```

---

## 8. Functionality Analysis (per control)
### F-01 · <Control>
| Aspect | Detail | Confidence |
|---|---|---|
| Trigger | | |
| Expected behavior | | |
| Input | | |
| Validation | | |
| Output | | |
| Success state | | |
| Failure state | | |
| User feedback | | |
| Edge cases | | |

---

## 9. Feature Discovery
| Feature | Status | Evidence | Confidence |
|---|---|---|---|
| | Present / Implied / Missing / Premium / Admin | | |

---

## 10. User Flows Touching This Screen
```mermaid
flowchart TD
```
Step-by-step narrative:
1.

---

## 11. Business Logic
| Rule | Statement | Evidence | Confidence |
|---|---|---|---|

- **Permissions / roles:**
- **Data dependencies:**
- **Backend interactions:**
- **Offline behavior:**
- **Sync strategy:**

---

## 12. State Analysis
| State | Visual treatment | Trigger | Observed or inferred |
|---|---|---|---|
| Loading | | | |
| Empty | | | |
| Error | | | |
| Success | | | |
| Disabled | | | |
| Offline | | | |
| Editing | | | |
| Selected | | | |
| Expanded / Collapsed | | | |

---

## 13. Design System Contribution
- **New tokens this screen introduces:**
- **Components promoted to shared library:**
- **Spacing scale / radius scale / elevation scale confirmations:**

---

## 14. Accessibility Audit
| Check | Result | Measured / est. | Recommendation |
|---|---|---|---|
| Text contrast (WCAG AA 4.5:1) | | | |
| Touch target ≥48×48dp | | | |
| Font scaling to 200% | | | |
| Color-only information | | | |
| TalkBack labels needed | | | |
| Focus order | | | |

---

## 15. Animation & Motion Inference
| Element | Motion | Duration (ms) | Easing | Confidence |
|---|---|---|---|---|

---

## 16. Technical Architecture Notes (screen-scoped)
- **Composable tree:**
```kotlin
```
- **ViewModel + UiState:**
```kotlin
```
- **Events / intents:**
- **Repository calls:**
- **DI bindings:**

---

## 17. Data Model Touchpoints
| Entity | Fields used on this screen | Source | Confidence |
|---|---|---|---|

---

## 18. Screen Relationships
```mermaid
graph TD
```

---

## 19. Improvement Suggestions *(NOT part of the original design)*
> Everything below is a proposal, explicitly separated from the reverse-engineered spec above.

| # | Type | Suggestion | Impact | Effort |
|---|---|---|---|---|

---

## 20. Open Questions, Conflicts & Missing Information
| # | Question / conflict | Why it matters | How to resolve |
|---|---|---|---|

---

## 21. Confidence Summary for This Screen
| Analysis area | Confidence | Rationale |
|---|---|---|
| Screen identity | | |
| Layout & measurements | | |
| Component inventory | | |
| Color values | | |
| Typography | | |
| Iconography | | |
| Navigation | | |
| Functionality | | |
| Business logic | | |
| Data model | | |
| **Overall** | | |
