# Fällgrens Finsnickeri – premium-redesign

Öppna index.html i en modern webbläsare. Bilder, typsnitt, stilar och funktioner ingår. Ingen installation behövs. Redigerbar.html är samma webbplats med separata assets- och fonts-mappar; behåll dem bredvid filen. Alla vyer nås genom navigationen. Äldre sidnamn omdirigeras i ZIP-paketet.

## Innehåll
Fullskärmshero med verklig verkstadsbild och transparent originallogotyp. Fyra tjänster inklusive Campervan Haven, nio källverifierade galleri-/arbetsposter med egna vyer, åtta produkter med egna produktsidor, fungerande förfrågningslista, personpresentation, arbetssätt, FAQ, kontakt och offertutkast. Mobilanpassning, färgtema, tangentbordsstöd och reducerad rörelse. Designed by Ekom länkar till ekom.se.

## Förfrågan och produkter
Formulären förbereder mejlutkast till fredrik@fallgrens.se. Besökaren granskar, bifogar underlag och skickar själv. Ingen server, automatisk sändning, betalning, beställning, bokning eller reservation sker. Telefonnummer är frivilligt. Förfrågningslistan kan samla produkter, ändra antal och ta bort dem. Den skickas som en del av det mejlutkast besökaren väljer att förbereda. Ett direkt köp kan göras i den länkade originalwebbshoppen på dess aktuella villkor.

Text och lista behålls endast inom den öppna sidan och rensas vid omladdning. Ingen lokal lagring, analys, spårning, reklam, kartinbäddning eller annan automatisk nätverkssändning används. Kopiering är besökarens uttryckliga handling och har en alternativ textinstruktion om webbläsaren inte tillåter urklipp. Integritetstexten behöver uppdateras om någon senare ansluter betalning, formulärserver eller lagring.

## Källor och begränsningar
Företagsuppgifter och innehåll kommer från fallgrens.se. Det publika verksamhetsnamnet är Fällgrens Finsnickeri och personen är Fredrik Fällgren. Enskild firma: ingen AB-form eller personligt organisationsnummer publiceras. Postnummer38891 följer kontaktsidan och stödregister; motstridig gammal footer38894 förs inte över. Inga nya sociala användarnamn skapas från den otydliga numeriska Instagramlänken.

Nio verkliga bild/textpar från tjänstesidorna redovisas som arbeten: sex uttryckliga kundcase och tre möbel-/produktgalleriposter. En bild per post; inga extra vinklar, klientnamn, projektorter eller datum påhittas. Källans Skåp-bildtext talar om sovrumsförvaring trots en bild av ett fristående skåp. Visningen använder en neutral beskrivning av skåpet; den verkliga sovrumsförvaringen är en separat källpost. Produkt small och medium delar samma fotografi i originalet och gör det även här.

Campervan Haven är ett verkstads-/planeringskoncept. Inspirationsbilder från originalets Campervan-sida är uttryckligen märkta och presenteras inte som egna kundprojekt. Odaterade avgifter, tidslöften, avtal, försäkrings- och behörighetsuppgifter kopieras inte som aktuella villkor. Ingen verkstadsplats bokas via formuläret.

Originalbutiken har pris- och lagerobservationer som skiljer sig i synlig text och JSON-LD. Dessa finns dokumenterade i källmetadata men visas inte som nya erbjudanden eller lagersaldon. Aktuellt pris, utförande och tillgänglighet bekräftas i originalbutiken eller med Fredrik. Inga osäkra måttenheter läggs till produktuppgifter.

Källor och avgränsningar: research/SOURCES.md och facts.json. Bildfiler, originaladresser, dimensioner och SHA256 finns i bildkallor.json och research/assets.json. Logotypen hade befintlig transparens; endast befintliga alfamarginaler beskars och den skalades. Inga genererade bilder, falska recensioner, garantier eller gratis offertlöften.

## Redigera och kontrollera
Källor: qa/template.html, qa/site.css, qa/site.js, qa/content.json och research/media.json. Med Python3, BeautifulSoup och Node kan du bygga om via python3 qa/build.py och kontrollera via python3 qa/verify.py. Hash-navigation används för fristående fil; titlar och beskrivningar byts vid navigation. Lösningen är ingen serverrenderad flersidesbutik för sökmotorindexering.

Bitter och DM Sans från Google Fonts. SIL Open Font-licenser finns i fonts, källor och filhashar i typsnitt.json. Kod, alla vyer och länkar, inbäddade bilder/typsnitt, Ekom-länk, företagsuppgifter, metadata, ZIP CRC och exakt filinnehåll kontrolleras. Verklig mobil-/datorgranskning och interaktionstest utförs i lokal webbläsare. Mejllänkar granskas utan sändning, ingen mejlklient öppnas och inget beställs. Native filöppning automatiseras inte. Webbplatsen är inte publicerad och ersätter inte originalet.

Slutkontroll: 32 vyer i fem skärmbredder för den redigerbara versionen (160 kontroller) och samtliga 32 fristående vyer i mobilbredd. Heron har dessutom kontrollerats i åtta skärmformat, inklusive kort liggande skärm. Inget horisontellt överflöde, trasiga färdigladdade bilder eller konsolfel hittades. Meny, bildvisare, filtrering, sökning, FAQ, färgtema, formulärvalidering, antal/ta bort i förfrågningslistan, mejlutkast och kopiering har provats. En medvetet felaktig provfil med ett externt skript avvisades av kontrollen. Skärmbilder och testunderlag ligger i projektets qa-mapp.
