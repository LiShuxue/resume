## 基本信息

姓名：李树雪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;性别：男

电话：15822472510&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;邮箱：1149926505@qq.com

学校：天津商业大学&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;专业：计算机科学与技术

工作年限：7 年&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;个人博客：https://lishuxue.site

&nbsp;

## 个人优势

1、承担团队技术项目攻坚工作，注重前端标准化，在多个项目中落地自己实现的前端工具

2、深入理解 Javascript 语言，对 Babel 编译，V8 运行机制等底层有一定了解

3、熟悉 Vue，React 等框架及其源码，熟悉 Typescript，能熟练运用开发项目

4、熟悉 Webpack，Vite 等前端工程化工具，能编写自定义 plugin 或 loader 来实现特定功能

5、熟悉 Nodejs，Koa，数据库等，可通过 Nodejs 开发后台 api 服务，也可开发一些 CLI 工具或中间件

6、了解 H5，小程序等移动端开发，了解原生开发和混合开发

&nbsp;

## 工作经历

2021.5--now&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;美团&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前端

2016.4--2021.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;渣打银行&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前端

&nbsp;

## 项目经验

### 美团优选&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;商家后台管理系统

**项目描述：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;商家端后台管理系统。这个系统主要是给运营人员使用，比如审核商家建的商品，排期上架，履约等等。技术栈是 Vue，使用基于 Element 二次封装的优选组件库，前后端分离的模式。

**项目角色：** 核心开发

**项目经验：**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;经过长达 2 年的快速开发迭代，项目的架构，代码已经很繁重。页面运行起来较为卡顿，尤其在低端电脑上，页面甚至卡成了幻灯片。因为业务非常复杂，直接就导致了页面代码异常臃肿，可读性差，容易出现线上事故，所以进行项目重构优化。

1. 整体架构：更加细致的拆分主体文件，项目配置 TS ，增强代码可维护性和可读性
2. 代码层面：有针对性的减少 data 字段，减少嵌套字段，来加速 vue2 代码的初始化，响应式等等。
3. 页面布局：单一性。尽量说服产品将业务逻辑不那么强的功能分开到不同页面，有效提高每个页面的加载速度和性能。

&nbsp;

### 美团优选&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;商家端小程序

**项目描述：**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;作为一个面向全国商家的小程序，商家端小程序承载了商家非常多关于商品的相关功能，比如：建/维品，审核，上/下架，排期，送货，履约等功能。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;同时作为业务复杂，功能多，用户多，DAU 超百万的小程序，如何合理的进行项目开发，维护迭代，项目配置，组织结构，代码开发等就显得非常重要。

**项目角色：** 核心开发

**项目经验：**

1. 日常开发，维护迭代，code-review，优化重构，技术方案选型等。

1. 小程序核心列表卡顿优化，列表分成 3 个列表，用 tab 来切换，卡顿问题排查以及优化。  
   作为使用量最多的页面，这个页面功能多，并且复杂，糅合了各种各样的筛选，各种各样的业务相关信息展示。项目运行到 22 年底，已经出现首屏加载时间一度到 5-8s 的情况。经过仔细调研排查之后，制定了详细的解决方案。
   1. 列表懒加载（之前进入第一个 tab 也会加载第二个 tab 数据）
   2. 列表加载数据缓存（已加载的列表不在重复加载，记住滚动距离等）
   3. 部分节点延迟加载（日历筛选项节点延迟渲染，一部分放在点击打开日历事件里渲染）
   4. 降低 setdata 次数（从最开始 200+，降低到 50 以下）

&nbsp;

### 美团优选&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前端代码质量度量平台

**项目描述：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;为应用提供全面、灵活、专业的质量度量与治理服务平台。  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. 链路全覆盖：支持在研发链路的全生命周期（本地提交，PR，发布，线上）进行质量度量和卡控。  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. 灵活自定义：项目可自由选用不同的度量规则（Lint 和非 Lint），卡控环节，卡控阈值等。  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. 开放规则市场：根据项目线上问题产生的规则，以及一些其他维度的规则，被发布到平台，其他团队可自由选用。如果不满足，也可以自己创建规则集，发布到市场，供所有团队选用。

**项目角色：** 核心开发

**技术：** ESLint 二次封装，ESLint 自定义插件，创建脚手架，Nodejs，数据库等

