# Zenith HUB

Zenith HUB is a clean, modern landing page for a premium Roblox script hub offering one-time lifetime access to a collection of Lua scripts. The site highlights features, supported games, pricing information, and a Discord-based support/purchase flow.

> Note: This repository contains the static site (index.html, styles and scripts) for the landing page. It does not include backend purchase/payment processing — purchases are handled via Discord support as described on the site.

## Live / Source
- Page source: https://github.com/Hwrhero13gmailcom/Zenith/blob/297cae5098e0aedcad2fe7e1d85b200cb55bbf46/index.html

## Key Features
- Polished hero section with animated background and gradient text.
- Modal purchase dialog that directs users to Discord for support and purchases.
- Pricing block advertising a one-time "Lifetime Access" key (example price shown: $7.99 or 1,000 Robux).
- Tabbed content sections: All Scripts, About Us, FAQ, Supported Games.
- Responsive layout and animated UI elements for modern presentation.
- Minimal JavaScript for modal and tab interactions.
- OptiMonk onsite script included (loaded asynchronously in the page).

## Supported Games (shown on the site)
- Build A Stone Miner — automation and mining optimisation
- Gun Grounds FFA — aimbot, ESP, combat enhancements
- Murder VS Sheriff Duels — role detection, ESP, auto-play
- KillStreak Sword Fighting — auto-parry, reach extension
- Arise Crossover — character unlocks, auto-farm, quest automation

## Purchase & Support
The site instructs users to join the official Discord server to open a support ticket and purchase a lifetime key. The example Discord invite used in the site:
- https://discord.gg/b8WFc7ZNje

Price shown on the landing page: $7.99 (or 1,000 Robux). This is presented as promotional/launch pricing in the demo content.

## Running Locally
To preview the site locally:
1. Clone the repository:
   git clone https://github.com/Hwrhero13gmailcom/Zenith.git
2. Open `index.html` in a web browser, or serve it with a simple static server:
   - Python 3: `python -m http.server 8000` (then open http://localhost:8000)
   - Node (http-server): `npx http-server .`

No build step is required — the project is a static HTML/CSS/JS page.

## Contributing
- If you want to improve content, styles, or accessibility, feel free to submit issues or pull requests.
- Please keep changes focused and include screenshots for visual updates when appropriate.

## Security & Legal Disclaimer
- Zenith HUB is not affiliated with Roblox Corporation. This is stated in the site footer.
- The repository contains only the landing page and marketing copy for a script hub. The scripts themselves are not included here.
- Using or distributing third-party game scripts may violate the terms of service of the game platform (Roblox). Users should exercise caution and are responsible for complying with all applicable terms and laws.
- This project includes a third-party OptiMonk script loaded from their CDN. Review and understand any external scripts before deploying.

## License
This repository does not include an explicit license file. If you want others to reuse or contribute under a clear license, consider adding a LICENSE file such as MIT, Apache-2.0, or another license that fits your needs.

## Contact / Support
- Join the Discord listed on the site for support, purchases, and announcements: https://discord.gg/b8WFc7ZNje
