# Warren's Sci-Fi & Pop Culture Archive
A Life is Strange fan site inspired by Warren Graham - a small interactive archive of movies, music, and pop culture references.

<!-- Screenshot coming soon -->

## Try it
Live demo: coming soon, it will be on GitHub Pages.

## Quick Start
There is no setup, no installs and no build step needed. Just open the file.

1. Clone the repo: 
git clone https://github.com/PXLS-png/stardance-archive.git

2. Open 'index.html' in a browser.

That's it.

## Features
- **Movie of the Day** a new film every day, picked by date. It changes at midnight Pacific time, because the game takes place in Oregon. The list merges various different genres - sci-fi classics, cult picks, foreign films, weird 80s oddities, and everything in between. 

- **Special date overrides** on a few specific dates which are meaningful to the Life is Strange storyline, the system operates with fixed movies. Contrary to the regular randomized rotation, these fixed movies are closely tied to distinctive in-game moments.

- **Top 5 movie picks** five films referenced in the Life is Strange universe, each shown with a quote from the game and a link to IMDb.

- **A song on repeat** "She Blinded Me With Science" by Thomas Dolby.

- **Dual clocks** two time zones side by side, one is the user's local time, one Warren's. A small nod to the time travel theme.

- **Easter eggs** many hidden things to find. Click around, look at the source, and find out what happens.

## How It Works

- **HTML, CSS, and JavaScript only.** 

- **Movie of the Day** uses `Intl.DateTimeFormat` with the `America/Los_Angeles` timezone to get today's date in Oregon, then picks a film from a fixed list based on that date. Everyone sees the same movie on the same day. 

- **Special date overrides** work the same way, certain month-day pairs point to specific movies instead of the normal rotation.

- **Frutiger Aero styling** glassy panels made with `backdrop-filter: blur()` and `::before` pseudo-element reflections.

- **Mobile responsive** a media query at 600px shrinks the layout for phones and iPads 

- **A few hidden things** some might be animations, secret codes, messages etc. Keeping an eye out for secrets is strongly encouraged.

## Credits
- **Life is Strange** and all characters belong to Dontnod Entertainment and Square Enix. This is an unofficial fan project, not affiliated with or endorsed by them.

- **Frutiger Aero aesthetic** inspired by the early-2000s design movement.

- Made for **Hack Club Stardance**

## Note
Fan project. Not official. Non-commercial. All rights belong to the owners.






