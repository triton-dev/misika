
Ez egy konkrét jól körülhatárolt feladat: https://hup.hu/node/157466
-----------------------------------------------------------------------------------------------------------------------------
Egy autómosó törzsvásárlói mini rendszerének programozására keresek php programozót. Egy kicsi rendszert szeretnénk az alábbi funkciókkal:
A törzskártyák, vonalkóddal ellátott kártyák lesznek.
- kártyák rögzítése
- kedvezmények rögzítése a kártyákhoz
- prepaid funkció (ügyfelek előre kifizetnek tetszőleges összeget és ezt a kártyán rögzítjük)
- látogatások naplózása a kedvezmények miatt
- ügyfelek külön felületen tudják nyomkövetni a kártya egyenlegét
--------------------------------------------------------------------------------------------------------------------------------------
# Boncolgassuk mit is akar:
## vonalkóddal ellátott kártya:
### Kérdések:
     * milyen kártya 
     * valamilyen papír alapú, helyben készülő, vagy előre gyártott…
     * milyen vonalkód 
       * kell-e valamilyen spéci szoftver az előállításhoz, vagy egyszerű, pl CODE39…
     * hogy kerül a kártyára
       * helyben nyomtatják, vagy előre nyomott etikettet ragasztanak fel, stb…
      
## kártyák kezelése cégen belül:
### Kérdések:
  * ki rögzítheti a kártyát
    * hány felhasználót, milyen jogosultsági körrel kell kezelni
  *	mit kell megadni a kártya rögzítésekor
    * a kártya mögött lesz-e megszemélyesítés, vagy elegendő a kártya felmutatása
  * ki, és mit módosíthat a kártya adatain, vagy a kártyához kapcsolódó adatokon
    * egy látogatás egy egységnyi látogatás, vagy több szolgáltatás igénybevétele befolyásol-e valamit
    * lesz-e valamilyen automatizmus, pl behajtáskor lehúzza az ügyfél egy szkenner előtt és az eszköz automatikusan
        küldi az információt, vagy ember végzi ugyan ezt
      
## pre-paid funkció:
### Kérdések:
  *	**nyugta, vagy számla adás nem feladat!**
  * mikor kerül levonásra a szolgáltatás díja és ki végzi ezt el
  * mi történik akkor, ha a kártyán nincs elegendő összeg
  * hogyan rögzítik a kedvezményt, és mikor lehet érvényesíteni
 
## egyenleg nyomonkövetés
### Kérdések:
  * elég megadni a kártya számát, vagy kell-e még egyéb adat is
  * elveszett kártya kezelése
    * letilthatja-e az ügyfél és hogyan,
    * csak a cég alkalmazottja tudja letiltani, hogyan
    * megtalált kártya tiltásának feloldását ki végezheti el,
    * mi lesz a kártyán lévő összeggel


