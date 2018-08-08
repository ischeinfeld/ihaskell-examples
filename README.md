# ihaskell-examples

A collection of Haskell examples / experiments written as IHaskell notebooks.

## Generative Art

This collection of examples show how generative art can be produced in Haskell. These exaples levarage the [random-fu](http://hackage.haskell.org/package/random-fu) package for seeded randomization and the [diagrams](https://archives.haskell.org/projects.haskell.org/diagrams/doc/quickstart.html) library for drawing.

* [Basic Usage](genart/basic_usage.ipynb) - Basic usage of the diagrams and random-fu libraries.
* [Stack v1](genart/stack_v1.ipynb) - A first approach to generating art, based on random evolutions.
* [Stack v2](genart/stack_v2.ipynb) - A second approach, utilizing a monad transformer stack. Currently under development.
* Stack v3 - A third approach will use mtl typeclasses to separate generation and drawing effects. Other possibilites include
* * Introducing [extensible](https://hackage.haskell.org/package/extensible) records to the reader monad to allow for the composition of configuration data.
* * Indroducing other data structures to state so that each artist can add their own state as needed.
