# **Popis systému Exercisea**


Systém Exercisea je webová aplikácia, ktorá slúži na evidovanie cvičení a ich kategórií. Aplikácia umožňuje používateľom zobraziť dostupné kategórie a v rámci nich pridávať cviky s popisom a fotkami alebo videami. K cvikom je tiež možné pridávať komentáre, ktoré môžu byť viditeľné pre všetkých používateľov aplikácie.


## **Uživateľské role**

**V aplikácii sa budú používať dve uživateľské role:**
### **Administrátor**
Má prístup k správe celej aplikácie a môže pridávať, upravovať a mazať kategórie, cviky a komentáre.
Zároveň má rovnaké schopnosti ako prihlásený používateľ.

### **Prihlásený používateľ**
Môže zobraziť kategórie, cviky a pridávať komentáre k cvikom. Kategórie a cviky je schopný vyhľadávať. Môže sa z detailov každého cviku niečo dozvedieť. V neposlednom rade je schopný sa prihlásiť a odhlásiť.

## **Funkcie systému**
* Registrácia a prihlásenie používateľov
* Evidencia kategórií
* Pridávanie cvičení s popisom a fotografiou kategóriám
* Pridávanie komentárov ku cvičeniam a kategóriám
* Správa obsahu (kategórie, cvičenia, používatelia)
* Vyhľadávanie cvičení a kategórií podľa názvu, popisu alebo kľúčových slov.
* Možnosť hodnotenia cvičení používateľmi a zobrazenie priemerného hodnotenia pre každé cvičenie.
* Zdieľanie cvičení a kategórií na sociálnych sieťach alebo prostredníctvom odkazov.

## **Technológie použité v rámci projektu**
Pre vývoj aplikácie bude použitá kombinácia technológií:
* React.js: Knižnica pre tvorbu užívateľského rozhrania. Momentálne s touto technológiou nemám veľké skúsenosti, ale v rámci kurzu PB138 sa s ňou učím pracovať.
* Next.js + Prisma: Zabezpečuje server-side rendering a slúži ako ORM (object-relational mapping) vrstva pre prácu s databázou. S oboma technológiami sa učím pracovať v rámci kurzu PB138 a PV178.
* SQLite: Relačná databáza pre ukladanie dát - s touto technológiou som pracovala na kurze PV178.
* Bootstrap: open-source css framework pre vývoj webových stránok, s ktorým som ešte nepracovala, ale môj tímový partner s ním má skúsenosti.

Front-end: React.js
Back-end: Next.js + Prisma
Databáza: SQLite
CSS Framework: Tailwindcss

## **Model životného cyklu**
Pre tento projekt sme sa rozhodli použiť model životného cyklu Agile. Tento model umožňuje flexibilitu a rýchlu iteráciu, čo je dôležité pre vývoj webovej aplikácie. S týmto modelom je možné prispôsobiť sa zmenám požiadaviek v priebehu vývoja a postupne dodávať nové funkcie aplikácie. Taktiež umožňuje zákazníkovi sledovať priebeh vývoja a poskytovať spätnú väzbu.