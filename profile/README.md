<div align="center">

<img src="https://github.com/aesara-devs/aesara/blob/main/doc/images/aesara_logo_2400.png?raw=true" alt="logo"></img>

[![Gitter][gitter-badge]][gitter]
[![Discord][discord-badge]][discord]
[![Twitter][twitter-badge]][twitter]

*Welcome to the Aesara Project!*

</div>

The Aesara Project is a collection of Python projects&mdash;built on a fork of Theano named [Aesara](https://github.com/aesara-devs/aesara)&mdash;that aid in the construction and use of domain-specific compilers for tensor-related computations.

Currently, the Aesara Project primarily serves the probabilistic modeling community through its Probabilistic Programming Language-generating capabilities and model-specific optimizations; however, its scope is not limited to just that.  See the discussion [here](https://github.com/aesara-devs/aesara/discussions/879#discussioncomment-2472927) for an explanation of the Aesara Project's goals and history.

## The Aesara projects

* [Aesara](https://github.com/aesara-devs/aesara) is a hackable "meta" tensor library that enables the manipulation of mathematical expressions involving multidimensional arrays;
* [AePPL](https://github.com/aesara-devs/aeppl) provides an intermediate representation for Probabilistic Programming Languages, and automatically derives log-densities for probabilistic models;
* [AeHMC](https://github.com/aesara-devs/aehmc) provides a symbolic implementation of the HMC and NUTS samplers;
* [AeMCMC](https://github.com/aesara-devs/aemcmc) automatically builds custom samplers for probabilistic models and performs model-specific optimizations such as automatic Rao-Blackwellization, Bayesian conjugation, and marginalization.

## What distinguishes Aesara from other tensor libraries?

In the context of statistical modeling, **Aesara allows you to focus only on the model**.  It provides a single, easily customizable form of a model that can be used to encode all the information needed to produce numerical optimizers and samplers.

In other words, users can build a symbolic graph that represents the mathematical operations performed by the model. This graph can be inspected and modified at runtime&mdash;thanks to a fully featured and extensible rewrite system&mdash;and all without ever leaving Python.  Graphs can then be transpiled to a number of supported target languages (e.g. C, Numba, JAX).

Aesara is modular by design and it is straightforward to add new mathematical operators, new rewrite rules (e.g. numerical stabilizations, optimizations, etc.), and even new target languages.

**Aesara opens new possibilities in Machine Learning, exemplified by the AePPL and AeMMC libraries.**


## Contact us!

Chat with us via the [Gitter](gitter.im) link above. It's also compatible with [Matrix](https://matrix.org/)!

[discord]: https://discord.gg/h3sjmPYuGJ
[discord-badge]: https://img.shields.io/discord/1072170173785723041?color=81A1C1&logo=discord&logoColor=white&style=flat-square
[gitter]: https://gitter.im/aesara-devs/community
[gitter-badge]: https://img.shields.io/gitter/room/aesara-devs/community?color=81A1C1&logo=matrix&logoColor=white&style=flat-square
[twitter]: https://twitter.com/AesaraDevs
[twitter-badge]: https://img.shields.io/twitter/follow/AesaraDevs?style=social
