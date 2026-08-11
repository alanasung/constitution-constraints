<p align="center">
  <h1 align="center">Constraint Checks for Multi-Rule Constitutions</h1>
  <p align="center"><strong>Encode constitution-like rules as constraints and measure multi-dimensional compliance on local models.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Constraint Checks for Multi-Rule Constitutions**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Encode constitution-like rules as constraints and measure multi-dimensional compliance on local models.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
