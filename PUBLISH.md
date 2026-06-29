# How to publish this plugin (one time)

Do this once. After that, anyone can install your kit with two lines.

## Step 1 — Create a free GitHub account (skip if you have one)

Go to https://github.com/signup and create an account. Remember your username.

## Step 2 — Create an empty repository

1. Go to https://github.com/new
2. Repository name: `aiboost-claude-kit`
3. Set it to **Public**.
4. Do NOT tick "Add a README" (this folder already has one).
5. Click **Create repository**.

## Step 3 — Push this folder to that repo

You need Git installed. Check by running `git --version` in your terminal. If it's missing, install it from https://git-scm.com/downloads.

Then run these commands from inside this folder. Replace `YOUR-GITHUB-USERNAME` with your real username:

```
cd "aiboost-claude-kit"
git init
git add .
git commit -m "AI Boost Center Claude Code starter kit v1.0.0"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/aiboost-claude-kit.git
git push -u origin main
```

GitHub will ask you to log in the first time. Follow the prompt.

## Step 4 — Update the install line

Open `README.md` and replace `YOUR-GITHUB-USERNAME` with your real username in the install command. Commit and push again:

```
git add README.md
git commit -m "Set install username"
git push
```

## Step 5 — Test it

In Claude Code, run:

```
/plugin marketplace add YOUR-GITHUB-USERNAME/aiboost-claude-kit
/plugin install aiboost-starter
```

Then `/welcome` should run. If it does, you're live. Share the two install lines with anyone.

---

## To update the plugin later

Make your changes, bump the version in `plugins/aiboost-starter/.claude-plugin/plugin.json`, then:

```
git add .
git commit -m "Update to vX.Y.Z"
git push
```

Users get the update by running `/plugin marketplace update aiboost-claude-kit`.
