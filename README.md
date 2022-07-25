# Thai Grapheme to Phoneme (G2P) Wiktionary Corpus

This is the Thai Grapheme to Phoneme corpus for build Thai grapheme-to-phoneme models. The corpus come from Wiktionary that scrape by [WikiPron](https://pypi.org/project/wikipron/). It is use IPA.

The corpus license is [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).

**Files**
- wiktionary-23-7-2022-clean.tsv - scraped 23 July 2022 and clean dataset
- wiktionary-23-7-2022.tsv - scraped 23 July 2022
- wiktionary-11-2-2020.tsv - scraped 11 February 2020
- clean_corpus.ipynb - clean source code
- get-wikipron.ipynb - for scrape by WikiPron.

**Example**
| Word | Phonemes |
|------|----------|
| เมน |	m eː n ˧ |
| เมนส์	| m e n ˧ |
| เมรุ | m eː n ˧ |
| เมรุ | m eː n ˧ . |
| เมรุ | m eː ˧ . r u ˦˥ . |
| นิติรัฐ | n i ˦˥ . t i ˨˩ . r a t̚ ˦˥ |
| รัฐชาติ | r a t̚ ˦˥ . t͡ɕʰ aː t̚ ˥˩ |
| รัฐธรรมนูญ | r a t̚ ˦˥ . tʰ a ˨˩ . tʰ a m ˧ . m a ˦˥ . n uː n ˧ |
