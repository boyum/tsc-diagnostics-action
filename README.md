# tsc-diagnostics-action

This GitHub Action runs the TypeScript compiler (tsc) with the `--diagnostics` and optionally the `--extendedDiagnostics` flags on your codebase and compares the output with the main branch.
It can trigger an error if the change in the compiler performance metrics (such as memory usage, emit time, etc.) exceeds a certain threshold.
This can help you monitor and optimize the performance of your TypeScript code.
