# wikidict-dsl-ru - Wikidata Bilingual DSL Dictionaries (Russian)

This repository makes available a collection of bilingual Russian dictionaries in DSL format derived from interwiki links (links between article titles in different languages) in Wikipedia. The data has been extracted from [Wikidata](https://www.wikidata.org/).

## Format

ABBYY Lingvo DSL is a flexible dictionary format that can be read by dictionary applications such as [Goldendict](https://github.com/goldendict/goldendict) and converted to other formats using tools such as [pyglossary](https://github.com/ilius/pyglossary). There are also a number of tools for creating DSL format dictionaries available in the [dsl-tools](https://github.com/dohliam/dsl-tools) project.

DSL files *must* be saved as UTF-16 to be usable by dictionary programs. The raw source files in this repository are saved in UTF-8 format, which is both significantly smaller in terms of file size, and also readable (and diffable) by git. However, there are fully encoded and compressed `.dsl.dz` dictionaries ready for use available in the [Releases](https://github.com/open-dsl-dict/wikidict-dsl-ru/releases) section.

You can also use the `rezip_dsl.rb` and `unzip_dsl.rb` [scripts](https://github.com/dohliam/dsl-tools/tree/master/zip_unzip) provided by the [dsl-tools](https://github.com/dohliam/dsl-tools) repo to encode/compress and decode/uncompress the dictionaries either individually or as a group.

## Data

The data directory contains the bilingual dictionaries in pairs according to [ISO language code](http://en.wikipedia.org/wiki/ISO_639-1).

The basic filename pattern is `[ISO]-ru_wikidict.dsl`, with `[ISO]` being the source language ISO code. A list of all language pairs is [below](#available-language-pairs).

## Available language pairs

Language codes | Language names
-------------- | --------------
`af-ru` | Afrikaans => Russian
`am-ru` | Amharic => Russian
`ang-ru` | Anglo-Saxon => Russian
`ar-ru` | Arabic => Russian
`arc-ru` | Aramaic => Russian
`bg-ru` | Bulgarian => Russian
`bi-ru` | Bislama => Russian
`bn-ru` | Bengali => Russian
`bo-ru` | Tibetan => Russian
`br-ru` | Breton => Russian
`bs-ru` | Bosnian => Russian
`ca-ru` | Catalan => Russian
`cdo-ru` | Min Dong => Russian
`chr-ru` | Cherokee => Russian
`chy-ru` | Cheyenne => Russian
`cr-ru` | Cree => Russian
`cs-ru` | Czech => Russian
`cy-ru` | Welsh => Russian
`da-ru` | Danish => Russian
`de-ru` | German => Russian
`el-ru` | Greek => Russian
`en-ru` | English => Russian
`eo-ru` | Esperanto => Russian
`es-ru` | Spanish => Russian
`et-ru` | Estonian => Russian
`eu-ru` | Basque => Russian
`fa-ru` | Persian => Russian
`ff-ru` | Fula => Russian
`fi-ru` | Finnish => Russian
`fr-ru` | French => Russian
`ga-ru` | Irish => Russian
`gan-ru` | Gan => Russian
`gd-ru` | Scottish Gaelic => Russian
`gu-ru` | Gujarati => Russian
`gv-ru` | Manx => Russian
`ha-ru` | Hausa => Russian
`hak-ru` | Hakka => Russian
`haw-ru` | Hawaiian => Russian
`he-ru` | Hebrew => Russian
`hi-ru` | Hindi => Russian
`hr-ru` | Croatian => Russian
`ht-ru` | Haitian => Russian
`hu-ru` | Hungarian => Russian
`hy-ru` | Armenian => Russian
`id-ru` | Indonesian => Russian
`ig-ru` | Igbo => Russian
`is-ru` | Icelandic => Russian
`it-ru` | Italian => Russian
`iu-ru` | Inuktitut => Russian
`ja-ru` | Japanese => Russian
`jbo-ru` | Lojban => Russian
`jv-ru` | Javanese => Russian
`ka-ru` | Georgian => Russian
`kg-ru` | Kongo => Russian
`ki-ru` | Kikuyu => Russian
`kl-ru` | Greenlandic => Russian
`km-ru` | Khmer => Russian
`ko-ru` | Korean => Russian
`la-ru` | Latin => Russian
`lg-ru` | Luganda => Russian
`lo-ru` | Lao => Russian
`lt-ru` | Lithuanian => Russian
`lv-ru` | Latvian => Russian
`mg-ru` | Malagasy => Russian
`mi-ru` | Maori => Russian
`mn-ru` | Mongolian => Russian
`ms-ru` | Malay => Russian
`mt-ru` | Maltese => Russian
`nah-ru` | Nahuatl => Russian
`ne-ru` | Nepali => Russian
`nl-ru` | Dutch => Russian
`nn-ru` | Norwegian (Nynorsk) => Russian
`no-ru` | Norwegian => Russian
`nv-ru` | Navajo => Russian
`ny-ru` | Chichewa => Russian
`oc-ru` | Occitan => Russian
`pa-ru` | Punjabi => Russian
`pi-ru` | Pali => Russian
`pl-ru` | Polish => Russian
`ps-ru` | Pashto => Russian
`pt-ru` | Portuguese => Russian
`qu-ru` | Quechua => Russian
`ro-ru` | Romanian => Russian
`sa-ru` | Sanskrit => Russian
`se-ru` | Northern Sami => Russian
`sh-ru` | Serbo-Croatian => Russian
`sk-ru` | Slovak => Russian
`sl-ru` | Slovenian => Russian
`sn-ru` | Shona => Russian
`so-ru` | Somali => Russian
`sq-ru` | Albanian => Russian
`sr-ru` | Serbian => Russian
`sv-ru` | Swedish => Russian
`sw-ru` | Kiswahili => Russian
`ta-ru` | Tamil => Russian
`te-ru` | Telugu => Russian
`th-ru` | Thai => Russian
`tl-ru` | Tagalog => Russian
`tpi-ru` | Tok Pisin => Russian
`tr-ru` | Turkish => Russian
`ug-ru` | Uyghur => Russian
`uk-ru` | Ukrainian => Russian
`ur-ru` | Urdu => Russian
`vi-ru` | Vietnamese => Russian
`wo-ru` | Wolof => Russian
`wuu-ru` | Wu => Russian
`xh-ru` | Xhosa => Russian
`yi-ru` | Yiddish => Russian
`yo-ru` | Yoruba => Russian
`za-ru` | Zhuang => Russian
`zh-ru` | Chinese (Mandarin) => Russian
`zh_classical-ru` | Classical Chinese => Russian
`zh_min_nan-ru` | Min Nan => Russian
`zh_yue-ru` | Cantonese => Russian
`zu-ru` | Zulu => Russian

## Statistics

### Dictionary size

Language pair | # of entries
------------- | ------------
`af-ru` | 22103
`am-ru` | 5654
`ang-ru` | 2328
`ar-ru` | 117691
`arc-ru` | 1311
`bg-ru` | 108412
`bi-ru` | 451
`bn-ru` | 19165
`bo-ru` | 2629
`br-ru` | 32330
`bs-ru` | 33331
`ca-ru` | 175715
`cdo-ru` | 1970
`chr-ru` | 459
`chy-ru` | 564
`cr-ru` | 94
`cs-ru` | 146517
`cy-ru` | 24170
`da-ru` | 93247
`de-ru` | 419832
`el-ru` | 55319
`en-ru` | 628522
`eo-ru` | 117080
`es-ru` | 343844
`et-ru` | 64649
`eu-ru` | 83491
`fa-ru` | 147974
`ff-ru` | 198
`fi-ru` | 169724
`fr-ru` | 435978
`ga-ru` | 20548
`gan-ru` | 4461
`gd-ru` | 10464
`gu-ru` | 3915
`gv-ru` | 3911
`ha-ru` | 386
`hak-ru` | 2492
`haw-ru` | 1836
`he-ru` | 93640
`hi-ru` | 24541
`hr-ru` | 67685
`ht-ru` | 10893
`hu-ru` | 123444
`hy-ru` | 92615
`id-ru` | 96919
`ig-ru` | 727
`is-ru` | 21176
`it-ru` | 383559
`iu-ru` | 340
`ja-ru` | 224129
`jbo-ru` | 1152
`jv-ru` | 15638
`ka-ru` | 54145
`kg-ru` | 802
`ki-ru` | 295
`kl-ru` | 1549
`km-ru` | 1587
`ko-ru` | 126028
`la-ru` | 66391
`lg-ru` | 159
`lo-ru` | 1083
`lt-ru` | 76351
`lv-ru` | 41839
`mg-ru` | 28109
`mi-ru` | 2141
`mn-ru` | 11262
`ms-ru` | 86030
`mt-ru` | 2197
`nah-ru` | 6911
`ne-ru` | 6955
`nl-ru` | 315264
`nn-ru` | 48733
`no-ru` | 160516
`nv-ru` | 1585
`ny-ru` | 95
`oc-ru` | 51284
`pa-ru` | 8202
`pi-ru` | 2203
`pl-ru` | 372401
`ps-ru` | 2748
`pt-ru` | 302078
`qu-ru` | 10903
`ro-ru` | 137094
`sa-ru` | 4956
`se-ru` | 5151
`sh-ru` | 100925
`sk-ru` | 95665
`sl-ru` | 52331
`sn-ru` | 1478
`so-ru` | 2317
`sq-ru` | 24569
`sr-ru` | 122060
`sv-ru` | 237970
`sw-ru` | 16095
`ta-ru` | 22016
`te-ru` | 8087
`th-ru` | 47694
`tl-ru` | 31312
`tpi-ru` | 1262
`tr-ru` | 114464
`ug-ru` | 2239
`uk-ru` | 310596
`ur-ru` | 26705
`vi-ru` | 144734
`wo-ru` | 890
`wuu-ru` | 2041
`xh-ru` | 254
`yi-ru` | 7203
`yo-ru` | 13433
`za-ru` | 616
`zh-ru` | 234289
`zh_classical-ru` | 2271
`zh_min_nan-ru` | 10040
`zh_yue-ru` | 17169
`zu-ru` | 549

### Top ten dictionaries by number of entries

Language pair | # of entries
------------- | ------------
`en-ru` | 628522
`fr-ru` | 435978
`de-ru` | 419832
`it-ru` | 383559
`pl-ru` | 372401
`es-ru` | 343844
`nl-ru` | 315264
`uk-ru` | 310596
`pt-ru` | 302078
`sv-ru` | 237970

## License

According to the Wikidata website:

> All structured data from the main and property namespace is available under the Creative Commons CC0 License

The data in this repository is therefore made available under the same [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/) as that used by the Wikidata project. All of the data has been derived from the Wikidata JSON format [database dumps](https://dumps.wikimedia.org/wikidatawiki/entities/).
