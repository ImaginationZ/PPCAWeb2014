#ACM班级网页修改策划方案
—— By 柏钧文 陈昕昀 李佳骏 徐亦飞

<!--
一、网站建设目标 
	1.1 网站目标与期望  
	1.2 网站设计原则
	1.3解决方案

二、风格

三、各部分的具体改造方案

- 综述
- ACM主页
- ACM班介绍
- 课程中心
	- Online Judge系统
- 学术中心
- 活动中心
- 招生信息
-->

##一、网站改造目标

###1.1 网站目标与期望

- 改造现有的ACM班班级主页，整合当前较为杂乱的分类，处理样式与内容陈旧、布局不合理等现象。以此提升ACM班对外的宣传能力。

- 建立一个方便且功能准确的平台。使得浏览网站的人更容易获取有效信息，使用课程中心进行课程管理时更加便捷，并突出ACM班新闻宣传的及时性和分类准确性。

- 突出ACM班的“继承”性质，丰富网页设计思路，为后续的改造者做好铺垫。

###1.2 网站改造原则

- 功能性原则

	ACM班班级主页是功能性主页，在改造工程中，须保证基本的功能的展示。班级主页的设计基础是向阅读者反应有效信息并以此达到宣传ACM班，让外界了解ACM班的目的。

- 艺术性原则
	
	须充分反映ACM班学子的文艺气质与修养内涵。版面设计尤其是主页设计，一定要炫酷，但不要花哨。网站需充分反映ACM班的内涵。

- 扩充性原则

	网站的整体规划及框架设计是具可扩充性的，页面的设计需保证网站在增加栏目后不会破坏网站的整体结构。后台的设计也应如此，后续的维护者可以根据需要，对栏目、类别进行增、删或修改。

##二、全新的页面风格

###2.1 风格的统一化

>目前的ACM班级主页有三大部分组成，主页部分，课件中心和OJ系统，三大部分风格迥异，不成体系。

于是我们需要进行风格的统一化，一个统一的风格有助于提升网站的整体完整性，规范性。

具体风格有以下三个要素：

- 顺应扁平化发展潮流，向扁平化发展。

- 注意将内容置为主体，尽量缩小导航区域。

- 可行的话，拥有手机端的适配，自动适应宽度。

具体风格方案，有待进一步确定。

###2.2 令人耳目一新的主页

index是网站的门面，在它上面花上大工夫是值得的，具体方案参见  *3.2节*

###2.3 下拉菜单的应用

