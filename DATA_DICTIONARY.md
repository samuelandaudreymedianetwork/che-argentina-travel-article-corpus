# Che Argentina Travel Article Corpus — Data Dictionary

This file defines the fields used in `che-argentina-travel.jsonl` and `che-argentina-travel.csv`.

| Field | Description |
|---|---|
| `record_id` | Stable dataset record identifier. |
| `record_type` | Record type. For this dataset, records use `article`. |
| `id` | Original stable article identifier from the source export. |
| `dataset` | Current dataset slug. |
| `source` | Original source label from the source export. |
| `source_site` | Human-readable source website name. |
| `source_url` | Source website URL. |
| `lang` | Language code from the source export. |
| `language` | Normalized language code alias. |
| `title` | Article title. |
| `text` | Full article text. |
| `domain` | Source domain. |
| `content_hash` | Integrity / deduplication hash of the article text. |
| `license` | Dataset license. |

## Notes

The dataset preserves the source article text. Cleanup focused on package naming, documentation, metadata consistency, and file organization.

Some article text may contain older travel information, legacy formatting, affiliate callouts, or historical references from the original website publication context.
