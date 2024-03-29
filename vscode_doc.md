# VSCode常用功能说明

## 快捷键

### 基础编辑


|  快捷键   | 作用  |
|  ----  | ----  |
|Ctrl+X	|剪切|
|Ctrl+C|	复制|
|Ctrl+Shift+K|	删除当前行|
|Ctrl+Enter|	在当前行之后插入一行|
|Ctrl+Shift+Enter|	在当前行之前插入一行|
|Alt+Up/Down|	移动当前行上下|
|Shift+Alt+Up/Down|	在当前行上下复制当前行|
|Ctrl+Up/Down|	行视图上下偏移|
|Alt+PageUp/PageDown|	屏视图上下偏移|
|Ctrl+Shift+[	|折叠区域代码|
|Ctrl+Shift+]	|展开区域代码|
|Ctrl+K Ctrl+[|	折叠区域内所有代码（包括子域和父域）|
|Ctrl+K Ctrl+]|	展开区域内所有代码（包括子域和父域）|
|Ctrl+K Ctrl+0|	折叠所有区域内的代码|
|Ctrl+K Ctrl+J|	展开所有区域内的代码|
|Ctrl+K Ctrl+C|	添加行注释|
|Ctrl+K Ctrl+U|	删除行注释|
|Ctrl+/	|添加关闭行注释|
|Shift+Alt+A|	添加关闭区域注释|
|Alt+Z|	添加关闭自动换行|
### 导航
|  快捷键   | 作用  |
|  ----  | ----  |
|Ctrl+T	|启动符号搜索框|
|Ctrl+G|	跳转行|
|Ctrl+P|	启动文件搜索框，方便快速打开文件|
|Ctrl+Shift+O|	跳转至符号处|
|Ctrl+Shift+M|	显示问题面板|
|F8|	跳转到下一个错误或者警告|
|Shift+F8|	跳转到上一个错误或者警告|
|Ctrl+Shift+Tab	|切换到最近打开的文件|
|Alt+Left/Right|	向前/向后|
### 查询
|  快捷键   | 作用  |
|  ----  | ----  |
|Ctrl+F|	查询|
|Ctrl+H|	替换|
|F3|	查找下一个|
|Shift+F3|	查找上一个|
|Alt+Enter|	选中所有匹配的查询字符|
|Alt+C|	切换是否区分大小写查找|
|Alt+R|	切换是否使用正则查找|
|Alt+W|	切换是否使用全词查找|
### 编辑/窗口管理
|  快捷键   | 作用  |
|  ----  | ----  |
|Ctrl+Shift+N|	打开新窗口|
|Ctrl+W	|关闭窗口|
|Ctrl+F4|	关闭当前编辑窗口|
|Ctrl+K F|	关闭当前打开的文件夹|
|Ctrl+\	|拆分编辑器（最多拆分为三块）|
|Ctrl+1/2/3	|切换焦点在不同的拆分窗口|
### 文件管理
|  快捷键   | 作用  |
|  ----  | ----  |
|Ctrl+N|	新建文件|
|Ctrl+O|	打开文件|
|Ctrl+S|	保存文件|
|Ctrl+K S|	保存所有文件|
|Ctrl+Shift+S|	另存为|
|Ctrl+K W|	关闭一组拆分的窗口|
|Ctrl+K Ctrl+W|	关闭所有编辑窗口|
|Ctrl+Shift+T|	撤销最近关闭的一个文件编辑窗口|
|Ctrl+Tab|	调出最近打开的文件列表，重复按会切换到下一个|
|Ctrl+Shift+Tab|	调出最近打开的文件列表，重复按会切换到上一个|
|Ctrl+K P|	复制当前打开文件的存放路径|
|Ctrl+K R|	打开当前编辑文件存放位置【文件管理器】|
|Ctrl+K O|	在新的编辑器中打开当前编辑的文件|
### 显示
|  快捷键   | 作用  |
|  ----  | ----  |
|F11|	切换全屏显示|
|Ctrl+B|	切换侧边栏显示隐藏|
|Ctrl+Shift+V|	Markdown预览切换|
### 光标操作
|  快捷键   | 作用  |
|  ----  | ----  |
|Home/End|	光标跳转到行首/尾|
|Ctrl+Home/End|	光标跳转到页首/尾|
|Alt+Click|	插入光标（支持多个）|
|Ctrl+Alt+Up/Down|	上下插入光标（支持多个）|
|Ctrl+U|	撤销最后一次光标操作|
|Shift+Alt+I|	插入光标到选中范围内所有行行尾|
|Ctrl+I|	选中当前行|
|Shift+Alt+(drag mouse)	|在鼠标拖动区域的每行行尾插入光标|
|Ctrl+F2|	选择当前字符的所有出现，然后进行操作|

## 插件安装卸载
### 安装
1. 点击extentions或者使用快捷键Ctrl+Shift+X打开插件搜索页面

2. 搜索想要安装的插件，例如instant markdown，点击install便可安装

![](https://work.mafengshe.com/static/upload/article/pic1561728129103.jpg)

### 卸载
1. 查看已经安装的插件

![](https://work.mafengshe.com/static/upload/article/pic1561728202252.jpg)

2. 找到想卸载的插件，点击设置按钮，选择uninstall便可卸载

![](https://work.mafengshe.com/static/upload/article/pic1561728296692.jpg)

## git集成

打开分支按钮，可以看到修改前后的对比

![](https://work.mafengshe.com/static/upload/article/pic1561728767581.jpg)

点击对号符号，可以进行提交；点击更多按钮可以进行push、pull等更多git操作。
