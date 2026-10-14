# name: Pernecker Dávid neptun: YSFKEJ id: 2026-NP-03 github: https://github.com/Davder1/project github_project: 

# Valós idejű procedurális terepgenerálás és a részletességi szintek kezelése

A projekt célja egy olyan terepdemonstrátor elkészítése Godot játékmotorral, amely nagy kiterjedésű terepet képes procedurálisan létrehozni és valós időben megjeleníteni. A terep kisebb blokkokra lesz felosztva, amelyek betöltése és eltávolítása a kamera helyzetéhez igazodik. A rendszer saját részletességkezelést (LOD) valósít meg, és lehetőséget biztosít különböző megközelítések teljesítményének és vizuális minőségének összehasonlítására.

## Célok

- **Elsődleges cél:** Működő, valós időben frissülő procedurális terepdemonstrátor elkészítése saját blokkkezeléssel és LOD-rendszerrel.
- **Célfelhasználók / érintettek:** Elsődlegesen a projekt fejlesztője és témavezetője; a demonstrátor a terepgenerálási és LOD-megoldások vizsgálatát szolgálja.
- **Mérhető sikerkritériumok:** A rendszer képes terepblokkok generálására, a kamera mozgásához igazodó betöltésére és eltávolítására, valamint a részletességi szintek saját szabályok alapján történő kiválasztására. Legalább két érdemben eltérő megközelítés összehasonlítható reprodukálható mérésekkel. A teljesítmény, a memóriaigény és a blokkok közötti átmenetek vizsgálata dokumentált.
- **Korlátok:** A projekt Godot játékmotort és kezdetben GDScript nyelvet használ. A terepgenerálás és a LOD-kezelés központi logikája saját megvalósítás lesz; a motor elsősorban a megjelenítést és az általános infrastruktúrát biztosítja. Teljes játék vagy nyílt világú játékmenet elkészítése nem cél.

## Hatókör

### Benne van a hatókörben

- Procedurálisan generált terepgeometria vagy terepmagasság előállítása.
- A terep blokkokra bontása és a blokkok dinamikus kezelése.
- A kamera mozgásához igazodó blokkbetöltés és -eltávolítás.
- Saját LOD-kiválasztási mechanizmus megvalósítása.
- Legalább két érdemben eltérő generálási vagy LOD-megközelítés összehasonlítása.
- A különböző részletességű szomszédos blokkok közötti rések és átmenetek vizsgálata.
- Fokozatos vagy aszinkron feldolgozás alkalmazása.
- Teljesítmény-, memória- és geometriai mérések végrehajtása és dokumentálása.
- A forráskód és a dokumentáció verziókezelése GitHubon.

### Nincs benne a hatókörben

- Teljes, önállóan játszható játék elkészítése.
- Kidolgozott játékmechanikák, történet vagy küldetésrendszer.
- Teljes nyílt világú játékhoz szükséges minden rendszer megvalósítása.
- A játékmotor beépített automatikus LOD- vagy tereprendszerének használata a projekt központi megoldásaként.
- A témakiírásban nem szereplő, nagyobb kiegészítő funkciók megvalósítása, amennyiben azok nem szükségesek a demonstrátorhoz és a mérésekhez.

## Jegyzetek

A fejlesztés egy egyszerű, procedurálisan generált terepblokkal és mozgatható kamerával kezdődik. Ezt követi a blokkok dinamikus kezelése, majd a saját LOD-rendszer kialakítása. A konkrétan összehasonlítandó módszereket, a LOD-kiválasztás szabályait, az aszinkron feldolgozás megoldását és a mérési eljárásokat a specifikációban kell pontosítani.

A méréseket reprodukálható módon, dokumentált beállításokkal kell elvégezni. A fejlesztés során külön figyelmet kell fordítani a különböző részletességű szomszédos blokkok közötti folytonosságra és az esetleges látható hibákra.


