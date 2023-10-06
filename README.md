# Key4hep tutorials

This repository contains instructions and documentation as well as potentially
necessary (code) resources for several Key4hep tutorials. Each tutorial is aimed
at being as standalone as possible, i.e. it should be possible to simply start
any tutorial without having done any other before. Each tutorial is in it's own
subfolder in this repository.

## Available tutorials

- [`gaudi_ild_reco`](./gaudi_ild_reco/README.md) - A tutorial that shows the
  full chain from simulation to reconstruction with the Gaudi based Key4hep
  framework using the ILD as example.

## The instructions look a bit weird
The instructions are in markdown (`md`) format, but they might contain `sphinx`
specific tags since some of them are also included in the [key4hep
website](https://key4hep.github.io/key4hep-doc/tutorials), where these allow for
a nicer rendering of additional information or the usage of more advanced
documentation features. These tags usually start with at least three colons
(':') and the most common one is probably

```
:::{dropdown} Some more text
```
