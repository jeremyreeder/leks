# LEKS
## Leksikona Esperanta Komandlinia Sercxilo

_Leks_ is a lexical parser of words of the Esperanto language, implemented as a
command-line Python script. Use it like a dictionary to look up a word. Even if
the word is too complex to exist in a dictionary, Leks will break it down into
its various parts (separating them with hyphens) and (coming soon) explain the
meaning of each. All standard prefixes, suffixes, and grammatical word endings
(excluding verb conjugations) are currently supported.  Compound roots are not
yet separable.  The breakdown given by Leks is for just one plausible
interpretation, the first one that Leks found. In cases of ambiguity, such as
"ek-sendo" vs "eks-endo", the future intention is to list each possibility.
