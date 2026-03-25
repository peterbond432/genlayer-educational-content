# Hello World Intelligent Contract

This tutorial shows how to create a simple “Hello World” contract using GenLayer.

## Steps

1. Open GitHub Codespaces (green **Code → Open with Codespaces**).
2. Create a new Python file: `hello_world_validator.py`
3. Paste the following code:

```python
from genlayer import Validator

validator = Validator(name="HelloWorldValidator")
result = validator.run_test("Hello World")
print(result)  # Output: "Hello World"
