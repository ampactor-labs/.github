# Ampactor Labs

Ampactor Labs is [Morgan Espitia](https://ampactor.dev), a systems engineer in
Salt Lake City. The house rule: correctness is measured in CI, not asserted.
Every claim below has a command you can run that checks it.

| Project | The receipt |
|---|---|
| [turbosort](https://github.com/ampactor-labs/turbosort) | SIMD radix sort on [crates.io](https://crates.io/crates/turbosort): 2.2–3.2× `std::sort` for u32/f32, measured 1M–100M keys; perf/flamegraph profiling story in the README; Miri-checked unsafe core on every push |
| [landed](https://github.com/ampactor-labs/landed) | Fail-closed Solana execution gateway on [crates.io](https://crates.io/crates/landed): assemble, gate, submit by RPC or Jito bundle, track to a landed slot; CI starts a real `solana-test-validator` and lands live transactions every push |
| [two-top](https://github.com/ampactor-labs/two-top) | Rollback-netcode brawler: bit-identical simulation across Linux, ARM, macOS, and Android, verified by CI checksum diff; Q16.16 fixed-point, zero floats in the sim |
| [sonido](https://github.com/ampactor-labs/sonido) | One `no_std` Rust DSP codebase shipping as a CLAP plugin, a live WASM demo, and bare-metal STM32/Daisy firmware; 36 effects, 1,800+ tests, per-effect µs budgets |
| [mentl](https://github.com/ampactor-labs/mentl) | Self-hosting compiler targeting WebAssembly: byte-identical self-compilation fixpoint, boots from a 1.6 MB WASM build of itself |
| tokensafe | Live paid Solana token-safety API: x402 USDC micropayments, Ed25519-signed verdicts, Docker/Prometheus in production — [ampactor.dev](https://ampactor.dev) |

Also live at [ampactor.dev](https://ampactor.dev): COPYCATS (race your own
replay ghosts) and BITS (a video instrument — perform the edit). Upstream:
found and patched a fail-open vulnerability in Coinbase's x402 Rust paygate
(PR #74).

Currently interviewing for systems roles, Salt Lake City or remote.
Resume and contact: [ampactor.dev](https://ampactor.dev) ·
ampactorlabs@gmail.com
