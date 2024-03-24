# Evaluation

This folder provide scripts to evaluation the generated code for PolyHumanEval.

## Usage
To simplify the replication, you can use `nix` package manager:
```bash
> nix-shell
> bash check_gold_solution.sh
```
If the environment is well settled, this code should print no error message.

Then you can start evalute the results:
```bash
> nix-shell
> bash evaluate_generated.sh
```
This will evaluate all codes in `data/RQ1-2_CodeLlama-13B.json` check the results.
