# Terminut.
<img src="https://img.shields.io/pypi/v/terminut?style=for-the-badge&logo=python">
<img alt="followers" src="https://img.shields.io/github/followers/imvast?color=f429ff&style=for-the-badge&logo=github&label=Follow"/>

```less
            > Custom Console Going To Be Used For My Projects
                And Available To Anyone Else Who Wants To Use <
```

---

### Installation
```yaml
! package NOT FULLY available for non-personal use !
~ use at the knowledge of knowing it may be buggy ~

pip install terminut
```

### Usage
```py
# default shit if u want to only import for ease - auto switches #

from terminut import printf as print, inputf as input, init
init(debug=True)

print("[DEBUG] Should Not Show")
print("[INFO] Should Show")

# --------------------------------------------------------- #

# this is for custom cool stuff as seen here: 
# https://cdn.discordapp.com/attachments/1099515953223569420/1105295220414885998/2023-05-08_20-46-22.mp4

import time
from terminut import BetaConsole
c = BetaConsole(speed=2)
while True:
    try:
        timestamp = c.getTimestamp()
        c.alphaPrint("[INF]", f"[{timestamp}] made by vast :D", increment=False)
        time.sleep(0.001)
    except KeyboardInterrupt: exit(0)
```

---

## * [vast#1337](https://discord.com/users/852976920148967485) | [imvast@github](https://github.com/imvast) | [vast.gay](https://vast.gay) *