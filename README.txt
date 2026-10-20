THEY CAME - web version
=======================

This folder is the whole game. Put it on any website that serves static files and share the link.
Players need nothing but the link: no Claude account, no sign-up, no install. Works on desktop and phone browsers.

Co-op (Co-op on the main menu) - built for strangers to team up, no hosting
- Open city, on foot: drop in anytime. Everyone in the city fights the same endless invasion; each player's
  game runs the aliens that spawn around it and shares them, so nobody has to host.
- Open city, convoy: roll a supply truck through the same city (up to 15 at once). Pull up next to a player
  on foot to restock them; run supplies to the crews marked on your map.
- Quick play: wave mode with whoever's on, through to the mothership.

How players connect: browsers find each other through free public relay servers, then talk directly to
each other. There is no game server to run. A few networks (some mobile carriers and strict work or school
Wi-Fi) block direct browser-to-browser links; players on those can still play solo.

Hosting it
- Upload the CONTENTS of this folder (index.html must be at the top level) to a static host, for example
  itch.io (HTML game, upload the zip), Netlify, GitHub Pages or Cloudflare Pages. You need a free account
  on the host; your players don't.
- It must be served over https and opened from the web. Double-clicking index.html on your computer
  won't load the game.

Leaderboard and achievements are saved in each player's own browser in this version.
