# AI Boost Center Starter Kit — manual install (no plugin needed)

Use this if the `/plugin install` method does not work on your machine (some work computers block it). This way copies the skills straight into Claude Code by hand. No internet, no install command, no admin rights.

You have two folders here: **skills** and **commands**. You will copy them into Claude Code's settings folder, called `.claude`.

---

## Option A — for ALL your projects (recommended)

This makes the kit available everywhere you use Claude Code.

**On Mac:**
1. Open Finder.
2. In the menu bar, click **Go** then **Go to Folder** (or press Shift + Cmd + G).
3. Type `~/.claude` and press Enter.
4. Copy the **skills** folder and the **commands** folder from this kit into that `.claude` folder.
   - If `.claude` already has a `skills` or `commands` folder, just drag these folders' contents in to merge. Say "Keep Both" or "Merge" if asked.

**On Windows:**
1. Open File Explorer.
2. In the address bar at the top, type `%USERPROFILE%\.claude` and press Enter.
3. Copy the **skills** and **commands** folders from this kit into that `.claude` folder.
   - Merge if it asks.

---

## Option B — for ONE project only

If you only want the kit inside a single folder you work in:

1. Go to your project folder.
2. If it does not already have a folder called `.claude`, create one.
3. Copy the **skills** and **commands** folders into that `.claude` folder.

---

## Final step — restart Claude Code

Close Claude Code fully and open it again so it picks up the new skills.

---

## Check it worked

In Claude Code, type `/` and you should see these in the list:

- `/welcome`
- `/setup-kit`
- `/prompt-master`
- `/humanizer`
- `/researcher`
- `/caveman`
- `/find-skills`
- `/frontend-slides`

Type `/welcome` to begin.

---

## One tool installs separately: superpowers

`superpowers` is the only piece not in this folder, because it is a plugin, not a skill. If your machine allows it, run:

```
/plugin marketplace add anthropics/claude-plugins-official
/plugin install superpowers
```

If that is blocked too, no problem. The eight items above still work on their own.

---

Need help? fawwaz@aiboostcenter.com
