# Spot-Check Report — Augustine De Trinitate Quotes

Encoding session reports for `augustinedetrinitate_candidates_for_Gi9qrR.json`.
Check items off as you verify them. Line numbers were current when each batch was written;
if a link is off, grep for the `source="...@range"` attribute, which is stable.

## Batch 6 (2026-07-12) — 10 candidates, 11 quote elements (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "Nos, secundum quod mente aliquid aeternum… non sunt in hoc mundo" (August. 4. de Tri. c. 30) | `adt-l4-d1e640@209-241` | [m030083:464](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m030083/cod-grsb22_Gi9qrR-m030083.xml:464) |
| <ul><li>[ ] </li></ul> | 2 | "quae utraque nobis ad hoc proponitur intuenda… & istam creauit" — **⚠ no attribution** | `adt-l2-d1e188@130-148` | [k001070:793](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k001070/cod-grsb21_Gi9qrR-k001070.xml:793) |
| <ul><li>[ ] </li></ul> | 3 | "cum sicut Filio praestat essentiam… de utroque processio" (15. de Trin. cap. 26) | `adt-l15-d1e1975@8-38` | [e95127:994](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e95127/cod-GRvsd1_Gi9qrR-e95127.xml:994) |
| <ul><li>[ ] </li></ul> | 4 | "Quae autem est scientia Dei, est ipsa sapientia… hoc est & esse" ("5." de Trin. cap. 14 — actually book 15) | `adt-l15-d1e1845@9-43` | [e31870:969](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e31870/cod-GRvsd1_Gi9qrR-e31870.xml:969) |
| <ul><li>[ ] </li></ul> | 5 | "Non sane omne, quod in creaturis est simile Deo… nulla interiecta est natura" (Aug. 11. de Tri. c. 5) | `adt-l11-d1e1245@128-165` | [m000333:1110](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m000333/cod-grsb22_Gi9qrR-m000333.xml:1110) |
| <ul><li>[ ] </li></ul> | 6 | "Voluntas Dei est prima & summa causa… aut permittatur quantum ad mala" (3. de Trinitate) | `adt-l3-d1e400@69-100` | [k147958:1094](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k147958/cod-grsb21_Gi9qrR-k147958.xml:1094) |
| <ul><li>[ ] </li></ul> | 7 | "Dilectio, quae ex Deo est, & Deus est… tota inhabitat Trinitas" (idem ibidem cap. 18 = De Trin. 15.18) | `adt-l15-d1e1896@233-259` | [e84651:651](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e84651/cod-GRvsd1_Gi9qrR-e84651.xml:651) |
| <ul><li>[ ] </li></ul> | 8 | "Quid plura & plura bonum hoc & bonum illud… sed bonum omnis boni" ("5." de Trinit. cap. 3 — actually book 8) | `adt-l8-d1e952@127-156` | [e42391:178](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e42391/cod-GRvsd1_Gi9qrR-e42391.xml:178) |
| <ul><li>[ ] </li></ul> | 9 | Same passage, shorter — ends at "ita Deum videbis" | `adt-l8-d1e952@127-148` | [e13599:237](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e13599/cod-GRvsd1_Gi9qrR-e13599.xml:237) |
| <ul><li>[ ] </li></ul> | 10 | "Nullo modo tamen scriptum esset apud Apostolum, [1 Cor 12:8 nested]… haec singula vocarentur" (dicitur ibidem = De Trin. 13.19) | `adt-l13-d1e1507@259-280` + nested `Icor12_8@1-11` | [de6352:204](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-de6352/cod-GRvsd1_Gi9qrR-de6352.xml:204) |

### Notes

- **Item 2 (k001070) — the one to check**: verbatim ~19-word borrowing of Augustine's *De Trin.* 2 prologue, but the MS gives **no attribution** ("Praeterea: Duobus modis cognoscitur Deus…"). Encoded since the match is too long to be coincidence; if policy is attribution-required, revert to `not_found`.
- **Item 10 (de6352)**: first nested Bible quote added by Claude — Augustine quotes 1 Cor 12:8 inside the passage, so the Icor quote sits inside the Augustine quote element.
- **Item 6 (k147958)**: MS interpolates "quantum ad bona" / "quantum ad mala" after "iubeatur"/"permittatur" — short glosses kept inside the continuous quote per convention; the second gloss trails at the very end of the quote.
- **Items 4, 8, 9**: MS book numbers are wrong ("5. de Trin." for passages from books 15 and 8) — text matches unambiguous; noted in the JSON log.
- Two new codex prefixes handled this batch: `cod-grsb22` (m-directories) alongside `cod-grsb21` and `cod-GRvsd1`.

## Batch 7 (2026-07-12) — 10 candidates: 8 encoded (13 quote elements), 2 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found** — MS quotes Eph 4:23-24 directly ("dicitur de Christo ad Ephesios"); Augustine candidate matched only because he quotes the same verse | `adt-l14-d1e1659` | Gi9qrR-m111736-d1e1458 (no edit) |
| <ul><li>[ ] </li></ul> | 2a | "Ad se dicitur Persona, sicut ad se dicitur Deus magnus & bonus" (Aug. 7. de Trin. cap. 6, condensed) | `adt-l7-d1e905@188-207` | [f17097:1721](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f17097/cod-GRvsd1_Gi9qrR-f17097.xml:1721) |
| <ul><li>[ ] </li></ul> | 2b | "Non dicimus Patrem Personam esse Filij… Persona alterius" (rhetorical question → statement) | `adt-l7-d1e905@121-150` | [f17097:1724](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f17097/cod-GRvsd1_Gi9qrR-f17097.xml:1724) |
| <ul><li>[ ] </li></ul> | 3 | Three quotes from De Trin. 15.18: "Spiritus Sanctus cuique datur…" / "Nec Spiritus Sanctus proprie dicitur donum…" / "Spiritus S. est, per quem diffunditur…" | `adt-l15-d1e1896@33-43`, `@50-57`, `@243-278` | [e71027:180](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e71027/cod-GRvsd1_Gi9qrR-e71027.xml:180) |
| <ul><li>[ ] </li></ul> | 4a | "Vniuersas autem creaturas suas… ideo sunt, quia nouit" (August. 15. de Trin. c. 13. ait) | `adt-l15-d1e1842@66-83` | [k168961:619](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k168961/cod-grsb21_Gi9qrR-k168961.xml:619) |
| <ul><li>[ ] </li></ul> | 4b | "Voluntas Dei est prima & summa causa… aut permittat" ("13." de Trin. — actually book 3) | `adt-l3-d1e400@69-100` | [k168961:623](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k168961/cod-grsb21_Gi9qrR-k168961.xml:623) |
| <ul><li>[ ] </li></ul> | 5 | "nec aliter scivit ea creata, quam creanda… illa mansit ut erat" (innuit Aug. 15. de Trin. cap. 13; "quod Deus" intro left outside) | `adt-l15-d1e1842@98-124` | [f88211:557](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f88211/cod-GRvsd1_Gi9qrR-f88211.xml:557) |
| <ul><li>[ ] </li></ul> | 6 | "Sicut Pater & Filius unus Deus… unum principium" (Aug. 5. lib. de Trin. cap. 14) | `adt-l5-d1e756@151-172` | [f44523:130](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f44523/cod-GRvsd1_Gi9qrR-f44523.xml:130) |
| <ul><li>[ ] </li></ul> | 7a | "Non eodem modo in Divinis dicitur Verbum sicut sapientia…" (7. de Trin. "cap. 2", adapted paraphrase, verbatim core) | `adt-l7-d1e864@88-110` | [f37690:821](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f37690/cod-GRvsd1_Gi9qrR-f37690.xml:821) |
| <ul><li>[ ] </li></ul> | 7b | "Sicut enim Filius ad Patrem refertur… eo Verbum, quo Filius" (7. de Trin. "cap. 11", verbatim) | `adt-l7-d1e864@32-64` | [f37690:850](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f37690/cod-GRvsd1_Gi9qrR-f37690.xml:850) |
| <ul><li>[ ] </li></ul> | 8 | "Filium mitti a Patre sine Spiritu Sancto non potuit… fecisse" (arguit August. 2. de Trin. cap. 5) | `adt-l2-d1e213@125-151` | [e73536:367](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e73536/cod-GRvsd1_Gi9qrR-e73536.xml:367) |
| <ul><li>[ ] </li></ul> | 9 | **not_found** — duplicate-passage: Augustine repeats "an angeli qui iam erant…" in De Trin. 2 & 3; MS cites book 3 and matches adt-l3-d1e371 (already encoded, batch 3) | `adt-l2-d1e245` | Gi9qrR-k100392-d1e3250 (no edit) |
| <ul><li>[ ] </li></ul> | 10 | "Vniversas creaturas suas & spiritales & corporales…" (Aug. 15. de Trin. cap. 13. qui ait) | `adt-l15-d1e1842@66-83` | [f72462:561](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f72462/cod-GRvsd1_Gi9qrR-f72462.xml:561) |

### Notes

- **Two false positives this batch** (items 1, 9) — first ones encountered: one where MS and Augustine independently quote the same Bible verse (Eph 4:23-24), one where Augustine repeats nearly the same sentence in two books and the MS's citation + word order point to the already-encoded passage.
- **Item 2b (f17097)**: the MS converts Augustine's rhetorical question ("Num placet dicamus patrem personam esse filii…?") into a negative statement ("Non dicimus…") — encoded as one quote over the corresponding source span @121-150.
- **Item 4 (k168961)**: paragraph quotes two different candidates back-to-back; both were listed in the JSON and both encoded.
- **Item 7 (f37690)**: MS cites "cap. 2" and "cap. 11" of De Trin. 7 but both quotes come from the same source paragraph (adt-l7-d1e864).
- **Item 3 (e71027)**: third quote spans the MS's omission of "per quam nos tota inhabitet trinitas" — kept as one quote per the omission convention.
- Items 1 and 9 require no XML review (nothing was changed); listed for completeness.

