# Källor och avgränsningar

Kontrollerat20november2026. Aktuell originalwebbplats kunde hämtas direkt via offentlig HTTPS, även när webbläsningsverktygets första hämtning gav timeout. Inga certifikatundantag, inloggningar eller privata API:er användes. Alla kundtexter i qa/content.json är omskrivna.

## Företagets originalwebbplats

- [Startsida](https://fallgrens.se/): Fällgrens Finsnickeri, småskalig produktion, byggservice, specialsnickerier, möbler och inredning, länk till CampervanHaven och webbshop.
- [Byggservice](https://fallgrens.se/byggservice/): nybyggnad, tillbyggnad, renoveringar, tak/fönster/kök/golv, byggservice för privatpersoner och företag. Här finns tre källa-märkta kundcase med rubriker för brygga, trall och kök. Redesignen återger inga ROT-satser, avdragsbedömningar eller garantiutfästelser.
- [Specialsnickerier](https://fallgrens.se/specialsnickerier/): ritningar, projektering, val av träslag och utförande; bland annat diskar, garderober, skåp, bord, bänkar, kontors-/butiksinredning och utställningsmontrar. Tre ursprungliga casekort med köks-/förvaringsrubriker. Specialarbetens pris sätts individuellt.
- [Möbler & inredning](https://fallgrens.se/mobler-inredning/): kundanpassad tillverkning av möbler, kök, garderober, skärbrädor, badrumsinredning och detaljer. Tre originalkort om stol, skåp och skärbräda. Dessa kort behandlas som faktiska originalpresentationer; inga nya kundnamn, platser, budgetar eller byggår läggs till.
- [Om mig](https://fallgrens.se/om-mig/): Fredrik Fällgren driver verksamheten i Kalmar län och anger utbildning vid TibroHantverksakademi. Detta är en självrapporterad yrkesbakgrund. Inga examensår, yrkesbevis eller ytterligare certifieringar påstås.
- [Kontakt](https://fallgrens.se/kontakt/): FredrikFällgren,076-1735608,fredrik@fallgrens.se,Kulltorp122,38891Vassmolösa. Sidan har inget faktiskt kontaktformulär i sin levererade HTML; redesignens förfrågningsformulär är en ny lokal mejlutkastfunktion.
- [CampervanHaven](https://fallgrens.se/elementor-1746/): det exakta gamla sidnamnet är elementor-1746. Konceptet omfattar planering, verkstadsplats, verktyg, material och diskussion om vilken hjälp kunden vill ha. Källans odaterade priser, boknings-/tidsexempel, försäkrings-/ansvarstexter och detaljerade arbetsmoment återpubliceras inte som nya aktuella villkor. Besökaren får kontakta Fredrik för aktuell tillgång och överenskommelse. Ingen bokning eller betalning genomförs i den lokala filen.
- [Shop](https://fallgrens.se/shop/): åtta verkliga produkter. Originalets köp-/betalflöde är kvar på originalwebbplatsen. Redesignens produktlista är en katalog och förfrågningslista, inte en ny kassa.

Dessa åtta originalsidor samt samtliga åtta produktsidor är sparade i research/pages. Manifestet innehåller källadress, kontrolltidpunkt, byteantal och SHA256.

## Produktkatalogen

Exakta ursprungliga namn och slugs:

- [Pokerset](https://fallgrens.se/produkt/pokerset/)
- [Presentförpackning](https://fallgrens.se/produkt/presentforpackning/)
- [Skärbräda](https://fallgrens.se/produkt/skarbrada/)
- [Serveringsbräda](https://fallgrens.se/produkt/serveringsbrada/)
- [Serveringsbräda small](https://fallgrens.se/produkt/serveringsbrada-small/)
- [Serveringsbräda medium](https://fallgrens.se/produkt/serveringsbrada-medium/)
- [Stol](https://fallgrens.se/produkt/stol/)
- [Klubba](https://fallgrens.se/produkt/klubba/)

Produktmetadata i qa/content.json innehåller källans observerade priser och synliga lagermarkeringar, med publish_price/publish_stock=false. Observationen är inte ett nytt pris- eller lagerlöfte. Priserna är2995/400/850/900/550/700/11995/995kr inklusive moms i ordningen ovan. Pokerset och Stol kallas Beställningsvara i den synliga texten, samtidigt som WooCommerceJSON-LD säger InStock för alla åtta. Dessa motstridiga uppgifter blir inte nya lagersaldon. JSON-LD:s validUntil2027 är mallmetadata, inte en självständig bekräftelse på framtida pris eller tillgång.

Serveringsbrädornas källtext har storlekar110×25,15×25 och40×25, men ingen explicit måttenhet. Ingen ny enhet antas. Materialart, livsmedelscertifiering, ytbehandling eller tekniska garantier hittas inte på. Lasergravyr nämns enligt de faktiska källbeskrivningarna för presentförpackning och skärbräda; inget nytt gratiserbjudande läggs till.

Produktbilder, case-/bildparningar, samma bild för small/medium och Campervanillustrationernas ursprung dokumenteras av bildinventeringen i research/assets.json och asset-notes.md. Den fristående produktbilden på Stol och tjänstesidans stolbild är olika ursprungliga vyer; dessa behöver inte marknadsföras som ett nyuppfunnet projekt.

## Företagsidentitet och postnummer

[Ratsit: Fällgren,Fredrik](https://www.ratsit.se/940314CQSZ-Fallgren%2C_Fredrik) identifierar enskild näringsidkare med samma telefon och Kulltorp122,38891Vassmolösa. [Bolagsfaktas sökresultat](https://www.bolagsfakta.se/940314CQSZ-Fallgren%2C_Fredrik) och [Hittas adressuppgift](https://www.hitta.se/kalmar%2Bl%C3%A4n/vassmol%C3%B6sa/kulltorp%2B122/omr%C3%A5de/56.591846%3A16.126629) stödjer38891. Sidornas visade stödtext lästes med webbläsningsverktyget; de är inte redovisade som sparade primärHTML-filer.

Det publika verksamhetsnamnet är **Fällgrens Finsnickeri**. Registerbenämningen är **Fällgren,Fredrik**, enskild näringsverksamhet. Verksamheten kallas inte AB. Inget personligt organisationsnummer, födelsedatum eller annan privat bakgrund förs över till kundsidorna.

Originalets footer skriver38894, medan den särskilda kontaktsidan anger38891. Kontaktsidan plus oberoende adress-/företagsuppgifter väger tyngre. Redesignen använder därför **38891Vassmolösa**. Adressen är den som företaget självt publicerar som kontaktadress; ett öppet showroom eller fria drop-inbesök påstås inte.

## Sociala länkar

Originalets Instagramfeed länkar till https://www.instagram.com/17841408654880543/ , ett numeriskt konto-id. Ett normalt publikt användarnamn har inte verifierats. Inget nytt @fallgrens-profilnamn eller Facebookkonto konstrueras. En neutral länk till originalwebbplatsen kan användas om besökaren vill följa originalets egna kanaler.

## Medvetna avgränsningar

- Inga fabricerade omdömen, stjärnor, kundantal, case, datum, material, priser, garantier eller svarstider.
- Inget påstående om personlig elauktorisation, certifierat elföretag eller att bolaget själv utför allt elarbete som nämns i Campervankonceptet. Yrkesinsatser och tillgång stäms av för projektet.
- Inga rättsliga/skattetekniska råd, avdragssatser eller DIY-instruktioner för el-/fordons-/byggnadsarbete.
- Processen beskriver hur kunden lämnar underlag och stämmer av ett uppdrag, inte ett nytt leverans- eller tidsgarantilöfte.
- Ingen kostnadsfri offert påstås; originalet erbjuder individuellt pris men använder inte ett tydligt gratislöfte.
- Katalog-/förfrågningslistan är lokal och skapar inget köp. Direkta köp ska länkas till originalshoppen och dess aktuella villkor.

## Formulär och integritet

Den levererade filen ska endast förbereda mejlutkast till fredrik@fallgrens.se. Besökaren granskar, bifogar eventuellt underlag och skickar själv. Ingen automatisk sändning, beställning, bokning, betalning eller mottagningsbekräftelse finns. Formulärtext och förfrågningslista finns i den öppna sidans minne, utan localStorage/sessionStorage, analys eller externa inbäddningar. Integritetstexten behöver anpassas om ett serverbaserat formulär eller annan lagring senare ansluts.
