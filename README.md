# tutorial-cat

Code for the `Pragmatic Introduction to Category Theory`.

[Slides](https://speakerdeck.com/danielasfregola/scalaworld-2017-a-pragmatic-introduction-to-category-theory) and [video](https://www.youtube.com/watch?v=Ss149MsZluI) are now available online!

## Installation
- clone the repo
- `sbt test:compile`
- `sbt run`
- if you see the secret message you are good to go!

## Agenda

### Intro

### Monoid
- Define a monoid for `Int`
- Define a monoid for `String`

`sbt 'testOnly *Monoid*'`


### Functor
- Define a functor for `Maybe`
- Define a functor for `ZeroOrMore`

`sbt 'testOnly *Functor*'`


### Applicative
- Define `map` in terms of `ap` and `pure`
- Define an applicative for `Maybe`
- Define an applicative for `ZeroOrMore`

`sbt 'testOnly *Applicative*'`

### Monad (1)
- Define `flatten` using `flatMap`
- Define `map` using `flatMap` and `pure`
- Define `ap` using `flatMap` and `map`

### Monad (2)
- Define a monad for `Maybe`
- Define a monad for `ZeroOrMore`

`sbt 'testOnly *Monad*'`


## Solutions
Solution of the exercises are available [here](https://gist.github.com/DanielaSfregola/ddf48f6c5638f6284b563798c55d5ebd)
