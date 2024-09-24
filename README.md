# app-eselect/eselect-kubler

WARNING! This will only work when using kubler from my Gentoo overlay found at:
[lysolaka/genthree](https://github.com/lysolaka/genthree)

## Why?

This is really the main question with this eselect module.
The short story is that [kubler](https://github.com/edannenberg/kubler) from the [kubler overlay](https://github.com/edannenberg/kubler-overlay) doesn't fully work.
Then just before giving up I found a [fork](https://github.com/babykart/kubler) of kubler, which surprisingly worked until a specific moment.
Then it appeared that the 'official' kubler worked rest of the way.

Obviously the solution is to fix the official kubler or make a fully working fork, but I lack the skills to do that.
The best I could do is to put both kubler versions into slots and manage symlinks using eselect.
