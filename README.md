# ie-domain-name-lists

A collection of Irish domain name and word-derived `.ie` datasets.



ie_domain_names.txt 187,062 .ie domain names 


## Files in this repository

| File | Rows | Type | Columns / Format | Notes |
|------|------|------|------------------|-------|
| `ie_domain_names.txt` | 187,062 | TXT | one domain per line | Large list of `.ie` domain names |
| `1_character_.ie_domains.txt` | 36 | TXT | one domain per line | Generated 1-character combinations (`a.ie` ... `z.ie`, digits) |
| `2_character_.ie_domains.txt` | 1,296 | TXT | one domain per line | Generated 2-character combinations |
| `3_character_.ie_domains.txt` | 46,656 | TXT | one domain per line | Generated 3-character combinations |
| `4_character_.ie_domains.txt` | 1,679,616 | TXT | one domain per line | Generated 4-character combinations |
| `irish_firstnames.csv` | 1,960 | CSV | `Name,births,domain` | Irish first names mapped to `.ie` domains |
| `irish_counties_domainnames.csv` | 32 | CSV (single column, no header) | one domain per line | All 32 Irish counties as `.ie` domains |
| `words_ending_in_ie_by_popularity.csv` | 382 | CSV | `word,domainname` | Words ending in `ie` plus corresponding `.ie` domain |
| `ie_domains_from_words.csv` | 381 | CSV (single column, no header) | one domain per line | Domain list derived from words ending in `ie` |
| `ie_domains_from_cisco_umbrella_by_popularity.csv` | 461 | CSV (two columns, no header) | `rank,domain` | Popular `.ie` domains by DNS traffic (Cisco Umbrella) |
| `ie_domains_magestic_millions_dec_2019.csv` | 1,265 | CSV | `GlobalRank,TldRank,Domain,...` | `.ie` domains from Majestic Million snapshot (Dec 2019) |

## Notes

- Row counts are line-based and include header rows where present.
- CSV files are intentionally mixed: some include headers, some are plain single-column lists.
- Domain labels in `.ie` names generally use letters, digits, and hyphens (subject to registry rules).
