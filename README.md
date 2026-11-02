# Leapla Docs

De handleiding van Leapla, voor wie de app gebruikt: docs.leapla.co. Gemaakt met [Mintlify](https://mintlify.com), thema Maple, zoals docs.macro.com.

| Bestand | Pagina |
|---|---|
| `index.mdx` | Welkom |
| `getting-started.mdx` | Aan de slag |
| `features/<name>.mdx` | Home, Inbox, Taken, Agenda, Geld, Papieren, Docs, Gedeeld, Apla (home, inbox, tasks, calendar, money, papers, docs, shared, apla) |
| `en/…` | The same pages in English, with the same file names |
| `docs.json` | Naam, kleuren, lettertype (Sora), menu |

**Deze repo is openbaar.** Er komt alleen tekst voor gebruikers in, nooit interne notities.

**Afspraak (2 november 2026):** bij elke nieuwe of veranderde functie van de app wordt de pagina hier mee bijgewerkt. Wat nog niet bestaat, staat er als "Binnenkort".

## Lokaal bekijken

```
npx mint@4.2.1063 dev
```

Dan op http://localhost:3000. Nakijken voor een commit: `npx mint@4.2.1063 validate` en `npx mint@4.2.1063 broken-links`.

## Live

Mintlify publiceert wat op `main` staat. Daarom: werken op een tak, en naar `main` pas met het akkoord van Seppe.
