# Reconstruction for Lax Module Monads

Slides for my [CT2025](https://conference.math.muni.cz/ct2025) talk.

- To clone, use `git clone --recurse-submodules «URL»`;
  this is important, since the style file and the beamer template are in their own repositories,
  and a specific commit is included here.
  Be sure to check out the `ct2025` branch!

- To build, either use `nix build .?submodules=1` to automatically pull in any dependencies,
  or try your best with `latexmk -pdf main`.
