# Toetsing van het Gemini-onderzoek

**Getoetst op:** 11 november 2026.
**Bron:** het Gemini Deep Research-rapport "Geschiktheid van Signhost voor Digitale Zorgcontractering" (20 pagina's, 74 bronvermeldingen). Het volledige rapport hoort lokaal in `invoer/vertrouwelijk/` en staat niet in deze openbare repository.

Dit document vat samen wat Gemini concludeert en legt vast welke dragende beweringen bij controle aan de oorspronkelijke bron standhouden. De bron-ID's verwijzen naar [Bronnen en bevindingen](bronnen-en-bevindingen.md).

## Uitkomst in het kort

Het rapport is bruikbaar als denkkader en als opzet voor werkroute, pilot en video. Het is niet bruikbaar als onderbouwing van een besluit: vier beweringen waarop het oordeel rust, kloppen niet of zijn niet terug te vinden in de opgegeven bron.

| Bewering van Gemini | Uitkomst van de controle | Gevolg |
| --- | --- | --- |
| De SVB schrijft bij papieren pgb-formulieren voor: "Zet de handtekening met pen. Een digitale handtekening is niet toegestaan." Signhost is daarom "volledig ongeschikt" voor pgb. | **Niet bevestigd.** Het citaat staat niet op de opgegeven pagina (SRC-05). Het actuele SVB-formulier "Zorgovereenkomst met een zorginstelling", versie 2026, zegt: "Onderteken de overeenkomst met pen of gebruik de ondertekenfunctie van het programma Adobe Acrobat Reader. De getypte handtekening is niet toegestaan." (SRC-06) | Het oordeel "volledig ongeschikt" vervalt. Of de SVB een via Signhost getekende pdf van het voorgeschreven formulier accepteert, is onbekend en moet aan de SVB of de verstrekker worden gevraagd. Het PGB Portaal blijft de standaardroute. |
| Sms-code levert een geavanceerde handtekening (AES) op en is "in de jurisprudentie meermaals bevestigd" als voldoende. | **Niet bevestigd, deels in tegenspraak met de leverancier.** Signhost deelt sms zelf in bij "eenvoudige verificaties", samen met krabbel en iDEAL. iDIN, DigiD en itsme Identification staan bij "geavanceerde verificaties" (SRC-08). De genoemde rechtspraak is niet met vindplaats onderbouwd. | De standaardkeuze "zorgcontract = sms" is niet onderbouwd. Welk eIDAS-niveau een route oplevert, moet Signhost schriftelijk bevestigen. |
| Entrust schakelt Amazon Web Services en Dizzydata in als subverwerkers; verwerking binnen de EER. | **Onjuist.** De opgegeven verwerkersovereenkomst (entrust.nl) is van een administratiekantoor met de naam Entrust in Apeldoorn, KvK 76824195, met subverwerkers als Twinfield, Yuki en Nmbrs. Dit is niet de leverancier van Signhost (SRC-12). | Over subverwerkers en verwerkingslocaties van Signhost is nog niets vastgesteld. Opvragen bij Signhost. |
| De bewaartermijn in Signhost is instelbaar; advies is 30 dagen of korter. | **Niet bevestigd.** Volgens de helppagina zijn getekende documenten standaard maximaal 30 dagen te downloaden en worden persoonsgegevens 90 dagen na een eindstatus geanonimiseerd. Een eigen instelling wordt niet beschreven (SRC-09). | Het risico ligt andersom: wie niet binnen 30 dagen downloadt, kan het document mogelijk niet meer ophalen. Dit hoort in de werkinstructie en de pilot. |

## Overige beweringen

### Bevestigd aan de bron

- **Artikel 3:15a BW.** Een gekwalificeerde handtekening heeft dezelfde rechtsgevolgen als een handgeschreven handtekening. Voor andere elektronische handtekeningen geldt dat alleen als de methode voldoende betrouwbaar is, gelet op het doel en de omstandigheden (SRC-13, tekst geldend vanaf 1 juli 2025).
- **HR 14 juni 2019, ECLI:NL:HR:2019:957.** De uitspraak bestaat. Zij gaat over de geneeskundige verklaring onder de Wet Bopz: daar moet een elektronische handtekening geavanceerd of gekwalificeerd zijn (SRC-14, via samenvattingen; rechtspraak.nl was niet bereikbaar). Gemini trekt dit door naar WGBO-toestemming en zorgcontracten. Die stap is een eigen gevolgtrekking van Gemini, geen inhoud van de uitspraak.
- **PGB Portaal.** Ondertekening in het portaal verloopt via inloggen met DigiD, VECOZO of eHerkenning; eerst de zorgverlener, dan de budgethouder (SRC-05).
- **Prijzen.** Start €99, Basic €297 en Plus €594 per jaar, met 100, 300 en 600 credits en 1, 2 en 4 gebruikers. Dit volgt uit zoekresultaten die de Entrust-prijspagina weergeven; de pagina zelf was niet rechtstreeks te openen (SRC-11). Oudere vergelijkingssites noemen €90, €270 en €540.
- **Gekwalificeerde routes bestaan.** Signhost noemt Signhost QES, itsme Qualified en ZealiD, alle "via CSC Qualified" (SRC-08).

### Onnauwkeurig

- **Creditkosten.** Gemini: sms is "1 credit plus meerkosten" en iDIN "plus 1 credit". De helppagina van 15 april 2026: 1 ondertekenverzoek is 1 credit inclusief twee handtekeningen, elke extra handtekening 0,5 credit, sms 0,2 credit, en in het rekenvoorbeeld 1 credit per ondertekenaar voor iDIN (SRC-10).
- **DigiD.** Gemini noemt DigiD niet als beperking. Signhost vermeldt dat DigiD alleen beschikbaar is voor (semi)overheidsinstanties en dat iDIN alleen werkt met particuliere rekeningen (SRC-08).
- **DPIA.** Gemini noemt een DPIA "onontkoombaar" en "wettelijk verplicht". Een DPIA ligt voor de hand bij gezondheidsgegevens van kwetsbare personen, maar de plicht hangt af van schaal en inrichting. Dat is een beoordeling voor de functionaris gegevensbescherming of privacyverantwoordelijke, geen vaststaand feit.
- **Bewaartermijnen.** Gemini noemt 20 jaar (WGBO) en 7 jaar (fiscaal) als algemene termijnen. De opdracht vroeg juist om geen universele termijn te geven. Voor Wmo- en Jeugdwet-dossiers gelden eigen wettelijke termijnen. Per documentsoort vaststellen; in deze ronde zijn de wetsartikelen niet nagelopen.
- **"KNMP-richtlijnen"** als bron voor machtigingen tot gegevensuitwisseling. De KNMP is de beroepsorganisatie van apothekers; de relevantie voor deze organisatie is niet onderbouwd.

### Niet gecontroleerd of niet te controleren

- **Signhost als gekwalificeerde vertrouwensdienstverlener (QTSP) op de EU Trusted List, met een gekwalificeerd zegel op elk document.** Gemini verwijst alleen naar een statistiekpagina. De helppagina zegt slechts dat het certificaat is uitgegeven door "een erkende Certificate Authority, waar Signhost bij is aangesloten" (SRC-08). Welke entiteit welke gekwalificeerde dienst levert, moet Signhost aantonen.
- **PAdES met LTV en een gekwalificeerd tijdstempel.** De bronnen van Gemini zijn documentatie van Syncfusion en Docusign, niet van Signhost. Toetsen in de pilot door een getekend document in Adobe Acrobat te valideren, en navragen bij Signhost.
- **Certificeringen ISO 27001, ISO 9001 en NEN 7510.** Een Signhost-overzicht uit oktober 2024 noemt volgens zoekresultaten ISO/IEC 27001:2022 en SOC 2 Type II. NEN 7510 is niet teruggevonden. Het document zelf was niet te openen. Actuele certificaten met scope en geldigheid opvragen.
- **Bewijslast bij een gekwalificeerde handtekening.** Gemini stelt dat bij betwisting de bewijslast omkeert. Dat is een juridische interpretatie zonder vindplaats; laten beoordelen als een document hiervan afhangt.
- **Vertegenwoordiging en leeftijdsgrenzen (artikelen 7:447, 7:450 en 7:465 BW).** De weergave komt overeen met de gangbare uitleg van de WGBO, maar de wettekst is in deze ronde niet nagelopen. De regels gelden voor de geneeskundige behandelingsovereenkomst en niet vanzelf voor andere zorgcontracten.
- **Koppeling met Nedap ONS.** De bron is een blog van een dienstverlener. Het dossiersysteem van de organisatie is nog onbekend.
- **eIDAS 2.0.** De opmerking dat leveranciers de EU-wallet moeten ondersteunen en dat dit "de langetermijnkeuze bestendigt", is een verwachting en geen grond voor het besluit.

## Kwaliteit van de bronnen

De opdracht vroeg om wetgeving, rechtspraak en leveranciersdocumentatie als hoofdbron. Het bronnenregister van Gemini leunt grotendeels op blogs van advocatenkantoren, concurrenten van Signhost en vergelijkingssites. In het register zelf staan geen directe links en geen raadpleegdata per conclusie. Twee citaten zijn niet terug te vinden in de opgegeven bron (het SVB-citaat en de verwerkersovereenkomst).

Gemini geeft ook een voorlopig oordeel "geschikt onder strikte voorwaarden" terwijl zorgvorm, financiering, contractmodellen, dossiersysteem en volumes onbekend zijn. Dat oordeel beschrijft scenario's en geen situatie van de organisatie.

## Wat het rapport wel oplevert

- **Bevoegdheid is mensenwerk.** Signhost controleert hoogstens wie tekent, niet of die persoon mag tekenen. De controle van vertegenwoordiging hoort vóór het versturen plaats te vinden en in het dossier te worden vastgelegd.
- **Onderscheid tussen eisen.** Schriftelijke vastlegging, een handtekening, een origineel en een papieren handtekening zijn verschillende eisen. Een eis van een financier is geen wet.
- **Werkroute in negen stappen** en een lijst uitzonderingen (geen e-mail, beperkte digitale vaardigheid, vertegenwoordiger, geen reactie, weigering, fout document, afwezigheid). Deze sluiten aan op het pilotplan in het [onderzoeksplan](onderzoeksplan.md).
- **Pilotopzet:** twee medewerkers, vijf transacties met fictieve gegevens, met acceptatiecriteria voor verzegeling, transactiebewijs, thuiswerkplek en doorlooptijd.
- **Aandachtspunt thuiswerken:** bij handmatig downloaden staan getekende documenten tijdelijk op de laptop. Het toegangslog van het dossiersysteem dekt die stap niet vanzelf.
- **Beslispunten:** handtekeningniveau per documentsoort, de pgb-route, de DPIA-beoordeling en de keuze tussen portaal en koppeling.

Deze punten zijn verwerkt in de [contractenmatrix](contractenmatrix.md), de [vragenlijst](vragenlijst.md) en het [videoscript](../video/videoscript.md).

## Wat nu nodig is

Sinds de toetsing heeft de organisatie opgegeven dat de financiering Wlz en Wmo is, dat pgb afloopt, dat ZilliZ het dossiersysteem is en dat de eis van een natte handtekening van een collega komt. Pgb valt daarmee buiten de Signhost-werkwijze.

1. Navraag bij de collega over het document en de herkomst van de eis, en de voorwaarden van zorgkantoor en gemeenten.
2. Schriftelijke bevestiging van Signhost over het handtekeningniveau per route, het zegel en tijdstempel, de bewaartermijnen, de subverwerkers en de certificaten.
3. Navraag bij ZilliZ over ondertekenen in het cliëntportaal en een eventuele koppeling.
4. Een pilot met fictieve gegevens, waarin het downloaden binnen 30 dagen en de validatie van het getekende bestand worden getoetst.
