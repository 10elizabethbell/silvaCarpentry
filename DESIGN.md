---
name: Silva Carpentry LLC
description: Finish carpentry measured out on a pullable tape blade and snapped into sections with pluckable chalk lines.
colors:
  chalk-navy: "#142a4c"
  chalk-deep: "#0f2140"
  primed: "#f3f5f2"
  field-white: "#ffffff"
  ink: "#13294b"
  ink-soft: "#43597a"
  tape: "#f5c400"
  tape-hover: "#ffd31f"
  tape-ink: "#1d2430"
  chip-on: "#fff6cc"
  stud: "#d6332a"
  chalk: "#4f8fe6"
  focus: "#2f6fd6"
  on-navy: "#f5f7fa"
  on-navy-soft: "#c3d1e8"
  rule: "#c9d2de"
  error: "#b3261e"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.9rem, 15vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.4rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.3rem"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "0"
  list-name:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.18rem"
    fontWeight: 850
    letterSpacing: "0.01em"
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1rem, 4.4vw, 1.25rem)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 800
    lineHeight: 1.55
rounded:
  tape: "3px"
  check: "4px"
  control: "10px"
  round: "50%"
spacing:
  gutter-phone: "20px"
  gutter-desk: "40px"
  tight: "12px"
  field-gap: "22px"
  block: "26px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.tape}"
    textColor: "{colors.tape-ink}"
    rounded: "{rounded.control}"
    padding: "0 26px"
    height: "58px"
  button-primary-hover:
    backgroundColor: "{colors.tape-hover}"
    textColor: "{colors.tape-ink}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.on-navy}"
    rounded: "{rounded.control}"
    padding: "0 26px"
    height: "58px"
  text-field:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "13px 14px"
    height: "54px"
  chip:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.chip-on}"
    textColor: "{colors.ink}"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.list-name}"
    padding: "10px 2px"
    height: "72px"
  step-tape:
    backgroundColor: "{colors.tape}"
    textColor: "{colors.tape-ink}"
    rounded: "{rounded.tape}"
    height: "40px"
---

# Design System: Silva Carpentry LLC

## Overview

**Creative North Star: "The Tape and the Chalk Line"**

A finish carpenter lives by the tape. The page is measured out on a live tape blade the visitor can pull from its case, and it is snapped into sections with chalk lines that can be plucked like string. Everything else stays out of the way: two flat, full-width grounds (deep chalk-line navy and paint-grade primed white) alternate down the page, and the only loud material is the tape itself.

The system is heavy, plain and trade-literal. Type is the system sans at black weight, set in uppercase, tight and large; it reads like a stencilled job sign, not an agency layout. Icons are molding-profile line drawings (casing, crown, baseboard sections), the numbered steps are printed on short tape segments, and the 16-inch stud mark is the only red on the page. The stock contractor template (hero photo, icon cards, stats band) is refused.

Density is low and phone-first: one column on phones, a single tap target per row, generous 44px-plus hit areas, and every contact path ending in a call or a pre-written text.

**Key Characteristics:**
- Two flat grounds, navy and primed white, alternating full width; no cards, no panels.
- Chalk-line dividers at every ground change, pluckable, with powder rather than a vector stroke.
- A live tape measure in the hero: straight steel with slight gravity sag, numbered from the hook, snaps home on release.
- Tape yellow is a material, not a highlight colour: the primary action, the blade and the tape segments.
- Black-weight uppercase system sans for every heading.
- Molding-profile line icons drawn at 2.2px stroke in the ink colour.

## Colors

Two trade grounds (chalk-line navy, primed trim white) and one loud material (tape-blade yellow), with chalk blue and focus blue doing quiet work and stud red held to a single job.

### Primary
- **Tape-Blade Yellow** (`tape`): the primary action fill ("Text us a photo", "Text this to Silva Carpentry"), the tape blade and case, and the numbered step segments. Also the border of the outlined button, the phone icon, the selected-chip border, the service-row arrow fill on hover/focus, link hover on navy, and text selection.
- **Bright Blade** (`tape-hover`): the primary button's hover fill, nothing else.
- **Graduation Ink** (`tape-ink`): text, graduations and numbers printed on yellow.

### Secondary
- **Chalk Blue** (`chalk`): the chalk-line dividers and their powder puffs, only. Drawn as layered translucent passes of this hue, never as a solid stroke.
- **Layout Blue** (`focus`): every form outline on hover and focus, the focus ring on primed ground, and the text caret. It is the "this is live" colour for controls.

### Tertiary
- **Stud Red** (`stud`): the plate behind every 16th inch on the tape blade (16, 32, ...), with white numerals. Nowhere else.

