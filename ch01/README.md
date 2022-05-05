# Rust Life | Introduction | Gyaan Waali Baatein
Part 1 of this series is more about highlighting relevance of using Rust programming language.
Those who can interpret following concepts can easily draw advantage of Rust over other programming languages.
Skip this part if you are interested in actual code. It is there in Part 2. 

```
"Padhna hai to padho, warna aage badho" - adage from college life.
```

## What is Rust?
- Rust is a modern programming language with a focus on performance and safety.
- Rust’s safety guarantees don’t come for free, the cost of those features' comes in terms of added language and compilation-time complexity.
- the main differentiator is the lack of a runtime interpreter, as Rust is compiled to platform-dependent binaries. Thus, one must distribute their Rust programs as binaries.

## The Core Suite
- rustc, the official Rust compiler
- cargo, a package manager and build tool
- crates.io, a package registry

## Modern programming language features
- The borrow checker, which enforces Rust’s memory management model 
- Static typing
- Asynchronous I/O Closures
- Generics
- Macros
- Traits

## Safety
- Rust can provide very high safety guarantees by a feature known as the borrow checker.
- Rust’s borrow checker works by validating references at compile time, rather than reference counting or performing garbage collection at runtime.
- The borrow checker is part of Rust’s compiler, rustc, which verifies that for any given object or variable, there can be no more than one mutable reference. It’s possible to have multiple immutable references (i.e., read-only references) to objects or variables, but you may never have more than a single active mutable reference.
- With Rust, it’s not possible to have more than one mutable reference simultaneously, thereby ensuring data synchronization issues are avoided.

## Modern
- Rust largely eschews paradigms like object-oriented in favour of traits, generics, and functional programming.
### Features worth highlighting
- lifetimes, for handling references
- metaprogramming, through its macro system 
- asynchronous programming, with async/await
- zero cost abstractions


## Use cases
- Code Acceleration
  - accelerate functions from other languages like Python, Ruby, or Elixir.
- Concurrent systems
  - safety guarantees apply to concurrent code.
- Cryptography
  - ideally suited for implementing cryptography algorithms.
- Performance critical
  - It’s easy to write code that’s extremely fast, without compromising on safety with Rust.
- String processing
  - it’s easy to write code that can’t overflow.
- Replacing legacy C or C++

## Personal Usecase
- Highly paid salaries
  - Many crypto and financial services projects are high on Rust adoption. 
  - From application development to CI/CD pipelines Rust can be plug-in at any corner.
  - These projects offer exceptionally high salaries to their dev team members. :heart_eyes:
