# 5.4 Docstrings

Just like with program headers and comments, we add **docstrings** to document what the function does, the purpose of the parameters, what it returns, and who wrote the docstring.

## Docstring Template
```python
""" Description

Args:
  param1 (type): description
  param2 (type): description

Returns
  type: description
"""
```

## Example #1: Area of Rectangle
Add a docstring to the following function. We will do this in Lesson.py
```python
def rect_area(l: float, w: float) -> float:
  area = l * w
  return area
```