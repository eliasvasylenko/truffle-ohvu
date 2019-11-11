# Preste

Preste is a predicatively-typed, purely-functional Lisp dialect with the following goals.

- An innovative "predicative" type system, making power-features like dependent types intuitively accessible to the average coder.
- An effect system, to realise the power of purely-functional programming within an imperative programming model.
- A deterministic concurrency model which can be locally reasoned about; inter-coroutine communication is mediated by a single thread in the form of an effect handler.
- Lisp-like macro metaprogramming, but with the additional power of the effect system to allow nested macros to collaborate within their lexical scope.
- A reference implementation supporting both native image generation and an interpreted mode with a state-of-the-art JIT compiler, via GraalVM & Truffle.
