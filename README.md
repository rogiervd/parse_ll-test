# Superrepository for _parse_ll_ repository

This repository is used to run the unit tests for the _parse_ll_ repository.
It contains the submodules that the _parse_ll_ repository requires, with commits that are compatible with each other.
The Jamroot file tells Boost.Build how to test this repository when one says:

    bjam test

[![Build Status](https://travis-ci.org/rogiervd/parse_ll-test.svg?branch=master)](https://travis-ci.org/rogiervd/parse_ll-test)
