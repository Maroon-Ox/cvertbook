# cvertbook
基于xelatex的中文直排书籍尝试，最终目标是排出一整部二十四史
使用，需要编译三次才能得到正确结果

## 已经完成的工作
- 基础的直排
- 直排的页眉与页脚
- 直排的单双页装订裁剪
- 英文基线校准
- 重写章节等标题与目录样式，因为改动较大舍弃了titlesec，titletoc等宏包而重写一遍\part等命令
- 因为二十四史有三千多卷，目录很长，搞了一个前置目录，即一个精确到\part级别的目录，用于指引到正常目录中的某部书，而正常目录要精确到卷(\chapter)
- 去除标点符号，标点符号变为不占位置的句读模式

## TODO
- 割注、行间注、头注等（不一定需要）
- 边栏
- 插入图片。

## 还有可能遇到的问题
- 奇怪的符号、异体字。
