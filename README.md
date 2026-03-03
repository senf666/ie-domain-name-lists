# ie domain name lists

Lists upon lists of domain names.

A collection of Irish-specific word lists and domain name datasets.

## .ie domain name list

170k-ie-domainnames.txt	        170,000 registered .ie domain names	
170k-ie-domainnames.parquet	     same as above but in Parquet format

## .ie Domain Rules

Domain names can only use:
- Letters
- Numbers
- The fada character (acute accent)
- Hyphens ("-")

Spaces and other symbols are not permitted. Names cannot begin or end with a hyphen. Names are not case sensitive. Domains cannot exceed 63 characters.

## Domain Lists

| File | Description | Format | Source |
|------|-------------|--------|--------|
| irish_firstnames.csv | Most common registered Irish first names (male & female), 1964-2016 | name, count, domain | Central Statistics Office |
| irish_counties_domainnames.csv | All 32 Irish counties as .ie domains | domain | |
| words_ending_in_ie_by_popularity.csv | Words ending in "ie" ordered by popularity with corresponding .ie domains | word, domainname | |
| ie_domains_from_cisco_umbrella_by_popularity.csv | Popular .ie domains by DNS traffic | rank, domain | Cisco Umbrella |
| ie_domains_magestic_millions_dec_2019.csv | .ie domains ranked by link profiles (Dec 2019) | GlobalRank, TldRank, Domain, etc. | [Majestic Million](https://blog.majestic.com/development/majestic-million-csv-daily/) |
| ie_domains_from_words.csv | .ie domains generated from words ending in "ie" (381 domains) | domain | Derived from words_ending_in_ie_by_popularity.csv |
| 170k-ie-domainnames.txt | 170,000 registered .ie domain names | domain | |
| 170k-ie-domainnames.parquet | 170,000 registered .ie domain names in Parquet format | domain | Converted from 170k-ie-domainnames.txt |
| 1_character_.ie_domains.txt | All 36 possible 1-character .ie domains | domain | Generated |
| 2_character_.ie_domains.txt | All 1,296 possible 2-character .ie domains | domain | Generated |
| 3_character_.ie_domains.txt | All 46,656 possible 3-character .ie domains | domain | Generated |
| 4_character_.ie_domains.txt | All 1,679,616 possible 4-character .ie domains | domain | Generated |
