# guns.lol/.DaVe Clone

1:1 style clone of the [guns.lol/.DaVe](https://guns.lol/.DaVe) profile page.

## Features
- Dark neon purple theme matching guns.lol aesthetic
- Background video
- Profile avatar (SSG neon logo)
- Polish text: "Witaj w Nielegalnej Dzielnicy"
- Stats: UID, Premium, Views, Location
- **Edytowalna lista gier z miniaturkami** (patrz niżej)
- Discord widget for Szara Strefa Gospodarki
- Background music player (.DaVe - PoloWagen)

## Edytowanie listy gier

Otwórz `index.html` i znajdź na górze skryptu tablicę `const games = [ ... ]`.

Dodaj/usuń obiekty w formacie:
```js
{ name: "Nazwa gry", thumb: "https://link-do-miniaturki.jpg" }
```

Możesz używać zewnętrznych linków (np. z IGDB, Steam) albo wrzucić własne obrazki do folderu i podać lokalną ścieżkę np. `games/valorant.jpg`.

## How to host on GitHub Pages

1. Create a new public repository on GitHub (e.g. `dave-guns-clone`)
2. Upload all files from this folder:
   - `index.html`
   - `avatar.webp`
   - `background.mp4`
   - `music.mp3`
3. Go to Settings → Pages
4. Select branch `main` / root
5. Save — your site will be live at `https://yourusername.github.io/dave-guns-clone/`

## Notes
- Video is ~24MB, music ~5MB — acceptable for GitHub.
- Music starts after first click (browser autoplay policy).
- Discord link points to the original guns.lol Discord.

Made as a static clone for easy self-hosting.
