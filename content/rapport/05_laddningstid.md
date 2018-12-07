---
---
##Laddningstid







Urval
-----------------------

Jag har valt tre spa sidor som är etablerade på Sardinen, där jag bor. Jag valde dem då jag visste att dem innehåll mycket bilder med bra kvalitet för att förmedla sina produkter. Då kursmoment 5 handlar om bilder så ville jag fokusera på detta. Samt att jag antog att de inte skulle ha den bästa optimiseringen på bilder så som exempel Facebook har tid och ekonomi till.


Metod
-----------------------

Jag har använt mig av Develpment toopls i Google crome browser i Cognito mode.
Samt Google Pagespeed.




Rangordna dina webbplatser baserat på deras mätvärden och kommentera resultatet.

Bestäm en gräns för absolut laddningstid som du själv uppfattar som snabb eller långsam webbplats. Skriv ett stycke om hur ditt urval av webbplatser klarar ditt gränsvärde och hur du upplever webbplatsernas snabbhet.

I slutet av rapporten skriver du ett eget stycke med namnen på dina gruppmedlemmar.






Resultat
-----------------------

vad kan de förbättra? Varje sida?

##T-Hotell - 1

[FIGURE src=image/thotell.png?w=700 class="thotell"]

[THotell](https://www.thotel.it/it/centro-benessere-spa-cagliari.html)

Förbättringar som kan göras för att påverka PageSpeed:

Det kan byta formatet på deras bilder. Då vissa format kan komprimera sig bättre och då ger bättre nedladdnings hastighet. Via PageSpeed kan man se hur mycket man kan spara per bild.

Använda bilder med rätt storlek för att spara på nedladdnings mängden.

Sidan verkar ha blockerade kod. Till exempel JavaScript kod som gör att sidan måste stanna där och läsa igenom det först innan den kan få ut hela html sidan. De kan flytta ner sådan kod för att ge prioritet för viktigare kod först.

De kan även städa upp i sin kod så kod som inte används tas bort eller ta bort överflödiga tecken som "," eller " ". Så färre bytes behöver hämtas.


##Sardegna Termale - 2

[FIGURE src=image/termale.png?w=700 class="termale"]
[Sardegna Termale](http://www.sardegnatermale.it/spa-benessere/)

Förbättringar som kan göras för att påverka PageSpeed:

Denna sidan verkar ha stört nöd att ta bort blockerade kod, som jag nämnde ovan. Exempelvis JavaScript kod som måste läsas igenom först innan man kan få ut hela sidan. De behöver även minifiera sina JavaScript filer, genom tex UglifyJS.

Sen har de tre mindre saker så som att städa upp css kod, aktivera textkomprimering samt att använde modernare bild format.



##Spa Italia Wellness - 3

[FIGURE src=image/wellness.png?w=700 class="wellness"]
[Spa Italia Wellness](https://www.spaitaliawellness.com/spasardegna/spa-centri-benessere-sardegna/city-spa-cagliari/#)

Förbättringar som kan göras för att påverka PageSpeed:


Denna sidans störta problem är svarstiderna från serven. Alltså tiden från att första byten laddas.

Även dem här behöver ta bort blockerade kod, skicka bilder i modernare format, koda bilderna mer effektivt och städa rent i sin css kod.


Rå data från Speed Tester
-----

<iframe width="480" height="246" frameborder="0" scrolling="no" src="https://studentbth-my.sharepoint.com/personal/jobj18_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={303980fd-be1f-46df-a0e4-78003c5ef175}&action=embedview&wdAllowInteractivity=False&ActiveCell='Sheet1'!A3&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True"></iframe>


Analys
-----------------------

Diskutera och analysera de resultaten du fann.

Alla tre sidorna hade lågt betyg på Google PageSpeed, mellan 24-49, vilket definieras som långsam.

Jag fann att mycket av orsakerna till deras långsamma laddningstid har relativt enkla lösningar. Såsom att använda mer modernare filformat till bilder, städa upp i koden, tillåta komprimering av kod och bilder.

De hade även alla blockerade kod på något sätt. Jag antar att alla tre sidor kan ändra på detta då i alla fall JavaScript kod inte är nödvändigt att ladda först på dessa sidor.


##Rangordning

Rangordna dina webbplatser baserat på deras mätvärden och kommentera resultatet.

##Plats 1:
T-Hotell(1) kommer på första plats då den laddar ungefär lika snabbt och har ungefär samma betyg som Spa Italia Wellness men den totala storleken på sidan är betydligt större så de har redan jobbat mycket med pagespeed och att optimisera deras sida.


##Plats 2:
Spa Italia Wellness(3) får ligga på plats 2 då som jag nämnde ovan så laddades de ungefär lite snabbt och hade ungefär samma betyg, dock hade Spa Italia Wellness bättre betyg men den totala storleken på sidan var betydligt mindre och den borde bara på den aspekten få bättre resultat.


##Plats 3:  

Sardegna Termale (2) lägger jag på sista plats för de hade en liten sida som laddades på kort tid men på tanke på hur liten sidan var och det låga betyget från Google på 24 så hamnar den på sista plats. Det har mycket det kan förbättra på deras sida.



Jag anser att en sida aldrig bör ladda över 3 sekunder. Det skojas mycket om Millenials och generationen Z och hur mycket koncentrationsförmåga dem har. Men skämt och sidor så anser jag att det stämmer.

När man bygger en sida för webben så måste man lägga fokus på vem det är man bygger den till. Min farmor bryr sig inte så mycket om sidan laddas i 5 sekunder, för henne är det snabbt. Men hon köper inte heller alla julklappar till alla hon känner via online butiker eller bokar alla sina resor, biobiljetter osv genom internet.
Både jag och min sambo lämnar en sida innan den har laddat klart om den inte är tillräckligt snabb. Så jag anser att laddningstiden är lika viktigt som vad som finns på sidan, samt layouten.

Jag anser att mina val av sidor ligger lite i överkant för hur snabbt en sida kan laddas. Dock så kom lite av sidan fram ganska snabbt men totala laddningstiden var längre.   









Övrigt
-----------------------
Jag valde dessa sidor just för att jag antog att jag skulle få fram mycket saker att jobba med. Men var fortfarande förvånad över tex utdaterade bildformat osv. Det har gett mig en insikt i världens om vi kommer jobba i.


// Johanna Attefalk
