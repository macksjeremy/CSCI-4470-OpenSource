This is a doctest based regression suite for unnecessary_math.py
Each '>>' line is run as if in a python shell, and counts as a test.
The next line, if not '>>' is the expected output of the previous line.
If anything doesn't match exactly (including trailing spaces), the test fails.
 
>>> from unnecessary_math import multiply
>>> multiply(3, 5)
15
>>> multiply('b', 4)
'bbbb'
