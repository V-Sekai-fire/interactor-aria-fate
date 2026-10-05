# interactor-aria-fate

Character generation and planning for an aspect-based tabletop role-playing system, built on its CC BY reference documents.

## What it is for

It models a character sheet and a character arc, generates characters under constraints, parses the system reference documents it carries, and exposes a planner domain that builds a character step by step.

## Build and run

It is an umbrella application: its mix project takes its build, config and dependency paths from the umbrella root two levels up. From that root:

```sh
mix compile
mix test
```

## Licence

The repository has no LICENSE file, so the code's licence is not stated. The reference documents it carries are under Creative Commons Attribution.