### Neutral
- **Chalk-Line Navy** (`chalk-navy`): header, hero, the steps section and the closing band; also the browser theme colour.
- **Deep Navy** (`chalk-deep`): reserved footer ground (declared; the shipped footer sits inside the closing navy band).
- **Primed White** (`primed`): the light ground for services and the quote form.
- **Field White** (`field-white`): inside text fields and chips, one step brighter than primed so controls read as surfaces.
- **Trim Ink** (`ink`): text and icons on primed ground.
- **Soft Ink** (`ink-soft`): secondary text on primed (notes, ledes, "(optional)"), checkbox borders.
- **Navy Text** (`on-navy`) and **Soft Navy Text** (`on-navy-soft`): primary and secondary text on navy.
- **Pencil Rule** (`rule`): hairline row dividers, control borders at rest, arrow-circle borders. On navy the equivalent rule is soft navy text at 22% alpha.
- **Error Red** (`error`): validation message and invalid field border. Deliberately a different, darker red from stud red.

### Named Rules
**The Tape Is the Accent Rule.** Yellow as a resting fill appears only on the primary action, the tape blade and case, and the tape step segments. Every other yellow is a state (hover, focus, selected) or a thin edge. If a new element wants yellow at rest, it must be the primary action or a piece of tape.

**The Stud Mark Rule.** Stud red marks 16-inch centres on the tape blade and nothing else. Errors use their own darker red.

**The Two Grounds Rule.** Sections alternate chalk-line navy and primed white, full width, flat. No third ground, no tinted cards, no gradients behind content.

## Typography

