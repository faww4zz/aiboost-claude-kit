---
description: Install the AI Boost Center recommended skills and plugins for new Claude Code users, one at a time, checking each step.
---

The user wants to install the recommended starter kit from their AI Boost Center training. Walk them through it one step at a time. Explain each tool in one plain sentence before installing. Confirm each install worked before moving to the next. Do not rush ahead.

Be warm and plain. Short sentences. No jargon.

Install these in order. For each one: say what it does, run or show the step, then check it landed.

**1. superpowers (plugin)** — Makes Claude think, plan, build, then check its own work. Fewer mistakes on big jobs.

Tell the user you will add the official marketplace and install it. Run:
- `/plugin marketplace add anthropics/claude-plugins-official`
- `/plugin install superpowers`

Note: `/plugin` opens an interactive menu in Claude Code. If the user is in the desktop app, tell them to type `/plugin`, choose to add the marketplace `anthropics/claude-plugins-official`, then install `superpowers` from the list.

**2. humanizer (skill)** — Strips the AI tells out of any text so it reads like a person wrote it.

The easy way: tell the user to type "find and install a humanizer skill" and let the find-skills flow handle it. Or browse https://skills.sh and install from there.

**3. researcher (skill)** — Deep, multi-source research with real sources. Useful before any decision or report.

Same as above: "find and install a researcher skill", or browse https://skills.sh.

**4. caveman (skill)** — Same answer, far fewer words. Fun, and saves tokens.

This one installs from the command line. Show the user this command to run in their terminal:
`npx skills add juliusbrussee/caveman@caveman`

**5. find-skills (skill)** — Finds and installs other skills for you, just by describing what you want.

Tell the user: "find me a skill for X" works once this is in. Install via https://skills.sh or by asking Claude to find and install a find-skills skill.

---

After all five, summarise what is now installed and what each one does in one line. Then remind them: `prompt-master` is already built into this starter kit, so they can run `/prompt-master` right away. Tell them where to browse more: https://skills.sh, claudemarketplaces.com, tonsofskills.com.

If any step fails, stop and help them fix it before continuing. Do not claim something installed unless you have seen it confirmed.
