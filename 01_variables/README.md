
# Module 01 — Variables & Data Types

## What Are Variables?
A variable is a container that stores a value in your program. Think of it like a labelled test tube in a biology lab — the label is the variable name, and what's inside is the value.

---

## What I Covered
- Declaring and assigning variables
- Data types: strings, integers, floats, booleans
- Updating variable values mid-program
- Using variables in print statements
- Converting numbers to strings with `str()`
- Naming conventions (snake_case)

---

## Data Types at a Glance

| Type | Example | Notes |
|---|---|---|
| String | `"Jaded Lax"` | Always in quotation marks |
| Integer | `34` | Whole numbers, no quotes |
| Float | `120.5` | Decimal numbers, no quotes |
| Boolean | `True` / `False` | Capital T or F, no quotes |

---

## Real-World Connection to QA
In test automation, variables store test data — like a patient's name, a drug dosage value, or an expected test result. Understanding variables is the foundation of writing any test script.

---

## Practice Exercise — Patient Profile

```python
# Storing patient information
patient_name = "Jaded Lax"
patient_age = 34
blood_pressure = 120.5
blood_type = "O+"
is_admitted = True
ward = 7

# Printing patient details
print("Patient: " + patient_name)
print("Age: " + str(patient_age))
print("Blood Pressure: " + str(blood_pressure))
print("Blood Type: " + blood_type)
print("Ward: " + str(ward) + " | Admitted: " + str(is_admitted))

# Arithmetic with variables
age_in_days = patient_age * 365
print("Age in days: " + str(age_in_days))

# Updating variables
patient_name = "Mirabel Creed"
ward = 12
print("Updated Patient: " + patient_name + " | New Ward: " + str(ward))
```

---

## Key Takeaways
- Variable names should be descriptive and use `snake_case`
- Python is dynamically typed — you don't declare the type manually
- Variables can be reassigned at any time
- Use `str()` to convert numbers when joining with text in print statements
- Booleans are `True` / `False`. Capital first letter, no quotes

---

## F-Strings Shortcut
Printing becomes much cleaner with F-strings:
```python
# Instead of this:
print("Patient: " + patient_name)

# You can write this:
print(f"Patient: {patient_name}")
```
Both do the same thing. F-strings are the professional preferred method.

---

## Common Mistakes to Avoid
- `character-age` → `character_age` (no hyphens)
- Forgetting `str()` when printing numbers with text
- Putting quotes around a number: `"34"` makes it a string not an integer
- Boolean spelling: `True` not `true` or `TRUE`

---

## Revision Checklist
- Can I create a variable for each data type?
- Can I print a sentence using variables?
- Can I update a variable mid-program?
- Can I convert a number to string for printing?
- Do I understand why order of instructions matters?
```