## Batch 8 (2026-07-12) — 10 candidates: 10 encoded (13 quote elements) (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Tres Personas eiusdem essentiae… ex eadem essentia non dicimus" (Aug. 7. de Trin. cap. ult. ait) | `adt-l7-d1e918@42-59` | [f63641:924](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f63641/cod-GRvsd1_Gi9qrR-f63641.xml:924) |
| <ul><li>[x] </li></ul> | 2 | "ideo Christus virtus est, │ & sapientia Dei… sicut lumen de Patre lumine" ("5." de Trin. cap. 3 — actually book 7) — **⚠ split across paras d1e589/d1e636** | `adt-l7-d1e870@2-4` + `@5-24` | [e99806:298](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e99806/cod-GRvsd1_Gi9qrR-e99806.xml:298) |
| <ul><li>[x] </li></ul> | 3 | "Vt exterioribus visis hominum corda commota… converterentur" (secundum August. 2. de Trin. cap. 5) | `adt-l2-d1e226@125-140` | [e80626:419](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e80626/cod-GRvsd1_Gi9qrR-e80626.xml:419) |
| <ul><li>[x] </li></ul> | 4 | "Hoc enim sanius creditur… non frustra proprie charitas nuncupatur" (Aug. 15. de Trinit. cap. 19. qui ait) | `adt-l15-d1e1912@102-123` | [e55878:399](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e55878/cod-GRvsd1_Gi9qrR-e55878.xml:399) |
| <ul><li>[x] </li></ul> | 5 | "Pater qui in natura eius ineffabiliter simplici… de substantia eius est genitus" (Aug. 15. de Trin. cap. 19. dicens; adapted) | `adt-l15-d1e1912@317-358` | [e34455:149](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e34455/cod-GRvsd1_Gi9qrR-e34455.xml:149) |
| <ul><li>[x] </li></ul> | 6 | "Memoria, intelligentia, & voluntas quoniam non sunt tres vitae… sed una substantia" (idem 10. de Trin. cap. penult.) | `adt-l10-d1e1182@4-29` | [e24207:273](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e24207/cod-GRvsd1_Gi9qrR-e24207.xml:273) |
| <ul><li>[x] </li></ul> | 7 | "Credendum est, mentis intellectualis naturam ita conditam esse… circum adiacent" (August. 12. de Trinitate; word order adapted) | `adt-l12-d1e1372@100-134` | [k116053:3247](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k116053/cod-grsb21_Gi9qrR-k116053.xml:3247) |
| <ul><li>[x] </li></ul> | 8 | "Vniuersas autem creaturas… quia nouit" + "non aliter ea sciuit creata, quam creanda" (August. in 15. De Trini., "Vnde ait" / "Et subdit") | `adt-l15-d1e1842@66-83`, `@98-104` | [k065200:4566](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k065200/cod-grsb21_Gi9qrR-k065200.xml:4566) |
| <ul><li>[x] </li></ul> | 9 | "Dominus ipse Iesus Spiritum Sanctum non solum dedit ut Deus, sed etiam accepit ut homo" (Aug. 15. de Trin. cap. 26. qui dicit) | `adt-l15-d1e1969@4-18` | [e71027:910](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e71027/cod-GRvsd1_Gi9qrR-e71027.xml:910) |
| <ul><li>[x] </li></ul> | 10 | "Spiritus S. non solus est in illa Trinitate vel Spiritus vel S.… quod ambo communiter" (August. 15. de Trin. cap. 19. qui ait: quod) | `adt-l15-d1e1912@130-177` | [e55878:949](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e55878/cod-GRvsd1_Gi9qrR-e55878.xml:949) |

### Notes

- **⚠ Item 2 (e99806) — erroneous paragraph split**: the quote begins at the end of `d1e589` ("ideo Christus virtus est,") and continues mid-sentence into `d1e636` ("& sapientia Dei: quia de Patre virtute…"). Encoded as two contiguous parts (@2-4 / @5-24); merging the paragraphs would reconcile them to @2-24. Also the MS cites "5. de Trin." for a book-7 passage.
- **Item 5 (e34455)** is the loosest match this batch: the MS adapts "Caritas quippe patris quae in natura eius est…" to "Pater qui in natura eius…" and "filius caritatis eius" to plain "Filius", and skips "ut saepe iam diximus…piget" mid-quote. Same paragraph also quotes *Contra Maximinum* (outside the De Trin. corpus, left alone).
- **Item 8 (k065200)**: the indirect lead-in "Deus non aliter novit facta, quam fienda" (paraphrase with facta/fienda for creata/creanda) was left unencoded; the verbatim "Et subdit" quote of the same sentence is encoded. A later "vt idem Aug. eodem libro… innuit" allusion is purely indirect, also left unencoded.
- **Items 7, 10**: MS reorders source wording (noted in JSON); ranges cover the full corresponding spans.
- **Item 6 (e24207)**: "Memoria, intelligentia & voluntas" opens the quote where the source has "Haec igitur tria, memoria…" — range starts at word 4.

## Batch 9 (2026-07-12) — 10 candidates: 6 encoded (6 quote elements), 4 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x ] </li></ul> | 1 | "Singula sunt in singulis, & omnia in singulis… & unum omnia" (Aug. in fine de Trin. = end of De Trin. 6) | `adt-l6-d1e833@95-113` | [e26033:191](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e26033/cod-GRvsd1_Gi9qrR-e26033.xml:191) |
| <ul><li>[x] </li></ul> | 2 | "voluntas Dei est prima & summa causa… praemiorum atque poenarum" (secundum Augustinum 3. de Trinit.; "id est, voluntate" gloss inside) | `adt-l3-d1e400@69-106` | [m163618:455](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m163618/cod-grsb22_Gi9qrR-m163618.xml:455) |
| <ul><li>[ ] </li></ul> | 3 | **not_found ×2** — para on gratia/virtus echoes Gal 5:6 via the Lombard; no Augustine quote | `adt-l8-d1e996`, `adt-l13-d1e1460` | Gi9qrR-m099109-d1e349 (no edit) |
| <ul><li>[ ] </li></ul> | 4 | **not_found ×2** — MS quotes Rom 5:5 directly ("Iuxta illud Apostoli ad Ro."); both candidates merely quote the same verse | `adt-l8-d1e996`, `adt-l13-d1e1460` | Gi9qrR-m092759-d1e610 (no edit) |
| <ul><li>[x] </li></ul> | 5 | "Cum verba iudicis praeco nunciat… Prophetam non subtrahimus" (tangit Aug. 3. de Trini. dicens; two "vt ait" re-markers kept inside) | `adt-l3-d1e476@20-58` | [k106469:2037](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k106469/cod-grsb21_Gi9qrR-k106469.xml:2037) |
| <ul><li>[x] </li></ul> | 6 | "Deus omnia novit, ut nec ea quae dicuntur praeterita… simul praesto sunt universa" — **⚠ MS cites "15. de Civi. Dei" but text is De Trin. 15** | `adt-l15-d1e1763@8-57` | [k095288:343](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k095288/cod-grsb21_Gi9qrR-k095288.xml:343) |
| <ul><li>[x] </li></ul> | 7 | "Neque enim divinorum librorum tantummodo auctoritas… praestantissimum conditorem" (patet per Augustinum 15. de Trin. dicentem) | `adt-l15-d1e1728@28-55` | [k039964:1832](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k039964/cod-grsb21_Gi9qrR-k039964.xml:1832) |
| <ul><li>[ ] </li></ul> | 8 | "Sciri enim aliquid, & non diligi potest; diligi autem quod nescitur quero utrum possit?" (secundum Aug. 8. de Trin. cap. 4) | `adt-l8-d1e965@53-66` | [e88383:407](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e88383/cod-GRvsd1_Gi9qrR-e88383.xml:407) |

### Notes

- **Four false positives** (items 3, 4 — two paragraphs × two candidates each): the recurring pattern where the MS quotes/echoes a Bible verse (Rom 5:5, Gal 5:6) that Augustine also quotes. No XML edits.
- **⚠ Item 6 (k095288) — misattribution worth review**: the MS explicitly cites "Augu. 15. de Civi. Dei" but the text is verbatim De Trin. 15 (adt-l15-d1e1763). Encoded against De Trin.; noted in JSON. The quote also spans two MS omissions ("ibi praetereant", "nec singula cogitentur…transeatur").
- **Item 1 (e26033)**: completes the fourth quote in the batch-4 paragraph — all four Augustine quotes in that responsio are now sourced.
- **Item 8 (e88383)**: the MS's "Nequaquam." after the quote is the author answering Augustine's rhetorical question — left outside the quote.
- **Item 5 (k106469)**: MS re-marks the quote with "vt ait" twice mid-stream — treated as gloss-like interruptions, one continuous quote.

## Batch 10 (2026-07-12) — 10 candidates: 6 encoded (6 quote elements), 4 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Eadem ipsam fraternam dilectionem (nam fraterna dilectio est, qua diligimus invicem) non solum ex Deo, sed etiam Deum esse" (Aug. 8. de Trin. cap. 8. dicit) | `adt-l8-d1e1006@254-272` | [e84651:605](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e84651/cod-GRvsd1_Gi9qrR-e84651.xml:605) |
| <ul><li>[ ] </li></ul> | 2 | **not_found ×2** — MS quotes Rom 5:5 directly ("scribitur ad Rom. 5"); both candidates quote the same verse | `adt-l8-d1e996`, `adt-l13-d1e1460` | Gi9qrR-e71027-d1e263 (no edit) |
| <ul><li>[x] </li></ul> | 3 | "Ad illam summam & ineffabilem, incorpoream, immutabilemque naturam… melius ceteris animalibus habet" (Aug. 15. de Trin. cap. ultimo) | `adt-l15-d1e1981@222-262` | [e66783:191](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e66783/cod-GRvsd1_Gi9qrR-e66783.xml:191) |
| <ul><li>[x] </li></ul> | 4 | "Partum ergo mentis antecedit appetitus quidam; quo id quod nosse volumus quaerendo & inveniendo" (Aug. in fine 9. de Trin.) | `adt-l9-d1e1103@285-298` | [e37961:90](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e37961/cod-GRvsd1_Gi9qrR-e37961.xml:90) |
| <ul><li>[x]</li></ul> | 5 | "Nec ita sane gignit istam notitiam suam mens… etiam si non cogitentur" (dicitur 14. de Trinit. cap. 6) | `adt-l14-d1e1567@139-171` | [e22819:371](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e22819/cod-GRvsd1_Gi9qrR-e22819.xml:371) |
| <ul><li>[x] </li></ul> | 6 | "ibi Quaerenda, & invenienda est in nobis, quo etiam natura nostra nihil habet melius" (attribution in preceding para) | `adt-l14-d1e1586@46-59` | [e22819:665](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e22819/cod-GRvsd1_Gi9qrR-e22819.xml:665) |
| <ul><li>[ ] </li></ul> | 7 | **not_found ×2** — adt-l15-d1e1893 for the two m-paragraphs from batch 9: shared caritas/dilectio vocabulary only | `adt-l15-d1e1893` | m099109-d1e349, m092759-d1e610 (no edit) |
| <ul><li>[x] </li></ul> | 8 | "Inquantum aliquid aeternum mente capimus: non in hoc mundo sumus…" ("3." de Trinita. cap. 20 — actually book 4; condensed opening) | `adt-l4-d1e640@210-241` | [k171638:1804](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k171638/cod-grsb21_Gi9qrR-k171638.xml:1804) |

### Notes

- **Four false positives** (items 2, 7): the Rom 5:5 pattern again (e71027-d1e263), plus the recurring `adt-l15-d1e1893` candidate that matched the two m-paragraphs from batch 9 on vocabulary alone. All four paragraphs' candidate lists are now fully resolved.
- **Item 8 (k171638)**: same De Trin. 4.20 passage as batch 6 item 1, but this MS condenses the opening ("Inquantum aliquid aeternum mente capimus") and reads "eterna sapiunt" for "divina sapiunt"; cites "3. de Trinita." for book 4.
- **Item 6 (e22819-d1e1394)**: the quote opens the paragraph mid-argument ("dicitur quod ibi…") — attribution stands in the preceding paragraph; not a paragraph-split problem since the quote itself is intact. The same paragraph's indirect references to De Trin. 14 capp. 7/12 were left unencoded.
- **Item 4 (e37961)**: the MS cuts the quote before "nascitur proles ipsa notitia"; its other quote ("Rem prorsus ignotam amare…", De Trin. 10.1) belongs to a different candidate and should surface later.
- **Item 1 (e84651)**: Augustine's own parenthesis kept inside the quote; the next paragraph (d1e1254) quotes the same chapter again — separate candidate, later batch.

