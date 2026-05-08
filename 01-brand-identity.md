# Graceland Boutique Vacation Club
## Brand Identity System v1.0

*Prepared by KGC for Jecoliah · DFBA · April 2026*

---

## 1. Brand Foundation

### What Graceland Is

Graceland Boutique Vacation Club is a multi-suite boutique hospitality property in South Bahamia, Freeport, Grand Bahama. It operates as both a guest-facing vacation destination and an investment-grade hospitality asset, with named suites (Amelia, Turks Cove, Andros Breeze) and a central courtyard that hosts events and serves as the property's social hub.

### Positioning

**A curated Bahamian retreat for travelers who want privacy, polish, and place.**

Graceland is not a hotel. It is not an Airbnb. It sits in the small, deliberate category of *boutique vacation clubs* — properties that combine the comfort of a private home with the service standards of hospitality. The "club" in the name is intentional: it implies access, curation, and a relationship that extends beyond a single stay.

### Brand Essence

> *More than a stay — a curated Bahamian experience.*

This existing tagline holds. It is the through-line across every suite, every event, and every investor conversation.

### Brand Pillars

1. **Curated** — Nothing is generic. Every suite is named, every experience is selected, every guest is considered.
2. **Bahamian** — Rooted in Grand Bahama and the wider archipelago. The names of the suites (Amelia, Turks Cove, Andros) are not decoration; they are anchors.
3. **Boutique** — Small by design. Personal by default. The opposite of resort-scale.
4. **Earned** — Investor-credible. The Courtyard is positioned as a daily-income asset, not a lifestyle aspiration. Quiet competence over loud marketing.

---

## 2. Audience

Graceland speaks to two audiences. The brand must hold both without leaning too far in either direction.

### Primary: The Curated Traveler
Returning Bahamian diaspora, regional professionals, and discerning international visitors who want a private base in Freeport. They book direct, value privacy, and care more about *fit* than amenity checklists.

### Secondary: The Hospitality Investor
Bahamian and regional investors looking at The Courtyard and future Graceland phases as income-producing assets. They need to see substance, numbers, and credibility — not vacation marketing.

The brand must feel polished enough that the investor takes it seriously, and warm enough that the guest feels welcomed. Quiet luxury does both.

---

## 3. Voice & Tone

### Voice (always true)

- **Composed.** Never breathless. Never hard-selling.
- **Specific.** Names places, names suites, names experiences. Avoids "amazing," "beautiful," "stunning."
- **Hospitable.** Warm without being familiar. The voice of a good host, not a brochure.
- **Confident.** Makes claims it can defend. Never manufactures urgency.

### Tone (shifts by context)

| Context | Tone |
|---|---|
| Suite descriptions | Warm, sensory, restrained |
| Investor materials | Substantive, precise, measured |
| Event hosting | Generous, occasion-aware |
| Booking confirmations | Crisp, reassuring |
| Social posts | Quiet, well-lit, low-frequency |

### Voice Examples

**Don't write:**
> Welcome to The Amelia Suite, an absolutely stunning 2-bedroom oasis where luxury meets paradise! Book now for an unforgettable experience!

**Do write:**
> The Amelia Suite. Two bedrooms, two baths, and a kitchen built for slow mornings. South Bahamia, twenty minutes from the airport.

---

## 4. Color System

The existing direction (deep navy + gold) is the right foundation. The system below refines it into a working palette with clear hierarchy and accessible contrast.

### Primary Palette

| Token | Name | Hex | Usage |
|---|---|---|---|
| `--graceland-navy` | Graceland Navy | `#0B1B2E` | Primary background, primary brand surface |
| `--graceland-navy-deep` | Deep Navy | `#06111E` | Deepest surface, dark headers, footers |
| `--graceland-gold` | Graceland Gold | `#C8A24B` | Primary accent, monogram, key calls-to-action |
| `--graceland-gold-soft` | Soft Gold | `#E2C684` | Type accents, fine rules, secondary highlights |

### Neutrals

| Token | Name | Hex | Usage |
|---|---|---|---|
| `--graceland-bone` | Bone | `#F4EFE6` | Light theme background, off-white surfaces |
| `--graceland-sand` | Sand | `#D9CFB8` | Light theme accent surface, dividers |
| `--graceland-stone` | Stone | `#8A8170` | Body text on bone, secondary text on light |
| `--graceland-ink` | Ink | `#1A1A1A` | Body text on bone, deep contrast on light |

### Functional Tones

