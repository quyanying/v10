# 分区编辑器
## 概 述
根据用户使用习惯，增加了用户分区的创建和使用支持，在系统安装时用户可以选择创建数据分区，系统文件管理器将会以数据盘的形式展现，相当于Windows系统的C/D/E盘，可以更好的适应用户使用习惯的切换。

分区编辑器是一款系统应用软件，用户可以对本机所有存储设备(比如本地硬盘、移动硬盘、U 盘等)进行查看和编辑(新建分区、删除分区、格式化等相关磁盘操作)。主界面由标题栏（最小化、最大化、关闭）、菜单、分区功能控制区以及磁盘信息区构成，如图1所示。

![图 1 分区编辑器主界面-big](image/1.png)
<br>

## 基本功能
磁盘分区中的彩色条显示各个分区大小，对应下面列表中的分区名称；列表区展示了各个分区的详细信息，比如分区名称、挂载点等，如图2所示。

主界面介绍：

![图 2 分区编辑器基本功能区介绍](image/2.png)

图标及其功能介绍：

|图标|	图标功能说明|	图标|	图标功能说明
| :------------ | :------------ | :------------ | :------------ |
|![](image/icon1.png)|在选定的未分配空间内建立一个新的分区|	![](image/icon5.png)|	删除选定分区
|![](image/icon2.png)|调整大小/移动选定分区|![](image/icon6.png)|将选定分区复制到剪切板
|![](image/icon3.png)|从剪切板粘贴分区|![](image/icon7.png)|撤销上次操作
|![](image/icon4.png)|应用全部操作	|![](image/icon8.png)|	当前设备信息

<br>

## 高级功能
用户可以通过菜单的分区编辑器、编辑、查看、设备、分区、帮助选项，对分区编辑器进行相关操作，如图3所示。

![图 3 分区编辑器高级功能区介绍](image/3.png)
 
图标及其功能介绍：

|图标	|图标功能说明	|图标	|图标功能说明
| :------------ | :------------ | :------------ | :------------ |
|![](image/icon9.png)|	刷新设备|![](image/icon17.png)|		当前设备信息
|![](image/icon10.png)|	退出	|![](image/icon18.png)|	撤销上次操作
|![](image/icon11.png)|	清除全部操作	|![](image/icon19.png)|	应用全部操作
|![](image/icon12.png)|	新建分区	|![](image/icon20.png)|	删除分区
|![](image/icon13.png)|	更改大小/移动	|![](image/icon21.png)|	复制
|![](image/icon14.png)|	粘贴	|![](image/icon22.png)|	格式化为（ntfs、linux-swap等）
|![](image/icon15.png)|	信息	|![](image/icon23.png)|	进入用户手册
|![](image/icon16.png)|	关于分区编辑器	||	||

<br>

### 分区编辑器
用户可以通过点击：菜单 > 分区编辑器，如图4所示。

![图 4 分区编辑器-big](image/4.png)

#### 刷新设备
用户可以通过点击：菜单 > 分区编辑器 > 刷新设备，对当前磁盘信息刷新，如图5所示。

![图 5 刷新设备-big](image/5.png)

#### 查看设备
用户可以通过点击：菜单 > 分区编辑器 > 设备，查看当前设备信息，如图6所示。

![图 6 查看设备信息](image/6.png)

### 编 辑
用户可以通过点击：菜单 > 编辑，如图7所示。

![图 7 编辑-big](image/7.png)

### 查 看
用户可以通过点击：菜单 > 查看，可以查看设备信息、待执行操作以及文件系统支持信息表，如图8所示。

![图 8 查看-big](image/8.png)

#### 设备信息&待执行操作
用户可以通过点击：菜单 > 查看 > 设备信息&待执行操作，可以查看设备信息、待执行操作，如图9所示。

![图 9 查看设备信息&待执行操作](image/9.png)

#### 文件系统支持
用户可以通过点击：菜单 > 查看 > 文件系统支持，可以文件系统支持信息表，此操作需作为超级用户，如图10所示。

![图 10 查看文件系统支持信息表-big](image/10.png)

### 设 备
用户可以通过点击：菜单 > 设备，创建分区表，如图11所示。

![图 11 设备-big](image/11.png)

![图 12 提示创建分区表](image/12.png)

### 分 区
用户可以通过点击：菜单 > 分区，对磁盘进行删除、更改大小/移动、渎职、格式化等操作，如图13所示。

![图 13 分区-big](image/13.png)

#### 更改大小&移动
用户可以通过点击：菜单 > 分区 > 更改大小&移动，如图14所示。

![图 14 更改大小&移动](image/14.png)

#### 格式化
用户可以通过点击：菜单 > 分区 > 格式化，如图15所示。

![图 15 格式化](image/15.png)

#### 分区名称
用户可以通过点击：菜单 > 分区 > 分区名称，如修改“/dev/sda5”分区的名称，如图16所示。

![图 16 分区名称](image/16.png)

#### 管理标志
用户可以通过点击：菜单 > 分区 > 管理标志，如管理“/dev/sda5”的标志，如图17所示。

![图 17 管理标志](image/17.png)

#### 检查分区
用户可以通过点击：菜单 > 分区 > 检查，如检查“/dev/sda5”分区，如图18所示。

![图 18 检查分区](image/18.png)

#### 文件系统卷标
用户可以通过点击：菜单 > 分区 > 文件系统卷标，可以修改文件系统卷标，如图19所示为“/dev/sda5”分区卷标信息。

![图 19 文件系统卷标](image/19.png)

#### 新UUID
用户可以通过点击：菜单 > 分区 > 新UUID，需要注意的是更改UUID可能会验证windows产品激活密，如图20所示。

![图 20 新UUID](image/20.png)

提示信息：

在FAT和NTFS文件系统上，卷序列号用作UUID。 更改Windows系统分区（通常为C :）上的卷序列号可能会使WPA密钥无效。无效的WPA密钥将阻止登录，直到您重新激活Windows。
为了避免使WPA密钥无效，在NTFS文件系统上，只有一半的UUID设置为新的随机值。

通常，更改外部存储介质和非系统分区上的UUID是安全的，但不能保证。

#### 信 息
用户可以通过点击：菜单 > 分区 > 信息，显示当前分区信息，如图21所示为显示的未分配分区的信息。

![图 21 当前分区信息](image/21.png)

### 帮 助
用户可以通过点击：菜单 > 帮助，如图22所示。

![图 22 帮 助-big](image/22.png)

#### 内 容
用户可以通过点击：菜单 > 帮助 > 内容，跳转到用户手册。

#### 关 于
用户可以通过点击：菜单 > 帮助 > 关于，查看分区编辑器的信息，如图23所示。

![图 23 关于分区编辑器](image/23.png)
<br>

## 常见问题
### 使用分区编辑器的注意事项
用户在打开分区编辑器前，需要先进行授权进入，授权密码为登录系统时的用户密码，授权后等待加载进入主界面，如图所示。

![图 24 问题一](image/24.png)
<br>

## 附 录
### 快捷键

|选项	|快捷键
| :------------ | :------------ |
|刷新设备（R）..|.	Ctrl+R
|退出（Q）|	Ctrl+Q
|撤销上次操作（U）|	Ctrl+Z
|应用全部操作（A）|	Ctrl+回车
|删除（D）|	Delete
|复制（C）|	Ctrl+C
|粘贴（P）|	Ctrl+V
|内容（C）|	F1

