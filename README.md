# Moerbeke lexicon packs

Dictionary and word-parsing packs for [Moerbeke](https://github.com/johnhboyer-sys/moerbeke),
a translation workbench for Greek and Latin. The app downloads and installs
them from Settings › Lexicon, and checks each file's SHA-256 before it
installs anything. You can also download a zip from the
[Releases](https://github.com/johnhboyer-sys/moerbeke-packs/releases) page and
choose it with "Install from file…".

| Pack | Dictionary | Licence |
|---|---|---|
| `grc-lexicon-pack.zip` | Liddell & Scott, with Morpheus word analyses | CC BY-SA 3.0 US |
| `lat-lexicon-pack.zip` | Lewis & Short, with Morpheus word analyses | CC BY-SA 3.0 US |

The dictionaries come from the [Perseus Digital Library](https://www.perseus.tufts.edu/)
under the [Creative Commons Attribution-ShareAlike 3.0 United States](https://creativecommons.org/licenses/by-sa/3.0/us/)
licence, and the word analyses from Morpheus, the Perseus Project's parser, as
distributed with [Diogenes](https://d.iogen.es/d) (Peter Heslin). Each zip
carries its own `LICENCE` and `CREDITS`, saying what was changed. The packs are
shared under the same licence.

The packs are built with `scripts/build_lexicon_pack.py` in the Moerbeke
repository. Each release lists every file's SHA-256 in `SHA256SUMS`.
