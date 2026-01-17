# IKT2_GIT_01

Ez a repository egy tanulmányi célú GIT gyakorlat megvalósítását tartalmazza.
A feladat célja egy egyszerű, reszponzív HTML + CSS alapú statikus weboldal elkészítése külső könyvtárak használata nélkül, miközben a fejlesztés több ágon (branch) történik, sűrű commit-okkal. A külön ágakon elkészült munkák Pull Request segítségével kerülnek beolvasztásra a main ágba.

A projekt során a parancssori GIT használata, a GitHub Pull Request folyamata, valamint az alap webfejlesztési technológiák (HTML, CSS, JavaScript) kerülnek alkalmazásra.

Felhasznált technológiák
GIT
HTML
CSS3
JavaScript
GIT:
Egy verziókezelő rendszer, amely lehetővé teszi a forráskód változásainak nyomon követését. Segítségével több fejlesztő dolgozhat ugyanazon a projekten, külön ágakon, majd a változások biztonságosan összevonhatók. A GIT támogatja a commit, branch és merge műveleteket, amelyek alapvetőek a modern szoftverfejlesztésben.

git status
git add .
git commit -m "Initial commit"
HTML: Egy leíró jellegű jelölőnyelv, amelyet a böngészők értelmeznek és megjelenítenek. A HTML határozza meg egy weboldal szerkezetét, tartalmát és szemantikus elemeit. Az oldal elemei úgynevezett tagek segítségével épülnek fel.

<!DOCTYPE html>
<html lang="hu">
  <head>
    <title>Példa oldal</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
CSS3: A CSS a weboldalak megjelenéséért felelős stílusnyelv. Segítségével beállítható a színek, méretek, elrendezések és animációk kinézete. A CSS3 támogatja a reszponzív megjelenést, például flexbox és media query használatával.

header {
  height: 100px;
  background-color: #3939c8;
  color: white;
}
JavaScript: Egy programozási nyelv, amely dinamikus működést biztosít a weboldalak számára. Segítségével eseményeket kezelhetünk, adatokat módosíthatunk és interaktív funkciókat valósíthatunk meg. A böngészők natívan támogatják.

const year = new Date().getFullYear();
console.log(year);
GIT	HTML	CSS	JS
	⭐⭐⭐⭐	⭐⭐	⭐⭐⭐
