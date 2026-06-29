---
description: Install the one remaining tool (superpowers) that ships separately from this plugin. Everything else is already bundled.
---

Good news first: most of the kit is already installed. This plugin bundles six skills — prompt-master, humanizer, researcher, caveman, find-skills, and frontend-slides. They work right now, no setup needed.

There is only one more tool to add: **superpowers**. It is a plugin, not a skill, so it installs from its own marketplace.

Be warm and plain. Short sentences. No jargon.

**superpowers (plugin)** — Makes Claude think, plan, build, then check its own work. Fewer mistakes on big jobs.

Tell the user you will add the official marketplace and install it. Run:
- `/plugin marketplace add anthropics/claude-plugins-official`
- `/plugin install superpowers`

Note: `/plugin` opens an interactive menu in Claude Code. In the desktop app, tell them to type `/plugin`, choose to add the marketplace `anthropics/claude-plugins-official`, then install `superpowers` from the list. If a permission box pops up, click Allow.

After it installs, confirm it landed, then summarise the full kit they now have:

- **prompt-master** — rough idea to a clean, ready-to-paste prompt (`/prompt-master`)
- **humanizer** — strips AI tells out of any text
- **researcher** — deep, multi-source research with real sources
- **caveman** — same answer, far fewer words (`/caveman`)
- **find-skills** — finds and installs more skills, just describe what you want
- **frontend-slides** — builds slide decks, dashboards, and small web pages
- **superpowers** — plan-build-check for bigger jobs

Tell them to start with one real task. If any step fails, stop and help them fix it. Do not claim something installed unless you have seen it confirmed.
