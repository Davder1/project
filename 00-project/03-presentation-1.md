---
project_outline: https://github.com/Davder1/project/blob/main/00-project/01-project-outline.md
---

<!-- @slide Címlap -->

<!-- @set-align center -->

<!-- @space -->

# Valós idejű procedurális terepgenerálás és a részletességi szintek kezelése

**Pernecker Dávid**

Neptun: YSFKEJ

Témavezető: Novák Péter

Projektazonosító: 2026-NP-03

<!-- @space -->

---

<!-- @slide Probléma -->

# Probléma

A nagy kiterjedésű terepek valós idejű megjelenítése jelentős teljesítményigénnyel járhat, különösen akkor, ha a teljes terepet egyszerre kell kezelni. A hatékony működéshez szükséges a terep kisebb blokkokra bontása, a kamerához igazodó dinamikus betöltés és eltávolítás, valamint a távolsághoz igazított részletességkezelés. A projekt célja annak vizsgálata, hogy különböző terepgenerálási módszerekkel hogyan valósítható meg egy hatékonyan működő, valós időben frissülő tereprendszer.

---

<!-- @slide Célfelhasználók -->

# Célfelhasználók

<!-- @columns 2 4 -->

## Játékfejlesztők és grafikai programozók

- Nagy kiterjedésű terepek megjelenítése.
- Dinamikus blokkkezelési és LOD-megoldások vizsgálata.
- Teljesítménybeli kompromisszumok megértése.

<!-- @col-break -->

## Hallgatók és kutatók

- Procedurális terepgenerálási módszerek vizsgálata.
- Különböző algoritmusok összehasonlítása.
- Mérési eredmények elemzése.

---

<!-- @slide Tervezett hatókör -->

# Tervezett hatókör

- Procedurálisan generált terep létrehozása Godotban.
- A terep blokkokra bontása, valamint a blokkok dinamikus betöltése és eltávolítása a kamera helyzete alapján.
- Saját LOD-rendszer kialakítása a terep részletességének szabályozására.
- Két terepgeneráló algoritmus teljesítményének és vizuális minőségének összehasonlítása.
- A generálási idő, a teljesítmény, a memóriahasználat és a blokkok közötti átmenetek vizsgálata.
---

<!-- @slide A projekt korlátai -->

# Mi nem része a projektnek?

- Teljes, önálló játék elkészítése.
- Nyílt világú játékmenet és egyéb, a tereprendszerhez nem kapcsolódó játékfunkciók fejlesztése.
- A játékmotor beépített terep- vagy automatikus LOD-rendszerének központi megoldásként történő használata.

**Fókusz:** a terepgenerálás, a dinamikus blokkkezelés, a részletességkezelés és a mérhető teljesítmény.

---

<!-- @slide Kezdeti felhasználói utak -->

# Kezdeti felhasználói utak

1. A felhasználó elindítja a programot.
2. A rendszer létrehozza a kamera környezetében szükséges terepblokkokat.
3. A felhasználó mozgatja a kamerát, miközben a rendszer a szükséges blokkokat betölti, a feleslegeseket pedig eltávolítja.
4. A rendszer a kamera helyzetéhez igazítja a terep részletességét.
5. A felhasználó megfigyelheti a terep megjelenítését és a blokkok közötti átmeneteket.

---

<!-- @slide Kezdeti felhasználói utak – mérés -->

# Terepgenerálási algoritmusok összehasonlítása

1. A felhasználó kiválasztja a vizsgált algoritmust.
2. Beállítja a mérési paramétereket.
3. Elindítja a generálást és a teljesítménymérést.
4. A mérést a másik algoritmussal is megismétli.
5. Összehasonlítja az eredményeket.

**Vizsgált szempontok:** generálási idő, teljesítmény, memóriahasználat és vizuális minőség.

---

<!-- @slide Következő lépések -->

# Következő lépések

<!-- @set-align left -->

1. A terepgeneráló algoritmusok és a LOD-kiválasztási módszer megtervezése.
2. Egy egyszerű, procedurálisan generált terepblokk létrehozása Godotban.
3. A kamerához igazodó dinamikus blokkkezelés megvalósítása.
4. A saját LOD-rendszer kialakítása és a szomszédos blokkok közötti átmenetek vizsgálata.
5. A fokozatos vagy aszinkron generálás megvalósítása.
6. Két terepgeneráló algoritmus összehasonlítása és a mérési módszerek kialakítása.
7. Teljesítménymérések elvégzése, az eredmények dokumentálása és értékelése.
