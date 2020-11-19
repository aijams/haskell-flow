# haskell-flow
A Flow Based Programming runtime written in Haskell

# Why FBP?
Support for Flow Based Programming (FBP) is mostly non-existant outside of Javascript, with the notable exception of J. Paul Morrison's repositories for Java, C\# and C++. This project is an attempt to build an FBP scheduler using Haskell.

# Why Haskell?
Haskell as a language is quite different from more traditional imperative-style languages. This project will test the virtues of combining the language features of Haskell with those of FBP.

# Project Scope
This project is intended to be a conceptual test of compatibility between Haskell and FBP by construction of an FBP scheduler and a set of basic components.

The list of deliverables is as follows:
- An FBP runtime capable of accepting a graph specification as input, then executing the processes specified in the graph.

# FBP Runtime
The FBP runtime will require the following active components:
- Graph Parser
- Scheduler
- Process Runner

The runtime will also require these storage components:
- Process Checkpoint Storage
- Connection Queue Storage