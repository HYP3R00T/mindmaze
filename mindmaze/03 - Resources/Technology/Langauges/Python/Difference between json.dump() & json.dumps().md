---
tags:
- python
- json
---

# Difference between json.dump() & json.dumps()

https://stackoverflow.com/a/32911421/16038271

Note that [`dump`](https://docs.python.org/library/json.html#json.dump) and `load` convert between files and objects, while `dumps` and [`loads`](https://docs.python.org/library/json.html#json.loads) convert between _strings_ and objects. You can think of the `s`-less functions as wrappers around the `s` functions:

```python
def dump(obj, fh):
    fh.write(dumps(obj))

def load(fh):
    return loads(fh.read())
```
