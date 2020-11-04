# Icelandic NLP tools
This is an list of known tools designed specifically to do linguistic processing in Icelandic. It is intended to give readers a clear overview of the ever-growing arsenal of tools for working with Icelandic natural language data at a glance.

This list is categorized by task to increase clarity. Due to that, some multi-functional tools and toolkits might appear more than once in the list.
If you notice a category or resource is missing or have suggestions on how to improve this list, please open a pull request.
## Contents
* [Useful links](#Useful-links)
* [Toolkits](#Toolkits-↑)
* [Tokenization and text normalization](#Tokenization-and-text-normalization-↑)
* [POS tagging](#POS-tagging-↑)
* [Syntactic parsing](#Syntactic-parsing-↑)
* [Grapheme-to-phoneme](#Grapheme-to-phoneme-↑)
* [Stress analysis](#Stress-analysis-↑)
## Useful links
* [CLARIN-IS](https://repository.clarin.is/repository/xmlui/)
  * The Icelandic branch of the CLARIN-ERIC language resource initiative. Contains information on and downloads for many tools and datasets.
* [malfong.is](https://malfong.is)
  * List of language technology resources, maintained by Árnastofnun.
## Toolkits [↑](#Contents)
### [Greynir](http://hdl.handle.net/20.500.12537/76)
  * Python 3 package which is capable of syntactic parsing, lemmatization, POS tagging, noun phrase inflection and more
  * [The GitHub repo for this project](https://github.com/mideind/GreynirPackage/releases/tag/2.6.1)
  * Developed by [Miðeind ehf.](https://mideind.is)
### [IceNLP](https://github.com/hrafnl/icenlp)
  * Java toolkit which does tokenization, POS tagging, lemmatization, parsing and NER
  * Developed by [Hrafn Loftsson](http://www.ru.is/faculty/hrafn/)
## Tokenization and text normalization [↑](#Contents)
* [Icelandic tokenizer](https://github.com/mideind/Tokenizer)
* [Textahaukur - text normalization toolkit](https://github.com/cadia-lvl/Icelandic-textnorm)
  * This seems to be in suspended development
## POS tagging [↑](#Contents)
* [POS tagger based on ABLTagger](https://github.com/cadia-lvl/POS)
    * [Publication describing ABLTagger](https://www.aclweb.org/anthology/R19-1133/)
* [The standard Icelandic fine-grained POS Tagset](https://drive.google.com/file/d/1mlQmYZ34ICeWYOdgGgj8Q2tPoWaGq8uK/view)
## Syntactic parsing [↑](#Contents)
* [Neural parsing pipeline for Icelandic](http://hdl.handle.net/20.500.12537/17)
  * [The GitHub repo for this project](https://github.com/antonkarl/iceParsingPipeline)
* Greynir, [see above](#Greynir)
* IceNLP, [see above](#IceNLP)
## Grapheme-to-phoneme [↑](#Contents)
* [Icelandic pronunciation dictionary](https://github.com/cadia-lvl/SLT2018)
* [Pronunciation dictionary editor](https://github.com/grammatek/pedi)
* [Thrax G2P grammar for Icelandic](https://github.com/grammatek/g2p-thrax)
## Stress analysis [↑](#Contents)
* I don't know of any stress analysis tools for Icelandic. Please let me know if you know of one!