Webbplatsers laddningstid och användarbarhet
=======================
><a href="01_colors" class="show"><i class="fas fa-arrow-left"></i> Föregående</a> <a href="03_design_principles" class="show">Nästa <i class="fas fa-arrow-right"></i> </a>

I denna rapport analyseras och jämförs tre olika webbplatsers laddningstid och användarbarhet.

Urval
-----------------------

Urvalet för den aktuella analysen är tre olika webbplatser med fokus på deras laddningstid. Dessa tre sidor kommer analyseras för att se vad som eventuellt kan förbättras för att få en snabbare och mer effektiv sida.
Webbplasterna som kommer analyseras är <a href="https://www.vaningen.se/" class="show-analysis">Vaningen.se</a>, <a href="https://www.bjurfors.se/" class="show-analysis">Bjurfors.se</a> och <a href="https://www.svenskfast.se/" class="show-analysis">Svenskfast.se</a>.
Urvalet föll på tre olika mäklare som alla har mycket bilder och hög omsättning av bilder. Detta för att analysera vilken eller vilka sidor som använder sig av bäst teknik och bildformat i sina presentationer. Det är deras första landningssida som kommer analyseras i denna rapport.

Metod
-----------------------

För att göra undersökningen så har webbplatsernas värde testas med hjälp av webbläsaren Chromes Network verktyg under Devtools, detta utan cache. Webbplatserna har även testat sin laddningstid med hjälp av hemsidan <a href="https://developers.google.com/speed/pagespeed/insights/" class="show-analysis">PageSpeed Insights</a>.

Resultat
-----------------------
>Här finns ett <a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vReTeApS5N3eQynCSlKWcTNejed81lCngMEN6oquSNR2FXjwV1n5VChXMTJFO1sRBiEkJl9ZojHS5Jw/pubhtml?gid=0&single=true" class="show-analysis">Excelark</a> med en sammanställning av webbplatsernas värde.

><p class="small-header" ><a href="https://www.vaningen.se/" class="show-analysis">Vaningen.se:</a></p>
![vaningen](%assets_url%/img/analysis-loading/vaningen1.png)

>Våningen och villans webbplats får ett genomsnittsbetyg för desktop på 65,67 och för mobila enheter 15,33. Webbplatsens totala storlek var 22,67 MB och laddningstiden var 5,89 sekunder. Antalet resurser som laddades in var 107 stycken. 

>Webbplatsens största tid och storleksbov är dess bilder som man hade kunnat komprimera för att göra sidan mer effektiv. Det finns även bilder som försöker laddas in men som inte kan lokaliseras, det påverkar laddningstiden negativt i detta fall. Enligt PageSpeed Insights rekommenderas man att koda bilderna mer effektivt och undvika tomma resurser som laddas in. 

><p class="small-header" ><a href="https://www.bjurfors.se/" class="show-analysis">Bjurfors.se:</a></p>
![bjurfors](%assets_url%/img/analysis-loading/bjurfors1.png)

>Bjurfors webbplats får ett genomsnittsbetyg för desktop på 44,33 och för mobila enheter 14,33. Webbplatsens totala storlek var 10 MB och laddningstiden var 6,52 sekunder. Antalet resurser som laddades in var 222 stycken. 

>Enligt PageSpeed Insight finns det tid att spara vid ladding av viktiga resurser. Det är på Bjurfors hemsida framförallt typsnittet som man kunnat ladda in i förväg alternativt ändra typsnitt till något typsnitt som finns förinstallerat på de flesta datorer och mobilia enheter. Eftersomd det är bilderna på hemsidan som ska visa upp objekten så kan man välja att använda sig av ett typsnitt som laddas in fort. 

><p class="small-header" ><a href="https://www.svenskfast.se/" class="show-analysis">Svenskfast.se:</a></p>
![svenskfast](%assets_url%/img/analysis-loading/svenskfast1.png)

>Svensk fastighetsförmedlings webbplats får ett genomsnittsbetyg för desktop på 82,33 och för mobila enheter 29,33. Webbplatsens totala storlek var 3,6 MB och laddningstiden var 4,46 sekunder. Antalet resurser som laddades in var 93 stycken. 

