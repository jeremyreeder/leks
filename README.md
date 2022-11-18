# LEKS
## Leksikona Esperanta Komandlinia Sercxilo

_Leks_ is a lexical parser of words of the Esperanto language, implemented as a
command-line Python script. Use it like a dictionary to look up a word. Even if
the word is too complex to exist in a dictionary, Leks will break it down into
its various parts (separating them with hyphens) and identify the role of each
in the meaning of the word. All standard prefixes, suffixes, common roots, and
grammatical word endings (excluding verb conjugations) are currently supported.
There are certain ambiguous cases, such as where "eksendo" could be interpreted
as "ek-sendo" or "eks-endo".
