---
tags:
- python
- pip
---

# Export Pip Package Lists (Platform independent)

First install `setuptools` using `pip install setuptools`

```python
import pkg_resources

with open('requirements.txt', 'w') as file:
    for package in pkg_resources.working_set:
        file.write(package.project_name + '\\n')
```

Save it with any name and store it in the system environment to easy access
