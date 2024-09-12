# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm280本科生导师指导平台+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1gn8XeNE2J?p=77)


# 系统概述
1.1 研究背景

如今互联网高速发展，网络遍布全球，通过互联网发布的消息能快而方便的传播到世界每个角落，并且互联网上能传播的信息也很广，比如文字、图片、声音、视频等。从而，这种种好处使得互联网成了信息传播的主要途径，社会上各种各样的信息都想尽办法通过互联网进行传播，互联网对社会产生的影响越来越大。

随着计算机技术的发展以及计算机网络的逐渐普及，互联网成为人们查找信息的重要场所，二十一世纪是信息的时代，所以信息的交换和信息流通显得特别重要。因此，开发合适的本科生导师指导平台成为企业必然要走的一步棋。开发合适的本科生导师指导平台，可以方便管理人员对本科生导师指导平台的管理，提高信息管理工作效率及查询效率，有利于更好的为学生提供服务。

1.2研究目的

随着互联网技术的快速发展，网络时代的到来，网络信息也将会改变当今社会。各行各业在日常企业经营管理等方面也在慢慢的向规范化和网络化趋势汇合。本科生导师指导平台的信息化程度体现在将互联网与信息技术应用于经营与管理，以现代化工具代替传统手工作业。无疑，使用网络信息化管理使信息管理更先进、更高效、更科学，信息交流更迅速。

企业如果还用之前的人工记账形式的管理，已经很落伍了，这样会导致了效率低下。而且，时间一长的话，积累下来的数据信息不容易保存，对于查询、更新还有维护会带来不少问题。对于数据交接也存在很大的隐患。如果采用电子化的存储方式就会带来很大的改善，而且给学生的查询带来了很大便利，因此设计一个本科生导师指导平台刻不容缓，能够提高企业在信息技术方面的展示水平。
## 1.3系统设计思想
一个成功的网站应明确建设网站的目的，确定网站的功能，确定网站规模、投入费用，进行必要的市场分析等。只有详细的策划，才能避免在网站建设中出现的很多问题，使网站建设能顺利进行。同时，一个大型的计算机网站系统，必须有一个正确的设计指导思想，通过合理选择数据结构、网络结构、操作系统以及开发环境，构成一个完善的网络体系结构，才能充分发挥计算机信息管理的优势。根据现实生活中网民的实际需求，本系统的设计按照下述原则进行。

1. 有效性：实际上这里的有效性包括两个方面的意思：有用性和可用性。有用性是指站点潜在的能满足学生需求的功能，而可用性是指能够通过站点的操作实现特定的目标。可以看出一个站点如果不能恰当运行或设计得非常槽糕就不是一个好站点。可用站点的效益应该非常高，并易于学习，在实现学生目标时令人满意而不出错。
1. 高可靠性：一个实用的网站同时必须是可靠的，本设计通过合理而先进的网络设计以及软、硬件的优化选型，可保证网站的可靠性与容错性。
1. 高安全性：在设计中，将充分利用网络软、硬件提供的各种安全措施，既可以保证学生共享资源，充分考虑系统及数据资源的容灾、备份、恢复的要求。为系统提供强大的数据库备份工具。可以保证关键数据的安全性。操作权限级，设置不同的角色确保每一步的操作权限，可以由管理员进行设置。
1. 先进性：采用目前国际上最先进的开发技术，使用JSP开发技术，MYSQL作为网站后台数据库。采用这些技术降低了以后的系统运营成本，提高了系统的稳定性和易维护性。
1. 采用标准技术：本网站的所有设计遵循国际上现行的标准进行，以提高系统的开放性。
1. 外观和技术平衡：系统采用Web风格的界面设计，界面友好、美观，使用方便，易学易用。网站设计的关键问题是外观和技术的平衡。外现不好的网站令人厌烦，站点可以运行很好，但却不能带动学生积极性，相反，如果外观非常有表现力，但技术有限，学生则会感到非常失望。在外观与技术之间需要确定一个清晰而连续的关系，即外观与站点的意图相关，对不同类型的网站处理方法不同。



# 2相关技术
## 2.1 MYSQL数据库
MySQL是一个真正的多学生、多线程SQL数据库服务器。 是基于SQL的客户/服务器模式的关系数据库管理系统，它的有点有有功能强大、使用简单、管理方便、安全可靠性高、运行速度快、多线程、跨平台性、完全网络化、稳定性等，非常适用于Web站点或者其他应用软件的数据库后端的开发工作。此外，学生可利用许多语言编写访问MySQL数据库的程序。作为开放源代码运动的产物之一，MySQL关系数据库管理系统越来越受到人们的青睐，应用范围也越来越广。速度和易用性使MySQL特别适用于Web站点或应用软件的数据库后端的开发工作。

