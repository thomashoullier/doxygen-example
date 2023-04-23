# Doxygen example
A minimal example for running doxygen over a C++ project and deploying the
documentation to a github page automatically.

The doxygen example is taken from
https://pages.cs.wisc.edu/~jignesh/cs564/notes/Doxygen.pdf

I use the
[doxygen-github-pages-action](https://github.com/DenverCoder1/doxygen-github-pages-action).

Setting up a token with contents access is required. The action is run whenever
`master` is pushed to and the results pushed to a branch `gh-pages`.

The resulting website is available at https://thomashoullier.github.io/doxygen-example/index.html
