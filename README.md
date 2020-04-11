# PyTex
PyTex用于简化Tex的编写。

## 特色功能
1. 提供了试卷编写模块，详情见pytex/exam/README.md。<br/>
2. 支持定义局部操作，例如在经常用到导数和积分的局部区域
将`\text{d}`定义为`\d`而不是`\dif`，而在其他区域
将`\dot`定义为`\d`，注意定义命令符时应尽量避免歧义，
例如若将`\text{d}`定义为`d`，则`ad`也会被错误识别。<br/>
3. 支持部分Markdown语法转LaTex。
4. 伪代码编写

## 计划实现功能
1. 神经网络结构可视化，输入处理形状变换可视化。
2. 更好地和symbol交互。

## 更新日志
- (2020.04.1) v0.1.1 发布
    - 修复了部分问题。
- (2020.04.08) v0.1.0 发布
    - 实现了DocTree，用于将dict转化为文档结构。
        
