# 计算机组成原理课程设计

By Nihileon & Columbine1999

## 设计目的

1. 融会贯通计算机组成原理课程各章节的内容。

- 通过知识的综合运用，加深对 CPU 各模块工作原理及相互联系的认识，特别是对硬布线控制器的认识。

- 建立清晰的整机概念。

1. 掌握非流水与流水硬布线控制器的设计方法。
2. 学习运用可编程逻辑技术进行逻辑设计和调试的基本步骤和方法。
3. 培养科学研究能力，取得设计和调试的实践经验。

## 分析

1. 根据课本上的指令系统和 TEC-8 的数据通路，在 EPM7128SLC84-15N 芯片上编写一个硬布线控制器，实现以下的基本功能：
1. 能够正确读写寄存器。
2. 可以在任意位置读写存储器。
4. 可以分析指令各个节拍的作用，并能操作硬件实现指令功能。
1. 在完成基本功能的前提下，实现指令多级流水，提高指令执行效率。
2. 拓展指令集，让机器能够运行更多指令。
3. 实现取指阶段的指针，让机器能够在任意位置开始执行指令。
4. 在当前机器上设计单级中断方案。

## 注意

###### ⚠️ 这种编码方法极其诡异，BUG 频发

###### ⚠️ TEC-8 实验箱的BUG 远比代码的要多，请认准经过开光的 15016 和 15081 号箱子，选了课程设计而又没有找到这俩箱子的同学请保重。

###### ⚠️ TEC-8 数据通路本身就有问题，如果遇到了不可调解的 BUG，请不要砸墙，不要骂街，一定要稳住自己的心情，在嘴里不停地小声念叨："佛祖保佑，上帝保佑，马克思保佑🙏。"

**地狱空荡荡，BUG 在人间。**

