THEY CAME - web version
=======================

This folder is the whole game. Put it on any website that serves static files and share the link.
Players need nothing but the link: no Claude account, no sign-up, no install. Works on desktop and phone browsers.

Co-op (Co-op on the main menu)
- Quick play: everyone who presses it lands in one shared fight (up to 4). If the player running the
  aliens leaves, someone else takes over and the run keeps going.
- Host a game: gives a 4-letter code for friends to type in.
- Open city: drop-in sandbox with endless aliens; everyone in the city shows on the map as a white dot and
  appears as their hero when close.

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
