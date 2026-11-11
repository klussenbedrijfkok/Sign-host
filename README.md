# Onderzoek naar Signhost voor de zorgadministratie

Dit project bereidt de keuze en inrichting van Signhost voor en bevat de opzet voor een praktische uitlegvideo. De zorgadministratie gaat vanuit huis werken; de beoogde kantoorlocatie is Bussum. Contracten moeten op afstand kunnen worden aangeboden, ondertekend, opgevolgd en opgeslagen.

**Status op 11 november 2026:** onderzoeksopzet. De contracten, financiering, interne werkwijze en Signhost-instellingen moeten nog worden aangeleverd. Er is nog geen definitief geschiktheidsoordeel.

GitHub: [klussenbedrijfkok/Sign-host](https://github.com/klussenbedrijfkok/Sign-host). Deze repository is bij de voorbereiding als openbaar aangetroffen.

## Bestanden

| Bestand | Doel |
| --- | --- |
| [Onderzoeksplan](onderzoek/onderzoeksplan.md) | Onderzoeksvragen, aanpak en criteria voor het besluit |
| [Contractenmatrix](onderzoek/contractenmatrix.md) | Beoordeling per documentsoort en ondertekenroute |
| [Bronnen en bevindingen](onderzoek/bronnen-en-bevindingen.md) | Controleerbare onderbouwing en openstaande claims |
| [Vragenlijst](onderzoek/vragenlijst.md) | Benodigde informatie van de organisatie en Signhost |
| [Videoscript](video/videoscript.md) | Conceptscenario, spreektekst en opnameplan |
| [Gemini deep research](prompts/gemini-deep-research.md) | Volledige opdracht om in Gemini Deep Research te plakken |
| [Invoer aanleveren](invoer/README.md) | Waar contractmodellen en aanvullende informatie kunnen komen |

## Eerstvolgende stappen

1. Kopieer de opdracht uit `prompts/gemini-deep-research.md` naar Gemini Deep Research.
2. Bewaar het volledige Gemini-resultaat met bronlinks lokaal in `invoer/vertrouwelijk/`.
3. Voeg contractmodellen en informatie over de huidige werkwijze toe volgens de invoerinstructies.
4. Controleer de onderzoeksresultaten aan de oorspronkelijke bronnen en vul de contractenmatrix aan.
5. Beproef de voorgestelde werkwijze met fictieve gegevens en werk daarna het videoscript uit met de werkelijke schermen.

## Omgaan met projectinformatie

`invoer/vertrouwelijk/` wordt door `.gitignore` uitgesloten van normale Git-toevoegingen. Dit is geen toegangsbeveiliging en voorkomt geen handmatige upload of geforceerde toevoeging. Bewaar cliëntgegevens, ingevulde contracten, handtekeningen en interne screenshots uitsluitend in de daarvoor geschikte omgeving. Gebruik voor dit onderzoek bij voorkeur lege modellen of geanonimiseerde voorbeelden; controleer ook bijlagen en documentmetadata.

Het onderzoeksplan, videoscript en de prompt bevatten geen cliëntgegevens. Neem in openbare onderzoeksresultaten alleen informatie op die openbaar mag worden gedeeld.
