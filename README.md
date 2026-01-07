# diffsinger Taiwanese phonetic system
A more detailed phonetic system for diffsinger Taiwanese

## [View phoneme chart](/Phonemes.md)

## [View dictionary](/dsdict)

The [dictionary-tw.txt](/dictionary-tw.txt) is a minimal dictionary for training, will not work with OpenUtau or command-line interface (CLI) inference.

For use in OU, use the dictionary provided [here](/dsdict), and for CLI inference, use [this](/dict-tw-CLI.txt). 

Do note that due to the fact that there currently is no phonemizer specifically made for Taiwanese, you'll have to just use the base diffsinger phonemizer, and paste the dsdict content into dsdict.yaml.

Taiwanese is essentially a variant Hokkien that went through some alterations in Taiwan, making it bear a few differences from Hokkien, the names are pretty much interchangable.

The minimal dictionary above will differ from the one included in the one provided with [ACV-001](https://github.com/archivoice/acv-001)'s V1.0 release under the context that `j` and `ji` aren't used in the branch of Taiwanese spoken by YiChen, the voice provider and creator. And diffsinger requires a dictionary that only covers the recorded phonemes, thus those two phonemes are excluded from the dataset's dictionary.


For reference, the main difference would be that in other branches of the dialect, a word like 日 would be pronounced `ji̍t`, while according to the branch YiChen speaks would be pronounced `li̍t `.
