**适用于hoshino的战地风云2042战绩查询（图片版本）**
<br><br>
****战地风云2042****
`战绩查询`<br><br>
[`.盒`+`ID`] PC战绩查询<br><br>
[`.2042战绩`+`ID`] PC战绩查询<br><br>
[`.2042xbox端战绩`+`ID`] xbox战绩查询<br><br>
[`.2042ps端战绩`+`ID`] ps战绩查询<br><br>
[`.绑定+ID`] 绑定游戏id到QQ<br><br>
[`.修改绑定+ID`] 修改绑定的游戏id

特权<br><br>
[`.添加用户表`] 添加玩家绑定用的表结构<br><br>
[`.添加名单 + @用户`] 添加玩家自定义背景权限<br><br>
[`.上传图片 `] 上传玩家自定义的背景图片<br><br>
[`.查询名单 `] 查询所有的绑定用户（很长建议别用，等我优化或者你自己优化bushi）

**需要安装pillow**

    pip install pillow

**在`hoshino`的`config`文件夹中`__bot__.py`中的`MODULES_ON`部分添加`bf2042`即可**
<br><br>
代码写的很烂，轻喷，主业是Java，Python是我东拼西凑整了一点出来用的，毫无编码规范（屎山警告）
<br>自己随便整了一个外挂的检测方法，可以简单的判断该玩家是否为外挂<br>
`bg`文件夹中存放的是背景<br>
~~`admin`是bot管理员用的背景（主要是我想看涩涩）（已废除）~~<br>
`common`是普通背景<br>有什么好看的就往里面塞吧<br>
`user`是用户的背景存放位置，根据qq号会创建对应的文件夹，可以放入多张图片，随机选取其中一张作为背景
<br>**PS**：分辨率最好是是16:9的，不然系统裁剪后会有黑边，虽然不影响，但是你不想看你好看的色图做你的背景吗？<br>
<br>第一次运行如果没有对应的图片会自己下载，有些东西名字太长可能会遮挡到别的内容，我也没时间详细弄了，要上班的
<br><br>
![示例图](https://sansenhoshi.site/upload/battleinfo.png)
