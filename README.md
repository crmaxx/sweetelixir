# Sweet Elixir!
## A Gentle Introduction to Erlang’s cute younger brother Elixir

![elixir-lang][elixir-logo]

## Getting Started
1. **What is Erlang?**

  Erlang is a functional language with focuses on concurrency and fault tolerance. It first appeared in 1986 as part of Ericsson's quest to build fault tolerant, scalable telecommunication systems. It was open-sourced in 1998 and has gone on to power large portions of the worlds telecom systems, in addition to some of the most popular online services.

1. **Why Elixir?**

  Elixir is a language is built on top of the Erlang VM. Elixir exists with the goal to build concurrent, distributed, fault-tolerant systems with productive and powerful language features. Mainstream languages were constructed around limited CPUs, threading, and shared-everything state. This concurrency models can become fragile and can make concurrent programs difficult to reason about. Other languages skirt these issues by running on a single CPU with multiple processes to achieve concurrency; however, as Moore's Law pushes us towards increasing multicore CPUs, this approach becomes unmanageable. Elixir's immutable state, Actors, and processes produce a concurrency model that is easy to reason about and allows code to be written distributively without extra fanfare. Additionally, by building on top of Erlang, Elixir can take advantage of all the libraries and advantages that the Erlang ecosystem has to offer. 

1. [Setup][setup]
1. [Tools][tools]

## How to use
Most of this guide will use `iex` (interactive elixir).  We'll try to let you know when we don't, but here are some guidelines...

* `iex> command` means we're executing `command` in interactive elixir.
* `$> elixir <filename>` means run the `elixir` command at terminal to execute the file.  These files will most likely be an `.exs`  or elixir script file.  These will usually be found within the `src/` folder for that particular module.

## [Basics][basics]
1. Numbers, atoms, strings, lists, tuples, ...
1. Functions
1. [Operators][operators]
1. [Modules][modules]

[Cheatsheet][cheetsheet]

## Advanced
1. [Records & Protocols][records_protocols]
1. [Pattern Matching][pattern_matching]
1. [Map/Reduce][map_reduce]
1. [Pipeline][pipeline]
1. Processes

## [Common Patterns/OTP][otp]

1. Stack Server (manual)
1. GenServer, Supervisors

## Distributed Elixir

## Web & DB

[elixir-logo]: ./elixir-logo.png
[setup]: ./04-setup/README.md
[tools]: ./06-tools/README.md
[basics]: ./07-basics/README.md
[otp]: ./10-otp/README.md
[pattern_matching]: ./08-advanced/pattern_matching.md
[records_protocols]: ./08-advanced/records_protocols.md
[map_reduce]: ./08-advanced/map_reduce.md
[pipeline]: ./08-advanced/pipeline.md
[cheetsheet]: http://media.pragprog.com/titles/elixir/ElixirCheat.pdf
[operators]: ./07-basics/README.md#operators
[modules]: ./07-basics/README.md#modules
