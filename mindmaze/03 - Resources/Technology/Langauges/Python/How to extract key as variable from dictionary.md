---
tags: 
- python
---

# How to Extract Key as Variable from Dictionary?

```python
for key in my_dict:
    locals()[key] = my_dict[key]
```

This way we can extract `key` as variable so that we use it however we want.
