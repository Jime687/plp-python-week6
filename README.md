## Password and Error Handling Week 6

`safe_tools.py` contains functions that safely handle division, number conversion, and missing dictionary fields.

`unbreakable.py` demonstrates how to use error handling to keep a program running when errors occur.

The `if` check cannot catch `abc` on its own because converting `"abc"` to an integer causes a `ValueError` before the program can continue with the check. Using `try` and `except` allows the program to catch that error safely.
 plp-python-week6