# meshcode-ai/skills-copy

![Copy & Content cover](assets/cover.svg)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-blue)](#)
[![Standard](https://img.shields.io/badge/agent--skills-spec-brightgreen)](https://agentskills.io/specification)

Copywriting and content skills for Claude Code, Codex, Cursor — landing copy, cold email, email subject lines, content strategy, content briefs, brand voice, copy editing, AI phrasing removal (humanize), and PR outreach. 10 knowledge-first agent skills in Korean, distilled from open-source marketing playbooks (MIT: coreyhaines31/marketingskills, anthropics/skills brand-guidelines, blader/humanizer). Use them with meshcode desktop, Claude Code, Codex, Cursor, or any Agent Skills-compatible runtime for copywriting, content creation, email outreach, and brand-consistent messaging at agent speed.

## Install

Download the zip → extract into your project's `.meshcode/skills/` (keep the flat layout). Automatically exposed from the next session onward.

## Who this is for

- **Founders / solo marketers** — SaaS founders who need to write landing copy, cold emails, and newsletters themselves without a copywriter
- **Content owners** — editors who must run strategy → brief → draft → editing consistently through delegation documents
- **Brand managers** — people who manage voice guides and rewrites so the tone never drifts across channels
- **AI agent operators** — users who want to equip Claude Code / Codex / Cursor with copy and content expertise

## TOC

- [Skills](#skills)
- [Role separation](#role-separation)
- [Hub & sibling repos](#hub--sibling-repos)
- [Use with meshcode](#use-with-meshcode)

## Skills

| Skill | Description summary |
|---|---|
| `copy-copywriting` | Framework judgment — AIDA/PAS/BAB/OBJ/4U selection criteria, headlines, features→benefits, CTA. "copywriting", "headline writing" |
| `copy-landing-copy` | Landing page copy — 3 hero elements, section order, message match, CTA. "landing page copy", "hero copy" |
| `copy-copy-editing` | 3-pass manuscript review — structure/sentences/notation, weak-verb and repetition removal, defensibility checklist. "copy editing", "sentence polishing" |
| `copy-cold-email` | First-touch cold email — the 150-word rule, 1 line of personalization, single CTA, 3 follow-ups. "cold email" |
| `copy-email-sequences` | Email copy — subject lines, preview text, scan-structured body. "subject line", "email copy" |
| `copy-content-strategy` | Content strategy — pillar selection, 80-10-10, channel matrix, 90-day calendar. "content strategy", "content calendar" |
| `copy-content-brief` | Brief = acceptance spec — SERP gap, intent anchoring, 10 elements. "content brief", "writing guidelines" |
| `copy-brand-voice` | Voice guidelines — 4-axis setup, per-channel tone variation, before/after rewrites. "brand voice", "tone & manner" |
| `copy-humanize` | Removing AI boilerplate — opening deletion, rhythm mixing, specificity injection. "humanize", "AI phrasing removal" |
| `copy-pr-outreach` | Press releases and journalist pitches — 5 news-value criteria, 5W1H lead, embargo. "press release", "journalist pitch" |

## Role separation

`copy-copywriting` handles framework selection (what to write), while `copy-landing-copy` handles the layout of a single page (where it goes). `copy-content-strategy` decides what to create, `copy-content-brief` turns it into a delegation document, and `copy-copy-editing` delivers the final verdict on a draft. `copy-cold-email` (1:1 first touch) and `copy-email-sequences` (1:N body and subject) are the two branches of email copy. Flow design (when to send) pairs with `mkt-email-sequences` in [skills-marketing](../skills-marketing/), and the SEO quality bar pairs with `seo-content-eeat` in [skills-seo](../skills-seo/).

## Hub & sibling repos

- Hub catalog: [meshcode-ai/skills](https://github.com/meshcode-ai/skills) — index of skills across all domains
- Sibling: [meshcode-ai/skills-seo](https://github.com/meshcode-ai/skills-seo) — 7 SEO/AEO skills
- Sibling: [meshcode-ai/skills-marketing](https://github.com/meshcode-ai/skills-marketing) — 20 funnel/growth/ads skills

## Use with meshcode

These skills are built for [meshcode](https://meshcode.ai) (free download — macOS/Windows):

1. Open your project in meshcode
2. In chat, ask **"show available skills"**, then **"install the copy skills"** — meshcode fetches from this repo automatically, no git or terminal needed
3. They appear in the next session and load only when a task matches, so installing all of them stays cheap

Manual alternative: download this repo's zip and extract into your project's `.meshcode/skills/`. Also works in Claude Code (`~/.claude/skills/`), Codex, and Cursor.

