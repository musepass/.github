# Contributing to MusePass

The project's contributing guide lives with the code:
**[musepass/musepass → CONTRIBUTING.md](https://github.com/musepass/musepass/blob/main/CONTRIBUTING.md)**.

Three rules are not negotiable, and they apply to every repository in this
organisation:

1. **Do not invent data.** Every published number carries a transaction hash, an
   endpoint or a command that reproduces it.
2. **Claims are gated.** A sentence about what the product can do maps to a gate in
   `config/claims-gates.json`; opening a gate needs evidence attached to it.
3. **The site is English only.** The build fails on a CJK character under `apps/web`.
