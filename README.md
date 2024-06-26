# Icelandic NLP resources
This is an list of known tools and resources developed specifically to do linguistic processing in Icelandic. It is intended to give readers a clear overview of the ever-growing arsenal of tools for working with Icelandic natural language data at a glance.

This list is categorized by task to increase clarity. Due to that, some multi-functional tools and toolkits might appear more than once in the list.
If you notice a category or resource is missing or have suggestions on how to improve this list, please open a GitHub pull request. For those who do not know how to make pull requests, you can also create an issue with your GitHub account.

## Contents
* [Notable papers](#notable-papers-and-reports-)
* [Other resource collections](#other-resource-collections-)
* [Corpora](#corpora-)
* [European Language Grid Services](#european-language-grid-services-)
* [Toolkits](#toolkits-)
* [Tokenization and text normalization](#tokenization-and-text-normalization-)
* [POS tagging](#pos-tagging-)
* [Syntactic parsing](#syntactic-parsing-)
* [Grapheme-to-phoneme](#grapheme-to-phoneme-)
* [Stress analysis](#stress-analysis-)
* [Speech synthesis (TTS)](#Speech-synthesis-)
* [Speech recognition (ASR)](#speech-recognition-)

## Notable papers and reports [↑](#contents)
* [Máltækniáætlun fyrir íslensku 2018-2022](https://www.stjornarradid.is/library/03-Verkefni/Menningarmal/M%C3%A1lt%C3%A6kni%C3%A1%C3%A6tlun.pdf) ([English version](https://clarin.is/media/uploads/mlt-en.pdf))
  * The project plan for an ongoing language technology programme funded by the Icelandic Ministry of Education.
  * [Short paper describing the programme](https://arxiv.org/pdf/2003.09244.pdf), note that the programme has been postponed by a year compared to the original plan.
* [Risamálheild: A Very Large Icelandic Text Corpus](https://www.aclweb.org/anthology/L18-1690.pdf)
  * Paper describing the Icelandic Gigaword Corpus, a tagged and lemmatized corpus containing over 10^9 tokens.
* [A Wide-Coverage Context-Free Grammar for Icelandic and an Accompanying Parsing System](https://acl-bg.org/proceedings/2019/RANLP%202019/pdf/RANLP160.pdf)
* Please send a pull request with additions to this list. If you create a Github issue with the following details of the paper: title, link/URL to PDF/book, and a short description then we can add it to the website/markdown file.

## Other resource collections [↑](#contents)
* [CLARIN-IS](https://repository.clarin.is/repository/xmlui/)
  * The Icelandic branch of the CLARIN-ERIC language resource initiative. Contains information on and downloads for many tools and datasets.
* [SÍM homepage](https://icelandic-lt.gitlab.io/)
  * Overview page for SÍM (the Icelandic Language Technology Consortium), which contains mirrors and descriptions for all Language Technology Programme projects.
* [malfong.is](https://malfong.is)
  * List of language technology resources, maintained by Árnastofnun.
* [Comprehensive list of language resources](language_resources.md)
  * This list of over 100 Icelandic language technology resources was compiled by [@bjarnigithub](https://github.com/bjarnigithub) in the summer of 2021.

## Corpora [↑](#contents)
* [Talrómur](http://hdl.handle.net/20.500.12537/104)
  * A large public domain TTS corpus designed for research and development. Contains over 160 hours of studio-recorded prompted speech, divided between 8 speakers.
* [Samrómur](https://samromur.is/gagnasafn)
  * An open and accessible speech recognition dataset with FLAC audio files, corresponding text and metadata.
* [Icelandic broadcast speech](http://hdl.handle.net/20.500.12537/193)
  * 193 hours of radio and TV data from the Icelandic National Broadcasting Service (RÚV).
* [Spjallromur](http://hdl.handle.net/20.500.12537/187)
  * Icelandic Conversational Speech
* [Kennslurómur](http://hdl.handle.net/20.500.12537/171)
  * Icelandic lectures with audio and corresponding text.
* [GreynirCorpus](https://github.com/mideind/GreynirCorpus)
  * A large, parsed treebank of modern Icelandic text

## European Language Grid Services [↑](#contents)
* [tokenizer_api](https://live.european-language-grid.eu/catalogue/tool-service/17480)
* [icenlp_api](https://live.european-language-grid.eu/catalogue/tool-service/17684)
* [icenlp_api (IceParser - Shallow Parser)](https://live.european-language-grid.eu/catalogue/tool-service/17682)
* [pos_api](https://live.european-language-grid.eu/catalogue/tool-service/18084)
* [ner_api](https://live.european-language-grid.eu/catalogue/tool-service/18082)
* [far_abltagger_api](https://live.european-language-grid.eu/catalogue/tool-service/18026)
* [icesum_api](https://live.european-language-grid.eu/catalogue/tool-service/18038)
* [nefnir_api](https://live.european-language-grid.eu/catalogue/tool-service/18290)
* [greynirseq_api](https://live.european-language-grid.eu/catalogue/tool-service/18351)
* [greynirseq_api](https://live.european-language-grid.eu/catalogue/tool-service/18510)
* [binpackage_api](https://live.european-language-grid.eu/catalogue/tool-service/18677)
* [greynircorrect_api](https://live.european-language-grid.eu/catalogue/tool-service/18613)


## Toolkits [↑](#contents)

### [Greynir](http://hdl.handle.net/20.500.12537/76)
  * Python 3 package which is capable of syntactic parsing, lemmatization, POS tagging, noun phrase inflection and more
  * [The GitHub repo for this project](https://github.com/mideind/GreynirPackage/releases/tag/2.6.1)
  * Developed by [Miðeind ehf.](https://mideind.is)

### [IceNLP](https://github.com/hrafnl/icenlp)
  * Java toolkit which does tokenization, POS tagging, lemmatization, parsing and NER
  * Developed by [Hrafn Loftsson](http://www.ru.is/faculty/hrafn/)

### [LVL-tts-frontend](https://github.com/cadia-lvl/lvl_tts_frontend)
* TTS frontend designed to work with the [Merlin](https://github.com/CSTR-Edinburgh/merlin) speech synthesis system developed by [CSTR](http://www.cstr.ed.ac.uk/)
* It contains a pronunciation dictionary, sequitur g2p model, stress analysis component and more. Unfortunately it does not include any documentation.
  * Developed by Anna Björk Nikulásdóttir at LVL

## Tokenization and text normalization [↑](#contents)
* [Icelandic tokenizer](https://github.com/mideind/Tokenizer)
* [Textahaukur - text normalization toolkit](https://github.com/cadia-lvl/Icelandic-textnorm)
  * This seems to be in suspended development and claims to not be functional as of yet.
* [Regína normalizer](https://github.com/cadia-lvl/regina-normalizer)
  * Regex-based text normalization in python. Currently in early stages of development.

## POS tagging [↑](#contents)
* [POS tagger based on ABLTagger](https://github.com/cadia-lvl/POS)
    * [Publication describing ABLTagger](https://www.aclweb.org/anthology/R19-1133/)
* [The standard Icelandic fine-grained POS Tagset](https://drive.google.com/file/d/1mlQmYZ34ICeWYOdgGgj8Q2tPoWaGq8uK/view)

## Syntactic parsing [↑](#contents)
* [Neural parsing pipeline for Icelandic](http://hdl.handle.net/20.500.12537/17)
  * [The GitHub repo for this project](https://github.com/antonkarl/iceParsingPipeline)
* Greynir, [see above](#greynir)
* IceNLP, [see above](#icenlp)

## Grapheme-to-phoneme [↑](#contents)
* [LSTM encoder-decoder sequence-to-sequence models for Icelandic](https://github.com/grammatek/g2p-lstm), [reference](g2p-reference.md#grammatekg2p-lstm)
* [g2p-service](https://github.com/rkjaran/g2p-service) is a g2p web service.
[reference](g2p-reference.md#rkjarang2p-service)
* [Icelandic pronunciation dictionary](https://github.com/grammatek/iceprondict)
* [Pronunciation dictionary editor](https://github.com/grammatek/pedi)
* [Thrax G2P grammar for Icelandic](https://github.com/grammatek/g2p-thrax), [reference](g2p-reference.md#grammatekg2p-thrax)
* [LVL-tts-frontend](#lvl-tts-frontend)
* [G2P - Atli Thor's g2p python module/pip package](https://github.com/atliSig/g2p), [reference](g2p-reference.md#atlisigg2p)
* [Module for preparing text data for TTS data collections ...](https://github.com/cadia-lvl/tts_data), [reference](g2p-reference.md#cadia-lvltts_data)
* [Althingi ASR g2p](https://github.com/cadia-lvl/kaldi/tree/master/egs/althingi/s5/local), [reference](g2p-reference.md#althingis5)

## Stress analysis [↑](#contents)
* [LVL-tts-frontend](#lvl-tts-frontend) performs stress analysis

## Speech synthesis [↑](#contents)
* [Unit selection recipe in Festival for Icelandic](https://github.com/cadia-lvl/unit-selection-festival)
* [FastSpeech2 with support for the Talromur corpus](https://github.com/cadia-lvl/FastSpeech2)

## Speech recognition [↑](#contents)
* [Ice-ASR](https://github.com/cadia-lvl/ice-asr)
* [Alþingi](https://github.com/cadia-lvl/kaldi)
  * [Just the recipe](https://github.com/cadia-lvl/althingi-asr)
* [Samromur ASR](https://github.com/cadia-lvl/samromur-asr)
  * Contains a vanilla recipe (base), subword modelling, and specialized
    children and adolescent recipes
* [alignment and segmentation](https://github.com/cadia-lvl/alignment-and-segmentation)
  * Scripts to prepare RÚV TV data for alignment and segmentation to make an ASR dataset
* [Tiro Speech Core](https://github.com/tiro-is/tiro-speech-core)
* [Tal](https://tal.ru.is)

## Our CADIA-LVL works in progress
You can also see our many works in progress at LVL itself if you follow us on our github: https://github.com/cadia-lvl \
Facebook page: https://www.facebook.com/languageandvoice/

[//]: # (And our website at Reykjavík University: https://lvl.ru.is/)

