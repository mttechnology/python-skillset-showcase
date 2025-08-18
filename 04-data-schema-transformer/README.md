# Data Schema Transformer

## Overview
This project demonstrates how to transform **raw sales data** (stored as a list of tuples) into a **structured, schema-based dictionary**.  
The goal is to practice data structuring, using the zip function effectively, and designing extensible code that adapts to future changes in schema.

---

## Example Data

```python
data = [
    ("item1", 10, 100.0),
    ("item2", 5, 25.0),
    ("item3", 100, 0.25)
]

schema = ["name", "sold", "unit_price"]
```
## Expected Output
```python
{
    "item1": {"sold": 10, "unit_price": 100.0},
    "item2": {"sold": 5, "unit_price": 25.0},
    "item3": {"sold": 100, "unit_price": 0.25}
}
```
## Key Points
Main key: product name
Value: dictionary of attributes (from schema)

Extensible design: if schema changes 
```python 
# For Example:
["name", "sold", "unit_price", "stock"]
```
the code still works with minimal modifications

