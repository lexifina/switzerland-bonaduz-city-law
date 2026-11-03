# Bonaduz (city): law history in git

The municipal law of the municipality of Bonaduz (Gemeinde Bonaduz, canton of Graubünden, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Graubünden is in [lexifina/switzerland-graubunden-law](https://github.com/lexifina/switzerland-graubunden-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

29 acts with 36 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeverfassung (SRS 1.1-1) | 2 | oldest version available, then each consolidated version: 27 November 2022 to 1 January 2026 |
| `1-1-2/` | Finanzkompetenzregelung (SRS 1.1-2) | 1 | as enacted, 30 March 2008 |
| `1-2-1-offentlichkeitsgesetz/` | Gesetz über das Öffentlichkeitsprinzip (SRS 1.2-1) | 1 | as enacted, 1 January 2026 |
| `1-2-2/` | Reglement über die Nutzung der digitalen Ortseingangstafel der Gemeinde Bonaduz (SRS 1.2-2) | 1 | as enacted, 1 May 2026 |
| `1-6-1-entschadigungsgesetz/` | Gesetz über die Entschädigung von Behörden und Kommissionen (SRS 1.6-1) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `1-7-1-pg/` | Personalgesetz (SRS 1.7-1) | 1 | one version (the oldest available), 1 August 2010 |
| `4-2-1/` | Schulordnung Schule Bonaduz (SRS 4.2-1) | 2 | as enacted, then each consolidated version: 19 September 2013 to 1 January 2026 |
| `4-2-2/` | Schulordnung Oberstufen-Schulverband Bonaduz Rhäzüns (SRS 4.2-2) | 1 | as enacted, 1 January 2026 |
| `4-8-1/` | Reglement betreffend Unterstützung jugendfördernder Vereine (SRS 4.8-1) | 1 | as enacted, 1 July 2013 |
| `5-1-1-polg/` | Polizeigesetz (SRS 5.1-1) | 2 | as enacted, then each consolidated version: 1 January 2023 to 1 December 2025 |
| `5-1-2/` | Ordnungsbussenliste (SRS 5.1-2) | 1 | as enacted, 1 March 2026 |
| `5-3-1-gemeindefuhrungsstab/` | Gesetz über die Katastrophenorganisation (SRS 5.3-1) | 1 | as enacted, 3 December 2008 |
| `5-5-1/` | Feuerwehrgesetz (SRS 5.5-1) | 1 | as enacted, 1 January 2026 |
| `5-5-1-1/` | Betriebsreglement der Feuerwehr Bonaduz Rhäzüns (SRS 5.5-1.1) | 1 | as enacted, 1 January 2026 |
| `6-3-1/` | Steuergesetz (SRS 6.3-1) | 1 | one version (the oldest available), 2 December 2020 |
| `6-4-1/` | Kanzleigebühren (SRS 6.4-1) | 2 | as enacted, then each consolidated version: 1 May 2021 to 1 January 2026 |
| `6-6-1/` | Reglement für die Benutzung der Gemeindeanlagen (SRS 6.6-1) | 1 | as enacted, 24 January 2022 |
| `6-6-2/` | Betriebskonzept Freizeitanlagen (SRS 6.6-2) | 1 | as enacted, 23 October 2023 |
| `6-6-3/` | Benutzungsgebühren der Gemeindeanlagen (SRS 6.6-3) | 1 | as enacted, 24 January 2022 |
| `6-8-1/` | Beschaffungsrichtlinien (SRS 6.8-1) | 1 | as enacted, 23 October 2023 |
| `7-4-1-1/` | Erschliessungsgesetz (Wasserversorgung, Abwasserentsorgung, Verkehrsanlagen, Abfallbewirtschaftung, energetische Fördermassnahmen) (SRS 7.4.1-1) | 2 | as enacted, then each consolidated version: 1 January 2012 to 16 January 2026 |
| `7-4-1-1-1-wasserversorgung-abwasserentsorgung-verkehrsanlagen-abfallbewirtschaftung-verwaltungs-und-kanzleigebuhren/` | Gebührenordnung (SRS 7.4.1-1.1) | 1 | one version (the oldest available), 8 July 2024 |
| `7-6-1/` | Gesetz für das Befahren von Waldstrassen mit Motorfahrzeugen (SRS 7.6-1) | 1 | as enacted, 1 January 2021 |
| `7-7-1/` | Verordnung betreffend Benutzung des Durchgangsplatzes für Schweizer Fahrende (SRS 7.7-1) | 2 | as enacted, then each consolidated version: 13 April 2015 to 1 March 2026 |
| `7-7-2/` | Allgemeinverfügung Nutzung Schulareal (SRS 7.7-2) | 1 | as enacted, 4 October 2021 |
| `8-2-1/` | Friedhof- und Bestattungsgesetz (SRS 8.2-1) | 1 | as enacted, 1 January 2016 |
| `9-2-1/` | Alp- und Weideordnung (SRS 9.2-1) | 1 | as enacted, 1 July 1982 |
| `9-5-1/` | Gastwirtschaftsgesetz der Gemeinde Bonaduz (SRS 9.5-1) | 1 | as enacted, 1 January 2009 |
| `9-5-1-1/` | Verordnung zum Gastwirtschaftsgesetz (SRS 9.5-1.1) | 1 | as enacted, 1 April 2015 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://bonaduz.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@bonaduz.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
