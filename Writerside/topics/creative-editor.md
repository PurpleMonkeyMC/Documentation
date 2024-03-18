# 世界编辑工具

您可打开 [创意功能界面](creative.md#functions) 并在 **方块与物品** 中从工具包获得世界编辑工具。

本文档内涉及的基本按键/操作简写

|           简写            | 代表功能 |
|:-----------------------:|:----:|
| <shortcut>S</shortcut>  | 下蹲键  |
| <shortcut>LB</shortcut> | 左键方块 |
| <shortcut>LA</shortcut> | 左键空气 |
| <shortcut>RB</shortcut> | 右键方块 |
| <shortcut>RA</shortcut> | 右键空气 |


## 快速传送

鼠标准星对准方块，<shortcut>LA</shortcut>/<shortcut>RA</shortcut> 即可快速传送到目标位置。

## 撤销

撤回当前使用工具的操作。

> 注意：最多只能撤销10次操作！ {style=warning}

## 远程放置工具

使用<shortcut>LB</shortcut>选取需要用于放置的方块，
远程放置需要离开玩家触碰距离。

> 副手放对应方块可进行双倍放置。{style=note}

[//]: # (<2024.3.17 已知bug 距离过近右键会使工具变成选取方块>)

## 脚下方块生成器

使用 <shortcut>LB</shortcut> 选取方块，
再使用 <shortcut>RA</shortcut> 即可从玩家脚下生成对应方块(即玩家位置的`~, ~-1, ~`)。

## 遮罩工具

在使用工具中使忽略方块，或者说**保护方块**不被替换。

### 启用遮罩

启用之后 在遮罩工具选取对应方块保护其方块不会影响

列子:对角选取区域 遮罩选取钻石块 使用区域填充工具

|:-----------------------:|:----:|
| 未启用|![遮罩](OffEnveloped.png)|
| 启用 |![遮罩2](OnEnveloped.png)|

### 反转遮罩

启用之后,在遮罩工具选取对应方块其**影响方块**

实例：对角选取区域，遮罩选取钻石块，使用区域填充工具。

|:-----------------------:|:----:|
| 未启用|![反转遮罩](offReverseshroud.png)|
| 启用 |![反转遮罩2](OnReverseshroud.png)|

## 区域填充工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
<shortcut>S+RB</shortcut> 选取方块进行区域内填充。

![区域填充](Areafilling.png)

## 区域框架工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
<shortcut>S+RB</shortcut> 选取方块进行区域内**边**填充。

![区域框架](frame.png)

## 区域清理工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
<shortcut>S+RB</shortcut> 进行区域内清除。

![区域清理](Theareaisclear.png)

## 圆工具

<shortcut>LB</shortcut>进行圆心选取，<shortcut>RB</shortcut>进行圆半径选取；
<shortcut>S+LA</shortcut>选取方块，<shortcut>S+RA</shortcut>进行区域填充。

![圆工具](cylinder.png)

## 替换工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
`SL`选取方块`SR`选取方块进行替换

(类似上面区域填充反转遮罩效果)

## 平移工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
`SL`向任意六个方向选取目标方块`SR`向目标目标方块平移

![平移工具](translate.png)

## 镜向工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
`RA`选择水平或者垂直模式`SR`进行镜向

|:-----------------------:|:----:|
| 水平|![镜像水平](mirrorhorizontal.png)|
| 垂直 |![镜像垂直](mirrorperpendicular.png)|

## 复制黏贴工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
在准星对准方块时显示可视化框架,确认目标进行`SR`执行复制

![复制黏贴](copy.png)

## 旋转工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
使用 `S+L`切换角度
`S+R`执行旋转

![旋转](revolve.png)

## 画笔工具

笔刷默认空气,请自行选取方块

### 球形笔刷

选择半径(1-5) `R` 进行放置球形

![球形](spherical.png)

### 方形笔刷

选择半径(1-5) `R` 进行放置正方形

![方形](square.png)

### 圆柱笔刷

旋转半径(1-5) 旋转高度(1-5) `R` 进行放置圆柱

![圆柱](Oncylinder.png)

### 平滑笔刷

选择半径(1-5) `R` 进行对地形平滑

|:-----------------------:|:----:|
|预定地形|![不平滑地形](Offsmooth.png)|
|使用笔刷|![平滑工具](Onsmooth_1.png)|