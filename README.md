# Axalier Language

A brainfuck derivative based off the vocabulary of Axalier.

Syntax
----
Axalier | brainfuck | description
--------------|-----------|------------
`包丁` | + | increment the byte at pointer
`太陽神` | - | decrement the byte at pointer
`女ァ!` | [ | if pointer is zero, jump to matching `妹`
`妹` | ] | if pointer is not zero, jump to matching `女ァ!`
`ケッコンシヨウ` | > | increment the data pointer
`浮気` | < | decrement the data pointer
`メイド服` | , | input of one byte into pointer
`おハァ〜イコンシャスネス♡` | . | output the byte at pointer

Sample
----

##### hello_world.axalier

> 包丁包丁包丁包丁包丁包丁包丁包丁女ァ!ケッコンシヨウ包丁包丁包丁包丁女ァ!ケッコンシヨウ包丁包丁ケッコンシヨウ包丁包丁包丁ケッコンシヨウ包丁包丁包丁ケッコンシヨウ包丁浮気浮気浮気浮気太陽神妹ケッコンシヨウ包丁ケッコンシヨウ包丁ケッコンシヨウ太陽神ケッコンシヨウケッコンシヨウ包丁女ァ!浮気妹浮気太陽神妹ケッコンシヨウケッコンシヨウおハァ〜イコンシャスネス♡ケッコンシヨウ太陽神太陽神太陽神おハァ〜イコンシャスネス♡包丁包丁包丁包丁包丁包丁包丁おハァ〜イコンシャスネス♡おハァ〜イコンシャスネス♡包丁包丁包丁おハァ〜イコンシャスネス♡ケッコンシヨウケッコンシヨウおハァ〜イコンシャスネス♡浮気太陽神おハァ〜イコンシャスネス♡浮気おハァ〜イコンシャスネス♡包丁包丁包丁おハァ〜イコンシャスネス♡太陽神太陽神太陽神太陽神太陽神太陽神おハァ〜イコンシャスネス♡太陽神太陽神太陽神太陽神太陽神太陽神太陽神太陽神おハァ〜イコンシャスネス♡ケッコンシヨウケッコンシヨウ包丁おハァ〜イコンシャスネス♡ケッコンシヨウ包丁包丁おハァ〜イコンシャスネス♡

##### execute
> ./axalier hello_world.axalier

##### output

> Hello World!


SEE ALSO
----
https://www.muppetlabs.com/~breadbox/bf/
