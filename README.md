# Dozenal

A Python package for handling the Dozenal (base 12) system.

# Features
- Convert between decimal and dozenal (base 12)
- DozenalNumber class for arithmetic, comparison, and bitwise operations
- String conversion and parsing
- Absolute value, negation, exponentiation, and more

## Usage
```python
from dozenal import DozenalNumber

# Create from decimal or dozenal string
a = DozenalNumber(1728)
b = DozenalNumber('1000')

print(str(a))  # '1000'
print(int(b))  # 1728

# Arithmetic
c = DozenalNumber('10') + DozenalNumber('2')
print(str(c))  # '12'

# Bitwise and math operations
d = DozenalNumber('10') ** 2
print(str(d))  # '100'
print(abs(DozenalNumber('-10')))
print(~DozenalNumber('10'))
```

## Installation
```sh
pip install dozenal
```

## Publishing
To publish to PyPI:
1. Build the package: `python3 setup.py sdist bdist_wheel`
2. Upload: `twine upload dist/*`
# dozenal
