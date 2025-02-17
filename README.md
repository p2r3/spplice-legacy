# This is not the repository you're looking for.
Here you'll find the code for the very first version of Spplice, which was last updated in November of 2022. This version has been deprecated and, although likely still functional, is no longer supported.

Two major rewrites have come out since then - Spplice 2, which is built with Electron and is somewhat closed-source, and [SppliceCPP](https://github.com/p2r3/spplice-cpp), which is open-source and under active development. Please turn your attention to the latter instead, as we plan for that to be the definitive version of Spplice going forward.

## The first ever dedicated Portal 2 mod launcher
The Simple Portal 2 Package Loading Instrument for Convenient External modding, or Spplice for short, aims to be a solution to intuitive and user-friendly Portal 2 modding. Spplice makes it easy for players to hop in and play, and lets developers focus less on distribution, and more on making their games fun.

### Built on NeutralinoJS
To keep things lightweight, this project uses [NeutralinoJS](https://neutralino.js.org) for the web-based UI and for the API that manages Steam, Portal 2 and all of the packages. In short, Neutralino is similar to Electron. But instead of bundling a whole browser, it relies on what's already present on the user's system.

### Contributing
To contribute, all you need is Git, Neutralino, Steam, Portal 2, and a general understanding of what Spplice is about.

Assuming you've already installed Neutralino on your system, clone the repository and do `neu update` to fetch the required binaries. Then you can do `neu run` to ensure that everything works properly.
