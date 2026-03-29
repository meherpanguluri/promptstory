# promptstory

A curated library of high-leverage AI prompts — the ones that actually change how you work.

Live at: https://meherpanguluri.github.io/promptstory

## What this is

Not a list of "act as an expert" templates. Each prompt here is included because it inverts a common failure mode: asking AI to confirm what you already think, jumping to solutions before diagnosing problems, outsourcing thinking instead of sharpening it.

## Adding a prompt

Edit `prompts.json`. Each entry follows this shape:

```json
{
  "id": 7,
  "title": "Prompt title",
  "category": "One of the defined categories",
  "tags": ["tag1", "tag2"],
  "prompt": "The actual prompt text.",
  "why_it_works": "One sentence on the mechanism.",
  "usage_notes": "When and how to use it."
}
```

**Categories:** Project Kickoff · Debugging · Writing · Research · Code Review · Thinking

## Stack

Static HTML + Tailwind CSS (CDN) + vanilla JS. No build step. Hosted on GitHub Pages.