**Display Font:** system sans stack (`-apple-system`, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same stack

**Character:** One family, pushed to black weight and uppercase for every heading, so it reads like stencilled lettering on a job sign; body stays regular weight at a comfortable phone size.

### Hierarchy
- **Display** (900, clamp(2.9rem, 15vw, 6rem), 0.98, uppercase, -0.02em): the hero headline only, capped at 9ch so it breaks into two or three heavy lines.
- **Headline** (900, clamp(2rem, 9vw, 3.4rem), 0.98, uppercase, -0.02em): section titles. The closing wordmark band runs larger (clamp(2.4rem, 12vw, 4.6rem) on phones, clamp(2.4rem, 6vw, 4.6rem) on desktop).
- **Title** (900, 1.3rem, uppercase, no tracking): step titles.
- **List name** (850, 1.18rem, uppercase, 0.01em): service row names; single-line on desktop.
- **Lede** (400, clamp(1rem, 4.4vw, 1.25rem), 1.5): the hero promise, max 34ch (40ch desktop), in soft navy text.
- **Body** (400, 17px, 1.55): all running text, `text-wrap: pretty`; ledes capped near 36 to 44ch.
- **Label** (800, 1rem): form labels and legends; "(optional)" drops to 500 in soft ink. Button text is 800 at 1.06rem.
- **Wordmark** (900, uppercase, 0.04em, with "LLC" beneath at 0.75rem, 700, 0.18em tracking).
- Phone numbers use tabular numerals.

### Named Rules
**The House Stack Rule.** The system font stack is the house face, by the owner's decision (PRODUCT.md: "system font stack"). Do not introduce a webfont or a separate display face; weight and case carry the hierarchy.

**The Uppercase Heading Rule.** Every heading (h1 to h3, service names, wordmark) is uppercase at 850 to 900 weight with `text-wrap: balance`. Body copy and labels are never uppercase.

## Layout

Single-column, phone-first. Content sits in a centred container (max 1160px) with 20px gutters on phones and 40px from 760px. Sections are full-bleed colour bands; there are no cards or boxed panels.

- **Breakpoints:** below 380px (chips tighten), 760px (desktop layout: two-column service list with a 48px column gap, three-column steps, side-by-side hero actions, larger tape band), 1024px (quote section splits 5fr / 7fr with the heading column sticky at 40px).
- **Section rhythm:** roughly 34 to 48px vertical padding on phones, 56 to 72px on desktop.
- **Inner rhythm:** 12px between stacked buttons, 22px between form fields, 26px before action groups and between steps.
- **Hero:** wordmark left, tap-to-call number top right, headline, promise, two actions, then the tape band (clamp(170px, 30svh, 250px) tall on phones; 440px on desktop, pulled up 200px under the copy, with the blade kept clear of the text).
- **Contact placement:** the phone number appears only top-right on the first screen (and again beside the quote button and in the footer); email appears only in the footer. No sticky bottom bar.
- Safe-area insets are respected at the top of the header and the bottom of the footer.

## Elevation & Depth

Flat by default. Content grounds and controls carry no shadow; depth belongs only to the physical tape objects.

### Shadow Vocabulary
- **Tape lift** (`box-shadow: 0 6px 14px rgba(5,14,30,.35)`): the numbered tape step segments, so they sit on the navy like a real piece of blade.
- **Blade and case** (canvas shadow, rgba(4,12,28,.42 to .5), blur 12 to 18, offset-y 8 to 9): the hero tape measure.
- **Focus halo** (`box-shadow: 0 0 0 3px rgba(47,111,214,.25)`): focused text fields and chips; a state ring, not elevation.

### Named Rules
**The Only Tape Casts a Shadow Rule.** Shadows belong to tape objects. Buttons, rows, fields and sections stay flat.

## Shapes

Gently rounded controls (10px) against hard, full-width section edges. Tape segments are nearly square-cornered (3px), checkboxes 4px, and the service-row arrow is a full circle. Section boundaries are never straight rules: they are chalk lines, drawn as a wavering powder edge where one ground meets the next. Lists use 1px hairline rules top and bottom rather than boxes.

## Components

### Buttons
Solid, wide, thumb-sized.
- **Shape:** gently rounded (10px), min height 58px, 26px side padding, 2px tape border, 22px leading icon.
- **Primary:** tape fill, graduation ink text, 800 weight. Full width on phones; inline on desktop.
- **Hover / Focus:** hover brightens the fill to bright blade; press nudges down 1px. On the quote form the primary also gains a 3px layout-blue outline on hover. Focus ring is 3px layout blue on primed, 3px tape yellow on navy.
- **Outline:** transparent with a tape border and navy text, used once beside the primary in the hero; hover adds a 12% yellow wash.

### Chips
- **Style:** field white, 2px rule border, 10px radius, 46px tall, 700 weight, with a 16px square checkbox drawn in soft ink.
- **State:** hover turns the border layout blue; focus adds the blue halo; checked fills chip-on cream with a tape border and an ink checkbox with a white tick. Two columns on phones, auto-fill at 160px from 1024px.

### Inputs / Fields
- **Style:** field white, 2px rule border, 10px radius, 54px min height (textarea 120px), 17px text so iOS does not zoom. Selects use a drawn chevron.
- **Hover / Focus:** border turns layout blue on hover and on focus; focus adds the 3px blue halo. The caret is layout blue.
- **Error:** border and message in error red, message 700 weight below the field.

### Navigation
There is no menu. The header is the wordmark (links to top) and the tap-to-call number with a yellow phone glyph; the number turns yellow on hover.

### Service Row
A full-width link row, 72px min height, between hairline rules: a 44px molding-profile icon, the uppercase service name, and a 44px circular arrow. Tapping opens a pre-written text for that service. Hover changes only the arrow (fills tape yellow with a tape border); the row itself gets no background, underline or shadow. Keyboard focus fills the arrow and rings it in layout blue.

### Tape Step
Numbered steps print their number on a short tape segment (40px tall; 58px wide on phones, 96px on desktop) with CSS-drawn graduations on both edges and the tape lift shadow.

### Tape Measure (hero signature)
A canvas tape measure runs out of its case along the bottom of the hero.
- The blade is straight steel with only slight gravity sag (it cannot bend sideways), cupped darker toward its edges, with quarter-inch graduations and numbers measured from the hook.
- Every 16th inch sits on a stud-red plate with white numerals.
- On phones only even inches are numbered from 8 on, so numbers never run together.
- At rest it measures on its own; a finger drags the hook anywhere in the band and a mouse steers it while hovering. On release it snaps home, the case kicks and the steel shivers, then measuring resumes.
- On desktop the blade rises into the open space and is kept clear of the headline and buttons.
- Reduced motion draws one static extended blade.
- Tunables live in the IIFE's `TUNE` object. Sawdust is off (`DUST_PHONE` and `DUST_DESK` = 0) because at this size it read as stars.

### Chalk Line (section divider)
Every ground change is a chalk line: an SVG string simulation (64 nodes) with the upper ground behind and the lower ground filled up to the line. It is drawn as a broken core plus two irregular translucent powder passes in chalk blue, so it reads as powder, not a vector stroke. A finger or mouse crossing it plucks it at that point, with a small chalk puff on fast plucks; it also plucks itself softly every 6 to 12 seconds while on screen. Tunables live in its `TUNE` object. Reduced motion leaves it still.

## Do's and Don'ts

### Do:
- **Do** alternate full-width chalk-line navy and primed white grounds, and join them with a chalk line.
- **Do** keep tape yellow as a resting fill for the primary action, the blade and the tape segments only.
- **Do** set every heading in the system stack at 850 to 900 weight, uppercase.
- **Do** outline form controls in layout blue on hover and focus.
- **Do** use molding-profile line drawings (2.2px stroke, ink colour) for service icons.
- **Do** keep the phone number top-right on the first screen and the email in the footer only.
- **Do** keep hit areas at 44px or more and text fields at 17px.
- **Do** expose motion tunables in each feature's `TUNE` object and honour reduced motion.

### Don't:
- **Don't** use stud red for anything but the 16-inch marks on the tape.
- **Don't** add a webfont or a separate display face; the system stack is the house face.
- **Don't** add a sticky bottom call bar.
- **Don't** change a service row's background, underline or shadow on hover; only the arrow changes.
- **Don't** bend the tape blade sideways or number it from the case; it runs straight from the mouth, sags slightly, and is numbered from the hook.
- **Don't** turn sawdust or floating particles back on in the hero.
- **Don't** put shadows on buttons, rows, fields or sections.
- **Don't** use a hero photo, icon cards or a stats band.
