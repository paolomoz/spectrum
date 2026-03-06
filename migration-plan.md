# Spectrum Adobe Design System — AEM EDS Migration Plan

**Source:** https://spectrum.adobe.com/
**Target:** AEM Edge Delivery Services (this project)
**Date:** 2026-03-06
**Total Pages:** 138 (137 sitemap + 1 homepage)

---

## Site Overview

Spectrum is Adobe's design system documentation site. All content pages live under `/page/{slug}`.

---

## Page Groupings (Detailed)

### Group A: Homepage (1 page)

| # | Slug | URL |
|---|------|-----|
| 1 | (root) | https://spectrum.adobe.com/ |

**Template:** Hero heading + description, large illustration, 3-column cards (Principles / Resources / Implementations), pagination link, footer.

---

### Group B: Component Documentation (59 pages)

Organized by the Spectrum side-navigation sub-categories:

#### B1 — Actions (8 pages)
| # | Slug | URL |
|---|------|-----|
| 1 | action-bar | https://spectrum.adobe.com/page/action-bar |
| 2 | action-button | https://spectrum.adobe.com/page/action-button |
| 3 | action-group | https://spectrum.adobe.com/page/action-group |
| 4 | button | https://spectrum.adobe.com/page/button |
| 5 | button-group | https://spectrum.adobe.com/page/button-group |
| 6 | close-button | https://spectrum.adobe.com/page/close-button |
| 7 | link | https://spectrum.adobe.com/page/link |
| 8 | menu | https://spectrum.adobe.com/page/menu |

#### B2 — Inputs (14 pages)
| # | Slug | URL |
|---|------|-----|
| 1 | checkbox | https://spectrum.adobe.com/page/checkbox |
| 2 | checkbox-group | https://spectrum.adobe.com/page/checkbox-group |
| 3 | color-area | https://spectrum.adobe.com/page/color-area |
| 4 | color-loupe | https://spectrum.adobe.com/page/color-loupe |
| 5 | color-slider | https://spectrum.adobe.com/page/color-slider |
| 6 | color-wheel | https://spectrum.adobe.com/page/color-wheel |
| 7 | combo-box | https://spectrum.adobe.com/page/combo-box |
| 8 | dropdown | https://spectrum.adobe.com/page/dropdown |
| 9 | field-label | https://spectrum.adobe.com/page/field-label |
| 10 | picker | https://spectrum.adobe.com/page/picker |
| 11 | radio-button | https://spectrum.adobe.com/page/radio-button |
| 12 | radio-group | https://spectrum.adobe.com/page/radio-group |
| 13 | search-field | https://spectrum.adobe.com/page/search-field |
| 14 | slider | https://spectrum.adobe.com/page/slider |
| 15 | swatch | https://spectrum.adobe.com/page/swatch |
| 16 | swatch-group | https://spectrum.adobe.com/page/swatch-group |
| 17 | switch | https://spectrum.adobe.com/page/switch |
| 18 | text-area | https://spectrum.adobe.com/page/text-area |
| 19 | text-field | https://spectrum.adobe.com/page/text-field |

#### B3 — Feedback (7 pages)
| # | Slug | URL |
|---|------|-----|
| 1 | alert-banner | https://spectrum.adobe.com/page/alert-banner |
| 2 | alert-dialog | https://spectrum.adobe.com/page/alert-dialog |
| 3 | bar-loader | https://spectrum.adobe.com/page/bar-loader |
| 4 | circle-loader | https://spectrum.adobe.com/page/circle-loader |
| 5 | coach-mark | https://spectrum.adobe.com/page/coach-mark |
| 6 | in-line-alert | https://spectrum.adobe.com/page/in-line-alert |
| 7 | progress-bar | https://spectrum.adobe.com/page/progress-bar |
| 8 | progress-circle | https://spectrum.adobe.com/page/progress-circle |
| 9 | toast | https://spectrum.adobe.com/page/toast |

