# ExcelToUnity
一个为Unity3D编写的插件，可以快速地将Excel文件转换为JSON、CSV和XML，方便在游戏过程中处理各种Excel文件。本项目参考了[excel2json](https://github.com/neil3d/excel2json)，在此表示感谢。

# 如何使用ExcelToUnity
将本项目中的Source文件夹直接复制到Unity3D项目中即可，Unity3D的菜单栏将会增加一个Plugins的菜单项，通过此菜单项的ExcelTools打开插件窗口。在项目资源中选中Excel文件后，点击插件窗口上的"转换"按钮即可！

# 使用ExcelToUnity的默认约束条件
* Excel数据表默认以第一行作为字段
* Excel工作表默认以第一个工作表为主
* 目前支持utf-8和gb2312两种字符编码类型

# Excel文件转换示例
假设Excel文件定义如下：
Name    Level    Description    Skill    Time
南小媛    12    《虚拟偶像》新兴偶像    跳舞    2019出道
初音未来    20    《日本声优》女主角    唱歌    2007出道
末末酱    18    《MOMO》    唱歌、搞笑    2018出道
一蝉小和尚    24    《一蝉小和尚》配角    搞笑、心灵鸡汤    2019出道

则经过转换后的JSON、CSV和Xml文件具体看项目中的文件。
