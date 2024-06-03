# WHU武汉大学中文简历模板
Made by 小红书 @虎生

## 版权与字体
本模板使用的字体为开源字体狮尾四季春，详见
https://github.com/max32002/swei-spring

## 致谢
本模板基于
1. [北师大中文CV模板](https://github.com/LeyuDame/BNUCV)
2. [西北工业大学中文CV模板](https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx)。这个西北工业大学的模板做得非常好，此模板基本上就是基于西工大的模板改了一些小地方。

主要改动包括：
1. 修改校标、配色、字体等；
2. 增加研究生对应模块；
3. 做了一些更契合个人习惯的改动（毕竟是自用模板）。

## 使用方法
1. 使用XeLaTeX编译。不成功的话可以试着多编译几次（之前的模板里这样说）。
2. 建议上传Overleaf编译。如果文件太大可以分几次上传。

## 其他注意事项
1. 所有以\fa开头的都是font awesome宏包里的logo。详细信息参考：[font awesome文档](https://mirrors.ibiblio.org/CTAN/fonts/fontawesome5/doc/fontawesome5.pdf)
2. 如何修改栏目名称？以个人信息为例。本模板中使用下述命令定义栏目名（即章节名）：```\section{\makebox[\widthof{\faAddressCard}][c]{\color{WHU_Blue}{\faAddressCard}}\quad 个人信息}```。```\faAddressCard```为font awesome中提供的图标。个人信息即章节名。其他如无必要可以不用管。
3. 我注释掉了一些我用不到的东西。如果你觉得有用，可以选中后按ctrl+/取消注释。
