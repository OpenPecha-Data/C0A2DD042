# Open Parallel Corpus

This corpus contains a growing collection of multilingual texts aligned to Tibetan texts (bo) at the sentence level. 

## Current total stats
- **2,08,736** Tibetan segments 
- **4,611** files 
- Files from [Lotsawa House](https://www.lotsawahouse.org/) and [84,000](https://read.84000.co/)

| Languages: |   bo-en   |   bo-es  |   bo-fr  |   bo-de  |  bo-it |  bo-nl |   bo-zh  |  bo-pt |
|:------------:|:------:|:-----:|:-----:|:-----:|:---:|:---:|:-----:|:---:|
| Segments:     | 2,08,736 | 3,481 | 8,971 | 5,892 | 1,129 | 889 | 2,573 | 2018 |

A list of all included texts can be found in the corpus's [text pairs catalog](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/text-pairs-catalog.csv).

## Table of contents
<p align="center">
  <a href="#views">Views</a> •
  <a href="#dataset-breakdown">Dataset breakdown</a> •
  <a href="#coming-soon">Coming soon</a> •
  <a href="#corpus-owners">Corpus owners</a> •
  <a href="#how-to-get-help">How to get help</a> •
  <a href="#terms-of-use">Terms of use</a>
</p>

## Views

This collection contains two views of the same data: one for text pairs and one for TMs.

### View 1 - Text pairs

#### What it is

[Plain text pairs](https://github.com/OpenPecha-Data/C0A2DD042/tree/main/text-pairs) in .txt format ([see detailed catalog](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/text-pairs-catalog.csv)).

<details >
<summary>More</summary>

Text pairs consist of matching sets of `.txt` files. They include a file containing a Tibetan text with one chunk of text per line and one or more `.txt` files of translations of the text into other languages. Translation files are also split into lines to correspond to the line breaks in the Tibetan file.

Titles of any file can be found on line 1 of the file or by searching for a file's identifying number (e.g. A00023033) in the corpus's [text pairs catalog](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/text-pairs-catalog.csv).

Text pairs or groups share the same identifying number and differ only in the ending language tag.

Example:
- A00023033-bo.txt
- A00023033-en.txt
- A00023033-fr.txt

As stated above, these files are aligned by line to match the Tibetan version. 

Example:
Tibetan text
```
1 ༄༅། །འཆི་མེད་འཕགས་མའི་སྙིང་ཐིག་གི་བརྒྱུད་པའི་གསོལ་འདེབས་ཚེ་དབང་བཅུད་འཛིན་ཞེས་བྱ་བ་བཞུགས་སོ། །
2 རང་བྱུང་རྟག་པའི་རྡོ་རྗེ་ཚེ་དཔག་མེད། །
3 འཆི་བདག་བདུད་འཇོམས་གཙུག་ཏོར་རྣམ་པར་རྒྱལ། །
```
English text
```
1 The Fount of Longevity Chimé Phakmé Nyingtik Lineage Prayer
2 Amitāyus, Boundless Life, natural, everlasting and indestructible,
3 Uṣṇīṣa-Vijayā, Victorious Conqueror of māra , Lord of Death,
```
French text
```
1 La Fontaine de longévité La prière à la lignée de Chimé p'akmé nyingthik
2 Existant par lui-même et éternel, indestructible Amitāyus,
3 Celle qui triomphe du démon Seigneur de la mort, Uṣṇīṣa Vijayā,
```

</details>

#### Who it's for

View 1 is intended for developers who want to train a translation model.

**How to use it**

This data can be fed into machine translation training pipelines such as using this and that.

### View 2 - TMs

1. [TM files](https://github.com/OpenPecha-Data/C0A2DD042/tree/main/tmx) in .tmx format ([see detailed catalog](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/tmx-catalog.csv)). 

> **Note**: Contact us [here](<link to issue at a place TBD>) if you need a different format

## Dataset breakdown

### Lotsawa House
| Source: | https://www.lotsawahouse.org/ |
| --- | --- |
|Pairs: | 76,135 | 
|Files: | 4,405 |
|Accessed on: | 2023-01-04 12:44:15.146037 |
|Crawler: | [LH Crawler](https://github.com/jungtop/lotsawa_house_parser/blob/master/parser_v2.py) |
|Parser: | [LH Parser](https://github.com/jungtop/lotsawa_house_parser/blob/master/parser_v2.py) |
|Layers: | **Base** + `Segments` |

| Languages: |   bo-en   |   bo-es  |   bo-fr  |   bo-de  |  bo-it |  bo-nl |   bo-zh  |  bo-pt |
|:------------:|:------:|:-----:|:-----:|:-----:|:---:|:---:|:-----:|:---:|
| Segments:     | 76,135 | 3,481 | 8,971 | 5,892 | 1,129 | 889 | 2,573 | 2018 |

A list of included texts can be found [here](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/text-pairs-catalog.csv).

### 84000-translation-memory

|Source | https://read.84000.co/ |
| --- | --- |
|Pairs | 132601 |
|Files | 206 |
|Accessed On | 2018-09-26T07:14:13.428Z |
|Crawler: | [TMX Crawler](https://github.com/OpenPecha/Toolkit/blob/master/openpecha/alignment/tmx/create_opf.py) |
|Parser: | [TMX Parser](https://github.com/OpenPecha/Toolkit/blob/master/openpecha/alignment/tmx/create_opf.py) |
|Layers | **Base** + `Segments` |

| Languages: |   bo-en   | 
|:------------:|:------:|
| Segments:     | 1,32,601 |

A list of included texts can be found [here](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/text-pairs-catalog.csv).

## Coming Soon

- **700** more texts from [Lotsawa House](https://www.lotsawahouse.org/)
- **87** texts from [Oslo](https://www2.hf.uio.no/polyglotta/index.php?page=library&bid=2)

## Corpus owners

- [@jungtop](https://github.com/jungtop)
- [@ngawangtrinley](https://github.com/ngawangtrinley)

## How to get help
* Email us at openpecha[at]gmail.com.
* Join our [discord](https://discord.com/invite/7GFpPFSTeA).
* File an [issue](/issue).

## Terms of use
This corpus is licensed under the [MIT License](/LICENSE.md).
