# 爱家智码 - iHomeCoder

iHomeCoder is an intelligent development assistant plugin developed based on large models, supporting Visual Studio Code and JetBrains IDEs. It accommodates a variety of programming languages including Python, Java, C++/C, JavaScript, and Go. The plugin offers developers functionalities such as code completion, code explanation, code optimization, comment generation, free-form R&D Q&A, code knowledge-assisted Q&A, and capability recommendations. Its goal is to enhance programming efficiency through intelligent means.
爱家智码（iHomeCoder）是基于代码大模型开发的支持Visual Studio Code/ JetBrins IDEs的智能研发助手插件，支持Python、Java、C++/C、Javascript、Go等多种编程语言，为开发者提供代码补全、代码解释、代码优化、注释生成、研发自由问答、代码知识辅助问答、能力推荐等功能，旨在通过智能化的方式帮助开发者提高编程效率。

环境要求Environmental Requirements
The IDEA version must be between 2022.2 and 2024.2.
The Visual Studio Code version must be 1.83.1 or higher.

IDEA 版本要求 2022.2至2024.2之间。
Visual Studio Code版本要求 1.83.1 及以上。

插件配置Plugin Configuration
Directly open the extension marketplace to search and install, or download the installation package from the EP platform plugin download page.
On the login page, enter the Access Key for identity authentication (please apply for the Access Key on the EP platform first).

直接打开扩展应用市场搜索安装，或从EP平台插件下载页面下载安装包。
在登录页输入授权码Access Key进行身份认证（请先前往EP平台申请授权码）。

功能使用 Feature Utilization
1. 代码补全 Code Completion
自动触发代码建议
热键触发代码建议
During the coding process, code completion suggestions can be automatically triggered when you cease typing, or you may proactively invoke code completion suggestions by using the shortcut Alt+\ (for Windows computers) or Option+\ (for Mac computers).
When the plugin offers code suggestions, the proposed content is displayed in gray at the cursor position within the editor. You may press the Tab key to accept the suggestion, or continue typing to disregard it.
在编码过程中，当停止输入时，代码补全建议可自动触发（在配置选项Auto Completion Delay中可设置为1~3秒），或者您也可以主动触发代码补全建议，使用快捷键Alt+\（对于Windows电脑）或option+\（对于Mac电脑）。
当插件提供代码建议时，建议内容以灰色显示在编辑器光标位置，您可以按下Tab键来接受该建议，或者继续输入以忽略该建议。

2. 代码辅助 Code Assistance
对一段代码进行解释/优化/清理
为一段代码生成注释/单元测试
检查一段代码是否存在性能/安全性问题
Open the plugin interface in the sidebar, select a segment of code within the editor, and choose the corresponding function item from the iHomeCoder context menu by right-clicking. The plugin will then provide an appropriate response in the Q&A interface.
在侧边栏中打开插件问答界面，在编辑器中选中一段代码，在鼠标右键iHomeCoder菜单中选择对应的功能项，插件将在问答界面中给出相应的答复。

3. 研发问答 Code Q&A
支持多轮对话
支持会话历史
基于历史会话（做为上文）进行多轮对话
对任一问题，可重新获取回答
在回答过程中，可以打断
On the Q&A page, you can engage in dialogue and click the copy button to duplicate the code blocks provided by the development assistant.
在问答页面进行对话，可以点击复制按钮复制研发助手提供的代码块。

4. 能力推荐 Code Recommendation
支持原子能力列表查询
支持原子能力详情查询
可编辑问题，重新提问
对任一问题，可重新获取回答
During a conversation on the code recommendation page, the assistant is capable of suggesting existing code blocks from the asset library that can be directly reused.
在能力推荐页面进行对话，研发助手能够推荐资产库中可直接复用的已有代码块。

5. 知识辅助问答 Knowledge-Assisted Q&A
已基于优质代码资产构建向量化库
支持代码知识辅助问答
显示知识文件来源
Supports code knowledge-assisted Q&A（RAG）.

6.多模型调度 Multi-Model Scheduling
The assistant supports users in selecting and switching between different large models for Q&A, including the DeepSeek-R1-671B, DeepSeek-V3, the JiuTian large model, the DeepSeek distilled version, and the Qwen2.5-Coder, among other large models.
支持用户选择、切换不同版本、不同规模的大模型进行问答，包括DeepSeek-R1满血版、DeepSeek-V3满血版、JiuTian大模型、DeepSeek蒸馏版、Qwen2.5-Coder等大模型。

