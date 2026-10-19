---
project_outline: "https://github.com/Davder1/project/blob/main/00-project/01-project-outline.md"
---

> Ez az 1. félév első kötelező prezentációja. Bemutatja a projekt témáját, problémáját, célfelhasználóit, tervezett hatókörét és kezdeti felhasználói útjait. A kurzus szabványos Presented Markdown (PRMD) formátumában kell elkészíteni.

<!-- 5xl -->
# PROJEKT CÍME

Szerző:  Pernecker Dávid
Neptun:  YSFKEJ
Témavezető: Novák Péter 
Projektazonosító:  2026-NP-03

---

<!-- 2xl -->
[prmd.atom-forge.eu/docs](https://prmd.atom-forge.eu/docs)

---

## Probléma
A nagy kiterjedésű terepek valós idejű megjelenítése jelentős teljesítményigénnyel járhat, különösen akkor, ha a teljes terepet egyszerre kell kezelni. A hatékony működéshez szükséges a terep kisebb blokkokra bontása, a kamerához igazodó dinamikus betöltés és eltávolítás, valamint a távolsághoz igazított részletességkezelés. A projekt célja annak vizsgálata, hogy különböző terepgenerálási módszerekkel hogyan valósítható meg egy hatékonyan működő, valós időben frissülő tereprendszer.
## Célfelhasználók
- Játékfejlesztők és grafikai programozók, akik nagy kiterjedésű terepek hatékony megjelenítésével foglalkoznak.

- Hallgatók és kutatók, akik procedurális terepgenerálási módszereket és részletességkezelési megoldásokat szeretnének vizsgálni és összehasonlítani.
## Tervezett hatókör
**A projekt része:**

- Procedurálisan generált terep létrehozása Godotban.

- A terep blokkokra bontása, valamint a blokkok dinamikus betöltése és eltávolítása a kamera helyzete alapján.

- Saját LOD-rendszer kialakítása a terep részletességének szabályozására.

- Két terepgeneráló algoritmus teljesítményének és vizuális minőségének összehasonlítása.

- A generálási idő, a teljesítmény, a memóriahasználat és a blokkok közötti átmenetek vizsgálata.

**Nem része a projektnek:**

- Teljes, önálló játék elkészítése.

- Nyílt világú játékmenet és egyéb, a tereprendszerhez nem kapcsolódó játékfunkciók fejlesztése.

- A játékmotor beépített terep- vagy automatikus LOD-rendszerének központi megoldásként történő használata.
## Kezdeti felhasználói utak
**Terep bejárása**

- A felhasználó elindítja a programot.

- A program létrehozza a kamera környezetében szükséges terepblokkokat.

- A felhasználó mozgatja a kamerát, miközben a rendszer a szükséges blokkokat betölti, a feleslegeseket pedig eltávolítja.

- A rendszer a kamera helyzetéhez igazítja a terep részletességét.

- A felhasználó megfigyelheti a terep megjelenítését és a blokkok közötti átmeneteket.

**Terepgeneráló algoritmusok összehasonlítása**

- A felhasználó kiválasztja a vizsgált terepgeneráló algoritmust.

- Beállítja a mérési paramétereket.

- Elindítja a generálást és a teljesítménymérést.

- A program eredményeit rögzítik, majd a folyamatot a másik algoritmussal is megismétlik.

A felhasználó összehasonlítja a mért teljesítményt, a memóriahasználatot és a létrehozott terep vizuális minőségét.
## Következő lépések
1. A terepgeneráló algoritmusok és a LOD-kiválasztási módszer megtervezése.

2. Egy egyszerű, procedurálisan generált terepblokk létrehozása Godotban.

3. A kamerához igazodó dinamikus blokkkezelés megvalósítása.

4. A saját LOD-rendszer kialakítása és a szomszédos blokkok közötti átmenetek vizsgálata.

5. A fokozatos vagy aszinkron generálás megvalósítása.

6. Két terepgeneráló algoritmus összehasonlítása és a mérési módszerek kialakítása.

7. Teljesítménymérések elvégzése, az eredmények dokumentálása és értékelése.
