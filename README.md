# Adding package to your project

```
import sys
PACKAGE_PATH = 'path/to/package'
sys.path.insert(0, PACKAGE_PATH)
from math_package import simple_math
```

# Test function
```
x = 4
y = 3
print(simple_math.add(x, y))
print(simple_math.subtract(x, y))
print(simple_math.multiply(x, y))
print(simple_math.divide(x, y))
```
