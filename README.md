# json-dict-comparator
Provides tools for comparing python dictionaries obtained from json objects.

# Installing
```
pip install json_dict_comparator
```

# Example
```
from json_dict_comparator import json_dict_any_order_equal

d1 = {a: 1}
d2 = {a: 1}

json_dict_any_order_equal(d1, d2)
```
