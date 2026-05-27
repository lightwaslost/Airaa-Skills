# Airaa Skills

> AI skills that make you a better creator-campaign operator — powered by [Airaa](https://airaa.xyz).

Install all skills in one command:

```bash
npx skills add lightwaslost/Airaa-Skills
```

Or install a single skill:

```bash
npx skills add lightwaslost/Airaa-Skills --skill airaa-campaign-planner
```

---

## What is a skill?

A **skill** is a file you add to your AI coding assistant (Claude Code, Cursor, Copilot, etc.) that teaches it how to do a specific job — step by step, using real data and battle-tested playbooks.

Think of it like hiring an expert who already knows Airaa inside out. You ask a question, they give you a direct answer. No Googling, no guesswork.

---

## Available Skills

| Skill | What it does | Trigger it with |
|-------|-------------|-----------------|
| [airaa-campaign-planner](./airaa-campaign-planner/) | Builds a complete UGC or clipping campaign brief, recommends strategy + CPM, then walks you through launching on Airaa | "I want to run a creator campaign", "help me build a brief", "I want to go viral", or share your website URL |

> More skills coming soon — Aura Board strategy, creator sourcing, campaign analytics, Guild onboarding.

---

## Install

### Option 1 — One command (recommended)

Requires Node.js. If you don't have it, [download it here](https://nodejs.org) — takes 2 minutes.

```bash
npx skills add airaa-xyz/Airaa-Skills
```

That's it. The skill is now available in Claude Code, Cursor, and any other AI tool you have installed.

### Option 2 — Manual (Claude Code)

1. Download or clone this repo
2. Copy the skill folder into your Claude skills directory:

```bash
# macOS / Linux
cp -r airaa-campaign-planner ~/.claude/skills/

# Windows
xcopy airaa-campaign-planner %USERPROFILE%\.claude\skills\ /E /I
```

3. Restart your AI tool.

---

## How to use a skill once installed

Just talk to Claude naturally. The skill activates automatically when you say something relevant.

**Examples that trigger `airaa-campaign-planner`:**

- *"I want to run a creator campaign for my fitness app"*
- *"Help me build a UGC brief — here's our website: [url]"*
- *"How do I set up a clipping campaign?"*
- *"I want creators to go viral for my brand"*

Claude will guide you through a structured 8-phase process — brand research, strategy options, campaign Q&A, budget recommendation, full brief generation, and Airaa launch walkthrough.

---

## What Airaa is

[Airaa](https://airaa.xyz) is the operating system for creator programs.

Brands use Airaa to run UGC campaigns, clipping campaigns, Instant Tasks, and KOL programs — with 48-hour USDC payouts, AI-powered quality verification, and a persistent creator community that compounds across campaigns.

- 50,000+ verified creators on the platform
- TikTok, Instagram Reels, YouTube Shorts, X
- Pay per verified view — you only pay for content you approve
- [Read the docs](https://docs.airaa.xyz) · [Sign up](https://app.airaa.xyz)

---

## Contributing

Have a skill idea for Airaa? Open an issue or PR. Skills we're building next:

- `airaa-aura-board` — KOL strategy and Aura Board setup
- `airaa-creator-brief` — Creator-side onboarding and campaign instructions
- `airaa-analytics` — Reading and acting on campaign analytics
- `airaa-guild-setup` — Guild onboarding for brands running multiple campaigns

---

## Works with

This skill repo follows the [open Agent Skills standard](https://agentskills.io) and works with any compatible AI tool:

Claude Code · Cursor · GitHub Copilot · Cline · Windsurf · OpenAI Codex CLI · Gemini CLI · and more

---

<p align="center">
  Built by the <a href="https://airaa.xyz">Airaa</a> team · <a href="https://docs.airaa.xyz">Docs</a> · <a href="https://app.airaa.xyz">Launch a campaign</a>
</p>
