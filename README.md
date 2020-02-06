# json-dict-comparator
Provides tools for comparing python dictionaries obtained from json objects.
Inspired by https://stackoverflow.com/questions/25851183/how-to-compare-two-json-objects-with-the-same-elements-in-a-different-order-equa

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
