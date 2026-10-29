# 11



今年开始把工作里的一些想法做成产品。说实话，我对行业里使用AI这件事一直有些感触：国知局和企业都在积极使用AI，到了代理师这里，用AI辅助反而有点不方便摆到台面上说。一旦客户知道用了AI，就容易觉得工作量少了，收费也应该降。可专利撰写真正值钱的部分，难道只是敲了多少字、花了多少小时吗？

下面这两个项目，一个来自我的工作，一个来自我自己备考的需要。

## TTC：这两个月一直在改的AI专利撰写工具

做专利时，交底材料拿到手，后面还有很多判断要做。技术方案怎么理解，哪些内容值得保护，权利要求写到什么程度，这些都会影响后面的稿子。

TTC把这个过程分成几步，AI先整理和起草，代理师可以查看、修改，确认后再继续。我主导需求、流程和开发迭代，借助AI编程工具实现；一位行业经验更丰富的伙伴参与专业规则的测试和优化。

花时间最多的是权利要求的质量控制。最早用固定工作流，后来发现有些问题需要回查材料、重新判断，就引入了Agent。试下来又发现，给它更多自主步骤、让它写更细的审核报告，也不一定能把稿子改好。现在是一边看实际结果，一边调整哪些交给模型、哪些由程序处理、哪些还得请人确认。

这段过程我单独写了下来：[做TTC的这两个月](https://github.com/orphanwarrior/028-ttc-showcase/blob/main/docs/PRODUCT_CASE_STUDY.md)。

![TTC 案件工作台](https://raw.githubusercontent.com/orphanwarrior/028-ttc-showcase/main/assets/screenshots/workbench.jpg)

*实际应用界面，截图用的是单独准备的测试材料和模拟模型。*

TTC已经可以通过公网访问，目前邀请制内测。源码和专业规则暂时放在私有仓库，公开仓库里有介绍、截图和实现说明。

用到的主要技术是Next.js、React、TypeScript、SQLite和大模型HTTP接口。

[看看 TTC](https://github.com/orphanwarrior/028-ttc-showcase) · [界面和操作](https://github.com/orphanwarrior/028-ttc-showcase/blob/main/docs/DEMO_WALKTHROUGH.md)

## 专利代理师考试学习系统

这是之前准备代理师考试时做的，也给同事内部用过。当时想有个不用买题库会员、打开就能练题的小工具，就做了这个网页。

可以随机出题、看解析，错题和收藏会留下来，方便回头再做。没有注册和登录，学习记录保存在当前浏览器，换设备不会同步。

用HTML、CSS和JavaScript做的，放在GitHubPages上，可以直接试。

[打开练习系统](https://orphanwarrior.github.io/test-web/study.html) · [项目介绍和代码](https://github.com/orphanwarrior/test-web)
