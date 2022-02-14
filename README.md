# string-conv-tests


## Synopsis

Property tests for the Haskell string-conv library


## Description

These are in a separate project not only to keep dependencies low when the
string-conv library is included in a project but also because these property
tests use `quickcheck-instances` which defines many orphan instances. Never a
good idea to force instances like this on other projects.

This project expects the source code of the string-conv project to be in a
sibling directory.


## Development

To run these tests

    $ stack test string-conv-tests


## Contact

### Authors

Dino Morelli <dino@ui3.info>
