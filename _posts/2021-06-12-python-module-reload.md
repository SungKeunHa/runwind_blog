# python module reload

ipython 혹은 python console에서도 module reload가 필요하 때가      
있다. 그럴 때 사용하느 방법      
개인적으로는 주로 해당 모듈을 수정해가면서 사용할 때 요긴해왔다. 

```python
import imp
imp.reload(module)
```
