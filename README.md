# Szakdolgozat projekt (DarkRealm)

### Téma relevanciája
A játékfejlesztés egyre **nagy**obb **népszerűség**nek örvend a szórakoztatóiparban. Ezzel a szakdolgozattal egy olyan játék tervezését és fejlesztését célzom meg, amely egy **középkori fantasy** világban játszódik, és olyan elemeket tartalmaz, amelyek vonzóak lehetnek a felhasználók számára. Ez a típusú játék kezd újra népszerűvé válni a játékosok körében, pontosan azért, mert **egyszerű és sokoldalú** tud lenni. Az ötletemmel próbálom ezt az egyszerűséget egy kicsit gyorsabb, izgalmasabb, és színesebb módon megjeleníteni. Emellett a pályák, a játékmechanikák, és a különböző karakterépítési lehetőségek hozzájárulnak a játék **újraélhetőség**éhez, komplexitásához.

## Téma általános leírása
 A szakdolgozatom egy **videójáték** tervezésével és fejlesztésével foglalkozik, amelyet a sötétség témája köré építek fel. Ez egy **3D-s, belső nézetes dungeon-crawler**/felfedező játék, amely középkori fantasy környezetben játszódik. A játékban statikus pályákon kell felfedezni a rejtett titkokat, legyőzni az ellenségeket, **új**, illetve jobb **fegyvereket** és egyéb felszerelést zsákmányolni. A játékos **különböző karakterépítések**et alkothat, és a játék során nem fog kötődni semmilyen osztályhoz. Ez annyit jelent, hogy **ha egy új típusú fegyverre bukkan**, bármilyen lekötés nélkül **használhatja azt**. Ez segíti az újrajátszhatóságot, és a monotonitás elkerülését. A játékos a **felszerelését** az **ellenségektől, ládákból, vagy boltokból kapja**. A pályák felfedezése alatt **bukkanhat fegyverekre, páncélzatra, felszerelésre**, vagy pénzérmére. Ezeket felhasználhatja, vagy **eladhatja a boltokban**, ahonnan akár **új tárgyakat, fegyvereket is vásárolhat**. A különböző fegyvereket, és páncélokat a felhasználó egymástól független felveheti. **A fegyverek** a következők: **kések, egykezes kard** és **pajzs, íj**, valamint egy **kétkezes fejsze**. Ezeknek különböző tulajdonságaik vannak, így **fegyverenként megváltozik a játékélmény**. **A páncélt nehéz, közepes, és könnyű** kategóriákba sorolhatjuk. A nehéz páncél sok sebzést levéd, de lelassítja a felhasználót. A könnyű, kevés sebzést véd le, de nem lassít, a közepes páncél pedig ezeknek a középpontját szolgálja. A felszerelés alatt az olyan **kisegítő tárgyak**at értjük, mint például a **nyílvessző, vagy a bandázs**. **A fő játékmechanika a sötétség köré épül**, ugyanis a pályák nincsenek bevilágítva, és a sötétség legyőzésére csak néhány módszer van. A felhasználó **támadásnál**, afféle **tűz-effektus**t bocsájt ki az általa választott fegyverből, ami reagál a körülötte lévő területre, tárgyakra. Az effektus, miután megközelített egy falat/tárgyat, a felhasználó tartózkodási helyétől, és a fegyver típusától függően, reális szögben **pattan le a fal vagy tárgyról**. A lepattant effektus **több sebzést okoz**, ezzel inspirálva a felhasználót ennek a kreatív harcrendszernek a használatára. A tűznek **3 típus**a elérhető, amit a játékosnak a pálya belépése előtt ki kell választania. A tűz típusai a **piros, a zöld, és a kék**. Ezek különböző segítségekkel szolgálnak a felhasználónak. A fegyver használatánál, **ha az ellenséget eltaláltuk** a tűz-effekttel, annak esélye van az ellenségekre valamely **gyengítő hatás**sal szolgálni. A 3 típus más-más hatást válthat ki az ellenségekre. **A piros** pár másodpercen át **folyamatosan sebez**, **a zöld** képes **egy találat sebzését átadni egy másik közeli ellenfélre** is, valamint **a kék lelassíthatja az ellenfeleket**. **Az ellenfelek**et egyszerű, feltámadt csontvázaknak képzeltem el. Ezek között néhány típus létezik. **Egy**, amely **távolról íjászkodik**. Ettől kaphatjuk meg az íj fegyvert, valamint a könnyű páncélzatot. **Egy**, ami közepes páncéllal, valamint **kard és pajzzsal, vagy késsel** közelít. **Az utolsó** nehéz páncélzatot visel, és **kétkezes fejszével** támadhat a játékosra. Amíg **"sötét” van**, a játékos a világot **ködösen, színek nélkül** látja, és csak az ellenfelek halvány körvonala segíti a tájékozódásban. Azonban a játékos **fegyvere használatánál**, a terület **felvilágosodik, a színek láthatóvá válnak, és a kiválasztott tűz árnyalatában gyengén átszineződik** a területet a felhasználó és az ellenfelek körül. A sötétséget ki lehet használni a javunkra is, mivel a **lopakodás** szerepet kap a játékprogramban. Ha a játékost **még nem vették észre**, az ellenfél mögül lehetősége van egy azonnali **“kivégzésre”**. Azonban ezzel magára vonja a figyelmet, és minden ellenfél a környéken megtámadja őt. Ezzel szemben a játékos dönthet úgy, hogy megpróbál figyelmen kívül maradni, és a területen lévő ládákból **zsákmányt szerezni, anélkül, hogy harcba kerülne**. **Halál esetén** a játékos pozíciója elmentődik, és az **összes felszerelése azon a ponton marad**. A játékos ezután a pálya elején ébred, ahol **néhány alapfegyver**t találhat, majd újra kezdheti a pályát, ami pont úgy marad, ahogy hagyta. Azok az ellenfelek amiket a felhasználó már legyőzött, nem élednek újra. A játékosnak ez után lehetősége lesz visszamenni arra a pontra, ahol meghalt, ahol **a felszerelése nagyját egyből visszakaphatja**. Attól függően, hogy milyen sokáig tart a felhasználónak visszatérnie, oda, ahol meghalt, találhatja a felszerelésének egy részét vagy egészét. Ezt 3 szakaszban képzeltem el. **Ha a játékos gyorsan visszatér** a halála pontjához, az **összes felszerelés**ét egyből visszaszerezheti, azonban **némely pénzt veszített**, amit már **az ellenségek birtokolnak** a holttest körül. Ha a játékos **közepes idő**ben ér vissza, **a zsákmánya nagyrészét** egyből visszakaphatja, és egy **kevés pénzt is talál** a holttesténél. Azonban ha a felhasználónak **sokáig tart visszaérni, a felszerelésének a legjavát, és a pénze egészét az ellenségeknél fogja találni**. 
 
