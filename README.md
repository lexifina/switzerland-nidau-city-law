# Nidau (city): law history in git

The municipal law of the city of Nidau (Stadt Nidau, canton of Bern, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Bern is in [lexifina/switzerland-bern-law](https://github.com/lexifina/switzerland-bern-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the city publishes it.

## What this repository holds

59 acts with 74 versions so far: the Stadtordnung (the city's charter) and 58 other enactments in force. The 20 acts added most recently are current-text records with one source-dated version each. Three of those records (SRS 161.11, 161.15 and 430.12) carry explicit omission labels for five official annexes whose normative layouts cannot yet be preserved by the shared builder, so they do not count as complete. Thirty-four PDF-only entries in the official collection and the newly revised SRS 171.9 also remain to be added after exact text, table, scan and image verification.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `101-1/` | Stadtordnung von Nidau (SRS 101.1) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 July 2016 |
| `141-1/` | Reglement über Gemeindeabstimmungen und -wahlen (SRS 141.1) | 1 | one current-text version (oldest version available), 1 January 2003 |
| `151-1-go-sr/` | Geschäftsordnung des Stadtrats (SRS 151.1) | 1 | one current-text version (oldest version available), 1 January 2024 |
| `161-11-verwaltungsverordnung/` | Verordnung über die Verwaltungsorganisation (SRS 161.11) | 1 | one current-text version (oldest version available), 1 October 2026 |
| `161-12-geververordnung/` | Verordnung über die elektronische Geschäftsverwaltung und Archivierung in der Stadtverwaltung Nidau (SRS 161.12) | 1 | one current-text version (oldest version available), 1 January 2020 |
| `161-14/` | Verordnung über die Nutzung von Informatikmitteln (SRS 161.14) | 1 | one current-text version (oldest version available), 1 October 2025 |
| `161-15/` | Richtlinie für die nachhaltige Beschaffung (SRS 161.15) | 1 | one current-text version (oldest version available), 1 April 2020 |
| `171-1/` | Personalreglement (SRS 171.1) | 1 | one current-text version (oldest version available), 1 July 2006 |
| `171-15/` | Verordnung über die städtischen Parkplätze (SRS 171.15) | 1 | one current-text version (oldest version available), 1 August 2005 |
| `172-1/` | Reglement über Entschädigungen für Behörden und Kommissionen (SRS 172.1) | 1 | one current-text version (oldest version available), 1 January 2013 |
| `421-11-vbib/` | Bibliotheksverordnung (SRS 421.11) | 1 | one current-text version (oldest version available), 1 January 2016 |
| `421-12-vlud/` | Ludotheksverordnung (SRS 421.12) | 1 | one current-text version (oldest version available), 1 January 2016 |
| `423-11/` | Verordnung über die Ehrung im Bereich Kultur, Kunst, Soziales und Sport (SRS 423.11) | 1 | one current-text version (oldest version available), 1 January 2007 |
| `430-1-schulreglement/` | Reglement über das Schulwesen (SRS 430.1) | 1 | one current-text version (oldest version available), 1 April 2010 |
| `430-11-schulverordnung/` | Verordnung über das Schulwesen (SRS 430.11) | 1 | one current-text version (oldest version available), 1 April 2010 |
| `430-12/` | Verordnung über die Schulzahnpflege (SRS 430.12) | 1 | one current-text version (oldest version available), 1 May 2003 |
| `435-1/` | Reglement über die Jugendkommission Nidau (SRS 435.1) | 1 | one current-text version (oldest version available), 1 January 2004 |
| `435-4/` | Reglement über die Kinderbetreuung (SRS 435.4) | 1 | one current-text version (oldest version available), 1 April 2020 |
| `435-52/` | Verordnung über die Kinderbetreuung (SRS 435.52) | 1 | one current-text version (oldest version available), 1 January 2020 |
| `437-81/` | Badeordnung (SRS 437.81) | 1 | one current-text version (oldest version available), 1 January 2026 |
| `437-82-strandbadtarif/` | Tarif für die Benützung der Anlagen des Strandbades Nidau (SRS 437.82) | 1 | one current-text version (oldest version available), 1 January 2026 |
| `521-1/` | Reglement über die Übertragung der Aufgaben in den Bereichen Feuerwehr und Gemeindeführung in Katastrophen und Notlagen (SRS 521.1) | 1 | as enacted, 21 June 2012 |
| `521-11/` | Vertrag betreffend die Besorgung der Aufgaben des Gemeindeführungsorgans im Sinne von Artikel 15 und Artikel 25 des Kantonalen Bevölkerungsschutzund Zivilschutzgesetzes vom 24. Juni 2004 (BSG 521.1) (SRS 521.11) | 1 | as enacted, 1 March 2011 |
| `521-12/` | Vertrag betreffend Regiofeuerwehr Agglomeration Biel (SRS 521.12) | 1 | as enacted, 1 January 2013 |
| `552-1/` | Polizeireglement (SRS 552.1) | 2 | as enacted, then each consolidated version: 6 November 2012 to 1 January 2021 |
| `554-1-videoreglement/` | Reglement über die Videoüberwachung Im öffentlichen Raum (SRS 554.1) | 1 | as enacted, 1 January 2012 |
| `556-1/` | Reglement über die unentgeltliche Bestattung (SRS 556.1) | 1 | as enacted, 28 November 1993 |
| `621-1/` | Reglement über die Spezialfinanzierung Wasserversorgung (SRS 621.1) | 1 | as enacted, 16 September 2004 |
| `622-1/` | Reglement über die Spezialfinanzierung «Parkplatzersatzabgaben» (SRS 622.1) | 1 | as enacted, 1 July 2008 |
| `623-1/` | Reglement über die Spezialfinanzierung Liegenschaften des Finanzvermögens (SRS 623.1) | 1 | as enacted, 14 May 1998 |
| `624-1/` | Reglement zur Förderung von Anstrengungen in den Bereichen Energieeffizienz und Klimaschutz (Spezialfinanzierung) (SRS 624.1) | 2 | as enacted, then each consolidated version: 1 July 2011 to 1 January 2021 |
| `624-11/` | Verordnung zur Förderung von Anstrengungen in den Bereichen Energieeffizienz und Klimaschutz (SRS 624.11) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 August 2025 |
| `661-1/` | Reglement über die Liegenschaftssteuern (SRS 661.1) | 1 | as enacted, 31 December 2004 |
| `671-1/` | Gebührenreglement (SRS 671.1) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `671-11/` | Verordnung über die Kanzleigebühren (SRS 671.11) | 1 | as enacted, 1 January 2017 |
| `681-2/` | Nutzungsordnung Parzellen 17 und 525 (SRS 681.2) | 2 | as enacted, then each consolidated version: 1 October 2023 to 1 January 2025 |
| `681-11/` | Verordnung über die Benützung der Schul- und Sportanlagen (SRS 681.11) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 April 2025 |
| `681-12-nutzungsordnung-balainen/` | Nutzungsordnung für das Schulgelände Balainen (SRS 681.12) | 1 | as enacted, 1 April 2025 |
| `720-1/` | Baureglement (SRS 720.1) | 1 | as enacted, 20 May 2014 |
| `720-2-tbr-altstadt/` | Teilbaureglement Altstadt (SRS 720.2) | 1 | as enacted, 11 December 2020 |
| `720-3-tbr-gmp/` | Teilbaureglement Guido-Müller-Platz West (SRS 720.3) | 1 | as enacted, 28 February 2020 |
| `720-4-tbr-weiteres-stadtgebiet/` | Teilbaureglement weiteres Stadtgebiet und Vorschriften zum Uferschutzplan Nidau-Büren-Kanal (SRS 720.4) | 1 | as enacted, 21 September 2023 |
| `726-1/` | Reglement über die Errichtung von Radio- und Fernseantennenanlagen (SRS 726.1) | 1 | as enacted, 24 March 1972 |
| `727-1-verordnung-fachausschuss/` | Verordnung über den Fachausschuss für Planungs- und Baufragen (SRS 727.1) | 2 | as enacted, then each consolidated version: 1 September 2023 to 21 September 2023 |
| `732-5-strassenbeitragsreglement/` | Reglement über die Erhebung von Beiträgen der Grundeigentümer an die Strassenbaukosten der Gemeinde Nidau (SRS 732.5) | 1 | as enacted, 1 July 1976 |
| `734-1-abwasserreglement/` | Reglement über die Entsorgung des Abwassers (SRS 734.1) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `734-11/` | Verordnung über den Abwassertarif (SRS 734.11) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `742-1-stromreglement/` | Reglement über die allgemeinen Bedingungen für den Netzanschluss, die Netznutzung und die Lieferung elektrischer Energie (SRS 742.1) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2027 |
| `742-11/` | Verordnung über die Gebühren und Tarife der Elektrizitätsversorgung (SRS 742.11) | 1 | as enacted, 1 October 2004 |
| `751-11/` | Reglement über die Übertragung der Wasserversorgung an die Stadt Biel (SRS 751.11) | 1 | as enacted, 1 January 2005 |
| `761-1-parkierungsreglement/` | Reglement über die Benützung der öffentlichen Parkplätze der Stadt Nidau (SRS 761.1) | 1 | as enacted, 24 June 2004 |
| `761-11-parkierungsverordnung/` | Verordnung über die Benützung der öffentlichen Parkplätze der Stadt Nidau (SRS 761.11) | 2 | as enacted, then each consolidated version: 24 May 2005 to 4 December 2013 |
| `822-1-abfallreglement/` | Reglement über die Abfallentsorgung (SRS 822.1) | 1 | one version (the oldest available), 1 July 2013 |
| `841-1-regak/` | Reglement für die Gemeindeausgleichskasse Nidau (SRS 841.1) | 1 | as enacted, 1 January 1998 |
| `860-1/` | Reglement über die Sozialkommission (SRS 860.1) | 2 | as enacted, then each consolidated version: 6 November 2012 to 1 January 2026 |
| `865-11/` | Vertrag betreffend Zusammenarbeit im Bereich der öffentlichen Sozialhilfe und des Kindes- und Erwachsenenschutz (SRS 865.11) | 1 | as enacted, 1 January 2013 |
| `935-1/` | Reglement über die Erhebung einer Kurtaxe (SRS 935.1) | 1 | as enacted, 1 January 2007 |
| `935-11/` | Verordnung über die Erhebung einer Kurtaxe (SRS 935.11) | 1 | as enacted, 1 January 2007 |
| `936-1/` | Reglement über die Arbeits- und Ruhezeit für das Taxigewerbe (SRS 936.1) | 1 | as enacted, 25 February 1969 |

## Source

The SRS (systematic collection) of the city, published by the city at <https://nidau.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). PDF-only texts, annexes and normative visual material are included only after their text and images have been verified exactly.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the city's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@nidau.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the city publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included; the official collection currently lists 94 active entries.
