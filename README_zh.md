# Awesome Electronics 中文版

> 电子工程师和爱好者的精选资源列表

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![English](https://img.shields.io/badge/English-README-blue)](README.md)

本项目是 [awesome-electronics](https://github.com/xfengyin/awesome-electronics) 的中文版本，旨在为中文用户提供更友好的电子工程资源导航。

**电子工程 (Electronic Engineering, EE)** 是理解、设计和构建电子电路的实践。与电气工程不同，电子工程主要处理低压直流电子电路，但两者之间有大量交叉领域。

电子电路的实验和构建也是一种流行的爱好，专业资源和爱好者资源往往同样适用。

---

## 目录

- [学习资源](#学习资源)
- [电路设计（原理图与PCB）](#电路设计原理图与pcb)
- [仿真与建模](#仿真与建模)
- [元器件库](#元器件库)
- [PCB制造](#pcb制造)
- [嵌入式开发](#嵌入式开发)
- [测试与测量](#测试与测量)
- [开源硬件](#开源硬件)
- [中文生态](#中文生态)

---

## 学习资源

### 技术教程
- [Sparkfun 学习中心](https://learn.sparkfun.com/tutorials/tags/skill) - 涵盖各种电子工程技术技能的广泛教程。
- [焊接很简单](https://mightyohm.com/blog/2011/04/soldering-is-easy-comic-book/) - 用漫画书讲解焊接基础知识，已翻译成多种语言。
- [烙铁头使用指南](https://www.instructables.com/id/Uses-of-Different-Soldering-Iron-Tips/) - 介绍各种烙铁头的用途。
- [如何为电子项目设计主板](https://www.staycaffeinated.com/2021/02/21/how-to-design-a-motherboard-for-your-project-part-1) - 原理图与PCB设计入门教程。

### 在线课程
- [Khan Academy - 电气工程](https://www.khanacademy.org/science/electrical-engineering) - 非营利学习平台，提供完整的电气工程课程。
- [NEETS (海军电子与电气培训系列)](https://www.fcctests.com/neets/Neets.htm) - 美国海军非驻校培训课程材料。
- [NPTEL](https://nptel.ac.in/course.html) - 免费工程课程，包括电子、电气和通信工程。
- [Udemy 电子相关课程](https://www.udemy.com/topic/electronics/) - Udemy 上的热门付费课程。
- [Coursera 电子相关课程](https://www.coursera.org/courses?query=electronics) - 包括一些免费课程，完成后可获得证书。

### 大学课程资源
- [Berkeley EECS](http://inst.eecs.berkeley.edu/classes-eecs.html) - 伯克利电子工程与计算机科学课程档案。
- [Dr. Jacob Baker 课程](http://cmosedu.com) - 内华达大学拉斯维加斯分校教授的课程和教程。

---

## 电路设计（原理图与PCB）

### 免费EDA软件
- [KiCad](https://kicad.org/) - 开源EDA软件，支持推挤布线器、差分对等功能。
- [Eagle](https://www.autodesk.com/products/eagle/overview) - 由于有限制条件的免费版本而成为最流行的EDA软件之一。
- [DesignSpark PCB](https://www.rs-online.com/designspark/pcb-software) - RS Components 赞助的无限功能免费EDA软件。
- [Altium CircuitMaker](https://circuitmaker.com/) - Altium 提供的免费软件。
- [gEDA](http://geda-project.org) - 另一个开源软件包，适合喜欢脚本和Makefile的用户。
- [DipTrace](https://diptrace.com) - 高质量原理图捕获和PCB设计软件（有引脚和信号层限制的免费版本）。
- [LibrePCB](https://librepcb.org/) - 新一代强大直观的EDA工具，跨平台。
- [Horizon EDA](https://github.com/horizon-eda/horizon) - 专注于快捷键操作的开源EDA工具。
- [EasyEDA](https://easyeda.com/) - 易用的在线和跨平台应用版本，集成 LCSC 和 JLCPCB 元器件目录。

### 付费EDA软件
- [Altium](https://www.altium.com/) - 专业PCB设计软件。
- [Proteus](https://www.labcenter.com/) - PCB设计和电路仿真软件。

### CAD特定资源

#### KiCad
- [KiCad 第三方工具列表](https://github.com/xesscorp/kicad-3rd-party-tools)
- [KiCad 论坛](https://forum.kicad.info) - 用户讨论和帮助论坛。
- [KiCad 速查表](https://silica.io/wp-content/uploads/2018/06/kicad-cheatsheet.pdf) - 常用操作快捷键速查。
- [封装收集](https://github.com/kitspace/kicad_footprints) - 所有在线可用KiCad封装的收集。

---

## 仿真与建模

### 模拟和混合信号电路仿真器
- [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) - 来自Linear Technologies的行业标准免费SPICE电路仿真器。
- [ngspice](http://ngspice.sourceforge.net/) - 开源SPICE电路仿真器。
- [Circuit JS/Falstad](http://www.falstad.com/circuit/circuitjs.html) - 免费开源在线仿真器，带电子流动画。
- [EveryCircuit](https://everycircuit.com) - 免费在线可视化交互电路仿真器，适合简单电路。
- [Qucs](http://qucs.sourceforge.net/) - 开源、跨平台、非SPICE仿真器，支持S参数和谐波平衡。
- [TINA-TI](http://www.ti.com/tool/TINA-TI) - 德州仪器的TINA版本，捆绑了TI模型。
- [Proteus](https://www.labcenter.com/) - PCB设计和电路仿真软件。

### Gerber查看器

#### 在线
- [Tracespace Viewer](https://tracespace.io/) - Gerber查看器，可检查各层和PCB预览。
- [Gerblook](https://www.gerblook.org/) - 由Gerbv驱动的在线Gerber查看器。

#### 可安装
- [Gerbv](http://gerbv.geda-project.org/) - 适用于Linux和BSD的优秀Gerber查看器。
- [KiCAD Gerbview](https://kicad.org/) - KiCAD的Gerber查看器。

---

## 中文生态

### EDA工具（国产）
- [立创EDA (LCEDA)](https://lceda.cn/) - 免费在线EDA工具，集成元器件库，在国内非常流行。
- [EasyEDA](https://easyeda.com/) - 基于浏览器的EDA工具，支持中文界面，集成LCSC。

### PCB制造（国产）
- [嘉立创 (JLCPCB)](https://jlcpcb.com/) - 低成本PCB制造和SMT贴装服务，全球流行。
- [捷配 (PCBAOK)](https://www.jiepei.com/) - 国内PCB制造和PCBA服务。
- [华秋DFM](https://www.hqdfm.com/) - 免费DFM分析工具和PCB制造。

### 元器件分销（国产）
- [立创商城 (LCSC)](https://www.lcsc.com/) - 国内主要元器件分销商，价格有竞争力。
- [云汉芯城 (ICZOOM)](https://www.iczoom.com/) - 国内最大的元器件分销商之一。
- [硬之城](https://www.allparts.cn/) - 国内元器件搜索引擎和分销商。

### 学习平台（中文）

#### B站UP主
- [硬件工程师炼成记](https://space.bilibili.com/) - 专业电子教程。
- [趣玩电子](https://space.bilibili.com/) - 电子项目和教程。
- [杜洋工作室](https://space.bilibili.com/25036806) - DIY电子和嵌入式教程。

#### 国产MCU资源
- [兆易创新 (GD32)](https://www.gd32mcu.com/) - 国产ARM Cortex-M MCU，STM32的替代品。
- [沁恒 (WCH)](https://www.wch.cn/) - 国产MCU，专注于USB和以太网（CH32系列）。
- [灵动微 (BLM)](https://www.bluenrg.com/) - 国产ARM Cortex-M MCU。

---

## 社区

### 博客
- [Hackaday](https://hackaday.com) - 最受欢迎的电子和硬件黑客博客。
- [Bunnie Studios](https://www.bunniestudios.com) - Bunnie Huang涵盖硬件黑客、开源硬件、制造等。
- [Bald Engineer](https://www.baldengineer.com) - James Lewis的电子和嵌入式软件项目日志和教程。

### 论坛
- [EEVBlog论坛](https://www.eevblog.com/forum/) - 最大的电子工程讨论论坛。
- [Reddit /r/electronics](https://www.reddit.com/r/electronics/) - 最活跃的电子子reddit。
- [电子技术问答](https://electronics.stackexchange.com) - 基于Stack Overflow的电子技术问答网站。

### 视频
- [EEVblog](https://www.youtube.com/user/EEVblog) - Dave Jones的拆解、教程等。
- [BigClive](https://www.youtube.com/user/bigclivedotcom) - 拆解（包括危险产品）、电路逆向工程和教程。
- [ElectroBOOM](https://www.youtube.com/user/msadaghd) - 用大量喜剧元素解释电子工程主题。
- [Ben Eater](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU) - 用面包板构建8位计算机的系列视频。

---

## 贡献指南

欢迎提交新的资源！请查看 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何贡献。

---

## 许可证

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者已放弃本作品的所有版权和相关权利。
