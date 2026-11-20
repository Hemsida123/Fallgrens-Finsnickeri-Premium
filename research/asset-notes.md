# Originalbilder – Fällgrens Finsnickeri

Källor hämtade 20 november 2026 via offentlig HTTPS med normal certifikatkontroll. Originalwebbplatsen fungerar med direkt hämtning, även när en sök-/webbrenderare får timeout. Sju originalsidor och det offentliga WordPress-bildregistret granskades för att hitta exakt använda bilder. Sidkopiorna finns tillfälligt i /private/tmp/fallgrens-*.html; källagenten för fakta bevarar avsedda sidkopior i research/pages.

## Levererade filer

31 filer: företagets logotyp, verkliga arbets-/verkstads-/produktbilder, nio ursprungliga galleri-/casebilder, åtta produktposter som använder sju olika produktbilder, samt tre separat märkta campervan-illustrationer från originalsidan. Bilderna har bara EXIF-orienterats, skalats proportionellt och komprimerats till AVIF/lossless WebP. Inga element har genererats, bytts eller retuscherats. Alla original- och leveranshashar, dimensioner, källsidor och WordPress-ID finns i research/assets.json.

## Hero och person

Huvudhero är WordPress-bild1466, ett verkligt svartvitt foto av arbete i verkstaden. About-bild1504 visar samma person i en annan arbetssituation. Porträtt1505 är originalets bild intill avsnittet om Fredrik Fällgren på /om-mig/, vilket ger personkopplingen. Ingen ny fotograferingsplats, dag eller projektkund anges. Alternativ hero1525 visar en terrass i kvällsljus från samma offentliga företagsarkiv, utan att bindas till ett nytt namngivet projekt. Övriga arkivbilder har neutrala beskrivningar och skiljs från uttryckliga kundcase.

## Nio exakta bild-/textpar

Sex poster anges uttryckligen som Kundcase på /byggservice/ och /specialsnickerier/:

| Titel | Originalets beskrivning | Bild-ID |
|---|---|---|
| Byggnation av brygga | Planering och byggnation av brygga |1442|
| Byggnation av trall | Byggnation av trall och nedsänkning av spabad |1444|
| Kök | Installation av kök |1573|
| Köksinredning | Byggnation och design av kök |1476|
| Förvaring sovrum | Platsbyggd förvaring i sovrum |1475|
| Platsbyggda köksskåp | Platsbyggda köksskåp |1553|

Tre ytterligare bildposter på /mobler-inredning/ heter Stol, Skåp och Skärbräda. De har respektive bild-ID1313,1280,1320. Originalets titel och text hämtades från samma Elementor-kolumn som bilden. Ingen annan vinkel har grupperats ihop med en post. Formuleringen ”nio arbeten” är bredare och mer korrekt än att kalla alla nio för namngivna kundcase.

Originalet återanvänder beskrivningen ”Platsbyggd förvaring i sovrum” för Skåp, trots en frilagd bild av ett fristående skåp. Exakt källtext ligger i source_caption. En neutral publik beskrivning som ”Skåp i trä med skjutdörrar” följer det som faktiskt syns och undviker ett nytt påstående om rummets placering. Det verkliga sovrumscaset1475 är en annan bild.

## Åtta produktposter

Korrekt titel-/bildpar från /shop/: Pokerset, Presentförpackning, Skärbräda, Serveringsbräda, Serveringsbräda small, Serveringsbräda medium, Stol och Klubba. Small och medium använder exakt samma bild i originalet, vilket har behållits och dokumenterats. Produktposter är inga nya kundcase och inga priser, lagersaldon eller leveransvillkor har lagts in i bildmetadata. Den frilagda produktstolen1310 är ett annat originalfoto än galleristolen1313; bilderna blandas inte ihop till en påhittad fotogrupp.

## Campervan Haven – illustrationer

De tre bilderna från /elementor-1746/ har filnamn som pekar på tredje parters campervan-miljöer (Boho/Camplify), inte dokumenterade Fällgrens-arbeten. De levereras som media.camper och camperIllustrations med provenance_type original-site-third-party-inspiration-not-customer-project och tydlig bildtext. De får användas som märkta inspirationsbilder men inte som företagets egna kundprojekt. De ingår aldrig i media.works eller media.images. Det finns inga tillverkade nya campervan-projekt eller kundberättelser i paketet.

## Logotyp

Originalet Fallgrens_logga_farg_v2.png är redan RGBA med transparent bakgrund. Endast den befintliga transparenta ytterkanten beskars, och formen skalades med lossless WebP. Gulbrun sköld, svart text, ornament och EST2020 är ursprungliga bildpixlar. Inget bakgrundsbyte, ingen ny färg eller rekonstruktion av bokstäver. Använd utan färgfilter om originalets profil ska behållas.

## Visuell granskning

Originalkontaktskarta och qa/contact-sheet.jpg över alla levererade filer granskades: alla nio galleriobjekt och alla produktpar stämmer med sina källkolumner. Porträttet är rätt personkontext. Verkliga projektnamn, bilder och generiska illustrationer hålls isär. Huvudheron har tillräcklig upplösning för fullskärmsvisning och en genuin verkstadsmiljö. Tre camperbilder är uttryckligen avskilda från företagets arbeten. qa/verify_assets.py kontrollerar hash, dimensioner, avkodning, befintlig logo-alfa och alla exakta ID-/produktparningar.
