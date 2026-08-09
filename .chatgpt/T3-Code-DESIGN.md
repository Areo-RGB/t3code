---
version: alpha
name: T3 Code Mobile Light
description: "Light-only, mobile-first design system for the T3 Code showcase web app, preserving the native iOS-inspired hierarchy, coding surfaces, and responsive split-pane behavior."
colors:
  primary: "#007AFF"
  on-primary: "#FFFFFF"
  secondary: "#525252"
  tertiary: "#737373"
  neutral: "#F2F2F7"
  surface: "#F2F2F7"
  surface-container: "#FFFFFF"
  surface-container-high: "#F5F5F5"
  on-surface: "#262626"
  on-surface-strong: "#111111"
  on-surface-variant: "#737373"
  outline: "rgba(0, 0, 0, 0.10)"
  outline-variant: "rgba(0, 0, 0, 0.06)"
  search-background: "rgba(118, 118, 128, 0.12)"
  subtle: "rgba(0, 0, 0, 0.04)"
  subtle-strong: "rgba(0, 0, 0, 0.08)"
  success: "#199F43"
  success-bright: "#34C759"
  warning: "#9A6700"
  plan: "#A21CAF"
  error: "#DC2626"
  terminal-foreground: "#6C6C71"
  terminal-muted: "#8E8E95"
  terminal-success: "#0DBE4E"
  diff-add-background: "#E5F8F5"
  diff-delete-background: "#FFE6E7"
  diff-delete: "#D52C36"
typography:
  headline-lg:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 21px
    fontWeight: 650
    lineHeight: 1.1
    letterSpacing: -0.55px
  headline-md:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.2
  title-md:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 17px
    fontWeight: 700
    lineHeight: 1.28
    letterSpacing: -0.2px
  body-md:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.62
  body-sm:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
  label-md:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 12px
    fontWeight: 750
    lineHeight: 1.2
  label-sm:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 10px
    fontWeight: 750
    lineHeight: 1.1
  label-xs:
    fontFamily: "Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 9px
    fontWeight: 800
    lineHeight: 1
    letterSpacing: 0.45px
  terminal-md:
    fontFamily: "MesloT3, ui-monospace, monospace"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.7
  terminal-sm:
    fontFamily: "MesloT3, ui-monospace, monospace"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.6
rounded:
  none: 0px
  xs: 7px
  sm: 10px
  md: 13px
  lg: 16px
  xl: 20px
  xxl: 24px
  bubble: 21px
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 20px
  xxl: 24px
  content-gutter: 20px
  header-gutter: 16px
  composer-inset: 12px
components:
  app-shell:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
  surface-card:
    backgroundColor: "{colors.surface-container}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.xxl}"
    padding: "{spacing.lg}"
  activity-card:
    backgroundColor: "{colors.surface-container-high}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  fab-dark:
    backgroundColor: "{colors.on-surface}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.full}"
    height: 52px
    padding: "{spacing.lg}"
  message-user:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.bubble}"
    padding: "{spacing.md}"
  assistant-message:
    textColor: "{colors.on-surface-strong}"
    typography: "{typography.body-md}"
  search-field:
    backgroundColor: "{colors.search-background}"
    rounded: "{rounded.lg}"
    height: 48px
    padding: "{spacing.md}"
  icon-button:
    backgroundColor: "{colors.subtle}"
    rounded: "{rounded.full}"
    size: 44px
  icon-button-hover:
    backgroundColor: "{colors.subtle-strong}"
    rounded: "{rounded.full}"
    size: 44px
  secondary-label:
    textColor: "{colors.secondary}"
    typography: "{typography.label-sm}"
  tertiary-label:
    textColor: "{colors.tertiary}"
    typography: "{typography.label-sm}"
  status-working:
    textColor: "{colors.success}"
    typography: "{typography.label-xs}"
    rounded: "{rounded.full}"
  connection-dot:
    backgroundColor: "{colors.success-bright}"
    size: 7px
    rounded: "{rounded.full}"
  status-approval:
    textColor: "{colors.warning}"
    typography: "{typography.label-xs}"
    rounded: "{rounded.full}"
  status-plan:
    textColor: "{colors.plan}"
    typography: "{typography.label-xs}"
    rounded: "{rounded.full}"
  danger-action:
    textColor: "{colors.error}"
    typography: "{typography.label-sm}"
  terminal-surface:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.terminal-foreground}"
    typography: "{typography.terminal-md}"
  terminal-muted:
    textColor: "{colors.terminal-muted}"
    typography: "{typography.terminal-sm}"
  terminal-success:
    textColor: "{colors.terminal-success}"
    typography: "{typography.terminal-md}"
  diff-add-surface:
    backgroundColor: "{colors.diff-add-background}"
  diff-add-text:
    textColor: "{colors.success}"
    typography: "{typography.terminal-sm}"
  diff-delete-surface:
    backgroundColor: "{colors.diff-delete-background}"
  diff-delete-text:
    textColor: "{colors.diff-delete}"
    typography: "{typography.terminal-sm}"
  composer:
    backgroundColor: "{colors.surface-container}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.xxl}"
    padding: "{spacing.sm}"
  environment-card:
    backgroundColor: "{colors.surface-container}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.xxl}"
    padding: "{spacing.lg}"
