# Onderzoek naar Signhost voor de zorgadministratie

Dit project bereidt de keuze en inrichting van Signhost voor en bevat de opzet voor een praktische uitlegvideo. De zorgadministratie gaat vanuit huis werken; de beoogde kantoorlocatie is Bussum. Contracten moeten op afstand kunnen worden aangeboden, ondertekend, opgevolgd en opgeslagen.

**Status op 11 november 2026:** het Gemini-onderzoek is ontvangen en getoetst. Vier dragende beweringen uit dat rapport houden geen stand, waaronder het pgb-verbod van de SVB op digitale handtekeningen. De contracten, financiering, interne werkwijze en Signhost-instellingen moeten nog worden aangeleverd. Er is nog geen geschiktheidsoordeel.

GitHub: [klussenbedrijfkok/Sign-host](https://github.com/klussenbedrijfkok/Sign-host). Deze repository is bij de voorbereiding als openbaar aangetroffen.

## Bestanden

| Bestand | Doel |
| --- | --- |
| [Onderzoeksplan](onderzoek/onderzoeksplan.md) | Onderzoeksvragen, aanpak en criteria voor het besluit |
| [Toetsing Gemini-onderzoek](onderzoek/toetsing-gemini-onderzoek.md) | Wat het Gemini-rapport concludeert en wat daarvan standhoudt |
| [Contractenmatrix](onderzoek/contractenmatrix.md) | Voorlopige beoordeling per documentsoort en ondertekenroute |
| [Bronnen en bevindingen](onderzoek/bronnen-en-bevindingen.md) | Controleerbare onderbouwing en openstaande claims |
| [Vragenlijst](onderzoek/vragenlijst.md) | Benodigde informatie van de organisatie en Signhost |
| [Videoscript](video/videoscript.md) | Conceptscenario, spreektekst en opnameplan |
| [Gemini deep research](prompts/gemini-deep-research.md) | Volledige opdracht om in Gemini Deep Research te plakken |
| [Invoer aanleveren](invoer/README.md) | Waar contractmodellen en aanvullende informatie kunnen komen |

## Eerstvolgende stappen

1. Beantwoord de vragen onder "Eerst beantwoorden" in de [vragenlijst](onderzoek/vragenlijst.md).
2. Leg de vragen voor Signhost schriftelijk voor en vraag de verwerkersovereenkomst, subverwerkerslijst en certificaten op.
3. Vraag bij pgb-overeenkomsten de SVB of de verstrekker of een elektronisch getekend formulier wordt geaccepteerd.
4. Voeg contractmodellen en informatie over de huidige werkwijze toe volgens de invoerinstructies en vul de contractenmatrix per model aan.
5. Beproef de voorgestelde werkwijze met fictieve gegevens en werk daarna het videoscript uit met de werkelijke schermen.

Het volledige Gemini-rapport hoort lokaal in `invoer/vertrouwelijk/` te staan.

## Omgaan met projectinformatie

`invoer/vertrouwelijk/` wordt door `.gitignore` uitgesloten van normale Git-toevoegingen. Dit is geen toegangsbeveiliging en voorkomt geen handmatige upload of geforceerde toevoeging. Bewaar cliëntgegevens, ingevulde contracten, handtekeningen en interne screenshots uitsluitend in de daarvoor geschikte omgeving. Gebruik voor dit onderzoek bij voorkeur lege modellen of geanonimiseerde voorbeelden; controleer ook bijlagen en documentmetadata.

Het onderzoeksplan, videoscript en de prompt bevatten geen cliëntgegevens. Neem in openbare onderzoeksresultaten alleen informatie op die openbaar mag worden gedeeld.
