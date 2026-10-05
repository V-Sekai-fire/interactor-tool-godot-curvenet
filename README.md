# interactor-tool-godot-curvenet

A Lean 4 specification of profile-curve character deformation, with its compute kernels emitted as Slang and checked against the spec.

## What it is for

The Lean package states the deformation and emits each kernel, and checked lemmas pin the emitted text and the algorithm's invariants. The same package reads and writes glTF and safetensors and builds a small demo rig as a `.glb`. [`docs/DEVELOPING.md`](docs/DEVELOPING.md) covers how the pieces fit, and [`references.bib`](references.bib) lists the papers.

## Build and run

    misc/install-slang.sh
    cd lean && lake build

## Licence

MIT; see [`LICENSE.md`](LICENSE.md).
