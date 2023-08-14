# Introduction
The `workset` directory contains multiple data files with metadata about the workset and its volumes. Details about each file, its format, and structure are included below
explain:

## `history-of-black-writing-works.csv`

These are simple CSV files listing the volume ID and some additional metadata for each volume in the worksets.

The columns in the CSV file are:

- id (volume identifier)
- title 
- year (year of publication)
- language (volume language represented as ISO-369-3 language code) 
- authors

Example:

| id | title | year | language | authors |
|:---|:---   |:---  |:---      |:---     |
| uva.x001016358 | The children of Sisyphus / | 1964 | eng | Patterson, Orlando 1940- |
| mdp.39015016452230 | Trumbull park, a novel. | 1959 | eng | Brown, Frank London |
| mdp.39015069290172 | A lova' like no otha' / Stephanie Perry Moore. | 2003 | eng | Moore, Stephanie Perry |
| mdp.39015000544745 | Portrait of a young man drowning. | 1962 | eng | Perry, Charles 1924-1969 |
| uc1.32106005680761 | Clotel; or, The president's daughter : a narrative of slave life in the United States / by William Wells Brown. | 1984 | eng | Perry, Charles 1924-1969 |


## `history-of-black-writing-works.json`

These are JSON files with some basic metadata about the worksets themselves, including the creators of and contributors to the worksets. Also included is a list of workset IDs as persistent links to the item in the [HathiTrust Digital Library](https://hathitrust.org).

