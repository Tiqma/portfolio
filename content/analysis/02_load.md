Analys
=======================

Här kommer vi analysera olika laddningstider för tre olika hemsidor.

Urval
-----------------------

Jag valde att använda mig utav samma tre webbsidor som jag hade valt i analysdel 1. De har inte mycket gemensamt vilket gör för ett intressant analys av vad olika webbsidor försöker åstadkomma.

Metod
-----------------------
Jag har använt mig utav https://pagespeed.web.dev/ för att räkna ut sidors prestanda.

Jag har även använt mig utav devtools för att kunna räkna ut sidors laddningstider och hur mycket data som skickas.

Google kalkylblad har använts för att presentera den data jag har tagit fram.

Resultat:
-----------------------

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSMho6-vNzLRt4RP_vPijtd0yDuD9Vz4PFtJLjqMMogIBFT3fmR7cechw1GDy9x6xRx27bl606sprbd/pubhtml?widget=true&amp;headers=false" width="750" height="200"></iframe>

Twitter
-----------------------
<img src="../image/twitter.PNG" alt="Twitter" class="twitter">

Twitter uppdaterar sitt flöde hela tiden och vilken media som helst kan dyka upp som förändrar laddningstiden och resurser.

1177
-----------------------
<img src="../image/1177.PNG" alt="elva" class="elva">

Har inga större problem med sin laddningstid och har ganska simpla medier.

Polisen
-----------------------
<img src="../image/polis.PNG" alt="polis" class="polis">

Polisens hemsida är klart snabbast, men också mest simpel i design.

Analys
-----------------------

Polisen har en väldigt lättviktig design och deras bilder tar inget utrymme. Den minimalistiska layouten och optimerade bildhanteringen har resulterat i nästan perfekta resultat i både mobil- och laptop-prestandatester, där de nästan uppnådde 100 i båda testerna.. Kan inte säga att de kan förbättra sin sida något mer.

1177 håller också bra standard när det kommer till performance, men faller lite kort när det gäller mobilsidan. De kanske ska kolla till att förminska sina filstorlekar och optimera den responsiva designen för att uppnå detta. 1177 har både dubbelt så mycket laddningstid och resurser jämfört med polisen.

Twitter har desto mer problem, men jag ska kasta dem ett ben till en början och ge omtanke till algoritmen som kan leverera både videor och bilder i vilken upplösning och storlek som helst.. Vad som dyker upp i ens flöde kommer troligtvis förändra prestandan och laddningstiden. Man hade kanske kunnat förbättra det genom att sätta en maxstorlek på bilder och videor tills att man tryckt in sig på mediet. Dock så har den samma laddningstid som 1177 och samtidigt har nästan 5 gånger så mycket resurser, vilket är en bra optimering. Deras prestanda på mobila enheter var endast 38, troligen på grund av att de fokuserar huvudsakligen på att optimera sin app, vilket resulterar i försummad prestanda för den mobila webbplatsen.

Den vanligaste förbättringsåtgärden skulle nog vara att fixa repsonsiviteten och göra bilderna så små i storlek som möjligt.

Min gräns för absolut laddningstid skulle nog ligga på en sekund. Efter det känns det långsamt. Twitter är svår att säga eftersom den hela tiden uppdaterar sig själv och inte ger någon klar laddningstid. För polisen och 1177 så klarar de det galant.

Skriven av:
-----------------------
Tim Swärd