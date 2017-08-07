# VSCode Tricks
VSCode相关快捷键与技巧个人收藏

## 快捷键
#### 重构代码
* 上下移动一行：Alt+Up 或 Alt+Down
* 向上向下复制一行：Shift+Alt+Up或Shift+Alt+Down
* 跳转到定义处：F12
* 定义处缩略图：查看浏览而不跳转过去Alt+F12
* 列出所有的引用：Shift+F12
* 同时修改本文件中所有匹配的：Ctrl+F12
* 重命名：选中后按F2，输入新的名字回车，会发现所有的文件都修改过了。
* 跳转到下一个Error或Warning：当有多个错误时可以按F8逐个跳转
* 查看diff 在explorer里选择文件右键 Set file to compare，然后需要对比的文件上右键选择Compare with 'file_name_you_chose'.

#### 查找替换
* 查找 Ctrl+F
* 查找替换 Ctrl+Alt+F
* 整个文件夹中查找 Ctrl+Shift+F
* 查找文件 Ctrl+P
* 代码反选到文件 Ctrl+Shift+E

#### 显示
* 侧边栏显/隐：Ctrl+B
* 预览markdown: Ctrl+Shift+V
* 代码格式化：Shift+Alt+F

#### 注释
* 多行注释: Shift+Alt+A
* 生成注释文档：Control+Alt+D两次(需要)

## 命令面板
直接输入文件名，跳转到文件
* \> 打开命令面板。在打开的输入框内，可以输入任何命令(Ctrl+Shift+P)
* ? 列出当前可执行的动作
* ! 显示 Errors或 Warnings，也可以 Ctrl+Shift+M
* : 跳转到行数，也可以 Ctrl+G 直接进入
* @ 跳转到 symbol（搜索变量或者函数），也可以 Ctrl+Shift+O 直接进入
* \# 根据名字查找 symbol，也可以 Ctrl+T
* \* 显示命令 Ctrl+Shift+P


## 相关插件安装
- [Document this](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight): 任务中可搜索List hilighted annotations
- [React Native Tool](https://marketplace.visualstudio.com/items?itemName=vsmobile.vscode-react-native)

## 参考
- https://medium.com/react-native-training/vscode-for-react-native-526ec4a368ce
- MS官方tips: https://github.com/Microsoft/vscode-tips-and-tricks