## A szakdolgozatom során az alábbi feladatokat kell elvégeznem: 

### Játékmechanika kidolgozása
- Tűzhatásrendszer tervezése és implementálása 
- Falakkal és tárgyakkal való ütközés fizikájának implementálása 
- Ellenfelek AI-jának tervezése és implementálása 
- Fegyverek és felszerelések tervezése és implementálása 
- Sötétség és lopakodás rendszerének kidolgozása 

### Halál és újjáéledés rendszer
 - A játékos pozíciójának és felszereléseinek mentése halál esetén 
 - Halál utáni újraéledési pont kiválasztása és implementálása 
 - Zsákmány ellenfeleknek való átadása idő múltával 

### Grafika és design
- Vizuális stílus és atmoszféra kialakítása 
- 3D modellek és animációk létrehozása a fegyverekhez, ellenfelekhez és a környezethez 
- Tűzhatások és vizuális effektusok kialakítása 
- Felhasználói felület és HUD tervezése és implementálása 
 
 ### Pályatervezés
 - Pályák tervezése 
 - Ládák, és ellenfelek elhelyezése a pályán 
 - Játékmenet és egyensúly
     >Ellenfelek erősségének és viselkedésének beállítása 
 - Fegyverek és tűzhatások sebzésének és hatásának beállítása

### Tesztelés és hibajavítás
- Játéktesztek végrehajtása, hibák azonosítása 
- Hibajavítások végrehajtása a játék stabilitásának és minőségének javítása érdekében 
- Finomítás és optimalizáció 
  > Vizuális és hanghatások finomhangolása 
- Játékmenet és szintek finomítása 
- Felhasználói felület optimalizálása 
- Használt technológiák ismertetése

### Játék motor
Ehhez a típusú játékhoz az **Unreal Engine 5**-öt választottam. Ez a motor **erős grafikai képességek**kel rendelkezik, valamint különféle **fizikai és animációs funkciók**at kínál, amelyek segítségével megvalósíthatók a tervezett játékmechanikák. 

### Grafikai tervezés
A vizuális stílus és atmoszféra kialakításához a **Blender** modellező és animációs szoftverre gondoltam. Ezzel a szoftverrel létrehozhatom a játékban szereplő karaktereket, fegyvereket, ellenfeleket és a környezet modelleit, valamint az animációikat.

### Fizikai motor
Az **Unreal Engine 5 már tartalmazza a kellő fizika motort**, így nincs szükség külön fizika motor használatára. A beépített fizikai motor támogatja a valós idejű ütközésvizsgálatot és a dinamikus objektumok szimulálását. 

### Mesterséges intelligencia (AI)
Az ellenfelek számára tervezett AI megvalósításához **szkriptelési nyelveket vagy AI rendszereket** használnék, mint például a **Behavior Tree vagy a State Machine**. Ezen rendszerek segítségével különböző viselkedéseket és döntési folyamatokat írnék az ellenfelek számára. 

### Tűzhatások és vizuális effektusok
A tűzhatások és más vizuális effektusok kialakításához az **Unreal Engine 5-ben** lévő beépített effektus-szerkesztő szoftvert használnám. 

### Felhasználói felület (UI)
A játékhoz szükségem lesz egy felhasználói felületre és HUD-ra. Ehhez az **Adobe Photoshop**-ot választottam.

## A munka ütemterve
|**Ütemterv**|**Teendő**|
|----------------|-------------------------------|
|`Szeptember-október`|Játékmechanika kidolgozása, implementálása
|`November-december`|Halál és újjáéledés rendszer & Grafika és design
|`Január-február`|Grafika és design & Pályatervezés
|`Március-április`|Játékmenet és egyensúly & Tesztelés és hibajavítás & Finomítás és optimalizáció
