# Chapter 4

- `substring(i, j)`: j 番目の文字は含めない
- https://docs.oracle.com/javase/jp/8/docs/api/java/lang/String.html#substring-int-int-

- `advance()` をする前は `isAtEnd()` でチェックすることが必須。でないと `source` の範囲外参照をしてしまう可能性がある。

# Chapter 6

BNF の書き換えは Precedence, Associativity を反映させるためにやっている。
equality という non-term があっても比較演算が必ず入るわけではないので注意。
例:
123 という数字は以下のように解釈される
```
expression -> equality -> comparison -> term -> factor -> unary -> primary -> NUMBER
```
