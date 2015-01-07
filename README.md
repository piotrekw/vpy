# v.py
Get version of a package/module with one function call.

Example:

```python
>>> import django, tornado, flask
>>> from v import v
>>> v(django)
((1, 3, 1, 'final', 0), 'VERSION')
>>> v(tornado)
('4.0.2', 'version')
>>> v(flask)
('0.9', '__version__')
```
