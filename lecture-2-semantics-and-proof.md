## Lecture 2 - Model Theory

`4 = (2 + x)` is an *open sentence* (it has *variables*), if we replace the variables with *constants* then we get a *closed sentence* which may be true or false. If the sentence can be made true then this *interpretation* is considered a *model* of that sentence, if it is made false then it is a *countermodel* of that sentence. If the sentence has at least one model it is considered *satisfiable*.

There are two special cases:

1. An open sentence is *valid* if only when every interpretation is a model of that sentence (i.e. `x + y = y + x`)
2. An open sentence is *countervalid* only if every interpretation is a countermodel of that sentence (i.e. `x + 1 = x`)

One way of describing the semantics of a proof system is to describe what counts as an interpretation of a sentence of that language and the conditions under which that interpretation makes the sentence true. This is a *truth conditions* or *model theoretic* account of the semantics of that language.

Exercise 2.1

1. `4 = x` is neither valid nor countervalid (only `x = 4` provides a valid model, all others are countermodels)
2. `x = (x - 1)` is countervalid, all values of `x` are countermodels.
3. `(x * (y + z)) = ((x * y) + (x * z))` is valid as the two sides are algebraically equivalent.
4. `(- (- x) = x` is valid.
5. `(x + y) = x` is neither as its valid for `y = 0` but countervalid for all other values.

