# 🚀 Setup Guide — Put Your Minecraft Profile on GitHub

## 1. Edit placeholders (5 minutes)

Open `README.md` and replace everything marked with ✏️:

| What | Where |
|------|-------|
| Your name / bio details | `## 🏝️ About Me` section |
| City, job, learning, skills | `## 🏝️ About Me` bullets |
| Email address | `## 📮 Contact` Gmail badge |
| LinkedIn / Twitter handle | `## 📮 Contact` badges |
| Website URL | `## 📮 Contact` Portfolio badge |
| Medium username | `## 📰` section (optional) |
| Project repo names | `## 📦` commented block (once you have repos) |

## 2. Create the profile repo (must match your username!)

```bash
gh repo create sai-pa416 --public --description "My Minecraft-themed GitHub profile"
```

## 3. Push the README

```bash
git init
git add README.md
git commit -m "⛏️ Add Minecraft profile README"
git branch -M main
git remote add origin https://github.com/sai-pa416/sai-pa416.git
git push -u origin main
```

## 4. Done! 🎉

Open https://github.com/sai-pa416 — your profile README appears at the top.

## Notes

- **Stats look empty at first** — normal! They fill in as you commit/star repos. Give GitHub a few hours.
- The stats service (`github-readme-stats`) was briefly down during testing — it's the standard service and recovers automatically.
- **Pinned projects**: once you have repos, uncomment the `## 📦` block and swap `REPO_NAME` for each repo.
- Want different colors? The palette is already Minecraft-themed:
  - Grass green `5fbf3e` · Gold `ffd83b` · Stone gray `7f7f7f` · Deep cave `0b0b0b`
- The fun GIF is hosted by Giphy — if it ever breaks, drop any GIF URL you like into that line.