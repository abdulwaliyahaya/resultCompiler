# resultCompiler
A python class for compiling end of the term result for primary and secondary schools in Nigeria.
# Motivation
As a corp member serving in a secondary school in Gombe State, the step it takes to generate students results is hectic,
inefficient, error prone and time consuming. This is an attempt to make this step less hectic, efficient, error free and
in the matter of a second. This python class was developed for use in a larger system (a web-based result management
system).
# How to use
the `Compiler class` in the `result.py` accepts scores of students (including attendance record and remark)
as a list of list (or tuple) with the first list (or tuple) consisting of subject list with attendance and remark
appended at the end.
example:
```
raw result = [('Maths','English', 'Drawing', 'Attendance','Remark'),
         ('fas13geo001',43,76,54,123, 'average student... try harder'),
         ('fas13geo002',89,78,67,124, 'an excellent result... keep it up')
         ]
```

