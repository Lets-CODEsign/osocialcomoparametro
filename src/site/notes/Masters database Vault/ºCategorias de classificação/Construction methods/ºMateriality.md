---
dg-publish: true
---

```dataview 
TABLE cumincad as id, ano_de_publicação as ano
FROM "🔸Sample Database" WHERE contains(file.outlinks, link("Categorização/Construction Methods/Materiality")) 
Sort cumincad asc 
```

