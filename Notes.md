```bash
man qlmanage
echo $@
vim /Users/superuser/bins
---
#!/bin/bash
qlmanage -p "$@" >& /dev/null &
---
ln -s /Users/superuser/bins/ql /usr/local/bin/
which ql
```