MYSQL数据库具有以下特点：

1、C和C ++中使用和测试，以确保源代码的编译器的便携性和灵活性。

2、支持多种操作系统AIX的，FreeBSD下，HP-UX，Linux和Mac OS中，Novell公司的Netware，OpenBSD系统，OS/2裹时，Solaris，Windows等。

3、提供了用于不同的编程语言的API。编程语言，如C,, C ++，Python和Java的，的Perl，PHP，埃菲尔铁塔，Ruby和Tcl的。

4、以及使用的CPU资源来支持多线程。

5、算法优化查询SQL，切实提高搜索速度。

6、网络上的客户端和服务器可以用来编程任何独立的编程环境，也有中国，GB2312，BIG5，日文写作，一般基金，用于支持多国语言，并且可以嵌入在数据表和其他软件shift\_jis访问柱可以用作的名称。

7、TCP / IP，ODBC和JDBC数据库，并提供连接到其他。

8、管理工具的管理，控制和优化数据库的操作。

9、可以数以千万计的记录在一个大的数据库。
## 2.2 B/S结构
B/S架构是一种基于互联网系统的软件系统开发架构，是现如今在软件系统开发中采用非常大量的一种软件系统结构。现如今B/S架构已经被大量使用，打破了C/S结构的结构，给基于网络结构的软件系统提供了良好的支持。B/S架构伴随着计算机网络技术发展而逐步的发展和更新。伴随着互联网的进一步发展，就要求大多数的管理系统要求不仅仅可以在一台电脑上使用，同时可以在接入互联网的其他电脑也可以使用对系统进行操作和使用。在这样的背景下基于B/S架构的软件系统设计方法得到了越来越大量的使用，基础部分也在不断的更新。

B/S架构是利用操作系统中的浏览器来进行使用的，不是一种窗体软件系统，不需要在使用系统的电脑上进行安装。B/S架构的运行方式是在远程的服务器上把开发的软件系统部署在远程的服务器上，在部署好软件系统之后就可以实现在任何接入互联网的电脑上访问部署好的软件系统。B/S架构给使用管理系统的学生带来极大的便利。

在三层体系结构的B/S（Browser/Server，浏览器/服务器结构）系统中，学生可以通过浏览器向分布在网络上的众多服务器发出请求。B/S系统极大地简化了客户机的工作量，客户机上只需要安装、配置少量的客户端运行软件即可，服务器将担负大量的工作，对数据库的访问以及应用程序的执行都将由服务器来完成。

B/S架构的不断成熟，主要使用WWW浏览器技术，结合多种浏览器脚本语言，用通用浏览器需要实现原本复杂的专有软件来实现的强大功能，并节约了开发成本，是一种新的软件架构。B/S系统包括：表示逻辑层，控制逻辑层，数据展现层，三层是相对独立又相互关联。
## 2.3 SSM框架简介
SSM框架，是Spring+Spring MVC+MyBatis的缩写，这个是继SSH之后，目前比较主流的Java EE企业级框架，适用于搭建各种大型的企业级应用系统。

1.Spring简介

Spring是一个开源框架，Spring是于2003年兴起的一个轻量级的Java开发框架，由Rod Johnson在其著作Expert One-On-One J2EE Development and Design中阐述的部分理念和原型衍生而来。它是为了解决企业应用开发的复杂性而创建的。Spring使用基本的JavaBean来完成以前只可能由EJB完成的事情。然而，Spring的用途不仅限于服务器端的开发。从简单性、可测试性和松耦合的角度而言，任何Java应用都可以从Spring中受益。简单来说，Spring是一个轻量级的控制反转（IoC）和面向切面（AOP）的容器框架。

A.控制反转（IOC）是什么呢？

IOC:控制反转也叫依赖注入。利用了工厂模式将对象交给容器管理，你只需要在spring配置文件总配置相应的bean，以及设置相关的属性，让spring容器来生成类的实例对象以及管理对象。在spring容器启动的时候，spring会把你在配置文件中配置的bean都初始化好，然后在你需要调用的时候，就把它已经初始化好的那些bean分配给你需要调用这些bean的类（假设这个类名是A），分配的方法就是调用A的setter方法来注入，而不需要你在A里面new这些bean了。

