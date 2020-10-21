# ByteBoard met Mblock

# Inhoud
- [Wat is dit?](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/nederlands.md#wat-is-dit)
- [Instalatie](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/nederlands.md#instalatie)
- [Gebruik](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/nederlands.md#gebruik)
- [Problemen oplossen]
- [Toekomstige Ideeen](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/nederlands.md#toekomstige-ideeen)

# Wat is dit?
De byteboard is een board met alles erop en eraan. Dit maakt het gemakkelijk voor leerlingen om deze te leren programmeren. Doordat alles er al op zit is het (bijna) onmogelijk om iets kapot te maken. Je kan het gemakkelijk programeren met de arduino IDE (instructies) of met het blokjes programma Mblock (instructies).

De byteboard heeft veel verschillende componeten zoals een led matrix, meerdere sensoren en io poorten voor toekomstige andere componenten zoals grote LED strips.

# Instalatie
#### Stap 0. 
###### Zorg dat je het volgende hebt:
- Mac of Windows Computer
- Een Byteboard
- Een USB kabel voor de byteboard
- Werkende internet verbinding


#### Stap 1. Downloaden en installeren
###### Voor de instalatie moeten we de volgende programmas downloaden: 
- Arduino Ide van de website www.arduino.cc/download verder omlaag kun je de Arduino IDE voor je OS downloaden
- CHX Driver voor je mac. LETOP: DOWNLOAD DIT ALLEEN ALS JE NOG NOOIT MET ARDUINO HEBT GEWERKT!! (dus als je ooit al arduinos hebt gebruikt download dit dan niet! Je kan hiermee je configuratie corrupten) Als je het nog nooit eerder hebt gedaan download het dan hier https://github.com/darkroasted/Files/raw/master/CH34x_Install_V1.5.pkg
- MBlock Programma. Deze kun je hier vinden: https://mblock.makeblock.com/en-us/download/ Selecteer download PC version.

Installeer nu de net gedownloadde software. Als je dat hebt gedaan kun je verder
# 
#### Stap 2. MBlock instellen. 
Nadat je alles hebt geinstaleerd kun je MBlock openen via je spotlight. Vervolgens om mblock de correcte blocken te geven moeten we een extensie voor de ByteBoard downloaden. Deze kun je hier downloaden https://github.com/darkroasted/ByteBoard-MBlock-Extension/releases
Zorg daarbij dat je de meest recente versie hebt. (Je kunt hem ook gelijk hier downloaden via direct download: https://github.com/darkroasted/ByteBoard-MBlock-Extension/releases/download/V1.1/ext_c600784a-V1.1.mext)

Zodra je de extensie hebt gedownload die eindigd in .mext kun je deze vannuit je downloads map in je mblock slepen en daar laten vallen.

#### Stap 3. Gebruik
Je bent nu klaar met de installatie. En nu kun je door naar het leren gebruiken van mblock met je byteboard.

# Gebruik
#### Stap 0. Installatie
Zorg ervoor dat je de bovenstaande stappen allemaal hebt uitgevoerd en dat je het volgende scherm voor je hebt 

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/1.png?raw=true)

#### Stap 1. Programeren
Nu gaan we beginnen met de eerste code programeren. Hierbij zetten we gewoon een lichtje aan als de byteboard opstart. Dit doen we door het blok "when arduino starts up" uit de map gebeurtenissen te halen en het veld in te slepen.

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/2.png?raw=true)

Nu plaatsen we daaronder het blok: "Led Boven Aan" uit het mapje ByteBoard. 

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/3.png?raw=true)

Als het goed is zou het er nu zo uit moeten zien

![verify](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/4.png?raw=true)

#### Stap 2. Naar Arduino IDE
Nu gaan we onze net gemaakte code uploaden naar de ByteBoard. Dit doen we door als eerste de code die MBlock voor ons heeft gegenereerd te copieren. Deze code kunnen we vinden door op het gele "</>" knopje rechts te klikken.

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/5.png?raw=true)

Als we daar op klikken komt er een zijbalk met allemaal arduino code. Dat zou er zo uit moeten zien. 

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/6.png?raw=true)

We moeten nu al deze code copieren door er even op te klikken en dan CMD + A in de drukken om alles te selecteren en dan CMD + C om het te copieren. 

Hierna openen we de Arduino IDE. Dan krijgen we dit scherm met al wat code erin.

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/7.png?raw=true)

Dit moeten we eerst verwijderen en daarna plakken we de net gecopieerde code uit MBlock daarin.

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/9.png?raw=true)

#### Stap 3. Verbinden
Verbind nu je Byteboard met je laptop via de USB kabel


![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/laptop-usb-cable.png?raw=true)

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/board-usb-cable.png?raw=true)

#### Stap 4. Uploaden
Eerst moeten we het correcte board selecteren. Dit doen we door in het Arduino programma in te bovenste balk via het kopje Hulpmiddelen > Board en dan "arduino nano" te selecteren

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/board-select.png?raw=true)

Nu moeten we even de bootloader selecteren dit down we door weer naar Hulpmiddelen te gaan en dan via Hulpmiddelen > Processor en dan "ATmega328P (old bootload) te selecteren"

![image](https://raw.githubusercontent.com/darkroasted/ByteBoard-MBlock-Extension/master/images/bootloader-select.png)

Nu kunnen we de poort selecteren. Dit doen we weer bij Hulpmiddelen en dan Naar poort en dan selecteer je iets met CHU.W. (niet die ene met bluetooth)

Om het nu op de board te plaatsen klikken we op het upload pijltje

![image](https://github.com/darkroasted/ByteBoard-MBlock-Extension/blob/master/images/arduino-ide-upload.png?raw=true)

Nu moeten we wachten tot het klaar is....

je kan onderaan zien of het klaar is.

![image](https://raw.githubusercontent.com/darkroasted/ByteBoard-MBlock-Extension/master/images/Schermafbeelding%202020-03-09%20om%2017.36.24.png)

# Toekomstige Ideeen
- Dit afmaken
- Mogelijkheid toevoegen om dit aan de led strip te koppelen in de makerij







