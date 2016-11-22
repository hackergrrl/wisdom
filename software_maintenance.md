(from _Building Maintainable Software_ by Joost Visser. Some notes are verbatim
Joost's, others are rewritten by me based on my understanding of his concepts.

---

# Write shorter units of code

Shorter units (functions, in most languages) are easier to analyze, test, and reuse.

# Write simple units of code

Units with fewer decision points (conditional branches) are easier to analyze and test.

# Write code once

Duplication of code (including literals) should be avoided at all times, since changes will need to be made to each copy. Duplication is also a source of regression bugs.

# Keep unit interfaces small

Units with fewer parameters are easier to test and reuse

# TODO: write something about complexity (amount of state coder needs to keep in their head) per-unit and per-module

# Separate concerns in modules

Modules that are loosely coupled are easier to modify and evolve

# Couple architecture components loosely

Top-level business logic components that are more loosely coupled are easier to modify, and lead to a more modular system

# Keep architecture components balanced

A well balanced architecture, with not too many and not too few components, of uniform size, is the most modular and enables easy modification through separation of concerns.

# Keep your codebase small

A large system is difficult to maintain because more code needs to be analyzed, changed, and tested. Also, maintenance productivity _per line of code_ is lower in a large system than in a small system.

# write automated tests

# write clean code

1. leave no unit-level code smells behind
  1. long units
  2. branching units
  3. units /w large interfaces
2. leave no bad comments behind
3. leave no code in comments behind
4. leave no dead code behind
5. leave no long identifier names behind
6. leave no magic constants behind
7. leave no badly handled exceptions / error cases behind

