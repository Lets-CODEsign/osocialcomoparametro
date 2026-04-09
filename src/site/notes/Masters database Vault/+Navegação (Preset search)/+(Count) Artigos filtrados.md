---
dg-publish: true
---
*Total de artigos filtrados*
<!-- QueryToSerialize: TABLE length(file.inlinks) AS Number FROM "=Local" -->
<!-- SerializedQuery: TABLE length(file.inlinks) AS Number FROM "=Local" -->

| File                                                                   | Number |
| ---------------------------------------------------------------------- | ------ |
| [[=Sydney]]                  | 6      |
| [[=Sarajevo]] | 3      |
| [[=Munich]]                    | 3      |
| [[=Wismar]]                    | 3      |
| [[=Lovaina]]                  | 3      |
| [[=Milan]]                        | 3      |
| [[=Pisa]]                          | 3      |
| [[=Bologna]]                    | 3      |
| [[=Athens]]                     | 3      |
| [[=Porto]]                     | 3      |
| [[=Lausanne]]            | 3      |
| [[=Zürich]]                | 3      |
| [[=Hatfield]]                     | 3      |
| [[=Cambridge]]                   | 3      |
| [[=London]]                         | 6      |
| [[=Incheon]]              | 4      |
| [[=Viena]]                      | 4      |
| [[=California]]                | 3      |
| [[=Nashville]]                  | 3      |
| [[=Massachusetts]]          | 3      |
| [[=Tennessee]]                  | 3      |
| [[=Texas]]                          | 3      |
| [[=Minnesota]]                  | 3      |
| [[=Mississippi]]              | 3      |
| [[=Ceará]]                         | 5      |
| [[=Paraíba]]                     | 3      |
| [[=Hong Kong]]                  | 3      |
| [[=Guangdong]]                  | 6      |
| [[=Nanjing]]                      | 4      |
| [[=Shanghai]]                    | 4      |
| [[=Shenzhen]]                    | 3      |
| [[=Suzhou]]                        | 3      |
| [[=Cairo]]                          | 3      |
| [[=Singapore]]              | 3      |
| [[=Instanbul]]                 | 4      |
| [[=Montevideo]]              | 3      |

<!-- SerializedQuery END -->

*Filtrados por ano*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" GROUP by ano_de_publicação -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" GROUP by ano_de_publicação -->

| ano_de_publicação | Number |
| ----------------- | ------ |
| 2022              | 19     |
| 2023              | 20     |

<!-- SerializedQuery END -->

*Filtrados por conferência*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" GROUP by conferência -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" GROUP by conferência -->

| conferência    | Number |
| -------------- | ------ |
| ACADIA         | 3      |
| ASCAAD         | 1      |
| CAADRIA        | 6      |
| CDRF           | 3      |
| eCAADe         | 12     |
| IJAC (Journal) | 5      |
| SIGraDi        | 9      |

<!-- SerializedQuery END -->

*Filtrados por escala*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" GROUP by escala -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" GROUP by escala -->

| escala      | Number |
| ----------- | ------ |
| Arquitetura | 22     |
| Urbanismo   | 17     |

<!-- SerializedQuery END -->

*Filtrados por escala e organizados por conferência (Arquitetura)*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" and escala = "Arquitetura" GROUP by conferência -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" and escala = "Arquitetura" GROUP by conferência -->

| conferência    | Number |
| -------------- | ------ |
| ACADIA         | 3      |
| ASCAAD         | 1      |
| CDRF           | 2      |
| eCAADe         | 10     |
| IJAC (Journal) | 2      |
| SIGraDi        | 4      |

<!-- SerializedQuery END -->

*Filtrados por escala e organizados por conferência (Urbanismo)*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" and escala = "Urbanismo" GROUP by conferência -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" WHERE source_sample = "Yes" and escala = "Urbanismo" GROUP by conferência -->

| conferência    | Number |
| -------------- | ------ |
| CAADRIA        | 6      |
| CDRF           | 1      |
| eCAADe         | 2      |
| IJAC (Journal) | 3      |
| SIGraDi        | 5      |

<!-- SerializedQuery END -->

*Filtrados por Norte-global*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" and #Where/Norte_Global WHERE source_sample = "Yes" GROUP by conferência -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" and #Where/Norte_Global WHERE source_sample = "Yes" GROUP by conferência -->

| conferência    | Number |
| -------------- | ------ |
| ACADIA         | 3      |
| ASCAAD         | 1      |
| CAADRIA        | 4      |
| CDRF           | 1      |
| eCAADe         | 11     |
| IJAC (Journal) | 3      |
| SIGraDi        | 2      |

<!-- SerializedQuery END -->

*Filtrados por Sul-global*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" and #Where/Sul_Global WHERE source_sample = "Yes" GROUP by conferência -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" and #Where/Sul_Global WHERE source_sample = "Yes" GROUP by conferência -->

| conferência    | Number |
| -------------- | ------ |
| ACADIA         | 2      |
| CAADRIA        | 2      |
| CDRF           | 2      |
| eCAADe         | 2      |
| IJAC (Journal) | 2      |
| SIGraDi        | 8      |

<!-- SerializedQuery END -->

