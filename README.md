```python
import os
import platform

with open('system_info.txt', 'w', encoding ='utf-8') as file:
  file.writes(
      f"Sys version {sys.version}"
      )
```
