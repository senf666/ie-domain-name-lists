# ie-domain-name-lists

A collection of Irish domain name and word-derived `.ie` datasets.


## Files in this repository

| File | Rows | Type | Columns / Format | Notes |
|------|------|------|------------------|-------|
| `ie_domain_names.txt` | 187,062 | TXT | one domain per line | Large list of `.ie` domain names |
| `lists/1_character_.ie_domains.txt` | 36 | TXT | one domain per line | Generated 1-character combinations (`a.ie` ... `z.ie`, digits) |
| `lists/2_character_.ie_domains.txt` | 1,296 | TXT | one domain per line | Generated 2-character combinations |
| `lists/3_character_.ie_domains.txt` | 46,656 | TXT | one domain per line | Generated 3-character combinations |
| `lists/4_character_.ie_domains.txt` | 1,679,616 | TXT | one domain per line | Generated 4-character combinations |
| `lists/irish_firstnames.csv` | 1,960 | CSV | `Name,births,domain` | Irish first names mapped to `.ie` domains |
| `lists/irish_counties_domainnames.csv` | 32 | CSV (single column, no header) | one domain per line | All 32 Irish counties as `.ie` domains |
| `lists/words_ending_in_ie_by_popularity.csv` | 382 | CSV | `word,domainname` | Words ending in `ie` plus corresponding `.ie` domain |
| `lists/ie_domains_from_words.csv` | 381 | CSV (single column, no header) | one domain per line | Domain list derived from words ending in `ie` |
| `lists/ie_domains_from_cisco_umbrella_by_popularity.csv` | 461 | CSV (two columns, no header) | `rank,domain` | Popular `.ie` domains by DNS traffic (Cisco Umbrella) |
| `lists/ie_domains_magestic_millions_dec_2019.csv` | 1,265 | CSV | `GlobalRank,TldRank,Domain,...` | `.ie` domains from Majestic Million snapshot (Dec 2019) |

## Notes

- Row counts are line-based and include header rows where present.
- CSV files are intentionally mixed: some include headers, some are plain single-column lists.
- Repository layout: `ie_domain_names.txt` is at root; all other datasets are in `lists/`.
- Domain labels in `.ie` names generally use letters, digits, and hyphens (subject to registry rules).

## License

This repository is licensed under `CC BY-NC 4.0` (Creative Commons Attribution-NonCommercial 4.0 International).

- Commercial use is not permitted.
- Attribution is required.
- See `LICENSE` for details and the full license URL.
