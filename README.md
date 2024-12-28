# 07.-Python-Logical-and-Comparison-Operators-in-Python
Here’s a well-structured explanation of logical and comparison operators in Python with code examples,
# **Logical and Comparison Operators in Python**

This chapter covers **logical operators** and **comparison operators**, which are essential for building conditional expressions, controlling program flow, and filtering data in Python.

---

## **Logical Operators**

Logical operators are used to combine conditional expressions and return a boolean value.

| Operator | Description                         | Example           | Result   |
|----------|-------------------------------------|-------------------|----------|
| `and`    | Returns `True` if both conditions are true | `(5 > 3) and (2 > 1)` | `True`   |
| `or`     | Returns `True` if at least one condition is true | `(5 > 3) or (2 < 1)` | `True`   |
| `not`    | Reverses the boolean value of a condition | `not(5 > 3)`     | `False`  |

---

## **Comparison Operators**

Comparison operators compare values and return a boolean result.

| Operator | Description               | Example      | Result  |
|----------|---------------------------|--------------|---------|
| `==`     | Equal to                  | `5 == 5`     | `True`  |
| `!=`     | Not equal to              | `5 != 3`     | `True`  |
| `>`      | Greater than              | `5 > 3`      | `True`  |
| `<`      | Less than                 | `5 < 3`      | `False` |
| `>=`     | Greater than or equal to  | `5 >= 5`     | `True`  |
| `<=`     | Less than or equal to     | `5 <= 3`     | `False` |

---

## **Code Examples**

### **Logical Operators**
```python
# Example of logical AND
a = True
b = False
print("a and b:", a and b)  # Output: False

# Example of logical OR
print("a or b:", a or b)    # Output: True

# Example of logical NOT
print("not a:", not a)      # Output: False
