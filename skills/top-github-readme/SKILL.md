---
name: top-github-readme
description: Design, audit, and rewrite any GitHub README.md using researched top-starred repository layouts (AFFiNE Product Showcase, shadcn/Drizzle Developer SDK, or Supabase System Map) tailored to the project type.
---

# Top GitHub README Skill

Use this skill whenever creating or upgrading a `README.md` so it matches the highest-converting open-source repositories on GitHub.

## Workflow
1. **Classify the Project Type:**
   - **Web App / Visual Product** → Use the *Product Showcase* layout (Hero Banner/Mascot + Real Animated Demo GIF + Comparison Table + 60s Quick Start).
   - **Library / CLI / Token Kit** → Use the *Developer SDK* layout (Centered Header + Instant 1-Command CLI Proof above the fold + Feature/Token Table + Copy-Paste Usage).
   - **AI Agent Suite / Protocol** → Use the *System Map* layout (Centered Header + Visual Preview/Diagram + Roster/Lifecycle Tables + 1-Command Installer + Mobile `<details>` ZIP).
2. **Apply the 10-Second Above-the-Fold Formula (Mandatory Visual Demo):**
   - Centered `<h1 align="center">` + 1-sentence value prop (no hype fluff).
   - Centered Quick-Nav bar (`Quick Start · Features · Architecture · Issues`).
   - 4–5 crisp `for-the-badge` shields.io badges (real signals only).
   - **Mandatory Integrated Demonstration:** Always embed a real visual demonstration (`assets/demo.gif` or `demo/preview.svg`) directly in the README showing the actual app, themes, or CLI/protocol working — never ship a text-only README.
3. **Weave in the Natural Clarity Story (5W+H) & Dual PC/Laptop + Mobile Quick Start:**
   - Naturally answer *who it's built for, what problem it eliminates, when to reach for it, where it runs, why it wins, and how to start in under 60 seconds* without robotic headings.
   - Always include both **💻 1. PC / Laptop Quick Start (Mac, Windows, Linux & Chromebook)** and **📱 2. Mobile Quick Start (iPhone, iPad & Android)** (with a collapsible `<details>` 1-tap ZIP download link, iOS/Android unzip instructions, and mobile AI app usage steps).
4. **Enforce Scannability & IP Safety:**
   - Replace dense paragraphs with comparison tables, clean folder trees, and `<details>` blocks.
   - Never name competitor trademarks in comparison tables (use generic category names).
   - Add a **CRTA Tech Solutions Ecosystem** cross-link table at the bottom so all repos lift each other's discoverability.
5. **Verify Before Pushing:**
   - Confirm every relative image path (`assets/banner.png`, `assets/demo.gif`, `demo/preview.svg`), anchor link, and clone URL resolves cleanly on GitHub.
