# Rune Midgard — SoulBound Journey Guild Website

A dark fantasy guild headquarters for **Rune Midgard**, a Ragnarok Online guild on SoulBound Journey.

## Version 1

The website is a single static `index.html` file and requires no build step.

Features:
- Cinematic, mobile-friendly homepage
- Editable guild level, guild EXP and roster capacity
- Member/character roster with search
- Location-based party planner for **Magma2**, **Stalactic Golem**, and **Endless Tower**, with customizable role capacities and character signups
- Guild events board
- Optional official Discord server widget and invite link
- Browser-local storage for prototype data

## View locally

Open `index.html` in a browser, or serve the folder from any simple static web server.

## Publish

For GitHub Pages, go to **Settings → Pages** and choose **Deploy from a branch**, branch `main`, folder `/ (root)`. GitHub Pages should then serve the website at:

https://dennisvanfaassen.github.io/Runemidgard/

This URL is only active after Pages is enabled and deployed.

## Configure Discord

Select **Site settings** at the bottom of the website:
1. Enter the numeric Discord server ID.
2. Enter a Discord invite URL (`https://discord.gg/...`).
3. In your Discord server settings, enable its public **Server Widget**.

The official Discord widget shows server membership/presence and voice channels, not a full embedded text chat.

## Important limitations

- All settings, members, parties, party role claims and events are currently stored **only in the current browser** with localStorage. Edits are not shared across visitors or devices. Other guild members cannot see signups made on another device yet.
- No SoulBound Journey server API or guild synchronization has been confirmed.
- Guild EXP and guild level are manually entered.
- No authentication or admin permission system exists yet. Do not treat this demo interface as an authenticated admin dashboard.
- The hero uses a remote Unsplash fantasy image. Replace with licensed/owned Ragnarok artwork when available.

## Next phase

Introduce Supabase authentication, persistent database-backed guild members/parties/events, role-based permissions, Discord OAuth and a verified read-only guild-data feed if the server owners provide one.

Fan-made site; not affiliated with Gravity Co., Ltd.