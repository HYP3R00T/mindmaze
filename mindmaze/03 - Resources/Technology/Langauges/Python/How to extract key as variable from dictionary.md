---
tags: 
- python
---

# How to extract key as variable from dictionary?
```python
for key in my_dict:
    locals()[key] = my_dict[key]
```
This way we can extract `key` as variable so that we use it however we want.