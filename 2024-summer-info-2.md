# 2024uestc-se开源操作系统训练营第二阶段环境配置与学习资料
原文链接来自[清华大学开源操作系统训练营](https://github.com/LearningOS/rust-based-os-comp2024/blob/main/2024-spring-scheduling-2.md)

#### 课程参考
- [课程幻灯片](https://www.yuque.com/docs/share/4c39608f-3051-4445-96ca-f3c018cb96c7)
- 参考书
  - [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)
  - [深入了解计算机系统](https://hansimov.gitbook.io/csapp/)
  - [RISC-V Reader中文版](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf)
#### 课程实践：rCore Tutorial Book v3
-  [课程实践参考书](https://learningos.github.io/rCore-Tutorial-Book-v3/)
-  [课程实践代码仓库](https://github.com/rcore-os/rCore-Tutorial-v3)
-  [课程实践代码的API文档](https://github.com/rcore-os/rCore-Tutorial-v3#os-api-docs)

#### 基于Rust语言的rCore Tutorial实验指导（做题最重要的文档资料！！！）
- [实验文档](https://learningos.github.io/rCore-Tutorial-Guide-2024S/)
- [API文档](https://github.com/LearningOS/rCore-Tutorial-Guide-2024S/#os-api-docs-of-rcore-tutorial-code-2022s) 
- [实验代码](https://github.com/LearningOS/rCore-Tutorial-Code-2024S)
- [测试用例](https://github.com/LearningOS/rCore-Tutorial-Test-2024S)

#### 自学材料和练习要求:

1. 阅读书籍和在线课程

   - 自学[PPT for RISC-V特权指令级架构](https://content.riscv.org/wp-content/uploads/2018/05/riscv-privileged-BCN.v7-2.pdf)
   - 自学[RISC-V手册：一本开源指令集的指南](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf) 重点是第10章
   - （Option）自学[RISC-V特权指令级规范](https://riscv.org/technical/specifications/) 重点是与OS相关的特权硬件访问的规范内容（Privileged Spec）
   - （Option）自学[RISC-V汇编手册](https://github.com/riscv-non-isa/riscv-asm-manual/blob/master/riscv-asm.md)
   - （Option）[计算机组成与设计：RISC-V 教材](https://item.jd.com/12887758.html) 这是完整的课程教材，不要求全部看完，请根据自己的需求选择。
   - （Option）[计算机组成与设计：RISC-V 浙大在线课程](http://www.icourse163.org/course/ZJU-1452997167) 这是完整的一门课，不要求全部看完，请根据自己的需求选择。

2. 其他参考学习信息

   - （Option）[Berkeley CS61C: Great Ideas in Computer Architecture (Machine Structures)](http://www-inst.eecs.berkeley.edu/~cs61c/sp18/)

   > Option的含义是：如果有足够的时间建议看看，否则在后续要用到时或需要查询进一步信息时再查阅这些内容。

## 重要提示！！！
- 做题仓库里面同样也给出了精简版和详细版实验文档，精简版文档是针对题目lab的，而详细文档是涵盖了更全面的知识点，根据你的时间以及兴趣程度做调整。
- 从第3章开始才有需要写的题目，题目章节是ch3、4、5、6、8共5个，但是中间1、2、7章建议同样仔细阅读，最好跟着把代码敲一遍
- 仔细浏览仓库的readme，明白它写的shell 命令的含义
- 不排斥上网络查找题目资源，但是一定要懂，并且最好是实在找不出问题的时候再依赖别人的答案，最终考核结果并不只是最后分数，同时做完的同学也可以尝试完成思考题。