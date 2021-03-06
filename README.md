# Towerdenfense
塔防游戏——Fantasy
一．项目说明
  Fantasy是我们设计的一个塔防游戏的桌面程序，主要利用Qt作为程序开发的框架。游戏规则与大部分塔防游戏相同，通过在地图上建造防御塔等建筑物，以阻止游戏中敌人进攻的策略型游戏，且我们设计多种形态和特性的防御塔和怪兽，和几个不同难度的地图，还加入了升级防御塔的功能，为整体游戏增加趣味性和耐玩性。


二．项目工具
版本控制：Git
开发环境：QT 5.9.0
编程语言：C++ 17
框架结构：MVVM


三．框架描述
  框架采用MVVM模式，分为View,View Model与Model层，View层主要负责Window的交互界面部分和有关显示部分的内容；View Model负责作为上下层的接口，和进行数据转换，在游戏中主要体现在按钮输入，防御塔攻击与升级，重生怪物与巡线，游戏路径分析等方面，Model层负责底层数据处理，在游戏中主要体现在怪物血量计算，防御塔相关数值，主塔生命值计算，怪物攻击波计算等数值设计方面。

四．实施方案
1.第一轮迭代：完成防御塔，主塔，子弹，怪物的基础设定和有关交互界面的设定
2.第二轮迭代：完成开始画面，选关画面，开始、选关功能，游戏声音
3.第三轮迭代：完成游戏画面，设计地图中的防御塔可放位置和怪物路线
4.第四轮迭代：完成剩余细小功能：删除防御塔，升级防御塔，怪物波次等
5.第五轮迭代：优化游戏细节，修复遇到的问题


五．项目分工：
View: 曾致语 ；View Model: 孙家阳；Model: 朱允怀
