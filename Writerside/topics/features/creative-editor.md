# 世界编辑工具

<show-structure for="chapter,procedure" depth="2"/>

您可打开 [创意功能界面](creative.md#functions) 并在 **方块与物品** 中从工具包获得世界编辑工具。

![creative-editor-tools.png](creative-editor-tools.png)

本文档内涉及的基本按键/操作简写如下

{id=keymap type=narrow}
<shortcut>S</shortcut>
: 下蹲键

<shortcut>LA</shortcut>
: 左键空气

<shortcut>LB</shortcut>
: 左键方块

<shortcut>RA</shortcut>
: 右键空气

<shortcut>RB</shortcut>
: 右键方块

## 快速传送

鼠标准星对准方块，<shortcut>LA</shortcut>/<shortcut>RA</shortcut> 即可快速传送到目标位置。

## 撤销操作

每<shortcut>RA</shortcut>一次，就撤回一次最后的世界编辑操作。

> 注意：最多只能撤销10次操作！ {style=warning}

## 远程放置工具

使用<shortcut>LB</shortcut>选取需要用于放置的方块，
远程放置需要离开玩家触碰距离。

> 副手放对应方块可进行双倍放置。{style=note}

[//]: # (<2024.3.17 已知bug 距离过近右键会使工具变成选取方块>)

## 脚下方块生成器

使用 <shortcut>LB</shortcut> 选取方块，
再使用 <shortcut>RA</shortcut> 即可从玩家脚下生成对应方块 *(即当前位置的`~, ~-1, ~`)* 。

## 遮罩工具

在使用工具中使忽略方块，或者说**保护方块**不被替换。

### 启用遮罩

在遮罩工具选取对应方块将保护其方块不会影响。

列子: 对角选取区域，遮罩选取钻石块，使用区域填充工具。

|                   未启用时执行效果                   |                   启用时执行效果                    |
|:--------------------------------------------:|:--------------------------------------------:|
| ![遮罩](worldeditor-mask-off.png){width="300"} | ![遮罩2](worldeditor-mask-on.png){width="300"} |

### 反转遮罩

启用之后,在遮罩工具内选取想要**被影响的方块**类型。

实例：对角选取区域，遮罩选取钻石块，使用区域填充工具。

|                        未启用时执行效果                        |                        启用时执行效果                         |
|:------------------------------------------------------:|:------------------------------------------------------:|
| ![反转遮罩](worldeditor-reversedmask-off.png){width="300"} | ![反转遮罩2](worldeditor-reversedmask-on.png){width="300"} |

## 区域填充工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
<shortcut>S+RB</shortcut> 选取方块进行区域内填充。

![区域填充](worldeditor-fill.png){width="300"}

## 区域框架工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
<shortcut>S+RB</shortcut> 选取方块进行区域内**边**填充。

![区域框架](worldeditor-frame.png){width="300"}

## 区域清理工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
<shortcut>S+RB</shortcut> 进行区域内清除。

![区域清理](worldeditor-clear.png){width="300"}

## 圆形工具

<shortcut>LB</shortcut>进行圆心选取，<shortcut>RB</shortcut>进行圆半径选取；
<shortcut>S+LA</shortcut>选取方块，<shortcut>S+RA</shortcut>进行区域填充。

![圆工具](worldeditor-brush-circle.png){width="300"}

## 替换工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
使用<shortcut>S+LA</shortcut>选取方块，<shortcut>S+RA</shortcut>选取方块进行替换。

> 该效果类似于 区域填充+反转遮罩 。

## 平移工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
使用<shortcut>S+LA</shortcut>向任意六个方向选取目标方块，
使用<shortcut>S+RA</shortcut>向目标目标方块平移。

![平移工具](translate.png){width="300"}

## 镜向工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
使用<shortcut>RA</shortcut> 切换水平模式或者垂直模式，
使用<shortcut>S+RA</shortcut>进行镜向操作。

|:-----------------------:|:----:|
| 水平镜像效果 |![水平镜像](worldeditor-mirror-horizontal.png){width="300"} |
| 垂直镜像效果 |![垂直镜像](worldeditor-mirror-perpendicular.png){width="300"} |

## 复制黏贴工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
在准星对准方块时将显示可视化框架；确认目标后，进行<shortcut>S+RA</shortcut>执行复制操作。

![复制黏贴](worldeditor-copy.png)

## 旋转工具

<shortcut>LB</shortcut>/<shortcut>RB</shortcut> 分别选取对角方块后，
使用<shortcut>S+LA</shortcut>切换旋转角度，
使用<shortcut>S+RA</shortcut>执行旋转操作。

![旋转](worldeditor-rotate.png){width="300"}

## 画笔工具

默认情况下，画笔操作的方块类型为“空气”。如有需要，请自行切换为其他方块类型。

### 球形笔刷

在选择 **半径**(1-5) 后，使用 <shortcut>RA</shortcut> 放置球形。

![球形](worldeditor-brush-sphere.png){width="300"}

### 方形笔刷

在选择 **边长**(1-5) 后，使用 <shortcut>RA</shortcut> 进行放置正方形。

![方形](worldeditor-brush-square.png){width="300"}

### 圆柱笔刷

在 **旋转半径**(1-5) 与 **旋转高度**(1-5) 后，
使用 <shortcut>RA</shortcut>进行放置圆柱。

![圆柱](worldeditor-cylinder.png){width="300"}

### 平滑笔刷

在选择 **半径**(1-5) 后， 使用 <shortcut>RA</shortcut> 进行地形平滑操作。

|:-----------------------:|:----:|
|平滑操作前|![不平滑地形](worldeditor-brush-smooth-before.png){width="300"} |
|平滑操作后|![平滑工具](worldeditor-brush-smooth.png){width="300"} |