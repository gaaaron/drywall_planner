# Gipszkarton Fal Tervező

Fémvázas gipszkarton válaszfal tervező eszköz — elsősorban lépcsőház-lezárásokhoz: ferde (lépcsőkar fölötti) felső és alsó él, sarokban csatlakozó falszakaszok, ajtónyílás (dupla CW vagy UA tokoszlop), réteges rajz (profilok / gipszkarton / szigetelés), vágási lista, anyagszükséglet és bevásárlólista.

Önálló, build-lépés nélküli statikus HTML/CSS/JS eszköz — nincs szükség szerverre vagy telepítésre, egyetlen fájl (`index.html`) futtatja az egészet a böngészőben.

## Használat

Nyisd meg az [`index.html`](index.html) fájlt bármelyik modern böngészőben, vagy a GitHub Pages verziót:

**Élő verzió:** https://gaaaron.github.io/drywall-planner/

A beállítások automatikusan mentésre kerülnek a böngésző `localStorage`-jába.

## Fejlesztés

A teljes alkalmazás az [`app.html`](app.html) fájlban van (inline CSS + JS). Az `index.html` ugyanennek egy `<!doctype>`/`<html>`/`<body>` csomagolással ellátott, önállóan futtatható változata.
