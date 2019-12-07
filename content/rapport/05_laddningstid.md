Laddningstid
=======================

För kmom05 fick vi i uppgift att undersöka hur lång laddningstid 3 olika sidor har. Sidorna skall vara av 'samma typ' för att få en rättvis jämförelse.
Vi ska också analysera resultaten och rangordna sidorna utefter dettsa.

Urval
-----------------------

Jag har valt att använda mig av samma sidor som under kmom04, det vill säga tre stora snabbmatskedjor, Max, McDonalds och Burger King.
Det kan vara kul att se även i detta kursmoment då det är stora företag, men sidorna är uppbyggda av väldigt mycket bilder osv som kan påverka laddningstiden.
Innan jag börjat analysera sidorna så känns det instinktivt som att sidor, med företag av denna storlek borde tänkt på sådant som laddningstid och ha löst det på ett bra sätt, men det återstår att se!

Metod
-----------------------

Då ingen av sidorna kräver inloggning har jag valt att använda Google Page Speed för att mäta sidorna. Jag använder Chrome, så hade sidorna krävt inloggning hade jag kunnat använda mig av inbyggda funktionen LightHouse, använder även DevTools i Chrome för laddningstiden, storlek och förfrågningar. Jag kör varje sida 3 gånger för att få ut någon form av snitt och se så inget sticker ut, både i mobilanpassat läge samt desktop läge. För att redovisa resultaten används Google Docs som länkas under resultat.

Nedan kan ni se skärmdump från startsidan för vardera sida:

![McDonalds Frontpage](../htdocs/img/McDonaldsfrontpage.jpg "McDonalds Frontpage")


![Burger King Frontpage](../htdocs/img/burgerkingfrontpage.jpg "Burger King Frontpage")


![Max Frontpage](../htdocs/img/maxfrontpage.png "Max Frontpage")

Resultat
-----------------------

[Resultat](https://docs.google.com/spreadsheets/d/1ddMLMBVAwO5PuQYAX2e_YBLjOxPxF3dXQCAjS_La5U4/edit?usp=sharing)

#### McDonalds

McDonalds startsida hade en genomsnittlig laddningstid på 1,6 sekunder och var högst bland de tre testade sidorna.
Näst högst låg menyn på som hade genomsnittlig tid på 1,38s och snabbast gick Om Oss med en genomsnittlig tid på 1,16s.

För de tre sidorna laddades i snitt 98,3 resurser ner för startsidan, 80st för Om Oss samt 97st för menyn.
MB som hämtades för vardera var 8mb startsida, 2,6mb för Om Oss samt 5,2MB för menyn.

Ser man till testerna på Google Page Speed så rankades McDonalds klart sämst, särskilt när det kom till mobilversionen. Startsidan fick 15 i score, medans Om Oss landade på 31 och menyn på 24. Det såg lite positivare ut i desktop, 78 startsida, 90 Om Oss samt 88 menyn.

#### Burger King

Laddningstiderna för Burger King var följande i snitt;
Startsida - 0,45s
Om Oss -0,33s
Meny - 0,762s

För sidorna så fick startsidan snittet på 45,6 resurser, Om Oss på 19,6 resurser samt Meny 118 rerurser. Den totala storleken för varje i snitt var 2,6MB för startsidan, 0,6MB för Om Oss samt 1,56MB för menyn.

När jag körde Burger Kings sidor i Google Page Speed blev resultatet 92 i mobil för startsidan, 94 för om oss samt 45 för menyn. Desktop så glänsde de desto mer med 100 för startsidan, 100 för Om Oss och 97 för menyn.


#### Max Hamburgare

Laddningstiderna för Max var följande i snitt;
Startsida - 1,25s
Om Oss -0,63s
Meny - 0,938s

Antalet resurser för startsidan slutade på 55, medans storleken blev 1,63MB. För Om Oss så slutade det på 43,7 resurser och en storlek på 1,1MB. Menyn hade 50 resurser samt 1,1MB storlek.

I Google Page Speed så fick de ranking för mobil 84 Startsida, 90 Om Oss samt 91 menyn. Desktop landade något högre med 98 för startsidan samt 100 för både Om Oss och Meny.



Analys
-----------------------

##### Mobil

Ser man på vad de olika hemsidorna presterade när det testades som mobil version så är det Burger King som sticker ut som bäst, tätt efter Max och absolut sämst McDonalds.
Det som verkade vara en genomgående förbättringsåtgärd för alla tre sidor var dels att arbeta mer med bilderna, där lazy loading gavs som en möjlig lösning särskilt för McDonalds som hade det kämpigare med detta. Men också arbeta med att ha rätt storlek på bilderna samt använda sig av andra format för sina bilder. De hade onödigt stora bilder och att byta format kunde på så vis kompremera detta till viss del. Då alla tre sidor jobbar extremt mycket med olika bilder så känns de som en stor förbättringspotential som kan göra mycket för dem.




##### Desktop

Resultaten för desktop såg ju betydligt bättre ut för alla tre hemsidorna. Det vanligaste förbättringensåtgärden här för Max och McDonalds var som tidigare att använda sig av rätt format på alla de bilder de använder för att få snabbare loading och mindre data konsumption. För Burger King däremot var inte detta ett problem, där fanns dock en förbättringsåtgärd i att använda sig av cache som sparas över tid, så allt inte behövdes laddas om varje gång. Till de menyer osv som de i stort sett alltid har borde detta vara en lösning då de förmodligen alltid ser samma ut.


##### Vinnare
För mig känns vinnaren som Burger King, de har en bra sida med snabb loading, de hade väldigt hög score både på mobil samt desktop men också rent generellt bra resultat i de vi mätte. McDonalds fick ju oväntat dåligt resultat i Google Page Speed så de får ta sista platsen.

##### Laddningstid
För mig känns en bra laddningstid under 3 sekunder. Självklart kan man ha viss förståelse för en del sidor där man känner till att de är tunga saker som ska laddas in, men i det stora hela får det inte ta längre tid. Jag har funderat kring de och när man googlar och man väljer någon sida man inte varit inne på t ex om man ska handla något, och inte känner till sidan. För mig, om sidan tar lång tid att ladda ger det ett oseriöst intryck och jag kommer förmodligen välja en annan sida att handla på. Dock så pratades det om Lazy Loading på föreläsningen och jag hade de som förslag tidigare i texten här också, då känns det helt klart mer OK angående laddningstid.

De sidor jag besökte nu tyckte jag va klart godkända via desktop som jag mest tittat på dem, särskilt när man vet att de är väldigt många bilder som ska laddas in också. De går snabbt och bra, även om vissa bilder dyker upp en halv sekund senare än andra.

Referenser
-----------------------

Ange de eventuella referenser du använder dig av, om några.

Övrigt
-----------------------

Arbete gjort av Christoffer Bolin
