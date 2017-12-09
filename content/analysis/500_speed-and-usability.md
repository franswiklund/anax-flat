<h1>Utvärdera webbplatser</h1>

<p>Jag har gjort mitt urval baserat på webbplatser som jag själv brukar besöka och därför är intresserad av att veta hur dom presterar i en utvärdering som denna. Vi använder oss alla idag av ganska många olika typer av webbplatser så därför har jag försökt välja tre stycken som enligt mig är väldigt olika.</p>

<p>Den första sidan jag har valt är mitt eget företags <a href="http://studioreko.com">Studio Rekos</a> webbplats som jag av naturliga skäl besöker titt som tätt. Den andra är <a href="http://lagenhetsbyte.se">Lägenhetsbyte</a> där jag spenderar en del tid då jag planerar att flytta och den tredje är <a href="http://svtplay.se">SVT Play</a> som jag ofta använder på fritiden.</p>

<p>För att göra den här utvärderingen möjlig så har jag använt mig att Mozilla Firefox Devtools och Google Pagespeed för att samla in informationen och Google Kalkylark för att sammanställa informationen.</p>

<h2>Studio Reko</h2>

<img src="../htdocs/img/studioreko.png" style="display: inline-block;width: 66%;min-width: 300px;border: 1px solid black">

<h3>Hur webbplatsen presterade</h3>

<h4><a href="http://studioreko.com/project/">Sida 1: Projects</a></h4>
<p>I Pagespeed (Desktop och Mobile): 90/100 och 74/100</p>
<p>I Devtools (snitt): 65 / 1,61mb / 3,513s</p>

<h4><a href="http://studioreko.com/archive/">Sida 2: Archive</a></h4>
<p>I Pagespeed (Desktop och Mobile): 90/100 och 74/100</p>
<p>I Devtools (snitt): 24,3 / 549,6kb / 1,95s</p>

<h4><a href="http://studioreko.com/information/">Sida 3: Information</a></h4>
<p>I Pagespeed (Desktop och Mobile): 90/100 och 74/100</p>
<p>I Devtools (snitt): 25 / 676,3kb / 1,8s</p>

<a href="https://docs.google.com/spreadsheets/d/1zCC_slmWc9eJP0cjLMbMoG92Okd7QhtuvMkKdWoatdg/edit?usp=sharing">Här kan du se alla insamlade värden i mitt kalkylark.</a>

<p>Jag har alltid uppfattat vår hemsida som välbyggd men långsam vilket min undersökning bekräftar. Den får överlag bra betyg i Pagespeed men stora bildfiler försämrar laddningstiden. Att ta en titt på skalbara bilder med CImage är nog ingen dum idé. Vi bör också se över JS/CSS-kod som blockerar rendering och cachelagring.</p>

<h2>Lägenhetsbyte</h2>

<img src="../htdocs/img/lagenhetsbyte.png" style="display: inline-block;width: 66%;min-width: 300px;border: 1px solid black">

<h3>Hur webbplatsen presterade</h3>

<h4><a href="https://www.lagenhetsbyte.se/">Sida 1: Landningssida</a></h4>
<p>I Pagespeed (Desktop och Mobile): 83/100 och 62/100</p>
<p>I Devtools (snitt): 70,3 / 4,48mb / 5,97s</p>

<h4><a href="https://www.lagenhetsbyte.se/Sok">Sida 2: Sök</a></h4>
<p>I Pagespeed (Desktop och Mobile): 83/100 och 62/100</p>
<p>I Devtools (snitt): 70,3 / 4,48mb / 12,77s</p>

<h4><a href="https://www.lagenhetsbyte.se/avtalsassistenten">Sida 3: Avtalsassistenten</a></h4>
<p>I Pagespeed (Desktop och Mobile): 83/100 och 66/100</p>
<p>I Devtools (snitt): 45 / 2,8mb / 3,72s</p>

<a href="https://docs.google.com/spreadsheets/d/1zCC_slmWc9eJP0cjLMbMoG92Okd7QhtuvMkKdWoatdg/edit?usp=sharing">Här kan du se alla insamlade värden i mitt kalkylark.</a>

