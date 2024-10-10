## 파이썬 실수 비교

```
import math, sys
x = 0.1 + 0.2
math.fabs(x - 0.3) <= sys.float_info.epsilon
```

```
import math
math.isclose(0.1 + 0.2, 0.3)
```

```
from decimal import Decimal
Decimal('0.1') + Decimal('0.2')
```

```
from fractions import Fracion
Fraction('10/3')
```