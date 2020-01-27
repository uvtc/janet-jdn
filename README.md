# jdn

Janet data notation, A set convenience wrappers around the janet parser api.

# Quick Examples

```
(import jdn)

(jdn/encode @[1 nil 2])
"@[1 nil 2]"
(jdn/decode-values "")
@[]
(jdn/decode-values "a b c")
@[a b c]
(jdn/decode "a b")
a
(jdn/decode "nil")
nil
```