## Batch 11 (2026-07-12) — 10 candidates: 8 encoded (8 quote elements), 2 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "Filius autem de patre natus est, & Spiritus sanctus de patre principaliter, & de utroque communiter procedit" (Augustinus 15. de Trini. ait; MS skips a clause) | `adt-l15-d1e1975@98-120` | [k168961:1123](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k168961/cod-grsb21_Gi9qrR-k168961.xml:1123) |
| <ul><li>[x] </li></ul> | 2 | "Neque in hac Trinitate, cum dicimus Personam Patris, aliud dicimus, quam substantiam Patris" (August. 7. de Trin. "cap. 7") | `adt-l7-d1e905@151-163` | [f26985:105](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f26985/cod-GRvsd1_Gi9qrR-f26985.xml:105) |
| <ul><li>[x] </li></ul> | 3 | Same quote, second MS ("cap. 6"; following "Et ibidem vult…" left as paraphrase) | `adt-l7-d1e905@151-163` | [f17097:139](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f17097/cod-GRvsd1_Gi9qrR-f17097.xml:139) |
| <ul><li>[x] </li></ul> | 4 | "Non frustra in hac Trinitate non dicitur Verbum Dei, nisi Filius, nec donum Dei, nisi Spiritus Sanctus" (August. 15. de Trin. cap. 17. qui ait) | `adt-l15-d1e1886@3-19` | [e95127:512](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e95127/cod-GRvsd1_Gi9qrR-e95127.xml:512) |
| <ul><li>[x] </li></ul> | 5 | "Et amor amatur, nec alio nisi amore amari potest, id est, se ipso" (unde Aug. 9. de Trin. cap. 5) | `adt-l9-d1e1059@135-147` | [e88383:359](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e88383/cod-GRvsd1_Gi9qrR-e88383.xml:359) |
| <ul><li>[x] </li></ul> | 6 | "In eo quod de illo scriptum est quod acceperit a Patre promissionem… effudit ut Deus" — **⚠ garbled transmission, phrases out of order** | `adt-l15-d1e1969@224-256` | [e78766:438](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e78766/cod-GRvsd1_Gi9qrR-e78766.xml:438) |
| <ul><li>[ ] </li></ul> | 7 | **not_found ×2** — e71027-d1e263 (Rom 5:5 quoted directly, closing that para) and e71027-d1e1042 (thematic caritas/donum overlap, no quote) | `adt-l15-d1e1893`, `adt-l15-d1e1896` | (no edit) |
| <ul><li>[x] </li></ul> | 8 | "semel in terra propter dilectionem proximi: & iterum de Coelo propter dilectionem Dei" (divisio textus, "manifestat hoc idem per Aug.") | `adt-l15-d1e1962@57-69` | [e69700:107](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e69700/cod-GRvsd1_Gi9qrR-e69700.xml:107) |
| <ul><li>[x] </li></ul> | 9 | "quoniam non potest acies animi simul omnia, quae memoria tenet, uno aspectu contueri" ("15." de Trin. cap. 8 — actually book 11) | `adt-l11-d1e1260@2-14` | [e39991:957](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e39991/cod-GRvsd1_Gi9qrR-e39991.xml:957) |

### Notes

- **⚠ Item 6 (e78766) — the one to check**: the print transmission is badly scrambled — "in humana scilicet & Divina" and "accepit quippe" appear *before* "In eo quod de illo scriptum est…", apparently a line-order error in the exemplar. I wrapped the entire stretch after "dicit::" as one quote with the full source range (@224-256). You may prefer different markup for the corruption.
- **Item 8 (e69700)**: first divisio-textus case — the paragraph describes the Lombard's structure, but the phrase describing Augustine's point is verbatim Augustine; encoded just the verbatim stretch inside the indirect discourse.
- **Items 2, 3**: the same De Trin. 7 sentence quoted in two different files, cited as cap. 7 and cap. 6 respectively.
- **Item 9 (e39991)**: MS cites "15. de Trin. cap. 8" for a De Trin. 11 passage — wrong book, unambiguous text.
- The two e71027 false positives close out that file's remaining low-count candidates.

## Batch 12 (2026-07-12) — 10 candidates: 7 encoded (9 quote elements), 3 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Divina voluntas est prima & summa causa omnium: Nihil enim fit │ visibiliter & sensibiliter… aut permittatur" ("[3]. de Trin. cap. 4") — **⚠ split across paras d1e1437/d1e1467** | `adt-l3-d1e400@69-83` + `@84-100` | [e38320:723](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e38320/cod-GRvsd1_Gi9qrR-e38320.xml:723) |
| <ul><li>[x] </li></ul> | 2 | "voluntas Dei si proprie dicenda est aliqua in Trinitate Persona magis hoc nomen Spiritui Sancto competit" (Aug. 15. de Trin. 20. cap. ait) | `adt-l15-d1e1918@98-114` | [e36732:390](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e36732/cod-GRvsd1_Gi9qrR-e36732.xml:390) |
| <ul><li>[ ] </li></ul> | 3 | bookkeeping: e36732-d1e390 no longer exists (merged into d1e334 in batch 5); JSON entry annotated | `adt-l15-d1e1813` | (no edit) |
| <ul><li>[x] </li></ul> | 4 | "Anima [source: Mens] ergo ipsa sicut corporearum rerum notitias per sensus corporis colligit, sic incorporearum per semetipsam" (Haec tria tangens Aug. 9. de Trinit. ait) | `adt-l9-d1e1043@147-161` | [e24207:451](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e24207/cod-GRvsd1_Gi9qrR-e24207.xml:451) |
| <ul><li>[x] </li></ul> | 5 | "Nec ista duo sic accipiamus… utraque sapientia & │ utraque scientia dici potest" (Aug. 13. de Trin. cap. penult.; "scilicet" gloss inside) — **⚠ split across paras d1e377/d1e409** | `adt-l13-d1e1507@226-254` + `@255-258` | [de6352:193](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-de6352/cod-GRvsd1_Gi9qrR-de6352.xml:193) |
| <ul><li>[ ] </li></ul> | 6 | **not_found ×2** — MS quotes John 1:14 and Heb 1:1 directly; both De Trin. 13 candidates quote the same verses | `adt-l13-d1e1504`, `adt-l13-d1e1387` | Gi9qrR-m198570-d1e2025 (no edit) |
| <ul><li>[x] </li></ul> | 7 | "haec est sapientiae & scientiae recta distinctio… temporalium rerum cognitio rationalis" ("17." de Trinita. — actually book 12; "actualis" for "intellectualis") | `adt-l12-d1e1375@3-24` | [m173872:188](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m173872/cod-grsb22_Gi9qrR-m173872.xml:188) |
| <ul><li>[ ] </li></ul> | 8 | **not_found** — MS quotes Matt 15:17 directly ("vt dicitur Matthei") | `adt-l15-d1e1794` | Gi9qrR-m125279-d1e185 (no edit) |
| <ul><li>[x] </li></ul> | 9 | "nullum est isto dono Dei excellentius: solum est, quod dividit inter filios regni aeterni & filios perditionis aeternae" (dicat Augustinus de Trinitate) | `adt-l15-d1e1896@1-18` | [m111736:2081](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m111736/cod-grsb22_Gi9qrR-m111736.xml:2081) |

### Notes

- **⚠ Two erroneous paragraph splits** (items 1, 5), both mid-sentence: e38320 splits at "Nihil enim fit | visibiliter" (d1e1437/d1e1467) and de6352 splits at "utraque sapientia & | utraque scientia" (d1e377/d1e409). Both encoded as contiguous parts; merging will reconcile them (@69-100 and @226-258 respectively). The de6352 case also retro-fixes batch 4: the unexplained "utraque scientia dici potest" opening of d1e409 turned out to be this quote's tail.
- **Item 3**: bookkeeping only — the candidates file still had an unchecked entry for the paragraph you merged away in batch 5; annotated as covered.
- **Item 2 (e36732)**: the paragraph's earlier Eunomius narrative ("qui secundum quod narrat Aug. 15. de Trin. cap. 20…") comes from a *different* De Trin. 15 paragraph — will surface if it's a listed candidate.
- **Three Bible-verse false positives** (items 6, 8): John 1:14 + Heb 1:1, and Matt 15:17.
- **Item 7**: another wrong book number ("17. de Trinita." for book 12 — De Trin. only has 15 books, so this one is a giveaway).

## Batch 13 (2026-07-12) — 11 candidates: 10 encoded (12 quote elements), 1 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Universas autem creaturas spirituales & corporales… quia novit" + "voluntas Dei est prima & summa causa omnium" (Augustinus 15./3. de Trinitate) — two candidates, one para | `adt-l15-d1e1842@66-83`, `adt-l3-d1e400@69-76` | [m092759:283](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m092759/cod-grsb22_Gi9qrR-m092759.xml:283) |
| <ul><li>[x] </li></ul> | 2 | Same "Universas… creaturas" quote (secundum August. 15. de Trin. … vt ait) | `adt-l15-d1e1842@66-83` | [m058588:1136](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m058588/cod-grsb22_Gi9qrR-m058588.xml:1136) |
| <ul><li>[x] </li></ul> | 3 | "non potest acies animi simul omnia… Trinitates cogitationum" (vt dicit Aug 11. de Trinita.) | `adt-l11-d1e1260@3-21` | [k065200:3932](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k065200/cod-grsb21_Gi9qrR-k065200.xml:3932) |
| <ul><li>[x] </li></ul> | 4 | "Non autem Pater & Filius simul ambo imago, sed Filius imago Patris…" (6. de Trin. cap. 2 scribitur) | `adt-l6-d1e788@73-88` | [f42722:623](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f42722/cod-GRvsd1_Gi9qrR-f42722.xml:623) |
| <ul><li>[x] </li></ul> | 5 | "In hac Trinitate non dicitur Verbum Dei nisi Filius…" (habetur 15. de Trin. cap. 17; MS omits "non frustra") | `adt-l15-d1e1886@5-19` | [f42722:609](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f42722/cod-GRvsd1_Gi9qrR-f42722.xml:609) |
| <ul><li>[x] </li></ul> | 6 | "Neque in hac Trinitate…" + "Quemadmodum hoc Patri [illi] est esse… quod Personam esse" (idem in eodem libro & cap.) | `adt-l7-d1e905@151-163`, `@216-236` | [f17097:1132](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f17097/cod-GRvsd1_Gi9qrR-f17097.xml:1132) |
| <ul><li>[x] </li></ul> | 7 | "Inferiore utendum est ad Deum; pari autem fruendum, sed in Deo" + "Nobis ergo & fratribus in Domino fruamur" (Aug. de Trin. lib. 9. cap. 8, split by "& sequitur") | `adt-l9-d1e1078@50-60`, `@86-92` | [e10930:127](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e10930/cod-GRvsd1_Gi9qrR-e10930.xml:127) |
| <ul><li>[ ] </li></ul> | 8 | **not_found** — MS quotes 1 Jn 4:16 directly, unattributed | `adt-l8-d1e1006` | Gi9qrR-m166345-d1e1982 (no edit) |
| <ul><li>[x] </li></ul> | 9 | "quod dividit inter filios Regni aeterni & filios perditionis aeternae" (secundum Aug. 15. de Trini.; MS lead-in adaptation outside) | `adt-l15-d1e1896@9-18` | [k126175:232](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k126175/cod-grsb21_Gi9qrR-k126175.xml:232) |
| <ul><li>[x] </li></ul> | 10 | "corpora grossiora & inferiora per subtiliora & potentiora quodam ordine reguntur… universa creatura per creatorem" (Vnde Aug 3. de Trinit., condensed) | `adt-l3-d1e400@3-52` | [k116053:334](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k116053/cod-grsb21_Gi9qrR-k116053.xml:334) |

### Notes