#### B4 — Navigation (5 pages)
| # | Slug | URL |
|---|------|-----|
| 1 | breadcrumbs | https://spectrum.adobe.com/page/breadcrumbs |
| 2 | side-navigation | https://spectrum.adobe.com/page/side-navigation |
| 3 | tabs | https://spectrum.adobe.com/page/tabs |
| 4 | tab-bar-ios | https://spectrum.adobe.com/page/tab-bar-ios |
| 5 | bottom-navigation-android | https://spectrum.adobe.com/page/bottom-navigation-android |

#### B5 — Containers & Overlays (5 pages)
| # | Slug | URL |
|---|------|-----|
| 1 | application-frame | https://spectrum.adobe.com/page/application-frame |
| 2 | contextual-help | https://spectrum.adobe.com/page/contextual-help |
| 3 | popover | https://spectrum.adobe.com/page/popover |
| 4 | tooltip | https://spectrum.adobe.com/page/tooltip |
| 5 | tray | https://spectrum.adobe.com/page/tray |

#### B6 — Status & Info (6 pages)
| # | Slug | URL |
|---|------|-----|
| 1 | avatar | https://spectrum.adobe.com/page/avatar |
| 2 | badge | https://spectrum.adobe.com/page/badge |
| 3 | help-text | https://spectrum.adobe.com/page/help-text |
| 4 | meter | https://spectrum.adobe.com/page/meter |
| 5 | rating | https://spectrum.adobe.com/page/rating |
| 6 | status-light | https://spectrum.adobe.com/page/status-light |
| 7 | tag | https://spectrum.adobe.com/page/tag |

#### B7 — Content Display (6 pages)
| # | Slug | URL |
|---|------|-----|
| 1 | cards | https://spectrum.adobe.com/page/cards |
| 2 | divider | https://spectrum.adobe.com/page/divider |
| 3 | quick-actions | https://spectrum.adobe.com/page/quick-actions |
| 4 | table | https://spectrum.adobe.com/page/table |
| 5 | tool | https://spectrum.adobe.com/page/tool |
| 6 | tree-view | https://spectrum.adobe.com/page/tree-view |