| Token | Name | Hex | Usage |
|---|---|---|---|
| `--graceland-success` | Reef Green | `#3F7A5E` | Confirmations, "available" states |
| `--graceland-warning` | Amber | `#B88A2E` | Limited availability, attention |
| `--graceland-error` | Coral | `#A94B3B` | Errors, blocked states |

### Application Rules

1. **Navy dominates.** The brand is dark-first. Light surfaces are intentional moments, not the default.
2. **Gold is rare.** Gold is the accent for the monogram, primary CTAs, and key wordmark moments. It is never used for body text or large fields.
3. **One gold per surface.** Avoid gold-on-gold. Gold lives against navy or bone, never against itself.
4. **Bone is the breath.** When the brand needs to feel open or hospitable (booking flows, investor packets), bone takes over from navy.

### Contrast Pairings (verified)

- Gold `#C8A24B` on Navy `#0B1B2E` → 7.4:1 ✓
- Bone `#F4EFE6` on Navy `#0B1B2E` → 14.8:1 ✓
- Ink `#1A1A1A` on Bone `#F4EFE6` → 16.1:1 ✓
- Stone `#8A8170` on Bone `#F4EFE6` → 3.6:1 (large text only)

---

## 5. Typography

### Type Pairing

**Display: Cormorant Garamond**
A refined transitional serif with high contrast and elegant terminals. It carries the existing classical-serif feel of the wordmark but is sharper, more contemporary, and free for web use. Used for the Graceland wordmark, suite names, and major headings.

**Subhead: Playfair Display (semibold)**
For section labels and small caps treatments where Cormorant feels too thin. Used sparingly.

**Body: Inter Tight or Söhne (if licensed)**
A clean, neutral sans-serif. Inter Tight is the recommended free option — its tighter tracking pairs well with serif display type without competing.

**Mono: JetBrains Mono**
Reserved for booking codes, reservation numbers, and investor data tables.

### Type Scale (web)

| Role | Font | Weight | Size | Line Height | Tracking |
|---|---|---|---|---|---|
| Display XL | Cormorant Garamond | 400 | 72px | 1.05 | -0.02em |
| Display | Cormorant Garamond | 400 | 56px | 1.08 | -0.015em |
| H1 | Cormorant Garamond | 500 | 40px | 1.15 | -0.01em |
| H2 | Cormorant Garamond | 500 | 32px | 1.2 | -0.005em |
| H3 | Playfair Display | 600 | 22px | 1.3 | 0 |
| Eyebrow | Inter Tight | 500 | 12px | 1.4 | 0.18em (uppercase) |
| Body L | Inter Tight | 400 | 18px | 1.6 | 0 |
| Body | Inter Tight | 400 | 16px | 1.6 | 0 |
| Body S | Inter Tight | 400 | 14px | 1.5 | 0.005em |
| Caption | Inter Tight | 500 | 12px | 1.4 | 0.02em |

### Typographic Principles

1. **Serif for proper nouns, sans for everything else.** Suite names and the Graceland wordmark are always set in Cormorant. Booking buttons, body copy, and forms are always Inter Tight.
2. **Generous line height on display.** Cormorant is high-contrast and needs room to breathe. Never set display type below 1.05.
3. **Eyebrows do the work of decoration.** Small uppercase Inter Tight labels (12px, 0.18em tracking) replace ornamental dividers in most places.
4. **No italics in the system.** The brand voice is composed. Italics are reserved for editorial moments — pull quotes, the tagline, and nothing else.

---

## 6. Logo System

### The Existing Monogram

The "GB" monogram with the crown and roof element is the foundation of the system and is preserved. It is distinctive, ownable, and already has equity. The brand identity is built *around* it, not over it.

### Lockup Variants

The system needs four lockups to handle different applications cleanly:

1. **Primary Lockup (Stacked)**
   Monogram centered above "GRACELAND BOUTIQUE VACATION CLUB" wordmark. For hero placements, covers, and primary brand surfaces.

2. **Horizontal Lockup**
   Monogram on the left, wordmark on the right, vertically centered. For headers, email signatures, and constrained horizontal space.

3. **Compact Lockup**
   Monogram + "GRACELAND" only (no descriptor). For app icons, social avatars, favicons, and small-format placements.

4. **Mark Only**
   The GB monogram alone. For watermarks, loyalty cards, embossing, and contexts where the brand is already established.

### Clear Space

Minimum clear space around any lockup equals the height of the "G" in the wordmark. Nothing intrudes within this space — not images, not other type, not edges of containers.

### Minimum Size

