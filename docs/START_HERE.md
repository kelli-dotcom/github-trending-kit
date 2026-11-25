# Start Here — One-Page Spec

## 1. The idea

A drop-in open-source launch kit of five AI skills, a Launch Director agent, and contributor templates that turn any GitHub repository into a clear, high-converting landing page.

## 2. Who it is for

Open-source maintainers, solo builders, and developer-tool founders who want stronger README conversion, discoverable GitHub topics, and crisp launch copy without hiring a growth agency.

## 3. What it does

- Audits and upgrades repository READMEs for first-screen clarity, Uneven U structure, and working live demos (`skills/top-github-readme`, `skills/readme-conversion-audit`).
- Generates targeted GitHub SEO topic tags and platform-native launch copy for Show HN, X, Reddit, and Dev.to (`skills/github-seo-topics`, `skills/launch-copy-generator`).
- Scaffolds contributor ergonomics (`CONTRIBUTING.md`, issue templates) and provides a live browser-based README & Uneven U Conversion Auditor in `preview/index.html`.

## 4. What it does NOT do

- Does not auto-post to social media, buy stars, or fabricate metrics, testimonials, or fake live demos.

## 5. How to tell it works

- Every `skills/*/SKILL.md` passes YAML frontmatter validation and `preview/index.html` stays under the `20 KB` Draft Feather Standard code limit.
- Open the live auditor at `https://kelli-dotcom.github.io/github-trending-kit/preview/` (`HTTP 200`) and paste any README to see instant conversion scoring, weak-prose flags, and topic suggestions.
- Run: `node tests/smoke.test.mjs` (or `bun tests/smoke.test.mjs` once `.github/workflows/ci.yml` is added).

## 6. What is left to do

1. Add `.github/workflows/ci.yml` so `tests/smoke.test.mjs` passes all 25 Repoverse manifest checks.
2. Add a real-world before/after README case study under `examples/`.