下拉菜单已被大部分网站应用，（参见[致远学院官网](http://zhiyuan.sjtu.edu.cn)），使用下拉菜单有助于更紧凑的调整页面，将次级标题放入下拉菜单后，能够节约目前页面右边的空白，增加主体区域。

###2.4 更多图片素材的加入

目前ACM的班级主页图片远远不够，需要更多的图片加入不同的页面，例如，教师介绍应该放上教师的图片，更多的活动图片，更多的集体照，更多的学术交流图等等。

- 课程中心的课程入口可以以图片为入口，例如这样：[教室查询系统](http://classroom.jwc.sjtu.edu.cn/)

- 教师介绍和花名册可以参考致远官网，这样：[教师介绍](http://zhiyuan.sjtu.edu.cn/teachers/computer)

- 活动中心以图片为主题，可以参考人人个人主页，这样：[个人主页](http://www.renren.com/725686138/profile)

在这里，有两个难点：

- 素材的来源可能有点难度。

- 加入图片后，框架风格可能需要修正。

##三、网站具体架构

###3.1 综述

* 在内容布局方面，整个网站分为班级介绍、课程中心、学术中心、活动中心、招生信息五个部分。

* 同时我们希望能够在整个网站内实现类似于十周年网页中的账户系统。课程中心中一些课件、具体教学安排尤其是一些联系方式不宜公开，账户系统不仅可以使一些信息私有化，也更方便于网站中很多内容的具体化，下述关于内容的布局很多也是基于这样一个系统。同时账户系统也是网站中一些交互功能实现的前提。

###3.2 主页

* 主页内容应体现ACM班的一些特色，用于对班级的介绍与宣传。

* 主页形式可以参考如下网页：  
  <a href="http://www.mi.com/note">小米手机官网</a>（中部)  
  即整个页面由几张大图进行拼接，每张大图展现ACM班的一个方面，在图的边上附加简短的**辅助性**文字介绍。

* 页面左侧可设计一个浮动的目录栏，就是将如下网页的目录栏改为浮动于左侧：  
  <a href="http://iiis.tsinghua.edu.cn/zh/yaoclass/">姚班主页</a>  
  但不希望像姚班主页一样将所有内容集中在一个页面上，这样显得过于冗长。

* 可以在主页上设置一个班级新闻的栏目，在其中插入一些连到最新更新的网页的超链接，比如关于最新的学术活动、学生获奖的报道等。

### 3.3 ACM班介绍

- ####班级介绍

	基本内容延续原课程主页。ACM班的大致介绍仍采用老板的文章。且置于默认页。其次，教育理念板块仍可以保留。但文章的分布格局与页面风格要依上一节做出相应改变。

- ####老师介绍

	由于ACM班的教学教师相对固定，因此可以给每个教师一个介绍专栏（包含主讲课程、个人经历等等）。教师的分类可以按照专业非专业来分，也可以按照年级来分。
 
- ####学子风采

	这一栏按照学生的年级进行分类，每一个年级的学生的花名册依照致远学院的来设计。但每个人的专栏内容可以扩充。样式排版也要与网页风格统一。可以在后期考虑是否要加入班委一栏介绍。

- ####荣誉榜

	这一栏的荣誉主要包括ACM竞赛所取得的成绩、ACM班同学发表的高质量论文获奖情况，以及一些其他ACM班集体或个人所得荣誉。

- ####ACM竞赛

	主要是历年ACM Final的战报，可以在原有的ACM竞赛专栏的基础上进行扩充，并补上近年来的几届报告。

### 3.4 招生信息

这一栏目需要与老板商量内容的设计，但这一栏目是必须的。目前讨论所得要添加的项目有招生简章、报名条件、招生政策等。

### 3.5 课程中心

- 课程中心的设计在内容上延续之前的版本，即各个年级的不同课程与不同年级的各个大作业按课程及年份分类。但页面布局要修改，修改方案参照上一节的设计风格。 

- 在之前的课程基础上，要添加一些例如数理逻辑、数学分析、计算机科学导论等栏目，栏目中可以放置一些老师推荐的bibliographies，电子教参，相关网站，助教联系方式，当周作业等等。

- 由于课程需要具有一定的保密性，我们需要考虑是否采用账户系统来限制访问权限

- 在适当的位置插入OJ的地址

### 3.6 学术中心

- ####科研成果

	这一栏中主要放一些重要的，具有非凡意义的，非常高质量的论文原稿或者网站链接，附带作者介绍。可以的话，可以附上作者写这篇论文所感所想。

	除了论文外，有一些在应用层面的科研成果也可以放置于其上，包括一些大型项目、工程，和它们的团队介绍。

- ####学术交流

	这一部分主要是一些交流活动的新闻介绍。例如，这一届大三的Connell University 访问交流学习，之前的教育部“拔尖计划”学生学术交流会，以及其他的一些交流项目的报道。

- ####学长讲坛

	这个栏目的内容可以分为两个部分。

	- 第一，优秀学长的个人介绍。如近期致远官网上“致远三期”优秀毕业生介绍，他们中的很多人是从ACM班走出去的，完全可以在本栏目中着重介绍。
	
	- 第二，学长有关学习、实习、工作的经验分享。例如上次的“学长去哪了”讲坛。此外还可以涉及一些有关GRE、TOFEL、留学事宜的Q&A。

- ####学术节

	这一部分主要包括每年举办一次的“学术节”的活动照片，优秀学长的介绍和研究方向介绍。此外，优秀论文的展示也是必不可少的。

- ####实习板块

	这一板块的内容有待后续讨论，是否开启主要取决于实习学长的信息共享度，如果效果不好的话，这个栏目可以去掉。

### 3.7 活动中心

>这一部分主要介绍有关ACM班比较轻松愉快、不那么学术的活动，包含的范围也可以扩充。

- ####体育节

	每年一度的体育节是ACM班同学的欢乐时刻，在这个活动中可以产生大量的新闻作品和优秀照片。

	内容的逻辑顺序按照时间顺序（按年份来）。但每年不同的活动可以归在一起，也可以各自独立。

	每年，体育节的整体安排可以直接放到网页的这一栏上，有关各个项目负责人的信息也可以放置于其上（包括联系方式等）。

	此外，还可以放上各个项目的实时战况积分表，增加竞争性。

- ####春游

	春游是每年各个班级都会组织的一项活动，参照体育节，春游活动的一些安排可以放到网上，包括一些投票系统（如果可以的话）。

	活动过程中的照片，经典，合影等都可以放上来。

	此外，还可以附上各个小组的联系电话，保证安全。

- ####信息学特长夏令营
	
	这主要是对每一年进行的夏令营的报道（如果有的话），这个页面也可以作为吸引小朋友报考ACM班的宣传工具

##附、网站地图

- ACM主页
	- 首页
	- ACM班介绍
		- 班级介绍
		- 教师介绍
		- 学子风采
			- 花名册
			- 集体照
		- 荣誉榜
		- ACM-ICPC
			- 介绍
			- 训练方式
	- 招生信息
		- 招生简章
		- 报名条件
		- 招生政策
	- 课程中心
		- 课程介绍
		- 课程平台
			- 作业发布
			- 课程大纲
			- 课程教案
			- 课程助教
		- Online Judge系统
	- 学术中心
		- 科研成果
		- 学术交流
		- 学长讲坛
		- 学术节
		- 实习版块
	- 活动中心
		- 体育节
		- 旅游旅游
		- 夏令营
