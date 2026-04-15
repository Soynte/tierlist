# MyPvP • Leaderboards

A beautiful, fully functional, single-file Minecraft PvP tier list website for the **MyPvP** community.

Track the best players across Classic, UHC, Only Sword, and Pot with an aggregated **Overall** leaderboard, a **Retired** section, and a stunning **Hall of Fame**.

**Live Demo:** [https://soynte.github.io/tierlist](https://soynte.github.io/tierlist)

## ✨ Features

- **Overall Leaderboard** – Aggregates points from all gamemodes
- Individual leaderboards for:
  - Classic
  - UHC
  - Only Sword
  - Pot
- **Retired** section (multi-gamemode support)
  - Retired tiers appear in Overall as **(R) Low Tier 2** (display only — does **not** count toward points or ranking)
- **Hall of Fame** with:
  - 3D player skins (Visage)
  - Prime years
  - Description
  - Quote
  - Reordering
- Modern point system:
  - High Tier 1 = 100 Points  
  - Low Tier 1 = 90 Points  
  - ...  
  - Low Tier 5 = 10 Points
- Full manual control: **Add • Edit • Delete • Reorder** players
- Tierpoints legend (dropdown)
- Search bar
- Top 3 Podium display
- Smooth fade animations
- Fully responsive (great on mobile)
- Data saved automatically in browser (`localStorage`)
- Easy JSON export/import for backup or multi-device use

## 🎮 Gamemode Icons

- Classic: Trident (subtiers.net)
- UHC: UHC icon (mctiers.com)
- Only Sword: Sword icon (mctiers.com)
- Pot: Potion icon (mctiers.com)

## How to Use

1. Open the website
2. Click **ADD PLAYER** to add players to any list
3. Click a player’s name to view their detail widget
4. Use the **pen icon** to edit tiers
5. Use the **trash icon** to delete
6. In the **Overall** list, retired tiers automatically appear with `(R)`
7. Use the **Tierpoints** dropdown to see point values

**Data Tip:** Your data is saved in your browser. To move it to another device, use the Export/Import JSON feature (or manually copy the `mvp_leaderboards.json` file).

## Deployment & Editing

The entire site is just **one file**: `index.html`

- Host it for free on **GitHub Pages**
- To edit: open `index.html`, make changes, commit & push
- GitHub Pages will update automatically

## Technologies

- HTML5 + CSS3 + Vanilla JavaScript
- Tailwind CSS (via CDN)
- Font Awesome
- Minecraft heads: `mc-heads.net`
- 3D skins: `visage.surgeplay.com`

## Author

Created and maintained by **Soynte** for the MyPvP community.

---

Feel free to fork this project and create your own community tier list!