- **Item 1 (m092759-d1e551)**: both listed candidates genuine in one paragraph — the "Universas creaturas" quote plus the short "voluntas Dei" clause with its own "ubi ait, quod" attribution.
- **Item 10 (k116053)**: heavily condensed rendering of the De Trin. 3 chain-of-government passage — same situation as batch 3's g14772, encoded with the full span @3-52 as approximation.
- **Item 6 (f17097-d1e2433)**: retro-completes the paragraph first seen in batch 4; MS reads "Patri" where the source has "illi".
- **Item 3 (k065200)**: extends the same De Trin. 11 sentence encoded in batch 11 (e39991) two clauses further ("sed alternant vicissim… Trinitates cogitationum").
- The "Universas autem creaturas" passage (De Trin. 15.13) has now been quoted six times across the corpus — the most-cited passage so far.

## Batch 14 (2026-07-12) — 10 candidates: 4 encoded (4 quote elements), 6 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found ×2** — k116053-d1e4543 (hierarchies, vocabulary only) and k065200-d1e8933 (Ps 93 quoted directly) | `adt-l14-d1e1668`, `adt-l14-d1e1630` | (no edit) |
| <ul><li>[x] </li></ul> | 2 | "Praetermissis aliis innumerabilibus modis… ipsam mortem potissimum eligere voluit, ut fieret" ("15." de Trinit. — actually book 13; question → statement) | `adt-l13-d1e1495@10-25` | [k030178:196](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k030178/cod-grsb21_Gi9qrR-k030178.xml:196) |
| <ul><li>[ ] </li></ul> | 3 | "Pater & Filius simul sunt una sapientia quia una essentia, & sigillatim sapientia de sapientia…" (7. de Trin. cap. 2 scribitur) | `adt-l7-d1e864@218-235` | [f63641:137](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f63641/cod-GRvsd1_Gi9qrR-f63641.xml:137) |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — f51093-d1e255: genuine *reference* to De Trin. 15.17 ("istam quaestionem pertractat…") but wholly indirect summary; nothing to encode | `adt-l15-d1e1893` | (no edit) |
| <ul><li>[ ] </li></ul> | 5 | **not_found ×2** — f44523-d1e963 (theophany candidate, no connection) and e71027-d1e707 (thematic overlap) | `adt-l2-d1e305`, `adt-l15-d1e1893` | (no edit) |
| <ul><li>[x] </li></ul> | 6 | "Proinde verbum, quod foris sonat, signum est verbi, quod intus lucet" (15. de Trin. cap. 11 scribitur) | `adt-l15-d1e1804@1-11` | [f13632:460](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f13632/cod-GRvsd1_Gi9qrR-f13632.xml:460) |
| <ul><li>[ ] </li></ul> | 7 | **not_found** — e52685-d1e1256: the "Revera enim…" quote is De Trin. **5**.9 (adt-l5), not this De Trin. 7 candidate; overlap = John 10:30 | `adt-l7-d1e921` | (no edit) |
| <ul><li>[x] </li></ul> | 8 | "Non ergo ille Dei Filius cogitatio Dei, sed Verbum Dei dicitur" (10. cap. dicti libri = De Trin. 15.16) | `adt-l15-d1e1870@9-19` | [e39991:996](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e39991/cod-GRvsd1_Gi9qrR-e39991.xml:996) |

### Notes

- **6/10 not_found** — the highest miss rate yet, as expected at intersectionCount 8. Patterns: Bible verses quoted directly (Ps 93, John 10:30), thematic vocabulary, one wrong-source attribution (e52685: the real source De Trin. 5.9 = adt-l5 may deserve encoding when/if it appears as a candidate), and one genuine but wholly indirect chapter summary (f51093).
- **Item 2 (k030178)**: MS converts Augustine's rhetorical question ("cur non… eligeretur") into a statement ("eligere voluit") — same pattern as batch 7's f17097.
- **Item 8 (e39991-d1e1988)**: second candidate encoded in this paragraph (the "Pater genuit Verbum" pair was batch 2); its cap. 15 and cap. 13 citations point to still other candidates.

## Batch 15 (2026-07-12) — 10 candidates: 2 encoded (4 quote elements), 8 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Nec ita sane gignit istam notitiam suam mens… quae memoria continentur" (14. de Trin. cap. 6) — **⚠ split across paras d1e1709/d1e1731 mid-word** | `adt-l14-d1e1567@139-149` + `@150-171` | [e24207:828](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e24207/cod-GRvsd1_Gi9qrR-e24207.xml:828) |
| <ul><li>[x] </li></ul> | 2 | "Videtur ad memoriam mensura, ad visionem vero numerus pertinere" + "voluntas vero, quae ista coniungit &c. Ponderi similis est" (Aug. 11. de Trin. cap. ult.) | `adt-l11-d1e1279@11-19`, `@96-123` | [e19689:968](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e19689/cod-GRvsd1_Gi9qrR-e19689.xml:968) |
| <ul><li>[ ] </li></ul> | 3 | **not_found ×8** — all Bible-verse false positives: Rom 5:12/6:23 + Wis 1:13 (m137429, m120136 ×2, m118407), Eph 4:23-24 (m111736 ×2), Wis 8:1 (m101737 ×2) | various | (no edit) |

### Notes

- **⚠ Item 1 (e24207)**: the "Nec ita sane gignit…" quote (same De Trin. 14.6 passage as e22819 in batch 10) splits mid-word ("intellect:m | e conspicit") across d1e1709/d1e1731 — merge candidate. Encoded as contiguous parts.
- **Item 2 (e19689)**: the MS abbreviates the second quote with "&c." mid-quote — encoded with the full source span @96-123 covering the elision.
- **8/10 not_found**, all the shared-Bible-verse pattern. At intersectionCount ≤ 8, most m-file (Reportatio) candidates are Scripture-quotation collisions; the genuine finds are concentrated in the e/f/k files.

