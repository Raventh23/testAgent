# testAgent
QuickCalculator

A simple Python calculator that performs basic arithmetic operations.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division
- Error handling for division by zero
- Interactive command-line interface
- Clean, object-oriented design

## Usage

### Interactive Mode

Run the calculator in interactive mode:

```bash
python3 calculator.py
```

Then enter calculations in the format: `number operator number`

Example:
```
Enter calculation (e.g., '5 + 3') or 'quit': 10 + 5
Result: 15.0

Enter calculation (e.g., '5 + 3') or 'quit': 20 / 4
Result: 5.0

Enter calculation (e.g., '5 + 3') or 'quit': quit
Goodbye!
```

### Programmatic Usage

You can also import and use the Calculator class in your own code:

```python
from calculator import Calculator

calc = Calculator()

# Basic operations
result = calc.add(5, 3)        # 8
result = calc.subtract(10, 4)  # 6
result = calc.multiply(6, 7)   # 42
result = calc.divide(15, 3)    # 5.0
```

## Supported Operations

- `+` : Addition
- `-` : Subtraction
- `*` : Multiplication
- `/` : Division (with zero-division protection)

## Requirements

- Python 3.x

