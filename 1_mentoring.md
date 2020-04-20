**Jupyter Notebookの実行画面**

[![Image from Gyazo](https://t.gyazo.com/teams/diveintocode/e9e3c6e91b7d4abd99001aa0848e4059.png)](https://diveintocode.gyazo.com/e9e3c6e91b7d4abd99001aa0848e4059)

**実行したコード**

```py
import numpy as np

a = np.array([[-1,2,3]])
b = np.array([[0,2,1]])
np.dot(a,b)
```

**Error分析**
1. `numpy.dot(a, b, out=None)`は「2つのアレイのドット積」を返すメソッドです。
2. aとbの両方が2次元配列の場合、それは行列の乗算を返します。
3. 行列の乗算の前提として、aの列の数とbの行の数が一致することが必要です。
[![Image from Gyazo](https://i.gyazo.com/4317591a041fe1bd7c6c8c05066c448a.png)](https://gyazo.com/4317591a041fe1bd7c6c8c05066c448a)
