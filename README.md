## Rasmus Ros

Kotlin, Python, and Go. Optimization, streaming statistics, and LLM tooling.

### Tools

- **[lx](https://github.com/rasros/lx)** (Go) CLI and agent skill that bundles files for LLMs, with type/function skeletons, tree views, etc.
- **[vectrify](https://github.com/rasros/vectrify)** (Python) Raster to vector via LLMs and NSGA-II.

### Eignex

[Eignex](https://eignex.com) is a Bayesian optimization framework with a constraint system for ruling out invalid configurations, started during my PhD on optimizing software configurations. It is split into Kotlin multiplatform libraries:

- **[combo](https://github.com/Eignex/combo)** The main engine that ties it together. Under construction.
- **[kumulant](https://github.com/Eignex/kumulant)** Lock-free streaming statistics: EWMA, time-decaying aggregates, and more.
- **[klause](https://github.com/Eignex/klause)** Hybrid general-purpose CSP-SAT-LP optimizer.
- **[koblas](https://github.com/Eignex/koblas)** BLAS and LAPACK bindings for dense and sparse matrices, with reference implementations when system binaries are missing.
- **[skema](https://github.com/Eignex/skema)** Schemas that are both typed Kotlin code and serialized wire data, so consumers without the Kotlin source can still walk them.
- **[kencode](https://github.com/Eignex/kencode)** Compact, ASCII-safe encodings for size-limited channels.
- **[kpermute](https://github.com/Eignex/kpermute)** Shuffle huge sequences without holding them in memory; also handy for ID obfuscation.

### Other

- **[prompts](https://github.com/rasros/prompts)** Prompts library used with [lx](https://github.com/rasros/lx).
- **[largesofteng](https://github.com/lunduniversity/largesofteng)** Open labs for a Lund course on software at scale.
- **[aoc23](https://github.com/rasros/aoc23) / [aoc25](https://github.com/rasros/aoc25)** Advent of Code.
- **[Google Scholar](https://scholar.google.com/citations?user=ojVVLfkAAAAJ&hl=sv)** Publications.
