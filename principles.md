
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
