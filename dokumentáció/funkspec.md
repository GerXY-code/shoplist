# Áttekintés
Egy olyan webes alkamazást készítünk, amely segítségével a felhasználó képes lesz bevásárlási listát összeállítani.
Ezt az alkamazást nem kell telepíteni, nem kell kompatibilitási problémákat megoldani, egyszerűen csak át kell másolni a telefonra a html file-t.

# Jelenlegi állapot
Sokszor előfordul az, hogy az ember nincs internet közelben és előre nem írta meg a bevásárló listát, viszont letölteni sem tud appot, mert esetleg nincs internet közelben. Ezt a problémát küszöböli ki a webes alkalmazás, melynek nincs szüksége internetre, csupán csak egy böngészőre és magára a telefonra esetleg tabletre, vagy esetleg egy kisebb méretű notebookra.

# Képernyőterv
Miután elindítjuk az alkalmazást ez a képernyő fogadja a felhasználót: ![Default](https://github.com/GerXY-code/shoplist/blob/main/k%C3%A9pek/alap.PNG)

Ha valamelyik mezőt nem töltik ki, és/vagy helytelen értéket adunk, akkor azt a képen látható módon jelezzük a felhasználónak: ![Error](https://github.com/GerXY-code/shoplist/blob/main/k%C3%A9pek/hahiba.PNG)

Amennyiben sikerült a felvitel, akkor a felhasználó számára, a képen láthatóan meg fog jelenni a termék összes adata: ![Added](https://github.com/GerXY-code/shoplist/blob/main/k%C3%A9pek/felvitel.PNG) 

## Követelmények listája.
Modul | ID | Név | Verzió | Magyarázat
------------ | ------------- | ------------ | ----------- | -----------
Felvitel | K1 | Űrlap kitöltése | 1.0 | Itt kell megadni hogy milyen terméket vásárol a felhasználó.
Hiba | K2 | Hiba megjelenítése | 1.0 | Tudatni kell a felhasználóval, hogyha valamit nem jól töltött ki, esetleg nem töltött ki.
Módosítás | K3 | Termék módosítása | 1.0 | Módosíthatja a felhasználó az adott terméket.
Törlés | K4 | Termék törlése | 1.0 | A felhasználó törölheti a terméket a listábról.