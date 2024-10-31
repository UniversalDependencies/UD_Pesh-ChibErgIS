# Summary

A Universal Dependencies corpus for Pesh (aka Paya), a member of the Chibchan language family. The language is spoken by about 500 speakers in Honduras.

# Introduction

The treebank is an automatic conversion of the SUD_Pesh-ChibErgIS, which is an automatic conversion of the [mSUD_Pesh-ChibErgIS](https://github.com/surfacesyntacticud/mSUD_Pesh-ChibErgIS) which was extracted from Claudine Chamoreaus and Natalia Cáceres interlinearized corpus in Flex format, itself an extension of an oral corpus documented by Claudine Chamoreau (https://www.elararchive.org/dk0392).

# Acknowledgments

Sentences are annotated with the following metadata:
`speaker_id` (which identifies the turn of speech)
 - `sent_timecode` (which will enable playback of the sentence)
 - `morphemic_text`: (original segmentation of the text into morphemes)
 - `text`: (lexical tokenization)
 - `text_en`: (English interpretation)
 - `text_phrase-gls-de`: (original id)
 - `text_phrase-gls-es`: (Spanish interpretation)
 - `text_phrase-gls-it`: (IPA transcription)
 - `text_phrase-gls-pro`: (prosodic transcription)
 - `text_phrase-gls-tl`: (original comments in Flex)
 - `text_phrase-gls-wg`: (original word-gloss in Flex) - 

## Structure
This version of the treebank is a dependency parsing of the original corpus first four files.

The original data are spoken data, which were originally segmented in words with concatenated clitics, then interlinearized and glossed in Flex with clitics as separate tokens. Tokens comprize words and affixes (preceded by a "=" sign). 

The **UD_Pesh-ChibErgIS** counts 2,507 tokens for 307 sentences.

## References

- Chamoreau, Claudine. 2015. A cross-varietal documentation and description of Pesh, a Chibchan language of Honduras. Endangered Languages Archive. Handle: http://hdl.handle.net/2196/00-0000-0000-000F-BF49-B

## Acknowledgments

This treebank was produced as part of the ChibErgIS and Autogramm ANR projects. With special thanks to Bruno Guillaume for the conversion from SUD to UD, Sylvain Kahane, Christian Chanard, Uyên-To Rabier and Aleksandra Miletic.

# Changelog

* 2024-11-15 v2.15
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.15
License: CC BY-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Cáceres, Natalia
Contributing: elsewhere
Contact: nataliacaceres@gmail.com
===============================================================================
</pre>