**Template:** Component hero (title + description + illustration) → Anatomy → Options → Behaviors → Usage Guidelines (Do/Don't) → Content Standards → Internationalization → Keyboard Interactions → Theming → Changelog.
**Key blocks needed:** hero, anatomy, do-dont, image-gallery, keyboard-table, changelog, section-metadata.

---

### Group C: Data Visualization (12 pages)

| # | Slug | URL |
|---|------|-----|
| 1 | area-chart | https://spectrum.adobe.com/page/area-chart |
| 2 | axis | https://spectrum.adobe.com/page/axis |
| 3 | bar-chart | https://spectrum.adobe.com/page/bar-chart |
| 4 | big-number | https://spectrum.adobe.com/page/big-number |
| 5 | color-for-data-visualization | https://spectrum.adobe.com/page/color-for-data-visualization |
| 6 | data-visualization-fundamentals | https://spectrum.adobe.com/page/data-visualization-fundamentals |
| 7 | donut-chart | https://spectrum.adobe.com/page/donut-chart |
| 8 | histogram | https://spectrum.adobe.com/page/histogram |
| 9 | legend | https://spectrum.adobe.com/page/legend |
| 10 | line-chart | https://spectrum.adobe.com/page/line-chart |
| 11 | scatter-plot | https://spectrum.adobe.com/page/scatter-plot |
| 12 | scroll-zoom-bar | https://spectrum.adobe.com/page/scroll-zoom-bar |

**Template:** Same component-doc structure as Group B but focused on chart components. Has Anatomy, Options, Behaviors, Do/Don't, Keyboard Interactions sections.
**Note:** All chart visuals are static images (no interactive demos).

---

### Group D: Foundation & Design (20 pages)

| # | Slug | URL |
|---|------|-----|
| 1 | color | https://spectrum.adobe.com/page/color |
| 2 | color-fundamentals | https://spectrum.adobe.com/page/color-fundamentals |
| 3 | color-palette | https://spectrum.adobe.com/page/color-palette |
| 4 | color-palette-archive | https://spectrum.adobe.com/page/color-palette-archive |
| 5 | color-system | https://spectrum.adobe.com/page/color-system |
| 6 | design-tokens | https://spectrum.adobe.com/page/design-tokens |
| 7 | iconography | https://spectrum.adobe.com/page/iconography |
| 8 | icons | https://spectrum.adobe.com/page/icons |
| 9 | illustration | https://spectrum.adobe.com/page/illustration |
| 10 | motion | https://spectrum.adobe.com/page/motion |
| 11 | object-styles | https://spectrum.adobe.com/page/object-styles |
| 12 | platform-scale | https://spectrum.adobe.com/page/platform-scale |
| 13 | principles | https://spectrum.adobe.com/page/principles |
| 14 | responsive-grid | https://spectrum.adobe.com/page/responsive-grid |
| 15 | spacing | https://spectrum.adobe.com/page/spacing |
| 16 | states | https://spectrum.adobe.com/page/states |
| 17 | theming | https://spectrum.adobe.com/page/theming |
| 18 | using-color | https://spectrum.adobe.com/page/using-color |
| 19 | bi-directionality | https://spectrum.adobe.com/page/bi-directionality |
| 20 | inclusive-design | https://spectrum.adobe.com/page/inclusive-design |

**Template:** Hero (title + description), illustrated content sections with definition lists, visual comparisons, diagrams, resource links. Varies more page-to-page than component docs.
**Key blocks needed:** hero, columns, image-with-text, definition-list, section-metadata.

---

### Group E: Typography (6 pages)

| # | Slug | URL |
|---|------|-----|
| 1 | body | https://spectrum.adobe.com/page/body |
| 2 | code | https://spectrum.adobe.com/page/code |
| 3 | detail | https://spectrum.adobe.com/page/detail |
| 4 | headers | https://spectrum.adobe.com/page/headers |
| 5 | heading | https://spectrum.adobe.com/page/heading |
| 6 | typography | https://spectrum.adobe.com/page/typography |

**Template:** Same as Group D foundations. Heavy use of typographic specimens and visual scales.

---

### Group F: Content Design / Writing (11 pages)

| # | Slug | URL |
|---|------|-----|
| 1 | form-errors | https://spectrum.adobe.com/page/form-errors |
| 2 | grammar-and-mechanics | https://spectrum.adobe.com/page/grammar-and-mechanics |
| 3 | in-product-word-list | https://spectrum.adobe.com/page/in-product-word-list |
| 4 | inclusive-ux-writing | https://spectrum.adobe.com/page/inclusive-ux-writing |
| 5 | international-design | https://spectrum.adobe.com/page/international-design |
| 6 | voice-and-tone | https://spectrum.adobe.com/page/voice-and-tone |
| 7 | writing-about-people | https://spectrum.adobe.com/page/writing-about-people |
| 8 | writing-for-errors | https://spectrum.adobe.com/page/writing-for-errors |
| 9 | writing-for-onboarding | https://spectrum.adobe.com/page/writing-for-onboarding |
| 10 | writing-for-readability | https://spectrum.adobe.com/page/writing-for-readability |
| 11 | writing-with-visuals | https://spectrum.adobe.com/page/writing-with-visuals |

**Template:** Primarily text-heavy guideline pages with Do/Don't examples, tables, and inline images. Shares blocks with foundation pages.

---

### Group G: Resources & Utility (6 pages)

| # | Slug | URL |
|---|------|-----|
| 1 | contact-us | https://spectrum.adobe.com/page/contact-us |
| 2 | fonts | https://spectrum.adobe.com/page/fonts |
| 3 | home | https://spectrum.adobe.com/page/home |
| 4 | spectrum-xd-plugin | https://spectrum.adobe.com/page/spectrum-xd-plugin |
| 5 | ui-kits | https://spectrum.adobe.com/page/ui-kits |
| 6 | whats-new | https://spectrum.adobe.com/page/whats-new |

**Template:** Simpler layouts with download links, resource listings, contact forms. Likely each somewhat unique.

---

## Batch Sizes & Execution Strategy

### Mega-Batch Approach

The migration runs as **3 mega-batches**, each autonomous. Within each mega-batch, every step chains automatically — no pausing for confirmation unless a genuine ambiguity requires human input.

#### Mega-Batch 1: Foundation + Analysis + Block Development
**Scope:** Phases 1–4
**What it produces:** Design system, navigation, page templates, block implementations, import infrastructure
**Estimated skill invocations:** ~10

| Step | Skill | Input | Output |
|------|-------|-------|--------|
| 1.1 | `excat-complete-design-expert` | Homepage URL | styles/styles.css, fonts.css, lazy-styles.css |
| 1.2 | `excat-navigation-expert` | Homepage URL | content/nav.html, content/footer.html, header/footer blocks |
| 2.1 | `excat-site-analysis` | 138 URLs | page-templates.json (4 template skeletons) |
| 2.2 | `excat-page-analysis` × 4 | 1 sample per template | Analysis artifacts per template |
| 2.3 | `block-mapping-manager` | Analysis output | Updated page-templates.json with block mappings |
| 3.1–3.2 | `excat-eds-developer` | Block list | Custom block JS/CSS implementations |
| 3.3 | `block-variant-manager` | Block catalog | metadata.json with variant registry |
| 4.1 | `excat-import-infrastructure` | page-templates.json | Block parsers + page transformers |
| 4.2 | `excat-import-script` | Parsers + transformers | Executable import script |

#### Mega-Batch 2: Content Migration (all 138 pages)
**Scope:** Phase 5
**What it produces:** All 138 content HTML files in `/content/`

The `excat-site-migration` skill handles internal batching. Pages are fed **grouped by template** so the skill can reuse parsers/transformers per group.

| Batch | Group | Pages | Batch Size | URLs |
|-------|-------|-------|------------|------|
| 5.1 | A: Homepage | 1 | 1 | (root) |
| 5.2 | B1-B2: Actions + Inputs | 27 | 27 | action-bar through text-field |
| 5.3 | B3-B7: Feedback + Nav + Containers + Status + Content | 32 | 32 | alert-banner through tree-view |
| 5.4 | C: Data Visualization | 12 | 12 | area-chart through scroll-zoom-bar |
| 5.5 | D: Foundation & Design | 20 | 20 | color through inclusive-design |
| 5.6 | E+F: Typography + Content Design | 17 | 17 | body through writing-with-visuals |
| 5.7 | G: Resources & Utility | 6 | 6 | contact-us through whats-new |
| | | **Total: 115** | | *(+ ~23 already counted in sub-groups above)* |

**Total: 138 pages across 7 batches**

> **Why this grouping?** Pages within the same nav sub-category share identical DOM structure. Grouping by sub-category means a single parser/transformer handles every page in the batch with zero or minimal adjustments.

#### Mega-Batch 3: QA + Fix Loop
**Scope:** Phases 6–7
**What it produces:** CSS fixes, accessibility improvements, lint-clean code, commit

The QA loop runs iteratively:

```
for each template:
  1. Screenshot migrated page
  2. Screenshot original page
  3. Compare visually (excat-page-critique)
  4. Generate CSS fixes
  5. Apply fixes
  6. Re-screenshot → re-compare
  7. If acceptable → move to next template
  8. If not → drill into blocks (excat-block-critique) → fix → loop
```

| Step | Skill | Scope |
|------|-------|-------|
| 6.1 | `excat-page-critique` | 1 page per template (4 pages) |
| 6.2 | `excat-block-critique` | Individual blocks needing fixes |
| 6.3 | `excat-eds-debugger` | Cross-page consistency, responsive, a11y |
| 7.1 | (lint) | `npm run lint:fix` |
| 7.2 | (preview) | Verify 4 key pages at localhost:3000 |
| 7.3 | (commit) | Feature branch + push |

---

## Risks & Considerations (with Examples)

### Risk 1: JavaScript-Rendered Content (Next.js SSR/CSR)

**Impact:** HIGH — affects all 138 pages
**Description:** Spectrum is a Next.js application. Content is rendered client-side via JavaScript. A plain HTTP fetch (`curl`) returns an empty `<div id="__next">` shell with no content.

**Example — `/page/button`:**
```
$ curl -s https://spectrum.adobe.com/page/button | grep -c '<h1>'
0    # ← No heading in raw HTML
```
The `<h1>Button</h1>` heading, anatomy diagrams, options tables, and all other content only appear after JavaScript execution.

**Mitigation:** All page scraping must use **Playwright** (headless browser) instead of HTTP fetches. The migration infrastructure uses `browser_navigate` + `browser_evaluate` to capture the fully-rendered DOM. This is already handled by the EXCAT toolchain, but adds ~2-5 seconds per page load vs instant curl.

---

### Risk 2: Interactive Component Demos

**Impact:** MEDIUM — affects ~20 component pages that have interactive examples
**Description:** Some component documentation pages include live, interactive demos rendered with Spectrum Web Components or React Spectrum. These cannot be migrated as-is to static EDS HTML.

**Example — `/page/button`:**
The Options section on the Button page shows live interactive button variants (Primary, Secondary, Negative, etc.) where users can hover/click. On inspection:
```html
<!-- Source site renders these as live web components -->
<sp-button variant="primary">Primary</sp-button>
<sp-button variant="secondary">Secondary</sp-button>
```
These are custom elements (`<sp-*>`) that require the Spectrum Web Components runtime to function.

**Example — `/page/color-wheel`:**
Contains an interactive `<sp-color-wheel>` element users can manipulate — impossible to represent as static HTML.

**Mitigation:** All interactive demos are captured as **static screenshots** during scraping. The migrated page will show the screenshot image in place of the live demo. The visual result is identical for documentation purposes. Pages affected: button, checkbox, switch, slider, color-area, color-wheel, color-slider, color-loupe, dropdown, picker, combo-box, radio-button, search-field, text-field, text-area, rating, tabs, swatch, swatch-group, meter.

---

### Risk 3: Custom Blocks Required

**Impact:** HIGH — affects all component/data-viz pages (71 pages)
**Description:** The component documentation format uses several recurring patterns that don't exist in the EDS boilerplate or standard Block Collection.

**Example — Anatomy block (`/page/button`):**
Every component page has an Anatomy section with a labeled diagram:
```
┌─────────────────────────────────────┐
│   [Button illustration]             │
│      ↑1  ↑2    ↑3                   │
│                                     │
│   1. Container                      │
│   2. Label                          │
│   3. Icon (optional)                │
└─────────────────────────────────────┘
```
This is rendered as a custom React component (`illustrative-visual_anatomy`) with numbered callouts overlaid on an SVG. EDS needs a custom `anatomy` block with CSS-positioned labels.

**Example — Do/Don't block (`/page/button`):**
The Button page alone has **107 Do/Don't usage guideline instances**. Each is a paired comparison:
```
┌──────────────┐  ┌──────────────┐
│  [Image]     │  │  [Image]     │
│  ✓ Do        │  │  ✗ Don't     │
│  Use accent  │  │  Don't use   │
│  fill...     │  │  negative... │
└──────────────┘  └──────────────┘
```
The source uses `usage-guideline_do__*` and `usage-guideline_dont__*` CSS module classes. This needs a custom `do-dont` block.

**Example — Keyboard Interactions table (`/page/button`):**
```
┌────────────────┬───────────────────────────┐
│ Key            │ Description               │
├────────────────┼───────────────────────────┤
│ Space / Enter  │ Activates the button      │
│ Tab            │ Moves focus to next       │
└────────────────┴───────────────────────────┘
```
Uses `keyboard-interactions_keyboardInteractionsTable` class. Needs a custom `keyboard-table` block.

**Example — Changelog (`/page/button`):**
Version history table with Date, Version, download links for Spectrum and Express UI Kit files. Uses `changelog_notes` class.

**Full list of custom blocks required:**
| Block | Source Pattern | Pages Using It |
|-------|--------------|----------------|
| `anatomy` | `illustrative-visual_anatomy` | ~59 component + 12 data-viz = 71 |
| `do-dont` | `usage-guideline_do/dont` | ~59 component + 12 data-viz + ~11 content design = 82 |
| `keyboard-table` | `keyboard-interactions_*` | ~59 component + 12 data-viz = 71 |
| `changelog` | `changelog_notes` | ~59 component + 12 data-viz = 71 |
| `component-header` | Page hero with illustration | ~59 component + 12 data-viz = 71 |
| `image-gallery` | Options visual examples | ~59 component + 12 data-viz = 71 |

**Mitigation:** All 6 custom blocks are built in Phase 3 before any content migration begins. The `excat-eds-developer` skill creates JS + CSS for each. Block variant management (`block-variant-manager`) ensures consistent reuse across all 71+ pages.

---

### Risk 4: Rich Side Navigation

**Impact:** MEDIUM — affects site-wide UX
**Description:** Spectrum uses a multi-level collapsible side navigation with 7 top-level categories and nested sub-categories. The standard EDS header/nav pattern supports a flat or single-level navigation.

**Example — Side navigation structure (observed via Playwright):**
```
├── Spectrum (top-level)
├── Foundation
├── Content
├── Components ← expanded
│   ├── Actions
│   │   ├── Action bar
│   │   ├── Action button
│   │   ├── Action group
│   │   ├── Button        ← current page highlighted
│   │   ├── Button group
│   │   ├── Close button
│   │   ├── Link
│   │   └── Menu
│   ├── Containers
│   ├── Data visualization
│   ├── Feedback
│   ├── Inputs
│   ├── Navigation
│   ├── Status
│   └── Typography
├── Patterns
├── Tools and resources
└── Support
```
Plus a secondary nav rail:
```
├── Preview Spectrum 2 → (external)
├── Spectrum CSS → (external)
├── React Spectrum → (external)
└── Spectrum Web Components → (external)
```

This is a **3-level deep** nav tree. Standard EDS `nav.html` supports 2 levels.

**Mitigation:** The `excat-navigation-expert` skill will build a custom `side-nav` block that supports 3-level nesting with expand/collapse. The `content/nav.html` will encode the full tree structure using nested lists. The header block will be customized to render the hamburger → side-nav pattern matching the original.

---

### Risk 5: Image Volume & External References

**Impact:** LOW-MEDIUM — affects all pages
**Description:** The Button page alone has **85 images**. Across 138 pages, the total is estimated at **3,000–5,000 images**. During migration, images are referenced by their source URLs (not downloaded).

**Example — `/page/button` images:**
```
Images: 85
- Hero illustration (1)
- Anatomy diagrams (2)
- Options examples (~20 variants × 2 states each)
- Do/Don't comparison images (~40 pairs)
- Behavior illustrations (~10)
```

**Mitigation:** During migration, all `<img>` tags keep their source URLs (`https://spectrum.adobe.com/...`). Images render correctly in preview because they're fetched from the origin. For production:
- Images authored in the CMS will be automatically optimized by AEM
- For git-committed images, a separate optimization pass is needed
- The migration infrastructure handles image URL rewriting if needed

---

### Risk 6: Scale — 138 Pages, Repetitive Structure

**Impact:** MEDIUM — affects execution time and error accumulation
**Description:** 138 pages is a significant migration. Small errors in parsers compound across pages.

**Mitigation strategy:**
1. **Template-first:** Build and validate parsers against 1 representative page per template before running in batch
2. **Grouped execution:** Pages within the same nav sub-category share identical structure — process them together
3. **Validation checkpoints:** After each batch, spot-check 1 page visually before proceeding
4. **Fix-forward:** If a parser issue is found, fix it and re-run that batch (not the whole migration)

---

## Migration Phases

### Phase 1: Foundation Setup
**Goal:** Establish design system, navigation, and project infrastructure

#### Step 1.1: Design System Extraction
> **Skill:** `excat:excat-complete-design-expert`

Extract and migrate the Spectrum design tokens to EDS CSS custom properties:
- Colors (Spectrum blue `#1473E6`, grays, semantic colors)
- Typography (Adobe Clean font family, heading/body sizes, line heights)
- Spacing scale
- Border radius, shadows, elevation
- Responsive breakpoints

**Input:** https://spectrum.adobe.com/
**Output:** Updated `styles/styles.css`, `styles/fonts.css`, `styles/lazy-styles.css`

#### Step 1.2: Navigation Setup
> **Skill:** `excat:excat-navigation-expert`

Migrate the 3-level side navigation + footer:
- 7 top-level categories: Spectrum, Foundation, Content, Components, Patterns, Tools and resources, Support
- Nested sub-categories under Components (Actions, Containers, Data visualization, Feedback, Inputs, Navigation, Status, Typography)
- External links rail (Spectrum 2, Spectrum CSS, React Spectrum, Spectrum Web Components)
- Footer: Copyright + Privacy / Terms / Cookies / CCPA / AdChoices

**Input:** https://spectrum.adobe.com/
**Output:** `content/nav.html`, `content/footer.html`, header + footer blocks

---

### Phase 2: Site Analysis & Template Definition
**Goal:** Classify pages, analyze templates, map blocks

#### Step 2.1: Site-Level Analysis
> **Skill:** `excat:excat-site-analysis`

Create template skeletons for the 4 page types using all 138 URLs.
**Output:** `page-templates.json`

#### Step 2.2: Page Analysis (4 representative pages)
> **Skill:** `excat:excat-page-analysis` × 4 invocations

| Template | Representative Page | Why This One |
|----------|-------------------|--------------|
| Homepage | https://spectrum.adobe.com/ | Only homepage |
| Component Doc | https://spectrum.adobe.com/page/button | Richest component page (85 images, 107 do/donts, anatomy, keyboard table, changelog) |
| Foundation | https://spectrum.adobe.com/page/color-fundamentals | Content-heavy with glossaries, diagrams, visual comparisons |
| Resource | https://spectrum.adobe.com/page/fonts | Download-oriented, simpler structure |

**Output:** Analysis artifacts per template (JSON, screenshots, cleaned HTML)

#### Step 2.3: Block Mapping
> **Skill:** `excat:block-mapping-manager`

Map DOM selectors to EDS blocks. Full anticipated mapping:

| Source Selector Pattern | EDS Block | Custom? |
|------------------------|-----------|---------|
| `h1` + description + illustration (page top) | `hero` | Variant |
| `illustrative-visual_anatomy` | `anatomy` | Yes |
| `usage-guideline_do/dont` | `do-dont` | Yes |
| `keyboard-interactions_*Table*` | `keyboard-table` | Yes |
| `changelog_notes` | `changelog` | Yes |
| Multi-column card layouts | `columns` | No |
| Option variant images | `image-gallery` | Yes |
| `design-api_table` | `table` | No |
| Section backgrounds | `section-metadata` | No |
| Page title, description, image | `metadata` | No |

**Output:** Updated `page-templates.json`

---

### Phase 3: Block Development
**Goal:** Implement all required EDS blocks

#### Step 3.1–3.2: Block Implementation
> **Skill:** `excat:excat-eds-developer`

| Priority | Block | Type | Description |
|----------|-------|------|-------------|
| 1 | `hero` | Variant | Component page hero with title + description + illustration |
| 2 | `do-dont` | Custom | Side-by-side Do ✓ / Don't ✗ comparison with images |
| 3 | `anatomy` | Custom | Labeled diagram with numbered callouts |
| 4 | `keyboard-table` | Custom | Key → Description interaction table |
| 5 | `changelog` | Custom | Version history with download links |
| 6 | `image-gallery` | Custom | Grid of variant example images with captions |
| 7 | `columns` | Variant | 2-col, 3-col layouts for homepage cards |

#### Step 3.3: Block Variant Management
> **Skill:** `excat:block-variant-manager`

Register all variants in `metadata.json` with 70% similarity detection.

---

### Phase 4: Import Infrastructure
**Goal:** Build parsers and transformers

#### Step 4.1: Create Infrastructure
> **Skill:** `excat:excat-import-infrastructure`

Block parsers (1 per block type) + page transformers (1 per template).

#### Step 4.2: Build Import Script
> **Skill:** `excat:excat-import-script`

Combines parsers + transformers into a runnable import script.

---

### Phase 5: Content Migration
**Goal:** Migrate all 138 pages

> **Skill:** `excat:excat-site-migration` (handles batching internally)

| Batch | Group | Pages | Size | Notes |
|-------|-------|-------|------|-------|
| 5.1 | A: Homepage | 1 | 1 | Validation gate — verify before continuing |
| 5.2 | B1+B2: Actions + Inputs | 27 | 27 | Largest component batch |
| 5.3 | B3–B7: Remaining Components | 32 | 32 | Feedback, Nav, Containers, Status, Content Display |
| 5.4 | C: Data Visualization | 12 | 12 | Same template as B, different content focus |
| 5.5 | D: Foundation & Design | 20 | 20 | Different template, more text-heavy |
| 5.6 | E+F: Typography + Content Design | 17 | 17 | Similar to D, merged for efficiency |
| 5.7 | G: Resources & Utility | 6 | 6 | Smallest batch, most varied |
| | **TOTAL** | **115** unique slugs | **138** with sub-groups | |

---

### Phase 6: QA Loop (Iterate Until Right)
**Goal:** Visual fidelity, accessibility, consistency

```
REPEAT for each template (4 iterations):
  ├── excat-page-critique → compare full page
  ├── if issues found:
  │   ├── excat-block-critique → drill into problem blocks
  │   ├── fix CSS/JS
  │   └── re-verify
  └── if clean → next template

THEN:
  ├── excat-eds-debugger → cross-page consistency
  ├── responsive check (600px, 900px, 1200px)
  └── accessibility audit (heading hierarchy, ARIA, alt text)
```

**QA sample pages:**
| Template | Page | Why |
|----------|------|-----|
| Homepage | `/` | Only one, must be perfect |
| Component | `/page/button` | Most complex (85 images, 107 do/donts) |
| Foundation | `/page/color-fundamentals` | Content-dense with diagrams |
| Resource | `/page/fonts` | Download-oriented layout |

---

### Phase 7: Final Validation & Ship
**Goal:** Lint, verify, commit

1. `npm run lint:fix` — auto-fix all linting issues
2. Local preview verification at `localhost:3000` for 4 key pages
3. Commit to feature branch + push
4. Open PR with preview URLs

---

## Execution Summary

| Mega-Batch | Phases | Skills Used | Pages Touched | Checkpoint |
|------------|--------|-------------|---------------|------------|
| **1** | 1–4 | design-expert, navigation-expert, site-analysis, page-analysis, block-mapping, eds-developer, variant-manager, import-infrastructure, import-script | 4 samples | Verify blocks render in preview |
| **2** | 5 | site-migration (7 sub-batches) | 138 | Spot-check 1 page per batch |
| **3** | 6–7 | page-critique, block-critique, eds-debugger, lint | 4 QA + all | Clean lint, visual match, PR |

---

## Appendix: Skill Reference

| Skill | Purpose | Phase |
|-------|---------|-------|
| `excat:excat-complete-design-expert` | Design tokens, colors, fonts, spacing | 1.1 |
| `excat:excat-navigation-expert` | Navigation + footer | 1.2 |
| `excat:excat-site-analysis` | Template skeletons from URL patterns | 2.1 |
| `excat:excat-page-analysis` | Deep-dive page structure per template | 2.2 |
| `excat:block-mapping-manager` | DOM selector → EDS block mapping | 2.3 |
| `excat:excat-eds-developer` | Custom block JS/CSS | 3.1–3.2 |
| `excat:block-variant-manager` | Variant registry + similarity matching | 3.3 |
| `excat:excat-import-infrastructure` | Block parsers + page transformers | 4.1 |
| `excat:excat-import-script` | Executable import script | 4.2 |
| `excat:excat-site-migration` | Full content migration orchestrator | 5.1–5.7 |
| `excat:excat-page-critique` | Page-level visual comparison | 6.1 |
| `excat:excat-block-critique` | Block-level visual comparison | 6.2 |
| `excat:excat-eds-debugger` | Cross-page debugging + a11y | 6.3 |
