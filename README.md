Both DNA and RNA strands are a sequence of nucleotides.

The four nucleotides found in DNA are adenine (**A**), cytosine (**C**),
guanine (**G**) and thymine (**T**).

The four nucleotides found in RNA are adenine (**A**), cytosine (**C**),
guanine (**G**) and uracil (**U**).

Given a DNA strand, its transcribed RNA strand is formed by replacing
each nucleotide with its complement:

* `G` -> `C`
* `C` -> `G`
* `T` -> `A`
* `A` -> `U`

## JS: Understand Function Scope

```javascript
yvan@x230:~$ nodejs 
> function test_1(x) { x = x + "!"; }
undefined
> var s = "boo"
undefined
> test_1(s)
undefined
> s
'boo'
> function test_2(x) { x = x + "!"; return x; }
undefined
> test_2(s)
'boo!'
> s
'boo'
>
```
