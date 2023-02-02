[![Community Gitter](https://badges.gitter.im/aesara-devs/community.svg)](https://gitter.im/aesara-devs/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# Welcome to the Aesara Project

![logo](https://github.com/aesara-devs/aesara/blob/main/doc/images/aesara_logo_2400.png?raw=true)

Aesara is a hackable meta-tensor library, it allows the manipulation of mathematical expressions involving multidimensional arrays. It currently supports C, Numba and JAX as backends.

## What distinguishes Aesara from other tensor libraries?

**With Aesara you only have to focus on the model**

Aesara decouples the mathematical representation of models from compiler-specific considerations. When building an Aesara model, users build a symbolic graph that represents the mathematical operations performed by the model. This graph can be inspected and modified at runtime thanks to a powerful rewrite system, without ever leaving Python, and ultimately transpiled to any of the supported backends. Aesara is modular by design and it is straightforward to add new mathematical operators, new rewrite rules (numerical stabilization, optimizations, etc.), and even new backends.

Aesara opens new possibilities in Machine Learning, exemplified by the AePPL and AeMMC libraries.

## The Aesara ecosystem

* [AePPL](https://github.com/aesara-devs/aeppl) provides an intermediate representation for Probabilistic Programming Languages, and automatically derives log-densities for probabilistic models;
* [AeHMC](https://github.com/aesara-devs/aehmc) provides a symbolic implementation of the HMC and NUTS samplers;
* [AeMCMC](https://github.com/aesara-devs/aemcmc) automatically builds custom samplers for probabilistic models;

Although Aesara grew out of probabilistic modeling, it is more general and shouldn't be conflated with these domains of applications.

## Reach out to us

Chat with us via the [Gitter](gitter.im) links above.  They're also compatible with [Matrix](https://matrix.org/)!
