# 语法

## 命令行语法

如何安装软件：`sudo apt install xxx` 进行安装 

## code编程相关

### c语言：
``` c
void main()
{
    return 0;
}
```

### python示例1：

``` py
import tk
import time

def myCalc():
    # 一些注释

```

### python示例2：
``` py title="demo_oled.py"
import sys

def init():
    # do something

```

### python示例3：
``` py title="demo_apple.py" linenums="1"
import sys

def init():
    # do something

```

### 高亮一些行数：
``` py title="main.py" linenums="1" hl_lines="3 4"
import sys

def init():
    # do something
    make_job()


```

## 表情包
:smile: 

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }

## 编写文档用到的命令

和mkdocs相关：

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.

和github提交相关：

``` bash
git add .  # git reset . 表示反操作
git comment -m "xxx"
git push origin main

# 然后在action中对分支进行ci部署
```