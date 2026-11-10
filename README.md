# Summary

A Universal Dependencies corpus for Pesh (aka Paya), a member of the Chibchan language family. The language is spoken by about 500 speakers in Honduras.

# Introduction

The treebank is an automatic conversion of the SUD_Pesh-ChibErgIS, which is an automatic conversion of the [mSUD_Pesh-ChibErgIS](https://github.com/surfacesyntacticud/mSUD_Pesh-ChibErgIS) which was extracted from Claudine Chamoreau and Natalia Cáceres interlinearized corpus in Flex format, itself an extension of an oral corpus documented by Claudine Chamoreau (https://www.elararchive.org/dk0392).

The corpus can be found [here](https://universal.grew.fr/?corpus=mSUD_Pesh-ChibErgIS@filter)

## Metadata

Sentences are annotated with the following metadata:
 - `speaker_id` (which identifies the turn of speech)
 - `sent_timecode` (which will enable playback of the sentence)
 - `morphemic_text` (original segmentation of the text into morphemes)
 - `text` (lexical tokenization)
 - `text_en` (English interpretation)
 - `text_phrase-gls-de` (original id)
 - `text_phrase-gls-es` (Spanish interpretation)
 - `text_phrase-gls-it` (IPA transcription)
 - `text_phrase-gls-pro` (prosodic transcription)
 - `text_phrase-gls-tl` (original comments in Flex)
 - `text_phrase-gls-wg` (original word-gloss in Flex) - 

## Description

The original Pesh data are spoken data, which were segmented in words with concatenated clitics, then interlinearized and glossed in Flex with clitics as separate tokens. Tokens include words and clitics (preceded by a "=" sign).

-- 2024-11-15 v2.15 --
This version of the treebank is a dependency parsing of four initial text files (008_Childhood, 086_Wisinka, 103_MotherFish, 165_RabbitTiger).

Total count: 2,507 tokens for 307 sentences.

-- 2025-05-15 v2.16 --
This version of the treebank contains three additional text files (085_MotheFishPrankster, 100_Laguna, 151_Hunting).

Total count: 4,275 tokens for 524 sentences.

-- 2026-11-15 v2.19 --
This version of the treebank contains one additional partially annotated text (005_EvilEye) and some annotation revisions.

Total count: 4,330 tokens for 529 sentences.

## Development

The corpus is maintained [here](https://github.com/surfacesyntacticud/mSUD_Pesh-ChibErgIS) in the [SUD](https://surfacesyntacticud.org/) framework and automatically converted into UD using the [Grew](https://grew.fr) software with the conversions rules described [here](https://github.com/surfacesyntacticud/conversions).

## References

- Chamoreau, Claudine. 2015. A cross-varietal documentation and description of Pesh, a Chibchan language of Honduras. Endangered Languages Archive. Handle: http://hdl.handle.net/2196/00-0000-0000-000F-BF49-B
- Chamoreau, Claudine & Cáceres Arandia, Natalia. 2024. Texts in Indigenous Languages of the Americas: Texts in
Three Varieties of Pesh \[TILA 4\]. International Journal of American Linguistics, 90 (S1).

## Acknowledgments

This treebank was produced as part of the ChibErgIS and Autogramm ANR projects.

Data collection: Claudine Chamoreau

Morphological interlinearization: Claudine Chamoreau, Natalia Cáceres Arandia

Syntactic annotation: Natalia Cáceres Arandia

Discussion and advice on SUD annotation: Sylvain Kahane, Bruno Guillaume, Aleksandra Miletic

Conversion to CoNLLu format: Christian Chanard, Uyên-To Rabier

UD conversion and handling of data validation : Bruno Guillaume


# Changelog

* 2026-11-15 v2.19
  * Some revised annotations.

* 2025-05-15 v2.16
  * Three new texts added.

* 2024-11-15 v2.15
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.15
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Cáceres Arandia, Natalia; Chamoreau, Claudine; Kahane, Sylvain; Guillaume, Bruno
Contributing: elsewhere
Contact: natalia.caceres.arandia@cnrs.fr
===============================================================================
</pre>
