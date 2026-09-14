# Import: Förråd, garage och lägenheter

**Källa:** `Förråd_garagelista 2026-02-25.xlsx`

**Underlagets uppdateringsdatum:** 2026-02-25

## Importerade uppgifter

- 78 lägenheter
- 78 lägenhetsanknutna förråd
- 70 garage kopplade till lägenheter
- 8 parkeringsplatser kopplade till lägenheter
- 1 parkeringsplats markerad som BRF (771)
- 15 byggnadsobjekt enligt föreningens befintliga byggnadslista, med koppling till lägenheterna där sådan finns

## Objektkoppling

Varje lägenhet har kopplats till:

- hus
- förråd
- garage eller parkeringsplats
- föreningens befintliga Objekt-ID

Inga personuppgifter om boende har importerats.

## Datakvalitet

Förråd 610 och 611 är numrerade i kalkylbladet men saknar i underlaget uppgift om tillhörighet och förrådstyp. De har därför lagts in med `datastatus: preliminär` och ska verifieras innan de används som säker information.

Parkeringsplats 771 är markerad som `BRF` i underlaget och har därför lagts in som föreningsanknuten parkeringsplats.

## Registerfiler

- `lagenheter/register.yaml`
- `byggnader/register.yaml`
- `gemensamma-anlaggningar/forrad/register.yaml`
- `gemensamma-anlaggningar/garage-och-parkering/register.yaml`
