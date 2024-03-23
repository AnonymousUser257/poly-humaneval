# Self-Training Data

This folder contains self-generated data by CodeLlama-13B.
The `generated_py_codes.json`(generated_py_codes.json) is the LLM-generated Python code that have passed self-generated testcases.
The `generated.testdsl`(generated.testdsl) is the TestDSL format of over LLM-generated testcases.

The parallel Go code is presented in prompts for fine-tuning, which is saved in [./fine-tune-prompts](./fine-tune-prompts) folder, including 3 versions: unchecked, checked(pass@1) and checked(pass@5)
