# Contributing to MyCode

MyCode is primarily a personal learning repository, but thoughtful suggestions and improvements
are welcome.

## Before Adding Code

- Keep examples focused on one concept or problem.
- Prefer clear, beginner-friendly code over unnecessary abstractions.
- Add only work that can be explained and maintained.
- Do not commit credentials, tokens, generated files, or machine-specific configuration.
- Use the existing structure when it fits; introduce a new directory only when it represents a
  meaningful category of content.

## Organizing Content

Use descriptive, lowercase directory and file names. Group code by its purpose:

- `languages/` for language-specific practice
- `algorithms/` for algorithm implementations and problem solving
- `data-structures/` for data-structure exercises
- `projects/` for small, self-contained projects
- `experiments/` for focused investigations and prototypes

If an example needs context, include a short local README explaining what it demonstrates and how
to run it. Keep setup instructions close to the code they describe.

## Reviewing Changes

Before opening a pull request or sharing a change:

1. Check that the code runs or compiles when a local toolchain is available.
2. Remove temporary files and local configuration.
3. Update nearby documentation when the structure or usage changes.
4. Confirm that links and commands in the relevant README still make sense.

There is no requirement to add a test framework for a small learning exercise. Add tests when
they meaningfully demonstrate or protect the behavior being practiced.
