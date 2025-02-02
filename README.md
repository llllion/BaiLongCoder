# BaiLongCoder
Your AI Coding Assistant. Make Coding Easier, Faster, Better.

## 白龙码 - BaiLong Coder
白龙码（BaiLong Coder）是基于代码大模型开发的支持Visual Studio Code的智能研发助手插件，支持Python、Java、C++/C、Javascript、Go等多种编程语言，为开发者提供代码补全、代码解释、代码优化、注释生成、研发自由问答、代码知识辅助问答、能力推荐等功能，旨在通过智能化的方式帮助开发者提高编程效率。

### 环境要求
node版本v18及以上

Visual Studio Code版本要求 1.83.1 及以上

IDEA 版本要求 2022.2至2024.2之间

### 配置插件
直接打开扩展应用市场搜索安装，或从EP平台插件下载页面下载安装包。

在登录页输入授权码Access Key进行身份认证（请先前往EP平台申请授权码）。

### 功能特性
1. 代码补全

自动触发代码建议

热键触发代码建议

在编码过程中，当停止输入时，代码补全建议可自动触发（在配置选项Auto Completion Delay中可设置为1~3秒），或者您也可以主动触发代码补全建议，使用快捷键Alt+\（对于Windows电脑）或option+\（对于Mac电脑）。

当插件提供代码建议时，建议内容以灰色显示在编辑器光标位置，您可以按下Tab键来接受该建议，或者继续输入以忽略该建议。

2. 代码辅助

  对一段代码进行解释/优化/清理

  为一段代码生成注释/单元测试

  检查一段代码是否存在性能/安全性问题

  在vscode侧边栏中打开插件问答界面，在编辑器中选中一段代码，在鼠标右键BaiLong菜单中选择对应的功能项，插件将在问答界面中给出相应的答复。

3. 研发问答

支持多轮对话

支持会话历史

基于历史会话（做为上文）进行多轮对话

对任一问题，可重新获取回答

在回答过程中，可以打断

在问答界面的代码块中，可以点击复制按钮复制该代码块。

4. 能力推荐

支持原子能力列表查询

支持原子能力详情查询

可编辑问题，重新提问

对任一问题，可重新获取回答

在问答界面的能力块中，可以点击复制按钮复制该能力块。

5. 知识辅助问答

已基于优质代码资产构建向量化库

支持代码知识辅助问答

显示知识文件来源
