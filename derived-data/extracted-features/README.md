This directory contains the HTRC Extracted Features files for 1997 volumes of English-language fiction identified by the History of Black Writing at University of Kansas as being authored by African American authors. There is an separate JSON file for each file. 

The file name prefix is the “clean” HathiTrust ID for the volume. See “clean” HT IDs below. 

For example the HT volume ID for the Indiana University copy of Donald Goine’s _Eldorado Red_ is `inu.30000111164251` and the corresponding JSON file is `inu.30000111164251.json.`

Each json file is compressed with open source [bzip2](http://sourceware.org/bzip2/) compression and may be uncompressed with standard compression/archive utilities available on most operation systems.

Information about each volume is contained in the metadata section of each JSON file, and the HathiTrust IDs included in the metadata can be used to gather further information about each volume.

For more information on the HTRC Extracted Features Dataset, including detailed information on the data fields in each file, see <https://doi.org/10.13012/R2TE-C227>.

For more information on the History of Black Writing, see <https://hbw.ku.edu/>

## Clean HT IDs

The “clean” version of a volume ID, replaces  the following characters `:`,`/`, and `.` with `+` , `=`, and `,` respectively. 

|original volume ID character | clean volume ID character |
|:---                         | :---                      |
| `:`                         | `+`                       |
| `/`                         | `=`                       |
