# Knapsack: a flexible, light weight, open source persistence library

This is based on Arthur Lemmens's [Rucksack](http://common-lisp.net/project/rucksack/) with some enhancements.

## Getting started

To compile and load Knapsack and make sure that the basics are working:

1. Make sure you have ASDF (Another System Definition Facility) loaded.

2. Load knapsack.asd.

3. Load tests/knapsack-test.asd.

4. (asdf:oos 'asdf:load-op :knapsack-test)

5. (in-package :knapsack-test)

6. (run-tests)

## Tutorial

The tutorial by Brad Beveridge (in doc/rucksack-tutorial.lisp) is a
good next step.
