# cll-std

**standard library** — part of [CLL](https://github.com/CLT-Wasim/CLL), the Conserving Logic Language.

> Read [`AGENTS.md`](./AGENTS.md) first. It points at the binding rules; this README is only a summary.

## Purpose

core, alloc, std: deterministic collections, strings, and the project's own math library. Time and randomness are capabilities, not ambient services.

## Status

Pre-v1. Nothing here is shipped until a command produced the result and the result is in a
results table with the command that produced it. See the milestone list in
[`ROADMAP.md`](https://github.com/CLT-Wasim/CLL/blob/main/ROADMAP.md).

## Layout

* `core/`
* `alloc/`
* `std/`
* `math/`

## Language policy

CLL only (DECISIONS [139]). No third-party dependencies at runtime.

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
