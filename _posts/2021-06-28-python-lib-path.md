# python 3rd party library path

주로 윈도우에서 사용하다 보니 library path를    
  1. Windows : Lib\site-packages   
만 알고 있었는데 mac에서의 경로가 궁금해서 방법을 찾아보니   
   
```python
import sys
sys.path
```
을 사용하면 확인이 가능하다   
   
   
추가로 mac에서 숨김 폴더를 보느 방법은    
  shift + command + G   
를 하며 찾아가기가 나오고 그곳에 필요하 경로를 타이핑해주며 된다.    
항상 그렇지만 검색하며 다나오는....
