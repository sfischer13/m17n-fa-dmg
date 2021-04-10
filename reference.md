# Reference (m17n-fa-post)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Introduction](#introduction)
- [Letters](#letters)
  - [Persian](#persian)
  - [Arabic](#arabic)
  - [Alef](#alef)
  - [Hamza](#hamza)
  - [Miscellaneous](#miscellaneous)
- [Diacritics](#diacritics)
- [Numbers](#numbers)
  - [Perso-Arabic](#perso-arabic)
  - [Western Arabic](#western-arabic)
  - [Eastern Arabic](#eastern-arabic)
- [Symbols](#symbols)
  - [Punctuation](#punctuation)
  - [Typography](#typography)
  - [Mathematics](#mathematics)
- [Space and (Non-)Joiners](#space-and-non-joiners)
- [Bi-directional text](#bi-directional-text)
  - [Marks](#marks)
  - [Isolates](#isolates)
  - [Embeddings](#embeddings)
  - [Overrides](#overrides)
  - [Pops](#pops)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

The `m17n` library has its quirks. [Dead keys](https://en.wikipedia.org/wiki/Dead_key) and [AltGr](https://en.wikipedia.org/wiki/AltGr_key) might not work if you use a non-US keyboard. You can still fall back on one of the alternative keyboard shortcuts (e.g. *c* instead of *`*).

* `A` means `Alt`
* `C` means `Ctrl`
* `S` means `Shift`

## Letters

### Persian

Letter  | `m17n`              | Name  | DMG           | EI    | Wehr
------- | ------------------- | ----- | ------------- | ----- | -----
‎ء      | ` / **H**           | hamze | ʾ             | ʾ     | ʼ
`       | ``                  |       |               |       |
‎ا      | **a**               | alef  | **ā** / **ʾ** |       | ā
‎ب      | b                   | be    | b             | b     | b
‎پ      | p                   | pe    | p             | p     |
‎ت      | t                   | te    | t             | t     | t
‎ث      | s- / t-             | se    | s̱ (ṯ)         | ṯ     | ṯ
‎ج      | g^ / **G** / j      | jim   | ǧ             | j     | ǧ / j
‎چ      | c^ / **c** / **C**  | che   | č             | č     |
‎ح      | h.                  | he    | ḥ             | ḥ     | ḥ
‎خ      | **h-** / k- / **x** | khe   | **ḫ**         | ḵ     | ḫ / ḵ
‎د      | d                   | dal   | d             | d     | d
‎ذ      | z- / d-             | zal   | ẕ (ḏ)         | ḏ     | ḏ
‎ر      | r                   | re    | r             | r     | r
‎ز      | z                   | ze    | z             | z     | z
‎ژ      | z^ / **Z**          | že    | ž             | ž     |
‎س      | s                   | sin   | s             | s     | s
‎ش      | s^ / **S**          | shin  | š             | š     | š
‎ص      | s.                  | sad   | ṣ             | ṣ     | ṣ
‎ض      | **z:** / d.         | zad   | **ż** (ḍ)     | ż     | ḍ
‎ط      | t.                  | ta    | ṭ             | ṭ     | ṭ
‎ظ      | z.                  | za    | ẓ             | ẓ     | ẓ
‎ع      | ´ / **E**           | eyn   | ʿ             | ʿ     | ʻ
´       | ´´                  |       |               |       |
‎غ      | g. / g-             | geyn  | ġ             | ḡ     | ġ / ḡ
‎ف      | f                   | fe    | f             | f     | f
‎ق      | q                   | qaf   | q             | q     | q
‎ک      | k                   | kaf   | k             | k     | k
‎گ      | g                   | gaf   | g             | g     |
‎ل      | l                   | lam   | l             | l     | l
‎م      | m                   | mim   | m             | m     | m
‎ن      | n                   | nun   | n             | n     | n
‎و      | w / **u** / v       | vav   | w / **ū**     | v     | w, u, ū
‎ه      | h                   | he    | h             | h     | h
‎ی      | y / **i**           | ye    | y / **ī**     | y     | y, i, ī

### Arabic

Letter  | `m17n`  | Name
------- | ------- | ----------
‎ك      | k: / K  | Arabic kaf
‎ي      | y: / Y  | Arabic ye

### Alef

Letter  | `m17n`     | Name
------- | ---------- | ---------------
ا       | a          | Alef
آ       | a- / o / A | Alef Madda
ى       | a: / M     | Alef Maksura
اً       | a= / N     | Alef + Fathatan
ٱ       | W          | Alef Wasla

### Hamza

Letter  | `m17n`   | Name
------- | -------- | ---------------------
أ       | a#       | Alef with Hamza above
إ       | a##      | Alef with Hamza below
هٔ       | h#       | He with Hamza above
ؤ       | v#       | Vav with Hamza above
ئ       | y#       | Ye with Hamza above

### Miscellaneous

Letter  | `m17n`      | Name
------- | ----------- | ---------------------
ة       | h: / t: / T | Teh Marbuta
لا      | L           | Lam Alef
ای      | I           | Alef Ye
او      | U           | Alef Vav
خو      | X           | Khe Vav

## Diacritics

Letter  | `m17n`  | Name
------- | ------- | --------------------
'       | ''      |
ـَ       | 'f / 'a | Fatha
ـِ       | 'k / 'e | Kasra
ـُ       | 'd / 'o | Damma
ـً       | 'F / 'A | Fathatan
ـٍ       | 'K / 'E | Kasratan
ـٌ       | 'D / 'O | Dammatan
ـٔ       | 'h      | Hamza above
ـٕ       | 'H      | Hamza below
ـٓ       | 'm      | Madda
ـْ       | 's      | Sukun
ـّ       | 't      | Tashdid (Shadda)
ـٰ       | 'x      | Khanjariyah (Dagger)

## Numbers

### Perso-Arabic

Number  | `m17n`
------- | -------
۱       | 1
۲       | 2
۳       | 3
۴       | 4
۵       | 5
۶       | 6
۷       | 7
۸       | 8
۹       | 9
۰       | 0

### Western Arabic

Number  | `m17n`
------- | -------
1       | A-1
2       | A-2
3       | A-3
4       | A-4
5       | A-5
6       | A-6
7       | A-7
8       | A-8
9       | A-9
0       | A-0

### Eastern Arabic

Number  | `m17n`
------- | -------
٤       | 4:
٥       | 5:
٦       | 6:

## Symbols

### Punctuation

Symbol  | `m17n`  | Name
------- | ------- | -------------
،       | ,       | Comma
,       | ,,      |
‎؛      | ;       | Semicolon
;       | ;;      |
‎؟      | ?       | Question mark
?       | ??      |
‎٭      | *       | Arabic star
*       | **      |

### Typography

- `A--` means `Alt` key plus `-` key.

Symbol  | `m17n`    | Name
------- | --------- | -----------------------
«       | <<        | Opening quotation marks
»       | >>        | Closing quotation marks
–       | --        | En dash
—       | ---       | Em dash
·       | ..        | Middle dot
…       | ...       | Ellipsis
ـ       | A--       | Tatweel

### Mathematics

Symbol  | `m17n`   | Name
------- | -------- | -------------------
÷       | \/       | Division
×       | \*       | Multiplication
−       | \-       | Minus
٪       | \%       | Percent
٫       | \, / A-, | Decimal separator
٬       | \' / A-' | Thousands separator

## Space and (Non-)Joiners

- `A-␣` means `Alt` key plus space bar.
- `S-␣` means `Shift` key plus space bar.

`m17n`      | Name
----------- | ----------------------------
!NBSP / S-␣ | Non-breaking space (NBSP)
!ZWNJ / A-␣ | Zero-width non-joiner (ZWNJ)
!ZWJ / A-+  | Zero-width joiner (ZWJ)

## Bi-directional text

For more details, see the Wikipedia article about [bi-directional text](https://en.wikipedia.org/wiki/Bi-directional_text).

### Marks

BIDI  | `m17n`    | Name
----- | --------- | ------------------
ALM   | !ALM / !+ | Arabic letter mark
LRM   | !LRM / !> | Left-to-right mark
RLM   | !RLM / !< | Right-to-left mark

### Isolates

*Isolates* were created as a replacement of *embeddings*.

BIDI  | `m17n`    | Name
----- | --------- | ---------------------
LRI   | !LRI / !) | Left-to-right isolate
RLI   | !RLI / !( | Right-to-left isolate
FSI   | !FSI / !* | First strong isolate

### Embeddings

*Embeddings* are being discouraged in favor of *isolates*.

BIDI  | `m17n`    | Name
----- | --------- | -----------------------
LRE   | !LRE / !] | Left-to-right embedding
RLE   | !RLE / ![ | Right-to-left embedding

### Overrides

Don't use *overrides* unless you know what you do.

BIDI  | `m17n`    | Name
----- | --------- | ----------------------
LRO   | !LRO / !} | Left-to-right override
RLO   | !RLO / !{ | Right-to-left override

### Pops

BIDI  | `m17n`     | Name
----- | ---------- | --------------------------
PDI   | !PDI / !=  | Pop directional isolate
PDF   | !PDF / !-  | Pop directional formatting