<p>Sett ur ett användarperspektiv är webbplatsen godkänd men inte mycket mer. Ganska långa laddningstider som irriterar när jag klickar runt mellan sidorna. Behöver ta bort JS/CSS-kod som blockerar rendering av innehåll ovanför mitten.</p>

<h2>SVT Play</h2>

<img src="../htdocs/img/svtplay.png" style="display: inline-block;width: 66%;min-width: 300px;border: 1px solid black">

<h3>Hur webbplatsen presterade</h3>

<h4><a href="https://www.svtplay.se/">Sida 1: Landningssida</a></h4>
<p>I Pagespeed (Desktop och Mobile): 72/100 och 52/100</p>
<p>I Devtools (snitt): 86,3 / 5,67mb / 7,38s</p>

<h4><a href="https://www.svtplay.se/program">Sida 2: Program</a></h4>
<p>I Pagespeed (Desktop och Mobile): 78/100 och 59/100</p>
<p>I Devtools (snitt): 54,6 / 4,78mb / 14,77s</p>

<h4><a href="https://www.svtplay.se/installningar">Sida 3: Inställningar</a></h4>
<p>I Pagespeed (Desktop och Mobile): 75/100 och 55/100</p>
<p>I Devtools (snitt): 46 / 11,41mb / 21,27s</p>

<a href="https://docs.google.com/spreadsheets/d/1zCC_slmWc9eJP0cjLMbMoG92Okd7QhtuvMkKdWoatdg/edit?usp=sharing">Här kan du se alla insamlade värden i mitt kalkylark.</a>

<p>Den här webbplatsen gillar jag vilket gör mig förvånad över deras ljumna betyg i Pagespeed. Att sidorna tar lång tid att ladda färdigt är kanske inte så förvånande med tanke på mängden information som finns på sidorna. Katastrofalt betyg i Mobile kan delvis förklaras av att deras app är mer populär i det lilla formatet men dom bör nog se över den delen oavsett. Ta bort JS/CSS som blockerar redneringen från innehåll ovanför sidans mitt.</p>

<h1>Sammanfattning</h1>

<p>Jag är lite förvånad över resultaten då jag trodde att min egen sida skulle få sämre resultat än dom andra på det mesta eftersom mina två andra exempel är så pass stora webbplatser. De vanligaste förbättringsåtgärderna för mina tre exempel är lite svårt att svara på då sidorna är så olika, men för webbplatser som påminner om min, alltså portfolioliknande sidor som till stor del är bilddrivna så är det nog också i just hur bilder laddas, i vilka format, hur dom skalas och att dom är komprimerade som är den viktigaste förbättringsåtgärden. Om vi pratar lite mer generella förbättringsmöjligheter så kan t.ex. komprimering av HTML-, JS och CSS kod vara en bra idé för att spara plats och hämta in sidan på kortare tid.</p>

<h2>Rangordning</h2>

<p>Sett till Pagespeed så har mitt företag Studio Reko den bästa webbplatsen följd av Lägenhetsbyte på en andraplats och SVT Play på sista plats. Studio Reko ligger bra till i mätningarna från Devtools också men när man tar hänsyn till hur pass mycket mer information som laddas på de andra sidorna så framstår Studio Rekos laddningstider som väldigt långa.</p>

<p>Den största skillnaden tycker jag inte ligger i siffrorna som mätningarna visar utan i hur snabba webbplatserna "verkar" vara. SVT Play känns snabbast för att den viktigaste informationen dyker upp på skärmen direkt även om den sedan fortsätter ladda ett tag under ytan medan både Studio Reko och Lägenhetsbyte framstår som långsamma för att skärmen ekar tom en liten stund under laddningen. Jag tror att det vore smart att se till att saker börjar visas på sidan innan all tung information har laddats klart så att webbplatsen framstår som snabbare.</p>

<h2>Gräns för absolut laddningstid</h2>

<p>Enligt mig så bör en sida inte ta längre än 1-2 sekunder att ladda till den grad att besökaren kan börja använda den. Sen får den gärna fortsätta ladda ned nödvändig information i bakgrunden eller begränsa vad jag som besökare kan göra på sidan ytterligare 1-2 sekunder utan att det blir allt för irriterande. Det viktigaste är att jag inte sitter och tittar på ett helt tomt vitt fönster allt för länge.</p>
