//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.parser](../index.md)/[Token](index.md)/[specialToken](special-token.md)

# specialToken

[jvm]\
open val [specialToken](special-token.md): [Token](index.md)

This field is used to access special tokens that occur prior to this token, but after the immediately preceding regular (non-special) token. If there are no such special tokens, this field is set to null. When there are more than one such special token, this field refers to the last of these special tokens, which in turn refers to the next previous special token through its specialToken field, and so on until the first special token (whose specialToken field is null). The next fields of special tokens refer to other special tokens that immediately follow it (without an intervening regular token). If there is no such token, this field is null.