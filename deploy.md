# 配置

```js
基本
"contrastActiveBorder"/在活动元素周围额外的一层边框，用来提高对比度从而区别其他元素
"contrastBorder"在元素周围额外的一层边框，用来提高对比度从而区别其他元素
"widget.shadow"编辑器内小组件(如查找/替换)的阴影颜色
"progressBar.background"表示长时间操作的进度条的背景色，是一个向右滑动同时伸缩的窄条
"foreground"整体前景色
"icon.foreground"工作台中图标的默认颜色
"imagePreview.border"图片边框颜色
"errorForeground"错误信息的整体前景色，颜色仅在不被组件覆盖时适用

活动栏
"activityBar.activeBackground"活动栏当前选中项的背景色
"activityBar.activeBorder"活动栏当前选中项靠近窗口边缘处有竖条，竖条颜色
"activityBar.activeFocusBorder"按下活动栏的选中项，边框呈现此颜色
"activityBar.background"活动栏背景色
"activityBar.border"分隔活动栏与其他栏的边界
"activityBar.foreground"活动栏选中和悬停颜色
"activityBar.inactiveForeground"活动栏图标颜色

徽章
"activityBarBadge.background"活动栏角标背景色
"activityBarBadge.foreground"活动栏角标前景色
"badge.background"信息标签背景色，资源管理器显示的“一个未保存”等等，此颜色与 activityBarBadge.background 不会互相覆盖，这还是 jupyter notebook 编辑器的一些边框颜色和文字的背景色
"badge.foreground"信息标签前景色

面包屑导航栏
"breadcrumb.foreground"面包屑普通文字颜色
"breadcrumb.background"面包屑导航背景色
"breadcrumb.activeSelectionForeground"点击面包屑导航一段字后可见字变成此颜色并弹出菜单
"breadcrumb.focusForeground"面包屑上的一段字按住不放可见此颜色
"breadcrumbPicker.background"点击面包屑导航一段字后弹出菜单的背景色

按钮颜色
"button.background"按钮背景色
"button.hoverBackground"按钮在悬停时的背景色
"button.secondaryForeground"辅助按钮前景色。
"button.secondaryBackground"辅助按钮背景色
"button.secondaryHoverBackground"辅助按钮悬停

调试
调试工具栏
"debugToolBar.background"调试工具栏背景色，就是调试的时候一个很窄的窗口
"debugToolBar.border"调试工具栏边框
"debugIcon.continueForeground"调试工具栏图标，竖线和三角
"debugIcon.disconnectForeground"拔开的插销
"debugIcon.pauseForeground"两竖线
"debugIcon.restartForeground"循环箭头
"debugIcon.stepBackForeground"弯箭头和圆点
"debugIcon.startForeground"空心三角，这个出现在侧边栏的一个下拉框上，不在调试工具栏里
"debugIcon.stepOutForeground"上箭头和圆点
"debugIcon.stepIntoForeground"下箭头和圆点
"debugIcon.stepOverForeground"弯箭头和圆点
"debugIcon.stopForeground"空心方块

断点
"debugIcon.breakpointForeground"断点圆形符号颜色
"debugIcon.breakpointUnverifiedForeground"未验证断点空心圆圈符号
"debugIcon.breakpointDisabledForeground"在断点圆形符号单机右键，点禁用断点，断点圆形符号变为此颜色
"debugIcon.breakpointCurrentStackframeForeground"当前断点堆栈帧的图标颜色，D 形的小框套着断点图标
"editor.stackFrameHighlightBackground"编辑器调试中，当前行背景色
"debugIcon.breakpointStackframeForeground"所有断点堆栈帧的图标颜色，有时候 D 形的小框会变成这种颜色，在单步调试时也可以看到普通颜色的 D 形框突然变成此颜色
"editor.focusedStackFrameHighlightBackground"debugIcon.breakpointStackframeForeground 对应的编辑器行背景色

调试视图
"debugTokenExpression.value"、"debugTokenExpression.boolean"、"debugTokenExpression.number"、"debugTokenExpression.string"调试视图的变量中不同种类值颜色，不是变量的颜色，是值的颜色；用光标悬停在编辑器中对应变量上也可以看到这些颜色的文本(编辑器组件相关颜色未设置)
"debugTokenExpression.name"调试视图中显示的变量名称的前景色
"debugView.valueChangedHighlight"在“变量”视图中可见此颜色，当变量值改变时，此颜色作为值的背景色突然出现后逐渐淡出并消失，整个过程时间很短
"debugTokenExpression.error"调试视图中表达式错误的前景色，在 2020 年 4 月的更新中这个颜色开始可以在主题中设置，上图并没有展示此颜色
"debugView.stateLabelBackground"“调用堆栈”(CALL STACK)视图中标签的背景色，显示当前会话或线程的状态
"debugView.stateLabelForeground"“调用堆栈”视图中标签的前景色
"debugView.exceptionLabelBackground"调试器因异常而中断时，“调用堆栈”视图中显示的标签的背景色，上图并没有展示此颜色
"debugView.exceptionLabelForeground"调试器因异常而中断时，“调用堆栈”视图中显示的标签的前景色

面板
"panel.background"面板背景色，面板显示在编辑器区域下方，可包含输出和集成终端等视图
"panel.border"面板与编辑器之间的边界
"panelSection.border"面板标签下还可以拖好多的标签，拖进去多个视图就在面板里中水平堆叠，这些视图的分隔线颜色
"panelSectionHeader.background"当多个视图在面板中水平堆叠时，这些视图的头部背景色
"panelSectionHeader.border"上图中没有此颜色，在高对比主题中也没发现此颜色……
"panelSectionHeader.foreground"当多个视图在面板中水平堆叠时，这些视图的头部前景色
"panelTitle.activeBorder"面板标题下划线
"panelTitle.activeForeground"活动面板标题字体颜色
"panelTitle.inactiveForeground"不活动的面板标题的字体颜色
"terminal.ansiBlack"、"terminal.ansiRed"、"terminal.ansiGreen"、"terminal.ansiYellow"、"terminal.ansiBlue"、"terminal.ansiMagenta"、"terminal.ansiCyan"、"terminal.ansiWhite"、"terminal.ansiBrightBlack"、"terminal.ansiBrightRed"、"terminal.ansiBrightGreen"、"terminal.ansiBrightYellow"、"terminal.ansiBrightBlue"、"terminal.ansiBrightMagenta"、"terminal.ansiBrightCyan"、"terminal.ansiBrightWhite"这些是集成终端里有色文字的颜色
"terminal.background"集成终端背景色
"terminal.border"并排两个集成终端分割线颜色
"terminal.foreground"集成终端普通文字颜色
"terminal.selectionBackground"终端选中内容的背景颜色，此颜色不透明的话会遮挡文字
"terminalCursor.background"设置"terminal.integrated.cursorStyle": "block"之后可见，终端光标变成方块，被方块盖住的字体成为此颜色
"terminalCursor.foreground"终端光标的前景色
"debugConsole.errorForeground"调试 REPL 控制台中错误消息的前景色，调试控制台输入支持语法着色
"debugConsole.warningForeground"调试 REPL 控制台中警告消息的前景色
"debugConsole.infoForeground"调试 REPL 控制台中信息消息的前景色
"debugConsole.sourceForeground"调试 REPL 控制台中源文件名的前景色
"debugConsoleInputIcon.foreground"调试控制台输入标记图标的前景色

拖放
"activityBar.dropBorder": "#000"当拖动活动栏上的图标时将可以看到此颜色
"panel.dropBorder"面板头部的标签也可以拖动，拖动将看到此颜色
"panelSection.dropBackground"面板向下方拖动到头部以外时可以看到，这样拖动减少了头部的标签数量
"sideBar.dropBackground"侧边栏拖拽节标题可见
"editorGroup.dropBackground"编辑器选项卡拖拽可见
"list.dropBackground"列表拖拽通用

标题栏和窗框
"titleBar.activeBackground"活动窗口标题栏背景色
"titleBar.activeForeground"活动窗口标题栏前景色
"titleBar.border"标题栏边框
"titleBar.inactiveBackground"非活动窗口标题栏背景色
"titleBar.inactiveForeground"非活动窗口标题栏前景色
"menubar.selectionBackground"菜单栏中选定菜单项的背景色
"menubar.selectionBorder"菜单栏中所选菜单项的虚线边框颜色
"menubar.selectionForeground"菜单栏中选定菜单项的前景色
"window.activeBorder"活动窗框颜色，仅在使用自定义标题栏时在桌面客户端中支持
"window.inactiveBorder"非活动窗框颜色

状态栏
"statusBar.background"工作区打开时状态栏的背景色
"statusBar.border"状态栏分隔侧边栏和编辑器的边框颜色
"statusBar.foreground"工作区打开时状态栏的前景色
"statusBar.debuggingBackground"调试中状态栏的背景色
"statusBar.debuggingBorder"调试中状态栏的边框色
"statusBar.debuggingForeground"调试中状态栏的前景色
"statusBar.noFolderBorder"当没有打开文件夹时状态栏的背景色
"statusBar.noFolderBackground"当没有打开文件夹时状态栏的边框颜色
"statusBar.noFolderForeground"当没有打开文件夹时状态栏的前景色
"statusBarItem.activeBackground"按下状态栏的一个图标或文字可见
"statusBarItem.hoverBackground"光标悬停在状态栏的一个图标或文字可见
"statusBarItem.prominentBackground"状态栏突出显示项的背景颜色，在命令面板中更改“Toggle Tab Key Moves Focus”可查看示例
"statusBarItem.prominentForeground"状态栏突出显示项的前景色
"statusBarItem.prominentHoverBackground"光标悬停状态栏突出显示项的背景色
"statusBarItem.remoteBackground"远程指示器在安装 ms-vscode-remote.vscode-remote-extensionpack 插件才有效，在状态栏左侧有一个小符号，其背景色
"statusBarItem.remoteForeground"远程指示器前景色

侧边栏
"sideBar.background"侧边栏背景色
"sideBar.border"侧边栏分隔编辑器的边框颜色
"sideBar.foreground"侧边栏前景色
"sideBarSectionHeader.background"侧边栏节标题的背景颜色
"sideBarSectionHeader.border"侧边栏节标题的边框色
"sideBarSectionHeader.foreground"侧边栏节标题的前景色
"sideBarTitle.foreground"侧边栏标题前景色，标题在所有节标题的上方

列表

"list.warningForeground"列表中包含警告的列表项的前景颜色
"list.errorForeground"列表中包含错误的列表项的前景颜色，比如文件里代码错了，侧边栏文件夹就看到文件名变为此颜色
"list.focusBackground"列表焦点背景色，在列表按上下键可见
"list.focusForeground"列表焦点前景色
"listFilterWidget.background"在列表中查找，比如在资源管理器中按动键盘上的字母会出现筛选器组件小框，小框背景色
"listFilterWidget.noMatchesOutline"筛选器组件搜索无结果时，其边界颜色
"listFilterWidget.outline"筛选器组件边框色
"list.highlightForeground"在列表或树中搜索时，其中匹配内容的高亮颜色，上图看不出此颜色，可以在 ctrl/cmd+shift+p 命令中输入一个字母就可以看到正下方列表中有相同字母变成此颜色
"list.hoverBackground"列表悬停背景色
"list.hoverForeground"列表悬停前景色
"list.invalidItemForeground"列表或树中无效项的前景色，例如资源管理器中没有解析的根目录
"list.activeSelectionBackground"已选项背景色
"list.activeSelectionForeground"已选项前景色，即使项有警告或错误，其文字也会变成此颜色
"list.inactiveSelectionBackground"已选项在非活动的列表或树的背景色
"list.inactiveSelectionForeground"已选项在非活动的列表或树的前景色
"list.deemphasizedForeground"取消强调的项目的列表/树前景颜色，调用堆栈中可以看到
"list.inactiveFocusBackground"非活动的列表或树控件中焦点项的背景颜色，在大纲里按上下方向键但后鼠标点别处可见此颜色
"menu.background"菜单(菜单栏下拉和右键菜单)背景色
"menu.border"菜单边框
"menu.foreground"菜单前景色
"menu.selectionBackground"菜单中所选菜单项的背景色
"menu.selectionBorder"菜单中所选菜单项的边框
"menu.selectionForeground"菜单中所选菜单项的前景色
"menu.separatorBackground"菜单分割线颜色自动透明

活动选项卡
活动选项卡
"tab.activeBackground"活动选项卡的背景色
"tab.activeBorder":活动选项卡的下框线色
"tab.activeBorderTop"活动选项卡的上边框颜色可以单独设置
"tab.activeForeground":活动选项卡的前景色
"tab.hoverBackground"选项卡的悬停背景色，光标悬停在活动选项卡时，活动选项卡背景也变成此颜色
"tab.hoverBorder"选项卡的悬停下框线色，光标悬停在活动选项卡时，活动选项卡下框线不会变成此颜色
"tab.hoverForeground"选项卡的悬停前景色，光标悬停在活动选项卡时，活动选项卡字体也变成此颜色
"tab.inactiveBackground"普通选项卡背景色
"tab.inactiveForeground"普通选项卡前景色
"tab.border"选项卡两侧边框色
"tab.unfocusedActiveBackground"、"tab.unfocusedActiveBorder"``"tab.unfocusedActiveBorderTop"、"tab.unfocusedActiveForeground"、"tab.unfocusedHoverBackground"、"tab.unfocusedHoverBorder"、"tab.unfocusedHoverForeground"、"tab.unfocusedInactiveBackground"、"tab.unfocusedInactiveForeground"不带焦点的组中的选项卡对应颜色

编辑器组头部
"editorGroupHeader.border"编辑器组标题标头的边框颜色，面包屑下方横线颜色
"editorGroupHeader.noTabsBackground"设置"workbench.editor.showTabs": false 之后可见
"editorGroupHeader.tabsBackground"选项卡停靠位置的背景色，上图非活动选项卡颜色被我调成了透明
"editorGroupHeader.tabsBorder"编辑器组标题的边框，就是面包屑上方选项卡下方的横线颜色

快速选取器
"quickInput.background"快速选取器背景色
"quickInput.foreground"快速选取器前景色
"quickInputTitle.background"快速选取器标题背景色，标题位于输入框上方
"pickerGroup.border"快速选取器分组边框色
"pickerGroup.foreground"快速选取器分组标签色

输入框
输入框选项
"inputOption.activeBackground"输入字段中激活选项的背景色
"inputOption.activeBorder"输入字段中激活选项的边框色
"inputOption.activeForeground"输入字段中激活选项的前景色，这些选项还出现在侧边栏的一些输入框上

输入验证
"inputValidation.errorBackground"输入验证结果为错误级别时的背景色输入框下面多出一个有文本的小框，与输入框等宽
"inputValidation.errorBorder"输入验证结果为错误级别时的边框色，小框与输入框共用边框颜色
"inputValidation.errorForeground"输入验证结果为错误级别时的前景色
"inputValidation.warningBackground"输入验证结果为警告级别时的背景色，上图就是警告级别
"inputValidation.warningBorder"输入验证结果为警告级别时的边框色
"inputValidation.warningForeground"输入验证结果为警告级别时的前景色
"inputValidation.infoBackground"输入验证结果为信息级别时的背景色
"inputValidation.infoBorder"输入验证结果为信息级别时的边框色
"inputValidation.infoForeground"输入验证结果为信息级别时的前景色

输入框
"input.background"输入框背景色
"input.border"输入框边框色
"input.foreground"输入框前景色
"input.placeholderForeground"输入框中占位符的前景色
"settings.numberInputBackground"设置编辑器编号输入框背景色
"settings.numberInputBorder"设置编辑器编号输入框边框色
"settings.numberInputForeground"设置编辑器编号输入框前景色
"settings.textInputBackground"设置编辑器文本输入框背景色
"settings.textInputBorder"设置编辑器文本输入框边框色
"settings.textInputForeground"设置编辑器文本输入框前景色
"searchEditor.textInputBorder"活动栏搜索中按下纸张图标打开新的搜索编辑器可见此颜色
"panelInput.border"面板上的输入框边框颜色

下拉框、复选框
"checkbox.background"复选框小部件的背景颜色是复选框中心的颜色
"checkbox.border"复选框小部件的边框颜色是圆角矩形的颜色
"checkbox.foreground"复选框对勾的颜色
"settings.checkboxBackground"、"settings.checkboxBorder"、"settings.checkboxForeground"设置页面里的复选框颜色
"dropdown.background"下拉列表背景色
"dropdown.foreground"下拉列表前景色
"dropdown.border"下拉列表边框色
"settings.dropdownBackground"、"settings.dropdownBorder"、"settings.dropdownForeground"设置编辑器下拉列表颜色
"dropdown.listBackground"下拉列表背景色
"settings.dropdownListBorder"设置编辑器下拉列表边框，这会将选项包围起来，并将选项与描述分开。

文本编辑器、设置界面、欢迎界面
编辑器基础颜色
"editor.foreground"编辑器普通文字前景色
"editorGroup.border"将多个编辑器组彼此分隔开的颜色
"editorGroup.emptyBackground"空编辑器组的背景色
"editorGroup.focusedEmptyBorder"获得焦点的空编辑器组的边框色，在"editorGroup.focusedEmptyBorder"内侧出现一圈边框
"editor.lineHighlightBackground"光标所在行的背景色
"editor.lineHighlightBorder"光标所在行边框
"editor.background"非空编辑器的背景色
"editorLineNumber.activeForeground"“editor.renderLineHighlight”: “all"之后可见光标所在行行号变色了
"editorLineNumber.foreground"行号颜色
"editorPane.background"在 ctrl/cmd+shift+p 命令中输入 Toggle Centered Layout 就可以看到这种颜色
"editorRuler.foreground"编辑器标尺颜色，通过设置"editor.rulers”: [这里随便输几个数字]来控制标尺位置，标尺实际上会遮挡文字，但是标尺很细一般不会影响编辑
"editorGutter.background"行号背景色默认是编辑器的背景色
"minimap.background"小视图背景色默认也是编辑器的背景色
"editorOverviewRuler.background"编辑器右侧滚动条(概述标尺)的背景色，默认就是启用的，默认和编辑器背景一个颜色
"editorOverviewRuler.border"编辑器右侧滚动条边框色

设置、欢迎界面
"settings.headerForeground"设置的节标题或活动标题的前景颜色
"settings.modifiedItemIndicator"设置修改后的设置指示器的颜色，是在修改后的设置的左边的一个竖条
"walkThrough.embeddedEditorBackground"命令输入 Interactive Playground 可以打开交互式演练场，其中有占据整行的可编辑区域
"welcomePage.background"欢迎页面的背景色
"welcomePage.buttonBackground"欢迎页按钮的背景色
"welcomePage.buttonHoverBackground"欢迎页按钮悬停时背景色

光标
"editorCursor.background"编辑器光标颜色
"editorCursor.foreground"设置"editor.cursorStyle": "block"后被光标遮住的文字前景色

灯泡

"editorLightBulb.foreground"编辑器灯泡颜色
"editorLightBulbAutoFix.foreground"这不是小改锥的颜色，是另一种灯泡，产品图标参考找到灯泡自动修复

编辑器组件
"editorWidget.background"一次性设置所有编辑器组件背景色
"editorWidget.border"所有编辑器组件边框色
"editorWidget.resizeBorder"所有编辑器组件调整大小用的竖条色
"editorWidget.foreground"所有编辑器组件字体颜色
"editorHoverWidget.background"编辑器悬停提示的背景色，悬停提示就是光标在代码的一个单词或波浪线上悬停出现的小框
"editorHoverWidget.border"编辑器悬停提示的边框颜色
"editorHoverWidget.foreground"编辑器悬停提示的前景色
"editorHoverWidget.statusBarBackground"编辑器悬停状态栏的背景色，状态栏上写着“速览问题”和“快速修复”
"editorSuggestWidget.background"建议小组件背景色，建议小组件如图所示，用来提示代码的，形如列表，建议小组件的悬停背景色和前景色采用列表的悬停背景色和前景色
"editorSuggestWidget.border"建议小组件边框色
"editorSuggestWidget.foreground"建议小组件前景色
"editorSuggestWidget.highlightForeground"建议小组件中匹配内容的高亮颜色，就是和已经在编辑器中敲出来的部分匹配的内容的前景色
"editorSuggestWidget.selectedBackground"建议小组件中选中项背景

代码片段
"editor.snippetFinalTabstopHighlightBackground"只有在包含“$0”的代码片段中才能看到此颜色，因为这时代码片段中最后的 Tab 位不是一条竖线，参考代码片段
"editor.snippetFinalTabstopHighlightBorder"代码片段中最后的 Tab 位边框色
"editor.snippetTabstopHighlightBackground"代码片段 Tab 位的高亮背景色
"editor.snippetTabstopHighlightBorder"代码片段 Tab 位的高亮边框色

笔记本(没图)
VSCode-win32-x64-1.48.0-insider 中安装 ms-vscode.vscode-github-issue-notebooks 插件之后就可以用 VSCode insider 查看和编辑.github-issue 后缀的文件了，这可能需要登一下 GitHub
"notebook.cellBorderColor"笔记本单元格中编辑器在无焦点时的边框颜色
"notebook.focusedEditorBorder"笔记本单元格中编辑器在有焦点时的边框颜色
"notebook.cellHoverBackground"悬停在笔记本单元格上时笔记本单元格的颜色
"notebook.focusedCellBackground"焦点单元格的背景色
"notebook.focusedCellBorder"焦点单元格的上下边框的颜色
"notebook.cellInsertionIndicator"笔记本单元格插入指示符的颜色
"notebook.cellStatusBarItemHoverBackground"笔记本单元格可编辑区域右下角的“GitHub Issues”或者“Markdown”字样的背景色
"notebook.outputContainerBackgroundColor"笔记本输出容器背景色
"notebook.cellToolbarSeperator"Property notebook.cellToolbarSeperator is not allowed.
"notebook.focusedCellShadow"Property notebook.focusedCellShadow is not allowed.
"notebookStatusRunningIcon.foreground"单元格状态栏中笔记本单元格的“正在运行”图标颜色
"notebookStatusSuccessIcon.foreground"单元格状态栏中笔记本单元格的完成图标颜色
"notebookStatusErrorIcon.foreground"单元格状态栏中笔记本单元格的错误图标颜色

速览视图
"peekView.border"速览视图边框和箭头颜色，所谓箭头即上图边框上的多出来的三角
"peekViewEditor.background"速览视图编辑器背景色
"peekViewEditorGutter.background"速览视图编辑器行号背景色
"peekViewResult.background"速览视图右侧结果列表背景色，其悬停背景色和前景色采用列表的悬停背景色和前景色
"peekViewResult.fileForeground"速览视图结果列表中文件节点的前景色，文件节点左侧有 V 形图标右侧有数字
"peekViewResult.lineForeground"速览视图结果列表中行节点的前景色
"peekViewResult.selectionBackground"速览视图右侧结果列表中所选条目的背景色
"peekViewResult.selectionForeground"速览视图右侧结果列表中所选条目的前景色
"peekViewTitle.background"速览视图标题区域背景色
"peekViewTitleDescription.foreground"速览视图标题信息颜色，标题信息在标题右侧，上图中一段文件路径呈现此颜色
"peekViewTitleLabel.foreground"速览视图标题前景色
"debugExceptionWidget.border"异常小组件边框颜色，调试异常小部件是一个 peek 视图，上图展示了调试异常小部件
"debugExceptionWidget.background"异常小组件背景颜色
"editorMarkerNavigation.background"编辑器标记导航小组件背景色，在一个有错误/警告/信息波浪线的代码上悬停直到看到悬停小组件，在小组件装天蓝上点击“速览问题”即可看到标记导航小组件
"editorMarkerNavigationError.background"编辑器标记导航小组件错误边框色
"editorMarkerNavigationWarning.background"编辑器标记导航小组件警告边框色
"editorMarkerNavigationInfo.background"编辑器标记导航小组件信息边框色

提示
"editorError.border"语法错误代码双下划线颜色
"editorWarning.border"有警告的代码双下划线颜色
"editorInfo.border"一些信息代码双下划线颜色
"editorHint.border"这个颜色和"editorHint.foreground"早在 2018 年 3 月的更新中就出现了，被提示代码单虚颜色

"editorError.foreground"语法错误代码波浪线颜色
"editorWarning.foreground"有警告的代码波浪线颜色
"editorInfo.foreground"一些信息代码波浪线颜色
"editorHint.foreground"被提示代码单虚颜色，首次见到是在交互式操练场页

"editorOverviewRuler.errorForeground"语法错误代码在滚动条高亮显示
"editorOverviewRuler.warningForeground"有警告的代码在滚动条高亮显示
"editorOverviewRuler.infoForeground"信息代码在在滚动条高亮显示

"minimap.errorHighlight"小视图中的语法错误代码前景色和背景色
"minimap.warningHighlight"小视图中的有警告的代码前景色和背景色

对比
"diffEditor.border"两个文本编辑器之间的边框色
"diffEditor.diagonalFill"差异编辑器的密密麻麻的 45° 斜线颜色
"merge.border"内联合并冲突中标头和分割线的边框颜色，就是“<<<<<<< HEAD”所在的一行的上下边框颜色

"diffEditor.insertedTextBackground"已插入的文本的背景色，默认偏绿在右侧，就是刚刚改过打算保存结果保存不了的文本
"diffEditor.insertedTextBorder"已插入的文本的轮廓颜色，即使透明也会出现横条

"diffEditor.removedTextBackground"已删除的文本的背景色；就是打算保存结果保存不了时文件中已有的较新的版本，默认偏红在左侧；颜色必须透明，以免隐藏下面的修饰效果，但是上图的颜色就不透明，并没有遮挡文字
"diffEditor.removedTextBorder"已删除文本的轮廓颜色，即使透明也会出现横条

"merge.currentContentBackground"内联合并冲突中的当前内容背景，点击“比较变更”后跑到编辑器左侧
"merge.currentHeaderBackground"当前标题背景的内联合并冲突
"editorOverviewRuler.currentContentForeground"内联合并冲突中当前版本区域的概览标尺前景色，默认是"merge.currentHeaderBackground"的颜色，连透明度一起继承

"merge.incomingContentBackground"内联合并冲突中的传入内容背景，点击“比较变更”后跑到编辑器右侧
"merge.incomingHeaderBackground"内联合并冲突中的传入标题背景
"editorOverviewRuler.incomingContentForeground"内联合并冲突中传入的版本区域的概览标尺前景色，默认是"merge.incomingHeaderBackground"的颜色

"merge.commonContentBackground"内联合并冲突中的共同祖先内容背景，上图中未出现共同祖先内容
"merge.commonHeaderBackground"内联合并冲突中的共同祖先标题背景
"editorOverviewRuler.commonContentForeground"内联合并冲突中共同祖先区域的概览标尺前景色

其它
"editorCodeLens.foreground"编辑器 CodeLens 的前景色，Java 插件的“Run|Debug”等等，悬停颜色是"editorLink.activeForeground"
"editorUnnecessaryCode.opacity"、"editorUnnecessaryCode.border"非必须代码的在编辑器中显示的不透明度。对于高对比度主题则使用“editorUnnecessaryCode.border”，"editorUnnecessaryCode.opacity"颜色中仅透明度值发挥作用，上图中 RGB 部分设置了橙色但非必须代码依然显示白色
"editorWhitespace.foreground"编辑器中空白字符的颜色，设置"editor.renderWhitespace": "all"可以清楚地看到此颜色
"editor.foldBackground"折叠范围后面的背景颜色，点击行号旁边的尖角图标可以折叠代码并且看到此颜色
"editorGutter.foldingControlForeground"行号旁边的尖角图标颜色

源代码控制颜色
"scm.providerBorder"SCM 提供程序分隔符边框

链接
"textLink.foreground"文本中链接的前景色，在欢迎和许多扩展的界面里普遍存在
"textLink.activeForeground"文本中链接在点击或鼠标悬停时的前景色
"notificationLink.foreground"通知链接的前景色，有少量通知中有链接，上图未展示此颜色
"editorLink.activeForeground"活动链接颜色

标签文本
"textBlockQuote.background"文本中块引用的背景颜色
"textBlockQuote.border"文本中块引用的边框颜色

"textBlockQuote.background"就是这个的颜色，"textBlockQuote.border"就是左边竖条的颜色

"textCodeBlock.background"文本中代码块的背景颜色，上图建议小组件中可以非常明显地看到此颜色
"descriptionForeground"提供其他信息的说明文本的前景色，例如标签文本
"textPreformat.foreground"预格式化文本段的前景色，如图中 C#扩展所示
"textSeparator.foreground"文字分隔符的颜色。

匹配
上图中各种匹配背景色均不透明，并没有遮挡文字

列表
"list.filterMatchBackground"列表筛选后的匹配项的背景颜色，可以不透明，不会遮挡文字，上图
"list.filterMatchBorder"列表筛选后的匹配项的边框色

编辑器匹配
"editor.findMatchBackground"编辑器中当前匹配项背景色
"editor.findMatchBorder"编辑器中当前匹配项边框色
"minimap.findMatchHighlight"编辑器匹配项在右侧小视图中的背景色与前景色，设置"editor.minimap.enabled": true 就可以看到小视图
"editorOverviewRuler.findMatchForeground"编辑器匹配项在滚动条上的颜色，这些颜色显示为小矩形
"editor.findMatchHighlightBackground"编辑器中匹配项背景色
"editor.findMatchHighlightBorder"编辑器中匹配项边框色
"editor.rangeHighlightBackground"编辑器中当前匹配项所在整行的背景色
"editor.rangeHighlightBorder"编辑器中当前匹配项所在整行的边框色，这个颜色如果设置了，即使为透明也会让匹配充满横条
"editorOverviewRuler.rangeHighlightForeground"编辑器当前匹配项在右侧小视图中的背景色与前景色，这个颜色似乎总是不显示

编辑器限制搜索的范围
"editor.findRangeHighlightBackground"限制搜索的范围背景色
"editor.findRangeHighlightBorder"这个颜色使得限制搜索的范围有许多横线，即使设置为透明色横线依然存在，所以只能不设置此颜色才能去掉这些横线

搜索编辑器
"searchEditor.findMatchBackground"搜索编辑器查询匹配的背景色
"searchEditor.findMatchBorder"搜索编辑器查询匹配的边框色

括号匹配
"editorBracketMatch.background"匹配括号的背景色
"editorBracketMatch.border"匹配括号的边框色
"editorOverviewRuler.bracketMatchForeground"匹配括号在滚动条上的颜色

速览视图
"peekViewEditor.matchHighlightBackground"在速览视图编辑器中匹配突出显示颜色，就是右侧列表中的方法名等在左侧编辑器中的匹配颜色
"peekViewEditor.matchHighlightBorder"在速览视图编辑器中匹配突出显示边框色
"peekViewResult.matchHighlightBackground"在速览视图结果列表中匹配突出显示颜色

选中文本
这些颜色真的需要透明，它们在同一个地方出现有时会互相覆盖
"editor.selectionBackground"编辑器所选内容的背景色
"editor.selectionForeground"编辑器所选内容的前景色，高对比度专用
"editor.inactiveSelectionBackground"非活动编辑器中所选内容背景色，默认是"editor.selectionBackground"基础上更加透明

"editor.selectionHighlightBackground"具有与所选项相关内容的区域的背景色
"editor.selectionHighlightBorder"具有与所选项相关内容的区域的边框颜色"editorOverviewRuler.selectionHighlightForeground"滚动条具有与所选项相关内容的区域颜色

"editor.symbolHighlightBackground"突出显示的符号的背景颜色，上图中未展示此颜色
"editor.symbolHighlightBorder"突出显示的符号的边框颜色，上图中未展示此颜色

"editor.wordHighlightBackground"读取访问期间符号的背景色，如图所示的 css 文件中将编辑器光标停在选择器上时同时出现读访问和写访问背景色
"editor.wordHighlightBorder"符号在进行读取访问操作时的边框颜色
"editorOverviewRuler.wordHighlightForeground"读访问滚动条颜色

"editor.wordHighlightStrongBackground"写入访问过程中符号的背景色
"editor.wordHighlightStrongBorder"符号在进行写入访问操作时的边框色
"editorOverviewRuler.wordHighlightStrongForeground"写访问滚动条颜色
"minimap.selectionHighlight"编辑器选区在小视图中对应的标记颜色
"selection.background"工作台所选文本的背景颜色，不适用于编辑器
"editor.hoverHighlightBackground"光标悬停在代码上时代码高亮背景色

滚动条
"scrollbarSlider.activeBackground"滚动条滑块在被点击时的背景色
"scrollbarSlider.hoverBackground"光标悬停滚动条在滑块时的滑块背景色
"scrollbarSlider.background"滚动条滑块背景色
"notebookScrollbarSlider.activeBackground"、"notebookScrollbarSlider.background"、"notebookScrollbarSlider.hoverBackground"笔记本中的滚动条颜色可以单独设置
"minimapSlider.background"小视图滑块背景色
"minimapSlider.hoverBackground"光标悬停小视图在滑块时的滑块背景色
"minimapSlider.activeBackground"小视图滑块被点击时背景色
"scrollbar.shadow"这根本不是什么 Scrollbar slider shadow，这是面包屑下面那条阴影的颜色，有些列表也有此阴影

缩进参考线
"editorIndentGuide.activeBackground"编辑器活动缩进参考线的颜色
"editorIndentGuide.background"编辑器缩进参考线的颜色
"tree.indentGuidesStroke"缩进参考线颜色

通知
"notificationCenter.border"通知中心的边框颜色，点击状态栏的铃铛就可以看到通知中心了
"notificationToast.border"通知横幅的边框颜色，通知中心和横幅上一般都有按钮
"notificationCenterHeader.background"通知中心头部的背景色
"notificationCenterHeader.foreground"通知中心头部的前景色
"notifications.border"通知中心中分隔通知的边框的颜色
"notifications.background"通知横幅和通知中心的背景色
"notifications.foreground"通知的前景色

Git

选项卡的上边框
"tab.activeModifiedBorder"活动编辑器组中活动选项卡
"tab.inactiveModifiedBorder"活动编辑器组中非活动选项卡
"tab.unfocusedActiveModifiedBorder"非活动编辑器组中活动选项卡
"tab.unfocusedInactiveModifiedBorder"非活动编辑器组中非活动选项卡

源代码管理的视图
"gitDecoration.conflictingResourceForeground"创建分支后分别做不同编辑然后合并即可造成冲突
"gitDecoration.addedResourceForeground"新增资源的颜色，资源右侧的字母为“A”
"gitDecoration.deletedResourceForeground"已删除的资源的颜色，资源右侧的字母为“D”
"gitDecoration.ignoredResourceForeground"忽略的资源的颜色，右侧没有字母
"gitDecoration.modifiedResourceForeground"已更改的资源的颜色，资源右侧的字母为“M”
"gitDecoration.submoduleResourceForeground"子模块资源的颜色
"gitDecoration.untrackedResourceForeground"未跟踪资源的颜色，资源右侧的字母为“U”

编辑器
"editorGutter.addedBackground"行号右侧新增行的颜色
"minimapGutter.addedBackground"小视图左侧新增行的颜色
"editorOverviewRuler.addedForeground"滚动条新增行的颜色

"editorGutter.deletedBackground"行号右侧删除行的颜色，表示为一个很小很小的三角
"minimapGutter.deletedBackground"小视图左侧删除行的颜色，是一段短线或者说一个小矩形
"editorOverviewRuler.deletedForeground"也是一段短线，比"minimapGutter.deletedBackground"略大

"editorGutter.modifiedBackground"行号右侧修改过的行的颜色
"minimapGutter.modifiedBackground"小视图左侧修改的行颜色
"editorOverviewRuler.modifiedForeground"滚动条修改过的行颜色

"editorGutter.commentRangeForeground"导航线中表示评论范围的颜色

图标
"problemsErrorIcon.foreground"问题错误图标的颜色，出现在标记导航小组件等地方
"notificationsErrorIcon.foreground"错误通知图标的颜色，出现在通知中心
"problemsWarningIcon.foreground"问题警告图标的颜色
"notificationsWarningIcon.foreground"警告通知图标的颜色
"problemsInfoIcon.foreground"问题信息图标的颜色
"notificationsInfoIcon.foreground"信息通知图标的颜色

符号

"symbolIcon.arrayForeground"数组符号：一对方括号
"symbolIcon.booleanForeground"布尔符号：半黑半白矩形里面有双向箭头
"symbolIcon.classForeground"类符号：分枝状符号
"symbolIcon.colorForeground"颜色符号：一个调色盘，首次见到是在 html 中写 svg 标签时
"symbolIcon.constantForeground"常量符号：“目”形，很扁，大纲和建议小部件都可见
"symbolIcon.constructorForeground"构造函数符号：立方体形符号
"symbolIcon.enumeratorForeground"枚举符号：“目目”形
"symbolIcon.enumeratorMemberForeground"枚举器成员符号：“日目”形
"symbolIcon.eventForeground"事件符号：空心闪电形符号
"symbolIcon.fieldForeground"字段符号：一块砖
"symbolIcon.fileForeground"文件符号：一张折角纸，出现在建议小部件
"symbolIcon.folderForeground"文件夹符号：就是文件夹的形状，出现在建议小部件
"symbolIcon.functionForeground"函数符号：立方体形符号
"symbolIcon.interfaceForeground"接口符号：用横线连在一起的实心圆和空心圆
"symbolIcon.keyForeground"键符号：不明
"symbolIcon.keywordForeground"关键字符号：方块和四道横条，其中两道是断的
"symbolIcon.methodForeground"方法符号：立方体形符号
"symbolIcon.moduleForeground"模块符号：一对花括号，json 大纲和建议小部件都可见
"symbolIcon.namespaceForeground"命名空间符号：一对花括号
"symbolIcon.nullForeground"空符号：不明
"symbolIcon.numberForeground"数字符号：“#”形
"symbolIcon.objectForeground"对象符号：一对花括号
"symbolIcon.operatorForeground"运算符符号：“%-×+”字样田字排列
"symbolIcon.packageForeground"包符号：一对花括号
"symbolIcon.propertyForeground"属性符号：一个管道扳手
"symbolIcon.referenceForeground"参考符号：折角纸和弯箭头，敲 C#时在建议小部件里发现此符号，之前一直没看到
"symbolIcon.snippetForeground"片段符号：下框线为虚线的矩形
"symbolIcon.stringForeground"字符串符号：圆角矩形内部有“abc”
"symbolIcon.structForeground"结构符号：“品”形
"symbolIcon.textForeground"文本符号：“abc”字样
"symbolIcon.typeParameterForeground"类型参数符号：不明
"symbolIcon.unitForeground"单位符号：刻度尺形，首次见到是在修改 html 中的动画时
"symbolIcon.variableForeground"变量符号：方括号内一块砖

扩展视图小组件
"extensionBadge.remoteBackground"扩展视图中远程徽标的背景色
"extensionBadge.remoteForeground"扩展视图中远程徽标的前景色
"extensionButton.prominentForeground"扩展中突出操作的按钮前景色，是左上角星标和右下角安装按钮
"extensionButton.prominentHoverBackground"扩展中突出操作的按钮被悬停时的颜色
"extensionButton.prominentBackground"扩展中突出操作的按钮背景色
```
