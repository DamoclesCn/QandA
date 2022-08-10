## SourceTree 无效的源路径
> 场景：电脑是64位，安装sourcetree前没有下载git，安装时下载了内置git(32位)，随后clone时不管输入啥url都显示：`仓库类型：无效的源路径`。

## 解决方法
1. 下载64位Git
2. 打开sourcetree -> 工具 -> 选项 -> Git -> Git版本 -> 点击System(下方文字 `内嵌Git版本***` 变成了 `系统Git版本***` )
3. 可以clone了