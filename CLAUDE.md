# CLAUDE.md — holcotwisdom Project

## Encoding Quotations

Use the `/encode-quotes` skill with the following project-specific arguments:

```
/encode-quotes /Users/jcwitt/Projects/scta/scta-texts/Gi9qrR bible_candidates_for_Gi9qrR.json {codexid}_{dir_id}.xml
```

- **Base directory:** `/Users/jcwitt/Projects/scta/scta-texts/Gi9qrR`
- **Candidates file:** `bible_candidates_for_Gi9qrR.json`
- **XML filename pattern:** `{codexid}_{dir_id}.xml` (e.g. `Gi9qrR-d1e6xx/cod-GRvsd1_Gi9qrR-d1e6xx.xml`)

## Project-Specific Notes

### Multi-verse quotes: combined source attribute
When a MS quote spans two or more consecutive verses, combine them in a single `<quote>` element with space-separated source URIs:
```xml
<quote source="http://scta.info/resource/deut17_18@1-20 http://scta.info/resource/deut17_19@1-25">quote text...</quote>
```
Do NOT use two separate `<quote>` elements for a continuous passage.

### Linter behavior
- Auto-adds `xml:id` to `<quote>` elements — do not add manually
- Also reconciles multi-verse spans and updates `source` to combined form automatically
- If "file unexpectedly modified" error on Edit, re-read before retrying
