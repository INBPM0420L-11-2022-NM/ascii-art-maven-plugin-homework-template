# ASCII Art Maven Plugin

Készíts egy Maven plugint, amely egy ASCII artot ír a konzolra buildeléskor.

### Követelmények:

* Megoldásként hozz létre egy `maven` projektet. A pom.xml-ben tüntesd fel magad a `developers/developer` elemben.
* Helyezz el három darab, ASCII artot tartalmazó `txt` fájlt a `resources` mappán belül (pl. `llama.txt`).
* A pluginnak legyen egy célja, ami a három fájl közül egyet kiválaszt véletlenszerűen, és a kimenetre írja a fájlban található ASCII artot.
* A pluginnak legyen egy paramétere, amivel megadható, hogy melyik artot szeretnénk a kimenetre írni (pl. `llama`). Ebben az esetben véletlenszerű választás nem kell, csak a kért art megjelenítése. Ha helytelen azonosítót kér a felhasználó, akkor pedig egy hibaüzenetet írjon ki a plugin.

A fenti követelményeken kívüli további részletek rád vannak bízva (pl. a plugin neve, a cél neve stb.)

#### A következő oldalak hasznosak lehetnek:

* Maven plugin készítés: https://www.baeldung.com/maven-plugin
* ASCII artok: https://www.asciiart.eu/
* Reading a file from the Classpath szekció ebből a posztból (valamint a `stream-playground` projekt `Repository` kódja): https://www.baeldung.com/reading-file-in-java

A megoldásodat pushold fel ennek a repónak a master branchébe.
