---
license: cc-by-nc-4.0
language:
- en
task_categories:
- text-generation
- question-answering
- summarization
tags:
- travel
- tourism
- argentina
- patagonia
- buenos-aires
- cordoba
- argentina-travel
- itineraries
- travel-guides
- article-corpus
- creator-archive
- retrieval
- media-archive
size_categories:
- n<1K
---

# Che Argentina Travel Article Corpus

This dataset contains a structured corpus of long-form Argentina travel articles published on **CheArgentinaTravel.com** by the Samuel & Audrey Media Network.

The corpus includes **88 article records** covering Argentina travel guides, itineraries, cultural experiences, regional food, transportation, accommodations, local logistics, and destination planning. It includes coverage of major areas such as Buenos Aires and Patagonia, along with regional destinations in Córdoba and other parts of Argentina.

This dataset is intended for non-commercial research, retrieval workflows, travel writing analysis, archive search, destination content review, and study of Argentina-focused travel publishing.

## Canonical links

- Hugging Face dataset: https://huggingface.co/datasets/samuelandaudreymedianetwork/che-argentina-travel-article-corpus
- GitHub repository: https://github.com/samuelandaudreymedianetwork/che-argentina-travel-article-corpus
- Zenodo DOI: https://doi.org/10.5281/zenodo.18665586
- Source website: https://cheargentinatravel.com

## Dataset contents

| Record type | Count |
|---|---:|
| `article` | 88 |

## Snapshot details

| Field | Value |
|---|---:|
| Article records | 88 |
| Records with titles | 88 |
| Records with content hashes | 88 |
| Language | English |
| Approximate total words | 225,408 |
| Approximate total characters | 1,281,808 |

## What is included

- Full article text
- Article titles
- Stable record identifiers
- Source/domain metadata
- Language metadata
- Content hashes for deduplication and integrity checks
- JSONL and CSV formats
- Data dictionary, schema, citation file, license file, manifest, checksums, and llms exports

Each JSONL or CSV row represents one full-length article record.

## Files

- `che-argentina-travel.jsonl` — canonical structured article records
- `che-argentina-travel.jsonl.gz` — compressed JSONL
- `che-argentina-travel.csv` — spreadsheet-friendly export
- `che-argentina-travel.csv.gz` — compressed CSV
- `DATA_DICTIONARY.md` — field definitions
- `SCHEMA.json` — machine-readable schema
- `CITATION.cff` — citation metadata
- `LICENSE.txt` — license text
- `MANIFEST.json` — package manifest
- `SHA256SUMS.txt` — file checksums
- `llms.txt` — short machine-readable dataset guide
- `llms-che-argentina-travel-article-corpus.txt` — full plain-text export

## Related uses

This dataset can be used alongside Samuel & Audrey Media Network video transcripts, YouTube metadata indexes, photography metadata archives, and Argentina/Patagonia travel archives for cross-media retrieval and destination analysis.

## Limitations

This dataset contains article text and metadata, not a complete or current travel guide.

Some articles may include historical prices, older transport information, outdated business details, changed routes, accommodation information, or destination conditions that have evolved since publication. Users should verify current travel details from up-to-date official, local, and operator sources before relying on practical information.

The corpus may include older writing styles, legacy formatting, affiliate callouts, and content created across different stages of the Che Argentina Travel website.

## Notes on cleanup and naming

The public Hugging Face repository uses the stable slug `che-argentina-travel-article-corpus`. The canonical data files retain the concise `che-argentina-travel` basename because it matches the source website and original corpus identity.

The previous full `llms.txt` bundle was replaced with a short `llms.txt` guide plus a separate full export file named `llms-che-argentina-travel-article-corpus.txt`.

## License

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

For commercial licensing inquiries, expanded usage rights, or partnership questions, contact nomadicsamuel@gmail.com.

## Citation

Samuel & Audrey Media Network. (2026). *Che Argentina Travel Article Corpus*. Zenodo. https://doi.org/10.5281/zenodo.18665586
