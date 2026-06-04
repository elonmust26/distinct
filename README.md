<div align="center">

# distinct

**A skill that fights AI homogenization.**

Stop your AI assistant from handing you the same generic name, the same
dark-gradient design, and the same concept it hands everyone else. `distinct`
forces it to check what already exists and steer toward something original.

![type](https://img.shields.io/badge/type-Agent_Skill-9db888)
![license](https://img.shields.io/badge/license-MIT-blue.svg)

</div>

---

## The problem

Ask an AI to "name my finance app" or "design a clean landing page," and you'll
often get the same answers everyone else gets — because the model converges on its
statistical defaults. The symptoms are everywhere:

- **Names:** `calm`+X, X+`OS`, X+`AI`, `smart`+X, two stacked dictionary words.
- **Design:** dark background, neon/gradient glow, sage-or-indigo accent, the same
  hero-with-three-cards layout, a leaf or blob logo.
- **Concepts:** the obvious take on the obvious idea.

The result: people independently launch products that look and sound nearly
identical, sometimes days apart. This isn't a leak — it's **homogenization**, a known
weakness of AI output. And it's a real cost: a generic name collides with existing
products and is instantly forgettable.

## What `distinct` does

It's an Agent Skill. Once installed, whenever you're naming, designing, or conceiving
something, it forces your assistant to:

1. **Check what already exists first** — search the name, its domain variants, the
   category, and the top competitors. Report it before suggesting anything.
2. **Reject generic names** — flag the overused patterns and generate distinctive
   candidates from unexpected angles instead (5+, each with its rationale).
3. **Break out of default design** — offer 2–3 genuinely different visual directions
   tied to the product's character, not one default with swapped colors.
4. **State the difference** — one line on what makes the result unlike the field.

## Install

This is an Agent Skill (`SKILL.md` format), compatible with Claude and other
assistants that support skills.

- **Claude (skills-enabled):** add the `distinct` folder / `.skill` file to your
  skills.
- Or just drop `SKILL.md` into your project's skills directory.

Once installed, it triggers automatically when you start naming or designing
something — no need to invoke it by hand.

## Honest scope

`distinct` **reduces** lookalike results. It does **not guarantee** uniqueness — the
same real-world need can lead different people to similar ideas independently, and no
tool controls that. What it controls is the controllable part: **not defaulting to
the obvious**, checking the landscape, and choosing distinctive names and designs on
purpose.

## License

[MIT](./LICENSE) — use it, change it, ship it.

<div align="center">
<sub>Built by <a href="https://x.com/ElonCmedia">@ElonCmedia</a>.</sub>
</div>
