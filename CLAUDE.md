# Grave Error — Site Guide

Read the master workspace guide first: [`..\CLAUDE.md`](../CLAUDE.md). It covers the
shared build recipe (Astro + GitHub Pages) and the publish steps. This file only covers
what's specific to Grave Error.

- **Domain:** graveerrorgame.com, served by GitHub Pages (repo `jwollberg/graveerrorgame`)
  through Cloudflare: apex and `www` are proxied CNAMEs to `jwollberg.github.io`, SSL mode
  "Full", same as atheosstudios.com. The old Page Rule that forwarded it to
  atheosstudios.com was deleted 2026-10-09.
- **What it is:** the one-page site for *Grave Error*, the zombie survival game by
  Atheos Studios. Links back to atheosstudios.com.
- **The old Google Sites page is gone.** It lived in the josh@atheosstudios.com
  Workspace, which is cancelled, and the Internet Archive never saved it. Its details
  were out of date anyway (Unity, "Coming soon", wishlist). Don't try to recover it.

## Design (2026-10-09)

- **"Nyx"**, the same design as atheosstudios.com: paper type on ink plus a deeper
  ink `#1E2228`, a turning star-dial hero, a star field, and the Grave constellation
  (the tombstone emblem plus stars). Same palette and fonts as the studio's brand kit:
  slate `#2A2E34`, paper `#FBFAF7`, ink `#262B33`, **Marcellus** (never bold it) +
  **Jost**.
- **Grave Error touches:** the dial's ring reads "It began with a software update…",
  one ring jolts out of true now and then, and the title glitches briefly every few
  seconds ("graveyard meets glitch"). Both stop for reduced-motion users.
- **No logo yet:** the header and footer use a Marcellus wordmark. The tab icon
  (`public/icons/`) is the cracked tombstone on dark slate.
- `src/components/Sprite.astro` is a copy of the Atheos site's: the Atheos laurel
  lockup and the game emblems.
- Sections: hero, I · The update (premise), II · The Hacks (six numbered notes),
  III · The world, studio credit, footer. No email signup, wishlist, socials or contact.
- The three files in `design-options/` are the old, unpicked 2025 teaser mockups with
  outdated copy. Ignore them.

## Copy rules

- **Ground every claim in the game's own canon:** `C:\Projects\Grave Error\LORE.md`
  (premise and settled facts) and `docs\vision.md`. Don't invent lore.
- **Facts:** 3D first-person zombie survival; solo or co-op for 2–4 players; PC;
  "realism first"; the status is **"Coming eventually"**. The risen are **Hacks**, the
  player is a **Null** (can't turn), the program is **HACK**, the update is **Core
  Update 3.0**. The world is procedurally generated present-day America, the size of
  the Earth.
- **Never say:** top-down or 2D, Unity, Early Access, Steam or wishlist, "coming soon",
  or any date. Present vehicles, crafting and traders as future plans, not features.
- **Voice:** ominous and sparse, and plain about the facts. The tagline "You don't beat
  this world. You outlast it." is Josh's. Avoid AI-sounding copy (stacked long
  dashes, rule-of-three lists, slogan filler). Neutral "we"; never imply a team and
  never say solo.

**Status:** live at graveerrorgame.com (shipped 2026-10-09). Push to `main` = deploy.
