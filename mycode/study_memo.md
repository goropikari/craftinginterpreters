# Chapter 4

- `substring(i, j)`: j 番目の文字は含めない
- https://docs.oracle.com/javase/jp/8/docs/api/java/lang/String.html#substring-int-int-

- `advance()` をする前は `isAtEnd()` でチェックすることが必須。でないと `source` の範囲外参照をしてしまう可能性がある。
