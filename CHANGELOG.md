# 更新日志
> 有空会补补BUG、添添新功能。    
> 同时也欢迎大家的参与！感谢各位朋友的支持！ .TAT.

## 2016/03

### /30
  1. 修正更新菜单栏判断条件（win禁止按钮

### /29
  1. 完成在线更新功能（目前不支持windows以及开发版本

### /26
  1. 文件管理双击：size < 100kb ? 编辑 : 下载
  2. 调整 Custom 方式数据库部分代码 // 2-4:感谢[@Medicean](https://github.com/Medicean)
  3. 添加 Shells 目录, 用于存放 shell 样本代码
  4. 添加 `custom.jsp` 服务端样本代码

### /24
  1. 文件管理双击文件进行编辑 //size < 100kb

### /23 (v1.1.0)
  1. 优化数据处理截断算法

### /22
  1. 数据分类重命名
  2. 新增代理连接配置 // 感谢[@Medicean](https://github.com/Medicean)

### /21
  1. 优化UI组建自适应，在调整窗口大小的时候不刷新就能调整UI尺寸

### /18
  1. 修复数据库XSS安全隐患以及特殊符号处理 // 感谢[@peablog](https://github.com/peablog)

### /15
  1. 修复了部分XSS遗留问题（主要在语言模板以及文件管理上还有虚拟终端等，其他地方可能还存在 // 感谢[@loveshell](https://github.com/loveshell)

### /14
  1. 修复文件管理中过滤不当引发的xss安全问题
  2. 增加窗口调整大小刷新UI之前弹框提醒用户选择是否刷新
  3. 删除无用语言包（jp）
  4. 更新支持PHP7 // 感谢[@Lupino](https://github.com/Lupino)
    1. 删除`core/php/index.jsx`中的`@set_magic_quotes_runtime(0);`
    2. 升级`core/php/template/database/mysql.jsx`中的`mysql`为`mysqli`

### /13
  1. 修复源码中`jquery`库缺失问题

# 待做事项
  * 数据高级搜索功能
  * 数据库配置编辑功能
  * 在线检测/下载/安装更新
  * 虚拟终端复制粘贴tab补全
  * 插件模块 //实时编写插件执行、UI以及各种操作API设计
  * 扩展模块 //用于扩展一些高级的功能，懒人必备
  * 代码重构
  * 中文开发文档
  * 英文说明+开发文档
  * nodejs服务端脚本支持
  * python服务端脚本支持