**项目难点：**

1. 跟现有的项目中直接配置 ESLint 有什么区别或优势？
2. 如何保证用户愿意使用且愿意解决分析出来的所有问题，如果问题较多，用户一般是抵触解决的？
3. 如何在不同的关键节点做卡控，且怎么保证确实卡控，用户如果强行跳过会不会有兜底？
4. 用户怎么能快速实现自己的规则？

**项目成果：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;目前共有 6 个团队接入，累计接入项目达 37 个，其中覆盖了不同的技术栈，如 vue，react，小程序等，也同时支持 Javascript 和 Typescript。  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;平均每天的提交卡控上百次，PR 检查且推送结果到群几十次，线上巡检每天扫描出代码问题高达上千个（待统一修复）。

&nbsp;

### 美团优选&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;废弃代码分析

**项目描述：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;随着项目迭代，一些历史页面或代码可能已经不再使用和维护。该工具可以分析代码仓库中的废弃代码文件，找出废弃页面，低流量页面，废弃文件，引用但未使用文件，无用代码块等。报表展示出来，推动各小组进行删除治理。

**项目角色：** Owner

**技术：** Babel 编译，AST 遍历，Nodejs 等

**项目难点：**

1. 怎么分析文件的依赖关系，依赖中遇见环怎么处理？
2. 怎么标识引用但未使用的文件，一个文件可能在 A 文件中引用了没有使用，但可能在 B 文件使用了。
3. 怎么寻找无用代码块？

**项目成果：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;共分析了优选商品终端的 26 个前端项目，累计分析出废弃文件上千，运营推动各小组都删除废弃文件，极大的减少了代码构建时间，包体积和文件数量等，本地启动时间，性能也显著提升。

&nbsp;

### 美团优选&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;用户信息采集 SDK

**项目描述：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;通过无侵入的埋点，定向采集用户在 PC 端操作过程中的数据，如进入页面 PV，页面某模块展示 MV，点击按钮 MC，发送请求 RQ，页面跳转链路 LK 等。根据采集到的数据，配置用户的关键动作链路监控，实现关键动作中断时的实时报警。

**项目角色：** Owner

**技术：** 前端监控，Service Worker，Typescript 等

**项目难点：**

1. 怎么采集关键数据，怎么上报？
2. 怎么做无侵入？
3. 怎么确定关键链路和监控复合指标？

**项目成果：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;优选商品终端共有 10 个重要项目接入该 SDK，每天累计监控线上用户几百个关键动作，累计发现十多次由于代码不健壮导致的用户行为中断，及时告警相关责任人，使其修复或回滚，避免了问题的扩大。

&nbsp;

## 个人总结

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;较强的学习能力，解决问题能力，以及执行力。工作中不管遇到什么疑难杂症都能很快的且顺利的解决。也在持续学习新的知识，来确保自己不被行业所落下。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;业余时间也开发了自己的[个人站点](https://lishuxue.site)，记录一些平时的学习笔记，分享给大家。对于不知道的也会刨根问底探究一下底层原理，机制。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在学生和工作阶段，都是比较优秀的，下面列了一些曾经的荣誉:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**大学期间**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[14 年一等奖学金](https://cdn.lishuxue.site/resume/images/2014yideng.jpeg)、[15 年一等奖学金](https://cdn.lishuxue.site/resume/images/2015yideng.jpeg)、[16 年一等奖学金](https://cdn.lishuxue.site/resume/images/2016yideng.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[14 年三好学生](https://cdn.lishuxue.site/resume/images/2014sanhao.jpeg)、[15 年三好学生](https://cdn.lishuxue.site/resume/images/2015sanhao.jpeg)、[16 年优秀毕业生](https://cdn.lishuxue.site/resume/images/youxiubiye.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[校级优秀团员](https://cdn.lishuxue.site/resume/images/youxiutuanyuan.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[中级软件设计师](https://cdn.lishuxue.site/resume/images/ruanjiansheji.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[C 语言二级](https://cdn.lishuxue.site/resume/images/c2ji.jpeg)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;励志奖学金

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**工作期间**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2017 年度最佳新人  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2018 年度最佳员工  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2019 年度最佳团队  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2020 年团队优秀员工  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2022 年优选终端春季之星](https://cdn.lishuxue.site/resume/images/zhongduanzhixing.png)
