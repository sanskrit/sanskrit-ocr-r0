# sanskrit-ocr-r0
A project to OCR critical sanskrit texts

## How to get OCR-s?
* Archive already has a crude OCR which does not recognize devanAgarI - example [https://archive.org/stream/ADictionaryOfSanskritGrammarByMahamahopadhyayaKashinathVasudevAbhyankar/DictionaryOfSanskritGrammar_abhyankar_djvu.txt] .
* If you work at some companies (say Google), you may have wonderful infrastructure and a couple of hundred machines to get good OCR's fast. Ask around!

## Making corrections
### In dictionary type files
1] Mark new headwords with a string - say "############". 
2] Fix egregious errors - especially in the headwords - to facilitate lookup. Typo errors in the meanings are more tolerable (usually the fixes are obvious to the reader).

For example:
If in the current text we have:

    हेमाब्दानुशासनलधुन्यास a short comm-
    entary on Hemacandra'sSabdanu-
    Sव्रsana written by Devendrastri.
    हेमाब्दानुशासनव्राते a short gloss call-
    ed अवचूरि also, written by a Jain
    grammarian नन्दसुन्दर on the ईम-
    इब्दानुद्भासन. _
    ह्यस्तनी imperfect tense; a term
    used by ancient grammarians for
    the affixes of the immediate past
    tense, but not comprising the
    present day, corresponding to the
    term लङ्क of Pafini. The term is
    found in the Katantra and Haima-
    candra grammars; cf. Kt. III.
    1.23, 27; cf. Hema. III. 3.9.
    इस्व short, a term used in connec-
    tion with the short vowels taking
    a umit of time measured by one
    matra for their utterance: cf.
    ऊकालेोज्इरस्वदीर्घप्लुत: P. I. 2.27.

This should be replaced with (note bolded letters such as श ह्र which have been fixed.):

    ############
    हेमाशब्दानुशासनलधुन्यास a short comm-
    entary on Hemacandra's Sabdanu-
    Sव्रsana written by Devendrastri.
    हेमाब्दानुशासनव्राते a short gloss call-
    ed अवचूरि also, written by a Jain
    grammarian नन्दसुन्दर on the हेम-
    शब्दानुद्भासन. _
    ############
    ह्यस्तनी imperfect tense; a term
    used by ancient grammarians for
    the affixes of the immediate past
    tense, but not comprising the
    present day, corresponding to the
    term लङ्क of Pafini. The term is
    found in the Katantra and Haima-
    candra grammars; cf. Kt. III.
    1.23, 27; cf. Hema. III. 3.9.
    ############
    ह्रस्व short, a term used in connec-
    tion with the short vowels taking
    a umit of time measured by one
    matra for their utterance: cf.
    ऊकालेोज्इरस्वदीर्घप्लुत: P. I. 2.27.