## Batch 16 (2026-07-12) — 10 candidates: 5 encoded (5 quote elements), 5 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found ×4** — m099109-d1e465 (×2, vocabulary), m099109-d1e349 + m092759-d1e610 vs adt-l7-d1e874 (no match) | various | (no edit) |
| <ul><li>[x] </li></ul> | 2 | "quod dividit inter filios regni aeterni & filios perditionis aeternae" (allusive "illud donum…"; following "vt ait Aug." intro leads to author's own counterfactual) | `adt-l15-d1e1896@9-18` | [m094931:409](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m094931/cod-grsb22_Gi9qrR-m094931.xml:409) |
| <ul><li>[x] </li></ul> | 3 | "Bonum hoc & bonum illud: tolle hoc, & tolle illud. tunc intelligens ipsum bonum…" (iuxta illud Aug. 8. de Trin. — book correct, text adapted) | `adt-l8-d1e952@131-156` | [m085947:2073](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m085947/cod-grsb22_Gi9qrR-m085947.xml:2073) |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — m066811-d1e460 quotes Rom 1:20 + 1 Cor 13:12 directly | `adt-l2-d1e305` | (no edit) |
| <ul><li>[x] </li></ul> | 5 | "Nihil enim visibiliter & sensibiliter hic agitur… aut iubeatur, aut permittatur" ("19." de Trin. — book 3) | `adt-l3-d1e400@81-100` | [m066811:1660](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m066811/cod-grsb22_Gi9qrR-m066811.xml:1660) |
| <ul><li>[x] </li></ul> | 6 | "Sic eius ordinata est anima, cum naturali ordine non locorum, ut supra illam non sit, nisi ille" (Augustinus xiiii. de Trinit.; "id est, Deus" gloss-tail outside) | `adt-l14-d1e1643@70-84` | [m066811:116](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m066811/cod-grsb22_Gi9qrR-m066811.xml:116) |
| <ul><li>[x] </li></ul> | 7 | "ars quaedam omnipotentis atque sapientis Dei plena omnium rationum viventium & incommutabilium" (iuxta illud Aug. de Trini. 6.) | `adt-l6-d1e826@197-207` | [k183174:824](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k183174/cod-grsb21_Gi9qrR-k183174.xml:824) |

### Notes

- **Item 2 (m094931)**: subtle case — the verbatim "quod dividit…" phrase rides inside the author's own sentence, and the explicit "vt ait Aug. de Trin." introduces a *counterfactual by the author* ("Si enim posset esse charitas sine gratia…") that is NOT in Augustine. Only the phrase was encoded; worth a look.
- **Item 3 (m085947)**: the MS reworks the syntax ("tunc intelligens ipsum bonum" for "et vide ipsum bonum si potes; ita deum videbis") — encoded over the corresponding span with the adaptation noted.
- **Item 6 (m066811-d1e216)**: MS "anima, cum naturali ordine" for source "naturarum ordine" — the reading garbles Augustine but the match is clear.
- Wrong book numbers this batch: "19. de Trin." (item 5, book 3) and note item 3's correct "8." — the first *correct* book citation for the "Bonum hoc" passage after two "5. de Trin." errors in batch 6.

## Batch 17 (2026-07-12) — 10 candidates: 5 encoded (5 quote elements), 5 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "ars quaedam omnipotentis atque sapientis Dei… incommutabilium" ("9." de Trinitate ca. ult. — actually book 6) | `adt-l6-d1e826@197-207` | [k147958:544](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k147958/cod-grsb21_Gi9qrR-k147958.xml:544) |
| <ul><li>[ ] </li></ul> | 2 | **not_found ×2** — Wis 8:1 quoted without Augustine attribution (k021496) | `adt-l3-d1e378`, `adt-l2-d1e210` | (no edit) |
| <ul><li>[x] </li></ul> | 3 | "ex ipso id est ex patre: omnia per ipsum id est per filium: omnia in ipso id est in spiritu sancto" (secundum August.; attributed paraphrase of the Rom 11:36 exegesis) | `adt-l1-d1e59@80-92` | [k012098:3959](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k012098/cod-grsb21_Gi9qrR-k012098.xml:3959) |
| <ul><li>[x] </li></ul> | 4 | "Non solum malos sed nec bonos Angelos fas est putare posse aliquid creare" (Augustinus ait; "posse aliquid creare" for "creatores") | `adt-l3-d1e425@24-34` | [k003329:2007](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k003329/cod-grsb21_Gi9qrR-k003329.xml:2007) |
| <ul><li>[ x] </li></ul> | 5 | "Verbum, quod foris sonat, signum est verbi, quod intus lucet" (15. de Trin. cap. 11) — two MSS | `adt-l15-d1e1804@2-11` ×2 | [g06755:562](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-g06755/cod-GRvsd1_Gi9qrR-g06755.xml:562), [f37690:499](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f37690/cod-GRvsd1_Gi9qrR-f37690.xml:499) |
| <ul><li>[ ] </li></ul> | 6 | **not_found ×3** — k012098 vs adt-l14-d1e1624 (Rom 11:36 only) and f72242-d1e127 ×2 (divisio textus, Rom 11:36 lemma only) | various | (no edit) |

### Notes

- **Item 3 (k012098)**: interesting case — the Rom 11:36 lemma was already encoded as a Bible quote (`rom11_36`); what I added is the *per-person exegesis* ("ex ipso, ex patre; per ipsum, per filium; in ipso, in spiritu sancto") encoded against De Trin. 1 as an attributed paraphrase. The preceding "non est confuse accipiendum" echoes the end of De Trin. 6 (adt-l6-d1e833), which is not a listed candidate for this para.
- **Item 5**: the "Verbum quod foris sonat" sentence has now been quoted four times across the corpus (f13632, g06755, f37690 ×1 each this session).
- Wrong book number: item 1 cites "9. de Trinitate" for the book-6 "ars" passage.

## Batch 18 (2026-07-12) — 10 candidates: 6 encoded (8 quote elements + 1 normalized), 4 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x ] </li></ul> | 1 | "At enim nec verbum dicendum est quod verum non est: & cum verum est verbum nostrum, tunc recte verbum vocatur" (August. 15. de Trinit. cap. 15; spans omission) | `adt-l15-d1e1858@1-25` | [f37690:227](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f37690/cod-GRvsd1_Gi9qrR-f37690.xml:227) |
| <ul><li>[x] </li></ul> | 2 | "eo quippe Filius quo Verbum, & eo Verbum, quo Filius" (secundum August. 7. de Trin. cap. 11) | `adt-l7-d1e864@55-64` | [f37690:961](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f37690/cod-GRvsd1_Gi9qrR-f37690.xml:961) |
| <ul><li>[ ] </li></ul> | 3 | **not_found ⚠ LITTERA LEMMA** — f35624-d1e116 quotes the Sentences littera ("In Deo autem nihil quod secundum accidens dicitur…"), which itself borrows De Trin. 5.5. Not encoded per lemma convention — **review whether you want littera quotes sourced to Augustine** | `adt-l5-d1e696` | (no edit) |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — f17097-d1e1630: indirect report ("August. autem negat proprie Deum dici substantiam") | `adt-l7-d1e902` | (no edit) |
| <ul><li>[x] </li></ul> | 5 | "Filius alibi loquens voce sapientiae (ipse est enim Dei sapientia) ait: Gyrum caeli circumivi sola, separavit a se Patrem" — **⚠ unattributed borrowing**, incl. Augustine's parenthesis | `adt-l1-d1e52@117-136` | [f10588:553](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f10588/cod-GRvsd1_Gi9qrR-f10588.xml:553) |
| <ul><li>[x] </li></ul> | 6 | "non ita dictum est Deo tu es patientia mea…" + "Sed ita dictum esse Deus charitas est, sicut dictum est: Deus Spiritus est" (15. de Trin. cap. 17, "ait Aug. quod" / "Vnde concludit") | `adt-l15-d1e1877@150-175`, `@230-241` | [e84651:637](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e84651/cod-GRvsd1_Gi9qrR-e84651.xml:637) |
| <ul><li>[x] </li></ul> | 7 | "Nunquam scriptum est quod Deus Pater sit maior Spiritu Sancto…" (August. 2. de Trin. cap. 6. qui ait) | `adt-l2-d1e229@3-18` | [e81896:854](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e81896/cod-GRvsd1_Gi9qrR-e81896.xml:854) |
| <ul><li>[x] </li></ul> | 8 | "Quemadmodum qui genuit & qui genitus est, ita & qui misit & qui missus est unum sunt" + "Pater mittit & Filius mittitur…" (4. de Trin. cap. penult.) | `adt-l4-d1e643@15-31`, `@1-13` | [e77122:643](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e77122/cod-GRvsd1_Gi9qrR-e77122.xml:643) |
| <ul><li>[ ] </li></ul> | 9 | **not_found ×2** — e71027-d1e263 (Rom 5:5, closes that para's list) and e59711-d1e374 (quote is De Trin. 15.14, not the listed adt-l5 candidate) | `adt-l7-d1e874`, `adt-l5-d1e756` | (no edit) |
| <ul><li>[x ] </li></ul> | 10 | normalized: e59711's pre-existing quote had `synch="85-103"` instead of `@85-103` in the source URI — converted to standard form | `adt-l15-d1e1848@85-103` | [e59711:188](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e59711/cod-GRvsd1_Gi9qrR-e59711.xml:188) |

### Notes

- **⚠ Item 3 (f35624) — policy question**: first littera-lemma case where the Sentences text being commented is itself verbatim Augustine (De Trin. 5.5). Marked not_found per the lemma convention, but flag if you want such lemmata sourced.
- **⚠ Item 5 (f10588)**: second unattributed verbatim borrowing of the project (after k001070 in batch 6) — encoded on the same too-long-to-be-coincidence reasoning.
- **Item 10**: found a legacy `synch` attribute encoding a word range outside the source URI — normalized; grep for `synch=` to find any others.

## Batch 19 (2026-07-12) — 10 candidates: 7 encoded (7 quote elements + 1 source correction), 3 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Nihil itaque accidens in Deo, quia nihil mutabile aut amissibile" (Aug. 5. de Trin. cap. 4, "concludit") — **⚠ pre-existing quote had WRONG source pointing at the MS paragraph itself; corrected** | `adt-l5-d1e690@131-140` | [e35828:469](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e35828/cod-GRvsd1_Gi9qrR-e35828.xml:469) |
| <ul><li>[x] </li></ul> | 2 | "Nefas est dicere, ut subsit Deus suae bonitati… sed in illo sit tanquam in subiecto" (Aug. 7. de Trin. cap. 5) | `adt-l7-d1e902@138-170` | [e30175:665](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e30175/cod-GRvsd1_Gi9qrR-e30175.xml:665) |
| <ul><li>[ ] </li></ul> | 3 | "non propterea Dei imago est, quia sui meminit… amare a quo facta est" (14. de Trin. cap. 12; MS "anima" for "trinitas mentis") | `adt-l14-d1e1621@5-31` | [e22819:492](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e22819/cod-GRvsd1_Gi9qrR-e22819.xml:492) |
| <ul><li>[x ] </li></ul> | 4 | "Cur itaque ibi non cognoscimus Trinitatem: An haec sapientia… non se diligit?" (Aug. 15. de Trinit. cap. 6; "cognoscimus" for "agnoscimus") | `adt-l15-d1e1750@240-257` | [e17864:834](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e17864/cod-GRvsd1_Gi9qrR-e17864.xml:834) |
| <ul><li>[x] </li></ul> | 5 | "verbum quod foris sonat, signum est verbi, quod intus **latet**" (Aug. 15 de Trinitate; fifth occurrence of this sentence) | `adt-l15-d1e1804@2-11` | [m192314:735](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m192314/cod-grsb22_Gi9qrR-m192314.xml:735) |
| <ul><li>[ ] </li></ul> | 6 | **not_found ×3** — m163618-d1e1057 (Christ's passion; Damascene/Aristotle quotes only) | `adt-l4-d1e513`, `adt-l13-d1e1492`, `adt-l13-d1e1466` | (no edit) |
| <ul><li>[x] </li></ul> | 7 | "non est alia vita hominis vitiosa atque culpabilis, quam male utens & male fruens" (Aug. 10. de Tri.) | `adt-l10-d1e1166@230-243` | [m161211:1057](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m161211/cod-grsb22_Gi9qrR-m161211.xml:1057) |
| <ul><li>[x] </li></ul> | 8 | "nullum est isto dono excellentius. Hoc enim solum est, quod dividit inter filios regni aeterni & perditionis aeternae" (Aug 15. de Tri.) | `adt-l15-d1e1896@1-18` | [m140285:1434](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m140285/cod-grsb22_Gi9qrR-m140285.xml:1434) |

### Notes

- **⚠ Item 1 (e35828) — data error found and fixed**: a pre-existing quote element carried `source="…/Gi9qrR-e35828-d1e878@217-217"` — pointing at the manuscript paragraph *itself* rather than the Augustine source. Corrected to `adt-l5-d1e690@131-140`. Worth grepping other files for self-referential sources: `grep -rn 'source="http://scta.info/resource/Gi9qrR' */cod-*.xml`.
- **Item 7 (m161211)**: the following sentence ("Dicemus ergo cum Aug. eo. lib. quod uti est assumere aliquid in facultatem voluntatis") paraphrases De Trin. 10's definition of *uti* — left indirect.
- Textual variants this batch: "latet"/"lucet" (item 5), "cognoscimus"/"agnoscimus" (item 4), "anima"/"trinitas mentis" (item 3).

## Batch 20 (2026-07-12) — 10 candidates: 1 encoded (1 quote element), 9 not_found (reviewd)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found ×9** — all Bible-verse/vocabulary collisions: Rom 5:12 ×3 (m130280, m120136-d1e839, m111736-d1e1192), Wis 1:13 (m120136-d1e504), Matt 22:37 + Eccl 9:1 (m105850), gratia/virtus vocabulary ×2 (m099109-d1e465), 1 Cor 2:9 + vocabulary ×2 (m058588-d1e1589) | various | (no edit) |
| <ul><li>[x] </li></ul> | 2 | "Species corporis, quae videtur, & imago eius impressa sensui est visio" (Sic enim ait August. 11. de Trinit. cap. 2) | `adt-l11-d1e1219@18-29` | [m074663:714](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m074663/cod-grsb22_Gi9qrR-m074663.xml:714) |

### Notes

- **9/10 not_found** — the worst hit rate so far, all in m-files at count 6. The adt-l4-d1e580 (Rom 5:12) candidate alone has now produced 8 false positives across the corpus; every one of its m-file matches has been a direct Pauline quotation.
- The one genuine find (m074663) is a textbook case: explicit "ait August. 11. de Trinit. cap. 2" with a near-verbatim clause.

## Batch 21 (2026-07-12) — 10 candidates: 4 encoded (4 quote elements), 6 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "genuit filium per omnia sibi aequalem: & est per omnia id, quod pater: non tamen pater: quia iste filius: ille pater" (secundum Aug.) — **blends two source spots; encoded with two ranges on one quote** | `adt-l15-d1e1848@78-84 + @25-37` | [m000333:150](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m000333/cod-grsb22_Gi9qrR-m000333.xml:150) |
| <ul><li>[x ] </li></ul> | 2 | "verbum, quod foris sonat, signum est verbi, quod intus latet" (vt dicit Augustinus 15. de Trinitate; inside a parenthesis) | `adt-l15-d1e1804@2-11` | [k139995:1401](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k139995/cod-grsb21_Gi9qrR-k139995.xml:1401) |
| <ul><li>[x] </li></ul> | 3 | "Secundum, quod mente aliquod aeternum, quantum possumus, capimus, non in hoc mundo sumus" (patet per August. 4. de Trini. dicentem) | `adt-l4-d1e640@210-222` | [k039964:104](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k039964/cod-grsb21_Gi9qrR-k039964.xml:104) |
| <ul><li>[x] </li></ul> | 4 | **⚠ loose end resolved**: g14772's unsourced quote Qd1e417 ("Deus suam influentiam ordinatissimis creaturae motibus…") sourced to De Trin. 3 (adt-l3-d1e397); MS interpolates a paraphrase clause mid-quote | `adt-l3-d1e397@82-100` | [g14772:210](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-g14772/cod-GRvsd1_Gi9qrR-g14772.xml:210) |
| <ul><li>[ ] </li></ul> | 5 | **not_found ×6** — John 5:26 (m007566), Nicene creed phrases (k168961), no-connection candidates (k126175, k116053), Wis 8:1 ×2 (k075328) | various | (no edit) |

### Notes

- **Item 1 (m000333)**: first use of *two space-separated ranges on one source* for a quote that stitches together two non-contiguous spots of the same source paragraph — check that this is the encoding you want for blended quotes (alternative: two separate quote elements split at the "&").
- **Item 4**: closes the batch-3 note about `Qd1e417` — the "Deus suam influentiam…" quote turned out to be De Trin. 3.4's "Inde se quibusdam ordinatissimis creaturae motibus… per cuncta diffundit" with an interpolated clause. All pre-existing unsourced quotes in g14772 are now sourced.
- The "verbum quod foris sonat" sentence reached its sixth occurrence (item 2).

## Batch 22 (2026-07-12) — 10 candidates: 5 encoded (5 new quote elements + 1 reconciled), 5 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Manifestum est Deum abusive substantiam vocari… vere ac proprie dicitur" (eodem lib. cap. 5) | `adt-l7-d1e902@172-187` | [f63641:706](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f63641/cod-GRvsd1_Gi9qrR-f63641.xml:706) |
| <ul><li>[x] </li></ul> | 2 | bonus: "Initium omnis operis Verbum" (15. de Trin. cap. 11) — listed candidate was wrong, but this quote was encodable | `adt-l15-d1e1813@46-49` | [f46046:1377](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f46046/cod-GRvsd1_Gi9qrR-f46046.xml:1377) |
| <ul><li>[x] </li></ul> | 3 | "fortassis igitur commodius dicuntur tres Personae, quam tres substantiae" (Aug. 7. de Trin. cap. 6. dicit; inside littera commentary) | `adt-l7-d1e902@262-270` | [f21019:86](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f21019/cod-GRvsd1_Gi9qrR-f21019.xml:86) |
| <ul><li>[x] </li></ul> | 4 | "Ipsa est etiam vera aeternitas qua est immutabilis Deus" (iuxta illud August. 15. de Trin. cap. 5) | `adt-l15-d1e1734@149-157` | [e99806:843](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e99806/cod-GRvsd1_Gi9qrR-e99806.xml:843) |
| <ul><li>[x] </li></ul> | 5 | "Nec etiam (scilicet Fidem) quisquam hominum videt in alio, sed unusquisque in semetipso" (Aug. 13. de Trin. cap. 2) | `adt-l13-d1e1403@101-111` | [e88383:443](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e88383/cod-GRvsd1_Gi9qrR-e88383.xml:443) |
| <ul><li>[x] </li></ul> | 6 | reconciled: e95127-d1e772's quote was already encoded (pre-existing `Qzznnmm` @71-79) — JSON status updated | `adt-l4-d1e643@71-79` | [e95127:124](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e95127/cod-GRvsd1_Gi9qrR-e95127.xml:124) |
| <ul><li>[x] </li></ul> | 7 | **not_found ×5** — littera commentary (f53145), wrong candidate f46046 (see item 2), divisio (f30889), indirect reports ×2 (f12706) | various | (no edit) |

### Notes

- **Item 2 (f46046)**: the listed candidate (adt-l2-d1e305) was wrong, but the paragraph's two real quotes were both handled: "Non confuse accipiendum est…" was already encoded (pre-existing), and "Initium omnis operis Verbum" was added — the same Sir-via-Augustine phrase encoded four times elsewhere.
- **Item 3 (f21019)**: littera-commentary paragraph, but with one true "dicit" quote inside — encoded just that, lemmata left per convention.
- Items 1 and 3 both draw on adt-l7-d1e902 — that paragraph (De Trin. 7.5's substantia discussion) has now been quoted five times.

## Batch 23 (2026-07-12) — 10 candidates: 4 encoded (4 quote elements), 6 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[x] </li></ul> | 1 | "Vt exterioribus visis hominum corda commota… semper praesentis convertantur" (Aug. 2. de Trin. cap. 5; third occurrence) | `adt-l2-d1e226@125-140` | [e80626:554](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e80626/cod-GRvsd1_Gi9qrR-e80626.xml:554) |
| <ul><li>[x] </li></ul> | 2 | **⚠ loose end resolved**: the Eunomius narrative in e36732-d1e723 ("qui secundum quod narrat Aug. 15. de Trin. cap. 20. cum non potuisset intelligere…") sourced to adt-l15-d1e1915 | `adt-l15-d1e1915@13-56` | [e36732:360](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e36732/cod-GRvsd1_Gi9qrR-e36732.xml:360) |
| <ul><li>[x] </li></ul> | 3 | "Frui est uti cum gaudio, non adhuc spei, sed iam rei" (secundum Aug. 10. de Trin.; MS "Erui" typo) | `adt-l10-d1e1178@189-200` | [e12140:143](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e12140/cod-GRvsd1_Gi9qrR-e12140.xml:143) |
| <ul><li>[x] </li></ul> | 4 | reconciled: e74632-d1e293's "Nec confuse accipiendum esse…" was already encoded (pre-existing) — listed candidate marked not_found | `adt-l6-d1e833@156-168` | [e74632:161](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e74632/cod-GRvsd1_Gi9qrR-e74632.xml:161) |
| <ul><li>[ ] </li></ul> | 5 | **not_found ×6** — Confessions cited (m201351), 1 Jn 4:16 (m166345), passion para (m163618), Isa 53/Rom 8:32 (m158550), Matt 15:17 lemma (m125279), Rom 5:12 + De Civ. Dei (m120136) | various | (no edit) |

### Notes

- **Item 2** closes the batch-12 note: the Eunomius story was indeed a separate candidate (adt-l15-d1e1915), now encoded @13-56. Both quotes in e36732-d1e723 are sourced.
- **Item 3 (e12140)**: the transcription reads "Erui" for "Frui" — encoded as-is; possible transcription-error flag for a later /flag-transcription-errors pass.

## Batch 24 (2026-07-12) — 10 candidates: 2 encoded + 2 bonus quotes, 8 not_found (reviewed)

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ x] </li></ul> | 1 | "Intelligamus Deum quantum possumus, sine qualitate bonum, sine quantitate magnum" ("7." de Tri. — actually De Trin. 5.1) | `adt-l5-d1e677@188-199` | [m065508:366](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m065508/cod-grsb22_Gi9qrR-m065508.xml:366) |
| <ul><li>[x ] </li></ul> | 2 | "Imago Dei quaerenda est in illa sola parte animi, qua superior solus Deus est… nulla interiecta natura est" (August. 11. de Trin. c. 5; heavily adapted) | `adt-l11-d1e1245@147-165` | [m004306:129](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m004306/cod-grsb22_Gi9qrR-m004306.xml:129) |
| <ul><li>[x ] </li></ul> | 3 | bonus ×2 in k168961-d1e464 (listed candidate wrong): "eo verbum, quo Filius, & eo Filius, quo verbum" (order reversed) + "verbi, quod foris sonat…" (seventh occurrence) | `adt-l7-d1e864@55-64`, `adt-l15-d1e1804@2-11` | [k168961:242](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k168961/cod-grsb21_Gi9qrR-k168961.xml:242) |
| <ul><li>[ ] </li></ul> | 4 | **not_found ×8** — Rom 1:21/Isa 59:2 ×2 (m109266), speculum para (m066811), 1 Jn 1:5 ×2 (m007566), John 5:19 (k168961-d1e293), John 3:16/Rom 8:32 (k144528), k168961-d1e464's listed candidate | various | (no edit) |

### Notes

- **Item 2 (m004306)** is the loosest encode this batch: the MS turns Augustine's "Non sane omne quod in creaturis…" into a positive rule ("Imago Dei quaerenda est in illa sola parte animi…") — encoded over the verbatim-core span @147-165; review whether the adaptation is too free.
- **Item 3**: the k-file Reportatio version (k168961) reverses "eo quippe filius quo uerbum et eo uerbum quo filius" — encoded against the same span.

## Batch 25 (2026-07-12) — 10 candidates: 0 encoded, 10 not_found (reviewed)

| ✓ | # | Disposition | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found ×10** — 1 Cor 15:24 ×3 (k131651), Rom 8:32/John 3:16 ×2 (k144528), 1 Jn 1:5 ×2 (k116053-d1e6738), hierarchy vocabulary ×2 (k116053-d1e4543), Dionysius (k126175) | various | (no edit) |

### Notes

- First zero-encode batch. One borderline: k131651-d1e1525's "Cum ergo Christus tradet regnum Deo & Patri, **id est perducet fideles ut fruantur Deo Patre**" loosely tracks Augustine's exegesis of 1 Cor 15:24 in De Trin. 1 ("id est cum perduxerit iustos… ad contemplationem dei et patris") — left unencoded as too free and unattributed, but noted in the JSON if you want it.
- Running totals: 341 candidates dispositioned (**249 encoded**, **92 not_found**), **204 remaining**.

## Batch 26 (2026-07-13) — 10 candidates: 2 encoded (2 quote elements), 8 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "iniqui (id est Diaboli) voluntatem suam habent iniustam, potestatem autem… ad laudem bonorum" (attribution follows: vt dicit Augustinus 3. de Trini. c. 9) | `adt-l3-d1e425@85-109` | [k088458:701](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k088458/cod-grsb21_Gi9qrR-k088458.xml:701) |
| <ul><li>[ ] </li></ul> | 2 | "corpora inferiora per subtiliora & potentiora quodam ordine reguntur" (Vnde August. 3. de Trinitate ait; verbatim core inside loose reportatio blend) | `adt-l3-d1e400@3-13` | [k039964:2477](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k039964/cod-grsb21_Gi9qrR-k039964.xml:2477) |
| <ul><li>[ ] </li></ul> | 3 | **not_found ×8** — De Gen. ad litt. cited ×2 (k065200), Confessions cited ×2 (k039964-d1e425), Rom 11:36 already sourced (k012098), Gen 15:1/John 6:69 ×3 (k001070) | various | (no edit) |

### Notes

- **Item 1 (k088458)**: nice example of the attribution-after-quote pattern with an "id est Diaboli" gloss inside; the MS also singularizes Augustine's plural ("Diabolus…accepit" for "iniqui…accipiunt").
- A new false-positive family emerged: **other Augustine works** (De Genesi ad litteram, Confessions) cited in the paragraph while the intersection matched a De Trin. candidate.

## Batch 27 (2026-07-13) — 10 candidates: 1 encoded, 9 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "sacra scriptura parvulis congruens nullius generis rerum verba vitavit" (loquitur Augustinus, quod; MS "sacra" for "sancta") | `adt-l1-d1e14@9-17` | [k001070:551](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k001070/cod-grsb21_Gi9qrR-k001070.xml:551) |
| <ul><li>[ ] </li></ul> | 2 | **not_found ×9** — Wis 13:5 commentary (k000003), Rom 1:20/doxology ×2 (g25010), quote already sourced to De Trin. 5.2 (f72462-d1e1877), divisio ×2 (f72242, f49262), Rom 1:20/Hilary (f65447), littera commentary ×2 (f53145) | various | (no edit) |

### Notes

- **f72462-d1e1877 / f17097-d1e2157**: the "Sicut ab eo quod est sapere dicta est sapientia… dicta essentia" quote (De Trin. 5.2, noted unencoded back in batch 3) turned out to be *already encoded* in both files (`adt-l5-d1e680@16-43`) — presumably by an earlier pass. Used findTextCandidates to pin the source; no edit needed.
- Hit rate continues to fall: batches 25–27 produced 3 encodes across 30 candidates. Remaining ~184 are count ≤ 5, dominated by divisio/littera paragraphs and Bible collisions.

## Batch 28 (2026-07-13) — 12 candidates: 5 encoded (5 quote elements), 7 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "Verbum ergo Dei Patris unigenitus Dei Filius est per omnia Patri similis & aequalis" (15. de Trin. "cap. 44" = 14) | `adt-l15-d1e1848@1-12` | [f07791:801](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f07791/cod-GRvsd1_Gi9qrR-f07791.xml:801) |
| <ul><li>[ ] </li></ul> | 2 | "Sicut enim corpus carnis nihil est aliud, quam caro, sic donum Spiritus Sancti nihil est aliud, quam Spiritus Sanctus" (15. de Trin. cap. 19) | `adt-l15-d1e1908@29-47` | [e95127:1217](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e95127/cod-GRvsd1_Gi9qrR-e95127.xml:1217) |
| <ul><li>[ ] </li></ul> | 3 | "per donum, quod est Spiritus Sanctus, in communi omnibus membris Christi multa dona… dividuntur" (15. de Trin. cap. 19; MS garbled "Quin po donum") | `adt-l15-d1e1902@215-232` | [e95127:762](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e95127/cod-GRvsd1_Gi9qrR-e95127.xml:762) |
| <ul><li>[x] </li></ul> | 4 | "Magis novit dilectionem, qua diligit, quam fratrem, quem diligit" (August. 8. de Trinit. cap. 5) | `adt-l8-d1e1003@13-22` | [e88383:429](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e88383/cod-GRvsd1_Gi9qrR-e88383.xml:429) |
| <ul><li>[x ] </li></ul> | 5 | "ad demonstrandum, quod opus fuit, ad tempus apparuerunt, & esse postea destiterunt" (August. 2. de Trinit. cap. 6; adapted lead-in outside) | `adt-l2-d1e239@46-57` | [e81896:532](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e81896/cod-GRvsd1_Gi9qrR-e81896.xml:532) |
| <ul><li>[] </li></ul> | 6 | **not_found ×7** — Hilary quote already sourced (f42722), divisio (f49262), indirect/echo ×2 (f17097), De Trin. 5.8 not listed ×2 (f07791-d1e260), no quote (e99806) | various | (no edit) |

### Notes

- **Item 6 → f07791-d1e260**: the paragraph's "una magnitudo… hoc est ibi esse, quod magnum esse" quote (cited "5. de Trin. cap. 6") comes from De Trin. 5.8, which is *not among the listed candidates* — an encodable quote left unsourced because the candidate generator missed it. Grep-able later: `una magnitudo, non tres magnitudines`.
- **Item 3 (e95127-d1e1547)**: transmission garbles the opening ("Quin po donum" for "per donum quod") — encoded over the full source span.

## Batch 29 (2026-07-13) — 10 candidates: 3 encoded + 1 bonus (4 quote elements), 6 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "exire a Patre & venire in hunc mundum, hoc est mitti" (Aug. 2. de Trin. cap. 5) — two MSS | `adt-l2-d1e210@23-33` ×2 | [e80626:149](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e80626/cod-GRvsd1_Gi9qrR-e80626.xml:149), [e77122:333](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e77122/cod-GRvsd1_Gi9qrR-e77122.xml:333) |
| <ul><li>[ ] </li></ul> | 2 | "Pater & Filius & Spiritus Sanctus relative ad creaturam unum principium, unus Creator, & unus Dominus" (5. de Trin. cap. 14, adapted) | `adt-l5-d1e756@173-189` | [e19689:233](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e19689/cod-GRvsd1_Gi9qrR-e19689.xml:233) |
| <ul><li>[ ] </li></ul> | 3 | bonus: same clause in e10930-d1e736 (cited "5. de Trin. cap. 13"; listed candidate was wrong) | `adt-l5-d1e756@173-189` | [e10930:371](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e10930/cod-GRvsd1_Gi9qrR-e10930.xml:371) |
| <ul><li>[ ] </li></ul> | 4 | **not_found ×6** — Lot narrative indirect (e80626-d1e778), De Trin. 5.9 unlisted (e52685), littera lemma (e46927), no quote ×2 (e26033, e24207-d1e337), already-encoded essentia quote (e24207-d1e1316) | various | (no edit) |

### Notes

- The De Trin. 5 "unum principium / unus Creator" tail-clause (adt-l5-d1e756@173-189) surfaced twice this batch under two different chapter citations ("cap. 14" and "cap. 13").
- Unlisted-but-real quotes noted for a future sweep: De Trin. 5.9 "Revera enim cum Pater non sit Filius…" (e52685-d1e1256, also batch 14's e52685 note) and De Trin. 5.8 "una magnitudo…" (f07791-d1e260, batch 28).

## Batch 30 (2026-07-13) — 10 candidates: 2 encoded (2 quote elements), 8 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ x] </li></ul> | 1 | "Usus in voluntate est pertractante illa, quae in memoria & intelligentia continentur…" (Aug. de Trinit. cap. penult.) | `adt-l10-d1e1178@159-180` | [e10930:520](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e10930/cod-GRvsd1_Gi9qrR-e10930.xml:520) |
| <ul><li>[ ] </li></ul> | 2 | "fruimur enim cognitis, in quibus voluntas ipsis propter se ipsa delectata conquiescit" (concludit Aug. 10. de Trin. c. 10. Dicens) | `adt-l10-d1e1166@208-219` | [de9325:244](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-de9325/cod-GRvsd1_Gi9qrR-de9325.xml:244) |
| <ul><li>[ ] </li></ul> | 3 | **not_found ×8** — Rom 8:28 (e10930-d1e1194), Wis 7:25-27 lemma collision (d1e6xx-d1e111!), Eph 4:24 ×2 (m203599), Confessions (m201351), John 1:14 ×2 (m198570), passion para (m163618) | various | (no edit) |

### Notes

- **d1e6xx-d1e111**: the very first collatio paragraph's last unchecked candidate resolves as a Wisdom-lemma collision — that paragraph is now fully dispositioned.
- The De Trin. 10 frui/uti definitions have now been quoted three ways across the corpus (uti definition, frui definition, usus definition — m161211, e12140, e10930, de9325).

## Batch 31 (2026-07-13) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Disposition | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found ×10** — Isa 53/Rom 8:32 ×3 (m158550), Rom 5:12 ×2 (m135006, m120136), natura/finis vocabulary ×2 (m130280), Matt 15:17 exegesis (m125279), 1 Cor 15:45-49 (m111736), John 1 (m105850) | various | (no edit) |

### Notes

- Second zero-encode batch; all m-file paragraphs with Bible or vocabulary collisions. 142 candidates remain, all count ≤ 4.

## Bulk triage + Batch 32 (2026-07-13) — 97 candidates: 2 encoded, 95 not_found

| ✓ | # | Item | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **Bulk triage**: 88 candidates across 55 paragraphs with **no Augustine/De Trinitate citation** marked not_found in one pass (every genuine find at count ≤5 has had an explicit citation; these are Bible/vocabulary collisions) | various | JSON notes flag "bulk triage 2026-07-13" |
| <ul><li>[ ] </li></ul> | 2 | "Non existimet aliud alio, vel maius, vel melius, vel aliqua ex parte diversum" (Aug. 7. de Trin. cap. ult.) | `adt-l7-d1e921@83-95` | [e52685:317](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e52685/cod-GRvsd1_Gi9qrR-e52685.xml:317) |
| <ul><li>[ ] </li></ul> | 3 | "tres boni, sed unus bonus" (ut vult Aug. 5. de Trin. cap. 8) | `adt-l5-d1e718@133-137` | [e52685:526](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e52685/cod-GRvsd1_Gi9qrR-e52685.xml:526) |
| <ul><li>[ ] </li></ul> | 4 | **not_found ×7 in e52685** — incl. three quotes discovered to be *already encoded* by an earlier pass: the "Quidquid ergo ad se ipsum" regula (adt-l5-d1e725@1-29), "Sicut non dicimus tres essentias" (adt-l5-d1e725@51-60), and **"Revera enim…" (adt-l5-d1e734@25-73) — closing the batch-14/29 loose end** | various | (no edit) |

### Notes

- **Triage rule** (flag if you disagree): paragraphs whose text contains no "Aug"+"Trin" co-mention were bulk-dismissed. The two known unattributed-borrowing cases (k001070, f10588) would have been missed by this rule, so there is a small residual risk in the 88; they are individually greppable via the JSON note.
- e52685 turns out to have had a substantial earlier encoding pass (quotes sourced to adt-l5-d1e725/734) that the candidates file didn't reflect — statuses now reconciled.

## Batch 33

| ✓ | Quote (MS citation) | Source | Link |
|---|---|---|---|
| ☐ | "sancta Scriptura parvulis congruens nullius generis rerum verba vitavit" (1. de Trin. cap. 1. ait) | `adt-l1-d1e14@9-17` | [d1e901:406](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-d1e901/cod-GRvsd1_Gi9qrR-d1e901.xml:406) |
| ☐ | "Deus multipliciter quidem dicitur… Magnus, bonus, sapiens, Beatus, verus… Non indigne dici videtur" (lib. 6. cap. 7. ait) | `adt-l6-d1e814@3-17` | [e13599:443](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e13599/cod-GRvsd1_Gi9qrR-e13599.xml:443) |
| ☐ | "Non enim est aliud aliquid, quam ipsum bonum, ac per hoc est etiam summum bonum" (de Trin. 3. cap. dicit) | `adt-l8-d1e958` (no range) | [e42391:423](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e42391/cod-GRvsd1_Gi9qrR-e42391.xml:423) |
| ☐ | "Filius non est Verbum de Verbo: quia Pater & Filius non ambo Verbum simul, sed solus Filius Verbum" (dicens) | `adt-l7-d1e864@17-31` | [e55878:440](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e55878/cod-GRvsd1_Gi9qrR-e55878.xml:440) |
| ☐ | "accessit quaedam actio significativa iam existentibus" (secundum ipsum) | `adt-l2-d1e235@183-189` | [e81896:707](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e81896/cod-GRvsd1_Gi9qrR-e81896.xml:707) |
| ☐ | "Ista similia videntur flammae illi, quae in rubo apparuit Moysi & illi, quam populus sequebatur in eremo" (ibidem) | `adt-l2-d1e235@204-222` | [e81896:709](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e81896/cod-GRvsd1_Gi9qrR-e81896.xml:709) |
| ☐ | "Pater genuit Verbum sibi aequale per omnia" (ut dicitur 15. de Trin. cap. 14) | `adt-l15-d1e1848@78-84` | [e98438:685](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e98438/cod-GRvsd1_Gi9qrR-e98438.xml:685) |
| ☐ | "Quoniam non aliud est Deo esse, & aliud esse magnum, vel bonum esse, sed sunt ipsum esse" (ut potest haberi ab August. 6. de Trin. capit. 5) | `adt-l5-d1e725@32-49` | [e99806:973](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e99806/cod-GRvsd1_Gi9qrR-e99806.xml:973) |

**Not found:**
- e95127-d1e2649 → adt-l15-d1e1893: indirect report ("determinat/ostendit"), no verbatim quote.
- f10588-d1e915 → adt-l1-d1e116: false positive — the MS quote there ("Si quis enim interroget, Pater solus utrum sit Deus…") is De Trin. 6.9 and was already encoded as `adt-l6-d1e823@35-71` by an earlier pass.

**Notes / judgment calls:**
1. **e13599**: MS gloss "scilicet perfectionis" kept inside the quote per the one-word-gloss convention.
2. **e42391**: loose paraphrase ("Non enim est aliud aliquid quam ipsum bonum…") — encoded resource-only, no @range. Same "ipsum bonum" family flagged earlier at e13599/e30175 for a future sweep.
3. **e55878**: opening clause "Filius non est Verbum de Verbo" is the MS's adaptation; verbatim portion begins at "Pater & Filius non ambo Verbum simul". Kept as one continuous quote since the adaptation directly condenses the same source sentence (@17-31 = "Sed non pater et filius simul ambo unum uerbum…").
4. **e81896**: two separate quotes from the same source paragraph (author interrupts with "sed magis secundum ipsum ibidem") — split per convention 1.
5. **e99806**: MS cites "6. de Trin. capit. 5" but the text matched is book 5 (adt-l5-d1e725) — wrong book number in MS, text match decides. MS adds "vel bonum esse"; encoded as close paraphrase with approximate range. The following sentence ("Illa mensura, quae mensurat esse Divinum…") reads as the author's inference, left unencoded.

## Batch 34

| ✓ | Quote (MS citation) | Source | Link |
|---|---|---|---|
| x | "Nullum est isto dono Dei excellentius. Solum est, quod dividit inter filios regni aeterni & filios perditionis aeternae" (August. 15. de Trin. cap. 18. ait) | `adt-l15-d1e1896@1-18` (bonus — not the listed candidate) | [e71027:571](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-e71027/cod-GRvsd1_Gi9qrR-e71027.xml:571) |
| x | "Si enim dixisset.. (supple de Patre) qui solus habet immortalitatem, nec sic inde separatum Filium oporteret intelligi. Neque enim: quia ipse" (1. de Trin. cap. 6. qui ait) | `adt-l1-d1e52@86-117` | [f10588:547](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f10588/cod-GRvsd1_Gi9qrR-f10588.xml:547) |
| ☐ | "res immutabiles, neque simplices proprie dicuntur substantiae" (secundum August. 7. de Trin. cap. 4) | `adt-l7-d1e902@83-90` | [f17097:570](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f17097/cod-GRvsd1_Gi9qrR-f17097.xml:570) |
| ☐ | "Deo nefas est dicere ut subsistat" (secundum August. 7. de Trin cap. 5) | `adt-l7-d1e902@138-143` | [f17097:581](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f17097/cod-GRvsd1_Gi9qrR-f17097.xml:581) |

**Not found:**
- e71027-d1e1042 → adt-l15-d1e1893 & adt-l8-d1e1006: both false positives via shared 1 Jn 4:16 material; the real Augustine quote there is De Trin. 15.18 (adt-l15-d1e1896), bonus-encoded above.
- f12706-d1e215 → adt-l1-d1e116: the paragraph's quote is De Trin. 6.9, already encoded (`adt-l6-d1e823@35-71`, [f12706:109](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f12706/cod-GRvsd1_Gi9qrR-f12706.xml:109)).
- f12706-d1e412 → adt-l1-d1e36 / adt-l1-d1e59 / adt-l15-d1e1760 (×3): indirect report ("sic intelligit eam August. cum negat…"), no verbatim quote.
- f13632-d1e2063 → adt-l5-d1e693: indirect summary ("ut potest patere ex 5. de Trin.") of Augustine's fourfold classification of divine names.
- f16841-d1e129 → adt-l15-d1e1760: divisio textus paragraph; only "ostendit per August." indirect.

**Notes / judgment calls:**
1. **f10588-d1e956** ⚠ **erroneous paragraph split**: the quote ends mid-sentence at "Neque enim: quia ipse" and continues in the next paragraph d1e1125, where the continuation is already encoded as `adt-l1-d1e52@117-136` ("Filius alibi loquens voce sapientiae…"). Merging the paragraphs will let the linter reconcile the two ranges. Note the two ranges share word 117 (off-by-one in the earlier encoding); the linter merge should resolve it.
2. **f10588-d1e956**: MS gloss "(supple de Patre)" abridges the Pauline quotation in Augustine's text; kept inside the quote per the gloss convention, and the encoded range @86-117 spans the abridged words.
3. **f17097-d1e1182**: MS reads "res *immutabiles*" where the source has "res *mutabiles*" — encoded anyway since the rest is verbatim (likely MS/print error). "In Divinis esse tres Personas" (cap. 4 & 6 "qui dicit") left unencoded as an indirect accusative+infinitive report.
4. **f17097-d1e1182**: "Deo nefas est dicere ut subsistat" is condensed from "Nefas est autem dicere ut subsistat et subsit deus bonitati suae" — encoded with the approximate range @138-143, MS "Deo" fronting kept inside.

## Batch 35

| ✓ | Quote (MS citation) | Source | Link |
|---|---|---|---|
| ☐ | "Hoc est Deo esse, quod subsistere" (August. 7. de Trin. cap. 4. ait) | `adt-l7-d1e902@247-252` | [f17097:597](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f17097/cod-GRvsd1_Gi9qrR-f17097.xml:597) |
| ☐ | "Filius eo Verbum quo Filius" (August. 7. de Trinit. cap. 2. qui ait) | `adt-l7-d1e864@55-64` (bonus) | [f37690:734](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f37690/cod-GRvsd1_Gi9qrR-f37690.xml:734) |
| ☐ | "Pater & Filius non sunt unum Verbum: quia non sunt unus Filius" (continuation, after "& quod") | `adt-l7-d1e864@17-31` (bonus) | [f37690:735](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f37690/cod-GRvsd1_Gi9qrR-f37690.xml:735) |
| ☐ | "Indivisa sunt opera Trinitatis" (secundum Aug. 1. de Trin. cap. 4) | `adt-l1-d1e36@205-210` | [f46046:1296](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f46046/cod-GRvsd1_Gi9qrR-f46046.xml:1296) |
| ☐ | "Pater & Filius & Spiritus Sanctus sunt unus Deus, & relative ad creaturam unum principium" (secundum Aug. 5. de Trin. cap. 13) | `adt-l5-d1e756@173-189` (bonus) | [f46046:1301](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f46046/cod-GRvsd1_Gi9qrR-f46046.xml:1301) |
| ☐ | "omnis essentia quae relative dicitur, est etiam aliquid excepto relativo" (ut vult Augustinus libro 7. de Trin. cap. 1) | `adt-l7-d1e855@100-109` | [f58561:1599](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f58561/cod-GRvsd1_Gi9qrR-f58561.xml:1599) |
| ☐ | "Novit omnia Deus Pater in se ipso: novit omnia in Filio" (secundum Aug. 15. de Trin. cap. 14) | `adt-l15-d1e1848@191-201` | [f67197:857](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f67197/cod-GRvsd1_Gi9qrR-f67197.xml:857) |

**Not found:**
- f17097-d1e2496 → adt-l15-d1e1760: indirect ("ubi istam quaestionem pertractat").
- f37690-d1e1491 → adt-l2-d1e201: false positive; the genuine quote there is De Trin. 7.2 (bonus-encoded above).
- f46046-d1e2833 → adt-l2-d1e340 / adt-l3-d1e489 / adt-l7-d1e908 (×3): false positives — the paragraph's real quotes were already encoded by an earlier pass (`adt-l15-d1e1813@46-49` "Initium omnis operis Verbum" and `adt-l6-d1e833@156-168` "Non confuse accipiendum est…").
- f51093-d1e255 → adt-l15-d1e1889: indirect summary ("istam quaestionem pertractat 15. de Trin. cap. 17 ostendens…").

**Notes / judgment calls:**
1. **f37690**: split into two quotes because the MS interposes reporting "& quod" between the clauses. First clause "Filius eo Verbum quo Filius" condenses source "Eo quippe filius quo uerbum et eo uerbum quo filius" (@55-64, approximate). Second clause matches the same passage encoded for e55878 in batch 33 (@17-31).
2. **f46046-d1e2689**: "Indivisa sunt opera Trinitatis" is the scholastic tag for De Trin. 1.4's "sicut inseparabiles sunt, ita inseparabiliter operentur" — encoded with that fragment's range as approximation. The following "Nam secundum eundem sicut Pater est Deus… ita Pater est principium… unum principium" matches Lombard's rendering (Sent. I d.29) rather than Augustine's own wording, so it was left outside the quote ("secundum eundem" framing).
3. **f58561**: encoded despite "ut vult" framing because the clause is verbatim De Trin. 7.1 ("omnis essentia quae relatiue dicitur est etiam aliquid excepto relatiuo"). MS "Rrelative" carries a stray drop-cap letter.
4. **f17097-d1e1263**: "Et cap. 5. hoc idem dicitur" after the quote left unencoded (bare cross-reference).

## Batch 36 (final)

| ✓ | Quote (MS citation) | Source | Link |
|---|---|---|---|
| ☐ | "Simplex illa natura sicut intelligit sentit, sicut sentit intelligit, idemque sensus qui intellectus est illi" (Aug. 15. de Trin. cap. 5. ait) | `adt-l15-d1e1734@101-115` | [f72462:495](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-f72462/cod-GRvsd1_Gi9qrR-f72462.xml:495) |
| ☐ | "Sicut Spiritus sanctus est Deus cum Patre, & Filio, & vnus Deus; sic ad creaturam sunt vnum principium non duo, vel tria principia" (Augustinus 5. de Trinita. ait) | `adt-l5-d1e756@151-183` (bonus) | [k168961:1175](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k168961/cod-grsb21_Gi9qrR-k168961.xml:1175) |
| ☐ | "contemplatio, siue visio Dei promittitur nobis actionum omnium finis, atque aeterna perfectio gaudiorum" (secundum eundem [Aug. 1. de Trin.] cap. 8) | `adt-l1-d1e87@1-12` | [m066811:164](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-m066811/cod-grsb22_Gi9qrR-m066811.xml:164) |

**Not found:**
- k147958-d1e1095 → adt-l13-d1e1387 / adt-l13-d1e1390 (×2): the genuine quote ("Verbum Dei est ars quaedam omnipotentis…") is De Trin. 6.10 and was already encoded (`adt-l6-d1e826@197-207`, [k147958:544](vscode://file/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR/Gi9qrR-k147958/cod-grsb21_Gi9qrR-k147958.xml:544)); MS cites "9. de Trinitate ca. vlti." (wrong book).
- k168961-d1e293 → adt-l15-d1e1848 / adt-l2-d1e201 (×2): shared John 5:19; "quod Aug. exponens ait" is indirect.
- k168961-d1e2413 → six candidates (adt-l1-d1e59, l15-d1e1934, l2-d1e340, l3-d1e489, l4-d1e656, l7-d1e908): all false positives — the genuine "ait" quote is De Trin. 5.14 (adt-l5-d1e756), bonus-encoded above.
- m099109-d1e465 → adt-l15-d1e1734 / adt-l2-d1e334 / adt-l6-d1e804 (×3): no Augustine citation; virtue/habit discussion citing only the Philosopher.

**Already encoded (reconciled):**
- k168961-d1e464 → adt-l15-d1e1804: already encoded @2-11 ("verbi quod foris sonat…") in an earlier bonus pass, plus `adt-l7-d1e864@55-64` in the same paragraph — JSON status reconciled.

**Notes / judgment calls:**
1. **k168961-d1e2413**: MS wording adapts De Trin. 5.14 ("sicut pater et filius unus deus et ad creaturam relatiue unus creator et unus dominus, sic relatiue ad spiritum sanctum unum principium…") into a Spirit-focused formulation — encoded as adaptation with approximate range @151-183.
2. **m066811-d1e322**: "visio est tota merces" (cited as 1. de Trin. cap. 9) has no verbatim match in the SCTA De Trin. text (likely a compressed scholastic tag) — left unencoded, flagged for the future unsourced-quotes sweep.
3. **k168961-d1e464**: "Vnde Augustinus 9. de Trinita. ait: quod diffinitio quid sit temperantia, vel intemperantia, hoc est verbum eius" remains unencoded (loose paraphrase of De Trin. 9 verbum/notitia material) — also flagged for the future sweep.

---

# ✅ COMPLETE — all 545 candidates dispositioned (280 encoded, 265 not_found)
