# Codelijst CSOR Drager

SKOS-codelijst voor **dragers** binnen het Centraal Systeem voor Omgevingsrapportering (CSOR).

Een drager beschrijft het medium waarin een kenmerk geobserveerd wordt (bv. omgevingslucht, waterbodem, PM10).

## Conceptschema

URI: `https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/drager`

Namespace CSOR-ontologie: `https://data.omgeving.vlaanderen.be/ns/csor#`

## Concepten

| ID    | Label                        | Deprecated |
|-------|------------------------------|------------|
| DR_1  | Waterstaal                   | ja         |
| DR_2  | Waterbodem                   | nee        |
| DR_3  | Biota                        | nee        |
| DR_4  | PassiveSamplingFilter        | nee        |
| DR_7  | TSP                          | nee        |
| DR_8  | omgevingslucht               | nee        |
| DR_9  | PM10                         | nee        |
| DR_10 | bulk depositie (precip)      | nee        |
| DR_11 | regen                        | nee        |
| DR_12 | PM2.5                        | nee        |
| DR_13 | wet-only depositie (prec)    | nee        |

## Bestandsformaten

De codelijst is beschikbaar in drie RDF-serialisaties:

| Bestand         | Formaat             |
|-----------------|---------------------|
| `dragers.ttl`   | Turtle              |
| `dragers.nt`    | N-Triples           |
| `dragers.rj`    | RDF/JSON            |

Bestanden staan onder `src/main/resources/be/vlaanderen/omgeving/data/id/conceptscheme/csor/drager/`.

## Licentie

[GNU General Public License v3.0](LICENSE)