>Svensk fastighetsförmedling kan förbättra sin sida genom att ändra i ordningen av hur de läser in sina resurser, js-kod som är mindre viktig för sidans funktionalitet och utseende hade man kunnat ladda in senare för att snabbar visa upp sin huvudbild och fånga intresse hos läsaren.

Analys
-----------------------

>Det var stor skillnad på antalet resurser, storlek och laddningstid de olika mäklarwebbplatserna hade. Den vanligaste förbättringsåtgärden på dessa sidor är komprimering av deras bilder. Alla hemsidor har väldigt många bilder som ska laddas in och då är det extra viktigt att man optimerar flödet så mycket som möjligt genom att välja rätt filtyp och storlek på bilderna som ska visas upp. PageSpeed Insights ger som tips till alla sidor att de bör ladda in sina resurser i ett mer optimerat flöde, där är det framförallt JS/CSS-koden som det anses att det finns tid att spara. Det är förståeligt då det är mycket av den koden för att få en webbplats till att se bra och proffsug ut med många olika bilder. 

><a href="https://www.svenskfast.se/" class="show-analysis">Svenskfast.se</a> är den sidan som klarat testerna bäst och kommer därmed först i min rangordning. Detta för att webbplatsen är överlagset snabbast på att ladda in samt använder minst resurser och har minst totala storlek. Trots det så ser den minst lika proffsig ut som de övriga och är vädligt användarvänlig eftersom den laddar in nya sidor och innehåll väldigt snabbt. 

>Två blir <a href="https://www.vaningen.se/" class="show-analysis">Vaningen.se</a>, webbplatsen klarade sig näst bäst i genomsnitt på alla mätinstanser men når inte topplaceringen eftersom <a href="https://www.vaningen.se/" class="show-analysis">Vaningen.se</a> är den webbplats som har mest tid att spara genom att optimera sitt bildflöde. Enligt PageSpeed Insights finns det stor förbättringspotential i koden när det kommer till bildhanteringen. Då bilderna är en så pass viktig del av sidan är det intressant att man inte har optimerat bildflödet mer. 

>Längst ner på listan kommer <a href="https://www.bjurfors.se/" class="show-analysis">Bjurfors.se</a>, webbplatsen är sämst i alla mätinstanser och tar därmed även längst tid att ladda in. Nästan hela landningssidan är en enda stor bild som man inte ser förren efter ett par sekunder på sidan. Då får man genast ett intryck av att webbplatsen är långsam och det är lätt att man drar sig från att klicka sig vidare. Här hade man kunnat tänka om och välja fler mindre bilder med lägre kvalitet på första sidan för att sedan när man fångat läsarens intresse och den klickat sig vidare kunnat visa upp sina stora bilder med hög kvalitet. 

>Jag anser att gränsen för absolut laddningstid är runt 2 sekunder. Detta är för att man då snabbt kan visa upp det man vill innan läsaren väljer att lämna sidan. Om det tar längre tid så får man lätt känslan av att hela webbplatsen är långsam och det kommer ta tid att klicka sig runt. I urvalet av webbplaster som varit aktuella för denna rapport är samtiliga långt ifrån mitt gränsvärde. Det var relativt väntat då urvalet är baserat på webbplatser som innehåller mycket bilder. Trots detta så anser jag att både Svensk fastighetsförmedling och Våningen & Villan ger ett snabbare intryck än vad mätdatan säger. Man reagerar inte så mycket på att det tar någon sekund extra eftersom man förväntar sig bra och stora bilder på webbplatsen.

Referenser
-----------------------

<a href="https://www.svenskfast.se/" class="show-analysis">Svenskfast.se</a>
<a href="https://www.vaningen.se/" class="show-analysis">Vaningen.se</a>
<a href="https://www.bjurfors.se/" class="show-analysis">Bjurfors.se</a>
<a href="https://developers.google.com/speed/pagespeed/insights/" class="show-analysis">PageSpeed Insights</a>
<a href="https://dbwebb.se/kurser/design-v3/kmom05" class="show-analysis">DbWebb</a>

Övrigt
-----------------------

Skriven och analyserat av: Frans Nordqvist (frnr20)