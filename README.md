# Cavern Keeper: Sovereign Imp

A cosy first-person digging game. You're an imp who has just won your
freedom, with nothing but bare hands and a sharp bit of rock. Dig tunnels,
haul treasure home, catch bugs for pep, shore up your ceilings, and slowly
turn the caverns into a home.

This is the phone (web browser) version of a game made for the M5Stack
Cardputer ADV. It's the same game code, compiled to run in a browser.

**Play:** open the GitHub Pages link for this repository on your phone and
turn it sideways.

## Putting it on GitHub Pages

1. Create a new repository on GitHub (for example `cavern-keeper`). It can
   be public or private, but Pages on a private repository needs a paid plan.
2. Upload every file in this folder to the top level of the repository:
   `index.html`, `game.wasm`, `sw.js`, `manifest.webmanifest`,
   `icon-192.png`, `icon-512.png`, `OFL.txt` and this `README.md`.
   (On the repository page: **Add file → Upload files**, drag them all in,
   then **Commit changes**.)
3. Go to **Settings → Pages**. Under **Build and deployment**, set
   **Source** to **Deploy from a branch**, pick the **main** branch and the
   **/ (root)** folder, and press **Save**.
4. After a minute or two the page shows your link, which looks like
   `https://YOUR-USERNAME.github.io/cavern-keeper/`.

To update the game later, upload the new `game.wasm` (and `index.html` and
`sw.js` if they changed) over the old ones.

## On your phone

- **Add it to your home screen** for a full-screen app with its own icon:
  in Chrome on Android, open the menu and choose **Add to Home screen**
  (or **Install app**); in Safari on iPhone, tap **Share → Add to Home Screen**.
- **It works offline** after you've opened it once with a signal, so it
  will run on the bus with no connection. When you're online it picks up
  any new version automatically.
- **Saves** are kept in that browser on that phone. Clearing the browser's
  site data deletes them, and they don't move between devices.

## Controls

- **D-pad:** step forward and back, turn left and right (hold to keep
  walking); also moves through menus.
- **Dig / Use:** dig, open the chest, talk to the Light Crystal, confirm.
- **Back:** close a menu, or answer "no".
- **Pick up, Drop, Catch, Eat, Build, Reinforce, Teleport, Save:** as named.

A keyboard works too: arrow keys, Enter, Esc, and the same letters as the
Cardputer (E dig, B build, R reinforce, P pick up, D drop, C catch, F eat,
S save, T teleport). Don't rebind keys on the Controls screen in this
version, because the touch buttons send the default keys.

## Credits and licences

Cavern Keeper: Sovereign Imp © 2026 Tara Carter (sauvryn).

Fonts built into the game:

- **"Sovereign Imp" title lettering:** converted from *Eater* by Typomondo,
  used under the SIL Open Font License 1.1 (see `OFL.txt`). Inside the game
  it is renamed "Scrawl", as the licence asks for modified versions.
- **Menu and interface fonts:** the Adafruit GLCD 5×7 font (BSD licence)
  and the 16-pixel font from TFT_eSPI (FreeBSD licence), as included in
  M5GFX / LovyanGFX.
- **"Cavern Keeper" title lettering:** FreeSerif Bold from GNU FreeFont
  (GPL with the font exception, which allows embedding), via the Adafruit
  GFX library.
