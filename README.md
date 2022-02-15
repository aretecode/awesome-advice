# Awesome Advice [![awesome.list](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome pieces of advice

## Priority
- The better the problem is defined, the better the solution will be

## Research
- #1. most important thing in programming is knowing how to research.
- #2. is research.
- #3. is research.

## 15 minute rule
  > general rule of thumb / proverbial saying, not 100% black-and-white, just don't be an askhole.

  - If you ask for help on a problem before doing at least 15 minutes of work researching, debugging, and defining your problem, you're doing the other person a disservice.
  - If you wait longer than 45 minutes and you are stuck, you are doing yourself a disservice.

## Proverbial
- Measure twice, cut once
- There is never any code that is more permanent than temporary code
- When you have a hammer, everything looks like a nail
- If you're not using a framework, you're making one.

## Principles (search these out if you don't know them!)

**YAGNI** (Ya Ain't Gonna Need It)

> "Always implement things when you actually need them, never when you just foresee that you need them." - Martin Fowler

Related: Gall's Law, KISS, Occams Razor

**KISS** (Keep It Simple Stupid)

Understand the difference between simple and easy, watch [Rich Hickey's talk](https://www.infoq.com/presentations/Simple-Made-Easy/). Avoid unnecessary complexity to keep systems easier to understand and update.

**DRY** (Don't Repeat Yourself)

> "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system." - The Pragmatic Programmer

**SOLID**
- Single-responsibility Principle: Classes should only have one reason to change, have only one job
- Open-Closed Principle: Classes should extendable without modifying the class itself
- Liskov Substitution Principle: Every subclass can be replaced by it's parent (recursive)
- Interface Segregation Principle: Never have unused dependencies or force unused interface implementations
- Dependency Inversion Principle: Avoid direct dependencies by using an abstraction (e.g. interface)

**POLA** (Principle Of Least Astonishment)
- Systems should not surprise the user
- Behavior should be consistent with prior knowledge
- Users feel a sense of comfort/control when it behaves predictably

**80/20** (Pareto Principle)
80% of results come from 20% of the input. For example, fixing 20% of the bugs results in 80% drop in errors. Or, 80% of a system can be written in 20% of the time (the final pieces of a project are 4x slower).

Related Principles: Done is better than Perfect, Minimum Effective Dose

**Occam's Razor** (Principle of Parsimony)
The simplest explanation is usually the best.

**MED** (Minimum Effective Dose)

The smallest dose that will produce a desired outcome. Do more with less.

> "Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away." - Antoine de Saint-Exupéry

Related Principles: MVP, 80/20

## Laws

**LOD** (Law Of Demeter)

> A class should have only limited knowledge about the details of its dependencies.

Build deep classes but shallow APIs. Hide internal knowledge and reduce API complexity.

**BDUF** (Big Design Up Front)

> First solve the problem, then write the code

Design should be done before coding starts
- Remove blockers for exponential speed gains
- Sequence milestones thoughtfully
- Align on breakdown and ownership

**SOC** (Separation of concerns)

Build domain boundaries around necessary dependencies, build interfaces where domains must interact.

**SSOT** (Single Source Of Truth)

Reliable data should be found in one place. Related: immutability

**CQS** (Command-query separation)

Separate writes from reads. E.g. DB writes/reads.

## Best Practices

**Use the right tool for the job**

> "If your only tool is a hammer, every problem looks like an nail." - Abraham Maslow

There are no good or bad solutions, only optimizations around specific context.

The answer to any CS question is always "maybe".

**Avoid premature optimization**

Humans are terrible at predicting the future, your code is not likely withstand the test of time, it's more important to be modifiable and deletable than all-encompassing.

---

## General
- Design patterns: don't let the names dictate the form of your code
- Expressive, clearly communicative, clean code
  - Have [variable names describe their intention](https://twitter.com/svensauleau/status/856424137493008384)
- Join in the community, conversing with people interested in the same thing, helping solve problems & getting your problems solved
- Don't worry if you think it sucks, contributing open source code helps build important skills, practice makes permanent
- Muscle memory is 10x more effective than memorization: study, but don't forget to _exercise_ your learning

[eslint]: https://www.npmjs.com/package/eslint
[prettier]: https://github.com/prettier/prettier
[tslint]: https://www.npmjs.com/package/tslint-eslint-rules
[xo]: https://github.com/sindresorhus/xo

## Tools
- Consistency - use tools to keep consistent rules [[eslint][eslint], [prettier][prettier], [tslint][tslint], [xo][xo]]
- [Backwards compatibility is for suckers](http://blog.ircmaxell.com/2013/06/backwards-compatibility-is-for-suckers.html)

## Performance
- Premature optimization is the root of all evil
- Make it debuggable
- Ensure that the micro-optimizations are really things to optimize if they may do less benefit and cause more negatives than obvious ones
- [Benchmark](https://github.com/aretecode/bench-chain)

## Always
- Good APIs
- Schema validation
- Good http transactions
- Simple DBs

--------

## Contribute

Contributions welcome!
Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)
To the extent possible under law, James has waived all copyright and related or neighboring rights to this work.
