# ihaskell-examples

A collection of Haskell examples / experiments written as IHaskell notebooks.

## Generative Art

These exaples levarage the [random-fu](http://hackage.haskell.org/package/random-fu) library for seeded randomization and the [diagrams](https://archives.haskell.org/projects.haskell.org/diagrams/doc/quickstart.html) library for drawing.

* [Basic Usage](genart/basic_usage.ipynb) - Basic usage of the diagrams and random-fu libraries.
* [Stack v1](genart/stack_v1.ipynb) - A first approach to generating art, based on random evolutions.
* [Stack v2](genart/stack_v2.ipynb) - A second approach I have just begun working on, utilizing a monad transformer stack simulating a changing environment with unchanging laws.
* Stack v3 - A third approach will use mtl typeclasses to separate generation and drawing effects. Other approaches I want to investigate include:
  * Using either typeclasses or [extensible](https://hackage.haskell.org/package/extensible) records to allow passing type-checked composable configuration data through reader.
  * Indroducing other environment data structures so that each artist can add their own state as needed.
