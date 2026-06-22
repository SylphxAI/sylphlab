# SylphLab Project

SylphLab is an incubating research repository. Its current default branch only
contains minimal documentation, so any future product, code, deployment, or
commercial boundary must be added explicitly before agents treat it as active.

## Lifecycle

- Lifecycle: `incubating`
- Layer: `research`
- Doctrine source of truth: [SylphxAI/doctrine](https://github.com/SylphxAI/doctrine)
- Machine manifest: `.doctrine/project.json`

## Goals

- Preserve a minimal research workspace for future SylphLab experiments.
- Require future code, docs, CI, delivery, and commercial surfaces to declare
  their own boundaries before production-shaped work begins.

## Non-Goals

- Do not infer production behavior, deployment, pricing, or package release
  obligations from the current minimal repository state.
- Do not use this repository as a hidden dependency for another product without
  a declared public surface.

## Boundaries

This repository currently owns only its minimal research documentation and the
project manifest. Future experiments must update this file and
`.doctrine/project.json` before they add product-specific behavior or public
surfaces.

## Public Surfaces

- Minimal privacy documentation in `Privacy.md`
- Project control-plane manifest in `.doctrine/project.json`

## Delivery

No CI or deploy path is declared. Current proof is project manifest audit only.
Future active work must add local validation and delivery proof before claiming
production readiness.

## Commercial Direction

`not-applicable`: no pricing, packaging, paid entitlement, or commercial
experiment surface is declared in the current repository state.
