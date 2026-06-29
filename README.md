# Quartz-HispaniaBeta

**The player's guide to _Hispania Royal House_** — a public, web-based wiki that explains how the game works and how to play it, from your first reign to uniting Hispania in 1492.

🔗 **Live site:** https://kroryan.github.io/Quartz-HispaniaBeta/

---

## 📖 What this is

*Hispania Royal House* is a narrative dynasty-simulation game set in medieval Spain (722–1492). You rule a royal house decision by decision — balancing the Church, the People, the Army and the Treasury, securing heirs, waging war, and (if you're bold) reuniting all of Hispania under your crown.

This repository is the **player-facing guide** to that game: a large, illustrated, beginner-friendly wiki covering every major system — the four Powers, dynasty & succession, the royal court, war & diplomacy, faith & the Papacy, the economy, and the long road to victory. It's written **without technical jargon**, for players who just want to understand and master the game.

> ⚠️ **Beta disclaimer:** This guide describes the game **as of 29 June 2026**, while it is in **beta** and under active development. Numbers, rules, menus and screens may change in later versions. Treat everything here as "how it works right now."

## 🏗️ Built with Quartz

This site is generated with [Quartz v5](https://quartz.jzhao.xyz/) and styled with a custom medieval/heraldic theme (parchment, gold and royal red) to match the feel of the game. Content lives as Markdown in [`content/`](./content); diagrams use Mermaid; screenshots live in [`content/images/`](./content/images).

### Run locally

```bash
npm install
npx quartz build --serve
```

Then open the local address Quartz prints (usually `http://localhost:8080`).

### Deployment

Pushing to `main` triggers the GitHub Actions workflow in [`.github/workflows/deploy.yml`](./.github/workflows/deploy.yml), which builds the site and publishes it to **GitHub Pages** at the live URL above. (Enable Pages → "GitHub Actions" in the repository settings once.)

## 🗂️ Structure

```
content/
├── index.md            # Home / welcome
├── basics/             # How to play, the four Powers, decisions, time
├── dynasty/            # Heirs, succession, marriage, bastards, traits
├── court/              # Court, council, nobles, authority, intrigue
├── realm/              # Map, climbing the ladder, war, armies, diplomacy, economy
├── faith/              # Religion, the Papacy, doctrines & excommunication
├── world/              # Culture, legacy, relics, crises, geography
├── guide/              # Winning, achievements, strategy, difficulty, glossary, FAQ
└── images/             # In-game screenshots and the banner
```

## 📝 Credits

- Game: *Hispania Royal House* (in beta).
- Site engine: [Quartz](https://github.com/jackyzha0/quartz) by Jacky Zhao, MIT licensed (see [`LICENSE.txt`](./LICENSE.txt)).
- This guide is a fan-style player resource and contains no confidential or internal development material.
