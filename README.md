# interactor-aria-fate

Character generation and planning for an aspect-based tabletop role-playing system, built on its CC BY reference documents.

## What it is for

It models a character sheet and a character arc, generates characters under constraints, parses the system reference documents it carries, and exposes a planner domain that builds a character step by step.

## Build and run

It does not build standalone. `mix.exs` takes its build, config and dependency paths and its lockfile from an umbrella root two levels up, and no repository in the organisation holds it as an umbrella app; it builds once `mix.exs` drops those `../../` paths or an umbrella places it under `apps/`.

## Licence

The repository has no LICENSE file, so the code's licence is not stated. The reference documents it carries are under Creative Commons Attribution.
