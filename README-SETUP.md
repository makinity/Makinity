# GitHub Profile README — Setup Guide

> Complete instructions for every dynamic feature in this profile README.

---

## 🚀 Quick Start

1. Create a new repository named `makinity` (same as your GitHub username) — this makes it your **profile README** repo
2. Clone it locally
3. Copy all files from this project into the repo
4. Push to `main`
5. Your profile page will update automatically

### File Structure

```
makinity/
├── README.md                    # Your profile README
├── assets/
│   ├── banner.svg              # Hero banner
│   ├── footer.svg              # Footer banner
│   ├── icons/                  # Custom icons (add as needed)
│   └── screenshots/            # Project screenshots (add as needed)
└── .github/
    └── workflows/
        └── snake.yml           # Snake contribution animation
```

---

## 🐍 Snake Animation

**What it does:** An animated snake eats through your contribution graph.

**Setup:**
1. The workflow is at `.github/workflows/snake.yml`
2. It runs every 12 hours and on push to `main`
3. It generates `assets/github-snake.svg`
4. The README references this SVG

**First run:**
- Push the workflow to `main`
- Go to **Actions** tab → **Generate Snake Animation** → **Run workflow**
- Wait 1-2 minutes for it to complete
- The SVG will appear in `assets/`

**If the snake doesn't appear:**
- Ensure the repo name matches your GitHub username exactly
- Check the Actions tab for errors
- The workflow needs `actions: write` permission (usually automatic)

---

## 📊 GitHub Stats Cards

**What they show:** Your GitHub statistics in beautiful cards.

**Cards included:**
1. **GitHub Stats** — Total commits, PRs, issues, stars
2. **Top Languages** — Most used programming languages
3. **GitHub Streak** — Contribution streak
4. **Activity Graph** — 1-year contribution graph

**No setup needed** — these are dynamic and auto-update.

**Customization options:**
- Change theme: `theme=radical` → `theme=chartreuse-dark`, `theme=tokyonight`
- Hide stats: `&hide=stars,issues,prs`
- Show private repos: `&count_private=true`

---

## 🏆 GitHub Trophies

**What they show:** Achievement trophies based on your GitHub activity.

**No setup needed** — auto-generates from your profile.

**Customization:**
- Change theme: `&theme=radical` → `&theme=onedark`
- Adjust columns: `&column=7`
- Show/hide specific trophies: `&row=1`

---

## 👁️ Profile Views Counter

**What it shows:** How many people have viewed your profile.

**No setup needed** — uses `komarev.com` counter.

**Customization:**
- Change label: `&label=Views`
- Change color: `&color=1683DF`

---

## ⌨️ Typing Animation

**What it does:** Cycles through your roles/titles in an animated typing effect.

**No setup needed** — uses `readme-typing-svg.demolab.com`.

**Customization:**
- Edit the lines in the `&lines=` parameter
- Change font: `&font=Inter`
- Change speed: `&duration=3000`
- Change color: `&color=1683DF`

---

## 🖼️ Custom Banner

**What it does:** Displays a hero banner at the top of your profile.

**Setup:**
1. The banner is at `assets/banner.svg`
2. It's referenced in the README as `<img src="assets/banner.svg" />`
3. Edit the SVG to customize colors, text, or layout

**Color palette used:**
- Dark Navy: `#111f42`
- Primary Blue: `#1683DF`
- Light Blue: `#93CCE9`
- Cyan: `#00d4ff`

---

## 🔧 Customization Checklist

After pushing, verify these work:

- [ ] Banner loads at top of profile
- [ ] Typing animation cycles through roles
- [ ] Profile views counter increments
- [ ] GitHub stats cards render correctly
- [ ] Language stats show your top languages
- [ ] Streak stats display your activity
- [ ] Activity graph renders
- [ ] Trophies appear
- [ ] Snake animation generates after first Actions run
- [ ] All project links work
- [ ] Social links are correct
- [ ] Footer SVG loads

---

## 🎨 Adding Project Screenshots

1. Take a screenshot of your project
2. Save it to `assets/screenshots/`
3. Reference it in the README:
```html
<img src="assets/screenshots/boardease-dashboard.png" alt="BoardEase Dashboard" width="100%" />
```

---

## 📱 Adding More Badges

Use [shields.io](https://shields.io) to create custom badges:

```
https://img.shields.io/badge/LABEL-MESSAGE-COLOR?style=for-the-badge&logo=LOGO&logoColor=white
```

**Examples:**
- `https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white`
- `https://img.shields.io/badge/Freelance-Available-22C55E?style=for-the-badge`

---

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Snake not appearing | Run the workflow manually from Actions tab |
| Stats cards not loading | Check username: `makinity` must match exactly |
| Banner broken | Ensure `assets/banner.svg` is in the repo root |
| Profile views stuck | Counter may cache; wait 24 hours |
| Typing not animating | Some clients strip animations; it degrades gracefully |
| Theme doesn't match dark mode | Change `theme=` parameter in stats URLs |

---

## 🔄 Updating the README

1. Edit `README.md` locally
2. Commit and push to `main`
3. Changes appear on your profile within seconds

**Pro tip:** Preview locally with a Markdown viewer before pushing.

---

## 📋 Services Offered (for reference)

| Service | Description | Rate |
|---------|-------------|------|
| **SMM + VA** | Social Media Management & Virtual Assistance | $5-7/hr |
| **Web Development** | Custom websites & web apps | ₱5,000+ |
| **AI Integration** | Chatbots, automation, ML | Custom |

---

*Last updated: 2026-07-31*
