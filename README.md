# Head of Content — Codex Skill

An open-source Codex skill that operates like a strategic **Head of Content**: brand positioning, original insights, hooks, packaging, storytelling, creative production, distribution, measurement and team operations.

**Not an auto-posting bot.** Publishing, messaging and spending remain under your control.

## Install for Codex

Run in your terminal:

```bash
git clone https://github.com/Pedroshakoor/head-of-content.git
mkdir -p ~/.codex/skills
cp -R head-of-content/skills/head-of-content ~/.codex/skills/
```

Restart Codex / open a new session, then invoke:

```text
$head-of-content Audit my existing X content and give me 10 original post ideas for SaaS founders. Explain the underlying insight and measurable objective of each.
```

### Project-local install

Place `skills/head-of-content/` inside `.agents/skills/head-of-content/` in a project that uses project-local Codex skills.

## What the skill does

| Capability | Result |
| --- | --- |
| Brand-market fit | ICP, voice, positioning, differentiated point of view |
| Content strategy | Pillars, original ideas, formats, content calendars |
| Packaging | Distinct hooks, thumbnails, titles, first frames, overlays |
| Production | X posts/threads, short video scripts, screenshot carousels |
| Distribution | Platform-native repurposing, audience capture, community |
| Analytics | Audits, conversion metrics, experiments, weekly reviews |
| Operations | SOPs, approval processes, ownership, team handoffs |
| Hiring | Role scorecards, paid trials and evaluation rubrics |

## Sample prompts

**30-day strategy:**
```text
$head-of-content Build a 30-day X content strategy for my product. Read the repo first to identify its actual value and differentiators. Focus on qualified customers, not vanity impressions.
```

**Carousel using only existing screenshots:**
```text
$head-of-content Turn these chart screenshots into a 3-slide educational carousel. Give the exact text overlay and screenshot choice for each slide. Don't invent performance claims.
```

**Measure:**
```text
$head-of-content Review these content analytics exports. Diagnose why our posts are or aren't attracting our target audience, and design three measurable experiments.
```

## Structure

```text
skills/
  head-of-content/
    SKILL.md
    agents/
      openai.yaml
    references/
      production.md
      measurement.md
      operations.md
LICENSE
README.md
```

## Principles

- Original insights and evidence before copywriting
- No fake urgency, fabricated testimonials, invented earnings or unsupported metrics
- Strong creative judgment and platform-native packaging
- Qualified reach and business results before vanity virality
- Practical production assets, not generic AI-generated marketing language

## License

[MIT](LICENSE) — free to use, modify and distribute.
