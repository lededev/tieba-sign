## 百度贴吧自动签到

### 安装
```
pip install --user tieba-sign
```

### 使用
```
C:\Users\>tieba-sign -h
usage: tieba-sign [-h] [-c COOKIE] [-f FILE] [-t TIME] [-d] [-v]

optional arguments:
  -h, --help            show this help message and exit
  -c COOKIE, --cookie COOKIE
                        Cookies
  -f FILE, --file FILE  cookies file
  -t TIME, --time TIME  sleep time
  -d, --dump            dump list to file
  -v                    verbose mode


C:\Users\>tieba-sign -c "Cookie:hUb3NkcVBMfk1NV1Y3bGtjdHBnNzVFYktRbjBCVmVvWS03YzZ"

```

###  
```
from tieba import Tieba

tieba=Tieba("Your Cookie")
tieba.get_bars()
tieba.batch_sign(1)
```