B.面向切面(AOP)又是什么呢？

首先，需要说明的一点，AOP只是Spring的特性，它就像OOP一样是一种编程思想，并不是某一种技术,AOP可以说是对OOP的补充和完善。OOP引入封装、继承和多态性等概念来建立一种对象层次结构，用以模拟公共行为的一个集合。当我们需要为分散的对象引入公共行为的时候，OOP则显得无能为力。也就是说，OOP允许你定义从上到下的关系，但并不适合定义从左到右的关系。例如日志功能。日志代码往往水平地散布在所有对象层次中，而与它所散布到的对象的核心功能毫无关系。在OOP设计中，它导致了大量代码的重复，而不利于各个模块的重用。将程序中的交叉业务逻辑（比如安全，日志，事务等），封装成一个切面，然后注入到目标对象（具体业务逻辑）中去。

实现AOP的技术，主要分为两大类：一是采用动态代理技术，利用截取消息的方式，对该消息进行装饰，以取代原有对象行为的执行；二是采用静态织入的方式，引入特定的语法创建“方面”，从而使得编译器可以在编译期间织入有关“方面”的代码。

2.Spring MVC简介

Spring MVC属于Spring Framework的后续产品，已经融合在Spring Web Flow里面，它原生支持的Spring特性，让开发变得非常简单规范。Spring MVC分离了控制器、模型对象、分派器以及处理程序对象的角色，这种分离让它们更容易进行定制。

3.MyBatis简介

MyBatis本是apache的一个开源项目iBatis,2010年这个项目由apache software foundation迁移到了google code，并且改名为MyBatis。MyBatis是一个基于Java的持久层框架。iBATIS提供的持久层框架包括SQL Maps和Data Access Objects（DAO）MyBatis消除了几乎所有的JDBC代码和参数的手工设置以及结果集的检索。MyBatis使用简单的XML或注解用于配置和原始映射，将接口和Java的POJOs（Plain Old Java Objects，普通的Java对象）映射成数据库中的记录。可以这么理解，MyBatis是一个用来帮你管理数据增删改查的框架。


# 3系统分析
## 3.1可行性分析
通过对本本科生导师指导平台实行的目的初步调查和分析，提出可行性方案并对其一一进行论证。我们在这里主要从技术可行性、经济可行性、操作可行性等方面进行分析。
### 3.1.1技术可行性
本本科生导师指导平台采用JAVA作为开发语言，Spring Boot框架，是基于WEB平台的B/S架构系统。

（1）Java提供了稳定的性能、优秀的升级性、更快速的开发、更简便的管理、全新的语言以及服务。整个系统帮学生做了大部分不重要的琐碎的工作。

（2）基于B/S模式的系统的开发已发展日趋成熟。

（3）众所周知，Java是面向对象的开发语言。程序开发员可以在Eclipse平台上面方便的使用一些已知的解决方案。    

因此，本科生导师指导平台在开发技术上具有很高可行性，且开发人员掌握了一定的开发技术，所以此系统的开发技术具有可行性。
### 3.1.2经济可行性
本本科生导师指导平台采用的软件都是开源的，这样能够削减很多的精力和资源，降低开发成本。同时对计算机的配置要求也极低，即使是淘汰下来的计算机也能够满足需要，因此，本系统在经济上是完全具有可行性的，所以在经济上是十分可行的。
### 3.1.3操作可行性
本本科生导师指导平台的界面简单易操作，学生只要平时有在用过电脑，都能进行访问和操作。本系统具有易操作、易管理、交互性好的特点，在操作上是非常简单的，因此在操作上具有很高的可行性。

综上所述，此系统开发目标已明确，在技术、经济和操作方面都具有很高的可行性，并且投入少、功能完善、管理方便，因此系统的开发是完全可行的。
## 3.2系统性能分析
### 3.2.1 系统安全性
此本科生导师指导平台要严格控制管理权限，具体要求如下：

（1）要想对本科生导师指导平台进行管理，首先要依靠学生名和密码在系统中登陆，无权限的学生不可以通过任何方式登录系统和对系统的任何信息和数据进行查看，这样可以保证系统的安全可靠性和准确性。

（2）在具体实现中对不同的权限进行设定，不同权限的学生在系统中登陆后，不可以越级操作。
### 3.2.2 数据完整性
（1）所有记录信息要保持全面，信息记录内容不可以是空。

