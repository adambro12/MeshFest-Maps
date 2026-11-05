# MeshFest Maps

Festival maps that the Armageddon MeshFest app can download (Festival map > Download a festival map).
This repo must stay **public** so phones can read it without logging in.

- `index.json` – the list of maps the app shows.
- `<folder>/map.png` – each map image (JPG or PNG, under 25 MB).

Each map's `spots` are alignment points: `x`/`y` are fractions of the image width/height
(0 = left/top, 1 = right/bottom) and `lat`/`lon` are the real position of that spot.
With 3 or more spots the map opens already lined up. With none, it is lined up on site
in the app (stand at a spot and press "I am standing here now").
