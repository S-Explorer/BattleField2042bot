**适用于hoshino的战地风云2042战绩查询（图片）**
<br><br>
**战地风云2042**
<br>
<br>****战绩查询****<br>
PC：<br>
[`.盒`+`ID`]  PC战绩查询<br><br>
[`.数据`+`ID`]  PC战绩查询（文字图片版本）（为了Linux平台）<br><br>
[`.2042战绩`+`ID`]  PC战绩查询<br><br>
[`.武器`+`ID`]  武器数据查询<br><br>
[`.枪械`+`ID`] 另一种查询武器数据的方法<br><br>
[`.载具`+`ID`] 查询载具数据<br><br>
[`.专家`+`ID`] 查询专家数据<br><br>
[`.模式`+`ID`] 查询游戏模式数据<br><br>
[`.地图`+`ID`] 查询地图游玩情况<br><br>
[`.装置`+`ID`] 查询配备数据<br><br>
[`.绑定+ID`]  绑定游戏id到QQ<br><br>
[`.修改绑定+ID`]  修改绑定的游戏id<br><br>
主机：<br>
[`.2042xbox端战绩`+`ID`] xbox战绩查询（仅支持XBOX）<br><br>
[`.2042ps端战绩`+`ID`] ps战绩查询（仅支持PS）<br><br>
[`.PS绑定`+`ID`] 绑定游戏ID到QQ（仅支持PS）
[`.XBOX绑定`+`ID`] 绑定游戏ID到QQ（仅支持XBOX）

<br>****特权****<br>
~~[`.添加用户表`]  添加玩家绑定用的表结构<br><br>~~ 已经改用云端数据库不需要该方法了
[`.添加名单 + @用户`]  添加玩家自定义背景权限<br><br>
[`.上传图片 `]  上传玩家自定义的背景图片<br><br>
~~[`.查询名单 + 数字（页码）`]  查询绑定的用户（很长建议别用，等我优化或者你自己优化bushi）~~该方法已经废弃

<br>****小功能****<br>
检测到新的入群申请，检测回答中的EA ID，然后查询数据发送图片到群消息<br>
推荐设置申请群问题为：`EA/橘子ID是什么？`

<br>****门户****<br>
~~[`.2042门户 + 门户关键字 `] 查询关键字在线人数最多的服务器~~ 暂时出了点问题，查不到服务器或者直接报错，等修复

**需要安装依赖**

```bash
pip install -r requirements.txt
```

**在`hoshino`的`config`文件夹中`__bot__.py`中的`MODULES_ON`部分添加`bf2042`即可**
<br><br>
1.代码写的很烂，轻喷，主业是Java，Python是我东拼西凑整了一点出来用的，毫无编码规范（屎山警告）
<br>2.自己随便整了一个外挂的检测方法，可以简单的判断该玩家是否为暴力外挂<br>
<br>
`bg`文件夹中存放的是背景<br>
`common`是普通背景<br>有什么好看的就往里面塞吧<br>
`user`是用户的背景存放位置，根据qq号会创建对应的文件夹，可以放入多张图片，随机选取其中一张作为背景
<br>
<br>**PS**：分辨率最好是是16:9的，不然系统裁剪后会有黑边，虽然不影响，但是你不想看你好看的色图做你的背景吗？<br>
<br>第一次运行如果没有对应的图片会自己下载，有些东西名字太长可能会遮挡到别的内容，我也没时间详细弄了，打工人何必为难打工人呢<br>
<br>
<br><br>
![个人数据示例图](https://sansenhoshi.site/upload/67FE863E3934CCB998F735DF1966FAD6.jpg)
![武器数据示例图](https://sansenhoshi.site/upload/weapon-info.png)
