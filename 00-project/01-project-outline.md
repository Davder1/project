---
name: Pernecker Dávid
neptun: YSFKEJ
id: 2026-NP-03
github: https://github.com/Davder1/project
github_project: https://github.com/Davder1/project
---

# Valós idejű procedurális terepgenerálás és a részletességi szintek kezelése

A projekt célja egy olyan terepdemonstrátor elkészítése Godot játékmotorral, amely nagy kiterjedésű terepet képes procedurálisan létrehozni és valós időben megjeleníteni. A terep kisebb blokkokra lesz felosztva, amelyek betöltése és eltávolítása a kamera helyzetéhez igazodik. A rendszer saját részletességkezelést (LOD) valósít meg. A projekt során legalább két eltérő terepgeneráló algoritmust hasonlítok össze a generálási teljesítményük, memóriaigényük és az általuk létrehozott terep vizuális minősége alapján.

## Célok

- **Elsődleges cél:** Működő, valós időben frissülő procedurális terepdemonstrátor elkészítése saját blokkkezeléssel és LOD-rendszerrel.
- **Célfelhasználók / érintettek:** Elsődlegesen a projekt fejlesztője és témavezetője. A program a terepgenerálási módszerek teljesítményének és vizuális minőségének vizsgálatát szolgálja.
- **Mérhető sikerkritériumok:** A rendszer képes terepblokkok generálására, a kamera mozgásához igazodó betöltésére és eltávolítására, valamint a részletességi szintek saját szabályok alapján történő kiválasztására. Legalább két eltérő terepgeneráló algoritmus összehasonlítható reprodukálható mérésekkel. A mérések kiterjednek a generálási időre, a CPU- és képkockaköltségre, a memóriahasználatra, a generált geometria méretére és a blokkok betöltési késleltetésére. A különböző részletességű szomszédos blokkok közötti átmeneteket és az esetleges látható réseket szintén vizsgálni és dokumentálni kell
- **Korlátok:** A projekt Godot játékmotort és kezdetben GDScript nyelvet használ. A terepgenerálás, a blokkkezelés és a LOD-kiválasztás központi logikája saját megvalósítás lesz. A motor elsősorban a megjelenítést és az általános infrastruktúrát biztosítja. Teljes játék vagy nyílt világú játékmenet elkészítése nem cél.

## Hatókör

### Benne van a hatókörben

- Procedurálisan generált terep előállítása.
- A terep blokkokra bontása és a blokkok dinamikus kezelése.
- A terepblokkok betöltése, frissítése és eltávolítása a kamera helyzetéhez igazodva.
- Saját LOD-kiválasztási mechanizmus megvalósítása.
- Legalább két eltérő terepgeneráló algoritmus összehasonlítása.
- A különböző részletességű szomszédos blokkok közötti folytonosság vizsgálata, beleértve a látható rések és hirtelen átmenetek kezelését.
- Fokozatos vagy aszinkron generálás és blokkbetöltés megvalósítása.
- A generálási idő, a CPU- és képkockaköltség, a memóriahasználat, a geometria mérete és a blokkbetöltési késleltetés mérése.
- A forráskód és a mérési eredmények dokumentációja, verziókezelése GitHubon.

### Nincs benne a hatókörben

- Teljes, önállóan játszható játék elkészítése.
- Nyílt világú játékhoz szükséges rendszerek megvalósítása.
- A játékmotor beépített terepgeneráló vagy automatikus LOD-rendszerének használata.

## Jegyzetek

A fejlesztés egy egyszerű, procedurálisan generált terepblokkal és mozgatható kamerával kezdődik. Ezt követi a terepblokkok dinamikus kezelése, majd a saját LOD-rendszer kialakítása. Ezután két eltérő terepgeneráló algoritmus megvalósítása és összehasonlítása következik.

Pontosítani kell a kiválasztott algoritmusokat, a LOD-kiválasztás szabályait, az aszinkron feldolgozás megoldását és a mérési eljárásokat.

A méréseket dokumentált beállításokkal, reprodukálható módon kell elvégezni. A fejlesztés során külön figyelmet kell fordítani a különböző részletességű szomszédos blokkok közötti folytonosságra, valamint az esetleges látható rések és hirtelen átmenetek kezelésére.