（2）各种数据间相互联系要保持正确。

（3）相同数据在不同记录中要保持一致。

3.3系统界面分析

目前，界面设计已经成为对软件质量进行评价的一条关键指标，一个好的学生界面可以使学生使用系统的信心和兴趣增加，从而使工作效率提高，JSP技术是将JAVA语言作为脚本语言的，JSP网页给整个服务器端的JAVA库单元提供了一个接口用来服务HTTP的应用程序。创建动态页面比较方便。客户界面是指软件系统与学生交互的接口，往往涵盖输出、输入、人机对话的界面格式等。

1.输出设计

输出是由电脑对输入的基本信息进行解决，生成高质量的有效信息，并使之具有一定的格式，提供给管理者使用，这是输出设计的主要责任和目标。

系统开发的过程与实施过程相反，并不是从输入设计到输出设计，而是从输出设计到输入设计。这是由于输出表格与使用者直接相联系，设计的目的应当是确保使用者可以很方便的使用输出表格，并且可以将各部门的有用信息及时的反映出来。输出设计的准绳是既要整体琢磨不同管理层的所有需要，又要简洁，不要提供给学生不需要的信息。

2.输入设计

输入数据的收集和录入是比较麻烦的，需要非常多的人力和一定设备，而且经常出错。一旦输入系统的数据不正确，那么处理后的输出就会扩大这些错误，因此输入的数据的准确性对整个系统的性能起着决定性意义。

输入设计有以下几点原则：

1）输入量应尽量保持在能够满足处理要求的最低限度。输入量越少，错误率就会越少，数据的准备时间也越少。

2）应尽可能的使输入的准备以及输入的过程进行时比较方便，这样使错误的发生率降低。

3）应尽量早检查输入数据（尽量接近原数据发生点）,以便使错误更正比较及时。

4）输入数据尽早地记录成其处理所需的形式，以防止数据由一种介质转移到另一种介质时需要转录而可能发生的错误。
## 3.4系统流程和逻辑
![](/md/blog.001.png)

图3-3登录流程图

![](/md/blog.002.png)

图3-4修改密码流程图

# 4系统概要设计
## 4.1概述
本系统采用B/S结构(Browser/Server,浏览器/服务器结构)和基于Web服务两种模式，是一个适用于Internet环境下的模型结构。只要学生能连上Internet,便可以在任何时间、任何地点使用。系统工作原理图如图4-1所示：

![](/md/blog.003.png)

图4-1系统工作原理图
## 4.2系统结构
本系统是基于B/S架构的网站系统，设计的功能结构图如下图所示：

![](/md/blog.004.png)

图4-2功能结构图

## 4.3.数据库设计
### 4.3.1数据库实体
概念设计的目标是设计出反映某个组织部门信息需求的数据库系统概念模式，数据库系统的概念模式独立于数据库系统的逻辑结构、独立于数据库管理系统（DBMS）、独立于计算机系统。

概念模式的设计方法是在需求分析的基础上，用概念数据模型（例如E-R模型）表示数据及数据之间的相互联系，设计出反映学生信息需求和处理需求的数据库系统概念模式。概念设计的目标是准确描述应用领域的信息模式，支持学生的各种应用，这样既容易转换为数据库系统逻辑模式，又容易为学生理解。数据库系统概念模式是面向现实世界的数据模型，不能直接用于数据库系统的实现。在此阶段，学生可以参与和评价数据库系统的设计，从而有利于保证数据库系统的设计与学生的需求相吻合。在概念模式的设计中，E-R模型法是最常见的设计方法。本系统的E-R图如下图所示：

1. 老师评价信息的实体属性图如下：

![](/md/blog.005.png)

图4.12 老师评价信息实体属性图

（2）班级实体属性图如图4.13所示：

![](/md/blog.006.png)

图4.13   班级实体属性图

（3）导师组实体属性图如图4.14所示：

![](/md/blog.007.png)

图4.14 导师组实体属性图
### 4.3.2数据库设计表
本科生导师指导平台需要后台数据库，下面介绍数据库中的各个表的详细信息：

