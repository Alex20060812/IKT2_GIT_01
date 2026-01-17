Semmi mást nem kell vele csinálnod.

# Webfejlesztési alaptechnológiák

## Felhasznált technológiák
- GIT
- HTML
- CSS3
- JavaScript

---

## GIT
A GIT egy verziókezelő rendszer, amely lehetővé teszi a forráskód változásainak nyomon követését.  
Segít több fejlesztő egyidejű munkájának összehangolásában, valamint a hibák visszakövetésében.  
Fontos alapfogalmai: repository, commit, branch, merge.

| Technológia | Értékelés |
|-------------|-----------|
| GIT         | ⭐⭐⭐⭐☆     |

```bash
git init
git add .
git commit -m "Első commit"

HTML

A HTML egy leíró nyelv, amelyet a böngészők értelmeznek, és amely meghatározza egy weboldal szerkezetét és tartalmát.
Az oldal elemei úgynevezett tagekből állnak (<tagnev></tagnev>).
A HTML adja a weboldal alapját.

Technológia	Értékelés
HTML	⭐⭐⭐⭐⭐
<!DOCTYPE html>
<html>
  <head>
    <title>Példa oldal</title>
  </head>
  <body>
    <h1>Hello világ!</h1>
    <p>Ez egy egyszerű HTML példa.</p>
  </body>
</html>

CSS

A CSS (Cascading Style Sheets) a weboldalak megjelenéséért felelős stílusleíró nyelv.
Segítségével állíthatók be a színek, betűtípusok, méretek és az elrendezés.
A HTML elemek kinézetét szabályozza.

Technológia	Értékelés
CSS	⭐⭐⭐⭐☆
body {
  background-color: #f0f0f0;
}

h1 {
  color: blue;
  text-align: center;
}

JavaScript

A JavaScript egy programozási nyelv, amely dinamikussá és interaktívvá teszi a weboldalakat.
Eseményeket kezel, logikát valósít meg és módosítja a HTML tartalmát futás közben.
Közvetlenül a böngészőben fut.

Technológia	Értékelés
JavaScript	⭐⭐⭐⭐⭐
document.getElementById("gomb").addEventListener("click", function () {
  alert("Szia! Ez egy JavaScript esemény.");
});
