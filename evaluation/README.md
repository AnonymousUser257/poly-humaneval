# Evaluation

This folder provide scripts to evaluation the generated code for PolyHumanEval.

## Usage
To simplify the replication, you can use `nix` package manager(Note that swift package is broken in nix currently, you should manually install it on your computer.)
```bash
> nix-shell
> python code/check_poly_humaneval_parallel.py
```
If the environment is well settled, this code should print no error message.

Then you can start evalute the results:
```bash
> nix-shell
> python code/check_generated_parallel.py --input data/RQ1-2_CodeLlama-13B.json --output result.json
```
This will evaluate all codes in `data/RQ1-2_CodeLlama-13B.json` and produce the results at `result.json`.