表4.1 班级

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|banji|varchar(200)|是|NULL|班级|
表4.2 导师

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|daoshizhanghao|varchar(200)|否||导师账号|
|mima|varchar(200)|否||密码|
|daoshixingming|varchar(200)|否||导师姓名|
|xingbie|varchar(200)|是|NULL|性别|
|zhicheng|varchar(200)|是|NULL|职称|
|shouji|varchar(200)|是|NULL|手机|
|youxiang|varchar(200)|是|NULL|邮箱|
|daoshizu|varchar(200)|是|NULL|导师组|
|yanjiufangxiang|varchar(200)|是|NULL|研究方向|
|yanjiufangxiangjieshao|longtext|是|NULL|研究方向介绍|
|gerenjianjie|longtext|是|NULL|个人简介|
|xueshuchengguo|varchar(200)|是|NULL|学术成果|
|zhaopian|varchar(200)|是|NULL|照片|
表4.3 导师选择列表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|daoshizhanghao|varchar(200)|是|NULL|导师账号|
|daoshixingming|varchar(200)|是|NULL|导师姓名|
|xingbie|varchar(200)|是|NULL|性别|
|zhicheng|varchar(200)|是|NULL|职称|
|youxiang|varchar(200)|是|NULL|邮箱|
|yanjiufangxiang|varchar(200)|是|NULL|研究方向|
|yanjiufangxiangjieshao|longtext|是|NULL|研究方向介绍|
|gerenjianjie|longtext|是|NULL|个人简介|
|xueshuchengguo|varchar(200)|是|NULL|学术成果|
|zhaopian|varchar(200)|是|NULL|照片|
|clicktime|datetime|是|NULL|最近点击时间|
|clicknum|int(11)|是|0|点击次数|
表4.4 导师组

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|daoshizu|varchar(200)|是|NULL|导师组|
表4.5 指导中心

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|title|varchar(200)|是|NULL|帖子标题|
|content|longtext|否||帖子内容|
|parentid|bigint(20)|是|NULL|父节点id|
|userid|bigint(20)|否||用户id|
|username|varchar(200)|是|NULL|用户名|
|isdone|varchar(200)|是|NULL|状态|
表4.6 老师评价

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|daoshizhanghao|varchar(200)|是|NULL|导师账号|
|daoshixingming|varchar(200)|是|NULL|导师姓名|
|xueqi|varchar(200)|是|NULL|学期|
|laoshipingjia|longtext|是|NULL|老师评价|
|pingjiashijian|datetime|是|NULL|评价时间|
|xuegonghao|varchar(200)|是|NULL|学工号|
|xueshengxingming|varchar(200)|是|NULL|学生姓名|
表4.7 年级

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|nianji|varchar(200)|是|NULL|年级|
表4.8 管理员信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|username|varchar(100)|否||用户名|
|password|varchar(100)|否||密码|
|role|varchar(100)|是|管理员|角色|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|新增时间|
表4.9 我的导师

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|daoshizhanghao|varchar(200)|是|NULL|导师账号|
|daoshixingming|varchar(200)|是|NULL|导师姓名|
|xingbie|varchar(200)|是|NULL|性别|
|zhicheng|varchar(200)|是|NULL|职称|
|youxiang|varchar(200)|是|NULL|邮箱|
|yanjiufangxiang|varchar(200)|是|NULL|研究方向|
|yanjiufangxiangjieshao|varchar(200)|是|NULL|研究方向介绍|
|gerenjianjie|varchar(200)|是|NULL|个人简介|
|xueshuchengguo|varchar(200)|是|NULL|学术成果|
|zhaopian|varchar(200)|是|NULL|照片|
|xuegonghao|varchar(200)|是|NULL|学工号|
|xueshengxingming|varchar(200)|是|NULL|学生姓名|
|zhiyuanshunxu|varchar(200)|是|NULL|志愿顺序|
表4.10 我的学生

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|daoshizhanghao|varchar(200)|是|NULL|导师账号|
|daoshixingming|varchar(200)|是|NULL|导师姓名|
|xingbie|varchar(200)|是|NULL|性别|
|zhicheng|varchar(200)|是|NULL|职称|
|youxiang|varchar(200)|是|NULL|邮箱|
|yanjiufangxiang|varchar(200)|是|NULL|研究方向|
|yanjiufangxiangjieshao|varchar(200)|是|NULL|研究方向介绍|
|gerenjianjie|varchar(200)|是|NULL|个人简介|
|xueshuchengguo|varchar(200)|是|NULL|学术成果|
|zhaopian|varchar(200)|是|NULL|照片|
|xuegonghao|varchar(200)|是|NULL|学工号|
|xueshengxingming|varchar(200)|是|NULL|学生姓名|
|zhiyuanshunxu|varchar(200)|是|NULL|志愿顺序|
表4.11 学期

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|xueqi|varchar(200)|是|NULL|学期|
表4.12 学生

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|xuegonghao|varchar(200)|否||学工号|
|mima|varchar(200)|否||密码|
|xueshengxingming|varchar(200)|否||学生姓名|
|xingbie|varchar(200)|是|NULL|性别|
|xueyuan|varchar(200)|是|NULL|学院|
|zhuanye|varchar(200)|是|NULL|专业|
|nianji|varchar(200)|是|NULL|年级|
|banji|varchar(200)|是|NULL|班级|
|youxiang|varchar(200)|是|NULL|邮箱|
|shouji|varchar(200)|是|NULL|手机|
|gerenjianjie|longtext|是|NULL|个人简介|
|zhaopian|varchar(200)|是|NULL|照片|
表4.13 学生成绩

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|xuegonghao|varchar(200)|是|NULL|学工号|
|xueshengxingming|varchar(200)|是|NULL|学生姓名|
|xueshengchengji|varchar(200)|是|NULL|学生成绩|
|daoshizhanghao|varchar(200)|是|NULL|导师账号|
|daoshixingming|varchar(200)|是|NULL|导师姓名|
|lurushijian|datetime|是|NULL|录入时间|
表4.14 学生评价

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|xuegonghao|varchar(200)|是|NULL|学工号|
|xueshengxingming|varchar(200)|是|NULL|学生姓名|
|xueqi|varchar(200)|是|NULL|学期|
|xueshengpingjia|longtext|是|NULL|学生评价|
|pingjiashijian|datetime|是|NULL|评价时间|
|daoshizhanghao|varchar(200)|是|NULL|导师账号|
|daoshixingming|varchar(200)|是|NULL|导师姓名|
表4.15 学院

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|xueyuan|varchar(200)|是|NULL|学院|
表4.16 研究方向

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yanjiufangxiang|varchar(200)|是|NULL|研究方向|
表4.17 已选导师

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|daoshizhanghao|varchar(200)|是|NULL|导师账号|
|daoshixingming|varchar(200)|是|NULL|导师姓名|
|xingbie|varchar(200)|是|NULL|性别|
|zhicheng|varchar(200)|是|NULL|职称|
|youxiang|varchar(200)|是|NULL|邮箱|
|yanjiufangxiang|varchar(200)|是|NULL|研究方向|
|yanjiufangxiangjieshao|varchar(200)|是|NULL|研究方向介绍|
|gerenjianjie|varchar(200)|是|NULL|个人简介|
|xueshuchengguo|varchar(200)|是|NULL|学术成果|
|zhaopian|varchar(200)|是|NULL|照片|
|xuegonghao|varchar(200)|是|NULL|学工号|
|xueshengxingming|varchar(200)|是|NULL|学生姓名|
|zhiyuanshunxu|varchar(200)|是|NULL|志愿顺序|
|sfsh|varchar(200)|是|否|是否审核|
|shhf|longtext|是|NULL|审核回复|
表4.18 专业

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|zhuanye|varchar(200)|是|NULL|专业|
![](/md/blog.008.png "打开新的 phpMyAdmin 窗口")



# 5系统详细实现
## 5.1 管理员模块的实现
### 5.1.1 学生管理
本科生导师指导平台的系统管理员可以管理学生信息，可以对学生信息添加修改删除操作。具体界面的展示如图5.1所示。

![](/md/blog.009.png)

图5.1 学生管理界面
### 5.1.2 年级管理
系统管理员可以对年级进行管理操作。具体界面如图5.2所示。

![](/md/blog.010.png)

图5.3 年级管理界面
### 5.1.3 我的导师
系统管理员可以对我的导师查看。界面如下图所示：

![](/md/blog.011.png)

图5.4 我的导师界面

## 5.2 学生模块的实现
### 5.2.1 导师选择列表
学生登录后，在导师选择列表选择导师。界面如下图所示：

![](/md/blog.012.png)

图5.5 导师选择列表界面
### 5.2.2 已选导师管理
学生登录后，可以查看已选导师信息。界面如下图所示：

![](/md/blog.013.png)

图5.6 已选导师界面
### 5.2.3 我的导师管理
学生登录后可以查看我的导师。界面如下图所示：

![](/md/blog.014.png)

图5.7 我的导师管理界面















