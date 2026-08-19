# Inburgering 2026 — A2 exam prep

Personal study repo for the Dutch Inburgeringsexamen (A2). Inspired by
[thecr7guy2/learnindutch](https://github.com/thecr7guy2/learnindutch), reworked to lean on
native GitHub features (Issues, labels) instead of a custom app, and organized around the
official exam task types instead of a general framework.

## Countdown

| Onderdeel | Datum | Status |
|---|---|---|
| Lezen | — | ✅ Geslaagd |
| Luisteren | — | ✅ Geslaagd |
| Schrijven | **27 augustus 2026** | Geboekt |
| Spreken | TBD | Nog boeken |
| KNM | TBD | Nog boeken |

> Update this table as soon as spreken and KNM are booked — `git log` on this file doubles as a
> record of when things changed.

## Structure

```
schrijven/       task types, example texts, phrase bank, dated practice attempts
spreken/         common topics with model Q&A, phrase bank
knm/             one file per official theme (wonen, werk, gezondheid, ...)
woordenbank.csv  central vocab bank, tagged by theme/skill — importable into Anki
voortgang.md     dated study log / journal
```

## How mistakes are tracked

Instead of one flat `logboek.md`, mistakes are logged as **GitHub Issues** with the
`fout` template (`.github/ISSUE_TEMPLATE/fout.yml`) and labelled by skill
(`skill:schrijven`, `skill:spreken`, `skill:knm`). That makes them:

- filterable by skill/theme via labels
- searchable instead of scrolling one long markdown file
- closeable once a mistake stops recurring (closed ≠ deleted — history stays)

Open mistakes: use the Issues tab, filter by label. A closed issue that gets reopened is a
signal a mistake came back — worth flagging in `voortgang.md`.

## Vocab bank

`woordenbank.csv` is a flat table (`woord,vertaling,thema,onderdeel,voorbeeldzin`). Keep
adding rows as you go. Because it's plain CSV, it imports directly into Anki
(File → Import) if you want spaced-repetition drilling without maintaining a custom flashcard
app.

## Note on KNM content

The theme files in `knm/themas/` are scaffolds with structure and a few widely-taught
starting facts — **not** a substitute for the official KNM course material / DUO
oefenexamens. Civic-knowledge facts (dates, institutions, procedures) need to come from an
authoritative source since getting them wrong on the exam matters; fill these in from your
course book as you study each theme.