- Primary lockup: 120px wide minimum (digital), 1.25" wide (print)
- Horizontal lockup: 180px wide minimum
- Mark only: 24px square minimum

### Color Applications

- Gold mark on navy field (primary, default)
- Navy mark on bone field (secondary, light surfaces)
- Bone mark on navy field (alternate, when gold is unavailable)
- Single-color mark in ink on bone (utility, faxes/forms)

### What Not To Do

- Never recolor the monogram outside the approved palette
- Never place the mark on photography without a navy or bone scrim behind it
- Never stretch, skew, rotate, or add effects (drop shadows, glows, outlines)
- Never combine the monogram with another logo lockup-style. Co-branding lives in the footer.

---

## 7. Sub-Brand & Suite Naming

Graceland is the parent brand. Everything else is a named offering beneath it.

### Naming Convention

**`The [Place Name] Suite`** — for accommodations
- The Amelia Suite
- The Turks Cove Suite
- The Andros Breeze Suite

**`The [Function] @ Graceland`** — for amenities and venues
- The Courtyard @ Graceland
- The Pool @ Graceland (future)

**`Graceland [Service]`** — for service tiers
- Graceland Concierge
- Graceland Memberships
- Graceland Investors

### Why This Matters

The naming system creates a brand architecture that scales. As Jecoliah adds suites, amenities, and investor products, each one slots into the system without needing a separate brand. The Graceland mark and wordmark stay consistent; the named layer carries the variation.

### Canonical Spellings (use these going forward)

- **South Bahamia** (not "South Bahama") — confirm with Jecoliah which is correct, then lock
- **Grand Bahama** (the island)
- **Graceland** (one word, capital G)
- **The Courtyard @ Graceland** (with the @ symbol, stylized)
- **2-bedroom, 2-bathroom** (lowercase, hyphenated) in body copy; **2BR / 2BA** in compact contexts

---

## 8. Photography & Imagery Direction

The current flyer photography is functional but inconsistent — mixed lighting, visible date stamps, varying composition. The brand needs a photography standard before the landing page goes live.

### Photography Principles

1. **Natural light, not staged.** Morning and late afternoon are the windows. Avoid harsh midday sun and on-camera flash.
2. **Wide and quiet.** Full-room compositions with breathing space. No close-up detail shots of a single pillow or faucet.
3. **People, occasionally.** A figure in soft focus — pouring coffee, on the porch — adds life without staging. No posed groups.
4. **Color discipline.** The palette of the photograph should sit inside the brand palette: navy, bone, sand, with gold as a natural accent (sun, wood, brass). Avoid loud reds, neon greens, and saturated party lighting.
5. **No date stamps. No watermarks.** The photographs are the asset; the brand context is in the layout around them.

### Until New Photography Exists

Use the cleanest existing photos (the suite interiors, not the parking lot exteriors). Apply a subtle navy duotone or a 5–10% navy color overlay to unify them. The site plan render (Image 6) is strong as-is and should anchor the "what's coming" section.

---

## 9. Application Principles

How the brand shows up in real surfaces.

### On the Web
- Dark-first. Navy backgrounds with bone surfaces for content blocks.
- Cormorant for everything that names something (suite, place, headline). Inter Tight for everything functional.
- Gold reserved for the monogram, the primary CTA, and the underline on hover states.
- Generous vertical rhythm. Refined boutique reads as *space*, not density.

### In Print
- Bone paper stock with navy ink + gold foil for premium pieces (welcome cards, investor packets).
- Single-color navy on bone for everyday print (receipts, internal forms).

### In Social
- Square or 4:5 only. The brand does not chase reels-first formats.
- Caption discipline: one sentence, one detail, one call to action. No emoji clusters.
- Post weekly, not daily. The brand earns attention by being worth waiting for.

### In Hospitality (in-suite)
- Welcome card: navy stock, gold monogram, handwritten guest name.
- Wi-Fi card: bone, navy ink, mono type for the password.
- Guidebook: bone cover, Cormorant title, Inter Tight body, sewn binding.

---

## 10. What's Next

This document is the foundation. The next pieces in the system are:

1. **Landing page (coming soon + dual waitlist)** — the immediate deliverable
2. **Booking flow design** — once direct bookings open
3. **Investor one-pager** — refined version of the existing Courtyard flyer
4. **Suite collateral templates** — replacing the current flyers with system-consistent versions
5. **Email templates** — confirmation, pre-arrival, post-stay, investor updates

Each of these inherits directly from the tokens, type system, and voice defined here.

---

*End of brand identity document v1.0*
