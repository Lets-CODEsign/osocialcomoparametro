---
dg-publish: true
---
*Total de artigos filtrados*
<!-- QueryToSerialize: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" GROUP by tags -->
<!-- SerializedQuery: TABLE length(rows) as Number FROM "''Artigos Algorithm aided Parametric Design + CumInCAD" GROUP by tags -->

| tags                                                                                       | Number |
| ------------------------------------------------------------------------------------------ | ------ |
| \-                                                                                         | 601    |
| <ul><li>Where/Norte_Global/Australia</li></ul>                                             | 3      |
| <ul><li>Where/Norte_Global/Austria/Viena</li></ul>                                         | 2      |
| <ul><li>Where/Norte_Global/Bélgica/Lovânia</li></ul>                                       | 1      |
| <ul><li>Where/Norte_Global/Germany</li></ul>                                               | 1      |
| <ul><li>Where/Norte_Global/Germany/Munich</li></ul>                                        | 1      |
| <ul><li>Where/Norte_Global/Greece</li></ul>                                                | 1      |
| <ul><li>Where/Norte_Global/Italy</li></ul>                                                 | 1      |
| <ul><li>Where/Norte_Global/Italy</li><li>Where/Norte_Global/Australia</li></ul>            | 1      |
| <ul><li>Where/Norte_Global/Italy</li><li>Where/Norte_Global/UK</li></ul>                   | 1      |
| <ul><li>Where/Norte_Global/Portugal</li><li>Where/Sul_Global/Turkey</li></ul>              | 1      |
| <ul><li>Where/Norte_Global/South_Korea</li></ul>                                           | 2      |
| <ul><li>Where/Norte_Global/Switzerland</li></ul>                                           | 1      |
| <ul><li>Where/Norte_Global/UK</li></ul>                                                    | 1      |
| <ul><li>Where/Norte_Global/UK</li><li>Where/Norte_Global/Switzerland</li></ul>             | 1      |
| <ul><li>Where/Norte_Global/USA</li></ul>                                                   | 2      |
| <ul><li>Where/Norte_Global/USA</li><li>Where/Norte_Global/Bosnia_and_Herzegovina</li></ul> | 1      |
| <ul><li>Where/Norte_Global/USA/Nashville</li><li>Where/Sul_Global/Brasil/Paraíba</li></ul> | 1      |
| <ul><li>Where/Norte_Global/USA/Tennessee</li></ul>                                         | 1      |
| <ul><li>Where/Sul_Global/Brasil</li></ul>                                                  | 2      |
| <ul><li>Where/Sul_Global/Brasil/Ceará</li></ul>                                            | 1      |
| <ul><li>Where/Sul_Global/China</li></ul>                                                   | 3      |
| <ul><li>Where/Sul_Global/China</li><li>Where/Norte_Global/UK</li></ul>                     | 2      |
| <ul><li>Where/Sul_Global/China/Guangzhou</li></ul>                                         | 2      |
| <ul><li>Where/Sul_Global/China/Nanjing</li></ul>                                           | 2      |
| <ul><li>Where/Sul_Global/Egypt</li></ul>                                                   | 1      |
| <ul><li>Where/Sul_Global/Singapore</li></ul>                                               | 1      |
| <ul><li>Where/Sul_Global/Turkey/Instanbul</li></ul>                                        | 1      |
| <ul><li>Where/Sul_Global/Uruguay/Montevideo</li></ul>                                      | 1      |

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

