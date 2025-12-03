# Pandoc WASM

Build and run a WebAssembly (WASM) version of [Pandoc](https://pandoc.org/), the universal document converter. This project produces an optimized `pandoc.wasm` using the GHC `wasm32-wasi` toolchain and demonstrates execution with a WASI runtime (Wasmtime).

Docker image is available at https://hub.docker.com/r/shenlu89/pandoc-wasm

## Who is using Pandoc WASM?

- [Mathcheap](https://mathcheap.xyz): Converts LaTeX to DOCX documents.

## Acknowledgements

- Upstream source: https://github.com/haskell-wasm/pandoc (branch `wasm`)
- WASI runtime: https://wasmtime.dev/

## License

Licensed under [GPL-2.0-or-later](https://github.com/mathcheap/pandoc-wasm/blob/main/LICENSE).
