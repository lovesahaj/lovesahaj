# Sahaj

Compilers and GPU work in Zig, Rust, and C++. Currently doing an MSc in
Computer Science at the University of Edinburgh. Previously shipped a
Rust → Verilog topological-sort compiler at Infineon (24× speedup on the
team's largest IP designs), and backend / data-pipeline work at Max Healthcare.

## What I'm working on

**[Zigton](https://github.com/lovesahaj/zigton)** — a Triton-inspired tile DSL
in Zig that compiles to CUDA PTX. Building it in public, phase by phase.

- **Phase 0** — host runtime around the CUDA Driver API
- **Phase 1** — Zig kernels → PTX, wired into `build.zig`, first tile abstraction
- **Phase 2** — shared memory, barriers, block-level reductions *(in progress)*

Writeups live on the blog: [portfolio.lovesahaj1225.workers.dev](https://portfolio.lovesahaj1225.workers.dev/#writing).

## Reach me

- email — lovesahaj@outlook.com
- linkedin — [linkedin.com/in/lovesahaj](https://linkedin.com/in/lovesahaj)
- x — @love_sahaj

Open to compiler, GPU, and ML infrastructure roles.
