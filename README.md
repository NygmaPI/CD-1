# Tatoeba Datasets
## Information
This repository includes three (3) Tab-separated values (TSV) files provided by Language Technology Research Group at the University of Helsinki. These files were provided by the University of Helsinki on HuggingFace([1](https://huggingface.co/datasets/Helsinki-NLP/tatoeba_mt/tree/main/test)) and their website([2](https://tatoeba.org/en/downloads)) in relation to their **Taboeba** project. These files were released under [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/).

All three of these files were chosen because of their inclusion of the Frisian language. While there are several branches of Frisian, these datasets are comprised of the West Frisian branch of the Frisian language, which is by far the most spoken of the three. It is an official language in the Dutch province of Friesland, where it is spoken on the mainland, and on two of the West Frisian Islands, as well as an official language of the Netherlands.

![Frisian Flag](https://upload.wikimedia.org/wikipedia/commons/c/ca/Frisian_flag.svg | width=200)

### Frisian
> Frisian language, the West Germanic language most closely related to English. Although Frisian was formerly spoken from what is now the province of Noord-Holland (North Holland) in the Netherlands along the North Sea coastal area to modern German Schleswig, including the offshore islands in this area, modern Frisian is spoken in only three small remaining areas, each with its own dialect. [...]
> 
> Written records date from the end of the 13th century and are in Old Frisian, a stage of the language that lasted until the late 16th century. Old Frisian shows all the features that distinguish English and Frisian from the other Germanic languages.
> 
> Although Frisian was little used as a written language for about 300 years after the end of the Old Frisian period, there has been a revival in modern times in the West Frisian area. The language is now used in the schools and courts in the province of Friesland. There is also a Frisian Academy. East and North Frisian are being gradually supplanted by German.

— [Britannica](https://www.britannica.com/topic/Frisian-language)

### Taboeba
According to their website([3](https://tatoeba.org/en)), Taboeba is:
> a large database of sentences and translations. Its content is ever-growing and results from the voluntary contributions of thousands of members.
> Tatoeba provides a tool for you to see examples of how words are used in the context of a sentence. You specify words that interest you, and it returns sentences containing these words with their translations in the desired languages. The name Tatoeba (_for example_ in Japanese) captures this concept.

## Data
### General Information
Both the _tatoeba-test.eng-fry.tsv_ and _tatoeba-test.fry-nld.tsv_ files are from "Tatoeba MT benchmark version v2021-08-07", whereas the _fry_sentences.tsv_ is an up-to-date version of the sentences appearing on the Tatoeba website. All three of these files include samples of the Frisian language:
- _fry_sentences.tsv_ includes all the sentences in Frisian on Taboeba, with no additional languages.
- _tatoeba-test.eng-fry.tsv_ includes English sentences and their Frisian equivalent.
- _tatoeba-test.fry-nld.tsv_ includes Frisian sentences and their Dutch equivalent.

## Variables
a table with a list of the variables in the dataset and a brief description of what they are
#### _tatoeba-test.eng-fry.tsv_