---

# T3 Code Mobile Light Design System

## Overview

T3 Code Mobile Light is a **light-only, mobile-first coding workspace** designed to feel native on iPhone and Android while remaining comfortable on tablets and desktop browsers. The interface should feel calm, direct, technical, and highly legible rather than decorative.

The visual language follows modern iOS conventions: a soft system-gray canvas, white content surfaces, translucent headers, restrained borders, pill-shaped actions, and compact type. Information density is moderate-to-high, but hierarchy comes from spacing, weight, alignment, and tonal separation rather than heavy chrome.

The product has five canonical showcase surfaces: **Threads**, **Thread**, **Terminal**, **Review**, and **Environments**. All five must use the same light visual system. Do not introduce a dark terminal, dark diff viewer, or automatic dark-mode fallback.

## Colors

The palette is built around **iOS system neutrals with a single blue interaction accent**.

- **Primary — iOS Blue (`primary`, #007AFF):** Use for conversation emphasis and explicit completion/review actions. It is not the default fill for every button.
- **Ink (`on-surface`, #262626):** The dominant foreground and the fill for strong utility actions such as New Task, Send, and Save.
- **Screen (`neutral` / `surface`, #F2F2F7):** The persistent app canvas, terminal canvas, and review canvas.
- **Card (`surface-container`, #FFFFFF):** Cards, inputs, environment groups, composer surfaces, and floating light controls.
- **Raised Soft Surface (`surface-container-high`, #F5F5F5):** Low-emphasis grouped content and activity blocks.
- **Secondary/Tertiary neutrals (`secondary`, `tertiary`):** Metadata, subtitles, timestamps, icons, and quiet labels.
- **Success (`success`, `success-bright`):** Connected state, terminal success, completed activity, and working indicators.
- **Warning (`warning`):** Approval-required state.
- **Plan (`plan`):** Planning state.
- **Error (`error`, `diff-delete`):** Destructive controls and deleted diff lines.
- **Diff backgrounds:** Use `diff-add-background` and `diff-delete-background` as pale tonal rows, never as saturated blocks.
- **Terminal colors:** Keep the terminal light. `terminal-foreground`, `terminal-muted`, and `terminal-success` are calibrated for the #F2F2F7 terminal surface.

Borders are intentionally low contrast. `outline` is for explicit field/container boundaries; `outline-variant` is for separators and hairlines.

## Typography

The UI uses a **system-first sans stack** for native platform familiarity and **MesloT3** for code and terminal content.

- `headline-lg` is reserved for the T3 Code brand lockup and rare top-level identity moments.
- `title-md` is the dominant thread-list title level.
- `body-md` is the main conversation and application body style.
- `body-sm` handles supporting copy and empty-state descriptions.
- `label-md`, `label-sm`, and `label-xs` handle metadata, status pills, compact controls, environment fields, and technical labels.
- `terminal-md` is the default terminal text. At viewports of 430px or wider it may increase to 13px while keeping the same line-height character.
- `terminal-sm` is used for terminal chrome, diff metadata, and dense review details.

Use weight to establish hierarchy before increasing font size. Keep labels compact; do not turn the UI into a large-type marketing interface.

## Layout

The layout is **mobile-first and full-height**.

- Minimum supported viewport width is 320px.
- Primary list/header content is constrained to approximately 720px where appropriate.
- Horizontal screen gutters are normally 16–20px.
- The composer floats 12px from the viewport edge and respects safe-area insets.
- At **430px and above**, expose additional connection metadata and slightly widen conversation content.
- At **620px and below**, compress the review file sidebar and diff typography.
- At **900px and above**, render the app inside a framed desktop shell up to 1260px wide. Detail scenes become a two-pane layout with a 360px thread sidebar.
- At **1160px and above**, widen the sidebar to 390px and the changed-files panel to 285px.

Spacing follows a **4px base rhythm** with 8px, 12px, 16px, 20px, and 24px as the dominant steps. Prefer consistent internal rhythm over mathematically equal whitespace.

## Elevation & Depth

Depth is restrained and functional.

The base canvas uses #F2F2F7. White cards sit above it through tonal contrast, not heavy borders. Headers and the composer may use high-opacity white with backdrop blur to create a native translucent layer.

Use shadows only for floating or framed surfaces:

- The primary floating action button uses a soft downward shadow.
- The composer uses a broader low-opacity shadow to separate it from scrolling conversation content.
- On desktop, the entire app frame may use a large soft shadow against the outer neutral background.

Do not add Material-style elevation stacks or glossy glass effects. The interface should still read as flat and native at a glance.

## Shapes

The shape language is **soft, compact, and iOS-influenced**.

- Small identity marks and glyph tiles use 7–10px radii.
- Inputs and compact cards cluster around 13–16px.
- Large environment cards and the composer use 23–24px rounding.
- Conversation bubbles use a 21px body radius with an asymmetrical tighter corner to indicate direction.
- Icon buttons, status chips, scene navigation, and primary floating actions use fully rounded pills/circles.

Avoid sharp-cornered controls unless the element is code itself. Do not mix arbitrary radii; select from the `rounded` scale.

## Components

### Headers

Headers use a near-white translucent surface, a subtle bottom hairline, and backdrop blur. Keep the visual weight low so scrolling content remains dominant. Detail headers center the scene title and optional subtitle between navigation and action controls.

### Thread List

Thread rows sit directly on the screen surface rather than individual cards. Use a 17px title, 13–14px metadata, and subtle separators. Status pills are tiny and semantic: green for working, amber for approval, purple for plan, neutral gray for queued.

Project headers are quieter than thread titles. They group content without becoming card headers.

### Buttons and Actions

There are two principal action treatments:

1. **Ink actions:** `fab-dark` for high-confidence utility actions such as New Task, Send, and Save.
2. **Blue actions:** Use `primary` sparingly for explicit review completion or conversation emphasis.

Icon buttons are 44px circular touch targets on a faint neutral fill. Hover/pressed states should change tone or scale slightly rather than introducing heavy borders.

### Conversation

User messages use a compact rounded blue bubble. Assistant messages remain mostly unboxed on the neutral canvas, preserving reading width and reducing visual noise. Agent/tool activity appears in low-emphasis rounded activity cards.

The composer is a floating white rounded surface with a compact attachment button, expanding textarea, dark send control, and quiet footer metadata.

### Terminal

The terminal is **light-only** and uses MesloT3. Its background stays aligned with the screen gray rather than switching to black. Green is reserved for prompt accents, Vite/test success, and readiness. Chrome and secondary output use `terminal-muted`.

### Review

The review screen uses a light file navigator and light diff canvas. Additions receive a pale mint background; deletions receive a pale red background. Do not use dark code-editor styling.

On narrow screens, compress the changed-files rail rather than replacing the diff with a different interaction model.

### Environments

Environment groups are large white cards on the light sheet background. Rows are 72px minimum height with a rounded neutral icon tile, title/status stack, and chevron. Expanded editors use white inputs and compact 13px radii.

Connected states use green text. Destructive actions use red but remain visually secondary until invoked.

## Do's and Don'ts

- **Do** keep every canonical scene light, including Terminal and Review.
- **Do** use #F2F2F7 as the persistent canvas and white for elevated content surfaces.
- **Do** reserve #007AFF for high-signal interaction and conversation emphasis.
- **Do** use #262626 for strong utility actions when blue would be too visually dominant.
- **Do** preserve compact iOS-like type sizes and 44px touch targets.
- **Do** use the 4px spacing rhythm and the declared rounded scale.
- **Do** keep code and terminal content in MesloT3.
- **Do** respect safe-area insets and reduced-motion preferences.
- **Don't** add automatic dark mode, dark terminal styling, or dark review styling.
- **Don't** convert thread rows into heavy cards.
- **Don't** overuse borders; prefer tonal separation and hairlines.
- **Don't** use saturated semantic colors as large background fills.
- **Don't** introduce decorative gradients inside product surfaces; the subtle outer desktop framing gradient is the only exception.
- **Don't** replace the compact product UI with marketing-scale typography.
