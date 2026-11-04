# Städly social assets

Bilder för [Städlys](https://stadly.nu) inlägg i sociala medier. Städly är en städfirma i Göteborg. Inläggen hämtar bilderna härifrån via jsDelivr.

Repot innehåller 22 JPG-bilder (1080 × 1080 px). Ingen kod och ingen build.

## Bildernas URL:er

Varje bild nås på `https://cdn.jsdelivr.net/gh/orangeelefant/stadly-social-assets@main/<filnamn>`. Filnamn och sökvägar ändras aldrig, eftersom schemalagda och publicerade inlägg pekar på dem.

## Namngivning

| Prefix | Innehåll |
|---|---|
| `vecka-01` till `vecka-20` | En bild per vecka i serien. Namnet efter numret är temat, till exempel `vecka-04-rut.jpg`. |
| `samhalle-` | Bilder för kampanjer som Rosa bandet och Movember. |

## Lägga till en bild

Lägg filen i roten med nästa lediga veckonummer, committa och pusha till `main`. jsDelivr cachar `@main` en stund, så en ny bild kan dröja innan den syns på CDN-adressen.

## Dokumentation

[AGENTS.md](AGENTS.md) · [CLAUDE.md](CLAUDE.md) · [CHANGELOG.md](CHANGELOG.md) · [TODO.md](TODO.md)

---
**Webraketen på GitHub:** [Portfolio](https://github.com/orangeelefant/portfolio) · [Kundcase](https://github.com/orangeelefant/case-studies) · [Blue Pencil](https://github.com/orangeelefant/bluepencil) · [webraketen.se](https://webraketen.se)
