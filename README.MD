# WowsQuery 帮助文档

---

### 服务器列表
|代号|说明|代号|说明|
|---|---|---|---|
|asia|亚服|ru|俄服|
|eu|欧服|na|美服|

### 绑定账号
绑定账号可以在各个命令中使用 <kbd style="color: orange">me</kbd> 关键字表示绑定的账号。

<kbd>wws server nick set</kbd>

### 随机战数据查询
> 忽略 <kbd>server</kbd> 属性时，默认查询亚服（asia）
>
> 忽略 <kbd>day</kbd> 属性时，默认查询当天

总体数据查询：<kbd>wws server nick</kbd> 或 <kbd style="color: orange">wws me</kbd>

近期数据查询：<kbd>wws server nick recent day</kbd> 或 <kbd style="color: orange">wws me recent day</kbd>

单舰数据查询：<kbd>wws server nick ship shipName</kbd> 或 <kbd style="color: orange">wws me ship shipName</kbd>
